#### Test 58380500c26a9ef_thali05_motorola-Nexus 6 Logs


```
--------- beginning of main
V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/HeadsetStateMachine( 2187): Disconnected process message: 10, size: 0
,D/AndroidRuntime( 3700): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 3700): CheckJNI is OFF
D/AndroidRuntime( 3700): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  821): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/WindowManager(  821): addAppToken: AppWindowToken{25318082 token=Token{13e8afcd ActivityRecord{11cb3164 u0 com.test.thalitest/.MainActivity t28}}} to stack=1 task=28 at 0
D/AndroidRuntime( 3700): Shutting down VM
V/WindowManager(  821): Adding window Window{3e5cc5ef u0 Starting com.test.thalitest} at 2 of 7 (after Window{7a37ba6 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
I/MicrophoneInputStream( 1525): mic_close com.google.android.apps.gsa.speech.audio.u@37126a6b
I/HotwordDetector( 1525): Closing mic
I/ActivityManager(  821): Start proc 3714:com.test.thalitest/u0a265 for activity com.test.thalitest/.MainActivity
D/audio_hw_primary(  356): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  356): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  356): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1525): Hotword detection finished
I/HotwordRecognitionRnr( 1525): Stopping hotword detection.
I/art     (  368): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 431us total 43.214ms
I/art     (  368): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 315us total 13.382ms
I/art     (  368): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 217us total 10.195ms
I/art     (  821): Explicit concurrent mark sweep GC freed 19467(951KB) AllocSpace objects, 4(64KB) LOS objects, 32% free, 33MB/49MB, paused 1.361ms total 47.942ms
E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1660654867
E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
I/ActivityManager(  821): Killing 3291:com.android.settings/1000 (adj 15): empty #17
,I/WebViewFactory( 3714): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3714): Time to load native libraries: 2 ms (timestamps 8850-8852)
I/LibraryLoader( 3714): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3714): Binding Chromium to main looper Looper (main, tid 1) {29604b32}
,I/LibraryLoader( 3714): Expected native library version number "",actual native library version number ""
I/chromium( 3714): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3714): Initializing chromium process, singleProcess=true
,W/art     ( 3714): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3714): ApplicationContext is null in ApplicationStatus
,W/chromium( 3714): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3714): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3714): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3714): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/BluetoothManagerService(  821): Message: 20
D/BluetoothManagerService(  821): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@103fe939:true
,W/art     ( 3714): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3714): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3714): CordovaWebView is running on device made by: motorola
,W/art     ( 3714): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 3714): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3714): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,D/Atlas   ( 3714): Validating map...
,V/WindowManager(  821): Adding window Window{e9092a9 u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{3e5cc5ef u0 Starting com.test.thalitest})
,W/chromium( 3714): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3714): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3714): Enabling debug mode 0
,I/Keyboard.Facilitator( 1242): onFinishInput()
,I/ActivityManager(  821): Displayed com.test.thalitest/.MainActivity: +899ms
,W/BindingManager( 3714): Cannot call determinedVisibility() - never saw a connection for the pid: 3714
,D/JsMessageQueue( 3714): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3714): JniHelper::setJavaVM(0xb489d200), pthread_self() = -1576322944
,I/chromium( 3714): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 3714): Initializing JXcore engine
W/jxcore-log( 3714): JXcore engine is ready
,W/Thread-407( 3770): type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[11449]" dev="sockfs" ino=11449 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/Thread-407( 3770): type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-407( 3770): type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[11636]" dev="sockfs" ino=11636 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-407( 3770): type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[21901]" dev="sockfs" ino=21901 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 3714): Starting JXcore engine
,W/jxcore-log( 3714): Platform android
W/jxcore-log( 3714): 
W/jxcore-log( 3714): Process ARCH arm
W/jxcore-log( 3714): 
,I/jxcore-log( 3714): JXcore Cordova bridge is ready!
I/jxcore-log( 3714): 
W/jxcore-log( 3714): JXcore engine is started
,I/jxcore-log( 3714): Toggling radios to true
I/jxcore-log( 3714): 
,D/BluetoothAdapter( 3714): enable(): BT is already enabled..!,
,D/WifiService(  821): setWifiEnabled: true pid=3714, uid=10265,
E/WifiService(  821): Invoking mWifiStateMachine.setWifiEnabled,
D/WifiService(  821): New client listening to asynchronous messages,
,I/jxcore-log( 3714): Radios toggled
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): My device name is: motorola-Nexus 6
I/jxcore-log( 3714): 
I/wpa_supplicant( 1149): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  821): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  821): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  352): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1259): Read error: ssl=0xb4888600: I/O error during system call, Connection timed out
V/NativeCrypto( 1259): SSL shutdown failed: ssl=0xb4888600: I/O error during system call, Broken pipe
,D/ConnectivityService(  821): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10011
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): ValidatedState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): DefaultState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): Forcing reevaluation
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
D/ConnectivityService(  821): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
D/ConnectivityService(  821): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
E/WifiStateMachine(  821): Start Disconnecting Watchdog 1
E/WifiStateMachine(  821): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,D/CommandListener(  352): Clearing all IP addresses on wlan0
D/WifiNetworkAgent(  821): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine(  821): CMD_AUTO_CONNECT sup state CompletedState my state DisconnectedState nid=0 roam=3
E/WifiStateMachine(  821): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=0
,D/ConnectivityService(  821): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/CSLegacyTypeTracker(  821): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): OfflineState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): Disconnected - quitting
D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityManager.CallbackHandler( 1071): CM callback handler got msg 524292
D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering(  821): MasterInitialState.processMessage what=3
,D/ConnectivityService(  821): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/Tethering(  821): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 3055): type=WIFI subType= reason=null isConnected=false
,D/ConnectivityService(  821): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
E/ConnectivityService(  821): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,D/NetworkChangeNotifierAutoDetect( 1525): Network connectivity changed, type is: 6
,V/MusicLeanback( 3055): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/PhoneInterfaceManager( 1327): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1327): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  821): getDataEnabled: retVal=false
,E/WifiConfigStore(  821): Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiConfigStore(  821): will read network variables netId=0
,I/ActivityManager(  821): Start proc 3778:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.steen.receiver.ConnectivityChangeReceiver
,E/WifiStateMachine(  821): CMD_AUTO_CONNECT did save config ->  nid=0
,E/WifiConfigStore(  821): will read network variables netId=0
,E/GpsLocationProvider(  821): No APN found to select.
,D/PhoneInterfaceManager( 1327): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1327): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  821): getDataEnabled: retVal=false
,E/GpsLocationProvider(  821): No APN found to select.
,I/ActivityManager(  821): Start proc 3805:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
I/ActivityManager(  821): Killing 3308:com.google.android.apps.maps/u0a65 (adj 15): empty #17
,D/SprintDMReceiver( 3805): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3805): simOperator:  IMSI: null
D/SprintDMReceiver( 3805): Not Sprint UICC, don't do anything.
,I/ActivityManager(  821): Killing 3416:com.google.android.partnersetup/u0a16 (adj 15): empty #17,
,I/SystemUpdateService( 1774): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1774): onCreate
,D/SystemUpdateService( 1774): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1774): active receiver: enabled
,I/SystemUpdateService( 1774): showing system update notification
,I/ValidateNoPeople(  821): skipping global notification
,I/ActivityManager(  821): Waited long enough for: ServiceRecord{1b42aebc u0 com.motorola.android.buacontactadapter/.AuthenticationService}
,V/SystemUpdateService( 1774): retry (wakeup: false) in 3599968 ms
,I/iu.Environment( 1774): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1774): num queued entries: 0
,I/iu.UploadsManager( 1774): num updated entries: 0
,D/SystemUpdateService( 1774): onDestroy
,I/iu.SyncManager( 1774): NEXT; no task
,D/ChimeraCfgMgr( 1774): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 1774): [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
,I/Babel   ( 2792): connection state changed from CONNECTED to DISCONNECTED
,I/ActivityManager(  821): Start proc 3825:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,I/GAv4    ( 3825): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3825):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3825):   adb logcat -s GAv4
,W/GAv4    ( 3825): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3825): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3825): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 3825): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3825): Time to load native libraries: 1 ms (timestamps 3047-3048)
I/LibraryLoader( 3825): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3825): Binding Chromium to main looper Looper (main, tid 1) {3772f1c1}
,I/LibraryLoader( 3825): Expected native library version number "",actual native library version number ""
,I/chromium( 3825): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3825): Initializing chromium process, singleProcess=true
,W/art     ( 3825): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3825): ApplicationContext is null in ApplicationStatus
,W/chromium( 3825): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3825): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3825): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3825): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,W/AudioManagerAndroid( 3825): Requires BLUETOOTH permission
,I/NSApplication( 3825): Starting up...
,I/ActivityManager(  821): Start proc 3881:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
I/ActivityManager(  821): Killing 3437:com.android.musicfx/u0a18 (adj 15): empty #17
,I/ActivityManager(  821): Killing 3466:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,V/MusicLeanback( 3055): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/SprintDMReceiver( 3805): Received intent: android.net.conn.CONNECTIVITY_CHANGE
D/SprintDMHelper( 3805): simOperator:  IMSI: null
D/SprintDMReceiver( 3805): Not Sprint UICC, don't do anything.
I/SystemUpdateService( 1774): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
D/SystemUpdateService( 1774): onCreate
D/SystemUpdateService( 1774): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
I/SystemUpdateService( 1774): active receiver: enabled
I/SystemUpdateService( 1774): showing system update notification
D/ChimeraCfgMgr( 1774): Loading module com.google.android.gms.kids from APK com.google.android.gms
I/Kids    ( 1774): [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
I/ValidateNoPeople(  821): skipping global notification
,V/SystemUpdateService( 1774): retry (wakeup: false) in 3599974 ms
,D/SystemUpdateService( 1774): onDestroy
,I/wpa_supplicant( 1149): wlan0: Trying to associate with SSID 'NG7005g'
,I/wpa_supplicant( 1149): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 1149): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP],
,I/wpa_supplicant( 1149): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=0 id_str=]
,D/ConnectivityService(  821): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} }
,E/WifiConfigStore(  821): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  821): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  821): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  352): Setting iface cfg
,E/WifiStateMachine(  821): Start Dhcp Watchdog 2
,E/WifiStateMachine(  821):  WifiLinkLayerStats: 
E/WifiStateMachine(  821):  my bss beacon rx: 175
E/WifiStateMachine(  821):  RSSI mgmt: -54
E/WifiStateMachine(  821):  BE :  rx=156 tx=142 lost=0 retries=0
E/WifiStateMachine(  821):  BK :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  821):  VI :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  821):  VO :  rx=4 tx=0 lost=0 retries=0
E/WifiStateMachine(  821):  on_time : 7866 tx_time=154 rx_time=364 scan_time=0
,D/ConnectivityService(  821): updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,E/native  (  821): do suspend false
,E/WifiStateMachine(  821): scanCount==0 - aborting
,I/dhcpcd  ( 3911): version 5.5.6 starting
,I/dhcpcd  ( 3911): wlan0: rebinding lease of 192.168.1.122
,I/ActivityManager(  821): Killing 3248:android.process.acore/u0a5 (adj 15): empty #17
,I/dhcpcd  ( 3911): wlan0: acknowledged 192.168.1.122 from 192.168.1.1
,I/dhcpcd  ( 3911): wlan0: leased 192.168.1.122 for 86400 seconds
,I/ActivityManager(  821): Killing 3596:com.google.android.gm.exchange/u0a77 (adj 15): empty #18
,D/ConnectivityService(  821): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  821): Adding iface wlan0 to network 101,
,E/WifiStateMachine(  821): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  821): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  821): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  821): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  821): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  821): Setting Dns servers for network 101 to [/192.168.1.1]
,D/ConnectivityService(  821): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  821): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  821): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  821):    accepting network in place of null
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  821): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  821): Connected
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  821): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  821): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
D/ConnectivityService(  821): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} }
,D/ConnectivityService(  821): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/CSLegacyTypeTracker(  821): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 1071): CM callback handler got msg 524290
,D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  821): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 3055): type=WIFI subType= reason=null isConnected=true
,D/NetworkChangeNotifierAutoDetect( 1525): Network connectivity changed, type is: 2
,D/PhoneInterfaceManager( 1327): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1327): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  821): getDataEnabled: retVal=false
,V/MusicLeanback( 3055): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,E/GpsLocationProvider(  821): No APN found to select.
,D/SprintDMReceiver( 3805): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3805): simOperator:  IMSI: null
D/SprintDMReceiver( 3805): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1774): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1774): onCreate
,D/SystemUpdateService( 1774): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1774): active receiver: enabled
,D/AlarmManagerService(  821): Setting time of day to sec=1454983569
W/AlarmManagerService(  821): Unable to set rtc to 1454983569: Invalid argument
,I/SystemUpdateService( 1774): showing system update notification
,I/iu.Environment( 1774): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1774): num queued entries: 0
,I/iu.UploadsManager( 1774): num updated entries: 0
,I/iu.SyncManager( 1774): NEXT; no task
,D/ChimeraCfgMgr( 1774): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 1774): [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  821): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 09 Feb 2016 02:06:09 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454983569352], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454983569331]}
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  821): Validated
D/ConnectivityService(  821): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/ConnectivityService(  821): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  821): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  821): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  821): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1071): CM callback handler got msg 524290
,D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
I/ValidateNoPeople(  821): skipping global notification
,V/SystemUpdateService( 1774): retry (wakeup: false) in 3599709 ms
,D/SystemUpdateService( 1774): onDestroy
,I/ActivityManager(  821): Start proc 3957:com.google.android.keep/u0a79 for broadcast com.google.android.keep/.notification.AlertReceiver
,I/Babel   ( 2792): connection state changed from DISCONNECTED to CONNECTED
,I/GLSUser ( 1259): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1259): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1259): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1259): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3228): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3228): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3228): 	at jdm.a(PG:82)
E/HttpOperation( 3228): 	at jcs.o(PG:406)
E/HttpOperation( 3228): 	at jcn.a(PG:1379)
E/HttpOperation( 3228): 	at jcs.i(PG:143)
E/HttpOperation( 3228): 	at blb.a(PG:3937)
E/HttpOperation( 3228): 	at czp.a(PG:18188)
E/HttpOperation( 3228): 	at czp.a(PG:9081)
E/HttpOperation( 3228): 	at czq.run(PG:1686)
E/HttpOperation( 3228): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3228): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3228): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3228): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3228): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3228): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3228): 	at jdj.a(PG:4091)
E/HttpOperation( 3228): 	at jdj.a(PG:1125)
E/HttpOperation( 3228): 	at jdm.a(PG:77)
E/HttpOperation( 3228): 	... 12 more
E/HttpOperation( 3228): Caused by: faj: BadAuthentication
E/HttpOperation( 3228): 	at fal.a(PG:38)
E/HttpOperation( 3228): 	at jdj.a(PG:4089)
E/HttpOperation( 3228): 	... 14 more
,I/GLSUser ( 1259): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1259): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1259): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1259): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3228): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3228): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3228): 	at jdm.a(PG:82)
E/HttpOperation( 3228): 	at jcs.o(PG:406)
E/HttpOperation( 3228): 	at jcn.a(PG:1379)
E/HttpOperation( 3228): 	at jcs.i(PG:143)
E/HttpOperation( 3228): 	at hec.a(PG:42)
E/HttpOperation( 3228): 	at hee.a(PG:102)
E/HttpOperation( 3228): 	at czr.a(PG:65)
E/HttpOperation( 3228): 	at kka.a(PG:108)
E/HttpOperation( 3228): 	at czp.a(PG:19176)
E/HttpOperation( 3228): 	at czp.a(PG:9081)
E/HttpOperation( 3228): 	at czq.run(PG:1686)
E/HttpOperation( 3228): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3228): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3228): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3228): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3228): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3228): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3228): 	at jdj.a(PG:4091)
E/HttpOperation( 3228): 	at jdj.a(PG:1125)
E/HttpOperation( 3228): 	at jdm.a(PG:77)
E/HttpOperation( 3228): 	... 15 more
E/HttpOperation( 3228): Caused by: faj: BadAuthentication
E/HttpOperation( 3228): 	at fal.a(PG:38)
E/HttpOperation( 3228): 	at jdj.a(PG:4089)
E/HttpOperation( 3228): 	... 17 more
E/ExperimentLoader( 3228): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3228): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3228): 	at jdm.a(PG:82)
E/ExperimentLoader( 3228): 	at jcs.o(PG:406)
E/ExperimentLoader( 3228): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3228): 	at jcs.i(PG:143)
E/ExperimentLoader( 3228): 	at hec.a(PG:42)
E/ExperimentLoader( 3228): 	at hee.a(PG:102)
E/ExperimentLoader( 3228): 	at czr.a(PG:65)
E/ExperimentLoader( 3228): 	at kka.a(PG:108)
E/ExperimentLoader( 3228): 	at czp.a(PG:19176)
E/ExperimentLoader( 3228): 	at czp.a(PG:9081)
E/ExperimentLoader( 3228): 	at czq.run(PG:1686)
E/ExperimentLoader( 3228): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3228): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3228): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3228): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3228): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3228): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3228): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3228): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3228): 	at jdm.a(PG:77)
E/ExperimentLoader( 3228): 	... 15 more
E/ExperimentLoader( 3228): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3228): 	at fal.a(PG:38)
E/ExperimentLoader( 3228): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3228): 	... 17 more
,D/GCM     ( 1259): Connected
,D/GCM     ( 1259): Message class com.google.f.a.a.p
,I/art     (  821): Explicit concurrent mark sweep GC freed 48924(2MB) AllocSpace objects, 6(96KB) LOS objects, 32% free, 33MB/49MB, paused 1.564ms total 75.116ms
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 74112, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/art     ( 1259): Explicit concurrent mark sweep GC freed 16415(905KB) AllocSpace objects, 0(0B) LOS objects, 38% free, 25MB/41MB, paused 792us total 19.569ms
,I/ActivityManager(  821): Start proc 3982:com.qualcomm.timeservice/1000 for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver
,D/TimeService( 3982): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1454983569746
D/        ( 3982): TimeServiceNative: User Time to be set is 1454983569746
D/QC-time-services( 3982): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 3982): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 3982): Lib:time_genoff_operation: pargs->ts_val = 1454983569746
D/QC-time-services(  372): Daemon: Connection accepted:time_genoff
D/QC-time-services( 3982): Lib:time_genoff_operation: Send to server  passed!!
,D/QC-time-services(  372): Daemon:Received base = 2, unit = 1, operation = 0,value = 1454983569746
D/QC-time-services(  372): Daemon:genoff_opr: Base = 2, val = 1454983569746, operation = 0
D/QC-time-services(  372): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS5/26/70 22:18:29
D/QC-time-services(  372): Daemon:Value read from RTC seconds = 15286709000
D/QC-time-services(  372): Daemon:new time 1454983569746 
D/QC-time-services(  372): Daemon: delta 1439696860746 genoff 1439696860746 
D/QC-time-services(  372): Daemon:genoff_persistent_update: Writing genoff = 1439696860746 to memory
D/QC-time-services(  372): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  372): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  372): Updating the TOD offset
D/QC-time-services(  372): Daemon:genoff_persistent_update: Writing genoff = 1439696860746 to memory
D/QC-time-services(  372): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  372): Daemon:time_persistent_memory_opr:Genoff write operation 
,E/QC-time-services(  372): Daemon:Update to modem bit set
,D/QC-time-services(  372): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  372): Daemon: Base = 2, Value being sent to MODEM = 1139018769746
E/QC-time-services( 3982): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,I/ActivityManager(  821): Killing 3545:com.google.android.gms:car/u0a11 (adj 15): empty #17
,E/QC-time-services(  372): Daemon: Time-services: Waiting to acceptconnection
,E/QC-time-services(  372): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,I/ActivityManager(  821): Start proc 4002:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver
,I/GAv4    ( 4002): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4002):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4002):   adb logcat -s GAv4
,W/GAv4    ( 4002): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4002): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4002): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,V/Herrevad( 1774): NQAS connected
,I/GCM     ( 1774): Message from null null
E/GCM     ( 1774): Dropping message from null
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1259): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1259): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1259): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1259): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/ConnectivityService(  821): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3505): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3505): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3505): [1] 5.onFinished: Scheduling replication attempt 1.
,I/ActivityManager(  821): Killing 3570:com.google.android.gm/u0a78 (adj 15): empty #17
,I/jxcore-log( 3714): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 3714): 
,I/ActivityManager(  821): Killing 3379:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=9.19 rxSuccessRate=10.78 targetRoamBSSID=any RSSI=-55
E/WifiStateMachine(  821): WifiStateMachine L2Connected CMD_START_SCAN source -2 6, 7 -> obsolete
,I/jxcore-log( 3714): Test app app.js loaded
I/jxcore-log( 3714): 
,I/chromium( 3714): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): 	Bluetooth MAC address: F8:CF:C5:D9:E5:61, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): 	Discovery mode: BLE_AND_WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): 	Scan mode: 1
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@387893aa added. We now have 1 listener(s)
,I/jxcore-log( 3714): BLE advertisement is supported
I/jxcore-log( 3714): 
,E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=9.19 rxSuccessRate=10.78 targetRoamBSSID=any RSSI=-55
E/WifiStateMachine(  821): WifiStateMachine L2Connected CMD_START_SCAN source -2 5, 7 -> obsolete
,E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.85 rxSuccessRate=2.77 targetRoamBSSID=any RSSI=-54
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1259): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1259): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1259): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1259): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3505): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3505): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3505): [1] 5.onFinished: Scheduling replication attempt 2.
,I/ActivityManager(  821): Start proc 4040:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,W/GAV2    ( 4040): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/BooksApp( 4040): Created application version: 3.6.8 (30608)
,I/BooksSync( 4040): Starting books sync for 61035162, extras: ade
,V/KeepSync( 3957): Connecting to GoogleApiClient
,I/BooksConfig( 4040): GmsCore Version = 7.8.99 (2134222-430)
,I/art     (  821): Explicit concurrent mark sweep GC freed 31112(1448KB) AllocSpace objects, 6(96KB) LOS objects, 32% free, 33MB/49MB, paused 1.354ms total 52.131ms
,I/GLSUser ( 1259): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1259): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1259): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1259): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1259): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1259): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1259): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1259): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1774): Handling authorization failure
E/ClientConnectionOperation( 1774): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1774): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1774): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1774): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1774): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1774): 	... 7 more
,V/KeepSync( 3957): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3957): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3957): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3957): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1259): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1259): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1259): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1259): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 4040): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 4040): Soft error
E/BooksSync( 4040): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4040): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 4040): Sync error
E/BooksSync( 4040): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4040): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 4040): Finished books sync
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 75950, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1259): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1259): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1259): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1259): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3957): IOException
E/KeepSync( 3957): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3957): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3957): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3957): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3957): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3957): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3957): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3957): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3957): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3957): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3957): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3957): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3957): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3957): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3957): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3957): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3957): 	... 10 more
,W/KeepSync( 3957): Sync result 2
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 75896, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager(  821): Killing 3055:com.google.android.music:main/u0a66 (adj 15): empty #17
,I/GAV2    ( 4040): Thread[GAThread,5,main]: No campaign data found.
,E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.95 rxSuccessRate=2.75 targetRoamBSSID=any RSSI=-54
E/WifiStateMachine(  821): WifiStateMachine starting scan for "NG7005g"WPA_PSK with 2412,5220
,D/Finsky  ( 3505): [365] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1259): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1259): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1259): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1259): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3505): [365] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1259): Explicit concurrent mark sweep GC freed 26179(1505KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 1.552ms total 56.755ms
,I/GLSUser ( 1259): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1259): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1259): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1259): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3505): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3505): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3505): [1] 5.onFinished: Scheduling replication attempt 3.
,D/HeadsetStateMachine( 2187): Disconnected process message: 10, size: 0
,I/Keyboard.Facilitator.LanguageModelFlusher( 1242): run()
I/Keyboard.Facilitator( 1242): flushDynamicLanguageModels()
,I/ConfigService( 1259): onCreate
,I/ConfigService( 1259): onDestroy
,E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=1.17 rxSuccessRate=2.79 targetRoamBSSID=any RSSI=-54
,I/GLSUser ( 1259): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1259): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1259): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1259): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3228): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3228): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3228): 	at jdm.a(PG:82)
E/HttpOperation( 3228): 	at jcs.o(PG:406)
E/HttpOperation( 3228): 	at jcn.a(PG:1379)
E/HttpOperation( 3228): 	at jcs.i(PG:143)
E/HttpOperation( 3228): 	at blb.a(PG:3937)
E/HttpOperation( 3228): 	at czp.a(PG:18188)
E/HttpOperation( 3228): 	at czp.a(PG:9081)
E/HttpOperation( 3228): 	at czq.run(PG:1686)
E/HttpOperation( 3228): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3228): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3228): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3228): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3228): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3228): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3228): 	at jdj.a(PG:4091)
E/HttpOperation( 3228): 	at jdj.a(PG:1125)
E/HttpOperation( 3228): 	at jdm.a(PG:77)
E/HttpOperation( 3228): 	... 12 more
E/HttpOperation( 3228): Caused by: faj: BadAuthentication
E/HttpOperation( 3228): 	at fal.a(PG:38)
E/HttpOperation( 3228): 	at jdj.a(PG:4089)
E/HttpOperation( 3228): 	... 14 more
,I/GLSUser ( 1259): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1259): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1259): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1259): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3228): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3228): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3228): 	at jdm.a(PG:82)
E/HttpOperation( 3228): 	at jcs.o(PG:406)
E/HttpOperation( 3228): 	at jcn.a(PG:1379)
E/HttpOperation( 3228): 	at jcs.i(PG:143)
E/HttpOperation( 3228): 	at hec.a(PG:42)
E/HttpOperation( 3228): 	at hee.a(PG:102)
E/HttpOperation( 3228): 	at czr.a(PG:65)
E/HttpOperation( 3228): 	at kka.a(PG:108)
E/HttpOperation( 3228): 	at czp.a(PG:19176)
E/HttpOperation( 3228): 	at czp.a(PG:9081)
E/HttpOperation( 3228): 	at czq.run(PG:1686)
E/HttpOperation( 3228): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3228): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3228): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3228): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3228): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3228): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3228): 	at jdj.a(PG:4091)
E/HttpOperation( 3228): 	at jdj.a(PG:1125)
E/HttpOperation( 3228): 	at jdm.a(PG:77)
E/HttpOperation( 3228): 	... 15 more
E/HttpOperation( 3228): Caused by: faj: BadAuthentication
E/HttpOperation( 3228): 	at fal.a(PG:38)
E/HttpOperation( 3228): 	at jdj.a(PG:4089)
E/HttpOperation( 3228): 	... 17 more
E/ExperimentLoader( 3228): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3228): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3228): 	at jdm.a(PG:82)
E/ExperimentLoader( 3228): 	at jcs.o(PG:406)
E/ExperimentLoader( 3228): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3228): 	at jcs.i(PG:143)
E/ExperimentLoader( 3228): 	at hec.a(PG:42)
E/ExperimentLoader( 3228): 	at hee.a(PG:102)
E/ExperimentLoader( 3228): 	at czr.a(PG:65)
E/ExperimentLoader( 3228): 	at kka.a(PG:108)
E/ExperimentLoader( 3228): 	at czp.a(PG:19176)
E/ExperimentLoader( 3228): 	at czp.a(PG:9081)
E/ExperimentLoader( 3228): 	at czq.run(PG:1686)
E/ExperimentLoader( 3228): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3228): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3228): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3228): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3228): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3228): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3228): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3228): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3228): 	at jdm.a(PG:77)
E/ExperimentLoader( 3228): 	... 15 more
E/ExperimentLoader( 3228): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3228): 	at fal.a(PG:38)
E/ExperimentLoader( 3228): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3228): 	... 17 more
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 108592, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1259): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1259): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1259): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1259): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3505): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3505): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3505): [1] 5.onFinished: Scheduling replication attempt 4.
,E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.85 rxSuccessRate=3.17 targetRoamBSSID=any RSSI=-54
E/WifiStateMachine(  821): WifiStateMachine starting scan for "NG7005g"WPA_PSK with 2412,5220
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1259): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1259): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1259): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1259): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3505): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3505): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3505): [1] 5.onFinished: Scheduling replication attempt 5.
,I/PowerManagerService(  821): Going to sleep due to screen timeout (uid 1000)...
,I/Adreno  (  821): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/PermissionCache(  260): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (251 us)
,I/DisplayManagerService(  821): Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,D/SurfaceFlinger(  260): Set power mode=0, type=0 flinger=0xb6482000,
D/qdhwcomposer(  260): hwc_setPowerMode: Setting mode 0 on display: 0
V/ActivityManager(  821): Display changed displayId=0,
,I/kickstart(  871): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
I/kickstart(  871): STATUS: Wrote to /sys/power/wake_lock
,E/kickstart(  871): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2,
I/kickstart(  871): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2' for writing
,I/qdhwcomposer(  260): handle_blank_event: dpy:0 panel power state: 0
,D/qdhwcomposer(  260): hwc_setPowerMode: Done setting mode 0 on display 0
,D/SurfaceControl(  821): Excessive delay in setPowerMode(): 280ms
,I/DreamManagerService(  821): Entering dreamland.
,I/DreamController(  821): Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,I/PowerManagerService(  821): Dozing...
,D/audio_hw_primary(  356): adev_set_parameters: enter: screen_state=on
,D/mot_vr_audio_hw(  356): adev_set_parameters: screen_state=on
,E/WifiStateMachine(  821): cancelDelayedScan -> 12
,E/native  (  821): do suspend false
,I/Keyboard.Facilitator( 1242): onFinishInput()
,E/WifiStateMachine(  821): cancelDelayedScan -> 14
,E/native  (  821): do suspend true
,D/audio_hw_primary(  356): adev_set_parameters: enter: screen_state=off
D/mot_vr_audio_hw(  356): adev_set_parameters: screen_state=off,
,E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-54,
E/WifiStateMachine(  821): WifiStateMachine L2Connected CMD_START_SCAN source -2 13, 14 -> obsolete
,I/kickstart(  871): STATUS: Received file 'm9kefs2',
I/kickstart(  871): STATUS: 950272 bytes transferred in 0.999882 seconds
I/kickstart(  871): STATUS: Successfully downloaded files from target 
,I/kickstart(  871): STATUS: Wrote to /sys/power/wake_unlock
,I/kickstart(  871): STATUS: Sahara protocol completed
,I/BooksSync( 4040): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 4040): GmsCore Version = 7.8.99 (2134222-430)
,V/KeepSync( 3957): Connecting to GoogleApiClient
,I/GLSUser ( 1259): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1259): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1259): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1259): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  821): Explicit concurrent mark sweep GC freed 50662(2MB) AllocSpace objects, 14(224KB) LOS objects, 31% free, 34MB/50MB, paused 1.412ms total 75.484ms
,I/GLSUser ( 1259): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1259): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1259): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1259): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1774): Handling authorization failure
E/ClientConnectionOperation( 1774): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1774): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1774): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1774): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1774): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1774): 	... 7 more
,V/KeepSync( 3957): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3957): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3957): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3957): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1259): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1259): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1259): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1259): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 4040): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 4040): Soft error
E/BooksSync( 4040): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4040): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 4040): Sync error
E/BooksSync( 4040): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4040): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 4040): Finished books sync
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 137179, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1259): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive,
I/GLSUser ( 1259): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1259): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1259): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3957): IOException
E/KeepSync( 3957): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3957): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3957): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3957): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3957): 	,at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3957): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3957): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3957): 	,at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3957): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3957): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
,E/KeepSync( 3957): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3957): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3957): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.,
E/KeepSync( 3957): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3957): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
,E/KeepSync( 3957): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3957): 	... 10 more
,W/KeepSync( 3957): Sync result 2
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 138800, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-54
E/WifiStateMachine(  821): WifiStateMachine L2Connected CMD_START_SCAN source -2 11, 14 -> obsolete
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GoogleAuthProtoRequest( 3778): [400] a.<init>: mAccountName set to: thalitester@gmail.com
,I/VacuumService( 1259): Vacuum at: now=1454983676562 tag=VacuumService
,I/GLSUser ( 1259): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1259): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1259): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1259): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3778): [400] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3778): [400] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3778): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3778): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3778): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3778): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3778): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3778): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3778): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3778): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3778): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3778): 	at com.a.a.k.run(SourceFile:110)
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GoogleURLConnFactory( 1259): Using platform SSLCertificateSocketFactory
,W/Uploader( 1259): No account for auth token provided
,I/GLSUser ( 1259): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1259): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1259): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1259): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3505): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3505): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3505): [1] 5.onFinished: Giving up after 6 failures.
,W/Uploader( 1259): No account for auth token provided
,W/Uploader( 1259): No account for auth token provided
,W/Uploader( 1259): No account for auth token provided
,I/GLSUser ( 1259): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1259): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1259): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1259): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/Uploader( 1259): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1259): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
,E/Uploader( 1259): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1259): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1259): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1259): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1259): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1259): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1259): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1259): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1259): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1259): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1259): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/GLSUser ( 1259): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1259): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1259): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1259): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1259): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1259): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1259): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1259): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1259): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1259): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1259): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1259): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1259): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1259): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1259): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1259): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1259): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1259): No account for auth token provided
,I/GLSUser ( 1259): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1259): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1259): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1259): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1259): Explicit concurrent mark sweep GC freed 58422(3MB) AllocSpace objects, 7(700KB) LOS objects, 36% free, 27MB/43MB, paused 2.265ms total 67.875ms
,E/Uploader( 1259): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1259): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1259): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1259): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1259): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1259): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1259): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1259): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1259): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1259): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1259): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1259): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1259): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1259): No account for auth token provided
,W/Uploader( 1259): No account for auth token provided
,W/Uploader( 1259): No account for auth token provided,
,W/Uploader( 1259): No account for auth token provided
,W/Uploader( 1259): No account for auth token provided
,W/Uploader( 1259):  no longer exists, so no auth token.
,D/HeadsetStateMachine( 2187): Disconnected process message: 10, size: 0
,I/GLSUser ( 1259): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1259): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1259): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1259): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1259): Failed to get auth token: User intervention required. Notification has been pushed.,
E/Uploader( 1259): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1259): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1259): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1259): 	at com.google.android.gms.auth.p.c(SourceFile:550),
E/Uploader( 1259): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1259): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1259): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1259): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1259): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1259): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1259): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1259): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,D/HeadsetStateMachine( 2187): Disconnected process message: 10, size: 0
,V/GoogleAuthProtoRequest( 3778): [402] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1259): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1259): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1259): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1259): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3778): [402] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3778): [402] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3778): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3778): 	at com.a.a.a.k.a(SourceFile:117)
,W/ExperimentUpdateService( 3778): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3778): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3778): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3778): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3778): 	at com.google.android.flib.a.a.a(SourceFile:167),
W/ExperimentUpdateService( 3778): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3778): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3778): 	at com.a.a.k.run(SourceFile:110)
,I/Keyboard.Facilitator.LanguageModelFlusher( 1242): run()
I/Keyboard.Facilitator( 1242): flushDynamicLanguageModels()
,I/ConfigService( 1259): onCreate
,I/GLSUser ( 1259): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1259): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1259): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1259): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3228): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3228): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3228): 	at jdm.a(PG:82)
E/HttpOperation( 3228): 	at jcs.o(PG:406)
E/HttpOperation( 3228): 	at jcn.a(PG:1379)
E/HttpOperation( 3228): 	at jcs.i(PG:143)
E/HttpOperation( 3228): 	at blb.a(PG:3937)
E/HttpOperation( 3228): 	at czp.a(PG:18188)
E/HttpOperation( 3228): 	at czp.a(PG:9081)
E/HttpOperation( 3228): 	at czq.run(PG:1686)
E/HttpOperation( 3228): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3228): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3228): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3228): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3228): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3228): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3228): 	at jdj.a(PG:4091)
E/HttpOperation( 3228): 	at jdj.a(PG:1125)
E/HttpOperation( 3228): 	at jdm.a(PG:77)
E/HttpOperation( 3228): 	... 12 more
E/HttpOperation( 3228): Caused by: faj: BadAuthentication
E/HttpOperation( 3228): 	at fal.a(PG:38)
E/HttpOperation( 3228): 	at jdj.a(PG:4089)
E/HttpOperation( 3228): 	... 14 more
,I/GLSUser ( 1259): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1259): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1259): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1259): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/HttpOperation( 3228): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3228): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3228): 	at jdm.a(PG:82)
E/HttpOperation( 3228): 	at jcs.o(PG:406)
E/HttpOperation( 3228): 	at jcn.a(PG:1379)
E/HttpOperation( 3228): 	at jcs.i(PG:143)
E/HttpOperation( 3228): 	at hec.a(PG:42)
E/HttpOperation( 3228): 	at hee.a(PG:102)
E/HttpOperation( 3228): 	at czr.a(PG:65)
E/HttpOperation( 3228): 	at kka.a(PG:108)
E/HttpOperation( 3228): 	at czp.a(PG:19176)
E/HttpOperation( 3228): 	at czp.a(PG:9081)
E/HttpOperation( 3228): 	at czq.run(PG:1686)
E/HttpOperation( 3228): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3228): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3228): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3228): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3228): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3228): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3228): 	at jdj.a(PG:4091)
E/HttpOperation( 3228): 	at jdj.a(PG:1125)
E/HttpOperation( 3228): 	at jdm.a(PG:77)
E/HttpOperation( 3228): 	... 15 more
E/HttpOperation( 3228): Caused by: faj: BadAuthentication
E/HttpOperation( 3228): 	at fal.a(PG:38)
E/HttpOperation( 3228): 	at jdj.a(PG:4089)
E/HttpOperation( 3228): 	... 17 more
,E/ExperimentLoader( 3228): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3228): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3228): 	at jdm.a(PG:82)
E/ExperimentLoader( 3228): 	at jcs.o(PG:406)
E/ExperimentLoader( 3228): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3228): 	at jcs.i(PG:143)
E/ExperimentLoader( 3228): 	at hec.a(PG:42)
E/ExperimentLoader( 3228): 	at hee.a(PG:102)
E/ExperimentLoader( 3228): 	at czr.a(PG:65)
E/ExperimentLoader( 3228): 	at kka.a(PG:108)
E/ExperimentLoader( 3228): 	at czp.a(PG:19176)
E/ExperimentLoader( 3228): 	at czp.a(PG:9081)
E/ExperimentLoader( 3228): 	at czq.run(PG:1686)
E/ExperimentLoader( 3228): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3228): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3228): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3228): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3228): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3228): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3228): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3228): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3228): 	at jdm.a(PG:77)
E/ExperimentLoader( 3228): 	... 15 more
E/ExperimentLoader( 3228): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3228): 	at fal.a(PG:38)
E/ExperimentLoader( 3228): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3228): 	... 17 more
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 201607, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/ConfigService( 1259): onDestroy
,D/HeadsetStateMachine( 2187): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2187): Disconnected process message: 10, size: 0
,I/art     (  821): Explicit concurrent mark sweep GC freed 38372(1707KB) AllocSpace objects, 5(268KB) LOS objects, 31% free, 34MB/50MB, paused 1.367ms total 66.848ms
,I/BooksSync( 4040): Starting books sync for 61035162, extras: ade
,V/KeepSync( 3957): Connecting to GoogleApiClient
,I/BooksConfig( 4040): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1259): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1259): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1259): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1259): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
I/GLSUser ( 1259): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1259): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1259): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1259): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1774): Handling authorization failure
E/ClientConnectionOperation( 1774): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1774): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1774): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1774): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1774): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1774): 	... 7 more
,V/KeepSync( 3957): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3957): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3957): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3957): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1259): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1259): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1259): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1259): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 4040): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 4040): Soft error
E/BooksSync( 4040): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4040): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 4040): Sync error
E/BooksSync( 4040): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4040): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 4040): Finished books sync
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 228214, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1259): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1259): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1259): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1259): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3957): IOException
E/KeepSync( 3957): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3957): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3957): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3957): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3957): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3957): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3957): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3957): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3957): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3957): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3957): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3957): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3957): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3957): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
,E/KeepSync( 3957): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3957): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3957): 	... 10 more
W/KeepSync( 3957): Sync result 2
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 231158, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/jxcore-log( 3714): TAP version 13
I/jxcore-log( 3714): 
I/jxcore-log( 3714): # setup
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): # multiplex can send data
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): # teardown
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): ok 1 String should be length:200
I/jxcore-log( 3714): 
I/jxcore-log( 3714): # setup
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): # enqueue and run in order
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): # teardown
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): ok 2 firstPromise setTimeout
I/jxcore-log( 3714): 
I/jxcore-log( 3714): ok 3 firstPromise result
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): ok 4 firstPromise testValue
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): ok 5 secondPromise setTimeout
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): ok 6 secondPromise result
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): ok 7 secondPromise testValue
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): ok 8 thirdPromise in promise
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): ok 9 thirdPromise result,
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): ok 10 thirdPromise testValue,
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): # setup,
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): # basic,
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): # teardown,
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): ok 11 sane,
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): # setup,
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): # another,
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): # teardown,
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): ok 12 sane,
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): # setup,
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): # successfully create a new pkcs12 file and return hash value,
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): # teardown
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): ok 13 should be equal
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): ok 14 null
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): ok 15 (unnamed assert)
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): ok 16 should be equal
I/jxcore-log( 3714): 
I/jxcore-log( 3714): ok 17 should not throw
I/jxcore-log( 3714): 
I/jxcore-log( 3714): # setup
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): # successfully read a previous pkcs12 file and return hash value
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): # teardown
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): ok 18 (unnamed assert)
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): ok 19 (unnamed assert)
,I/jxcore-log( 3714): 
I/jxcore-log( 3714): ok 20 should not throw
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): ok 21 should be equal
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): ok 22 should be equal
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): # setup
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): # failed to extract public key because of corrupt pkcs12 file
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): # teardown
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): ok 23 should be equal
I/jxcore-log( 3714): ,
,I/jxcore-log( 3714): # setup
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): # failed to get mobile documents path
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): # teardown
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): ok 24 should be equal
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): # setup
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): # #init should register the peerAvailabilityChanged event
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): # teardown
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): ok 25 should be equal
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): ok 26 should be equal
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): ok 27 should be equal
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): # setup
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): # #init should register the networkChanged event
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): # teardown
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): ok 28 should be equal
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): # setup
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): # #startBroadcasting should throw on null device name
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): # teardown
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): ok 29 should throw
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): # setup
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): # #startBroadcasting should throw on empty string device name
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): # teardown
,I/jxcore-log( 3714): 
,I/jxcore-log( 3714): ok 30 should throw
,I/jxcore-log( 3714): 
,I/jxcore-log( 3714): # setup
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): # #startBroadcasting should throw on non-number port
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): # teardown
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): ok 31 should throw
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): # setup
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): # #startBroadcasting should throw on NaN port
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): # teardown
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): ok 32 should throw
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): # setup
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): # #startBroadcasting should throw on negative port
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): # teardown
I/jxcore-log( 3714): ,
,I/jxcore-log( 3714): ok 33 should throw
,I/jxcore-log( 3714): 
,I/jxcore-log( 3714): # setup
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): # #startBroadcasting should throw on too large port
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): # teardown
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): ok 34 should throw
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): # setup
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): # #startBroadcasting should call Mobile("StartBroadcasting") without an error
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): # teardown
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): ok 35 should be equal
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): ok 36 should be equal
I/jxcore-log( 3714): 
I/jxcore-log( 3714): ok 37 should be equal
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): # setup
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): # #startBroadcasting should call Mobile("StartBroadcasting") and handle an error
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): # teardown
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): ok 38 should be equal
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): ok 39 should be equal
I/jxcore-log( 3714): 
I/jxcore-log( 3714): ok 40 should be equal
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): # setup
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): # #stopBroadcasting should call Mobile("StopBroadcasting") without an error
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): # teardown
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): ok 41 should be equal
I/jxcore-log( 3714): ,
I/jxcore-log( 3714): ok 42 should be equal
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): # setup
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): # #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): # teardown
I/jxcore-log( 3714): ,
,I/jxcore-log( 3714): ok 43 should be equal
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): ok 44 should be equal
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): # setup
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): # #connect should call Mobile("Connect") with a port and without an error
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): # teardown
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): ok 45 should be equal
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): ok 46 should be equal
I/jxcore-log( 3714): 
I/jxcore-log( 3714): ok 47 should be equal
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): # setup
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): # #connect should call Mobile("Connect") and handle an error
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): # teardown
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): ok 48 should be equal
,I/jxcore-log( 3714): 
I/jxcore-log( 3714): ok 49 should be equal
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): # setup
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): # should call Mobile("Disconnect") without an error
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): # teardown
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): ok 50 should be equal
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): ok 51 should be equal
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): # setup
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): # should call Mobile("Disconnect") and handle an error
I/jxcore-log( 3714): ,
,I/jxcore-log( 3714): # teardown
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): ok 52 should be equal
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): ok 53 should be equal
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): # setup
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): # ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): # teardown
I/jxcore-log( 3714): 
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3714): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3714): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3714): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3714): 	Maximum number of connection attempt retries: 0
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): 	Bluetooth MAC address: F8:CF:C5:D9:E5:61, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): 	Discovery mode: BLE_AND_WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): 	Scan mode: 1
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27d0db9b added. We now have 2 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): setDiscoveryMode: BLE_AND_WIFI -> WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onDiscoveryModeChanged: Mode set to WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onDiscoveryModeChanged: Mode set to WIFI
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3714): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454983781959.3714
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3714): bind: Binding a new listener
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3714): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3714): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454983781959.3714","ra":"F8:CF:C5:D9:E5:61"},
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3714): setConnectionTimeout: 15000
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3714): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3714): startListeningForIncomingConnections: Starting...
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3714): setState: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3714): start: OK
I/io.jxcore.node.ConnectionHelper( 3714): start: Using peer discovery mode: WIFI
,I/io.jxcore.node.ConnectionHelper( 3714): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454983781959.3714, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3714): bind: Binding a new listener
W/BluetoothAdapter( 3714): getBluetoothService() called with no BluetoothManagerCallback
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3714): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onWifiStateChanged: State changed to 2
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3714): Waiting for incoming connections...
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3714): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454983781959.3714","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3714): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454983781959.3714","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3714): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1454983781959.3714","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onIsWifiPeerDiscoveryStartedChanged: true,
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3714): start: Already running, call stopListening() first to restart
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): startWifiPeerDiscovery: Wi-Fi Direct OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): start: OK
I/io.jxcore.node.ConnectionHelper( 3714): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454983781959.3714, mode: WIFI,
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/jxcore-log( 3714): ok 54 Should be able to call startBroadcasting without error
I/jxcore-log( 3714): 
,I/io.jxcore.node.ConnectionHelper( 3714): stop
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3714): stop: Stopping Bluetooth...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3714): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3714): stopListeningForIncomingConnections: Stopping...
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3714): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3714): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3714): onServerStopped
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3714): release: 1 listener(s) left,
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3714): setState: NOT_STARTED
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3714): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 3714): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3714): stop: Stopping services
I/io.jxcore.node.ConnectionHelper( 3714): onDiscoveryManagerStateChanged: RUNNING_WIFI
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3714): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 3714): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): P2P device discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onIsWifiPeerDiscoveryStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): setState: STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3714): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3714): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3714): release: No more listeners, de-initializing...
I/wpa_supplicant( 1149): P2P-FIND-STOPPED 
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3714): clear
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3714): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 3714): ok 55 Should be able to call stopBroadcasting without error
I/jxcore-log( 3714): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): P2P device discovery stopped successfully
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3714): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3714): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3714): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3714): 	Maximum number of connection attempt retries: 0
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3714): Service requests cleared successfully
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): 	Bluetooth MAC address: F8:CF:C5:D9:E5:61, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): 	Scan mode: 1
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dad82e4 added. We now have 3 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): setDiscoveryMode: WIFI -> BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3714): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454983782075.3714
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3714): bind: Binding a new listener
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3714): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3714): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454983782075.3714","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3714): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3714): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3714): startListeningForIncomingConnections: Starting...
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3714): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3714): start: OK
I/io.jxcore.node.ConnectionHelper( 3714): start: Using peer discovery mode: BLE_AND_WIFI
,I/io.jxcore.node.ConnectionHelper( 3714): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3714): getBluetoothService() called with no BluetoothManagerCallback
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454983782075.3714, mode: BLE_AND_WIFI,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3714): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3714): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onWifiStateChanged: State changed to 2
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3714): Waiting for incoming connections...
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): constructBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...,
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3714): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3714): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3714): start
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3714): createAdvertiseData: From: 1454983782075.3714 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3714): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,D/BtGatt.GattService( 2187): registerClient() - UUID=d44db5ae-ea0d-4eff-86c2-af5618e422d0
D/BtGatt.GattService( 2187): onClientRegistered() - UUID=d44db5ae-ea0d-4eff-86c2-af5618e422d0, clientIf=5
,D/BluetoothLeScanner( 3714): onClientRegistered() - status=0 clientIf=5
,D/BtGatt.GattService( 2187): start scan with filters
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3714): setState: State changed from NOT_STARTED to STARTING,
,D/BtGatt.ScanManager( 2187): handling starting scan
,D/BluetoothAdapterService( 2187): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f957083
,D/BtGatt.GattService( 2187): registerClient() - UUID=959981ce-e95b-4b5c-8336-6b5393ccbbff
,D/BtGatt.GattService( 2187): onClientRegistered() - UUID=959981ce-e95b-4b5c-8336-6b5393ccbbff, clientIf=6
D/BluetoothLeAdvertiser( 3714): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.AdvertiseManager( 2187): message : 0
,D/BtGatt.GattService( 2187): onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,D/BtGatt.ScanManager( 2187): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2187): onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,D/BtGatt.ScanManager( 2187): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2187): configureRegularScanParams() - queue=1
D/BtGatt.ScanManager( 2187): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
D/BtGatt.AdvertiseManager( 2187): starting multi advertising
,D/BtGatt.GattService( 2187): onAdvertiseInstanceEnabled() - clientIf=6, status=0
,D/BtGatt.GattService( 2187): onAdvertiseDataSet() - clientIf=6, status=0
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3714): setState: State changed from NOT_STARTED to STARTING
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): startBlePeerDiscoverer: OK
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3714): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454983782075.3714","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3714): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454983782075.3714","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3714): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1454983782075.3714","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3714): start: Already running, call stopListening() first to restart
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): setState: RUNNING_BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): start: OK
I/io.jxcore.node.ConnectionHelper( 3714): start: OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454983782075.3714, mode: BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3714): start
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3714): createAdvertiseData: From: 1454983782075.3714 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
I/jxcore-log( 3714): ok 56 Should be able to call startBroadcasting without error
I/jxcore-log( 3714): 
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3714): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/io.jxcore.node.ConnectionHelper( 3714): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3714): stop: Stopping Bluetooth...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3714): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3714): stopListeningForIncomingConnections: Stopping...
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3714): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3714): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3714): onServerStopped
,I/wpa_supplicant( 1149): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3714): release: 1 listener(s) left
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3714): setState: NOT_STARTED
,D/BtGatt.AdvertiseManager( 2187): message : 1
D/BtGatt.AdvertiseManager( 2187): stop advertise for client 6
D/BtGatt.GattService( 2187): onAdvertiseInstanceDisabled() - clientIf=6, status=0
D/BtGatt.GattService( 2187): Client app is not null!
D/BtGatt.GattService( 2187): unregisterClient() - clientIf=6
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3714): stop: Stopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3714): setState: State changed from STARTING to NOT_STARTED
D/BtGatt.GattService( 2187): registerClient() - UUID=5051e8df-ad71-4ec4-95f2-5712fa89a0ba
,D/BtGatt.GattService( 2187): onClientRegistered() - UUID=5051e8df-ad71-4ec4-95f2-5712fa89a0ba, clientIf=6
D/BluetoothLeAdvertiser( 3714): onClientRegistered() - status=0 clientIf=6
D/BtGatt.AdvertiseManager( 2187): message : 0
,D/BtGatt.AdvertiseManager( 2187): starting multi advertising,
,D/BtGatt.GattService( 2187): onAdvertiseInstanceEnabled() - clientIf=6, status=0
,D/BtGatt.GattService( 2187): onAdvertiseDataSet() - clientIf=6, status=0
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3714): setState: State changed from NOT_STARTED to STARTING
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3714): start: Already running
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3714): start: Already running
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): startBlePeerDiscoverer: OK
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3714): start: Already running, call stopListening() first to restart
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): stop: Stopping peer discovery...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 3714): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3714): stop
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3714): onStartSuccess
D/BtGatt.AdvertiseManager( 2187): message : 1
,D/BtGatt.AdvertiseManager( 2187): stop advertise for client 6
,D/BtGatt.GattService( 2187): onAdvertiseInstanceDisabled() - clientIf=6, status=0,
,D/BtGatt.GattService( 2187): Client app is not null!,
D/BtGatt.GattService( 2187): unregisterClient() - clientIf=6,
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3714): stop: Stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3714): setState: State changed from STARTING to NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3714): onIsAdvertiserStartedChanged: false,
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3714): updateState(): State changed from [NOT_STARTED] to [SCANNING]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onIsBlePeerDiscovererStateChanged: [SCANNING]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3714): setState: State changed from NOT_STARTED to RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3714): onIsAdvertiserStartedChanged: true
D/BtGatt.GattService( 2187): stopScan() - queue size =1,
D/BtGatt.GattService( 2187): unregisterClient() - clientIf=5
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3714): stop: Stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3714): setState: State changed from STARTING to NOT_STARTED,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3714): onIsScannerStartedChanged: false
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3714): updateState(): State changed from [SCANNING] to [ADVERTISING_SELF]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onIsBlePeerDiscovererStateChanged: [ADVERTISING_SELF]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): stopBlePeerDiscoverer: Stopped,
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3714): stop: Stopping services
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): setState: RESTARTING
,I/io.jxcore.node.ConnectionHelper( 3714): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3714): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 3714): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): P2P device discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): setState: NOT_INITIALIZED
,D/BtGatt.GattService( 2187): onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
D/BtGatt.ScanManager( 2187): callback done for clientIf - 5 status - 0
D/BtGatt.ScanManager( 2187): stop scan
D/BtGatt.ScanManager( 2187): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager( 2187): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
,D/BtGatt.ScanManager( 2187): configureRegularScanParams() - queue emtpy, scan stopped
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): setState: STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3714): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onIsWifiPeerDiscoveryStartedChanged: false
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3714): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3714): release: No more listeners, de-initializing...
I/wpa_supplicant( 1149): P2P-FIND-STOPPED 
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3714): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3714): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3714): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 3714): ok 57 Should be able to call stopBroadcasting without error
I/jxcore-log( 3714): 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): P2P device discovery stopped successfully
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3714): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3714): 	,Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3714): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3714): 	Maximum number of connection attempt retries: 0
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): load: 
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): 	Automate Bluetooth MAC address resolution: true, ,
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): 	Bluetooth MAC address: F8:CF:C5:D9:E5:61, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): 	Discovery mode: BLE_AND_WIFI, 
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): 	Scan mode: 1
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9b4dd6f added. We now have 4 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): setDiscoveryMode: BLE_AND_WIFI -> WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onDiscoveryModeChanged: Mode set to WIFI
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3714): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onDiscoveryModeChanged: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onDiscoveryModeChanged: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onDiscoveryModeChanged: Mode set to WIFI
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3714): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454983782235.3714
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3714): bind: Binding a new listener
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3714): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3714): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454983782235.3714","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3714): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3714): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3714): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3714): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3714): start: OK
I/io.jxcore.node.ConnectionHelper( 3714): start: Using peer discovery mode: WIFI
I/io.jxcore.node.ConnectionHelper( 3714): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3714): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3714): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454983782235.3714, mode: WIFI,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3714): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3714): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3714): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454983782235.3714","ra":"F8:CF:C5:D9:E5:61"},
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3714): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454983782235.3714","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3714): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1454983782235.3714","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onIsWifiPeerDiscoveryStartedChanged: true,
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3714): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): start: OK
,I/io.jxcore.node.ConnectionHelper( 3714): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454983782235.3714, mode: WIFI
I/wpa_supplicant( 1149): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/jxcore-log( 3714): ok 58 Should be able to call startBroadcasting without error
I/jxcore-log( 3714): 
I/io.jxcore.node.ConnectionHelper( 3714): stop
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3714): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3714): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3714): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3714): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3714): release: 1 listener(s) left
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3714): setState: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3714): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3714): onServerStopped
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3714): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3714): Local service added successfully
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): stopForRestart
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 3714): stopProvideBluetoothMacAddressMode
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): setState: RESTARTING
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3714): stop: Stopping services
I/io.jxcore.node.ConnectionHelper( 3714): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): P2P device discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): setState: NOT_INITIALIZED
,I/wpa_supplicant( 1149): P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 3714): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): stopWifiPeerDiscovery: Stopped
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3714): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3714): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3714): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): setState: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper( 3714): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3714): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3714): Service requests cleared successfully
I/jxcore-log( 3714): ok 59 Should be able to call stopBroadcasting without error
I/jxcore-log( 3714): 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3714): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3714): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3714): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3714): 	Maximum number of connection attempt retries: 0
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): 	Bluetooth MAC address: F8:CF:C5:D9:E5:61, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17dbe18b added. We now have 5 listener(s)
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): setDiscoveryMode: WIFI -> BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3714): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454983782300.3714
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3714): bind: Binding a new listener
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3714): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3714): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454983782300.3714","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3714): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3714): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3714): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3714): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3714): start: OK
I/io.jxcore.node.ConnectionHelper( 3714): start: Using peer discovery mode: BLE_AND_WIFI
,I/io.jxcore.node.ConnectionHelper( 3714): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
W/BluetoothAdapter( 3714): getBluetoothService() called with no BluetoothManagerCallback
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454983782300.3714, mode: BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3714): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3714): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onWifiStateChanged: State changed to 2
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3714): Waiting for incoming connections...
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): constructBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3714): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3714): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3714): start
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3714): createAdvertiseData: From: 1454983782300.3714 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3714): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,D/BtGatt.GattService( 2187): registerClient() - UUID=0f504c7a-6be2-42a6-884a-4865fc1870f9
,D/BtGatt.GattService( 2187): onClientRegistered() - UUID=0f504c7a-6be2-42a6-884a-4865fc1870f9, clientIf=5
D/BluetoothLeScanner( 3714): onClientRegistered() - status=0 clientIf=5
D/BtGatt.GattService( 2187): start scan with filters
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3714): setState: State changed from NOT_STARTED to STARTING
,D/BtGatt.ScanManager( 2187): handling starting scan
,D/BtGatt.GattService( 2187): onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,D/BtGatt.ScanManager( 2187): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2187): registerClient() - UUID=aefc344a-1af5-480f-ba55-a0df0847bcd0
D/BtGatt.GattService( 2187): onClientRegistered() - UUID=aefc344a-1af5-480f-ba55-a0df0847bcd0, clientIf=6
D/BluetoothLeAdvertiser( 3714): onClientRegistered() - status=0 clientIf=6
D/BtGatt.AdvertiseManager( 2187): message : 0
D/BtGatt.GattService( 2187): onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,D/BtGatt.ScanManager( 2187): callback done for clientIf - 5 status - 0
D/BtGatt.ScanManager( 2187): configureRegularScanParams() - queue=1
D/BtGatt.ScanManager( 2187): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
,D/BtGatt.AdvertiseManager( 2187): starting multi advertising
,D/BtGatt.GattService( 2187): onAdvertiseInstanceEnabled() - clientIf=6, status=0
,D/BtGatt.GattService( 2187): onAdvertiseDataSet() - clientIf=6, status=0
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3714): setState: State changed from NOT_STARTED to STARTING
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): startBlePeerDiscoverer: OK
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3714): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454983782300.3714","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3714): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454983782300.3714","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3714): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1454983782300.3714","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3714): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): start: OK
,I/io.jxcore.node.ConnectionHelper( 3714): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454983782300.3714, mode: BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3714): start
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3714): createAdvertiseData: From: 1454983782300.3714 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3714): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/wpa_supplicant( 1149): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
I/jxcore-log( 3714): ok 60 Should be able to call startBroadcasting without error
I/jxcore-log( 3714): 
,D/BtGatt.AdvertiseManager( 2187): message : 1
D/BtGatt.AdvertiseManager( 2187): stop advertise for client 6
,I/io.jxcore.node.ConnectionHelper( 3714): stop
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3714): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3714): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3714): stopListeningForIncomingConnections: Stopping...
D/BtGatt.GattService( 2187): onAdvertiseInstanceDisabled() - clientIf=6, status=0
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3714): shutdown
D/BtGatt.GattService( 2187): Client app is not null!
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3714): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3714): onServerStopped
D/BtGatt.GattService( 2187): unregisterClient() - clientIf=6
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3714): stop: Stopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3714): setState: State changed from STARTING to NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3714): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3714): setState: NOT_STARTED
,D/BtGatt.GattService( 2187): registerClient() - UUID=c981515a-4ad6-4066-ae5a-24f211a5ed16
D/BtGatt.GattService( 2187): onClientRegistered() - UUID=c981515a-4ad6-4066-ae5a-24f211a5ed16, clientIf=6
,D/BluetoothLeAdvertiser( 3714): onClientRegistered() - status=0 clientIf=6
D/BtGatt.AdvertiseManager( 2187): message : 0
,D/BtGatt.AdvertiseManager( 2187): starting multi advertising
,D/BtGatt.GattService( 2187): onAdvertiseInstanceEnabled() - clientIf=6, status=0
,D/BtGatt.GattService( 2187): onAdvertiseDataSet() - clientIf=6, status=0
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3714): setState: State changed from NOT_STARTED to STARTING
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3714): start: Already running
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3714): start: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): startBlePeerDiscoverer: OK
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3714): start: Already running, call stopListening() first to restart
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3714): onStartSuccess
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3714): setState: State changed from STARTING to RUNNING
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3714): onIsAdvertiserStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 3714): stopProvideBluetoothMacAddressMode
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3714): updateState(): State changed from [NOT_STARTED] to [SCANNING, ADVERTISING_SELF]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onIsBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING_SELF]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3714): stop
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 3714): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3714): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/io.jxcore.node.ConnectionHelper( 3714): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3714): onStartSuccess
I/wpa_supplicant( 1149): P2P-FIND-STOPPED 
D/BtGatt.AdvertiseManager( 2187): message : 1
D/BtGatt.AdvertiseManager( 2187): stop advertise for client 6
D/BtGatt.GattService( 2187): onAdvertiseInstanceDisabled() - clientIf=6, status=0
,D/BtGatt.GattService( 2187): Client app is not null!
D/BtGatt.GattService( 2187): unregisterClient() - clientIf=6
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3714): stop: Stopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3714): setState: State changed from RUNNING to NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3714): onIsAdvertiserStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3714): updateState(): State changed from [SCANNING, ADVERTISING_SELF] to [SCANNING]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onIsBlePeerDiscovererStateChanged: [SCANNING]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3714): setState: State changed from NOT_STARTED to RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3714): onIsAdvertiserStartedChanged: true
,D/BtGatt.GattService( 2187): stopScan() - queue size =1
D/BtGatt.GattService( 2187): unregisterClient() - clientIf=5
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3714): stop: Stopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3714): setState: State changed from STARTING to NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3714): onIsScannerStartedChanged: false,
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3714): updateState(): State changed from [SCANNING] to [ADVERTISING_SELF]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onIsBlePeerDiscovererStateChanged: [ADVERTISING_SELF]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): stopBlePeerDiscoverer: Stopped
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3714): stop: Stopping services
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
D/BtGatt.GattService( 2187): onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16,
D/BtGatt.ScanManager( 2187): callback done for clientIf - 5 status - 0
D/BtGatt.ScanManager( 2187): stop scan
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): stop: Stopping P2P device discovery...
D/BtGatt.ScanManager( 2187): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager( 2187): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager( 2187): configureRegularScanParams() - queue emtpy, scan stopped
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): setState: NOT_INITIALIZED
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): restart: Cannot restart, because not initialized
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3714): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3714): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3714): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3714): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3714): onDiscoveryManagerStateChanged: NOT_STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3714): Service requests cleared successfully
I/jxcore-log( 3714): ok 61 Should be able to call stopBroadcasting without error
I/jxcore-log( 3714): 
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3714): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3714): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3714): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3714): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): 	Bluetooth MAC address: F8:CF:C5:D9:E5:61, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): 	Discovery mode: BLE_AND_WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): 	Scan mode: 1
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1517b9bd added. We now have 6 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): setDiscoveryMode: BLE_AND_WIFI -> WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onDiscoveryModeChanged: Mode set to WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onDiscoveryModeChanged: Mode set to WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onDiscoveryModeChanged: Mode set to WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onDiscoveryModeChanged: Mode set to WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onDiscoveryModeChanged: Mode set to WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onDiscoveryModeChanged: Mode set to WIFI
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3714): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454983782412.3714
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3714): bind: Binding a new listener
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3714): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3714): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454983782412.3714","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3714): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3714): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3714): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3714): setState: RUNNING,
I/io.jxcore.node.ConnectionHelper( 3714): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3714): start: OK
I/io.jxcore.node.ConnectionHelper( 3714): start: Using peer discovery mode: WIFI
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3714): getBluetoothService() called with no BluetoothManagerCallback,
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454983782412.3714, mode: WIFI,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3714): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3714): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3714): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onWifiStateChanged: State changed to 2,
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3714): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454983782412.3714","ra":"F8:CF:C5:D9:E5:61"},
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3714): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454983782412.3714","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3714): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1454983782412.3714","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onIsWifiPeerDiscoveryStartedChanged: true,
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3714): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): start: OK
I/io.jxcore.node.ConnectionHelper( 3714): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454983782412.3714, mode: WIFI
,I/wpa_supplicant( 1149): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/jxcore-log( 3714): ok 62 Should be able to call startBroadcasting without error
I/jxcore-log( 3714): 
,I/io.jxcore.node.ConnectionHelper( 3714): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3714): stop: Stopping Bluetooth...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3714): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3714): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3714): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3714): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3714): onServerStopped
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3714): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3714): release: 1 listener(s) left
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): start: OK
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3714): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 3714): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): restart: Restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3714): stop: Stopping services
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): setState: RESTARTING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3714): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 3714): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/io.jxcore.node.ConnectionHelper( 3714): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3714): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3714): release: No more listeners, de-initializing...,
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3714): Local services cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3714): clear
I/wpa_supplicant( 1149): P2P-FIND-STOPPED ,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3714): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 3714): ok 63 Should be able to call stopBroadcasting without error
I/jxcore-log( 3714): 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3714): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3714): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3714): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3714): 	Maximum number of connection attempt retries: 0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): P2P device discovery stopped successfully
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): 	Bluetooth MAC address: F8:CF:C5:D9:E5:61, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): 	Scan mode: 1
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@128b34b9 added. We now have 7 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): setDiscoveryMode: WIFI -> BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3714): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3714): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454983782481.3714
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3714): bind: Binding a new listener
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3714): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3714): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454983782481.3714","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3714): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3714): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3714): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3714): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper( 3714): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3714): start: OK
I/io.jxcore.node.ConnectionHelper( 3714): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3714): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3714): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454983782481.3714, mode: BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3714): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3714): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onWifiStateChanged: State changed to 2
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): constructBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3714): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3714): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3714): start
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3714): createAdvertiseData: From: 1454983782481.3714 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3714): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,D/BtGatt.GattService( 2187): registerClient() - UUID=1a1598ea-c4d1-44b6-9355-145ba1b08140
,D/BtGatt.GattService( 2187): onClientRegistered() - UUID=1a1598ea-c4d1-44b6-9355-145ba1b08140, clientIf=5
D/BluetoothLeScanner( 3714): onClientRegistered() - status=0 clientIf=5
,D/BtGatt.GattService( 2187): start scan with filters
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3714): setState: State changed from NOT_STARTED to STARTING
D/BtGatt.ScanManager( 2187): handling starting scan
,D/BtGatt.GattService( 2187): onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,D/BtGatt.ScanManager( 2187): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2187): onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
D/BtGatt.ScanManager( 2187): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2187): configureRegularScanParams() - queue=1
D/BtGatt.ScanManager( 2187): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
D/BtGatt.GattService( 2187): registerClient() - UUID=875eae28-0dee-4c0f-a2db-e7d095f59544
D/BtGatt.GattService( 2187): onClientRegistered() - UUID=875eae28-0dee-4c0f-a2db-e7d095f59544, clientIf=6
,D/BluetoothLeAdvertiser( 3714): onClientRegistered() - status=0 clientIf=6
D/BtGatt.AdvertiseManager( 2187): message : 0
,D/BtGatt.AdvertiseManager( 2187): starting multi advertising
,D/BtGatt.GattService( 2187): onAdvertiseInstanceEnabled() - clientIf=6, status=0
,D/BtGatt.GattService( 2187): onAdvertiseDataSet() - clientIf=6, status=0
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3714): setState: State changed from NOT_STARTED to STARTING
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): startBlePeerDiscoverer: OK
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3714): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454983782481.3714","ra":"F8:CF:C5:D9:E5:61"},
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3714): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454983782481.3714","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3714): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1454983782481.3714","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): setState: INITIALIZED,
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onIsWifiPeerDiscoveryStartedChanged: true
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3714): start: Already running, call stopListening() first to restart
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): setState: RUNNING_BLE_AND_WIFI
I/wpa_supplicant( 1149): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): start: OK
I/io.jxcore.node.ConnectionHelper( 3714): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454983782481.3714, mode: BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3714): start,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3714): createAdvertiseData: From: 1454983782481.3714 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3714): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/jxcore-log( 3714): ok 64 Should be able to call startBroadcasting without error
I/jxcore-log( 3714): 
D/BtGatt.AdvertiseManager( 2187): message : 1
D/BtGatt.AdvertiseManager( 2187): stop advertise for client 6
,I/io.jxcore.node.ConnectionHelper( 3714): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3714): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3714): Shutting down...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3714): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3714): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3714): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3714): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3714): release: 1 listener(s) left
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3714): setState: NOT_STARTED
,D/BtGatt.GattService( 2187): onAdvertiseInstanceDisabled() - clientIf=6, status=0
D/BtGatt.GattService( 2187): Client app is not null!
,D/BtGatt.GattService( 2187): unregisterClient() - clientIf=6
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3714): stop: Stopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3714): setState: State changed from STARTING to NOT_STARTED
,D/BtGatt.GattService( 2187): registerClient() - UUID=ac8dbf53-abe6-4f28-a4a6-d0ce0716de09
D/BtGatt.GattService( 2187): onClientRegistered() - UUID=ac8dbf53-abe6-4f28-a4a6-d0ce0716de09, clientIf=6
,D/BluetoothLeAdvertiser( 3714): onClientRegistered() - status=0 clientIf=6
D/BtGatt.AdvertiseManager( 2187): message : 0
,D/BtGatt.AdvertiseManager( 2187): starting multi advertising,
,D/BtGatt.GattService( 2187): onAdvertiseInstanceEnabled() - clientIf=6, status=0
,D/BtGatt.GattService( 2187): onAdvertiseDataSet() - clientIf=6, status=0
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3714): setState: State changed from NOT_STARTED to STARTING
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3714): start: Already running
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3714): start: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): startBlePeerDiscoverer: OK
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3714): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): startWifiPeerDiscovery: Wi-Fi Direct OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3714): onStartSuccess
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3714): setState: State changed from STARTING to RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3714): onIsAdvertiserStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3714): updateState(): State changed from [NOT_STARTED] to [SCANNING, ADVERTISING_SELF]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onIsBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING_SELF]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3714): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): setState: RESTARTING
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): stop: Stopping peer discovery...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 3714): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3714): stop
I/io.jxcore.node.ConnectionHelper( 3714): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): setState: STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3714): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3714): onStartSuccess
I/wpa_supplicant( 1149): P2P-FIND-STOPPED 
D/BtGatt.AdvertiseManager( 2187): message : 1
,D/BtGatt.AdvertiseManager( 2187): stop advertise for client 6
,D/BtGatt.GattService( 2187): onAdvertiseInstanceDisabled() - clientIf=6, status=0
,D/BtGatt.GattService( 2187): Client app is not null!
,D/BtGatt.GattService( 2187): unregisterClient() - clientIf=6
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3714): stop: Stopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3714): setState: State changed from RUNNING to NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3714): onIsAdvertiserStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3714): updateState(): State changed from [SCANNING, ADVERTISING_SELF] to [SCANNING]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onIsBlePeerDiscovererStateChanged: [SCANNING]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3714): setState: State changed from NOT_STARTED to RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3714): onIsAdvertiserStartedChanged: true
D/BtGatt.GattService( 2187): stopScan() - queue size =1
,D/BtGatt.GattService( 2187): unregisterClient() - clientIf=5
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3714): stop: Stopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3714): setState: State changed from STARTING to NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3714): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3714): updateState(): State changed from [SCANNING] to [ADVERTISING_SELF]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onIsBlePeerDiscovererStateChanged: [ADVERTISING_SELF]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): setState: RESTARTING
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): stopBlePeerDiscoverer: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3714): stop: Stopping services
,D/BtGatt.GattService( 2187): onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
D/BtGatt.ScanManager( 2187): callback done for clientIf - 5 status - 0
D/BtGatt.ScanManager( 2187): stop scan
D/BtGatt.ScanManager( 2187): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager( 2187): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager( 2187): configureRegularScanParams() - queue emtpy, scan stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3714): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3714): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3714): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3714): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3714): Local services cleared successfully
I/jxcore-log( 3714): ok 65 Should be able to call stopBroadcasting without error
I/jxcore-log( 3714): 
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3714): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3714): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3714): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3714): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): ,	Bluetooth MAC address: F8:CF:C5:D9:E5:61, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): 	Discovery mode: BLE_AND_WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@246c437b added. We now have 8 listener(s)
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): setDiscoveryMode: BLE_AND_WIFI -> WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3714): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onDiscoveryModeChanged: Mode set to WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onDiscoveryModeChanged: Mode set to WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onDiscoveryModeChanged: Mode set to WIFI,
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onDiscoveryModeChanged: Mode set to WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onDiscoveryModeChanged: Mode set to WIFI,
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onDiscoveryModeChanged: Mode set to WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onDiscoveryModeChanged: Mode set to WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onDiscoveryModeChanged: Mode set to WIFI,
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0,
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3714): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454983782613.3714,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3714): bind: Binding a new listener
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3714): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3714): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454983782613.3714","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3714): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3714): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3714): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3714): setState: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3714): start: OK
I/io.jxcore.node.ConnectionHelper( 3714): start: Using peer discovery mode: WIFI
I/io.jxcore.node.ConnectionHelper( 3714): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
W/BluetoothAdapter( 3714): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3714): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454983782613.3714, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3714): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3714): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onWifiStateChanged: State changed to 2
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3714): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454983782613.3714","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3714): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454983782613.3714","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3714): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1454983782613.3714","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onIsWifiPeerDiscoveryStartedChanged: true
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3714): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): startWifiPeerDiscovery: Wi-Fi Direct OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): start: OK
I/io.jxcore.node.ConnectionHelper( 3714): start: OK
I/wpa_supplicant( 1149): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454983782613.3714, mode: WIFI
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/jxcore-log( 3714): ok 66 Should be able to call startBroadcasting without error
I/jxcore-log( 3714): 
I/io.jxcore.node.ConnectionHelper( 3714): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3714): stop: Stopping Bluetooth...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3714): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3714): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3714): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3714): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3714): onServerStopped
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3714): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3714): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3714): setState: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): stopForRestart
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3714): Local service added successfully,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 3714): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3714): stop: Stopping services
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 3714): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): setState: STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3714): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): stop: Stopping P2P device discovery...
I/wpa_supplicant( 1149): P2P-FIND-STOPPED 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3714): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3714): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3714): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3714): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3714): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3714): onDiscoveryManagerStateChanged: NOT_STARTED
,I/jxcore-log( 3714): ok 67 Should be able to call stopBroadcasting without error
I/jxcore-log( 3714): 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3714): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3714): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3714): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3714): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): 	Bluetooth MAC address: F8:CF:C5:D9:E5:61, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25f19c57 added. We now have 9 listener(s)
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): setDiscoveryMode: WIFI -> BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI,
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0,
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0,
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3714): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454983782700.3714
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3714): bind: Binding a new listener
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3714): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3714): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454983782700.3714","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3714): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3714): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3714): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3714): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 3714): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3714): start: OK
I/io.jxcore.node.ConnectionHelper( 3714): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3714): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3714): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454983782700.3714, mode: BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3714): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3714): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): constructBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3714): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3714): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3714): start,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3714): createAdvertiseData: From: 1454983782700.3714 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3714): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,D/BtGatt.GattService( 2187): registerClient() - UUID=bdf53ee4-b425-4c6a-9199-a3e9b9b74408
,D/BtGatt.GattService( 2187): onClientRegistered() - UUID=bdf53ee4-b425-4c6a-9199-a3e9b9b74408, clientIf=5
D/BluetoothLeScanner( 3714): onClientRegistered() - status=0 clientIf=5
D/BtGatt.GattService( 2187): start scan with filters
D/BtGatt.ScanManager( 2187): handling starting scan
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3714): setState: State changed from NOT_STARTED to STARTING
,D/BtGatt.GattService( 2187): onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
D/BtGatt.ScanManager( 2187): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2187): onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
D/BtGatt.ScanManager( 2187): callback done for clientIf - 5 status - 0
D/BtGatt.ScanManager( 2187): configureRegularScanParams() - queue=1
D/BtGatt.ScanManager( 2187): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
D/BtGatt.GattService( 2187): registerClient() - UUID=55fac6dd-9946-4ea2-92ae-564147395508
,D/BtGatt.GattService( 2187): onClientRegistered() - UUID=55fac6dd-9946-4ea2-92ae-564147395508, clientIf=6
D/BluetoothLeAdvertiser( 3714): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.AdvertiseManager( 2187): message : 0,
,D/BtGatt.AdvertiseManager( 2187): starting multi advertising
,D/BtGatt.GattService( 2187): onAdvertiseInstanceEnabled() - clientIf=6, status=0
,D/BtGatt.GattService( 2187): onAdvertiseDataSet() - clientIf=6, status=0
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3714): setState: State changed from NOT_STARTED to STARTING
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): startBlePeerDiscoverer: OK
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3714): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454983782700.3714","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3714): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454983782700.3714","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3714): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1454983782700.3714","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3714): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): startWifiPeerDiscovery: Wi-Fi Direct OK,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): start: OK
I/io.jxcore.node.ConnectionHelper( 3714): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454983782700.3714, mode: BLE_AND_WIFI
,I/wpa_supplicant( 1149): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3714): start
I/jxcore-log( 3714): ok 68 Should be able to call startBroadcasting without error
I/jxcore-log( 3714): 
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3714): createAdvertiseData: From: 1454983782700.3714 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3714): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/io.jxcore.node.ConnectionHelper( 3714): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3714): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3714): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3714): stopListeningForIncomingConnections: Stopping...
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3714): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3714): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3714): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3714): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3714): setState: NOT_STARTED
D/BtGatt.AdvertiseManager( 2187): message : 1
,D/BtGatt.AdvertiseManager( 2187): stop advertise for client 6
D/BtGatt.GattService( 2187): onAdvertiseInstanceDisabled() - clientIf=6, status=0
D/BtGatt.GattService( 2187): Client app is not null!
,D/BtGatt.GattService( 2187): unregisterClient() - clientIf=6
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3714): stop: Stopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3714): setState: State changed from STARTING to NOT_STARTED
,D/BtGatt.GattService( 2187): registerClient() - UUID=a04e48ff-cb3e-4c3e-a1e4-0251cc73ae13
,D/BtGatt.GattService( 2187): onClientRegistered() - UUID=a04e48ff-cb3e-4c3e-a1e4-0251cc73ae13, clientIf=6
D/BluetoothLeAdvertiser( 3714): onClientRegistered() - status=0 clientIf=6
D/BtGatt.AdvertiseManager( 2187): message : 0
,D/BtGatt.AdvertiseManager( 2187): starting multi advertising
,D/BtGatt.GattService( 2187): onAdvertiseInstanceEnabled() - clientIf=6, status=0
,D/BtGatt.GattService( 2187): onAdvertiseDataSet() - clientIf=6, status=0
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3714): setState: State changed from NOT_STARTED to STARTING
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3714): start: Already running
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3714): start: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): startBlePeerDiscoverer: OK
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3714): start: Already running, call stopListening() first to restart
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3714): onStartSuccess
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3714): setState: State changed from STARTING to RUNNING
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 3714): stopProvideBluetoothMacAddressMode,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3714): onIsAdvertiserStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3714): updateState(): State changed from [NOT_STARTED] to [SCANNING, ADVERTISING_SELF]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onIsBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING_SELF]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3714): stop
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3714): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 3714): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3714): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3714): onStartSuccess
I/wpa_supplicant( 1149): P2P-FIND-STOPPED 
,D/BtGatt.AdvertiseManager( 2187): message : 1
D/BtGatt.AdvertiseManager( 2187): stop advertise for client 6
D/BtGatt.GattService( 2187): onAdvertiseInstanceDisabled() - clientIf=6, status=0
D/BtGatt.GattService( 2187): Client app is not null!
D/BtGatt.GattService( 2187): unregisterClient() - clientIf=6
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3714): stop: Stopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3714): setState: State changed from RUNNING to NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3714): onIsAdvertiserStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3714): updateState(): State changed from [SCANNING, ADVERTISING_SELF] to [SCANNING]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onIsBlePeerDiscovererStateChanged: [SCANNING]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3714): setState: State changed from NOT_STARTED to RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3714): onIsAdvertiserStartedChanged: true
D/BtGatt.GattService( 2187): stopScan() - queue size =1
D/BtGatt.GattService( 2187): unregisterClient() - clientIf=5
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3714): stop: Stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3714): setState: State changed from STARTING to NOT_STARTED,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3714): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3714): updateState(): State changed from [SCANNING] to [ADVERTISING_SELF]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onIsBlePeerDiscovererStateChanged: [ADVERTISING_SELF]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): setState: RESTARTING
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): stopBlePeerDiscoverer: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3714): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): setState: NOT_INITIALIZED
D/BtGatt.GattService( 2187): onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16,
D/BtGatt.ScanManager( 2187): callback done for clientIf - 5 status - 0
D/BtGatt.ScanManager( 2187): stop scan
D/BtGatt.ScanManager( 2187): configureRegularScanParams() - queue=0
,D/BtGatt.ScanManager( 2187): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager( 2187): configureRegularScanParams() - queue emtpy, scan stopped
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): stopWifiPeerDiscovery: Stopped,
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3714): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3714): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3714): clear
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3714): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3714): Local services cleared successfully
I/jxcore-log( 3714): ok 69 Should be able to call stopBroadcasting without error
,I/jxcore-log( 3714): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3714): Service requests cleared successfully
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3714): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3714): 	Connection timeout in milliseconds: 15000, 
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3714): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3714): 	Maximum number of connection attempt retries: 0
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): 	Bluetooth MAC address: F8:CF:C5:D9:E5:61, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): 	Discovery mode: BLE_AND_WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): 	Scan mode: 1
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1605be29 added. We now have 10 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): setDiscoveryMode: BLE_AND_WIFI -> WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onDiscoveryModeChanged: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onDiscoveryModeChanged: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onDiscoveryModeChanged: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onDiscoveryModeChanged: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onDiscoveryModeChanged: Mode set to WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onDiscoveryModeChanged: Mode set to WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onDiscoveryModeChanged: Mode set to WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onDiscoveryModeChanged: Mode set to WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onDiscoveryModeChanged: Mode set to WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onDiscoveryModeChanged: Mode set to WIFI
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0,
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3714): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454983782848.3714
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3714): bind: Binding a new listener
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3714): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3714): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454983782848.3714","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3714): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3714): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3714): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3714): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper( 3714): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3714): start: OK
,I/io.jxcore.node.ConnectionHelper( 3714): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3714): getBluetoothService() called with no BluetoothManagerCallback
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454983782848.3714, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3714): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3714): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3714): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onWifiStateChanged: State changed to 2
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3714): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454983782848.3714","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3714): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454983782848.3714","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3714): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1454983782848.3714","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): setState: INITIALIZED,
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onIsWifiPeerDiscoveryStartedChanged: true
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3714): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): start: OK
I/io.jxcore.node.ConnectionHelper( 3714): start: OK
I/wpa_supplicant( 1149): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454983782848.3714, mode: WIFI
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/jxcore-log( 3714): ok 70 Should be able to call startBroadcasting without error
I/jxcore-log( 3714): 
,I/io.jxcore.node.ConnectionHelper( 3714): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3714): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3714): Shutting down...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3714): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3714): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3714): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3714): onServerStopped
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3714): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3714): Local service added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): setState: RESTARTING
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3714): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3714): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 3714): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3714): stop: Stopping services
I/io.jxcore.node.ConnectionHelper( 3714): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3714): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onIsWifiPeerDiscoveryStartedChanged: false
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3714): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3714): Local services cleared successfully
I/wpa_supplicant( 1149): P2P-FIND-STOPPED 
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3714): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): P2P device discovery stopped successfully
,I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3714): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): setState: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper( 3714): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3714): Service requests cleared successfully
I/jxcore-log( 3714): ok 71 Should be able to call stopBroadcasting without error
I/jxcore-log( 3714): 
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3714): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3714): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3714): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3714): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): 	Automate Bluetooth MAC address resolution: true, 
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): 	Bluetooth MAC address: F8:CF:C5:D9:E5:61, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): 	Advertise mode: 1, ,
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@391313e5 added. We now have 11 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): setDiscoveryMode: WIFI -> BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3714): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454983782929.3714
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3714): bind: Binding a new listener
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3714): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3714): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454983782929.3714","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3714): setConnectionTimeout: 15000
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3714): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3714): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3714): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3714): start: OK
I/io.jxcore.node.ConnectionHelper( 3714): start: Using peer discovery mode: BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 3714): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3714): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3714): Waiting for incoming connections...,
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454983782929.3714, mode: BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3714): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3714): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onWifiStateChanged: State changed to 2
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): constructBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3714): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3714): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3714): start
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3714): createAdvertiseData: From: 1454983782929.3714 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3714): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,D/BtGatt.GattService( 2187): registerClient() - UUID=8f978f28-7548-4972-8859-f5464720eaaa
,D/BtGatt.GattService( 2187): onClientRegistered() - UUID=8f978f28-7548-4972-8859-f5464720eaaa, clientIf=5
D/BluetoothLeScanner( 3714): onClientRegistered() - status=0 clientIf=5
D/BtGatt.GattService( 2187): start scan with filters
,D/BtGatt.ScanManager( 2187): handling starting scan
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3714): setState: State changed from NOT_STARTED to STARTING
,D/BtGatt.GattService( 2187): onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,D/BtGatt.ScanManager( 2187): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2187): onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,D/BtGatt.ScanManager( 2187): callback done for clientIf - 5 status - 0
D/BtGatt.ScanManager( 2187): configureRegularScanParams() - queue=1
D/BtGatt.ScanManager( 2187): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
,D/BtGatt.GattService( 2187): registerClient() - UUID=2727f3b1-0f84-4f92-a9be-ad933b62af58
,D/BtGatt.GattService( 2187): onClientRegistered() - UUID=2727f3b1-0f84-4f92-a9be-ad933b62af58, clientIf=6
D/BluetoothLeAdvertiser( 3714): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.AdvertiseManager( 2187): message : 0
,D/BtGatt.AdvertiseManager( 2187): starting multi advertising
,D/BtGatt.GattService( 2187): onAdvertiseInstanceEnabled() - clientIf=6, status=0
,D/BtGatt.GattService( 2187): onAdvertiseDataSet() - clientIf=6, status=0
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3714): setState: State changed from NOT_STARTED to STARTING
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): startBlePeerDiscoverer: OK
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3714): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454983782929.3714","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3714): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454983782929.3714","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3714): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1454983782929.3714","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onIsWifiPeerDiscoveryStartedChanged: true
,I/wpa_supplicant( 1149): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3714): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): start: OK
,I/io.jxcore.node.ConnectionHelper( 3714): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454983782929.3714, mode: BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3714): start
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3714): createAdvertiseData: From: 1454983782929.3714 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3714): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/jxcore-log( 3714): ok 72 Should be able to call startBroadcasting without error
I/jxcore-log( 3714): 
I/io.jxcore.node.ConnectionHelper( 3714): stop
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3714): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3714): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3714): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3714): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3714): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3714): onServerStopped
,D/BtGatt.AdvertiseManager( 2187): message : 1
D/BtGatt.AdvertiseManager( 2187): stop advertise for client 6
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3714): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3714): setState: NOT_STARTED
D/BtGatt.GattService( 2187): onAdvertiseInstanceDisabled() - clientIf=6, status=0
D/BtGatt.GattService( 2187): Client app is not null!
D/BtGatt.GattService( 2187): unregisterClient() - clientIf=6
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3714): stop: Stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3714): setState: State changed from STARTING to NOT_STARTED
,D/BtGatt.GattService( 2187): registerClient() - UUID=3b8409c9-4c73-4659-b9cf-a6da50da61cb
,D/BtGatt.GattService( 2187): onClientRegistered() - UUID=3b8409c9-4c73-4659-b9cf-a6da50da61cb, clientIf=6
,D/BluetoothLeAdvertiser( 3714): onClientRegistered() - status=0 clientIf=6
D/BtGatt.AdvertiseManager( 2187): message : 0
,D/BtGatt.AdvertiseManager( 2187): starting multi advertising
,D/BtGatt.GattService( 2187): onAdvertiseInstanceEnabled() - clientIf=6, status=0
,D/BtGatt.GattService( 2187): onAdvertiseDataSet() - clientIf=6, status=0
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3714): setState: State changed from NOT_STARTED to STARTING
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3714): start: Already running
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3714): start: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): startBlePeerDiscoverer: OK
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3714): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): startWifiPeerDiscovery: Wi-Fi Direct OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): start: OK
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3714): onStartSuccess
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3714): setState: State changed from STARTING to RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3714): onIsAdvertiserStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3714): updateState(): State changed from [NOT_STARTED] to [SCANNING, ADVERTISING_SELF]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onIsBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING_SELF]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): stop: Stopping peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3714): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 3714): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3714): stop
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 3714): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): setState: STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3714): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3714): onStartSuccess
I/wpa_supplicant( 1149): P2P-FIND-STOPPED 
D/BtGatt.AdvertiseManager( 2187): message : 1
D/BtGatt.AdvertiseManager( 2187): stop advertise for client 6
D/BtGatt.GattService( 2187): onAdvertiseInstanceDisabled() - clientIf=6, status=0
,D/BtGatt.GattService( 2187): Client app is not null!
D/BtGatt.GattService( 2187): unregisterClient() - clientIf=6
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3714): stop: Stopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3714): setState: State changed from RUNNING to NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3714): onIsAdvertiserStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3714): updateState(): State changed from [SCANNING, ADVERTISING_SELF] to [SCANNING]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onIsBlePeerDiscovererStateChanged: [SCANNING]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3714): setState: State changed from NOT_STARTED to RUNNING,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3714): onIsAdvertiserStartedChanged: true
D/BtGatt.GattService( 2187): stopScan() - queue size =1
D/BtGatt.GattService( 2187): unregisterClient() - clientIf=5
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3714): stop: Stopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3714): setState: State changed from STARTING to NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3714): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3714): updateState(): State changed from [SCANNING] to [ADVERTISING_SELF]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onIsBlePeerDiscovererStateChanged: [ADVERTISING_SELF]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): stopBlePeerDiscoverer: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3714): stop: Stopping services
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): setState: RESTARTING
D/BtGatt.GattService( 2187): onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
D/BtGatt.ScanManager( 2187): callback done for clientIf - 5 status - 0
D/BtGatt.ScanManager( 2187): stop scan
D/BtGatt.ScanManager( 2187): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager( 2187): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager( 2187): configureRegularScanParams() - queue emtpy, scan stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3714): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3714): Local services cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3714): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3714): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3714): onDiscoveryManagerStateChanged: NOT_STARTED
,I/jxcore-log( 3714): ok 73 Should be able to call stopBroadcasting without error
I/jxcore-log( 3714): 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3714): Service requests cleared successfully
,I/jxcore-log( 3714): # setup
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): # ThaliEmitter calls startBroadcasting twice with error
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): # teardown
I/jxcore-log( 3714): 
,V/GoogleAuthProtoRequest( 3778): [403] a.<init>: mAccountName set to: thalitester@gmail.com
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3714): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3714): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3714): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3714): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): 	Bluetooth MAC address: F8:CF:C5:D9:E5:61, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): 	Discovery mode: BLE_AND_WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@193c4947 added. We now have 12 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): setDiscoveryMode: BLE_AND_WIFI -> WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onDiscoveryModeChanged: Mode set to WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onDiscoveryModeChanged: Mode set to WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onDiscoveryModeChanged: Mode set to WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onDiscoveryModeChanged: Mode set to WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onDiscoveryModeChanged: Mode set to WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onDiscoveryModeChanged: Mode set to WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onDiscoveryModeChanged: Mode set to WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onDiscoveryModeChanged: Mode set to WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onDiscoveryModeChanged: Mode set to WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onDiscoveryModeChanged: Mode set to WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onDiscoveryModeChanged: Mode set to WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onDiscoveryModeChanged: Mode set to WIFI
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3714): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454983783220.3714
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3714): bind: Binding a new listener
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3714): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3714): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454983783220.3714","ra":"F8:CF:C5:D9:E5:61"},
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3714): setConnectionTimeout: 15000,
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3714): startListeningForIncomingConnections
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3714): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3714): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3714): start: OK
,I/io.jxcore.node.ConnectionHelper( 3714): start: Using peer discovery mode: WIFI
I/io.jxcore.node.ConnectionHelper( 3714): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454983783220.3714, mode: WIFI
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3714): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3714): bind: Binding a new listener
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
W/BluetoothAdapter( 3714): getBluetoothService() called with no BluetoothManagerCallback
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onWifiStateChanged: State changed to 2,
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3714): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3714): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454983783220.3714","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3714): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454983783220.3714","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3714): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1454983783220.3714","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): setState: INITIALIZED,
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3714): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): setState: RUNNING_WIFI,
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): start: OK
I/io.jxcore.node.ConnectionHelper( 3714): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454983783220.3714, mode: WIFI
I/wpa_supplicant( 1149): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/jxcore-log( 3714): ok 74 Should be able to call startBroadcasting without error,
I/jxcore-log( 3714): 
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3714): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): start: OK
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): setState: RESTARTING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3714): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 3714): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/wpa_supplicant( 1149): P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): P2P device discovery stopped successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): setState: RESTARTING
,I/jxcore-log( 3714): ok 75 Cannot call startBroadcasting twice
I/jxcore-log( 3714): 
I/io.jxcore.node.ConnectionHelper( 3714): stop
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3714): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3714): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3714): stopListeningForIncomingConnections: Stopping...
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3714): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3714): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3714): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3714): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3714): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3714): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): stopForRestart
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 3714): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3714): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3714): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3714): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): P2P device discovery stopped successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3714): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3714): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3714): clear
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): setState: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper( 3714): onDiscoveryManagerStateChanged: NOT_STARTED
,I/jxcore-log( 3714): ok 76 Should be able to call stopBroadcasting without error
I/jxcore-log( 3714): 
,I/GLSUser ( 1259): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1259): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1259): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1259): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/jxcore-log( 3714): # setup
I/jxcore-log( 3714): 
,W/ExperimentUpdateService( 3778): [403] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3778): [403] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3778): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3778): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3778): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3778): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3778): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3778): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3778): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3778): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3778): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3778): 	at com.a.a.k.run(SourceFile:110)
,I/jxcore-log( 3714): # ThaliEmitter throws on connection to bad peer
I/jxcore-log( 3714): 
,I/jxcore-log( 3714): # teardown
I/jxcore-log( 3714): 
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3714): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3714): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3714): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3714): 	Maximum number of connection attempt retries: 0
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): 	Bluetooth MAC address: F8:CF:C5:D9:E5:61, ,
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): 	Advertise mode: 1, 
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@256a32e3 added. We now have 13 listener(s)
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3714): setDiscoveryMode: WIFI -> BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3714): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454983783402.3714,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3714): bind: Binding a new listener
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3714): initialize: My bluetooth address is F8:CF:C5:D9:E5:61,
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3714): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454983783402.3714","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3714): setConnectionTimeout: 15000,
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3714): startListeningForIncomingConnections
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3714): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3714): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3714): start: OK
I/io.jxcore.node.ConnectionHelper( 3714): start: Using peer discovery mode: BLE_AND_WIFI
,I/io.jxcore.node.ConnectionHelper( 3714): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3714): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454983783402.3714, mode: BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3714): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3714): bind: Binding a new listener,
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3714): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): constructBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3714): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3714): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3714): start
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3714): createAdvertiseData: From: 1454983783402.3714 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3714): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,D/BtGatt.GattService( 2187): registerClient() - UUID=620eae9a-e6fc-4818-8cd1-fc9da8fcf15c
,D/BtGatt.GattService( 2187): onClientRegistered() - UUID=620eae9a-e6fc-4818-8cd1-fc9da8fcf15c, clientIf=5
,D/BluetoothLeScanner( 3714): onClientRegistered() - status=0 clientIf=5
,D/BtGatt.GattService( 2187): start scan with filters
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3714): setState: State changed from NOT_STARTED to STARTING
D/BtGatt.ScanManager( 2187): handling starting scan,
,D/BtGatt.GattService( 2187): registerClient() - UUID=c1e83af9-1af5-414b-a845-662b3ef4422f,
,D/BtGatt.GattService( 2187): onClientRegistered() - UUID=c1e83af9-1af5-414b-a845-662b3ef4422f, clientIf=6
,D/BtGatt.GattService( 2187): onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,D/BtGatt.ScanManager( 2187): callback done for clientIf - 5 status - 0
,D/BluetoothLeAdvertiser( 3714): onClientRegistered() - status=0 clientIf=6
D/BtGatt.GattService( 2187): onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,D/BtGatt.ScanManager( 2187): callback done for clientIf - 5 status - 0
D/BtGatt.AdvertiseManager( 2187): message : 0
D/BtGatt.ScanManager( 2187): configureRegularScanParams() - queue=1
,D/BtGatt.ScanManager( 2187): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
,D/BtGatt.AdvertiseManager( 2187): starting multi advertising
,D/BtGatt.GattService( 2187): onAdvertiseInstanceEnabled() - clientIf=6, status=0
,D/BtGatt.GattService( 2187): onAdvertiseDataSet() - clientIf=6, status=0
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3714): setState: State changed from NOT_STARTED to STARTING
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): startBlePeerDiscoverer: OK
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3714): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454983783402.3714","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3714): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454983783402.3714","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3714): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1454983783402.3714","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3714): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3714): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): start: OK
I/wpa_supplicant( 1149): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454983783402.3714, mode: BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3714): start
I/io.jxcore.node.ConnectionHelper( 3714): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3714): createAdvertiseData: From: 1454983783402.3714 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3714): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,D/BtGatt.AdvertiseManager( 2187): message : 1
D/BtGatt.AdvertiseManager( 2187): stop advertise for client 6
,I/jxcore-log( 3714): ok 77 Should be able to call startBroadcasting without error
I/jxcore-log( 3714): 
D/BtGatt.GattService( 2187): onAdvertiseInstanceDisabled() - clientIf=6, status=0
D/BtGatt.GattService( 2187): Client app is not null!
I/io.jxcore.node.ConnectionHelper( 3714): connect: Trying to connect to peer with ID foobar
,W/io.jxcore.node.ConnectionHelper( 3714): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
D/BtGatt.GattService( 2187): unregisterClient() - clientIf=6
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3714): stop: Stopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3714): setState: State changed from STARTING to NOT_STARTED
E/io.jxcore.node.ConnectionHelper( 3714): connect: Invalid Bluetooth address: foobar
,D/BtGatt.GattService( 2187): registerClient() - UUID=e2e33316-57ae-4258-861e-fd2abe93a5b9
,D/BtGatt.GattService( 2187): onClientRegistered() - UUID=e2e33316-57ae-4258-861e-fd2abe93a5b9, clientIf=6
D/BluetoothLeAdvertiser( 3714): onClientRegistered() - status=0 clientIf=6
I/jxcore-log( 3714): ok 78 Should not connect to a bad peer
I/jxcore-log( 3714): 
,D/BtGatt.AdvertiseManager( 2187): message : 0
,I/io.jxcore.node.ConnectionHelper( 3714): stop
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3714): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3714): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3714): stopListeningForIncomingConnections: Stopping...
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3714): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3714): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3714): setState: NOT_STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3714): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3714): onServerStopped
D/BtGatt.AdvertiseManager( 2187): starting multi advertising
,D/BtGatt.GattService( 2187): onAdvertiseInstanceEnabled() - clientIf=6, status=0
,D/BtGatt.GattService( 2187): onAdvertiseDataSet() - clientIf=6, status=0
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3714): setState: State changed from NOT_STARTED to STARTING
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3714): start: Already running
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3714): start: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): startBlePeerDiscoverer: OK
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3714): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): start: OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3714): stopForRestart
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3714): onStartSuccess
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 3714): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3714): stop
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3714): setState: State changed from STARTING to RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3714): onIsAdvertiserStartedChanged: true
,D/btif_config_util( 2187): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/HeadsetStateMachine( 2187): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2187): Disconnected process message: 10, size: 0
,I/wpa_supplicant( 1149): P2P-DEVICE-FOUND dc:4a:3e:0f:c2:f1 p2p_dev_addr=de:4a:3e:0f:89:ad pri_dev_type=3-0050F204-1 name='DIRECT-AD-HP DeskJet 3630 series' config_methods=0x5a88 dev_capab=0x4 group_capab=0x1 vendor_elems=1
,I/GLSUser ( 1259): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1259): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1259): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1259): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3228): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3228): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3228): 	at jdm.a(PG:82)
E/HttpOperation( 3228): 	at jcs.o(PG:406)
E/HttpOperation( 3228): 	at jcn.a(PG:1379)
E/HttpOperation( 3228): 	at jcs.i(PG:143)
E/HttpOperation( 3228): 	at blb.a(PG:3937)
E/HttpOperation( 3228): 	at czp.a(PG:18188)
E/HttpOperation( 3228): 	at czp.a(PG:9081)
E/HttpOperation( 3228): 	at czq.run(PG:1686)
E/HttpOperation( 3228): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3228): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3228): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3228): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3228): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3228): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3228): 	at jdj.a(PG:4091)
E/HttpOperation( 3228): 	at jdj.a(PG:1125)
E/HttpOperation( 3228): 	at jdm.a(PG:77)
E/HttpOperation( 3228): 	... 12 more
E/HttpOperation( 3228): Caused by: faj: BadAuthentication
E/HttpOperation( 3228): 	at fal.a(PG:38)
E/HttpOperation( 3228): 	at jdj.a(PG:4089)
E/HttpOperation( 3228): 	... 14 more
,I/GLSUser ( 1259): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1259): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1259): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1259): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3228): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3228): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3228): 	at jdm.a(PG:82)
E/HttpOperation( 3228): 	at jcs.o(PG:406)
E/HttpOperation( 3228): 	at jcn.a(PG:1379)
E/HttpOperation( 3228): 	at jcs.i(PG:143)
E/HttpOperation( 3228): 	at hec.a(PG:42)
E/HttpOperation( 3228): 	at hee.a(PG:102)
E/HttpOperation( 3228): 	at czr.a(PG:65)
E/HttpOperation( 3228): 	at kka.a(PG:108)
E/HttpOperation( 3228): 	at czp.a(PG:19176)
E/HttpOperation( 3228): 	at czp.a(PG:9081)
E/HttpOperation( 3228): 	at czq.run(PG:1686)
E/HttpOperation( 3228): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3228): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3228): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3228): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3228): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3228): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3228): 	at jdj.a(PG:4091)
E/HttpOperation( 3228): 	at jdj.a(PG:1125)
E/HttpOperation( 3228): 	at jdm.a(PG:77)
E/HttpOperation( 3228): 	... 15 more
E/HttpOperation( 3228): Caused by: faj: BadAuthentication
E/HttpOperation( 3228): 	at fal.a(PG:38)
E/HttpOperation( 3228): 	at jdj.a(PG:4089)
E/HttpOperation( 3228): 	... 17 more
E/ExperimentLoader( 3228): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3228): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3228): 	at jdm.a(PG:82)
E/ExperimentLoader( 3228): 	at jcs.o(PG:406)
E/ExperimentLoader( 3228): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3228): 	at jcs.i(PG:143)
E/ExperimentLoader( 3228): 	at hec.a(PG:42)
E/ExperimentLoader( 3228): 	at hee.a(PG:102)
E/ExperimentLoader( 3228): 	at czr.a(PG:65)
E/ExperimentLoader( 3228): 	at kka.a(PG:108)
E/ExperimentLoader( 3228): 	at czp.a(PG:19176)
E/ExperimentLoader( 3228): 	at czp.a(PG:9081)
E/ExperimentLoader( 3228): 	at czq.run(PG:1686)
E/ExperimentLoader( 3228): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3228): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3228): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3228): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3228): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3228): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3228): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3228): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3228): 	at jdm.a(PG:77)
E/ExperimentLoader( 3228): 	... 15 more
E/ExperimentLoader( 3228): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3228): 	at fal.a(PG:38)
E/ExperimentLoader( 3228): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3228): 	... 17 more
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 357415, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1259): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1259): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1259): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1259): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1259): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1259): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1259): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1259): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1259): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1259): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1259): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 3505): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3505): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3505): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 3505): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3505): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/PlayEventLogger( 3505): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3505): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 3505): Ignoring header User-Agent because its value was null.
,D/HeadsetStateMachine( 2187): Disconnected process message: 10, size: 0
,D/WifiService(  821): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@2fd4ccb3}
,E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-54
,D/HeadsetStateMachine( 2187): Disconnected process message: 10, size: 0
,D/WifiService(  821): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@2fd4ccb3}
,I/art     (  821): Explicit concurrent mark sweep GC freed 36910(1851KB) AllocSpace objects, 10(725KB) LOS objects, 31% free, 34MB/50MB, paused 2.854ms total 97.070ms
,I/BooksSync( 4040): Starting books sync for 61035162, extras: ade
,V/KeepSync( 3957): Connecting to GoogleApiClient
,I/BooksConfig( 4040): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1259): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1259): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1259): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1259): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1259): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1259): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1259): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1259): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1259): Explicit concurrent mark sweep GC freed 55716(3MB) AllocSpace objects, 11(1137KB) LOS objects, 36% free, 27MB/43MB, paused 1.401ms total 83.554ms
,E/ClientConnectionOperation( 1774): Handling authorization failure
E/ClientConnectionOperation( 1774): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1774): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1774): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1774): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1774): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1774): 	... 7 more
,V/KeepSync( 3957): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3957): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3957): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3957): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1259): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1259): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1259): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1259): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 4040): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 4040): Soft error
E/BooksSync( 4040): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4040): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 4040): Sync error
E/BooksSync( 4040): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4040): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 4040): Finished books sync
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 380478, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1259): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1259): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1259): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1259): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3957): IOException
E/KeepSync( 3957): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3957): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3957): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3957): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3957): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3957): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3957): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3957): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3957): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3957): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3957): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3957): 	,at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3957): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3957): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3957): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3957): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3957): 	... 10 more
W/KeepSync( 3957): Sync result 2
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 386296, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/wpa_supplicant( 1149): P2P-FIND-STOPPED 
,E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::injectLocation(GpsExtLocation):857]: error! inject position failed
,I/wpa_supplicant( 1149): P2P-DEVICE-LOST p2p_dev_addr=de:4a:3e:0f:89:ad
,D/HeadsetStateMachine( 2187): Disconnected process message: 10, size: 0
,V/GoogleAuthProtoRequest( 3778): [404] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1259): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1259): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1259): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1259): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3778): [404] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3778): [404] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3778): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3778): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3778): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3778): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3778): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3778): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3778): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3778): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3778): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3778): 	at com.a.a.k.run(SourceFile:110)
,D/HeadsetStateMachine( 2187): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2187): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2187): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2187): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2187): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2187): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2187): Disconnected process message: 10, size: 0
,I/GLSUser ( 1259): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1259): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1259): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1259): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3228): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3228): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3228): 	at jdm.a(PG:82)
E/HttpOperation( 3228): 	at jcs.o(PG:406)
E/HttpOperation( 3228): 	at jcn.a(PG:1379)
E/HttpOperation( 3228): 	at jcs.i(PG:143)
E/HttpOperation( 3228): 	at blb.a(PG:3937)
E/HttpOperation( 3228): 	at czp.a(PG:18188)
E/HttpOperation( 3228): 	at czp.a(PG:9081)
E/HttpOperation( 3228): 	at czq.run(PG:1686)
E/HttpOperation( 3228): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3228): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3228): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3228): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3228): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3228): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3228): 	at jdj.a(PG:4091)
E/HttpOperation( 3228): 	at jdj.a(PG:1125)
E/HttpOperation( 3228): 	at jdm.a(PG:77)
E/HttpOperation( 3228): 	... 12 more
E/HttpOperation( 3228): Caused by: faj: BadAuthentication
E/HttpOperation( 3228): 	at fal.a(PG:38)
E/HttpOperation( 3228): 	at jdj.a(PG:4089)
E/HttpOperation( 3228): 	... 14 more
,I/GLSUser ( 1259): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1259): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1259): [GLSUser] Extracting token using key: Auth,
W/GLSActivity( 1259): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3228): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3228): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3228): 	at jdm.a(PG:82)
E/HttpOperation( 3228): 	at jcs.o(PG:406)
E/HttpOperation( 3228): 	at jcn.a(PG:1379)
E/HttpOperation( 3228): 	at jcs.i(PG:143)
E/HttpOperation( 3228): 	at hec.a(PG:42)
E/HttpOperation( 3228): 	at hee.a(PG:102)
E/HttpOperation( 3228): 	at czr.a(PG:65)
E/HttpOperation( 3228): 	at kka.a(PG:108)
E/HttpOperation( 3228): 	at czp.a(PG:19176)
E/HttpOperation( 3228): 	at czp.a(PG:9081)
E/HttpOperation( 3228): 	at czq.run(PG:1686)
E/HttpOperation( 3228): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3228): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3228): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3228): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3228): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3228): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3228): 	at jdj.a(PG:4091)
E/HttpOperation( 3228): 	at jdj.a(PG:1125)
E/HttpOperation( 3228): 	at jdm.a(PG:77)
E/HttpOperation( 3228): 	... 15 more
E/HttpOperation( 3228): Caused by: faj: BadAuthentication
E/HttpOperation( 3228): 	at fal.a(PG:38)
E/HttpOperation( 3228): 	at jdj.a(PG:4089)
E/HttpOperation( 3228): 	... 17 more
E/ExperimentLoader( 3228): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3228): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3228): 	at jdm.a(PG:82)
E/ExperimentLoader( 3228): 	at jcs.o(PG:406)
E/ExperimentLoader( 3228): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3228): 	at jcs.i(PG:143)
E/ExperimentLoader( 3228): 	at hec.a(PG:42)
E/ExperimentLoader( 3228): 	at hee.a(PG:102)
E/ExperimentLoader( 3228): 	at czr.a(PG:65)
E/ExperimentLoader( 3228): 	at kka.a(PG:108)
E/ExperimentLoader( 3228): 	at czp.a(PG:19176)
E/ExperimentLoader( 3228): 	at czp.a(PG:9081)
E/ExperimentLoader( 3228): 	at czq.run(PG:1686)
E/ExperimentLoader( 3228): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3228): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3228): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3228): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3228): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3228): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3228): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3228): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3228): 	at jdm.a(PG:77)
E/ExperimentLoader( 3228): 	... 15 more
E/ExperimentLoader( 3228): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3228): 	at fal.a(PG:38)
E/ExperimentLoader( 3228): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3228): 	... 17 more
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 620341, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/BooksSync( 4040): Starting books sync for 61035162, extras: ade
,V/KeepSync( 3957): Connecting to GoogleApiClient
,I/BooksConfig( 4040): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1259): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1259): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1259): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1259): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1259): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1259): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1259): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1259): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1774): Handling authorization failure
E/ClientConnectionOperation( 1774): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1774): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1774): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1774): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1774): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1774): 	... 7 more
,V/KeepSync( 3957): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3957): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3957): (284) automatic index on blob_node(is_deleted),
E/SQLiteLog( 3957): (284) automatic index on blob_node(is_deleted)
,I/art     (  821): Explicit concurrent mark sweep GC freed 32570(1440KB) AllocSpace objects, 9(426KB) LOS objects, 31% free, 34MB/50MB, paused 1.482ms total 80.011ms
,I/GLSUser ( 1259): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1259): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1259): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1259): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 4040): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 4040): Soft error
E/BooksSync( 4040): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4040): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 4040): Sync error
E/BooksSync( 4040): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4040): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 4040): Finished books sync
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 636906, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1259): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1259): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1259): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1259): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3957): IOException
E/KeepSync( 3957): com.google.android.apiary.AuthenticationException: Could not get an auth token
,E/KeepSync( 3957): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3957): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3957): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3957): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3957): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
,E/KeepSync( 3957): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3957): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3957): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3957): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3957): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3957): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259),
E/KeepSync( 3957): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3957): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3957): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3957): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3957): 	... 10 more
W/KeepSync( 3957): Sync result 2
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 648526, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2187): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2187): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2187): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2187): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2187): Disconnected process message: 10, size: 0
,V/GoogleAuthProtoRequest( 3778): [405] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1259): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1259): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1259): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1259): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3778): [405] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3778): [405] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3778): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3778): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3778): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3778): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3778): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3778): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3778): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3778): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3778): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3778): 	at com.a.a.k.run(SourceFile:110)
,D/HeadsetStateMachine( 2187): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2187): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2187): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2187): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2187): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2187): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2187): Disconnected process message: 10, size: 0
,I/EventLogService( 1774): Opted in for usage reporting
,I/EventLogService( 1774): Aggregate from 1454982742105 (log), 1454982742105 (data)
,I/art     ( 1259): Explicit concurrent mark sweep GC freed 66067(3MB) AllocSpace objects, 15(1654KB) LOS objects, 36% free, 27MB/43MB, paused 1.621ms total 51.923ms
,D/GCM     ( 1259): Message class com.google.f.a.a.i
,W/EventLogAggregator( 1774): Unknown tag: snet_gcore
,W/EventLogAggregator( 1774): Unknown tag: snet_launch_service
,I/ServiceDumpSys( 1774): dumping service [account]
,D/HeadsetStateMachine( 2187): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2187): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2187): Disconnected process message: 10, size: 0
,I/art     ( 1801): Explicit concurrent mark sweep GC freed 16472(1020KB) AllocSpace objects, 8(128KB) LOS objects, 37% free, 26MB/42MB, paused 1.788ms total 76.204ms
,I/GLSUser ( 1259): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1259): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1259): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1259): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
E/DataBuffer( 1801): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@19faed09)
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3228): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3228): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3228): 	at jdm.a(PG:82)
E/HttpOperation( 3228): 	at jcs.o(PG:406)
E/HttpOperation( 3228): 	at jcn.a(PG:1379)
E/HttpOperation( 3228): 	at jcs.i(PG:143)
E/HttpOperation( 3228): 	at blb.a(PG:3937)
E/HttpOperation( 3228): 	at czp.a(PG:18188)
E/HttpOperation( 3228): 	at czp.a(PG:9081)
E/HttpOperation( 3228): 	at czq.run(PG:1686)
E/HttpOperation( 3228): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3228): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3228): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3228): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3228): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3228): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3228): 	at jdj.a(PG:4091)
E/HttpOperation( 3228): 	at jdj.a(PG:1125)
E/HttpOperation( 3228): 	at jdm.a(PG:77)
E/HttpOperation( 3228): 	... 12 more
E/HttpOperation( 3228): Caused by: faj: BadAuthentication
E/HttpOperation( 3228): 	at fal.a(PG:38)
E/HttpOperation( 3228): 	at jdj.a(PG:4089)
E/HttpOperation( 3228): 	... 14 more
,I/GLSUser ( 1259): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1259): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1259): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1259): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3228): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3228): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3228): 	at jdm.a(PG:82)
E/HttpOperation( 3228): 	at jcs.o(PG:406)
E/HttpOperation( 3228): 	at jcn.a(PG:1379)
E/HttpOperation( 3228): 	at jcs.i(PG:143)
E/HttpOperation( 3228): 	at hec.a(PG:42)
E/HttpOperation( 3228): 	at hee.a(PG:102)
E/HttpOperation( 3228): 	at czr.a(PG:65)
E/HttpOperation( 3228): 	at kka.a(PG:108)
E/HttpOperation( 3228): 	at czp.a(PG:19176)
E/HttpOperation( 3228): 	at czp.a(PG:9081)
E/HttpOperation( 3228): 	at czq.run(PG:1686)
E/HttpOperation( 3228): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3228): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3228): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3228): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3228): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3228): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3228): 	at jdj.a(PG:4091)
E/HttpOperation( 3228): 	at jdj.a(PG:1125)
E/HttpOperation( 3228): 	at jdm.a(PG:77)
E/HttpOperation( 3228): 	... 15 more
E/HttpOperation( 3228): Caused by: faj: BadAuthentication
E/HttpOperation( 3228): 	at fal.a(PG:38)
E/HttpOperation( 3228): 	at jdj.a(PG:4089)
E/HttpOperation( 3228): 	... 17 more
E/ExperimentLoader( 3228): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3228): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3228): 	at jdm.a(PG:82)
E/ExperimentLoader( 3228): 	at jcs.o(PG:406)
E/ExperimentLoader( 3228): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3228): 	at jcs.i(PG:143)
E/ExperimentLoader( 3228): 	at hec.a(PG:42)
E/ExperimentLoader( 3228): 	at hee.a(PG:102)
E/ExperimentLoader( 3228): 	at czr.a(PG:65)
E/ExperimentLoader( 3228): 	at kka.a(PG:108)
E/ExperimentLoader( 3228): 	at czp.a(PG:19176)
E/ExperimentLoader( 3228): 	at czp.a(PG:9081)
E/ExperimentLoader( 3228): 	at czq.run(PG:1686)
E/ExperimentLoader( 3228): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3228): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3228): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3228): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3228): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3228): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3228): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3228): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3228): 	at jdm.a(PG:77)
E/ExperimentLoader( 3228): 	... 15 more
E/ExperimentLoader( 3228): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3228): 	at fal.a(PG:38)
E/ExperimentLoader( 3228): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3228): 	... 17 more
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 1145635, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/BooksSync( 4040): Starting books sync for 61035162, extras: ade
,V/KeepSync( 3957): Connecting to GoogleApiClient
,I/BooksConfig( 4040): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1259): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1259): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1259): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1259): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1259): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1259): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1259): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1259): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1774): Handling authorization failure
E/ClientConnectionOperation( 1774): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1774): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1774): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1774): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1774): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1774): 	... 7 more
,V/KeepSync( 3957): GoogleApiClient failed to connect with error code: 4
E/SQLiteLog( 3957): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3957): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3957): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1259): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1259): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1259): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1259): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  821): Explicit concurrent mark sweep GC freed 42363(2006KB) AllocSpace objects, 10(442KB) LOS objects, 31% free, 34MB/50MB, paused 1.599ms total 68.401ms
,E/BooksAccountManager( 4040): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4040): Soft error
E/BooksSync( 4040): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4040): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 4040): Sync error
E/BooksSync( 4040): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4040): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 4040): Finished books sync
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1148830, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1259): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1259): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1259): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1259): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3957): IOException,
E/KeepSync( 3957): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3957): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3957): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89),
E/KeepSync( 3957): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3957): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3957): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3957): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3957): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3957): ,	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3957): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3957): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3957): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3957): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3957): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3957): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3957): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3957): 	... 10 more
,W/KeepSync( 3957): Sync result 2
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 1171934, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,W/bt-btm  ( 2187): Request to stop oneshot timer with non empty queue
,I/UsageStatsService(  821): User[0] Flushing usage stats to disk
,D/HeadsetStateMachine( 2187): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2187): Disconnected process message: 10, size: 0
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 4386): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 4386): CheckJNI is OFF
D/AndroidRuntime( 4386): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  821): Force stopping com.test.thalitest appid=10265 user=-1: uninstall pkg
I/ActivityManager(  821): Killing 3714:com.test.thalitest/u0a265 (adj 0): stop com.test.thalitest
W/PackageSettings(  821): Skipping PackageSetting{394f094e com.example.hello/10273} due to missing metadata
E/JavaBinder( 2187): !!! FAILED BINDER TRANSACTION !!!
E/BtGatt.GattService( 2187): Exception: android.os.TransactionTooLargeException
D/BtGatt.GattService( 2187): Binder is dead - unregistering client (6)!
I/WindowState(  821): WIN DEATH: Window{e9092a9 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  821): Client connection lost with reason: 4
D/BtGatt.AdvertiseManager( 2187): message : 1
D/BtGatt.GattService( 2187): onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
D/BtGatt.ScanManager( 2187): callback done for clientIf - 5 status - 0
D/BtGatt.ScanManager( 2187): stop scan
D/BtGatt.AdvertiseManager( 2187): stop advertise for client 6
D/BtGatt.ScanManager( 2187): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager( 2187): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager( 2187): configureRegularScanParams() - queue emtpy, scan stopped
D/BtGatt.AdvertiseManager( 2187): app died - unregistering client : 6
D/BtGatt.GattService( 2187): unregisterClient() - clientIf=6
E/libprocessgroup(  821): failed to kill 1 processes for processgroup 3714
W/ActivityManager(  821): Force removing ActivityRecord{11cb3164 u0 com.test.thalitest/.MainActivity t28}: app died, no saved state
D/BtGatt.GattService( 2187): onAdvertiseInstanceDisabled() - clientIf=255, status=0
E/BtGatt.ContextMap( 2187): Context not found for ID 255
V/ActivityManager(  821): Display changed displayId=0
I/ActivityManager(  821): Force stopping com.test.thalitest appid=10265 user=0: pkg removed
W/ActivityManager(  821): Spurious death for ProcessRecord{3e4ece0b 3714:com.test.thalitest/u0a265}, curProc for 3714: null
D/TaskPersister(  821): removeObsoleteFile: deleting file=28_task.xml
I/InputReader(  821): Reconfiguring input devices.  changes=0x00000010
I/Keyboard.Facilitator( 1242): resetDictionaries() : en_US
D/BuaReceiver( 3396): ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
I/Keyboard.Facilitator.DecoderInitializer( 1242): run()
I/ActivityManager(  821): Start proc 4402:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
W/InputMethodManagerService(  821): Got RemoteException sending setActive(false) notification to pid 3714 uid 10265
I/art     ( 1071): Explicit concurrent mark sweep GC freed 71465(2MB) AllocSpace objects, 0(0B) LOS objects, 18% free, 71MB/87MB, paused 1.365ms total 56.437ms
I/Keyboard.Facilitator( 1242): onFinishInput()
I/Decoder ( 1242): createOrResetDecoder
I/art     ( 1525): Explicit concurrent mark sweep GC freed 3417(207KB) AllocSpace objects, 0(0B) LOS objects, 36% free, 27MB/43MB, paused 1.331ms total 91.508ms
I/art     (  821): Explicit concurrent mark sweep GC freed 18353(1208KB) AllocSpace objects, 10(348KB) LOS objects, 31% free, 34MB/50MB, paused 2.552ms total 87.688ms
I/art     (  821): WaitForGcToComplete blocked for 80.689ms for cause Explicit
I/art     ( 1360): Explicit concurrent mark sweep GC freed 4993(364KB) AllocSpace objects, 13(1519KB) LOS objects, 31% free, 35MB/51MB, paused 723us total 18.034ms
I/ConfigService( 1259): onCreate
I/Keyboard.Facilitator.MainLanguageModelLoader( 1242): run()
W/LocationOracleImpl( 1525): Best location was null
D/JobSchedulerService(  821): Receieved: android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  821): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/HotwordRecognitionRnr( 1525): Starting hotword detection.
I/MicrophoneInputStream( 1525): mic_starting com.google.android.apps.gsa.speech.audio.u@2f0dcb44
I/AudioFlinger(  356): AudioFlinger's thread 0xb4d4b000 ready to run
I/Keyboard.Facilitator.MainLanguageModelLoader( 1242): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1242): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1242): run() : Loading LM = contacts
I/SoundTriggerHwService::Module(  356): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1242): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1242): run() : Loading LM = history
I/MicrophoneInputStream( 1525): mic_started com.google.android.apps.gsa.speech.audio.u@2f0dcb44
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1242): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1242): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1242): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1242): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1242): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1242): run()
I/StatsUtilsManager( 1242): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1242): shouldRecordStats() = Too Soon
D/audio_hw_primary(  356): select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
D/msm8974_platform(  356): platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
E/ACDB-LOADER(  356): Error: ACDB AudProc vol returned = -19
D/audio_hw_primary(  356): enable_snd_device: snd_device(55: voice-rec-mic)
D/audio_hw_primary(  356): enable_audio_route: apply and update mixer path: audio-record
D/VoicemailCleanupService( 4402): Cleaning up data for package: com.test.thalitest
I/ActivityManager(  821): Start proc 4439:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
I/ContactLocale( 4402): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
D/WifiService(  821): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@f5f60b4}
E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=53.00 rxSuccessRate=62.25 targetRoamBSSID=any RSSI=-54
I/art     (  821): Explicit concurrent mark sweep GC freed 6862(325KB) AllocSpace objects, 0(0B) LOS objects, 31% free, 34MB/50MB, paused 1.619ms total 167.374ms
I/ActivityManager(  821): Start proc 4458:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
I/HotwordWorker( 1525): onReady
I/art     (  368): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 199us total 12.822ms
I/art     (  368): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 202us total 9.107ms
W/ContextImpl( 4458): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2609 
I/art     (  368): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 200us total 9.032ms
E/NetworkScheduler.SchedulerReceiver( 1259): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1259): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1660654867
E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
D/ChimeraCfgMgr( 1774): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1774): Module APK com.google.android.play.games already loaded
D/PackageBroadcastService( 1774): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1774): Clearing selected account for com.test.thalitest
I/ActivityManager(  821): Killing 3805:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
I/art     ( 4386): System.exit called, status: 0
I/AndroidRuntime( 4386): VM exiting with result code 0.
D/ChimeraCfgMgr( 1774): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1774): Module APK com.google.android.play.games already loaded
E/SQLiteLog( 1774): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
I/LocationSettingsChecker( 1774): Removing dialog suppression flag for package com.test.thalitest
E/SQLiteLog( 1774): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/DriveAsyncService( 1774): disk I/O error (code 3850)
E/DriveAsyncService( 1774): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 1774): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 1774): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/DriveAsyncService( 1774): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 1774): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 1774): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/DriveAsyncService( 1774): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/DriveAsyncService( 1774): 	at com.google.android.gms.drive.database.k.l(SourceFile:596)
E/DriveAsyncService( 1774): 	at com.google.android.gms.drive.database.k.b(SourceFile:570)
E/DriveAsyncService( 1774): 	at com.google.android.gms.drive.database.f.h(SourceFile:1473)
E/DriveAsyncService( 1774): 	at com.google.android.gms.drive.api.a.bc.a(SourceFile:16)
E/DriveAsyncService( 1774): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/DriveAsyncService( 1774): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 1774): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 1774): 	at java.lang.Thread.run(Thread.java:818)
D/Launcher.Workspace( 1360): 11683562 - stripEmptyScreens()
D/Launcher.Workspace( 1360): 11683562 - stripEmptyScreens()
I/UpdateIcingCorporaServi( 1525): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
--------- beginning of crash
E/AndroidRuntime( 1774): FATAL EXCEPTION: PlayGamesAsyncThread1
E/AndroidRuntime( 1774): Process: com.google.android.gms, PID: 1774
E/AndroidRuntime( 1774): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1774): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 1774): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/AndroidRuntime( 1774): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 1774): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 1774): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/AndroidRuntime( 1774): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:469)
E/AndroidRuntime( 1774): 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
E/AndroidRuntime( 1774): 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
E/AndroidRuntime( 1774): 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
E/AndroidRuntime( 1774): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
E/AndroidRuntime( 1774): 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
E/AndroidRuntime( 1774): 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3044)
E/AndroidRuntime( 1774): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
E/AndroidRuntime( 1774): 	at com.google.android.gms.games.service.PlayGamesAsyncService$OperationAdapter.execute(PlayGamesAsyncService.java:920)
E/AndroidRuntime( 1774): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
E/AndroidRuntime( 1774): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 1774): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 1774): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 1774): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 1774): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1774): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1774): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1774): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1774): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1774): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1774): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1774): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1774): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1774): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1774): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 1774): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 1774): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1774): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 1774): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 1774): 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
E/SQLiteDatabase( 1774): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 1774): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 1774): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1774): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1774): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 1774): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 1774): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 1774): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1774): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1774): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 1774): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 1774): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1774): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1774): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1774): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteOpenHelper( 1774): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteOpenHelper( 1774): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 1774): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteOpenHelper( 1774): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 1774): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 1774): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 1774): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 1774): 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
E/SQLiteOpenHelper( 1774): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 1774): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 1774): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 1774): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 1774): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteOpenHelper( 1774): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/SQLiteOpenHelper( 1774): Opened metrics.db in read-only mode
D/GOOGLEHELP_CompatibleDatabase( 1774): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1774): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
E/SQLiteLog( 1774): (8) statement aborts at 16: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
D/GOOGLEHELP_CompatibleDatabase( 1774): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
I/Process ( 1774): Sending signal. PID: 1774 SIG: 9
E/SQLiteLog( 1360): (3850) statement aborts at 24: [DELETE FROM shortcut_and_widget_previews WHERE name LIKE ? OR name LIKE ?] disk I/O error
E/SQLiteLog( 1525): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
I/ActivityManager(  821): Start proc 4492:com.google.android.gms.wearable/u0a11 for service com.google.android.gms/.wearable.service.WearableControlService
E/DropBoxManagerService(  821): Can't write: system_app_crash
E/DropBoxManagerService(  821): java.io.FileNotFoundException: /data/system/dropbox/drop98.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  821): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  821): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  821): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  821): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  821): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  821): 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
E/DropBoxManagerService(  821): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  821): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  821): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  821): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  821): 	... 5 more
E/SQLiteLog( 4402): (3850) statement aborts at 22: [DELETE FROM deleted_contacts WHERE contact_deleted_timestamp < ?] disk I/O error
E/AndroidRuntime( 4402): FATAL EXCEPTION: ContactsProviderWorker
E/AndroidRuntime( 4402): Process: android.process.acore, PID: 4402
E/AndroidRuntime( 4402): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4402): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 4402): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 4402): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 4402): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 4402): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/AndroidRuntime( 4402): 	at com.android.providers.contacts.database.DeletedContactsTableUtil.deleteOldLogs(DeletedContactsTableUtil.java:78)
E/AndroidRuntime( 4402): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1730)
E/AndroidRuntime( 4402): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1492)
E/AndroidRuntime( 4402): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4402): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 4402): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Launcher( 1360): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@1d4a10f5 new=com.google.android.velvet.VelvetApplication@1d4a10f5
E/SQLiteLog( 1360): (3850) statement aborts at 24: [DELETE FROM shortcut_and_widget_previews WHERE name LIKE ? OR name LIKE ?] disk I/O error
I/ActivityManager(  821): Start proc 4510:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
E/SharedPreferencesImpl( 1525): Couldn't create directory for SharedPreferences file /data/data/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml
E/AndroidRuntime( 1525): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 1525): Process: com.google.android.googlequicksearchbox:search, PID: 1525
E/AndroidRuntime( 1525): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1525): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 1525): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/AndroidRuntime( 1525): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 1525): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 1525): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/AndroidRuntime( 1525): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/AndroidRuntime( 1525): 	at com.google.android.apps.gsa.extradex.icingsync.b.a(ApplicationsHelperImpl.java:85)
E/AndroidRuntime( 1525): 	at com.google.android.search.core.icingsync.d.i(InternalIcingCorporaProvider.java:623)
E/AndroidRuntime( 1525): 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:298)
E/AndroidRuntime( 1525): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:328)
E/AndroidRuntime( 1525): 	at android.content.ContentResolver.update(ContentResolver.java:1333)
E/AndroidRuntime( 1525): 	at com.google.android.search.core.icingsync.e.JA(UpdateIcingCorporaService.java:408)
E/AndroidRuntime( 1525): 	at com.google.android.search.core.icingsync.g.aTY(UpdateIcingCorporaService.java:347)
E/AndroidRuntime( 1525): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:320)
E/AndroidRuntime( 1525): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.ba(UpdateIcingCorporaService.java:215)
E/AndroidRuntime( 1525): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:201)
E/AndroidRuntime( 1525): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 1525): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1525): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 1525): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DropBoxManagerService(  821): Can't write: system_app_crash
E/DropBoxManagerService(  821): java.io.FileNotFoundException: /data/system/dropbox/drop99.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  821): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  821): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  821): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  821): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  821): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  821): 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
E/DropBoxManagerService(  821): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  821): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  821): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  821): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  821): 	... 5 more
W/ResourcesManager( 4492): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4492): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/WifiService(  821): Client connection lost with reason: 4
I/ActivityManager(  821): Start proc 4528:com.google.android.apps.docs/u0a46 for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
I/ActivityManager(  821): Process com.google.android.gms (pid 1774) has died
W/ActivityManager(  821): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 1000ms
W/ActivityManager(  821): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 1000ms
W/ActivityManager(  821): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 11000ms
W/ActivityManager(  821): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 10999ms
W/ActivityManager(  821): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 10999ms
W/ActivityManager(  821): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 10999ms
I/MultiDex( 4492): VM with version 2.1.0 has multidex support
I/MultiDex( 4492): install
I/MultiDex( 4492): VM has multidex support, MultiDex support library is disabled.
E/DropBoxManagerService(  821): Can't write: system_app_crash
E/DropBoxManagerService(  821): java.io.FileNotFoundException: /data/system/dropbox/drop100.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  821): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  821): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  821): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  821): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  821): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  821): 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
E/DropBoxManagerService(  821): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  821): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  821): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  821): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  821): 	... 5 more
W/ResourcesManager(  821): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(  821): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/OpenGLRenderer(  821): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
D/Atlas   (  821): Validating map...
I/OpenGLRenderer(  821): Initialized EGL, version 1.4
I/ActivityManager(  821): Start proc 4548:com.google.android.gms/u0a11 for service com.google.android.gms/.feedback.FeedbackService
D/OpenGLRenderer(  821): Enabling debug mode 0
V/JNIHelp ( 4492): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
W/ResourcesManager( 4548): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4548): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ProviderInstaller( 4492): Installed default security provider GmsCore_OpenSSL
W/NativeLibraryUtils( 4492): Failed to open lock file
W/NativeLibraryUtils( 4492): java.io.FileNotFoundException: /data/data/com.google.android.gms/cache/.lib.lock: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 4492): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/NativeLibraryUtils( 4492): 	at java.io.RandomAccessFile.<init>(RandomAccessFile.java:117)
W/NativeLibraryUtils( 4492): 	at com.google.android.gms.common.util.ax.a(SourceFile:305)
W/NativeLibraryUtils( 4492): 	at com.google.android.gms.common.app.a.run(SourceFile:136)
W/NativeLibraryUtils( 4492): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 4492): 	at libcore.io.Posix.open(Native Method)
W/NativeLibraryUtils( 4492): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/NativeLibraryUtils( 4492): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/NativeLibraryUtils( 4492): 	... 3 more
I/ActivityManager(  821): Killing 3825:com.google.android.apps.magazines/u0a67 (adj 15): empty #17
I/MultiDex( 4548): VM with version 2.1.0 has multidex support
I/MultiDex( 4548): install
I/MultiDex( 4548): VM has multidex support, MultiDex support library is disabled.
E/SQLiteDatabase( 4548): Failed to open database '/data/data/com.google.android.gms/databases/snet_safe_browsing.db'.
E/SQLiteDatabase( 4548): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4548): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4548): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4548): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4548): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4548): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4548): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4548): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4548): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4548): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4548): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4548): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4548): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4548): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4548): 	at com.google.android.gms.security.snet.ab.a(SourceFile:1181)
E/SQLiteDatabase( 4548): 	at com.google.android.gms.security.snet.ab.a(SourceFile:1200)
E/SQLiteDatabase( 4548): 	at com.google.android.gms.security.snet.w.doInBackground(SourceFile:133)
E/SQLiteDatabase( 4548): 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
E/SQLiteDatabase( 4548): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4548): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4548): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4548): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4548): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 4548): Failed to open database '/data/data/com.google.android.gms/databases/snet_safe_browsing.db'.
E/SQLiteDatabase( 4548): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4548): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4548): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4548): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4548): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4548): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4548): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4548): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4548): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4548): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4548): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4548): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4548): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4548): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4548): 	at com.google.android.gms.security.snet.aa.b(SourceFile:826)
E/SQLiteDatabase( 4548): 	at com.google.android.gms.security.snet.aa.a(SourceFile:847)
E/SQLiteDatabase( 4548): 	at com.google.android.gms.security.snet.w.doInBackground(SourceFile:133)
E/SQLiteDatabase( 4548): 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
E/SQLiteDatabase( 4548): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4548): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4548): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4548): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4548): 	at java.lang.Thread.run(Thread.java:818)
I/HotwordDetector( 1525): Closing mic
I/MicrophoneInputStream( 1525): mic_close com.google.android.apps.gsa.speech.audio.u@2f0dcb44
V/JNIHelp ( 4548): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
E/Search.SharedPreferencesProto( 1525): Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
I/ProviderInstaller( 4548): Installed default security provider GmsCore_OpenSSL
D/audio_hw_primary(  356): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  356): disable_snd_device: snd_device(55: voice-rec-mic)
W/NativeLibraryUtils( 4548): Failed to open lock file
W/NativeLibraryUtils( 4548): java.io.FileNotFoundException: /data/data/com.google.android.gms/cache/.lib.lock: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 4548): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/NativeLibraryUtils( 4548): 	at java.io.RandomAccessFile.<init>(RandomAccessFile.java:117)
W/NativeLibraryUtils( 4548): 	at com.google.android.gms.common.util.ax.a(SourceFile:305)
W/NativeLibraryUtils( 4548): 	at com.google.android.gms.common.app.a.run(SourceFile:136)
W/NativeLibraryUtils( 4548): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 4548): 	at libcore.io.Posix.open(Native Method)
W/NativeLibraryUtils( 4548): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/NativeLibraryUtils( 4548): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/NativeLibraryUtils( 4548): 	... 3 more
I/SoundTriggerHwService::Module(  356): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1525): Hotword detection finished
I/HotwordRecognitionRnr( 1525): Stopping hotword detection.
I/ActivityManager(  821): Killing 3881:com.android.chrome/u0a40 (adj 15): empty #17
E/SQLiteDatabase( 4548): Failed to open database '/data/data/com.google.android.gms/databases/reminders.db'.
E/SQLiteDatabase( 4548): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4548): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4548): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4548): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4548): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4548): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4548): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4548): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4548): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4548): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4548): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4548): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4548): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4548): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 4548): 	at com.google.android.gms.reminders.provider.RemindersProvider.query(SourceFile:419)
E/SQLiteDatabase( 4548): 	at android.content.ContentProvider.query(ContentProvider.java:966)
E/SQLiteDatabase( 4548): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:211)
E/SQLiteDatabase( 4548): 	at android.content.ContentResolver.query(ContentResolver.java:478)
E/SQLiteDatabase( 4548): 	at android.content.ContentResolver.query(ContentResolver.java:422)
E/SQLiteDatabase( 4548): 	at com.google.android.gms.reminders.a.a.a(SourceFile:71)
E/SQLiteDatabase( 4548): 	at com.google.android.gms.reminders.a.c.doInBackground(SourceFile:39)
E/SQLiteDatabase( 4548): 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
E/SQLiteDatabase( 4548): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4548): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4548): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4548): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4548): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteOpenHelper( 4548): Couldn't open reminders.db for writing (will try read-only):
E/SQLiteOpenHelper( 4548): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4548): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4548): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 4548): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 4548): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4548): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4548): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4548): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteOpenHelper( 4548): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteOpenHelper( 4548): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 4548): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteOpenHelper( 4548): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 4548): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 4548): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 4548): 	at com.google.android.gms.reminders.provider.RemindersProvider.query(SourceFile:419)
E/SQLiteOpenHelper( 4548): 	at android.content.ContentProvider.query(ContentProvider.java:966)
E/SQLiteOpenHelper( 4548): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:211)
E/SQLiteOpenHelper( 4548): 	at android.content.ContentResolver.query(ContentResolver.java:478)
E/SQLiteOpenHelper( 4548): 	at android.content.ContentResolver.query(ContentResolver.java:422)
E/SQLiteOpenHelper( 4548): 	at com.google.android.gms.reminders.a.a.a(SourceFile:71)
E/SQLiteOpenHelper( 4548): 	at com.google.android.gms.reminders.a.c.doInBackground(SourceFile:39)
E/SQLiteOpenHelper( 4548): 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
E/SQLiteOpenHelper( 4548): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteOpenHelper( 4548): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteOpenHelper( 4548): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteOpenHelper( 4548): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteOpenHelper( 4548): 	at java.lang.Thread.run(Thread.java:818)
W/SQLiteOpenHelper( 4548): Opened reminders.db in read-only mode
I/GAv4    ( 4528): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4528):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4528):   adb logcat -s GAv4
W/GAv4    ( 4528): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
E/SQLiteDatabase( 4548): Failed to open database '/data/data/com.google.android.gms/databases/plus.db'.
E/SQLiteDatabase( 4548): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4548): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4548): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4548): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4548): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4548): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4548): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4548): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4548): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4548): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4548): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4548): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4548): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4548): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4548): 	at com.google.android.gms.plus.provider.PlusProvider.a(SourceFile:329)
E/SQLiteDatabase( 4548): 	at com.google.android.gms.plus.provider.b.a(SourceFile:146)
E/SQLiteDatabase( 4548): 	at com.google.android.gms.plus.provider.b.doInBackground(SourceFile:143)
E/SQLiteDatabase( 4548): 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
E/SQLiteDatabase( 4548): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4548): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4548): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4548): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4548): 	at java.lang.Thread.run(Thread.java:818)
E/AndroidRuntime( 4548): FATAL EXCEPTION: AsyncTask #3
E/AndroidRuntime( 4548): Process: com.google.android.gms, PID: 4548
E/AndroidRuntime( 4548): java.lang.RuntimeException: An error occured while executing doInBackground()
E/AndroidRuntime( 4548): 	at android.os.AsyncTask$3.done(AsyncTask.java:304)
E/AndroidRuntime( 4548): 	at java.util.concurrent.FutureTask.finishCompletion(FutureTask.java:355)
E/AndroidRuntime( 4548): 	at java.util.concurrent.FutureTask.setException(FutureTask.java:222)
E/AndroidRuntime( 4548): 	at java.util.concurrent.FutureTask.run(FutureTask.java:242)
E/AndroidRuntime( 4548): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/AndroidRuntime( 4548): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 4548): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 4548): 	at java.lang.Thread.run(Thread.java:818)
E/AndroidRuntime( 4548): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4548): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4548): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 4548): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 4548): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4548): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4548): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4548): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AndroidRuntime( 4548): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AndroidRuntime( 4548): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 4548): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AndroidRuntime( 4548): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 4548): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 4548): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 4548): 	at com.google.android.gms.plus.provider.PlusProvider.a(SourceFile:329)
E/AndroidRuntime( 4548): 	at com.google.android.gms.plus.provider.b.a(SourceFile:146)
E/AndroidRuntime( 4548): 	at com.google.android.gms.plus.provider.b.doInBackground(SourceFile:143)
E/AndroidRuntime( 4548): 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
E/AndroidRuntime( 4548): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AndroidRuntime( 4548): 	... 4 more
W/GAv4    ( 4528): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
E/SharedPreferencesImpl( 4528): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4528): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/DropBoxManagerService(  821): Can't write: system_app_crash
E/DropBoxManagerService(  821): java.io.FileNotFoundException: /data/system/dropbox/drop104.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  821): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  821): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  821): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  821): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  821): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  821): 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
E/DropBoxManagerService(  821): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  821): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  821): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  821): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  821): 	... 5 more
W/GAv4    ( 4528): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 4528): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
E/SharedPreferencesImpl( 4528): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/native  ( 1242): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1242): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1242): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1242): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1242): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1242): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1242): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1242): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/SQLiteDatabase( 4528): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4528): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4528): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4528): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4528): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4528): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4528): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4528): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4528): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4528): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4528): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4528): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4528): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4528): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4528): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4528): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 4528): 	at ael.a(PG:1521)
E/SQLiteDatabase( 4528): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 4528): 	at aen.run(PG:536)
E/SQLiteDatabase( 4528): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 4528): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4528): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4528): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4528): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4528): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4528): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4528): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4528): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4528): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4528): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4528): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4528): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4528): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4528): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4528): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 4528): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 4528): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 4528): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 4528): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 4528): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 4528): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4528): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4528): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4528): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4528): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 4528): 	at gir$c.run(Unknown Source)
E/GAv4    ( 4528): Opening the database failed, dropping the table and recreating it
I/Icing   ( 4548): Storage manager: low false usage 1.98MB avail 20.74GB capacity 22.09GB
E/SharedPreferencesImpl( 4528): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SQLiteDatabase( 4528): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 4528): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4528): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4528): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4528): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4528): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4528): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4528): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4528): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4528): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4528): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4528): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4528): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4528): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4528): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4528): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 4528): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 4528): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 4528): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 4528): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 4528): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 4528): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4528): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4528): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4528): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4528): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 4528): 	at gir$c.run(Unknown Source)
E/GAv4    ( 4528): Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 4528): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4528): Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 4528): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4528): Job execution failed: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 4528): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
I/GAv4-SVC( 4548): Google Analytics 7.8.99 is starting up.
D/GFEEDBACK_SendErrorReportOperation( 4548): Error doing instant send: java.io.IOException: failed to create reports directory
E/GFEEDBACK_SendErrorReportOperation( 4548): Error saving report: java.io.IOException: failed to create reports directory
W/Icing   ( 4548): Received bad json for section weights override -- ignoring.
W/Icing   ( 4548): Received bad json for corpus context scoring override -- ignoring.
W/Icing   ( 4548): Received bad json for section weights override -- ignoring.
W/Icing   ( 4548): Received bad json for corpus context scoring override -- ignoring.
E/SQLiteDatabase( 4528): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4528): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4528): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4528): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4528): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4528): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4528): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4528): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4528): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4528): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4528): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4528): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase,( 4528): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4528): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4528): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4528): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 4528): 	at ael.a(PG:1521)
E/SQLiteDatabase( 4528): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 4528): 	at aej.c(PG:139)
E/SQLiteDatabase( 4528): 	at aej.b(PG:398)
E/SQLiteDatabase( 4528): 	at agf.f(PG:417)
E/SQLiteDatabase( 4528): 	at oe.run(PG:1112)
E/SQLiteDatabase( 4528): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4528): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4528): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4528): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4528): 	at java.lang.Thread.run(Thread.java:818)
E/AbstractDatabaseInstance( 4528): Failed to delete from CachedSearch133
E/AbstractDatabaseInstance( 4528): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AbstractDatabaseInstance( 4528): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AbstractDatabaseInstance( 4528): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AbstractDatabaseInstance( 4528): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AbstractDatabaseInstance( 4528): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AbstractDatabaseInstance( 4528): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AbstractDatabaseInstance( 4528): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AbstractDatabaseInstance( 4528): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AbstractDatabaseInstance( 4528): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AbstractDatabaseInstance( 4528): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AbstractDatabaseInstance( 4528): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AbstractDatabaseInstance( 4528): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AbstractDatabaseInstance( 4528): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/Abstract
```
