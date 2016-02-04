#### Test 58259810381ca4f_thali05_motorola-Nexus 6 Logs


```
--------- beginning of system
I/ActivityManager(  822): Killing 3304:com.google.android.keep/u0a79 (adj 15): empty #17
I/ActivityManager(  822): Killing 3329:com.qualcomm.timeservice/1000 (adj 15): empty #17
,--------- beginning of main
D/AndroidRuntime( 3721): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 3721): CheckJNI is OFF
D/AndroidRuntime( 3721): Calling main entry com.android.commands.am.Am
I/ActivityManager(  822): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/WindowManager(  822): addAppToken: AppWindowToken{2fddbf74 token=Token{2087ab47 ActivityRecord{24876686 u0 com.test.thalitest/.MainActivity t28}}} to stack=1 task=28 at 0
D/AndroidRuntime( 3721): Shutting down VM
I/HotwordDetector( 1505): Closing mic
I/MicrophoneInputStream( 1505): mic_close com.google.android.apps.gsa.speech.audio.u@26db6631
V/WindowManager(  822): Adding window Window{374dd599 u0 Starting com.test.thalitest} at 2 of 7 (after Window{22730b7b u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
I/ActivityManager(  822): Start proc 3735:com.test.thalitest/u0a265 for activity com.test.thalitest/.MainActivity
D/audio_hw_primary(  358): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  358): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  358): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1505): Stopping hotword detection.
I/HotwordRecognitionRnr( 1505): Hotword detection finished
I/ActivityManager(  822): Killing 3349:com.google.android.deskclock/u0a44 (adj 15): empty #17
E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1659524371
E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,D/HeadsetStateMachine( 2156): Disconnected process message: 10, size: 0
,I/WebViewFactory( 3735): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3735): Time to load native libraries: 4 ms (timestamps 7801-7805)
I/LibraryLoader( 3735): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3735): Binding Chromium to main looper Looper (main, tid 1) {20d5aa36}
,I/LibraryLoader( 3735): Expected native library version number "",actual native library version number ""
,I/chromium( 3735): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3735): Initializing chromium process, singleProcess=true,
W/art     ( 3735): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3735): ApplicationContext is null in ApplicationStatus
,W/chromium( 3735): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3735): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3735): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3735): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/BluetoothManagerService(  822): Message: 20
D/BluetoothManagerService(  822): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1c419cd3:true
,W/art     ( 3735): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3735): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3735): CordovaWebView is running on device made by: motorola
,W/art     ( 3735): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3735): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3735): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,D/Atlas   ( 3735): Validating map...
,V/WindowManager(  822): Adding window Window{3ffb60c3 u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{374dd599 u0 Starting com.test.thalitest})
,W/chromium( 3735): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/art     (  822): Explicit concurrent mark sweep GC freed 20807(1026KB) AllocSpace objects, 4(64KB) LOS objects, 32% free, 33MB/49MB, paused 3.486ms total 79.778ms
,I/OpenGLRenderer( 3735): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3735): Enabling debug mode 0
,I/ActivityManager(  822): Displayed com.test.thalitest/.MainActivity: +992ms
,I/Keyboard.Facilitator( 1215): onFinishInput()
,W/BindingManager( 3735): Cannot call determinedVisibility() - never saw a connection for the pid: 3735
,D/JsMessageQueue( 3735): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3735): JniHelper::setJavaVM(0xb489d200), pthread_self() = -1576397056
,I/chromium( 3735): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 3735): Initializing JXcore engine
W/jxcore-log( 3735): JXcore engine is ready
,W/Thread-411( 3791): type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[12793]" dev="sockfs" ino=12793 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-411( 3791): type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-411( 3791): type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[12909]" dev="sockfs" ino=12909 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/Thread-411( 3791): type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[23723]" dev="sockfs" ino=23723 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 3735): Starting JXcore engine,
,W/jxcore-log( 3735): Platform android
W/jxcore-log( 3735): 
W/jxcore-log( 3735): Process ARCH arm,
W/jxcore-log( 3735): 
,I/jxcore-log( 3735): JXcore Cordova bridge is ready!
I/jxcore-log( 3735): 
W/jxcore-log( 3735): JXcore engine is started,
,I/jxcore-log( 3735): Toggling radios to true
I/jxcore-log( 3735): 
D/BluetoothAdapter( 3735): enable(): BT is already enabled..!
,D/WifiService(  822): setWifiEnabled: true pid=3735, uid=10265
,E/WifiService(  822): Invoking mWifiStateMachine.setWifiEnabled
D/WifiService(  822): New client listening to asynchronous messages
,I/jxcore-log( 3735): Radios toggled
I/jxcore-log( 3735): 
,I/jxcore-log( 3735): My device name is: motorola-Nexus 6
I/jxcore-log( 3735): 
,I/wpa_supplicant( 1185): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  822): WifiStateMachine: Leaving Connected state
,E/WifiConfigStore(  822): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  354): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1485): Read error: ssl=0xb4bc0000: I/O error during system call, Connection timed out,
,V/NativeCrypto( 1485): SSL shutdown failed: ssl=0xb4bc0000: I/O error during system call, Broken pipe
D/ConnectivityService(  822): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  822): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
E/WifiStateMachine(  822): Start Disconnecting Watchdog 1
E/WifiStateMachine(  822): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,D/ConnectivityService(  822): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10011
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): DefaultState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): Forcing reevaluation
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
,D/CommandListener(  354): Clearing all IP addresses on wlan0
,D/ConnectivityService(  822): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/CSLegacyTypeTracker(  822): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): OfflineState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityManager.CallbackHandler( 1066): CM callback handler got msg 524292
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): Disconnected - quitting
D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/WifiNetworkAgent(  822): NetworkAgent: NetworkAgent channel lost
D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  822): MasterInitialState.processMessage what=3
,E/WifiStateMachine(  822): CMD_AUTO_CONNECT sup state CompletedState my state DisconnectedState nid=0 roam=3
E/WifiStateMachine(  822): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=0
D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkChangeNotifierAutoDetect( 1505): Network connectivity changed, type is: 6
,I/NetworkMonitor( 3075): type=WIFI subType= reason=null isConnected=false
,D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  822): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/ConnectivityService(  822): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/ConnectivityService(  822): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
,D/Tethering(  822): MasterInitialState.processMessage what=3
,V/MusicLeanback( 3075): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/PhoneInterfaceManager( 1263): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1263): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  822): getDataEnabled: retVal=false
,E/WifiConfigStore(  822): Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiConfigStore(  822): will read network variables netId=0
,I/ActivityManager(  822): Start proc 3799:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,E/WifiStateMachine(  822): CMD_AUTO_CONNECT did save config ->  nid=0
,E/GpsLocationProvider(  822): No APN found to select.
,E/WifiConfigStore(  822): will read network variables netId=0
,D/PhoneInterfaceManager( 1263): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1263): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  822): getDataEnabled: retVal=false
,E/GpsLocationProvider(  822): No APN found to select.
,D/SprintDMReceiver( 3799): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3799): simOperator:  IMSI: null
,D/SprintDMReceiver( 3799): Not Sprint UICC, don't do anything.
I/ActivityManager(  822): Killing 3439:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,I/SystemUpdateService( 1769): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1769): onCreate
,D/SystemUpdateService( 1769): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1769): active receiver: enabled
,I/SystemUpdateService( 1769): showing system update notification
,I/iu.Environment( 1769): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1769): num queued entries: 0
,I/iu.UploadsManager( 1769): num updated entries: 0
,I/ValidateNoPeople(  822): skipping global notification
,I/iu.SyncManager( 1769): NEXT; no task
,V/SystemUpdateService( 1769): retry (wakeup: false) in 3599955 ms
,D/ChimeraCfgMgr( 1769): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 1769): [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
,D/SystemUpdateService( 1769): onDestroy
,I/Babel   ( 2793): connection state changed from CONNECTED to DISCONNECTED
,I/ActivityManager(  822): Start proc 3819:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,I/GAv4    ( 3819): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3819):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3819):   adb logcat -s GAv4
,W/GAv4    ( 3819): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3819): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3819): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 3819): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3819): Time to load native libraries: 2 ms (timestamps 1648-1650)
I/LibraryLoader( 3819): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3819): Binding Chromium to main looper Looper (main, tid 1) {3f446d15}
,I/LibraryLoader( 3819): Expected native library version number "",actual native library version number ""
,I/chromium( 3819): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3819): Initializing chromium process, singleProcess=true
W/art     ( 3819): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3819): ApplicationContext is null in ApplicationStatus
,W/chromium( 3819): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3819): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3819): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3819): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,W/AudioManagerAndroid( 3819): Requires BLUETOOTH permission
,I/NSApplication( 3819): Starting up...
,I/ActivityManager(  822): Start proc 3875:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,I/ActivityManager(  822): Killing 3460:com.android.musicfx/u0a18 (adj 15): empty #17
,I/ActivityManager(  822): Killing 3488:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,V/MusicLeanback( 3075): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/SprintDMReceiver( 3799): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3799): simOperator:  IMSI: null
D/SprintDMReceiver( 3799): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1769): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1769): onCreate
,D/SystemUpdateService( 1769): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1769): active receiver: enabled
,I/SystemUpdateService( 1769): showing system update notification
,D/ChimeraCfgMgr( 1769): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/ValidateNoPeople(  822): skipping global notification
,I/Kids    ( 1769): [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
,V/SystemUpdateService( 1769): retry (wakeup: false) in 3599978 ms
,D/SystemUpdateService( 1769): onDestroy
,I/wpa_supplicant( 1185): wlan0: Trying to associate with SSID 'NG7005g'
,I/ActivityManager(  822): Waited long enough for: ServiceRecord{acb3a21 u0 com.motorola.android.buacontactadapter/.AuthenticationService}
,I/wpa_supplicant( 1185): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 1185): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1185): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=0 id_str=]
,D/ConnectivityService(  822): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} }
,D/ConnectivityService(  822): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  822): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiConfigStore(  822): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any,
,D/CommandListener(  354): Setting iface cfg
,E/WifiStateMachine(  822): Start Dhcp Watchdog 2
,E/WifiStateMachine(  822):  WifiLinkLayerStats: ,
E/WifiStateMachine(  822):  my bss beacon rx: 175
E/WifiStateMachine(  822):  RSSI mgmt: -52
,E/WifiStateMachine(  822):  BE :  rx=159 tx=147 lost=0 retries=0
E/WifiStateMachine(  822):  BK :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  822):  VI :  rx=0 tx=0 lost=0 retries=0
,E/WifiStateMachine(  822):  VO :  rx=6 tx=0 lost=0 retries=0
E/WifiStateMachine(  822):  on_time : 10342 tx_time=212 rx_time=406 scan_time=0
,D/ConnectivityService(  822): updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,E/native  (  822): do suspend false
,E/WifiStateMachine(  822): scanCount==0 - aborting
,I/dhcpcd  ( 3905): version 5.5.6 starting
,I/dhcpcd  ( 3905): wlan0: rebinding lease of 192.168.1.122
,I/ActivityManager(  822): Killing 1377:android.process.acore/u0a5 (adj 15): empty #17
,I/ActivityManager(  822): Killing 3616:com.google.android.gm.exchange/u0a77 (adj 15): empty #18
,I/dhcpcd  ( 3905): wlan0: acknowledged 192.168.1.122 from 192.168.1.1
,I/dhcpcd  ( 3905): wlan0: leased 192.168.1.122 for 86400 seconds
,D/ConnectivityService(  822): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  822): Adding iface wlan0 to network 101
,E/WifiStateMachine(  822): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,I/jxcore-log( 3735): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 3735): 
,E/ConnectivityService(  822): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  822): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  822): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  822): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  822): Setting Dns servers for network 101 to [/192.168.1.1]
,D/ConnectivityService(  822): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  822): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  822): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  822):    accepting network in place of null
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  822): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  822): Connected
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  822): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  822): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
,D/ConnectivityService(  822): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} }
,D/ConnectivityService(  822): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/CSLegacyTypeTracker(  822): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 1066): CM callback handler got msg 524290
D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  822): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 3075): type=WIFI subType= reason=null isConnected=true
,D/NetworkChangeNotifierAutoDetect( 1505): Network connectivity changed, type is: 2
,V/MusicLeanback( 3075): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/PhoneInterfaceManager( 1263): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1263): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  822): getDataEnabled: retVal=false
,D/SprintDMReceiver( 3799): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,E/GpsLocationProvider(  822): No APN found to select.
,D/SprintDMHelper( 3799): simOperator:  IMSI: null
D/SprintDMReceiver( 3799): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1769): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1769): onCreate
,D/SystemUpdateService( 1769): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1769): active receiver: enabled
,I/SystemUpdateService( 1769): showing system update notification
,I/ActivityManager(  822): Start proc 3938:com.google.android.keep/u0a79 for service com.google.android.keep/.syncadapter.KeepSyncAdapterService
,I/iu.Environment( 1769): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/ValidateNoPeople(  822): skipping global notification
,V/SystemUpdateService( 1769): retry (wakeup: false) in 3599936 ms
,I/iu.UploadsManager( 1769): num queued entries: 0
I/iu.UploadsManager( 1769): num updated entries: 0
I/iu.SyncManager( 1769): NEXT; no task
,D/ChimeraCfgMgr( 1769): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 1769): [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
D/SystemUpdateService( 1769): onDestroy
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  822): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 04 Feb 2016 09:41:40 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454578900995], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454578900977]}
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  822): Validated
D/ConnectivityService(  822): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/ConnectivityService(  822): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  822): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  822): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  822): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 1066): CM callback handler got msg 524290
,V/Herrevad( 1769): NQAS connected
,I/Babel   ( 2793): connection state changed from DISCONNECTED to CONNECTED
,I/art     ( 1485): Explicit concurrent mark sweep GC freed 28206(1524KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 678us total 20.689ms
,V/KeepSync( 3938): Connecting to GoogleApiClient
,I/GLSUser ( 1485): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1485): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1485): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1485): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/GCM     ( 1485): Connected
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
,V/KeepSync( 3938): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3938): (284) automatic index on blob_node(is_deleted)
,D/GCM     ( 1485): Message class com.google.f.a.a.p
,E/SQLiteLog( 3938): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3938): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1485): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1485): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1485): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1485): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3938): IOException
E/KeepSync( 3938): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3938): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3938): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3938): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3938): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3938): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3938): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3938): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3938): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3938): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3938): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3938): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3938): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3938): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3938): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3938): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3938): 	... 10 more
W/KeepSync( 3938): Sync result 2
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 74979, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/jxcore-log( 3735): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 3735): 
,I/jxcore-log( 3735): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 3735): 
,I/jxcore-log( 3735): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 3735): 
,I/jxcore-log( 3735): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js,
I/jxcore-log( 3735): 
,I/jxcore-log( 3735): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 3735): 
,I/jxcore-log( 3735): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js,
I/jxcore-log( 3735): 
,I/jxcore-log( 3735): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 3735): 
,D/ConnectivityService(  822): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  822): Explicit concurrent mark sweep GC freed 50594(2MB) AllocSpace objects, 8(222KB) LOS objects, 32% free, 33MB/49MB, paused 2.628ms total 103.276ms
,I/GLSUser ( 1485): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1485): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1485): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1485): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3525): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3525): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3525): [1] 5.onFinished: Scheduling replication attempt 1.
,I/ActivityManager(  822): Killing 3565:com.google.android.gms:car/u0a11 (adj 15): empty #17
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=9.16 rxSuccessRate=10.86 targetRoamBSSID=any RSSI=-52
E/WifiStateMachine(  822): WifiStateMachine L2Connected CMD_START_SCAN source -2 6, 7 -> obsolete
,I/jxcore-log( 3735): Test app app.js loaded
,I/jxcore-log( 3735): 
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3735): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3735): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3735): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3735): 	Bluetooth MAC address: F8:CF:C5:D9:E5:61, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3735): 	Discovery mode: BLE_AND_WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3735): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3735): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3735): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3735): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3735): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2644232f added. We now have 1 listener(s)
,I/chromium( 3735): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/jxcore-log( 3735): BLE advertisement is supported
I/jxcore-log( 3735): 
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=6.58 rxSuccessRate=10.43 targetRoamBSSID=any RSSI=-52
E/WifiStateMachine(  822): WifiStateMachine L2Connected CMD_START_SCAN source -2 5, 7 -> obsolete
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.72 rxSuccessRate=3.28 targetRoamBSSID=any RSSI=-52
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1485): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1485): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1485): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1485): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3525): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3525): [1] 5.onFinished: Installation state replication failed.,
,D/Finsky  ( 3525): [1] 5.onFinished: Scheduling replication attempt 2.
,I/ActivityManager(  822): Start proc 3988:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,W/GAV2    ( 3988): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/BooksApp( 3988): Created application version: 3.6.8 (30608)
,I/BooksSync( 3988): Starting books sync for 61035162, extras: ade
,I/GLSUser ( 1485): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1485): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1485): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1485): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1485): Explicit concurrent mark sweep GC freed 20133(1184KB) AllocSpace objects, 3(330KB) LOS objects, 37% free, 26MB/42MB, paused 876us total 20.174ms
,E/HttpOperation( 3258): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3258): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3258): 	at jdm.a(PG:82)
E/HttpOperation( 3258): 	at jcs.o(PG:406)
E/HttpOperation( 3258): 	at jcn.a(PG:1379)
E/HttpOperation( 3258): 	at jcs.i(PG:143)
E/HttpOperation( 3258): 	at blb.a(PG:3937)
E/HttpOperation( 3258): 	at czp.a(PG:18188)
E/HttpOperation( 3258): 	at czp.a(PG:9081)
E/HttpOperation( 3258): 	at czq.run(PG:1686)
E/HttpOperation( 3258): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3258): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3258): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3258): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3258): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3258): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3258): 	at jdj.a(PG:4091)
E/HttpOperation( 3258): 	at jdj.a(PG:1125)
E/HttpOperation( 3258): 	at jdm.a(PG:77)
E/HttpOperation( 3258): 	... 12 more
E/HttpOperation( 3258): Caused by: faj: BadAuthentication
E/HttpOperation( 3258): 	at fal.a(PG:38)
E/HttpOperation( 3258): 	at jdj.a(PG:4089)
E/HttpOperation( 3258): 	... 14 more
,I/GLSUser ( 1485): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1485): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1485): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1485): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3258): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3258): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3258): 	at jdm.a(PG:82)
E/HttpOperation( 3258): 	at jcs.o(PG:406)
E/HttpOperation( 3258): 	at jcn.a(PG:1379)
E/HttpOperation( 3258): 	at jcs.i(PG:143)
E/HttpOperation( 3258): 	at hec.a(PG:42)
E/HttpOperation( 3258): 	at hee.a(PG:102)
E/HttpOperation( 3258): 	at czr.a(PG:65)
E/HttpOperation( 3258): 	at kka.a(PG:108)
E/HttpOperation( 3258): 	at czp.a(PG:19176)
E/HttpOperation( 3258): 	at czp.a(PG:9081)
E/HttpOperation( 3258): 	at czq.run(PG:1686)
E/HttpOperation( 3258): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3258): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3258): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3258): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3258): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3258): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3258): 	at jdj.a(PG:4091)
E/HttpOperation( 3258): 	at jdj.a(PG:1125)
E/HttpOperation( 3258): 	at jdm.a(PG:77)
E/HttpOperation( 3258): 	... 15 more
E/HttpOperation( 3258): Caused by: faj: BadAuthentication
E/HttpOperation( 3258): 	at fal.a(PG:38)
E/HttpOperation( 3258): 	at jdj.a(PG:4089)
E/HttpOperation( 3258): 	... 17 more
,E/ExperimentLoader( 3258): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3258): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3258): 	at jdm.a(PG:82)
E/ExperimentLoader( 3258): 	at jcs.o(PG:406)
E/ExperimentLoader( 3258): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3258): 	at jcs.i(PG:143)
E/ExperimentLoader( 3258): 	at hec.a(PG:42)
E/ExperimentLoader( 3258): 	at hee.a(PG:102)
E/ExperimentLoader( 3258): 	at czr.a(PG:65)
E/ExperimentLoader( 3258): 	at kka.a(PG:108)
E/ExperimentLoader( 3258): 	at czp.a(PG:19176)
E/ExperimentLoader( 3258): 	at czp.a(PG:9081)
E/ExperimentLoader( 3258): 	at czq.run(PG:1686)
E/ExperimentLoader( 3258): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3258): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3258): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3258): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3258): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3258): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3258): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3258): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3258): 	at jdm.a(PG:77)
E/ExperimentLoader( 3258): 	... 15 more
E/ExperimentLoader( 3258): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3258): 	at fal.a(PG:38)
E/ExperimentLoader( 3258): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3258): 	... 17 more
,I/BooksConfig( 3988): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1485): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1485): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1485): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1485): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 77145, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1485): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1485): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1485): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1485): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3988): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3988): Soft error
,E/BooksSync( 3988): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3988): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3988): Sync error,
E/BooksSync( 3988): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3988): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3988): Finished books sync
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 78312, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
I/ActivityManager(  822): Killing 3590:com.google.android.gm/u0a78 (adj 15): empty #17
,I/GAV2    ( 3988): Thread[GAThread,5,main]: No campaign data found.
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=1.17 rxSuccessRate=2.16 targetRoamBSSID=any RSSI=-52
,E/WifiStateMachine(  822): WifiStateMachine starting scan for "NG7005g"WPA_PSK with 2412,5220
,D/Finsky  ( 3525): [370] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1485): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1485): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1485): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1485): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3525): [370] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1485): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1485): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1485): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1485): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3525): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3525): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3525): [1] 5.onFinished: Scheduling replication attempt 3.
,D/HeadsetStateMachine( 2156): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2156): Disconnected process message: 10, size: 0
,I/Keyboard.Facilitator.LanguageModelFlusher( 1215): run()
I/Keyboard.Facilitator( 1215): flushDynamicLanguageModels()
,I/ConfigService( 1485): onCreate
,I/ConfigService( 1485): onDestroy
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.44 rxSuccessRate=1.85 targetRoamBSSID=any RSSI=-52
,I/art     (  822): Explicit concurrent mark sweep GC freed 47806(2MB) AllocSpace objects, 13(302KB) LOS objects, 31% free, 34MB/50MB, paused 1.719ms total 116.610ms
,V/KeepSync( 3938): Connecting to GoogleApiClient
,I/GLSUser ( 1485): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1485): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1485): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1485): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
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
,V/KeepSync( 3938): GoogleApiClient failed to connect with error code: 4
E/SQLiteLog( 3938): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3938): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3938): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1485): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1485): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1485): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1485): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3938): IOException
E/KeepSync( 3938): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3938): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3938): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3938): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3938): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3938): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3938): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3938): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3938): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3938): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3938): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3938): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3938): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3938): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3938): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3938): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3938): 	... 10 more
W/KeepSync( 3938): Sync result 2
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 108370, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1485): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1485): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1485): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1485): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3525): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3525): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3525): [1] 5.onFinished: Scheduling replication attempt 4.
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.38 rxSuccessRate=2.41 targetRoamBSSID=any RSSI=-52
E/WifiStateMachine(  822): WifiStateMachine starting scan for "NG7005g"WPA_PSK with 2412,5220
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1485): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1485): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1485): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1485): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/PowerManagerService(  822): Going to sleep due to screen timeout (uid 1000)...,
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Adreno  (  822): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/Finsky  ( 3525): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3525): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3525): [1] 5.onFinished: Scheduling replication attempt 5.
,D/PermissionCache(  258): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (318 us)
,I/DisplayManagerService(  822): Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
D/SurfaceFlinger(  258): Set power mode=0, type=0 flinger=0xb6082000
D/qdhwcomposer(  258): hwc_setPowerMode: Setting mode 0 on display: 0
,V/ActivityManager(  822): Display changed displayId=0
,I/kickstart(  872): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000,
I/kickstart(  872): STATUS: Wrote to /sys/power/wake_lock
,E/kickstart(  872): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1,
I/kickstart(  872): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1' for writing
,I/qdhwcomposer(  258): handle_blank_event: dpy:0 panel power state: 0
,D/qdhwcomposer(  258): hwc_setPowerMode: Done setting mode 0 on display 0
,D/SurfaceControl(  822): Excessive delay in setPowerMode(): 254ms
,I/DreamManagerService(  822): Entering dreamland.
,I/PowerManagerService(  822): Dozing...
I/DreamController(  822): Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,D/audio_hw_primary(  358): adev_set_parameters: enter: screen_state=on
D/mot_vr_audio_hw(  358): adev_set_parameters: screen_state=on
,E/WifiStateMachine(  822): cancelDelayedScan -> 12
,E/native  (  822): do suspend false
,I/Keyboard.Facilitator( 1215): onFinishInput()
,E/WifiStateMachine(  822): cancelDelayedScan -> 14
,E/native  (  822): do suspend true
,D/audio_hw_primary(  358): adev_set_parameters: enter: screen_state=off,
D/mot_vr_audio_hw(  358): adev_set_parameters: screen_state=off
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-52
E/WifiStateMachine(  822): WifiStateMachine L2Connected CMD_START_SCAN source -2 13, 14 -> obsolete
,I/kickstart(  872): STATUS: Received file 'm9kefs1'
I/kickstart(  872): STATUS: 950272 bytes transferred in 0.993758 seconds
I/kickstart(  872): STATUS: Successfully downloaded files from target 
I/kickstart(  872): STATUS: Wrote to /sys/power/wake_unlock
,I/kickstart(  872): STATUS: Sahara protocol completed,
,I/BooksSync( 3988): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3988): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1485): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1485): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1485): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1485): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
I/GLSUser ( 1485): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1485): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1485): [GLSUser] Extracting token using key: Auth,
W/GLSActivity( 1485): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3258): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3258): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3258): 	at jdm.a(PG:82)
E/HttpOperation( 3258): 	at jcs.o(PG:406)
E/HttpOperation( 3258): 	at jcn.a(PG:1379)
E/HttpOperation( 3258): 	at jcs.i(PG:143)
E/HttpOperation( 3258): 	at blb.a(PG:3937)
E/HttpOperation( 3258): 	at czp.a(PG:18188)
E/HttpOperation( 3258): 	at czp.a(PG:9081)
E/HttpOperation( 3258): 	at czq.run(PG:1686)
E/HttpOperation( 3258): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3258): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3258): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3258): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3258): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3258): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3258): 	at jdj.a(PG:4091)
E/HttpOperation( 3258): 	at jdj.a(PG:1125)
E/HttpOperation( 3258): 	at jdm.a(PG:77)
E/HttpOperation( 3258): 	... 12 more
E/HttpOperation( 3258): Caused by: faj: BadAuthentication
E/HttpOperation( 3258): 	at fal.a(PG:38)
E/HttpOperation( 3258): 	at jdj.a(PG:4089)
E/HttpOperation( 3258): 	... 14 more
,I/GLSUser ( 1485): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1485): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1485): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1485): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1485): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1485): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1485): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1485): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3258): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3258): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3258): 	at jdm.a(PG:82)
E/HttpOperation( 3258): 	at jcs.o(PG:406)
E/HttpOperation( 3258): 	at jcn.a(PG:1379)
E/HttpOperation( 3258): 	at jcs.i(PG:143)
E/HttpOperation( 3258): 	at hec.a(PG:42)
E/HttpOperation( 3258): 	at hee.a(PG:102)
E/HttpOperation( 3258): 	at czr.a(PG:65)
E/HttpOperation( 3258): 	at kka.a(PG:108)
E/HttpOperation( 3258): 	at czp.a(PG:19176)
E/HttpOperation( 3258): 	at czp.a(PG:9081)
E/HttpOperation( 3258): 	at czq.run(PG:1686)
E/HttpOperation( 3258): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3258): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3258): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3258): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587),
E/HttpOperation( 3258): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3258): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3258): 	at jdj.a(PG:4091)
E/HttpOperation( 3258): 	at jdj.a(PG:1125)
E/HttpOperation( 3258): 	at jdm.a(PG:77)
E/HttpOperation( 3258): 	... 15 more
E/HttpOperation( 3258): Caused by: faj: BadAuthentication
E/HttpOperation( 3258): 	at fal.a(PG:38)
E/HttpOperation( 3258): 	at jdj.a(PG:4089)
E/HttpOperation( 3258): 	... 17 more
E/ExperimentLoader( 3258): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3258): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3258): 	at jdm.a(PG:82)
E/ExperimentLoader( 3258): 	at jcs.o(PG:406)
E/ExperimentLoader( 3258): 	at jcn.a(PG:1379),
E/ExperimentLoader( 3258): 	at jcs.i(PG:143)
E/ExperimentLoader( 3258): 	at hec.a(PG:42)
E/ExperimentLoader( 3258): 	at hee.a(PG:102)
E/ExperimentLoader( 3258): 	at czr.a(PG:65)
E/ExperimentLoader( 3258): 	at kka.a(PG:108)
E/ExperimentLoader( 3258): 	at czp.a(PG:19176)
E/ExperimentLoader( 3258): 	at czp.a(PG:9081)
E/ExperimentLoader( 3258): 	at czq.run(PG:1686)
E/ExperimentLoader( 3258): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3258): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3258): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3258): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3258): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3258): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3258): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3258): 	at jdj.a(PG:1125),
E/ExperimentLoader( 3258): 	at jdm.a(PG:77)
E/ExperimentLoader( 3258): 	... 15 more
E/ExperimentLoader( 3258): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3258): 	at fal.a(PG:38)
E/ExperimentLoader( 3258): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3258): 	... 17 more
,E/BooksAccountManager( 3988): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3988): Soft error
E/BooksSync( 3988): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3988): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3988): Sync error,
E/BooksSync( 3988): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3988): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3988): Finished books sync
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 138425, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 138002, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-52
E/WifiStateMachine(  822): WifiStateMachine L2Connected CMD_START_SCAN source -2 11, 14 -> obsolete
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1485): Vacuum at: now=1454579008605 tag=VacuumService
,V/GoogleAuthProtoRequest( 3119): [306] a.<init>: mAccountName set to: thalitester@gmail.com
,I/art     ( 1485): Explicit concurrent mark sweep GC freed 42211(2MB) AllocSpace objects, 3(330KB) LOS objects, 37% free, 26MB/42MB, paused 798us total 33.281ms
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1485): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1485): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1485): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1485): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1485): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1485): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1485): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1485): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3119): [306] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3119): [306] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3119): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3119): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3119): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3119): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3119): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3119): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3119): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3119): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3119): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3119): 	at com.a.a.k.run(SourceFile:110)
,I/art     (  822): Explicit concurrent mark sweep GC freed 44364(2MB) AllocSpace objects, 12(286KB) LOS objects, 31% free, 34MB/50MB, paused 1.254ms total 67.415ms
,D/Finsky  ( 3525): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3525): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3525): [1] 5.onFinished: Giving up after 6 failures.
,I/GoogleURLConnFactory( 1485): Using platform SSLCertificateSocketFactory
,W/Uploader( 1485): No account for auth token provided
,W/Uploader( 1485): No account for auth token provided
,I/GLSUser ( 1485): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1485): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1485): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1485): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1485): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1485): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1485): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1485): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1485): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1485): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1485): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1485): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1485): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1485): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1485): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1485): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1485): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1485): No account for auth token provided
,I/GLSUser ( 1485): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1485): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1485): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1485): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1485): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1485): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1485): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1485): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1485): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1485): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1485): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1485): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1485): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1485): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1485): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1485): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1485): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1485): No account for auth token provided
,W/Uploader( 1485): No account for auth token provided
,W/Uploader( 1485): No account for auth token provided
,W/Uploader( 1485): No account for auth token provided
,I/GLSUser ( 1485): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1485): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1485): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1485): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1485): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1485): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1485): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1485): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1485): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1485): 	,at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1485): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1485): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1485): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1485): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1485): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1485): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1485): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1485): No account for auth token provided
,W/Uploader( 1485): No account for auth token provided
,W/Uploader( 1485): No account for auth token provided
,W/Uploader( 1485):  no longer exists, so no auth token.
,D/HeadsetStateMachine( 2156): Disconnected process message: 10, size: 0
,I/GLSUser ( 1485): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1485): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1485): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1485): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1485): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1485): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1485): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1485): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1485): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1485): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1485): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1485): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1485): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1485): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1485): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1485): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1485): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/GLSUser ( 1485): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1485): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1485): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1485): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1485): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1485): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1485): 	,at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1485): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1485): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1485): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1485): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1485): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1485): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1485): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1485): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1485): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1485): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,D/HeadsetStateMachine( 2156): Disconnected process message: 10, size: 0
,V/GoogleAuthProtoRequest( 3119): [307] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1485): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1485): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1485): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1485): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3119): [307] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3119): [307] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3119): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3119): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3119): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3119): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3119): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3119): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3119): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3119): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3119): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3119): 	at com.a.a.k.run(SourceFile:110)
,I/Keyboard.Facilitator.LanguageModelFlusher( 1215): run()
I/Keyboard.Facilitator( 1215): flushDynamicLanguageModels()
,I/ConfigService( 1485): onCreate
,V/KeepSync( 3938): Connecting to GoogleApiClient
,I/GLSUser ( 1485): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1485): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1485): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1485): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,V/KeepSync( 3938): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3938): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3938): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3938): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1485): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1485): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1485): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1485): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3938): IOException,
E/KeepSync( 3938): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3938): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3938): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3938): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3938): 	,at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3938): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3938): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3938): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3938): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3938): ,	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3938): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3938): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3938): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.,
E/KeepSync( 3938): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3938): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3938): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140),
E/KeepSync( 3938): 	... 10 more
W/KeepSync( 3938): Sync result 2
D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 201346, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/ConfigService( 1485): onDestroy
,I/BooksSync( 3988): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3988): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1485): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1485): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1485): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1485): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3258): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3258): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3258): 	at jdm.a(PG:82)
E/HttpOperation( 3258): 	at jcs.o(PG:406)
E/HttpOperation( 3258): 	at jcn.a(PG:1379)
E/HttpOperation( 3258): 	at jcs.i(PG:143)
E/HttpOperation( 3258): 	at blb.a(PG:3937)
E/HttpOperation( 3258): 	at czp.a(PG:18188)
E/HttpOperation( 3258): 	at czp.a(PG:9081)
E/HttpOperation( 3258): 	at czq.run(PG:1686)
E/HttpOperation( 3258): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3258): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3258): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3258): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3258): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3258): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3258): 	at jdj.a(PG:4091)
E/HttpOperation( 3258): 	at jdj.a(PG:1125)
E/HttpOperation( 3258): 	at jdm.a(PG:77)
E/HttpOperation( 3258): 	... 12 more
E/HttpOperation( 3258): Caused by: faj: BadAuthentication
E/HttpOperation( 3258): 	at fal.a(PG:38)
E/HttpOperation( 3258): 	at jdj.a(PG:4089)
E/HttpOperation( 3258): 	... 14 more
,I/GLSUser ( 1485): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1485): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1485): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1485): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1485): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1485): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1485): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1485): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3258): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3258): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3258): 	at jdm.a(PG:82)
E/HttpOperation( 3258): 	at jcs.o(PG:406)
E/HttpOperation( 3258): 	at jcn.a(PG:1379)
E/HttpOperation( 3258): 	at jcs.i(PG:143)
E/HttpOperation( 3258): 	at hec.a(PG:42)
E/HttpOperation( 3258): 	at hee.a(PG:102)
E/HttpOperation( 3258): 	at czr.a(PG:65)
E/HttpOperation( 3258): 	at kka.a(PG:108)
E/HttpOperation( 3258): 	at czp.a(PG:19176)
E/HttpOperation( 3258): 	at czp.a(PG:9081)
E/HttpOperation( 3258): 	at czq.run(PG:1686)
E/HttpOperation( 3258): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3258): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3258): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3258): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3258): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3258): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3258): 	at jdj.a(PG:4091)
E/HttpOperation( 3258): 	at jdj.a(PG:1125)
E/HttpOperation( 3258): 	at jdm.a(PG:77)
E/HttpOperation( 3258): 	... 15 more
E/HttpOperation( 3258): Caused by: faj: BadAuthentication
E/HttpOperation( 3258): 	at fal.a(PG:38)
E/HttpOperation( 3258): 	at jdj.a(PG:4089)
E/HttpOperation( 3258): 	... 17 more
E/ExperimentLoader( 3258): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3258): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3258): 	at jdm.a(PG:82)
E/ExperimentLoader( 3258): 	at jcs.o(PG:406)
E/ExperimentLoader( 3258): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3258): 	at jcs.i(PG:143)
E/ExperimentLoader( 3258): 	at hec.a(PG:42)
E/ExperimentLoader( 3258): 	at hee.a(PG:102)
E/ExperimentLoader( 3258): 	at czr.a(PG:65)
E/ExperimentLoader( 3258): 	at kka.a(PG:108)
E/ExperimentLoader( 3258): 	at czp.a(PG:19176)
E/ExperimentLoader( 3258): 	at czp.a(PG:9081)
E/ExperimentLoader( 3258): 	at czq.run(PG:1686)
E/ExperimentLoader( 3258): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3258): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3258): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3258): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3258): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3258): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3258): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3258): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3258): 	at jdm.a(PG:77)
E/ExperimentLoader( 3258): 	... 15 more
E/ExperimentLoader( 3258): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3258): 	at fal.a(PG:38)
E/ExperimentLoader( 3258): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3258): 	... 17 more
,I/GLSUser ( 1485): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1485): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1485): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1485): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3988): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3988): Soft error
E/BooksSync( 3988): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3988): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3988): Sync error
E/BooksSync( 3988): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3988): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3988): Finished books sync
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 230819, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 230127, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager(  822): Start proc 4089:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider
,I/GAv4    ( 4089): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4089):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4089):   adb logcat -s GAv4
,W/GAv4    ( 4089): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4089): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4089): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  822): Killing 3402:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,I/jxcore-log( 3735): --= Surplus to requirements =--
I/jxcore-log( 3735): 
I/jxcore-log( 3735): ****TEST TOOK:  ms ****
I/jxcore-log( 3735): 
I/jxcore-log( 3735): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3735): 
,D/AndroidRuntime( 4121): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,D/AndroidRuntime( 4121): CheckJNI is OFF
,D/AndroidRuntime( 4121): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  822): Force stopping com.test.thalitest appid=10265 user=-1: uninstall pkg
I/ActivityManager(  822): Killing 3735:com.test.thalitest/u0a265 (adj 0): stop com.test.thalitest
,W/PackageSettings(  822): Skipping PackageSetting{3facc392 com.example.hello/10273} due to missing metadata
,E/libprocessgroup(  822): failed to kill 1 processes for processgroup 3735
,W/ActivityManager(  822): Force removing ActivityRecord{24876686 u0 com.test.thalitest/.MainActivity t28}: app died, no saved state
,E/JavaBinder(  822): !!! FAILED BINDER TRANSACTION !!!
,D/WifiService(  822): Client connection lost with reason: 4
,W/WindowManager(  822): Failed looking up window
W/WindowManager(  822): java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@3362d472 does not exist
W/WindowManager(  822): 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8539)
W/WindowManager(  822): 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8530)
W/WindowManager(  822): 	at com.android.server.wm.WindowState$DeathRecipient.binderDied(WindowState.java:1142)
W/WindowManager(  822): 	at android.os.BinderProxy.sendDeathNotice(Binder.java:551)
I/WindowState(  822): WIN DEATH: null
,V/ActivityManager(  822): Display changed displayId=0
,I/ActivityManager(  822): Force stopping com.test.thalitest appid=10265 user=0: pkg removed
,I/InputReader(  822): Reconfiguring input devices.  changes=0x00000010
,I/Keyboard.Facilitator( 1215): resetDictionaries() : en_US
D/TaskPersister(  822): removeObsoleteFile: deleting file=28_task.xml
,D/BuaReceiver( 3420): ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,I/Keyboard.Facilitator.DecoderInitializer( 1215): run()
,I/Decoder ( 1215): createOrResetDecoder
,I/art     ( 1066): Explicit concurrent mark sweep GC freed 57123(2MB) AllocSpace objects, 0(0B) LOS objects, 18% free, 71MB/87MB, paused 1.047ms total 76.782ms
,I/ActivityManager(  822): Start proc 4137:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
I/art     ( 1505): Explicit concurrent mark sweep GC freed 2207(168KB) AllocSpace objects, 0(0B) LOS objects, 22% free, 27MB/35MB, paused 747us total 89.788ms
,I/art     (  822): Explicit concurrent mark sweep GC freed 39422(2033KB) AllocSpace objects, 8(316KB) LOS objects, 31% free, 34MB/50MB, paused 2.122ms total 103.216ms
I/art     (  822): WaitForGcToComplete blocked for 75.860ms for cause Explicit
,I/ContactLocale( 4137): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
I/art     (  822): Explicit concurrent mark sweep GC freed 2654(126KB) AllocSpace objects, 1(110KB) LOS objects, 31% free, 34MB/50MB, paused 1.593ms total 63.755ms
I/art     (  822): WaitForGcToComplete blocked for 58.656ms for cause Explicit
,D/JobSchedulerService(  822): Receieved: android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  822): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,I/art     (  822): Explicit concurrent mark sweep GC freed 1622(72KB) AllocSpace objects, 6(661KB) LOS objects, 32% free, 33MB/49MB, paused 1.255ms total 48.754ms
,W/InputMethodManagerService(  822): Got RemoteException sending setActive(false) notification to pid 3735 uid 10265
,I/ConfigService( 1485): onCreate
,I/Keyboard.Facilitator( 1215): onFinishInput()
,I/art     ( 4121): System.exit called, status: 0
I/AndroidRuntime( 4121): VM exiting with result code 0.
,D/VoicemailCleanupService( 4137): Cleaning up data for package: com.test.thalitest
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1215): run()
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1215): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1215): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1215): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1215): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1215): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1215): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1215): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1215): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1215): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1215): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1215): run()
I/StatsUtilsManager( 1215): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1215): shouldRecordStats() = Too Soon
,I/ActivityManager(  822): Start proc 4162:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,I/art     ( 1292): Explicit concurrent mark sweep GC freed 5708(420KB) AllocSpace objects, 12(1408KB) LOS objects, 31% free, 35MB/51MB, paused 1.958ms total 25.789ms
,W/LocationOracleImpl( 1505): Best location was null
,I/HotwordRecognitionRnr( 1505): Starting hotword detection.
,I/MicrophoneInputStream( 1505): mic_starting com.google.android.apps.gsa.speech.audio.u@33156bc
,I/AudioFlinger(  358): AudioFlinger's thread 0xb4068000 ready to run
,I/SoundTriggerHwService::Module(  358): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,I/MicrophoneInputStream( 1505): mic_started com.google.android.apps.gsa.speech.audio.u@33156bc
,D/audio_hw_primary(  358): select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
,D/msm8974_platform(  358): platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
E/ACDB-LOADER(  358): Error: ACDB AudProc vol returned = -19
D/audio_hw_primary(  358): enable_snd_device: snd_device(55: voice-rec-mic)
,D/audio_hw_primary(  358): enable_audio_route: apply and update mixer path: audio-record
,I/ActivityManager(  822): Start proc 4193:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,W/ContextImpl( 4193): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2609 
,E/SQLiteLog( 4137): (3850) statement aborts at 22: [DELETE FROM deleted_contacts WHERE contact_deleted_timestamp < ?] disk I/O error
--------- beginning of crash
E/AndroidRuntime( 4137): FATAL EXCEPTION: ContactsProviderWorker
E/AndroidRuntime( 4137): Process: android.process.acore, PID: 4137
E/AndroidRuntime( 4137): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4137): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 4137): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 4137): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 4137): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 4137): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/AndroidRuntime( 4137): 	at com.android.providers.contacts.database.DeletedContactsTableUtil.deleteOldLogs(DeletedContactsTableUtil.java:78)
E/AndroidRuntime( 4137): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1730)
E/AndroidRuntime( 4137): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1492)
E/AndroidRuntime( 4137): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4137): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 4137): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/DropBoxManagerService(  822): Can't write: system_app_crash
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
,I/HotwordWorker( 1505): onReady
,E/SQLiteDatabase( 4193): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4193): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4193): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4193): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4193): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4193): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4193): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4193): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4193): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4193): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4193): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4193): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4193): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4193): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4193): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4193): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
E/SQLiteDatabase( 4193): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
E/SQLiteDatabase( 4193): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4193): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4193): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 4193): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/AndroidRuntime( 4193): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4193): Process: com.android.keychain, PID: 4193
E/AndroidRuntime( 4193): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4193): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4193): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 4193): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 4193): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4193): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4193): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4193): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AndroidRuntime( 4193): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AndroidRuntime( 4193): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 4193): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AndroidRuntime( 4193): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 4193): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 4193): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 4193): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
E/AndroidRuntime( 4193): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396,)
E/AndroidRuntime( 4193): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4193): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4193): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 4193): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/OpenGLRenderer(  822): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
D/Atlas   (  822): Validating map...
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
D/Launcher.Workspace( 1292): 11683562 - stripEmptyScreens()
D/Launcher.Workspace( 1292): 11683562 - stripEmptyScreens()
D/WifiService(  822): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@1ba7ac87}
E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-52
E/SQLiteLog( 1485): (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
E/SQLiteLog( 1292): (3850) statement aborts at 24: [DELETE FROM shortcut_and_widget_previews WHERE name LIKE ? OR name LIKE ?] disk I/O error
D/AndroidRuntime( 1485): Shutting down VM
E/AndroidRuntime( 1485): FATAL EXCEPTION: main
E/AndroidRuntime( 1485): Process: com.google.process.gapps, PID: 1485
E/AndroidRuntime( 1485): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1485): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2616)
E/AndroidRuntime( 1485): 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
E/AndroidRuntime( 1485): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1380)
E/AndroidRuntime( 1485): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1485): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 1485): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
E/AndroidRuntime( 1485): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 1485): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 1485): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
E/AndroidRuntime( 1485): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
E/AndroidRuntime( 1485): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1485): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1485): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 1485): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1485): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1485): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/AndroidRuntime( 1485): 	at com.google.android.gms.gcm.bh.a(SourceFile:310)
E/AndroidRuntime( 1485): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:127)
E/AndroidRuntime( 1485): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:321)
E/AndroidRuntime( 1485): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2609)
E/AndroidRuntime( 1485): 	... 9 more
E/DropBoxManagerService(  822): Can't write: system_app_crash
E/DropBoxManagerService(  822): java.io.FileNotFoundException: /data/system/dropbox/drop100.tmp: open failed: EROFS (Read-only file system)
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
,I/OpenGLRenderer(  822): Initialized EGL, version 1.4
D/OpenGLRenderer(  822): Enabling debug mode 0
,I/HotwordDetector( 1505): Closing mic
I/MicrophoneInputStream( 1505): mic_close com.google.android.apps.gsa.speech.audio.u@33156bc
,E/Search.SharedPreferencesProto( 1505): Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
,I/ActivityManager(  822): Killing 3075:com.google.android.music:main/u0a66 (adj 15): empty #17
,D/audio_hw_primary(  358): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  358): disable_snd_device: snd_device(55: voice-rec-mic)
,I/SoundTriggerHwService::Module(  358): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,I/HotwordRecognitionRnr( 1505): Hotword detection finished
I/HotwordRecognitionRnr( 1505): Stopping hotword detection.
,I/qdhwcomposer(  258): handle_blank_event: dpy:0 panel power state: 0

```
