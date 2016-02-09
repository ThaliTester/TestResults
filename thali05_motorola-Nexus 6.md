#### Test 583805004f2b042_thali05_motorola-Nexus 6 Logs


```
--------- beginning of main
D/HeadsetStateMachine( 2153): Disconnected process message: 10, size: 0
I/MusicLeanback( 3650): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 3650): Stop autocaching.
E/GmsUtils( 3650): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
E/GmsUtils( 3650): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,--------- beginning of system
I/ActivityManager(  818): Killing 3293:com.google.android.keep/u0a79 (adj 15): empty #17
D/AndroidRuntime( 3728): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 3728): CheckJNI is OFF
D/AndroidRuntime( 3728): Calling main entry com.android.commands.am.Am
I/ActivityManager(  818): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/WindowManager(  818): addAppToken: AppWindowToken{312a4720 token=Token{17901623 ActivityRecord{15ed8352 u0 com.test.thalitest/.MainActivity t28}}} to stack=1 task=28 at 0
D/AndroidRuntime( 3728): Shutting down VM
I/MicrophoneInputStream( 1531): mic_close com.google.android.apps.gsa.speech.audio.u@d83770f
I/HotwordDetector( 1531): Closing mic
V/WindowManager(  818): Adding window Window{3de8995 u0 Starting com.test.thalitest} at 2 of 7 (after Window{12f2fb1c u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
I/ActivityManager(  818): Start proc 3742:com.test.thalitest/u0a265 for activity com.test.thalitest/.MainActivity
D/audio_hw_primary(  356): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  356): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  356): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1531): Stopping hotword detection.
I/HotwordRecognitionRnr( 1531): Hotword detection finished
I/ActivityManager(  818): Killing 3315:com.qualcomm.timeservice/1000 (adj 15): empty #17
E/LocSvc_IzatApiV02(  818): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1660753171
E/LocSvc_IzatApiV02(  818): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,I/WebViewFactory( 3742): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3742): Time to load native libraries: 2 ms (timestamps 8550-8552)
I/LibraryLoader( 3742): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3742): Binding Chromium to main looper Looper (main, tid 1) {3bfe9a3e}
I/LibraryLoader( 3742): Expected native library version number "",actual native library version number ""
I/chromium( 3742): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3742): Initializing chromium process, singleProcess=true
W/art     ( 3742): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3742): ApplicationContext is null in ApplicationStatus
W/chromium( 3742): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3742): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3742): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3742): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
D/BluetoothManagerService(  818): Message: 20
D/BluetoothManagerService(  818): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1602386f:true
W/art     ( 3742): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 3742): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 3742): CordovaWebView is running on device made by: motorola
W/art     ( 3742): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3742): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 3742): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
D/Atlas   ( 3742): Validating map...
V/WindowManager(  818): Adding window Window{1f981b5f u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{3de8995 u0 Starting com.test.thalitest})
W/chromium( 3742): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/OpenGLRenderer( 3742): Initialized EGL, version 1.4
D/OpenGLRenderer( 3742): Enabling debug mode 0
I/Keyboard.Facilitator( 1254): onFinishInput()
I/ActivityManager(  818): Displayed com.test.thalitest/.MainActivity: +944ms
W/BindingManager( 3742): Cannot call determinedVisibility() - never saw a connection for the pid: 3742
D/JsMessageQueue( 3742): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 3742): JniHelper::setJavaVM(0xb489d200), pthread_self() = -1576397056
I/chromium( 3742): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 3742): Initializing JXcore engine
W/jxcore-log( 3742): JXcore engine is ready
,W/Thread-417( 3795): type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[12669]" dev="sockfs" ino=12669 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-417( 3795): type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-417( 3795): type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[11612]" dev="sockfs" ino=11612 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-417( 3795): type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[21371]" dev="sockfs" ino=21371 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 3742): Starting JXcore engine
,W/jxcore-log( 3742): Platform android
W/jxcore-log( 3742): 
W/jxcore-log( 3742): Process ARCH arm
W/jxcore-log( 3742): 
,I/jxcore-log( 3742): JXcore Cordova bridge is ready!
I/jxcore-log( 3742): 
W/jxcore-log( 3742): JXcore engine is started
,I/jxcore-log( 3742): Toggling radios to true
I/jxcore-log( 3742): 
,D/BluetoothAdapter( 3742): enable(): BT is already enabled..!
,D/WifiService(  818): setWifiEnabled: true pid=3742, uid=10265,
E/WifiService(  818): Invoking mWifiStateMachine.setWifiEnabled
D/WifiService(  818): New client listening to asynchronous messages
I/jxcore-log( 3742): Radios toggled
I/jxcore-log( 3742): 
I/jxcore-log( 3742): My device name is: motorola-Nexus 6
I/jxcore-log( 3742): 
,I/wpa_supplicant( 1152): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  818): WifiStateMachine: Leaving Connected state
,E/WifiConfigStore(  818): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  352): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1235): Read error: ssl=0xaece3400: I/O error during system call, Connection timed out
,V/NativeCrypto( 1235): SSL shutdown failed: ssl=0xaece3400: I/O error during system call, Broken pipe
,D/ConnectivityService(  818): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  818): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
E/WifiStateMachine(  818): Start Disconnecting Watchdog 1
,D/ConnectivityService(  818): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10011
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  818): ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  818): DefaultState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  818): Forcing reevaluation
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  818): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  818): Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
,E/WifiStateMachine(  818): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,D/CommandListener(  352): Clearing all IP addresses on wlan0
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  818): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
,D/ConnectivityService(  818): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler( 1067): CM callback handler got msg 524292
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  818): OfflineState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  818): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  818): Disconnected - quitting
D/CSLegacyTypeTracker(  818): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  818): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  818): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  818): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  818): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  818): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/Tethering(  818): MasterInitialState.processMessage what=3
D/ConnectivityService(  818): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
,D/WifiNetworkAgent(  818): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine(  818): CMD_AUTO_CONNECT sup state CompletedState my state DisconnectedState nid=0 roam=3
E/WifiStateMachine(  818): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=0
,D/Tethering(  818): MasterInitialState.processMessage what=3
,D/PhoneInterfaceManager( 1336): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1336): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  818): getDataEnabled: retVal=false
,V/MusicLeanback( 3650): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,E/GpsLocationProvider(  818): No APN found to select.
,E/WifiConfigStore(  818): Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiConfigStore(  818): will read network variables netId=0
,I/ActivityManager(  818): Start proc 3803:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,E/WifiStateMachine(  818): CMD_AUTO_CONNECT did save config ->  nid=0
,E/WifiConfigStore(  818): will read network variables netId=0
,D/PhoneInterfaceManager( 1336): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1336): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  818): getDataEnabled: retVal=false
,E/GpsLocationProvider(  818): No APN found to select.
,D/SprintDMReceiver( 3803): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3803): simOperator:  IMSI: null
,D/SprintDMReceiver( 3803): Not Sprint UICC, don't do anything.
,I/ActivityManager(  818): Killing 3352:com.google.android.deskclock/u0a44 (adj 15): empty #17
,I/SystemUpdateService( 1805): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1805): onCreate
,D/SystemUpdateService( 1805): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1805): active receiver: enabled
,I/SystemUpdateService( 1805): showing system update notification
,I/iu.Environment( 1805): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1805): num queued entries: 0
I/iu.UploadsManager( 1805): num updated entries: 0
I/iu.SyncManager( 1805): NEXT; no task
,D/ChimeraCfgMgr( 1805): Loading module com.google.android.gms.kids from APK com.google.android.gms,
I/ValidateNoPeople(  818): skipping global notification
,I/Kids    ( 1805): [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
,I/Babel   ( 2796): connection state changed from CONNECTED to DISCONNECTED
,V/SystemUpdateService( 1805): retry (wakeup: false) in 3599957 ms
,I/ActivityManager(  818): Start proc 3823:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,D/SystemUpdateService( 1805): onDestroy
,I/GAv4    ( 3823): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3823):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3823):   adb logcat -s GAv4
,W/GAv4    ( 3823): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3823): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3823): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 3823): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3823): Time to load native libraries: 2 ms (timestamps 2163-2165)
I/LibraryLoader( 3823): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3823): Binding Chromium to main looper Looper (main, tid 1) {1e997dbd}
,I/LibraryLoader( 3823): Expected native library version number "",actual native library version number ""
,I/chromium( 3823): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3823): Initializing chromium process, singleProcess=true
W/art     ( 3823): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3823): ApplicationContext is null in ApplicationStatus
,W/chromium( 3823): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3823): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3823): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3823): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,W/AudioManagerAndroid( 3823): Requires BLUETOOTH permission
,I/NSApplication( 3823): Starting up...
,I/art     (  818): Explicit concurrent mark sweep GC freed 29510(1485KB) AllocSpace objects, 6(190KB) LOS objects, 32% free, 33MB/49MB, paused 1.440ms total 76.807ms
,I/ActivityManager(  818): Start proc 3880:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,I/ActivityManager(  818): Killing 3405:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,I/ActivityManager(  818): Killing 3425:com.android.musicfx/u0a18 (adj 15): empty #17
,V/MusicLeanback( 3650): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/SprintDMReceiver( 3803): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3803): simOperator:  IMSI: null
,D/SprintDMReceiver( 3803): Not Sprint UICC, don't do anything.
I/SystemUpdateService( 1805): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1805): onCreate
,D/SystemUpdateService( 1805): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
I/SystemUpdateService( 1805): active receiver: enabled
I/SystemUpdateService( 1805): showing system update notification
D/ChimeraCfgMgr( 1805): Loading module com.google.android.gms.kids from APK com.google.android.gms
I/Kids    ( 1805): [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
I/ValidateNoPeople(  818): skipping global notification
,V/SystemUpdateService( 1805): retry (wakeup: false) in 3599978 ms
,D/SystemUpdateService( 1805): onDestroy
,I/wpa_supplicant( 1152): wlan0: Trying to associate with SSID 'NG7005g'
,I/wpa_supplicant( 1152): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 1152): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 1152): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=0 id_str=]
,D/ConnectivityService(  818): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} }
,D/ConnectivityService(  818): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiConfigStore(  818): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any,
,E/WifiConfigStore(  818): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any,
,D/CommandListener(  352): Setting iface cfg
,E/WifiStateMachine(  818): Start Dhcp Watchdog 2
,E/WifiStateMachine(  818):  WifiLinkLayerStats: 
E/WifiStateMachine(  818):  my bss beacon rx: 167
E/WifiStateMachine(  818):  RSSI mgmt: -54
E/WifiStateMachine(  818):  BE :  rx=133 tx=123 lost=0 retries=0
E/WifiStateMachine(  818):  BK :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  818):  VI :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  818):  VO :  rx=6 tx=0 lost=0 retries=0
E/WifiStateMachine(  818):  on_time : 9811 tx_time=201 rx_time=383 scan_time=0
,D/ConnectivityService(  818): updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60,
,E/native  (  818): do suspend false
,E/WifiStateMachine(  818): scanCount==0 - aborting
,I/ActivityManager(  818): Waited long enough for: ServiceRecord{15a3c852 u0 com.motorola.android.buacontactadapter/.AuthenticationService}
,I/dhcpcd  ( 3914): version 5.5.6 starting
,I/dhcpcd  ( 3914): wlan0: rebinding lease of 192.168.1.122
,I/ActivityManager(  818): Killing 2539:android.process.acore/u0a5 (adj 15): empty #17
,I/ActivityManager(  818): Killing 3469:com.google.android.apps.docs/u0a46 (adj 15): empty #18
,I/dhcpcd  ( 3914): wlan0: acknowledged 192.168.1.122 from 192.168.1.1
,I/dhcpcd  ( 3914): wlan0: leased 192.168.1.122 for 86400 seconds,
,I/jxcore-log( 3742): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 3742): 
,D/ConnectivityService(  818): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  818): Adding iface wlan0 to network 101
,E/WifiStateMachine(  818): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  818): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  818): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  818): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
D/ConnectivityService(  818): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  818): Setting Dns servers for network 101 to [/192.168.1.1]
,D/ConnectivityService(  818): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  818): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  818): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  818): Connected
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  818): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  818): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
D/ConnectivityService(  818): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  818):    accepting network in place of null
,D/ConnectivityService(  818): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} }
,D/ConnectivityService(  818): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/CSLegacyTypeTracker(  818): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  818): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 1067): CM callback handler got msg 524290
,D/ConnectivityService(  818): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/PhoneInterfaceManager( 1336): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1336): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
D/TelephonyManager(  818): getDataEnabled: retVal=false
,D/Tethering(  818): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 3650): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 3650): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/SprintDMReceiver( 3803): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,E/GpsLocationProvider(  818): No APN found to select.
,D/SprintDMHelper( 3803): simOperator:  IMSI: null
D/SprintDMReceiver( 3803): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1805): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1805): onCreate
,D/SystemUpdateService( 1805): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1805): active receiver: enabled
,I/SystemUpdateService( 1805): showing system update notification
,I/iu.Environment( 1805): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1805): num queued entries: 0
I/iu.UploadsManager( 1805): num updated entries: 0
,I/iu.SyncManager( 1805): NEXT; no task
,D/ChimeraCfgMgr( 1805): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 1805): [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
,I/ValidateNoPeople(  818): skipping global notification
,V/SystemUpdateService( 1805): retry (wakeup: false) in 3599971 ms
,D/SystemUpdateService( 1805): onDestroy
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  818): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 09 Feb 2016 16:35:42 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1455035742311], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1455035742292]}
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  818): Validated
D/ConnectivityService(  818): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
,D/ConnectivityService(  818): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  818): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  818): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  818): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  818): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1067): CM callback handler got msg 524290
,V/Herrevad( 1805): NQAS connected
,I/Babel   ( 2796): connection state changed from DISCONNECTED to CONNECTED
,D/GCM     ( 1235): Connected
,D/GCM     ( 1235): Message class com.google.f.a.a.p
,I/jxcore-log( 3742): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 3742): 
,I/jxcore-log( 3742): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 3742): 
,I/jxcore-log( 3742): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
,I/jxcore-log( 3742): 
,I/jxcore-log( 3742): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 3742): 
,I/jxcore-log( 3742): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
I/jxcore-log( 3742): 
,D/ConnectivityService(  818): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,V/GLSActivity( 1235): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1235): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1235): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1235): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1235): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1235): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3511): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3511): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3511): [1] 5.onFinished: Scheduling replication attempt 1.
,I/art     ( 1235): Explicit concurrent mark sweep GC freed 30956(1675KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 1.314ms total 37.502ms
,I/jxcore-log( 3742): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 3742): 
,I/jxcore-log( 3742): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js,
I/jxcore-log( 3742): 
,I/jxcore-log( 3742): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 3742): 
,I/jxcore-log( 3742): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 3742): 
,E/WifiStateMachine(  818): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=8.39 rxSuccessRate=8.95 targetRoamBSSID=any RSSI=-54
E/WifiStateMachine(  818): WifiStateMachine L2Connected CMD_START_SCAN source -2 6, 7 -> obsolete
,I/jxcore-log( 3742): Test app app.js loaded
I/jxcore-log( 3742): 
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3742): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3742): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3742): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3742): 	Bluetooth MAC address: F8:CF:C5:D9:E5:61, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3742): 	Discovery mode: BLE_AND_WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3742): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3742): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3742): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3742): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3742): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13bac2a4 added. We now have 1 listener(s)
,I/jxcore-log( 3742): BLE advertisement is supported,
I/jxcore-log( 3742): 
,I/jxcore-log( 3742): TAP version 13,
I/jxcore-log( 3742): 
,I/chromium( 3742): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/jxcore-log( 3742): # setup
I/jxcore-log( 3742): 
I/jxcore-log( 3742): # #generatePreambleAndBeacons null ECDH for local device
I/jxcore-log( 3742): 
,I/jxcore-log( 3742): ok 1 publicKeysToNotify cannot be null,
I/jxcore-log( 3742): 
,I/jxcore-log( 3742): # teardown,
I/jxcore-log( 3742): ,
,I/jxcore-log( 3742): # setup,
,I/jxcore-log( 3742): ,
,I/jxcore-log( 3742): # #generatePreambleAndBeacons null ECDH for local device,
,I/jxcore-log( 3742): ,
,I/jxcore-log( 3742): ok 2 ecdhForLocalDevice cannot be null
I/jxcore-log( 3742): 
I/jxcore-log( 3742): # teardown
I/jxcore-log( 3742): 
I/jxcore-log( 3742): # setup
I/jxcore-log( 3742): 
I/jxcore-log( 3742): # #generatePreambleAndBeacons expiration out of range lower
I/jxcore-log( 3742): 
,I/jxcore-log( 3742): ok 3 secondsUntilExpiration out of range.
I/jxcore-log( 3742): 
,I/jxcore-log( 3742): # teardown
I/jxcore-log( 3742): 
,I/jxcore-log( 3742): # setup
I/jxcore-log( 3742): 
,I/jxcore-log( 3742): # #generatePreambleAndBeacons expiration out of range upper
I/jxcore-log( 3742): 
,I/jxcore-log( 3742): ok 4 secondsUntilExpiration out of range.,
I/jxcore-log( 3742): 
,I/jxcore-log( 3742): # teardown
I/jxcore-log( 3742): 
,I/jxcore-log( 3742): # setup
I/jxcore-log( 3742): 
I/jxcore-log( 3742): # #generatePreambleAndBeacons empty keys to notify
I/jxcore-log( 3742): 
,I/jxcore-log( 3742): ok 5 should be equal
I/jxcore-log( 3742): 
,I/jxcore-log( 3742): # teardown
I/jxcore-log( 3742): 
I/jxcore-log( 3742): # setup
I/jxcore-log( 3742): 
,I/jxcore-log( 3742): # #generatePreambleAndBeacons multiple keys to notify
I/jxcore-log( 3742): 
,I/jxcore-log( 3742): ok 6 should be equal
I/jxcore-log( 3742): 
,I/jxcore-log( 3742): ok 7 should be equal
I/jxcore-log( 3742): 
,I/jxcore-log( 3742): ok 8 should be equal
I/jxcore-log( 3742): 
,I/jxcore-log( 3742): ok 9 should be equal
I/jxcore-log( 3742): 
I/jxcore-log( 3742): # teardown
I/jxcore-log( 3742): 
I/jxcore-log( 3742): # setup
I/jxcore-log( 3742): 
I/jxcore-log( 3742): # #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble
I/jxcore-log( 3742): 
,I/jxcore-log( 3742): ok 10 should throw
I/jxcore-log( 3742): 
I/jxcore-log( 3742): # teardown
I/jxcore-log( 3742): 
I/jxcore-log( 3742): # setup
I/jxcore-log( 3742): 
I/jxcore-log( 3742): # #parseBeacons invalid expiration in beaconStreamWithPreAmble
I/jxcore-log( 3742): 
I/jxcore-log( 3742): ok 11 Preamble expiration must be a 64 bit integer
I/jxcore-log( 3742): 
I/jxcore-log( 3742): # teardown
I/jxcore-log( 3742): 
I/jxcore-log( 3742): # setup
I/jxcore-log( 3742): 
I/jxcore-log( 3742): # #parseBeacons expiration out of range lower,
I/jxcore-log( 3742): 
,I/jxcore-log( 3742): ok 12 Expiration out of range
I/jxcore-log( 3742): 
I/jxcore-log( 3742): # teardown,
I/jxcore-log( 3742): 
I/jxcore-log( 3742): # setup
I/jxcore-log( 3742): 
I/jxcore-log( 3742): # #parseBeacons expiration out of range lower
I/jxcore-log( 3742): 
,I/jxcore-log( 3742): ok 13 Expiration out of range
I/jxcore-log( 3742): 
,I/jxcore-log( 3742): # teardown
I/jxcore-log( 3742): 
,I/jxcore-log( 3742): # setup
I/jxcore-log( 3742): 
I/jxcore-log( 3742): # #parseBeacons no beacons returns null
I/jxcore-log( 3742): 
,I/jxcore-log( 3742): ok 14 should be equal,
I/jxcore-log( 3742): 
I/jxcore-log( 3742): # teardown
I/jxcore-log( 3742): 
,I/jxcore-log( 3742): # setup
I/jxcore-log( 3742): 
,I/jxcore-log( 3742): # #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble
I/jxcore-log( 3742): 
,I/jxcore-log( 3742): ok 15 Malformed encrypted beacon key ID
I/jxcore-log( 3742): 
,I/jxcore-log( 3742): # teardown
I/jxcore-log( 3742): 
I/jxcore-log( 3742): # setup
I/jxcore-log( 3742): 
,I/jxcore-log( 3742): # #parseBeacons addressBookCallback fails decrypt
I/jxcore-log( 3742): 
,I/jxcore-log( 3742): ok 16 should be equal
I/jxcore-log( 3742): ,
I/jxcore-log( 3742): # teardown
I/jxcore-log( 3742): 
I/jxcore-log( 3742): # setup
I/jxcore-log( 3742): 
I/jxcore-log( 3742): # #parseBeacons addressBookCallback returns no matches
I/jxcore-log( 3742): 
,I/jxcore-log( 3742): ok 17 should be equal
I/jxcore-log( 3742): 
,I/jxcore-log( 3742): ok 18 should be equal
I/jxcore-log( 3742): 
I/jxcore-log( 3742): # teardown
I/jxcore-log( 3742): 
I/jxcore-log( 3742): # setup
I/jxcore-log( 3742): 
,I/jxcore-log( 3742): # #parseBeacons addressBookCallback returns public key
I/jxcore-log( 3742): 
,I/jxcore-log( 3742): ok 19 should be equal
I/jxcore-log( 3742): 
I/jxcore-log( 3742): ok 20 (unnamed assert)
I/jxcore-log( 3742): 
,I/jxcore-log( 3742): # teardown,
I/jxcore-log( 3742): 
I/jxcore-log( 3742): # setup
I/jxcore-log( 3742): 
I/jxcore-log( 3742): # #parseBeacons with beacons both for and not for the user
I/jxcore-log( 3742): 
,I/jxcore-log( 3742): ok 21 (unnamed assert)
I/jxcore-log( 3742): ,
I/jxcore-log( 3742): # teardown
I/jxcore-log( 3742): 
,E/WifiStateMachine(  818): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=5.70 rxSuccessRate=5.48 targetRoamBSSID=any RSSI=-54
,E/WifiStateMachine(  818): WifiStateMachine L2Connected CMD_START_SCAN source -2 5, 7 -> obsolete
,E/WifiStateMachine(  818): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=1.17 rxSuccessRate=2.84 targetRoamBSSID=any RSSI=-54
,V/GLSActivity( 1235): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1235): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1235): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1235): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1235): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1235): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3511): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3511): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3511): [1] 5.onFinished: Scheduling replication attempt 2.
,I/ActivityManager(  818): Start proc 3968:com.google.android.keep/u0a79 for service com.google.android.keep/.syncadapter.KeepSyncAdapterService
,I/ActivityManager(  818): Start proc 3985:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,W/GAV2    ( 3985): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/BooksApp( 3985): Created application version: 3.6.8 (30608)
,I/BooksSync( 3985): Starting books sync for 61035162, extras: ade
,V/KeepSync( 3968): Connecting to GoogleApiClient
,I/BooksConfig( 3985): GmsCore Version = 7.8.99 (2134222-430)
,I/art     (  818): Explicit concurrent mark sweep GC freed 49606(2MB) AllocSpace objects, 10(160KB) LOS objects, 32% free, 33MB/49MB, paused 2.057ms total 58.698ms
,I/GLSUser ( 1235): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1235): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1235): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1235): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1235): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1235): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1235): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1235): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1235): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1235): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1805): Handling authorization failure
E/ClientConnectionOperation( 1805): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1805): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1805): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1805): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1805): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1805): 	... 7 more
,V/KeepSync( 3968): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3968): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3968): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3968): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1235): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1235): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1235): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1235): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1235): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3985): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3985): Soft error
E/BooksSync( 3985): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3985): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3985): Sync error
E/BooksSync( 3985): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3985): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3985): Finished books sync
,D/SyncManager(  818): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 76841, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1235): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1235): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1235): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1235): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1235): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3968): IOException
E/KeepSync( 3968): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3968): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3968): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3968): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3968): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3968): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3968): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3968): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3968): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3968): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3968): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3968): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3968): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3968): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3968): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3968): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3968): 	... 10 more
W/KeepSync( 3968): Sync result 2
,D/SyncManager(  818): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 76451, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,I/art     ( 1235): Explicit concurrent mark sweep GC freed 19245(1098KB) AllocSpace objects, 3(330KB) LOS objects, 37% free, 26MB/42MB, paused 1.021ms total 24.058ms
,I/GLSUser ( 1235): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1235): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1235): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1235): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1235): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3250): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3250): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3250): 	at jdm.a(PG:82)
E/HttpOperation( 3250): 	at jcs.o(PG:406)
E/HttpOperation( 3250): 	at jcn.a(PG:1379)
E/HttpOperation( 3250): 	at jcs.i(PG:143)
E/HttpOperation( 3250): 	at blb.a(PG:3937)
E/HttpOperation( 3250): 	at czp.a(PG:18188)
E/HttpOperation( 3250): 	at czp.a(PG:9081)
E/HttpOperation( 3250): 	at czq.run(PG:1686)
E/HttpOperation( 3250): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3250): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3250): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3250): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3250): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3250): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3250): 	at jdj.a(PG:4091)
E/HttpOperation( 3250): 	at jdj.a(PG:1125)
E/HttpOperation( 3250): 	at jdm.a(PG:77)
E/HttpOperation( 3250): 	... 12 more
E/HttpOperation( 3250): Caused by: faj: BadAuthentication
E/HttpOperation( 3250): 	at fal.a(PG:38)
E/HttpOperation( 3250): 	at jdj.a(PG:4089)
E/HttpOperation( 3250): 	... 14 more
,I/GLSUser ( 1235): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1235): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1235): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1235): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1235): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3250): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3250): java.io.IOException: Cannot obtain authentication token
,E/HttpOperation( 3250): 	at jdm.a(PG:82)
E/HttpOperation( 3250): 	at jcs.o(PG:406)
E/HttpOperation( 3250): 	at jcn.a(PG:1379)
E/HttpOperation( 3250): 	at jcs.i(PG:143)
E/HttpOperation( 3250): 	at hec.a(PG:42)
E/HttpOperation( 3250): 	at hee.a(PG:102)
E/HttpOperation( 3250): 	at czr.a(PG:65)
E/HttpOperation( 3250): 	at kka.a(PG:108)
E/HttpOperation( 3250): 	at czp.a(PG:19176)
E/HttpOperation( 3250): 	at czp.a(PG:9081)
E/HttpOperation( 3250): 	at czq.run(PG:1686)
E/HttpOperation( 3250): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3250): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3250): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3250): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
,E/HttpOperation( 3250): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3250): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3250): 	at jdj.a(PG:4091)
E/HttpOperation( 3250): 	at jdj.a(PG:1125)
E/HttpOperation( 3250): 	at jdm.a(PG:77)
E/HttpOperation( 3250): 	... 15 more
E/HttpOperation( 3250): Caused by: faj: BadAuthentication
E/HttpOperation( 3250): 	at fal.a(PG:38)
E/HttpOperation( 3250): 	at jdj.a(PG:4089)
E/HttpOperation( 3250): 	... 17 more
E/ExperimentLoader( 3250): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3250): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3250): 	at jdm.a(PG:82)
E/ExperimentLoader( 3250): 	at jcs.o(PG:406)
E/ExperimentLoader( 3250): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3250): 	at jcs.i(PG:143)
E/ExperimentLoader( 3250): 	at hec.a(PG:42)
E/ExperimentLoader( 3250): 	at hee.a(PG:102)
E/ExperimentLoader( 3250): 	at czr.a(PG:65)
E/ExperimentLoader( 3250): 	at kka.a(PG:108)
E/ExperimentLoader( 3250): 	at czp.a(PG:19176)
E/ExperimentLoader( 3250): 	at czp.a(PG:9081),
E/ExperimentLoader( 3250): 	at czq.run(PG:1686)
E/ExperimentLoader( 3250): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3250): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3250): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3250): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3250): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3250): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3250): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3250): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3250): 	at jdm.a(PG:77)
E/ExperimentLoader( 3250): 	... 15 more
E/ExperimentLoader( 3250): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3250): 	at fal.a(PG:38)
E/ExperimentLoader( 3250): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3250): 	... 17 more
,I/ActivityManager(  818): Killing 3551:com.google.android.gms:car/u0a11 (adj 15): empty #17
,D/SyncManager(  818): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 78025, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager(  818): Killing 3579:com.google.android.gm/u0a78 (adj 15): empty #17
,I/GAV2    ( 3985): Thread[GAThread,5,main]: No campaign data found.
,E/WifiStateMachine(  818): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.72 rxSuccessRate=2.57 targetRoamBSSID=any RSSI=-54
E/WifiStateMachine(  818): WifiStateMachine starting scan for "NG7005g"WPA_PSK with 2412,5220
,D/Finsky  ( 3511): [374] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,V/GLSActivity( 1235): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1235): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1235): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1235): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1235): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1235): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3511): [374] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,V/GLSActivity( 1235): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1235): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1235): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1235): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1235): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1235): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3511): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3511): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3511): [1] 5.onFinished: Scheduling replication attempt 3.
,D/HeadsetStateMachine( 2153): Disconnected process message: 10, size: 0
,I/Keyboard.Facilitator.LanguageModelFlusher( 1254): run()
I/Keyboard.Facilitator( 1254): flushDynamicLanguageModels()
,I/ConfigService( 1235): onCreate
,I/ConfigService( 1235): onDestroy
,E/WifiStateMachine(  818): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.35 rxSuccessRate=1.74 targetRoamBSSID=any RSSI=-53
,V/GLSActivity( 1235): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1235): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1235): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1235): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1235): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1235): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3511): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3511): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3511): [1] 5.onFinished: Scheduling replication attempt 4.
,E/WifiStateMachine(  818): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.91 rxSuccessRate=2.67 targetRoamBSSID=any RSSI=-53
,E/WifiStateMachine(  818): WifiStateMachine starting scan for "NG7005g"WPA_PSK with 2412,5220
,I/PowerManagerService(  818): Going to sleep due to screen timeout (uid 1000)...,
,I/Adreno  (  818): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/PermissionCache(  259): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (328 us)
,I/DisplayManagerService(  818): Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
D/SurfaceFlinger(  259): Set power mode=0, type=0 flinger=0xb6482000
D/qdhwcomposer(  259): hwc_setPowerMode: Setting mode 0 on display: 0
V/ActivityManager(  818): Display changed displayId=0
,I/kickstart(  868): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
I/kickstart(  868): STATUS: Wrote to /sys/power/wake_lock
,E/kickstart(  868): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2
I/kickstart(  868): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2' for writing
,I/qdhwcomposer(  259): handle_blank_event: dpy:0 panel power state: 0
,D/qdhwcomposer(  259): hwc_setPowerMode: Done setting mode 0 on display 0
,D/SurfaceControl(  818): Excessive delay in setPowerMode(): 273ms
,I/DreamManagerService(  818): Entering dreamland.
I/PowerManagerService(  818): Dozing...
I/DreamController(  818): Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,D/audio_hw_primary(  356): adev_set_parameters: enter: screen_state=on
D/mot_vr_audio_hw(  356): adev_set_parameters: screen_state=on
,E/WifiStateMachine(  818): cancelDelayedScan -> 12
,E/native  (  818): do suspend false
,I/Keyboard.Facilitator( 1254): onFinishInput()
,V/GLSActivity( 1235): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/WifiStateMachine(  818): cancelDelayedScan -> 14
,E/native  (  818): do suspend true
,D/audio_hw_primary(  356): adev_set_parameters: enter: screen_state=off,
,D/mot_vr_audio_hw(  356): adev_set_parameters: screen_state=off
,I/GLSUser ( 1235): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1235): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
,I/GLSUser ( 1235): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1235): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,V/GLSActivity( 1235): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3511): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3511): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3511): [1] 5.onFinished: Scheduling replication attempt 5.
,E/WifiStateMachine(  818): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-53
E/WifiStateMachine(  818): WifiStateMachine L2Connected CMD_START_SCAN source -2 13, 14 -> obsolete
,I/kickstart(  868): STATUS: Received file 'm9kefs2'
I/kickstart(  868): STATUS: 950272 bytes transferred in 1.003171 seconds
I/kickstart(  868): STATUS: Successfully downloaded files from target 
I/kickstart(  868): STATUS: Wrote to /sys/power/wake_unlock
,I/kickstart(  868): STATUS: Sahara protocol completed
,I/BooksSync( 3985): Starting books sync for 61035162, extras: ade
,V/KeepSync( 3968): Connecting to GoogleApiClient
,I/art     (  818): Explicit concurrent mark sweep GC freed 54280(2MB) AllocSpace objects, 16(256KB) LOS objects, 31% free, 34MB/50MB, paused 1.469ms total 100.330ms
,I/BooksConfig( 3985): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1235): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1235): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1235): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1235): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1235): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1235): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1235): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1235): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1235): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,V/GLSActivity( 1235): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1805): Handling authorization failure
E/ClientConnectionOperation( 1805): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1805): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1805): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1805): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1805): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1805): 	... 7 more
,V/KeepSync( 3968): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3968): (284) automatic index on blob_node(is_deleted),
,E/SQLiteLog( 3968): (284) automatic index on blob_node(is_deleted),
E/SQLiteLog( 3968): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1235): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1235): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1235): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1235): [GLSUser] Extracting token using key: Auth,
W/GLSActivity( 1235): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1235): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1235): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1235): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1235): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1235): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3985): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3985): Soft error
E/BooksSync( 3985): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3985): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3985): Sync error
E/BooksSync( 3985): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3985): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3985): Finished books sync
,D/SyncManager(  818): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 138531, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,E/KeepSync( 3968): IOException
E/KeepSync( 3968): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3968): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3968): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3968): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3968): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3968): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3968): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3968): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3968): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3968): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3968): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3968): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3968): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3968): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3968): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3968): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3968): 	... 10 more
W/KeepSync( 3968): Sync result 2
,D/SyncManager(  818): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 138770, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1235): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1235): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1235): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1235): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,V/GLSActivity( 1235): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3250): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3250): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3250): 	at jdm.a(PG:82)
E/HttpOperation( 3250): 	at jcs.o(PG:406)
E/HttpOperation( 3250): 	at jcn.a(PG:1379)
E/HttpOperation( 3250): 	at jcs.i(PG:143)
E/HttpOperation( 3250): 	at blb.a(PG:3937)
E/HttpOperation( 3250): 	at czp.a(PG:18188)
E/HttpOperation( 3250): 	at czp.a(PG:9081)
E/HttpOperation( 3250): 	at czq.run(PG:1686)
E/HttpOperation( 3250): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3250): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3250): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3250): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3250): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3250): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3250): 	at jdj.a(PG:4091)
E/HttpOperation( 3250): 	at jdj.a(PG:1125)
E/HttpOperation( 3250): 	at jdm.a(PG:77)
E/HttpOperation( 3250): 	... 12 more
E/HttpOperation( 3250): Caused by: faj: BadAuthentication
E/HttpOperation( 3250): 	at fal.a(PG:38)
E/HttpOperation( 3250): 	at jdj.a(PG:4089)
E/HttpOperation( 3250): 	... 14 more
,I/GLSUser ( 1235): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1235): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1235): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1235): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1235): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3250): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3250): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3250): 	at jdm.a(PG:82)
E/HttpOperation( 3250): 	at jcs.o(PG:406)
E/HttpOperation( 3250): 	at jcn.a(PG:1379)
E/HttpOperation( 3250): 	at jcs.i(PG:143)
E/HttpOperation( 3250): 	at hec.a(PG:42)
E/HttpOperation( 3250): 	at hee.a(PG:102)
E/HttpOperation( 3250): 	at czr.a(PG:65)
,E/HttpOperation( 3250): 	at kka.a(PG:108)
E/HttpOperation( 3250): 	at czp.a(PG:19176)
E/HttpOperation( 3250): 	at czp.a(PG:9081),
E/HttpOperation( 3250): 	at czq.run(PG:1686)
E/HttpOperation( 3250): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3250): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3250): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3250): 	,at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3250): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3250): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3250): 	at jdj.a(PG:4091)
E/HttpOperation( 3250): 	,at jdj.a(PG:1125)
E/HttpOperation( 3250): 	at jdm.a(PG:77)
E/HttpOperation( 3250): 	... 15 more
E/HttpOperation( 3250): Caused by: faj: BadAuthentication,
E/HttpOperation( 3250): 	at fal.a(PG:38)
E/HttpOperation( 3250): 	at jdj.a(PG:4089)
E/HttpOperation( 3250): ,	... 17 more
E/ExperimentLoader( 3250): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token,
E/ExperimentLoader( 3250): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3250): 	at jdm.a(PG:82)
E/ExperimentLoader( 3250): 	at jcs.o(PG:406)
E/ExperimentLoader( 3250): ,	at jcn.a(PG:1379)
E/ExperimentLoader( 3250): 	at jcs.i(PG:143)
E/ExperimentLoader( 3250): 	,at hec.a(PG:42)
E/ExperimentLoader( 3250): 	at hee.a(PG:102)
E/ExperimentLoader( 3250): ,	at czr.a(PG:65)
E/ExperimentLoader( 3250): 	at kka.a(PG:108)
E/ExperimentLoader( 3250): ,	at czp.a(PG:19176)
E/ExperimentLoader( 3250): 	at czp.a(PG:9081)
E/ExperimentLoader( 3250): 	,at czq.run(PG:1686)
E/ExperimentLoader( 3250): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3250): 	,at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3250): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3250): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
,E/ExperimentLoader( 3250): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3250): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3250): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3250): ,	at jdj.a(PG:1125)
E/ExperimentLoader( 3250): 	at jdm.a(PG:77)
E/ExperimentLoader( 3250): 	... 15 more,
E/ExperimentLoader( 3250): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3250): 	at fal.a(PG:38)
E/ExperimentLoader( 3250): 	at jdj.a(PG:4089)
,E/ExperimentLoader( 3250): 	... 17 more
,D/SyncManager(  818): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 139529, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,E/WifiStateMachine(  818): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-53
E/WifiStateMachine(  818): WifiStateMachine L2Connected CMD_START_SCAN source -2 11, 14 -> obsolete
,V/GLSActivity( 1235): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GoogleAuthProtoRequest( 3110): [310] a.<init>: mAccountName set to: thalitester@gmail.com
,I/VacuumService( 1235): Vacuum at: now=1455035850707 tag=VacuumService
,I/GLSUser ( 1235): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1235): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1235): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1235): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1235): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3110): [310] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3110): [310] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3110): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3110): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3110): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3110): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3110): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3110): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3110): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3110): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3110): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3110): 	at com.a.a.k.run(SourceFile:110)
,V/GLSActivity( 1235): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1235): Explicit concurrent mark sweep GC freed 43697(2MB) AllocSpace objects, 6(661KB) LOS objects, 37% free, 26MB/42MB, paused 1.280ms total 53.495ms
,I/GoogleURLConnFactory( 1235): Using platform SSLCertificateSocketFactory
,I/GLSUser ( 1235): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1235): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1235): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1235): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1235): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3511): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3511): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3511): [1] 5.onFinished: Giving up after 6 failures.
,I/GLSUser ( 1235): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1235): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1235): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1235): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1235): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1235): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1235): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1235): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1235): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1235): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1235): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1235): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1235): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1235): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1235): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1235): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1235): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1235): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,D/HeadsetStateMachine( 2153): Disconnected process message: 10, size: 0
,W/Uploader( 1235): No account for auth token provided
,W/Uploader( 1235): No account for auth token provided
,I/GLSUser ( 1235): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1235): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1235): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1235): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1235): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1235): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1235): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1235): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1235): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1235): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1235): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1235): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1235): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1235): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1235): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1235): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1235): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1235): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1235): No account for auth token provided
,W/Uploader( 1235): No account for auth token provided,
,W/Uploader( 1235): No account for auth token provided
,I/GLSUser ( 1235): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1235): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1235): [GLSUser] Extracting token using key: Auth,
W/GLSActivity( 1235): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1235): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1235): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1235): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1235): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1235): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1235): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1235): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1235): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1235): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1235): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1235): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1235): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1235): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1235): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1235): No account for auth token provided
,W/Uploader( 1235): No account for auth token provided
,W/Uploader( 1235): No account for auth token provided
,W/Uploader( 1235): No account for auth token provided
,W/Uploader( 1235): No account for auth token provided
,W/Uploader( 1235):  no longer exists, so no auth token.,
,I/GLSUser ( 1235): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1235): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1235): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1235): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1235): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1235): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1235): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1235): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1235): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1235): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1235): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1235): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1235): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1235): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1235): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1235): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1235): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1235): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/GLSUser ( 1235): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1235): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1235): [GLSUser] Extracting token using key: Auth,
,W/GLSActivity( 1235): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1235): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1235): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1235): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1235): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1235): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1235): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1235): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1235): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1235): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1235): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1235): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1235): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1235): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1235): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,D/HeadsetStateMachine( 2153): Disconnected process message: 10, size: 0
,V/GoogleAuthProtoRequest( 3110): [311] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1235): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1235): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1235): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1235): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1235): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3110): [311] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3110): [311] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.,
W/ExperimentUpdateService( 3110): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3110): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3110): 	at com.a.a.a.k.get(SourceFile:97)
,W/ExperimentUpdateService( 3110): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3110): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3110): Caused by: com.a.a.a: User needs to (re)enter credentials.
,W/ExperimentUpdateService( 3110): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3110): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3110): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3110): 	at com.a.a.k.run(SourceFile:110)
,I/Keyboard.Facilitator.LanguageModelFlusher( 1254): run()
I/Keyboard.Facilitator( 1254): flushDynamicLanguageModels()
,I/ConfigService( 1235): onCreate
,I/ConfigService( 1235): onDestroy,
,I/BooksSync( 3985): Starting books sync for 61035162, extras: ade
,I/art     (  818): Explicit concurrent mark sweep GC freed 37299(1637KB) AllocSpace objects, 5(268KB) LOS objects, 31% free, 34MB/50MB, paused 2.533ms total 94.685ms
,I/BooksConfig( 3985): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1235): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1235): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1235): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1235): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1235): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1235): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1235): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
,I/GLSUser ( 1235): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1235): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1235): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3985): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3985): Soft error
E/BooksSync( 3985): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3985): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3985): Sync error
E/BooksSync( 3985): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3985): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3985): Finished books sync
,D/SyncManager(  818): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 230515, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,V/KeepSync( 3968): Connecting to GoogleApiClient
,I/GLSUser ( 1235): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1235): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1235): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1235): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1235): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1805): Handling authorization failure
E/ClientConnectionOperation( 1805): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1805): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1805): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1805): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1805): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1805): 	... 7 more
,V/KeepSync( 3968): GoogleApiClient failed to connect with error code: 4
E/SQLiteLog( 3968): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3968): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3968): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1235): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1235): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1235): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1235): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1235): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3968): IOException
E/KeepSync( 3968): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3968): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3968): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3968): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3968): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3968): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3968): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3968): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3968): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3968): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3968): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3968): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3968): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3968): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3968): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3968): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3968): 	... 10 more
W/KeepSync( 3968): Sync result 2
,D/SyncManager(  818): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 230848, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2153): Disconnected process message: 10, size: 0
,I/GLSUser ( 1235): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1235): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1235): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1235): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1235): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3250): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3250): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3250): 	at jdm.a(PG:82)
E/HttpOperation( 3250): 	at jcs.o(PG:406)
E/HttpOperation( 3250): 	at jcn.a(PG:1379)
E/HttpOperation( 3250): 	at jcs.i(PG:143)
E/HttpOperation( 3250): 	at blb.a(PG:3937)
E/HttpOperation( 3250): 	at czp.a(PG:18188)
E/HttpOperation( 3250): 	at czp.a(PG:9081)
E/HttpOperation( 3250): 	at czq.run(PG:1686)
E/HttpOperation( 3250): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3250): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3250): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3250): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3250): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3250): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3250): 	at jdj.a(PG:4091)
E/HttpOperation( 3250): 	at jdj.a(PG:1125)
E/HttpOperation( 3250): 	at jdm.a(PG:77)
E/HttpOperation( 3250): 	... 12 more
E/HttpOperation( 3250): Caused by: faj: BadAuthentication
E/HttpOperation( 3250): 	at fal.a(PG:38)
E/HttpOperation( 3250): 	at jdj.a(PG:4089)
E/HttpOperation( 3250): 	... 14 more
,I/GLSUser ( 1235): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1235): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1235): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1235): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1235): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3250): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3250): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3250): 	at jdm.a(PG:82)
E/HttpOperation( 3250): 	at jcs.o(PG:406)
E/HttpOperation( 3250): 	at jcn.a(PG:1379)
E/HttpOperation( 3250): 	at jcs.i(PG:143)
E/HttpOperation( 3250): 	at hec.a(PG:42)
E/HttpOperation( 3250): 	at hee.a(PG:102)
E/HttpOperation( 3250): 	at czr.a(PG:65)
E/HttpOperation( 3250): 	at kka.a(PG:108)
E/HttpOperation( 3250): 	at czp.a(PG:19176)
E/HttpOperation( 3250): 	at czp.a(PG:9081)
E/HttpOperation( 3250): 	at czq.run(PG:1686)
E/HttpOperation( 3250): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3250): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3250): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3250): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3250): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3250): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3250): 	at jdj.a(PG:4091)
E/HttpOperation( 3250): 	at jdj.a(PG:1125)
E/HttpOperation( 3250): 	at jdm.a(PG:77)
E/HttpOperation( 3250): 	... 15 more
E/HttpOperation( 3250): Caused by: faj: BadAuthentication
E/HttpOperation( 3250): 	at fal.a(PG:38)
E/HttpOperation( 3250): 	at jdj.a(PG:4089)
E/HttpOperation( 3250): 	... 17 more
E/ExperimentLoader( 3250): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3250): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3250): 	at jdm.a(PG:82)
E/ExperimentLoader( 3250): 	at jcs.o(PG:406)
E/ExperimentLoader( 3250): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3250): 	at jcs.i(PG:143)
E/ExperimentLoader( 3250): 	at hec.a(PG:42)
E/ExperimentLoader( 3250): 	at hee.a(PG:102)
E/ExperimentLoader( 3250): 	at czr.a(PG:65)
E/ExperimentLoader( 3250): 	at kka.a(PG:108)
E/ExperimentLoader( 3250): 	at czp.a(PG:19176)
E/ExperimentLoader( 3250): 	at czp.a(PG:9081)
E/ExperimentLoader( 3250): 	at czq.run(PG:1686)
E/ExperimentLoader( 3250): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3250): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3250): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3250): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3250): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3250): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3250): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3250): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3250): 	at jdm.a(PG:77)
E/ExperimentLoader( 3250): 	... 15 more
E/ExperimentLoader( 3250): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3250): 	at fal.a(PG:38)
E/ExperimentLoader( 3250): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3250): 	... 17 more
,D/SyncManager(  818): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 231491, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/jxcore-log( 3742): --= Surplus to requirements =--
I/jxcore-log( 3742): 
I/jxcore-log( 3742): ****TEST TOOK:  ms ****
I/jxcore-log( 3742): 
,I/jxcore-log( 3742): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3742): 
,D/AndroidRuntime( 4107): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,D/AndroidRuntime( 4107): CheckJNI is OFF
,D/AndroidRuntime( 4107): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  818): Force stopping com.test.thalitest appid=10265 user=-1: uninstall pkg
,I/ActivityManager(  818): Killing 3742:com.test.thalitest/u0a265 (adj 0): stop com.test.thalitest
,I/WindowState(  818): WIN DEATH: Window{1f981b5f u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  818): Client connection lost with reason: 4
,W/PackageSettings(  818): Skipping PackageSetting{1fa30a1a com.example.hello/10273} due to missing metadata
,E/libprocessgroup(  818): failed to kill 1 processes for processgroup 3742
W/ActivityManager(  818): Force removing ActivityRecord{15ed8352 u0 com.test.thalitest/.MainActivity t28}: app died, no saved state
,V/ActivityManager(  818): Display changed displayId=0
,I/ActivityManager(  818): Force stopping com.test.thalitest appid=10265 user=0: pkg removed
,W/ActivityManager(  818): Spurious death for ProcessRecord{1c27fa98 3742:com.test.thalitest/u0a265}, curProc for 3742: null
D/TaskPersister(  818): removeObsoleteFile: deleting file=28_task.xml
,D/BuaReceiver( 3388): ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,I/Keyboard.Facilitator( 1254): resetDictionaries() : en_US
I/InputReader(  818): Reconfiguring input devices.  changes=0x00000010
,I/Keyboard.Facilitator.DecoderInitializer( 1254): run()
,I/Decoder ( 1254): createOrResetDecoder
,I/art     ( 1067): Explicit concurrent mark sweep GC freed 55208(2MB) AllocSpace objects, 0(0B) LOS objects, 18% free, 71MB/87MB, paused 965us total 55.784ms
,I/ActivityManager(  818): Start proc 4123:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,I/ConfigService( 1235): onCreate
,I/art     (  818): Explicit concurrent mark sweep GC freed 22810(1315KB) AllocSpace objects, 12(851KB) LOS objects, 31% free, 34MB/50MB, paused 2.030ms total 81.405ms
,I/art     ( 1531): Explicit concurrent mark sweep GC freed 1107(113KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 1.557ms total 89.981ms
,I/art     ( 1531): WaitForGcToComplete blocked for 16.662ms for cause HeapTrim
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1254): run()
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1254): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1254): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1254): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1254): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1254): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1254): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1254): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1254): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1254): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1254): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1254): run()
I/StatsUtilsManager( 1254): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1254): shouldRecordStats() = Too Soon
,W/InputMethodManagerService(  818): Got RemoteException sending setActive(false) notification to pid 3742 uid 10265
I/Keyboard.Facilitator( 1254): onFinishInput()
,D/VoicemailCleanupService( 4123): Cleaning up data for package: com.test.thalitest
,D/JobSchedulerService(  818): Receieved: android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  818): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,I/ActivityManager(  818): Start proc 4146:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,W/LocationOracleImpl( 1531): Best location was null
,I/art     (  818): Explicit concurrent mark sweep GC freed 4606(223KB) AllocSpace objects, 2(220KB) LOS objects, 31% free, 34MB/50MB, paused 2.382ms total 110.345ms
,I/art     ( 1362): Explicit concurrent mark sweep GC freed 4985(363KB) AllocSpace objects, 13(1519KB) LOS objects, 31% free, 35MB/51MB, paused 886us total 29.163ms
,I/HotwordRecognitionRnr( 1531): Starting hotword detection.
,I/MicrophoneInputStream( 1531): mic_starting com.google.android.apps.gsa.speech.audio.u@270be9f3
,I/AudioFlinger(  356): AudioFlinger's thread 0xb4038000 ready to run
,I/SoundTriggerHwService::Module(  356): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,I/MicrophoneInputStream( 1531): mic_started com.google.android.apps.gsa.speech.audio.u@270be9f3
,D/audio_hw_primary(  356): select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
,D/msm8974_platform(  356): platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
E/ACDB-LOADER(  356): Error: ACDB AudProc vol returned = -19
D/audio_hw_primary(  356): enable_snd_device: snd_device(55: voice-rec-mic)
,D/audio_hw_primary(  356): enable_audio_route: apply and update mixer path: audio-record
,I/ContactLocale( 4123): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  818): Start proc 4178:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,D/Launcher.Workspace( 1362): 11683562 - stripEmptyScreens()
D/Launcher.Workspace( 1362): 11683562 - stripEmptyScreens()
,I/HotwordWorker( 1531): onReady
,I/art     ( 4107): System.exit called, status: 0
I/AndroidRuntime( 4107): VM exiting with result code 0.
,D/WifiService(  818): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@2cd0bfb}
,E/WifiStateMachine(  818): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-53
,W/ContextImpl( 4178): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2609 
,E/NetworkScheduler.SchedulerReceiver( 1235): Invalid parameter app
,E/NetworkScheduler.SchedulerReceiver( 1235): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,V/GoogleAuthProtoRequest( 3110): [312] a.<init>: mAccountName set to: thalitester@gmail.com
,D/PackageBroadcastService( 1805): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1805): Clearing selected account for com.test.thalitest
,D/ChimeraCfgMgr( 1805): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1805): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1805): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1805): Module APK com.google.android.play.games already loaded
,W/Launcher( 1362): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@2f7e8031 new=com.google.android.velvet.VelvetApplication@2f7e8031
I/LocationSettingsChecker( 1805): Removing dialog suppression flag for package com.test.thalitest
I/UpdateIcingCorporaServi( 1531): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,E/LocSvc_IzatApiV02(  818): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1660753171
E/LocSvc_IzatApiV02(  818): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,I/ActivityManager(  818): Start proc 4209:com.google.android.apps.docs/u0a46 for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
,D/GOOGLEHELP_CompatibleDatabase( 1805): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
,I/art     ( 1235): Explicit concurrent mark sweep GC freed 61208(3MB) AllocSpace objects, 10(757KB) LOS objects, 36% free, 27MB/43MB, paused 852us total 40.422ms
D/GOOGLEHELP_CompatibleDatabase( 1805): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1805): 0 metrics were deleted when clearing package com.test.thalitest.
D/GOOGLEHELP_CompatibleDatabase( 1805): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/GOOGLEHELP_CompatibleDatabase( 1805): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1805): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/GOOGLEHELP_CompatibleDatabase( 1805): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,I/art     (  367): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 208us total 23.127ms
,I/ConfigFetchService( 1805): onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,D/GOOGLEHELP_CompatibleDatabase( 1805): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1805): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/GOOGLEHELP_CompatibleDatabase( 1805): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/GOOGLEHELP_CompatibleDatabase( 1805): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/GOOGLEHELP_CompatibleDatabase( 1805): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/GOOGLEHELP_CompatibleDatabase( 1805): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,W/BaseAppContext( 1805): Using Auth Proxy for data requests.
,I/ConfigFetchService( 1805): service connected
W/BaseAppContext( 1805): Using Auth Proxy for data requests.
I/art     (  367): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 262us total 19.135ms
,I/PeopleContactsSync( 1805): CP2 sync disabled
,I/Icing   ( 1805): doRemovePackageData com.test.thalitest
,I/art     (  367): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 200us total 13.855ms
,I/UpdateIcingCorporaServi( 1531): UpdateCorporaTask done [took 89 ms] updated apps [took 89 ms] 
,I/GLSUser ( 1235): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1235): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1235): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1235): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1235): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3110): [312] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3110): [312] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3110): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3110): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3110): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3110): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3110): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3110): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3110): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3110): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3110): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3110): 	at com.a.a.k.run(SourceFile:110)
,I/ActivityManager(  818): Killing 2391:com.google.android.calendar/u0a37 (adj 15): empty #17
,I/GAv4    ( 4209): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4209):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4209):   adb logcat -s GAv4
,W/GAv4    ( 4209): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4209): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
E/SharedPreferencesImpl( 4209): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4209): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/GAv4    ( 4209): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
E/SharedPreferencesImpl( 4209): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/AnalyticsTrackerProxyImpl( 4209): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
,E/SQLiteDatabase( 4209): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 4209): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4209): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4209): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4209): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4209): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4209): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4209): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4209): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4209): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4209): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4209): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4209): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4209): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4209): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4209): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 4209): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 4209): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 4209): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 4209): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 4209): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 4209): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4209): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4209): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4209): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4209): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 4209): 	at gir$c.run(Unknown Source)
E/GAv4    ( 4209): Opening the database failed, dropping the table and recreating it
E/SharedPreferencesImpl( 4209): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SQLiteDatabase( 4209): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
,E/SQLiteDatabase( 4209): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4209): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4209): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4209): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4209): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4209): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4209): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4209): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4209): ,	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4209): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4209): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4209): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4209): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4209): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4209): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 4209): 	,at fdw.g(Unknown Source)
E/SQLiteDatabase( 4209): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 4209): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 4209): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 4209): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 4209): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4209): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4209): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4209): 	,at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4209): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 4209): 	at gir$c.run(Unknown Source)
E/GAv4    ( 4209): Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,E/SharedPreferencesImpl( 4209): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4209): Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 4209): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4209): Job execution failed: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 4209): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SQLiteDatabase( 4209): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
,E/SQLiteDatabase( 4209): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4209): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4209): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4209): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4209): ,	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4209): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4209): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4209): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4209): ,	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4209): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4209): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4209): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4209): ,	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4209): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4209): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 4209): 	at ael.a(PG:1521)
E/SQLiteDatabase( 4209): ,	at hix$a.a(PG:125)
E/SQLiteDatabase( 4209): 	at aen.run(PG:536)
,W/GAv4    ( 4209): Error opening database: android.database.sqlite.SQLiteException: Database open failed
,E/GAv4    ( 4209): Job execution failed: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4209): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4209): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/GAv4    ( 4209): Error opening database: android.database.sqlite.SQLiteException: Database open failed
W/GAv4    ( 4209): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4209): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4209): Failed to commit local dispatch transaction: android.database.sqlite.SQLiteException: Database open failed
W/GAv4    ( 4209): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4209): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4209): Sync local dispatch failed: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4209): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4209): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4209): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4209): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4209): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4209): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/GAv4    ( 4209): syncDispatchLocalHits failed: java.util.concurrent.ExecutionException: android.database.sqlite.SQLiteException: Database open failed
,E/CAKEMIX_CRASHED( 4209): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/CAKEMIX_CRASHED( 4209): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/CAKEMIX_CRASHED( 4209): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/CAKEMIX_CRASHED( 4209): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/CAKEMIX_CRASHED( 4209): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/CAKEMIX_CRASHED( 4209): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/CAKEMIX_CRASHED( 4209): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/CAKEMIX_CRASHED( 4209): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/CAKEMIX_CRASHED( 4209): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/CAKEMIX_CRASHED( 4209): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/CAKEMIX_CRASHED( 4209): 	,at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/CAKEMIX_CRASHED( 4209): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/CAKEMIX_CRASHED( 4209): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/CAKEMIX_CRASHED( 4209): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/CAKEMIX_CRASHED( 4209): 	at aev.getWritableDatabase(PG:238)
E/CAKEMIX_CRASHED( 4209): 	at ael.a(PG:1521)
E/CAKEMIX_CRASHED( 4209): 	at hix$a.a(PG:125)
E/CAKEMIX_CRASHED( 4209): 	at aen.run(PG:536)
E/SharedPreferencesImpl( 4209): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,I/ActivityManager(  818): START u0 {act=android.intent.action.BUG_REPORT flg=0x10000000 cmp=com.google.android.apps.docs/.app.ErrorNotificationActivity (has extras)} from uid 10046 on display 0
,V/WindowManager(  818): addAppToken: AppWindowToken{9633d45 token=Token{36ba29bc ActivityRecord{2915b1af u0 com.google.android.apps.docs/.app.ErrorNotificationActivity t29}}} to stack=1 task=29 at 0
,I/Process ( 4209): Sending signal. PID: 4209 SIG: 9
I/HotwordDetector( 1531): Closing mic
I/MicrophoneInputStream( 1531): mic_close com.google.android.apps.gsa.speech.audio.u@270be9f3
,E/lowmemorykiller(  256): Error writing /proc/4209/oom_score_adj; errno=22
,E/JavaBinder(  818): !!! FAILED BINDER TRANSACTION !!!
,W/ActivityManager(  818): Exception when starting activity com.google.android.apps.docs/.app.ErrorNotificationActivity
W/ActivityManager(  818): android.os.TransactionTooLargeException
W/ActivityManager(  818): 	at android.os.BinderProxy.transactNative(Native Method)
W/ActivityManager(  818): 	at android.os.BinderProxy.transact(Binder.java:496)
W/ActivityManager(  818): 	at android.app.ApplicationThreadProxy.scheduleLaunchActivity(ApplicationThreadNative.java:797)
W/ActivityManager(  818): 	at com.android.server.am.ActivityStackSupervisor.realStartActivityLocked(ActivityStackSupervisor.java:1181)
W/ActivityManager(  818): 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1281)
W/ActivityManager(  818): 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:1891)
W/ActivityManager(  818): 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1455)
W/ActivityManager(  818): 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2473)
W/ActivityManager(  818): 	at com.android.server.am.ActivityStack.completePauseLocked(ActivityStack.java:998)
W/ActivityManager(  818): 	at com.android.server.am.ActivityStack.activityPausedLocked(ActivityStack.java:896)
W/ActivityManager(  818): 	at com.android.server.am.ActivityManagerService.activityPaused(ActivityManagerService.java:6311)
W/ActivityManager(  818): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:512)
W/ActivityManager(  818): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2208)
W/ActivityManager(  818): 	at android.os.Binder.execTransact(Binder.java:446)
,D/audio_hw_primary(  356): disable_audio_route: reset and update mixer path: audio-record
,D/audio_hw_primary(  356): disable_snd_device: snd_device(55: voice-rec-mic)
,I/SoundTriggerHwService::Module(  356): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0,
,I/HotwordRecognitionRnr( 1531): Stopping hotword detection.
I/HotwordRecognitionRnr( 1531): Hotword detection finished
,I/ActivityManager(  818): Start proc 4246:com.google.android.apps.docs/u0a46 for activity com.google.android.apps.docs/.app.ErrorNotificationActivity
,W/ActivityManager(  818): Spurious death for ProcessRecord{7ebba24 4246:com.google.android.apps.docs/u0a46}, curProc for 4209: null
,E/Search.SharedPreferencesProto( 1531): Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
,I/ActivityManager(  818): Start proc 4265:com.android.documentsui/u0a45 for broadcast com.android.documentsui/.PackageReceiver
,W/OpenGLRenderer( 1362): Incorrectly called buildLayer on View: ew, destroying layer...
,I/ActivityManager(  818): Killing 3650:com.google.android.music:main/u0a66 (adj 15): empty #17
,E/native  ( 1254): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1254): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,E/SQLiteDatabase( 4265): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 4265): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4265): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4265): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4265): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4265): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4265): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4265): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4265): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4265): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4265): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4265): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4265): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4265): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4265): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4265): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/SQLiteDatabase( 4265): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/SQLiteDatabase( 4265): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:370)
E/SQLiteDatabase( 4265): 	at android.content.ContentResolver.call(ContentResolver.java:1372)
E/SQLiteDatabase( 4265): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/SQLiteDatabase( 4265): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2609)
E/SQLiteDatabase( 4265): 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
E/SQLiteDatabase( 4265): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1380)
E/SQLiteDatabase( 4265): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4265): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 4265): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
E/SQLiteDatabase( 4265): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 4265): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 4265): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
E/SQLiteDatabase( 4265): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,D/AndroidRuntime( 4265): Shutting down VM
,--------- beginning of crash
E/AndroidRuntime( 4265): FATAL EXCEPTION: main
E/AndroidRuntime( 4265): Process: com.android.documentsui, PID: 4265
E/AndroidRuntime( 4265): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4265): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2616)
E/AndroidRuntime( 4265): 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
E/AndroidRuntime( 4265): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1380)
E/AndroidRuntime( 4265): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4265): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 4265): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
E/AndroidRuntime( 4265): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 4265): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 4265): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
E/AndroidRuntime( 4265): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
E/AndroidRuntime( 4265): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4265): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4265): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 4265): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 4265): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4265): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4265): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4265): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AndroidRuntime( 4265): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AndroidRuntime( 4265): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 4265): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AndroidRuntime( 4265): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 4265): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 4265): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 4265): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/AndroidRuntime( 4265): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/AndroidRuntime( 4265): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:370)
E/AndroidRuntime( 4265): 	at android.content.ContentResolver.call(ContentResolver.java:1372)
E/AndroidRuntime( 4265): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/AndroidRuntime( 4265): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2609)
E/AndroidRuntime( 4265): 	... 9 more
,I/ActivityManager(  818): Start proc 4286:com.android.externalstorage/u0a10 for content provider com.android.externalstorage/.ExternalStorageProvider
E/native  ( 1254): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1254): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,E/DropBoxManagerService(  818): Can't write: system_app_crash
E/DropBoxManagerService(  818): java.io.FileNotFoundException: /data/system/dropbox/drop99.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  818): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  818): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  818): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  818): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  818): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  818): 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
E/DropBoxManagerService(  818): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  818): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  818): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  818): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  818): 	... 5 more
,D/OpenGLRenderer(  818): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,D/Atlas   (  818): Validating map...
,I/ActivityManager(  818): Killing 3803:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,I/OpenGLRenderer(  818): Initialized EGL, version 1.4
,D/OpenGLRenderer(  818): Enabling debug mode 0
,D/ExternalStorage( 4286): After updating volumes, found 1 active roots
,E/native  ( 1254): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1254): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
I/ActivityManager(  818): Killing 3823:com.google.android.apps.magazines/u0a67 (adj 15): empty #17
E/native  ( 1254): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1254): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
,I/Icing   ( 1805): Indexing 0A4562BF807829C124E952811A67787B55D6217E from com.google.android.googlequicksearchbox
,I/GAv4    ( 4246): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4246):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4246):   adb logcat -s GAv4
,W/GAv4    ( 4246): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4246): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,E/SharedPreferencesImpl( 4246): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4246): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/GAv4    ( 4246): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
E/Icing   ( 1805): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.deleted for write failed: Read-only file system
E/Icing   ( 1805): Could not init tag ds.tag.deleted
E/SharedPreferencesImpl( 4246): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SQLiteDatabase( 4246): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 4246): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4246): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4246): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4246): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4246): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4246): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4246): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4246): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4246): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4246): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4246): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4246): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4246): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4246): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4246): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 4246): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 4246): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 4246): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 4246): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 4246): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 4246): 	at java.util.concurrent.Executors$RunnableAd,apter.call(Executors.java:422)
E/SQLiteDatabase( 4246): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4246): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4246): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4246): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 4246): 	at gir$c.run(Unknown Source)
E/GAv4    ( 4246): Opening the database failed, dropping the table and recreating it
E/SharedPreferencesImpl( 4246): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SQLiteDatabase( 4246): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 4246): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4246): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4246): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4246): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4246): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4246): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4246): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4246): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4246): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4246): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4246): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4246): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4246): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4246): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4246): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 4246): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 4246): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 4246): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 4246): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 4246): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 4246): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4246): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4246): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4246): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4246): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 4246): 	at gir$c.run(Unknown Source)
,E/GAv4    ( 4246): Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/GAv4    ( 4246): Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 4246): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4246): Job execution failed: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 4246): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4246): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/AnalyticsTrackerProxyImpl( 4246): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
,E/SQLiteDatabase( 4246): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4246): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4246): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4246): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4246): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4246): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4246): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4246): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4246): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4246): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4246): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4246): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4246): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4246): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4246): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4246): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 4246): 	at ael.a(PG:1521)
E/SQLiteDatabase( 4246): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 4246): 	at aen.run(PG:536)
,I/Icing   ( 1805): Indexing done 0A4562BF807829C124E952811A67787B55D6217E
,E/Icing   ( 1805): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.status for write failed: Read-only file system
E/Icing   ( 1805): Writing status failed
,E/Icing   ( 1805): Error while writing to AppDataSearch-main-config-corpus-scratch-data.tmp: java.io.FileNotFoundException: /data/data/com.google.android.gms/files/AppDataSearch/main/AppDataSearch-main-config-corpus-scratch-data.tmp: open failed: EROFS (Read-only file system)
,E/SQLiteDatabase( 4246): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4246): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4246): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4246): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4246): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4246): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4246): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4246): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4246): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4246): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4246): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4246): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4246): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4246): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4246): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4246): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 4246): 	at ael.a(PG:1521)
E/SQLiteDatabase( 4246): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 4246): 	at aej.c(PG:139)
E/SQLiteDatabase( 4246): 	at aej.b(PG:398)
E/SQLiteDatabase( 4246): 	at agf.f(PG:417)
E/SQLiteDatabase( 4246): 	at oe.run(PG:1112)
E/SQLiteDatabase( 4246): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4246): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4246): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4246): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4246): 	at java.lang.Thread.run(Thread.java:818)
,E/AbstractDatabaseInstance( 4246): Failed to delete from CachedSearch133,
,E/AbstractDatabaseInstance( 4246): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AbstractDatabaseInstance( 4246): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AbstractDatabaseInstance( 4246): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AbstractDatabaseInstance( 4246): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AbstractDatabaseInstance( 4246): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AbstractDatabaseInstance( 4246): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AbstractDatabaseInstance( 4246): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AbstractDatabaseInstance( 4246): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AbstractDatabaseInstance( 4246): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AbstractDatabaseInstance( 4246): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AbstractDatabaseInstance( 4246): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AbstractDatabaseInstance( 4246): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AbstractDatabaseInstance( 4246): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AbstractDatabaseInstance( 4246): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AbstractDatabaseInstance( 4246): 	at aev.getWritableDatabase(PG:238)
E/AbstractDatabaseInstance( 4246): 	at ael.a(PG:1521)
E/AbstractDatabaseInstance( 4246): 	at hix$a.a(PG:125)
E/AbstractDatabaseInstance( 4246): 	at aej.c(PG:139)
,E/AbstractDatabaseInstance( 4246): 	at aej.b(PG:398)
E/AbstractDatabaseInstance( 4246): 	at agf.f(PG:417)
E/AbstractDatabaseInstance( 4246): 	at oe.run(PG:1112)
E/AbstractDatabaseInstance( 4246): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/AbstractDatabaseInstance( 4246): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AbstractDatabaseInstance( 4246): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AbstractDatabaseInstance( 4246): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AbstractDatabaseInstance( 4246): 	at java.lang.Thread.run(Thread.java:818)
,W/ResourcesManager( 4246): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 4246): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/ErrorNotificationActivity( 4246): Google Drive has stopped unexpectedly. Please provide additional details to help us diagnose the issue.
,V/JNIHelp ( 4246): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ProviderInstaller( 4246): Installed default security provider GmsCore_OpenSSL
,I/art     (  818): Explicit concurrent mark sweep GC freed 22238(1103KB) AllocSpace objects, 1(16KB) LOS objects, 31% free, 34MB/50MB, paused 1.656ms total 88.010ms
,D/OpenGLRenderer( 4246): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,D/Atlas   ( 4246): Validating map...
,V/WindowManager(  818): Adding window Window{2b92b452 u0 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity} at 2 of 8 (after Window{12f2fb1c u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
,V/WindowManager(  818): Adding window Window{33656020 u0 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity} at 2 of 9 (before Window{2b92b452 u0 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity})
,D/WifiService(  818): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@2cd0bfb}
,W/GAv4    ( 4246): Error opening database: android.database.sqlite.SQLiteException: Database open failed
,E/GAv4    ( 4246): Job execution failed: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4246): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4246): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4246): Error opening database: android.database.sqlite.SQLiteException: Database open failed
,W/GAv4    ( 4246): Error opening database: android.database.sqlite.SQLiteException: Database open failed
,E/GAv4    ( 4246): Failed to commit local dispatch transaction: android.database.sqlite.SQLiteException: Database open failed
,E/SQLiteDatabase( 4246): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4246): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4246): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4246): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4246): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4246): 	,at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4246): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4246): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4246): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4246): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4246): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4246): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4246): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4246): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4246): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4246): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 4246): 	at ael.a(PG:1521)
E/SQLiteDatabase( 4246): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 4246): 	at aej.c(PG:139)
E/SQLiteDatabase( 4246): 	at aej.a(PG:358)
E/SQLiteDatabase( 4246): 	at aej.a(PG:345)
E/SQLiteDatabase( 4246): 	at agf.d(PG:281)
E/SQLiteDatabase( 4246): 	at agf.b(PG:312)
E/SQLiteDatabase( 4246): 	at agf.a(PG:221)
E/,SQLiteDatabase( 4246): 	at com.google.android.apps.docs.storagebackend.StorageBackendContentProvider.queryRoots(PG:291)
E/SQLiteDatabase( 4246): 	at android.provider.DocumentsProvider.query(DocumentsProvider.java:480)
E/SQLiteDatabase( 4246): 	at android.content.ContentProvider.query(ContentProvider.java:966)
E/SQLiteDatabase( 4246): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:211)
E/SQLiteDatabase( 4246): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/SQLiteDatabase( 4246): 	at android.os.Binder.execTransact(Binder.java:446)
W/GAv4    ( 4246): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4246): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4246): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4246): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SharedPreferencesImpl( 4246): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/AbstractDatabaseInstance( 4246): Failed to query Account133 object
E/AbstractDatabaseInstance( 4246): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AbstractDatabaseInstance( 4246): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AbstractDatabaseInstance( 4246): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AbstractDatabaseInstance( 4246): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AbstractDatabaseInstance( 4246): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AbstractDatabaseInstance( 4246): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AbstractDatabaseInstance( 4246): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AbstractDatabaseInstance( 4246): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AbstractDatabaseInstance( 4246): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AbstractDatabaseInstance( 4246): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AbstractDatabaseInstance( 4246): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AbstractDatabaseInstance( 4246): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AbstractDatabaseInstance( 4246): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AbstractDatabaseInstance( 4246): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AbstractDatabaseInstance( 4246): 	at aev.getWritableDatabase(PG:238)
E/AbstractDatabaseInstance( 4246): 	at ael.a(PG:1521)
E/AbstractDatabaseInstance( 4246): 	at hix$a.a(PG:125)
E/AbstractDatabaseInstance( 4246): 	at aej.c(PG:139)
E/AbstractDatabaseInstance( 4246): 	at aej.a(PG:358)
E/AbstractDatabaseInstance( 4246): 	at aej.a(PG:345)
E/AbstractDatabaseInstance( 4246): 	at agf.d(PG:281)
E/AbstractDatabaseInstance( 4246): 	at agf.b(PG:312)
E/AbstractDatabaseInstance( 4246): 	at agf.a(PG:221)
E/AbstractDatabaseInstance( 4246): 	at com.google.android.apps.docs.storagebackend.StorageBackendContentProvider.queryRoots(PG:291)
E/AbstractDatabaseInstance( 4246): 	at android.provider.DocumentsProvider.query(DocumentsProvider.java:480)
E/AbstractDatabaseInstance( 4246): 	at android.content.ContentProvider.query(ContentProvider.java:966)
E/AbstractDatabaseInstance( 4246): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:211)
E/AbstractDatabaseInstance( 4246): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/AbstractDatabaseInstance( 4246): 	at android.os.Binder.execTransact(Binder.java:446)
E/SharedPreferencesImpl( 4246): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/DatabaseUtils( 4246): Writing exception to parcel
E/DatabaseUtils( 4246): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/DatabaseUtils( 4246): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/DatabaseUtils( 4246): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/DatabaseUtils( 4246): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/DatabaseUtils( 4246): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/DatabaseUtils( 4246): 	,at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/DatabaseUtils( 4246): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/DatabaseUtils( 4246): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/DatabaseUtils( 4246): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/DatabaseUtils( 4246): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/DatabaseUtils( 4246): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/DatabaseUtils( 4246): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/DatabaseUtils( 4246): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/DatabaseUtils( 4246): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/DatabaseUtils( 4246): 	at aev.getWritableDatabase(PG:238)
E/DatabaseUtils( 4246): 	at ael.a(PG:1521)
E/DatabaseUtils( 4246): 	at hix$a.a(PG:125)
E/DatabaseUtils( 4246): 	at aej.c(PG:139)
E/DatabaseUtils( 4246): 	at aej.a(PG:358)
E/DatabaseUtils( 4246): 	at aej.a(PG:345)
E/DatabaseUtils( 4246): 	at agf.d(PG:281)
E/DatabaseUtils( 4246): 	at agf.b(PG:312)
E/DatabaseUtils( 4246): 	at agf.a(PG:221)
E/DatabaseUtils( 4246): 	at com.google.android.apps.docs.storagebackend.StorageBackendContentProvider.queryRoots(PG:291)
E/DatabaseUtils( 4246): 	at android.provider.DocumentsProvider.query(DocumentsProvider.java:480)
E/DatabaseUtils( 4246): 	at android.content.ContentProvider.query(ContentProvider.java:966)
E/DatabaseUtils( 4246): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:211)
E/DatabaseUtils( 4246): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/DatabaseUtils( 4246): 	at android.os.Binder.execTransact(Binder.java:446)
E/GAv4    ( 4246): Sync local dispatch failed: android.database.sqlite.SQLiteException: Database open failed
W/Documents( 4265): Failed to load some roots from com.google.android.apps.docs.storage: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
D/Documents( 4265): Update found 6 roots in 918ms
W/GAv4    ( 4246): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4246): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4246): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4246): syncDispatchLocalHits failed: java.util.concurrent.ExecutionException: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4246): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/CAKEMIX_CRASHED( 4246): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/CAKEMIX_CRASHED( 4246): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/CAKEMIX_CRASHED( 4246): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/CAKEMIX_CRASHED( 4246): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/CAKEMIX_CRASHED( 4246): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/CAKEMIX_CRASHED( 4246): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/CAKEMIX_CRASHED( 4246): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/CAKEMIX_CRASHED( 4246): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/CAKEMIX_CRASHED( 4246): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/CAKEMIX_CRASHED( 4246): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/CAKEMIX_CRASHED( 4246): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/CAKEMIX_CRASHED( 4246): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/CAKEMIX_CRASHED( 4246): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/CAKEMIX_CRASHED( 4246): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/CAKEMIX_CRASHED( 4246): 	at aev.getWritableDatabase(PG:238)
E/CAKEMIX_CRASHED( 4246): 	at ael.a(PG:1521)
E/CAKEMIX_CRASHED( 4246): 	at hix$a.a(PG:125)
E/CAKEMIX_CRASHED( 4246): 	at aen.run(PG:536)
E/SQLiteDatabase( 4246): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4246): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4246): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4246): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4246): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4246): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4246): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4246): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4246): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4246): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4246): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4246): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4246): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4246): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4246): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4246): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 4246): 	at ael.a(PG:1521)
E/SQLiteDatabase( 4246): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 4246): 	at aej.c(PG:139)
E/SQLiteDatabase( 4246): 	at aej.a(PG:358)
E/SQLiteDatabase( 4246): 	at aej.a(PG:345)
E/SQLiteDatabase( 4246): 	at agf.c(PG:884)
E/SQLiteDatabase( 4246): 	at aii.doInBackground(PG:1063)
E/SQLiteDatabase( 4246): 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
E/SQLiteDatabase( 4246): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4246): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4246): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4246): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4246): 	at java.lang.Thread.run(Thread.java:818)
I/ActivityManager(  818): START u0 {act=android.intent.action.BUG_REPORT flg=0x10000000 cmp=com.google.android.apps.docs/.app.ErrorNotificationActivity (has extras)} from uid 10046 on display 0
E/AbstractDatabaseInstance( 4246): Failed to query Account133 object
E/AbstractDatabaseInstance( 4246): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AbstractDatabaseInstance( 4246): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AbstractDatabaseInstance( 4246): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AbstractDatabaseInstance( 4246): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AbstractDatabaseInstance( 4246): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AbstractDatabaseInstance( 4246): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AbstractDatabaseInstance( 4246): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AbstractDatabaseInstance( 4246): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AbstractDatabaseInstance( 4246): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AbstractDatabaseInstance( 4246): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AbstractDatabaseInstance( 4246): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AbstractDatabaseInstance( 4246): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AbstractDatabaseInstance( 4246): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AbstractDatabaseInstance( 4246): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AbstractDatabaseInstance( 4246): 	at aev.getWritableDatabase(PG:238)
E/AbstractDatabaseInstance( 4246): 	at ael.a(PG:1521)
E/AbstractDatabaseInstance( 4246): 	at hix$a.a(PG:125)
E/AbstractDatabaseInstance( 4246): 	at aej.c(PG:139)
E/AbstractDatabaseInstance( 4246): 	at aej.a(PG:358)
E/AbstractDatabaseInstance( 4246): 	at aej.a(PG:345)
E/AbstractDatabaseInstance( 4246): 	at agf.c(PG:884)
E/AbstractDatabaseInstance( 4246): 	at aii.doInBackground(PG:1063)
E/AbstractDatabaseInstance( 4246): 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
E/AbstractDatabaseInstance( 4246): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AbstractDatabaseInstance( 4246): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/AbstractDatabaseInstance( 4246): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AbstractDatabaseInstance( 4246): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AbstractDatabaseInstance( 4246): 	at java.lang.Thread.run(Thread.java:818)
W/GAv4    ( 4246): Error opening database: android.database.sqlite.SQLiteException: Database open failed
I/Process ( 4246): Sending signal. PID: 4246 SIG: 9
,W/InputDispatcher(  818): channel '2b92b452 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
I/WindowState(  818): WIN DEATH: Window{2b92b452 u0 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity}
E/InputDispatcher(  818): channel '2b92b452 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity (server)' ~ Channel is unrecoverably broken and will be disposed!
W/InputDispatcher(  818): Attempted to unregister already unregistered input channel '2b92b452 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity (server)'
W/InputDispatcher(  818): channel '33656020 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
E/InputDispatcher(  818): channel '33656020 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity (server)' ~ Channel is unrecoverably broken and will be disposed!
,I/ActivityManager(  818): Process com.google.android.apps.docs (pid 4246) has died
,I/WindowState(  818): WIN DEATH: Window{33656020 u0 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity},
W/InputDispatcher(  818): Attempted to unregister already unregistered input channel '33656020 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity (server)'
W/ActivityManager(  818): Force removing ActivityRecord{2915b1af u0 com.google.android.apps.docs/.app.ErrorNotificationActivity t29}: app died, no saved state
,I/ActivityManager(  818): Killing 3880:com.android.chrome/u0a40 (adj 15): empty #17
,E/SQLiteDatabase( 1235): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 1235): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1235): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1235): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1235): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1235): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1235): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1235): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1235): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1235): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1235): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1235): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 1235): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 1235): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 1235): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1235): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 1235): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:99)
E/SQLiteDatabase( 1235): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/SQLiteDatabase( 1235): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/SQLiteDatabase( 1235): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/SQLiteDatabase( 1235): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 1235): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 1235): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteOpenHelper( 1235): Couldn't open phenotype.db for writing (will try read-only):
E/SQLiteOpenHelper( 1235): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1235): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1235): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 1235): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 1235): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1235): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1235): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1235): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteOpenHelper( 1235): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteOpenHelper( 1235): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 1235): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteOpenHelper( 1235): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 1235): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 1235): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 1235): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 1235): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:99)
E/SQLiteOpenHelper( 1235): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/SQLiteOpenHelper( 1235): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/SQLiteOpenHelper( 1235): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/SQLiteOpenHelper( 1235): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteOpenHelper( 1235): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteOpenHelper( 1235): 	at java.lang.Thread.run(Thread.java:818)
,W/SQLiteOpenHelper( 1235): Opened phenotype.db in read-only mode
,E/SQLiteLog( 1235): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
,E/ClearcutLoggerIntentService( 1235): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1235): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1235): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1235): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1235): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1235): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1235): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1235): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1235): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1235): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1235): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1235): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1235): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1235): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1235): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 1235): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1235): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1235): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1235): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1235): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1235): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1235): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1235): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1235): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1235): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1235): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1235): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1235): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1235): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1235): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1235): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 1235): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
,E/ClearcutLoggerIntentService( 1235): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1235): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1235): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1235): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1235): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1235): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1235): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1235): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1235): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1235): 	,at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1235): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1235): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1235): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1235): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1235): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 1235): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
,E/ClearcutLoggerIntentService( 1235): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1235): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1235): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1235): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1235): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1235): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1235): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1235): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1235): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1235): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1235): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1235): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1235): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1235): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1235): 	at java.lang.Thread.run(Thread.java:818)
,E/PlayLogIntentService( 1235): database is locked (code 5)
E/PlayLogIntentService( 1235): android.database.sqlite.SQLiteDatabaseLockedException: database is locked (code 5)
E/PlayLogIntentService( 1235): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method),
E/PlayLogIntentService( 1235): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/PlayLogIntentService( 1235): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:319)
E/PlayLogIntentService( 1235): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/PlayLogIntentService( 1235): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/PlayLogIntentService( 1235): 	at android.database.sqlite.SQLiteDatabase.beginTransactionNonExclusive(SQLiteDatabase.java:440)
E/PlayLogIntentService( 1235): 	at com.google.android.gms.playlog.store.a.a(SourceFile:99)
E/PlayLogIntentService( 1235): 	at com.google.android.gms.playlog.store.g.b(SourceFile:385)
E/PlayLogIntentService( 1235): 	at com.google.android.gms.playlog.store.g.a(SourceFile:352)
E/PlayLogIntentService( 1235): 	at com.google.android.gms.playlog.service.d.a(SourceFile:136)
E/PlayLogIntentService( 1235): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/PlayLogIntentService( 1235): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/PlayLogIntentService( 1235): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/PlayLogIntentService( 1235): 	at java.lang.Thread.run(Thread.java:818)
,E/Search.SharedPreferencesProto( 1531): Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
,I/ConfigService( 1235): onDestroy
,E/QMI_FW  (  818): xport_send: Sendto failed for port 4608,
E/LocSvc_api_v02(  818): E/locClientSendReq:2446]: send_msg_sync error: -1
E/LocSvc_IzatApiV02(  818): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 11, ind.status = -1660753171
E/LocSvc_IzatApiV02(  818): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching ,
,E/kickstart(  868): ERROR: function: rx_data:288 Read/Write File descriptor returned error: No such device, error code -1
,E/kickstart(  868): ERROR: function: sahara_main:1143 Sahara protocol error
,E/kickstart(  868): ERROR: function: main:268 Uploading  Image using Sahara protocol failed
I/kickstart(  868): STATUS: Wrote to /sys/power/wake_unlock
,I/qdhwcomposer(  259): handle_blank_event: dpy:0 panel power state: 0

```
