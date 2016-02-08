#### Test 58135655812b57f_thali05_motorola-Nexus 6 Logs


```
--------- beginning of main
I/GAV2    ( 3551): Thread[GAThread,5,main]: No campaign data found.
--------- beginning of system
I/ActivityManager(  822): Killing 3253:com.google.android.apps.fitness/u0a51 (adj 15): empty #17
D/HeadsetStateMachine( 2205): Disconnected process message: 10, size: 0
I/ActivityManager(  822): Killing 3271:com.android.settings/1000 (adj 15): empty #17
,D/AndroidRuntime( 3679): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 3679): CheckJNI is OFF
V/GLSActivity( 1254): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/AndroidRuntime( 3679): Calling main entry com.android.commands.am.Am
I/ActivityManager(  822): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/WindowManager(  822): addAppToken: AppWindowToken{3494e48f token=Token{65c17ee ActivityRecord{17c29169 u0 com.test.thalitest/.MainActivity t28}}} to stack=1 task=28 at 0
V/WindowManager(  822): Adding window Window{385c4508 u0 Starting com.test.thalitest} at 2 of 7 (after Window{23bbb4bc u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
I/HotwordDetector( 1517): Closing mic
I/MicrophoneInputStream( 1517): mic_close com.google.android.apps.gsa.speech.audio.u@1f6324fb
D/AndroidRuntime( 3679): Shutting down VM
D/audio_hw_primary(  358): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  358): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  358): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1517): Hotword detection finished
I/HotwordRecognitionRnr( 1517): Stopping hotword detection.
I/ActivityManager(  822): Start proc 3697:com.test.thalitest/u0a265 for activity com.test.thalitest/.MainActivity
I/art     (  370): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 202us total 9.612ms
I/art     (  370): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 204us total 8.755ms
I/art     (  370): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 211us total 10.872ms
I/ActivityManager(  822): Killing 3288:com.google.android.apps.maps/u0a65 (adj 15): empty #17
E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1722680595
E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,I/WebViewFactory( 3697): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3697): Time to load native libraries: 2 ms (timestamps 8140-8142)
I/LibraryLoader( 3697): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3697): Binding Chromium to main looper Looper (main, tid 1) {370d0a76}
,I/LibraryLoader( 3697): Expected native library version number "",actual native library version number ""
,I/chromium( 3697): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3697): Initializing chromium process, singleProcess=true
,W/art     ( 3697): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3697): ApplicationContext is null in ApplicationStatus
,W/chromium( 3697): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3697): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3697): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3697): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/BluetoothManagerService(  822): Message: 20
D/BluetoothManagerService(  822): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3dc960aa:true
,W/art     ( 3697): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3697): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 3697): CordovaWebView is running on device made by: motorola
,I/art     (  822): Explicit concurrent mark sweep GC freed 20737(1027KB) AllocSpace objects, 4(64KB) LOS objects, 32% free, 33MB/49MB, paused 1.278ms total 60.650ms
,W/art     ( 3697): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3697): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3697): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,D/Atlas   ( 3697): Validating map...
,V/WindowManager(  822): Adding window Window{3b53485a u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{385c4508 u0 Starting com.test.thalitest})
,W/chromium( 3697): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3697): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3697): Enabling debug mode 0
,I/ActivityManager(  822): Displayed com.test.thalitest/.MainActivity: +858ms
,I/Keyboard.Facilitator( 1236): onFinishInput()
,W/BindingManager( 3697): Cannot call determinedVisibility() - never saw a connection for the pid: 3697
,D/JsMessageQueue( 3697): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3697): JniHelper::setJavaVM(0xb489d200), pthread_self() = -1576396672
,I/chromium( 3697): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 3697): Initializing JXcore engine
W/jxcore-log( 3697): JXcore engine is ready
,W/Thread-406( 3751): type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[11951]" dev="sockfs" ino=11951 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-406( 3751): type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,W/Thread-406( 3751): type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[12585]" dev="sockfs" ino=12585 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-406( 3751): type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[22605]" dev="sockfs" ino=22605 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 3697): Starting JXcore engine
,W/jxcore-log( 3697): Platform android
W/jxcore-log( 3697): 
,W/jxcore-log( 3697): Process ARCH arm
W/jxcore-log( 3697): 
,I/jxcore-log( 3697): JXcore Cordova bridge is ready!
,I/jxcore-log( 3697): 
W/jxcore-log( 3697): JXcore engine is started
,I/jxcore-log( 3697): Toggling radios to true
I/jxcore-log( 3697): 
D/BluetoothAdapter( 3697): enable(): BT is already enabled..!
D/WifiService(  822): New client listening to asynchronous messages
D/WifiService(  822): setWifiEnabled: true pid=3697, uid=10265
E/WifiService(  822): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3697): Radios toggled
I/jxcore-log( 3697): 
I/jxcore-log( 3697): My device name is: motorola-Nexus 6
I/jxcore-log( 3697): 
,I/wpa_supplicant( 1141): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  822): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  822): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  354): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1254): Read error: ssl=0xaecdd400: I/O error during system call, Connection timed out
,V/NativeCrypto( 1254): SSL shutdown failed: ssl=0xaecdd400: I/O error during system call, Broken pipe
,D/ConnectivityService(  822): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  822): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,D/ConnectivityService(  822): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10011
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): DefaultState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): Forcing reevaluation
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): EvaluatingState{ when=0 what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
E/WifiStateMachine(  822): Start Disconnecting Watchdog 1
,E/WifiStateMachine(  822): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,D/CommandListener(  354): Clearing all IP addresses on wlan0
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
,D/ConnectivityService(  822): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/CSLegacyTypeTracker(  822): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): OfflineState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 1064): CM callback handler got msg 524292
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): Disconnected - quitting
D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/Tethering(  822): MasterInitialState.processMessage what=3,
,D/NetworkChangeNotifierAutoDetect( 1517): Network connectivity changed, type is: 6,
D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/WifiNetworkAgent(  822): NetworkAgent: NetworkAgent channel lost
,E/WifiStateMachine(  822): CMD_AUTO_CONNECT sup state CompletedState my state DisconnectedState nid=0 roam=3
E/WifiStateMachine(  822): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=0
,I/NetworkMonitor( 3035): type=WIFI subType= reason=null isConnected=false
,D/ConnectivityService(  822): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService(  822): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/ConnectivityService(  822): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
,D/Tethering(  822): MasterInitialState.processMessage what=3
,V/MusicLeanback( 3035): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/PhoneInterfaceManager( 1360): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
,E/PhoneInterfaceManager( 1360): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  822): getDataEnabled: retVal=false
,E/WifiConfigStore(  822): Setting BSSID for "NG7005g"WPA_PSK to any
E/WifiConfigStore(  822): will read network variables netId=0
,I/ActivityManager(  822): Start proc 3758:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,E/WifiStateMachine(  822): CMD_AUTO_CONNECT did save config ->  nid=0
E/WifiConfigStore(  822): will read network variables netId=0
E/GpsLocationProvider(  822): No APN found to select.
,D/PhoneInterfaceManager( 1360): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1360): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  822): getDataEnabled: retVal=false
,E/GpsLocationProvider(  822): No APN found to select.
,D/SprintDMReceiver( 3758): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3758): simOperator:  IMSI: null
D/SprintDMReceiver( 3758): Not Sprint UICC, don't do anything.
,I/ActivityManager(  822): Killing 3372:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,I/SystemUpdateService( 1772): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1772): onCreate
,D/SystemUpdateService( 1772): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1772): active receiver: enabled
,I/SystemUpdateService( 1772): showing system update notification
,I/iu.Environment( 1772): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1772): num queued entries: 0
,I/iu.UploadsManager( 1772): num updated entries: 0
,I/iu.SyncManager( 1772): NEXT; no task
,D/ChimeraCfgMgr( 1772): Loading module com.google.android.gms.kids from APK com.google.android.gms
I/ValidateNoPeople(  822): skipping global notification
,V/SystemUpdateService( 1772): retry (wakeup: false) in 3599983 ms
,I/Kids    ( 1772): [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
,D/SystemUpdateService( 1772): onDestroy
,I/Babel   ( 2775): connection state changed from CONNECTED to DISCONNECTED
,I/ActivityManager(  822): Start proc 3778:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,I/GAv4    ( 3778): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3778):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3778):   adb logcat -s GAv4
,W/GAv4    ( 3778): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3778): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3778): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 3778): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3778): Time to load native libraries: 1 ms (timestamps 1817-1818)
I/LibraryLoader( 3778): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3778): Binding Chromium to main looper Looper (main, tid 1) {141a5255}
,I/LibraryLoader( 3778): Expected native library version number "",actual native library version number ""
I/chromium( 3778): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3778): Initializing chromium process, singleProcess=true
W/art     ( 3778): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3778): ApplicationContext is null in ApplicationStatus
,W/chromium( 3778): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3778): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 3778): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3778): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,W/AudioManagerAndroid( 3778): Requires BLUETOOTH permission
,I/NSApplication( 3778): Starting up...
,I/ActivityManager(  822): Start proc 3834:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,I/ActivityManager(  822): Killing 3392:com.android.musicfx/u0a18 (adj 15): empty #17
,I/ActivityManager(  822): Killing 3441:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,V/MusicLeanback( 3035): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/SprintDMReceiver( 3758): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3758): simOperator:  IMSI: null
,D/SprintDMReceiver( 3758): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1772): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1772): onCreate
,D/SystemUpdateService( 1772): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) },
,I/SystemUpdateService( 1772): active receiver: enabled
,I/SystemUpdateService( 1772): showing system update notification
,I/ValidateNoPeople(  822): skipping global notification
,V/SystemUpdateService( 1772): retry (wakeup: false) in 3599965 ms
,D/ChimeraCfgMgr( 1772): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 1772): [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
,D/SystemUpdateService( 1772): onDestroy
,I/wpa_supplicant( 1141): wlan0: Trying to associate with SSID 'NG7005g'
,I/ActivityManager(  822): Waited long enough for: ServiceRecord{17f7b0f3 u0 com.motorola.android.buacontactadapter/.AuthenticationService}
,I/wpa_supplicant( 1141): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 1141): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1141): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=0 id_str=]
,D/ConnectivityService(  822): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} }
D/ConnectivityService(  822): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiConfigStore(  822): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
E/WifiConfigStore(  822): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/CommandListener(  354): Setting iface cfg
E/WifiStateMachine(  822): Start Dhcp Watchdog 2
E/WifiStateMachine(  822):  WifiLinkLayerStats: 
E/WifiStateMachine(  822):  my bss beacon rx: 177
E/WifiStateMachine(  822):  RSSI mgmt: -55
E/WifiStateMachine(  822):  BE :  rx=224 tx=175 lost=0 retries=0
E/WifiStateMachine(  822):  BK :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  822):  VI :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  822):  VO :  rx=4 tx=0 lost=0 retries=0
E/WifiStateMachine(  822):  on_time : 8723 tx_time=154 rx_time=403 scan_time=0
D/ConnectivityService(  822): updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,E/native  (  822): do suspend false
,E/WifiStateMachine(  822): scanCount==0 - aborting
,I/dhcpcd  ( 3864): version 5.5.6 starting
,I/dhcpcd  ( 3864): wlan0: rebinding lease of 192.168.1.122
,I/ActivityManager(  822): Killing 1457:android.process.acore/u0a5 (adj 15): empty #17
,I/ActivityManager(  822): Killing 3578:com.google.android.gm.exchange/u0a77 (adj 15): empty #18
,I/dhcpcd  ( 3864): wlan0: acknowledged 192.168.1.122 from 192.168.1.1
,I/dhcpcd  ( 3864): wlan0: leased 192.168.1.122 for 86400 seconds
,I/jxcore-log( 3697): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 3697): 
,D/ConnectivityService(  822): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,E/WifiStateMachine(  822): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/ConnectivityService(  822): Adding iface wlan0 to network 101
,E/ConnectivityService(  822): Unexpected mtu value: 0, wlan0
,D/ConnectivityService(  822): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/ConnectivityService(  822): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
D/ConnectivityService(  822): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  822): Setting Dns servers for network 101 to [/192.168.1.1]
,D/ConnectivityService(  822): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  822): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  822): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  822):    accepting network in place of null,
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  822): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  822): Connected
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  822): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  822): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
,D/ConnectivityService(  822): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} }
D/ConnectivityService(  822): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/CSLegacyTypeTracker(  822): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 1064): CM callback handler got msg 524290
,D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  822): MasterInitialState.processMessage what=3,
,I/NetworkMonitor( 3035): type=WIFI subType= reason=null isConnected=true
,D/NetworkChangeNotifierAutoDetect( 1517): Network connectivity changed, type is: 2
,V/MusicLeanback( 3035): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/PhoneInterfaceManager( 1360): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
,E/PhoneInterfaceManager( 1360): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  822): getDataEnabled: retVal=false
,D/SprintDMReceiver( 3758): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,E/GpsLocationProvider(  822): No APN found to select.
,D/SprintDMHelper( 3758): simOperator:  IMSI: null
D/SprintDMReceiver( 3758): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1772): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1772): onCreate
,D/SystemUpdateService( 1772): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1772): active receiver: enabled
,I/SystemUpdateService( 1772): showing system update notification
,D/AlarmManagerService(  822): Setting time of day to sec=1454948629
,W/AlarmManagerService(  822): Unable to set rtc to 1454948629: Invalid argument
I/ActivityManager(  822): Start proc 3904:com.google.android.keep/u0a79 for service com.google.android.keep/.syncadapter.KeepSyncAdapterService
,I/iu.Environment( 1772): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1772): num queued entries: 0
I/iu.UploadsManager( 1772): num updated entries: 0
I/iu.SyncManager( 1772): NEXT; no task
,I/ValidateNoPeople(  822): skipping global notification
,V/SystemUpdateService( 1772): retry (wakeup: false) in 3600639 ms
,D/SystemUpdateService( 1772): onDestroy
,D/ChimeraCfgMgr( 1772): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 1772): [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  822): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 08 Feb 2016 16:23:49 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454948629210], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454948629178]}
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  822): Validated
D/ConnectivityService(  822): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/ConnectivityService(  822): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  822): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  822): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  822): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler( 1064): CM callback handler got msg 524290
D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,I/Babel   ( 2775): connection state changed from DISCONNECTED to CONNECTED
,I/ActivityManager(  822): Start proc 3938:com.qualcomm.timeservice/1000 for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver
,I/GLSUser ( 1254): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1254): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1254): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1254): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1254): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3207): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3207): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3207): 	at jdm.a(PG:82)
E/HttpOperation( 3207): 	at jcs.o(PG:406)
E/HttpOperation( 3207): 	at jcn.a(PG:1379)
E/HttpOperation( 3207): 	at jcs.i(PG:143)
E/HttpOperation( 3207): 	at blb.a(PG:3937)
E/HttpOperation( 3207): 	at czp.a(PG:18188)
E/HttpOperation( 3207): 	at czp.a(PG:9087)
E/HttpOperation( 3207): 	at czq.run(PG:1686)
E/HttpOperation( 3207): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3207): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3207): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3207): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3207): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3207): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3207): 	at jdj.a(PG:4091)
E/HttpOperation( 3207): 	at jdj.a(PG:1125)
E/HttpOperation( 3207): 	at jdm.a(PG:77)
E/HttpOperation( 3207): 	... 12 more
E/HttpOperation( 3207): Caused by: faj: BadAuthentication
E/HttpOperation( 3207): 	at fal.a(PG:38)
E/HttpOperation( 3207): 	at jdj.a(PG:4089)
E/HttpOperation( 3207): 	... 14 more
,D/TimeService( 3938): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1454948629426
D/        ( 3938): TimeServiceNative: User Time to be set is 1454948629426
D/QC-time-services( 3938): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 3938): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 3938): Lib:time_genoff_operation: pargs->ts_val = 1454948629426
D/QC-time-services(  375): Daemon: Connection accepted:time_genoff
,D/QC-time-services( 3938): Lib:time_genoff_operation: Send to server  passed!!
,D/QC-time-services(  375): Daemon:Received base = 2, unit = 1, operation = 0,value = 1454948629426
D/QC-time-services(  375): Daemon:genoff_opr: Base = 2, val = 1454948629426, operation = 0
D/QC-time-services(  375): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS5/26/70 12:36:9
D/QC-time-services(  375): Daemon:Value read from RTC seconds = 15251769000
D/QC-time-services(  375): Daemon:new time 1454948629426 
D/QC-time-services(  375): Daemon: delta 1439696860426 genoff 1439696860426 
D/QC-time-services(  375): Daemon:genoff_persistent_update: Writing genoff = 1439696860426 to memory
D/QC-time-services(  375): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  375): Daemon:time_persistent_memory_opr:Genoff write operation 
,V/KeepSync( 3904): Connecting to GoogleApiClient
,D/QC-time-services(  375): Updating the TOD offset
D/QC-time-services(  375): Daemon:genoff_persistent_update: Writing genoff = 1439696860426 to memory
D/QC-time-services(  375): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  375): Daemon:time_persistent_memory_opr:Genoff write operation 
,E/QC-time-services(  375): Daemon:Update to modem bit set
D/QC-time-services(  375): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  375): Daemon: Base = 2, Value being sent to MODEM = 1138983829426
E/QC-time-services( 3938): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,D/GCM     ( 1254): Connected
,D/GCM     ( 1254): Message class com.google.f.a.a.p
,E/QC-time-services(  375): Daemon: Time-services: Waiting to acceptconnection
,E/QC-time-services(  375): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,I/art     (  822): Explicit concurrent mark sweep GC freed 50913(2MB) AllocSpace objects, 8(128KB) LOS objects, 32% free, 33MB/49MB, paused 1.300ms total 51.697ms
,I/GLSUser ( 1254): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1254): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1254): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1254): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1254): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3207): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3207): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3207): 	at jdm.a(PG:82)
E/HttpOperation( 3207): 	at jcs.o(PG:406)
E/HttpOperation( 3207): 	at jcn.a(PG:1379)
E/HttpOperation( 3207): 	at jcs.i(PG:143)
E/HttpOperation( 3207): 	at blb.a(PG:3937)
E/HttpOperation( 3207): 	at czp.a(PG:18188)
E/HttpOperation( 3207): 	at czp.a(PG:9081)
E/HttpOperation( 3207): 	at czq.run(PG:1686)
E/HttpOperation( 3207): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3207): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3207): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3207): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3207): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3207): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3207): 	at jdj.a(PG:4091)
E/HttpOperation( 3207): 	at jdj.a(PG:1125)
E/HttpOperation( 3207): 	at jdm.a(PG:77)
E/HttpOperation( 3207): 	... 12 more
E/HttpOperation( 3207): Caused by: faj: BadAuthentication
E/HttpOperation( 3207): 	at fal.a(PG:38)
E/HttpOperation( 3207): 	at jdj.a(PG:4089)
E/HttpOperation( 3207): 	... 14 more
,I/ActivityManager(  822): Start proc 3965:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver
,I/GLSUser ( 1254): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1254): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1254): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1254): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1254): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1254): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1254): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1254): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1254): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1254): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3207): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3207): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3207): 	at jdm.a(PG:82)
E/HttpOperation( 3207): 	at jcs.o(PG:406)
E/HttpOperation( 3207): 	at jcn.a(PG:1379)
E/HttpOperation( 3207): 	at jcs.i(PG:143)
E/HttpOperation( 3207): 	at hec.a(PG:42)
E/HttpOperation( 3207): 	at hee.a(PG:102)
E/HttpOperation( 3207): 	at czr.a(PG:65)
E/HttpOperation( 3207): 	at kka.a(PG:108)
E/HttpOperation( 3207): 	at czp.a(PG:19176)
E/HttpOperation( 3207): 	at czp.a(PG:9081)
E/HttpOperation( 3207): 	at czq.run(PG:1686)
E/HttpOperation( 3207): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3207): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3207): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3207): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3207): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3207): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3207): 	at jdj.a(PG:4091)
E/HttpOperation( 3207): 	at jdj.a(PG:1125)
E/HttpOperation( 3207): 	at jdm.a(PG:77)
E/HttpOperation( 3207): 	... 15 more
E/HttpOperation( 3207): Caused by: faj: BadAuthentication
E/HttpOperation( 3207): 	at fal.a(PG:38)
E/HttpOperation( 3207): 	at jdj.a(PG:4089)
E/HttpOperation( 3207): 	... 17 more
E/ExperimentLoader( 3207): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3207): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3207): 	at jdm.a(PG:82)
E/ExperimentLoader( 3207): 	at jcs.o(PG:406)
E/ExperimentLoader( 3207): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3207): 	at jcs.i(PG:143)
E/ExperimentLoader( 3207): 	at hec.a(PG:42)
E/ExperimentLoader( 3207): 	at hee.a(PG:102)
E/ExperimentLoader( 3207): 	at czr.a(PG:65)
E/ExperimentLoader( 3207): 	at kka.a(PG:108)
E/ExperimentLoader( 3207): 	at czp.a(PG:19176)
E/ExperimentLoader( 3207): 	at czp.a(PG:9081)
E/ExperimentLoader( 3207): 	at czq.run(PG:1686)
E/ExperimentLoader( 3207): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3207): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3207): 	,at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3207): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3207): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3207): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3207): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3207): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3207): 	at jdm.a(PG:77)
E/ExperimentLoader( 3207): 	... 15 more
E/ExperimentLoader( 3207): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3207): 	at fal.a(PG:38)
E/ExperimentLoader( 3207): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3207): 	... 17 more
E/ClientConnectionOperation( 1772): Handling authorization failure
E/ClientConnectionOperation( 1772): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1772): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1772): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1772): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1772): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1772): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1772): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1772): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1772): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1772): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1772): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1772): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1772): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1772): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1772): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1772): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1772): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1772): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1772): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1772): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1772): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1772): 	... 7 more
V/KeepSync( 3904): GoogleApiClient failed to connect with error code: 4
E/SQLiteLog( 3904): (284) automatic index on blob_node(is_deleted)
I/jxcore-log( 3697): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 3697): 
E/SQLiteLog( 3904): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3904): (284) automatic index on blob_node(is_deleted)
I/GAv4    ( 3965): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3965):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3965):   adb logcat -s GAv4
,W/GAv4    ( 3965): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3965): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3965): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/jxcore-log( 3697): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 3697): 
,I/jxcore-log( 3697): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 3697): 
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 44059, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,V/Herrevad( 1772): NQAS connected
,I/ActivityManager(  822): Killing 3520:com.google.android.gms:car/u0a11 (adj 15): empty #17
,I/GLSUser ( 1254): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1254): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1254): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1254): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/art     ( 1254): Explicit concurrent mark sweep GC freed 18604(1065KB) AllocSpace objects, 0(0B) LOS objects, 38% free, 25MB/41MB, paused 888us total 21.122ms
,I/jxcore-log( 3697): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 3697): 
,I/jxcore-log( 3697): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 3697): 
,I/jxcore-log( 3697): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 3697): 
,I/jxcore-log( 3697): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 3697): ,
,V/GLSActivity( 1254): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  822): Start proc 3993:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,E/KeepSync( 3904): IOException
E/KeepSync( 3904): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3904): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3904): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3904): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3904): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3904): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3904): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3904): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3904): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3904): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3904): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3904): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3904): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3904): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3904): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3904): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3904): 	... 10 more
W/KeepSync( 3904): Sync result 2
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 74613, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager(  822): Killing 3480:com.android.vending/u0a19 (adj 15): empty #17
,D/ConnectivityService(  822): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,W/GAV2    ( 3993): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/BooksApp( 3993): Created application version: 3.6.8 (30608)
,I/BooksSync( 3993): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3993): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1254): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1254): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1254): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1254): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1254): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1254): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1254): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1254): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1254): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1254): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3993): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3993): Soft error
E/BooksSync( 3993): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3993): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3993): Sync error
E/BooksSync( 3993): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3993): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3993): Finished books sync
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 76088, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
I/ActivityManager(  822): Killing 3551:com.google.android.gm/u0a78 (adj 15): empty #17
,I/ActivityManager(  822): Start proc 4024:com.android.vending/u0a19 for service com.android.vending/com.google.android.finsky.services.ContentSyncService
,D/Finsky  ( 4024): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 4024): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,I/ActivityManager(  822): Start proc 4060:com.google.android.gms:car/u0a11 for service com.google.android.gms/.car.CarService
,W/Settings( 4024): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 4024): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ResourcesManager( 4060): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 4060): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/Finsky  ( 4024): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 4024): [1] 2.run: Finished loading 1 libraries.
,I/MultiDex( 4060): VM with version 2.1.0 has multidex support
I/MultiDex( 4060): install
I/MultiDex( 4060): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 4060): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ProviderInstaller( 4060): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 1254): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1254): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 1772): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/WearableService( 3412): callingUid 10011, callindPid: 3412
,E/MDM     ( 1792): [143] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 1772): Restart initialization of location
,D/Finsky  ( 4024): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 4024): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,V/Finsky  ( 4024): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,I/art     (  822): Explicit concurrent mark sweep GC freed 27792(1286KB) AllocSpace objects, 4(64KB) LOS objects, 32% free, 33MB/49MB, paused 895us total 44.286ms
,V/GLSActivity( 1254): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1254): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1254): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1254): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1254): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1254): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 4024): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 4024): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 4024): [1] 5.onFinished: Scheduling replication attempt 1.
,I/ActivityManager(  822): Killing 3035:com.google.android.music:main/u0a66 (adj 15): empty #17
,D/Finsky  ( 4024): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/GLSActivity( 1254): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1254): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1254): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1254): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1254): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1254): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 4024): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1254): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1254): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1254): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1254): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1254): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1254): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1254): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1254): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1254): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1254): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1254): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1254): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1254): Explicit concurrent mark sweep GC freed 22939(1307KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 1.209ms total 47.265ms
,W/Finsky  ( 4024): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1254): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1254): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1254): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1254): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1254): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1254): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 4024): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 4024): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 4024): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U],
,D/Finsky  ( 4024): [1] DailyHygiene.reschedule: Giving up. (failures=6),
,D/DeviceConnectionService( 1792): client connected with version: 7571000,
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=10.16 rxSuccessRate=16.59 targetRoamBSSID=any RSSI=-55
E/WifiStateMachine(  822): WifiStateMachine L2Connected CMD_START_SCAN source -2 6, 7 -> obsolete
,I/jxcore-log( 3697): Test app app.js loaded
I/jxcore-log( 3697): 
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3697): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3697): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3697): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3697): 	Bluetooth MAC address: F8:CF:C5:D9:E5:61, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3697): 	Discovery mode: BLE_AND_WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3697): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3697): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3697): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3697): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3697): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3248c986 added. We now have 1 listener(s)
,I/jxcore-log( 3697): BLE advertisement is supported
I/jxcore-log( 3697): 
,I/chromium( 3697): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=10.16 rxSuccessRate=16.59 targetRoamBSSID=any RSSI=-55
E/WifiStateMachine(  822): WifiStateMachine L2Connected CMD_START_SCAN source -2 5, 7 -> obsolete
,I/GAV2    ( 3993): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager(  822): Killing 3758:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,I/ActivityManager(  822): Killing 3778:com.google.android.apps.magazines/u0a67 (adj 15): empty #17
,D/Finsky  ( 4024): [425] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,V/GLSActivity( 1254): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1254): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1254): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1254): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1254): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1254): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 4024): [425] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=1.60 rxSuccessRate=7.33 targetRoamBSSID=any RSSI=-55
,V/GLSActivity( 1254): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1254): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1254): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1254): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1254): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1254): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 4024): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 4024): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 4024): [1] 5.onFinished: Scheduling replication attempt 2.
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=1.33 rxSuccessRate=4.43 targetRoamBSSID=any RSSI=-54,
E/WifiStateMachine(  822): WifiStateMachine starting scan for "NG7005g"WPA_PSK with 2412,5220
,V/GLSActivity( 1254): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1254): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1254): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1254): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1254): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1254): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/Finsky  ( 4024): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 4024): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 4024): [1] 5.onFinished: Scheduling replication attempt 3.
,D/HeadsetStateMachine( 2205): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2205): Disconnected process message: 10, size: 0
,I/Keyboard.Facilitator.LanguageModelFlusher( 1236): run()
I/Keyboard.Facilitator( 1236): flushDynamicLanguageModels()
,I/ConfigService( 1254): onCreate
,I/ConfigService( 1254): onDestroy
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.71 rxSuccessRate=2.01 targetRoamBSSID=any RSSI=-54
,V/KeepSync( 3904): Connecting to GoogleApiClient
,I/GLSUser ( 1254): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1254): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1254): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1254): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1254): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1254): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1254): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1254): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1254): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1254): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1772): Handling authorization failure
E/ClientConnectionOperation( 1772): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1772): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1772): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1772): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1772): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1772): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1772): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1772): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1772): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1772): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1772): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1772): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1772): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1772): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1772): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1772): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1772): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1772): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1772): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1772): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1772): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1772): 	... 7 more
,V/KeepSync( 3904): GoogleApiClient failed to connect with error code: 4
E/SQLiteLog( 3904): (284) automatic index on blob_node(is_deleted)
,E/HttpOperation( 3207): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3207): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3207): 	at jdm.a(PG:82)
E/HttpOperation( 3207): 	at jcs.o(PG:406)
E/HttpOperation( 3207): 	at jcn.a(PG:1379)
E/HttpOperation( 3207): 	at jcs.i(PG:143)
E/HttpOperation( 3207): 	at blb.a(PG:3937)
E/HttpOperation( 3207): 	at czp.a(PG:18188)
E/HttpOperation( 3207): 	at czp.a(PG:9081)
E/HttpOperation( 3207): 	at czq.run(PG:1686)
E/HttpOperation( 3207): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3207): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3207): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3207): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3207): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3207): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3207): 	at jdj.a(PG:4091)
E/HttpOperation( 3207): 	at jdj.a(PG:1125)
E/HttpOperation( 3207): 	at jdm.a(PG:77)
E/HttpOperation( 3207): 	... 12 more
E/HttpOperation( 3207): Caused by: faj: BadAuthentication
E/HttpOperation( 3207): 	at fal.a(PG:38)
E/HttpOperation( 3207): 	at jdj.a(PG:4089)
E/HttpOperation( 3207): 	... 14 more
E/SQLiteLog( 3904): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3904): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1254): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1254): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1254): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1254): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1254): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  822): Explicit concurrent mark sweep GC freed 36737(1673KB) AllocSpace objects, 11(364KB) LOS objects, 32% free, 33MB/49MB, paused 1.502ms total 78.179ms
,E/HttpOperation( 3207): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3207): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3207): 	at jdm.a(PG:82)
E/HttpOperation( 3207): 	at jcs.o(PG:406)
E/HttpOperation( 3207): 	at jcn.a(PG:1379)
E/HttpOperation( 3207): 	at jcs.i(PG:143)
E/HttpOperation( 3207): 	at hec.a(PG:42)
E/HttpOperation( 3207): 	at hee.a(PG:102)
E/HttpOperation( 3207): 	at czr.a(PG:65)
E/HttpOperation( 3207): 	at kka.a(PG:108)
E/HttpOperation( 3207): 	at czp.a(PG:19176)
E/HttpOperation( 3207): 	at czp.a(PG:9081)
E/HttpOperation( 3207): 	at czq.run(PG:1686)
E/HttpOperation( 3207): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3207): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3207): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3207): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3207): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3207): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3207): 	at jdj.a(PG:4091)
E/HttpOperation( 3207): 	at jdj.a(PG:1125)
E/HttpOperation( 3207): 	at jdm.a(PG:77)
E/HttpOperation( 3207): 	... 15 more
E/HttpOperation( 3207): Caused by: faj: BadAuthentication
E/HttpOperation( 3207): 	at fal.a(PG:38)
E/HttpOperation( 3207): 	at jdj.a(PG:4089)
E/HttpOperation( 3207): 	... 17 more
E/ExperimentLoader( 3207): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3207): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3207): 	at jdm.a(PG:82)
E/ExperimentLoader( 3207): 	at jcs.o(PG:406)
E/ExperimentLoader( 3207): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3207): 	at jcs.i(PG:143)
E/ExperimentLoader( 3207): 	at hec.a(PG:42)
E/ExperimentLoader( 3207): 	at hee.a(PG:102)
E/ExperimentLoader( 3207): 	at czr.a(PG:65)
E/ExperimentLoader( 3207): 	at kka.a(PG:108)
E/ExperimentLoader( 3207): 	at czp.a(PG:19176)
E/ExperimentLoader( 3207): 	at czp.a(PG:9081)
E/ExperimentLoader( 3207): 	at czq.run(PG:1686)
E/ExperimentLoader( 3207): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3207): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3207): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3207): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3207): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3207): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3207): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3207): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3207): 	at jdm.a(PG:77)
E/ExperimentLoader( 3207): 	... 15 more
E/ExperimentLoader( 3207): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3207): 	at fal.a(PG:38)
E/ExperimentLoader( 3207): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3207): 	... 17 more
,I/GLSUser ( 1254): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1254): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1254): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1254): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1254): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3904): IOException
E/KeepSync( 3904): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3904): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3904): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3904): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3904): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3904): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3904): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3904): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3904): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3904): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3904): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3904): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3904): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3904): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3904): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3904): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3904): 	... 10 more
W/KeepSync( 3904): Sync result 2
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 106936, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/BooksSync( 3993): Starting books sync for 61035162, extras: ade
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 108320, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,I/BooksConfig( 3993): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1254): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1254): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1254): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1254): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1254): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1254): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1254): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1254): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1254): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1254): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3993): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3993): Soft error
E/BooksSync( 3993): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3993): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3993): Sync error
E/BooksSync( 3993): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3993): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3993): Finished books sync
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 109346, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,V/GLSActivity( 1254): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1254): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1254): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1254): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1254): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1254): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 4024): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 4024): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 4024): [1] 5.onFinished: Scheduling replication attempt 4.
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.81 rxSuccessRate=2.43 targetRoamBSSID=any RSSI=-54
,E/WifiStateMachine(  822): WifiStateMachine starting scan for "NG7005g"WPA_PSK with 2412,5220
,V/GLSActivity( 1254): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1254): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1254): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1254): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1254): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1254): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 4024): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 4024): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 4024): [1] 5.onFinished: Scheduling replication attempt 5.
,I/PowerManagerService(  822): Going to sleep due to screen timeout (uid 1000)...
,I/Adreno  (  822): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/PermissionCache(  256): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (311 us)
,I/DisplayManagerService(  822): Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
D/SurfaceFlinger(  256): Set power mode=0, type=0 flinger=0xb6082000
D/qdhwcomposer(  256): hwc_setPowerMode: Setting mode 0 on display: 0
V/ActivityManager(  822): Display changed displayId=0
,I/kickstart(  872): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
,I/kickstart(  872): STATUS: Wrote to /sys/power/wake_lock
,E/kickstart(  872): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2
,I/kickstart(  872): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2' for writing
,I/qdhwcomposer(  256): handle_blank_event: dpy:0 panel power state: 0
,D/qdhwcomposer(  256): hwc_setPowerMode: Done setting mode 0 on display 0
,D/SurfaceControl(  822): Excessive delay in setPowerMode(): 255ms
,I/DreamManagerService(  822): Entering dreamland.
,I/DreamController(  822): Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
I/PowerManagerService(  822): Dozing...,
,D/audio_hw_primary(  358): adev_set_parameters: enter: screen_state=on
D/mot_vr_audio_hw(  358): adev_set_parameters: screen_state=on
,E/WifiStateMachine(  822): cancelDelayedScan -> 12
,E/native  (  822): do suspend false
,I/Keyboard.Facilitator( 1236): onFinishInput()
,E/WifiStateMachine(  822): cancelDelayedScan -> 14
,E/native  (  822): do suspend true
,D/audio_hw_primary(  358): adev_set_parameters: enter: screen_state=off
D/mot_vr_audio_hw(  358): adev_set_parameters: screen_state=off
,I/art     ( 1792): Explicit concurrent mark sweep GC freed 16271(973KB) AllocSpace objects, 8(128KB) LOS objects, 37% free, 26MB/42MB, paused 1.074ms total 41.503ms
,E/DataBuffer( 1792): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@31674b53)
,E/DataBuffer( 1792): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@17208c90)
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-54
E/WifiStateMachine(  822): WifiStateMachine L2Connected CMD_START_SCAN source -2 13, 14 -> obsolete
,I/kickstart(  872): STATUS: Received file 'm9kefs2'
I/kickstart(  872): STATUS: 950272 bytes transferred in 0.980225 seconds
I/kickstart(  872): STATUS: Successfully downloaded files from target 
I/kickstart(  872): STATUS: Wrote to /sys/power/wake_unlock
,I/kickstart(  872): STATUS: Sahara protocol completed
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-54
E/WifiStateMachine(  822): WifiStateMachine L2Connected CMD_START_SCAN source -2 11, 14 -> obsolete
,V/GLSActivity( 1254): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1254): Vacuum at: now=1454948734133 tag=VacuumService
,V/GoogleAuthProtoRequest( 3076): [300] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1254): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1254): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1254): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1254): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1254): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1254): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1254): Explicit concurrent mark sweep GC freed 41774(2MB) AllocSpace objects, 6(661KB) LOS objects, 37% free, 26MB/42MB, paused 2.054ms total 51.742ms
,I/GLSUser ( 1254): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1254): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1254): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1254): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/ExperimentUpdateService( 3076): [300] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
V/GLSActivity( 1254): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3076): [300] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3076): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3076): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3076): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3076): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3076): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3076): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3076): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3076): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3076): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3076): 	at com.a.a.k.run(SourceFile:110)
,D/Finsky  ( 4024): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 4024): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 4024): [1] 5.onFinished: Giving up after 6 failures.
,I/GoogleURLConnFactory( 1254): Using platform SSLCertificateSocketFactory
,W/Uploader( 1254): No account for auth token provided
,W/Uploader( 1254): No account for auth token provided
,I/GLSUser ( 1254): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1254): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1254): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1254): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1254): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1254): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1254): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1254): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
,E/Uploader( 1254): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1254): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1254): 	at com.google.android.gms.auth.p.b(SourceFile:477)
,E/Uploader( 1254): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1254): ,	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1254): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263),
E/Uploader( 1254): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1254): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1254): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1254): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/GLSUser ( 1254): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1254): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1254): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1254): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1254): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1254): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1254): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1254): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1254): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1254): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1254): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1254): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1254): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1254): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1254): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1254): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1254): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1254): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1254): No account for auth token provided
,I/GLSUser ( 1254): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1254): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1254): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1254): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1254): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/Uploader( 1254): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1254): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1254): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1254): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1254): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1254): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1254): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1254): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1254): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1254): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1254): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1254): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1254): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1254): No account for auth token provided
,W/Uploader( 1254): No account for auth token provided
,W/Uploader( 1254): No account for auth token provided
,W/Uploader( 1254): No account for auth token provided
,W/Uploader( 1254): No account for auth token provided,
,W/Uploader( 1254): No account for auth token provided
,W/Uploader( 1254):  no longer exists, so no auth token.
,I/GLSUser ( 1254): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1254): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1254): [GLSUser] Extracting token using key: Auth,
W/GLSActivity( 1254): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1254): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  822): Explicit concurrent mark sweep GC freed 46702(2MB) AllocSpace objects, 11(176KB) LOS objects, 31% free, 34MB/50MB, paused 1.437ms total 104.542ms
,E/Uploader( 1254): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1254): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1254): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1254): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1254): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1254): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1254): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1254): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1254): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1254): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1254): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1254): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1254): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,D/HeadsetStateMachine( 2205): Disconnected process message: 10, size: 0
,V/KeepSync( 3904): Connecting to GoogleApiClient
,I/GLSUser ( 1254): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1254): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1254): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1254): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1254): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1772): Handling authorization failure
E/ClientConnectionOperation( 1772): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1772): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1772): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1772): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1772): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1772): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1772): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1772): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1772): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1772): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1772): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1772): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1772): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1772): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1772): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1772): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1772): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1772): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1772): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1772): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1772): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1772): 	... 7 more
,V/KeepSync( 3904): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3904): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3904): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3904): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1254): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1254): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1254): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1254): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1254): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3904): IOException
E/KeepSync( 3904): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3904): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3904): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3904): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3904): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3904): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3904): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3904): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3904): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3904): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3904): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3904): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3904): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3904): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3904): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3904): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3904): 	... 10 more
W/KeepSync( 3904): Sync result 2
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 196763, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/Keyboard.Facilitator.LanguageModelFlusher( 1236): run()
,I/Keyboard.Facilitator( 1236): flushDynamicLanguageModels()
,V/GoogleAuthProtoRequest( 3076): [301] a.<init>: mAccountName set to: thalitester@gmail.com
,I/ConfigService( 1254): onCreate
,I/GLSUser ( 1254): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1254): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1254): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1254): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1254): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3076): [301] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3076): [301] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3076): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3076): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3076): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3076): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3076): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3076): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3076): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3076): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3076): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3076): 	at com.a.a.k.run(SourceFile:110)
,I/BooksSync( 3993): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3993): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1254): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1254): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1254): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1254): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1254): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1254): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1254): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1254): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1254): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1254): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3207): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3207): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3207): 	at jdm.a(PG:82)
E/HttpOperation( 3207): 	at jcs.o(PG:406)
E/HttpOperation( 3207): 	at jcn.a(PG:1379)
E/HttpOperation( 3207): 	at jcs.i(PG:143)
E/HttpOperation( 3207): 	at blb.a(PG:3937)
E/HttpOperation( 3207): 	at czp.a(PG:18188)
E/HttpOperation( 3207): 	at czp.a(PG:9081)
E/HttpOperation( 3207): 	at czq.run(PG:1686)
E/HttpOperation( 3207): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3207): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3207): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3207): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3207): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3207): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3207): 	at jdj.a(PG:4091)
E/HttpOperation( 3207): 	at jdj.a(PG:1125)
E/HttpOperation( 3207): 	at jdm.a(PG:77)
E/HttpOperation( 3207): 	... 12 more
E/HttpOperation( 3207): Caused by: faj: BadAuthentication
E/HttpOperation( 3207): 	at fal.a(PG:38)
E/HttpOperation( 3207): 	at jdj.a(PG:4089)
E/HttpOperation( 3207): 	... 14 more
,I/GLSUser ( 1254): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1254): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1254): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1254): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,V/GLSActivity( 1254): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1254): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1254): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1254): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1254): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1254): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3207): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3207): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3207): 	at jdm.a(PG:82)
E/HttpOperation( 3207): 	at jcs.o(PG:406)
E/HttpOperation( 3207): 	at jcn.a(PG:1379)
E/HttpOperation( 3207): 	at jcs.i(PG:143)
E/HttpOperation( 3207): 	at hec.a(PG:42)
E/HttpOperation( 3207): 	at hee.a(PG:102)
E/HttpOperation( 3207): 	at czr.a(PG:65)
E/HttpOperation( 3207): 	at kka.a(PG:108)
E/HttpOperation( 3207): 	at czp.a(PG:19176)
E/HttpOperation( 3207): 	at czp.a(PG:9081)
E/HttpOperation( 3207): 	at czq.run(PG:1686)
E/HttpOperation( 3207): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3207): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3207): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3207): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3207): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3207): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3207): 	at jdj.a(PG:4091)
E/HttpOperation( 3207): 	at jdj.a(PG:1125)
E/HttpOperation( 3207): 	at jdm.a(PG:77)
E/HttpOperation( 3207): 	... 15 more
E/HttpOperation( 3207): Caused by: faj: BadAuthentication
E/HttpOperation( 3207): 	at fal.a(PG:38)
E/HttpOperation( 3207): 	at jdj.a(PG:4089)
E/HttpOperation( 3207): 	... 17 more
,E/ExperimentLoader( 3207): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3207): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3207): 	at jdm.a(PG:82)
E/ExperimentLoader( 3207): 	at jcs.o(PG:406)
E/ExperimentLoader( 3207): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3207): 	at jcs.i(PG:143)
E/ExperimentLoader( 3207): 	at hec.a(PG:42)
E/ExperimentLoader( 3207): 	at hee.a(PG:102)
E/ExperimentLoader( 3207): 	at czr.a(PG:65)
E/ExperimentLoader( 3207): 	at kka.a(PG:108)
E/ExperimentLoader( 3207): 	at czp.a(PG:19176)
E/ExperimentLoader( 3207): 	at czp.a(PG:9081)
E/ExperimentLoader( 3207): 	at czq.run(PG:1686)
E/ExperimentLoader( 3207): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3207): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3207): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3207): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3207): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3207): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3207): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3207): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3207): 	at jdm.a(PG:77)
E/ExperimentLoader( 3207): 	... 15 more
E/ExperimentLoader( 3207): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3207): 	at fal.a(PG:38)
E/ExperimentLoader( 3207): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3207): ,	... 17 more
,E/BooksAccountManager( 3993): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3993): Soft error
E/BooksSync( 3993): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3993): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3993): Sync error
E/BooksSync( 3993): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3993): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3993): Finished books sync
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 199993, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 200091, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,I/ConfigService( 1254): onDestroy
,D/HeadsetStateMachine( 2205): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2205): Disconnected process message: 10, size: 0
,I/jxcore-log( 3697): --= Surplus to requirements =--
I/jxcore-log( 3697): 
I/jxcore-log( 3697): ****TEST TOOK:  ms ****
I/jxcore-log( 3697): 
I/jxcore-log( 3697): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3697): 
,D/AndroidRuntime( 4181): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,D/AndroidRuntime( 4181): CheckJNI is OFF
,D/AndroidRuntime( 4181): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  822): Force stopping com.test.thalitest appid=10265 user=-1: uninstall pkg
,I/ActivityManager(  822): Killing 3697:com.test.thalitest/u0a265 (adj 0): stop com.test.thalitest
,W/PackageSettings(  822): Skipping PackageSetting{35f4d7d2 com.example.hello/10273} due to missing metadata
,I/WindowState(  822): WIN DEATH: Window{3b53485a u0 com.test.thalitest/com.test.thalitest.MainActivity}
E/libprocessgroup(  822): failed to kill 1 processes for processgroup 3697
D/WifiService(  822): Client connection lost with reason: 4
,W/ActivityManager(  822): Force removing ActivityRecord{17c29169 u0 com.test.thalitest/.MainActivity t28}: app died, no saved state
,V/ActivityManager(  822): Display changed displayId=0
,I/ActivityManager(  822): Force stopping com.test.thalitest appid=10265 user=0: pkg removed
,I/Keyboard.Facilitator( 1236): resetDictionaries() : en_US
,I/InputReader(  822): Reconfiguring input devices.  changes=0x00000010
D/TaskPersister(  822): removeObsoleteFile: deleting file=28_task.xml
D/BuaReceiver( 3355): ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,I/Keyboard.Facilitator.DecoderInitializer( 1236): run()
,I/Decoder ( 1236): createOrResetDecoder
,I/ActivityManager(  822): Start proc 4196:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,I/art     (  822): Explicit concurrent mark sweep GC freed 31846(1718KB) AllocSpace objects, 11(647KB) LOS objects, 31% free, 34MB/50MB, paused 1.756ms total 65.013ms
I/art     (  822): WaitForGcToComplete blocked for 44.797ms for cause Explicit
I/art     ( 1064): Explicit concurrent mark sweep GC freed 54766(2MB) AllocSpace objects, 0(0B) LOS objects, 18% free, 71MB/87MB, paused 1.421ms total 58.957ms
,I/art     ( 1517): Explicit concurrent mark sweep GC freed 2151(159KB) AllocSpace objects, 0(0B) LOS objects, 22% free, 27MB/35MB, paused 660us total 91.453ms
,I/ConfigService( 1254): onCreate
,W/InputMethodManagerService(  822): Got RemoteException sending setActive(false) notification to pid 3697 uid 10265
,I/Keyboard.Facilitator( 1236): onFinishInput()
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1236): run()
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1236): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1236): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1236): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1236): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1236): run() : Loading LM = history
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1236): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1236): run() : Loading LM = user
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1236): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1236): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1236): run()
,I/Keyboard.Facilitator.RecurringTaskScheduler( 1236): run()
I/StatsUtilsManager( 1236): startPeriodStatsRecorder() : Success
,I/PeriodicStatsRecorder( 1236): shouldRecordStats() = Too Soon
,D/JobSchedulerService(  822): Receieved: android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  822): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
W/LocationOracleImpl( 1517): Best location was null
,I/art     ( 1393): Explicit concurrent mark sweep GC freed 5081(371KB) AllocSpace objects, 12(1408KB) LOS objects, 31% free, 35MB/51MB, paused 1.291ms total 19.924ms
,I/HotwordRecognitionRnr( 1517): Starting hotword detection.
I/MicrophoneInputStream( 1517): mic_starting com.google.android.apps.gsa.speech.audio.u@1c7affcd
,I/AudioFlinger(  358): AudioFlinger's thread 0xb4d54000 ready to run
,I/art     (  822): Explicit concurrent mark sweep GC freed 3076(136KB) AllocSpace objects, 3(330KB) LOS objects, 32% free, 33MB/49MB, paused 6.716ms total 124.863ms
,I/SoundTriggerHwService::Module(  358): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,I/MicrophoneInputStream( 1517): mic_started com.google.android.apps.gsa.speech.audio.u@1c7affcd
,D/VoicemailCleanupService( 4196): Cleaning up data for package: com.test.thalitest
,D/audio_hw_primary(  358): select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
D/msm8974_platform(  358): platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
,E/ACDB-LOADER(  358): Error: ACDB AudProc vol returned = -19
D/audio_hw_primary(  358): enable_snd_device: snd_device(55: voice-rec-mic)
,D/audio_hw_primary(  358): enable_audio_route: apply and update mixer path: audio-record
,I/ActivityManager(  822): Start proc 4230:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,I/art     (  370): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 206us total 11.389ms
,I/art     (  370): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 192us total 9.531ms
,I/art     (  370): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 199us total 8.950ms
,I/ContactLocale( 4196): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/HotwordWorker( 1517): onReady
,I/art     ( 4181): System.exit called, status: 0
I/AndroidRuntime( 4181): VM exiting with result code 0.
,I/ActivityManager(  822): Start proc 4253:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,D/WifiService(  822): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@10f5778d}
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-54
,W/ContextImpl( 4253): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2609 
,E/NetworkScheduler.SchedulerReceiver( 1254): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1254): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1722680595
E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,V/GoogleAuthProtoRequest( 3076): [302] a.<init>: mAccountName set to: thalitester@gmail.com
,D/PackageBroadcastService( 1772): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/ChimeraCfgMgr( 1772): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1772): Module APK com.google.android.play.games already loaded
,D/AccountUtils( 1772): Clearing selected account for com.test.thalitest
,D/ChimeraCfgMgr( 1772): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1772): Module APK com.google.android.play.games already loaded
,D/Launcher.Workspace( 1393): 11683562 - stripEmptyScreens()
D/Launcher.Workspace( 1393): 11683562 - stripEmptyScreens()
,I/UpdateIcingCorporaServi( 1517): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/LocationSettingsChecker( 1772): Removing dialog suppression flag for package com.test.thalitest
,D/GOOGLEHELP_CompatibleDatabase( 1772): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1772): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,D/gH_MetricsDatabase( 1772): 0 metrics were deleted when clearing package com.test.thalitest.
D/GOOGLEHELP_CompatibleDatabase( 1772): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,I/ConfigFetchService( 1772): onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,W/BaseAppContext( 1772): Using Auth Proxy for data requests.
,W/BaseAppContext( 1772): Using Auth Proxy for data requests.
,D/GOOGLEHELP_CompatibleDatabase( 1772): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1772): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/GOOGLEHELP_CompatibleDatabase( 1772): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,I/PeopleContactsSync( 1772): CP2 sync disabled
,E/AppDataSearchHelper( 1517): Exception thrown from onTableChanged
E/AppDataSearchHelper( 1517): java.lang.RuntimeException: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
E/AppDataSearchHelper( 1517): 	at com.google.android.gms.appdatasearch.a.a.a(AppDataSearchDbOpenHelperBase.java:343)
E/AppDataSearchHelper( 1517): 	at com.google.android.gms.appdatasearch.a.a.a(AppDataSearchDbOpenHelperBase.java:261)
E/AppDataSearchHelper( 1517): 	at com.google.android.search.core.icingsync.d.j(InternalIcingCorporaProvider.java:709)
E/AppDataSearchHelper( 1517): 	at com.google.android.search.core.icingsync.d.a(InternalIcingCorporaProvider.java:700)
E/AppDataSearchHelper( 1517): 	at com.google.android.search.core.icingsync.d.i(InternalIcingCorporaProvider.java:627)
E/AppDataSearchHelper( 1517): 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:298)
E/AppDataSearchHelper( 1517): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:328)
E/AppDataSearchHelper( 1517): 	at android.content.ContentResolver.update(ContentResolver.java:1333)
E/AppDataSearchHelper( 1517): 	at com.google.android.search.core.icingsync.e.JA(UpdateIcingCorporaService.java:408)
E/AppDataSearchHelper( 1517): 	at com.google.android.search.core.icingsync.g.aTY(UpdateIcingCorporaService.java:347)
E/AppDataSearchHelper( 1517): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:320)
E/AppDataSearchHelper( 1517): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.ba(UpdateIcingCorporaService.java:215)
E/AppDataSearchHelper( 1517): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:201)
E/AppDataSearchHelper( 1517): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AppDataSearchHelper( 1517): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AppDataSearchHelper( 1517): 	at android.os.Looper.loop(Looper.java:135)
E/AppDataSearchHelper( 1517): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/AppDataSearchHelper( 1517): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
E/AppDataSearchHelper( 1517): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AppDataSearchHelper( 1517): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/AppDataSearchHelper( 1517): 	at android.database.sqlite.SQLiteSession.endTransactionUnchecked(SQLiteSession.java:437)
E/AppDataSearchHelper( 1517): 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:401)
E/AppDataSearchHelper( 1517): 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:522)
E/AppDataSearchHelper( 1517): 	at com.google.android.gms.appdatasearch.a.a.a(AppDataSearchDbOpenHelperBase.java:669)
E/AppDataSearchHelper( 1517): 	at com.google.android.gms.appdatasearch.a.a$1.JA(AppDataSearchDbOpenHelperBase.java:246)
E/AppDataSearchHelper( 1517): 	at com.google.android.gms.appdatasearch.a.a$1.call(AppDataSearchDbOpenHelperBase.java:227)
E/AppDataSearchHelper( 1517): 	at com.google.android.gms.appdatasearch.a.a.a(AppDataSearchDbOpenHelperBase.java:341)
E/AppDataSearchHelper( 1517): 	... 16 more
,W/AppDataSearchHelper( 1517): Table change notification failed for com.google.android.gms.appdatasearch.a.h@be7fd6a1
I/UpdateIcingCorporaServi( 1517): UpdateCorporaTask done [took 69 ms] updated apps [took 69 ms] 
D/GOOGLEHELP_CompatibleDatabase( 1772): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1772): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
E/SQLiteLog( 1772): (3850) statement aborts at 25: [DELETE FROM suggestions WHERE app_package_name="com.test.thalitest"] disk I/O error
,D/GOOGLEHELP_CompatibleDatabase( 1772): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1,
--------- beginning of crash
E/AndroidRuntime( 1772): FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
E/AndroidRuntime( 1772): Process: com.google.android.gms, PID: 1772
E/AndroidRuntime( 1772): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1772): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1772): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 1772): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
,E/AndroidRuntime( 1772): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1772): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/AndroidRuntime( 1772): 	at com.google.android.gms.googlehelp.search.b.e(SourceFile:105)
E/AndroidRuntime( 1772): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:53)
E/AndroidRuntime( 1772): 	,at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 1772): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1772): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 1772): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/Launcher( 1393): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@28c0d949 new=com.google.android.velvet.VelvetApplication@28c0d949
,E/SQLiteLog( 1393): (3850) statement aborts at 24: [DELETE FROM shortcut_and_widget_previews WHERE name LIKE ? OR name LIKE ?] disk I/O error,
,I/GLSUser ( 1254): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova,
I/GLSUser ( 1254): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1254): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1254): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/art     ( 1254): Explicit concurrent mark sweep GC freed 53581(3MB) AllocSpace objects, 9(728KB) LOS objects, 36% free, 27MB/43MB, paused 2.002ms total 43.946ms
,I/ActivityManager(  822): Start proc 4288:com.google.android.apps.docs/u0a46 for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
,V/GLSActivity( 1254): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Icing   ( 1772): doRemovePackageData com.test.thalitest
,W/ResourcesManager(  822): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(  822): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/OpenGLRenderer(  822): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,D/Atlas   (  822): Validating map...
,W/ExperimentUpdateService( 3076): [302] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3076): [302] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3076): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3076): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3076): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3076): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3076): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3076): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3076): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3076): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3076): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3076): 	at com.a.a.k.run(SourceFile:110)
,I/ActivityManager(  822): Killing 3834:com.android.chrome/u0a40 (adj 15): empty #17
,I/OpenGLRenderer(  822): Initialized EGL, version 1.4
,D/OpenGLRenderer(  822): Enabling debug mode 0
,I/HotwordDetector( 1517): Closing mic
I/MicrophoneInputStream( 1517): mic_close com.google.android.apps.gsa.speech.audio.u@1c7affcd
,E/Search.SharedPreferencesProto( 1517): Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
,I/ActivityManager(  822): Killing 3938:com.qualcomm.timeservice/1000 (adj 15): empty #17
,D/audio_hw_primary(  358): disable_audio_route: reset and update mixer path: audio-record
,D/audio_hw_primary(  358): disable_snd_device: snd_device(55: voice-rec-mic)
,I/SoundTriggerHwService::Module(  358): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,I/HotwordRecognitionRnr( 1517): Hotword detection finished
,I/HotwordRecognitionRnr( 1517): Stopping hotword detection.
,I/GAv4    ( 4288): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4288):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4288):   adb logcat -s GAv4
,W/GAv4    ( 4288): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4288): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,E/SharedPreferencesImpl( 4288): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SharedPreferencesImpl( 4288): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/GAv4    ( 4288): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,E/SharedPreferencesImpl( 4288): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/AnalyticsTrackerProxyImpl( 4288): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
,E/SQLiteDatabase( 4288): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 4288): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4288): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4288): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4288): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4288): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4288): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4288): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4288): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4288): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4288): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4288): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4288): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4288): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4288): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4288): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 4288): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 4288): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 4288): 	at fdw.e(Unknown Source)
,E/SQLiteDatabase( 4288): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 4288): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 4288): 	at java.util.concurrent.Executors$RunnableAd,apter.call(Executors.java:422)
E/SQLiteDatabase( 4288): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4288): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4288): 	,at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4288): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 4288): 	at gir$c.run(Unknown Source)
,E/GAv4    ( 4288): Opening the database failed, dropping the table and recreating it
E/SharedPreferencesImpl( 4288): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SQLiteDatabase( 4288): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 4288): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4288): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
,E/SQLiteDatabase( 4288): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4288): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4288): 	,at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4288): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4288): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
,E/SQLiteDatabase( 4288): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4288): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4288): 	,at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4288): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4288): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
,E/SQLiteDatabase( 4288): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4288): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4288): 	,at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 4288): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 4288): 	at fdw.a(Unknown Source)
,E/SQLiteDatabase( 4288): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 4288): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 4288): 	,at feb.run(Unknown Source)
E/SQLiteDatabase( 4288): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4288): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237),
E/SQLiteDatabase( 4288): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4288): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4288): 	at java.lang.Thread.run(Thread.java:818),
E/SQLiteDatabase( 4288): 	at gir$c.run(Unknown Source)
E/GAv4    ( 4288): Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,W/GAv4    ( 4288): Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 4288): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/GAv4    ( 4288): Job execution failed: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 4288): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4288): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SQLiteDatabase( 4288): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4288): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4288): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
,E/SQLiteDatabase( 4288): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4288): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4288): 	,at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4288): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4288): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
,E/SQLiteDatabase( 4288): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4288): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4288): 	,at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4288): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4288): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4288): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4288): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4288): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 4288): 	at ael.a(PG:1521)
E/SQLiteDatabase( 4288): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 4288): 	at aen.run(PG:536)
,E/native  ( 1236): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,E/native  ( 1236): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,W/GAv4    ( 4288): Error opening database: android.database.sqlite.SQLiteException: Database open failed
,E/SharedPreferencesImpl( 4288): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4288): Job execution failed: android.database.sqlite.SQLiteException: Database open failed
,E/native  ( 1236): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1236): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,E/SharedPreferencesImpl( 4288): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SQLiteDatabase( 4288): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4288): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4288): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4288): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4288): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4288): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4288): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4288): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4288): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4288): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4288): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4288): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4288): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4288): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4288): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4288): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 4288): 	at ael.a(PG:1521)
E/SQLiteDatabase( 4288): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 4288): 	at aej.c(PG:139)
E/SQLiteDatabase( 4288): 	at aej.b(PG:398)
E/SQLiteDatabase( 4288): 	at agf.f(PG:417)
E/SQLiteDatabase( 4288): 	at oe.run(PG:1112)
E/SQLiteDatabase( 4288): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4288): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4288): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4288): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4288): 	at java.lang.Thread.run(Thread.java:818)
,E/AbstractDatabaseInstance( 4288): Failed to delete from CachedSearch133
E/AbstractDatabaseInstance( 4288): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.,
E/AbstractDatabaseInstance( 4288): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AbstractDatabaseInstance( 4288): 	,at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AbstractDatabaseInstance( 4288): 	,at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AbstractDatabaseInstance( 4288): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AbstractDatabaseInstance( 4288): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185),
E/AbstractDatabaseInstance( 4288): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AbstractDatabaseInstance( 4288): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
,E/AbstractDatabaseInstance( 4288): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AbstractDatabaseInstance( 4288): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AbstractDatabaseInstance( 4288): 	,at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AbstractDatabaseInstance( 4288): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AbstractDatabaseInstance( 4288): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
,E/AbstractDatabaseInstance( 4288): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AbstractDatabaseInstance( 4288): 	at aev.getWritableDatabase(PG:238)
E/AbstractDatabaseInstance( 4288): 	at ael.a(PG:1521)
E/AbstractDatabaseInstance( 4288): 	at hix$a.a(PG:125)
E/AbstractDatabaseInstance( 4288): 	at aej.c(PG:139)
E/AbstractDatabaseInstance( 4288): ,	at aej.b(PG:398)
E/AbstractDatabaseInstance( 4288): 	at agf.f(PG:417)
E/AbstractDatabaseInstance( 4288): 	,at oe.run(PG:1112)
E/AbstractDatabaseInstance( 4288): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/AbstractDatabaseInstance( 4288): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
,E/AbstractDatabaseInstance( 4288): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AbstractDatabaseInstance( 4288): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AbstractDatabaseInstance( 4288): 	,at java.lang.Thread.run(Thread.java:818)
W/GAv4    ( 4288): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4288): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak,
W/GAv4    ( 4288): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4288): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4288): Failed to commit local dispatch transaction: android.database.sqlite.SQLiteException: Database open failed
,E/SharedPreferencesImpl( 4288): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak,
,E/native  ( 1236): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1236): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp,
E/SharedPreferencesImpl( 4288): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/native  ( 1236): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
,E/native  ( 1236): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
W/GAv4    ( 4288): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4288): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak,
E/GAv4    ( 4288): Sync local dispatch failed: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4288): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/GAv4    ( 4288): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4288): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4288): syncDispatchLocalHits failed: java.util.concurrent.ExecutionException: android.database.sqlite.SQLiteException: Database open failed,
E/SharedPreferencesImpl( 4288): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/CAKEMIX_CRASHED( 4288): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,E/CAKEMIX_CRASHED( 4288): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/CAKEMIX_CRASHED( 4288): 	,at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/CAKEMIX_CRASHED( 4288): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/CAKEMIX_CRASHED( 4288): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/CAKEMIX_CRASHED( 4288): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/CAKEMIX_CRASHED( 4288): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
,E/CAKEMIX_CRASHED( 4288): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/CAKEMIX_CRASHED( 4288): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/CAKEMIX_CRASHED( 4288): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/CAKEMIX_CRASHED( 4288): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/CAKEMIX_CRASHED( 4288): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/CAKEMIX_CRASHED( 4288): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/CAKEMIX_CRASHED( 4288): 	,at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/CAKEMIX_CRASHED( 4288): 	at aev.getWritableDatabase(PG:238)
E/CAKEMIX_CRASHED( 4288): 	at ael.a(PG:1521)
E/CAKEMIX_CRASHED( 4288): 	at hix$a.a(PG:125)
E/CAKEMIX_CRASHED( 4288): 	at aen.run(PG:536)
W/ResourcesManager( 4288): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4288): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 4288): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ActivityManager(  822): Start proc 4327:com.android.documentsui/u0a45 for broadcast com.android.documentsui/.PackageReceiver
,I/ActivityManager(  822): START u0 {act=android.intent.action.BUG_REPORT flg=0x10000000 cmp=com.google.android.apps.docs/.app.ErrorNotificationActivity (has extras)} from uid 10046 on display 0
,V/WindowManager(  822): addAppToken: AppWindowToken{bde3126 token=Token{3ab4ec81 ActivityRecord{122c6068 u0 com.google.android.apps.docs/.app.ErrorNotificationActivity t29}}} to stack=1 task=29 at 0
,I/Process ( 4288): Sending signal. PID: 4288 SIG: 9
,E/lowmemorykiller(  253): Error writing /proc/4288/oom_score_adj; errno=22
,E/JavaBinder(  822): !!! FAILED BINDER TRANSACTION !!!
,W/ActivityManager(  822): Exception when starting activity com.google.android.apps.docs/.app.ErrorNotificationActivity
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
,I/ActivityManager(  822): Start proc 4344:com.google.android.apps.docs/u0a46 for activity com.google.android.apps.docs/.app.ErrorNotificationActivity
,W/ActivityManager(  822): Spurious death for ProcessRecord{3f70f750 4344:com.google.android.apps.docs/u0a46}, curProc for 4288: null
,W/OpenGLRenderer( 1393): Incorrectly called buildLayer on View: ew, destroying layer...
,E/SQLiteDatabase( 4327): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 4327): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4327): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4327): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4327): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4327): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4327): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4327): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4327): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4327): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4327): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4327): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4327): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4327): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4327): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4327): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/SQLiteDatabase( 4327): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/SQLiteDatabase( 4327): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:370)
E/SQLiteDatabase( 4327): 	at android.content.ContentResolver.call(ContentResolver.java:1372)
E/SQLiteDatabase( 4327): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/SQLiteDatabase( 4327): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2609)
E/SQLiteDatabase( 4327): 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
E/SQLiteDatabase( 4327): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1380)
E/SQLiteDatabase( 4327): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4327): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 4327): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
E/SQLiteDatabase( 4327): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 4327): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 4327): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
E/SQLiteDatabase( 4327): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,I/ActivityManager(  822): Killing 3965:com.google.android.deskclock/u0a44 (adj 15): empty #17
D/AndroidRuntime( 4327): Shutting down VM
,E/AndroidRuntime( 4327): FATAL EXCEPTION: main
E/AndroidRuntime( 4327): Process: com.android.documentsui, PID: 4327
E/AndroidRuntime( 4327): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4327): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2616)
E/AndroidRuntime( 4327): 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
E/AndroidRuntime( 4327): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1380)
E/AndroidRuntime( 4327): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4327): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 4327): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
E/AndroidRuntime( 4327): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 4327): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 4327): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
E/AndroidRuntime( 4327): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
E/AndroidRuntime( 4327): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4327): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4327): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 4327): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 4327): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4327): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4327): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4327): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AndroidRuntime( 4327): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AndroidRuntime( 4327): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 4327): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AndroidRuntime( 4327): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 4327): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 4327): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 4327): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/AndroidRuntime( 4327): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/AndroidRuntime( 4327): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:370)
E/AndroidRuntime( 4327): 	at android.content.ContentResolver.call(ContentResolver.java:1372)
E/AndroidRuntime( 4327): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/AndroidRuntime( 4327): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2609)
E/AndroidRuntime( 4327): 	... 9 more
,E/DropBoxManagerService(  822): Can't write: system_app_crash
E/DropBoxManagerService(  822): java.io.FileNotFoundException: /data/system/dropbox/drop101.tmp: open failed: EROFS (Read-only file system)
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
,I/ActivityManager(  822): Start proc 4367:com.android.externalstorage/u0a10 for content provider com.android.externalstorage/.ExternalStorageProvider
,I/ActivityManager(  822): Killing 3233:com.google.android.apps.photos/u0a71 (adj 15): empty #17
,E/SQLiteDatabase( 1254): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 1254): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1254): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1254): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1254): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1254): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1254): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1254): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1254): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1254): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1254): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1254): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 1254): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 1254): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 1254): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1254): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 1254): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:99)
E/SQLiteDatabase( 1254): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/SQLiteDatabase( 1254): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/SQLiteDatabase( 1254): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/SQLiteDatabase( 1254): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 1254): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 1254): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteOpenHelper( 1254): Couldn't open phenotype.db for writing (will try read-only):
E/SQLiteOpenHelper( 1254): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1254): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1254): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 1254): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 1254): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1254): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1254): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1254): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteOpenHelper( 1254): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteOpenHelper( 1254): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 1254): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteOpenHelper( 1254): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 1254): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 1254): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 1254): 	at android.databa,se.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 1254): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:99)
E/SQLiteOpenHelper( 1254): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/SQLiteOpenHelper( 1254): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/SQLiteOpenHelper( 1254): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/SQLiteOpenHelper( 1254): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteOpenHelper( 1254): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteOpenHelper( 1254): 	at java.lang.Thread.run(Thread.java:818)
,W/SQLiteOpenHelper( 1254): Opened phenotype.db in read-only mode
E/SQLiteLog( 1254): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1254): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1254): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1254): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1254): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1254): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1254): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1254): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1254): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1254): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1254): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1254): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1254): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1254): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1254): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteConnection.nati,veExecute(Native Method)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1254): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1254): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1254): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1254): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1254): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1254): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1254): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1254): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1254): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 1254): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
,E/ClearcutLoggerIntentService( 1254): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1254): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1254): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1254): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587),
E/ClearcutLoggerIntentService( 1254): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 1254): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1254): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1254): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1254): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1254): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1254): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 1254): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1254): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1254): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1254): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1254): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1254): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 1254): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1254): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1254): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1254): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1254): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1254): 	at java.lang.Thread.run(Thread.java:818)
I/GAv4    ( 4344): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4344):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4344):   adb logcat -s GAv4
,E/SQLiteLog( 1254): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1254): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1254): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1254): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1254): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1254): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1254): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1254): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1254): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1254): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1254): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1254): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1254): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1254): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1254): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1254): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1254): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1254): 	at java.lang.Thread.run(Thread.java:818)
W/GAv4    ( 4344): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
E/SQLiteLog( 1254): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1254): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1254): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1254): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1254): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1254): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1254): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1254): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1254): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1254): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1254): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1254): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1254): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1254): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1254): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1254): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1254): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1254): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1254): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1254): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1254): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1254): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1254): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1254): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1254): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1254): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1254): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1254): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1254): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1254): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1254): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1254): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1254): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1254): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1254): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1254): 	at java.lang.Thread.run(Thread.java:818)
E/SharedPreferencesImpl( 4344): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4344): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
E/SharedPreferencesImpl( 4344): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SQLiteLog( 1254): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1254): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1254): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1254): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1254): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1254): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1254): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1254): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1254): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1254): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1254): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1254): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 1254): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1254): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1254): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1254): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1254): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1254): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1254): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
W/GAv4    ( 4344): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
E/ClearcutLoggerIntentService( 1254): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1254): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1254): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1254): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1254): 	at java.lang.Thread.run(Thread.java:818)
E/SharedPreferencesImpl( 4344): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SQLiteDatabase( 4344): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 4344): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4344): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4344): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4344): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4344): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4344): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4344): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4344): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4344): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4344): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4344): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4344): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4344): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4344): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4344): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 4344): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 4344): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 4344): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 4344): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 4344): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 4344): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4344): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4344): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4344): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4344): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 4344): 	at gir$c.run(Unknown Source)
E/GAv4    ( 4344): Opening the database failed, dropping the table and recreating it
E/SharedPreferencesImpl( 4344): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SQLiteDatabase( 4344): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 4344): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4344): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4344): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4344): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4344): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4344): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4344): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4344): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4344): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4344): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4344): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4344): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4344): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4344): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4344): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 4344): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 4344): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 4344): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 4344): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 4344): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 4344): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4344): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4344): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4344): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4344): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 4344): 	at gir$c.run(Unknown Source)
E/GAv4    ( 4344): Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 4344): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SQLiteLog( 1254): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1254): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1254): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1254): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1254): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1254): 	at java.lang.Thread.run(Thread.java:818)
W/GAv4    ( 4344): Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 4344): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4344): Job execution failed: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteLog( 1254): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1254): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1254): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1254): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1254): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1254): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1254): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1254): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1254): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1254): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1254): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1254): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1254): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1254): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1254): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1254): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1254): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1254): 	at java.lang.Thread.run(Thread.java:818)
E/SharedPreferencesImpl( 4344): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SQLiteLog( 1254): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1254): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1254): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1254): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1254): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1254): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1254): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1254): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1254): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1254): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1254): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1254): 	at java.lang.Thread.run(Thread.java:818)
W/AnalyticsTrackerProxyImpl( 4344): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
E/SQLiteLog( 1254): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1254): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1254): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1254): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1254): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1254): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1254): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1254): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1254): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1254): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1254): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1254): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1254): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1254): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1254): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1254): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1254): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1254): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1254): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1254): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1254): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1254): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1254): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1254): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1254): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1254): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1254): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1254): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1254): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1254): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1254): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1254): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1254): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1254): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1254): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1254): 	at java.lang.Thread.run(Thread.java:818)
D/ExternalStorage( 4367): After updating volumes, found 1 active roots
E/SQLiteDatabase( 4344): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4344): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4344): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4344): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4344): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4344): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4344): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4344): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4344): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4344): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4344): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4344): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4344): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4344): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4344): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4344): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 4344): 	at ael.a(PG:1521)
E/SQLiteDatabase( 4344): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 4344): 	at aen.run(PG:536)
,E/SQLiteDatabase( 4344): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4344): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4344): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4344): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4344): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4344): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4344): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4344): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4344): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4344): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4344): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4344): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4344): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4344): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4344): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4344): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 4344): 	at ael.a(PG:1521)
E/SQLiteDatabase( 4344): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 4344): 	at aej.c(PG:139)
E/SQLiteDatabase( 4344): 	at aej.b(PG:398)
E/SQLiteDatabase( 4344): 	at agf.f(PG:417)
E/SQLiteDatabase( 4344): 	at oe.run(PG:1112)
E/SQLiteDatabase( 4344): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4344): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4344): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4344): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4344): 	at java.lang.Thread.run(Thread.java:818)
,W/ResourcesManager( 4344): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4344): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/AbstractDatabaseInstance( 4344): Failed to delete from CachedSearch133
E/AbstractDatabaseInstance( 4344): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AbstractDatabaseInstance( 4344): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AbstractDatabaseInstance( 4344): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AbstractDatabaseInstance( 4344): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AbstractDatabaseInstance( 4344): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AbstractDatabaseInstance( 4344): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AbstractDatabaseInstance( 4344): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AbstractDatabaseInstance( 4344): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AbstractDatabaseInstance( 4344): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AbstractDatabaseInstance( 4344): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AbstractDatabaseInstance( 4344): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AbstractDatabaseInstance( 4344): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AbstractDatabaseInstance( 4344): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AbstractDatabaseInstance( 4344): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AbstractDatabaseInstance( 4344): 	at aev.getWritableDatabase(PG:238)
E/AbstractDatabaseInstance( 4344): 	at ael.a(PG:1521)
E/AbstractDatabaseInstance( 4344): 	at hix$a.a(PG:125)
E/AbstractDatabaseInstance( 4344): 	at aej.c(PG:139)
E/AbstractDatabaseInstance( 4344): 	at aej.b(PG:398)
E/AbstractDatabaseInstance( 4344): 	at agf.f(PG:417)
E/AbstractDatabaseInstance( 4344): 	at oe.run(PG:1112)
E/AbstractDatabaseInstance( 4344): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/AbstractDatabaseInstance( 4344): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AbstractDatabaseInstance( 4344): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AbstractDatabaseInstance( 4344): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AbstractDatabaseInstance( 4344): 	at java.lang.Thread.run(Thread.java:818)
,E/ErrorNotificationActivity( 4344): Google Drive has stopped unexpectedly. Please provide additional details to help us diagnose the issue.
,V/JNIHelp ( 4344): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/OpenGLRenderer( 4344): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,D/Atlas   ( 4344): Validating map...
,V/WindowManager(  822): Adding window Window{166f999 u0 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity} at 2 of 9 (after Window{23bbb4bc u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
,V/WindowManager(  822): Adding window Window{3e10803f u0 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity} at 2 of 10 (before Window{166f999 u0 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity})
,W/GAv4    ( 4344): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/GAv4    ( 4344): Job execution failed: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4344): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4344): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/GAv4    ( 4344): Error opening database: android.database.sqlite.SQLiteException: Database open failed
,E/SharedPreferencesImpl( 4344): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/GAv4    ( 4344): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4344): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/GAv4    ( 4344): Failed to commit local dispatch transaction: android.database.sqlite.SQLiteException: Database open failed
,E/SharedPreferencesImpl( 4344): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4344): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/GAv4    ( 4344): Error opening database: android.database.sqlite.SQLiteException: Database open failed
,I/ProviderInstaller( 4344): Installed default security provider GmsCore_OpenSSL
E/SharedPreferencesImpl( 4344): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4344): Sync local dispatch failed: android.database.sqlite.SQLiteException: Database open failed
,E/SharedPreferencesImpl( 4344): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/GAv4    ( 4344): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4344): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/GAv4    ( 4344): syncDispatchLocalHits failed: java.util.concurrent.ExecutionException: android.database.sqlite.SQLiteException: Database open failed
E/CAKEMIX_CRASHED( 4344): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/CAKEMIX_CRASHED( 4344): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/CAKEMIX_CRASHED( 4344): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/CAKEMIX_CRASHED( 4344): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/CAKEMIX_CRASHED( 4344): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/CAKEMIX_CRASHED( 4344): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/CAKEMIX_CRASHED( 4344): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/CAKEMIX_CRASHED( 4344): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/CAKEMIX_CRASHED( 4344): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/CAKEMIX_CRASHED( 4344): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/CAKEMIX_CRASHED( 4344): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/CAKEMIX_CRASHED( 4344): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/CAKEMIX_CRASHED( 4344): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/CAKEMIX_CRASHED( 4344): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/CAKEMIX_CRASHED( 4344): 	at aev.getWritableDatabase(PG:238)
E/CAKEMIX_CRASHED( 4344): 	at ael.a(PG:1521)
E/CAKEMIX_CRASHED( 4344): 	at hix$a.a(PG:125)
E/CAKEMIX_CRASHED( 4344): 	at aen.run(PG:536)
E/SharedPreferencesImpl( 4344): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,I/art     (  822): Explicit concurrent mark sweep GC freed 25482(1337KB) AllocSpace objects, 4(64KB) LOS objects, 31% free, 34MB/50MB, paused 1.590ms total 55.987ms
,I/ActivityManager(  822): START u0 {act=android.intent.action.BUG_REPORT flg=0x10000000 cmp=com.google.android.apps.docs/.app.ErrorNotificationActivity (has extras)} from uid 10046 on display 0
,I/Process ( 4344): Sending signal. PID: 4344 SIG: 9
,D/WifiService(  822): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@10f5778d}
,I/WindowState(  822): WIN DEATH: Window{166f999 u0 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity}
,I/ActivityManager(  822): Process com.google.android.apps.docs (pid 4344) has died
I/ActivityThread( 4327): Removing dead content provider:android.content.ContentProviderProxy@29375802
W/InputDispatcher(  822): channel '3e10803f com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
E/InputDispatcher(  822): channel '3e10803f com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity (server)' ~ Channel is unrecoverably broken and will be disposed!
,W/ActivityManager(  822): Force removing ActivityRecord{122c6068 u0 com.google.android.apps.docs/.app.ErrorNotificationActivity t29}: app died, no saved state
,I/WindowState(  822): WIN DEATH: Window{3e10803f u0 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity}
W/InputDispatcher(  822): Attempted to unregister already unregistered input channel '3e10803f com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity (server)'
,W/Documents( 4327): Failed to load some roots from com.google.android.apps.docs.storage: android.os.DeadObjectException
,D/Documents( 4327): Update found 6 roots in 666ms
,E/SQLiteDatabase( 1254): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 1254): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,E/SQLiteDatabase( 1254): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1254): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1254): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1254): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1254): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1254): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1254): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1254): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1254): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1254): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 1254): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 1254): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 1254): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1254): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 1254): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:99)
E/SQLiteDatabase( 1254): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/SQLiteDatabase( 1254): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
,E/SQLiteDatabase( 1254): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
,E/SQLiteDatabase( 1254): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 1254): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 1254): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteOpenHelper( 1254): Couldn't open phenotype.db for writing (will try read-only):
E/SQLiteOpenHelper( 1254): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1254): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1254): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 1254): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 1254): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1254): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1254): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1254): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteOpenHelper( 1254): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteOpenHelper( 1254): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 1254): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteOpenHelper( 1254): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 1254): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 1254): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 1254): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 1254): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:99)
E/SQLiteOpenHelper( 1254): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/SQLiteOpenHelper( 1254): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/SQLiteOpenHelper( 1254): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/SQLiteOpenHelper( 1254): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteOpenHelper( 1254): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteOpenHelper( 1254): 	at java.lang.Thread.run(Thread.java:818)
,W/SQLiteOpenHelper( 1254): Opened phenotype.db in read-only mode
E/SQLiteLog( 1254): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1254): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1254): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1254): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1254): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1254): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 1254): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1254): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1254): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1254): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1254): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1254): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1254): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1254): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1254): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1254): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1254): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1254): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 1254): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1254): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1254): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1254): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1254): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1254): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1254): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1254): 	at java.lang.Thread.run(Thread.java:818)
,E/Search.SharedPreferencesProto( 1517): Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
,I/ConfigService( 1254): onDestroy
,E/QMI_FW  (  822): xport_send: Sendto failed for port 4352
,E/LocSvc_api_v02(  822): E/locClientSendReq:2446]: send_msg_sync error: -1
E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 11, ind.status = -1722680595
E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
E/QMI_FW  (  822): xport_send: Sendto failed for port 4352,
E/LocSvc_api_v02(  822): E/locClientSendReq:2446]: send_msg_sync error: -1
,E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::injectLocation(GpsExtLocation):857]: error! inject position failed
,I/qdhwcomposer(  256): handle_blank_event: dpy:0 panel power state: 0
,E/kickstart(  872): ERROR: function: rx_data:288 Read/Write File descriptor returned error: No such device, error code -1,
E/kickstart(  872): ERROR: function: sahara_main:1143 Sahara protocol error,
E/kickstart(  872): ERROR: function: main:268 Uploading  Image using Sahara protocol failed
,I/kickstart(  872): STATUS: Wrote to /sys/power/wake_unlock

```
