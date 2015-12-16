#### Test 50650278923ff9f_thali05_motorola-Nexus 6 Logs


```
--------- beginning of main
E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=2.77 targetRoamBSSID=any RSSI=-47
E/WifiStateMachine(  822): WifiStateMachine starting scan for "NG7005g"WPA_PSK with 2412,5220
,D/AndroidRuntime( 3665): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 3665): CheckJNI is OFF
D/AndroidRuntime( 3665): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  822): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/WindowManager(  822): addAppToken: AppWindowToken{77e0e26 token=Token{35a61d81 ActivityRecord{244fb568 u0 com.test.thalitest/.MainActivity t26}}} to stack=1 task=26 at 0
D/AndroidRuntime( 3665): Shutting down VM
I/MicrophoneInputStream( 1516): mic_close com.google.android.apps.gsa.speech.audio.u@21f8486
I/HotwordDetector( 1516): Closing mic
V/WindowManager(  822): Adding window Window{1294a603 u0 Starting com.test.thalitest} at 2 of 7 (after Window{1bf13ddf u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
I/ActivityManager(  822): Start proc 3679:com.test.thalitest/u0a265 for activity com.test.thalitest/.MainActivity
D/audio_hw_primary(  358): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  358): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  358): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1516): Stopping hotword detection.
I/HotwordRecognitionRnr( 1516): Hotword detection finished
I/art     (  369): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 608us total 34.988ms
I/art     (  369): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 378us total 23.045ms
I/art     (  369): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 321us total 16.720ms
I/ActivityManager(  822): Killing 3079:com.google.android.gm/u0a78 (adj 15): empty #17
E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1659286803
E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,I/ActivityManager(  822): Killing 2997:com.google.android.deskclock/u0a44 (adj 15): empty #18
,I/kickstart(  872): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
I/kickstart(  872): STATUS: Wrote to /sys/power/wake_lock
,E/kickstart(  872): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2
I/kickstart(  872): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2' for writing
,I/WebViewFactory( 3679): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3679): Time to load native libraries: 2 ms (timestamps 1778-1780)
I/LibraryLoader( 3679): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3679): Binding Chromium to main looper Looper (main, tid 1) {2a8f20df}
,I/LibraryLoader( 3679): Expected native library version number "",actual native library version number ""
I/chromium( 3679): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3679): Initializing chromium process, singleProcess=true
W/art     ( 3679): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3679): ApplicationContext is null in ApplicationStatus
,W/chromium( 3679): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3679): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3679): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3679): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/BluetoothManagerService(  822): Message: 20
D/BluetoothManagerService(  822): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2f7b15f3:true
,W/art     ( 3679): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3679): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3679): CordovaWebView is running on device made by: motorola
,W/art     ( 3679): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 3679): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3679): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,D/Atlas   ( 3679): Validating map...
,V/WindowManager(  822): Adding window Window{139561e3 u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{1294a603 u0 Starting com.test.thalitest})
,W/chromium( 3679): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3679): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3679): Enabling debug mode 0
,I/ActivityManager(  822): Displayed com.test.thalitest/.MainActivity: +1s136ms
,I/Keyboard.Facilitator( 1240): onFinishInput()
,W/BindingManager( 3679): Cannot call determinedVisibility() - never saw a connection for the pid: 3679
,D/JsMessageQueue( 3679): Set native->JS mode to OnlineEventsBridgeMode
,I/kickstart(  872): STATUS: Received file 'm9kefs2'
I/kickstart(  872): STATUS: 950272 bytes transferred in 0.986027 seconds
I/kickstart(  872): STATUS: Successfully downloaded files from target 
I/kickstart(  872): STATUS: Wrote to /sys/power/wake_unlock
,I/kickstart(  872): STATUS: Sahara protocol completed
,D/jxcore_app_log( 3679): JniHelper::setJavaVM(0xb489d200), pthread_self() = -1576257408
D/JX-Cordova( 3679): jxcore cordova android initializing
,W/jxcore-log( 3679): Initializing JXcore engine
,W/jxcore-log( 3679): JXcore engine is ready
,W/jxcore-log( 3679): Starting JXcore engine
,W/.test.thalitest( 3679): type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[10438]" dev="sockfs" ino=10438 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/.test.thalitest( 3679): type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,W/.test.thalitest( 3679): type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[13033]" dev="sockfs" ino=13033 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/.test.thalitest( 3679): type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[22946]" dev="sockfs" ino=22946 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 3679): Platform android
W/jxcore-log( 3679): 
W/jxcore-log( 3679): Process ARCH arm
W/jxcore-log( 3679): 
,I/jxcore-log( 3679): JXcore Cordova bridge is ready!
I/jxcore-log( 3679): 
W/jxcore-log( 3679): JXcore engine is started
,I/Choreographer( 3679): Skipped 131 frames!  The application may be doing too much work on its main thread.
I/chromium( 3679): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3679): Toggling radios to true
I/jxcore-log( 3679): 
,D/BluetoothAdapter( 3679): enable(): BT is already enabled..!
,D/WifiService(  822): setWifiEnabled: true pid=3679, uid=10265
D/WifiService(  822): New client listening to asynchronous messages
,E/WifiService(  822): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3679): Radios toggled
I/jxcore-log( 3679): 
,D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/jxcore-log( 3679): Got Device Bluetooth address: F8:CF:C5:D9:E5:61
I/jxcore-log( 3679): 
,I/jxcore-log( 3679): Perf Test app loaded loaded
I/jxcore-log( 3679): 
,I/jxcore-log( 3679): check test folder,
I/jxcore-log( 3679): 
,I/jxcore-log( 3679): found test : ./testFindPeers.js
I/jxcore-log( 3679): 
,I/wpa_supplicant( 1193): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  822): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  822): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,I/jxcore-log( 3679): found test : ./testSendData.js
I/jxcore-log( 3679): 
,D/CommandListener(  354): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1265): Read error: ssl=0xaec38800: I/O error during system call, Connection timed out
,V/NativeCrypto( 1265): SSL shutdown failed: ssl=0xaec38800: I/O error during system call, Broken pipe
,D/ConnectivityService(  822): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10011
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): ValidatedState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): DefaultState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): Forcing reevaluation
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
,D/ConnectivityService(  822): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,D/ConnectivityService(  822): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,E/WifiStateMachine(  822): Start Disconnecting Watchdog 1
,E/WifiStateMachine(  822): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,D/CommandListener(  354): Clearing all IP addresses on wlan0
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
,D/WifiNetworkAgent(  822): NetworkAgent: NetworkAgent channel lost
,E/WifiStateMachine(  822): CMD_AUTO_CONNECT sup state CompletedState my state DisconnectedState nid=0 roam=3
E/WifiStateMachine(  822): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=0
I/Choreographer( 3679): Skipped 69 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3679): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/ConnectivityService(  822): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityManager.CallbackHandler( 1071): CM callback handler got msg 524292
,D/CSLegacyTypeTracker(  822): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): OfflineState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): Disconnected - quitting
D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/Tethering(  822): MasterInitialState.processMessage what=3
,D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  822): MasterInitialState.processMessage what=3
,D/ConnectivityService(  822): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/ConnectivityService(  822): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/ConnectivityService(  822): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
,I/NetworkMonitor( 3255): type=WIFI subType= reason=null isConnected=false
,V/MusicLeanback( 3255): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/PhoneInterfaceManager( 1333): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1333): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  822): getDataEnabled: retVal=false
,E/GpsLocationProvider(  822): No APN found to select.
,E/WifiConfigStore(  822): Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiConfigStore(  822): will read network variables netId=0
,D/PhoneInterfaceManager( 1333): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1333): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  822): getDataEnabled: retVal=false
,I/ActivityManager(  822): Start proc 3739:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.steen.receiver.ConnectivityChangeReceiver
,E/WifiStateMachine(  822): CMD_AUTO_CONNECT did save config ->  nid=0
,E/WifiConfigStore(  822): will read network variables netId=0
,E/GpsLocationProvider(  822): No APN found to select.
,I/ActivityManager(  822): Start proc 3765:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,I/ActivityManager(  822): Killing 2279:com.google.android.calendar/u0a37 (adj 15): empty #17
,D/SprintDMReceiver( 3765): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3765): simOperator:  IMSI: null
D/SprintDMReceiver( 3765): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1774): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1774): onCreate
,D/SystemUpdateService( 1774): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1774): active receiver: enabled
,I/SystemUpdateService( 1774): showing system update notification
,I/iu.Environment( 1774): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1774): num queued entries: 0
I/iu.UploadsManager( 1774): num updated entries: 0
I/iu.SyncManager( 1774): NEXT; no task
,I/ValidateNoPeople(  822): skipping global notification
,D/ChimeraCfgMgr( 1774): Loading module com.google.android.gms.kids from APK com.google.android.gms
,V/SystemUpdateService( 1774): retry (wakeup: false) in 3599963 ms
,D/SystemUpdateService( 1774): onDestroy
,I/ActivityManager(  822): Start proc 3789:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,I/Babel   ( 2943): connection state changed from UNKNOWN to DISCONNECTED
,I/ActivityManager(  822): Killing 2299:com.android.providers.calendar/u0a3 (adj 15): empty #17
,I/GAv4    ( 3789): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3789):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3789):   adb logcat -s GAv4
,W/GAv4    ( 3789): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3789): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3789): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 3789): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3789): Time to load native libraries: 1 ms (timestamps 7341-7342)
I/LibraryLoader( 3789): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3789): Binding Chromium to main looper Looper (main, tid 1) {356f34f2}
I/LibraryLoader( 3789): Expected native library version number "",actual native library version number ""
I/chromium( 3789): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3789): Initializing chromium process, singleProcess=true
,W/art     ( 3789): Attempt to remove local handle scope entry from IRT, ignoring,
E/SysUtils( 3789): ApplicationContext is null in ApplicationStatus
,W/chromium( 3789): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3789): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3789): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3789): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,W/AudioManagerAndroid( 3789): Requires BLUETOOTH permission
,I/art     (  822): Explicit concurrent mark sweep GC freed 42857(2MB) AllocSpace objects, 11(270KB) LOS objects, 32% free, 33MB/49MB, paused 1.771ms total 62.101ms,
,V/GLSActivity( 1265): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NSApplication( 3789): Starting up...
,I/GLSUser ( 1265): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1265): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1265): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1265): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/ActivityManager(  822): Start proc 3845:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,V/GLSActivity( 1265): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3019): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3019): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3019): [1] 5.onFinished: Scheduling replication attempt 3.
,I/ActivityManager(  822): Killing 3360:android.process.acore/u0a5 (adj 15): empty #17
,I/wpa_supplicant( 1193): wlan0: Trying to associate with SSID 'NG7005g'
,I/ActivityManager(  822): Start proc 3866:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,I/ActivityManager(  822): Killing 3487:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,I/wpa_supplicant( 1193): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 1193): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 1193): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=0 id_str=]
,D/ConnectivityService(  822): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} }
E/WifiConfigStore(  822): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  822): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  822): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  354): Setting iface cfg,
E/WifiStateMachine(  822): Start Dhcp Watchdog 2
,E/WifiStateMachine(  822):  WifiLinkLayerStats: 
,E/WifiStateMachine(  822):  my bss beacon rx: 568
E/WifiStateMachine(  822):  RSSI mgmt: -47
E/WifiStateMachine(  822):  BE :  rx=215 tx=140 lost=0 retries=0
E/WifiStateMachine(  822):  BK :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  822):  VI :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  822):  VO :  rx=6 tx=0 lost=0 retries=0
E/WifiStateMachine(  822):  on_time : 18681 tx_time=287 rx_time=667 scan_time=0
,D/ConnectivityService(  822): updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,E/native  (  822): do suspend false
,E/WifiStateMachine(  822): scanCount==0 - aborting
,V/MusicLeanback( 3255): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) },
,I/ActivityManager(  822): Killing 3509:com.android.musicfx/u0a18 (adj 15): empty #17
,I/dhcpcd  ( 3884): version 5.5.6 starting
,D/SprintDMReceiver( 3765): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3765): simOperator:  IMSI: null
D/SprintDMReceiver( 3765): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1774): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1774): onCreate
,D/SystemUpdateService( 1774): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1774): active receiver: enabled
,I/SystemUpdateService( 1774): showing system update notification
,D/ChimeraCfgMgr( 1774): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/ValidateNoPeople(  822): skipping global notification
,V/SystemUpdateService( 1774): retry (wakeup: false) in 3599966 ms
,D/SystemUpdateService( 1774): onDestroy
,I/dhcpcd  ( 3884): wlan0: rebinding lease of 192.168.1.122
,I/dhcpcd  ( 3884): wlan0: acknowledged 192.168.1.122 from 192.168.1.1
,I/dhcpcd  ( 3884): wlan0: leased 192.168.1.122 for 86400 seconds
,D/ConnectivityService(  822): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  822): Adding iface wlan0 to network 101
,E/WifiStateMachine(  822): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  822): Unexpected mtu value: 0, wlan0
,D/ConnectivityService(  822): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/ConnectivityService(  822): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  822): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  822): Setting Dns servers for network 101 to [/192.168.1.1]
,D/ConnectivityService(  822): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  822): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  822): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  822): Connected
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  822): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  822): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
D/ConnectivityService(  822): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  822):    accepting network in place of null
,D/ConnectivityService(  822): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} }
,D/ConnectivityService(  822): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/CSLegacyTypeTracker(  822): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 1071): CM callback handler got msg 524290
,D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  822): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 3255): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 3255): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/SprintDMReceiver( 3765): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/PhoneInterfaceManager( 1333): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
,E/PhoneInterfaceManager( 1333): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  822): getDataEnabled: retVal=false
,D/SprintDMHelper( 3765): simOperator:  IMSI: null
D/SprintDMReceiver( 3765): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1774): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,E/GpsLocationProvider(  822): No APN found to select.
,D/SystemUpdateService( 1774): onCreate
,D/SystemUpdateService( 1774): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1774): active receiver: enabled
,I/SystemUpdateService( 1774): showing system update notification
,I/iu.Environment( 1774): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/ValidateNoPeople(  822): skipping global notification
,I/iu.UploadsManager( 1774): num queued entries: 0
I/iu.UploadsManager( 1774): num updated entries: 0
,V/SystemUpdateService( 1774): retry (wakeup: false) in 3599975 ms
,D/ChimeraCfgMgr( 1774): Loading module com.google.android.gms.kids from APK com.google.android.gms
I/iu.SyncManager( 1774): NEXT; no task
,D/ChimeraCfgMgr( 1774): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/SystemUpdateService( 1774): onDestroy
,I/GLSUser ( 1265): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1265): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1265): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1265): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1265): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  822): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 16 Dec 2015 15:46:33 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1450280793681], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1450280793655]},
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  822): Validated
D/ConnectivityService(  822): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/ConnectivityService(  822): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  822): rematching NetworkAgentInfo [WIFI () - 101],
D/ConnectivityService(  822): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  822): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1071): CM callback handler got msg 524290
,W/Kids    ( 1774): [AccountUtils] Account not ready
W/Kids    ( 1774): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 1774): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 1774): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 1774): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 1774): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 1774): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 1774): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 1774): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 1774): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 1774): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 1774): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 1774): 	at java.lang.Thread.run(Thread.java:818)
,V/Herrevad( 1774): NQAS connected
,I/Babel   ( 2943): connection state changed from DISCONNECTED to CONNECTED
,D/GCM     ( 1265): Connected
,I/GCM     ( 1774): Message from null null
E/GCM     ( 1774): Dropping message from null
,D/GCM     ( 1265): Message class com.google.f.a.a.p
,I/jxcore-log( 3679): BLE advertisement not supported: Bluetooth LE advertising is not supported,
I/jxcore-log( 3679): 
,D/ConnectivityService(  822): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=9.11 rxSuccessRate=9.98 targetRoamBSSID=any RSSI=-47
E/WifiStateMachine(  822): WifiStateMachine L2Connected CMD_START_SCAN source -2 10, 11 -> obsolete
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=3.28 rxSuccessRate=4.25 targetRoamBSSID=any RSSI=-47
E/WifiStateMachine(  822): WifiStateMachine L2Connected CMD_START_SCAN source -2 9, 11 -> obsolete
,I/PowerManagerService(  822): Going to sleep due to screen timeout (uid 1000)...
,I/Adreno  (  822): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/PermissionCache(  260): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (236 us)
,I/DisplayManagerService(  822): Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager(  822): Display changed displayId=0
,D/SurfaceFlinger(  260): Set power mode=0, type=0 flinger=0xb6482000
,D/qdhwcomposer(  260): hwc_setPowerMode: Setting mode 0 on display: 0
,I/qdhwcomposer(  260): handle_blank_event: dpy:0 panel power state: 0
,D/qdhwcomposer(  260): hwc_setPowerMode: Done setting mode 0 on display 0
,D/SurfaceControl(  822): Excessive delay in setPowerMode(): 259ms
,I/DreamManagerService(  822): Entering dreamland.
I/PowerManagerService(  822): Dozing...
,I/DreamController(  822): Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,D/audio_hw_primary(  358): adev_set_parameters: enter: screen_state=on
,D/mot_vr_audio_hw(  358): adev_set_parameters: screen_state=on
,E/WifiStateMachine(  822): cancelDelayedScan -> 12
,E/native  (  822): do suspend false
,I/Keyboard.Facilitator( 1240): onFinishInput()
,E/WifiStateMachine(  822): cancelDelayedScan -> 14,
,E/native  (  822): do suspend true
,D/audio_hw_primary(  358): adev_set_parameters: enter: screen_state=off
D/mot_vr_audio_hw(  358): adev_set_parameters: screen_state=off
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-47
E/WifiStateMachine(  822): WifiStateMachine L2Connected CMD_START_SCAN source -2 13, 14 -> obsolete
,D/HeadsetStateMachine( 2369): Disconnected process message: 10, size: 0
,I/GLSUser ( 1265): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1265): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1265): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1265): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1265): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3388): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3388): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3388): 	at jdm.a(PG:82)
E/HttpOperation( 3388): 	at jcs.o(PG:406)
E/HttpOperation( 3388): 	at jcn.a(PG:1379)
E/HttpOperation( 3388): 	at jcs.i(PG:143)
E/HttpOperation( 3388): 	at blb.a(PG:3937)
E/HttpOperation( 3388): 	at czp.a(PG:18188)
E/HttpOperation( 3388): 	at czp.a(PG:9081)
E/HttpOperation( 3388): 	at czq.run(PG:1686)
E/HttpOperation( 3388): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3388): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3388): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3388): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3388): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3388): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3388): 	at jdj.a(PG:4091)
E/HttpOperation( 3388): 	at jdj.a(PG:1125)
E/HttpOperation( 3388): 	at jdm.a(PG:77)
E/HttpOperation( 3388): 	... 12 more
E/HttpOperation( 3388): Caused by: faj: BadAuthentication
E/HttpOperation( 3388): 	at fal.a(PG:38)
E/HttpOperation( 3388): 	at jdj.a(PG:4089)
E/HttpOperation( 3388): 	... 14 more
,I/GLSUser ( 1265): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1265): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1265): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1265): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1265): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3388): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3388): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3388): 	at jdm.a(PG:82)
E/HttpOperation( 3388): 	at jcs.o(PG:406)
E/HttpOperation( 3388): 	at jcn.a(PG:1379)
E/HttpOperation( 3388): 	at jcs.i(PG:143)
E/HttpOperation( 3388): 	at hec.a(PG:42)
E/HttpOperation( 3388): 	at hee.a(PG:102)
E/HttpOperation( 3388): 	at czr.a(PG:65)
E/HttpOperation( 3388): 	at kka.a(PG:108)
E/HttpOperation( 3388): 	at czp.a(PG:19176)
E/HttpOperation( 3388): 	at czp.a(PG:9081)
E/HttpOperation( 3388): 	at czq.run(PG:1686)
E/HttpOperation( 3388): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3388): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3388): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3388): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3388): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3388): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3388): 	at jdj.a(PG:4091)
E/HttpOperation( 3388): 	at jdj.a(PG:1125)
E/HttpOperation( 3388): 	at jdm.a(PG:77)
E/HttpOperation( 3388): 	... 15 more
E/HttpOperation( 3388): Caused by: faj: BadAuthentication
E/HttpOperation( 3388): 	at fal.a(PG:38)
E/HttpOperation( 3388): 	at jdj.a(PG:4089)
E/HttpOperation( 3388): 	... 17 more
E/ExperimentLoader( 3388): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3388): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3388): 	at jdm.a(PG:82)
E/ExperimentLoader( 3388): 	at jcs.o(PG:406)
E/ExperimentLoader( 3388): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3388): 	at jcs.i(PG:143)
E/ExperimentLoader( 3388): 	at hec.a(PG:42)
E/ExperimentLoader( 3388): 	at hee.a(PG:102)
E/ExperimentLoader( 3388): 	at czr.a(PG:65)
E/ExperimentLoader( 3388): 	at kka.a(PG:108)
E/ExperimentLoader( 3388): 	at czp.a(PG:19176)
E/ExperimentLoader( 3388): 	at czp.a(PG:9081)
E/ExperimentLoader( 3388): 	at czq.run(PG:1686)
E/ExperimentLoader( 3388): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3388): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3388): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3388): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3388): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3388): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3388): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3388): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3388): 	at jdm.a(PG:77)
E/ExperimentLoader( 3388): 	... 15 more
E/ExperimentLoader( 3388): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3388): 	at fal.a(PG:38)
E/ExperimentLoader( 3388): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3388): 	... 17 more
,V/GLSActivity( 1265): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1265): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1265): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1265): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1265): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1265): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 167507, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,D/Finsky  ( 3019): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3019): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3019): [1] 5.onFinished: Scheduling replication attempt 4.
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-47
E/WifiStateMachine(  822): WifiStateMachine L2Connected CMD_START_SCAN source -2 11, 14 -> obsolete
,D/HeadsetStateMachine( 2369): Disconnected process message: 10, size: 0
,I/art     ( 1265): Explicit concurrent mark sweep GC freed 30035(1787KB) AllocSpace objects, 3(330KB) LOS objects, 37% free, 26MB/42MB, paused 744us total 29.140ms
,V/GLSActivity( 1265): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1265): Vacuum at: now=1450280831286 tag=VacuumService
,I/art     (  822): Explicit concurrent mark sweep GC freed 58489(2MB) AllocSpace objects, 8(222KB) LOS objects, 32% free, 33MB/49MB, paused 1.591ms total 57.025ms
,V/GoogleAuthProtoRequest( 3739): [400] a.<init>: mAccountName set to: thalitester@gmail.com
,V/GLSActivity( 1265): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1265): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1265): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1265): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1265): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1265): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3019): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3019): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3019): [1] 5.onFinished: Scheduling replication attempt 5.
,I/GLSUser ( 1265): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1265): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1265): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1265): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1265): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3739): [400] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3739): [400] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3739): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3739): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3739): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3739): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3739): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3739): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3739): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3739): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3739): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3739): 	at com.a.a.k.run(SourceFile:110)
,I/GoogleURLConnFactory( 1265): Using platform SSLCertificateSocketFactory
,W/Uploader( 1265): No account for auth token provided
,I/GLSUser ( 1265): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1265): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1265): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1265): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1265): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1265): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1265): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1265): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1265): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1265): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1265): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1265): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1265): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1265): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1265): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1265): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1265): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78),
E/Uploader( 1265): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1265): No account for auth token provided
,W/Uploader( 1265): No account for auth token provided
,W/Uploader( 1265): No account for auth token provided
,I/GLSUser ( 1265): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1265): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1265): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1265): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1265): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1265): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1265): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1265): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1265): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1265): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1265): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1265): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1265): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1265): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1265): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1265): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1265): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1265): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1265): No account for auth token provided
,I/GLSUser ( 1265): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1265): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1265): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1265): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1265): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1265): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1265): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1265): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1265): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1265): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1265): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1265): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1265): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1265): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1265): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1265): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1265): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1265): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1265): No account for auth token provided
,W/Uploader( 1265): No account for auth token provided,
,W/Uploader( 1265): No account for auth token provided
,W/Uploader( 1265): No account for auth token provided
,W/Uploader( 1265): No account for auth token provided
,W/Uploader( 1265):  no longer exists, so no auth token.
,W/Uploader( 1265): No account for auth token provided
,I/GLSUser ( 1265): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1265): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1265): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1265): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1265): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1265): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1265): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1265): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1265): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1265): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1265): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1265): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1265): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1265): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1265): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1265): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1265): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1265): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/GLSUser ( 1265): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1265): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1265): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1265): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1265): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1265): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1265): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1265): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1265): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1265): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1265): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1265): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1265): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1265): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1265): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1265): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1265): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1265): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/BooksSync( 3618): Starting books sync for 61035162, extras: ade
,V/KeepSync( 3587): Connecting to GoogleApiClient
,I/BooksConfig( 3618): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1265): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1265): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1265): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1265): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1265): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1265): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1265): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1265): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1265): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1265): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,V/KeepSync( 3587): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3587): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3587): (284) automatic index on blob_node(is_deleted),
E/SQLiteLog( 3587): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1265): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1265): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1265): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1265): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1265): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/BooksAccountManager( 3618): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3618): Soft error
E/BooksSync( 3618): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3618): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3618): Sync error
E/BooksSync( 3618): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3618): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3618): Finished books sync
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 167981, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1265): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1265): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1265): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1265): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1265): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3587): IOException
E/KeepSync( 3587): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3587): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3587): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3587): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3587): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3587): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3587): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3587): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3587): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3587): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3587): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3587): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3587): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3587): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3587): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3587): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3587): 	... 10 more
W/KeepSync( 3587): Sync result 2
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 168461, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,V/GoogleAuthProtoRequest( 3739): [401] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1265): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1265): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1265): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1265): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1265): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3739): [401] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3739): [401] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3739): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3739): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3739): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3739): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3739): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3739): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3739): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3739): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3739): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3739): 	at com.a.a.k.run(SourceFile:110)
,V/GLSActivity( 1265): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1265): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1265): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1265): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1265): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1265): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3019): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3019): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3019): [1] 5.onFinished: Giving up after 6 failures.
,I/Keyboard.Facilitator.LanguageModelFlusher( 1240): run()
I/Keyboard.Facilitator( 1240): flushDynamicLanguageModels()
,I/ConfigService( 1265): onCreate
,D/HeadsetStateMachine( 2369): Disconnected process message: 10, size: 0
,I/GLSUser ( 1265): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1265): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1265): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1265): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1265): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  822): Explicit concurrent mark sweep GC freed 30198(1372KB) AllocSpace objects, 3(142KB) LOS objects, 31% free, 34MB/50MB, paused 3.418ms total 90.153ms
,E/HttpOperation( 3388): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3388): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3388): 	at jdm.a(PG:82)
E/HttpOperation( 3388): 	at jcs.o(PG:406)
E/HttpOperation( 3388): 	at jcn.a(PG:1379)
E/HttpOperation( 3388): 	at jcs.i(PG:143)
E/HttpOperation( 3388): 	at blb.a(PG:3937)
E/HttpOperation( 3388): 	at czp.a(PG:18188)
E/HttpOperation( 3388): 	at czp.a(PG:9081)
E/HttpOperation( 3388): 	at czq.run(PG:1686)
E/HttpOperation( 3388): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3388): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3388): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3388): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3388): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3388): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3388): 	at jdj.a(PG:4091)
E/HttpOperation( 3388): 	at jdj.a(PG:1125)
E/HttpOperation( 3388): 	at jdm.a(PG:77)
E/HttpOperation( 3388): 	... 12 more
E/HttpOperation( 3388): Caused by: faj: BadAuthentication
E/HttpOperation( 3388): 	at fal.a(PG:38)
E/HttpOperation( 3388): 	at jdj.a(PG:4089)
E/HttpOperation( 3388): 	... 14 more
,I/GLSUser ( 1265): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1265): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1265): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1265): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1265): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3388): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3388): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3388): 	at jdm.a(PG:82)
E/HttpOperation( 3388): 	at jcs.o(PG:406)
E/HttpOperation( 3388): 	at jcn.a(PG:1379)
E/HttpOperation( 3388): 	at jcs.i(PG:143)
E/HttpOperation( 3388): 	at hec.a(PG:42)
E/HttpOperation( 3388): 	at hee.a(PG:102)
E/HttpOperation( 3388): 	at czr.a(PG:65)
E/HttpOperation( 3388): 	at kka.a(PG:108)
E/HttpOperation( 3388): 	at czp.a(PG:19176)
E/HttpOperation( 3388): 	at czp.a(PG:9081)
E/HttpOperation( 3388): 	at czq.run(PG:1686)
E/HttpOperation( 3388): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3388): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3388): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3388): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3388): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3388): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3388): 	at jdj.a(PG:4091)
E/HttpOperation( 3388): 	at jdj.a(PG:1125)
E/HttpOperation( 3388): 	at jdm.a(PG:77)
E/HttpOperation( 3388): 	... 15 more
E/HttpOperation( 3388): Caused by: faj: BadAuthentication
E/HttpOperation( 3388): 	at fal.a(PG:38)
E/HttpOperation( 3388): 	at jdj.a(PG:4089)
E/HttpOperation( 3388): 	... 17 more
,E/ExperimentLoader( 3388): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3388): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3388): 	at jdm.a(PG:82)
E/ExperimentLoader( 3388): 	at jcs.o(PG:406)
E/ExperimentLoader( 3388): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3388): 	at jcs.i(PG:143)
E/ExperimentLoader( 3388): 	at hec.a(PG:42)
E/ExperimentLoader( 3388): 	at hee.a(PG:102)
E/ExperimentLoader( 3388): 	at czr.a(PG:65)
E/ExperimentLoader( 3388): 	at kka.a(PG:108)
E/ExperimentLoader( 3388): 	at czp.a(PG:19176)
E/ExperimentLoader( 3388): 	at czp.a(PG:9081)
E/ExperimentLoader( 3388): 	at czq.run(PG:1686)
E/ExperimentLoader( 3388): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3388): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3388): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3388): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3388): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3388): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3388): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3388): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3388): 	at jdm.a(PG:77)
E/ExperimentLoader( 3388): 	... 15 more
E/ExperimentLoader( 3388): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3388): 	at fal.a(PG:38)
E/ExperimentLoader( 3388): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3388): 	... 17 more
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 199168, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,I/ConfigService( 1265): onDestroy
,D/HeadsetStateMachine( 2369): Disconnected process message: 10, size: 0
,I/art     ( 1265): Explicit concurrent mark sweep GC freed 70303(3MB) AllocSpace objects, 8(729KB) LOS objects, 36% free, 27MB/43MB, paused 2.108ms total 59.924ms
,I/BooksSync( 3618): Starting books sync for 61035162, extras: ade
,V/KeepSync( 3587): Connecting to GoogleApiClient
,I/BooksConfig( 3618): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1265): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1265): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1265): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1265): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1265): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1265): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata,
I/GLSUser ( 1265): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1265): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1265): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1265): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,V/KeepSync( 3587): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3587): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3587): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3587): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1265): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1265): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1265): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1265): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1265): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3618): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3618): Soft error
E/BooksSync( 3618): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3618): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3618): Sync error
E/BooksSync( 3618): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3618): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3618): Finished books sync
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 229320, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1265): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1265): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1265): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1265): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1265): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3587): IOException
E/KeepSync( 3587): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3587): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3587): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3587): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3587): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3587): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3587): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3587): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3587): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3587): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3587): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3587): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3587): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3587): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3587): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3587): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3587): 	... 10 more
W/KeepSync( 3587): Sync result 2
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 229694, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2369): Disconnected process message: 10, size: 0
,V/GoogleAuthProtoRequest( 3739): [403] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1265): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1265): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1265): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1265): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1265): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3739): [403] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3739): [403] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3739): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3739): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3739): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3739): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3739): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3739): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3739): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3739): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3739): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3739): 	at com.a.a.k.run(SourceFile:110)
,I/GLSUser ( 1265): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1265): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1265): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1265): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1265): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3388): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3388): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3388): 	at jdm.a(PG:82)
E/HttpOperation( 3388): 	at jcs.o(PG:406)
E/HttpOperation( 3388): 	at jcn.a(PG:1379)
E/HttpOperation( 3388): 	at jcs.i(PG:143)
E/HttpOperation( 3388): 	at blb.a(PG:3937)
E/HttpOperation( 3388): 	at czp.a(PG:18188)
E/HttpOperation( 3388): 	at czp.a(PG:9081)
E/HttpOperation( 3388): 	at czq.run(PG:1686)
E/HttpOperation( 3388): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3388): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3388): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3388): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3388): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3388): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3388): 	at jdj.a(PG:4091)
E/HttpOperation( 3388): 	at jdj.a(PG:1125)
E/HttpOperation( 3388): 	at jdm.a(PG:77)
E/HttpOperation( 3388): 	... 12 more
E/HttpOperation( 3388): Caused by: faj: BadAuthentication
E/HttpOperation( 3388): 	at fal.a(PG:38)
E/HttpOperation( 3388): 	at jdj.a(PG:4089)
E/HttpOperation( 3388): 	... 14 more
,I/GLSUser ( 1265): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1265): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1265): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1265): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1265): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/HttpOperation( 3388): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3388): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3388): 	at jdm.a(PG:82)
E/HttpOperation( 3388): 	at jcs.o(PG:406)
E/HttpOperation( 3388): 	at jcn.a(PG:1379)
E/HttpOperation( 3388): 	at jcs.i(PG:143)
E/HttpOperation( 3388): 	at hec.a(PG:42)
E/HttpOperation( 3388): 	at hee.a(PG:102)
E/HttpOperation( 3388): 	at czr.a(PG:65)
E/HttpOperation( 3388): 	at kka.a(PG:108)
E/HttpOperation( 3388): 	at czp.a(PG:19176)
E/HttpOperation( 3388): 	at czp.a(PG:9081)
E/HttpOperation( 3388): 	at czq.run(PG:1686)
E/HttpOperation( 3388): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3388): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3388): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3388): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3388): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3388): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3388): 	at jdj.a(PG:4091)
E/HttpOperation( 3388): 	at jdj.a(PG:1125)
E/HttpOperation( 3388): 	at jdm.a(PG:77)
E/HttpOperation( 3388): 	... 15 more
E/HttpOperation( 3388): Caused by: faj: BadAuthentication
E/HttpOperation( 3388): 	at fal.a(PG:38)
E/HttpOperation( 3388): 	at jdj.a(PG:4089)
E/HttpOperation( 3388): 	... 17 more
,E/ExperimentLoader( 3388): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token,
E/ExperimentLoader( 3388): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3388): 	at jdm.a(PG:82),
E/ExperimentLoader( 3388): 	at jcs.o(PG:406),
E/ExperimentLoader( 3388): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3388): 	at jcs.i(PG:143)
E/ExperimentLoader( 3388): 	at hec.a(PG:42)
E/ExperimentLoader( 3388): 	at hee.a(PG:102)
,E/ExperimentLoader( 3388): 	at czr.a(PG:65)
E/ExperimentLoader( 3388): 	at kka.a(PG:108)
E/ExperimentLoader( 3388): 	at czp.a(PG:19176)
E/ExperimentLoader( 3388): 	at czp.a(PG:9081)
E/ExperimentLoader( 3388): 	at czq.run(PG:1686)
E/ExperimentLoader( 3388): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3388): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3388): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3388): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3388): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3388): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3388): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3388): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3388): 	at jdm.a(PG:77)
E/ExperimentLoader( 3388): 	... 15 more
E/ExperimentLoader( 3388): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3388): 	at fal.a(PG:38)
E/ExperimentLoader( 3388): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3388): 	... 17 more
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 290554, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,I/jxcore-log( 3679): Connected to the server!
I/jxcore-log( 3679): 
,I/chromium( 3679): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,D/HeadsetStateMachine( 2369): Disconnected process message: 10, size: 0
,I/BooksSync( 3618): Starting books sync for 61035162, extras: ade
,V/KeepSync( 3587): Connecting to GoogleApiClient
,I/BooksConfig( 3618): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1265): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1265): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1265): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1265): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1265): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1265): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1265): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1265): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1265): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1265): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,V/KeepSync( 3587): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3587): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3587): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3587): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1265): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1265): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1265): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1265): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1265): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  822): Explicit concurrent mark sweep GC freed 31497(1329KB) AllocSpace objects, 12(851KB) LOS objects, 31% free, 34MB/50MB, paused 1.447ms total 71.227ms
,E/BooksAccountManager( 3618): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3618): Soft error
E/BooksSync( 3618): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3618): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3618): Sync error
E/BooksSync( 3618): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3618): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3618): Finished books sync
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 320874, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1265): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1265): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1265): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1265): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1265): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3587): IOException
E/KeepSync( 3587): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3587): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3587): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3587): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3587): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3587): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3587): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3587): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3587): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3587): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3587): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3587): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3587): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3587): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3587): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3587): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3587): 	... 10 more
W/KeepSync( 3587): Sync result 2
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 321532, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,V/GLSActivity( 1265): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1265): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1265): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1265): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1265): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1265): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1265): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1265): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1265): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1265): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1265): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1265): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1265): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 3019): Failed to get auth token: User intervention required. Notification has been pushed.,
E/PlayEventLogger( 3019): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.,
E/PlayEventLogger( 3019): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 3019): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3019): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/PlayEventLogger( 3019): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3019): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 3019): Ignoring header User-Agent because its value was null.,
,D/HeadsetStateMachine( 2369): Disconnected process message: 10, size: 0
,D/WifiService(  822): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@3f82f80}
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-47
,D/WifiService(  822): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@3f82f80}
,D/WifiService(  822): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@2fc6e98}
,E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::injectLocation(GpsExtLocation):857]: error! inject position failed
,D/WifiService(  822): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@2fc6e98}
,D/HeadsetStateMachine( 2369): Disconnected process message: 10, size: 0
,V/GoogleAuthProtoRequest( 3739): [404] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1265): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1265): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1265): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1265): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1265): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3739): [404] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3739): [404] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3739): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3739): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3739): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3739): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3739): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3739): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3739): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3739): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3739): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3739): 	at com.a.a.k.run(SourceFile:110)
,I/art     ( 1265): Explicit concurrent mark sweep GC freed 51519(2MB) AllocSpace objects, 17(1874KB) LOS objects, 36% free, 27MB/43MB, paused 1.479ms total 67.045ms
,I/GLSUser ( 1265): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1265): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1265): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1265): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1265): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3388): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3388): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3388): 	at jdm.a(PG:82)
E/HttpOperation( 3388): 	at jcs.o(PG:406)
E/HttpOperation( 3388): 	at jcn.a(PG:1379)
E/HttpOperation( 3388): 	at jcs.i(PG:143)
E/HttpOperation( 3388): 	at blb.a(PG:3937)
E/HttpOperation( 3388): 	at czp.a(PG:18188)
E/HttpOperation( 3388): 	at czp.a(PG:9081)
E/HttpOperation( 3388): 	at czq.run(PG:1686)
E/HttpOperation( 3388): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3388): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3388): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3388): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3388): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3388): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3388): 	at jdj.a(PG:4091)
E/HttpOperation( 3388): 	at jdj.a(PG:1125)
E/HttpOperation( 3388): 	at jdm.a(PG:77)
E/HttpOperation( 3388): 	... 12 more
E/HttpOperation( 3388): Caused by: faj: BadAuthentication
E/HttpOperation( 3388): 	at fal.a(PG:38)
E/HttpOperation( 3388): 	at jdj.a(PG:4089)
E/HttpOperation( 3388): 	... 14 more
,I/GLSUser ( 1265): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1265): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1265): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1265): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1265): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3388): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3388): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3388): 	at jdm.a(PG:82)
E/HttpOperation( 3388): 	at jcs.o(PG:406)
E/HttpOperation( 3388): 	at jcn.a(PG:1379)
E/HttpOperation( 3388): 	at jcs.i(PG:143)
E/HttpOperation( 3388): 	at hec.a(PG:42)
E/HttpOperation( 3388): 	at hee.a(PG:102)
E/HttpOperation( 3388): 	at czr.a(PG:65)
E/HttpOperation( 3388): 	at kka.a(PG:108)
E/HttpOperation( 3388): 	at czp.a(PG:19176)
E/HttpOperation( 3388): 	at czp.a(PG:9081)
E/HttpOperation( 3388): 	at czq.run(PG:1686)
E/HttpOperation( 3388): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3388): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3388): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3388): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3388): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3388): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3388): 	at jdj.a(PG:4091)
E/HttpOperation( 3388): 	at jdj.a(PG:1125)
E/HttpOperation( 3388): 	at jdm.a(PG:77)
E/HttpOperation( 3388): 	... 15 more
E/HttpOperation( 3388): Caused by: faj: BadAuthentication
E/HttpOperation( 3388): 	at fal.a(PG:38)
E/HttpOperation( 3388): 	at jdj.a(PG:4089)
E/HttpOperation( 3388): 	... 17 more
E/ExperimentLoader( 3388): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3388): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3388): 	at jdm.a(PG:82)
E/ExperimentLoader( 3388): 	at jcs.o(PG:406)
E/ExperimentLoader( 3388): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3388): 	at jcs.i(PG:143)
E/ExperimentLoader( 3388): 	at hec.a(PG:42)
E/ExperimentLoader( 3388): 	at hee.a(PG:102)
E/ExperimentLoader( 3388): 	at czr.a(PG:65)
E/ExperimentLoader( 3388): 	at kka.a(PG:108)
E/ExperimentLoader( 3388): 	at czp.a(PG:19176)
E/ExperimentLoader( 3388): 	at czp.a(PG:9081)
E/ExperimentLoader( 3388): 	at czq.run(PG:1686)
E/ExperimentLoader( 3388): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3388): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3388): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3388): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3388): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3388): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3388): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3388): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3388): 	at jdm.a(PG:77)
E/ExperimentLoader( 3388): 	... 15 more
E/ExperimentLoader( 3388): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3388): 	at fal.a(PG:38)
E/ExperimentLoader( 3388): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3388): 	... 17 more
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 443068, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2369): Disconnected process message: 10, size: 0
,I/BooksSync( 3618): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3618): GmsCore Version = 7.8.99 (2134222-430)
,V/KeepSync( 3587): Connecting to GoogleApiClient
,I/GLSUser ( 1265): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1265): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1265): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1265): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1265): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1265): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1265): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1265): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1265): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1265): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
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
,V/KeepSync( 3587): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3587): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3587): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3587): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1265): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1265): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1265): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1265): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1265): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3618): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3618): Soft error
E/BooksSync( 3618): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3618): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3618): Sync error
E/BooksSync( 3618): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3618): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3618): Finished books sync
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 474073, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1265): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1265): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1265): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1265): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1265): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3587): IOException
E/KeepSync( 3587): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3587): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3587): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3587): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3587): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3587): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3587): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3587): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3587): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3587): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3587): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3587): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3587): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3587): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3587): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3587): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3587): 	... 10 more
W/KeepSync( 3587): Sync result 2
D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 475341, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2369): Disconnected process message: 10, size: 0
,I/art     (  822): Explicit concurrent mark sweep GC freed 37500(1707KB) AllocSpace objects, 13(490KB) LOS objects, 31% free, 34MB/50MB, paused 1.634ms total 75.467ms
,D/HeadsetStateMachine( 2369): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2369): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2369): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2369): Disconnected process message: 10, size: 0
,I/GLSUser ( 1265): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1265): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1265): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1265): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1265): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3388): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3388): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3388): 	at jdm.a(PG:82)
E/HttpOperation( 3388): 	at jcs.o(PG:406)
E/HttpOperation( 3388): 	at jcn.a(PG:1379)
E/HttpOperation( 3388): 	at jcs.i(PG:143)
,E/HttpOperation( 3388): 	at blb.a(PG:3937)
E/HttpOperation( 3388): 	at czp.a(PG:18188)
E/HttpOperation( 3388): 	at czp.a(PG:9081)
E/HttpOperation( 3388): 	at czq.run(PG:1686)
E/HttpOperation( 3388): 	,at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3388): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3388): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3388): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3388): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3388): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3388): 	at jdj.a(PG:4091)
E/HttpOperation( 3388): 	at jdj.a(PG:1125)
E/HttpOperation( 3388): 	at jdm.a(PG:77)
E/HttpOperation( 3388): 	... 12 more,
E/HttpOperation( 3388): Caused by: faj: BadAuthentication
E/HttpOperation( 3388): 	at fal.a(PG:38)
E/HttpOperation( 3388): 	at jdj.a(PG:4089)
E/HttpOperation( 3388): 	... 14 more
,I/GLSUser ( 1265): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1265): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1265): [GLSUser] Extracting token using key: Auth,
W/GLSActivity( 1265): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,V/GLSActivity( 1265): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3388): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3388): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3388): 	at jdm.a(PG:82)
E/HttpOperation( 3388): 	at jcs.o(PG:406)
E/HttpOperation( 3388): 	at jcn.a(PG:1379)
E/HttpOperation( 3388): 	at jcs.i(PG:143)
E/HttpOperation( 3388): 	at hec.a(PG:42)
E/HttpOperation( 3388): 	at hee.a(PG:102)
,E/HttpOperation( 3388): 	at czr.a(PG:65)
E/HttpOperation( 3388): 	at kka.a(PG:108)
E/HttpOperation( 3388): 	at czp.a(PG:19176)
E/HttpOperation( 3388): 	at czp.a(PG:9081)
E/HttpOperation( 3388): 	at czq.run(PG:1686)
E/HttpOperation( 3388): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3388): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3388): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3388): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3388): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3388): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3388): 	at jdj.a(PG:4091)
E/HttpOperation( 3388): 	at jdj.a(PG:1125)
E/HttpOperation( 3388): 	at jdm.a(PG:77)
E/HttpOperation( 3388): 	... 15 more
,E/HttpOperation( 3388): Caused by: faj: BadAuthentication
E/HttpOperation( 3388): 	at fal.a(PG:38)
E/HttpOperation( 3388): 	at jdj.a(PG:4089)
E/HttpOperation( 3388): 	... 17 more
E/ExperimentLoader( 3388): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3388): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3388): 	at jdm.a(PG:82)
E/ExperimentLoader( 3388): 	at jcs.o(PG:406)
E/ExperimentLoader( 3388): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3388): 	at jcs.i(PG:143)
E/ExperimentLoader( 3388): 	at hec.a(PG:42)
E/ExperimentLoader( 3388): 	at hee.a(PG:102)
E/ExperimentLoader( 3388): 	at czr.a(PG:65)
E/ExperimentLoader( 3388): 	at kka.a(PG:108)
E/ExperimentLoader( 3388): ,	at czp.a(PG:19176)
E/ExperimentLoader( 3388): 	at czp.a(PG:9081)
E/ExperimentLoader( 3388): 	at czq.run(PG:1686)
E/ExperimentLoader( 3388): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3388): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3388): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3388): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3388): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3388): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3388): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3388): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3388): 	at jdm.a(PG:77)
E/ExperimentLoader( 3388): 	... 15 more
E/ExperimentLoader( 3388): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3388): 	,at fal.a(PG:38)
E/ExperimentLoader( 3388): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3388): 	... 17 more
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 693221, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2369): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2369): Disconnected process message: 10, size: 0
,I/BooksSync( 3618): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3618): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1265): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1265): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1265): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1265): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1265): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1265): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1265): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1265): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1265): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1265): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3618): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3618): Soft error
E/BooksSync( 3618): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3618): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3618): Sync error
E/BooksSync( 3618): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3618): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3618): Finished books sync
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 755183, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2369): Disconnected process message: 10, size: 0
,V/KeepSync( 3587): Connecting to GoogleApiClient
,I/GLSUser ( 1265): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1265): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1265): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1265): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1265): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,V/KeepSync( 3587): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3587): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3587): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3587): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1265): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1265): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1265): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1265): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1265): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3587): IOException
E/KeepSync( 3587): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3587): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3587): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3587): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3587): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3587): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3587): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3587): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3587): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3587): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3587): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3587): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3587): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3587): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3587): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3587): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3587): 	... 10 more
W/KeepSync( 3587): Sync result 2
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 757622, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,V/GoogleAuthProtoRequest( 3739): [405] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1265): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1265): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1265): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1265): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1265): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3739): [405] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3739): [405] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3739): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3739): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3739): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3739): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3739): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3739): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3739): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3739): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3739): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3739): 	at com.a.a.k.run(SourceFile:110)
,D/HeadsetStateMachine( 2369): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2369): Disconnected process message: 10, size: 0
,I/art     ( 1265): Explicit concurrent mark sweep GC freed 58172(3MB) AllocSpace objects, 13(1434KB) LOS objects, 36% free, 27MB/43MB, paused 1.459ms total 65.557ms
,D/HeadsetStateMachine( 2369): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2369): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2369): Disconnected process message: 10, size: 0
,W/bt-btm  ( 2369): Stopping oneshot timer
,I/ActivityManager(  822): Start proc 4169:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider
,I/GAv4    ( 4169): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4169):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4169):   adb logcat -s GAv4
,W/GAv4    ( 4169): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.,
,W/GAv4    ( 4169): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4169): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  822): Killing 3290:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,D/HeadsetStateMachine( 2369): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2369): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2369): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2369): Disconnected process message: 10, size: 0
,V/GoogleAuthProtoRequest( 3739): [406] a.<init>: mAccountName set to: thalitester@gmail.com
,D/GCM     ( 1265): Message class com.google.f.a.a.i
,I/GLSUser ( 1265): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1265): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1265): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1265): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1265): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  822): Explicit concurrent mark sweep GC freed 43348(1991KB) AllocSpace objects, 8(505KB) LOS objects, 31% free, 34MB/50MB, paused 1.457ms total 54.955ms
,W/ExperimentUpdateService( 3739): [406] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3739): [406] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3739): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3739): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3739): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3739): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3739): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3739): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3739): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3739): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3739): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3739): 	at com.a.a.k.run(SourceFile:110)
,V/GoogleAuthProtoRequest( 3739): [407] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1265): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1265): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1265): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1265): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1265): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3739): [407] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3739): [407] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3739): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3739): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3739): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3739): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3739): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3739): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3739): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3739): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3739): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3739): 	at com.a.a.k.run(SourceFile:110)
,D/HeadsetStateMachine( 2369): Disconnected process message: 10, size: 0
,I/GLSUser ( 1265): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1265): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1265): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1265): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1265): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3388): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3388): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3388): 	at jdm.a(PG:82)
E/HttpOperation( 3388): 	at jcs.o(PG:406)
E/HttpOperation( 3388): 	at jcn.a(PG:1379)
E/HttpOperation( 3388): 	at jcs.i(PG:143)
E/HttpOperation( 3388): 	at blb.a(PG:3937)
E/HttpOperation( 3388): 	at czp.a(PG:18188)
E/HttpOperation( 3388): 	at czp.a(PG:9081)
E/HttpOperation( 3388): 	at czq.run(PG:1686)
E/HttpOperation( 3388): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3388): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3388): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3388): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3388): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3388): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3388): 	at jdj.a(PG:4091)
E/HttpOperation( 3388): 	at jdj.a(PG:1125)
E/HttpOperation( 3388): 	at jdm.a(PG:77)
E/HttpOperation( 3388): 	... 12 more
E/HttpOperation( 3388): Caused by: faj: BadAuthentication
E/HttpOperation( 3388): 	at fal.a(PG:38)
E/HttpOperation( 3388): 	at jdj.a(PG:4089)
E/HttpOperation( 3388): 	... 14 more
,I/GLSUser ( 1265): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1265): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1265): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1265): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1265): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/HttpOperation( 3388): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3388): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3388): 	at jdm.a(PG:82)
,E/HttpOperation( 3388): 	at jcs.o(PG:406)
E/HttpOperation( 3388): 	at jcn.a(PG:1379)
E/HttpOperation( 3388): 	at jcs.i(PG:143)
E/HttpOperation( 3388): 	at hec.a(PG:42)
E/HttpOperation( 3388): 	at hee.a(PG:102)
E/HttpOperation( 3388): 	at czr.a(PG:65)
E/HttpOperation( 3388): 	at kka.a(PG:108)
E/HttpOperation( 3388): 	at czp.a(PG:19176)
E/HttpOperation( 3388): 	at czp.a(PG:9081)
E/HttpOperation( 3388): 	at czq.run(PG:1686)
E/HttpOperation( 3388): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3388): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3388): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3388): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3388): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3388): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3388): 	at jdj.a(PG:4091)
E/HttpOperation( 3388): 	at jdj.a(PG:1125)
E/HttpOperation( 3388): 	at jdm.a(PG:77)
E/HttpOperation( 3388): 	... 15 more
E/HttpOperation( 3388): Caused by: faj: BadAuthentication
E/HttpOperation( 3388): 	at fal.a(PG:38)
E/HttpOperation( 3388): 	at jdj.a(PG:4089)
E/HttpOperation( 3388): 	... 17 more
E/ExperimentLoader( 3388): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3388): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3388): 	at jdm.a(PG:82)
E/ExperimentLoader( 3388): 	at jcs.o(PG:406)
E/ExperimentLoader( 3388): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3388): 	at jcs.i(PG:143)
E/ExperimentLoader( 3388): 	at hec.a(PG:42)
E/ExperimentLoader( 3388): 	at hee.a(PG:102)
E/ExperimentLoader( 3388): 	at czr.a(PG:65)
E/ExperimentLoader( 3388): 	at kka.a(PG:108)
E/ExperimentLoader( 3388): 	at czp.a(PG:19176)
E/ExperimentLoader( 3388): 	at czp.a(PG:9081)
E/ExperimentLoader( 3388): 	at czq.run(PG:1686)
E/ExperimentLoader( 3388): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3388): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3388): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3388): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3388): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3388): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3388): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3388): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3388): 	at jdm.a(PG:77)
E/ExperimentLoader( 3388): 	... 15 more
E/ExperimentLoader( 3388): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3388): 	at fal.a(PG:38)
E/ExperimentLoader( 3388): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3388): 	... 17 more
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 1193125, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,V/GoogleAuthProtoRequest( 3739): [408] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1265): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1265): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1265): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1265): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1265): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3739): [408] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3739): [408] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3739): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3739): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3739): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3739): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3739): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3739): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3739): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3739): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3739): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3739): 	at com.a.a.k.run(SourceFile:110)
,D/HeadsetStateMachine( 2369): Disconnected process message: 10, size: 0
,I/UsageStatsService(  822): User[0] Flushing usage stats to disk
,D/HeadsetStateMachine( 2369): Disconnected process message: 10, size: 0
,I/BooksSync( 3618): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3618): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1265): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1265): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1265): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1265): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1265): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1265): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1265): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1265): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1265): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1265): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3618): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3618): Soft error
E/BooksSync( 3618): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3618): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3618): Sync error
E/BooksSync( 3618): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3618): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3618): Finished books sync
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1258932, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2369): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2369): Disconnected process message: 10, size: 0
,V/GoogleAuthProtoRequest( 3739): [409] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1265): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1265): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1265): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1265): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1265): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3739): [409] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3739): [409] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3739): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3739): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3739): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3739): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3739): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3739): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3739): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3739): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3739): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3739): 	at com.a.a.k.run(SourceFile:110)
,V/KeepSync( 3587): Connecting to GoogleApiClient
,I/GLSUser ( 1265): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1265): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1265): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1265): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1265): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,V/KeepSync( 3587): GoogleApiClient failed to connect with error code: 4
E/SQLiteLog( 3587): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3587): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3587): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1265): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1265): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1265): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1265): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1265): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3587): IOException
E/KeepSync( 3587): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3587): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3587): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3587): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3587): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3587): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3587): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3587): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3587): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3587): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3587): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3587): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3587): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3587): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3587): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3587): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3587): 	... 10 more
W/KeepSync( 3587): Sync result 2
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 1293874, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2369): Disconnected process message: 10, size: 0
,V/GoogleAuthProtoRequest( 3739): [410] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1265): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1265): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1265): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1265): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1265): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3739): [410] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3739): [410] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3739): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3739): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3739): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3739): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3739): 	at com.google.android.gms.gcm.c.run(Unknown Source)
,W/ExperimentUpdateService( 3739): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3739): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3739): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3739): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3739): 	at com.a.a.k.run(SourceFile:110)
,D/HeadsetStateMachine( 2369): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2369): Disconnected process message: 10, size: 0
,I/art     (  822): Explicit concurrent mark sweep GC freed 37724(1741KB) AllocSpace objects, 10(348KB) LOS objects, 31% free, 34MB/50MB, paused 1.844ms total 80.692ms
,I/art     ( 1265): Explicit concurrent mark sweep GC freed 69572(3MB) AllocSpace objects, 10(1102KB) LOS objects, 37% free, 27MB/43MB, paused 941us total 43.355ms
,D/HeadsetStateMachine( 2369): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2369): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2369): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2369): Disconnected process message: 10, size: 0
,V/GoogleAuthProtoRequest( 3739): [411] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1265): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1265): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1265): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1265): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1265): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3739): [411] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3739): [411] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3739): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3739): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3739): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3739): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3739): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3739): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3739): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3739): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3739): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3739): 	at com.a.a.k.run(SourceFile:110)
,D/HeadsetStateMachine( 2369): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2369): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2369): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2369): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2369): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2369): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2369): Disconnected process message: 10, size: 0
,I/ProcessStatsService(  822): Prepared write state in 8ms
,I/ProcessStatsService(  822): Pruning old procstats: /data/system/procstats/state-2015-12-16-02-32-37.bin
,I/EventLogService( 1774): Opted in for usage reporting
I/EventLogService( 1774): Aggregate from 1450280610768 (log), 1450280610768 (data)
,W/EventLogAggregator( 1774): Unknown tag: snet_gcore
W/EventLogAggregator( 1774): Unknown tag: snet_launch_service
,I/ServiceDumpSys( 1774): dumping service [account]
,D/HeadsetStateMachine( 2369): Disconnected process message: 10, size: 0
,W/bt-btm  ( 2369): Stopping oneshot timer
,I/GLSUser ( 1265): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2: email
,I/GLSUser ( 1265): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2: email without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1265): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1265): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1265): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/HeadsetStateMachine( 2369): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2369): Disconnected process message: 10, size: 0
,I/ActivityManager(  822): Killing 3438:com.android.defcontainer/u0a7 (adj 15): empty for 1825s
,I/ActivityManager(  822): Killing 3537:com.google.android.apps.docs/u0a46 (adj 15): empty for 1826s
,TIME-OUT KILL (timeout was 1800000ms)
```
