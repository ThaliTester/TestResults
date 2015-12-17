#### Test 539786639813e59_thali05_motorola-Nexus 6 Logs


```
--------- beginning of main
D/HeadsetStateMachine( 2365): Disconnected process message: 10, size: 0
,D/AndroidRuntime( 3787): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 3787): CheckJNI is OFF
D/AndroidRuntime( 3787): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  821): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/WindowManager(  821): addAppToken: AppWindowToken{103b7315 token=Token{26bd54cc ActivityRecord{16d5eff u0 com.test.thalitest/.MainActivity t26}}} to stack=1 task=26 at 0
D/AndroidRuntime( 3787): Shutting down VM
V/WindowManager(  821): Adding window Window{b67eaf6 u0 Starting com.test.thalitest} at 2 of 7 (after Window{313ede10 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
I/HotwordDetector( 1506): Closing mic
I/MicrophoneInputStream( 1506): mic_close com.google.android.apps.gsa.speech.audio.u@222fa266
D/audio_hw_primary(  357): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  357): disable_snd_device: snd_device(55: voice-rec-mic)
I/ActivityManager(  821): Start proc 3801:com.test.thalitest/u0a265 for activity com.test.thalitest/.MainActivity
I/SoundTriggerHwService::Module(  357): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1506): Hotword detection finished
I/HotwordRecognitionRnr( 1506): Stopping hotword detection.
I/ActivityManager(  821): Killing 2725:com.google.android.gm/u0a78 (adj 15): empty #17
,E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1720542483
E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,I/ActivityManager(  821): Killing 3390:com.google.android.apps.maps/u0a65 (adj 15): empty #18
,I/kickstart(  872): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
I/kickstart(  872): STATUS: Wrote to /sys/power/wake_lock
,E/kickstart(  872): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2
I/kickstart(  872): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2' for writing
,I/WebViewFactory( 3801): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3801): Time to load native libraries: 2 ms (timestamps 597-599)
,I/LibraryLoader( 3801): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3801): Binding Chromium to main looper Looper (main, tid 1) {2a238699}
,I/LibraryLoader( 3801): Expected native library version number "",actual native library version number ""
I/chromium( 3801): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3801): Initializing chromium process, singleProcess=true
W/art     ( 3801): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3801): ApplicationContext is null in ApplicationStatus
,W/chromium( 3801): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3801): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3801): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3801): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/BluetoothManagerService(  821): Message: 20
D/BluetoothManagerService(  821): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@113efda6:true
,W/art     ( 3801): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3801): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3801): CordovaWebView is running on device made by: motorola
,W/art     ( 3801): Attempt to remove local handle scope entry from IRT, ignoring,
,W/art     ( 3801): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3801): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,D/Atlas   ( 3801): Validating map...
,V/WindowManager(  821): Adding window Window{c181c56 u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{b67eaf6 u0 Starting com.test.thalitest})
,W/chromium( 3801): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3801): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3801): Enabling debug mode 0
,I/ActivityManager(  821): Displayed com.test.thalitest/.MainActivity: +882ms
,I/Keyboard.Facilitator( 1215): onFinishInput()
,W/BindingManager( 3801): Cannot call determinedVisibility() - never saw a connection for the pid: 3801
,D/JsMessageQueue( 3801): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3801): JniHelper::setJavaVM(0xb489d200), pthread_self() = -1576254592
,D/JX-Cordova( 3801): jxcore cordova android initializing
,I/kickstart(  872): STATUS: Received file 'm9kefs2'
I/kickstart(  872): STATUS: 950272 bytes transferred in 0.990650 seconds
I/kickstart(  872): STATUS: Successfully downloaded files from target 
I/kickstart(  872): STATUS: Wrote to /sys/power/wake_unlock
,I/kickstart(  872): STATUS: Sahara protocol completed,
,E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=2.29 targetRoamBSSID=any RSSI=-47
E/WifiStateMachine(  821): WifiStateMachine starting scan for "NG7005g"WPA_PSK with 2412,5220
,W/jxcore-log( 3801): Initializing JXcore engine
W/jxcore-log( 3801): JXcore engine is ready
,W/jxcore-log( 3801): Starting JXcore engine
,W/.test.thalitest( 3801): type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[11534]" dev="sockfs" ino=11534 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 3801): type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,W/.test.thalitest( 3801): type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[11713]" dev="sockfs" ino=11713 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0,
W/.test.thalitest( 3801): type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[22832]" dev="sockfs" ino=22832 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 3801): Platform android
,W/jxcore-log( 3801): 
W/jxcore-log( 3801): Process ARCH arm
W/jxcore-log( 3801): 
,I/jxcore-log( 3801): JXcore Cordova bridge is ready!
I/jxcore-log( 3801): ,
W/jxcore-log( 3801): JXcore engine is started
I/Choreographer( 3801): Skipped 140 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3801): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3801): Toggling radios to true
I/jxcore-log( 3801): 
,D/BluetoothAdapter( 3801): enable(): BT is already enabled..!
,D/WifiService(  821): New client listening to asynchronous messages
D/WifiService(  821): setWifiEnabled: true pid=3801, uid=10265
E/WifiService(  821): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3801): Radios toggled
I/jxcore-log( 3801): 
,I/wpa_supplicant( 1213): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  821): WifiStateMachine: Leaving Connected state
,E/WifiConfigStore(  821): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  353): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1470): Read error: ssl=0xaed24a00: I/O error during system call, Connection timed out
,V/NativeCrypto( 1470): SSL shutdown failed: ssl=0xaed24a00: I/O error during system call, Broken pipe
,D/ConnectivityService(  821): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,D/ConnectivityService(  821): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
E/WifiStateMachine(  821): Start Disconnecting Watchdog 1
,D/ConnectivityService(  821): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10011
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): DefaultState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): Forcing reevaluation
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
,E/WifiStateMachine(  821): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,D/CommandListener(  353): Clearing all IP addresses on wlan0
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
,D/WifiNetworkAgent(  821): NetworkAgent: NetworkAgent channel lost
,E/WifiStateMachine(  821): CMD_AUTO_CONNECT sup state CompletedState my state DisconnectedState nid=0 roam=3
E/WifiStateMachine(  821): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=0
D/ConnectivityService(  821): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityManager.CallbackHandler( 1067): CM callback handler got msg 524292
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): OfflineState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): Disconnected - quitting
D/CSLegacyTypeTracker(  821): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  821): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/Tethering(  821): MasterInitialState.processMessage what=3
E/ConnectivityService(  821): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/ConnectivityService(  821): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/Tethering(  821): MasterInitialState.processMessage what=3
,E/WifiConfigStore(  821): Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiConfigStore(  821): will read network variables netId=0
,D/PhoneInterfaceManager( 1261): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
,E/PhoneInterfaceManager( 1261): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
D/TelephonyManager(  821): getDataEnabled: retVal=false
,E/WifiStateMachine(  821): CMD_AUTO_CONNECT did save config ->  nid=0
V/MusicLeanback( 3035): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,E/WifiConfigStore(  821): will read network variables netId=0
,I/wpa_supplicant( 1213): wlan0: Trying to associate with SSID 'NG7005g'
E/GpsLocationProvider(  821): No APN found to select.
,I/ActivityManager(  821): Start proc 3862:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.steen.receiver.ConnectivityChangeReceiver
,D/PhoneInterfaceManager( 1261): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1261): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
D/TelephonyManager(  821): getDataEnabled: retVal=false
,E/GpsLocationProvider(  821): No APN found to select.
,I/ActivityManager(  821): Start proc 3888:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,I/ActivityManager(  821): Killing 2278:com.google.android.calendar/u0a37 (adj 15): empty #17
,D/SprintDMReceiver( 3888): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3888): simOperator:  IMSI: null
,D/SprintDMReceiver( 3888): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1772): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1772): onCreate
,D/SystemUpdateService( 1772): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1772): active receiver: enabled
,I/wpa_supplicant( 1213): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/SystemUpdateService( 1772): showing system update notification
,I/iu.Environment( 1772): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1772): num queued entries: 0
I/iu.UploadsManager( 1772): num updated entries: 0
I/iu.SyncManager( 1772): NEXT; no task
,I/ValidateNoPeople(  821): skipping global notification
,V/SystemUpdateService( 1772): retry (wakeup: false) in 3599976 ms
,D/ChimeraCfgMgr( 1772): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/wpa_supplicant( 1213): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1213): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=0 id_str=]
,D/SystemUpdateService( 1772): onDestroy
,D/ConnectivityService(  821): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} }
E/WifiConfigStore(  821): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  821): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,I/ActivityManager(  821): Start proc 3909:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,E/WifiConfigStore(  821): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  353): Setting iface cfg
,E/WifiStateMachine(  821): Start Dhcp Watchdog 2
,I/Babel   ( 3097): connection state changed from UNKNOWN to DISCONNECTED
,E/WifiStateMachine(  821):  WifiLinkLayerStats: 
E/WifiStateMachine(  821):  my bss beacon rx: 580
E/WifiStateMachine(  821):  RSSI mgmt: -47
E/WifiStateMachine(  821):  BE :  rx=220 tx=141 lost=0 retries=1
E/WifiStateMachine(  821):  BK :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  821):  VI :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  821):  VO :  rx=4 tx=0 lost=0 retries=0
E/WifiStateMachine(  821):  on_time : 21102 tx_time=226 rx_time=541 scan_time=0
,I/ActivityManager(  821): Killing 3346:com.android.providers.calendar/u0a3 (adj 15): empty #17
,D/ConnectivityService(  821): updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,E/native  (  821): do suspend false
,E/WifiStateMachine(  821): scanCount==0 - aborting
,I/GAv4    ( 3909): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3909):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3909):   adb logcat -s GAv4
,W/GAv4    ( 3909): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3909): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3909): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/dhcpcd  ( 3934): version 5.5.6 starting
,I/dhcpcd  ( 3934): wlan0: rebinding lease of 192.168.1.122
,I/art     (  821): Explicit concurrent mark sweep GC freed 48361(2MB) AllocSpace objects, 11(270KB) LOS objects, 32% free, 33MB/49MB, paused 1.691ms total 77.769ms
,I/WebViewFactory( 3909): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3909): Time to load native libraries: 1 ms (timestamps 4998-4999)
I/LibraryLoader( 3909): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3909): Binding Chromium to main looper Looper (main, tid 1) {218d8534}
,I/LibraryLoader( 3909): Expected native library version number "",actual native library version number ""
,I/chromium( 3909): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3909): Initializing chromium process, singleProcess=true
,W/art     ( 3909): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3909): ApplicationContext is null in ApplicationStatus
,W/chromium( 3909): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3909): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3909): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3909): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,W/AudioManagerAndroid( 3909): Requires BLUETOOTH permission
,I/NSApplication( 3909): Starting up...
,I/ActivityManager(  821): Start proc 3972:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,I/ActivityManager(  821): Killing 1362:android.process.acore/u0a5 (adj 15): empty #17
,I/ActivityManager(  821): Start proc 3998:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
I/ActivityManager(  821): Killing 3610:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/jxcore-log( 3801): Got Device Bluetooth address: F8:CF:C5:D9:E5:61
I/jxcore-log( 3801): 
I/jxcore-log( 3801): my name is : motorola-Nexus 6_PT6358
I/jxcore-log( 3801): 
,V/MusicLeanback( 3035): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/ActivityManager(  821): Killing 3631:com.android.musicfx/u0a18 (adj 15): empty #17
,I/jxcore-log( 3801): attempting to connect to test coordinator
,I/jxcore-log( 3801): 
I/jxcore-log( 3801): check test folder
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): found test : ./testFindPeers.js,
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): found test : ./testReConnect.js
,I/jxcore-log( 3801): 
,I/jxcore-log( 3801): found test : ./testSendData.js
,I/jxcore-log( 3801): 
,I/jxcore-log( 3801): Test app app.js loaded
,I/jxcore-log( 3801): 
,I/jxcore-log( 3801): DBG, CoordinatorConnector connect_error called
,I/jxcore-log( 3801): 
,I/Choreographer( 3801): Skipped 123 frames!  The application may be doing too much work on its main thread.,
,I/chromium( 3801): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51),
,D/SprintDMReceiver( 3888): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3888): simOperator:  IMSI: null
D/SprintDMReceiver( 3888): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1772): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1772): onCreate
,D/SystemUpdateService( 1772): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1772): active receiver: enabled
,I/SystemUpdateService( 1772): showing system update notification
,I/ValidateNoPeople(  821): skipping global notification
,V/SystemUpdateService( 1772): retry (wakeup: false) in 3599983 ms
,D/ChimeraCfgMgr( 1772): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/SystemUpdateService( 1772): onDestroy
,I/dhcpcd  ( 3934): wlan0: acknowledged 192.168.1.122 from 192.168.1.1
,I/dhcpcd  ( 3934): wlan0: leased 192.168.1.122 for 86400 seconds,
,D/ConnectivityService(  821): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  821): Adding iface wlan0 to network 101
,E/WifiStateMachine(  821): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  821): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  821): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  821): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  821): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  821): Setting Dns servers for network 101 to [/192.168.1.1]
,D/ConnectivityService(  821): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  821): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  821): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  821): Connected
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  821): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  821): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
,D/ConnectivityService(  821): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  821):    accepting network in place of null
,D/ConnectivityService(  821): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} }
,D/ConnectivityService(  821): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1067): CM callback handler got msg 524290
D/CSLegacyTypeTracker(  821): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  821): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 3035): type=WIFI subType= reason=null isConnected=true
,D/PhoneInterfaceManager( 1261): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1261): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
V/MusicLeanback( 3035): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/TelephonyManager(  821): getDataEnabled: retVal=false
,E/GpsLocationProvider(  821): No APN found to select.
,D/SprintDMReceiver( 3888): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3888): simOperator:  IMSI: null
,D/SprintDMReceiver( 3888): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1772): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1772): onCreate
,D/SystemUpdateService( 1772): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1772): active receiver: enabled
,I/SystemUpdateService( 1772): showing system update notification
,I/jxcore-log( 3801): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3801): 
,I/iu.Environment( 1772): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1772): num queued entries: 0
I/iu.UploadsManager( 1772): num updated entries: 0
I/iu.SyncManager( 1772): NEXT; no task
,D/ChimeraCfgMgr( 1772): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/ValidateNoPeople(  821): skipping global notification
,D/ChimeraCfgMgr( 1772): Loading module com.google.android.gms.kids from APK com.google.android.gms
,V/SystemUpdateService( 1772): retry (wakeup: false) in 3599976 ms
,D/SystemUpdateService( 1772): onDestroy
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  821): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 17 Dec 2015 14:11:59 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1450361519851], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1450361519834]}
I/GLSUser ( 1470): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1470): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1470): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1470): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  821): Validated
,D/ConnectivityService(  821): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null,
D/ConnectivityService(  821): Validated NetworkAgentInfo [WIFI () - 101],
D/ConnectivityService(  821): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  821): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  821): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1067): CM callback handler got msg 524290,
,V/GLSActivity( 1470): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/Herrevad( 1772): NQAS connected
,W/Kids    ( 1772): [AccountUtils] Account not ready
W/Kids    ( 1772): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 1772): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 1772): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 1772): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 1772): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 1772): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 1772): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 1772): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 1772): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 1772): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 1772): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 1772): 	at java.lang.Thread.run(Thread.java:818)
,I/Babel   ( 3097): connection state changed from DISCONNECTED to CONNECTED
,I/art     ( 1797): Explicit concurrent mark sweep GC freed 15725(942KB) AllocSpace objects, 11(176KB) LOS objects, 37% free, 26MB/42MB, paused 1.399ms total 42.592ms
,E/DataBuffer( 1797): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@de53214)
,D/GCM     ( 1470): Connected
,D/GCM     ( 1470): Message class com.google.f.a.a.p
,D/ConnectivityService(  821): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/jxcore-log( 3801): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3801): 
,V/GLSActivity( 1470): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1470): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1470): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1470): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1470): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1470): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3220): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3220): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3220): [1] 5.onFinished: Scheduling replication attempt 3.
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 3801): BLE supported!!
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3801): 
,E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=6.89 rxSuccessRate=8.25 targetRoamBSSID=any RSSI=-47
E/WifiStateMachine(  821): WifiStateMachine L2Connected CMD_START_SCAN source -2 10, 11 -> obsolete
,I/jxcore-log( 3801): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3801): 
,E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=2.22 rxSuccessRate=5.06 targetRoamBSSID=any RSSI=-47
E/WifiStateMachine(  821): WifiStateMachine L2Connected CMD_START_SCAN source -2 9, 11 -> obsolete
,I/PowerManagerService(  821): Going to sleep due to screen timeout (uid 1000)...
,I/Adreno  (  821): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/PermissionCache(  260): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (244 us)
,I/DisplayManagerService(  821): Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,V/ActivityManager(  821): Display changed displayId=0
,D/SurfaceFlinger(  260): Set power mode=0, type=0 flinger=0xb6082000
,D/qdhwcomposer(  260): hwc_setPowerMode: Setting mode 0 on display: 0
,I/qdhwcomposer(  260): handle_blank_event: dpy:0 panel power state: 0,
,D/qdhwcomposer(  260): hwc_setPowerMode: Done setting mode 0 on display 0
,D/SurfaceControl(  821): Excessive delay in setPowerMode(): 281ms
I/DreamManagerService(  821): Entering dreamland.
,I/PowerManagerService(  821): Dozing...
,I/DreamController(  821): Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0,
,D/audio_hw_primary(  357): adev_set_parameters: enter: screen_state=on
D/mot_vr_audio_hw(  357): adev_set_parameters: screen_state=on
,E/WifiStateMachine(  821): cancelDelayedScan -> 12
,E/native  (  821): do suspend false
,I/Keyboard.Facilitator( 1215): onFinishInput()
,E/WifiStateMachine(  821): cancelDelayedScan -> 14
,E/native  (  821): do suspend true
,D/audio_hw_primary(  357): adev_set_parameters: enter: screen_state=off
,D/mot_vr_audio_hw(  357): adev_set_parameters: screen_state=off
,E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-47
E/WifiStateMachine(  821): WifiStateMachine L2Connected CMD_START_SCAN source -2 13, 14 -> obsolete
,I/jxcore-log( 3801): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3801): 
,E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-47
,E/WifiStateMachine(  821): WifiStateMachine L2Connected CMD_START_SCAN source -2 11, 14 -> obsolete
,V/GLSActivity( 1470): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1470): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1470): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1470): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1470): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1470): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3220): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3220): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3220): [1] 5.onFinished: Scheduling replication attempt 4.
,I/GLSUser ( 1470): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1470): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1470): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1470): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1470): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3512): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3512): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3512): 	at jdm.a(PG:82)
,E/HttpOperation( 3512): 	at jcs.o(PG:406)
E/HttpOperation( 3512): 	at jcn.a(PG:1379)
E/HttpOperation( 3512): 	at jcs.i(PG:143)
E/HttpOperation( 3512): 	at blb.a(PG:3937)
E/HttpOperation( 3512): 	,at czp.a(PG:18188)
E/HttpOperation( 3512): 	at czp.a(PG:9081)
E/HttpOperation( 3512): 	at czq.run(PG:1686)
E/HttpOperation( 3512): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3512): 	,at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3512): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3512): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3512): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3512): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3512): 	at jdj.a(PG:4091)
E/HttpOperation( 3512): ,	at jdj.a(PG:1125)
E/HttpOperation( 3512): 	at jdm.a(PG:77)
E/HttpOperation( 3512): 	... 12 more
E/HttpOperation( 3512): Caused by: faj: BadAuthentication
,E/HttpOperation( 3512): 	at fal.a(PG:38)
E/HttpOperation( 3512): 	at jdj.a(PG:4089)
E/HttpOperation( 3512): 	... 14 more
,I/GLSUser ( 1470): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1470): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1470): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1470): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1470): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/HttpOperation( 3512): [getmobileexperiments] Unexpected exception,
,E/HttpOperation( 3512): java.io.IOException: Cannot obtain authentication token
,E/HttpOperation( 3512): 	at jdm.a(PG:82)
E/HttpOperation( 3512): 	at jcs.o(PG:406)
E/HttpOperation( 3512): ,	at jcn.a(PG:1379)
,E/HttpOperation( 3512): 	at jcs.i(PG:143)
E/HttpOperation( 3512): 	at hec.a(PG:42)
E/HttpOperation( 3512): ,	at hee.a(PG:102),
E/HttpOperation( 3512): 	at czr.a(PG:65)
E/HttpOperation( 3512): 	at kka.a(PG:108)
E/HttpOperation( 3512): 	at czp.a(PG:19176)
E/HttpOperation( 3512): 	at czp.a(PG:9081)
E/HttpOperation( 3512): 	at czq.run(PG:1686)
E/HttpOperation( 3512): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3512): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237),
E/HttpOperation( 3512): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3512): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3512): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3512): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3512): 	at jdj.a(PG:4091)
E/HttpOperation( 3512): 	at jdj.a(PG:1125)
E/HttpOperation( 3512): 	at jdm.a(PG:77)
E/HttpOperation( 3512): 	... 15 more
E/HttpOperation( 3512): Caused by: faj: BadAuthentication
E/HttpOperation( 3512): 	at fal.a(PG:38)
E/HttpOperation( 3512): 	at jdj.a(PG:4089)
E/HttpOperation( 3512): 	... 17 more
,E/ExperimentLoader( 3512): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3512): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3512): 	at jdm.a(PG:82)
E/ExperimentLoader( 3512): 	at jcs.o(PG:406)
E/ExperimentLoader( 3512): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3512): 	at jcs.i(PG:143)
E/ExperimentLoader( 3512): 	at hec.a(PG:42)
E/ExperimentLoader( 3512): 	at hee.a(PG:102)
E/ExperimentLoader( 3512): 	at czr.a(PG:65)
E/ExperimentLoader( 3512): 	at kka.a(PG:108)
E/ExperimentLoader( 3512): 	at czp.a(PG:19176)
E/ExperimentLoader( 3512): 	at czp.a(PG:9081)
E/ExperimentLoader( 3512): 	at czq.run(PG:1686)
E/ExperimentLoader( 3512): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3512): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3512): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3512): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3512): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3512): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3512): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3512): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3512): 	at jdm.a(PG:77)
E/ExperimentLoader( 3512): 	... 15 more
E/ExperimentLoader( 3512): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3512): 	at fal.a(PG:38)
E/ExperimentLoader( 3512): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3512): 	... 17 more
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 170445, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,I/jxcore-log( 3801): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3801): 
,D/HeadsetStateMachine( 2365): Disconnected process message: 10, size: 0
,I/art     (  821): Explicit concurrent mark sweep GC freed 47467(2MB) AllocSpace objects, 3(142KB) LOS objects, 32% free, 33MB/49MB, paused 1.346ms total 63.152ms
,V/GLSActivity( 1470): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1470): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1470): Vacuum at: now=1450361562467 tag=VacuumService
,V/GoogleAuthProtoRequest( 3862): [415] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1470): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1470): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1470): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1470): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1470): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3220): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3220): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3220): [1] 5.onFinished: Scheduling replication attempt 5.
,I/GLSUser ( 1470): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1470): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1470): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1470): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1470): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3862): [415] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3862): [415] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3862): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3862): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3862): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3862): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3862): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3862): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3862): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3862): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3862): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3862): 	at com.a.a.k.run(SourceFile:110)
,I/GoogleURLConnFactory( 1470): Using platform SSLCertificateSocketFactory
,W/Uploader( 1470): No account for auth token provided
,W/Uploader( 1470): No account for auth token provided
,I/GLSUser ( 1470): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1470): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1470): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1470): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1470): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1470): Explicit concurrent mark sweep GC freed 47012(2MB) AllocSpace objects, 8(716KB) LOS objects, 37% free, 26MB/42MB, paused 1.850ms total 57.246ms
,E/Uploader( 1470): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1470): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1470): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1470): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1470): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1470): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1470): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1470): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1470): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1470): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1470): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1470): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1470): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/GLSUser ( 1470): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1470): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1470): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1470): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1470): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1470): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1470): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1470): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1470): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1470): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1470): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1470): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1470): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1470): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1470): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1470): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1470): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1470): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1470): No account for auth token provided
,W/Uploader( 1470): No account for auth token provided
,I/GLSUser ( 1470): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1470): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1470): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1470): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1470): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/Uploader( 1470): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1470): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1470): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1470): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1470): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1470): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1470): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1470): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1470): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1470): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1470): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1470): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1470): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1470): No account for auth token provided
,W/Uploader( 1470): No account for auth token provided,
,W/Uploader( 1470): No account for auth token provided
,W/Uploader( 1470): No account for auth token provided
,W/Uploader( 1470): No account for auth token provided
,W/Uploader( 1470): No account for auth token provided
,W/Uploader( 1470):  no longer exists, so no auth token.
,I/jxcore-log( 3801): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3801): 
,I/GLSUser ( 1470): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1470): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1470): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1470): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1470): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1470): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1470): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1470): 	at com.google.android.gms.auth.p.e(SourceFile:1268),
E/Uploader( 1470): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1470): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1470): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1470): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1470): ,	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1470): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1470): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1470): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
,E/Uploader( 1470): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1470): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/jxcore-log( 3801): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3801): 
,D/HeadsetStateMachine( 2365): Disconnected process message: 10, size: 0
,I/BooksSync( 3707): Starting books sync for 61035162, extras: ade
,V/KeepSync( 3744): Connecting to GoogleApiClient
,I/BooksConfig( 3707): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1470): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1470): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1470): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1470): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1470): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1470): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1470): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1470): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1470): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1470): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,V/KeepSync( 3744): GoogleApiClient failed to connect with error code: 4,
,E/SQLiteLog( 3744): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3744): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3744): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1470): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1470): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1470): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1470): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1470): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3707): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3707): Soft error
E/BooksSync( 3707): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3707): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3707): Sync error
E/BooksSync( 3707): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3707): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3707): Finished books sync
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 171017, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1470): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1470): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1470): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1470): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1470): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3744): IOException
E/KeepSync( 3744): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3744): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3744): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3744): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3744): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3744): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3744): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3744): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3744): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3744): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3744): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3744): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3744): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3744): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3744): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3744): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3744): 	... 10 more
,W/KeepSync( 3744): Sync result 2
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 172701, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,I/jxcore-log( 3801): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3801): 
,V/GoogleAuthProtoRequest( 3862): [416] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1470): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1470): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1470): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1470): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1470): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3862): [416] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3862): [416] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3862): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3862): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3862): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3862): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3862): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3862): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3862): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3862): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3862): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3862): 	at com.a.a.k.run(SourceFile:110)
,V/GLSActivity( 1470): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  821): Explicit concurrent mark sweep GC freed 28324(1288KB) AllocSpace objects, 4(158KB) LOS objects, 31% free, 34MB/50MB, paused 2.517ms total 54.648ms
,I/GLSUser ( 1470): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1470): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1470): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1470): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1470): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3220): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3220): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3220): [1] 5.onFinished: Giving up after 6 failures.
,I/Keyboard.Facilitator.LanguageModelFlusher( 1215): run()
I/Keyboard.Facilitator( 1215): flushDynamicLanguageModels()
,I/ConfigService( 1470): onCreate
,I/jxcore-log( 3801): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3801): 
,I/ConfigService( 1470): onDestroy
,I/GLSUser ( 1470): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1470): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1470): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1470): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1470): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3512): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3512): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3512): 	at jdm.a(PG:82)
E/HttpOperation( 3512): 	at jcs.o(PG:406)
E/HttpOperation( 3512): 	at jcn.a(PG:1379)
E/HttpOperation( 3512): 	at jcs.i(PG:143)
E/HttpOperation( 3512): 	at blb.a(PG:3937)
E/HttpOperation( 3512): 	at czp.a(PG:18188)
E/HttpOperation( 3512): 	at czp.a(PG:9081)
E/HttpOperation( 3512): 	at czq.run(PG:1686)
E/HttpOperation( 3512): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3512): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3512): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3512): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3512): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3512): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3512): 	at jdj.a(PG:4091)
E/HttpOperation( 3512): 	at jdj.a(PG:1125)
E/HttpOperation( 3512): 	at jdm.a(PG:77)
E/HttpOperation( 3512): 	... 12 more
E/HttpOperation( 3512): Caused by: faj: BadAuthentication
E/HttpOperation( 3512): 	at fal.a(PG:38)
E/HttpOperation( 3512): 	at jdj.a(PG:4089)
E/HttpOperation( 3512): 	... 14 more
,I/GLSUser ( 1470): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1470): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1470): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1470): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1470): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3512): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3512): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3512): 	at jdm.a(PG:82)
E/HttpOperation( 3512): 	at jcs.o(PG:406)
E/HttpOperation( 3512): 	at jcn.a(PG:1379)
E/HttpOperation( 3512): 	at jcs.i(PG:143)
E/HttpOperation( 3512): 	at hec.a(PG:42)
E/HttpOperation( 3512): 	at hee.a(PG:102)
E/HttpOperation( 3512): 	at czr.a(PG:65)
E/HttpOperation( 3512): 	at kka.a(PG:108)
E/HttpOperation( 3512): 	at czp.a(PG:19176)
E/HttpOperation( 3512): 	at czp.a(PG:9081)
E/HttpOperation( 3512): 	at czq.run(PG:1686)
E/HttpOperation( 3512): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3512): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3512): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3512): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3512): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3512): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3512): 	at jdj.a(PG:4091)
E/HttpOperation( 3512): 	at jdj.a(PG:1125)
E/HttpOperation( 3512): 	at jdm.a(PG:77)
E/HttpOperation( 3512): 	... 15 more
E/HttpOperation( 3512): Caused by: faj: BadAuthentication
E/HttpOperation( 3512): 	at fal.a(PG:38)
E/HttpOperation( 3512): 	at jdj.a(PG:4089)
E/HttpOperation( 3512): 	... 17 more
E/ExperimentLoader( 3512): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3512): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3512): 	at jdm.a(PG:82)
E/ExperimentLoader( 3512): 	at jcs.o(PG:406)
E/ExperimentLoader( 3512): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3512): 	at jcs.i(PG:143)
E/ExperimentLoader( 3512): 	at hec.a(PG:42)
E/ExperimentLoader( 3512): 	at hee.a(PG:102)
E/ExperimentLoader( 3512): 	at czr.a(PG:65)
E/ExperimentLoader( 3512): 	at kka.a(PG:108)
E/ExperimentLoader( 3512): 	at czp.a(PG:19176)
E/ExperimentLoader( 3512): 	at czp.a(PG:9081)
E/ExperimentLoader( 3512): 	at czq.run(PG:1686)
E/ExperimentLoader( 3512): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3512): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3512): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3512): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3512): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3512): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3512): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3512): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3512): 	at jdm.a(PG:77)
E/ExperimentLoader( 3512): 	... 15 more
E/ExperimentLoader( 3512): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3512): 	at fal.a(PG:38)
E/ExperimentLoader( 3512): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3512): 	... 17 more
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 203814, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,I/jxcore-log( 3801): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3801): 
,D/HeadsetStateMachine( 2365): Disconnected process message: 10, size: 0
,I/jxcore-log( 3801): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 3801): 
,D/HeadsetStateMachine( 2365): Disconnected process message: 10, size: 0
,I/BooksSync( 3707): Starting books sync for 61035162, extras: ade
,V/KeepSync( 3744): Connecting to GoogleApiClient
,I/BooksConfig( 3707): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1470): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1470): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1470): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1470): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1470): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1470): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1470): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1470): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1470): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1470): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,V/KeepSync( 3744): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3744): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3744): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3744): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1470): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1470): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1470): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1470): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1470): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3707): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3707): Soft error
E/BooksSync( 3707): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3707): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3707): Sync error
E/BooksSync( 3707): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3707): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3707): Finished books sync
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 232568, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1470): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1470): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1470): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1470): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1470): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/KeepSync( 3744): IOException
E/KeepSync( 3744): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3744): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3744): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3744): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3744): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3744): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3744): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3744): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3744): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3744): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3744): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3744): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3744): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3744): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3744): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3744): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3744): 	... 10 more
W/KeepSync( 3744): Sync result 2
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 231112, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,I/jxcore-log( 3801): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3801): 
,I/ActivityManager(  821): Start proc 4117:com.google.android.youtube/u0a86 for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator
,W/ResourcesManager( 4117): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 4117): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 4117): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ProviderInstaller( 4117): Installed default security provider GmsCore_OpenSSL
,I/dex2oat ( 4145): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads-894415725.jar --oat-fd=24 --oat-location=/data/data/com.google.android.youtube/cache/ads-894415725.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,E/YouTube MDX( 4117): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,I/dex2oat ( 4145): dex2oat took 37.113ms (threads: 4) arena alloc=178KB java alloc=12KB native alloc=1221KB free=6MB
,W/InstanceID/Rpc( 4117): Found 10011
,I/jxcore-log( 3801): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3801): 
,I/ActivityManager(  821): Killing 3421:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,I/jxcore-log( 3801): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3801): 
,V/GoogleAuthProtoRequest( 3862): [417] a.<init>: mAccountName set to: thalitester@gmail.com
,I/art     ( 1470): Explicit concurrent mark sweep GC freed 57255(3MB) AllocSpace objects, 4(360KB) LOS objects, 36% free, 28MB/44MB, paused 1.496ms total 49.337ms
,I/GLSUser ( 1470): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1470): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1470): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1470): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1470): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3862): [417] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3862): [417] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3862): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3862): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3862): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3862): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3862): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3862): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3862): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3862): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3862): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3862): 	at com.a.a.k.run(SourceFile:110)
,I/jxcore-log( 3801): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3801): 
,D/HeadsetStateMachine( 2365): Disconnected process message: 10, size: 0
,I/jxcore-log( 3801): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): DBG, CoordinatorConnector connect called
I/jxcore-log( 3801): 
I/jxcore-log( 3801): Coordinator is now connected to the server!
I/jxcore-log( 3801): 
,I/chromium( 3801): [INFO:CONSOLE(63)] "logCallback connected to server", source: file:///android_asset/www/js/thali_main.js (63),
,D/HeadsetStateMachine( 2365): Disconnected process message: 10, size: 0
,I/GLSUser ( 1470): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1470): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1470): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1470): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1470): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3512): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3512): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3512): 	at jdm.a(PG:82)
E/HttpOperation( 3512): 	at jcs.o(PG:406)
E/HttpOperation( 3512): 	at jcn.a(PG:1379)
E/HttpOperation( 3512): 	at jcs.i(PG:143)
E/HttpOperation( 3512): 	at blb.a(PG:3937)
E/HttpOperation( 3512): 	at czp.a(PG:18188)
E/HttpOperation( 3512): 	at czp.a(PG:9081)
E/HttpOperation( 3512): 	at czq.run(PG:1686)
E/HttpOperation( 3512): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3512): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3512): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3512): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3512): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3512): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3512): 	at jdj.a(PG:4091)
E/HttpOperation( 3512): 	at jdj.a(PG:1125)
E/HttpOperation( 3512): 	at jdm.a(PG:77)
E/HttpOperation( 3512): 	... 12 more
E/HttpOperation( 3512): Caused by: faj: BadAuthentication
E/HttpOperation( 3512): 	at fal.a(PG:38)
E/HttpOperation( 3512): 	at jdj.a(PG:4089)
E/HttpOperation( 3512): 	... 14 more
,I/GLSUser ( 1470): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1470): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1470): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1470): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1470): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3512): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3512): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3512): 	at jdm.a(PG:82)
E/HttpOperation( 3512): 	at jcs.o(PG:406)
E/HttpOperation( 3512): 	at jcn.a(PG:1379)
E/HttpOperation( 3512): 	at jcs.i(PG:143)
E/HttpOperation( 3512): 	at hec.a(PG:42)
E/HttpOperation( 3512): 	at hee.a(PG:102)
E/HttpOperation( 3512): 	at czr.a(PG:65)
E/HttpOperation( 3512): 	at kka.a(PG:108)
E/HttpOperation( 3512): 	at czp.a(PG:19176)
E/HttpOperation( 3512): 	at czp.a(PG:9081)
E/HttpOperation( 3512): 	at czq.run(PG:1686)
E/HttpOperation( 3512): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3512): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3512): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3512): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3512): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3512): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3512): 	at jdj.a(PG:4091)
E/HttpOperation( 3512): 	at jdj.a(PG:1125)
E/HttpOperation( 3512): 	at jdm.a(PG:77)
E/HttpOperation( 3512): 	... 15 more
E/HttpOperation( 3512): Caused by: faj: BadAuthentication
E/HttpOperation( 3512): 	at fal.a(PG:38)
E/HttpOperation( 3512): 	at jdj.a(PG:4089)
E/HttpOperation( 3512): 	... 17 more
E/ExperimentLoader( 3512): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3512): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3512): 	at jdm.a(PG:82)
E/ExperimentLoader( 3512): 	at jcs.o(PG:406)
E/ExperimentLoader( 3512): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3512): 	at jcs.i(PG:143)
E/ExperimentLoader( 3512): 	at hec.a(PG:42)
E/ExperimentLoader( 3512): 	at hee.a(PG:102)
E/ExperimentLoader( 3512): 	at czr.a(PG:65)
E/ExperimentLoader( 3512): 	at kka.a(PG:108)
E/ExperimentLoader( 3512): 	at czp.a(PG:19176)
E/ExperimentLoader( 3512): 	at czp.a(PG:9081)
E/ExperimentLoader( 3512): 	at czq.run(PG:1686)
E/ExperimentLoader( 3512): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3512): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3512): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3512): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3512): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3512): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3512): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3512): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3512): 	at jdm.a(PG:77)
E/ExperimentLoader( 3512): 	... 15 more
E/ExperimentLoader( 3512): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3512): 	at fal.a(PG:38)
E/ExperimentLoader( 3512): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3512): 	... 17 more
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 296623, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager(  821): Start proc 4225:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider
,I/GAv4    ( 4225): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4225):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4225):   adb logcat -s GAv4
,W/GAv4    ( 4225): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4225): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4225): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  821): Killing 3659:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,I/art     (  821): Explicit concurrent mark sweep GC freed 29688(1281KB) AllocSpace objects, 10(725KB) LOS objects, 31% free, 34MB/50MB, paused 1.565ms total 84.114ms
,D/WifiService(  821): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@2ed6a704}
,E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-47
,D/WifiService(  821): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@2ed6a704}
,D/WifiService(  821): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@22e6ff22}
,E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::injectLocation(GpsExtLocation):857]: error! inject position failed
,I/BooksSync( 3707): Starting books sync for 61035162, extras: ade
,V/KeepSync( 3744): Connecting to GoogleApiClient
,I/BooksConfig( 3707): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1470): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1470): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1470): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1470): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1470): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1470): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1470): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1470): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1470): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1470): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,V/KeepSync( 3744): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3744): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3744): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3744): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1470): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1470): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1470): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1470): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1470): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3707): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3707): Soft error
E/BooksSync( 3707): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3707): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3707): Sync error
E/BooksSync( 3707): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3707): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3707): Finished books sync
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 324368, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1470): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1470): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1470): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1470): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1470): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3744): IOException
E/KeepSync( 3744): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3744): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3744): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3744): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3744): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3744): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3744): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3744): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3744): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3744): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3744): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3744): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3744): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3744): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3744): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3744): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3744): 	... 10 more
W/KeepSync( 3744): Sync result 2
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 321334, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,D/WifiService(  821): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@22e6ff22},
,V/GLSActivity( 1470): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1470): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1470): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1470): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1470): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1470): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/GLSActivity( 1470): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1470): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1470): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1470): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1470): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1470): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1470): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 3220): Failed to get auth token: User intervention required. Notification has been pushed.,
E/PlayEventLogger( 3220): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3220): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 3220): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3220): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867),
E/PlayEventLogger( 3220): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3220): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 3220): Ignoring header User-Agent because its value was null.
,D/HeadsetStateMachine( 2365): Disconnected process message: 10, size: 0
,V/GoogleAuthProtoRequest( 3862): [418] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1470): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1470): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1470): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1470): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1470): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3862): [418] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3862): [418] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3862): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3862): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3862): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3862): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3862): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3862): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3862): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3862): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3862): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3862): 	at com.a.a.k.run(SourceFile:110)
,D/HeadsetStateMachine( 2365): Disconnected process message: 10, size: 0
,I/jxcore-log( 3801): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): DBG, CoordinatorConnector command called
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":20000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":14,"addressList":[{"address":"7C:F9:0E:37:96:AB","tryCount":0},{"address":"58:3F:54:73:64:C0","tryCount":0},{"address":"F8:95:C7:87:85:54","tryCount":0},{"address":"7C:F9:0E:34:8A:A0","tryCount":0},{"address":"34:FC:EF:11:AE:67","tryCount":0},{"address":"F8:95:C7:87:3C:51","tryCount":0},{"address":"08:EC:A9:50:75:41","tryCount":0},{"address":"90:E7:C4:F6:69:77","tryCount":0},{"address":"B0:C5:59:3F:75:69","tryCount":0},{"address":"7C:F9:0E:51:18:22","tryCount":0},{"address":"08:EC:A9:50:76:27","tryCount":0},{"address":"E0:DB:10:1F:C9:5E","tryCount":0},{"address":"44:80:EB:7B:5A:05","tryCount":0},{"address":"E0:DB:10:14:E2:C0","tryCount":0}]}
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): Start now : testSendData.js
I/jxcore-log( 3801): 
I/jxcore-log( 3801): testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 14
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): check server
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): serverPort is 51447
I/jxcore-log( 3801): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): setDiscoveryMode: Mode set to BLE_AND_WIFI,
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3801): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: motorola-Nexus 6_PT6358
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3801): bind: Binding a new listener
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3801): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3801): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT6358","ra":"F8:CF:C5:D9:E5:61"},
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3801): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3801): startListeningForIncomingConnections
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3801): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3801): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3801): setState: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3801): start: OK
I/io.jxcore.node.ConnectionHelper( 3801): start: Using peer discovery mode: BLE_AND_WIFI
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3801): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: motorola-Nexus 6_PT6358
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3801): bind: Binding a new listener
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0,
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3801): setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3801): createAdvertiseData: From: motorola-Nexus 6_PT6358 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3801): F8:CF:C5:D9:E5:61
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3801): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3801): setScanSettings: Mode: 0, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService( 2365): registerClient() - UUID=133c7ded-1bbf-41f9-893c-0e58056a797a
,D/BtGatt.GattService( 2365): onClientRegistered() - UUID=133c7ded-1bbf-41f9-893c-0e58056a797a, clientIf=5
,D/BluetoothLeAdvertiser( 3801): onClientRegistered() - status=0 clientIf=5
,D/BtGatt.AdvertiseManager( 2365): message : 0
,D/BtGatt.AdvertiseManager( 2365): starting multi advertising
,D/BtGatt.GattService( 2365): onAdvertiseInstanceEnabled() - clientIf=5, status=0
,D/BtGatt.GattService( 2365): onAdvertiseDataSet() - clientIf=5, status=0
,D/BtGatt.GattService( 2365): registerClient() - UUID=b12b77bd-e52d-490a-88d6-86731e09f259
,D/BtGatt.GattService( 2365): onClientRegistered() - UUID=b12b77bd-e52d-490a-88d6-86731e09f259, clientIf=6
D/BluetoothLeScanner( 3801): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.GattService( 2365): start scan with filters
,D/BtGatt.ScanManager( 2365): handling starting scan
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): startBlePeerDiscovery: OK
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/BluetoothAdapterService( 2365): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37791d5e
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3801): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT6358","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3801): bind: Binding a new listener
,D/BtGatt.GattService( 2365): onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,D/BtGatt.ScanManager( 2365): callback done for clientIf - 6 status - 0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3801): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT6358","ra":"F8:CF:C5:D9:E5:61"}
D/BtGatt.GattService( 2365): onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
D/BtGatt.ScanManager( 2365): callback done for clientIf - 6 status - 0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3801): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT6358","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
D/BtGatt.ScanManager( 2365): configureRegularScanParams() - queue=1
D/BtGatt.ScanManager( 2365): configureRegularScanParams() - ScanSetting Scan mode=0 mLastConfiguredScanSetting=-2147483648
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3801): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3801): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 3801): start: OK
I/jxcore-log( 3801): StartBroadcasting started ok
I/jxcore-log( 3801): 
I/jxcore-log( 3801): do fake peer & start
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): Connect to fake peer: E0:DB:10:1F:C9:5E
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:16:43.773Z SendDataConnector.js: Start called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3801): 
I/jxcore-log( 3801): 2015-12-17T14:16:43.773Z SendDataConnector.js: doConnect called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:16:43.773Z SendDataConnector.js: do connect now
I/jxcore-log( 3801): 
I/io.jxcore.node.ConnectionHelper( 3801): connect: Trying to connect to peer with ID E0:DB:10:1F:C9:5E
,D/io.jxcore.node.ConnectionHelper( 3801): hasConnection: No connection with peer with ID E0:DB:10:1F:C9:5E
W/io.jxcore.node.ConnectionHelper( 3801): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3801): connect: [E0:DB:10:1F:C9:5E E0:DB:10:1F:C9:5E]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3801): connect: Trying to start connecting to null in address E0:DB:10:1F:C9:5E
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3801): setInsecureRfcommSocketPort: Using port -1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3801): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3801): onConnecting: null E0:DB:10:1F:C9:5E
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3801): connect: Started connecting to null in address E0:DB:10:1F:C9:5E
I/io.jxcore.node.ConnectionHelper( 3801): connect: Connection process successfully started (peer ID: E0:DB:10:1F:C9:5E)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3801): Trying to connect to peer with address E0:DB:10:1F:C9:5E (thread ID: 423)
W/BluetoothAdapter( 3801): getBluetoothService() called with no BluetoothManagerCallback
I/jxcore-log( 3801): 2015-12-17T14:16:43.788Z SendDataTCPServer.js: TCP/IP server is bound to port: 51447
I/jxcore-log( 3801): 
I/chromium( 3801): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
I/io.jxcore.node.ConnectionHelper( 3801): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3801): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3801): onIsAdvertiserStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: motorola-Nexus 6_PT6358
,D/BTIF_SOCK( 2365): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): startBlePeerDiscovery: Already running
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): startBlePeerDiscovery: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): startWifiPeerDiscovery: Wi-Fi Direct OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): start: OK
I/io.jxcore.node.ConnectionHelper( 3801): onDiscoveryManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3801): Local service added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3801): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3801): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3801): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3801): onScanResult: Callback type: 1, Scan result: ScanResult{mDevice=F0:8B:B2:7E:EA:D2, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=null, mManufacturerSpecificData={}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-91, mTimestampNanos=431008599938}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3801): onScanResult: Callback type: 1, Scan result: ScanResult{mDevice=C8:D9:53:A0:EC:4E, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 8, -20, -87, 80, 118, 39]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-81, mTimestampNanos=431272627438}
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): onPeerDiscovered: [8:EC:A9:50:76:27 <no peer name>]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): modifyListOfDiscoveredPeers: [8:EC:A9:50:76:27 <no peer name>], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): modifyListOfDiscoveredPeers: Adding new peer: [8:EC:A9:50:76:27 <no peer name>]
I/io.jxcore.node.ConnectionHelper( 3801): onPeerDiscovered: [8:EC:A9:50:76:27 <no peer name>], Bluetooth address: 8:EC:A9:50:76:27, device name: , device address: 
D/io.jxcore.node.ConnectionHelper( 3801): notifyPeerAvailability: Peer [8:EC:A9:50:76:27 <no peer name>] is available
,W/bt-btif ( 2365): info:x10
,D/        ( 2365): remote version info [90:e7:c4:f6:69:77]: 7, 1d, 7d3
E/BluetoothRemoteDevices( 2365): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 2365): info:x10
,D/        ( 2365): remote version info [e0:db:10:1f:c9:5e]: 7, f, 6109
E/BluetoothRemoteDevices( 2365): aclStateChangeCallback: Device is NULL
,D/btif_config( 2365): btif_get_device_type: Device [90:e7:c4:f6:69:77] type 1,
,I/BluetoothBondStateMachine( 2365): bondStateChangeCallback: Status: 0 Address: 90:E7:C4:F6:69:77 newState: 1
,E/bt-btif ( 2365): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2365): Bond State Change Intent:90:E7:C4:F6:69:77 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2365): Entering PendingCommandState State
,W/bt-btif ( 2365): info:x10,
D/        ( 2365): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
E/BluetoothRemoteDevices( 2365): aclStateChangeCallback: Device is NULL
,I/ActivityManager(  821): Start proc 4281:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.BluetoothPairingRequest
,I/art     (  368): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 348us total 16.617ms
,I/art     (  368): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 357us total 15.574ms
,I/art     (  368): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 239us total 15.592ms
,I/BluetoothBondStateMachine( 2365): bondStateChangeCallback: Status: 0 Address: 90:E7:C4:F6:69:77 newState: 0
D/BluetoothAdapterProperties( 2365): Failed to remove device: 90:E7:C4:F6:69:77
,I/BluetoothBondStateMachine( 2365): Bond State Change Intent:90:E7:C4:F6:69:77 OldState: 11 NewState: 10
,D/BluetoothManagerService(  821): Message: 20
D/BluetoothManagerService(  821): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@20adb542:true
,I/BluetoothBondStateMachine( 2365): StableState(): Entering Off State
,I/ActivityManager(  821): Killing 3563:com.android.defcontainer/u0a7 (adj 15): empty #17
,E/bt-btm  ( 2365): tBTM_SEC_DEV:0xa2f41eb4 rs_disc_pending=0
,W/bt-btif ( 2365): bta_dm_check_av:0
W/bt-btif ( 2365): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 1213): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3801): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
,D/WifiP2pManager( 3801): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3801): Service request added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3801): onScanResult: Callback type: 1, Scan result: ScanResult{mDevice=88:C6:26:19:97:DC, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=[72daa6c3-29c2-6283-0c4a-2818e4d37e75], mManufacturerSpecificData={50824=[38, 25, -105, -36]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=��], mRssi=-77, mTimestampNanos=433827971916}
,W/bt-btif ( 2365): new conn_srvc id:26, app_id:255
W/bt-btif ( 2365): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2365): bta_dm_pm_ssr:2, lat:1200
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3801): Incoming connection accepted
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3801): Incoming connection initialized (thread ID: 424)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3801): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3801): Entering thread (ID: 424)
,E/bt-btm  ( 2365): tBTM_SEC_DEV:0xa2f41eb4 rs_disc_pending=1
,W/bt-btif ( 2365): bta_dm_check_av:0
W/bt-btif ( 2365): btif_dm_cback : unhandled event (14)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3801): onBytesRead: Read 81 bytes successfully (thread ID: 424)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3801): Got valid identity from [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT7778]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3801): onBytesWritten: 82 bytes successfully written (thread ID: 424)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3801): removeThreadFromList: Removing thread with ID 424
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3801): Handshake thread disposed (thread ID: 424)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3801): onIncomingConnectionConnected: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT7778]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3801): Exiting thread (ID: 424)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3801): onConnected: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT7778]
I/io.jxcore.node.ConnectionHelper( 3801): onConnected: Incoming connection to peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT7778]
D/io.jxcore.node.ConnectionHelper( 3801): hasConnection: No connection with peer with ID 90:E7:C4:F6:69:77
D/io.jxcore.node.ConnectionHelper( 3801): notifyPeerAvailability: Peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT7778] is available
,I/io.jxcore.node.ConnectionHelper( 3801): onConnected: Incoming socket thread, for peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT7778], created successfully
,D/io.jxcore.node.ConnectionHelper( 3801): onConnected: The total number of connections is now 1
D/io.jxcore.node.IncomingSocketThread( 3801): Entering thread (ID: 425)
,I/io.jxcore.node.IncomingSocketThread( 3801): Local host address: localhost/127.0.0.1, port: 51447
,D/io.jxcore.node.IncomingSocketThread( 3801): Setting local streams and starting stream copying threads...
,I/io.jxcore.node.StreamCopyingThread( 3801): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3801): setBufferSize: Setting buffer size to 8192 bytes
,D/io.jxcore.node.StreamCopyingThread( 3801): Entering thread (ID: 426, name: Sender)
I/io.jxcore.node.IncomingSocketThread( 3801): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3801): Exiting thread (ID: 425)
I/jxcore-log( 3801): 2015-12-17T14:16:47.273Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3801): 
,D/io.jxcore.node.StreamCopyingThread( 3801): Entering thread (ID: 427, name: Receiver),
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3801): onScanResult: Callback type: 1, Scan result: ScanResult{mDevice=E0:B7:20:28:C5:81, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -32, -37, 16, 20, -30, -64]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-83, mTimestampNanos=434388315718},
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): onPeerDiscovered: [E0:DB:10:14:E2:C0 <no peer name>]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 <no peer name>], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): modifyListOfDiscoveredPeers: Adding new peer: [E0:DB:10:14:E2:C0 <no peer name>]
,I/io.jxcore.node.ConnectionHelper( 3801): onPeerDiscovered: [E0:DB:10:14:E2:C0 <no peer name>], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 
D/io.jxcore.node.ConnectionHelper( 3801): notifyPeerAvailability: Peer [E0:DB:10:14:E2:C0 <no peer name>] is available
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3801): onScanResult: Callback type: 1, Scan result: ScanResult{mDevice=FC:F3:1C:68:15:41, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 124, -7, 14, 52, -118, -96]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-83, mTimestampNanos=434520400353}
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): onPeerDiscovered: [7C:F9:E:34:8A:A0 <no peer name>]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): modifyListOfDiscoveredPeers: [7C:F9:E:34:8A:A0 <no peer name>], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:E:34:8A:A0 <no peer name>]
I/io.jxcore.node.ConnectionHelper( 3801): onPeerDiscovered: [7C:F9:E:34:8A:A0 <no peer name>], Bluetooth address: 7C:F9:E:34:8A:A0, device name: , device address: 
D/io.jxcore.node.ConnectionHelper( 3801): notifyPeerAvailability: Peer [7C:F9:E:34:8A:A0 <no peer name>] is available
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3801): Service discovery started successfully
,E/bt-btm  ( 2365): tBTM_SEC_DEV:0xa2f41eb4 rs_disc_pending=0
,W/bt-btif ( 2365): bta_dm_check_av:0
W/bt-btif ( 2365): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 2365): process_service_search_attr_rsp
,I/jxcore-log( 3801): 2015-12-17T14:16:48.141Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:16:48.170Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:16:48.180Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:16:48.188Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:16:48.214Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:16:48.298Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:16:48.324Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:16:48.360Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:16:48.439Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:16:48.460Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:16:48.508Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:16:48.584Z SendDataTCPServer.js: TCP/IP server has received 25740 bytes of data
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:16:48.678Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:16:48.684Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:16:48.725Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:16:48.751Z SendDataTCPServer.js: TCP/IP server has received 33660 bytes of data
I/jxcore-log( 3801): 
D/btif_config( 2365): btif_get_device_type: Device [08:ec:a9:50:76:27] type 1
,I/BluetoothBondStateMachine( 2365): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:76:27 newState: 1
,E/bt-btif ( 2365): check_cod: remote_cod = 0x5a020c
I/BluetoothBondStateMachine( 2365): Bond State Change Intent:08:EC:A9:50:76:27 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2365): Entering PendingCommandState State
,I/jxcore-log( 3801): 2015-12-17T14:16:48.799Z SendDataTCPServer.js: TCP/IP server has received 35640 bytes of data
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:16:48.821Z SendDataTCPServer.js: TCP/IP server has received 37620 bytes of data
I/jxcore-log( 3801): 
,I/BluetoothBondStateMachine( 2365): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:76:27 newState: 0
,D/BluetoothAdapterProperties( 2365): Failed to remove device: 08:EC:A9:50:76:27
,I/BluetoothBondStateMachine( 2365): Bond State Change Intent:08:EC:A9:50:76:27 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2365): StableState(): Entering Off State
,I/jxcore-log( 3801): 2015-12-17T14:16:48.921Z SendDataTCPServer.js: TCP/IP server has received 39600 bytes of data
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:16:49.056Z SendDataTCPServer.js: TCP/IP server has received 41580 bytes of data
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:16:49.163Z SendDataTCPServer.js: TCP/IP server has received 43560 bytes of data
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:16:49.200Z SendDataTCPServer.js: TCP/IP server has received 45540 bytes of data
I/jxcore-log( 3801): 
,W/bt-btif ( 2365): new conn_srvc id:26, app_id:255,
W/bt-btif ( 2365): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2365): bta_dm_pm_ssr:2, lat:1200,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3801): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3801): Incoming connection initialized (thread ID: 428)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3801): Waiting for incoming connections...
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3801): Entering thread (ID: 428)
,I/jxcore-log( 3801): 2015-12-17T14:16:49.295Z SendDataTCPServer.js: TCP/IP server has received 47520 bytes of data
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:16:49.388Z SendDataTCPServer.js: TCP/IP server has received 49500 bytes of data,
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:16:49.397Z SendDataTCPServer.js: TCP/IP server has received 51480 bytes of data
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:16:49.480Z SendDataTCPServer.js: TCP/IP server has received 53460 bytes of data
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:16:49.541Z SendDataTCPServer.js: TCP/IP server has received 55440 bytes of data
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:16:49.567Z SendDataTCPServer.js: TCP/IP server has received 57420 bytes of data
I/jxcore-log( 3801): 
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3801): onBytesRead: Read 83 bytes successfully (thread ID: 428)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3801): Got valid identity from [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7181]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3801): onBytesWritten: 82 bytes successfully written (thread ID: 428)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3801): removeThreadFromList: Removing thread with ID 428
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3801): Handshake thread disposed (thread ID: 428)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3801): onIncomingConnectionConnected: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7181]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3801): Exiting thread (ID: 428)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3801): onConnected: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7181]
I/io.jxcore.node.ConnectionHelper( 3801): onConnected: Incoming connection to peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7181]
,D/io.jxcore.node.ConnectionHelper( 3801): hasConnection: No connection with peer with ID 08:EC:A9:50:76:27
D/io.jxcore.node.ConnectionHelper( 3801): notifyPeerAvailability: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7181] is available
,I/io.jxcore.node.ConnectionHelper( 3801): onConnected: Incoming socket thread, for peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7181], created successfully
,D/io.jxcore.node.ConnectionHelper( 3801): onConnected: The total number of connections is now 2
I/jxcore-log( 3801): 2015-12-17T14:16:49.629Z SendDataTCPServer.js: TCP/IP server has received 59400 bytes of data
I/jxcore-log( 3801): 
,D/io.jxcore.node.IncomingSocketThread( 3801): Entering thread (ID: 429)
,I/jxcore-log( 3801): 2015-12-17T14:16:49.635Z SendDataTCPServer.js: TCP/IP server has received 61380 bytes of data
I/jxcore-log( 3801): 
,I/io.jxcore.node.IncomingSocketThread( 3801): Local host address: localhost/127.0.0.1, port: 51447,
D/io.jxcore.node.IncomingSocketThread( 3801): Setting local streams and starting stream copying threads...
,I/io.jxcore.node.StreamCopyingThread( 3801): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3801): setBufferSize: Setting buffer size to 8192 bytes
,I/jxcore-log( 3801): 2015-12-17T14:16:49.642Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3801): 
,D/io.jxcore.node.StreamCopyingThread( 3801): Entering thread (ID: 430, name: Sender)
I/io.jxcore.node.IncomingSocketThread( 3801): startStreamCopyingThreads: OK
,D/io.jxcore.node.IncomingSocketThread( 3801): Exiting thread (ID: 429)
,D/io.jxcore.node.StreamCopyingThread( 3801): Entering thread (ID: 431, name: Receiver)
,I/jxcore-log( 3801): 2015-12-17T14:16:49.739Z SendDataTCPServer.js: TCP/IP server has received 63360 bytes of data
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:16:49.879Z SendDataTCPServer.js: TCP/IP server has received 65340 bytes of data
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:16:49.916Z SendDataTCPServer.js: TCP/IP server has received 67320 bytes of data
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:16:49.980Z SendDataTCPServer.js: TCP/IP server has received 69300 bytes of data
I/jxcore-log( 3801): 
,D/btif_config( 2365): btif_get_device_type: Device [e0:db:10:1f:c9:5e] type 1
,I/BluetoothBondStateMachine( 2365): bondStateChangeCallback: Status: 0 Address: E0:DB:10:1F:C9:5E newState: 1
E/bt-btif ( 2365): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2365): Bond State Change Intent:E0:DB:10:1F:C9:5E OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2365): Entering PendingCommandState State
,I/jxcore-log( 3801): 2015-12-17T14:16:50.051Z SendDataTCPServer.js: TCP/IP server has received 71280 bytes of data,
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:16:50.097Z SendDataTCPServer.js: TCP/IP server has received 73260 bytes of data,
I/jxcore-log( 3801): 
,I/BluetoothBondStateMachine( 2365): bondStateChangeCallback: Status: 0 Address: E0:DB:10:1F:C9:5E newState: 0,
D/BluetoothAdapterProperties( 2365): Failed to remove device: E0:DB:10:1F:C9:5E
,I/jxcore-log( 3801): 2015-12-17T14:16:50.222Z SendDataTCPServer.js: TCP/IP server has received 75240 bytes of data,
I/jxcore-log( 3801): 
I/BluetoothBondStateMachine( 2365): Bond State Change Intent:E0:DB:10:1F:C9:5E OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2365): StableState(): Entering Off State
,I/jxcore-log( 3801): 2015-12-17T14:16:50.279Z SendDataTCPServer.js: TCP/IP server has received 77220 bytes of data
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:16:50.310Z SendDataTCPServer.js: TCP/IP server has received 79200 bytes of data
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:16:50.317Z SendDataTCPServer.js: TCP/IP server has received 81180 bytes of data
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:16:50.327Z SendDataTCPServer.js: TCP/IP server has received 83160 bytes of data
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:16:50.359Z SendDataTCPServer.js: TCP/IP server has received 85140 bytes of data
I/jxcore-log( 3801): 
,E/bt-btm  ( 2365): tBTM_SEC_DEV:0xa2f41eb4 rs_disc_pending=1
,W/bt-btif ( 2365): bta_dm_check_av:0
W/bt-btif ( 2365): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3801): 2015-12-17T14:16:50.527Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:16:50.563Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
,I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:16:50.572Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data,
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:16:50.638Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data,
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:16:50.646Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data,
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:16:50.702Z SendDataTCPServer.js: TCP/IP server has received 87120 bytes of data,
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:16:50.721Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:16:50.758Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:16:50.789Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:16:50.805Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:16:50.817Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:16:50.849Z SendDataTCPServer.js: TCP/IP server has received 89100 bytes of data
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:16:50.856Z SendDataTCPServer.js: TCP/IP server has received 91080 bytes of data
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:16:50.859Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:16:50.867Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:16:50.899Z SendDataTCPServer.js: TCP/IP server has received 25740 bytes of data
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:16:50.904Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:16:50.910Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:16:50.916Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:16:50.922Z SendDataTCPServer.js: TCP/IP server has received 33660 bytes of data
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:16:50.960Z SendDataTCPServer.js: TCP/IP server has received 35640 bytes of data
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:16:50.974Z SendDataTCPServer.js: TCP/IP server has received 93060 bytes of data
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:16:51.008Z SendDataTCPServer.js: TCP/IP server has received 37620 bytes of data
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:16:51.024Z SendDataTCPServer.js: TCP/IP server has received 95040 bytes of data
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:16:51.033Z SendDataTCPServer.js: TCP/IP server has received 97020 bytes of data
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:16:51.038Z SendDataTCPServer.js: TCP/IP server has received 39600 bytes of data
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:16:51.045Z SendDataTCPServer.js: TCP/IP server has received 41580 bytes of data
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:16:51.050Z SendDataTCPServer.js: TCP/IP server has received 43560 bytes of data,
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:16:51.090Z SendDataTCPServer.js: TCP/IP server has received 45540 bytes of data
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:16:51.098Z SendDataTCPServer.js: TCP/IP server has received 99000 bytes of data
I/jxcore-log( 3801): ,
,I/jxcore-log( 3801): 2015-12-17T14:16:51.108Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:16:51.149Z SendDataTCPServer.js: TCP/IP server has received 47520 bytes of data
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:16:51.214Z SendDataTCPServer.js: TCP/IP server has received 49500 bytes of data
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:16:51.263Z SendDataTCPServer.js: TCP/IP server has received 51480 bytes of data
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:16:51.375Z SendDataTCPServer.js: TCP/IP server has received 53460 bytes of data
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:16:51.409Z SendDataTCPServer.js: TCP/IP server has received 55440 bytes of data,
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:16:51.478Z SendDataTCPServer.js: TCP/IP server has received 57420 bytes of data
I/jxcore-log( 3801): 
,E/bt-btm  ( 2365): tBTM_SEC_DEV:0xa2f4207c rs_disc_pending=0
,W/bt-btif ( 2365): bta_dm_check_av:0
W/bt-btif ( 2365): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3801): 2015-12-17T14:16:51.561Z SendDataTCPServer.js: TCP/IP server has received 59400 bytes of data
I/jxcore-log( 3801): 
,W/bt-btif ( 2365): invalid rfc slot id: 4
W/io.jxcore.node.StreamCopyingThread( 3801): Either failed to read from the output stream or write to the input stream (thread ID: 427, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 3801): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3801): onDisconnected: Incoming connection, peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT7778] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3801): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 425
D/io.jxcore.node.IncomingSocketThread( 3801): close: Stopping receiving thread...
,I/io.jxcore.node.StreamCopyingThread( 3801): doStop: Thread ID: 427
D/io.jxcore.node.IncomingSocketThread( 3801): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3801): doStop: Thread ID: 426
,D/io.jxcore.node.IncomingSocketThread( 3801): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 3801): closeLocalSocketAndStreams: Closing the local input stream...
D/io.jxcore.node.IncomingSocketThread( 3801): closeLocalSocketAndStreams: Closing the local output stream...
,W/io.jxcore.node.StreamCopyingThread( 3801): Either failed to read from the output stream or write to the input stream (thread ID: 426, thread name: Sender): Socket closed
D/io.jxcore.node.IncomingSocketThread( 3801): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 3801): closeBluetoothSocketAndStreams
E/io.jxcore.node.IncomingSocketThread( 3801): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3801): onDisconnected: Incoming connection, peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT7778] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.ConnectionHelper( 3801): closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3801): Exiting thread (ID: 427, name: Receiver)
D/io.jxcore.node.ConnectionHelper( 3801): closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3801): Exiting thread (ID: 426, name: Sender)
,I/jxcore-log( 3801): 2015-12-17T14:16:51.599Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3801): 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3801): onScanResult: Callback type: 1, Scan result: ScanResult{mDevice=88:C6:26:19:97:DC, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=[72daa6c3-29c2-6283-0c4a-2818e4d37e75], mManufacturerSpecificData={50824=[38, 25, -105, -36]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=��], mRssi=-87, mTimestampNanos=438647968060}
,W/bt-rfcomm( 2365): rfc_find_lcid_mcb LCID reused LCID:0x42 current:0x0
,W/bt-rfcomm( 2365): RFCOMM_DisconnectInd LCID:0x42
,I/jxcore-log( 3801): 2015-12-17T14:16:51.958Z SendDataTCPServer.js: TCP/IP server has received 61380 bytes of data
I/jxcore-log( 3801): ,
,E/bt-btm  ( 2365): tBTM_SEC_DEV:0xa2f41eb4 rs_disc_pending=0
,W/bt-btif ( 2365): bta_dm_check_av:0
W/bt-btif ( 2365): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3801): onScanResult: Callback type: 1, Scan result: ScanResult{mDevice=77:BD:1F:8C:AD:03, mScanRecord=ScanRecord [mAdvertiseFlags=26, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -107, -57, -121, 60, 81]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-89, mTimestampNanos=439127791289}
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): onPeerDiscovered: [F8:95:C7:87:3C:51 <no peer name>]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 <no peer name>], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 <no peer name>]
I/io.jxcore.node.ConnectionHelper( 3801): onPeerDiscovered: [F8:95:C7:87:3C:51 <no peer name>], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
,D/io.jxcore.node.ConnectionHelper( 3801): notifyPeerAvailability: Peer [F8:95:C7:87:3C:51 <no peer name>] is available
,I/jxcore-log( 3801): 2015-12-17T14:16:52.141Z SendDataTCPServer.js: TCP/IP server has received 63360 bytes of data
I/jxcore-log( 3801): 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3801): onScanResult: Callback type: 1, Scan result: ScanResult{mDevice=88:C6:26:19:97:DC, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=[72daa6c3-29c2-6283-0c4a-2818e4d37e75], mManufacturerSpecificData={50824=[38, 25, -105, -36]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=��], mRssi=-86, mTimestampNanos=439263021914}
,E/bt-btm  ( 2365): tBTM_SEC_DEV:0xa2f4207c rs_disc_pending=1,
W/bt-btif ( 2365): bta_dm_check_av:0
W/bt-btif ( 2365): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3801): onScanResult: Callback type: 1, Scan result: ScanResult{mDevice=E0:B7:20:28:C5:81, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -32, -37, 16, 20, -30, -64]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-79, mTimestampNanos=439315102070}
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): onPeerDiscovered: [E0:DB:10:14:E2:C0 <no peer name>]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 <no peer name>], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 <no peer name>]
I/io.jxcore.node.ConnectionHelper( 3801): onPeerDiscovered: [E0:DB:10:14:E2:C0 <no peer name>], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 
W/io.jxcore.node.ConnectionHelper( 3801): modifyListOfDiscoveredPeers: Peer [E0:DB:10:14:E2:C0 <no peer name>] already in the list, will not add again
,I/jxcore-log( 3801): 2015-12-17T14:16:52.437Z SendDataTCPServer.js: TCP/IP server has received 65340 bytes of data
I/jxcore-log( 3801): 
,W/bt-btif ( 2365): new conn_srvc id:26, app_id:1
W/bt-btif ( 2365): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2365): bta_dm_pm_ssr:2, lat:1200
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3801): onSocketConnected: [E0:DB:10:1F:C9:5E E0:DB:10:1F:C9:5E]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3801): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 423)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3801): onBytesWritten: 82 bytes successfully written (thread ID: 432)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3801): Outgoing connection initialized (*handshake* thread ID: 432)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3801): Exiting thread (thread ID: 423)
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3801): Entering thread (ID: 432)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3801): onScanResult: Callback type: 1, Scan result: ScanResult{mDevice=88:C6:26:19:97:DC, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=[72daa6c3-29c2-6283-0c4a-2818e4d37e75], mManufacturerSpecificData={50824=[38, 25, -105, -36]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=��], mRssi=-86, mTimestampNanos=439634303424}
,I/jxcore-log( 3801): 2015-12-17T14:16:52.598Z SendDataTCPServer.js: TCP/IP server has received 67320 bytes of data
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:16:52.755Z SendDataTCPServer.js: TCP/IP server has received 69300 bytes of data,
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:16:52.825Z SendDataTCPServer.js: TCP/IP server has received 71280 bytes of data
I/jxcore-log( 3801): 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3801): onScanResult: Callback type: 1, Scan result: ScanResult{mDevice=88:C6:26:19:97:DC, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=[72daa6c3-29c2-6283-0c4a-2818e4d37e75], mManufacturerSpecificData={50824=[38, 25, -105, -36]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=��], mRssi=-88, mTimestampNanos=439884421288}
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3801): onBytesRead: Read 82 bytes successfully (thread ID: 432)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3801): Handshake succeeded with [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT2526]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3801): onHandshakeSucceeded: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT2526]
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3801): Exiting thread (ID: 432)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3801): onConnected: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT2526]
I/io.jxcore.node.ConnectionHelper( 3801): onConnected: Outgoing connection to peer [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT2526]
,D/io.jxcore.node.ConnectionHelper( 3801): hasConnection: No connection with peer with ID E0:DB:10:1F:C9:5E
D/io.jxcore.node.ConnectionHelper( 3801): notifyPeerAvailability: Peer [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT2526] is available
,I/io.jxcore.node.ConnectionHelper( 3801): onConnected: Outgoing socket thread, for peer [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT2526], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3801): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 3801): onConnected: The total number of connections is now 2
D/io.jxcore.node.OutgoingSocketThread( 3801): Entering thread (ID: 433)
,D/io.jxcore.node.OutgoingSocketThread( 3801): Server socket local port: 41422
,I/io.jxcore.node.OutgoingSocketThread( 3801): Now accepting connections...
,I/jxcore-log( 3801): 2015-12-17T14:16:53.012Z SendDataTCPServer.js: TCP/IP server has received 73260 bytes of data
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:16:53.143Z SendDataTCPServer.js: TCP/IP server has received 75240 bytes of data
I/jxcore-log( 3801): ,
,I/jxcore-log( 3801): 2015-12-17T14:16:53.152Z SendDataTCPServer.js: TCP/IP server has received 77220 bytes of data,
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:16:53.191Z SendDataTCPServer.js: TCP/IP server has received 79200 bytes of data,
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:16:53.200Z SendDataTCPServer.js: TCP/IP server has received 81180 bytes of data
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:16:53.206Z SendDataTCPServer.js: TCP/IP server has received 83160 bytes of data
I/jxcore-log( 3801): 
,I/io.jxcore.node.ConnectionHelper( 3801): onListeningForIncomingConnections: Outgoing connection is using port 41422 (peer ID: E0:DB:10:1F:C9:5E)
,I/jxcore-log( 3801): 2015-12-17T14:16:53.249Z SendDataConnector.js: CLIENT connected to 41422, error: null
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:16:53.250Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3801): 
,I/io.jxcore.node.OutgoingSocketThread( 3801): Incoming data from address: /127.0.0.1, port: 41422
,D/io.jxcore.node.OutgoingSocketThread( 3801): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3801): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3801): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.OutgoingSocketThread( 3801): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3801): Exiting thread (ID: 433)
,D/io.jxcore.node.StreamCopyingThread( 3801): Entering thread (ID: 434, name: Sender)
,I/jxcore-log( 3801): 2015-12-17T14:16:53.273Z SendDataTCPServer.js: TCP/IP server has received 85140 bytes of data
I/jxcore-log( 3801): 
,D/io.jxcore.node.StreamCopyingThread( 3801): Entering thread (ID: 435, name: Receiver)
,I/jxcore-log( 3801): 2015-12-17T14:16:53.277Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3801): 
,D/HeadsetStateMachine( 2365): Disconnected process message: 10, size: 0
,E/bt-btm  ( 2365): tBTM_SEC_DEV:0xa2f4207c rs_disc_pending=1
W/bt-btif ( 2365): bta_dm_check_av:0
W/bt-btif ( 2365): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3801): 2015-12-17T14:16:53.783Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3801): ,
,W/bt-btif ( 2365): invalid rfc slot id: 6,
W/io.jxcore.node.StreamCopyingThread( 3801): Either failed to read from the output stream or write to the input stream (thread ID: 431, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 3801): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3801): onDisconnected: Incoming connection, peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7181] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,I/io.jxcore.node.ConnectionHelper( 3801): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 429
D/io.jxcore.node.OutgoingSocketThread( 3801): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3801): doStop: Thread ID: 431
D/io.jxcore.node.OutgoingSocketThread( 3801): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3801): doStop: Thread ID: 430
D/io.jxcore.node.OutgoingSocketThread( 3801): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 3801): closeLocalSocketAndStreams: Closing the local input stream...
D/io.jxcore.node.OutgoingSocketThread( 3801): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 3801): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3801): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3801): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3801): Exiting thread (ID: 431, name: Receiver)
W/io.jxcore.node.StreamCopyingThread( 3801): Either failed to read from the output stream or write to the input stream (thread ID: 430, thread name: Sender): Socket closed,
E/io.jxcore.node.OutgoingSocketThread( 3801): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3801): onDisconnected: Incoming connection, peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7181] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.ConnectionHelper( 3801): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3801): Exiting thread (ID: 430, name: Sender)
I/jxcore-log( 3801): 2015-12-17T14:16:53.925Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3801): 
,E/bt-btm  ( 2365): tBTM_SEC_DEV:0xa2f42244 rs_disc_pending=0
,W/bt-btif ( 2365): bta_dm_check_av:0
W/bt-btif ( 2365): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3801): 2015-12-17T14:16:54.315Z SendDataConnector.js: CLIENT is data received : 10000,
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:16:54.549Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:16:54.760Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3801): 
,W/bt-rfcomm( 2365): rfc_find_lcid_mcb LCID reused LCID:0x45 current:0x0,
W/bt-rfcomm( 2365): RFCOMM_DisconnectInd LCID:0x45
,I/jxcore-log( 3801): 2015-12-17T14:16:55.003Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3801): 
,E/bt-btm  ( 2365): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2365): onReceive,
,D/BluetoothManagerService(  821): Message: 20
,D/BluetoothManagerService(  821): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@31e92290:true
,I/BTConnectionReceiver( 1506): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=90:E7:C4:F6:69:77, alias=null, name=HTC One M8s, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1506): Bluetooth Device Name: HTC One M8s
,I/jxcore-log( 3801): 2015-12-17T14:16:55.515Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3801): ,
,E/bt-btm  ( 2365): tBTM_SEC_DEV:0xa2f42244 rs_disc_pending=1
,W/bt-btif ( 2365): bta_dm_check_av:0
W/bt-btif ( 2365): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3801): 2015-12-17T14:16:55.674Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:16:55.725Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:16:55.828Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:16:55.969Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:16:56.100Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:16:56.105Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:16:56.110Z SendDataConnector.js: CLIENT Stop now,
I/jxcore-log( 3801): 
I/jxcore-log( 3801): 2015-12-17T14:16:56.110Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3801): 
D/io.jxcore.node.ConnectionHelper( 3801): disconnectOutgoingConnection: Trying to close connection to peer with ID E0:DB:10:1F:C9:5E
,I/io.jxcore.node.ConnectionHelper( 3801): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: E0:DB:10:1F:C9:5E
,I/io.jxcore.node.OutgoingSocketThread( 3801): close
D/io.jxcore.node.OutgoingSocketThread( 3801): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3801): doStop: Thread ID: 435
D/io.jxcore.node.OutgoingSocketThread( 3801): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3801): doStop: Thread ID: 434
D/io.jxcore.node.OutgoingSocketThread( 3801): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 3801): closeLocalSocketAndStreams: Closing the local input stream...
W/io.jxcore.node.StreamCopyingThread( 3801): Either failed to read from the output stream or write to the input stream (thread ID: 434, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3801): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
,W/io.jxcore.node.ConnectionHelper( 3801): onDisconnected: Outgoing connection, peer [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT2526] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed,
D/io.jxcore.node.OutgoingSocketThread( 3801): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 3801): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3801): closeBluetoothSocketAndStreams
,D/io.jxcore.node.ConnectionHelper( 3801): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3801): disconnectOutgoingConnection: Successfully disconnected (peer ID: E0:DB:10:1F:C9:5E
E/io.jxcore.node.ConnectionHelper( 3801): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID E0:DB:10:1F:C9:5E
D/io.jxcore.node.ConnectionHelper( 3801): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3801): Exiting thread (ID: 434, name: Sender)
,W/io.jxcore.node.StreamCopyingThread( 3801): Either failed to read from the output stream or write to the input stream (thread ID: 435, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 3801): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,W/io.jxcore.node.ConnectionHelper( 3801): onDisconnected: Outgoing connection, peer [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT2526] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
E/io.jxcore.node.ConnectionHelper( 3801): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID E0:DB:10:1F:C9:5E
D/io.jxcore.node.ConnectionHelper( 3801): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3801): Exiting thread (ID: 435, name: Receiver)
I/jxcore-log( 3801): 2015-12-17T14:16:56.115Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3801): 
I/jxcore-log( 3801): ---- round done--------
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): do fake peer & start
I/jxcore-log( 3801): 
I/jxcore-log( 3801): Connect to fake peer: 7C:F9:0E:51:18:22
I/jxcore-log( 3801): 
I/jxcore-log( 3801): 2015-12-17T14:16:56.116Z SendDataConnector.js: Start called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3801): 
I/jxcore-log( 3801): 2015-12-17T14:16:56.117Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3801): 
I/jxcore-log( 3801): 2015-12-17T14:16:56.117Z SendDataConnector.js: do connect now
,I/jxcore-log( 3801): 
I/io.jxcore.node.ConnectionHelper( 3801): connect: Trying to connect to peer with ID 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 3801): hasConnection: No connection with peer with ID 7C:F9:0E:51:18:22
W/io.jxcore.node.ConnectionHelper( 3801): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3801): connect: [7C:F9:0E:51:18:22 7C:F9:0E:51:18:22],
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3801): connect: Trying to start connecting to null in address 7C:F9:0E:51:18:22
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3801): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3801): setMaxNumberOfRetries: 0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3801): onConnecting: null 7C:F9:0E:51:18:22
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3801): connect: Started connecting to null in address 7C:F9:0E:51:18:22
I/io.jxcore.node.ConnectionHelper( 3801): connect: Connection process successfully started (peer ID: 7C:F9:0E:51:18:22)
I/chromium( 3801): [INFO:CONSOLE(63)] "logCallback Round of send data to peer E0:DB:10:1F:C9:5E done with result: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3801): Trying to connect to peer with address 7C:F9:0E:51:18:22 (thread ID: 436)
W/BluetoothAdapter( 3801): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 2365): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2365): bta_jv_rfc_port_to_cb(port_handle:0x9):jv handle:0x0 not FOUND
,E/bt-btm  ( 2365): tBTM_SEC_DEV:0xa2f42244 rs_disc_pending=0
,W/bt-btif ( 2365): bta_dm_check_av:0
,W/bt-btif ( 2365): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 2365): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3801): onDnsSdServiceAvailable: Identity: "{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT7778","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3801): onDnsSdServiceAvailable: Resolved peer properties: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT7778]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3801): onServiceDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT7778]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT7778]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT7778], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): modifyListOfDiscoveredPeers: Adding new peer: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT7778]
I/io.jxcore.node.ConnectionHelper( 3801): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT7778], Bluetooth address: 90:E7:C4:F6:69:77, device name: , device address: 92:e7:c4:e6:4c:f8
W/io.jxcore.node.ConnectionHelper( 3801): modifyListOfDiscoveredPeers: Peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT7778] already in the list, will not add again
,E/bt-btm  ( 2365): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2365): onReceive
,I/BTConnectionReceiver( 1506): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1506): Bluetooth Device Name: Thali Test (Galaxy A3)
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3801): onDnsSdServiceAvailable: Identity: "{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT4451","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3801): onDnsSdServiceAvailable: Resolved peer properties: [44:80:EB:7B:5A:05 motorola-XT1072_PT4451]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3801): onServiceDiscovered: [44:80:EB:7B:5A:05 motorola-XT1072_PT4451]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): onPeerDiscovered: [44:80:EB:7B:5A:05 motorola-XT1072_PT4451]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): modifyListOfDiscoveredPeers: [44:80:EB:7B:5A:05 motorola-XT1072_PT4451], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): modifyListOfDiscoveredPeers: Adding new peer: [44:80:EB:7B:5A:05 motorola-XT1072_PT4451]
I/io.jxcore.node.ConnectionHelper( 3801): onPeerDiscovered: [44:80:EB:7B:5A:05 motorola-XT1072_PT4451], Bluetooth address: 44:80:EB:7B:5A:05, device name: , device address: 44:80:eb:7b:5a:07
D/io.jxcore.node.ConnectionHelper( 3801): notifyPeerAvailability: Peer [44:80:EB:7B:5A:05 motorola-XT1072_PT4451] is available
,E/bt-btm  ( 2365): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2365): onReceive
,I/BTConnectionReceiver( 1506): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1506): Bluetooth Device Name: Note3-1,
,W/bt-sdp  ( 2365): SDP - Rcvd conn cnf with error: 0x4  CID 0x46
,E/bt-btif ( 2365): DISCOVERY_COMP_EVT slot id:8, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2365): invalid rfc slot id: 8
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3801): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 436)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3801): Maximum number of allowed retries (0) reached, giving up... (thread ID: 436)
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3801): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3801): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [7C:F9:0E:51:18:22 7C:F9:0E:51:18:22]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3801): Exiting thread (thread ID: 436)
,I/jxcore-log( 3801): 2015-12-17T14:17:01.258Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [7C:F9:0E:51:18:22 7C:F9:0E:51:18:22] failed
I/jxcore-log( 3801): 
I/jxcore-log( 3801): 2015-12-17T14:17:01.258Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [7C:F9:0E:51:18:22 7C:F9:0E:51:18:22] failed
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:17:01.260Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3801): 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3801): setInsecureRfcommSocketPort: Will use port 1 when trying to connect
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3801): shutdown (thread ID: 436)
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3801): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT9642","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3801): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642],
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3801): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642],
I/io.jxcore.node.ConnectionHelper( 3801): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], Bluetooth address: 08:EC:A9:50:75:41, device name: , device address: 0a:ec:a9:50:75:42
D/io.jxcore.node.ConnectionHelper( 3801): notifyPeerAvailability: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642] is available
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3801): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1016","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local.",
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3801): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3801): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
,I/io.jxcore.node.ConnectionHelper( 3801): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 3801): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3801): onScanResult: Callback type: 1, Scan result: ScanResult{mDevice=88:C6:26:19:97:DC, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=[72daa6c3-29c2-6283-0c4a-2818e4d37e75], mManufacturerSpecificData={50824=[38, 25, -105, -36]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=��], mRssi=-79, mTimestampNanos=452180935346},
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3801): onScanResult: Callback type: 1, Scan result: ScanResult{mDevice=88:C6:26:19:97:DC, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=[72daa6c3-29c2-6283-0c4a-2818e4d37e75], mManufacturerSpecificData={50824=[38, 25, -105, -36]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=��], mRssi=-80, mTimestampNanos=452300117221},
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3801): onScanResult: Callback type: 1, Scan result: ScanResult{mDevice=88:C6:26:19:97:DC, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=[72daa6c3-29c2-6283-0c4a-2818e4d37e75], mManufacturerSpecificData={50824=[38, 25, -105, -36]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=��], mRssi=-79, mTimestampNanos=452427686284}
,I/GLSUser ( 1470): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1470): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1470): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1470): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1470): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3512): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3512): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3512): 	at jdm.a(PG:82)
E/HttpOperation( 3512): 	at jcs.o(PG:406)
E/HttpOperation( 3512): 	at jcn.a(PG:1379)
E/HttpOperation( 3512): 	at jcs.i(PG:143)
E/HttpOperation( 3512): 	at blb.a(PG:3937)
E/HttpOperation( 3512): 	at czp.a(PG:18188)
E/HttpOperation( 3512): 	at czp.a(PG:9081)
E/HttpOperation( 3512): 	at czq.run(PG:1686)
E/HttpOperation( 3512): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3512): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3512): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3512): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3512): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3512): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3512): 	at jdj.a(PG:4091)
E/HttpOperation( 3512): 	at jdj.a(PG:1125)
E/HttpOperation( 3512): 	at jdm.a(PG:77)
E/HttpOperation( 3512): 	... 12 more
E/HttpOperation( 3512): Caused by: faj: BadAuthentication
E/HttpOperation( 3512): 	at fal.a(PG:38)
E/HttpOperation( 3512): 	at jdj.a(PG:4089)
E/HttpOperation( 3512): 	... 14 more
,I/art     (  821): Explicit concurrent mark sweep GC freed 31293(1440KB) AllocSpace objects, 9(332KB) LOS objects, 31% free, 34MB/50MB, paused 1.480ms total 75.486ms
,I/GLSUser ( 1470): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1470): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1470): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1470): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1470): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3512): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3512): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3512): 	at jdm.a(PG:82)
E/HttpOperation( 3512): 	at jcs.o(PG:406)
E/HttpOperation( 3512): 	at jcn.a(PG:1379)
E/HttpOperation( 3512): 	at jcs.i(PG:143)
E/HttpOperation( 3512): 	at hec.a(PG:42)
E/HttpOperation( 3512): 	at hee.a(PG:102)
E/HttpOperation( 3512): 	at czr.a(PG:65)
E/HttpOperation( 3512): 	at kka.a(PG:108)
E/HttpOperation( 3512): 	at czp.a(PG:19176)
E/HttpOperation( 3512): 	at czp.a(PG:9081)
E/HttpOperation( 3512): 	at czq.run(PG:1686)
E/HttpOperation( 3512): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3512): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3512): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3512): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3512): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3512): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3512): 	at jdj.a(PG:4091)
E/HttpOperation( 3512): 	at jdj.a(PG:1125)
E/HttpOperation( 3512): 	at jdm.a(PG:77)
E/HttpOperation( 3512): 	... 15 more
E/HttpOperation( 3512): Caused by: faj: BadAuthentication
E/HttpOperation( 3512): 	at fal.a(PG:38)
E/HttpOperation( 3512): 	at jdj.a(PG:4089)
E/HttpOperation( 3512): 	... 17 more
,E/ExperimentLoader( 3512): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3512): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3512): 	at jdm.a(PG:82)
E/ExperimentLoader( 3512): 	at jcs.o(PG:406)
E/ExperimentLoader( 3512): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3512): 	at jcs.i(PG:143)
E/ExperimentLoader( 3512): 	at hec.a(PG:42)
E/ExperimentLoader( 3512): 	at hee.a(PG:102)
E/ExperimentLoader( 3512): 	at czr.a(PG:65)
E/ExperimentLoader( 3512): 	at kka.a(PG:108)
E/ExperimentLoader( 3512): 	at czp.a(PG:19176)
E/ExperimentLoader( 3512): 	at czp.a(PG:9081)
E/ExperimentLoader( 3512): 	at czq.run(PG:1686)
E/ExperimentLoader( 3512): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3512): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3512): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3512): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3512): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3512): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3512): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3512): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3512): 	at jdm.a(PG:77)
E/ExperimentLoader( 3512): 	... 15 more
E/ExperimentLoader( 3512): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3512): 	at fal.a(PG:38)
E/ExperimentLoader( 3512): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3512): 	... 17 more
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 452343, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,I/jxcore-log( 3801): 2015-12-17T14:17:06.263Z SendDataConnector.js: re-try now : 7C:F9:0E:51:18:22,
I/jxcore-log( 3801): 
I/jxcore-log( 3801): 2015-12-17T14:17:06.264Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3801): 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3801): onScanResult: Callback type: 1, Scan result: ScanResult{mDevice=88:C6:26:19:97:DC, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=[72daa6c3-29c2-6283-0c4a-2818e4d37e75], mManufacturerSpecificData={50824=[38, 25, -105, -36]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=��], mRssi=-77, mTimestampNanos=457250548469},
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3801): onScanResult: Callback type: 1, Scan result: ScanResult{mDevice=E0:B7:20:28:C5:81, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -32, -37, 16, 20, -30, -64]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-83, mTimestampNanos=457345428001}
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): onPeerDiscovered: [E0:DB:10:14:E2:C0 <no peer name>]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 <no peer name>], add/update: true,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 <no peer name>]
I/io.jxcore.node.ConnectionHelper( 3801): onPeerDiscovered: [E0:DB:10:14:E2:C0 <no peer name>], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 
W/io.jxcore.node.ConnectionHelper( 3801): modifyListOfDiscoveredPeers: Peer [E0:DB:10:14:E2:C0 <no peer name>] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3801): onScanResult: Callback type: 1, Scan result: ScanResult{mDevice=88:C6:26:19:97:DC, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=[72daa6c3-29c2-6283-0c4a-2818e4d37e75], mManufacturerSpecificData={50824=[38, 25, -105, -36]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=��], mRssi=-77, mTimestampNanos=457362443105},
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3801): onScanResult: Callback type: 1, Scan result: ScanResult{mDevice=FC:F3:1C:A2:30:44, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 124, -7, 14, 81, 24, 34]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-89, mTimestampNanos=457443035761}
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): onPeerDiscovered: [7C:F9:E:51:18:22 <no peer name>],
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): modifyListOfDiscoveredPeers: [7C:F9:E:51:18:22 <no peer name>], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:E:51:18:22 <no peer name>]
I/io.jxcore.node.ConnectionHelper( 3801): onPeerDiscovered: [7C:F9:E:51:18:22 <no peer name>], Bluetooth address: 7C:F9:E:51:18:22, device name: , device address: 
D/io.jxcore.node.ConnectionHelper( 3801): notifyPeerAvailability: Peer [7C:F9:E:51:18:22 <no peer name>] is available
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3801): onScanResult: Callback type: 1, Scan result: ScanResult{mDevice=88:C6:26:19:97:DC, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=[72daa6c3-29c2-6283-0c4a-2818e4d37e75], mManufacturerSpecificData={50824=[38, 25, -105, -36]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=��], mRssi=-77, mTimestampNanos=457609539094}
,D/io.jxcore.node.ConnectionHelper( 3801): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:51:18:22,
E/io.jxcore.node.ConnectionHelper( 3801): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 3801): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,W/io.jxcore.node.ConnectionHelper( 3801): disconnectOutgoingConnection: Failed to disconnect (peer ID: 7C:F9:0E:51:18:22), either no such connection or failed to close the connection
I/jxcore-log( 3801): 2015-12-17T14:17:11.270Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3801): 
I/jxcore-log( 3801): 2015-12-17T14:17:11.271Z SendDataConnector.js: Connect (retry count 1) to peer 7C:F9:0E:51:18:22 with availability status: true
I/jxcore-log( 3801): 
I/jxcore-log( 3801): 2015-12-17T14:17:11.271Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3801): 
I/jxcore-log( 3801): 2015-12-17T14:17:11.272Z SendDataConnector.js: do connect now
I/jxcore-log( 3801): 
,I/io.jxcore.node.ConnectionHelper( 3801): connect: Trying to connect to peer with ID 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 3801): hasConnection: No connection with peer with ID 7C:F9:0E:51:18:22
W/io.jxcore.node.ConnectionHelper( 3801): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3801): connect: [7C:F9:0E:51:18:22 7C:F9:0E:51:18:22]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3801): connect: Trying to start connecting to null in address 7C:F9:0E:51:18:22
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3801): setInsecureRfcommSocketPort: Using port 1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3801): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3801): onConnecting: null 7C:F9:0E:51:18:22
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3801): connect: Started connecting to null in address 7C:F9:0E:51:18:22
I/io.jxcore.node.ConnectionHelper( 3801): connect: Connection process successfully started (peer ID: 7C:F9:0E:51:18:22)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3801): Trying to connect to peer with address 7C:F9:0E:51:18:22 (thread ID: 438)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3801): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3801): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2365): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3801): onScanResult: Callback type: 1, Scan result: ScanResult{mDevice=88:C6:26:19:97:DC, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=[72daa6c3-29c2-6283-0c4a-2818e4d37e75], mManufacturerSpecificData={50824=[38, 25, -105, -36]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=��], mRssi=-86, mTimestampNanos=462306497738}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3801): onScanResult: Callback type: 1, Scan result: ScanResult{mDevice=88:C6:26:19:97:DC, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=[72daa6c3-29c2-6283-0c4a-2818e4d37e75], mManufacturerSpecificData={50824=[38, 25, -105, -36]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=��], mRssi=-85, mTimestampNanos=462426745342}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3801): onScanResult: Callback type: 1, Scan result: ScanResult{mDevice=FC:F3:1C:68:15:41, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 124, -7, 14, 52, -118, -96]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-86, mTimestampNanos=462522782217}
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): onPeerDiscovered: [7C:F9:E:34:8A:A0 <no peer name>]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): modifyListOfDiscoveredPeers: [7C:F9:E:34:8A:A0 <no peer name>], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:E:34:8A:A0 <no peer name>]
I/io.jxcore.node.ConnectionHelper( 3801): onPeerDiscovered: [7C:F9:E:34:8A:A0 <no peer name>], Bluetooth address: 7C:F9:E:34:8A:A0, device name: , device address: 
,W/io.jxcore.node.ConnectionHelper( 3801): modifyListOfDiscoveredPeers: Peer [7C:F9:E:34:8A:A0 <no peer name>] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3801): onScanResult: Callback type: 1, Scan result: ScanResult{mDevice=88:C6:26:19:97:DC, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=[72daa6c3-29c2-6283-0c4a-2818e4d37e75], mManufacturerSpecificData={50824=[38, 25, -105, -36]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=��], mRssi=-87, mTimestampNanos=462545143676}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3801): onScanResult: Callback type: 1, Scan result: ScanResult{mDevice=88:C6:26:19:97:DC, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=[72daa6c3-29c2-6283-0c4a-2818e4d37e75], mManufacturerSpecificData={50824=[38, 25, -105, -36]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=��], mRssi=-87, mTimestampNanos=462672528467}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3801): onScanResult: Callback type: 1, Scan result: ScanResult{mDevice=F0:8B:B2:7E:EA:D2, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -80, -59, 89, 63, 117, 105]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-92, mTimestampNanos=462684309196}
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): onPeerDiscovered: [B0:C5:59:3F:75:69 <no peer name>]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 <no peer name>], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): modifyListOfDiscoveredPeers: Adding new peer: [B0:C5:59:3F:75:69 <no peer name>]
,I/io.jxcore.node.ConnectionHelper( 3801): onPeerDiscovered: [B0:C5:59:3F:75:69 <no peer name>], Bluetooth address: B0:C5:59:3F:75:69, device name: , device address: 
D/io.jxcore.node.ConnectionHelper( 3801): notifyPeerAvailability: Peer [B0:C5:59:3F:75:69 <no peer name>] is available
,W/bt-sdp  ( 2365): SDP - Rcvd conn cnf with error: 0x4  CID 0x47
,E/bt-btif ( 2365): DISCOVERY_COMP_EVT slot id:9, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2365): invalid rfc slot id: 9
W/BluetoothAdapter( 3801): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2365): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66,
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3801): Got discovery timeout, restarting...,
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3801): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3801): setState: RESTARTING
I/wpa_supplicant( 1213): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1213): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80,
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3801): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped,
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3801): onP2pDeviceListChanged: 0 device(s) discovered
,W/bt-btif ( 2365): info:x10,
,D/        ( 2365): remote version info [7c:f9:0e:51:18:22]: 7, 1d, 7d3
E/BluetoothRemoteDevices( 2365): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2365): process_service_search_attr_rsp,
,D/btif_config( 2365): btif_get_device_type: Device [7c:f9:0e:51:18:22] type 1,
,I/BluetoothBondStateMachine( 2365): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:51:18:22 newState: 1
,E/bt-btif ( 2365): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2365): Bond State Change Intent:7C:F9:0E:51:18:22 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2365): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2365): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:51:18:22 newState: 0
,D/BluetoothAdapterProperties( 2365): Failed to remove device: 7C:F9:0E:51:18:22
I/BluetoothBondStateMachine( 2365): Bond State Change Intent:7C:F9:0E:51:18:22 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2365): StableState(): Entering Off State
,W/bt-btif ( 2365): new conn_srvc id:26, app_id:1,
W/bt-btif ( 2365): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2365): bta_dm_pm_ssr:2, lat:1200
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3801): onSocketConnected: [7C:F9:0E:51:18:22 7C:F9:0E:51:18:22]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3801): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 438)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3801): onBytesWritten: 82 bytes successfully written (thread ID: 439)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3801): Outgoing connection initialized (*handshake* thread ID: 439)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3801): Exiting thread (thread ID: 438)
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3801): Entering thread (ID: 439)
,E/bt-btm  ( 2365): tBTM_SEC_DEV:0xa2f4240c rs_disc_pending=0
,W/bt-btif ( 2365): bta_dm_check_av:0
W/bt-btif ( 2365): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2365): invalid rfc slot id: 10
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3801): Disconnected: bt socket closed, read return: -1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3801): onDisconnected: [null null null] (thread ID: 439)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3801): onConnectionFailed: Socket disconnected
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3801): shutdown (thread ID: 438)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3801): onConnectionFailed: Socket disconnected [null null null]
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3801): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3801): Exiting thread (ID: 439)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3801): shutdown (thread ID: 438)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3801): onScanResult: Callback type: 1, Scan result: ScanResult{mDevice=88:C6:26:19:97:DC, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=[72daa6c3-29c2-6283-0c4a-2818e4d37e75], mManufacturerSpecificData={50824=[38, 25, -105, -36]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=��], mRssi=-79, mTimestampNanos=467232248205}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3801): onScanResult: Callback type: 1, Scan result: ScanResult{mDevice=E0:B7:20:28:C5:81, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -32, -37, 16, 20, -30, -64]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-84, mTimestampNanos=467286958674}
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): onPeerDiscovered: [E0:DB:10:14:E2:C0 <no peer name>]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 <no peer name>], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 <no peer name>]
I/io.jxcore.node.ConnectionHelper( 3801): onPeerDiscovered: [E0:DB:10:14:E2:C0 <no peer name>], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 
,W/io.jxcore.node.ConnectionHelper( 3801): modifyListOfDiscoveredPeers: Peer [E0:DB:10:14:E2:C0 <no peer name>] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3801): onScanResult: Callback type: 1, Scan result: ScanResult{mDevice=88:C6:26:19:97:DC, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=[72daa6c3-29c2-6283-0c4a-2818e4d37e75], mManufacturerSpecificData={50824=[38, 25, -105, -36]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=��], mRssi=-80, mTimestampNanos=467355805340}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3801): onScanResult: Callback type: 1, Scan result: ScanResult{mDevice=88:C6:26:19:97:DC, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=[72daa6c3-29c2-6283-0c4a-2818e4d37e75], mManufacturerSpecificData={50824=[38, 25, -105, -36]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=��], mRssi=-79, mTimestampNanos=467978610392}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3801): onScanResult: Callback type: 1, Scan result: ScanResult{mDevice=C8:D9:53:A0:EA:82, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 8, -20, -87, 80, 117, 65]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-86, mTimestampNanos=468079358517}
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): onPeerDiscovered: [8:EC:A9:50:75:41 <no peer name>]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): modifyListOfDiscoveredPeers: [8:EC:A9:50:75:41 <no peer name>], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): modifyListOfDiscoveredPeers: Adding new peer: [8:EC:A9:50:75:41 <no peer name>]
I/io.jxcore.node.ConnectionHelper( 3801): onPeerDiscovered: [8:EC:A9:50:75:41 <no peer name>], Bluetooth address: 8:EC:A9:50:75:41, device name: , device address: 
D/io.jxcore.node.ConnectionHelper( 3801): notifyPeerAvailability: Peer [8:EC:A9:50:75:41 <no peer name>] is available
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3801): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3801): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3801): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3801): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,E/bt-btm  ( 2365): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2365): onReceive
,I/BTConnectionReceiver( 1506): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:51:18:22, alias=null, name=Thali Test (Galaxy A5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1506): Bluetooth Device Name: Thali Test (Galaxy A5)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3801): onScanResult: Callback type: 1, Scan result: ScanResult{mDevice=88:C6:26:19:97:DC, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=[72daa6c3-29c2-6283-0c4a-2818e4d37e75], mManufacturerSpecificData={50824=[38, 25, -105, -36]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=��], mRssi=-77, mTimestampNanos=472160653776}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3801): onScanResult: Callback type: 1, Scan result: ScanResult{mDevice=88:C6:26:19:97:DC, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=[72daa6c3-29c2-6283-0c4a-2818e4d37e75], mManufacturerSpecificData={50824=[38, 25, -105, -36]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=��], mRssi=-76, mTimestampNanos=472285398047}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3801): onScanResult: Callback type: 1, Scan result: ScanResult{mDevice=88:C6:26:19:97:DC, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=[72daa6c3-29c2-6283-0c4a-2818e4d37e75], mManufacturerSpecificData={50824=[38, 25, -105, -36]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=��], mRssi=-77, mTimestampNanos=472409074297}
,W/bt-btif ( 2365): info:x10
,D/        ( 2365): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
E/BluetoothRemoteDevices( 2365): aclStateChangeCallback: Device is NULL
,D/btif_config( 2365): btif_get_device_type: Device [e0:db:10:14:e2:c0] type 1
,I/BluetoothBondStateMachine( 2365): bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 1,
E/bt-btif ( 2365): check_cod: remote_cod = 0x5a020c
I/BluetoothBondStateMachine( 2365): Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2365): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2365): bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 0
D/BluetoothAdapterProperties( 2365): Failed to remove device: E0:DB:10:14:E2:C0
,I/BluetoothBondStateMachine( 2365): Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2365): StableState(): Entering Off State
,W/bt-btif ( 2365): new conn_srvc id:26, app_id:255
W/bt-btif ( 2365): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 2365): bta_dm_pm_ssr:2, lat:1200
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3801): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3801): Incoming connection initialized (thread ID: 441)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3801): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3801): Entering thread (ID: 441)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3801): onBytesRead: Read 82 bytes successfully (thread ID: 441),
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3801): Got valid identity from [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT9551]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3801): onBytesWritten: 82 bytes successfully written (thread ID: 441)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3801): removeThreadFromList: Removing thread with ID 441
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3801): Handshake thread disposed (thread ID: 441)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3801): onIncomingConnectionConnected: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT9551]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3801): Exiting thread (ID: 441)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3801): onConnected: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT9551]
,I/io.jxcore.node.ConnectionHelper( 3801): onConnected: Incoming connection to peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT9551]
D/io.jxcore.node.ConnectionHelper( 3801): hasConnection: No connection with peer with ID E0:DB:10:14:E2:C0
W/io.jxcore.node.ConnectionHelper( 3801): modifyListOfDiscoveredPeers: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT9551] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 3801): onConnected: Incoming socket thread, for peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT9551], created successfully
,D/io.jxcore.node.ConnectionHelper( 3801): onConnected: The total number of connections is now 1
D/io.jxcore.node.IncomingSocketThread( 3801): Entering thread (ID: 442),
,I/io.jxcore.node.IncomingSocketThread( 3801): Local host address: localhost/127.0.0.1, port: 51447
,D/io.jxcore.node.IncomingSocketThread( 3801): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3801): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3801): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.IncomingSocketThread( 3801): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3801): Exiting thread (ID: 442)
I/jxcore-log( 3801): 2015-12-17T14:17:27.181Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3801): 
,D/io.jxcore.node.StreamCopyingThread( 3801): Entering thread (ID: 444, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3801): Entering thread (ID: 443, name: Sender)
,I/wpa_supplicant( 1213): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3801): onP2pDeviceListChanged: 1 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): onP2pDeviceListChanged: Peer 1: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3801): restart: Restarting...
,D/WifiP2pManager( 3801): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler },
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3801): Service request added successfully
,I/jxcore-log( 3801): 2015-12-17T14:17:27.876Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data,
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:17:27.881Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data,
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:17:27.891Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:17:27.913Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:17:27.924Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:17:27.944Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:17:27.964Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:17:28.000Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:17:28.011Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:17:28.014Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:17:28.037Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:17:28.063Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:17:28.100Z SendDataTCPServer.js: TCP/IP server has received 25740 bytes of data
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:17:28.108Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:17:28.129Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:17:28.153Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:17:28.182Z SendDataTCPServer.js: TCP/IP server has received 33660 bytes of data
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:17:28.219Z SendDataTCPServer.js: TCP/IP server has received 35640 bytes of data
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:17:28.253Z SendDataTCPServer.js: TCP/IP server has received 37620 bytes of data
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:17:28.259Z SendDataTCPServer.js: TCP/IP server has received 39600 bytes of data
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:17:28.282Z SendDataTCPServer.js: TCP/IP server has received 41580 bytes of data
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:17:28.308Z SendDataTCPServer.js: TCP/IP server has received 43560 bytes of data
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:17:28.361Z SendDataTCPServer.js: TCP/IP server has received 45540 bytes of data
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:17:28.391Z SendDataTCPServer.js: TCP/IP server has received 47520 bytes of data
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:17:28.421Z SendDataTCPServer.js: TCP/IP server has received 49500 bytes of data
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:17:28.552Z SendDataTCPServer.js: TCP/IP server has received 51480 bytes of data
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:17:28.583Z SendDataTCPServer.js: TCP/IP server has received 53460 bytes of data,
I/jxcore-log( 3801): 
I/wpa_supplicant( 1213): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3801): Service discovery started successfully
,I/jxcore-log( 3801): 2015-12-17T14:17:28.637Z SendDataTCPServer.js: TCP/IP server has received 55440 bytes of data
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:17:28.660Z SendDataTCPServer.js: TCP/IP server has received 57420 bytes of data
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:17:28.685Z SendDataTCPServer.js: TCP/IP server has received 59400 bytes of data
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:17:28.714Z SendDataTCPServer.js: TCP/IP server has received 61380 bytes of data
,I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:17:28.742Z SendDataTCPServer.js: TCP/IP server has received 63360 bytes of data,
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:17:28.780Z SendDataTCPServer.js: TCP/IP server has received 65340 bytes of data,
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:17:28.798Z SendDataTCPServer.js: TCP/IP server has received 67320 bytes of data
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:17:28.820Z SendDataTCPServer.js: TCP/IP server has received 69300 bytes of data
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:17:28.849Z SendDataTCPServer.js: TCP/IP server has received 71280 bytes of data
I/jxcore-log( 3801): ,
,I/jxcore-log( 3801): 2015-12-17T14:17:28.870Z SendDataTCPServer.js: TCP/IP server has received 73260 bytes of data
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:17:28.909Z SendDataTCPServer.js: TCP/IP server has received 75240 bytes of data
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:17:28.922Z SendDataTCPServer.js: TCP/IP server has received 77220 bytes of data
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:17:28.936Z SendDataTCPServer.js: TCP/IP server has received 79200 bytes of data
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:17:28.942Z SendDataTCPServer.js: TCP/IP server has received 81180 bytes of data,
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:17:28.977Z SendDataTCPServer.js: TCP/IP server has received 83160 bytes of data,
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:17:29.009Z SendDataTCPServer.js: TCP/IP server has received 85140 bytes of data,
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:17:29.030Z SendDataTCPServer.js: TCP/IP server has received 87120 bytes of data,
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:17:29.033Z SendDataTCPServer.js: TCP/IP server has received 89100 bytes of data
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:17:29.070Z SendDataTCPServer.js: TCP/IP server has received 91080 bytes of data,
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:17:29.077Z SendDataTCPServer.js: TCP/IP server has received 93060 bytes of data
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:17:29.090Z SendDataTCPServer.js: TCP/IP server has received 95040 bytes of data
I/jxcore-log( 3801): 
,I/jxcore-log( 3801): 2015-12-17T14:17:29.130Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3801): 
,W/bt-btif ( 2365): invalid rfc slot id: 7
W/io.jxcore.node.StreamCopyingThread( 3801): Either failed to read from the output stream or write to the input stream (thread ID: 444, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.IncomingSocketThread( 3801): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3801): onDisconnected: Incoming connection, peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT9551] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3801): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 442
D/io.jxcore.node.IncomingSocketThread( 3801): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3801): doStop: Thread ID: 444
D/io.jxcore.node.IncomingSocketThread( 3801): close: Stopping sending thread...
,I/io.jxcore.node.StreamCopyingThread( 3801): doStop: Thread ID: 443
D/io.jxcore.node.IncomingSocketThread( 3801): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 3801): closeLocalSocketAndStreams: Closing the local input stream...
D/io.jxcore.node.IncomingSocketThread( 3801): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 3801): closeLocalSocketAndStreams: Closing the localhost socket...
W/io.jxcore.node.StreamCopyingThread( 3801): Either failed to read from the output stream or write to the input stream (thread ID: 443, thread name: Sender): Socket closed
,I/io.jxcore.node.IncomingSocketThread( 3801): closeBluetoothSocketAndStreams
E/io.jxcore.node.IncomingSocketThread( 3801): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.ConnectionHelper( 3801): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3801): Exiting thread (ID: 444, name: Receiver)
W/io.jxcore.node.ConnectionHelper( 3801): onDisconnected: Incoming connection, peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT9551] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.ConnectionHelper( 3801): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,D/io.jxcore.node.StreamCopyingThread( 3801): Exiting thread (ID: 443, name: Sender)
I/jxcore-log( 3801): 2015-12-17T14:17:29.285Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3801): 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3801): onScanResult: Callback type: 1, Scan result: ScanResult{mDevice=E0:B7:20:28:C5:81, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -32, -37, 16, 20, -30, -64]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-79, mTimestampNanos=476348109920}
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): onPeerDiscovered: [E0:DB:10:14:E2:C0 <no peer name>]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 <no peer name>], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 <no peer name>]
I/io.jxcore.node.ConnectionHelper( 3801): onPeerDiscovered: [E0:DB:10:14:E2:C0 <no peer name>], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 
W/io.jxcore.node.ConnectionHelper( 3801): modifyListOfDiscoveredPeers: Peer [E0:DB:10:14:E2:C0 <no peer name>] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3801): onScanResult: Callback type: 1, Scan result: ScanResult{mDevice=88:C6:26:19:97:DC, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=[72daa6c3-29c2-6283-0c4a-2818e4d37e75], mManufacturerSpecificData={50824=[38, 25, -105, -36]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=��], mRssi=-86, mTimestampNanos=476353588462}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3801): onScanResult: Callback type: 1, Scan result: ScanResult{mDevice=88:C6:26:19:97:DC, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=[72daa6c3-29c2-6283-0c4a-2818e4d37e75], mManufacturerSpecificData={50824=[38, 25, -105, -36]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=��], mRssi=-87, mTimestampNanos=476480540129}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3801): onScanResult: Callback type: 1, Scan result: ScanResult{mDevice=C8:D9:53:A0:EC:4E, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 8, -20, -87, 80, 118, 39]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-83, mTimestampNanos=476783796847}
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): onPeerDiscovered: [8:EC:A9:50:76:27 <no peer name>]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): modifyListOfDiscoveredPeers: [8:EC:A9:50:76:27 <no peer name>], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): modifyListOfDiscoveredPeers: Updating the timestamp of peer [8:EC:A9:50:76:27 <no peer name>]
I/io.jxcore.node.ConnectionHelper( 3801): onPeerDiscovered: [8:EC:A9:50:76:27 <no peer name>], Bluetooth address: 8:EC:A9:50:76:27, device name: , device address: 
W/io.jxcore.node.ConnectionHelper( 3801): modifyListOfDiscoveredPeers: Peer [8:EC:A9:50:76:27 <no peer name>] already in the list, will not add again
,W/bt-rfcomm( 2365): rfc_find_lcid_mcb LCID reused LCID:0x4b current:0x0
,W/bt-rfcomm( 2365): RFCOMM_DisconnectInd LCID:0x4b
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3801): onScanResult: Callback type: 1, Scan result: ScanResult{mDevice=88:C6:26:19:97:DC, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=[72daa6c3-29c2-6283-0c4a-2818e4d37e75], mManufacturerSpecificData={50824=[38, 25, -105, -36]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=��], mRssi=-85, mTimestampNanos=476856171587}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3801): onScanResult: Callback type: 1, Scan result: ScanResult{mDevice=F0:8B:B2:7E:EA:D2, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -80, -59, 89, 63, 117, 105]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-93, mTimestampNanos=476997868670}
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): onPeerDiscovered: [B0:C5:59:3F:75:69 <no peer name>]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 <no peer name>], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 <no peer name>]
I/io.jxcore.node.ConnectionHelper( 3801): onPeerDiscovered: [B0:C5:59:3F:75:69 <no peer name>], Bluetooth address: B0:C5:59:3F:75:69, device name: , device address: 
W/io.jxcore.node.ConnectionHelper( 3801): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 <no peer name>] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3801): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1016","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3801): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3801): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
I/io.jxcore.node.ConnectionHelper( 3801): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 3801): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3801): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT9642","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3801): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3801): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
I/io.jxcore.node.ConnectionHelper( 3801): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], Bluetooth address: 08:EC:A9:50:75:41, device name: , device address: 0a:ec:a9:50:75:42
,W/io.jxcore.node.ConnectionHelper( 3801): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642] already in the list, will not add again
,E/bt-btm  ( 2365): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2365): onReceive
,I/BTConnectionReceiver( 1506): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1506): Bluetooth Device Name: Note4-1
,I/wpa_supplicant( 1213): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3801): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT7778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT7778]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
,I/BooksSync( 3707): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3707): GmsCore Version = 7.8.99 (2134222-430)
,V/KeepSync( 3744): Connecting to GoogleApiClient
,D/btif_config_util( 2365): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/GLSUser ( 1470): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1470): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1470): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1470): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1470): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1470): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1470): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1470): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1470): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1470): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,V/KeepSync( 3744): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3744): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3744): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3744): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1470): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1470): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1470): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1470): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1470): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1470): Explicit concurrent mark sweep GC freed 47682(2MB) AllocSpace objects, 19(2MB) LOS objects, 36% free, 27MB/43MB, paused 2.053ms total 44.485ms
,E/BooksAccountManager( 3707): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3707): Soft error
E/BooksSync( 3707): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3707): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3707): Sync error
E/BooksSync( 3707): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3707): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/GLSUser ( 1470): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/BooksSync( 3707): Finished books sync
I/GLSUser ( 1470): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1470): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1470): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1470): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 477981, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,E/KeepSync( 3744): IOException
E/KeepSync( 3744): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3744): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3744): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3744): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3744): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3744): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3744): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3744): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3744): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3744): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3744): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3744): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3744): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3744): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3744): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3744): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3744): 	... 10 more
W/KeepSync( 3744): Sync result 2
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 471836, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3801): onScanResult: Callback type: 1, Scan result: ScanResult{mDevice=58:BE:EA:0C:AC:D5, mScanRecord=ScanRecord [mAdvertiseFlags=2, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=HTC One M8s], mRssi=-85, mTimestampNanos=483950695178}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3801): onScanResult: Callback type: 1, Scan result: ScanResult{mDevice=88:C6:26:19:97:DC, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=[72daa6c3-29c2-6283-0c4a-2818e4d37e75], mManufacturerSpecificData={50824=[38, 25, -105, -36]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=��], mRssi=-80, mTimestampNanos=483980922001}
,D/HeadsetStateMachine( 2365): Disconnected process message: 10, size: 0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3801): onScanResult: Callback type: 1, Scan result: ScanResult{mDevice=88:C6:26:19:97:DC, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=[72daa6c3-29c2-6283-0c4a-2818e4d37e75], mManufacturerSpecificData={50824=[38, 25, -105, -36]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=��], mRssi=-77, mTimestampNanos=488668304134}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3801): onScanResult: Callback type: 1, Scan result: ScanResult{mDevice=88:C6:26:19:97:DC, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=[72daa6c3-29c2-6283-0c4a-2818e4d37e75], mManufacturerSpecificData={50824=[38, 25, -105, -36]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=��], mRssi=-77, mTimestampNanos=488784786634}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3801): onScanResult: Callback type: 1, Scan result: ScanResult{mDevice=88:C6:26:19:97:DC, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=[72daa6c3-29c2-6283-0c4a-2818e4d37e75], mManufacturerSpecificData={50824=[38, 25, -105, -36]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=��], mRssi=-78, mTimestampNanos=488908642051}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3801): onScanResult: Callback type: 1, Scan result: ScanResult{mDevice=88:C6:26:19:97:DC, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=[72daa6c3-29c2-6283-0c4a-2818e4d37e75], mManufacturerSpecificData={50824=[38, 25, -105, -36]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=��], mRssi=-77, mTimestampNanos=489030100853}
,I/wpa_supplicant( 1213): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3801): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3801): restart: Restarting...
,--------- beginning of crash
F/libc    ( 1213): Fatal signal 11 (SIGSEGV), code 1, fault addr 0xc in tid 1213 (wpa_supplicant)
I/libc    ( 1213): Suppressing debuggerd output because prctl(PR_GET_DUMPABLE)==0
,D/WifiP2pManager( 3801): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3801): Service request added successfully
,D/btif_config_util( 2365): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3801): onScanResult: Callback type: 1, Scan result: ScanResult{mDevice=88:C6:26:19:97:DC, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=[72daa6c3-29c2-6283-0c4a-2818e4d37e75], mManufacturerSpecificData={50824=[38, 25, -105, -36]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=��], mRssi=-86, mTimestampNanos=493688487987}
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3801): Failed to start the service discovery, got error code: 3
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3801): onScanResult: Callback type: 1, Scan result: ScanResult{mDevice=88:C6:26:19:97:DC, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=[72daa6c3-29c2-6283-0c4a-2818e4d37e75], mManufacturerSpecificData={50824=[38, 25, -105, -36]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=��], mRssi=-86, mTimestampNanos=493803037414}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3801): onScanResult: Callback type: 1, Scan result: ScanResult{mDevice=77:BD:1F:8C:AD:03, mScanRecord=ScanRecord [mAdvertiseFlags=26, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -107, -57, -121, 60, 81]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-88, mTimestampNanos=493920676632}
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): onPeerDiscovered: [F8:95:C7:87:3C:51 <no peer name>]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 <no peer name>], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 <no peer name>]
,I/io.jxcore.node.ConnectionHelper( 3801): onPeerDiscovered: [F8:95:C7:87:3C:51 <no peer name>], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
W/io.jxcore.node.ConnectionHelper( 3801): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 <no peer name>] already in the list, will not add again
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3801): onScanResult: Callback type: 1, Scan result: ScanResult{mDevice=88:C6:26:19:97:DC, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=[72daa6c3-29c2-6283-0c4a-2818e4d37e75], mManufacturerSpecificData={50824=[38, 25, -105, -36]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=��], mRssi=-86, mTimestampNanos=493923013403}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3801): onScanResult: Callback type: 1, Scan result: ScanResult{mDevice=77:BD:1F:8C:AD:03, mScanRecord=ScanRecord [mAdvertiseFlags=26, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -107, -57, -121, 60, 81]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-95, mTimestampNanos=498678853922}
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): onPeerDiscovered: [F8:95:C7:87:3C:51 <no peer name>]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 <no peer name>], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 <no peer name>]
,I/io.jxcore.node.ConnectionHelper( 3801): onPeerDiscovered: [F8:95:C7:87:3C:51 <no peer name>], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
W/io.jxcore.node.ConnectionHelper( 3801): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 <no peer name>] already in the list, will not add again
,D/HeadsetStateMachine( 2365): Disconnected process message: 10, size: 0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3801): onScanResult: Callback type: 1, Scan result: ScanResult{mDevice=88:C6:26:19:97:DC, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=[72daa6c3-29c2-6283-0c4a-2818e4d37e75], mManufacturerSpecificData={50824=[38, 25, -105, -36]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=��], mRssi=-75, mTimestampNanos=503791596056}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3801): onScanResult: Callback type: 1, Scan result: ScanResult{mDevice=C8:D9:53:A0:EA:82, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 8, -20, -87, 80, 117, 65]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-82, mTimestampNanos=503812116212},
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): onPeerDiscovered: [8:EC:A9:50:75:41 <no peer name>]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): modifyListOfDiscoveredPeers: [8:EC:A9:50:75:41 <no peer name>], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): modifyListOfDiscoveredPeers: Updating the timestamp of peer [8:EC:A9:50:75:41 <no peer name>]
I/io.jxcore.node.ConnectionHelper( 3801): onPeerDiscovered: [8:EC:A9:50:75:41 <no peer name>], Bluetooth address: 8:EC:A9:50:75:41, device name: , device address: ,
W/io.jxcore.node.ConnectionHelper( 3801): modifyListOfDiscoveredPeers: Peer [8:EC:A9:50:75:41 <no peer name>] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3801): onScanResult: Callback type: 1, Scan result: ScanResult{mDevice=88:C6:26:19:97:DC, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=[72daa6c3-29c2-6283-0c4a-2818e4d37e75], mManufacturerSpecificData={50824=[38, 25, -105, -36]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=��], mRssi=-77, mTimestampNanos=503913670847}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3801): onScanResult: Callback type: 1, Scan result: ScanResult{mDevice=88:C6:26:19:97:DC, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=[72daa6c3-29c2-6283-0c4a-2818e4d37e75], mManufacturerSpecificData={50824=[38, 25, -105, -36]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=��], mRssi=-77, mTimestampNanos=504037131941}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3801): onScanResult: Callback type: 1, Scan result: ScanResult{mDevice=88:C6:26:19:97:DC, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=[72daa6c3-29c2-6283-0c4a-2818e4d37e75], mManufacturerSpecificData={50824=[38, 25, -105, -36]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=��], mRssi=-86, mTimestampNanos=508596769596}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3801): onScanResult: Callback type: 1, Scan result: ScanResult{mDevice=88:C6:26:19:97:DC, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=[72daa6c3-29c2-6283-0c4a-2818e4d37e75], mManufacturerSpecificData={50824=[38, 25, -105, -36]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=��], mRssi=-86, mTimestampNanos=508719310585}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3801): onScanResult: Callback type: 1, Scan result: ScanResult{mDevice=88:C6:26:19:97:DC, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=[72daa6c3-29c2-6283-0c4a-2818e4d37e75], mManufacturerSpecificData={50824=[38, 25, -105, -36]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=��], mRssi=-88, mTimestampNanos=508844432095}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3801): onScanResult: Callback type: 1, Scan result: ScanResult{mDevice=88:C6:26:19:97:DC, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=[72daa6c3-29c2-6283-0c4a-2818e4d37e75], mManufacturerSpecificData={50824=[38, 25, -105, -36]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=��], mRssi=-87, mTimestampNanos=508968858762}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3801): onScanResult: Callback type: 1, Scan result: ScanResult{mDevice=77:BD:1F:8C:AD:03, mScanRecord=ScanRecord [mAdvertiseFlags=26, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -107, -57, -121, 60, 81]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-89, mTimestampNanos=509001956470}
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): onPeerDiscovered: [F8:95:C7:87:3C:51 <no peer name>]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 <no peer name>], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 <no peer name>]
I/io.jxcore.node.ConnectionHelper( 3801): onPeerDiscovered: [F8:95:C7:87:3C:51 <no peer name>], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
W/io.jxcore.node.ConnectionHelper( 3801): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 <no peer name>] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3801): onScanResult: Callback type: 1, Scan result: ScanResult{mDevice=FC:F3:1C:68:15:41, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 124, -7, 14, 52, -118, -96]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-86, mTimestampNanos=509018533293}
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): onPeerDiscovered: [7C:F9:E:34:8A:A0 <no peer name>]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): modifyListOfDiscoveredPeers: [7C:F9:E:34:8A:A0 <no peer name>], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:E:34:8A:A0 <no peer name>]
I/io.jxcore.node.ConnectionHelper( 3801): onPeerDiscovered: [7C:F9:E:34:8A:A0 <no peer name>], Bluetooth address: 7C:F9:E:34:8A:A0, device name: , device address: 
W/io.jxcore.node.ConnectionHelper( 3801): modifyListOfDiscoveredPeers: Peer [7C:F9:E:34:8A:A0 <no peer name>] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3801): onScanResult: Callback type: 1, Scan result: ScanResult{mDevice=E0:B7:20:28:C5:81, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -32, -37, 16, 20, -30, -64]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-78, mTimestampNanos=513727827771}
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): onPeerDiscovered: [E0:DB:10:14:E2:C0 <no peer name>]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 <no peer name>], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 <no peer name>]
I/io.jxcore.node.ConnectionHelper( 3801): onPeerDiscovered: [E0:DB:10:14:E2:C0 <no peer name>], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 
W/io.jxcore.node.ConnectionHelper( 3801): modifyListOfDiscoveredPeers: Peer [E0:DB:10:14:E2:C0 <no peer name>] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3801): onScanResult: Callback type: 1, Scan result: ScanResult{mDevice=88:C6:26:19:97:DC, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=[72daa6c3-29c2-6283-0c4a-2818e4d37e75], mManufacturerSpecificData={50824=[38, 25, -105, -36]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=��], mRssi=-79, mTimestampNanos=513756204594}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3801): onScanResult: Callback type: 1, Scan result: ScanResult{mDevice=88:C6:26:19:97:DC, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=[72daa6c3-29c2-6283-0c4a-2818e4d37e75], mManufacturerSpecificData={50824=[38, 25, -105, -36]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=��], mRssi=-79, mTimestampNanos=513879892250}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3801): onScanResult: Callback type: 1, Scan result: ScanResult{mDevice=88:C6:26:19:97:DC, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=[72daa6c3-29c2-6283-0c4a-2818e4d37e75], mManufacturerSpecificData={50824=[38, 25, -105, -36]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=��], mRssi=-79, mTimestampNanos=514007260166}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3801): onScanResult: Callback type: 1, Scan result: ScanResult{mDevice=88:C6:26:19:97:DC, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=[72daa6c3-29c2-6283-0c4a-2818e4d37e75], mManufacturerSpecificData={50824=[38, 25, -105, -36]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=��], mRssi=-77, mTimestampNanos=518680884800}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3801): onScanResult: Callback type: 1, Scan result: ScanResult{mDevice=88:C6:26:19:97:DC, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=[72daa6c3-29c2-6283-0c4a-2818e4d37e75], mManufacturerSpecificData={50824=[38, 25, -105, -36]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=��], mRssi=-77, mTimestampNanos=518804043394}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3801): onScanResult: Callback type: 1, Scan result: ScanResult{mDevice=C8:D9:53:A0:EA:82, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 8, -20, -87, 80, 117, 65]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-82, mTimestampNanos=518814328967}
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): onPeerDiscovered: [8:EC:A9:50:75:41 <no peer name>]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): modifyListOfDiscoveredPeers: [8:EC:A9:50:75:41 <no peer name>], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): modifyListOfDiscoveredPeers: Updating the timestamp of peer [8:EC:A9:50:75:41 <no peer name>]
I/io.jxcore.node.ConnectionHelper( 3801): onPeerDiscovered: [8:EC:A9:50:75:41 <no peer name>], Bluetooth address: 8:EC:A9:50:75:41, device name: , device address: 
W/io.jxcore.node.ConnectionHelper( 3801): modifyListOfDiscoveredPeers: Peer [8:EC:A9:50:75:41 <no peer name>] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3801): onScanResult: Callback type: 1, Scan result: ScanResult{mDevice=88:C6:26:19:97:DC, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=[72daa6c3-29c2-6283-0c4a-2818e4d37e75], mManufacturerSpecificData={50824=[38, 25, -105, -36]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=��], mRssi=-77, mTimestampNanos=518924088081}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3801): onScanResult: Callback type: 1, Scan result: ScanResult{mDevice=88:C6:26:19:97:DC, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=[72daa6c3-29c2-6283-0c4a-2818e4d37e75], mManufacturerSpecificData={50824=[38, 25, -105, -36]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=��], mRssi=-77, mTimestampNanos=519051601779}
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): checkListForExpiredPeers: Peer [44:80:EB:7B:5A:05 motorola-XT1072_PT4451] expired
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): checkListForExpiredPeers: Peer [7C:F9:E:51:18:22 <no peer name>] expired
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): modifyListOfDiscoveredPeers: [44:80:EB:7B:5A:05 motorola-XT1072_PT4451], add/update: false
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): modifyListOfDiscoveredPeers: Removed [44:80:EB:7B:5A:05 motorola-XT1072_PT4451]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): modifyListOfDiscoveredPeers: [7C:F9:E:51:18:22 <no peer name>], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): modifyListOfDiscoveredPeers: Removed [7C:F9:E:51:18:22 <no peer name>]
,I/io.jxcore.node.ConnectionHelper( 3801): onPeerLost: [44:80:EB:7B:5A:05 motorola-XT1072_PT4451]
D/io.jxcore.node.ConnectionHelper( 3801): hasConnection: No connection with peer with ID 44:80:EB:7B:5A:05
D/io.jxcore.node.ConnectionHelper( 3801): modifyListOfDiscoveredPeers: Peer [44:80:EB:7B:5A:05 motorola-XT1072_PT4451] removed
D/io.jxcore.node.ConnectionHelper( 3801): notifyPeerAvailability: Peer [44:80:EB:7B:5A:05 motorola-XT1072_PT4451] not available
I/io.jxcore.node.ConnectionHelper( 3801): onPeerLost: [7C:F9:E:51:18:22 <no peer name>]
,D/io.jxcore.node.ConnectionHelper( 3801): hasConnection: No connection with peer with ID 7C:F9:E:51:18:22
D/io.jxcore.node.ConnectionHelper( 3801): modifyListOfDiscoveredPeers: Peer [7C:F9:E:51:18:22 <no peer name>] removed
D/io.jxcore.node.ConnectionHelper( 3801): notifyPeerAvailability: Peer [7C:F9:E:51:18:22 <no peer name>] not available
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3801): Got discovery timeout, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3801): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3801): setState: RESTARTING
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3801): Failed to shutdown P2P device discovery, got error code: 0
,E/WifiStateMachine(  821): Connection lost, restart supplicant
,E/WifiMonitor(  821): killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,W/Settings( 3097): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/WifiConfigStore(  821): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
E/WifiConfigStore(  821): failed to set BSSID: any
E/native  (  821): do suspend true
D/CommandListener(  353): Clearing all IP addresses on wlan0
W/Settings( 1797): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/jxcore-log( 3801): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 3801): 
I/jxcore-log( 3801): The Coordinator has disconnected!
I/jxcore-log( 3801): 
,V/NativeCrypto( 1470): Read error: ssl=0xaed24800: I/O error during system call, Connection timed out
V/NativeCrypto( 1470): SSL shutdown failed: ssl=0xaed24800: I/O error during system call, Broken pipe
,D/ConnectivityService(  821): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  821): NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
,E/WifiStateMachine(  821): WifiStateMachine: Leaving Connected state
,E/WifiStateMachine(  821): Unexpected BatchedScanResults :null
D/WifiScanningService(  821): SCAN_AVAILABLE : 1
D/RttService(  821): SCAN_AVAILABLE : 1
D/RttService(  821): EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService(  821): StartedState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService(  821): DefaultState
,D/ConnectivityService(  821): reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10011
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  821): ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3801): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  821): DefaultState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  821): Forcing reevaluation
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  821): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  821): Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): onWifiStateChanged: State changed to 1
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): onWifiStateChanged: Wi-Fi disabled, pausing Wi-Fi Direct based peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3801): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3801): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3801): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3801): stopWifiPeerDiscovery: Stopped
,D/WifiNetworkAgent(  821): NetworkAgent: NetworkAgent channel lost
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3801): onP2pDeviceListChanged: 0 device(s) discovered
D/AndroidRuntime( 3801): Shutting down VM
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  821): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
,D/ConnectivityService(  821): notifyType LOST for NetworkAgentInfo [WIFI () - 101]
D/CSLegacyTypeTracker(  821): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  821): OfflineState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  821): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  821): Disconnected - quitting
D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityManager.CallbackHandler( 1067): CM callback handler got msg 524292
D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/Tethering(  821): MasterInitialState.processMessage what=3
,D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  821): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/ConnectivityService(  821): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/ConnectivityService(  821): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
,I/NetworkMonitor( 3035): type=WIFI subType= reason=null isConnected=false
,D/Tethering(  821): MasterInitialState.processMessage what=3
V/MusicLeanback( 3035): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/SprintDMReceiver( 3888): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3888): simOperator:  IMSI: null
D/SprintDMReceiver( 3888): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1772): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1772): onCreate
,D/SystemUpdateService( 1772): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1772): active receiver: enabled
,I/SystemUpdateService( 1772): showing system update notification
I/iu.Environment( 1772): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1772): num queued entries: 0
,I/iu.UploadsManager( 1772): num updated entries: 0
,I/iu.SyncManager( 1772): NEXT; no task
,D/ChimeraCfgMgr( 1772): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Babel   ( 3097): connection state changed from CONNECTED to DISCONNECTED
,I/ValidateNoPeople(  821): skipping global notification
,V/SystemUpdateService( 1772): retry (wakeup: false) in 3599973 ms
,D/SystemUpdateService( 1772): onDestroy
,D/PhoneInterfaceManager( 1261): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1261): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  821): getDataEnabled: retVal=false
,V/MusicLeanback( 3035): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,E/GpsLocationProvider(  821): No APN found to select.
,D/PhoneInterfaceManager( 1261): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
,E/PhoneInterfaceManager( 1261): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
D/TelephonyManager(  821): getDataEnabled: retVal=false
D/SprintDMReceiver( 3888): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3888): simOperator:  IMSI: null
,D/SprintDMReceiver( 3888): Not Sprint UICC, don't do anything.
,E/GpsLocationProvider(  821): No APN found to select.
I/SystemUpdateService( 1772): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1772): onCreate
,D/SystemUpdateService( 1772): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1772): active receiver: enabled
,I/SystemUpdateService( 1772): showing system update notification
,I/ValidateNoPeople(  821): skipping global notification,
V/SystemUpdateService( 1772): retry (wakeup: false) in 3599976 ms
,D/SystemUpdateService( 1772): onDestroy
,D/ChimeraCfgMgr( 1772): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/SoftapController(  353): Softap fwReload - Ok
,D/CommandListener(  353): Setting iface cfg
,D/CommandListener(  353): Trying to bring down wlan0
,D/CommandListener(  353): Clearing all IP addresses on wlan0
,D/Tethering(  821): InitialState.processMessage what=4
,D/Tethering(  821): sendTetherStateChangedBroadcast 0, 0, 0,
E/WifiMonitor(  821): killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,D/WifiMonitor(  821): startMonitoring(wlan0) with mConnected = false,
,E/WifiHW  (  821): Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory,
,I/wpa_supplicant( 4366): Successfully initialized wpa_supplicant
,I/wpa_supplicant( 4366): rfkill: Cannot open RFKILL control device,
,D/Tethering(  821): sendTetherStateChangedBroadcast 1, 0, 0
,I/wpa_supplicant( 4366): rfkill: Cannot open RFKILL control device
,E/wpa_supplicant( 4366): Could not read interface p2p-dev-wlan0 flags: No such device
,D/WifiConfigStore(  821): Loading config and enabling all networks 
,D/WifiService(  821): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@37e50cdc}
,E/WifiConfigStore(  821): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,D/WifiNative-HAL(  821): Setting external_sim to 1
,D/WifiStateMachine(  821): Setting OUI to 92-68-C3
,I/WifiNative-HAL(  821): startHal
D/wifi    (  821): setting scan oui 0xb4bab3d0
D/WifiHAL (  821): Sending mac address OUI
W/Settings( 3097): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,E/native  (  821): do suspend true,
,W/CommandListener(  353): Failed to retrieve HW addr for p2p0 (No such device)
,D/WifiScanningService(  821): SCAN_AVAILABLE : 3
,D/RttService(  821): SCAN_AVAILABLE : 3
D/RttService(  821): DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService(  821): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  821): startHal
,D/wifi    (  821): getting scan capabilities on interface[0] = 0xb4bab3d0
D/WifiHAL (  821): Creating message to get scan capablities; iface = 5
D/WifiHAL (  821): In GetCapabilities::handleResponse
D/WifiHAL (  821): Id = 0, subcmd = 0, len = 28, expected len = 32
D/WifiScanningService(  821): StartedState
D/CommandListener(  353): Setting iface cfg
,E/WifiP2pService(  821): Unable to change interface settings: java.lang.IllegalStateException: command '76 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 76 Failed to set address (No such device)'
D/WifiMonitor(  821): startMonitoring(p2p0) with mConnected = true
,I/wpa_supplicant( 4366): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,D/WifiNative-HAL(  821): p2pGetDeviceAddress
,D/WifiNative-HAL(  821): p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,I/wpa_supplicant( 4366): p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN,
,E/WifiStateMachine(  821): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,E/WifiConfigStore(  821):  rewrite network history for "NG700"WPA_PSK
,E/WifiConfigStore(  821):  rewrite network history for "NG7005g"WPA_PSK
,E/WifiStateMachine(  821): CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
E/WifiConfigStore(  821): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiStateMachine(  821): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=0
,E/WifiConfigStore(  821): will read network variables netId=0
,E/WifiStateMachine(  821): CMD_AUTO_CONNECT did save config ->  nid=0,
E/WifiConfigStore(  821): will read network variables netId=0
,I/wpa_supplicant( 4366): wlan0: Trying to associate with SSID 'NG7005g'
,I/wpa_supplicant( 4366): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 4366): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 4366): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=0 id_str=]
,D/ConnectivityService(  821): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} }
,E/WifiConfigStore(  821): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  821): NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  821): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  353): Setting iface cfg
,E/WifiStateMachine(  821): Start Dhcp Watchdog 3
,E/WifiStateMachine(  821):  WifiLinkLayerStats: 
E/WifiStateMachine(  821):  my bss beacon rx: 1
E/WifiStateMachine(  821):  RSSI mgmt: -47
E/WifiStateMachine(  821):  BE :  rx=0 tx=3 lost=0 retries=0
E/WifiStateMachine(  821):  BK :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  821):  VI :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  821):  VO :  rx=2 tx=0 lost=0 retries=0
E/WifiStateMachine(  821):  on_time : 0 tx_time=40 rx_time=168 scan_time=0
,E/native  (  821): do suspend false
,E/WifiStateMachine(  821): scanCount==0 - aborting
,I/dhcpcd  ( 4373): version 5.5.6 starting
,I/dhcpcd  ( 4373): wlan0: rebinding lease of 192.168.1.122
,I/dhcpcd  ( 4373): wlan0: acknowledged 192.168.1.122 from 192.168.1.1
,I/dhcpcd  ( 4373): wlan0: leased 192.168.1.122 for 86400 seconds
,E/native  (  821): do suspend true
,D/ConnectivityService(  821): NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService(  821): Adding iface wlan0 to network 102
,E/WifiStateMachine(  821): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  821): Unexpected mtu value: 0, wlan0
,D/ConnectivityService(  821): Adding Route [fe80::/64 -> :: wlan0] to network 102
,D/ConnectivityService(  821): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102,
,D/ConnectivityService(  821): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,D/ConnectivityService(  821): Setting Dns servers for network 102 to [/192.168.1.1],
,D/ConnectivityService(  821): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,D/ConnectivityService(  821): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,D/ConnectivityService(  821): rematching NetworkAgentInfo [WIFI () - 102]
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 102](  821): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 102](  821): Connected
,D/ConnectivityService(  821):    accepting network in place of null
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 102](  821): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 102](  821): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
,D/ConnectivityService(  821): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} }
,D/ConnectivityService(  821): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
,D/ConnectivityManager.CallbackHandler( 1067): CM callback handler got msg 524290
,D/CSLegacyTypeTracker(  821): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  821): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 3035): type=WIFI subType= reason=null isConnected=true
,D/PhoneInterfaceManager( 1261): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1261): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  821): getDataEnabled: retVal=false
,V/MusicLeanback( 3035): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,E/GpsLocationProvider(  821): No APN found to select.
,D/SprintDMReceiver( 3888): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3888): simOperator:  IMSI: null
D/SprintDMReceiver( 3888): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1772): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1772): onCreate
,D/SystemUpdateService( 1772): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1772): active receiver: enabled
,I/SystemUpdateService( 1772): showing system update notification
,I/iu.Environment( 1772): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1772): num queued entries: 0
I/iu.UploadsManager( 1772): num updated entries: 0
I/ValidateNoPeople(  821): skipping global notification
,I/iu.SyncManager( 1772): NEXT; no task
,V/SystemUpdateService( 1772): retry (wakeup: false) in 3599973 ms
,D/ChimeraCfgMgr( 1772): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/SystemUpdateService( 1772): onDestroy
,D/ChimeraCfgMgr( 1772): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 102](  821): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 17 Dec 2015 14:18:26 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1450361906468], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1450361906451]}
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 102](  821): Validated
D/ConnectivityService(  821): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
,D/ConnectivityService(  821): Validated NetworkAgentInfo [WIFI () - 102]
D/ConnectivityService(  821): rematching NetworkAgentInfo [WIFI () - 102]
D/ConnectivityService(  821): Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
D/ConnectivityService(  821): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
,D/ConnectivityManager.CallbackHandler( 1067): CM callback handler got msg 524290
D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,I/GLSUser ( 1470): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1470): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1470): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1470): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1470): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/Herrevad( 1772): NQAS connected
,D/WifiService(  821): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@37e50cdc}
,I/Babel   ( 3097): connection state changed from DISCONNECTED to CONNECTED
,I/art     (  821): Explicit concurrent mark sweep GC freed 64402(2MB) AllocSpace objects, 7(394KB) LOS objects, 31% free, 34MB/50MB, paused 1.657ms total 78.821ms
,W/Kids    ( 1772): [AccountUtils] Account not ready
W/Kids    ( 1772): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 1772): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 1772): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 1772): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 1772): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 1772): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 1772): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 1772): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 1772): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 1772): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 1772): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 1772): 	at java.lang.Thread.run(Thread.java:818)
,D/GCM     ( 1470): Connected
,D/GCM     ( 1470): Message class com.google.f.a.a.p
,D/ConnectivityService(  821): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,D/HeadsetStateMachine( 2365): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2365): Disconnected process message: 10, size: 0
,W/bt-btif ( 2365): info:x10
,D/        ( 2365): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3,
E/BluetoothRemoteDevices( 2365): aclStateChangeCallback: Device is NULL
,D/btif_config( 2365): btif_get_device_type: Device [7c:f9:0e:37:96:ab] type 1
,I/BluetoothBondStateMachine( 2365): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:37:96:AB newState: 1
,E/bt-btif ( 2365): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2365): Bond State Change Intent:7C:F9:0E:37:96:AB OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 2365): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2365): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:37:96:AB newState: 0
D/BluetoothAdapterProperties( 2365): Failed to remove device: 7C:F9:0E:37:96:AB
,I/BluetoothBondStateMachine( 2365): Bond State Change Intent:7C:F9:0E:37:96:AB OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2365): StableState(): Entering Off State
,W/bt-btif ( 2365): new conn_srvc id:26, app_id:255
W/bt-btif ( 2365): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 2365): bta_dm_pm_ssr:2, lat:1200
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3801): Incoming connection accepted
,D/HeadsetStateMachine( 2365): Disconnected process message: 10, size: 0
,D/btif_config_util( 2365): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 2365): invalid rfc slot id: 11
,W/bt-rfcomm( 2365): rfc_find_lcid_mcb LCID reused LCID:0x4d current:0x0
,W/bt-rfcomm( 2365): RFCOMM_DisconnectInd LCID:0x4d
,E/bt-btm  ( 2365): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2365): onReceive
,I/BTConnectionReceiver( 1506): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1506): Bluetooth Device Name: A5-1
,W/bt-btif ( 2365): info:x10
,D/        ( 2365): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1506): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1506): Bluetooth Device Name: A5-1
,W/bt-btif ( 2365): new conn_srvc id:26, app_id:255
W/bt-btif ( 2365): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 2365): bta_dm_pm_ssr:2, lat:1200
,D/btif_config_util( 2365): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 2365): info:x10
,D/        ( 2365): remote version info [f8:95:c7:87:85:54]: 6, f, 410d,
E/BluetoothRemoteDevices( 2365): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 2365): tBTM_SEC_DEV:0xa2f42964 rs_disc_pending=0
,W/bt-btif ( 2365): bta_dm_check_av:0
W/bt-btif ( 2365): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2365): tBTM_SEC_DEV:0xa2f4279c rs_disc_pending=1,
W/bt-btif ( 2365): bta_dm_check_av:0
W/bt-btif ( 2365): btif_dm_cback : unhandled event (14)
,D/btif_config( 2365): btif_get_device_type: Device [f8:95:c7:87:85:54] type 1
,I/BluetoothBondStateMachine( 2365): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 1
E/bt-btif ( 2365): check_cod: remote_cod = 0x5a020c
I/BluetoothBondStateMachine( 2365): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2365): Entering PendingCommandState State,
,I/BluetoothBondStateMachine( 2365): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 0
,D/BluetoothAdapterProperties( 2365): Failed to remove device: F8:95:C7:87:85:54
,I/BluetoothBondStateMachine( 2365): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2365): StableState(): Entering Off State
,W/bt-btif ( 2365): new conn_srvc id:26, app_id:255
W/bt-btif ( 2365): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2365): bta_dm_pm_ssr:2, lat:1200
,W/bt-btif ( 2365): invalid rfc slot id: 12
,E/bt-btm  ( 2365): tBTM_SEC_DEV:0xa2f42964 rs_disc_pending=1
,W/bt-btif ( 2365): bta_dm_check_av:0
W/bt-btif ( 2365): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 2365): rfc_find_lcid_mcb LCID reused LCID:0x4f current:0x0
,W/bt-rfcomm( 2365): RFCOMM_DisconnectInd LCID:0x4f
,V/GoogleAuthProtoRequest( 3862): [420] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1470): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1470): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1470): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1470): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1470): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3862): [420] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3862): [420] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3862): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3862): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3862): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3862): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3862): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3862): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3862): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3862): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3862): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3862): 	at com.a.a.k.run(SourceFile:110)
,E/bt-btm  ( 2365): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2365): onReceive
,I/BTConnectionReceiver( 1506): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1506): Bluetooth Device Name: A5-1
,D/btif_config_util( 2365): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/HeadsetStateMachine( 2365): Disconnected process message: 10, size: 0
,W/bt-btif ( 2365): invalid rfc slot id: 13
,W/bt-rfcomm( 2365): rfc_find_lcid_mcb LCID reused LCID:0x43 current:0x0
W/bt-rfcomm( 2365): RFCOMM_DisconnectInd LCID:0x43
,E/bt-btm  ( 2365): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2365): onReceive
,I/BTConnectionReceiver( 1506): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1506): Bluetooth Device Name: G3s-1
,D/HeadsetStateMachine( 2365): Disconnected process message: 10, size: 0
,W/bt-btif ( 2365): info:x10
,D/        ( 2365): remote version info [f8:95:c7:87:85:54]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1506): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1506): Bluetooth Device Name: G3s-1
,D/btif_config( 2365): btif_get_device_type: Device [f8:95:c7:87:85:54] type 1,
,I/BluetoothBondStateMachine( 2365): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 1
,E/bt-btif ( 2365): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2365): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 2365): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2365): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 0
D/BluetoothAdapterProperties( 2365): Failed to remove device: F8:95:C7:87:85:54
,I/BluetoothBondStateMachine( 2365): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2365): StableState(): Entering Off State
,W/bt-btif ( 2365): new conn_srvc id:26, app_id:255
,W/bt-btif ( 2365): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2365): bta_dm_pm_ssr:2, lat:1200
,D/btif_config_util( 2365): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 2365): invalid rfc slot id: 14
,W/bt-rfcomm( 2365): rfc_find_lcid_mcb LCID reused LCID:0x42 current:0x0
,W/bt-rfcomm( 2365): RFCOMM_DisconnectInd LCID:0x42
,W/bt-btif ( 2365): info:x10
,D/        ( 2365): remote version info [7c:f9:0e:37:96:ab]: 6, f, 410d
,I/BTConnectionReceiver( 1506): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1506): Bluetooth Device Name: A5-1,
,W/bt-btif ( 2365): new conn_srvc id:26, app_id:255
,W/bt-btif ( 2365): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2365): bta_dm_pm_ssr:2, lat:1200
,W/bt-btif ( 2365): invalid rfc slot id: 15
,W/bt-rfcomm( 2365): rfc_find_lcid_mcb LCID reused LCID:0x46 current:0x0
,W/bt-rfcomm( 2365): RFCOMM_DisconnectInd LCID:0x46
,E/bt-btm  ( 2365): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2365): onReceive
,I/BTConnectionReceiver( 1506): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1506): Bluetooth Device Name: G3s-1
,E/bt-btm  ( 2365): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2365): onReceive
,I/BTConnectionReceiver( 1506): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1506): Bluetooth Device Name: A5-1,
,D/btif_config_util( 2365): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 2365): info:x10
,D/        ( 2365): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,I/BTConnectionReceiver( 1506): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1506): Bluetooth Device Name: G3s-1
,D/btif_config( 2365): btif_get_device_type: Device [f8:95:c7:87:85:54] type 1
,I/BluetoothBondStateMachine( 2365): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 1,
E/bt-btif ( 2365): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2365): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 2365): Entering PendingCommandState State
,W/bt-btif ( 2365): info:x10
,D/        ( 2365): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3,
,I/BTConnectionReceiver( 1506): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1506): Bluetooth Device Name: A5-1
,I/BluetoothBondStateMachine( 2365): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 0
,D/BluetoothAdapterProperties( 2365): Failed to remove device: F8:95:C7:87:85:54,
,I/BluetoothBondStateMachine( 2365): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 11 NewState: 10,
,I/BluetoothBondStateMachine( 2365): StableState(): Entering Off State
,E/bt-btm  ( 2365): tBTM_SEC_DEV:0xa2f42964 rs_disc_pending=1
W/bt-btif ( 2365): bta_dm_check_av:0
,W/bt-btif ( 2365): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2365): new conn_srvc id:26, app_id:255
,W/bt-btif ( 2365): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2365): bta_dm_pm_ssr:2, lat:1200
,W/bt-btif ( 2365): new conn_srvc id:26, app_id:255
,W/bt-btif ( 2365): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2365): bta_dm_pm_ssr:2, lat:1200
,I/GLSUser ( 1470): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1470): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1470): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1470): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1470): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3512): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3512): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3512): 	at jdm.a(PG:82)
E/HttpOperation( 3512): 	at jcs.o(PG:406)
,E/HttpOperation( 3512): 	at jcn.a(PG:1379)
E/HttpOperation( 3512): 	at jcs.i(PG:143)
E/HttpOperation( 3512): 	at blb.a(PG:3937)
E/HttpOperation( 3512): 	at czp.a(PG:18188)
E/HttpOperation( 3512): 	at czp.a(PG:9081)
E/HttpOperation( 3512): 	at czq.run(PG:1686)
E/HttpOperation( 3512): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3512): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3512): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3512): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3512): ,	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3512): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3512): 	at jdj.a(PG:4091)
E/HttpOperation( 3512): 	at jdj.a(PG:1125)
E/HttpOperation( 3512): 	at jdm.a(PG:77)
E/HttpOperation( 3512): 	... 12 more,
E/HttpOperation( 3512): Caused by: faj: BadAuthentication
E/HttpOperation( 3512): 	at fal.a(PG:38)
E/HttpOperation( 3512): 	at jdj.a(PG:4089)
E/HttpOperation( 3512): 	... 14 more
,I/GLSUser ( 1470): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1470): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1470): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1470): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1470): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3512): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3512): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3512): 	at jdm.a(PG:82)
E/HttpOperation( 3512): 	at jcs.o(PG:406)
E/HttpOperation( 3512): 	at jcn.a(PG:1379)
E/HttpOperation( 3512): 	at jcs.i(PG:143)
E/HttpOperation( 3512): 	at hec.a(PG:42)
E/HttpOperation( 3512): 	at hee.a(PG:102)
E/HttpOperation( 3512): 	at czr.a(PG:65)
E/HttpOperation( 3512): 	at kka.a(PG:108)
E/HttpOperation( 3512): 	at czp.a(PG:19176)
E/HttpOperation( 3512): 	at czp.a(PG:9081)
E/HttpOperation( 3512): 	at czq.run(PG:1686)
E/HttpOperation( 3512): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3512): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3512): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3512): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3512): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3512): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3512): 	at jdj.a(PG:4091)
E/HttpOperation( 3512): 	at jdj.a(PG:1125)
E/HttpOperation( 3512): 	at jdm.a(PG:77)
E/HttpOperation( 3512): 	... 15 more
E/HttpOperation( 3512): Caused by: faj: BadAuthentication
E/HttpOperation( 3512): 	at fal.a(PG:38)
E/HttpOperation( 3512): 	at jdj.a(PG:4089)
E/HttpOperation( 3512): 	... 17 more
,E/ExperimentLoader( 3512): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3512): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3512): 	at jdm.a(PG:82)
E/ExperimentLoader( 3512): 	,at jcs.o(PG:406)
E/ExperimentLoader( 3512): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3512): 	at jcs.i(PG:143)
E/ExperimentLoader( 3512): 	at hec.a(PG:42)
E/ExperimentLoader( 3512): 	at hee.a(PG:102),
E/ExperimentLoader( 3512): 	at czr.a(PG:65)
,E/ExperimentLoader( 3512): 	at kka.a(PG:108)
E/ExperimentLoader( 3512): 	at czp.a(PG:19176)
E/ExperimentLoader( 3512): 	at czp.a(PG:9081)
E/ExperimentLoader( 3512): 	at czq.run(PG:1686)
E/ExperimentLoader( 3512): ,	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3512): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3512): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3512): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3512): ,	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3512): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3512): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3512): 	at jdj.a(PG:1125)
,E/ExperimentLoader( 3512): 	at jdm.a(PG:77)
E/ExperimentLoader( 3512): 	... 15 more
E/ExperimentLoader( 3512): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3512): 	at fal.a(PG:38)
E/ExperimentLoader( 3512): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3512): 	... 17 more
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 715390, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,D/btif_config_util( 2365): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/HeadsetStateMachine( 2365): Disconnected process message: 10, size: 0
,W/bt-btif ( 2365): invalid rfc slot id: 16
,E/bt-btm  ( 2365): tBTM_SEC_DEV:0xa2f4279c rs_disc_pending=0
,W/bt-btif ( 2365): bta_dm_check_av:0
W/bt-btif ( 2365): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 2365): rfc_find_lcid_mcb LCID reused LCID:0x49 current:0x0
,W/bt-rfcomm( 2365): RFCOMM_DisconnectInd LCID:0x49
,W/bt-btif ( 2365): invalid rfc slot id: 17
,E/bt-btm  ( 2365): tBTM_SEC_DEV:0xa2f4279c rs_disc_pending=1
,W/bt-btif ( 2365): bta_dm_check_av:0
W/bt-btif ( 2365): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 2365): rfc_find_lcid_mcb LCID reused LCID:0x4a current:0x0
,W/bt-rfcomm( 2365): RFCOMM_DisconnectInd LCID:0x4a
,E/bt-btm  ( 2365): tBTM_SEC_DEV:0xa2f4279c rs_disc_pending=0
,W/bt-btif ( 2365): bta_dm_check_av:0
W/bt-btif ( 2365): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2365): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2365): onReceive
,I/BTConnectionReceiver( 1506): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1506): Bluetooth Device Name: A5-1
,E/bt-btm  ( 2365): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2365): onReceive
,I/BTConnectionReceiver( 1506): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1506): Bluetooth Device Name: G3s-1,
,W/bt-btif ( 2365): info:x10
D/        ( 2365): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,I/BTConnectionReceiver( 1506): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1506): Bluetooth Device Name: G3s-1
,D/btif_config( 2365): btif_get_device_type: Device [f8:95:c7:87:85:54] type 1
,I/BluetoothBondStateMachine( 2365): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 1
,E/bt-btif ( 2365): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2365): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 2365): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2365): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 0
D/BluetoothAdapterProperties( 2365): Failed to remove device: F8:95:C7:87:85:54
,I/BluetoothBondStateMachine( 2365): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2365): StableState(): Entering Off State
,W/bt-btif ( 2365): new conn_srvc id:26, app_id:255
,W/bt-btif ( 2365): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2365): bta_dm_pm_ssr:2, lat:1200
,I/BooksSync( 3707): Starting books sync for 61035162, extras: ade
,V/KeepSync( 3744): Connecting to GoogleApiClient,
,I/BooksConfig( 3707): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1470): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1470): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1470): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1470): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1470): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1470): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1470): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1470): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1470): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1470): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,V/KeepSync( 3744): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3744): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3744): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3744): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1470): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1470): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1470): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1470): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1470): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3707): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3707): Soft error
E/BooksSync( 3707): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3707): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3707): Sync error
E/BooksSync( 3707): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3707): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3707): Finished books sync
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 736738, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1470): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1470): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1470): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1470): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1470): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3744): IOException
E/KeepSync( 3744): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3744): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3744): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3744): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3744): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3744): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3744): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3744): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3744): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3744): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3744): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3744): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3744): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3744): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3744): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3744): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3744): 	... 10 more
W/KeepSync( 3744): Sync result 2
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 724326, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,D/btif_config_util( 2365): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 2365): invalid rfc slot id: 18
,W/bt-rfcomm( 2365): rfc_find_lcid_mcb LCID reused LCID:0x4c current:0x0
W/bt-rfcomm( 2365): RFCOMM_DisconnectInd LCID:0x4c
,E/bt-btm  ( 2365): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2365): onReceive
,I/BTConnectionReceiver( 1506): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1506): Bluetooth Device Name: G3s-1
,W/bt-btif ( 2365): info:x10
D/        ( 2365): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,I/BTConnectionReceiver( 1506): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1506): Bluetooth Device Name: G3s-1
,D/btif_config( 2365): btif_get_device_type: Device [f8:95:c7:87:85:54] type 1
,I/BluetoothBondStateMachine( 2365): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 1
E/bt-btif ( 2365): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2365): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 2365): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2365): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 0
D/BluetoothAdapterProperties( 2365): Failed to remove device: F8:95:C7:87:85:54
,I/BluetoothBondStateMachine( 2365): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2365): StableState(): Entering Off State
,W/bt-btif ( 2365): new conn_srvc id:26, app_id:255
,W/bt-btif ( 2365): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2365): bta_dm_pm_ssr:2, lat:1200
,I/art     (  821): Explicit concurrent mark sweep GC freed 37552(1735KB) AllocSpace objects, 6(284KB) LOS objects, 31% free, 34MB/50MB, paused 1.697ms total 77.252ms
,I/GLSUser ( 1470): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1470): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1470): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1470): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1470): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3512): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3512): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3512): 	at jdm.a(PG:82)
E/HttpOperation( 3512): 	at jcs.o(PG:406)
E/HttpOperation( 3512): 	at jcn.a(PG:1379)
E/HttpOperation( 3512): 	at jcs.i(PG:143)
E/HttpOperation( 3512): 	at blb.a(PG:3937)
E/HttpOperation( 3512): 	at czp.a(PG:18188)
E/HttpOperation( 3512): 	at czp.a(PG:9081)
E/HttpOperation( 3512): 	at czq.run(PG:1686)
E/HttpOperation( 3512): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3512): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3512): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3512): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3512): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3512): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3512): 	at jdj.a(PG:4091)
E/HttpOperation( 3512): 	at jdj.a(PG:1125)
E/HttpOperation( 3512): 	at jdm.a(PG:77)
E/HttpOperation( 3512): 	... 12 more
E/HttpOperation( 3512): Caused by: faj: BadAuthentication
E/HttpOperation( 3512): 	at fal.a(PG:38)
E/HttpOperation( 3512): 	at jdj.a(PG:4089)
E/HttpOperation( 3512): 	... 14 more
,I/GLSUser ( 1470): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1470): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1470): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1470): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1470): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3512): [getmobileexperiments] Unexpected exception,
E/HttpOperation( 3512): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3512): 	at jdm.a(PG:82)
E/HttpOperation( 3512): 	at jcs.o(PG:406)
E/HttpOperation( 3512): 	at jcn.a(PG:1379)
,E/HttpOperation( 3512): 	at jcs.i(PG:143)
E/HttpOperation( 3512): 	at hec.a(PG:42)
E/HttpOperation( 3512): 	at hee.a(PG:102)
E/HttpOperation( 3512): 	at czr.a(PG:65)
E/HttpOperation( 3512): 	,at kka.a(PG:108)
E/HttpOperation( 3512): 	at czp.a(PG:19176)
E/HttpOperation( 3512): 	at czp.a(PG:9081)
E/HttpOperation( 3512): 	at czq.run(PG:1686)
E/HttpOperation( 3512): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3512): 	,at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3512): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3512): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3512): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3512): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3512): 	at jdj.a(PG:4091)
E/HttpOperation( 3512): 	at jdj.a(PG:1125)
E/HttpOperation( 3512): 	at jdm.a(PG:77)
E/HttpOperation( 3512): 	... 15 more
E/HttpOperation( 3512): Caused by: faj: BadAuthentication
E/HttpOperation( 3512): 	at fal.a(PG:38)
E/HttpOperation( 3512): 	at jdj.a(PG:4089)
E/HttpOperation( 3512): 	... 17 more
,E/ExperimentLoader( 3512): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3512): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3512): 	,at jdm.a(PG:82)
E/ExperimentLoader( 3512): 	at jcs.o(PG:406)
E/ExperimentLoader( 3512): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3512): 	,at jcs.i(PG:143)
E/ExperimentLoader( 3512): 	at hec.a(PG:42)
E/ExperimentLoader( 3512): 	at hee.a(PG:102)
E/ExperimentLoader( 3512): 	at czr.a(PG:65),
E/ExperimentLoader( 3512): 	at kka.a(PG:108)
E/ExperimentLoader( 3512): 	at czp.a(PG:19176)
E/ExperimentLoader( 3512): 	at czp.a(PG:9081)
E/ExperimentLoader( 3512): 	at czq.run(PG:1686)
E/ExperimentLoader( 3512): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3512): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3512): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3512): 	,at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3512): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3512): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3512): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3512): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3512): 	at jdm.a(PG:77)
E/ExperimentLoader( 3512): 	... 15 more,
E/ExperimentLoader( 3512): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3512): 	at fal.a(PG:38)
E/ExperimentLoader( 3512): 	at jdj.a(PG:4089)
,E/ExperimentLoader( 3512): 	... 17 more
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 746135, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,D/btif_config_util( 2365): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 2365): invalid rfc slot id: 19
,W/bt-rfcomm( 2365): rfc_find_lcid_mcb LCID reused LCID:0x4e current:0x0
W/bt-rfcomm( 2365): RFCOMM_DisconnectInd LCID:0x4e
,E/bt-btm  ( 2365): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2365): onReceive
,I/BTConnectionReceiver( 1506): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
I/BluetoothClassifier( 1506): Bluetooth Device Name: G3s-1
,D/HeadsetStateMachine( 2365): Disconnected process message: 10, size: 0
,I/BooksSync( 3707): Starting books sync for 61035162, extras: ade
,V/KeepSync( 3744): Connecting to GoogleApiClient
,I/BooksConfig( 3707): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1470): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1470): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1470): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1470): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1470): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1470): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1470): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1470): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1470): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1470): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1772): Handling authorization failure
,E/ClientConnectionOperation( 1772): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1772): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1772): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1772): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1772): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62),
E/ClientConnectionOperation( 1772): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1772): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1772): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1772): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1772): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1772): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1772): ,	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1772): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1772): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1772): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1772): 	at com.google.android.gms.common.server.o.b(SourceFile:30),
E/ClientConnectionOperation( 1772): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1772): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1772): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1772): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1772): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1772): 	... 7 more,
V/KeepSync( 3744): GoogleApiClient failed to connect with error code: 4
E/SQLiteLog( 3744): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3744): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3744): (284) automatic index on blob_node(is_deleted)
,I/art     ( 1470): Explicit concurrent mark sweep GC freed 53869(2MB) AllocSpace objects, 11(1213KB) LOS objects, 36% free, 27MB/43MB, paused 2.467ms total 44.817ms
,I/GLSUser ( 1470): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1470): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1470): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1470): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1470): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive,
I/GLSUser ( 1470): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1470): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1470): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1470): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1470): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3707): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3707): Soft error
E/BooksSync( 3707): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3707): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3707): Sync error,
E/BooksSync( 3707): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3707): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3707): Finished books sync
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 777362, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,E/KeepSync( 3744): IOException
E/KeepSync( 3744): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3744): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3744): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3744): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3744): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3744): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3744): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3744): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3744): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3744): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3744): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3744): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3744): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3744): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3744): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3744): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3744): 	... 10 more
W/KeepSync( 3744): Sync result 2
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 776615, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1470): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1470): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1470): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1470): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1470): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3512): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3512): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3512): 	at jdm.a(PG:82)
E/HttpOperation( 3512): 	at jcs.o(PG:406)
E/HttpOperation( 3512): 	at jcn.a(PG:1379)
E/HttpOperation( 3512): 	at jcs.i(PG:143)
E/HttpOperation( 3512): 	at blb.a(PG:3937)
E/HttpOperation( 3512): 	at czp.a(PG:18188)
E/HttpOperation( 3512): 	at czp.a(PG:9081)
E/HttpOperation( 3512): 	at czq.run(PG:1686)
E/HttpOperation( 3512): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3512): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3512): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3512): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3512): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3512): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3512): 	at jdj.a(PG:4091)
E/HttpOperation( 3512): 	at jdj.a(PG:1125)
E/HttpOperation( 3512): 	at jdm.a(PG:77)
E/HttpOperation( 3512): 	... 12 more
E/HttpOperation( 3512): Caused by: faj: BadAuthentication
E/HttpOperation( 3512): 	at fal.a(PG:38)
E/HttpOperation( 3512): 	at jdj.a(PG:4089)
E/HttpOperation( 3512): 	... 14 more
,I/GLSUser ( 1470): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1470): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1470): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1470): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1470): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3512): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3512): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3512): 	at jdm.a(PG:82)
E/HttpOperation( 3512): 	at jcs.o(PG:406)
E/HttpOperation( 3512): 	at jcn.a(PG:1379)
E/HttpOperation( 3512): 	at jcs.i(PG:143)
E/HttpOperation( 3512): 	at hec.a(PG:42)
E/HttpOperation( 3512): 	at hee.a(PG:102)
E/HttpOperation( 3512): 	at czr.a(PG:65)
E/HttpOperation( 3512): 	at kka.a(PG:108)
E/HttpOperation( 3512): 	at czp.a(PG:19176)
E/HttpOperation( 3512): 	at czp.a(PG:9081)
E/HttpOperation( 3512): 	at czq.run(PG:1686)
E/HttpOperation( 3512): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3512): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3512): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3512): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3512): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3512): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3512): 	at jdj.a(PG:4091)
E/HttpOperation( 3512): 	at jdj.a(PG:1125)
E/HttpOperation( 3512): 	at jdm.a(PG:77)
E/HttpOperation( 3512): 	... 15 more
E/HttpOperation( 3512): Caused by: faj: BadAuthentication
E/HttpOperation( 3512): 	at fal.a(PG:38)
E/HttpOperation( 3512): 	at jdj.a(PG:4089)
E/HttpOperation( 3512): 	... 17 more
,E/ExperimentLoader( 3512): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3512): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3512): 	at jdm.a(PG:82)
E/ExperimentLoader( 3512): 	at jcs.o(PG:406)
E/ExperimentLoader( 3512): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3512): 	at jcs.i(PG:143)
E/ExperimentLoader( 3512): 	at hec.a(PG:42)
E/ExperimentLoader( 3512): 	at hee.a(PG:102)
E/ExperimentLoader( 3512): 	at czr.a(PG:65)
E/ExperimentLoader( 3512): 	at kka.a(PG:108)
E/ExperimentLoader( 3512): 	at czp.a(PG:19176)
E/ExperimentLoader( 3512): 	at czp.a(PG:9081)
E/ExperimentLoader( 3512): 	at czq.run(PG:1686)
E/ExperimentLoader( 3512): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3512): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3512): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3512): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3512): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3512): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3512): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3512): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3512): 	at jdm.a(PG:77)
E/ExperimentLoader( 3512): 	... 15 more
E/ExperimentLoader( 3512): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3512): 	at fal.a(PG:38)
E/ExperimentLoader( 3512): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3512): 	... 17 more
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 836471, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,I/BooksSync( 3707): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3707): GmsCore Version = 7.8.99 (2134222-430)
,V/KeepSync( 3744): Connecting to GoogleApiClient
,I/GLSUser ( 1470): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1470): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1470): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1470): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1470): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1470): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1470): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1470): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1470): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1470): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,V/KeepSync( 3744): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3744): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3744): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3744): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1470): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1470): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1470): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1470): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1470): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3707): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3707): Soft error
E/BooksSync( 3707): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3707): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3707): Sync error
E/BooksSync( 3707): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3707): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3707): Finished books sync
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 869129, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/art     (  821): Explicit concurrent mark sweep GC freed 34290(1464KB) AllocSpace objects, 9(426KB) LOS objects, 31% free, 34MB/50MB, paused 2.133ms total 139.730ms
,I/GLSUser ( 1470): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1470): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1470): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1470): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1470): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3744): IOException
E/KeepSync( 3744): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3744): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3744): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3744): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3744): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3744): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3744): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3744): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3744): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3744): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3744): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3744): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3744): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3744): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3744): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3744): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3744): 	... 10 more
W/KeepSync( 3744): Sync result 2
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 867478, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2365): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2365): Disconnected process message: 10, size: 0
,V/GoogleAuthProtoRequest( 3862): [421] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1470): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1470): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1470): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1470): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1470): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/ExperimentUpdateService( 3862): [421] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.,
W/ExperimentUpdateService( 3862): [421] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3862): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3862): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3862): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3862): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3862): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3862): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3862): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3862): 	,at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3862): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3862): 	at com.a.a.k.run(SourceFile:110)
,D/HeadsetStateMachine( 2365): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2365): Disconnected process message: 10, size: 0
,V/GoogleAuthProtoRequest( 3862): [422] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1470): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1470): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1470): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1470): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1470): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3862): [422] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3862): [422] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3862): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3862): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3862): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3862): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3862): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3862): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3862): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3862): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3862): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3862): 	at com.a.a.k.run(SourceFile:110)
,I/GLSUser ( 1470): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1470): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1470): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1470): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1470): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3512): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3512): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3512): 	at jdm.a(PG:82)
E/HttpOperation( 3512): 	at jcs.o(PG:406)
E/HttpOperation( 3512): 	at jcn.a(PG:1379)
E/HttpOperation( 3512): 	at jcs.i(PG:143)
E/HttpOperation( 3512): 	at blb.a(PG:3937)
E/HttpOperation( 3512): 	at czp.a(PG:18188)
E/HttpOperation( 3512): 	at czp.a(PG:9081)
E/HttpOperation( 3512): 	at czq.run(PG:1686)
E/HttpOperation( 3512): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3512): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3512): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3512): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3512): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3512): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3512): 	at jdj.a(PG:4091)
E/HttpOperation( 3512): 	,at jdj.a(PG:1125)
E/HttpOperation( 3512): 	at jdm.a(PG:77)
E/HttpOperation( 3512): 	... 12 more
E/HttpOperation( 3512): Caused by: faj: BadAuthentication
E/HttpOperation( 3512): 	at fal.a(PG:38)
E/HttpOperation( 3512): 	at jdj.a(PG:4089),
E/HttpOperation( 3512): 	... 14 more
,I/GLSUser ( 1470): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1470): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1470): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1470): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1470): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3512): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3512): java.io.IOException: Cannot obtain authentication token,
E/HttpOperation( 3512): 	at jdm.a(PG:82)
E/HttpOperation( 3512): 	at jcs.o(PG:406)
E/HttpOperation( 3512): 	,at jcn.a(PG:1379)
E/HttpOperation( 3512): 	at jcs.i(PG:143)
E/HttpOperation( 3512): 	at hec.a(PG:42)
E/HttpOperation( 3512): 	at hee.a(PG:102)
E/HttpOperation( 3512): 	at czr.a(PG:65)
E/HttpOperation( 3512): 	at kka.a(PG:108)
E/HttpOperation( 3512): 	at czp.a(PG:19176)
E/HttpOperation( 3512): ,	at czp.a(PG:9081)
E/HttpOperation( 3512): 	at czq.run(PG:1686)
E/HttpOperation( 3512): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3512): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
,E/HttpOperation( 3512): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3512): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3512): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3512): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3512): 	at jdj.a(PG:4091)
E/HttpOperation( 3512): 	at jdj.a(PG:1125)
E/HttpOperation( 3512): 	at jdm.a(PG:77)
E/HttpOperation( 3512): 	... 15 more
E/HttpOperation( 3512): Caused by: faj: BadAuthentication
E/HttpOperation( 3512): 	at fal.a(PG:38)
E/HttpOperation( 3512): 	at jdj.a(PG:4089)
E/HttpOperation( 3512): 	... 17 more
,E/ExperimentLoader( 3512): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3512): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3512): 	at jdm.a(PG:82)
E/ExperimentLoader( 3512): 	at jcs.o(PG:406)
E/ExperimentLoader( 3512): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3512): 	at jcs.i(PG:143)
E/ExperimentLoader( 3512): 	at hec.a(PG:42)
E/ExperimentLoader( 3512): 	at hee.a(PG:102)
E/ExperimentLoader( 3512): 	at czr.a(PG:65)
E/ExperimentLoader( 3512): 	at kka.a(PG:108)
E/ExperimentLoader( 3512): 	at czp.a(PG:19176)
E/ExperimentLoader( 3512): 	at czp.a(PG:9081)
E/ExperimentLoader( 3512): 	at czq.run(PG:1686)
E/ExperimentLoader( 3512): 	,at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3512): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3512): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3512): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3512): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3512): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3512): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3512): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3512): 	at jdm.a(PG:77)
E/ExperimentLoader( 3512): 	... 15 more
E/ExperimentLoader( 3512): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3512): 	at fal.a(PG:38)
E/ExperimentLoader( 3512): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3512): 	... 17 more,
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 987227, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2365): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2365): Disconnected process message: 10, size: 0
,I/BooksSync( 3707): Starting books sync for 61035162, extras: ade
,V/KeepSync( 3744): Connecting to GoogleApiClient
,I/BooksConfig( 3707): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1470): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1470): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1470): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1470): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1470): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1470): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1470): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1470): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1470): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1470): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,V/KeepSync( 3744): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3744): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3744): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3744): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1470): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1470): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1470): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1470): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1470): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3707): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3707): Soft error
E/BooksSync( 3707): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3707): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3707): Sync error
E/BooksSync( 3707): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3707): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3707): Finished books sync
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1022540, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1470): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1470): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1470): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1470): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1470): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/KeepSync( 3744): IOException
,E/KeepSync( 3744): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3744): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3744): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3744): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3744): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3744): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3744): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3744): 	,at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3744): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3744): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3744): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3744): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3744): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3744): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3744): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3744): ,	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3744): 	... 10 more
W/KeepSync( 3744): Sync result 2
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 1019396, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,I/art     ( 1470): Explicit concurrent mark sweep GC freed 58786(3MB) AllocSpace objects, 13(1433KB) LOS objects, 36% free, 27MB/43MB, paused 1.260ms total 60.421ms
,V/GoogleAuthProtoRequest( 3862): [423] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1470): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1470): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1470): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1470): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1470): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3862): [423] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3862): [423] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3862): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3862): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3862): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3862): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3862): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3862): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3862): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3862): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3862): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3862): 	at com.a.a.k.run(SourceFile:110)
,D/HeadsetStateMachine( 2365): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2365): Disconnected process message: 10, size: 0
,V/GoogleAuthProtoRequest( 3862): [424] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1470): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1470): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1470): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1470): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1470): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3862): [424] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3862): [424] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3862): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3862): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3862): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3862): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3862): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3862): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3862): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3862): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3862): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3862): 	at com.a.a.k.run(SourceFile:110)
,D/HeadsetStateMachine( 2365): Disconnected process message: 10, size: 0
,V/GoogleAuthProtoRequest( 3862): [425] a.<init>: mAccountName set to: thalitester@gmail.com
,I/art     (  821): Explicit concurrent mark sweep GC freed 35285(1591KB) AllocSpace objects, 9(426KB) LOS objects, 31% free, 34MB/50MB, paused 1.547ms total 69.692ms
,I/GLSUser ( 1470): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1470): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1470): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1470): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1470): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3862): [425] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.,
W/ExperimentUpdateService( 3862): [425] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3862): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3862): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3862): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3862): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3862): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3862): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3862): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3862): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3862): 	at com.a.a.a.a.a(SourceFile:93)
,W/ExperimentUpdateService( 3862): 	at com.a.a.k.run(SourceFile:110)
,D/HeadsetStateMachine( 2365): Disconnected process message: 10, size: 0
,I/UsageStatsService(  821): User[0] Flushing usage stats to disk
,I/GLSUser ( 1470): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1470): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1470): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1470): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1470): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3512): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3512): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3512): 	at jdm.a(PG:82)
E/HttpOperation( 3512): 	at jcs.o(PG:406)
E/HttpOperation( 3512): 	at jcn.a(PG:1379)
E/HttpOperation( 3512): 	at jcs.i(PG:143)
E/HttpOperation( 3512): 	at blb.a(PG:3937)
E/HttpOperation( 3512): 	at czp.a(PG:18188)
E/HttpOperation( 3512): 	at czp.a(PG:9081)
E/HttpOperation( 3512): 	at czq.run(PG:1686)
E/HttpOperation( 3512): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3512): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3512): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3512): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3512): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3512): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3512): 	at jdj.a(PG:4091)
E/HttpOperation( 3512): 	at jdj.a(PG:1125)
E/HttpOperation( 3512): 	at jdm.a(PG:77)
E/HttpOperation( 3512): 	... 12 more
E/HttpOperation( 3512): Caused by: faj: BadAuthentication
E/HttpOperation( 3512): 	at fal.a(PG:38)
E/HttpOperation( 3512): 	at jdj.a(PG:4089)
E/HttpOperation( 3512): 	... 14 more
,I/GLSUser ( 1470): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1470): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1470): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1470): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1470): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3512): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3512): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3512): 	at jdm.a(PG:82)
E/HttpOperation( 3512): 	at jcs.o(PG:406)
E/HttpOperation( 3512): 	at jcn.a(PG:1379)
E/HttpOperation( 3512): 	at jcs.i(PG:143)
E/HttpOperation( 3512): 	at hec.a(PG:42)
E/HttpOperation( 3512): 	at hee.a(PG:102)
E/HttpOperation( 3512): 	at czr.a(PG:65)
E/HttpOperation( 3512): 	at kka.a(PG:108)
E/HttpOperation( 3512): 	at czp.a(PG:19176)
E/HttpOperation( 3512): 	at czp.a(PG:9081)
E/HttpOperation( 3512): 	at czq.run(PG:1686)
E/HttpOperation( 3512): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3512): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3512): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3512): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3512): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3512): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3512): 	at jdj.a(PG:4091)
E/HttpOperation( 3512): 	at jdj.a(PG:1125)
E/HttpOperation( 3512): 	at jdm.a(PG:77)
E/HttpOperation( 3512): 	... 15 more
E/HttpOperation( 3512): Caused by: faj: BadAuthentication
E/HttpOperation( 3512): 	at fal.a(PG:38)
E/HttpOperation( 3512): 	at jdj.a(PG:4089)
E/HttpOperation( 3512): 	... 17 more
,E/ExperimentLoader( 3512): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3512): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3512): 	at jdm.a(PG:82)
E/ExperimentLoader( 3512): 	at jcs.o(PG:406)
E/ExperimentLoader( 3512): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3512): 	at jcs.i(PG:143)
E/ExperimentLoader( 3512): 	at hec.a(PG:42)
E/ExperimentLoader( 3512): 	at hee.a(PG:102)
E/ExperimentLoader( 3512): 	at czr.a(PG:65)
E/ExperimentLoader( 3512): 	at kka.a(PG:108)
E/ExperimentLoader( 3512): 	at czp.a(PG:19176)
,E/ExperimentLoader( 3512): 	at czp.a(PG:9081)
E/ExperimentLoader( 3512): 	at czq.run(PG:1686)
E/ExperimentLoader( 3512): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3512): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3512): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3512): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3512): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3512): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3512): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3512): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3512): 	at jdm.a(PG:77)
E/ExperimentLoader( 3512): 	... 15 more
E/ExperimentLoader( 3512): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3512): 	at fal.a(PG:38)
E/ExperimentLoader( 3512): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3512): 	... 17 more
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 1255828, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,D/WifiService(  821): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@1ab8279b}
,D/WifiService(  821): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@1ab8279b}
,D/HeadsetStateMachine( 2365): Disconnected process message: 10, size: 0
,I/BooksSync( 3707): Starting books sync for 61035162, extras: ade
,V/KeepSync( 3744): Connecting to GoogleApiClient
,I/BooksConfig( 3707): GmsCore Version = 7.8.99 (2134222-430)
,I/art     ( 3744): Explicit concurrent mark sweep GC freed 19588(2MB) AllocSpace objects, 0(0B) LOS objects, 24% free, 23MB/31MB, paused 800us total 56.323ms
,I/GLSUser ( 1470): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1470): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1470): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1470): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1470): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1470): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1470): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1470): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1470): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1470): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,V/KeepSync( 3744): GoogleApiClient failed to connect with error code: 4
E/SQLiteLog( 3744): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3744): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3744): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1470): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1470): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1470): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1470): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1470): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3707): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3707): Soft error
E/BooksSync( 3707): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3707): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3707): Sync error
E/BooksSync( 3707): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3707): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3707): Finished books sync
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1296591, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1470): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1470): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1470): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1470): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1470): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3744): IOException
E/KeepSync( 3744): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3744): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3744): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3744): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3744): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3744): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3744): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3744): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3744): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3744): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3744): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3744): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3744): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3744): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3744): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3744): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3744): 	... 10 more
W/KeepSync( 3744): Sync result 2
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 1289905, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2365): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2365): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2365): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2365): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2365): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2365): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2365): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2365): Disconnected process message: 10, size: 0
,W/bt-btm  ( 2365): Request to stop oneshot timer with non empty queue
,V/GoogleAuthProtoRequest( 3862): [426] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1470): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1470): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1470): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1470): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1470): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3862): [426] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3862): [426] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3862): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3862): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3862): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3862): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3862): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3862): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3862): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3862): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3862): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3862): 	at com.a.a.k.run(SourceFile:110)
,D/GCM     ( 1470): Message class com.google.f.a.a.i
,D/HeadsetStateMachine( 2365): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2365): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2365): Disconnected process message: 10, size: 0
,I/art     ( 1470): Explicit concurrent mark sweep GC freed 63883(3MB) AllocSpace objects, 12(1323KB) LOS objects, 37% free, 27MB/43MB, paused 1.544ms total 46.101ms
,D/HeadsetStateMachine( 2365): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2365): Disconnected process message: 10, size: 0
,I/art     (  821): Explicit concurrent mark sweep GC freed 41667(1945KB) AllocSpace objects, 11(458KB) LOS objects, 31% free, 34MB/50MB, paused 1.874ms total 86.073ms
,I/GLSUser ( 1470): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1470): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1470): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1470): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1470): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3512): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3512): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3512): 	at jdm.a(PG:82)
E/HttpOperation( 3512): 	at jcs.o(PG:406)
E/HttpOperation( 3512): 	at jcn.a(PG:1379)
E/HttpOperation( 3512): 	at jcs.i(PG:143)
E/HttpOperation( 3512): 	at blb.a(PG:3937)
E/HttpOperation( 3512): 	at czp.a(PG:18188)
E/HttpOperation( 3512): 	at czp.a(PG:9081)
E/HttpOperation( 3512): 	at czq.run(PG:1686)
E/HttpOperation( 3512): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3512): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3512): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3512): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3512): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3512): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3512): 	at jdj.a(PG:4091)
E/HttpOperation( 3512): 	at jdj.a(PG:1125)
E/HttpOperation( 3512): 	at jdm.a(PG:77)
E/HttpOperation( 3512): 	... 12 more
E/HttpOperation( 3512): Caused by: faj: BadAuthentication
E/HttpOperation( 3512): 	at fal.a(PG:38)
E/HttpOperation( 3512): 	at jdj.a(PG:4089)
E/HttpOperation( 3512): 	... 14 more
,I/GLSUser ( 1470): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1470): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1470): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1470): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1470): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3512): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3512): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3512): 	at jdm.a(PG:82)
E/HttpOperation( 3512): 	at jcs.o(PG:406)
E/HttpOperation( 3512): 	at jcn.a(PG:1379)
E/HttpOperation( 3512): 	at jcs.i(PG:143)
E/HttpOperation( 3512): 	at hec.a(PG:42)
E/HttpOperation( 3512): 	at hee.a(PG:102)
E/HttpOperation( 3512): 	at czr.a(PG:65)
E/HttpOperation( 3512): 	at kka.a(PG:108)
E/HttpOperation( 3512): 	at czp.a(PG:19176)
E/HttpOperation( 3512): 	at czp.a(PG:9081)
E/HttpOperation( 3512): 	at czq.run(PG:1686)
E/HttpOperation( 3512): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3512): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3512): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3512): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3512): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3512): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3512): 	at jdj.a(PG:4091)
E/HttpOperation( 3512): 	at jdj.a(PG:1125)
E/HttpOperation( 3512): 	at jdm.a(PG:77)
E/HttpOperation( 3512): 	... 15 more
E/HttpOperation( 3512): Caused by: faj: BadAuthentication
E/HttpOperation( 3512): 	at fal.a(PG:38)
E/HttpOperation( 3512): 	at jdj.a(PG:4089)
E/HttpOperation( 3512): 	... 17 more
,E/ExperimentLoader( 3512): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3512): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3512): 	at jdm.a(PG:82)
E/ExperimentLoader( 3512): 	at jcs.o(PG:406)
E/ExperimentLoader( 3512): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3512): 	at jcs.i(PG:143)
E/ExperimentLoader( 3512): 	at hec.a(PG:42)
E/ExperimentLoader( 3512): 	at hee.a(PG:102)
,E/ExperimentLoader( 3512): 	at czr.a(PG:65)
E/ExperimentLoader( 3512): 	at kka.a(PG:108)
E/ExperimentLoader( 3512): 	at czp.a(PG:19176)
E/ExperimentLoader( 3512): 	at czp.a(PG:9081)
,E/ExperimentLoader( 3512): 	at czq.run(PG:1686)
E/ExperimentLoader( 3512): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3512): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3512): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112),
E/ExperimentLoader( 3512): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3512): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3512): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3512): 	at jdj.a(PG:4091)
,E/ExperimentLoader( 3512): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3512): 	at jdm.a(PG:77)
E/ExperimentLoader( 3512): 	... 15 more
E/ExperimentLoader( 3512): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3512): ,	at fal.a(PG:38)
E/ExperimentLoader( 3512): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3512): 	... 17 more
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 1740734, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2365): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2365): Disconnected process message: 10, size: 0
,V/KeepSync( 3744): Connecting to GoogleApiClient
,I/GLSUser ( 1470): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1470): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1470): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1470): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1470): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,V/KeepSync( 3744): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3744): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3744): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3744): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1470): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1470): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1470): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1470): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1470): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3744): IOException
E/KeepSync( 3744): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3744): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3744): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3744): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3744): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3744): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3744): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3744): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3744): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3744): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3744): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3744): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3744): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3744): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3744): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3744): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3744): 	... 10 more
W/KeepSync( 3744): Sync result 2
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 1809154, reason: 10079, SyncResult: stats [ numIoExceptions: 1],
,I/ProcessStatsService(  821): Prepared write state in 7ms
,I/ProcessStatsService(  821): Pruning old procstats: /data/system/procstats/state-2015-12-16-20-30-51.bin
,D/HeadsetStateMachine( 2365): Disconnected process message: 10, size: 0
,I/BooksSync( 3707): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3707): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1470): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1470): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1470): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1470): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1470): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1470): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1470): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1470): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1470): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1470): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3707): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3707): Soft error
E/BooksSync( 3707): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3707): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3707): Sync error
E/BooksSync( 3707): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3707): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3707): Finished books sync
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1822553, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2365): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2365): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2365): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2365): Disconnected process message: 10, size: 0
,TIME-OUT KILL (timeout was 1800000ms)
```
