#### Test 506502783fcf234_thali05_motorola-Nexus 6 Logs


```
--------- beginning of main
D/HeadsetStateMachine( 2363): Disconnected process message: 10, size: 0
,D/AndroidRuntime( 3662): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 3662): CheckJNI is OFF
D/AndroidRuntime( 3662): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  823): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/WindowManager(  823): addAppToken: AppWindowToken{1e673f7c token=Token{2b16866f ActivityRecord{1f9954e u0 com.test.thalitest/.MainActivity t26}}} to stack=1 task=26 at 0
D/AndroidRuntime( 3662): Shutting down VM
V/WindowManager(  823): Adding window Window{171b9781 u0 Starting com.test.thalitest} at 2 of 7 (after Window{29330d71 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
I/HotwordDetector( 1510): Closing mic
I/MicrophoneInputStream( 1510): mic_close com.google.android.apps.gsa.speech.audio.u@18a5ec1a
I/ActivityManager(  823): Start proc 3676:com.test.thalitest/u0a265 for activity com.test.thalitest/.MainActivity
D/audio_hw_primary(  359): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  359): disable_snd_device: snd_device(55: voice-rec-mic)
I/art     (  370): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 227us total 27.346ms
I/SoundTriggerHwService::Module(  359): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1510): Stopping hotword detection.
I/HotwordRecognitionRnr( 1510): Hotword detection finished
I/art     (  370): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 228us total 10.573ms
I/art     (  370): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 202us total 9.927ms
I/ActivityManager(  823): Killing 3077:com.google.android.gm/u0a78 (adj 15): empty #17
E/LocSvc_IzatApiV02(  823): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1701106963
E/LocSvc_IzatApiV02(  823): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,I/ActivityManager(  823): Killing 2689:com.google.android.apps.maps/u0a65 (adj 15): empty #18
,I/kickstart(  873): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
I/kickstart(  873): STATUS: Wrote to /sys/power/wake_lock
,E/kickstart(  873): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1
,I/kickstart(  873): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1' for writing
,E/WifiStateMachine(  823): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=1.90 targetRoamBSSID=any RSSI=-48
,E/WifiStateMachine(  823): WifiStateMachine starting scan for "NG7005g"WPA_PSK with 2412,5220
,I/WebViewFactory( 3676): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3676): Time to load native libraries: 1 ms (timestamps 1641-1642)
I/LibraryLoader( 3676): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3676): Binding Chromium to main looper Looper (main, tid 1) {c00791d}
I/LibraryLoader( 3676): Expected native library version number "",actual native library version number ""
I/chromium( 3676): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3676): Initializing chromium process, singleProcess=true
,W/art     ( 3676): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3676): ApplicationContext is null in ApplicationStatus
,W/chromium( 3676): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3676): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3676): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3676): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/BluetoothManagerService(  823): Message: 20
D/BluetoothManagerService(  823): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b7862f1:true
,W/art     ( 3676): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3676): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3676): CordovaWebView is running on device made by: motorola
,W/art     ( 3676): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 3676): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3676): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,D/Atlas   ( 3676): Validating map...
,V/WindowManager(  823): Adding window Window{3516ea61 u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{171b9781 u0 Starting com.test.thalitest})
,W/chromium( 3676): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3676): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3676): Enabling debug mode 0
,I/ActivityManager(  823): Displayed com.test.thalitest/.MainActivity: +1s29ms
,I/Keyboard.Facilitator( 1237): onFinishInput()
,W/BindingManager( 3676): Cannot call determinedVisibility() - never saw a connection for the pid: 3676
,I/kickstart(  873): STATUS: Received file 'm9kefs1'
,I/kickstart(  873): STATUS: 950272 bytes transferred in 0.995869 seconds
I/kickstart(  873): STATUS: Successfully downloaded files from target 
I/kickstart(  873): STATUS: Wrote to /sys/power/wake_unlock
,I/kickstart(  873): STATUS: Sahara protocol completed
,D/JsMessageQueue( 3676): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3676): JniHelper::setJavaVM(0xb489d200), pthread_self() = -1576259968
D/JX-Cordova( 3676): jxcore cordova android initializing
,W/jxcore-log( 3676): Initializing JXcore engine
W/jxcore-log( 3676): JXcore engine is ready
,W/jxcore-log( 3676): Starting JXcore engine
,W/.test.thalitest( 3676): type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[12989]" dev="sockfs" ino=12989 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 3676): type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,W/.test.thalitest( 3676): type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[10709]" dev="sockfs" ino=10709 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 3676): type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[22278]" dev="sockfs" ino=22278 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 3676): Platform android
W/jxcore-log( 3676): 
,W/jxcore-log( 3676): Process ARCH arm
W/jxcore-log( 3676): 
,I/jxcore-log( 3676): JXcore Cordova bridge is ready!
I/jxcore-log( 3676): 
W/jxcore-log( 3676): JXcore engine is started
,I/Choreographer( 3676): Skipped 137 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3676): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41),
,I/jxcore-log( 3676): Toggling radios to true
I/jxcore-log( 3676): 
,D/BluetoothAdapter( 3676): enable(): BT is already enabled..!
,D/WifiService(  823): setWifiEnabled: true pid=3676, uid=10265
,E/WifiService(  823): Invoking mWifiStateMachine.setWifiEnabled
D/WifiService(  823): New client listening to asynchronous messages
,I/jxcore-log( 3676): Radios toggled
I/jxcore-log( 3676): 
,D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/jxcore-log( 3676): Got Device Bluetooth address: F8:CF:C5:D9:E5:61
I/jxcore-log( 3676): 
,I/wpa_supplicant( 1191): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  823): WifiStateMachine: Leaving Connected state,
E/WifiConfigStore(  823): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,I/jxcore-log( 3676): Perf Test app loaded loaded
I/jxcore-log( 3676): 
D/CommandListener(  355): Clearing all IP addresses on wlan0
,I/Choreographer( 3676): Skipped 61 frames!  The application may be doing too much work on its main thread.
V/NativeCrypto( 1355): Read error: ssl=0xaec61600: I/O error during system call, Connection timed out
V/NativeCrypto( 1355): SSL shutdown failed: ssl=0xaec61600: I/O error during system call, Broken pipe
,D/ConnectivityService(  823): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,D/ConnectivityService(  823): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,E/WifiStateMachine(  823): Start Disconnecting Watchdog 1
,I/jxcore-log( 3676): check test folder
I/jxcore-log( 3676): 
E/WifiStateMachine(  823): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,D/ConnectivityService(  823): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10011
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  823): ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  823): DefaultState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  823): Forcing reevaluation
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  823): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  823): Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
,I/jxcore-log( 3676): found test : ./testFindPeers.js
I/jxcore-log( 3676): 
,D/CommandListener(  355): Clearing all IP addresses on wlan0
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  823): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
,I/jxcore-log( 3676): found test : ./testSendData.js
I/jxcore-log( 3676): 
,D/WifiNetworkAgent(  823): NetworkAgent: NetworkAgent channel lost
,D/ConnectivityService(  823): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,E/WifiStateMachine(  823): CMD_AUTO_CONNECT sup state CompletedState my state DisconnectedState nid=0 roam=3
E/WifiStateMachine(  823): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=0
D/ConnectivityManager.CallbackHandler( 1071): CM callback handler got msg 524292
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  823): OfflineState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  823): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  823): Disconnected - quitting
,D/CSLegacyTypeTracker(  823): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  823): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  823): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering(  823): MasterInitialState.processMessage what=3,
D/ConnectivityService(  823): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,I/NetworkMonitor( 3282): type=WIFI subType= reason=null isConnected=false
,D/ConnectivityService(  823): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  823): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService(  823): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/ConnectivityService(  823): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/Tethering(  823): MasterInitialState.processMessage what=3
,D/NetworkChangeNotifierAutoDetect( 1510): Network connectivity changed, type is: 6
,V/MusicLeanback( 3282): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/PhoneInterfaceManager( 1287): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1287): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,E/WifiConfigStore(  823): Setting BSSID for "NG7005g"WPA_PSK to any
D/TelephonyManager(  823): getDataEnabled: retVal=false
,E/WifiConfigStore(  823): will read network variables netId=0
,E/WifiStateMachine(  823): CMD_AUTO_CONNECT did save config ->  nid=0
,E/WifiConfigStore(  823): will read network variables netId=0
,E/GpsLocationProvider(  823): No APN found to select.
,I/wpa_supplicant( 1191): wlan0: Trying to associate with SSID 'NG7005g'
,I/ActivityManager(  823): Start proc 3738:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.steen.receiver.ConnectivityChangeReceiver
,D/PhoneInterfaceManager( 1287): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1287): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  823): getDataEnabled: retVal=false
,E/GpsLocationProvider(  823): No APN found to select.
,I/chromium( 3676): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/ActivityManager(  823): Start proc 3764:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,I/ActivityManager(  823): Killing 2277:com.google.android.calendar/u0a37 (adj 15): empty #17
,D/SprintDMReceiver( 3764): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3764): simOperator:  IMSI: null
D/SprintDMReceiver( 3764): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1779): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1779): onCreate
,D/SystemUpdateService( 1779): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1779): active receiver: enabled
,I/SystemUpdateService( 1779): showing system update notification
I/wpa_supplicant( 1191): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/iu.Environment( 1779): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1779): num queued entries: 0
I/iu.UploadsManager( 1779): num updated entries: 0
,I/iu.SyncManager( 1779): NEXT; no task
,I/ValidateNoPeople(  823): skipping global notification
,D/ChimeraCfgMgr( 1779): Loading module com.google.android.gms.kids from APK com.google.android.gms
,V/SystemUpdateService( 1779): retry (wakeup: false) in 3599984 ms
,D/SystemUpdateService( 1779): onDestroy
,I/wpa_supplicant( 1191): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 1191): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=0 id_str=]
,I/ActivityManager(  823): Start proc 3789:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,I/Babel   ( 2931): connection state changed from UNKNOWN to DISCONNECTED
,D/ConnectivityService(  823): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} }
D/ConnectivityService(  823): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiConfigStore(  823): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,I/ActivityManager(  823): Killing 3236:com.android.providers.calendar/u0a3 (adj 15): empty #17
,E/WifiConfigStore(  823): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  355): Setting iface cfg
,E/WifiStateMachine(  823): Start Dhcp Watchdog 2
,E/WifiStateMachine(  823):  WifiLinkLayerStats: 
E/WifiStateMachine(  823):  my bss beacon rx: 549
E/WifiStateMachine(  823):  RSSI mgmt: -48
E/WifiStateMachine(  823):  BE :  rx=218 tx=145 lost=0 retries=1
E/WifiStateMachine(  823):  BK :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  823):  VI :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  823):  VO :  rx=7 tx=0 lost=0 retries=0
E/WifiStateMachine(  823):  on_time : 13586 tx_time=223 rx_time=490 scan_time=0
,D/ConnectivityService(  823): updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,E/native  (  823): do suspend false
,I/GAv4    ( 3789): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
,I/GAv4    ( 3789):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3789):   adb logcat -s GAv4
,E/WifiStateMachine(  823): scanCount==0 - aborting
,W/GAv4    ( 3789): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3789): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.,
,W/GAv4    ( 3789): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/art     (  823): Explicit concurrent mark sweep GC freed 49650(2MB) AllocSpace objects, 11(270KB) LOS objects, 32% free, 33MB/49MB, paused 2.514ms total 75.286ms
,I/dhcpcd  ( 3819): version 5.5.6 starting
,I/WebViewFactory( 3789): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/dhcpcd  ( 3819): wlan0: rebinding lease of 192.168.1.122
,I/LibraryLoader( 3789): Time to load native libraries: 1 ms (timestamps 7102-7103),
I/LibraryLoader( 3789): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3789): Binding Chromium to main looper Looper (main, tid 1) {1b81a08},
I/LibraryLoader( 3789): Expected native library version number "",actual native library version number ""
,I/chromium( 3789): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3789): Initializing chromium process, singleProcess=true,
W/art     ( 3789): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3789): ApplicationContext is null in ApplicationStatus
,W/chromium( 3789): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3789): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3789): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3789): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,W/AudioManagerAndroid( 3789): Requires BLUETOOTH permission
,I/NSApplication( 3789): Starting up...
,I/ActivityManager(  823): Start proc 3853:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,I/ActivityManager(  823): Killing 2706:android.process.acore/u0a5 (adj 15): empty #17
,E/lowmemorykiller(  256): Error writing /proc/2706/oom_score_adj; errno=22
,I/ActivityManager(  823): Start proc 3874:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
I/ActivityManager(  823): Killing 3484:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,V/MusicLeanback( 3282): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/ActivityManager(  823): Killing 3505:com.android.musicfx/u0a18 (adj 15): empty #17
,D/SprintDMReceiver( 3764): Received intent: android.net.conn.CONNECTIVITY_CHANGE,
,D/SprintDMHelper( 3764): simOperator:  IMSI: null,
D/SprintDMReceiver( 3764): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1779): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1779): onCreate
,D/SystemUpdateService( 1779): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1779): active receiver: enabled
,I/SystemUpdateService( 1779): showing system update notification
,D/ChimeraCfgMgr( 1779): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/ValidateNoPeople(  823): skipping global notification
,V/SystemUpdateService( 1779): retry (wakeup: false) in 3599945 ms
,D/SystemUpdateService( 1779): onDestroy
,I/dhcpcd  ( 3819): wlan0: acknowledged 192.168.1.122 from 192.168.1.1
,I/dhcpcd  ( 3819): wlan0: leased 192.168.1.122 for 86400 seconds
,D/ConnectivityService(  823): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  823): Adding iface wlan0 to network 101
,E/WifiStateMachine(  823): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  823): Unexpected mtu value: 0, wlan0
,D/ConnectivityService(  823): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  823): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  823): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  823): Setting Dns servers for network 101 to [/192.168.1.1]
,D/ConnectivityService(  823): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  823): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  823): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  823):    accepting network in place of null
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  823): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  823): Connected
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  823): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  823): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
D/ConnectivityService(  823): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} }
,D/ConnectivityService(  823): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/CSLegacyTypeTracker(  823): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  823): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  823): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityManager.CallbackHandler( 1071): CM callback handler got msg 524290
,D/Tethering(  823): MasterInitialState.processMessage what=3
,D/NetworkChangeNotifierAutoDetect( 1510): Network connectivity changed, type is: 2
,I/NetworkMonitor( 3282): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 3282): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/PhoneInterfaceManager( 1287): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1287): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  823): getDataEnabled: retVal=false
,E/GpsLocationProvider(  823): No APN found to select.
,D/SprintDMReceiver( 3764): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3764): simOperator:  IMSI: null
D/SprintDMReceiver( 3764): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1779): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1779): onCreate
,D/SystemUpdateService( 1779): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1779): active receiver: enabled
,I/SystemUpdateService( 1779): showing system update notification
,I/iu.Environment( 1779): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1779): num queued entries: 0
I/iu.UploadsManager( 1779): num updated entries: 0
I/iu.SyncManager( 1779): NEXT; no task
,D/ChimeraCfgMgr( 1779): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/ValidateNoPeople(  823): skipping global notification
,D/ChimeraCfgMgr( 1779): Loading module com.google.android.gms.kids from APK com.google.android.gms
,V/SystemUpdateService( 1779): retry (wakeup: false) in 3599974 ms
,D/SystemUpdateService( 1779): onDestroy
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  823): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 16 Dec 2015 03:58:46 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1450238326074], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1450238326057]}
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  823): Validated
D/ConnectivityService(  823): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/ConnectivityService(  823): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  823): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  823): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  823): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1071): CM callback handler got msg 524290
D/ConnectivityService(  823): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,I/GLSUser ( 1355): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1355): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1355): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1355): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/Herrevad( 1779): NQAS connected
,I/GLSUser ( 1355): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1355): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1355): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1355): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Babel   ( 2931): connection state changed from DISCONNECTED to CONNECTED
,W/Kids    ( 1779): [AccountUtils] Account not ready
W/Kids    ( 1779): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 1779): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 1779): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 1779): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 1779): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 1779): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 1779): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 1779): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 1779): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 1779): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 1779): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 1779): 	at java.lang.Thread.run(Thread.java:818)
,D/Finsky  ( 3019): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3019): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3019): [1] 5.onFinished: Scheduling replication attempt 3.
,D/GCM     ( 1355): Connected
,D/GCM     ( 1355): Message class com.google.f.a.a.p
,D/ConnectivityService(  823): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/jxcore-log( 3676): BLE advertisement not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 3676): 
,E/WifiStateMachine(  823): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=7.80 rxSuccessRate=9.39 targetRoamBSSID=any RSSI=-48
E/WifiStateMachine(  823): WifiStateMachine L2Connected CMD_START_SCAN source -2 10, 11 -> obsolete
,E/WifiStateMachine(  823): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=3.90 rxSuccessRate=6.70 targetRoamBSSID=any RSSI=-48
,E/WifiStateMachine(  823): WifiStateMachine L2Connected CMD_START_SCAN source -2 9, 11 -> obsolete
,I/PowerManagerService(  823): Going to sleep due to screen timeout (uid 1000)...
,I/Adreno  (  823): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/PermissionCache(  259): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (230 us)
,I/DisplayManagerService(  823): Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
D/SurfaceFlinger(  259): Set power mode=0, type=0 flinger=0xb6482000
D/qdhwcomposer(  259): hwc_setPowerMode: Setting mode 0 on display: 0
V/ActivityManager(  823): Display changed displayId=0
,I/qdhwcomposer(  259): handle_blank_event: dpy:0 panel power state: 0
,D/qdhwcomposer(  259): hwc_setPowerMode: Done setting mode 0 on display 0,
D/SurfaceControl(  823): Excessive delay in setPowerMode(): 254ms
,I/DreamManagerService(  823): Entering dreamland.
,I/PowerManagerService(  823): Dozing...
,I/DreamController(  823): Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,D/audio_hw_primary(  359): adev_set_parameters: enter: screen_state=on
D/mot_vr_audio_hw(  359): adev_set_parameters: screen_state=on
,E/WifiStateMachine(  823): cancelDelayedScan -> 12
,E/native  (  823): do suspend false
,I/Keyboard.Facilitator( 1237): onFinishInput()
,E/WifiStateMachine(  823): cancelDelayedScan -> 14
,E/native  (  823): do suspend true
,D/audio_hw_primary(  359): adev_set_parameters: enter: screen_state=off
,D/mot_vr_audio_hw(  359): adev_set_parameters: screen_state=off
,E/WifiStateMachine(  823): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-48
E/WifiStateMachine(  823): WifiStateMachine L2Connected CMD_START_SCAN source -2 13, 14 -> obsolete
,V/KeepSync( 3581): Connecting to GoogleApiClient
,I/GLSUser ( 1355): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1355): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1355): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1355): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1779): Handling authorization failure,
E/ClientConnectionOperation( 1779): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
,E/ClientConnectionOperation( 1779): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1779): ,	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
,E/ClientConnectionOperation( 1779): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1779): ,	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1779): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112),
E/ClientConnectionOperation( 1779): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1779): ,	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1779): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1779): 	,at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1779): ,	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.common.server.c.b(SourceFile:109),
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1779): ,	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1779): ,	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689),
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1779): 	... 7 more
,V/KeepSync( 3581): GoogleApiClient failed to connect with error code: 4
E/SQLiteLog( 3581): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3581): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3581): (284) automatic index on blob_node(is_deleted),
,I/GLSUser ( 1355): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1355): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1355): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1355): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3581): IOException
E/KeepSync( 3581): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3581): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3581): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3581): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3581): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3581): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3581): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3581): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3581): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3581): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3581): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3581): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3581): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3581): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3581): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3581): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3581): 	... 10 more
W/KeepSync( 3581): Sync result 2
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 167842, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,E/WifiStateMachine(  823): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-48
E/WifiStateMachine(  823): WifiStateMachine L2Connected CMD_START_SCAN source -2 11, 14 -> obsolete
,I/art     (  823): Explicit concurrent mark sweep GC freed 46542(2MB) AllocSpace objects, 4(158KB) LOS objects, 32% free, 33MB/49MB, paused 2.761ms total 106.955ms
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1355): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1355): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1355): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1355): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/Finsky  ( 3019): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3019): [1] 5.onFinished: Installation state replication failed.,
D/Finsky  ( 3019): [1] 5.onFinished: Scheduling replication attempt 4.
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1355): Vacuum at: now=1450238355252 tag=VacuumService
,V/GoogleAuthProtoRequest( 3738): [400] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GoogleURLConnFactory( 1355): Using platform SSLCertificateSocketFactory
,W/Uploader( 1355): No account for auth token provided
,I/GLSUser ( 1355): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1355): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1355): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1355): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3738): [400] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3738): [400] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3738): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3738): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3738): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3738): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3738): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3738): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3738): 	,at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3738): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3738): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3738): ,	at com.a.a.k.run(SourceFile:110)
,W/Uploader( 1355): No account for auth token provided
,I/GLSUser ( 1355): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1355): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1355): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1355): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1355): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1355): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1355): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1355): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1355): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1355): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1355): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1355): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1355): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1355): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1355): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1355): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1355): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/GLSUser ( 1355): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1355): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1355): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1355): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1355): Failed to get auth token: User intervention required. Notification has been pushed.
,E/Uploader( 1355): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1355): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1355): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1355): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1355): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1355): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1355): 	,at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1355): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1355): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1355): ,	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1355): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1355): 	,at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1355): No account for auth token provided
,W/Uploader( 1355): No account for auth token provided
,W/Uploader( 1355): No account for auth token provided
,W/Uploader( 1355): No account for auth token provided
,W/Uploader( 1355): No account for auth token provided
,I/art     ( 1355): Explicit concurrent mark sweep GC freed 54073(3MB) AllocSpace objects, 7(700KB) LOS objects, 37% free, 27MB/43MB, paused 1.637ms total 72.619ms
,I/GLSUser ( 1355): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1355): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1355): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1355): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1355): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1355): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1355): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1355): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1355): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1355): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1355): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1355): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1355): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1355): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1355): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1355): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1355): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1355): No account for auth token provided
,W/Uploader( 1355): No account for auth token provided
,W/Uploader( 1355): No account for auth token provided
,W/Uploader( 1355): No account for auth token provided
,W/Uploader( 1355):  no longer exists, so no auth token.
,I/GLSUser ( 1355): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1355): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1355): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1355): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1355): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1355): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1355): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1355): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1355): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1355): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1355): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1355): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1355): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1355): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1355): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1355): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1355): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,D/HeadsetStateMachine( 2363): Disconnected process message: 10, size: 0
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1355): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1355): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1355): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1355): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/Finsky  ( 3019): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.,
D/Finsky  ( 3019): [1] 5.onFinished: Installation state replication failed.,
D/Finsky  ( 3019): [1] 5.onFinished: Scheduling replication attempt 5.,
,I/BooksSync( 3614): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3614): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1355): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1355): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1355): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1355): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1355): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1355): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1355): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1355): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3380): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3380): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3380): 	at jdm.a(PG:82)
E/HttpOperation( 3380): 	at jcs.o(PG:406)
E/HttpOperation( 3380): 	at jcn.a(PG:1379)
E/HttpOperation( 3380): 	at jcs.i(PG:143)
E/HttpOperation( 3380): 	at blb.a(PG:3937)
E/HttpOperation( 3380): 	at czp.a(PG:18188)
E/HttpOperation( 3380): 	at czp.a(PG:9081)
E/HttpOperation( 3380): 	at czq.run(PG:1686)
E/HttpOperation( 3380): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3380): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3380): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3380): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3380): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3380): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3380): 	at jdj.a(PG:4091)
E/HttpOperation( 3380): 	at jdj.a(PG:1125)
E/HttpOperation( 3380): 	at jdm.a(PG:77)
E/HttpOperation( 3380): 	... 12 more
E/HttpOperation( 3380): Caused by: faj: BadAuthentication
E/HttpOperation( 3380): 	at fal.a(PG:38)
E/HttpOperation( 3380): 	at jdj.a(PG:4089)
E/HttpOperation( 3380): 	... 14 more
,I/GLSUser ( 1355): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1355): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1355): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1355): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1355): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1355): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1355): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1355): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3380): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3380): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3380): 	at jdm.a(PG:82)
E/HttpOperation( 3380): 	at jcs.o(PG:406)
E/HttpOperation( 3380): 	at jcn.a(PG:1379)
E/HttpOperation( 3380): 	at jcs.i(PG:143)
E/HttpOperation( 3380): 	at hec.a(PG:42)
E/HttpOperation( 3380): 	at hee.a(PG:102)
E/HttpOperation( 3380): 	at czr.a(PG:65)
E/HttpOperation( 3380): 	at kka.a(PG:108)
E/HttpOperation( 3380): 	at czp.a(PG:19176)
E/HttpOperation( 3380): 	at czp.a(PG:9081)
E/HttpOperation( 3380): 	at czq.run(PG:1686)
E/HttpOperation( 3380): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3380): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3380): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3380): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3380): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3380): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3380): 	at jdj.a(PG:4091)
E/HttpOperation( 3380): 	at jdj.a(PG:1125)
E/HttpOperation( 3380): 	at jdm.a(PG:77)
E/HttpOperation( 3380): 	... 15 more
E/HttpOperation( 3380): Caused by: faj: BadAuthentication
E/HttpOperation( 3380): 	at fal.a(PG:38)
E/HttpOperation( 3380): 	at jdj.a(PG:4089)
E/HttpOperation( 3380): 	... 17 more
,E/ExperimentLoader( 3380): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3380): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3380): 	at jdm.a(PG:82)
E/ExperimentLoader( 3380): 	at jcs.o(PG:406)
E/ExperimentLoader( 3380): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3380): 	at jcs.i(PG:143)
E/ExperimentLoader( 3380): 	at hec.a(PG:42)
E/ExperimentLoader( 3380): 	,at hee.a(PG:102)
E/ExperimentLoader( 3380): 	at czr.a(PG:65)
E/ExperimentLoader( 3380): 	at kka.a(PG:108)
E/ExperimentLoader( 3380): 	at czp.a(PG:19176)
E/ExperimentLoader( 3380): 	at czp.a(PG:9081)
E/ExperimentLoader( 3380): 	at czq.run(PG:1686)
E/ExperimentLoader( 3380): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3380): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3380): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3380): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3380): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3380): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3380): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3380): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3380): 	at jdm.a(PG:77)
E/ExperimentLoader( 3380): 	... 15 more
E/ExperimentLoader( 3380): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3380): 	at fal.a(PG:38)
E/ExperimentLoader( 3380): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3380): 	... 17 more
,E/BooksAccountManager( 3614): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3614): Soft error
E/BooksSync( 3614): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3614): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3614): Sync error
E/BooksSync( 3614): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3614): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3614): Finished books sync
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 169704, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 170203, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2363): Disconnected process message: 10, size: 0
,V/GoogleAuthProtoRequest( 3738): [402] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1355): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1355): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1355): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1355): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3738): [402] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3738): [402] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3738): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3738): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3738): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3738): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3738): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3738): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3738): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3738): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3738): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3738): 	at com.a.a.k.run(SourceFile:110)
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  823): Explicit concurrent mark sweep GC freed 28589(1288KB) AllocSpace objects, 4(252KB) LOS objects, 31% free, 34MB/50MB, paused 1.624ms total 92.702ms
,I/GLSUser ( 1355): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1355): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1355): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1355): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3019): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3019): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3019): [1] 5.onFinished: Giving up after 6 failures.
,I/Keyboard.Facilitator.LanguageModelFlusher( 1237): run()
I/Keyboard.Facilitator( 1237): flushDynamicLanguageModels()
,I/ConfigService( 1355): onCreate
,I/ActivityManager(  823): Start proc 3980:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider
,I/GAv4    ( 3980): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3980):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3980):   adb logcat -s GAv4
,W/GAv4    ( 3980): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3980): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.,
,W/GAv4    ( 3980): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  823): Killing 3326:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,V/KeepSync( 3581): Connecting to GoogleApiClient
,I/GLSUser ( 1355): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1355): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1355): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1355): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1779): Handling authorization failure
E/ClientConnectionOperation( 1779): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1779): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1779): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1779): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1779): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1779): 	... 7 more
,V/KeepSync( 3581): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3581): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3581): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3581): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1355): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1355): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1355): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1355): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3581): IOException
E/KeepSync( 3581): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3581): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3581): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3581): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3581): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3581): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3581): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3581): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3581): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3581): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3581): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3581): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3581): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3581): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3581): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3581): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3581): 	... 10 more
W/KeepSync( 3581): Sync result 2
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 200453, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/ConfigService( 1355): onDestroy
,D/HeadsetStateMachine( 2363): Disconnected process message: 10, size: 0
,I/BooksSync( 3614): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3614): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1355): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1355): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1355): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1355): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1355): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1355): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1355): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1355): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3380): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3380): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3380): 	at jdm.a(PG:82)
E/HttpOperation( 3380): 	at jcs.o(PG:406)
E/HttpOperation( 3380): 	at jcn.a(PG:1379)
E/HttpOperation( 3380): 	at jcs.i(PG:143)
E/HttpOperation( 3380): 	at blb.a(PG:3937)
E/HttpOperation( 3380): 	at czp.a(PG:18188)
E/HttpOperation( 3380): 	at czp.a(PG:9081)
E/HttpOperation( 3380): 	at czq.run(PG:1686)
E/HttpOperation( 3380): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3380): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3380): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3380): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3380): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3380): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3380): 	at jdj.a(PG:4091)
E/HttpOperation( 3380): 	at jdj.a(PG:1125)
E/HttpOperation( 3380): 	at jdm.a(PG:77)
E/HttpOperation( 3380): 	... 12 more
E/HttpOperation( 3380): Caused by: faj: BadAuthentication
E/HttpOperation( 3380): 	at fal.a(PG:38)
E/HttpOperation( 3380): 	at jdj.a(PG:4089)
E/HttpOperation( 3380): 	... 14 more
,I/GLSUser ( 1355): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1355): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1355): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1355): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1355): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1355): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1355): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1355): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3380): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3380): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3380): 	at jdm.a(PG:82)
E/HttpOperation( 3380): 	at jcs.o(PG:406)
E/HttpOperation( 3380): 	at jcn.a(PG:1379)
E/HttpOperation( 3380): 	at jcs.i(PG:143)
E/HttpOperation( 3380): 	at hec.a(PG:42)
E/HttpOperation( 3380): 	at hee.a(PG:102)
E/HttpOperation( 3380): 	at czr.a(PG:65)
E/HttpOperation( 3380): 	at kka.a(PG:108)
E/HttpOperation( 3380): 	at czp.a(PG:19176)
E/HttpOperation( 3380): 	at czp.a(PG:9081)
E/HttpOperation( 3380): 	at czq.run(PG:1686)
E/HttpOperation( 3380): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3380): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3380): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3380): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3380): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3380): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3380): 	at jdj.a(PG:4091)
E/HttpOperation( 3380): 	at jdj.a(PG:1125)
E/HttpOperation( 3380): 	at jdm.a(PG:77)
E/HttpOperation( 3380): 	... 15 more
E/HttpOperation( 3380): Caused by: faj: BadAuthentication
E/HttpOperation( 3380): 	at fal.a(PG:38)
E/HttpOperation( 3380): 	at jdj.a(PG:4089)
E/HttpOperation( 3380): 	... 17 more
,E/ExperimentLoader( 3380): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3380): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3380): 	at jdm.a(PG:82)
E/ExperimentLoader( 3380): 	at jcs.o(PG:406)
E/ExperimentLoader( 3380): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3380): 	at jcs.i(PG:143)
E/ExperimentLoader( 3380): 	at hec.a(PG:42)
E/ExperimentLoader( 3380): 	at hee.a(PG:102)
E/ExperimentLoader( 3380): 	at czr.a(PG:65)
E/ExperimentLoader( 3380): 	at kka.a(PG:108)
E/ExperimentLoader( 3380): 	at czp.a(PG:19176)
E/ExperimentLoader( 3380): 	at czp.a(PG:9081)
E/ExperimentLoader( 3380): 	at czq.run(PG:1686)
E/ExperimentLoader( 3380): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3380): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3380): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3380): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3380): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3380): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3380): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3380): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3380): 	at jdm.a(PG:77)
E/ExperimentLoader( 3380): 	... 15 more
E/ExperimentLoader( 3380): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3380): 	at fal.a(PG:38)
E/ExperimentLoader( 3380): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3380): 	... 17 more
,E/BooksAccountManager( 3614): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication,
E/BooksSync( 3614): Soft error
E/BooksSync( 3614): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3614): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3614): Sync error
E/BooksSync( 3614): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3614): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3614): Finished books sync
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 231227, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 230869, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2363): Disconnected process message: 10, size: 0
,I/jxcore-log( 3676): Connected to the server!
I/jxcore-log( 3676): 
,I/chromium( 3676): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,D/HeadsetStateMachine( 2363): Disconnected process message: 10, size: 0
,V/GoogleAuthProtoRequest( 3738): [403] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1355): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1355): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1355): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1355): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3738): [403] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3738): [403] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3738): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3738): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3738): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3738): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3738): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3738): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3738): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3738): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3738): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3738): 	at com.a.a.k.run(SourceFile:110)
,V/KeepSync( 3581): Connecting to GoogleApiClient
,I/art     ( 1355): Explicit concurrent mark sweep GC freed 56134(3MB) AllocSpace objects, 11(1143KB) LOS objects, 36% free, 27MB/43MB, paused 1.511ms total 54.222ms
,I/GLSUser ( 1355): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1355): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1355): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1355): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1779): Handling authorization failure
E/ClientConnectionOperation( 1779): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1779): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1779): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1779): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1779): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1779): 	... 7 more
,V/KeepSync( 3581): GoogleApiClient failed to connect with error code: 4,
E/SQLiteLog( 3581): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3581): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3581): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1355): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1355): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1355): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1355): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3581): IOException
E/KeepSync( 3581): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3581): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3581): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3581): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3581): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3581): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3581): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3581): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3581): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3581): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3581): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3581): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3581): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3581): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3581): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3581): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3581): 	... 10 more
W/KeepSync( 3581): Sync result 2
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 292702, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/BooksSync( 3614): Starting books sync for 61035162, extras: ade
,I/art     (  823): Explicit concurrent mark sweep GC freed 33712(1429KB) AllocSpace objects, 10(631KB) LOS objects, 31% free, 34MB/50MB, paused 1.443ms total 75.588ms
,I/BooksConfig( 3614): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1355): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1355): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1355): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1355): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1355): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1355): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1355): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1355): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3380): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3380): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3380): 	at jdm.a(PG:82)
E/HttpOperation( 3380): 	at jcs.o(PG:406)
E/HttpOperation( 3380): 	at jcn.a(PG:1379)
E/HttpOperation( 3380): 	at jcs.i(PG:143)
E/HttpOperation( 3380): 	at blb.a(PG:3937)
E/HttpOperation( 3380): 	at czp.a(PG:18188)
E/HttpOperation( 3380): 	at czp.a(PG:9081)
E/HttpOperation( 3380): 	at czq.run(PG:1686)
E/HttpOperation( 3380): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3380): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3380): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3380): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3380): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3380): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3380): 	at jdj.a(PG:4091)
E/HttpOperation( 3380): 	at jdj.a(PG:1125)
E/HttpOperation( 3380): 	at jdm.a(PG:77)
E/HttpOperation( 3380): 	... 12 more
E/HttpOperation( 3380): Caused by: faj: BadAuthentication
E/HttpOperation( 3380): 	at fal.a(PG:38)
E/HttpOperation( 3380): 	at jdj.a(PG:4089)
E/HttpOperation( 3380): 	... 14 more
,I/GLSUser ( 1355): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1355): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1355): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1355): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3614): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3614): Soft error
E/BooksSync( 3614): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3614): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3614): Sync error
E/BooksSync( 3614): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3614): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3614): Finished books sync
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 324227, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1355): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1355): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1355): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1355): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3380): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3380): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3380): 	at jdm.a(PG:82)
E/HttpOperation( 3380): 	at jcs.o(PG:406)
E/HttpOperation( 3380): 	at jcn.a(PG:1379)
E/HttpOperation( 3380): 	at jcs.i(PG:143)
E/HttpOperation( 3380): 	at hec.a(PG:42)
E/HttpOperation( 3380): 	at hee.a(PG:102)
E/HttpOperation( 3380): 	at czr.a(PG:65)
E/HttpOperation( 3380): 	at kka.a(PG:108)
E/HttpOperation( 3380): 	at czp.a(PG:19176)
E/HttpOperation( 3380): 	at czp.a(PG:9081)
E/HttpOperation( 3380): 	at czq.run(PG:1686)
E/HttpOperation( 3380): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3380): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3380): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3380): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3380): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3380): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3380): 	at jdj.a(PG:4091)
E/HttpOperation( 3380): 	at jdj.a(PG:1125)
E/HttpOperation( 3380): 	at jdm.a(PG:77)
E/HttpOperation( 3380): 	... 15 more
E/HttpOperation( 3380): Caused by: faj: BadAuthentication
E/HttpOperation( 3380): 	at fal.a(PG:38)
E/HttpOperation( 3380): 	at jdj.a(PG:4089)
E/HttpOperation( 3380): 	... 17 more
,E/ExperimentLoader( 3380): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3380): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3380): 	at jdm.a(PG:82)
E/ExperimentLoader( 3380): 	at jcs.o(PG:406)
E/ExperimentLoader( 3380): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3380): 	at jcs.i(PG:143)
E/ExperimentLoader( 3380): 	at hec.a(PG:42)
E/ExperimentLoader( 3380): 	at hee.a(PG:102)
E/ExperimentLoader( 3380): 	,at czr.a(PG:65)
E/ExperimentLoader( 3380): 	at kka.a(PG:108)
E/ExperimentLoader( 3380): 	at czp.a(PG:19176)
E/ExperimentLoader( 3380): 	at czp.a(PG:9081)
E/ExperimentLoader( 3380): 	,at czq.run(PG:1686)
E/ExperimentLoader( 3380): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3380): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3380): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3380): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3380): 	,at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3380): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3380): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3380): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3380): 	,at jdm.a(PG:77)
E/ExperimentLoader( 3380): 	... 15 more
E/ExperimentLoader( 3380): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3380): 	at fal.a(PG:38)
E/ExperimentLoader( 3380): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3380): 	... 17 more
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 323363, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/WifiService(  823): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@e31246f}
,E/WifiStateMachine(  823): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-48
,D/WifiService(  823): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@e31246f}
,E/LocSvc_IzatApiV02(  823): E/virtual int izat_core::IzatApiV02::injectLocation(GpsExtLocation):857]: error! inject position failed
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1355): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1355): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1355): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1355): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1355): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1355): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1355): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1355): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1355): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1355): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1355): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 3019): Failed to get auth token: User intervention required. Notification has been pushed.
,E/PlayEventLogger( 3019): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3019): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 3019): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3019): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/PlayEventLogger( 3019): 	,at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3019): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 3019): Ignoring header User-Agent because its value was null.
,D/HeadsetStateMachine( 2363): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2363): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2363): Disconnected process message: 10, size: 0
,V/GoogleAuthProtoRequest( 3738): [404] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1355): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1355): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1355): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1355): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3738): [404] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3738): [404] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3738): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3738): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3738): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3738): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3738): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3738): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3738): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3738): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3738): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3738): 	at com.a.a.k.run(SourceFile:110)
,V/KeepSync( 3581): Connecting to GoogleApiClient
,I/GLSUser ( 1355): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1355): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1355): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1355): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1779): Handling authorization failure
E/ClientConnectionOperation( 1779): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1779): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1779): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1779): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1779): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1779): 	... 7 more
,V/KeepSync( 3581): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3581): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3581): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3581): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1355): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1355): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1355): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1355): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3581): IOException
E/KeepSync( 3581): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3581): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3581): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3581): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3581): ,	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3581): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3581): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3581): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3581): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3581): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
,E/KeepSync( 3581): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3581): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3581): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3581): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3581): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3581): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3581): 	... 10 more
,W/KeepSync( 3581): Sync result 2
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 447461, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2363): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2363): Disconnected process message: 10, size: 0
,I/BooksSync( 3614): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3614): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1355): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1355): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1355): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1355): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1355): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1355): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1355): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1355): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3380): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3380): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3380): 	at jdm.a(PG:82)
E/HttpOperation( 3380): 	at jcs.o(PG:406)
E/HttpOperation( 3380): 	at jcn.a(PG:1379)
E/HttpOperation( 3380): 	at jcs.i(PG:143)
E/HttpOperation( 3380): 	at blb.a(PG:3937)
E/HttpOperation( 3380): 	at czp.a(PG:18188)
E/HttpOperation( 3380): 	at czp.a(PG:9081)
E/HttpOperation( 3380): 	at czq.run(PG:1686)
E/HttpOperation( 3380): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3380): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3380): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3380): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3380): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3380): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3380): 	at jdj.a(PG:4091)
E/HttpOperation( 3380): 	at jdj.a(PG:1125)
E/HttpOperation( 3380): 	at jdm.a(PG:77)
E/HttpOperation( 3380): 	... 12 more
E/HttpOperation( 3380): Caused by: faj: BadAuthentication
E/HttpOperation( 3380): 	at fal.a(PG:38)
E/HttpOperation( 3380): 	at jdj.a(PG:4089)
E/HttpOperation( 3380): 	... 14 more
,I/GLSUser ( 1355): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1355): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1355): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1355): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3380): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3380): java.io.IOException: Cannot obtain authentication token,
E/HttpOperation( 3380): 	at jdm.a(PG:82)
E/HttpOperation( 3380): 	at jcs.o(PG:406)
E/HttpOperation( 3380): 	at jcn.a(PG:1379)
E/HttpOperation( 3380): 	at jcs.i(PG:143)
E/HttpOperation( 3380): 	at hec.a(PG:42)
E/HttpOperation( 3380): 	at hee.a(PG:102)
E/HttpOperation( 3380): 	at czr.a(PG:65)
E/HttpOperation( 3380): 	at kka.a(PG:108)
,E/HttpOperation( 3380): 	at czp.a(PG:19176)
E/HttpOperation( 3380): 	at czp.a(PG:9081)
E/HttpOperation( 3380): 	at czq.run(PG:1686)
E/HttpOperation( 3380): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3380): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237),
E/HttpOperation( 3380): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3380): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3380): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3380): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3380): 	,at jdj.a(PG:4091)
E/HttpOperation( 3380): 	at jdj.a(PG:1125)
E/HttpOperation( 3380): 	at jdm.a(PG:77)
E/HttpOperation( 3380): 	... 15 more
E/HttpOperation( 3380): Caused by: faj: BadAuthentication
E/HttpOperation( 3380): 	at fal.a(PG:38)
E/HttpOperation( 3380): 	,at jdj.a(PG:4089)
E/HttpOperation( 3380): 	... 17 more
E/ExperimentLoader( 3380): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3380): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3380): 	at jdm.a(PG:82)
E/ExperimentLoader( 3380): 	at jcs.o(PG:406)
E/ExperimentLoader( 3380): 	at jcn.a(PG:1379)
,E/ExperimentLoader( 3380): 	at jcs.i(PG:143)
E/ExperimentLoader( 3380): 	at hec.a(PG:42)
E/ExperimentLoader( 3380): 	at hee.a(PG:102)
E/ExperimentLoader( 3380): 	at czr.a(PG:65)
E/ExperimentLoader( 3380): 	at kka.a(PG:108)
E/ExperimentLoader( 3380): 	at czp.a(PG:19176)
E/ExperimentLoader( 3380): 	,at czp.a(PG:9081)
E/ExperimentLoader( 3380): 	at czq.run(PG:1686)
E/ExperimentLoader( 3380): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3380): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3380): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3380): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587),
E/ExperimentLoader( 3380): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3380): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3380): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3380): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3380): 	at jdm.a(PG:77)
E/ExperimentLoader( 3380): 	... 15 more
E/ExperimentLoader( 3380): Caused by: faj: BadAuthentication,
E/ExperimentLoader( 3380): 	at fal.a(PG:38)
E/ExperimentLoader( 3380): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3380): 	... 17 more,
,I/art     (  823): Explicit concurrent mark sweep GC freed 34147(1548KB) AllocSpace objects, 11(458KB) LOS objects, 31% free, 34MB/50MB, paused 1.478ms total 69.009ms,
,I/GLSUser ( 1355): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books,
I/GLSUser ( 1355): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1355): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1355): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3614): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3614): Soft error
E/BooksSync( 3614): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3614): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3614): Sync error
E/BooksSync( 3614): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3614): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3614): Finished books sync
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 480454, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 478659, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2363): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2363): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2363): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2363): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2363): Disconnected process message: 10, size: 0
,D/Finsky  ( 3019): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1355): Explicit concurrent mark sweep GC freed 51994(2MB) AllocSpace objects, 13(1433KB) LOS objects, 36% free, 27MB/43MB, paused 980us total 47.850ms
,V/GoogleAuthProtoRequest( 3738): [405] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1355): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1355): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1355): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1355): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 3019): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 1355): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1355): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1355): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1355): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3738): [405] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3738): [405] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3738): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3738): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3738): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3738): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3738): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3738): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3738): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3738): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3738): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3738): 	at com.a.a.k.run(SourceFile:110)
,I/GLSUser ( 1355): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1355): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1355): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1355): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1355): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1355): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1355): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1355): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 3019): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1355): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1355): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1355): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1355): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 3019): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 3019): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 3019): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3019): [1] DailyHygiene.reschedule: Scheduling new run in 29 minutes (failures=2)
,D/DeviceConnectionService( 1796): client connected with version: 7571000,
,D/HeadsetStateMachine( 2363): Disconnected process message: 10, size: 0
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1355): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1355): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1355): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1355): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3019): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3019): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3019): [1] 5.onFinished: Scheduling replication attempt 1.
,V/KeepSync( 3581): Connecting to GoogleApiClient
,I/GLSUser ( 1355): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1355): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1355): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1355): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1779): Handling authorization failure
E/ClientConnectionOperation( 1779): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1779): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1779): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1779): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1779): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1779): 	... 7 more
,V/KeepSync( 3581): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3581): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3581): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3581): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1355): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1355): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1355): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1355): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3581): IOException
E/KeepSync( 3581): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3581): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3581): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3581): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3581): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3581): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3581): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3581): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3581): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3581): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3581): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3581): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3581): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3581): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3581): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3581): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3581): 	... 10 more
W/KeepSync( 3581): Sync result 2
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 705611, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1],
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1355): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1355): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1355): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1355): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3019): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3019): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3019): [1] 5.onFinished: Scheduling replication attempt 2.
,D/HeadsetStateMachine( 2363): Disconnected process message: 10, size: 0
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  823): Explicit concurrent mark sweep GC freed 31343(1338KB) AllocSpace objects, 6(378KB) LOS objects, 31% free, 34MB/50MB, paused 1.707ms total 80.031ms,
,I/GLSUser ( 1355): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1355): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1355): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1355): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/Finsky  ( 3019): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3019): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3019): [1] 5.onFinished: Scheduling replication attempt 3.
,D/HeadsetStateMachine( 2363): Disconnected process message: 10, size: 0
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1355): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure,
I/GLSUser ( 1355): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1355): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1355): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3019): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3019): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3019): [1] 5.onFinished: Scheduling replication attempt 4.
,I/GLSUser ( 1355): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1355): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1355): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1355): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/HttpOperation( 3380): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3380): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3380): 	at jdm.a(PG:82)
E/HttpOperation( 3380): 	at jcs.o(PG:406)
E/HttpOperation( 3380): 	at jcn.a(PG:1379)
E/HttpOperation( 3380): 	at jcs.i(PG:143)
E/HttpOperation( 3380): 	at blb.a(PG:3937)
E/HttpOperation( 3380): 	at czp.a(PG:18188)
E/HttpOperation( 3380): 	at czp.a(PG:9081)
E/HttpOperation( 3380): 	at czq.run(PG:1686)
E/HttpOperation( 3380): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3380): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3380): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3380): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3380): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3380): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3380): 	at jdj.a(PG:4091)
E/HttpOperation( 3380): 	at jdj.a(PG:1125)
E/HttpOperation( 3380): 	at jdm.a(PG:77)
E/HttpOperation( 3380): 	... 12 more
E/HttpOperation( 3380): Caused by: faj: BadAuthentication
E/HttpOperation( 3380): 	at fal.a(PG:38)
E/HttpOperation( 3380): 	at jdj.a(PG:4089)
E/HttpOperation( 3380): 	... 14 more
,I/GLSUser ( 1355): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1355): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1355): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1355): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3380): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3380): java.io.IOException: Cannot obtain authentication token
,E/HttpOperation( 3380): 	at jdm.a(PG:82)
E/HttpOperation( 3380): 	at jcs.o(PG:406)
E/HttpOperation( 3380): 	at jcn.a(PG:1379)
E/HttpOperation( 3380): 	at jcs.i(PG:143)
E/HttpOperation( 3380): 	at hec.a(PG:42)
,E/HttpOperation( 3380): 	at hee.a(PG:102)
E/HttpOperation( 3380): 	at czr.a(PG:65)
E/HttpOperation( 3380): 	at kka.a(PG:108)
E/HttpOperation( 3380): 	at czp.a(PG:19176)
E/HttpOperation( 3380): 	at czp.a(PG:9081)
E/HttpOperation( 3380): 	at czq.run(PG:1686)
E/HttpOperation( 3380): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3380): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3380): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3380): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3380): 	at java.lang.Thread.run(Thread.java:818)
,E/HttpOperation( 3380): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3380): 	at jdj.a(PG:4091)
E/HttpOperation( 3380): 	at jdj.a(PG:1125)
E/HttpOperation( 3380): 	at jdm.a(PG:77)
E/HttpOperation( 3380): 	... 15 more
E/HttpOperation( 3380): Caused by: faj: BadAuthentication
E/HttpOperation( 3380): 	at fal.a(PG:38)
E/HttpOperation( 3380): 	at jdj.a(PG:4089)
E/HttpOperation( 3380): 	... 17 more
E/ExperimentLoader( 3380): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3380): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3380): 	at jdm.a(PG:82)
E/ExperimentLoader( 3380): 	at jcs.o(PG:406)
E/ExperimentLoader( 3380): 	at jcn.a(PG:1379)
,E/ExperimentLoader( 3380): 	at jcs.i(PG:143)
E/ExperimentLoader( 3380): 	at hec.a(PG:42)
E/ExperimentLoader( 3380): 	at hee.a(PG:102)
E/ExperimentLoader( 3380): 	at czr.a(PG:65)
E/ExperimentLoader( 3380): 	at kka.a(PG:108)
E/ExperimentLoader( 3380): 	at czp.a(PG:19176)
E/ExperimentLoader( 3380): 	at czp.a(PG:9081)
E/ExperimentLoader( 3380): 	at czq.run(PG:1686)
,E/ExperimentLoader( 3380): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3380): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3380): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3380): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3380): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3380): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3380): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3380): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3380): 	at jdm.a(PG:77)
E/ExperimentLoader( 3380): 	... 15 more
E/ExperimentLoader( 3380): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3380): 	at fal.a(PG:38)
E/ExperimentLoader( 3380): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3380): 	... 17 more
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 767938, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1355): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1355): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1355): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1355): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3019): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3019): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3019): [1] 5.onFinished: Scheduling replication attempt 5.
,D/HeadsetStateMachine( 2363): Disconnected process message: 10, size: 0
,I/BooksSync( 3614): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3614): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1355): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1355): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1355): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1355): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1355): Explicit concurrent mark sweep GC freed 48959(2MB) AllocSpace objects, 13(1434KB) LOS objects, 37% free, 26MB/42MB, paused 1.753ms total 58.370ms
,I/GLSUser ( 1355): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1355): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1355): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1355): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3614): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3614): Soft error
E/BooksSync( 3614): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3614): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3614): Sync error
E/BooksSync( 3614): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3614): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3614): Finished books sync
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 771679, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2363): Disconnected process message: 10, size: 0
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1355): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure,
I/GLSUser ( 1355): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1355): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1355): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/Finsky  ( 3019): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3019): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3019): [1] 5.onFinished: Giving up after 6 failures.
,D/HeadsetStateMachine( 2363): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2363): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2363): Disconnected process message: 10, size: 0
,W/bt-btm  ( 2363): Stopping oneshot timer
,D/HeadsetStateMachine( 2363): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2363): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2363): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2363): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2363): Disconnected process message: 10, size: 0
,D/GCM     ( 1355): Message class com.google.f.a.a.i
,V/GoogleAuthProtoRequest( 3738): [406] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GoogleURLConnFactory( 1355): Using platform SSLCertificateSocketFactory
,I/GLSUser ( 1355): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1355): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1355): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1355): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3738): [406] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3738): [406] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3738): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3738): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3738): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3738): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3738): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3738): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3738): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3738): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3738): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3738): 	at com.a.a.k.run(SourceFile:110)
,D/HeadsetStateMachine( 2363): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2363): Disconnected process message: 10, size: 0
,I/art     (  823): Explicit concurrent mark sweep GC freed 39119(1857KB) AllocSpace objects, 5(268KB) LOS objects, 32% free, 33MB/49MB, paused 2.164ms total 74.329ms
,V/KeepSync( 3581): Connecting to GoogleApiClient
,I/GLSUser ( 1355): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1355): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1355): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1355): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1779): Handling authorization failure
E/ClientConnectionOperation( 1779): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1779): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1779): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1779): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1779): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1779): 	... 7 more
,V/KeepSync( 3581): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3581): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3581): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3581): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1355): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1355): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1355): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1355): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/KeepSync( 3581): IOException
E/KeepSync( 3581): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3581): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3581): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3581): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3581): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3581): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3581): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3581): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3581): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3581): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3581): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3581): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3581): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3581): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3581): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3581): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3581): 	... 10 more
W/KeepSync( 3581): Sync result 2
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 1221593, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2363): Disconnected process message: 10, size: 0
,I/UsageStatsService(  823): User[0] Flushing usage stats to disk
,I/GLSUser ( 1355): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1355): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1355): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1355): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3380): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3380): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3380): 	at jdm.a(PG:82)
E/HttpOperation( 3380): 	at jcs.o(PG:406)
E/HttpOperation( 3380): 	at jcn.a(PG:1379)
E/HttpOperation( 3380): 	at jcs.i(PG:143)
E/HttpOperation( 3380): 	at blb.a(PG:3937)
E/HttpOperation( 3380): 	at czp.a(PG:18188)
E/HttpOperation( 3380): 	at czp.a(PG:9081)
E/HttpOperation( 3380): 	at czq.run(PG:1686)
E/HttpOperation( 3380): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3380): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3380): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3380): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3380): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3380): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3380): 	at jdj.a(PG:4091)
E/HttpOperation( 3380): 	at jdj.a(PG:1125)
E/HttpOperation( 3380): 	at jdm.a(PG:77)
E/HttpOperation( 3380): 	... 12 more
E/HttpOperation( 3380): Caused by: faj: BadAuthentication
E/HttpOperation( 3380): 	at fal.a(PG:38)
E/HttpOperation( 3380): 	at jdj.a(PG:4089)
E/HttpOperation( 3380): 	... 14 more
,I/GLSUser ( 1355): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1355): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1355): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1355): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3380): [getmobileexperiments] Unexpected exception,
E/HttpOperation( 3380): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3380): 	at jdm.a(PG:82)
E/HttpOperation( 3380): 	at jcs.o(PG:406)
,E/HttpOperation( 3380): 	at jcn.a(PG:1379)
E/HttpOperation( 3380): 	at jcs.i(PG:143)
E/HttpOperation( 3380): 	at hec.a(PG:42)
E/HttpOperation( 3380): 	at hee.a(PG:102)
E/HttpOperation( 3380): 	,at czr.a(PG:65)
E/HttpOperation( 3380): 	at kka.a(PG:108)
E/HttpOperation( 3380): 	at czp.a(PG:19176)
E/HttpOperation( 3380): 	at czp.a(PG:9081)
E/HttpOperation( 3380): 	,at czq.run(PG:1686)
E/HttpOperation( 3380): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3380): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3380): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3380): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587),
E/HttpOperation( 3380): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3380): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3380): 	at jdj.a(PG:4091)
E/HttpOperation( 3380): 	at jdj.a(PG:1125)
E/HttpOperation( 3380): 	at jdm.a(PG:77),
E/HttpOperation( 3380): 	... 15 more
E/HttpOperation( 3380): Caused by: faj: BadAuthentication
E/HttpOperation( 3380): 	at fal.a(PG:38)
E/HttpOperation( 3380): 	at jdj.a(PG:4089)
E/HttpOperation( 3380): 	,... 17 more
E/ExperimentLoader( 3380): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3380): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3380): 	at jdm.a(PG:82)
E/ExperimentLoader( 3380): 	at jcs.o(PG:406)
,E/ExperimentLoader( 3380): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3380): 	at jcs.i(PG:143)
E/ExperimentLoader( 3380): 	at hec.a(PG:42)
E/ExperimentLoader( 3380): 	at hee.a(PG:102)
E/ExperimentLoader( 3380): 	at czr.a(PG:65)
,E/ExperimentLoader( 3380): 	at kka.a(PG:108)
E/ExperimentLoader( 3380): 	at czp.a(PG:19176)
E/ExperimentLoader( 3380): 	at czp.a(PG:9081)
E/ExperimentLoader( 3380): 	,at czq.run(PG:1686)
E/ExperimentLoader( 3380): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3380): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3380): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3380): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3380): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3380): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3380): ,	at jdj.a(PG:4091)
E/ExperimentLoader( 3380): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3380): 	at jdm.a(PG:77)
E/ExperimentLoader( 3380): 	... 15 more
E/ExperimentLoader( 3380): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3380): 	at fal.a(PG:38)
E/ExperimentLoader( 3380): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3380): 	... 17 more
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 1288443, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2363): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2363): Disconnected process message: 10, size: 0
,I/BooksSync( 3614): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3614): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1355): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1355): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1355): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1355): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1355): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1355): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1355): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1355): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3614): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3614): Soft error
E/BooksSync( 3614): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3614): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3614): Sync error
E/BooksSync( 3614): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3614): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 3614): Finished books sync
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1326036, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2363): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2363): Disconnected process message: 10, size: 0
,I/art     ( 1355): Explicit concurrent mark sweep GC freed 62930(3MB) AllocSpace objects, 8(693KB) LOS objects, 36% free, 27MB/43MB, paused 1.369ms total 57.277ms
,D/HeadsetStateMachine( 2363): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2363): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2363): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2363): Disconnected process message: 10, size: 0
,I/EventLogService( 1779): Opted in for usage reporting
,I/EventLogService( 1779): Aggregate from 1450237993465 (log), 1450237993465 (data)
,W/EventLogAggregator( 1779): Unknown tag: snet_gcore
,W/EventLogAggregator( 1779): Unknown tag: snet_launch_service
,I/ServiceDumpSys( 1779): dumping service [account]
,D/HeadsetStateMachine( 2363): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2363): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2363): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2363): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2363): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2363): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2363): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2363): Disconnected process message: 10, size: 0
,W/bt-btm  ( 2363): Stopping oneshot timer
,I/ProcessStatsService(  823): Prepared write state in 21ms,
,I/ProcessStatsService(  823): Pruning old procstats: /data/system/procstats/state-2015-12-15-18-04-11.bin
,D/HeadsetStateMachine( 2363): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2363): Disconnected process message: 10, size: 0
,I/ActivityManager(  823): Killing 3435:com.android.defcontainer/u0a7 (adj 15): empty for 1810s
,I/ActivityManager(  823): Killing 3536:com.google.android.apps.docs/u0a46 (adj 15): empty for 1811s
,D/HeadsetStateMachine( 2363): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2363): Disconnected process message: 10, size: 0
,TIME-OUT KILL (timeout was 1800000ms)
```
