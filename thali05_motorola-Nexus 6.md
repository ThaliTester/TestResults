#### Test 50650278e989a4f_thali05_motorola-Nexus 6 Logs


```
--------- beginning of main
E/WifiStateMachine(  823): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=2.52 targetRoamBSSID=any RSSI=-48
E/WifiStateMachine(  823): WifiStateMachine starting scan for "NG7005g"WPA_PSK with 2412,5220
,D/AndroidRuntime( 3591): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 3591): CheckJNI is OFF
D/AndroidRuntime( 3591): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  823): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/WindowManager(  823): addAppToken: AppWindowToken{26fa38ae token=Token{8f5bd29 ActivityRecord{2ab0eab0 u0 com.test.thalitest/.MainActivity t26}}} to stack=1 task=26 at 0
V/WindowManager(  823): Adding window Window{16a9086b u0 Starting com.test.thalitest} at 2 of 7 (after Window{21793042 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
I/MicrophoneInputStream( 1524): mic_close com.google.android.apps.gsa.speech.audio.u@2db14a58
I/HotwordDetector( 1524): Closing mic
D/AndroidRuntime( 3591): Shutting down VM
D/audio_hw_primary(  358): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  358): disable_snd_device: snd_device(55: voice-rec-mic)
I/ActivityManager(  823): Start proc 3606:com.test.thalitest/u0a265 for activity com.test.thalitest/.MainActivity
I/SoundTriggerHwService::Module(  358): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1524): Hotword detection finished
I/HotwordRecognitionRnr( 1524): Stopping hotword detection.
I/ActivityManager(  823): Killing 2972:com.google.android.deskclock/u0a44 (adj 15): empty #17
,I/ActivityManager(  823): Killing 2708:com.google.android.apps.maps/u0a65 (adj 15): empty #18
,I/WebViewFactory( 3606): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3606): Time to load native libraries: 4 ms (timestamps 2672-2676)
I/LibraryLoader( 3606): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3606): Binding Chromium to main looper Looper (main, tid 1) {11b7cb53}
,I/LibraryLoader( 3606): Expected native library version number "",actual native library version number ""
I/chromium( 3606): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,E/LocSvc_IzatApiV02(  823): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1660106003
,E/LocSvc_IzatApiV02(  823): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,I/BrowserStartupController( 3606): Initializing chromium process, singleProcess=true
,W/art     ( 3606): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3606): ApplicationContext is null in ApplicationStatus
,W/chromium( 3606): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3606): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 3606): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3606): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,I/kickstart(  873): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
,I/kickstart(  873): STATUS: Wrote to /sys/power/wake_lock
,D/BluetoothManagerService(  823): Message: 20
D/BluetoothManagerService(  823): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1c0e25b:true
,E/kickstart(  873): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1
,I/kickstart(  873): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1' for writing
,W/art     ( 3606): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3606): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3606): CordovaWebView is running on device made by: motorola
,W/art     ( 3606): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 3606): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3606): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,D/Atlas   ( 3606): Validating map...
,V/WindowManager(  823): Adding window Window{203b184b u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{16a9086b u0 Starting com.test.thalitest})
,W/chromium( 3606): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3606): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3606): Enabling debug mode 0
,I/ActivityManager(  823): Displayed com.test.thalitest/.MainActivity: +922ms
,I/Keyboard.Facilitator( 1243): onFinishInput()
,W/BindingManager( 3606): Cannot call determinedVisibility() - never saw a connection for the pid: 3606
,D/JsMessageQueue( 3606): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3606): JniHelper::setJavaVM(0xb489d200), pthread_self() = -1576266880
D/JX-Cordova( 3606): jxcore cordova android initializing
,I/kickstart(  873): STATUS: Received file 'm9kefs1'
I/kickstart(  873): STATUS: 950272 bytes transferred in 1.000989 seconds
I/kickstart(  873): STATUS: Successfully downloaded files from target 
I/kickstart(  873): STATUS: Wrote to /sys/power/wake_unlock
,I/kickstart(  873): STATUS: Sahara protocol completed
,W/jxcore-log( 3606): Initializing JXcore engine
W/jxcore-log( 3606): JXcore engine is ready
,W/jxcore-log( 3606): Starting JXcore engine
,W/.test.thalitest( 3606): type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[12746]" dev="sockfs" ino=12746 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 3606): type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,W/.test.thalitest( 3606): type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[12807]" dev="sockfs" ino=12807 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/.test.thalitest( 3606): type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[20418]" dev="sockfs" ino=20418 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 3606): Platform android
W/jxcore-log( 3606): 
W/jxcore-log( 3606): Process ARCH arm
W/jxcore-log( 3606): 
,I/jxcore-log( 3606): JXcore Cordova bridge is ready!
I/jxcore-log( 3606): 
W/jxcore-log( 3606): JXcore engine is started
I/Choreographer( 3606): Skipped 137 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3606): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3606): Toggling radios to true
I/jxcore-log( 3606): 
,D/BluetoothAdapter( 3606): enable(): BT is already enabled..!
,D/WifiService(  823): New client listening to asynchronous messages
,D/WifiService(  823): setWifiEnabled: true pid=3606, uid=10265
,E/WifiService(  823): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3606): Radios toggled
I/jxcore-log( 3606): 
,D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/jxcore-log( 3606): Got Device Bluetooth address: F8:CF:C5:D9:E5:61
I/jxcore-log( 3606): 
,I/wpa_supplicant( 1197): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
I/jxcore-log( 3606): Perf Test app loaded loaded
I/jxcore-log( 3606): 
,E/WifiStateMachine(  823): WifiStateMachine: Leaving Connected state
I/jxcore-log( 3606): check test folder
I/jxcore-log( 3606): 
E/WifiConfigStore(  823): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,I/jxcore-log( 3606): found test : ./testFindPeers.js
I/jxcore-log( 3606): 
,D/CommandListener(  354): Clearing all IP addresses on wlan0
V/NativeCrypto( 1371): Read error: ssl=0xb4888600: I/O error during system call, Connection timed out
,D/ConnectivityService(  823): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  823): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,V/NativeCrypto( 1371): SSL shutdown failed: ssl=0xb4888600: I/O error during system call, Broken pipe
,D/ConnectivityService(  823): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10011
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  823): ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  823): DefaultState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  823): Forcing reevaluation
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  823): EvaluatingState{ when=-1ms what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  823): Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
,E/WifiStateMachine(  823): Start Disconnecting Watchdog 1
,E/WifiStateMachine(  823): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,I/jxcore-log( 3606): found test : ./testSendData.js
I/jxcore-log( 3606): 
,D/CommandListener(  354): Clearing all IP addresses on wlan0
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  823): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
,D/ConnectivityService(  823): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler( 1076): CM callback handler got msg 524292
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  823): OfflineState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  823): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  823): Disconnected - quitting
D/CSLegacyTypeTracker(  823): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,D/ConnectivityService(  823): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/WifiNetworkAgent(  823): NetworkAgent: NetworkAgent channel lost
D/ConnectivityService(  823): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  823): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  823): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering(  823): MasterInitialState.processMessage what=3
,E/WifiStateMachine(  823): CMD_AUTO_CONNECT sup state CompletedState my state DisconnectedState nid=0 roam=3
E/WifiStateMachine(  823): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=0
D/ConnectivityService(  823): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService(  823): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/ConnectivityService(  823): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
,I/NetworkMonitor( 3203): type=WIFI subType= reason=null isConnected=false
,D/Tethering(  823): MasterInitialState.processMessage what=3
,D/PhoneInterfaceManager( 1292): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1292): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
V/MusicLeanback( 3203): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/TelephonyManager(  823): getDataEnabled: retVal=false
,I/Choreographer( 3606): Skipped 76 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3606): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/ActivityManager(  823): Start proc 3670:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.steen.receiver.ConnectivityChangeReceiver
E/GpsLocationProvider(  823): No APN found to select.
,E/WifiConfigStore(  823): Setting BSSID for "NG7005g"WPA_PSK to any
,D/PhoneInterfaceManager( 1292): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1292): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
D/TelephonyManager(  823): getDataEnabled: retVal=false
E/WifiConfigStore(  823): will read network variables netId=0
,E/WifiStateMachine(  823): CMD_AUTO_CONNECT did save config ->  nid=0
,E/GpsLocationProvider(  823): No APN found to select.
,E/WifiConfigStore(  823): will read network variables netId=0
,I/ActivityManager(  823): Start proc 3696:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,I/ActivityManager(  823): Killing 3054:com.google.android.gm/u0a78 (adj 15): empty #17
,D/SprintDMReceiver( 3696): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3696): simOperator:  IMSI: null
,D/SprintDMReceiver( 3696): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1786): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1786): onCreate
,D/SystemUpdateService( 1786): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1786): active receiver: enabled
,I/SystemUpdateService( 1786): showing system update notification
,I/iu.Environment( 1786): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1786): num queued entries: 0
I/iu.UploadsManager( 1786): num updated entries: 0
I/iu.SyncManager( 1786): NEXT; no task
,D/ChimeraCfgMgr( 1786): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/ValidateNoPeople(  823): skipping global notification
,V/SystemUpdateService( 1786): retry (wakeup: false) in 3599965 ms
,I/ActivityManager(  823): Start proc 3721:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,D/SystemUpdateService( 1786): onDestroy
,I/art     (  369): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 338us total 16.295ms
,I/Babel   ( 2919): connection state changed from UNKNOWN to DISCONNECTED
,I/ActivityManager(  823): Killing 2289:com.google.android.calendar/u0a37 (adj 15): empty #17
,I/art     (  369): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 348us total 20.149ms
,I/art     (  369): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 328us total 14.491ms
,I/GAv4    ( 3721): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3721):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3721):   adb logcat -s GAv4
,W/GAv4    ( 3721): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3721): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.,
,W/GAv4    ( 3721): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/art     (  823): Explicit concurrent mark sweep GC freed 41848(2045KB) AllocSpace objects, 11(270KB) LOS objects, 32% free, 33MB/49MB, paused 1.524ms total 98.968ms
,I/WebViewFactory( 3721): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3721): Time to load native libraries: 1 ms (timestamps 8310-8311)
,I/LibraryLoader( 3721): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3721): Binding Chromium to main looper Looper (main, tid 1) {38fd2076}
,I/LibraryLoader( 3721): Expected native library version number "",actual native library version number ""
I/chromium( 3721): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3721): Initializing chromium process, singleProcess=true,
,W/art     ( 3721): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3721): ApplicationContext is null in ApplicationStatus
,W/chromium( 3721): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3721): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3721): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno  ( 3721): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,W/AudioManagerAndroid( 3721): Requires BLUETOOTH permission
I/NSApplication( 3721): Starting up...
,I/ActivityManager(  823): Start proc 3777:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,I/ActivityManager(  823): Killing 3178:com.android.providers.calendar/u0a3 (adj 15): empty #17
,I/wpa_supplicant( 1197): wlan0: Trying to associate with SSID 'NG7005g'
,I/ActivityManager(  823): Start proc 3798:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1371): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1371): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1371): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1371): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2994): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 2994): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 2994): [1] 5.onFinished: Scheduling replication attempt 3.
,I/ActivityManager(  823): Killing 3417:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,I/wpa_supplicant( 1197): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 1197): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 1197): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=0 id_str=]
,D/ConnectivityService(  823): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} }
,E/WifiConfigStore(  823): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  823): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,V/MusicLeanback( 3203): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
E/WifiConfigStore(  823): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  354): Setting iface cfg
,I/ActivityManager(  823): Killing 3438:com.android.musicfx/u0a18 (adj 15): empty #17
E/WifiStateMachine(  823): Start Dhcp Watchdog 2
,E/WifiStateMachine(  823):  WifiLinkLayerStats: 
E/WifiStateMachine(  823):  my bss beacon rx: 555
E/WifiStateMachine(  823):  RSSI mgmt: -48
E/WifiStateMachine(  823):  BE :  rx=213 tx=120 lost=0 retries=0
E/WifiStateMachine(  823):  BK :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  823):  VI :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  823):  VO :  rx=7 tx=0 lost=0 retries=0
E/WifiStateMachine(  823):  on_time : 15236 tx_time=283 rx_time=575 scan_time=0
,D/ConnectivityService(  823): updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,E/native  (  823): do suspend false
,E/WifiStateMachine(  823): scanCount==0 - aborting
,D/SprintDMReceiver( 3696): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3696): simOperator:  IMSI: null
,D/SprintDMReceiver( 3696): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1786): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1786): onCreate
,D/SystemUpdateService( 1786): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1786): active receiver: enabled
,I/SystemUpdateService( 1786): showing system update notification
,I/dhcpcd  ( 3817): version 5.5.6 starting
,I/ValidateNoPeople(  823): skipping global notification
,D/ChimeraCfgMgr( 1786): Loading module com.google.android.gms.kids from APK com.google.android.gms
,V/SystemUpdateService( 1786): retry (wakeup: false) in 3599935 ms
,D/SystemUpdateService( 1786): onDestroy
,I/dhcpcd  ( 3817): wlan0: rebinding lease of 192.168.1.122
,I/dhcpcd  ( 3817): wlan0: acknowledged 192.168.1.122 from 192.168.1.1
,I/dhcpcd  ( 3817): wlan0: leased 192.168.1.122 for 86400 seconds
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
D/ConnectivityService(  823): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  823):    accepting network in place of null
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  823): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  823): Connected
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  823): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  823): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
,D/ConnectivityService(  823): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} }
,D/ConnectivityService(  823): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/CSLegacyTypeTracker(  823): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  823): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 1076): CM callback handler got msg 524290
D/ConnectivityService(  823): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  823): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 3203): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 3203): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/SprintDMReceiver( 3696): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3696): simOperator:  IMSI: null
D/SprintDMReceiver( 3696): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1786): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1786): onCreate
,D/SystemUpdateService( 1786): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1786): active receiver: enabled
,I/SystemUpdateService( 1786): showing system update notification
,I/iu.Environment( 1786): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1786): num queued entries: 0
,I/iu.UploadsManager( 1786): num updated entries: 0
I/iu.SyncManager( 1786): NEXT; no task
,D/ChimeraCfgMgr( 1786): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/ValidateNoPeople(  823): skipping global notification
,D/ChimeraCfgMgr( 1786): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/PhoneInterfaceManager( 1292): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1292): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  823): getDataEnabled: retVal=false
,V/SystemUpdateService( 1786): retry (wakeup: false) in 3599976 ms
,D/SystemUpdateService( 1786): onDestroy
,E/GpsLocationProvider(  823): No APN found to select.
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  823): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 16 Dec 2015 02:31:43 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1450233103632], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1450233103610]}
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  823): Validated
,D/ConnectivityService(  823): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/ConnectivityService(  823): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  823): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  823): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  823): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  823): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1076): CM callback handler got msg 524290
,I/GLSUser ( 1371): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1371): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1371): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1371): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/Herrevad( 1786): NQAS connected
,I/Babel   ( 2919): connection state changed from DISCONNECTED to CONNECTED
,W/Kids    ( 1786): [AccountUtils] Account not ready
W/Kids    ( 1786): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 1786): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 1786): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 1786): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 1786): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 1786): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 1786): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 1786): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 1786): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 1786): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 1786): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 1786): 	at java.lang.Thread.run(Thread.java:818)
,D/GCM     ( 1371): Connected
,I/jxcore-log( 3606): BLE advertisement not supported: Bluetooth LE advertising is not supported
,I/jxcore-log( 3606): 
,D/GCM     ( 1371): Message class com.google.f.a.a.p
,D/ConnectivityService(  823): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,E/WifiStateMachine(  823): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=8.80 rxSuccessRate=10.22 targetRoamBSSID=any RSSI=-48
E/WifiStateMachine(  823): WifiStateMachine L2Connected CMD_START_SCAN source -2 10, 11 -> obsolete
,E/WifiStateMachine(  823): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=2.95 rxSuccessRate=4.80 targetRoamBSSID=any RSSI=-48
E/WifiStateMachine(  823): WifiStateMachine L2Connected CMD_START_SCAN source -2 9, 11 -> obsolete
,I/PowerManagerService(  823): Going to sleep due to screen timeout (uid 1000)...
,I/Adreno  (  823): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/PermissionCache(  259): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (233 us)
,I/DisplayManagerService(  823): Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
D/SurfaceFlinger(  259): Set power mode=0, type=0 flinger=0xb6082000
D/qdhwcomposer(  259): hwc_setPowerMode: Setting mode 0 on display: 0
,V/ActivityManager(  823): Display changed displayId=0
,I/qdhwcomposer(  259): handle_blank_event: dpy:0 panel power state: 0
,D/qdhwcomposer(  259): hwc_setPowerMode: Done setting mode 0 on display 0
D/SurfaceControl(  823): Excessive delay in setPowerMode(): 249ms
,I/DreamManagerService(  823): Entering dreamland.
,I/PowerManagerService(  823): Dozing...
I/DreamController(  823): Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,D/audio_hw_primary(  358): adev_set_parameters: enter: screen_state=on
D/mot_vr_audio_hw(  358): adev_set_parameters: screen_state=on
,E/WifiStateMachine(  823): cancelDelayedScan -> 12
,E/native  (  823): do suspend false
,I/Keyboard.Facilitator( 1243): onFinishInput()
,E/WifiStateMachine(  823): cancelDelayedScan -> 14
,E/native  (  823): do suspend true
,D/audio_hw_primary(  358): adev_set_parameters: enter: screen_state=off
,D/mot_vr_audio_hw(  358): adev_set_parameters: screen_state=off
,E/WifiStateMachine(  823): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-48
E/WifiStateMachine(  823): WifiStateMachine L2Connected CMD_START_SCAN source -2 13, 14 -> obsolete
,I/BooksSync( 3513): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3513): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1371): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1371): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1371): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1371): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1371): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1371): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1371): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1371): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3513): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3513): Soft error
E/BooksSync( 3513): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3513): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3513): Sync error
E/BooksSync( 3513): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3513): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3513): Finished books sync
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 168601, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1371): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1371): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1371): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1371): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  823): Explicit concurrent mark sweep GC freed 55074(2MB) AllocSpace objects, 8(222KB) LOS objects, 32% free, 33MB/49MB, paused 1.809ms total 82.846ms
,E/HttpOperation( 3317): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3317): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3317): 	at jdm.a(PG:82)
E/HttpOperation( 3317): 	at jcs.o(PG:406)
E/HttpOperation( 3317): 	at jcn.a(PG:1379)
E/HttpOperation( 3317): 	at jcs.i(PG:143)
E/HttpOperation( 3317): 	at blb.a(PG:3937)
E/HttpOperation( 3317): 	at czp.a(PG:18188)
E/HttpOperation( 3317): 	at czp.a(PG:9081)
E/HttpOperation( 3317): 	at czq.run(PG:1686)
E/HttpOperation( 3317): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3317): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3317): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3317): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3317): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3317): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3317): 	at jdj.a(PG:4091)
E/HttpOperation( 3317): 	at jdj.a(PG:1125)
E/HttpOperation( 3317): 	at jdm.a(PG:77)
E/HttpOperation( 3317): 	... 12 more
E/HttpOperation( 3317): Caused by: faj: BadAuthentication
E/HttpOperation( 3317): 	at fal.a(PG:38)
E/HttpOperation( 3317): 	at jdj.a(PG:4089)
E/HttpOperation( 3317): 	... 14 more
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1371): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1371): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1371): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1371): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1371): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure,
V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 1371): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1371): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1371): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/Finsky  ( 2994): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 2994): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 2994): [1] 5.onFinished: Scheduling replication attempt 4.
,E/HttpOperation( 3317): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3317): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3317): 	at jdm.a(PG:82)
E/HttpOperation( 3317): 	at jcs.o(PG:406)
E/HttpOperation( 3317): 	at jcn.a(PG:1379)
E/HttpOperation( 3317): 	at jcs.i(PG:143)
E/HttpOperation( 3317): 	at hec.a(PG:42)
E/HttpOperation( 3317): 	at hee.a(PG:102)
E/HttpOperation( 3317): 	at czr.a(PG:65)
E/HttpOperation( 3317): 	at kka.a(PG:108)
E/HttpOperation( 3317): 	at czp.a(PG:19176)
E/HttpOperation( 3317): 	at czp.a(PG:9081)
E/HttpOperation( 3317): 	at czq.run(PG:1686)
E/HttpOperation( 3317): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3317): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3317): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3317): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3317): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3317): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3317): 	at jdj.a(PG:4091)
E/HttpOperation( 3317): 	at jdj.a(PG:1125)
E/HttpOperation( 3317): 	at jdm.a(PG:77)
E/HttpOperation( 3317): 	... 15 more
E/HttpOperation( 3317): Caused by: faj: BadAuthentication
E/HttpOperation( 3317): 	at fal.a(PG:38)
E/HttpOperation( 3317): 	at jdj.a(PG:4089)
E/HttpOperation( 3317): 	... 17 more
,E/ExperimentLoader( 3317): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3317): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3317): 	at jdm.a(PG:82)
E/ExperimentLoader( 3317): 	at jcs.o(PG:406)
E/ExperimentLoader( 3317): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3317): 	at jcs.i(PG:143)
E/ExperimentLoader( 3317): 	at hec.a(PG:42)
,E/ExperimentLoader( 3317): 	at hee.a(PG:102)
E/ExperimentLoader( 3317): 	at czr.a(PG:65)
E/ExperimentLoader( 3317): 	at kka.a(PG:108)
E/ExperimentLoader( 3317): 	at czp.a(PG:19176)
E/ExperimentLoader( 3317): 	at czp.a(PG:9081)
E/ExperimentLoader( 3317): 	at czq.run(PG:1686)
E/ExperimentLoader( 3317): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3317): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3317): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3317): 	,at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3317): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3317): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3317): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3317): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3317): 	at jdm.a(PG:77)
E/ExperimentLoader( 3317): 	... 15 more
E/ExperimentLoader( 3317): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3317): 	at fal.a(PG:38)
E/ExperimentLoader( 3317): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3317): 	... 17 more
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 168944, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,E/WifiStateMachine(  823): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-48
,E/WifiStateMachine(  823): WifiStateMachine L2Connected CMD_START_SCAN source -2 11, 14 -> obsolete
,D/HeadsetStateMachine( 2379): Disconnected process message: 10, size: 0
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1371): Explicit concurrent mark sweep GC freed 34964(2MB) AllocSpace objects, 3(330KB) LOS objects, 37% free, 26MB/42MB, paused 1.674ms total 47.513ms
,I/VacuumService( 1371): Vacuum at: now=1450233130647 tag=VacuumService
,V/GoogleAuthProtoRequest( 3670): [385] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1371): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1371): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1371): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1371): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3670): [385] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3670): [385] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3670): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3670): 	at com.a.a.a.k.a(SourceFile:117)
,W/ExperimentUpdateService( 3670): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3670): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3670): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3670): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3670): 	,at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3670): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3670): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3670): 	,at com.a.a.k.run(SourceFile:110)
,I/GoogleURLConnFactory( 1371): Using platform SSLCertificateSocketFactory
,I/GLSUser ( 1371): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1371): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1371): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1371): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1371): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1371): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1371): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1371): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1371): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1371): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1371): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1371): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1371): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1371): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1371): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1371): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1371): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1371): No account for auth token provided
,W/Uploader( 1371): No account for auth token provided,
,W/Uploader( 1371): No account for auth token provided
,I/GLSUser ( 1371): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1371): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1371): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1371): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1371): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1371): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1371): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1371): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1371): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1371): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1371): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1371): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1371): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1371): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1371): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1371): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1371): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1371): No account for auth token provided
,W/Uploader( 1371): No account for auth token provided
,W/Uploader( 1371): No account for auth token provided,
,I/GLSUser ( 1371): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1371): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1371): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1371): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1371): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1371): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1371): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1371): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1371): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1371): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1371): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1371): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1371): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1371): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1371): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1371): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1371): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1371): No account for auth token provided
,W/Uploader( 1371): No account for auth token provided
,W/Uploader( 1371): No account for auth token provided
,W/Uploader( 1371): No account for auth token provided
,W/Uploader( 1371):  no longer exists, so no auth token.
,I/GLSUser ( 1371): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1371): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1371): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1371): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1371): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1371): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1371): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1371): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1371): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1371): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1371): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1371): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1371): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1371): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1371): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1371): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1371): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,D/HeadsetStateMachine( 2379): Disconnected process message: 10, size: 0
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1371): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1371): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1371): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1371): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/Finsky  ( 2994): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 2994): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 2994): [1] 5.onFinished: Scheduling replication attempt 5.
,V/KeepSync( 3547): Connecting to GoogleApiClient
,I/GLSUser ( 1371): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1371): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1371): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1371): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1786): Handling authorization failure
E/ClientConnectionOperation( 1786): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1786): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1786): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1786): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1786): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1786): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1786): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1786): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1786): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1786): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1786): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1786): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1786): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1786): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1786): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
,E/ClientConnectionOperation( 1786): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1786): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1786): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1786): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1786): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1786): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1786): 	... 7 more
,V/KeepSync( 3547): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3547): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3547): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3547): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1371): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1371): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1371): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1371): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3547): IOException
E/KeepSync( 3547): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3547): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3547): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3547): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3547): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3547): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3547): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3547): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3547): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3547): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3547): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3547): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3547): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3547): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3547): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3547): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3547): 	... 10 more
W/KeepSync( 3547): Sync result 2
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 171984, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,V/GoogleAuthProtoRequest( 3670): [386] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1371): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1371): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1371): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1371): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3670): [386] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3670): [386] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3670): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3670): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3670): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3670): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3670): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3670): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3670): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3670): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3670): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3670): 	at com.a.a.k.run(SourceFile:110)
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  823): Explicit concurrent mark sweep GC freed 30415(1352KB) AllocSpace objects, 4(252KB) LOS objects, 31% free, 34MB/50MB, paused 1.865ms total 94.370ms
,I/GLSUser ( 1371): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1371): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1371): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1371): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2994): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 2994): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 2994): [1] 5.onFinished: Giving up after 6 failures.
,I/Keyboard.Facilitator.LanguageModelFlusher( 1243): run()
I/Keyboard.Facilitator( 1243): flushDynamicLanguageModels()
,I/ConfigService( 1371): onCreate
,I/BooksSync( 3513): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3513): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1371): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1371): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1371): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1371): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1371): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1371): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1371): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1371): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3317): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3317): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3317): 	at jdm.a(PG:82)
E/HttpOperation( 3317): 	at jcs.o(PG:406)
E/HttpOperation( 3317): 	at jcn.a(PG:1379)
E/HttpOperation( 3317): 	at jcs.i(PG:143)
E/HttpOperation( 3317): 	at blb.a(PG:3937)
E/HttpOperation( 3317): 	at czp.a(PG:18188)
E/HttpOperation( 3317): 	at czp.a(PG:9081)
E/HttpOperation( 3317): 	at czq.run(PG:1686)
E/HttpOperation( 3317): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3317): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3317): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3317): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3317): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3317): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3317): 	at jdj.a(PG:4091)
E/HttpOperation( 3317): 	at jdj.a(PG:1125)
E/HttpOperation( 3317): 	at jdm.a(PG:77)
E/HttpOperation( 3317): 	... 12 more
E/HttpOperation( 3317): Caused by: faj: BadAuthentication
E/HttpOperation( 3317): 	at fal.a(PG:38)
E/HttpOperation( 3317): 	at jdj.a(PG:4089)
E/HttpOperation( 3317): 	... 14 more
,I/GLSUser ( 1371): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1371): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1371): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1371): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1371): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1371): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1371): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1371): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3317): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3317): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3317): 	at jdm.a(PG:82)
E/HttpOperation( 3317): 	at jcs.o(PG:406)
E/HttpOperation( 3317): 	at jcn.a(PG:1379)
E/HttpOperation( 3317): 	at jcs.i(PG:143)
E/HttpOperation( 3317): 	at hec.a(PG:42)
E/HttpOperation( 3317): 	at hee.a(PG:102)
E/HttpOperation( 3317): 	at czr.a(PG:65)
E/HttpOperation( 3317): 	at kka.a(PG:108)
E/HttpOperation( 3317): 	at czp.a(PG:19176)
E/HttpOperation( 3317): 	at czp.a(PG:9081)
E/HttpOperation( 3317): 	at czq.run(PG:1686)
E/HttpOperation( 3317): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3317): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3317): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3317): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3317): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3317): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3317): 	at jdj.a(PG:4091)
E/HttpOperation( 3317): 	at jdj.a(PG:1125)
E/HttpOperation( 3317): 	at jdm.a(PG:77)
E/HttpOperation( 3317): 	... 15 more
E/HttpOperation( 3317): Caused by: faj: BadAuthentication
E/HttpOperation( 3317): 	at fal.a(PG:38)
E/HttpOperation( 3317): 	at jdj.a(PG:4089)
E/HttpOperation( 3317): 	... 17 more
,E/ExperimentLoader( 3317): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3317): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3317): 	at jdm.a(PG:82)
E/ExperimentLoader( 3317): 	at jcs.o(PG:406)
E/ExperimentLoader( 3317): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3317): 	at jcs.i(PG:143)
E/ExperimentLoader( 3317): 	at hec.a(PG:42)
E/ExperimentLoader( 3317): 	at hee.a(PG:102)
E/ExperimentLoader( 3317): 	at czr.a(PG:65)
E/ExperimentLoader( 3317): 	at kka.a(PG:108)
E/ExperimentLoader( 3317): 	at czp.a(PG:19176)
E/ExperimentLoader( 3317): 	at czp.a(PG:9081)
E/ExperimentLoader( 3317): 	at czq.run(PG:1686)
E/ExperimentLoader( 3317): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3317): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3317): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3317): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3317): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3317): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3317): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3317): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3317): 	at jdm.a(PG:77)
E/ExperimentLoader( 3317): 	... 15 more
E/ExperimentLoader( 3317): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3317): 	at fal.a(PG:38)
E/ExperimentLoader( 3317): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3317): 	... 17 more
,E/BooksAccountManager( 3513): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3513): Soft error
E/BooksSync( 3513): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3513): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3513): Sync error
E/BooksSync( 3513): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3513): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3513): Finished books sync
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 199148, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 199953, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/ConfigService( 1371): onDestroy
,D/HeadsetStateMachine( 2379): Disconnected process message: 10, size: 0
,V/KeepSync( 3547): Connecting to GoogleApiClient
,I/art     ( 1371): Explicit concurrent mark sweep GC freed 68100(3MB) AllocSpace objects, 11(1060KB) LOS objects, 36% free, 27MB/43MB, paused 1.905ms total 59.035ms
,I/GLSUser ( 1371): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1371): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1371): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1371): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1786): Handling authorization failure
E/ClientConnectionOperation( 1786): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1786): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1786): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1786): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1786): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1786): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1786): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1786): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1786): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1786): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1786): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1786): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1786): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1786): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1786): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1786): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1786): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1786): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1786): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1786): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1786): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1786): 	... 7 more
,V/KeepSync( 3547): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3547): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3547): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3547): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1371): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1371): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1371): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1371): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/KeepSync( 3547): IOException
E/KeepSync( 3547): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3547): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3547): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3547): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3547): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3547): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3547): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3547): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3547): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3547): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3547): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3547): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3547): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3547): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3547): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3547): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3547): 	... 10 more
W/KeepSync( 3547): Sync result 2
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 231330, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,V/GoogleAuthProtoRequest( 3670): [387] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1371): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1371): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1371): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1371): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3670): [387] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3670): [387] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3670): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3670): 	at com.a.a.a.k.a(SourceFile:117)
,W/ExperimentUpdateService( 3670): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3670): ,	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3670): 	,at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3670): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3670): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3670): 	at com.a.a.a.g.a(SourceFile:79)
,W/ExperimentUpdateService( 3670): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3670): 	at com.a.a.k.run(SourceFile:110)
,D/HeadsetStateMachine( 2379): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2379): Disconnected process message: 10, size: 0
,I/jxcore-log( 3606): Connected to the server!
I/jxcore-log( 3606): 
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63),
,I/jxcore-log( 3606): --- start :testFindPeers.js---
,I/jxcore-log( 3606): 
,I/jxcore-log( 3606): testFindPeers created [object Object]
,I/jxcore-log( 3606): 
I/jxcore-log( 3606): serverPort is 8876
I/jxcore-log( 3606): 
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3606): setDiscoveryMode: Failed to set discovery mode to BLE,
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3606): setDiscoveryMode: Mode set to WIFI
,D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3606): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: motorola-Nexus 6_PT4732
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3606): bind: Binding a new listener,
,D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3606): initialize: My bluetooth address is F8:CF:C5:D9:E5:61,
,D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0,
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3606): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT4732","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3606): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3606): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3606): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3606): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3606): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3606): start: OK
,D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3606): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: motorola-Nexus 6_PT4732
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3606): Waiting for incoming connections...
,D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3606): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT4732","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3606): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3606): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT4732","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3606): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT4732","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3606): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3606): onIsDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3606): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3606): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3606): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 3606): start: OK
,I/jxcore-log( 3606): StartBroadcasting started ok
I/jxcore-log( 3606): 
I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback --- start :testFindPeers.js---", source: file:///android_asset/www/js/thali_main.js (63)
I/io.jxcore.node.ConnectionHelper( 3606): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3606): onWifiStateChanged: State changed to 2
I/io.jxcore.node.ConnectionHelper( 3606): onDiscoveryManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3606): Local service added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3606): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3606): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/BooksSync( 3513): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3513): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1371): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1371): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1371): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1371): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1371): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native,
I/GLSUser ( 1371): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1371): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1371): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3317): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3317): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3317): 	at jdm.a(PG:82)
E/HttpOperation( 3317): 	at jcs.o(PG:406)
E/HttpOperation( 3317): 	at jcn.a(PG:1379)
E/HttpOperation( 3317): 	at jcs.i(PG:143)
E/HttpOperation( 3317): 	at blb.a(PG:3937)
E/HttpOperation( 3317): 	at czp.a(PG:18188)
E/HttpOperation( 3317): 	at czp.a(PG:9081)
E/HttpOperation( 3317): 	at czq.run(PG:1686)
E/HttpOperation( 3317): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3317): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3317): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3317): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3317): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3317): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3317): 	at jdj.a(PG:4091)
E/HttpOperation( 3317): 	at jdj.a(PG:1125)
E/HttpOperation( 3317): 	at jdm.a(PG:77)
E/HttpOperation( 3317): 	... 12 more
E/HttpOperation( 3317): Caused by: faj: BadAuthentication
E/HttpOperation( 3317): 	at fal.a(PG:38)
E/HttpOperation( 3317): 	at jdj.a(PG:4089)
E/HttpOperation( 3317): 	... 14 more
,I/GLSUser ( 1371): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1371): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1371): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1371): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3317): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3317): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3317): 	at jdm.a(PG:82)
E/HttpOperation( 3317): 	at jcs.o(PG:406)
E/HttpOperation( 3317): 	at jcn.a(PG:1379)
E/HttpOperation( 3317): 	at jcs.i(PG:143)
E/HttpOperation( 3317): 	at hec.a(PG:42)
E/HttpOperation( 3317): 	at hee.a(PG:102)
E/HttpOperation( 3317): 	at czr.a(PG:65)
E/HttpOperation( 3317): 	at kka.a(PG:108)
E/HttpOperation( 3317): 	at czp.a(PG:19176)
E/HttpOperation( 3317): 	at czp.a(PG:9081)
E/HttpOperation( 3317): 	at czq.run(PG:1686)
E/HttpOperation( 3317): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3317): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3317): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3317): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3317): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3317): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3317): 	at jdj.a(PG:4091)
E/HttpOperation( 3317): 	at jdj.a(PG:1125)
E/HttpOperation( 3317): 	at jdm.a(PG:77)
E/HttpOperation( 3317): 	... 15 more
E/HttpOperation( 3317): Caused by: faj: BadAuthentication
E/HttpOperation( 3317): 	at fal.a(PG:38)
E/HttpOperation( 3317): 	at jdj.a(PG:4089)
E/HttpOperation( 3317): 	... 17 more
E/ExperimentLoader( 3317): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3317): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3317): 	at jdm.a(PG:82)
E/ExperimentLoader( 3317): 	at jcs.o(PG:406)
E/ExperimentLoader( 3317): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3317): 	at jcs.i(PG:143)
E/ExperimentLoader( 3317): 	at hec.a(PG:42)
E/ExperimentLoader( 3317): 	at hee.a(PG:102)
E/ExperimentLoader( 3317): 	at czr.a(PG:65)
E/ExperimentLoader( 3317): 	at kka.a(PG:108)
E/ExperimentLoader( 3317): 	at czp.a(PG:19176)
E/ExperimentLoader( 3317): 	at czp.a(PG:9081)
E/ExperimentLoader( 3317): 	at czq.run(PG:1686)
E/ExperimentLoader( 3317): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3317): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3317): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3317): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3317): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3317): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3317): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3317): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3317): 	at jdm.a(PG:77)
E/ExperimentLoader( 3317): 	... 15 more
E/ExperimentLoader( 3317): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3317): 	at fal.a(PG:38)
E/ExperimentLoader( 3317): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3317): 	... 17 more
,I/GLSUser ( 1371): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books,
I/GLSUser ( 1371): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1371): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1371): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/BooksAccountManager( 3513): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3513): Soft error
E/BooksSync( 3513): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3513): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3513): Sync error
E/BooksSync( 3513): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3513): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 3513): Finished books sync
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 289429, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 290099, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,V/KeepSync( 3547): Connecting to GoogleApiClient
,I/art     (  823): Explicit concurrent mark sweep GC freed 34218(1476KB) AllocSpace objects, 11(647KB) LOS objects, 31% free, 34MB/50MB, paused 2.642ms total 88.932ms
,I/GLSUser ( 1371): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1371): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1371): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1371): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1786): Handling authorization failure
E/ClientConnectionOperation( 1786): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1786): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1786): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1786): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1786): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1786): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1786): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1786): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1786): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1786): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1786): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1786): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1786): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1786): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1786): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1786): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1786): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1786): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1786): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1786): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1786): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1786): 	... 7 more
,V/KeepSync( 3547): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3547): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3547): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3547): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1371): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1371): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1371): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1371): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/KeepSync( 3547): IOException
E/KeepSync( 3547): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3547): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3547): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3547): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3547): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3547): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3547): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3547): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3547): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3547): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3547): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3547): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3547): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3547): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3547): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3547): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3547): 	... 10 more
W/KeepSync( 3547): Sync result 2
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 323728, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/WifiService(  823): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@34d6866b}
,E/WifiStateMachine(  823): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-48
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1371): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1371): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1371): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1371): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1371): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1371): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1371): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1371): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1371): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1371): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1371): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 2994): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 2994): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 2994): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 2994): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 2994): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/PlayEventLogger( 2994): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 2994): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 2994): Ignoring header User-Agent because its value was null.
,D/WifiService(  823): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@34d6866b}
,D/HeadsetStateMachine( 2379): Disconnected process message: 10, size: 0
,V/GoogleAuthProtoRequest( 3670): [388] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1371): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1371): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1371): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1371): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3670): [388] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3670): [388] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3670): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3670): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3670): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3670): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3670): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3670): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3670): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3670): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3670): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3670): 	at com.a.a.k.run(SourceFile:110)
,D/HeadsetStateMachine( 2379): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2379): Disconnected process message: 10, size: 0
,I/wpa_supplicant( 1197): P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3606): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3606): restart: Restarting...
,E/LocSvc_IzatApiV02(  823): E/virtual int izat_core::IzatApiV02::injectLocation(GpsExtLocation):857]: error! inject position failed
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3606): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3606): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3606): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/BooksSync( 3513): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3513): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1371): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1371): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1371): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1371): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1371): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1371): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1371): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1371): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3513): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3513): Soft error
E/BooksSync( 3513): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3513): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3513): Sync error
E/BooksSync( 3513): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3513): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3513): Finished books sync
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 440014, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1371): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1371): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1371): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1371): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3317): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3317): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3317): 	at jdm.a(PG:82)
E/HttpOperation( 3317): 	at jcs.o(PG:406)
E/HttpOperation( 3317): 	at jcn.a(PG:1379)
E/HttpOperation( 3317): 	at jcs.i(PG:143)
E/HttpOperation( 3317): 	at blb.a(PG:3937)
E/HttpOperation( 3317): 	at czp.a(PG:18188)
E/HttpOperation( 3317): 	at czp.a(PG:9081)
E/HttpOperation( 3317): 	at czq.run(PG:1686)
E/HttpOperation( 3317): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3317): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3317): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3317): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3317): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3317): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3317): 	at jdj.a(PG:4091)
E/HttpOperation( 3317): 	at jdj.a(PG:1125)
E/HttpOperation( 3317): 	at jdm.a(PG:77)
E/HttpOperation( 3317): 	... 12 more
E/HttpOperation( 3317): Caused by: faj: BadAuthentication
E/HttpOperation( 3317): 	at fal.a(PG:38)
E/HttpOperation( 3317): 	at jdj.a(PG:4089)
E/HttpOperation( 3317): 	... 14 more
,I/GLSUser ( 1371): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1371): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1371): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1371): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3317): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3317): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3317): 	at jdm.a(PG:82)
E/HttpOperation( 3317): 	at jcs.o(PG:406)
E/HttpOperation( 3317): 	at jcn.a(PG:1379)
E/HttpOperation( 3317): ,	at jcs.i(PG:143)
E/HttpOperation( 3317): 	at hec.a(PG:42)
E/HttpOperation( 3317): 	at hee.a(PG:102)
E/HttpOperation( 3317): 	at czr.a(PG:65)
E/HttpOperation( 3317): 	at kka.a(PG:108)
E/HttpOperation( 3317): 	at czp.a(PG:19176)
E/HttpOperation( 3317): 	at czp.a(PG:9081)
E/HttpOperation( 3317): 	at czq.run(PG:1686)
E/HttpOperation( 3317): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3317): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3317): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3317): 	,at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3317): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3317): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3317): 	at jdj.a(PG:4091)
E/HttpOperation( 3317): 	at jdj.a(PG:1125)
E/HttpOperation( 3317): 	at jdm.a(PG:77)
E/HttpOperation( 3317): 	... 15 more
E/HttpOperation( 3317): Caused by: faj: BadAuthentication
E/HttpOperation( 3317): 	at fal.a(PG:38)
E/HttpOperation( 3317): 	at jdj.a(PG:4089)
E/HttpOperation( 3317): 	... 17 more
E/ExperimentLoader( 3317): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
,E/ExperimentLoader( 3317): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3317): 	at jdm.a(PG:82)
E/ExperimentLoader( 3317): 	at jcs.o(PG:406)
E/ExperimentLoader( 3317): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3317): 	at jcs.i(PG:143)
E/ExperimentLoader( 3317): 	at hec.a(PG:42)
E/ExperimentLoader( 3317): 	at hee.a(PG:102)
E/ExperimentLoader( 3317): 	at czr.a(PG:65)
E/ExperimentLoader( 3317): 	at kka.a(PG:108)
E/ExperimentLoader( 3317): 	at czp.a(PG:19176)
E/ExperimentLoader( 3317): 	at czp.a(PG:9081)
E/ExperimentLoader( 3317): 	at czq.run(PG:1686)
E/ExperimentLoader( 3317): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3317): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3317): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3317): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3317): ,	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3317): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3317): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3317): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3317): 	at jdm.a(PG:77)
E/ExperimentLoader( 3317): 	... 15 more
E/ExperimentLoader( 3317): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3317): 	at fal.a(PG:38)
E/ExperimentLoader( 3317): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3317): 	... 17 more
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 441199, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2379): Disconnected process message: 10, size: 0
,I/art     ( 1371): Explicit concurrent mark sweep GC freed 49303(2MB) AllocSpace objects, 15(1653KB) LOS objects, 36% free, 27MB/43MB, paused 1.351ms total 61.782ms
,V/KeepSync( 3547): Connecting to GoogleApiClient
,I/art     (  823): Explicit concurrent mark sweep GC freed 32752(1489KB) AllocSpace objects, 11(458KB) LOS objects, 31% free, 34MB/50MB, paused 1.583ms total 74.389ms
,I/GLSUser ( 1371): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1371): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1371): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1371): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1786): Handling authorization failure
E/ClientConnectionOperation( 1786): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1786): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1786): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1786): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1786): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1786): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1786): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1786): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1786): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1786): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1786): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1786): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1786): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1786): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1786): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1786): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1786): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1786): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1786): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1786): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1786): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1786): 	... 7 more
,V/KeepSync( 3547): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3547): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3547): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3547): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1371): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1371): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1371): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1371): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3547): IOException
E/KeepSync( 3547): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3547): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152),
E/KeepSync( 3547): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3547): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3547): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3547): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3547): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3547): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3547): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3547): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3547): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3547): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3547): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3547): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3547): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3547): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3547): 	,... 10 more
W/KeepSync( 3547): Sync result 2
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 478253, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2379): Disconnected process message: 10, size: 0
,I/wpa_supplicant( 1197): P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3606): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...,
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3606): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3606): Start timer timeout, starting now...,
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3606): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3606): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,D/HeadsetStateMachine( 2379): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2379): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2379): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2379): Disconnected process message: 10, size: 0
,I/wpa_supplicant( 1197): P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3606): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3606): restart: Restarting...
,I/BooksSync( 3513): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3513): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1371): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1371): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1371): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1371): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1371): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books,
I/GLSUser ( 1371): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1371): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1371): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/BooksAccountManager( 3513): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3513): Soft error
E/BooksSync( 3513): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3513): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3513): Sync error
E/BooksSync( 3513): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3513): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3513): Finished books sync
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 682116, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3606): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3606): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3606): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,D/HeadsetStateMachine( 2379): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2379): Disconnected process message: 10, size: 0
,I/GLSUser ( 1371): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1371): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1371): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1371): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3317): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3317): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3317): 	at jdm.a(PG:82)
E/HttpOperation( 3317): 	at jcs.o(PG:406)
E/HttpOperation( 3317): 	at jcn.a(PG:1379)
E/HttpOperation( 3317): 	at jcs.i(PG:143)
E/HttpOperation( 3317): 	at blb.a(PG:3937)
E/HttpOperation( 3317): 	at czp.a(PG:18188)
E/HttpOperation( 3317): 	at czp.a(PG:9087)
E/HttpOperation( 3317): 	at czq.run(PG:1686)
E/HttpOperation( 3317): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3317): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3317): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3317): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3317): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3317): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3317): 	at jdj.a(PG:4091)
E/HttpOperation( 3317): 	at jdj.a(PG:1125)
E/HttpOperation( 3317): 	at jdm.a(PG:77)
E/HttpOperation( 3317): 	... 12 more
E/HttpOperation( 3317): Caused by: faj: BadAuthentication
E/HttpOperation( 3317): 	at fal.a(PG:38)
E/HttpOperation( 3317): 	at jdj.a(PG:4089)
E/HttpOperation( 3317): 	... 14 more
,I/GLSUser ( 1371): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1371): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1371): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1371): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3317): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3317): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3317): 	at jdm.a(PG:82)
E/HttpOperation( 3317): 	at jcs.o(PG:406)
E/HttpOperation( 3317): 	at jcn.a(PG:1379)
E/HttpOperation( 3317): 	at jcs.i(PG:143)
E/HttpOperation( 3317): 	at blb.a(PG:3937)
E/HttpOperation( 3317): 	at czp.a(PG:18188)
E/HttpOperation( 3317): 	at czp.a(PG:9081)
E/HttpOperation( 3317): 	at czq.run(PG:1686)
E/HttpOperation( 3317): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3317): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3317): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3317): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3317): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3317): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3317): 	at jdj.a(PG:4091)
E/HttpOperation( 3317): 	at jdj.a(PG:1125)
E/HttpOperation( 3317): 	at jdm.a(PG:77)
E/HttpOperation( 3317): 	... 12 more
E/HttpOperation( 3317): Caused by: faj: BadAuthentication
E/HttpOperation( 3317): 	at fal.a(PG:38)
E/HttpOperation( 3317): 	at jdj.a(PG:4089)
E/HttpOperation( 3317): 	... 14 more
,I/GLSUser ( 1371): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1371): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1371): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1371): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3317): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3317): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3317): 	at jdm.a(PG:82)
E/HttpOperation( 3317): 	at jcs.o(PG:406)
E/HttpOperation( 3317): 	at jcn.a(PG:1379)
E/HttpOperation( 3317): 	at jcs.i(PG:143)
E/HttpOperation( 3317): 	at hec.a(PG:42)
E/HttpOperation( 3317): 	at hee.a(PG:102)
E/HttpOperation( 3317): 	at czr.a(PG:65)
E/HttpOperation( 3317): 	at kka.a(PG:108)
E/HttpOperation( 3317): 	at czp.a(PG:19176)
E/HttpOperation( 3317): 	at czp.a(PG:9081)
E/HttpOperation( 3317): 	at czq.run(PG:1686)
E/HttpOperation( 3317): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3317): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3317): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3317): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3317): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3317): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3317): 	at jdj.a(PG:4091)
E/HttpOperation( 3317): 	at jdj.a(PG:1125)
E/HttpOperation( 3317): 	at jdm.a(PG:77)
E/HttpOperation( 3317): 	... 15 more
E/HttpOperation( 3317): Caused by: faj: BadAuthentication
E/HttpOperation( 3317): 	at fal.a(PG:38)
E/HttpOperation( 3317): 	at jdj.a(PG:4089)
E/HttpOperation( 3317): 	... 17 more
,E/ExperimentLoader( 3317): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3317): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3317): 	at jdm.a(PG:82)
E/ExperimentLoader( 3317): 	at jcs.o(PG:406)
,E/ExperimentLoader( 3317): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3317): 	at jcs.i(PG:143)
E/ExperimentLoader( 3317): 	at hec.a(PG:42)
E/ExperimentLoader( 3317): 	at hee.a(PG:102)
E/ExperimentLoader( 3317): 	at czr.a(PG:65)
E/ExperimentLoader( 3317): ,	at kka.a(PG:108)
E/ExperimentLoader( 3317): 	at czp.a(PG:19176)
E/ExperimentLoader( 3317): 	at czp.a(PG:9081)
E/ExperimentLoader( 3317): 	at czq.run(PG:1686)
E/ExperimentLoader( 3317): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3317): 	,at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3317): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3317): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3317): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3317): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3317): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3317): ,	at jdj.a(PG:1125)
E/ExperimentLoader( 3317): 	at jdm.a(PG:77)
E/ExperimentLoader( 3317): 	... 15 more
E/ExperimentLoader( 3317): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3317): 	at fal.a(PG:38)
,E/ExperimentLoader( 3317): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3317): 	... 17 more
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 470468, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,V/KeepSync( 3547): Connecting to GoogleApiClient
,I/GLSUser ( 1371): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1371): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1371): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1371): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1786): Handling authorization failure
E/ClientConnectionOperation( 1786): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1786): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1786): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1786): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1786): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1786): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1786): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1786): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1786): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1786): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1786): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1786): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1786): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1786): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1786): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1786): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1786): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1786): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1786): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1786): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1786): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1786): 	... 7 more
,V/KeepSync( 3547): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3547): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3547): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3547): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1371): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1371): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1371): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1371): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3547): IOException
E/KeepSync( 3547): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3547): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3547): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3547): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3547): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3547): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3547): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3547): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3547): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3547): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3547): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3547): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3547): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3547): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3547): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3547): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3547): 	... 10 more
,W/KeepSync( 3547): Sync result 2
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 758429, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2379): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2379): Disconnected process message: 10, size: 0
,I/GLSUser ( 1371): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1371): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1371): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1371): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3317): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3317): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3317): 	at jdm.a(PG:82)
E/HttpOperation( 3317): 	at jcs.o(PG:406)
E/HttpOperation( 3317): 	at jcn.a(PG:1379)
E/HttpOperation( 3317): 	at jcs.i(PG:143)
E/HttpOperation( 3317): 	at blb.a(PG:3937)
E/HttpOperation( 3317): 	at czp.a(PG:18188)
E/HttpOperation( 3317): 	at czp.a(PG:9081)
E/HttpOperation( 3317): 	at czq.run(PG:1686)
E/HttpOperation( 3317): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3317): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3317): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3317): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3317): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3317): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3317): 	at jdj.a(PG:4091)
E/HttpOperation( 3317): 	at jdj.a(PG:1125),
E/HttpOperation( 3317): 	at jdm.a(PG:77)
E/HttpOperation( 3317): 	... 12 more
E/HttpOperation( 3317): Caused by: faj: BadAuthentication
E/HttpOperation( 3317): 	at fal.a(PG:38)
E/HttpOperation( 3317): 	at jdj.a(PG:4089)
E/HttpOperation( 3317): 	... 14 more
,I/GLSUser ( 1371): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1371): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1371): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1371): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3317): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3317): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3317): 	at jdm.a(PG:82)
E/HttpOperation( 3317): 	at jcs.o(PG:406)
E/HttpOperation( 3317): 	at jcn.a(PG:1379)
E/HttpOperation( 3317): 	at jcs.i(PG:143)
E/HttpOperation( 3317): 	at hec.a(PG:42)
E/HttpOperation( 3317): 	at hee.a(PG:102)
E/HttpOperation( 3317): 	at czr.a(PG:65)
E/HttpOperation( 3317): 	at kka.a(PG:108)
E/HttpOperation( 3317): 	at czp.a(PG:19176)
E/HttpOperation( 3317): 	at czp.a(PG:9081)
E/HttpOperation( 3317): 	at czq.run(PG:1686)
E/HttpOperation( 3317): 	,at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3317): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3317): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3317): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3317): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3317): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3317): 	at jdj.a(PG:4091)
E/HttpOperation( 3317): 	at jdj.a(PG:1125)
E/HttpOperation( 3317): 	at jdm.a(PG:77)
E/HttpOperation( 3317): 	... 15 more
E/HttpOperation( 3317): Caused by: faj: BadAuthentication
E/HttpOperation( 3317): 	at fal.a(PG:38)
E/HttpOperation( 3317): 	at jdj.a(PG:4089),
E/HttpOperation( 3317): 	... 17 more
E/ExperimentLoader( 3317): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3317): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3317): 	at jdm.a(PG:82)
E/ExperimentLoader( 3317): 	at jcs.o(PG:406)
E/ExperimentLoader( 3317): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3317): 	at jcs.i(PG:143)
E/ExperimentLoader( 3317): 	at hec.a(PG:42)
E/ExperimentLoader( 3317): 	,at hee.a(PG:102)
E/ExperimentLoader( 3317): 	at czr.a(PG:65)
E/ExperimentLoader( 3317): 	at kka.a(PG:108)
,E/ExperimentLoader( 3317): 	at czp.a(PG:19176)
E/ExperimentLoader( 3317): 	at czp.a(PG:9081)
E/ExperimentLoader( 3317): 	at czq.run(PG:1686)
E/ExperimentLoader( 3317): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3317): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3317): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3317): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3317): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3317): Caused by: android.accounts.AuthenticatorException: Recoverable error
,E/ExperimentLoader( 3317): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3317): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3317): 	at jdm.a(PG:77)
E/ExperimentLoader( 3317): 	... 15 more
E/ExperimentLoader( 3317): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3317): 	at fal.a(PG:38)
E/ExperimentLoader( 3317): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3317): 	... 17 more
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 774334, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/wpa_supplicant( 1197): P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3606): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3606): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3606): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3606): P2P device discovery started successfully,
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3606): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/art     (  823): Explicit concurrent mark sweep GC freed 46497(2024KB) AllocSpace objects, 11(458KB) LOS objects, 31% free, 34MB/50MB, paused 1.242ms total 98.485ms
,V/GoogleAuthProtoRequest( 3670): [389] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1371): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1371): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1371): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1371): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3670): [389] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3670): [389] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3670): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3670): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3670): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3670): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3670): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3670): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3670): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3670): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3670): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3670): 	at com.a.a.k.run(SourceFile:110)
,D/HeadsetStateMachine( 2379): Disconnected process message: 10, size: 0
,I/art     ( 1371): Explicit concurrent mark sweep GC freed 51173(2MB) AllocSpace objects, 13(1434KB) LOS objects, 37% free, 27MB/43MB, paused 1.088ms total 30.637ms
,I/GLSUser ( 1371): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1371): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1371): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1371): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3317): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3317): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3317): 	at jdm.a(PG:82)
E/HttpOperation( 3317): 	at jcs.o(PG:406)
E/HttpOperation( 3317): 	at jcn.a(PG:1379)
E/HttpOperation( 3317): 	at jcs.i(PG:143)
E/HttpOperation( 3317): 	at blb.a(PG:3937)
E/HttpOperation( 3317): 	at czp.a(PG:18188)
E/HttpOperation( 3317): 	at czp.a(PG:9081)
E/HttpOperation( 3317): 	at czq.run(PG:1686)
E/HttpOperation( 3317): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3317): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3317): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3317): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3317): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3317): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3317): 	at jdj.a(PG:4091)
E/HttpOperation( 3317): 	at jdj.a(PG:1125)
E/HttpOperation( 3317): 	at jdm.a(PG:77)
E/HttpOperation( 3317): 	... 12 more
E/HttpOperation( 3317): Caused by: faj: BadAuthentication
E/HttpOperation( 3317): 	at fal.a(PG:38)
E/HttpOperation( 3317): 	at jdj.a(PG:4089)
E/HttpOperation( 3317): 	... 14 more
,I/GLSUser ( 1371): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1371): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1371): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1371): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3317): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3317): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3317): 	at jdm.a(PG:82)
E/HttpOperation( 3317): 	at jcs.o(PG:406)
E/HttpOperation( 3317): 	at jcn.a(PG:1379)
E/HttpOperation( 3317): 	at jcs.i(PG:143)
E/HttpOperation( 3317): 	at hec.a(PG:42)
E/HttpOperation( 3317): 	at hee.a(PG:102)
E/HttpOperation( 3317): 	at czr.a(PG:65)
E/HttpOperation( 3317): 	at kka.a(PG:108)
E/HttpOperation( 3317): 	at czp.a(PG:19176)
E/HttpOperation( 3317): 	at czp.a(PG:9081)
E/HttpOperation( 3317): 	at czq.run(PG:1686)
E/HttpOperation( 3317): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3317): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3317): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3317): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3317): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3317): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3317): 	at jdj.a(PG:4091)
E/HttpOperation( 3317): 	at jdj.a(PG:1125)
E/HttpOperation( 3317): 	at jdm.a(PG:77)
E/HttpOperation( 3317): 	... 15 more
E/HttpOperation( 3317): Caused by: faj: BadAuthentication
E/HttpOperation( 3317): 	at fal.a(PG:38)
E/HttpOperation( 3317): 	at jdj.a(PG:4089)
E/HttpOperation( 3317): 	... 17 more
E/ExperimentLoader( 3317): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3317): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3317): 	at jdm.a(PG:82)
E/ExperimentLoader( 3317): 	at jcs.o(PG:406)
E/ExperimentLoader( 3317): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3317): 	at jcs.i(PG:143)
E/ExperimentLoader( 3317): 	at hec.a(PG:42)
E/ExperimentLoader( 3317): 	at hee.a(PG:102)
E/ExperimentLoader( 3317): 	at czr.a(PG:65)
E/ExperimentLoader( 3317): 	at kka.a(PG:108)
E/ExperimentLoader( 3317): 	at czp.a(PG:19176)
E/ExperimentLoader( 3317): 	at czp.a(PG:9081)
E/ExperimentLoader( 3317): 	at czq.run(PG:1686)
E/ExperimentLoader( 3317): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3317): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3317): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3317): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3317): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3317): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3317): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3317): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3317): 	at jdm.a(PG:77)
E/ExperimentLoader( 3317): 	... 15 more
E/ExperimentLoader( 3317): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3317): 	at fal.a(PG:38)
E/ExperimentLoader( 3317): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3317): 	... 17 more
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 865688, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2379): Disconnected process message: 10, size: 0
,I/wpa_supplicant( 1197): P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3606): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3606): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3606): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3606): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3606): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,W/bt-btm  ( 2379): Stopping oneshot timer
,I/ActivityManager(  823): Start proc 4098:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider
,I/GAv4    ( 4098): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4098):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4098):   adb logcat -s GAv4
,W/GAv4    ( 4098): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.,
,W/GAv4    ( 4098): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4098): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  823): Killing 3235:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,D/HeadsetStateMachine( 2379): Disconnected process message: 10, size: 0
,I/GLSUser ( 1371): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1371): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1371): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1371): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3317): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
,E/HttpOperation( 3317): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3317): 	at jdm.a(PG:82)
E/HttpOperation( 3317): 	at jcs.o(PG:406)
E/HttpOperation( 3317): 	at jcn.a(PG:1379)
E/HttpOperation( 3317): 	at jcs.i(PG:143)
E/HttpOperation( 3317): 	at blb.a(PG:3937)
E/HttpOperation( 3317): 	at czp.a(PG:18188)
E/HttpOperation( 3317): 	at czp.a(PG:9081)
E/HttpOperation( 3317): 	at czq.run(PG:1686)
E/HttpOperation( 3317): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3317): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3317): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3317): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3317): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3317): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3317): 	at jdj.a(PG:4091)
E/HttpOperation( 3317): 	at jdj.a(PG:1125)
E/HttpOperation( 3317): 	at jdm.a(PG:77)
E/HttpOperation( 3317): 	... 12 more
E/HttpOperation( 3317): Caused by: faj: BadAuthentication
E/HttpOperation( 3317): 	at fal.a(PG:38)
E/HttpOperation( 3317): 	at jdj.a(PG:4089)
E/HttpOperation( 3317): 	... 14 more,
,I/GLSUser ( 1371): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1371): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1371): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1371): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3317): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3317): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3317): 	at jdm.a(PG:82)
E/HttpOperation( 3317): 	at jcs.o(PG:406)
E/HttpOperation( 3317): 	at jcn.a(PG:1379)
E/HttpOperation( 3317): 	at jcs.i(PG:143)
E/HttpOperation( 3317): 	at hec.a(PG:42)
E/HttpOperation( 3317): 	at hee.a(PG:102)
E/HttpOperation( 3317): 	at czr.a(PG:65)
E/HttpOperation( 3317): 	at kka.a(PG:108)
E/HttpOperation( 3317): 	at czp.a(PG:19176)
E/HttpOperation( 3317): 	at czp.a(PG:9081)
E/HttpOperation( 3317): 	at czq.run(PG:1686)
E/HttpOperation( 3317): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3317): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3317): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3317): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3317): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3317): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3317): 	at jdj.a(PG:4091)
E/HttpOperation( 3317): 	at jdj.a(PG:1125)
E/HttpOperation( 3317): 	at jdm.a(PG:77)
E/HttpOperation( 3317): 	... 15 more
E/HttpOperation( 3317): Caused by: faj: BadAuthentication
E/HttpOperation( 3317): 	at fal.a(PG:38)
E/HttpOperation( 3317): 	at jdj.a(PG:4089)
E/HttpOperation( 3317): 	... 17 more
,E/ExperimentLoader( 3317): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3317): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3317): 	at jdm.a(PG:82)
E/ExperimentLoader( 3317): 	at jcs.o(PG:406)
E/ExperimentLoader( 3317): 	,at jcn.a(PG:1379)
E/ExperimentLoader( 3317): 	at jcs.i(PG:143)
E/ExperimentLoader( 3317): 	at hec.a(PG:42)
E/ExperimentLoader( 3317): 	at hee.a(PG:102),
E/ExperimentLoader( 3317): 	at czr.a(PG:65)
E/ExperimentLoader( 3317): 	at kka.a(PG:108)
E/ExperimentLoader( 3317): 	at czp.a(PG:19176)
E/ExperimentLoader( 3317): 	at czp.a(PG:9081)
E/ExperimentLoader( 3317): 	at czq.run(PG:1686),
E/ExperimentLoader( 3317): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3317): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3317): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3317): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
,E/ExperimentLoader( 3317): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3317): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3317): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3317): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3317): 	at jdm.a(PG:77)
E/ExperimentLoader( 3317): ,	... 15 more
E/ExperimentLoader( 3317): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3317): 	at fal.a(PG:38)
E/ExperimentLoader( 3317): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3317): 	... 17 more
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 991767, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2379): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2379): Disconnected process message: 10, size: 0
,I/wpa_supplicant( 1197): P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3606): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...,
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3606): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3606): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3606): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3606): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,D/HeadsetStateMachine( 2379): Disconnected process message: 10, size: 0
,D/GCM     ( 1371): Message class com.google.f.a.a.i
,D/HeadsetStateMachine( 2379): Disconnected process message: 10, size: 0
,I/BooksSync( 3513): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3513): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1371): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1371): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1371): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1371): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1371): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1371): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1371): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1371): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3513): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3513): Soft error
E/BooksSync( 3513): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3513): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3513): Sync error
E/BooksSync( 3513): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3513): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3513): Finished books sync
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1165927, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/wpa_supplicant( 1197): P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3606): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3606): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3606): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3606): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3606): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,D/HeadsetStateMachine( 2379): Disconnected process message: 10, size: 0
,I/UsageStatsService(  823): User[0] Flushing usage stats to disk
,I/GLSUser ( 1371): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1371): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1371): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1371): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/HttpOperation( 3317): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3317): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3317): 	at jdm.a(PG:82)
E/HttpOperation( 3317): 	at jcs.o(PG:406)
E/HttpOperation( 3317): 	at jcn.a(PG:1379)
E/HttpOperation( 3317): 	at jcs.i(PG:143)
E/HttpOperation( 3317): 	at blb.a(PG:3937)
E/HttpOperation( 3317): 	at czp.a(PG:18188)
E/HttpOperation( 3317): 	at czp.a(PG:9081)
E/HttpOperation( 3317): 	at czq.run(PG:1686)
E/HttpOperation( 3317): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3317): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3317): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3317): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3317): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3317): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3317): 	at jdj.a(PG:4091)
E/HttpOperation( 3317): 	at jdj.a(PG:1125)
E/HttpOperation( 3317): 	at jdm.a(PG:77)
E/HttpOperation( 3317): 	... 12 more
E/HttpOperation( 3317): Caused by: faj: BadAuthentication
E/HttpOperation( 3317): 	at fal.a(PG:38)
E/HttpOperation( 3317): 	at jdj.a(PG:4089)
E/HttpOperation( 3317): 	... 14 more
,I/GLSUser ( 1371): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1371): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1371): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1371): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3317): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3317): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3317): 	at jdm.a(PG:82)
E/HttpOperation( 3317): 	at jcs.o(PG:406)
E/HttpOperation( 3317): 	at jcn.a(PG:1379)
E/HttpOperation( 3317): 	at jcs.i(PG:143)
E/HttpOperation( 3317): 	at hec.a(PG:42)
E/HttpOperation( 3317): 	at hee.a(PG:102)
E/HttpOperation( 3317): 	at czr.a(PG:65)
E/HttpOperation( 3317): 	at kka.a(PG:108)
E/HttpOperation( 3317): 	at czp.a(PG:19176)
E/HttpOperation( 3317): 	at czp.a(PG:9081)
E/HttpOperation( 3317): 	at czq.run(PG:1686)
E/HttpOperation( 3317): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3317): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3317): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3317): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3317): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3317): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3317): 	at jdj.a(PG:4091)
E/HttpOperation( 3317): 	at jdj.a(PG:1125)
E/HttpOperation( 3317): 	at jdm.a(PG:77)
E/HttpOperation( 3317): 	... 15 more
E/HttpOperation( 3317): Caused by: faj: BadAuthentication
E/HttpOperation( 3317): 	at fal.a(PG:38)
E/HttpOperation( 3317): 	at jdj.a(PG:4089)
E/HttpOperation( 3317): 	... 17 more
,E/ExperimentLoader( 3317): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3317): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3317): 	at jdm.a(PG:82)
E/ExperimentLoader( 3317): 	at jcs.o(PG:406)
E/ExperimentLoader( 3317): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3317): 	at jcs.i(PG:143)
E/ExperimentLoader( 3317): 	at hec.a(PG:42)
E/ExperimentLoader( 3317): 	at hee.a(PG:102)
E/ExperimentLoader( 3317): 	at czr.a(PG:65)
E/ExperimentLoader( 3317): 	at kka.a(PG:108)
E/ExperimentLoader( 3317): 	at czp.a(PG:19176)
E/ExperimentLoader( 3317): 	at czp.a(PG:9081)
E/ExperimentLoader( 3317): 	at czq.run(PG:1686)
E/ExperimentLoader( 3317): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3317): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3317): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3317): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3317): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3317): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3317): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3317): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3317): 	at jdm.a(PG:77)
E/ExperimentLoader( 3317): 	... 15 more
E/ExperimentLoader( 3317): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3317): 	at fal.a(PG:38)
E/ExperimentLoader( 3317): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3317): 	... 17 more
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 1243496, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2379): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2379): Disconnected process message: 10, size: 0
,V/KeepSync( 3547): Connecting to GoogleApiClient
,I/art     (  823): Explicit concurrent mark sweep GC freed 50920(2MB) AllocSpace objects, 13(490KB) LOS objects, 31% free, 34MB/50MB, paused 2.742ms total 90.839ms
,I/GLSUser ( 1371): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1371): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1371): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1371): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1786): Handling authorization failure
E/ClientConnectionOperation( 1786): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1786): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1786): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1786): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1786): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1786): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1786): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1786): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1786): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1786): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1786): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1786): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1786): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1786): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1786): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1786): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1786): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1786): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1786): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1786): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1786): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1786): 	... 7 more
,V/KeepSync( 3547): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3547): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3547): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3547): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1371): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1371): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1371): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1371): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3547): IOException
E/KeepSync( 3547): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3547): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3547): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3547): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3547): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3547): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3547): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3547): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3547): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3547): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3547): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3547): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3547): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3547): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3547): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3547): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3547): 	... 10 more
W/KeepSync( 3547): Sync result 2
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 1288840, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/wpa_supplicant( 1197): P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3606): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3606): restart: Restarting...
,I/jxcore-log( 3606): timeout now
I/jxcore-log( 3606): 
I/jxcore-log( 3606): weAreDoneNow
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): done, now sending data to server
I/jxcore-log( 3606): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3606): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3606): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3606): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,D/HeadsetStateMachine( 2379): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2379): Disconnected process message: 10, size: 0
,V/GoogleAuthProtoRequest( 3670): [390] a.<init>: mAccountName set to: thalitester@gmail.com
,I/EventLogService( 1786): Opted in for usage reporting
I/EventLogService( 1786): Aggregate from 1450232524903 (log), 1450232524903 (data)
,I/art     ( 1371): Explicit concurrent mark sweep GC freed 60222(3MB) AllocSpace objects, 8(882KB) LOS objects, 37% free, 27MB/43MB, paused 1.666ms total 60.965ms
,I/GLSUser ( 1371): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1371): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1371): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1371): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3670): [390] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3670): [390] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3670): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3670): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3670): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3670): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3670): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3670): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3670): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3670): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3670): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3670): 	at com.a.a.k.run(SourceFile:110)
,W/EventLogAggregator( 1786): Unknown tag: snet_gcore
,W/EventLogAggregator( 1786): Unknown tag: snet_launch_service
,I/ServiceDumpSys( 1786): dumping service [account]
,I/wpa_supplicant( 1197): P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3606): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...,
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3606): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3606): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3606): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3606): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,D/HeadsetStateMachine( 2379): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2379): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2379): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2379): Disconnected process message: 10, size: 0,
,I/wpa_supplicant( 1197): P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3606): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...,
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3606): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3606): Start timer timeout, starting now...,
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3606): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3606): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,D/HeadsetStateMachine( 2379): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2379): Disconnected process message: 10, size: 0
,I/wpa_supplicant( 1197): P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3606): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3606): restart: Restarting...
,D/HeadsetStateMachine( 2379): Disconnected process message: 10, size: 0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3606): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3606): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3606): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,D/HeadsetStateMachine( 2379): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2379): Disconnected process message: 10, size: 0
,I/GLSUser ( 1371): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1371): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1371): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1371): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3317): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3317): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3317): 	at jdm.a(PG:82)
E/HttpOperation( 3317): 	at jcs.o(PG:406)
E/HttpOperation( 3317): 	at jcn.a(PG:1379)
E/HttpOperation( 3317): 	at jcs.i(PG:143)
E/HttpOperation( 3317): 	at blb.a(PG:3937)
E/HttpOperation( 3317): 	at czp.a(PG:18188)
E/HttpOperation( 3317): 	at czp.a(PG:9081)
E/HttpOperation( 3317): 	at czq.run(PG:1686)
E/HttpOperation( 3317): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3317): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3317): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3317): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3317): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3317): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3317): 	at jdj.a(PG:4091)
E/HttpOperation( 3317): 	at jdj.a(PG:1125)
E/HttpOperation( 3317): 	at jdm.a(PG:77)
E/HttpOperation( 3317): 	... 12 more
E/HttpOperation( 3317): Caused by: faj: BadAuthentication
E/HttpOperation( 3317): 	at fal.a(PG:38)
E/HttpOperation( 3317): 	at jdj.a(PG:4089)
E/HttpOperation( 3317): 	... 14 more
,I/GLSUser ( 1371): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1371): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1371): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1371): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3317): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3317): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3317): 	at jdm.a(PG:82)
E/HttpOperation( 3317): 	at jcs.o(PG:406)
E/HttpOperation( 3317): 	at jcn.a(PG:1379)
E/HttpOperation( 3317): 	at jcs.i(PG:143)
E/HttpOperation( 3317): 	at hec.a(PG:42)
E/HttpOperation( 3317): 	at hee.a(PG:102)
E/HttpOperation( 3317): 	at czr.a(PG:65)
E/HttpOperation( 3317): 	at kka.a(PG:108)
E/HttpOperation( 3317): 	at czp.a(PG:19176)
E/HttpOperation( 3317): 	at czp.a(PG:9081)
E/HttpOperation( 3317): 	at czq.run(PG:1686)
E/HttpOperation( 3317): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3317): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3317): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3317): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3317): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3317): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3317): 	at jdj.a(PG:4091)
E/HttpOperation( 3317): ,	at jdj.a(PG:1125)
E/HttpOperation( 3317): 	at jdm.a(PG:77)
E/HttpOperation( 3317): 	... 15 more
E/HttpOperation( 3317): Caused by: faj: BadAuthentication
E/HttpOperation( 3317): ,	at fal.a(PG:38)
E/HttpOperation( 3317): 	at jdj.a(PG:4089)
E/HttpOperation( 3317): 	... 17 more
,E/ExperimentLoader( 3317): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3317): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3317): 	at jdm.a(PG:82)
E/ExperimentLoader( 3317): ,	at jcs.o(PG:406)
E/ExperimentLoader( 3317): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3317): 	at jcs.i(PG:143)
E/ExperimentLoader( 3317): 	at hec.a(PG:42)
,E/ExperimentLoader( 3317): 	at hee.a(PG:102)
E/ExperimentLoader( 3317): 	at czr.a(PG:65)
E/ExperimentLoader( 3317): 	at kka.a(PG:108)
E/ExperimentLoader( 3317): 	at czp.a(PG:19176)
E/ExperimentLoader( 3317): 	at czp.a(PG:9081)
E/ExperimentLoader( 3317): 	at czq.run(PG:1686)
E/ExperimentLoader( 3317): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3317): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3317): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3317): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587),
E/ExperimentLoader( 3317): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3317): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3317): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3317): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3317): 	at jdm.a(PG:77)
E/ExperimentLoader( 3317): 	... 15 more
E/ExperimentLoader( 3317): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3317): 	at fal.a(PG:38)
E/ExperimentLoader( 3317): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3317): 	... 17 more
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 1746096, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2379): Disconnected process message: 10, size: 0
,I/wpa_supplicant( 1197): P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3606): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3606): restart: Restarting...
,D/HeadsetStateMachine( 2379): Disconnected process message: 10, size: 0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3606): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3606): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3606): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started,
,I/ProcessStatsService(  823): Prepared write state in 22ms
,I/ProcessStatsService(  823): Pruning old procstats: /data/system/procstats/state-2015-12-15-16-16-43.bin
,W/bt-btm  ( 2379): Stopping oneshot timer
,I/GLSUser ( 1371): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2: email
I/GLSUser ( 1371): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2: email without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1371): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1371): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/HeadsetStateMachine( 2379): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2379): Disconnected process message: 10, size: 0
,I/ActivityManager(  823): Killing 3368:com.android.defcontainer/u0a7 (adj 15): empty for 1820s
,I/ActivityManager(  823): Killing 3468:com.google.android.apps.docs/u0a46 (adj 15): empty for 1821s
,D/HeadsetStateMachine( 2379): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2379): Disconnected process message: 10, size: 0
,I/wpa_supplicant( 1197): P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3606): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3606): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3606): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3606): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3606): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,TIME-OUT KILL (timeout was 1800000ms)
```
