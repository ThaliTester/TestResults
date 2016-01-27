#### Test 564496604206eac_thali05_motorola-Nexus 6 Logs


```
--------- beginning of main
D/Finsky  ( 3610): [385] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,V/GLSActivity( 1136): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 1136): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1136): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1136): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1136): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1136): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 3610): [385] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
D/AndroidRuntime( 3803): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 3803): CheckJNI is OFF
D/AndroidRuntime( 3803): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  818): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/WindowManager(  818): addAppToken: AppWindowToken{a61945d token=Token{155d8e34 ActivityRecord{277e7d07 u0 com.test.thalitest/.MainActivity t28}}} to stack=1 task=28 at 0
V/WindowManager(  818): Adding window Window{2622191e u0 Starting com.test.thalitest} at 2 of 7 (after Window{3f83f7bc u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
I/HotwordDetector( 1483): Closing mic
I/MicrophoneInputStream( 1483): mic_close com.google.android.apps.gsa.speech.audio.u@2e415b91
D/AndroidRuntime( 3803): Shutting down VM
D/audio_hw_primary(  356): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  356): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  356): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1483): Hotword detection finished
I/HotwordRecognitionRnr( 1483): Stopping hotword detection.
I/ActivityManager(  818): Start proc 3818:com.test.thalitest/u0a265 for activity com.test.thalitest/.MainActivity
I/ActivityManager(  818): Killing 3541:com.android.musicfx/u0a18 (adj 15): empty #17
,I/ActivityManager(  818): Killing 3518:com.google.android.partnersetup/u0a16 (adj 15): empty #18
,E/LocSvc_IzatApiV02(  818): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1660896531
E/LocSvc_IzatApiV02(  818): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,I/kickstart(  868): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
I/kickstart(  868): STATUS: Wrote to /sys/power/wake_lock
,E/kickstart(  868): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2
I/kickstart(  868): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2' for writing
,I/WebViewFactory( 3818): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3818): Time to load native libraries: 2 ms (timestamps 3623-3625)
I/LibraryLoader( 3818): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3818): Binding Chromium to main looper Looper (main, tid 1) {3a1b3ff0}
I/LibraryLoader( 3818): Expected native library version number "",actual native library version number ""
I/chromium( 3818): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3818): Initializing chromium process, singleProcess=true
,W/art     ( 3818): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3818): ApplicationContext is null in ApplicationStatus
,W/chromium( 3818): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3818): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3818): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno  ( 3818): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/BluetoothManagerService(  818): Message: 20
D/BluetoothManagerService(  818): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@281505ce:true
,W/art     ( 3818): Attempt to remove local handle scope entry from IRT, ignoring
,I/art     ( 1136): Explicit concurrent mark sweep GC freed 20251(1191KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 4.756ms total 42.432ms
,W/AwContents( 3818): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3818): CordovaWebView is running on device made by: motorola
,W/art     ( 3818): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3818): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3818): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,D/Atlas   ( 3818): Validating map...
,V/WindowManager(  818): Adding window Window{12b47e7e u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{2622191e u0 Starting com.test.thalitest})
,W/chromium( 3818): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3818): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3818): Enabling debug mode 0
,I/Keyboard.Facilitator( 1231): onFinishInput()
,I/ActivityManager(  818): Displayed com.test.thalitest/.MainActivity: +862ms
,W/BindingManager( 3818): Cannot call determinedVisibility() - never saw a connection for the pid: 3818
,D/JsMessageQueue( 3818): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3818): JniHelper::setJavaVM(0xb489d200), pthread_self() = -1580383744
,I/chromium( 3818): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/kickstart(  868): STATUS: Received file 'm9kefs2'
I/kickstart(  868): STATUS: 950272 bytes transferred in 0.996544 seconds
I/kickstart(  868): STATUS: Successfully downloaded files from target 
I/kickstart(  868): STATUS: Wrote to /sys/power/wake_unlock
,I/kickstart(  868): STATUS: Sahara protocol completed
,W/jxcore-log( 3818): Initializing JXcore engine
W/jxcore-log( 3818): JXcore engine is ready
,W/Thread-425( 3872): type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[11838]" dev="sockfs" ino=11838 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-425( 3872): type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,W/Thread-425( 3872): type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[12564]" dev="sockfs" ino=12564 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/Thread-425( 3872): type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[23847]" dev="sockfs" ino=23847 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 3818): Starting JXcore engine
,W/jxcore-log( 3818): Platform android
W/jxcore-log( 3818): 
,W/jxcore-log( 3818): Process ARCH arm
W/jxcore-log( 3818): 
,I/jxcore-log( 3818): JXcore Cordova bridge is ready!
I/jxcore-log( 3818): 
W/jxcore-log( 3818): JXcore engine is started
,I/jxcore-log( 3818): Toggling radios to true
I/jxcore-log( 3818): 
,D/BluetoothAdapter( 3818): enable(): BT is already enabled..!,
,D/WifiService(  818): setWifiEnabled: true pid=3818, uid=10265
,E/WifiService(  818): Invoking mWifiStateMachine.setWifiEnabled
D/WifiService(  818): New client listening to asynchronous messages
,I/jxcore-log( 3818): Radios toggled,
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): My device name is: motorola-Nexus 6
I/jxcore-log( 3818): 
,I/wpa_supplicant( 1044): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  818): WifiStateMachine: Leaving Connected state
,E/WifiConfigStore(  818): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  352): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1136): Read error: ssl=0x9cda8a00: I/O error during system call, Connection timed out
,V/NativeCrypto( 1136): SSL shutdown failed: ssl=0x9cda8a00: I/O error during system call, Broken pipe
,D/ConnectivityService(  818): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10011
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  818): ValidatedState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  818): DefaultState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  818): Forcing reevaluation
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  818): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  818): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
E/WifiStateMachine(  818): Start Disconnecting Watchdog 1
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  818): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
D/ConnectivityService(  818): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  818): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/ConnectivityService(  818): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityService(  818): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,E/WifiStateMachine(  818): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,D/CommandListener(  352): Clearing all IP addresses on wlan0
,D/ConnectivityService(  818): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler( 1066): CM callback handler got msg 524292
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  818): OfflineState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  818): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  818): Disconnected - quitting
D/CSLegacyTypeTracker(  818): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  818): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  818): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  818): MasterInitialState.processMessage what=3
D/ConnectivityService(  818): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/WifiNetworkAgent(  818): NetworkAgent: NetworkAgent channel lost
,E/WifiStateMachine(  818): CMD_AUTO_CONNECT sup state CompletedState my state DisconnectedState nid=0 roam=3
E/WifiStateMachine(  818): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=0
D/NetworkChangeNotifierAutoDetect( 1483): Network connectivity changed, type is: 6
I/NetworkMonitor( 3079): type=WIFI subType= reason=null isConnected=false
,D/ConnectivityService(  818): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  818): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/Tethering(  818): MasterInitialState.processMessage what=3
,V/MusicLeanback( 3079): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
D/PhoneInterfaceManager( 1281): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1281): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  818): getDataEnabled: retVal=false
,E/GpsLocationProvider(  818): No APN found to select.
,E/WifiConfigStore(  818): Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiConfigStore(  818): will read network variables netId=0
,I/ActivityManager(  818): Start proc 3880:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.steen.receiver.ConnectivityChangeReceiver
,E/WifiStateMachine(  818): CMD_AUTO_CONNECT did save config ->  nid=0
,E/WifiConfigStore(  818): will read network variables netId=0
,D/PhoneInterfaceManager( 1281): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
,E/PhoneInterfaceManager( 1281): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  818): getDataEnabled: retVal=false
,E/GpsLocationProvider(  818): No APN found to select.
,I/ActivityManager(  818): Start proc 3906:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,I/ActivityManager(  818): Killing 3572:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,D/SprintDMReceiver( 3906): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3906): simOperator:  IMSI: null
D/SprintDMReceiver( 3906): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1774): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1774): onCreate
,D/SystemUpdateService( 1774): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1774): active receiver: enabled
,I/SystemUpdateService( 1774): showing system update notification
,I/iu.Environment( 1774): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1774): num queued entries: 0
I/iu.UploadsManager( 1774): num updated entries: 0
I/iu.SyncManager( 1774): NEXT; no task
,D/ChimeraCfgMgr( 1774): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/ValidateNoPeople(  818): skipping global notification
,V/SystemUpdateService( 1774): retry (wakeup: false) in 3599969 ms
,I/Babel   ( 2804): connection state changed from CONNECTED to DISCONNECTED
,I/ActivityManager(  818): Start proc 3926:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,D/SystemUpdateService( 1774): onDestroy
,I/ActivityManager(  818): Killing 3277:com.google.android.apps.photos/u0a71 (adj 15): empty #17
,I/GAv4    ( 3926): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3926):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3926):   adb logcat -s GAv4
,W/GAv4    ( 3926): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3926): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3926): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 3926): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3926): Time to load native libraries: 1 ms (timestamps 8128-8129)
I/LibraryLoader( 3926): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3926): Binding Chromium to main looper Looper (main, tid 1) {b2bad57}
,I/LibraryLoader( 3926): Expected native library version number "",actual native library version number ""
I/chromium( 3926): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3926): Initializing chromium process, singleProcess=true
,W/art     ( 3926): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3926): ApplicationContext is null in ApplicationStatus
,W/chromium( 3926): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3926): validate_display:255 error 3008 (EGL_BAD_DISPLAY),
E/libEGL  ( 3926): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3926): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,W/AudioManagerAndroid( 3926): Requires BLUETOOTH permission
,I/art     (  818): Explicit concurrent mark sweep GC freed 38704(1857KB) AllocSpace objects, 8(128KB) LOS objects, 31% free, 34MB/50MB, paused 1.552ms total 63.128ms
I/NSApplication( 3926): Starting up...
,I/ActivityManager(  818): Start proc 3982:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,I/ActivityManager(  818): Start proc 4006:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
I/ActivityManager(  818): Killing 2578:android.process.acore/u0a5 (adj 15): empty #17
,V/GLSActivity( 1136): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1136): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1136): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1136): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1136): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1136): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3610): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3610): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3610): [1] 5.onFinished: Scheduling replication attempt 3.
,I/ActivityManager(  818): Killing 3427:com.google.android.gm/u0a78 (adj 15): empty #17
,I/wpa_supplicant( 1044): wlan0: Trying to associate with SSID 'NG7005g'
,I/ActivityManager(  818): Killing 3650:com.google.android.gms:car/u0a11 (adj 15): empty #17
,V/MusicLeanback( 3079): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/wpa_supplicant( 1044): wlan0: Associated with c0:ff:d4:d3:aa:4a
,D/SprintDMReceiver( 3906): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3906): simOperator:  IMSI: null
D/SprintDMReceiver( 3906): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1774): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1774): onCreate
,D/SystemUpdateService( 1774): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1774): active receiver: enabled
,I/SystemUpdateService( 1774): showing system update notification
,I/wpa_supplicant( 1044): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1044): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=0 id_str=]
,D/ConnectivityService(  818): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} }
,E/WifiConfigStore(  818): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  818): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  818): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  352): Setting iface cfg
E/WifiStateMachine(  818): Start Dhcp Watchdog 2
,I/ValidateNoPeople(  818): skipping global notification
,E/WifiStateMachine(  818):  WifiLinkLayerStats: 
E/WifiStateMachine(  818):  my bss beacon rx: 395
E/WifiStateMachine(  818):  RSSI mgmt: -50
E/WifiStateMachine(  818):  BE :  rx=196 tx=146 lost=0 retries=0
E/WifiStateMachine(  818):  BK :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  818):  VI :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  818):  VO :  rx=4 tx=0 lost=0 retries=0
E/WifiStateMachine(  818):  on_time : 13741 tx_time=270 rx_time=598 scan_time=0
,V/SystemUpdateService( 1774): retry (wakeup: false) in 3599970 ms
,D/ChimeraCfgMgr( 1774): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ConnectivityService(  818): updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
D/SystemUpdateService( 1774): onDestroy
,E/native  (  818): do suspend false
,E/WifiStateMachine(  818): scanCount==0 - aborting,
,I/dhcpcd  ( 4031): version 5.5.6 starting
,I/dhcpcd  ( 4031): wlan0: rebinding lease of 192.168.1.122
,I/dhcpcd  ( 4031): wlan0: acknowledged 192.168.1.122 from 192.168.1.1
,I/dhcpcd  ( 4031): wlan0: leased 192.168.1.122 for 86400 seconds,
,I/jxcore-log( 3818): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 3818): 
,D/ConnectivityService(  818): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  818): Adding iface wlan0 to network 101
,E/WifiStateMachine(  818): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  818): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  818): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  818): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  818): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  818): Setting Dns servers for network 101 to [/192.168.1.1]
,D/ConnectivityService(  818): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  818): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  818): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  818):    accepting network in place of null
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  818): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  818): Connected
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  818): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  818): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
,D/ConnectivityService(  818): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} }
,D/ConnectivityService(  818): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1066): CM callback handler got msg 524290
,D/CSLegacyTypeTracker(  818): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  818): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  818): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  818): MasterInitialState.processMessage what=3
,D/NetworkChangeNotifierAutoDetect( 1483): Network connectivity changed, type is: 2
,I/NetworkMonitor( 3079): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 3079): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/PhoneInterfaceManager( 1281): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1281): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  818): getDataEnabled: retVal=false
,D/SprintDMReceiver( 3906): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,E/GpsLocationProvider(  818): No APN found to select.
,D/SprintDMHelper( 3906): simOperator:  IMSI: null
D/SprintDMReceiver( 3906): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1774): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1774): onCreate
,D/SystemUpdateService( 1774): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1774): active receiver: enabled
,I/SystemUpdateService( 1774): showing system update notification
,I/iu.Environment( 1774): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1774): num queued entries: 0
I/iu.UploadsManager( 1774): num updated entries: 0
I/ValidateNoPeople(  818): skipping global notification
I/iu.SyncManager( 1774): NEXT; no task
,V/SystemUpdateService( 1774): retry (wakeup: false) in 3599985 ms
,D/ChimeraCfgMgr( 1774): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/SystemUpdateService( 1774): onDestroy
,D/ChimeraCfgMgr( 1774): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/GLSUser ( 1136): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1136): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1136): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1136): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1136): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  818): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 27 Jan 2016 09:05:32 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1453885532738], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1453885532719]}
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  818): Validated
D/ConnectivityService(  818): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/ConnectivityService(  818): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  818): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  818): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  818): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  818): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 1066): CM callback handler got msg 524290
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
,I/Babel   ( 2804): connection state changed from DISCONNECTED to CONNECTED
,V/Herrevad( 1774): NQAS connected
,D/GCM     ( 1136): Connected
,D/GCM     ( 1136): Message class com.google.f.a.a.p
,I/jxcore-log( 3818): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js,
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 3818): 
,E/WifiStateMachine(  818): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=10.00 rxSuccessRate=12.62 targetRoamBSSID=any RSSI=-50
E/WifiStateMachine(  818): WifiStateMachine L2Connected CMD_START_SCAN source -2 7, 9 -> obsolete
,D/ConnectivityService(  818): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,D/HeadsetStateMachine( 2158): Disconnected process message: 10, size: 0
,I/jxcore-log( 3818): Test app app.js loaded
I/jxcore-log( 3818): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): setDiscoveryMode: Mode set to BLE
,I/chromium( 3818): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/jxcore-log( 3818): BLE advertisement is supported
I/jxcore-log( 3818): 
,E/WifiStateMachine(  818): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=8.75 rxSuccessRate=8.91 targetRoamBSSID=any RSSI=-50
E/WifiStateMachine(  818): WifiStateMachine L2Connected CMD_START_SCAN source -2 8, 9 -> obsolete
,V/GLSActivity( 1136): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1136): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1136): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1136): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1136): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1136): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3610): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3610): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3610): [1] 5.onFinished: Scheduling replication attempt 4.
,E/WifiStateMachine(  818): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=1.21 rxSuccessRate=2.15 targetRoamBSSID=any RSSI=-50
,V/GLSActivity( 1136): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1136): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1136): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1136): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1136): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1136): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3610): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3610): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3610): [1] 5.onFinished: Scheduling replication attempt 5.
,E/WifiStateMachine(  818): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.79 rxSuccessRate=2.33 targetRoamBSSID=any RSSI=-50
E/WifiStateMachine(  818): WifiStateMachine starting scan for "NG7005g"WPA_PSK with 2412,5220
,I/PowerManagerService(  818): Going to sleep due to screen timeout (uid 1000)...
,I/Adreno  (  818): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/PermissionCache(  259): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (383 us)
,I/DisplayManagerService(  818): Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
D/SurfaceFlinger(  259): Set power mode=0, type=0 flinger=0xb6082000
,D/qdhwcomposer(  259): hwc_setPowerMode: Setting mode 0 on display: 0
,V/ActivityManager(  818): Display changed displayId=0
,I/qdhwcomposer(  259): handle_blank_event: dpy:0 panel power state: 0
,D/qdhwcomposer(  259): hwc_setPowerMode: Done setting mode 0 on display 0
,D/SurfaceControl(  818): Excessive delay in setPowerMode(): 286ms
,I/DreamManagerService(  818): Entering dreamland.
,I/DreamController(  818): Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0,
I/PowerManagerService(  818): Dozing...
,D/audio_hw_primary(  356): adev_set_parameters: enter: screen_state=on
D/mot_vr_audio_hw(  356): adev_set_parameters: screen_state=on
,E/WifiStateMachine(  818): cancelDelayedScan -> 12
,E/native  (  818): do suspend false
,I/Keyboard.Facilitator( 1231): onFinishInput()
,E/WifiStateMachine(  818): cancelDelayedScan -> 14
,E/native  (  818): do suspend true
,D/audio_hw_primary(  356): adev_set_parameters: enter: screen_state=off
D/mot_vr_audio_hw(  356): adev_set_parameters: screen_state=off
,E/WifiStateMachine(  818): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-50
E/WifiStateMachine(  818): WifiStateMachine L2Connected CMD_START_SCAN source -2 13, 14 -> obsolete
,I/BooksSync( 3749): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3749): GmsCore Version = 7.8.99 (2134222-430),
,I/GLSUser ( 1136): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1136): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1136): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1136): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1136): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/art     (  818): Explicit concurrent mark sweep GC freed 63370(3MB) AllocSpace objects, 15(428KB) LOS objects, 31% free, 34MB/50MB, paused 2.982ms total 95.504ms
,I/GLSUser ( 1136): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1136): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1136): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1136): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1136): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3749): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3749): Soft error
E/BooksSync( 3749): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3749): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3749): Sync error
E/BooksSync( 3749): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3749): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 3749): Finished books sync
,D/SyncManager(  818): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 167261, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,E/WifiStateMachine(  818): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-50
,E/WifiStateMachine(  818): WifiStateMachine L2Connected CMD_START_SCAN source -2 11, 14 -> obsolete
,V/GLSActivity( 1136): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1136): Vacuum at: now=1453885593024 tag=VacuumService
,V/GoogleAuthProtoRequest( 3880): [420] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1136): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1136): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1136): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1136): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1136): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1136): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3880): [420] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3880): [420] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3880): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3880): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3880): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3880): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3880): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3880): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3880): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3880): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3880): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3880): 	at com.a.a.k.run(SourceFile:110)
,I/GLSUser ( 1136): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1136): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1136): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1136): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1136): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GoogleURLConnFactory( 1136): Using platform SSLCertificateSocketFactory
,I/art     ( 1136): Explicit concurrent mark sweep GC freed 39395(2MB) AllocSpace objects, 6(661KB) LOS objects, 37% free, 26MB/42MB, paused 1.645ms total 49.209ms
,D/Finsky  ( 3610): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3610): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3610): [1] 5.onFinished: Giving up after 6 failures.
,W/Uploader( 1136): No account for auth token provided,
,W/Uploader( 1136): No account for auth token provided
,I/GLSUser ( 1136): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1136): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1136): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1136): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1136): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1136): Failed to get auth token: User intervention required. Notification has been pushed.,
E/Uploader( 1136): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1136): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1136): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1136): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1136): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1136): 	,at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1136): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1136): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1136): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1136): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1136): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1136): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1136): No account for auth token provided
,I/GLSUser ( 1136): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1136): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1136): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1136): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1136): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1136): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1136): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1136): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1136): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1136): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1136): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1136): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1136): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1136): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1136): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1136): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1136): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1136): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1136): No account for auth token provided
,I/GLSUser ( 1136): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1136): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1136): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1136): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1136): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1136): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1136): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1136): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1136): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1136): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1136): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1136): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1136): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1136): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1136): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1136): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1136): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1136): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1136): No account for auth token provided
,W/Uploader( 1136): No account for auth token provided
,W/Uploader( 1136): No account for auth token provided
,W/Uploader( 1136): No account for auth token provided
,W/Uploader( 1136): No account for auth token provided
,W/Uploader( 1136):  no longer exists, so no auth token.
,D/HeadsetStateMachine( 2158): Disconnected process message: 10, size: 0
,I/GLSUser ( 1136): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog,
I/GLSUser ( 1136): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1136): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1136): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1136): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1136): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1136): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1136): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1136): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1136): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1136): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1136): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1136): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1136): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1136): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1136): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1136): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1136): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/GLSUser ( 1136): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1136): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1136): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1136): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1136): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1136): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1136): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1136): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1136): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1136): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1136): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1136): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1136): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1136): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1136): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1136): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1136): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1136): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,D/HeadsetStateMachine( 2158): Disconnected process message: 10, size: 0
,V/KeepSync( 3732): Connecting to GoogleApiClient
,I/GLSUser ( 1136): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1136): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1136): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1136): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1136): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1136): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1136): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1136): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1136): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1136): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/HttpOperation( 3252): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3252): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3252): 	at jdm.a(PG:82)
E/HttpOperation( 3252): 	at jcs.o(PG:406)
E/HttpOperation( 3252): 	at jcn.a(PG:1379)
E/HttpOperation( 3252): 	at jcs.i(PG:143)
E/HttpOperation( 3252): 	at blb.a(PG:3937)
E/HttpOperation( 3252): 	at czp.a(PG:18188)
E/HttpOperation( 3252): 	at czp.a(PG:9081)
E/HttpOperation( 3252): 	at czq.run(PG:1686)
E/HttpOperation( 3252): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3252): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3252): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3252): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3252): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3252): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3252): 	at jdj.a(PG:4091)
E/HttpOperation( 3252): 	at jdj.a(PG:1125)
E/HttpOperation( 3252): 	at jdm.a(PG:77)
E/HttpOperation( 3252): 	... 12 more
E/HttpOperation( 3252): Caused by: faj: BadAuthentication
E/HttpOperation( 3252): 	at fal.a(PG:38)
E/HttpOperation( 3252): 	at jdj.a(PG:4089)
E/HttpOperation( 3252): 	... 14 more
,E/ClientConnectionOperation( 1774): Handling authorization failure
,E/ClientConnectionOperation( 1774): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62),
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
,V/KeepSync( 3732): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3732): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3732): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3732): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1136): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1136): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1136): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1136): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1136): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3252): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3252): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3252): 	at jdm.a(PG:82)
E/HttpOperation( 3252): 	at jcs.o(PG:406)
E/HttpOperation( 3252): 	at jcn.a(PG:1379)
E/HttpOperation( 3252): 	at jcs.i(PG:143)
E/HttpOperation( 3252): 	at hec.a(PG:42)
E/HttpOperation( 3252): 	at hee.a(PG:102)
E/HttpOperation( 3252): 	at czr.a(PG:65)
E/HttpOperation( 3252): 	at kka.a(PG:108)
E/HttpOperation( 3252): 	at czp.a(PG:19176)
E/HttpOperation( 3252): 	at czp.a(PG:9081)
E/HttpOperation( 3252): 	at czq.run(PG:1686)
E/HttpOperation( 3252): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3252): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3252): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3252): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3252): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3252): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3252): 	at jdj.a(PG:4091)
E/HttpOperation( 3252): 	at jdj.a(PG:1125)
E/HttpOperation( 3252): 	at jdm.a(PG:77)
E/HttpOperation( 3252): 	... 15 more
E/HttpOperation( 3252): Caused by: faj: BadAuthentication
E/HttpOperation( 3252): 	at fal.a(PG:38)
E/HttpOperation( 3252): 	at jdj.a(PG:4089)
E/HttpOperation( 3252): 	... 17 more
E/ExperimentLoader( 3252): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3252): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3252): 	at jdm.a(PG:82)
E/ExperimentLoader( 3252): 	at jcs.o(PG:406)
E/ExperimentLoader( 3252): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3252): 	at jcs.i(PG:143)
E/ExperimentLoader( 3252): 	at hec.a(PG:42)
E/ExperimentLoader( 3252): 	at hee.a(PG:102)
E/ExperimentLoader( 3252): 	at czr.a(PG:65)
E/ExperimentLoader( 3252): 	at kka.a(PG:108)
E/ExperimentLoader( 3252): 	at czp.a(PG:19176)
E/ExperimentLoader( 3252): 	at czp.a(PG:9081)
E/ExperimentLoader( 3252): 	at czq.run(PG:1686)
E/ExperimentLoader( 3252): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3252): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3252): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3252): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3252): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3252): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3252): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3252): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3252): 	at jdm.a(PG:77)
E/ExperimentLoader( 3252): 	... 15 more
E/ExperimentLoader( 3252): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3252): 	at fal.a(PG:38)
E/ExperimentLoader( 3252): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3252): 	... 17 more
,I/GLSUser ( 1136): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1136): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1136): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1136): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1136): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3732): IOException
E/KeepSync( 3732): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3732): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3732): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3732): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3732): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3732): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3732): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3732): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3732): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3732): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3732): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3732): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3732): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3732): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3732): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3732): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3732): 	... 10 more
W/KeepSync( 3732): Sync result 2
,D/SyncManager(  818): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 168492, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,D/SyncManager(  818): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 169600, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,V/GoogleAuthProtoRequest( 3880): [422] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1136): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1136): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1136): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1136): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1136): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  818): Explicit concurrent mark sweep GC freed 36527(1671KB) AllocSpace objects, 5(174KB) LOS objects, 31% free, 34MB/50MB, paused 1.656ms total 60.176ms
,W/ExperimentUpdateService( 3880): [422] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3880): [422] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3880): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3880): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3880): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3880): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3880): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3880): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3880): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3880): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3880): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3880): 	at com.a.a.k.run(SourceFile:110)
,I/Keyboard.Facilitator.LanguageModelFlusher( 1231): run()
I/Keyboard.Facilitator( 1231): flushDynamicLanguageModels()
,I/ConfigService( 1136): onCreate
,I/BooksSync( 3749): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3749): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1136): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1136): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1136): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1136): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1136): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1136): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1136): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1136): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1136): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1136): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3749): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3749): Soft error
E/BooksSync( 3749): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication,
E/BooksSync( 3749): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3749): Sync error
E/BooksSync( 3749): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3749): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3749): Finished books sync
,D/SyncManager(  818): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 200391, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1],
,V/KeepSync( 3732): Connecting to GoogleApiClient
,I/GLSUser ( 1136): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1136): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1136): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1136): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1136): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,V/KeepSync( 3732): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3732): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3732): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3732): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1136): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1136): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1136): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1136): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1136): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3732): IOException
E/KeepSync( 3732): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3732): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3732): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3732): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3732): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3732): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3732): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3732): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3732): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3732): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3732): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3732): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3732): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3732): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3732): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3732): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3732): 	... 10 more
W/KeepSync( 3732): Sync result 2
,D/SyncManager(  818): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 227707, reason: 10079, SyncResult: stats [ numIoExceptions: 1],
,I/ConfigService( 1136): onDestroy
,D/HeadsetStateMachine( 2158): Disconnected process message: 10, size: 0
,I/GLSUser ( 1136): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1136): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1136): [GLSUser] Extracting token using key: Auth,
W/GLSActivity( 1136): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1136): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3252): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3252): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3252): 	at jdm.a(PG:82)
E/HttpOperation( 3252): 	at jcs.o(PG:406)
E/HttpOperation( 3252): 	at jcn.a(PG:1379)
E/HttpOperation( 3252): 	at jcs.i(PG:143)
E/HttpOperation( 3252): 	at blb.a(PG:3937)
E/HttpOperation( 3252): 	at czp.a(PG:18188)
E/HttpOperation( 3252): 	at czp.a(PG:9081)
E/HttpOperation( 3252): 	at czq.run(PG:1686)
E/HttpOperation( 3252): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3252): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3252): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3252): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3252): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3252): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3252): 	at jdj.a(PG:4091)
E/HttpOperation( 3252): 	at jdj.a(PG:1125)
E/HttpOperation( 3252): 	at jdm.a(PG:77)
E/HttpOperation( 3252): 	... 12 more
E/HttpOperation( 3252): Caused by: faj: BadAuthentication
E/HttpOperation( 3252): 	at fal.a(PG:38)
E/HttpOperation( 3252): 	at jdj.a(PG:4089)
E/HttpOperation( 3252): 	... 14 more
,I/GLSUser ( 1136): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1136): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1136): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1136): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1136): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3252): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3252): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3252): 	at jdm.a(PG:82)
E/HttpOperation( 3252): 	at jcs.o(PG:406)
E/HttpOperation( 3252): 	at jcn.a(PG:1379)
E/HttpOperation( 3252): 	at jcs.i(PG:143)
E/HttpOperation( 3252): 	at hec.a(PG:42)
E/HttpOperation( 3252): 	at hee.a(PG:102)
E/HttpOperation( 3252): 	at czr.a(PG:65)
E/HttpOperation( 3252): 	at kka.a(PG:108)
E/HttpOperation( 3252): 	at czp.a(PG:19176)
E/HttpOperation( 3252): 	at czp.a(PG:9081)
E/HttpOperation( 3252): 	at czq.run(PG:1686)
E/HttpOperation( 3252): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3252): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3252): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3252): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3252): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3252): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3252): 	at jdj.a(PG:4091)
E/HttpOperation( 3252): 	at jdj.a(PG:1125)
E/HttpOperation( 3252): 	at jdm.a(PG:77)
E/HttpOperation( 3252): 	... 15 more
E/HttpOperation( 3252): Caused by: faj: BadAuthentication
E/HttpOperation( 3252): 	at fal.a(PG:38)
E/HttpOperation( 3252): 	at jdj.a(PG:4089)
E/HttpOperation( 3252): 	... 17 more
E/ExperimentLoader( 3252): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3252): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3252): 	at jdm.a(PG:82)
E/ExperimentLoader( 3252): 	at jcs.o(PG:406)
E/ExperimentLoader( 3252): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3252): 	at jcs.i(PG:143)
E/ExperimentLoader( 3252): 	at hec.a(PG:42)
E/ExperimentLoader( 3252): 	at hee.a(PG:102)
E/ExperimentLoader( 3252): 	at czr.a(PG:65)
E/ExperimentLoader( 3252): 	at kka.a(PG:108)
E/ExperimentLoader( 3252): 	at czp.a(PG:19176)
E/ExperimentLoader( 3252): 	at czp.a(PG:9081)
E/ExperimentLoader( 3252): 	at czq.run(PG:1686)
E/ExperimentLoader( 3252): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3252): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3252): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3252): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3252): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3252): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3252): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3252): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3252): 	at jdm.a(PG:77)
E/ExperimentLoader( 3252): 	... 15 more
E/ExperimentLoader( 3252): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3252): 	at fal.a(PG:38)
E/ExperimentLoader( 3252): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3252): 	... 17 more
,D/SyncManager(  818): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 229968, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,I/jxcore-log( 3818): TAP version 13
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): # setup,
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): # multiplex can send data
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): # teardown
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): ok 1 String should be length:200
I/jxcore-log( 3818): ,
,I/jxcore-log( 3818): # setup
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): # enqueue and run in order
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): # teardown
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): ok 2 firstPromise setTimeout
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): ok 3 firstPromise result
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): ok 4 firstPromise testValue
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): ok 5 secondPromise setTimeout
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): ok 6 secondPromise result
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): ok 7 secondPromise testValue
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): ok 8 thirdPromise in promise
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): ok 9 thirdPromise result
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): ok 10 thirdPromise testValue
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): # setup
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): # basic
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): # teardown
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): ok 11 sane
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): # setup
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): # another
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): # teardown
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): ok 12 sane
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): # setup
,I/jxcore-log( 3818): 
,I/jxcore-log( 3818): # successfully create a new pkcs12 file and return hash value
,I/jxcore-log( 3818): 
,I/jxcore-log( 3818): # teardown,
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): ok 13 should be equal,
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): ok 14 null,
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): ok 15 (unnamed assert),
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): ok 16 should be equal
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): ok 17 should not throw
I/jxcore-log( 3818): 
I/jxcore-log( 3818): # setup
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): # successfully read a previous pkcs12 file and return hash value
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): # teardown
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): ok 18 (unnamed assert)
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): ok 19 (unnamed assert)
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): ok 20 should not throw
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): ok 21 should be equal
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): ok 22 should be equal
I/jxcore-log( 3818): 
I/jxcore-log( 3818): # setup
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): # failed to extract public key because of corrupt pkcs12 file
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): # teardown
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): ok 23 should be equal
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): # setup
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): # failed to get mobile documents path
,I/jxcore-log( 3818): 
,I/jxcore-log( 3818): # teardown
,I/jxcore-log( 3818): 
,I/jxcore-log( 3818): ok 24 should be equal
,I/jxcore-log( 3818): 
I/jxcore-log( 3818): # setup
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): # #init should register the peerAvailabilityChanged event
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): # teardown
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): ok 25 should be equal
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): ok 26 should be equal
I/jxcore-log( 3818): 
I/jxcore-log( 3818): ok 27 should be equal
I/jxcore-log( 3818): 
I/jxcore-log( 3818): # setup
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): # #init should register the networkChanged event
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): # teardown
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): ok 28 should be equal
,I/jxcore-log( 3818): 
I/jxcore-log( 3818): # setup
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): # #startBroadcasting should throw on null device name
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): # teardown
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): ok 29 should throw
,I/jxcore-log( 3818): 
,I/jxcore-log( 3818): # setup
,I/jxcore-log( 3818): 
,I/jxcore-log( 3818): # #startBroadcasting should throw on empty string device name
,I/jxcore-log( 3818): 
,I/jxcore-log( 3818): # teardown
,I/jxcore-log( 3818): 
,I/jxcore-log( 3818): ok 30 should throw
I/jxcore-log( 3818): ,
I/jxcore-log( 3818): # setup
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): # #startBroadcasting should throw on non-number port
I/jxcore-log( 3818): ,
,I/jxcore-log( 3818): # teardown
,I/jxcore-log( 3818): 
,I/jxcore-log( 3818): ok 31 should throw
,I/jxcore-log( 3818): 
,I/jxcore-log( 3818): # setup
I/jxcore-log( 3818): ,
,I/jxcore-log( 3818): # #startBroadcasting should throw on NaN port
,I/jxcore-log( 3818): 
,I/jxcore-log( 3818): # teardown
I/jxcore-log( 3818): ,
,I/jxcore-log( 3818): ok 32 should throw
,I/jxcore-log( 3818): 
,I/jxcore-log( 3818): # setup
,I/jxcore-log( 3818): 
,I/jxcore-log( 3818): # #startBroadcasting should throw on negative port
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): # teardown
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): ok 33 should throw
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): # setup
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): # #startBroadcasting should throw on too large port
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): # teardown
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): ok 34 should throw
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): # setup
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): # #startBroadcasting should call Mobile("StartBroadcasting") without an error
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): # teardown
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): ok 35 should be equal
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): ok 36 should be equal
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): ok 37 should be equal
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): # setup
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): # #startBroadcasting should call Mobile("StartBroadcasting") and handle an error
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): # teardown
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): ok 38 should be equal
I/jxcore-log( 3818): 
I/jxcore-log( 3818): ok 39 should be equal
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): ok 40 should be equal
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): # setup
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): # #stopBroadcasting should call Mobile("StopBroadcasting") without an error
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): # teardown
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): ok 41 should be equal
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): ok 42 should be equal
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): # setup
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): # #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error,
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): # teardown,
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): ok 43 should be equal,
I/jxcore-log( 3818): 
I/jxcore-log( 3818): ok 44 should be equal
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): # setup,
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): # #connect should call Mobile("Connect") with a port and without an error,
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): # teardown,
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): ok 45 should be equal
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): ok 46 should be equal
I/jxcore-log( 3818): 
I/jxcore-log( 3818): ok 47 should be equal
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): # setup,
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): # #connect should call Mobile("Connect") and handle an error
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): # teardown
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): ok 48 should be equal
I/jxcore-log( 3818): 
I/jxcore-log( 3818): ok 49 should be equal,
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): # setup
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): # should call Mobile("Disconnect") without an error
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): # teardown
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): ok 50 should be equal
I/jxcore-log( 3818): 
I/jxcore-log( 3818): ok 51 should be equal,
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): # setup
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): # should call Mobile("Disconnect") and handle an error
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): # teardown
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): ok 52 should be equal
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): ok 53 should be equal
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): # setup
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): # ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): # teardown
I/jxcore-log( 3818): ,
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  818): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3818): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453885712977.3818
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3818): bind: Binding a new listener
,D/BluetoothManagerService(  818): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3818): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  818): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3818): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453885712977.3818","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3818): setConnectionTimeout: 15000
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3818): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3818): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  818): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3818): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3818): setState: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3818): start: OK
I/io.jxcore.node.ConnectionHelper( 3818): start: Using peer discovery mode: BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 3818): onConnectionManagerStateChanged: RUNNING,
D/BluetoothManagerService(  818): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3818): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453885712977.3818
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3818): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3818): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  818): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3818): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3818): createAdvertiseData: From: 1453885712977.3818 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3818): F8:CF:C5:D9:E5:61
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3818): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3818): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService( 2158): registerClient() - UUID=47d3e001-365e-4d94-bdf3-07a670ff76d5
,D/BtGatt.GattService( 2158): onClientRegistered() - UUID=47d3e001-365e-4d94-bdf3-07a670ff76d5, clientIf=5
,D/BluetoothLeAdvertiser( 3818): onClientRegistered() - status=0 clientIf=5
,D/BtGatt.AdvertiseManager( 2158): message : 0
,D/BtGatt.AdvertiseManager( 2158): starting multi advertising
,D/BtGatt.GattService( 2158): onAdvertiseInstanceEnabled() - clientIf=5, status=0
,D/BtGatt.GattService( 2158): onAdvertiseDataSet() - clientIf=5, status=0
,D/BtGatt.GattService( 2158): registerClient() - UUID=7a6aca10-986c-4842-8bef-181ac0e0c398
,D/BtGatt.GattService( 2158): onClientRegistered() - UUID=7a6aca10-986c-4842-8bef-181ac0e0c398, clientIf=6
D/BluetoothLeScanner( 3818): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.GattService( 2158): start scan with filters
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): startBlePeerDiscovery: OK
,D/BtGatt.ScanManager( 2158): handling starting scan
,D/BluetoothManagerService(  818): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
D/BluetoothAdapterService( 2158): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2eb58969
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3818): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453885712977.3818","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3818): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453885712977.3818","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3818): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1453885712977.3818","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
D/BtGatt.GattService( 2158): onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
D/BtGatt.ScanManager( 2158): callback done for clientIf - 6 status - 0
,D/BtGatt.GattService( 2158): onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,D/BtGatt.ScanManager( 2158): callback done for clientIf - 6 status - 0
D/BtGatt.ScanManager( 2158): configureRegularScanParams() - queue=1
D/BtGatt.ScanManager( 2158): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): start: Starting P2P device discovery...,
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): startWifiPeerDiscovery: Wi-Fi Direct OK,
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): setState: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 3818): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453885712977.3818
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): startBlePeerDiscovery: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): startWifiPeerDiscovery: Wi-Fi Direct OK
I/jxcore-log( 3818): ok 54 Should be able to call startBroadcasting without error
I/jxcore-log( 3818): 
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3818): onStartSuccess
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3818): onIsAdvertiserStartedChanged: true
I/io.jxcore.node.ConnectionHelper( 3818): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3818): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 3818): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3818): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3818): Shutting down...,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3818): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3818): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3818): Exiting thread,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3818): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3818): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3818): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3818): onConnectionManagerStateChanged: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
D/BtGatt.AdvertiseManager( 2158): message : 1
D/BtGatt.AdvertiseManager( 2158): stop advertise for client 5
,D/BtGatt.GattService( 2158): onAdvertiseInstanceDisabled() - clientIf=5, status=0
,D/BtGatt.GattService( 2158): Client app is not null!
D/BtGatt.GattService( 2158): unregisterClient() - clientIf=5
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3818): onIsAdvertiserStartedChanged: false
,D/BtGatt.GattService( 2158): stopScan() - queue size =1
,D/BtGatt.GattService( 2158): unregisterClient() - clientIf=6,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3818): onIsScannerStartedChanged: false
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3818): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): stopBlePeerDiscovery: Stopped
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3818): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): stop: Stopping P2P device discovery...
D/BtGatt.GattService( 2158): onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
D/BtGatt.ScanManager( 2158): callback done for clientIf - 6 status - 0
D/BtGatt.ScanManager( 2158): stop scan
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): setState: NOT_INITIALIZED
,D/BtGatt.ScanManager( 2158): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager( 2158): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager( 2158): configureRegularScanParams() - queue emtpy, scan stopped
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3818): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3818): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3818): Local services cleared successfully
,I/wpa_supplicant( 1044): P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3818): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): P2P device discovery stopped successfully
I/jxcore-log( 3818): ok 55 Should be able to call stopBroadcasting without error
I/jxcore-log( 3818): ,
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3818): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  818): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3818): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453885713170.3818
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3818): bind: Binding a new listener
D/BluetoothManagerService(  818): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3818): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  818): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3818): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453885713170.3818","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3818): setConnectionTimeout: 15000
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3818): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3818): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  818): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3818): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3818): setState: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3818): start: OK
I/io.jxcore.node.ConnectionHelper( 3818): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 3818): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService(  818): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3818): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453885713170.3818
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3818): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3818): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  818): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3818): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3818): createAdvertiseData: From: 1453885713170.3818 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3818): F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3818): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3818): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService( 2158): registerClient() - UUID=e0ceb6da-ba9d-4c0c-a371-e3f482c50021
,D/BtGatt.GattService( 2158): onClientRegistered() - UUID=e0ceb6da-ba9d-4c0c-a371-e3f482c50021, clientIf=5
D/BluetoothLeAdvertiser( 3818): onClientRegistered() - status=0 clientIf=5
D/BtGatt.AdvertiseManager( 2158): message : 0
,D/BtGatt.AdvertiseManager( 2158): starting multi advertising
,D/BtGatt.GattService( 2158): onAdvertiseInstanceEnabled() - clientIf=5, status=0
,D/BtGatt.GattService( 2158): onAdvertiseDataSet() - clientIf=5, status=0
,D/BtGatt.GattService( 2158): registerClient() - UUID=30ef81cb-7df0-44f6-972c-76467700db2d,
D/BtGatt.GattService( 2158): onClientRegistered() - UUID=30ef81cb-7df0-44f6-972c-76467700db2d, clientIf=6
D/BluetoothLeScanner( 3818): onClientRegistered() - status=0 clientIf=6
D/BtGatt.GattService( 2158): start scan with filters
,D/BtGatt.ScanManager( 2158): handling starting scan
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): startBlePeerDiscovery: OK
,D/BluetoothManagerService(  818): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3818): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453885713170.3818","ra":"F8:CF:C5:D9:E5:61"},
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3818): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453885713170.3818","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3818): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1453885713170.3818","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
D/BtGatt.GattService( 2158): onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
D/BtGatt.ScanManager( 2158): callback done for clientIf - 6 status - 0
D/BtGatt.GattService( 2158): onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
D/BtGatt.ScanManager( 2158): callback done for clientIf - 6 status - 0
D/BtGatt.ScanManager( 2158): configureRegularScanParams() - queue=1
D/BtGatt.ScanManager( 2158): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): start: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): setState: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 3818): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453885713170.3818
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): startBlePeerDiscovery: OK
I/jxcore-log( 3818): ok 56 Should be able to call startBroadcasting without error
I/jxcore-log( 3818): 
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): startWifiPeerDiscovery: Wi-Fi Direct OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3818): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3818): onIsAdvertiserStartedChanged: true
I/io.jxcore.node.ConnectionHelper( 3818): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): restart: Restarting...,
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): setState: RESTARTING
I/wpa_supplicant( 1044): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3818): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 3818): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3818): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3818): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3818): stopListeningForIncomingConnections: Stopping...
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3818): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): setState: STARTED
I/wpa_supplicant( 1044): P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3818): Exiting thread
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): setState: RESTARTING
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3818): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3818): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3818): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): stop: Stopping peer discovery...
I/io.jxcore.node.ConnectionHelper( 3818): onConnectionManagerStateChanged: NOT_STARTED
D/BtGatt.AdvertiseManager( 2158): message : 1
D/BtGatt.AdvertiseManager( 2158): stop advertise for client 5
,D/BtGatt.GattService( 2158): onAdvertiseInstanceDisabled() - clientIf=5, status=0
D/BtGatt.GattService( 2158): Client app is not null!
D/BtGatt.GattService( 2158): unregisterClient() - clientIf=5
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3818): onIsAdvertiserStartedChanged: false
D/BtGatt.GattService( 2158): stopScan() - queue size =1
D/BtGatt.GattService( 2158): unregisterClient() - clientIf=6
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3818): onIsScannerStartedChanged: false
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3818): setIsStarted: true
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3818): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): onIsWifiPeerDiscoveryStartedChanged: false,
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): stopWifiPeerDiscovery: Stopped
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3818): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3818): Local services cleared successfully,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3818): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3818): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3818): Service requests cleared successfully
I/jxcore-log( 3818): ok 57 Should be able to call stopBroadcasting without error
I/jxcore-log( 3818): 
,D/BtGatt.GattService( 2158): onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
D/BtGatt.ScanManager( 2158): callback done for clientIf - 6 status - 0
D/BtGatt.ScanManager( 2158): stop scan
D/BtGatt.ScanManager( 2158): configureRegularScanParams() - queue=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): setDiscoveryMode: Mode set to BLE
D/BtGatt.ScanManager( 2158): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager( 2158): configureRegularScanParams() - queue emtpy, scan stopped
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  818): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3818): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453885713273.3818
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3818): bind: Binding a new listener
,D/BluetoothManagerService(  818): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3818): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
D/BluetoothManagerService(  818): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3818): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453885713273.3818","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3818): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3818): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3818): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  818): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
W/BluetoothAdapter( 3818): getBluetoothService() called with no BluetoothManagerCallback
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3818): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper( 3818): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3818): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3818): start: OK
I/io.jxcore.node.ConnectionHelper( 3818): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService(  818): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453885713273.3818
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3818): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3818): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): onWifiStateChanged: State changed to 2
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  818): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3818): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3818): createAdvertiseData: From: 1453885713273.3818 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3818): F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3818): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3818): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService( 2158): registerClient() - UUID=9af6f4bd-f888-4d01-8270-b3f8e308d218
,D/BtGatt.GattService( 2158): onClientRegistered() - UUID=9af6f4bd-f888-4d01-8270-b3f8e308d218, clientIf=5
D/BluetoothLeAdvertiser( 3818): onClientRegistered() - status=0 clientIf=5
,D/BtGatt.AdvertiseManager( 2158): message : 0
,D/BtGatt.AdvertiseManager( 2158): starting multi advertising
,D/BtGatt.GattService( 2158): onAdvertiseInstanceEnabled() - clientIf=5, status=0
,D/BtGatt.GattService( 2158): onAdvertiseDataSet() - clientIf=5, status=0
,D/BtGatt.GattService( 2158): registerClient() - UUID=d7c31329-40d8-4cba-a315-eb8e88d2a2ed
D/BtGatt.GattService( 2158): onClientRegistered() - UUID=d7c31329-40d8-4cba-a315-eb8e88d2a2ed, clientIf=6
,D/BluetoothLeScanner( 3818): onClientRegistered() - status=0 clientIf=6
D/BtGatt.GattService( 2158): start scan with filters
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): startBlePeerDiscovery: OK
D/BtGatt.ScanManager( 2158): handling starting scan
,D/BluetoothManagerService(  818): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0,
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3818): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453885713273.3818","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3818): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453885713273.3818","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3818): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1453885713273.3818","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
D/BtGatt.GattService( 2158): onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
D/BtGatt.ScanManager( 2158): callback done for clientIf - 6 status - 0
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): setState: RUNNING_BLE_AND_WIFI
D/BtGatt.GattService( 2158): onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
I/io.jxcore.node.ConnectionHelper( 3818): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453885713273.3818
D/BtGatt.ScanManager( 2158): callback done for clientIf - 6 status - 0
I/wpa_supplicant( 1044): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,D/BtGatt.ScanManager( 2158): configureRegularScanParams() - queue=1
D/BtGatt.ScanManager( 2158): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): startBlePeerDiscovery: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): startWifiPeerDiscovery: Wi-Fi Direct OK
,I/jxcore-log( 3818): ok 58 Should be able to call startBroadcasting without error
I/jxcore-log( 3818): 
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3818): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3818): onIsAdvertiserStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 3818): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3818): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): P2P device discovery started successfully
,I/io.jxcore.node.ConnectionHelper( 3818): stop
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): setState: STARTED
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3818): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3818): Shutting down...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3818): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3818): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3818): release: 1 listener(s) left
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3818): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): stop: Stopping peer discovery...
I/io.jxcore.node.ConnectionHelper( 3818): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3818): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3818): onServerStopped
I/wpa_supplicant( 1044): P2P-FIND-STOPPED 
D/BtGatt.AdvertiseManager( 2158): message : 1
D/BtGatt.AdvertiseManager( 2158): stop advertise for client 5
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): restart: Restarting...,
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): setState: RESTARTING
D/BtGatt.GattService( 2158): onAdvertiseInstanceDisabled() - clientIf=5, status=0
D/BtGatt.GattService( 2158): Client app is not null!
D/BtGatt.GattService( 2158): unregisterClient() - clientIf=5
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3818): onIsAdvertiserStartedChanged: false
D/BtGatt.GattService( 2158): stopScan() - queue size =1
D/BtGatt.GattService( 2158): unregisterClient() - clientIf=6
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3818): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3818): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3818): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): stopWifiPeerDiscovery: Stopped
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3818): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3818): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3818): onDiscoveryManagerStateChanged: NOT_STARTED
,D/BtGatt.GattService( 2158): onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,D/BtGatt.ScanManager( 2158): callback done for clientIf - 6 status - 0
D/BtGatt.ScanManager( 2158): stop scan
D/BtGatt.ScanManager( 2158): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager( 2158): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager( 2158): configureRegularScanParams() - queue emtpy, scan stopped
I/jxcore-log( 3818): ok 59 Should be able to call stopBroadcasting without error
I/jxcore-log( 3818): 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3818): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  818): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3818): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3818): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453885713337.3818
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3818): bind: Binding a new listener
D/BluetoothManagerService(  818): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3818): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  818): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3818): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453885713337.3818","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3818): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3818): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3818): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  818): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3818): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3818): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 3818): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3818): start: OK
I/io.jxcore.node.ConnectionHelper( 3818): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService(  818): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3818): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453885713337.3818
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3818): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3818): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...,
D/BluetoothManagerService(  818): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3818): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3818): createAdvertiseData: From: 1453885713337.3818 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3818): F8:CF:C5:D9:E5:61
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3818): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3818): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService( 2158): registerClient() - UUID=f8b9ec93-cdf1-4221-b77e-425dc77720f3
,D/BtGatt.GattService( 2158): onClientRegistered() - UUID=f8b9ec93-cdf1-4221-b77e-425dc77720f3, clientIf=5
D/BluetoothLeAdvertiser( 3818): onClientRegistered() - status=0 clientIf=5
,D/BtGatt.AdvertiseManager( 2158): message : 0
,D/BtGatt.AdvertiseManager( 2158): starting multi advertising
,D/BtGatt.GattService( 2158): onAdvertiseInstanceEnabled() - clientIf=5, status=0
,D/BtGatt.GattService( 2158): onAdvertiseDataSet() - clientIf=5, status=0
,D/BtGatt.GattService( 2158): registerClient() - UUID=05ad9955-4eee-4186-98a5-41816c22794b,
D/BtGatt.GattService( 2158): onClientRegistered() - UUID=05ad9955-4eee-4186-98a5-41816c22794b, clientIf=6
,D/BluetoothLeScanner( 3818): onClientRegistered() - status=0 clientIf=6
D/BtGatt.GattService( 2158): start scan with filters
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): startBlePeerDiscovery: OK
D/BtGatt.ScanManager( 2158): handling starting scan
,D/BluetoothManagerService(  818): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3818): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453885713337.3818","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3818): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453885713337.3818","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3818): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1453885713337.3818","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
,D/BtGatt.GattService( 2158): onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
D/BtGatt.ScanManager( 2158): callback done for clientIf - 6 status - 0
D/BtGatt.GattService( 2158): onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
D/BtGatt.ScanManager( 2158): callback done for clientIf - 6 status - 0
,D/BtGatt.ScanManager( 2158): configureRegularScanParams() - queue=1
D/BtGatt.ScanManager( 2158): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): setState: RUNNING_BLE_AND_WIFI
,I/io.jxcore.node.ConnectionHelper( 3818): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453885713337.3818
I/wpa_supplicant( 1044): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): startBlePeerDiscovery: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): startWifiPeerDiscovery: Wi-Fi Direct OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): start: OK
I/jxcore-log( 3818): ok 60 Should be able to call startBroadcasting without error
I/jxcore-log( 3818): 
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3818): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3818): onIsAdvertiserStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): setState: RESTARTING
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3818): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 3818): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): setState: STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3818): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3818): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3818): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3818): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3818): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3818): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3818): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3818): release: 1 listener(s) left
I/wpa_supplicant( 1044): P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3818): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): stop: Stopping peer discovery...
I/io.jxcore.node.ConnectionHelper( 3818): onConnectionManagerStateChanged: NOT_STARTED
D/BtGatt.AdvertiseManager( 2158): message : 1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): P2P device discovery stopped successfully
D/BtGatt.AdvertiseManager( 2158): stop advertise for client 5
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): setState: RESTARTING
,D/BtGatt.GattService( 2158): onAdvertiseInstanceDisabled() - clientIf=5, status=0
,D/BtGatt.GattService( 2158): Client app is not null!
D/BtGatt.GattService( 2158): unregisterClient() - clientIf=5
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3818): onIsAdvertiserStartedChanged: false
,D/BtGatt.GattService( 2158): stopScan() - queue size =1
,D/BtGatt.GattService( 2158): unregisterClient() - clientIf=6
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3818): onIsScannerStartedChanged: false
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3818): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3818): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): onIsWifiPeerDiscoveryStartedChanged: false
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): stopWifiPeerDiscovery: Stopped
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3818): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3818): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3818): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3818): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 3818): ok 61 Should be able to call stopBroadcasting without error
I/jxcore-log( 3818): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): P2P device discovery stopped successfully
,D/BtGatt.GattService( 2158): onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
D/BtGatt.ScanManager( 2158): callback done for clientIf - 6 status - 0
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3818): Service requests cleared successfully
D/BtGatt.ScanManager( 2158): stop scan
D/BtGatt.ScanManager( 2158): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager( 2158): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager( 2158): configureRegularScanParams() - queue emtpy, scan stopped
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  818): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3818): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453885713397.3818
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3818): bind: Binding a new listener
D/BluetoothManagerService(  818): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3818): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  818): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3818): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453885713397.3818","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3818): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3818): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3818): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  818): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3818): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3818): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3818): start: OK
I/io.jxcore.node.ConnectionHelper( 3818): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 3818): start: Using peer discovery mode: BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3818): Waiting for incoming connections...
D/BluetoothManagerService(  818): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453885713397.3818
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3818): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3818): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): onWifiStateChanged: State changed to 2
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  818): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3818): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3818): createAdvertiseData: From: 1453885713397.3818 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3818): F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3818): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3818): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService( 2158): registerClient() - UUID=eb84b6bf-ed6d-484f-8783-dcaf1ba2ff62
,D/BtGatt.GattService( 2158): onClientRegistered() - UUID=eb84b6bf-ed6d-484f-8783-dcaf1ba2ff62, clientIf=5
D/BluetoothLeAdvertiser( 3818): onClientRegistered() - status=0 clientIf=5
,D/BtGatt.AdvertiseManager( 2158): message : 0
,D/BtGatt.AdvertiseManager( 2158): starting multi advertising
,D/BtGatt.GattService( 2158): onAdvertiseInstanceEnabled() - clientIf=5, status=0
,D/BtGatt.GattService( 2158): onAdvertiseDataSet() - clientIf=5, status=0
,D/BtGatt.GattService( 2158): registerClient() - UUID=f5857fb3-b56e-4c61-a807-817e844b5049
,D/BtGatt.GattService( 2158): onClientRegistered() - UUID=f5857fb3-b56e-4c61-a807-817e844b5049, clientIf=6
D/BluetoothLeScanner( 3818): onClientRegistered() - status=0 clientIf=6
D/BtGatt.GattService( 2158): start scan with filters
,D/BtGatt.ScanManager( 2158): handling starting scan
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): startBlePeerDiscovery: OK
,D/BluetoothManagerService(  818): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/BtGatt.GattService( 2158): onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,D/BtGatt.ScanManager( 2158): callback done for clientIf - 6 status - 0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3818): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453885713397.3818","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3818): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453885713397.3818","ra":"F8:CF:C5:D9:E5:61"}
,D/BtGatt.GattService( 2158): onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,D/BtGatt.ScanManager( 2158): callback done for clientIf - 6 status - 0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3818): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1453885713397.3818","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
D/BtGatt.ScanManager( 2158): configureRegularScanParams() - queue=1
D/BtGatt.ScanManager( 2158): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): start: Starting P2P device discovery...
I/wpa_supplicant( 1044): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): setState: RUNNING_BLE_AND_WIFI
,I/io.jxcore.node.ConnectionHelper( 3818): start: OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453885713397.3818
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): startBlePeerDiscovery: Already running
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): startBlePeerDiscovery: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): startWifiPeerDiscovery: Wi-Fi Direct OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3818): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3818): onIsAdvertiserStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3818): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 3818): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): P2P device discovery started successfully
I/jxcore-log( 3818): ok 62 Should be able to call startBroadcasting without error
I/jxcore-log( 3818): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): setState: STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3818): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3818): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3818): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3818): stopListeningForIncomingConnections: Stopping...
,I/wpa_supplicant( 1044): P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3818): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3818): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3818): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): stop: Stopping peer discovery...,
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3818): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3818): onServerStopped
,I/io.jxcore.node.ConnectionHelper( 3818): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): P2P device discovery stopped successfully
D/BtGatt.AdvertiseManager( 2158): message : 1
D/BtGatt.AdvertiseManager( 2158): stop advertise for client 5
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): setState: RESTARTING
D/BtGatt.GattService( 2158): onAdvertiseInstanceDisabled() - clientIf=5, status=0
D/BtGatt.GattService( 2158): Client app is not null!
D/BtGatt.GattService( 2158): unregisterClient() - clientIf=5,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3818): onIsAdvertiserStartedChanged: false
D/BtGatt.GattService( 2158): stopScan() - queue size =1
,D/BtGatt.GattService( 2158): unregisterClient() - clientIf=6,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3818): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3818): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): onIsBlePeerDiscoveryStartedChanged: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): stopBlePeerDiscovery: Stopped
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3818): stop: Stopping services
,D/BtGatt.GattService( 2158): onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,D/BtGatt.ScanManager( 2158): callback done for clientIf - 6 status - 0
D/BtGatt.ScanManager( 2158): stop scan
D/BtGatt.ScanManager( 2158): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager( 2158): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): stop: Stopping P2P device discovery...
D/BtGatt.ScanManager( 2158): configureRegularScanParams() - queue emtpy, scan stopped
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3818): release: No more listeners, de-initializing...,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3818): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3818): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3818): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3818): Service requests cleared successfully
,I/jxcore-log( 3818): ok 63 Should be able to call stopBroadcasting without error
I/jxcore-log( 3818): 
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): setDiscoveryMode: Mode set to BLE_AND_WIFI
,D/BluetoothManagerService(  818): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3818): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453885713478.3818
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3818): bind: Binding a new listener
D/BluetoothManagerService(  818): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3818): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  818): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3818): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453885713478.3818","ra":"F8:CF:C5:D9:E5:61"},
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3818): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3818): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3818): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  818): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
W/BluetoothAdapter( 3818): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3818): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper( 3818): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3818): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3818): start: OK
I/io.jxcore.node.ConnectionHelper( 3818): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService(  818): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453885713478.3818
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3818): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3818): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): onWifiStateChanged: State changed to 2,
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  818): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3818): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3818): createAdvertiseData: From: 1453885713478.3818 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3818): F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3818): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3818): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService( 2158): registerClient() - UUID=fb0a52ec-2736-4ecf-a270-0ba00bab2571
D/BtGatt.GattService( 2158): onClientRegistered() - UUID=fb0a52ec-2736-4ecf-a270-0ba00bab2571, clientIf=5
,D/BluetoothLeAdvertiser( 3818): onClientRegistered() - status=0 clientIf=5
D/BtGatt.AdvertiseManager( 2158): message : 0
,D/BtGatt.AdvertiseManager( 2158): starting multi advertising
,D/BtGatt.GattService( 2158): onAdvertiseInstanceEnabled() - clientIf=5, status=0
,D/BtGatt.GattService( 2158): onAdvertiseDataSet() - clientIf=5, status=0
,D/BtGatt.GattService( 2158): registerClient() - UUID=18dc38f4-dc33-48c1-b21d-d4bf1a40764a
,D/BtGatt.GattService( 2158): onClientRegistered() - UUID=18dc38f4-dc33-48c1-b21d-d4bf1a40764a, clientIf=6
D/BluetoothLeScanner( 3818): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.GattService( 2158): start scan with filters
,D/BtGatt.ScanManager( 2158): handling starting scan
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): startBlePeerDiscovery: OK
,D/BluetoothManagerService(  818): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3818): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453885713478.3818","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3818): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453885713478.3818","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3818): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1453885713478.3818","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
D/BtGatt.GattService( 2158): onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,D/BtGatt.ScanManager( 2158): callback done for clientIf - 6 status - 0
,D/BtGatt.GattService( 2158): onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
D/BtGatt.ScanManager( 2158): callback done for clientIf - 6 status - 0
D/BtGatt.ScanManager( 2158): configureRegularScanParams() - queue=1
D/BtGatt.ScanManager( 2158): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): setState: RUNNING_BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453885713478.3818
I/wpa_supplicant( 1044): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): startBlePeerDiscovery: OK
I/io.jxcore.node.ConnectionHelper( 3818): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3818): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3818): onIsAdvertiserStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3818): Local service added successfully
,I/io.jxcore.node.ConnectionHelper( 3818): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): setState: RESTARTING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/wpa_supplicant( 1044): P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): P2P device discovery stopped successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...,
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): setState: RESTARTING
I/jxcore-log( 3818): ok 64 Should be able to call startBroadcasting without error
I/jxcore-log( 3818): 
I/io.jxcore.node.ConnectionHelper( 3818): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3818): stop: Stopping Bluetooth...,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3818): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3818): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3818): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3818): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3818): setState: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3818): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3818): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): stop: Stopping peer discovery...
I/io.jxcore.node.ConnectionHelper( 3818): onConnectionManagerStateChanged: NOT_STARTED
,D/BtGatt.AdvertiseManager( 2158): message : 1
D/BtGatt.AdvertiseManager( 2158): stop advertise for client 5
D/BtGatt.GattService( 2158): onAdvertiseInstanceDisabled() - clientIf=5, status=0
,D/BtGatt.GattService( 2158): Client app is not null!
D/BtGatt.GattService( 2158): unregisterClient() - clientIf=5
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3818): onIsAdvertiserStartedChanged: false
D/BtGatt.GattService( 2158): stopScan() - queue size =1
,D/BtGatt.GattService( 2158): unregisterClient() - clientIf=6
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3818): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3818): setIsStarted: true
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): stopBlePeerDiscovery: Stopped
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3818): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): stop: Stopping P2P device discovery...,
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): onIsWifiPeerDiscoveryStartedChanged: false
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3818): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3818): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3818): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3818): onDiscoveryManagerStateChanged: NOT_STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3818): Service requests cleared successfully
,D/BtGatt.GattService( 2158): onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
D/BtGatt.ScanManager( 2158): callback done for clientIf - 6 status - 0
D/BtGatt.ScanManager( 2158): stop scan
,D/BtGatt.ScanManager( 2158): configureRegularScanParams() - queue=0
,D/BtGatt.ScanManager( 2158): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager( 2158): configureRegularScanParams() - queue emtpy, scan stopped
I/jxcore-log( 3818): ok 65 Should be able to call stopBroadcasting without error
I/jxcore-log( 3818): 
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  818): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3818): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453885713552.3818
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3818): bind: Binding a new listener
,D/BluetoothManagerService(  818): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3818): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  818): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3818): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453885713552.3818","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3818): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3818): startListeningForIncomingConnections
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3818): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  818): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3818): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3818): setState: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3818): start: OK
I/io.jxcore.node.ConnectionHelper( 3818): start: Using peer discovery mode: BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 3818): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3818): Waiting for incoming connections...
D/BluetoothManagerService(  818): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453885713552.3818
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3818): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3818): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  818): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3818): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3818): createAdvertiseData: From: 1453885713552.3818 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3818): F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3818): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3818): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService( 2158): registerClient() - UUID=7f92fc22-4885-4113-bec1-ba2da4fcad79
,D/BtGatt.GattService( 2158): onClientRegistered() - UUID=7f92fc22-4885-4113-bec1-ba2da4fcad79, clientIf=5
D/BluetoothLeAdvertiser( 3818): onClientRegistered() - status=0 clientIf=5
,D/BtGatt.AdvertiseManager( 2158): message : 0
,D/BtGatt.AdvertiseManager( 2158): starting multi advertising
,D/BtGatt.GattService( 2158): onAdvertiseInstanceEnabled() - clientIf=5, status=0
,D/BtGatt.GattService( 2158): onAdvertiseDataSet() - clientIf=5, status=0
,D/BtGatt.GattService( 2158): registerClient() - UUID=2fe4ab54-323b-4bb2-97d9-6a2b518eeba5
,D/BtGatt.GattService( 2158): onClientRegistered() - UUID=2fe4ab54-323b-4bb2-97d9-6a2b518eeba5, clientIf=6
,D/BluetoothLeScanner( 3818): onClientRegistered() - status=0 clientIf=6
D/BtGatt.GattService( 2158): start scan with filters
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): startBlePeerDiscovery: OK
,D/BtGatt.ScanManager( 2158): handling starting scan
,D/BluetoothManagerService(  818): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3818): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453885713552.3818","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3818): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453885713552.3818","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3818): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1453885713552.3818","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
D/BtGatt.GattService( 2158): onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
D/BtGatt.ScanManager( 2158): callback done for clientIf - 6 status - 0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): start: OK
,I/wpa_supplicant( 1044): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453885713552.3818
,D/BtGatt.GattService( 2158): onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
D/BtGatt.ScanManager( 2158): callback done for clientIf - 6 status - 0
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): startBlePeerDiscovery: Already running,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): startBlePeerDiscovery: OK
I/io.jxcore.node.ConnectionHelper( 3818): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): startWifiPeerDiscovery: Wi-Fi Direct OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3818): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3818): onIsAdvertiserStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): setState: RESTARTING
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3818): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 3818): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/wpa_supplicant( 1044): P2P-FIND-STOPPED 
D/BtGatt.ScanManager( 2158): configureRegularScanParams() - queue=1
D/BtGatt.ScanManager( 2158): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
I/jxcore-log( 3818): ok 66 Should be able to call startBroadcasting without error
I/jxcore-log( 3818): 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): P2P device discovery stopped successfully
I/io.jxcore.node.ConnectionHelper( 3818): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3818): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3818): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3818): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3818): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3818): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3818): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): setState: RESTARTING
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3818): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3818): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3818): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): stop: Stopping peer discovery...
D/BtGatt.AdvertiseManager( 2158): message : 1
,D/BtGatt.AdvertiseManager( 2158): stop advertise for client 5
,D/BtGatt.GattService( 2158): onAdvertiseInstanceDisabled() - clientIf=5, status=0
,D/BtGatt.GattService( 2158): Client app is not null!
D/BtGatt.GattService( 2158): unregisterClient() - clientIf=5
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3818): onIsAdvertiserStartedChanged: false
,D/BtGatt.GattService( 2158): stopScan() - queue size =1
,D/BtGatt.GattService( 2158): unregisterClient() - clientIf=6
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3818): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3818): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): stopBlePeerDiscovery: Stopped
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3818): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3818): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3818): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3818): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 3818): ok 67 Should be able to call stopBroadcasting without error
I/jxcore-log( 3818): 
,D/BtGatt.GattService( 2158): onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,D/BtGatt.ScanManager( 2158): callback done for clientIf - 6 status - 0
D/BtGatt.ScanManager( 2158): stop scan
D/BtGatt.ScanManager( 2158): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager( 2158): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager( 2158): configureRegularScanParams() - queue emtpy, scan stopped
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  818): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3818): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3818): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453885713628.3818
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3818): bind: Binding a new listener
D/BluetoothManagerService(  818): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3818): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3818): Service requests cleared successfully
,D/BluetoothManagerService(  818): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3818): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453885713628.3818","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3818): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3818): startListeningForIncomingConnections,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3818): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  818): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3818): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3818): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper( 3818): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3818): start: OK
I/io.jxcore.node.ConnectionHelper( 3818): start: Using peer discovery mode: BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3818): Waiting for incoming connections...
D/BluetoothManagerService(  818): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453885713628.3818
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3818): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3818): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): onWifiStateChanged: State changed to 2
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  818): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3818): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3818): createAdvertiseData: From: 1453885713628.3818 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3818): F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3818): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3818): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService( 2158): registerClient() - UUID=86399fba-a625-4fa7-a80d-50dd8542bcd8,
D/BtGatt.GattService( 2158): onClientRegistered() - UUID=86399fba-a625-4fa7-a80d-50dd8542bcd8, clientIf=5
D/BluetoothLeAdvertiser( 3818): onClientRegistered() - status=0 clientIf=5
,D/BtGatt.AdvertiseManager( 2158): message : 0
,D/BtGatt.AdvertiseManager( 2158): starting multi advertising
,D/BtGatt.GattService( 2158): onAdvertiseInstanceEnabled() - clientIf=5, status=0,
,D/BtGatt.GattService( 2158): onAdvertiseDataSet() - clientIf=5, status=0
,D/BtGatt.GattService( 2158): registerClient() - UUID=fef5b9c5-0d12-4dbb-a1f8-616de89fef8e,
D/BtGatt.GattService( 2158): onClientRegistered() - UUID=fef5b9c5-0d12-4dbb-a1f8-616de89fef8e, clientIf=6
D/BluetoothLeScanner( 3818): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.GattService( 2158): start scan with filters
D/BtGatt.ScanManager( 2158): handling starting scan
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): startBlePeerDiscovery: OK
,D/BluetoothManagerService(  818): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3818): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453885713628.3818","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3818): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453885713628.3818","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3818): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1453885713628.3818","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
D/BtGatt.GattService( 2158): onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
D/BtGatt.ScanManager( 2158): callback done for clientIf - 6 status - 0
,D/BtGatt.GattService( 2158): onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
D/BtGatt.ScanManager( 2158): callback done for clientIf - 6 status - 0
D/BtGatt.ScanManager( 2158): configureRegularScanParams() - queue=1
,D/BtGatt.ScanManager( 2158): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): onIsWifiPeerDiscoveryStartedChanged: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): startWifiPeerDiscovery: Wi-Fi Direct OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): setState: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 3818): start: OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453885713628.3818
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): startBlePeerDiscovery: OK
I/wpa_supplicant( 1044): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
I/jxcore-log( 3818): ok 68 Should be able to call startBroadcasting without error
,I/jxcore-log( 3818): 
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3818): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3818): onIsAdvertiserStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): setState: RESTARTING
,I/io.jxcore.node.ConnectionHelper( 3818): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3818): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 3818): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3818): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3818): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3818): stopListeningForIncomingConnections: Stopping...,
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3818): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3818): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3818): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3818): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3818): setState: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): stop: Stopping peer discovery...
I/io.jxcore.node.ConnectionHelper( 3818): onConnectionManagerStateChanged: NOT_STARTED
I/wpa_supplicant( 1044): P2P-FIND-STOPPED 
D/BtGatt.AdvertiseManager( 2158): message : 1
D/BtGatt.AdvertiseManager( 2158): stop advertise for client 5
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): P2P device discovery stopped successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): setState: RESTARTING
D/BtGatt.GattService( 2158): onAdvertiseInstanceDisabled() - clientIf=5, status=0
D/BtGatt.GattService( 2158): Client app is not null!
,D/BtGatt.GattService( 2158): unregisterClient() - clientIf=5,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3818): onIsAdvertiserStartedChanged: false
,D/BtGatt.GattService( 2158): stopScan() - queue size =1
,D/BtGatt.GattService( 2158): unregisterClient() - clientIf=6
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3818): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3818): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3818): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): stop: Stopping P2P device discovery...
D/BtGatt.GattService( 2158): onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
D/BtGatt.ScanManager( 2158): callback done for clientIf - 6 status - 0
,D/BtGatt.ScanManager( 2158): stop scan
,D/BtGatt.ScanManager( 2158): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager( 2158): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager( 2158): configureRegularScanParams() - queue emtpy, scan stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3818): Local services cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3818): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3818): release: No more listeners, de-initializing...,
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): setState: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3818): Service requests cleared successfully
,I/io.jxcore.node.ConnectionHelper( 3818): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 3818): ok 69 Should be able to call stopBroadcasting without error
I/jxcore-log( 3818): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  818): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3818): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453885713698.3818
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3818): bind: Binding a new listener
,D/BluetoothManagerService(  818): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3818): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  818): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3818): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453885713698.3818","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3818): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3818): startListeningForIncomingConnections
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3818): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  818): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
W/BluetoothAdapter( 3818): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3818): setState: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3818): start: OK
I/io.jxcore.node.ConnectionHelper( 3818): onConnectionManagerStateChanged: RUNNING
,I/io.jxcore.node.ConnectionHelper( 3818): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService(  818): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453885713698.3818
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3818): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3818): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3818): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  818): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3818): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3818): createAdvertiseData: From: 1453885713698.3818 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3818): F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3818): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3818): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService( 2158): registerClient() - UUID=fb7d0e5c-7f95-48d6-8f7b-4157aa15f9d3
D/BtGatt.GattService( 2158): onClientRegistered() - UUID=fb7d0e5c-7f95-48d6-8f7b-4157aa15f9d3, clientIf=5
,D/BluetoothLeAdvertiser( 3818): onClientRegistered() - status=0 clientIf=5
,D/BtGatt.AdvertiseManager( 2158): message : 0
,D/BtGatt.AdvertiseManager( 2158): starting multi advertising
,D/BtGatt.GattService( 2158): onAdvertiseInstanceEnabled() - clientIf=5, status=0
,D/BtGatt.GattService( 2158): onAdvertiseDataSet() - clientIf=5, status=0
,D/BtGatt.GattService( 2158): registerClient() - UUID=67bcafcb-81a9-495b-87f2-6af12732392d
,D/BtGatt.GattService( 2158): onClientRegistered() - UUID=67bcafcb-81a9-495b-87f2-6af12732392d, clientIf=6
D/BluetoothLeScanner( 3818): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.GattService( 2158): start scan with filters
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): startBlePeerDiscovery: OK
D/BtGatt.ScanManager( 2158): handling starting scan
,D/BluetoothManagerService(  818): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3818): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453885713698.3818","ra":"F8:CF:C5:D9:E5:61"},
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3818): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453885713698.3818","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3818): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1453885713698.3818","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
D/BtGatt.GattService( 2158): onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
D/BtGatt.ScanManager( 2158): callback done for clientIf - 6 status - 0
D/BtGatt.GattService( 2158): onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
D/BtGatt.ScanManager( 2158): callback done for clientIf - 6 status - 0
D/BtGatt.ScanManager( 2158): configureRegularScanParams() - queue=1
D/BtGatt.ScanManager( 2158): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): start: Starting P2P device discovery...
,I/wpa_supplicant( 1044): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): setState: RUNNING_BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453885713698.3818
,I/io.jxcore.node.ConnectionHelper( 3818): start: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): startBlePeerDiscovery: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3818): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3818): onIsAdvertiserStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3818): Local service added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): setState: RESTARTING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 3818): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/wpa_supplicant( 1044): P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): P2P device discovery stopped successfully,
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): setState: RESTARTING
,I/jxcore-log( 3818): ok 70 Should be able to call startBroadcasting without error
I/jxcore-log( 3818): 
I/io.jxcore.node.ConnectionHelper( 3818): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3818): stop: Stopping Bluetooth...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3818): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3818): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3818): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3818): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3818): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3818): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3818): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): stop: Stopping peer discovery...
I/io.jxcore.node.ConnectionHelper( 3818): onConnectionManagerStateChanged: NOT_STARTED
,D/BtGatt.AdvertiseManager( 2158): message : 1
D/BtGatt.AdvertiseManager( 2158): stop advertise for client 5
,D/BtGatt.GattService( 2158): onAdvertiseInstanceDisabled() - clientIf=5, status=0
,D/BtGatt.GattService( 2158): Client app is not null!
D/BtGatt.GattService( 2158): unregisterClient() - clientIf=5
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3818): onIsAdvertiserStartedChanged: false
,D/BtGatt.GattService( 2158): stopScan() - queue size =1
,D/BtGatt.GattService( 2158): unregisterClient() - clientIf=6
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3818): onIsScannerStartedChanged: false
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3818): setIsStarted: true
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3818): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): stop: Stopping P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3818): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): stopWifiPeerDiscovery: Stopped
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3818): release: No more listeners, de-initializing...
D/BtGatt.GattService( 2158): onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
D/BtGatt.ScanManager( 2158): callback done for clientIf - 6 status - 0
D/BtGatt.ScanManager( 2158): stop scan
D/BtGatt.ScanManager( 2158): configureRegularScanParams() - queue=0
,D/BtGatt.ScanManager( 2158): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager( 2158): configureRegularScanParams() - queue emtpy, scan stopped
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3818): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3818): Service requests cleared successfully
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3818): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 3818): ok 71 Should be able to call stopBroadcasting without error
I/jxcore-log( 3818): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  818): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3818): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453885713771.3818
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3818): bind: Binding a new listener
D/BluetoothManagerService(  818): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3818): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  818): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3818): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453885713771.3818","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3818): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3818): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3818): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  818): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0,
W/BluetoothAdapter( 3818): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3818): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3818): start: OK,
I/io.jxcore.node.ConnectionHelper( 3818): onConnectionManagerStateChanged: RUNNING
,I/io.jxcore.node.ConnectionHelper( 3818): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService(  818): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453885713771.3818
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3818): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3818): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3818): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  818): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3818): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3818): createAdvertiseData: From: 1453885713771.3818 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3818): F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3818): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3818): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService( 2158): registerClient() - UUID=edd5b11f-5b49-4d97-9770-fa97549dc6fe
D/BtGatt.GattService( 2158): onClientRegistered() - UUID=edd5b11f-5b49-4d97-9770-fa97549dc6fe, clientIf=5
,D/BluetoothLeAdvertiser( 3818): onClientRegistered() - status=0 clientIf=5
D/BtGatt.AdvertiseManager( 2158): message : 0
,D/BtGatt.AdvertiseManager( 2158): starting multi advertising
,D/BtGatt.GattService( 2158): onAdvertiseInstanceEnabled() - clientIf=5, status=0
,D/BtGatt.GattService( 2158): onAdvertiseDataSet() - clientIf=5, status=0
,D/BtGatt.GattService( 2158): registerClient() - UUID=ac8bc00d-0ef9-46ce-a90c-dd03b8d4d2cf
D/BtGatt.GattService( 2158): onClientRegistered() - UUID=ac8bc00d-0ef9-46ce-a90c-dd03b8d4d2cf, clientIf=6
D/BluetoothLeScanner( 3818): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.GattService( 2158): start scan with filters
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): startBlePeerDiscovery: OK
D/BtGatt.ScanManager( 2158): handling starting scan
,D/BluetoothManagerService(  818): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3818): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453885713771.3818","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3818): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453885713771.3818","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3818): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1453885713771.3818","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
D/BtGatt.GattService( 2158): onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
D/BtGatt.ScanManager( 2158): callback done for clientIf - 6 status - 0,
,D/BtGatt.GattService( 2158): onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
D/BtGatt.ScanManager( 2158): callback done for clientIf - 6 status - 0
,D/BtGatt.ScanManager( 2158): configureRegularScanParams() - queue=1
D/BtGatt.ScanManager( 2158): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): setState: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 3818): start: OK
I/wpa_supplicant( 1044): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453885713771.3818
I/jxcore-log( 3818): ok 72 Should be able to call startBroadcasting without error,
I/jxcore-log( 3818): 
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): startBlePeerDiscovery: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): startWifiPeerDiscovery: Wi-Fi Direct OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3818): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3818): onIsAdvertiserStartedChanged: true,
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3818): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 3818): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1044): P2P-FIND-STOPPED 
I/io.jxcore.node.ConnectionHelper( 3818): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3818): stop: Stopping Bluetooth...,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3818): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3818): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3818): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3818): release: 1 listener(s) left
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3818): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): stop: Stopping peer discovery...
I/io.jxcore.node.ConnectionHelper( 3818): onConnectionManagerStateChanged: NOT_STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3818): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3818): onServerStopped
D/BtGatt.AdvertiseManager( 2158): message : 1
D/BtGatt.AdvertiseManager( 2158): stop advertise for client 5
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): setState: RESTARTING
D/BtGatt.GattService( 2158): onAdvertiseInstanceDisabled() - clientIf=5, status=0
D/BtGatt.GattService( 2158): Client app is not null!
D/BtGatt.GattService( 2158): unregisterClient() - clientIf=5
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3818): onIsAdvertiserStartedChanged: false
D/BtGatt.GattService( 2158): stopScan() - queue size =1
D/BtGatt.GattService( 2158): unregisterClient() - clientIf=6
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3818): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3818): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): onIsBlePeerDiscoveryStartedChanged: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3818): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3818): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3818): release: No more listeners, de-initializing...
D/BtGatt.GattService( 2158): onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,D/BtGatt.ScanManager( 2158): callback done for clientIf - 6 status - 0
E/BtGatt.ContextMap( 2158): Context not found for ID 6
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3818): release: No more listeners, de-initializing...
D/BtGatt.ScanManager( 2158): stop scan
D/BtGatt.ScanManager( 2158): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager( 2158): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager( 2158): configureRegularScanParams() - queue emtpy, scan stopped
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3818): onDiscoveryManagerStateChanged: NOT_STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3818): Service requests cleared successfully
I/jxcore-log( 3818): ok 73 Should be able to call stopBroadcasting without error
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): # setup
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): # ThaliEmitter calls startBroadcasting twice with error
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): # teardown,
I/jxcore-log( 3818): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  818): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3818): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453885714101.3818
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3818): bind: Binding a new listener
,D/BluetoothManagerService(  818): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3818): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  818): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3818): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453885714101.3818","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3818): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3818): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3818): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  818): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3818): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3818): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3818): start: OK
,I/io.jxcore.node.ConnectionHelper( 3818): start: Using peer discovery mode: BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 3818): onConnectionManagerStateChanged: RUNNING
,D/BluetoothManagerService(  818): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453885714101.3818
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3818): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3818): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3818): Waiting for incoming connections...
,D/BluetoothManagerService(  818): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3818): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3818): createAdvertiseData: From: 1453885714101.3818 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3818): F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3818): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3818): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService( 2158): registerClient() - UUID=e06d1956-2952-4d02-b295-d57153a09e57
,D/BtGatt.GattService( 2158): onClientRegistered() - UUID=e06d1956-2952-4d02-b295-d57153a09e57, clientIf=5
D/BluetoothLeAdvertiser( 3818): onClientRegistered() - status=0 clientIf=5
,D/BtGatt.AdvertiseManager( 2158): message : 0
,D/BtGatt.AdvertiseManager( 2158): starting multi advertising
,D/BtGatt.GattService( 2158): onAdvertiseInstanceEnabled() - clientIf=5, status=0
,D/BtGatt.GattService( 2158): onAdvertiseDataSet() - clientIf=5, status=0
,D/BtGatt.GattService( 2158): registerClient() - UUID=d1ea3810-3f94-48c1-af87-a70db180c7b1
,D/BtGatt.GattService( 2158): onClientRegistered() - UUID=d1ea3810-3f94-48c1-af87-a70db180c7b1, clientIf=6
D/BluetoothLeScanner( 3818): onClientRegistered() - status=0 clientIf=6
D/BtGatt.GattService( 2158): start scan with filters
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): startBlePeerDiscovery: OK
,D/BtGatt.ScanManager( 2158): handling starting scan
,D/BluetoothManagerService(  818): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3818): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453885714101.3818","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3818): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453885714101.3818","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3818): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1453885714101.3818","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): setState: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 3818): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453885714101.3818
I/jxcore-log( 3818): ok 74 Should be able to call startBroadcasting without error
I/jxcore-log( 3818): 
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): startBlePeerDiscovery: OK
D/BtGatt.GattService( 2158): onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
D/BtGatt.ScanManager( 2158): callback done for clientIf - 6 status - 0
I/wpa_supplicant( 1044): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3818): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3818): onIsAdvertiserStartedChanged: true
D/BtGatt.GattService( 2158): onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,D/BtGatt.ScanManager( 2158): callback done for clientIf - 6 status - 0
I/io.jxcore.node.ConnectionHelper( 3818): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): setState: RESTARTING
I/art     ( 1136): Explicit concurrent mark sweep GC freed 59918(3MB) AllocSpace objects, 7(698KB) LOS objects, 36% free, 28MB/44MB, paused 1.147ms total 40.121ms
I/jxcore-log( 3818): ok 75 Cannot call startBroadcasting twice
I/jxcore-log( 3818): 
D/BtGatt.ScanManager( 2158): configureRegularScanParams() - queue=1
D/BtGatt.ScanManager( 2158): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3818): Local service added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/wpa_supplicant( 1044): P2P-FIND-STOPPED 
I/io.jxcore.node.ConnectionHelper( 3818): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3818): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3818): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3818): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3818): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3818): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3818): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3818): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3818): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): stop: Stopping peer discovery...
,I/io.jxcore.node.ConnectionHelper( 3818): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): setState: RESTARTING,
,D/BtGatt.AdvertiseManager( 2158): message : 1
D/BtGatt.AdvertiseManager( 2158): stop advertise for client 5
,D/BtGatt.GattService( 2158): onAdvertiseInstanceDisabled() - clientIf=5, status=0
D/BtGatt.GattService( 2158): Client app is not null!
,D/BtGatt.GattService( 2158): unregisterClient() - clientIf=5
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3818): onIsAdvertiserStartedChanged: false
,D/BtGatt.GattService( 2158): stopScan() - queue size =1
D/BtGatt.GattService( 2158): unregisterClient() - clientIf=6
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3818): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3818): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3818): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3818): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3818): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): setState: NOT_STARTED
,D/BtGatt.GattService( 2158): onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
D/BtGatt.ScanManager( 2158): callback done for clientIf - 6 status - 0
D/BtGatt.ScanManager( 2158): stop scan
D/BtGatt.ScanManager( 2158): configureRegularScanParams() - queue=0
I/jxcore-log( 3818): ok 76 Should be able to call stopBroadcasting without error
I/jxcore-log( 3818): 
D/BtGatt.ScanManager( 2158): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager( 2158): configureRegularScanParams() - queue emtpy, scan stopped
,I/jxcore-log( 3818): # setup
I/jxcore-log( 3818): 
,I/io.jxcore.node.ConnectionHelper( 3818): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3818): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): P2P device discovery stopped successfully
,V/GoogleAuthProtoRequest( 3880): [423] a.<init>: mAccountName set to: thalitester@gmail.com
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3818): Service requests cleared successfully
,I/GLSUser ( 1136): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova,
I/GLSUser ( 1136): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
,I/GLSUser ( 1136): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1136): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,V/GLSActivity( 1136): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3880): [423] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3880): [423] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3880): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3880): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3880): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3880): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3880): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3880): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3880): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3880): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3880): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3880): 	at com.a.a.k.run(SourceFile:110)
,I/jxcore-log( 3818): # ThaliEmitter throws on connection to bad peer
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): # teardown
I/jxcore-log( 3818): ,
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  818): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3818): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453885714647.3818
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3818): bind: Binding a new listener
D/BluetoothManagerService(  818): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3818): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  818): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3818): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453885714647.3818","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3818): setConnectionTimeout: 15000
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3818): startListeningForIncomingConnections
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3818): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  818): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
W/BluetoothAdapter( 3818): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3818): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3818): start: OK
I/io.jxcore.node.ConnectionHelper( 3818): start: Using peer discovery mode: BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 3818): onConnectionManagerStateChanged: RUNNING
,D/BluetoothManagerService(  818): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453885714647.3818
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3818): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3818): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3818): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  818): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3818): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3818): createAdvertiseData: From: 1453885714647.3818 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3818): F8:CF:C5:D9:E5:61
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3818): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3818): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0,
,D/BtGatt.GattService( 2158): registerClient() - UUID=8081a99c-cbac-4510-9816-633cf907ad7b
,D/BtGatt.GattService( 2158): onClientRegistered() - UUID=8081a99c-cbac-4510-9816-633cf907ad7b, clientIf=5
D/BluetoothLeAdvertiser( 3818): onClientRegistered() - status=0 clientIf=5
,D/BtGatt.AdvertiseManager( 2158): message : 0
,D/BtGatt.AdvertiseManager( 2158): starting multi advertising
,D/BtGatt.GattService( 2158): onAdvertiseInstanceEnabled() - clientIf=5, status=0
,D/BtGatt.GattService( 2158): onAdvertiseDataSet() - clientIf=5, status=0
,D/BtGatt.GattService( 2158): registerClient() - UUID=7553e0eb-a9d9-46d8-823b-abe8e4f13769
,D/BtGatt.GattService( 2158): onClientRegistered() - UUID=7553e0eb-a9d9-46d8-823b-abe8e4f13769, clientIf=6
D/BluetoothLeScanner( 3818): onClientRegistered() - status=0 clientIf=6
D/BtGatt.GattService( 2158): start scan with filters
D/BtGatt.ScanManager( 2158): handling starting scan
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): startBlePeerDiscovery: OK
,D/BluetoothManagerService(  818): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/BtGatt.GattService( 2158): onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,D/BtGatt.ScanManager( 2158): callback done for clientIf - 6 status - 0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3818): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453885714647.3818","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3818): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453885714647.3818","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3818): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1453885714647.3818","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
,D/BtGatt.GattService( 2158): onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
D/BtGatt.ScanManager( 2158): callback done for clientIf - 6 status - 0
,D/BtGatt.ScanManager( 2158): configureRegularScanParams() - queue=1
D/BtGatt.ScanManager( 2158): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): setState: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 3818): start: OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453885714647.3818
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): startBlePeerDiscovery: Already running
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): startBlePeerDiscovery: OK
I/jxcore-log( 3818): ok 77 Should be able to call startBroadcasting without error
I/jxcore-log( 3818): 
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): startWifiPeerDiscovery: Wi-Fi Direct OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3818): onStartSuccess
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3818): onIsAdvertiserStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 3818): connect: Trying to connect to peer with ID foobar
,W/io.jxcore.node.ConnectionHelper( 3818): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/io.jxcore.node.ConnectionHelper( 3818): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3818): Local service added successfully
E/io.jxcore.node.ConnectionHelper( 3818): connect: Invalid Bluetooth address: foobar
I/wpa_supplicant( 1044): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): setState: STARTED
I/wpa_supplicant( 1044): P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/jxcore-log( 3818): ok 78 Should not connect to a bad peer,
I/jxcore-log( 3818): 
I/io.jxcore.node.ConnectionHelper( 3818): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3818): stop: Stopping Bluetooth...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3818): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3818): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3818): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3818): Exiting thread
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3818): release: 1 listener(s) left
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3818): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3818): setState: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): stop: Stopping peer discovery...
,I/io.jxcore.node.ConnectionHelper( 3818): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): setState: RESTARTING
,D/BtGatt.AdvertiseManager( 2158): message : 1
D/BtGatt.AdvertiseManager( 2158): stop advertise for client 5
,D/BtGatt.GattService( 2158): onAdvertiseInstanceDisabled() - clientIf=5, status=0
,D/BtGatt.GattService( 2158): Client app is not null!
D/BtGatt.GattService( 2158): unregisterClient() - clientIf=5
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3818): onIsAdvertiserStartedChanged: false
,D/BtGatt.GattService( 2158): stopScan() - queue size =1
,D/BtGatt.GattService( 2158): unregisterClient() - clientIf=6
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3818): onIsScannerStartedChanged: false
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3818): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3818): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): setState: NOT_INITIALIZED
D/BtGatt.GattService( 2158): onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
D/BtGatt.ScanManager( 2158): callback done for clientIf - 6 status - 0
D/BtGatt.ScanManager( 2158): stop scan
D/BtGatt.ScanManager( 2158): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager( 2158): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager( 2158): configureRegularScanParams() - queue emtpy, scan stopped
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3818): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3818): Local services cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3818): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): setState: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper( 3818): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): P2P device discovery stopped successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3818): Service requests cleared successfully
,I/jxcore-log( 3818): ok 79 Should be able to call stopBroadcasting without error
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): # setup
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): # ThaliEmitter throws on disconnect to bad peer
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): # teardown
I/jxcore-log( 3818): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  818): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3818): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453885715058.3818,
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3818): bind: Binding a new listener
,D/BluetoothManagerService(  818): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3818): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  818): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0,
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3818): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453885715058.3818","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3818): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3818): startListeningForIncomingConnections
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3818): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  818): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3818): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3818): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper( 3818): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3818): start: OK
I/io.jxcore.node.ConnectionHelper( 3818): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService(  818): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3818): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453885715058.3818
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3818): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3818): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): onWifiStateChanged: State changed to 2
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  818): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3818): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3818): createAdvertiseData: From: 1453885715058.3818 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3818): F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3818): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3818): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService( 2158): registerClient() - UUID=c5054fb1-a103-4551-88b2-25f9e9a66837
,D/BtGatt.GattService( 2158): onClientRegistered() - UUID=c5054fb1-a103-4551-88b2-25f9e9a66837, clientIf=5
D/BluetoothLeAdvertiser( 3818): onClientRegistered() - status=0 clientIf=5
,D/BtGatt.AdvertiseManager( 2158): message : 0
,D/BtGatt.AdvertiseManager( 2158): starting multi advertising
,D/BtGatt.GattService( 2158): onAdvertiseInstanceEnabled() - clientIf=5, status=0
,D/BtGatt.GattService( 2158): onAdvertiseDataSet() - clientIf=5, status=0
,D/BtGatt.GattService( 2158): registerClient() - UUID=ef888283-bde7-4ce1-9be2-3dcbfc8f21a3
,D/BtGatt.GattService( 2158): onClientRegistered() - UUID=ef888283-bde7-4ce1-9be2-3dcbfc8f21a3, clientIf=6
D/BluetoothLeScanner( 3818): onClientRegistered() - status=0 clientIf=6
D/BtGatt.GattService( 2158): start scan with filters
D/BtGatt.ScanManager( 2158): handling starting scan
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): startBlePeerDiscovery: OK
,D/BluetoothManagerService(  818): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
D/BtGatt.GattService( 2158): onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
D/BtGatt.ScanManager( 2158): callback done for clientIf - 6 status - 0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3818): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453885715058.3818","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3818): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453885715058.3818","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3818): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1453885715058.3818","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
D/BtGatt.GattService( 2158): onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
D/BtGatt.ScanManager( 2158): callback done for clientIf - 6 status - 0
D/BtGatt.ScanManager( 2158): configureRegularScanParams() - queue=1
,D/BtGatt.ScanManager( 2158): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): onIsWifiPeerDiscoveryStartedChanged: true,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): startWifiPeerDiscovery: Wi-Fi Direct OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): start: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): setState: RUNNING_BLE_AND_WIFI
,I/io.jxcore.node.ConnectionHelper( 3818): start: OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453885715058.3818
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): startBlePeerDiscovery: OK,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): startWifiPeerDiscovery: Wi-Fi Direct OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): start: OK,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3818): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3818): onIsAdvertiserStartedChanged: true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): setState: RESTARTING,
I/io.jxcore.node.ConnectionHelper( 3818): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
I/jxcore-log( 3818): ok 80 Should be able to call startBroadcasting without error
I/jxcore-log( 3818): ,
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3818): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): P2P device discovery started successfully
,I/wpa_supplicant( 1044): P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started,
D/io.jxcore.node.ConnectionHelper( 3818): disconnectOutgoingConnection: Trying to close connection to peer with ID foobar
E/io.jxcore.node.ConnectionHelper( 3818): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID foobar
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): P2P device discovery stopped successfully
D/io.jxcore.node.ConnectionHelper( 3818): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
,W/io.jxcore.node.ConnectionHelper( 3818): disconnectOutgoingConnection: Failed to disconnect (peer ID: foobar), either no such connection or failed to close the connection
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): setState: RESTARTING
,I/jxcore-log( 3818): ok 81 Disconnect should fail to a non-existant peer ,
I/jxcore-log( 3818): 
I/io.jxcore.node.ConnectionHelper( 3818): stop
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3818): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3818): Shutting down...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3818): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3818): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3818): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3818): onServerStopped
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3818): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3818): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): stop: Stopping peer discovery...
I/io.jxcore.node.ConnectionHelper( 3818): onConnectionManagerStateChanged: NOT_STARTED
D/BtGatt.AdvertiseManager( 2158): message : 1
D/BtGatt.AdvertiseManager( 2158): stop advertise for client 5
D/BtGatt.GattService( 2158): onAdvertiseInstanceDisabled() - clientIf=5, status=0
D/BtGatt.GattService( 2158): Client app is not null!
,D/BtGatt.GattService( 2158): unregisterClient() - clientIf=5
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3818): onIsAdvertiserStartedChanged: false
,D/BtGatt.GattService( 2158): stopScan() - queue size =1
,D/BtGatt.GattService( 2158): unregisterClient() - clientIf=6
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3818): onIsScannerStartedChanged: false
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3818): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3818): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): stop: Stopping P2P device discovery...,
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3818): Local services cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3818): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3818): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3818): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3818): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3818): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3818): Service requests cleared successfully
D/BtGatt.GattService( 2158): onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
D/BtGatt.ScanManager( 2158): callback done for clientIf - 6 status - 0
D/BtGatt.ScanManager( 2158): stop scan
,D/BtGatt.ScanManager( 2158): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager( 2158): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager( 2158): configureRegularScanParams() - queue emtpy, scan stopped
I/jxcore-log( 3818): ok 82 Should be able to call stopBroadcasting without error
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): # setup
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): # #startListeningForAdvertisements should emit wifiPeerAvailabilityChanged after test peer becomes available
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): # teardown
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): ok 83 host address should match
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): ok 84 port should match
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): # setup
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): # #startUpdateAdvertisingAndListening should use different USN after every invocation
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): # teardown
I/jxcore-log( 3818): 
,D/HeadsetStateMachine( 2158): Disconnected process message: 10, size: 0
,I/jxcore-log( 3818): ok 85 USN should have changed from the first one
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): # setup
I/jxcore-log( 3818): ,
,I/jxcore-log( 3818): # messages with invalid location or USN should be ignored
I/jxcore-log( 3818): ,
,I/jxcore-log( 3818): # teardown,
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): WARN thaliWifiInfrastructure Failed to parse a valid port number from location: http://foo.bar:90000
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): ok 86 should not have emitted with invalid port
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): WARN thaliWifiInfrastructure Received an invalid USN value: 
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): ok 87 should not have emitted with invalid USN
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): # setup
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): # verify that Thali-specific messages are filtered correctly
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): # teardown
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): ok 88 irrelevant messages should be ignored
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): ok 89 relevant messages should not be ignored
I/jxcore-log( 3818): 
I/jxcore-log( 3818): ok 90 messages from this device should be ignored
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): # setup
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): # #start should fail if called twice in a row
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): # teardown
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): ok 91 specific error should be received
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): # setup
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): # #startUpdateAdvertisingAndListening should fail invalid router has been passed
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): # teardown
,I/jxcore-log( 3818): 
,E/jxcore-log( 3818): ERROR thaliWifiInfrastructure Unable to use the given router: TypeError: Router.use() requires middleware function but got a string
E/jxcore-log( 3818): 
,I/jxcore-log( 3818): ok 92 specific error should be received
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): # setup
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): # #startUpdateAdvertisingAndListening should fail if router server starting fails
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): # teardown
I/jxcore-log( 3818): 
,E/jxcore-log( 3818): ERROR thaliWifiInfrastructure Router server emitted an error: Error: listen EADDRINUSE
E/jxcore-log( 3818): 
,I/jxcore-log( 3818): ok 93 specific error expected
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): # setup
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): # #startUpdateAdvertisingAndListening should start hosting given router object
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): # teardown
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): ok 94 server should respond with code 200
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): # setup
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): # #stop can be called multiple times in a row
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): # teardown
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): ok 95 should be in stopped state
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): ok 96 should still be in stopped state
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): Tests Complete
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): Total: 0	Passed: 0	Failed: 0
I/jxcore-log( 3818): 
,I/chromium( 3818): [INFO:CONSOLE(63)] "logCallback ------ Final results ---- ", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3818): Toggling radios to false
I/jxcore-log( 3818): 
,I/chromium( 3818): [INFO:CONSOLE(63)] "logCallback Total: 0, Passed: 0, Failed: 0", source: file:///android_asset/www/js/thali_main.js (63)
,D/BluetoothManagerService(  818): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/BluetoothManagerService(  818): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@109d8ae1 mBinding = false
,D/BluetoothManagerService(  818): Message: 2
,D/WifiService(  818): setWifiEnabled: false pid=3818, uid=10265,
E/WifiService(  818): Invoking mWifiStateMachine.setWifiEnabled
,D/BluetoothManagerService(  818): Sending off request.
D/BluetoothAdapterState( 2158): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 2158): Setting state to 13
I/BluetoothAdapterState( 2158): Bluetooth adapter state changed: 12-> 13
D/BluetoothManagerService(  818): Message: 60
D/BluetoothManagerService(  818): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService(  818): Bluetooth State Change Intent: 12 -> 13
D/BluetoothAdapterProperties( 2158): onBluetoothDisable()
I/BluetoothAdapterState( 2158): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
D/BluetoothMapService( 2158): onReceive
,D/BluetoothMapService( 2158): STATE_TURNING_OFF
D/BluetoothMapService( 2158): MAP Service closeService in
D/BluetoothMapMasInstance( 2158): MAP Service shutdown
V/BluetoothMapMasInstance( 2158): Accept exception: (expected at shutdown)
V/BluetoothMapMasInstance( 2158): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 2158): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
V/BluetoothMapMasInstance( 2158): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:489)
V/BluetoothMapMasInstance( 2158): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:399)
V/BluetoothMapMasInstance( 2158): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
V/BluetoothMapMasInstance( 2158): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
V/BluetoothMapMasInstance( 2158): 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
,I/BtOppRfcommListener( 2158): stopping Accept Thread
E/BtOppRfcommListener( 2158): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/BtOppRfcommListener( 2158): BluetoothSocket listen thread finished
,I/jxcore-log( 3818): Radios toggled,
I/jxcore-log( 3818): 
E/WifiStateMachine(  818): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  818): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,I/jxcore-log( 3818): ****TEST TOOK:  ms ****
I/jxcore-log( 3818): 
,I/jxcore-log( 3818): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3818): 
E/native  (  818): do suspend true
,D/CommandListener(  352): Clearing all IP addresses on wlan0
V/NativeCrypto( 1136): Read error: ssl=0x9cda8a00: I/O error during system call, Connection timed out
I/jxcore-log( 3818): Toggling radios to false
I/jxcore-log( 3818): 
,I/ActivityManager(  818): Start proc 4176:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,D/BluetoothAdapterProperties( 2158): Scan Mode:20
D/BluetoothAdapterState( 2158): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
D/BluetoothManagerService(  818): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
D/BluetoothManagerService(  818): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@109d8ae1 mBinding = false
D/btif_config_util( 2158): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
W/bt-btif ( 2158): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
W/bt-l2cap( 2158): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2158): L2CAP - PSM: 0x0017 not found for deregistration
D/BluetoothManagerService(  818): Message: 2
D/BluetoothManagerService(  818): Sending off request.
D/ConnectivityService(  818): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  818): NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
E/WifiStateMachine(  818): scanCount==0 - aborting
,D/BluetoothAdapterState( 2158): CURRENT_STATE=PENDING, MESSAGE = USER_TURN_ON, isTurningOn=false, isTurningOff=true
,I/BluetoothAdapterState( 2158): CURRENT_STATE=PENDING: Alreadying turning off bluetooth... Ignoring USER_TURN_OFF...
D/WifiService(  818): setWifiEnabled: false pid=3818, uid=10265
E/WifiService(  818): Invoking mWifiStateMachine.setWifiEnabled
D/WifiScanningService(  818): SCAN_AVAILABLE : 1
D/RttService(  818): SCAN_AVAILABLE : 1
D/WifiScanningService(  818): StartedState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService(  818): DefaultState
D/RttService(  818): EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
I/jxcore-log( 3818): Radios toggled
I/jxcore-log( 3818): 
,D/WifiNetworkAgent(  818): NetworkAgent: NetworkAgent channel lost
E/native  (  818): do suspend true
,D/CommandListener(  352): Clearing all IP addresses on wlan0
,E/WifiStateMachine(  818): SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,I/art     (  818): Explicit concurrent mark sweep GC freed 40116(1980KB) AllocSpace objects, 10(819KB) LOS objects, 31% free, 34MB/50MB, paused 1.784ms total 82.069ms
,W/ContextImpl( 4176): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,V/NativeCrypto( 1136): SSL shutdown failed: ssl=0x9cda8a00: I/O error during system call, Broken pipe
,D/ConnectivityService(  818): notifyType LOST for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler( 1066): CM callback handler got msg 524292
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  818): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  818): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  818): Disconnected - quitting
D/ConnectivityService(  818): reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10011
D/CSLegacyTypeTracker(  818): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  818): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  818): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  818): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/Tethering(  818): MasterInitialState.processMessage what=3
,D/BluetoothManagerService(  818): Message: 20
D/BluetoothManagerService(  818): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@284194f4:true
,D/ConnectivityService(  818): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  818): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/NetworkChangeNotifierAutoDetect( 1483): Network connectivity changed, type is: 6
,D/Tethering(  818): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 3079): type=WIFI subType= reason=null isConnected=false
,I/wpa_supplicant( 1044): p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,D/PhoneInterfaceManager( 1281): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1281): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,I/wpa_supplicant( 1044): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,D/TelephonyManager(  818): getDataEnabled: retVal=false
,I/ActivityManager(  818): Start proc 4201:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,E/GpsLocationProvider(  818): No APN found to select.
,D/BluetoothManagerService(  818): Message: 30
,I/art     (  367): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 203us total 9.681ms
,D/BluetoothManagerService(  818): Message: 30
,D/LocalBluetoothProfileManager( 4176): Adding local MAP profile
D/BluetoothMap( 4176): Create BluetoothMap proxy object
,D/BluetoothManagerService(  818): Message: 30
,I/art     (  367): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 203us total 8.554ms
D/BluetoothManagerService(  818): Message: 30
,D/LocalBluetoothProfileManager( 4176): LocalBluetoothProfileManager construction complete
,D/DockEventReceiver( 4176): finishStartingService: stopping service
,D/BluetoothInputDevice( 4176): Proxy object connected
D/HidProfile( 4176): Bluetooth service connected
,I/art     (  367): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 193us total 8.817ms
D/BluetoothPan( 4176): BluetoothPAN Proxy object connected
,D/PanProfile( 4176): Bluetooth service connected
D/BluetoothMap( 4176): Proxy object connected
D/MapProfile( 4176): Bluetooth service connected
D/BluetoothMap( 4176): getConnectedDevices()
D/BluetoothMap( 4176): Bluetooth is Not enabled
,I/ActivityManager(  818): Killing 2487:com.google.android.calendar/u0a37 (adj 15): empty #17
,D/PhoneInterfaceManager( 1281): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1281): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
D/TelephonyManager(  818): getDataEnabled: retVal=false
,D/AndroidRuntime( 4197): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,D/AndroidRuntime( 4197): CheckJNI is OFF
,W/bt-btif ( 2158): ag scb idx 1 not allocated
E/bt-btif ( 2158): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 2158): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2158): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2158): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2158): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2158): L2CAP - PSM: 0x0019 not found for deregistration
,W/bt-l2cap( 2158): L2CAP - PSM: 0x0017 not found for deregistration
D/bt_userial( 2158): RX termination
W/bt_userial( 2158): select_read return size <=0:-1, exiting userial_read_thread
D/bt_userial( 2158): Leaving userial_read_thread()
D/bt_userial( 2158): userial_close_reader Joined userial reader thread: 0
D/bt_hwcfg( 2158): hw_epilog_process
I/bt_userial_vendor( 2158): device fd = 53 close
,D/AndroidRuntime( 4197): Calling main entry com.android.commands.pm.Pm
,E/GpsLocationProvider(  818): No APN found to select.
,I/ActivityManager(  818): Force stopping com.test.thalitest appid=10265 user=-1: uninstall pkg
,I/ActivityManager(  818): Killing 3818:com.test.thalitest/u0a265 (adj 0): stop com.test.thalitest
,I/GKI_LINUX( 2158): gki_task task_id=0 [BTU] terminating
I/GKI_LINUX( 2158): GKI_exit_task 0 done
I/GKI_LINUX( 2158): GKI_shutdown(): task [BTU] terminated
D/BluetoothAdapterState( 2158): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,I/wpa_supplicant( 1044): wlan0: CTRL-EVENT-TERMINATING 
D/Tethering(  818): InitialState.processMessage what=4
,E/WifiMonitor(  818): killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,W/PackageSettings(  818): Skipping PackageSetting{28e5c46c com.example.hello/10273} due to missing metadata
,I/WindowState(  818): WIN DEATH: Window{12b47e7e u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  818): Client connection lost with reason: 4
,W/ActivityManager(  818): Force removing ActivityRecord{277e7d07 u0 com.test.thalitest/.MainActivity t28}: app died, no saved state
,V/ActivityManager(  818): Display changed displayId=0,
,I/ActivityManager(  818): Force stopping com.test.thalitest appid=10265 user=0: pkg removed
,D/Tethering(  818): sendTetherStateChangedBroadcast 0, 0, 0
W/ActivityManager(  818): Spurious death for ProcessRecord{16f21e8d 3818:com.test.thalitest/u0a265}, curProc for 3818: null
,D/TaskPersister(  818): removeObsoleteFile: deleting file=28_task.xml
,D/HeadsetService( 2158): Received stop request...Stopping profile...
D/HeadsetStateMachine( 2158): Exit Disconnected: -1
,D/BluetoothHeadset(  818): Proxy object disconnected
,D/BluetoothHeadset( 1066): Proxy object disconnected
D/BluetoothHeadset( 1281): Proxy object disconnected
D/BluetoothHeadset(  818): Proxy object disconnected
D/BluetoothHeadset(  818): Proxy object disconnected
D/A2dpService( 2158): Received stop request...Stopping profile...
D/A2dpStateMachine( 2158): Exit Disconnected: -1
D/BluetoothAdapterState( 2158): Stopping profile services that were post enabled
,D/BluetoothA2dp(  818): Proxy object disconnected
,W/Settings( 2804): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Keyboard.Facilitator( 1231): resetDictionaries() : en_US
,I/Keyboard.Facilitator.DecoderInitializer( 1231): run()
,D/HidService( 2158): Received stop request...Stopping profile...
D/HealthService( 2158): Received stop request...Stopping profile...
D/PanService( 2158): Received stop request...Stopping profile...
D/BluetoothInputDevice( 4176): Proxy object disconnected
D/HidProfile( 4176): Bluetooth service disconnected
D/BluetoothPan( 4176): BluetoothPAN Proxy object disconnected
D/PanProfile( 4176): Bluetooth service disconnected
D/HeadsetStateMachine( 2158): Unbinding service...
,I/InputReader(  818): Reconfiguring input devices.  changes=0x00000010
,I/art     ( 1483): Explicit concurrent mark sweep GC freed 3000(190KB) AllocSpace objects, 0(0B) LOS objects, 22% free, 27MB/35MB, paused 1.167ms total 85.233ms
,W/BluetoothHeadsetServiceJni( 2158): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 2158): Cleaning up Bluetooth Handsfree callback object
,D/BtGatt.DebugUtils( 2158): handleDebugAction() action=null
D/BtGatt.GattService( 2158): Received stop request...Stopping profile...
D/BtGatt.GattService( 2158): stop()
D/BtGatt.AdvertiseManager( 2158): advertise clients cleared
,D/BluetoothMapService( 2158): Received stop request...Stopping profile...
D/BluetoothMapService( 2158): stop()
,D/BluetoothMapEmailAppObserver( 2158): deinitObservers()
D/BluetoothMapEmailAppObserver( 2158): removeReceiver()
,W/Settings( 1811): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/GKI_LINUX( 2158): gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 2158): GKI_exit_task 2 done
I/GKI_LINUX( 2158): GKI_shutdown(): task [A2DP-MEDIA] terminated
W/BluetoothHidServiceJni( 2158): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 2158): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 2158): Cleaning up Bluetooth GID callback object
W/BluetoothHealthServiceJni( 2158): Cleaning up Bluetooth Health Interface...
,W/BluetoothHealthServiceJni( 2158): Cleaning up Bluetooth Health object,
W/BluetoothPanServiceJni( 2158): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 2158): Cleaning up Bluetooth PAN callback object
D/BluetoothMapService( 2158): MAP Service closeService in
D/BluetoothAdapterState( 2158): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 2158): Setting state to 10
I/BluetoothAdapterState( 2158): Bluetooth adapter state changed: 13-> 10
D/BluetoothManagerService(  818): Message: 60
D/BluetoothManagerService(  818): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService(  818): Broadcasting onBluetoothStateChange(false) to 17 receivers.
D/BluetoothA2dpSink( 1066): onBluetoothStateChange: up=false
,E/BluetoothA2dpSink( 1066): 
E/BluetoothA2dpSink( 1066): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothA2dpSink$2@3f950d43
E/BluetoothA2dpSink( 1066): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1029)
E/BluetoothA2dpSink( 1066): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1808)
E/BluetoothA2dpSink( 1066): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:551)
E/BluetoothA2dpSink( 1066): 	at android.bluetooth.BluetoothA2dpSink$1.onBluetoothStateChange(BluetoothA2dpSink.java:139)
E/BluetoothA2dpSink( 1066): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothA2dpSink( 1066): 	at android.os.Binder.execTransact(Binder.java:446)
I/BluetoothAdapterState( 2158): Entering OffState
D/BluetoothMapService( 2158): cleanup()
D/BluetoothMapService( 2158): MAP Service closeService in
,D/BluetoothMap( 4176): onBluetoothStateChange: up=false
,D/BluetoothA2dp(  818): onBluetoothStateChange: up=false,
D/BluetoothHeadsetClient( 1066): onBluetoothStateChange: up=false
E/BluetoothHeadsetClient( 1066): 
E/BluetoothHeadsetClient( 1066): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothHeadsetClient$2@1533fc0
E/BluetoothHeadsetClient( 1066): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1029)
E/BluetoothHeadsetClient( 1066): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1808)
E/BluetoothHeadsetClient( 1066): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:551),
E/BluetoothHeadsetClient( 1066): 	at android.bluetooth.BluetoothHeadsetClient$1.onBluetoothStateChange(BluetoothHeadsetClient.java:382)
E/BluetoothHeadsetClient( 1066): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothHeadsetClient( 1066): 	at android.os.Binder.execTransact(Binder.java:446)
,D/BluetoothA2dp( 1066): onBluetoothStateChange: up=false
,I/Decoder ( 1231): createOrResetDecoder
D/BluetoothMap( 1066): onBluetoothStateChange: up=false
D/BluetoothPbap( 4176): onBluetoothStateChange: up=false
,D/BluetoothInputDevice( 4176): onBluetoothStateChange: up=false
,D/BluetoothHeadset(  818): onBluetoothStateChange: up=false
D/BluetoothHeadset(  818): onBluetoothStateChange: up=false
D/BluetoothHeadset(  818): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1281): onBluetoothStateChange: up=false
D/BluetoothInputDevice( 1066): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1066): onBluetoothStateChange: up=false
,D/BluetoothAvrcpController( 1066): onBluetoothStateChange: up=false
,E/BluetoothAvrcpController( 1066): 
E/BluetoothAvrcpController( 1066): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothAvrcpController$2@3c5ed4f9
E/BluetoothAvrcpController( 1066): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1029)
E/BluetoothAvrcpController( 1066): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1808)
E/BluetoothAvrcpController( 1066): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:551)
E/BluetoothAvrcpController( 1066): 	at android.bluetooth.BluetoothAvrcpController$1.onBluetoothStateChange(BluetoothAvrcpController.java:80)
E/BluetoothAvrcpController( 1066): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothAvrcpController( 1066): 	at android.os.Binder.execTransact(Binder.java:446)
D/BluetoothManagerService(  818): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService(  818): Broadcasting onBluetoothServiceDown() to 7 receivers.
,I/art     ( 1066): Explicit concurrent mark sweep GC freed 58043(2MB) AllocSpace objects, 0(0B) LOS objects, 18% free, 71MB/87MB, paused 3.680ms total 110.576ms
D/BluetoothManagerService(  818): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@109d8ae1 mBinding = false
,D/BluetoothManagerService(  818): Sending unbind request.
D/BluetoothManagerService(  818): Bluetooth State Change Intent: 13 -> 10
,D/BluetoothAdapter( 1066): 629864195: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1066): 629864195: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1066): 629864195: getState() :  mService = null. Returning STATE_OFF
,I/GKI_LINUX( 2158): gki_task task_id=1 [BTIF] terminating
,I/GKI_LINUX( 2158): GKI_exit_task 1 done
I/GKI_LINUX( 2158): GKI_shutdown(): task [BTIF] terminated
,I/BluetoothServiceJni( 2158): cleanupNative: return from cleanup
I/art     ( 2158): System.exit called, status: 0
I/AndroidRuntime( 2158): VM exiting with result code 0, cleanup skipped.
,I/ConfigService( 1136): onCreate
,D/JobSchedulerService(  818): Receieved: android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  818): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1231): run()
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1231): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/ActivityManager(  818): Process com.android.bluetooth (pid 2158) has died
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1231): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1231): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1231): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1231): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1231): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1231): run() : Loading LM = user
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1231): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1231): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1231): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1231): run()
I/StatsUtilsManager( 1231): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1231): shouldRecordStats() = Too Soon
,D/StrictMode( 4201): StrictMode policy violation; ~duration=457 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4201): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4201): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 4201): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 4201): 	at java.io.File.exists(File.java:363)
D/StrictMode( 4201): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:995)
D/StrictMode( 4201): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1018)
D/StrictMode( 4201): 	at android.content.ContextWrapper.getFilesDir(ContextWrapper.java:202)
D/StrictMode( 4201): 	at com.google.android.libraries.stitch.incompat.missinglibs.a.a(PG:31)
D/StrictMode( 4201): 	at com.google.android.libraries.stitch.incompat.b.a(PG:116)
D/StrictMode( 4201): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:510)
D/StrictMode( 4201): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4201): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4201): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4201): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4201): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4201): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4201): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4201): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4201): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4201): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4201): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4201): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 4201): StrictMode policy violation; ~duration=456 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4201): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4201): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 4201): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 4201): 	at java.io.File.exists(File.java:363)
D/StrictMode( 4201): 	at com.google.android.libraries.stitch.incompat.b.a(PG:116)
D/StrictMode( 4201): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:510)
D/StrictMode( 4201): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4201): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4201): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4201): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4201): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4201): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4201): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4201): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4201): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4201): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4201): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4201): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 4201): StrictMode policy violation; ~duration=454 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4201): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4201): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 4201): 	at libcore.io.IoUtils,.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 4201): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 4201): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 4201): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 4201): 	at java.lang.System.loadLibrary(System.java:988)
D/StrictMode( 4201): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:182)
D/StrictMode( 4201): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:81)
D/StrictMode( 4201): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:524)
D/StrictMode( 4201): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4201): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4201): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4201): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4201): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4201): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4201): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4201): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4201): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4201): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4201): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4201): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 4201): StrictMode policy violation; ~duration=447 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4201): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4201): 	at android.app.SharedPreferencesImpl.awaitLoadedLocked(SharedPreferencesImpl.java:202)
D/StrictMode( 4201): 	at android.app.SharedPreferencesImpl.getBoolean(SharedPreferencesImpl.java:259)
D/StrictMode( 4201): 	at android.preference.PreferenceManager.setDefaultValues(PreferenceManager.java:481)
D/StrictMode( 4201): 	at com.google.android.apps.gmm.shared.b.a.a(PG:938)
D/StrictMode( 4201): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 4201): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4201): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4201): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4201): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4201): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4201): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4201): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4201): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4201): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4201): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4201): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4201): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 4201): StrictMode policy violation; ~duration=439 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4201): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4201): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 4201): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 4201): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 4201): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 4201): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 4201): 	at java.lang.System.loadLibrary(System.java:988)
D/StrictMode( 4201): 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:42)
D/StrictMode( 4201): 	at com.google.android.apps.gmm.map.n.f.<clinit>(PG:80)
D/StrictMode( 4201): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 4201): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4201): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4201): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4201): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4201): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4201): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4201): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4201): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4201): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4201): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4201): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4201): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 4201): StrictMode policy violation; ~duration=181 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=287 violation=2
D/StrictMode( 4201): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4201): 	at android.database.sqlite.SQLiteConnection.applyBlockGuardPolicy(SQLiteConnection.java:1041)
D/StrictMode( 4201): 	at android.database.sqlite.SQLiteConnection.executeForCursorWindow(SQLiteConnection.java:842)
D/StrictMode( 4201): 	at android.database.sqlite.SQLiteSession.executeForCursorWindow(SQLiteSession.java:836)
D/StrictMode( 4201): 	at android.database.sqlite.SQLiteQuery.fillWindow(SQLiteQuery.java:62)
D/StrictMode( 4201): 	at android.database.sqlite.SQLiteCursor.fillWindow(SQLiteCursor.java:144)
D/StrictMode( 4201): 	at android.database.sqlite.SQLiteCursor.getCount(SQLiteCursor.java:133)
D/StrictMode( 4201): 	at android.database.CursorToBulkCursorAdaptor.getBulkCursorDescriptor(CursorToBulkCursorAdaptor.java:145)
D/StrictMode( 4201): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:122)
D/StrictMode( 4201): 	at android.os.Binder.execTransact(Binder.java:446)
D/StrictMode( 4201): # via Binder call with stack:
D/StrictMode( 4201): android.os.StrictMode$LogStackTrace
D/StrictMode( 4201): 	at android.os.StrictMode.readAndHandleBinderCallViolations(StrictMode.java:1717)
D/StrictMode( 4201): 	at android.os.Parcel.readExceptionCode(Parcel.java:1527)
D/StrictMode( 4201): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:134)
D/StrictMode( 4201): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:421)
D/StrictMode( 4201): 	at android.content.ContentResolver.query(ContentResolver.java:478)
D/StrictMode( 4201): 	at android.content.ContentResolver.query(ContentResolver.java:422)
D/StrictMode( 4201): 	at com.google.android.c.c.a(PG:87)
D/StrictMode( 4201): 	at com.google.android.c.c.a(PG:107)
D/StrictMode( 4201): 	at com.google.android.apps.gmm.shared.net.s.a(PG:325)
D/StrictMode( 4201): 	at com.google.android.apps.gmm.shared.net.s.a(PG:175)
D/StrictMode( 4201): 	at com.google.android.apps.gmm.map.n.o.a(PG:134)
D/StrictMode( 4201): 	at com.google.b.a.by.a(PG:125)
D/StrictMode( 4201): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 4201): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 4201): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4201): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4201): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4201): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4201): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4201): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4201): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4201): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4201): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4201): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4201): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4201): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 4201): StrictMode policy violation; ~duration=51 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4201): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4201): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 4201): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 4201): 	at java.io.File.exists(File.java:363)
D/StrictMode( 4201): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:995)
D/StrictMode( 4201): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1018)
D/StrictMode( 4201): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:960)
D/StrictMode( 4201): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 4201): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 4201): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 4201): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 4201): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 4201): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4201): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4201): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4201): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4201): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4201): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4201): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4201): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4201): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4201): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4201): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4201): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 4201): StrictMode policy violation; ~duration=50 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4201): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4201): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 4201): 	at libcore.io.IoBridge.open(IoBridge.java:442)
D/StrictMode( 4201): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 4201): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:961)
D/StrictMode( 4201): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 4201): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 4201): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 4201): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 4201): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 4201): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4201): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4201): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4201): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4201): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4201): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4201): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4201): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4201): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4201): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4201): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4201): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 4201): StrictMode policy violation; ~duration=50 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4201): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4201): 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
D/StrictMode( 4201): 	at libcore.io.IoBridge.open(IoBridge.java:445)
D/StrictMode( 4201): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 4201): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:961)
D/StrictMode( 4201): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 4201): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 4201): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 4201): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 4201): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 4201): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4201): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4201): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4201): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4201): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4201): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4201): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4201): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4201): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4201): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4201): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4201): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 4201): StrictMode policy violation; ~duration=49 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4201): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4201): 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
D/StrictMode( 4201): 	at libcore.io.IoBridge.read(IoBridge.java:472)
D/StrictMode( 4201): 	at java.io.FileInputStream.read(FileInputStream.java:177)
D/StrictMode( 4201): 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
D/StrictMode( 4201): 	at java.io.DataInputStream.read(DataInputStream.java:63)
D/StrictMode( 4201): 	at com.google.p.j.c(PG:1152)
D/StrictMode( 4201): 	at com.google.p.j.a(PG:121)
D/StrictMode( 4201): 	at com.google.t.b.a.dr.<init>(PG:24)
D/StrictMode( 4201): 	at com.google.t.b.a.ds.a(PG:61)
D/StrictMode( 4201): 	at com.google.p.e.a(PG:170)
D/StrictMode( 4201): 	at com.google.p.e.b(PG:21)
D/StrictMode( 4201): 	at com.google.android.apps.gmm.shared.c.h.a(PG:150)
D/StrictMode( 4201): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 4201): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 4201): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 4201): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4201): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4201): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4201): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4201): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4201): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4201): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4201): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4201): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4201): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4201): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4201): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
W/InputMethodManagerService(  818): Got RemoteException sending setActive(false) notification to pid 3818 uid 10265
I/Keyboard.Facilitator( 1231): onFinishInput()
W/com.google.a.a.a.b.a( 4201): Application name is not set. Call Builder#setApplicationName.
W/LocationOracleImpl( 1483): Best location was null
,I/HotwordRecognitionRnr( 1483): Starting hotword detection.
I/MicrophoneInputStream( 1483): mic_starting com.google.android.apps.gsa.speech.audio.u@31a9f9c
D/BluetoothManagerService(  818): Message: 20
D/BluetoothManagerService(  818): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1f582bf3:true
I/AudioFlinger(  356): AudioFlinger's thread 0xb4d4f000 ready to run
D/AuthorizationBluetoothService( 1136): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
I/SoundTriggerHwService::Module(  356): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/MicrophoneInputStream( 1483): mic_started com.google.android.apps.gsa.speech.audio.u@31a9f9c
I/art     ( 1319): Explicit concurrent mark sweep GC freed 5002(364KB) AllocSpace objects, 12(1408KB) LOS objects, 31% free, 35MB/51MB, paused 8.029ms total 38.219ms
D/audio_hw_primary(  356): select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
D/msm8974_platform(  356): platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
E/ACDB-LOADER(  356): Error: ACDB AudProc vol returned = -19
D/audio_hw_primary(  356): enable_snd_device: snd_device(55: voice-rec-mic)
D/audio_hw_primary(  356): enable_audio_route: apply and update mixer path: audio-record
V/MusicLeanback( 3079): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/SprintDMReceiver( 3906): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3906): simOperator:  IMSI: null
,D/SprintDMReceiver( 3906): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1774): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1774): onCreate
,D/Launcher.Workspace( 1319): 11683562 - stripEmptyScreens()
D/Launcher.Workspace( 1319): 11683562 - stripEmptyScreens()
,D/SystemUpdateService( 1774): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1774): active receiver: enabled
,I/art     (  818): Explicit concurrent mark sweep GC freed 21180(1354KB) AllocSpace objects, 4(252KB) LOS objects, 31% free, 34MB/50MB, paused 2.406ms total 296.990ms
,I/iu.Environment( 1774): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,D/ChimeraCfgMgr( 1774): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/iu.UploadsManager( 1774): num queued entries: 0
I/iu.UploadsManager( 1774): num updated entries: 0
I/iu.SyncManager( 1774): NEXT; no task
,I/Babel   ( 2804): connection state changed from CONNECTED to DISCONNECTED
,I/HotwordWorker( 1483): onReady
,I/art     ( 4197): System.exit called, status: 0
I/AndroidRuntime( 4197): VM exiting with result code 0.
,I/SystemUpdateService( 1774): showing system update notification
,I/ValidateNoPeople(  818): skipping global notification
,V/MusicLeanback( 3079): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,V/SystemUpdateService( 1774): retry (wakeup: false) in 3599943 ms
,D/SystemUpdateService( 1774): onDestroy
,D/SprintDMReceiver( 3906): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3906): simOperator:  IMSI: null
D/SprintDMReceiver( 3906): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1774): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1774): onCreate
,D/SystemUpdateService( 1774): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1774): active receiver: enabled
,I/SystemUpdateService( 1774): showing system update notification
,D/ChimeraCfgMgr( 1774): Loading module com.google.android.gms.kids from APK com.google.android.gms
,E/LocSvc_IzatApiV02(  818): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1660896531
,E/LocSvc_IzatApiV02(  818): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,I/ValidateNoPeople(  818): skipping global notification
,V/SystemUpdateService( 1774): retry (wakeup: false) in 3599980 ms
,D/SystemUpdateService( 1774): onDestroy
,D/BuaReceiver( 3491): ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,I/ActivityManager(  818): Start proc 4268:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,D/VoicemailCleanupService( 4268): Cleaning up data for package: com.test.thalitest
,E/SQLiteDatabase( 4268): Failed to open database '/data/data/com.android.providers.contacts/databases/contacts2.db'.
E/SQLiteDatabase( 4268): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4268): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4268): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4268): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4268): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4268): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4268): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4268): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4268): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4268): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4268): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4268): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4268): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4268): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 4268): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/SQLiteDatabase( 4268): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1561)
E/SQLiteDatabase( 4268): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1641)
E/SQLiteDatabase( 4268): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1492)
E/SQLiteDatabase( 4268): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4268): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 4268): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteOpenHelper( 4268): Couldn't open contacts2.db for writing (will try read-only):
E/SQLiteOpenHelper( 4268): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4268): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4268): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 4268): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 4268): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4268): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4268): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4268): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteOpenHelper( 4268): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteOpenHelper( 4268): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 4268): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteOpenHelper( 4268): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 4268): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 4268): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 4268): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/SQLiteOpenHelper( 4268): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1561)
E/SQLiteOpenHelper( 4268): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1641)
E/SQLiteOpenHelper( 4268): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1492)
E/SQLiteOpenHelper( 4268): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4268): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteOpenHelper( 4268): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ActivityManager(  818): Start proc 4289:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,E/SQLiteLog( 4268): (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
,E/SQLiteDatabase( 4268): Failed to open database '/data/data/com.android.providers.contacts/databases/contacts2.db'.
E/SQLiteDatabase( 4268): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4268): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4268): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4268): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4268): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4268): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4268): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4268): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4268): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4268): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4268): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4268): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4268): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4268): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4268): 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:181)
E/SQLiteDatabase( 4268): 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:130)
E/SQLiteDatabase( 4268): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
E/SQLiteDatabase( 4268): 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
E/SQLiteDatabase( 4268): 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
E/SQLiteDatabase( 4268): 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
E/SQLiteDatabase( 4268): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4268): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4268): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 4268): 	at android.os.HandlerThread.run(HandlerThread.java:61)
--------- beginning of crash
E/AndroidRuntime( 4268): FATAL EXCEPTION: IntentService[VoicemailCleanupService]
E/AndroidRuntime( 4268): Process: android.process.acore, PID: 4268
E/AndroidRuntime( 4268): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4268): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4268): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 4268): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 4268): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4268): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4268): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4268): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AndroidRuntime( 4268): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AndroidRuntime( 4268): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 4268): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:11,48)
E/AndroidRuntime( 4268): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 4268): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 4268): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 4268): 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:181)
E/AndroidRuntime( 4268): 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:130)
E/AndroidRuntime( 4268): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
E/AndroidRuntime( 4268): 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
E/AndroidRuntime( 4268): 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
E/AndroidRuntime( 4268): 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
E/AndroidRuntime( 4268): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4268): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4268): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 4268): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/Process ( 4268): Sending signal. PID: 4268 SIG: 9
,I/ActivityManager(  818): Start proc 4308:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,E/DropBoxManagerService(  818): Can't write: system_app_crash
E/DropBoxManagerService(  818): java.io.FileNotFoundException: /data/system/dropbox/drop103.tmp: open failed: EROFS (Read-only file system)
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
D/Atlas   (  818): Validating map...
,I/ActivityManager(  818): Process android.process.acore (pid 4268) has died
,W/ActivityManager(  818): Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
,W/ContextImpl( 4308): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2609 
,E/SQLiteLog( 1136): (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,D/AndroidRuntime( 1136): Shutting down VM
E/AndroidRuntime( 1136): FATAL EXCEPTION: main
E/AndroidRuntime( 1136): Process: com.google.process.gapps, PID: 1136
E/AndroidRuntime( 1136): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1136): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2616)
E/AndroidRuntime( 1136): 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
E/AndroidRuntime( 1136): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1380)
E/AndroidRuntime( 1136): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1136): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 1136): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
E/AndroidRuntime( 1136): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 1136): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 1136): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
E/AndroidRuntime( 1136): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
E/AndroidRuntime( 1136): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1136): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1136): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 1136): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1136): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1136): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/AndroidRuntime( 1136): 	at com.google.android.gms.gcm.bh.a(SourceFile:310)
E/AndroidRuntime( 1136): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:127)
E/AndroidRuntime( 1136): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:321)
E/AndroidRuntime( 1136): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2609)
E/AndroidRuntime( 1136): 	... 9 more
,E/DropBoxManagerService(  818): Can't write: system_app_crash
E/DropBoxManagerService(  818): java.io.FileNotFoundException: /data/system/dropbox/drop105.tmp: open failed: EROFS (Read-only file system)
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
,E/SQLiteDatabase( 4308): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4308): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4308): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4308): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4308): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4308): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4308): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4308): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4308): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4308): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4308): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4308): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4308): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4308): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4308): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4308): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
E/SQLiteDatabase( 4308): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
E/SQLiteDatabase( 4308): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4308): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4308): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 4308): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/AndroidRuntime( 4308): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4308): Process: com.android.keychain, PID: 4308
E/AndroidRuntime( 4308): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4308): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4308): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 4308): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 4308): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4308): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4308): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4308): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AndroidRuntime( 4308): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AndroidRuntime( 4308): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 4308): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AndroidRuntime( 4308): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 4308): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 4308): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 4308): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
E/AndroidRuntime( 4308): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396,)
E/AndroidRuntime( 4308): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4308): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4308): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 4308): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/DropBoxManagerService(  818): Can't write: system_app_crash
E/DropBoxManagerService(  818): java.io.FileNotFoundException: /data/system/dropbox/drop106.tmp: open failed: EROFS (Read-only file system),
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
,I/OpenGLRenderer(  818): Initialized EGL, version 1.4
,D/OpenGLRenderer(  818): Enabling debug mode 0
,W/InputMethodManagerService(  818): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@1065be59 attribute=null, token = android.os.BinderProxy@3ecdf7af
,I/OpenGLRenderer(  818): Initialized EGL, version 1.4
,I/HotwordDetector( 1483): Closing mic
,I/MicrophoneInputStream( 1483): mic_close com.google.android.apps.gsa.speech.audio.u@31a9f9c
,E/Search.SharedPreferencesProto( 1483): Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
,D/audio_hw_primary(  356): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  356): disable_snd_device: snd_device(55: voice-rec-mic)
,I/SoundTriggerHwService::Module(  356): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,I/ActivityManager(  818): Killing 3388:com.android.providers.calendar/u0a3 (adj 15): empty #17
,I/HotwordRecognitionRnr( 1483): Hotword detection finished
,I/HotwordRecognitionRnr( 1483): Stopping hotword detection.
,I/ActivityManager(  818): Killing 3409:com.google.android.gms.wearable/u0a11 (adj 15): empty #18
,E/native  ( 1231): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp,
E/native  ( 1231): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,I/ActivityManager(  818): Start proc 4339:android.process.acore/u0a5 for content provider com.android.providers.contacts/.ContactsProvider2
,E/SQLiteDatabase( 4339): Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
E/SQLiteDatabase( 4339): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4339): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4339): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4339): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4339): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4339): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4339): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4339): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4339): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4339): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4339): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4339): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4339): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4339): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 4339): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/SQLiteDatabase( 4339): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1561)
E/SQLiteDatabase( 4339): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1641)
E/SQLiteDatabase( 4339): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1492)
E/SQLiteDatabase( 4339): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4339): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 4339): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 4339): Couldn't open contacts2.db for writing (will try read-only):
E/SQLiteOpenHelper( 4339): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4339): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4339): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 4339): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 4339): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4339): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4339): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4339): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteOpenHelper( 4339): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteOpenHelper( 4339): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 4339): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteOpenHelper( 4339): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 4339): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 4339): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 4339): 	at com.android.provider,s.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/SQLiteOpenHelper( 4339): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1561)
E/SQLiteOpenHelper( 4339): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1641)
E/SQLiteOpenHelper( 4339): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1492)
E/SQLiteOpenHelper( 4339): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4339): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteOpenHelper( 4339): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteLog( 4339): (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
,E/AndroidRuntime( 4339): FATAL EXCEPTION: ContactsProviderWorker,
E/AndroidRuntime( 4339): Process: android.process.acore, PID: 4339
E/AndroidRuntime( 4339): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
,E/AndroidRuntime( 4339): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 4339): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 4339): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 4339): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 4339): 	at android.database.sqlite.SQLiteDatabase.executeSql(SQLiteDatabase.java:1676)
E/AndroidRuntime( 4339): 	at android.database.sqlite.SQLiteDatabase.execSQL(SQLiteDatabase.java:1605)
E/AndroidRuntime( 4339): 	at com.android.providers.contacts.ContactsDatabaseHelper.onOpen(ContactsDatabaseHelper.java:1068)
E/AndroidRuntime( 4339): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:266)
E/AndroidRuntime( 4339): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/AndroidRuntime( 4339): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/AndroidRuntime( 4339): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1561)
E/AndroidRuntime( 4339): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1641)
E/AndroidRuntime( 4339): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1492)
E/AndroidRuntime( 4339): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4339): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 4339): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DropBoxManagerService(  818): Can't write: system_app_crash
E/DropBoxManagerService(  818): java.io.FileNotFoundException: /data/system/dropbox/drop109.tmp: open failed: EROFS (Read-only file system)
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
,E/QMI_FW  (  818): xport_send: Sendto failed for port 4096
E/LocSvc_api_v02(  818): E/locClientSendReq:2446]: send_msg_sync error: -1
E/LocSvc_IzatApiV02(  818): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 11, ind.status = -1660896531
E/LocSvc_IzatApiV02(  818): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,I/qdhwcomposer(  259): handle_blank_event: dpy:0 panel power state: 0
```
