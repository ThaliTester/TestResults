#### Test 573480784751f5c_thali05_motorola-Nexus 6 Logs


```
--------- beginning of main
,D/Finsky  ( 3625): [385] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
V/GLSActivity( 1287): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/art     ( 1287): Explicit concurrent mark sweep GC freed 18566(1088KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 1.324ms total 40.885ms
I/GLSUser ( 1287): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1287): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1287): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1287): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1287): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 3625): [385] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
D/AndroidRuntime( 3845): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 3845): CheckJNI is OFF
D/AndroidRuntime( 3845): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  821): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/WindowManager(  821): addAppToken: AppWindowToken{30748012 token=Token{1500b39d ActivityRecord{2d14a274 u0 com.test.thalitest/.MainActivity t28}}} to stack=1 task=28 at 0
D/AndroidRuntime( 3845): Shutting down VM
I/MicrophoneInputStream( 1528): mic_close com.google.android.apps.gsa.speech.audio.u@1eec0ec2
I/HotwordDetector( 1528): Closing mic
V/WindowManager(  821): Adding window Window{2ec42b3f u0 Starting com.test.thalitest} at 2 of 7 (after Window{21bd505c u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
I/ActivityManager(  821): Start proc 3860:com.test.thalitest/u0a265 for activity com.test.thalitest/.MainActivity
D/audio_hw_primary(  358): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  358): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  358): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1528): Stopping hotword detection.
I/HotwordRecognitionRnr( 1528): Hotword detection finished
I/ActivityManager(  821): Killing 3537:com.google.android.partnersetup/u0a16 (adj 15): empty #17
E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1702352147
E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,I/ActivityManager(  821): Killing 3243:com.google.android.apps.photos/u0a71 (adj 15): empty #18,
,I/kickstart(  871): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000,
,I/kickstart(  871): STATUS: Wrote to /sys/power/wake_lock,
,E/kickstart(  871): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2
I/kickstart(  871): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2' for writing
,I/WebViewFactory( 3860): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3860): Time to load native libraries: 2 ms (timestamps 3408-3410),
I/LibraryLoader( 3860): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3860): Binding Chromium to main looper Looper (main, tid 1) {34f44a65}
,I/LibraryLoader( 3860): Expected native library version number "",actual native library version number ""
,I/chromium( 3860): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3860): Initializing chromium process, singleProcess=true
,W/art     ( 3860): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3860): ApplicationContext is null in ApplicationStatus
,W/chromium( 3860): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3860): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 3860): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3860): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/BluetoothManagerService(  821): Message: 20
D/BluetoothManagerService(  821): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1c64622f:true
,W/art     ( 3860): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3860): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3860): CordovaWebView is running on device made by: motorola
,W/art     ( 3860): Attempt to remove local handle scope entry from IRT, ignoring,
W/art     ( 3860): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3860): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,D/Atlas   ( 3860): Validating map...
,V/WindowManager(  821): Adding window Window{2b8351f u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{2ec42b3f u0 Starting com.test.thalitest})
,W/chromium( 3860): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3860): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3860): Enabling debug mode 0
,I/ActivityManager(  821): Displayed com.test.thalitest/.MainActivity: +934ms
,I/Keyboard.Facilitator( 1230): onFinishInput()
,W/BindingManager( 3860): Cannot call determinedVisibility() - never saw a connection for the pid: 3860
,D/JsMessageQueue( 3860): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3860): JniHelper::setJavaVM(0xb489d200), pthread_self() = -1576192256
,I/chromium( 3860): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41),
,I/kickstart(  871): STATUS: Received file 'm9kefs2'
I/kickstart(  871): STATUS: 950272 bytes transferred in 0.991029 seconds
I/kickstart(  871): STATUS: Successfully downloaded files from target 
I/kickstart(  871): STATUS: Wrote to /sys/power/wake_unlock
I/kickstart(  871): STATUS: Sahara protocol completed
,W/jxcore-log( 3860): Initializing JXcore engine
W/jxcore-log( 3860): JXcore engine is ready
,W/Thread-431( 3911): type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[12882]" dev="sockfs" ino=12882 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/Thread-431( 3911): type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,W/Thread-431( 3911): type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[13004]" dev="sockfs" ino=13004 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-431( 3911): type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[23339]" dev="sockfs" ino=23339 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 3860): Starting JXcore engine
,W/jxcore-log( 3860): Platform android
W/jxcore-log( 3860): 
W/jxcore-log( 3860): Process ARCH arm
W/jxcore-log( 3860): 
,I/jxcore-log( 3860): JXcore Cordova bridge is ready!
I/jxcore-log( 3860): 
W/jxcore-log( 3860): JXcore engine is started
,I/jxcore-log( 3860): Toggling radios to true
I/jxcore-log( 3860): 
,D/BluetoothAdapter( 3860): enable(): BT is already enabled..!
,D/WifiService(  821): New client listening to asynchronous messages
D/WifiService(  821): setWifiEnabled: true pid=3860, uid=10265
E/WifiService(  821): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3860): Radios toggled
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): My device name is: motorola-Nexus 6
I/jxcore-log( 3860): 
,I/wpa_supplicant( 1188): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  821): WifiStateMachine: Leaving Connected state
,E/WifiConfigStore(  821): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  354): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1287): Read error: ssl=0x9d28f800: I/O error during system call, Connection timed out
,D/ConnectivityService(  821): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  821): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
E/WifiStateMachine(  821): Start Disconnecting Watchdog 1
,E/WifiStateMachine(  821): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
V/NativeCrypto( 1287): SSL shutdown failed: ssl=0x9d28f800: I/O error during system call, Broken pipe
,D/ConnectivityService(  821): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10011
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): DefaultState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): Forcing reevaluation
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
,D/CommandListener(  354): Clearing all IP addresses on wlan0
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
,D/WifiNetworkAgent(  821): NetworkAgent: NetworkAgent channel lost
,E/WifiStateMachine(  821): CMD_AUTO_CONNECT sup state CompletedState my state DisconnectedState nid=0 roam=3
E/WifiStateMachine(  821): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=0
D/ConnectivityService(  821): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/CSLegacyTypeTracker(  821): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true,
D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 1066): CM callback handler got msg 524292
D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): OfflineState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): Disconnected - quitting
,D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  821): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/Tethering(  821): MasterInitialState.processMessage what=3
,D/Tethering(  821): MasterInitialState.processMessage what=3
,E/ConnectivityService(  821): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/ConnectivityService(  821): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
,D/NetworkChangeNotifierAutoDetect( 1528): Network connectivity changed, type is: 6
,V/MusicLeanback( 3049): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
E/WifiConfigStore(  821): Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiConfigStore(  821): will read network variables netId=0
,D/PhoneInterfaceManager( 1339): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1339): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
E/WifiStateMachine(  821): CMD_AUTO_CONNECT did save config ->  nid=0
,E/WifiConfigStore(  821): will read network variables netId=0
,D/TelephonyManager(  821): getDataEnabled: retVal=false
,I/ActivityManager(  821): Start proc 3920:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.steen.receiver.ConnectivityChangeReceiver
,E/GpsLocationProvider(  821): No APN found to select.
,D/PhoneInterfaceManager( 1339): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
,E/PhoneInterfaceManager( 1339): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
D/TelephonyManager(  821): getDataEnabled: retVal=false
,E/GpsLocationProvider(  821): No APN found to select.
,I/ActivityManager(  821): Start proc 3946:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,I/ActivityManager(  821): Killing 3557:com.android.musicfx/u0a18 (adj 15): empty #17
,D/SprintDMReceiver( 3946): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3946): simOperator:  IMSI: null
D/SprintDMReceiver( 3946): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1774): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
D/SystemUpdateService( 1774): onCreate
D/SystemUpdateService( 1774): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1774): active receiver: enabled
,I/SystemUpdateService( 1774): showing system update notification
,I/iu.Environment( 1774): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1774): num queued entries: 0
,I/iu.UploadsManager( 1774): num updated entries: 0
I/iu.SyncManager( 1774): NEXT; no task
,I/ValidateNoPeople(  821): skipping global notification,
,V/SystemUpdateService( 1774): retry (wakeup: false) in 3599973 ms
,D/ChimeraCfgMgr( 1774): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/SystemUpdateService( 1774): onDestroy
,I/Babel   ( 2797): connection state changed from CONNECTED to DISCONNECTED
,I/ActivityManager(  821): Start proc 3966:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,I/ActivityManager(  821): Killing 3586:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,I/GAv4    ( 3966): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3966):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3966):   adb logcat -s GAv4
,W/GAv4    ( 3966): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3966): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3966): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 3966): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3966): Time to load native libraries: 1 ms (timestamps 7705-7706)
,I/LibraryLoader( 3966): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3966): Binding Chromium to main looper Looper (main, tid 1) {1628a4f0}
,I/LibraryLoader( 3966): Expected native library version number "",actual native library version number ""
,I/chromium( 3966): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3966): Initializing chromium process, singleProcess=true
W/art     ( 3966): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3966): ApplicationContext is null in ApplicationStatus
,W/chromium( 3966): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3966): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3966): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3966): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,I/NSApplication( 3966): Starting up...
,W/AudioManagerAndroid( 3966): Requires BLUETOOTH permission
,I/ActivityManager(  821): Start proc 4022:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
I/ActivityManager(  821): Killing 1429:android.process.acore/u0a5 (adj 15): empty #17
,I/ActivityManager(  821): Start proc 4047:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,V/GLSActivity( 1287): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/wpa_supplicant( 1188): wlan0: Trying to associate with SSID 'NG7005g'
,I/art     (  821): Explicit concurrent mark sweep GC freed 36041(1704KB) AllocSpace objects, 4(158KB) LOS objects, 32% free, 33MB/49MB, paused 1.483ms total 51.534ms
,I/GLSUser ( 1287): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1287): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1287): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1287): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1287): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3625): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3625): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3625): [1] 5.onFinished: Scheduling replication attempt 3.
,I/ActivityManager(  821): Killing 3665:com.google.android.gms:car/u0a11 (adj 15): empty #17
,I/ActivityManager(  821): Killing 3443:com.google.android.gm/u0a78 (adj 15): empty #17
,V/MusicLeanback( 3049): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/SprintDMReceiver( 3946): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3946): simOperator:  IMSI: null
D/SprintDMReceiver( 3946): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1774): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1774): onCreate
,D/SystemUpdateService( 1774): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1774): active receiver: enabled
,I/SystemUpdateService( 1774): showing system update notification
,D/ChimeraCfgMgr( 1774): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/ValidateNoPeople(  821): skipping global notification
,V/SystemUpdateService( 1774): retry (wakeup: false) in 3599974 ms
,D/SystemUpdateService( 1774): onDestroy,
,I/wpa_supplicant( 1188): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 1188): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1188): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=0 id_str=]
,D/ConnectivityService(  821): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} }
E/WifiConfigStore(  821): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/ConnectivityService(  821): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  821): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  354): Setting iface cfg
,E/WifiStateMachine(  821): Start Dhcp Watchdog 2
,E/WifiStateMachine(  821):  WifiLinkLayerStats: ,
E/WifiStateMachine(  821):  my bss beacon rx: 427
E/WifiStateMachine(  821):  RSSI mgmt: -49
E/WifiStateMachine(  821):  BE :  rx=224 tx=157 lost=0 retries=0
E/WifiStateMachine(  821):  BK :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  821):  VI :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  821):  VO :  rx=6 tx=0 lost=0 retries=0
,E/WifiStateMachine(  821):  on_time : 17192 tx_time=217 rx_time=620 scan_time=0
,D/ConnectivityService(  821): updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60,
,E/native  (  821): do suspend false,
,E/WifiStateMachine(  821): scanCount==0 - aborting,
,I/dhcpcd  ( 4074): version 5.5.6 starting
,I/dhcpcd  ( 4074): wlan0: rebinding lease of 192.168.1.122
,I/dhcpcd  ( 4074): wlan0: acknowledged 192.168.1.122 from 192.168.1.1,
,I/dhcpcd  ( 4074): wlan0: leased 192.168.1.122 for 86400 seconds,
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
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  821): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  821): Connected
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  821): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  821): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
,D/ConnectivityService(  821): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} }
,D/ConnectivityService(  821): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/CSLegacyTypeTracker(  821): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 1066): CM callback handler got msg 524290,
,D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE,
,D/PhoneInterfaceManager( 1339): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1339): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/Tethering(  821): MasterInitialState.processMessage what=3
D/TelephonyManager(  821): getDataEnabled: retVal=false
,D/NetworkChangeNotifierAutoDetect( 1528): Network connectivity changed, type is: 2
,I/NetworkMonitor( 3049): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 3049): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,E/GpsLocationProvider(  821): No APN found to select.
,D/SprintDMReceiver( 3946): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3946): simOperator:  IMSI: null
D/SprintDMReceiver( 3946): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1774): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1774): onCreate
,D/SystemUpdateService( 1774): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1774): active receiver: enabled
,I/SystemUpdateService( 1774): showing system update notification
,I/ValidateNoPeople(  821): skipping global notification
,V/SystemUpdateService( 1774): retry (wakeup: false) in 3599987 ms
,I/iu.Environment( 1774): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1774): num queued entries: 0
I/iu.UploadsManager( 1774): num updated entries: 0
I/iu.SyncManager( 1774): NEXT; no task
,D/SystemUpdateService( 1774): onDestroy
,D/ChimeraCfgMgr( 1774): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 1774): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  821): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 28 Jan 2016 12:52:48 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1453985568769], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1453985568745]}
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  821): Validated
D/ConnectivityService(  821): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/ConnectivityService(  821): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  821): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  821): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  821): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1066): CM callback handler got msg 524290
,I/GLSUser ( 1287): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1287): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1287): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1287): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1287): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/Herrevad( 1774): NQAS connected
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
,I/Babel   ( 2797): connection state changed from DISCONNECTED to CONNECTED
,D/GCM     ( 1287): Connected
,D/GCM     ( 1287): Message class com.google.f.a.a.p
,I/jxcore-log( 3860): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 3860): 
,D/ConnectivityService(  821): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/jxcore-log( 3860): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js,
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 3860): 
,E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=16.25 rxSuccessRate=18.25 targetRoamBSSID=any RSSI=-49
E/WifiStateMachine(  821): WifiStateMachine L2Connected CMD_START_SCAN source -2 7, 9 -> obsolete
,D/HeadsetStateMachine( 2149): Disconnected process message: 10, size: 0
,E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=9.12 rxSuccessRate=10.12 targetRoamBSSID=any RSSI=-49
E/WifiStateMachine(  821): WifiStateMachine L2Connected CMD_START_SCAN source -2 8, 9 -> obsolete
,I/jxcore-log( 3860): Test app app.js loaded,
I/jxcore-log( 3860): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 3860): BLE advertisement is supported
I/jxcore-log( 3860): 
,I/chromium( 3860): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/HeadsetStateMachine( 2149): Disconnected process message: 10, size: 0
,V/GLSActivity( 1287): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1287): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure,
I/GLSUser ( 1287): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1287): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1287): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1287): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3625): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3625): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3625): [1] 5.onFinished: Scheduling replication attempt 4.
,E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=1.32 rxSuccessRate=2.29 targetRoamBSSID=any RSSI=-49
,V/GLSActivity( 1287): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1287): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1287): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1287): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1287): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1287): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/Finsky  ( 3625): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3625): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3625): [1] 5.onFinished: Scheduling replication attempt 5.
,E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.38 rxSuccessRate=2.38 targetRoamBSSID=any RSSI=-49
,E/WifiStateMachine(  821): WifiStateMachine starting scan for "NG7005g"WPA_PSK with 2412,5220
,I/PowerManagerService(  821): Going to sleep due to screen timeout (uid 1000)...
,I/Adreno  (  821): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/PermissionCache(  260): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (455 us)
,I/DisplayManagerService(  821): Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,V/ActivityManager(  821): Display changed displayId=0,
D/SurfaceFlinger(  260): Set power mode=0, type=0 flinger=0xb6482000
,D/qdhwcomposer(  260): hwc_setPowerMode: Setting mode 0 on display: 0
,I/qdhwcomposer(  260): handle_blank_event: dpy:0 panel power state: 0,
D/qdhwcomposer(  260): hwc_setPowerMode: Done setting mode 0 on display 0
D/SurfaceControl(  821): Excessive delay in setPowerMode(): 283ms
,I/DreamManagerService(  821): Entering dreamland.
,I/PowerManagerService(  821): Dozing...
,I/DreamController(  821): Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,D/audio_hw_primary(  358): adev_set_parameters: enter: screen_state=on
,D/mot_vr_audio_hw(  358): adev_set_parameters: screen_state=on
,E/WifiStateMachine(  821): cancelDelayedScan -> 12
,E/native  (  821): do suspend false
,I/BooksSync( 3771): Starting books sync for 61035162, extras: ade
,I/Keyboard.Facilitator( 1230): onFinishInput()
,I/BooksConfig( 3771): GmsCore Version = 7.8.99 (2134222-430)
,E/WifiStateMachine(  821): cancelDelayedScan -> 14
,E/native  (  821): do suspend true
,I/GLSUser ( 1287): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1287): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1287): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1287): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1287): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/audio_hw_primary(  358): adev_set_parameters: enter: screen_state=off
D/mot_vr_audio_hw(  358): adev_set_parameters: screen_state=off
,I/GLSUser ( 1287): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1287): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1287): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1287): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1287): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3771): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3771): Soft error
E/BooksSync( 3771): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3771): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3771): Sync error
E/BooksSync( 3771): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3771): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3771): Finished books sync
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 163581, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-49
E/WifiStateMachine(  821): WifiStateMachine L2Connected CMD_START_SCAN source -2 13, 14 -> obsolete
,E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-49
E/WifiStateMachine(  821): WifiStateMachine L2Connected CMD_START_SCAN source -2 11, 14 -> obsolete
,V/GLSActivity( 1287): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  821): Explicit concurrent mark sweep GC freed 65834(3MB) AllocSpace objects, 16(350KB) LOS objects, 31% free, 34MB/50MB, paused 1.570ms total 86.853ms
,V/GLSActivity( 1287): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1287): Vacuum at: now=1453985630935 tag=VacuumService
,V/GoogleAuthProtoRequest( 3920): [425] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1287): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1287): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1287): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1287): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1287): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1287): Explicit concurrent mark sweep GC freed 36398(2MB) AllocSpace objects, 6(661KB) LOS objects, 37% free, 26MB/42MB, paused 849us total 24.923ms
,D/Finsky  ( 3625): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3625): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3625): [1] 5.onFinished: Giving up after 6 failures.
,I/GLSUser ( 1287): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1287): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1287): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1287): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1287): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3920): [425] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3920): [425] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3920): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3920): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3920): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3920): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3920): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3920): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3920): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3920): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3920): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3920): 	at com.a.a.k.run(SourceFile:110)
,I/GoogleURLConnFactory( 1287): Using platform SSLCertificateSocketFactory
,I/GLSUser ( 1287): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1287): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1287): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1287): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1287): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1287): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1287): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1287): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1287): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1287): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1287): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1287): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1287): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1287): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1287): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1287): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1287): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1287): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1287): No account for auth token provided
,W/Uploader( 1287): No account for auth token provided,
,I/GLSUser ( 1287): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1287): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1287): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1287): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1287): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1287): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1287): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1287): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1287): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1287): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1287): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1287): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1287): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1287): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1287): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1287): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1287): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1287): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1287): No account for auth token provided
,W/Uploader( 1287): No account for auth token provided
,W/Uploader( 1287): No account for auth token provided
,W/Uploader( 1287): No account for auth token provided
,W/Uploader( 1287): No account for auth token provided
,I/GLSUser ( 1287): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1287): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1287): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1287): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1287): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1287): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1287): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1287): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1287): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1287): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1287): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1287): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1287): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1287): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1287): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1287): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1287): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1287): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1287): No account for auth token provided
,W/Uploader( 1287): No account for auth token provided
,W/Uploader( 1287): No account for auth token provided
,W/Uploader( 1287): No account for auth token provided
,W/Uploader( 1287): No account for auth token provided
,W/Uploader( 1287):  no longer exists, so no auth token.,
,D/HeadsetStateMachine( 2149): Disconnected process message: 10, size: 0
,I/GLSUser ( 1287): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1287): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1287): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1287): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1287): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1287): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1287): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1287): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1287): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1287): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1287): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1287): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1287): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1287): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1287): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1287): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1287): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1287): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,D/HeadsetStateMachine( 2149): Disconnected process message: 10, size: 0
,V/KeepSync( 3788): Connecting to GoogleApiClient
,I/GLSUser ( 1287): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1287): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1287): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1287): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/GLSUser ( 1287): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1287): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1287): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1287): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1287): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,V/GLSActivity( 1287): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/ClientConnectionOperation( 1774): Handling authorization failure,
E/ClientConnectionOperation( 1774): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249),
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1774): ,	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
,E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1774): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112),
E/ClientConnectionOperation( 1774): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
,E/ClientConnectionOperation( 1774): 	at java.lang.Thread.run(Thread.java:818)
,E/ClientConnectionOperation( 1774): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1774): ,	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.auth.p.a(SourceFile:365)
,E/ClientConnectionOperation( 1774): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1774): ,	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1774): 	... 7 more,
E/HttpOperation( 3686): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3686): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3686): 	at jdm.a(PG:82)
E/HttpOperation( 3686): 	at jcs.o(PG:406)
E/HttpOperation( 3686): 	at jcn.a(PG:1379)
E/HttpOperation( 3686): 	at jcs.i(PG:143)
E/HttpOperation( 3686): 	at blb.a(PG:3937)
E/HttpOperation( 3686): 	at czp.a(PG:18188)
E/HttpOperation( 3686): 	at czp.a(PG:9081)
E/HttpOperation( 3686): 	at czq.run(PG:1686)
E/HttpOperation( 3686): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3686): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3686): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3686): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3686): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3686): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3686): 	at jdj.a(PG:4091)
E/HttpOperation( 3686): 	at jdj.a(PG:1125)
E/HttpOperation( 3686): 	at jdm.a(PG:77)
E/HttpOperation( 3686): 	... 12 more
E/HttpOperation( 3686): Caused by: faj: BadAuthentication
E/HttpOperation( 3686): 	at fal.a(PG:38)
E/HttpOperation( 3686): 	at jdj.a(PG:4089)
E/HttpOperation( 3686): 	... 14 more
,V/KeepSync( 3788): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3788): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3788): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3788): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1287): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native,
I/GLSUser ( 1287): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1287): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1287): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1287): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3686): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3686): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3686): 	at jdm.a(PG:82)
E/HttpOperation( 3686): 	at jcs.o(PG:406)
E/HttpOperation( 3686): 	at jcn.a(PG:1379)
E/HttpOperation( 3686): 	at jcs.i(PG:143)
E/HttpOperation( 3686): 	at hec.a(PG:42)
E/HttpOperation( 3686): 	at hee.a(PG:102)
E/HttpOperation( 3686): 	at czr.a(PG:65)
E/HttpOperation( 3686): 	at kka.a(PG:108)
E/HttpOperation( 3686): 	at czp.a(PG:19176)
E/HttpOperation( 3686): 	at czp.a(PG:9081)
E/HttpOperation( 3686): 	at czq.run(PG:1686)
E/HttpOperation( 3686): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3686): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3686): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3686): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3686): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3686): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3686): 	at jdj.a(PG:4091)
E/HttpOperation( 3686): 	at jdj.a(PG:1125)
E/HttpOperation( 3686): 	at jdm.a(PG:77)
E/HttpOperation( 3686): 	... 15 more
E/HttpOperation( 3686): Caused by: faj: BadAuthentication
E/HttpOperation( 3686): 	at fal.a(PG:38)
E/HttpOperation( 3686): 	at jdj.a(PG:4089)
E/HttpOperation( 3686): 	... 17 more
,E/ExperimentLoader( 3686): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3686): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3686): 	at jdm.a(PG:82)
E/ExperimentLoader( 3686): 	at jcs.o(PG:406)
E/ExperimentLoader( 3686): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3686): 	at jcs.i(PG:143)
E/ExperimentLoader( 3686): 	at hec.a(PG:42)
E/ExperimentLoader( 3686): 	at hee.a(PG:102)
E/ExperimentLoader( 3686): 	at czr.a(PG:65)
E/ExperimentLoader( 3686): 	at kka.a(PG:108)
E/ExperimentLoader( 3686): 	at czp.a(PG:19176)
E/ExperimentLoader( 3686): 	at czp.a(PG:9081)
E/ExperimentLoader( 3686): 	at czq.run(PG:1686)
E/ExperimentLoader( 3686): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3686): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3686): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3686): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3686): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3686): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3686): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3686): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3686): 	at jdm.a(PG:77)
E/ExperimentLoader( 3686): 	... 15 more
E/ExperimentLoader( 3686): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3686): 	at fal.a(PG:38)
E/ExperimentLoader( 3686): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3686): 	... 17 more
,I/GLSUser ( 1287): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1287): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1287): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1287): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1287): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 168335, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,E/KeepSync( 3788): IOException
E/KeepSync( 3788): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3788): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3788): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3788): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3788): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3788): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3788): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3788): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3788): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3788): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3788): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3788): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3788): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3788): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3788): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3788): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3788): 	... 10 more
W/KeepSync( 3788): Sync result 2
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 168174, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,V/GoogleAuthProtoRequest( 3920): [427] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1287): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1287): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1287): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1287): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1287): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3920): [427] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3920): [427] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3920): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3920): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3920): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3920): 	,at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3920): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3920): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3920): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3920): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3920): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3920): 	at com.a.a.k.run(SourceFile:110)
,I/Keyboard.Facilitator.LanguageModelFlusher( 1230): run()
I/Keyboard.Facilitator( 1230): flushDynamicLanguageModels()
,I/ConfigService( 1287): onCreate
,I/BooksSync( 3771): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3771): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1287): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1287): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1287): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1287): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1287): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  821): Explicit concurrent mark sweep GC freed 33172(1477KB) AllocSpace objects, 4(252KB) LOS objects, 31% free, 34MB/50MB, paused 2.380ms total 118.799ms
,I/GLSUser ( 1287): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1287): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1287): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1287): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1287): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3771): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3771): Soft error
E/BooksSync( 3771): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3771): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3771): Sync error
E/BooksSync( 3771): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3771): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3771): Finished books sync
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 194038, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/ConfigService( 1287): onDestroy
,D/HeadsetStateMachine( 2149): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2149): Disconnected process message: 10, size: 0
,V/KeepSync( 3788): Connecting to GoogleApiClient
,I/GLSUser ( 1287): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1287): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1287): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1287): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1287): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1287): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1287): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1287): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1287): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1287): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3686): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3686): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3686): 	at jdm.a(PG:82)
E/HttpOperation( 3686): 	at jcs.o(PG:406)
E/HttpOperation( 3686): 	at jcn.a(PG:1379)
E/HttpOperation( 3686): 	at jcs.i(PG:143)
E/HttpOperation( 3686): 	at blb.a(PG:3937)
E/HttpOperation( 3686): 	at czp.a(PG:18188)
E/HttpOperation( 3686): 	at czp.a(PG:9081)
E/HttpOperation( 3686): 	at czq.run(PG:1686)
E/HttpOperation( 3686): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3686): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3686): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3686): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3686): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3686): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3686): 	at jdj.a(PG:4091)
E/HttpOperation( 3686): 	at jdj.a(PG:1125)
E/HttpOperation( 3686): 	at jdm.a(PG:77)
E/HttpOperation( 3686): 	... 12 more
E/HttpOperation( 3686): Caused by: faj: BadAuthentication
E/HttpOperation( 3686): 	at fal.a(PG:38)
E/HttpOperation( 3686): 	at jdj.a(PG:4089)
E/HttpOperation( 3686): 	... 14 more
,E/ClientConnectionOperation( 1774): Handling authorization failure
E/ClientConnectionOperation( 1774): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1774): ,	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1774): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1774): 	,at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
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
,V/KeepSync( 3788): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3788): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3788): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3788): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1287): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1287): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1287): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1287): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1287): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3686): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3686): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3686): 	at jdm.a(PG:82)
E/HttpOperation( 3686): 	at jcs.o(PG:406)
E/HttpOperation( 3686): 	at jcn.a(PG:1379)
E/HttpOperation( 3686): 	at jcs.i(PG:143)
E/HttpOperation( 3686): 	at hec.a(PG:42)
E/HttpOperation( 3686): 	at hee.a(PG:102)
,E/HttpOperation( 3686): 	at czr.a(PG:65)
E/HttpOperation( 3686): 	at kka.a(PG:108)
E/HttpOperation( 3686): 	at czp.a(PG:19176)
E/HttpOperation( 3686): 	at czp.a(PG:9081)
E/HttpOperation( 3686): 	at czq.run(PG:1686)
E/HttpOperation( 3686): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3686): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3686): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3686): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3686): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3686): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3686): 	at jdj.a(PG:4091)
E/HttpOperation( 3686): 	at jdj.a(PG:1125)
E/HttpOperation( 3686): 	at jdm.a(PG:77)
E/HttpOperation( 3686): 	... 15 more
E/HttpOperation( 3686): Caused by: faj: BadAuthentication
E/HttpOperation( 3686): 	at fal.a(PG:38)
E/HttpOperation( 3686): 	at jdj.a(PG:4089)
E/HttpOperation( 3686): 	... 17 more
,E/ExperimentLoader( 3686): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3686): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3686): 	at jdm.a(PG:82)
E/ExperimentLoader( 3686): 	at jcs.o(PG:406)
E/ExperimentLoader( 3686): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3686): 	at jcs.i(PG:143)
E/ExperimentLoader( 3686): 	at hec.a(PG:42)
E/ExperimentLoader( 3686): 	at hee.a(PG:102)
E/ExperimentLoader( 3686): 	at czr.a(PG:65)
E/ExperimentLoader( 3686): 	at kka.a(PG:108)
E/ExperimentLoader( 3686): 	at czp.a(PG:19176)
E/ExperimentLoader( 3686): 	at czp.a(PG:9081)
E/ExperimentLoader( 3686): 	at czq.run(PG:1686)
E/ExperimentLoader( 3686): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3686): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3686): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3686): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3686): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3686): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3686): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3686): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3686): 	at jdm.a(PG:77)
E/ExperimentLoader( 3686): 	... 15 more
E/ExperimentLoader( 3686): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3686): 	at fal.a(PG:38)
E/ExperimentLoader( 3686): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3686): 	... 17 more
,I/GLSUser ( 1287): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1287): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1287): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1287): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1287): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3788): IOException
E/KeepSync( 3788): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3788): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3788): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3788): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3788): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3788): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3788): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3788): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3788): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3788): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3788): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3788): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3788): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3788): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3788): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3788): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3788): 	... 10 more
,W/KeepSync( 3788): Sync result 2
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 226835, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 226403, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2149): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2149): Disconnected process message: 10, size: 0
,V/GoogleAuthProtoRequest( 3920): [428] a.<init>: mAccountName set to: thalitester@gmail.com
,I/art     ( 1287): Explicit concurrent mark sweep GC freed 70805(4MB) AllocSpace objects, 8(738KB) LOS objects, 36% free, 28MB/44MB, paused 1.801ms total 47.531ms
,I/GLSUser ( 1287): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1287): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1287): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1287): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1287): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3920): [428] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3920): [428] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3920): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3920): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3920): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3920): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3920): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3920): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3920): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3920): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3920): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3920): 	at com.a.a.k.run(SourceFile:110)
,I/BooksSync( 3771): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3771): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1287): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1287): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1287): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1287): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1287): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1287): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1287): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1287): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1287): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1287): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3771): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3771): Soft error
E/BooksSync( 3771): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3771): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3771): Sync error
E/BooksSync( 3771): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3771): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 3771): Finished books sync
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 284372, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/jxcore-log( 3860): TAP version 13
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): # setup
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): # multiplex can send data
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): # teardown
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): ok 1 String should be length:200
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): # setup
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): # enqueue and run in order
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): # teardown
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): ok 2 firstPromise setTimeout
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): ok 3 firstPromise result
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): ok 4 firstPromise testValue
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): ok 5 secondPromise setTimeout
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): ok 6 secondPromise result
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): ok 7 secondPromise testValue
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): ok 8 thirdPromise in promise
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): ok 9 thirdPromise result
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): ok 10 thirdPromise testValue
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): # setup
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): # basic
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): # teardown
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): ok 11 sane
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): # setup
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): # another
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): # teardown
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): ok 12 sane
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): # setup
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): # successfully create a new pkcs12 file and return hash value
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): # teardown
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): ok 13 should be equal
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): ok 14 null
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): ok 15 (unnamed assert)
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): ok 16 should be equal
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): ok 17 should not throw
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): # setup
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): # successfully read a previous pkcs12 file and return hash value
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): # teardown
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): ok 18 (unnamed assert)
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): ok 19 (unnamed assert)
I/jxcore-log( 3860): ,
I/jxcore-log( 3860): ok 20 should not throw
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): ok 21 should be equal
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): ok 22 should be equal
I/jxcore-log( 3860): 
I/jxcore-log( 3860): # setup
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): # failed to extract public key because of corrupt pkcs12 file
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): # teardown
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): ok 23 should be equal
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): # setup
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): # failed to get mobile documents path
I/jxcore-log( 3860): ,
,I/jxcore-log( 3860): # teardown
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): ok 24 should be equal
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): # setup
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): # #init should register the peerAvailabilityChanged event
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): # teardown
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): ok 25 should be equal
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): ok 26 should be equal
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): ok 27 should be equal
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): # setup
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): # #init should register the networkChanged event
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): # teardown
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): ok 28 should be equal
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): # setup
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): # #startBroadcasting should throw on null device name
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): # teardown
I/jxcore-log( 3860): ,
,I/jxcore-log( 3860): ok 29 should throw
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): # setup
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): # #startBroadcasting should throw on empty string device name
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): # teardown
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): ok 30 should throw
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): # setup
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): # #startBroadcasting should throw on non-number port
I/jxcore-log( 3860): ,
,I/jxcore-log( 3860): # teardown
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): ok 31 should throw
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): # setup
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): # #startBroadcasting should throw on NaN port
I/jxcore-log( 3860): ,
,I/jxcore-log( 3860): # teardown
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): ok 32 should throw
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): # setup
I/jxcore-log( 3860): ,
,I/jxcore-log( 3860): # #startBroadcasting should throw on negative port
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): # teardown
I/jxcore-log( 3860): ,
,I/jxcore-log( 3860): ok 33 should throw
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): # setup
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): # #startBroadcasting should throw on too large port
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): # teardown
I/jxcore-log( 3860): ,
,I/jxcore-log( 3860): ok 34 should throw
I/jxcore-log( 3860): ,
,I/jxcore-log( 3860): # setup
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): # #startBroadcasting should call Mobile("StartBroadcasting") without an error
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): # teardown
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): ok 35 should be equal
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): ok 36 should be equal
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): ok 37 should be equal
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): # setup
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): # #startBroadcasting should call Mobile("StartBroadcasting") and handle an error
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): # teardown
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): ok 38 should be equal
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): ok 39 should be equal
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): ok 40 should be equal
I/jxcore-log( 3860): 
I/jxcore-log( 3860): # setup
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): # #stopBroadcasting should call Mobile("StopBroadcasting") without an error
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): # teardown
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): ok 41 should be equal
I/jxcore-log( 3860): 
I/jxcore-log( 3860): ok 42 should be equal
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): # setup
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): # #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): # teardown
I/jxcore-log( 3860): ,
,I/jxcore-log( 3860): ok 43 should be equal
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): ok 44 should be equal
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): # setup
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): # #connect should call Mobile("Connect") with a port and without an error
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): # teardown
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): ok 45 should be equal
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): ok 46 should be equal
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): ok 47 should be equal
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): # setup
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): # #connect should call Mobile("Connect") and handle an error
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): # teardown
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): ok 48 should be equal
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): ok 49 should be equal
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): # setup
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): # should call Mobile("Disconnect") without an error
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): # teardown
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): ok 50 should be equal
I/jxcore-log( 3860): ,
I/jxcore-log( 3860): ok 51 should be equal
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): # setup
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): # should call Mobile("Disconnect") and handle an error
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): # teardown
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): ok 52 should be equal
I/jxcore-log( 3860): 
I/jxcore-log( 3860): ok 53 should be equal
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): # setup
I/jxcore-log( 3860): 
,I/jxcore-log( 3860): # ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
I/jxcore-log( 3860): ,
,I/jxcore-log( 3860): # teardown
I/jxcore-log( 3860): ,
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): setDiscoveryMode: Mode set to BLE_AND_WIFI
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3860): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453985772035.3860
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3860): bind: Binding a new listener
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3860): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3860): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453985772035.3860","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3860): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3860): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3860): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3860): getBluetoothService() called with no BluetoothManagerCallback,
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3860): setState: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3860): start: OK
I/io.jxcore.node.ConnectionHelper( 3860): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 3860): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3860): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453985772035.3860
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3860): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3860): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3860): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3860): createAdvertiseData: From: 1453985772035.3860 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3860): F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3860): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3860): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService( 2149): registerClient() - UUID=a7ee7a1c-97c7-4c05-996c-12c72a766b37
,D/BtGatt.GattService( 2149): onClientRegistered() - UUID=a7ee7a1c-97c7-4c05-996c-12c72a766b37, clientIf=5
D/BluetoothLeAdvertiser( 3860): onClientRegistered() - status=0 clientIf=5
,D/BtGatt.AdvertiseManager( 2149): message : 0
,D/BtGatt.AdvertiseManager( 2149): starting multi advertising,
,D/BtGatt.GattService( 2149): onAdvertiseInstanceEnabled() - clientIf=5, status=0,
,D/BtGatt.GattService( 2149): onAdvertiseDataSet() - clientIf=5, status=0,
,D/BtGatt.GattService( 2149): registerClient() - UUID=ffb7722f-991a-47d4-9663-8b0521fcdc0b
,D/BtGatt.GattService( 2149): onClientRegistered() - UUID=ffb7722f-991a-47d4-9663-8b0521fcdc0b, clientIf=6
D/BluetoothLeScanner( 3860): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.GattService( 2149): start scan with filters
,D/BtGatt.ScanManager( 2149): handling starting scan
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): startBlePeerDiscovery: OK
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
D/BluetoothAdapterService( 2149): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29cca33a
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3860): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453985772035.3860","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3860): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453985772035.3860","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3860): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1453985772035.3860","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
D/BtGatt.GattService( 2149): onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
D/BtGatt.ScanManager( 2149): callback done for clientIf - 6 status - 0
,D/BtGatt.GattService( 2149): onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,D/BtGatt.ScanManager( 2149): callback done for clientIf - 6 status - 0
D/BtGatt.ScanManager( 2149): configureRegularScanParams() - queue=1
,D/BtGatt.ScanManager( 2149): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453985772035.3860
I/io.jxcore.node.ConnectionHelper( 3860): start: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): startBlePeerDiscovery: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3860): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3860): onIsAdvertiserStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3860): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 3860): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/jxcore-log( 3860): ok 54 Should be able to call startBroadcasting without error
I/jxcore-log( 3860): 
,I/io.jxcore.node.ConnectionHelper( 3860): stop
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3860): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3860): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3860): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3860): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3860): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3860): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3860): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3860): setState: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper( 3860): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): stop: Stopping peer discovery...
D/BtGatt.AdvertiseManager( 2149): message : 1
D/BtGatt.AdvertiseManager( 2149): stop advertise for client 5
,D/BtGatt.GattService( 2149): onAdvertiseInstanceDisabled() - clientIf=5, status=0
D/BtGatt.GattService( 2149): Client app is not null!
,D/BtGatt.GattService( 2149): unregisterClient() - clientIf=5
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3860): onIsAdvertiserStartedChanged: false
,D/BtGatt.GattService( 2149): stopScan() - queue size =1
,D/BtGatt.GattService( 2149): unregisterClient() - clientIf=6
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3860): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3860): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): stopBlePeerDiscovery: Stopped
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3860): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3860): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3860): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3860): onDiscoveryManagerStateChanged: NOT_STARTED
D/BtGatt.GattService( 2149): onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
D/BtGatt.ScanManager( 2149): callback done for clientIf - 6 status - 0
I/jxcore-log( 3860): ok 55 Should be able to call stopBroadcasting without error
I/jxcore-log( 3860): 
D/BtGatt.ScanManager( 2149): stop scan
,D/BtGatt.ScanManager( 2149): configureRegularScanParams() - queue=0
,D/BtGatt.ScanManager( 2149): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager( 2149): configureRegularScanParams() - queue emtpy, scan stopped
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3860): Local services cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/wpa_supplicant( 1188): P2P-FIND-STOPPED 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3860): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453985772220.3860
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3860): bind: Binding a new listener
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0,
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3860): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3860): Service requests cleared successfully
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0,
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3860): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453985772220.3860","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3860): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3860): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3860): startListeningForIncomingConnections: Starting...,
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
W/BluetoothAdapter( 3860): getBluetoothService() called with no BluetoothManagerCallback,
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3860): setState: RUNNING,
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3860): start: OK
I/io.jxcore.node.ConnectionHelper( 3860): start: Using peer discovery mode: BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 3860): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3860): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453985772220.3860
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3860): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3860): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3860): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3860): createAdvertiseData: From: 1453985772220.3860 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3860): F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3860): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false],
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3860): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService( 2149): registerClient() - UUID=178f8f39-ef2e-4c62-b282-2e0937ac67b5
,D/BtGatt.GattService( 2149): onClientRegistered() - UUID=178f8f39-ef2e-4c62-b282-2e0937ac67b5, clientIf=5
D/BluetoothLeAdvertiser( 3860): onClientRegistered() - status=0 clientIf=5
,D/BtGatt.AdvertiseManager( 2149): message : 0
,D/BtGatt.AdvertiseManager( 2149): starting multi advertising
,D/BtGatt.GattService( 2149): onAdvertiseInstanceEnabled() - clientIf=5, status=0
,D/BtGatt.GattService( 2149): onAdvertiseDataSet() - clientIf=5, status=0
,D/BtGatt.GattService( 2149): registerClient() - UUID=e2a1ecfe-4b32-4b3c-826c-02be47c88dbd
D/BtGatt.GattService( 2149): onClientRegistered() - UUID=e2a1ecfe-4b32-4b3c-826c-02be47c88dbd, clientIf=6
D/BluetoothLeScanner( 3860): onClientRegistered() - status=0 clientIf=6,
D/BtGatt.GattService( 2149): start scan with filters
D/BtGatt.ScanManager( 2149): handling starting scan
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): startBlePeerDiscovery: OK
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0,
D/BtGatt.GattService( 2149): onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
D/BtGatt.ScanManager( 2149): callback done for clientIf - 6 status - 0
,D/BtGatt.GattService( 2149): onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,D/BtGatt.ScanManager( 2149): callback done for clientIf - 6 status - 0
D/BtGatt.ScanManager( 2149): configureRegularScanParams() - queue=1
D/BtGatt.ScanManager( 2149): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3860): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453985772220.3860","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3860): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453985772220.3860","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3860): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1453985772220.3860","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): startWifiPeerDiscovery: Wi-Fi Direct OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): start: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): setState: RUNNING_BLE_AND_WIFI
I/wpa_supplicant( 1188): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
I/io.jxcore.node.ConnectionHelper( 3860): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453985772220.3860
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): startBlePeerDiscovery: OK
I/jxcore-log( 3860): ok 56 Should be able to call startBroadcasting without error
I/jxcore-log( 3860): 
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): startWifiPeerDiscovery: Wi-Fi Direct OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3860): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3860): onIsAdvertiserStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3860): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 3860): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 3860): stop
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3860): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3860): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3860): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3860): shutdown
I/wpa_supplicant( 1188): P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3860): Exiting thread,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3860): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3860): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3860): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3860): onConnectionManagerStateChanged: NOT_STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): setState: RESTARTING
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): stop: Stopping peer discovery...
D/BtGatt.AdvertiseManager( 2149): message : 1
D/BtGatt.AdvertiseManager( 2149): stop advertise for client 5
,D/BtGatt.GattService( 2149): onAdvertiseInstanceDisabled() - clientIf=5, status=0
D/BtGatt.GattService( 2149): Client app is not null!
D/BtGatt.GattService( 2149): unregisterClient() - clientIf=5
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3860): onIsAdvertiserStartedChanged: false
,D/BtGatt.GattService( 2149): stopScan() - queue size =1
,D/BtGatt.GattService( 2149): unregisterClient() - clientIf=6
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3860): onIsScannerStartedChanged: false
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3860): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): onIsBlePeerDiscoveryStartedChanged: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3860): stop: Stopping services
D/BtGatt.GattService( 2149): onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
D/BtGatt.ScanManager( 2149): callback done for clientIf - 6 status - 0
D/BtGatt.ScanManager( 2149): stop scan
D/BtGatt.ScanManager( 2149): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager( 2149): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager( 2149): configureRegularScanParams() - queue emtpy, scan stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3860): Local services cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): onIsWifiPeerDiscoveryStartedChanged: false
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3860): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3860): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3860): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 3860): ok 57 Should be able to call stopBroadcasting without error
I/jxcore-log( 3860): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): setDiscoveryMode: Mode set to BLE
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3860): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): setDiscoveryMode: Mode set to BLE_AND_WIFI
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3860): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453985772316.3860
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3860): bind: Binding a new listener
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3860): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3860): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453985772316.3860","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3860): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3860): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3860): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
W/BluetoothAdapter( 3860): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3860): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3860): start: OK
I/io.jxcore.node.ConnectionHelper( 3860): start: Using peer discovery mode: BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 3860): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453985772316.3860
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3860): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3860): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3860): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3860): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3860): createAdvertiseData: From: 1453985772316.3860 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3860): F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3860): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3860): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService( 2149): registerClient() - UUID=491cf099-4f3b-4306-80f7-e26d06bd6e61
,D/BtGatt.GattService( 2149): onClientRegistered() - UUID=491cf099-4f3b-4306-80f7-e26d06bd6e61, clientIf=5
D/BluetoothLeAdvertiser( 3860): onClientRegistered() - status=0 clientIf=5
,D/BtGatt.AdvertiseManager( 2149): message : 0
,D/BtGatt.AdvertiseManager( 2149): starting multi advertising
,D/BtGatt.GattService( 2149): onAdvertiseInstanceEnabled() - clientIf=5, status=0,
,D/BtGatt.GattService( 2149): onAdvertiseDataSet() - clientIf=5, status=0
,D/BtGatt.GattService( 2149): registerClient() - UUID=f2556728-8621-4144-889d-aed8c7dc71f3
,D/BtGatt.GattService( 2149): onClientRegistered() - UUID=f2556728-8621-4144-889d-aed8c7dc71f3, clientIf=6
D/BluetoothLeScanner( 3860): onClientRegistered() - status=0 clientIf=6
D/BtGatt.GattService( 2149): start scan with filters
,D/BtGatt.ScanManager( 2149): handling starting scan
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): startBlePeerDiscovery: OK
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/BtGatt.GattService( 2149): onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
D/BtGatt.ScanManager( 2149): callback done for clientIf - 6 status - 0,
D/BtGatt.GattService( 2149): onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,D/BtGatt.ScanManager( 2149): callback done for clientIf - 6 status - 0
D/BtGatt.ScanManager( 2149): configureRegularScanParams() - queue=1
D/BtGatt.ScanManager( 2149): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3860): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453985772316.3860","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3860): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453985772316.3860","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3860): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1453985772316.3860","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): setState: INITIALIZED,
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): start: OK
I/wpa_supplicant( 1188): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): setState: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 3860): start: OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453985772316.3860
I/jxcore-log( 3860): ok 58 Should be able to call startBroadcasting without error
I/jxcore-log( 3860): 
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): startBlePeerDiscovery: OK
I/io.jxcore.node.ConnectionHelper( 3860): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3860): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3860): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3860): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3860): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3860): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3860): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3860): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3860): onIsAdvertiserStartedChanged: true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): setState: RESTARTING
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3860): release: 1 listener(s) left
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3860): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3860): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): stop: Stopping peer discovery...
I/io.jxcore.node.ConnectionHelper( 3860): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 3860): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): setState: STARTED
I/wpa_supplicant( 1188): P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): setState: RESTARTING
D/BtGatt.AdvertiseManager( 2149): message : 1
D/BtGatt.AdvertiseManager( 2149): stop advertise for client 5
D/BtGatt.GattService( 2149): onAdvertiseInstanceDisabled() - clientIf=5, status=0
D/BtGatt.GattService( 2149): Client app is not null!
D/BtGatt.GattService( 2149): unregisterClient() - clientIf=5
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3860): onIsAdvertiserStartedChanged: false
D/BtGatt.GattService( 2149): stopScan() - queue size =1
D/BtGatt.GattService( 2149): unregisterClient() - clientIf=6
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3860): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3860): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3860): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3860): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): setState: NOT_INITIALIZED
D/BtGatt.GattService( 2149): onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
D/BtGatt.ScanManager( 2149): callback done for clientIf - 6 status - 0
D/BtGatt.ScanManager( 2149): stop scan
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): P2P device discovery stopped successfully
D/BtGatt.ScanManager( 2149): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager( 2149): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager( 2149): configureRegularScanParams() - queue emtpy, scan stopped
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3860): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3860): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3860): Service requests cleared successfully
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3860): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 3860): ok 59 Should be able to call stopBroadcasting without error
I/jxcore-log( 3860): 
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3860): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453985772398.3860
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3860): bind: Binding a new listener
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3860): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3860): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453985772398.3860","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3860): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3860): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3860): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
W/BluetoothAdapter( 3860): getBluetoothService() called with no BluetoothManagerCallback
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3860): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3860): start: OK
I/io.jxcore.node.ConnectionHelper( 3860): start: Using peer discovery mode: BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 3860): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3860): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453985772398.3860
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3860): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3860): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3860): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3860): createAdvertiseData: From: 1453985772398.3860 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3860): F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3860): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3860): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
D/BtGatt.GattService( 2149): registerClient() - UUID=8c2e5013-e43c-4c8e-8831-5a0e11c7752e
D/BtGatt.GattService( 2149): onClientRegistered() - UUID=8c2e5013-e43c-4c8e-8831-5a0e11c7752e, clientIf=5
D/BluetoothLeAdvertiser( 3860): onClientRegistered() - status=0 clientIf=5
,D/BtGatt.AdvertiseManager( 2149): message : 0
D/BtGatt.AdvertiseManager( 2149): starting multi advertising
D/BtGatt.GattService( 2149): onAdvertiseInstanceEnabled() - clientIf=5, status=0
D/BtGatt.GattService( 2149): onAdvertiseDataSet() - clientIf=5, status=0
D/BtGatt.GattService( 2149): registerClient() - UUID=12fcd3ec-1f7c-4962-9975-523021f770e3
D/BtGatt.GattService( 2149): onClientRegistered() - UUID=12fcd3ec-1f7c-4962-9975-523021f770e3, clientIf=6
D/BluetoothLeScanner( 3860): onClientRegistered() - status=0 clientIf=6
D/BtGatt.GattService( 2149): start scan with filters
D/BtGatt.ScanManager( 2149): handling starting scan
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): startBlePeerDiscovery: OK
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3860): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453985772398.3860","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3860): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453985772398.3860","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3860): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1453985772398.3860","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
D/BtGatt.GattService( 2149): onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
D/BtGatt.ScanManager( 2149): callback done for clientIf - 6 status - 0
D/BtGatt.GattService( 2149): onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
D/BtGatt.ScanManager( 2149): callback done for clientIf - 6 status - 0
D/BtGatt.ScanManager( 2149): configureRegularScanParams() - queue=1
D/BtGatt.ScanManager( 2149): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): setState: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 3860): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453985772398.3860
I/wpa_supplicant( 1188): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): startBlePeerDiscovery: OK
I/jxcore-log( 3860): ok 60 Should be able to call startBroadcasting without error
I/jxcore-log( 3860): 
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3860): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3860): onIsAdvertiserStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3860): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 3860): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/wpa_supplicant( 1188): P2P-FIND-STOPPED 
I/io.jxcore.node.ConnectionHelper( 3860): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3860): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3860): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3860): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3860): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3860): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3860): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3860): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3860): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): stop: Stopping peer discovery...
I/io.jxcore.node.ConnectionHelper( 3860): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): setState: RESTARTING
D/BtGatt.AdvertiseManager( 2149): message : 1
D/BtGatt.AdvertiseManager( 2149): stop advertise for client 5
D/BtGatt.GattService( 2149): onAdvertiseInstanceDisabled() - clientIf=5, status=0
D/BtGatt.GattService( 2149): Client app is not null!
D/BtGatt.GattService( 2149): unregisterClient() - clientIf=5
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3860): onIsAdvertiserStartedChanged: false
D/BtGatt.GattService( 2149): stopScan() - queue size =1
D/BtGatt.GattService( 2149): unregisterClient() - clientIf=6
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3860): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3860): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3860): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3860): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3860): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3860): release: No more listeners, de-initializing...
D/BtGatt.GattService( 2149): onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,D/BtGatt.ScanManager( 2149): callback done for clientIf - 6 status - 0
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3860): onDiscoveryManagerStateChanged: NOT_STARTED
D/BtGatt.ScanManager( 2149): stop scan
D/BtGatt.ScanManager( 2149): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager( 2149): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager( 2149): configureRegularScanParams() - queue emtpy, scan stopped
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3860): Service requests cleared successfully
,I/jxcore-log( 3860): ok 61 Should be able to call stopBroadcasting without error
I/jxcore-log( 3860): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3860): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453985772469.3860
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3860): bind: Binding a new listener
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3860): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3860): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453985772469.3860","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3860): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3860): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3860): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3860): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3860): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3860): start: OK,
I/io.jxcore.node.ConnectionHelper( 3860): start: Using peer discovery mode: BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 3860): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3860): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453985772469.3860
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3860): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3860): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3860): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3860): createAdvertiseData: From: 1453985772469.3860 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3860): F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3860): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3860): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService( 2149): registerClient() - UUID=116c4206-5f34-4aeb-9fde-2925e5ab0baa
,D/BtGatt.GattService( 2149): onClientRegistered() - UUID=116c4206-5f34-4aeb-9fde-2925e5ab0baa, clientIf=5
D/BluetoothLeAdvertiser( 3860): onClientRegistered() - status=0 clientIf=5
,D/BtGatt.AdvertiseManager( 2149): message : 0
,D/BtGatt.AdvertiseManager( 2149): starting multi advertising,
,D/BtGatt.GattService( 2149): onAdvertiseInstanceEnabled() - clientIf=5, status=0,
,D/BtGatt.GattService( 2149): onAdvertiseDataSet() - clientIf=5, status=0
,D/BtGatt.GattService( 2149): registerClient() - UUID=dc1222ee-0ef1-4e6d-bfa8-2808b4361fe2
,D/BtGatt.GattService( 2149): onClientRegistered() - UUID=dc1222ee-0ef1-4e6d-bfa8-2808b4361fe2, clientIf=6
D/BluetoothLeScanner( 3860): onClientRegistered() - status=0 clientIf=6
D/BtGatt.GattService( 2149): start scan with filters
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): startBlePeerDiscovery: OK
,D/BtGatt.ScanManager( 2149): handling starting scan
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/BtGatt.GattService( 2149): onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,D/BtGatt.ScanManager( 2149): callback done for clientIf - 6 status - 0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3860): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453985772469.3860","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3860): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453985772469.3860","ra":"F8:CF:C5:D9:E5:61"}
D/BtGatt.GattService( 2149): onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
D/BtGatt.ScanManager( 2149): callback done for clientIf - 6 status - 0
,D/BtGatt.ScanManager( 2149): configureRegularScanParams() - queue=1
D/BtGatt.ScanManager( 2149): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3860): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1453985772469.3860","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453985772469.3860
,I/wpa_supplicant( 1188): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
I/io.jxcore.node.ConnectionHelper( 3860): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): startBlePeerDiscovery: Already running
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): startBlePeerDiscovery: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3860): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3860): onIsAdvertiserStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3860): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 3860): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/wpa_supplicant( 1188): P2P-FIND-STOPPED 
,I/jxcore-log( 3860): ok 62 Should be able to call startBroadcasting without error
I/jxcore-log( 3860): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): setState: RESTARTING
,I/io.jxcore.node.ConnectionHelper( 3860): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3860): stop: Stopping Bluetooth...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3860): Shutting down...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3860): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3860): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3860): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3860): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): stop: Stopping peer discovery...
I/io.jxcore.node.ConnectionHelper( 3860): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3860): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3860): onServerStopped
,D/BtGatt.AdvertiseManager( 2149): message : 1
D/BtGatt.AdvertiseManager( 2149): stop advertise for client 5
,D/BtGatt.GattService( 2149): onAdvertiseInstanceDisabled() - clientIf=5, status=0
D/BtGatt.GattService( 2149): Client app is not null!
,D/BtGatt.GattService( 2149): unregisterClient() - clientIf=5
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3860): onIsAdvertiserStartedChanged: false
,D/BtGatt.GattService( 2149): stopScan() - queue size =1
,D/BtGatt.GattService( 2149): unregisterClient() - clientIf=6
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3860): onIsScannerStartedChanged: false
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3860): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3860): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): stop: Stopping P2P device discovery...
,D/BtGatt.GattService( 2149): onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
D/BtGatt.ScanManager( 2149): callback done for clientIf - 6 status - 0
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): setState: NOT_INITIALIZED
,D/BtGatt.ScanManager( 2149): stop scan
D/BtGatt.ScanManager( 2149): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager( 2149): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager( 2149): configureRegularScanParams() - queue emtpy, scan stopped
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3860): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3860): Local services cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3860): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3860): Service requests cleared successfully
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3860): onDiscoveryManagerStateChanged: NOT_STARTED
,I/jxcore-log( 3860): ok 63 Should be able to call stopBroadcasting without error,
I/jxcore-log( 3860): 
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3860): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453985772559.3860
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3860): bind: Binding a new listener
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3860): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3860): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453985772559.3860","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3860): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3860): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3860): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3860): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3860): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 3860): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3860): start: OK
I/io.jxcore.node.ConnectionHelper( 3860): start: Using peer discovery mode: BLE_AND_WIFI
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3860): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453985772559.3860
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3860): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3860): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3860): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3860): createAdvertiseData: From: 1453985772559.3860 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3860): F8:CF:C5:D9:E5:61
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3860): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3860): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService( 2149): registerClient() - UUID=75b7ed3e-2972-4a03-9853-44688530d013
,D/BtGatt.GattService( 2149): onClientRegistered() - UUID=75b7ed3e-2972-4a03-9853-44688530d013, clientIf=5
,D/BluetoothLeAdvertiser( 3860): onClientRegistered() - status=0 clientIf=5
,D/BtGatt.AdvertiseManager( 2149): message : 0
,D/BtGatt.AdvertiseManager( 2149): starting multi advertising
,D/BtGatt.GattService( 2149): onAdvertiseInstanceEnabled() - clientIf=5, status=0
,D/BtGatt.GattService( 2149): onAdvertiseDataSet() - clientIf=5, status=0
,D/BtGatt.GattService( 2149): registerClient() - UUID=f72654fc-20b0-4e08-8528-9f75b749b216
,D/BtGatt.GattService( 2149): onClientRegistered() - UUID=f72654fc-20b0-4e08-8528-9f75b749b216, clientIf=6
,D/BluetoothLeScanner( 3860): onClientRegistered() - status=0 clientIf=6
D/BtGatt.GattService( 2149): start scan with filters
,D/BtGatt.ScanManager( 2149): handling starting scan
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): startBlePeerDiscovery: OK
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/BtGatt.GattService( 2149): onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,D/BtGatt.ScanManager( 2149): callback done for clientIf - 6 status - 0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3860): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453985772559.3860","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3860): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453985772559.3860","ra":"F8:CF:C5:D9:E5:61"}
D/BtGatt.GattService( 2149): onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3860): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1453985772559.3860","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
D/BtGatt.ScanManager( 2149): callback done for clientIf - 6 status - 0
D/BtGatt.ScanManager( 2149): configureRegularScanParams() - queue=1
D/BtGatt.ScanManager( 2149): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): setState: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 3860): start: OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453985772559.3860
I/wpa_supplicant( 1188): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): startBlePeerDiscovery: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3860): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3860): onIsAdvertiserStartedChanged: true
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3860): Local service added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): setState: RESTARTING
,I/io.jxcore.node.ConnectionHelper( 3860): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): setState: STARTED
,I/jxcore-log( 3860): ok 64 Should be able to call startBroadcasting without error
I/jxcore-log( 3860): 
I/wpa_supplicant( 1188): P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/io.jxcore.node.ConnectionHelper( 3860): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3860): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3860): Shutting down...,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3860): stopListeningForIncomingConnections: Stopping...
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3860): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3860): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3860): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): stop: Stopping peer discovery...
I/io.jxcore.node.ConnectionHelper( 3860): onConnectionManagerStateChanged: NOT_STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3860): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3860): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): P2P device discovery stopped successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): setState: RESTARTING
,D/BtGatt.AdvertiseManager( 2149): message : 1
D/BtGatt.AdvertiseManager( 2149): stop advertise for client 5,
,D/BtGatt.GattService( 2149): onAdvertiseInstanceDisabled() - clientIf=5, status=0
D/BtGatt.GattService( 2149): Client app is not null!
,D/BtGatt.GattService( 2149): unregisterClient() - clientIf=5
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3860): onIsAdvertiserStartedChanged: false
,D/BtGatt.GattService( 2149): stopScan() - queue size =1
,D/BtGatt.GattService( 2149): unregisterClient() - clientIf=6
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3860): onIsScannerStartedChanged: false
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3860): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3860): stop: Stopping services
D/BtGatt.GattService( 2149): onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
D/BtGatt.ScanManager( 2149): callback done for clientIf - 6 status - 0
D/BtGatt.ScanManager( 2149): stop scan
D/BtGatt.ScanManager( 2149): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager( 2149): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager( 2149): configureRegularScanParams() - queue emtpy, scan stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3860): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3860): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3860): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): P2P device discovery stopped successfully,
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): setState: NOT_STARTED,
I/io.jxcore.node.ConnectionHelper( 3860): onDiscoveryManagerStateChanged: NOT_STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3860): Service requests cleared successfully
I/jxcore-log( 3860): ok 65 Should be able to call stopBroadcasting without error
I/jxcore-log( 3860): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3860): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453985772701.3860
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3860): bind: Binding a new listener
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3860): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0,
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3860): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453985772701.3860","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3860): setConnectionTimeout: 15000
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3860): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3860): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3860): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3860): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper( 3860): onConnectionManagerStateChanged: RUNNING,
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3860): start: OK
,I/io.jxcore.node.ConnectionHelper( 3860): start: Using peer discovery mode: BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3860): Waiting for incoming connections...
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453985772701.3860
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3860): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3860): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3860): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3860): createAdvertiseData: From: 1453985772701.3860 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3860): F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3860): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3860): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService( 2149): registerClient() - UUID=a26f2c57-6a48-4807-b03a-421b7c3e2262
,D/BtGatt.GattService( 2149): onClientRegistered() - UUID=a26f2c57-6a48-4807-b03a-421b7c3e2262, clientIf=5
D/BluetoothLeAdvertiser( 3860): onClientRegistered() - status=0 clientIf=5
D/BtGatt.AdvertiseManager( 2149): message : 0
,D/BtGatt.AdvertiseManager( 2149): starting multi advertising
,D/BtGatt.GattService( 2149): onAdvertiseInstanceEnabled() - clientIf=5, status=0
,D/BtGatt.GattService( 2149): onAdvertiseDataSet() - clientIf=5, status=0
,D/BtGatt.GattService( 2149): registerClient() - UUID=ee92f360-8533-46b4-ad93-cf6313cade45
D/BtGatt.GattService( 2149): onClientRegistered() - UUID=ee92f360-8533-46b4-ad93-cf6313cade45, clientIf=6
,D/BluetoothLeScanner( 3860): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.GattService( 2149): start scan with filters
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): startBlePeerDiscovery: OK
,D/BtGatt.ScanManager( 2149): handling starting scan
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/BtGatt.GattService( 2149): onScanFilterEnableDisabled() - clientIf=6, status=0, action=1,
D/BtGatt.ScanManager( 2149): callback done for clientIf - 6 status - 0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3860): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453985772701.3860","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3860): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453985772701.3860","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3860): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1453985772701.3860","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
D/BtGatt.GattService( 2149): onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
D/BtGatt.ScanManager( 2149): callback done for clientIf - 6 status - 0
,D/BtGatt.ScanManager( 2149): configureRegularScanParams() - queue=1
D/BtGatt.ScanManager( 2149): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): startWifiPeerDiscovery: Wi-Fi Direct OK
I/wpa_supplicant( 1188): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): setState: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 3860): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453985772701.3860
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): startBlePeerDiscovery: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): startWifiPeerDiscovery: Wi-Fi Direct OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): start: OK
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3860): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3860): onIsAdvertiserStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): setState: RESTARTING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3860): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 3860): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): setState: STARTED
I/jxcore-log( 3860): ok 66 Should be able to call startBroadcasting without error
I/jxcore-log( 3860): 
I/wpa_supplicant( 1188): P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started,
I/io.jxcore.node.ConnectionHelper( 3860): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3860): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3860): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3860): stopListeningForIncomingConnections: Stopping...
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3860): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3860): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3860): Exiting thread
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3860): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3860): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): stop: Stopping peer discovery...
,I/io.jxcore.node.ConnectionHelper( 3860): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): restart: Restarting...
D/BtGatt.AdvertiseManager( 2149): message : 1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): setState: RESTARTING
D/BtGatt.AdvertiseManager( 2149): stop advertise for client 5
D/BtGatt.GattService( 2149): onAdvertiseInstanceDisabled() - clientIf=5, status=0
D/BtGatt.GattService( 2149): Client app is not null!
D/BtGatt.GattService( 2149): unregisterClient() - clientIf=5
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3860): onIsAdvertiserStartedChanged: false
D/BtGatt.GattService( 2149): stopScan() - queue size =1
D/BtGatt.GattService( 2149): unregisterClient() - clientIf=6
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3860): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3860): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3860): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): onIsWifiPeerDiscoveryStartedChanged: false
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3860): release: No more listeners, de-initializing...
D/BtGatt.GattService( 2149): onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,D/BtGatt.ScanManager( 2149): callback done for clientIf - 6 status - 0
D/BtGatt.ScanManager( 2149): stop scan
,D/BtGatt.ScanManager( 2149): configureRegularScanParams() - queue=0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3860): Local services cleared successfully
D/BtGatt.ScanManager( 2149): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
,D/BtGatt.ScanManager( 2149): configureRegularScanParams() - queue emtpy, scan stopped
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3860): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3860): onDiscoveryManagerStateChanged: NOT_STARTED
,I/jxcore-log( 3860): ok 67 Should be able to call stopBroadcasting without error
I/jxcore-log( 3860): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3860): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): setDiscoveryMode: Mode set to BLE_AND_WIFI
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3860): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453985772797.3860
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3860): bind: Binding a new listener
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3860): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3860): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453985772797.3860","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3860): setConnectionTimeout: 15000
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3860): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3860): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
W/BluetoothAdapter( 3860): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3860): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 3860): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3860): start: OK
I/io.jxcore.node.ConnectionHelper( 3860): start: Using peer discovery mode: BLE_AND_WIFI
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3860): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453985772797.3860
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3860): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3860): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3860): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3860): createAdvertiseData: From: 1453985772797.3860 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3860): F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3860): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3860): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService( 2149): registerClient() - UUID=caf3decb-97cb-4a5f-ae6e-19c71fc1aa0f
,D/BtGatt.GattService( 2149): onClientRegistered() - UUID=caf3decb-97cb-4a5f-ae6e-19c71fc1aa0f, clientIf=5
D/BluetoothLeAdvertiser( 3860): onClientRegistered() - status=0 clientIf=5
,D/BtGatt.AdvertiseManager( 2149): message : 0
,D/BtGatt.AdvertiseManager( 2149): starting multi advertising
,D/BtGatt.GattService( 2149): onAdvertiseInstanceEnabled() - clientIf=5, status=0
,D/BtGatt.GattService( 2149): onAdvertiseDataSet() - clientIf=5, status=0
,D/BtGatt.GattService( 2149): registerClient() - UUID=1079ed07-8bce-4206-b47f-f5505851a18b
,D/BtGatt.GattService( 2149): onClientRegistered() - UUID=1079ed07-8bce-4206-b47f-f5505851a18b, clientIf=6
D/BluetoothLeScanner( 3860): onClientRegistered() - status=0 clientIf=6
D/BtGatt.GattService( 2149): start scan with filters
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): startBlePeerDiscovery: OK
,D/BtGatt.ScanManager( 2149): handling starting scan
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3860): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453985772797.3860","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3860): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453985772797.3860","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3860): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1453985772797.3860","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
D/BtGatt.GattService( 2149): onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
D/BtGatt.ScanManager( 2149): callback done for clientIf - 6 status - 0
,D/BtGatt.GattService( 2149): onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
D/BtGatt.ScanManager( 2149): callback done for clientIf - 6 status - 0
,D/BtGatt.ScanManager( 2149): configureRegularScanParams() - queue=1
D/BtGatt.ScanManager( 2149): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): start: Starting P2P device discovery...
I/wpa_supplicant( 1188): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): onIsWifiPeerDiscoveryStartedChanged: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453985772797.3860
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): startBlePeerDiscovery: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): startWifiPeerDiscovery: Wi-Fi Direct OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3860): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3860): onIsAdvertiserStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3860): Local service added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): setState: RESTARTING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3860): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
I/wpa_supplicant( 1188): P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): P2P device discovery stopped successfully
I/io.jxcore.node.ConnectionHelper( 3860): start: OK
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): setState: RESTARTING
,I/jxcore-log( 3860): ok 68 Should be able to call startBroadcasting without error
I/jxcore-log( 3860): 
I/io.jxcore.node.ConnectionHelper( 3860): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3860): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3860): Shutting down...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3860): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3860): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3860): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3860): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3860): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3860): setState: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): stop: Stopping peer discovery...
I/io.jxcore.node.ConnectionHelper( 3860): onConnectionManagerStateChanged: NOT_STARTED
D/BtGatt.AdvertiseManager( 2149): message : 1
D/BtGatt.AdvertiseManager( 2149): stop advertise for client 5
D/BtGatt.GattService( 2149): onAdvertiseInstanceDisabled() - clientIf=5, status=0,
D/BtGatt.GattService( 2149): Client app is not null!
D/BtGatt.GattService( 2149): unregisterClient() - clientIf=5
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3860): onIsAdvertiserStartedChanged: false
,D/BtGatt.GattService( 2149): stopScan() - queue size =1
,D/BtGatt.GattService( 2149): unregisterClient() - clientIf=6
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3860): onIsScannerStartedChanged: false
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3860): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3860): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): stop: Stopping P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3860): Local services cleared successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): stopWifiPeerDiscovery: Stopped
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3860): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3860): Service requests cleared successfully
D/BtGatt.GattService( 2149): onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16,
D/BtGatt.ScanManager( 2149): callback done for clientIf - 6 status - 0
D/BtGatt.ScanManager( 2149): stop scan
,D/BtGatt.ScanManager( 2149): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager( 2149): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
,D/BtGatt.ScanManager( 2149): configureRegularScanParams() - queue emtpy, scan stopped
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3860): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3860): onDiscoveryManagerStateChanged: NOT_STARTED
,I/jxcore-log( 3860): ok 69 Should be able to call stopBroadcasting without error
I/jxcore-log( 3860): 
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): setDiscoveryMode: Mode set to BLE_AND_WIFI
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3860): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453985772875.3860
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3860): bind: Binding a new listener
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3860): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3860): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453985772875.3860","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3860): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3860): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3860): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3860): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3860): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3860): start: OK
I/io.jxcore.node.ConnectionHelper( 3860): start: Using peer discovery mode: BLE_AND_WIFI,
I/io.jxcore.node.ConnectionHelper( 3860): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453985772875.3860
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3860): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3860): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3860): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3860): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3860): createAdvertiseData: From: 1453985772875.3860 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3860): F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3860): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3860): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService( 2149): registerClient() - UUID=faeaf052-3d11-44a1-bbed-1e6eaa5a50be
,D/BtGatt.GattService( 2149): onClientRegistered() - UUID=faeaf052-3d11-44a1-bbed-1e6eaa5a50be, clientIf=5
,D/BluetoothLeAdvertiser( 3860): onClientRegistered() - status=0 clientIf=5
D/BtGatt.AdvertiseManager( 2149): message : 0
,D/BtGatt.AdvertiseManager( 2149): starting multi advertising
,D/BtGatt.GattService( 2149): onAdvertiseInstanceEnabled() - clientIf=5, status=0,
,D/BtGatt.GattService( 2149): onAdvertiseDataSet() - clientIf=5, status=0
,D/BtGatt.GattService( 2149): registerClient() - UUID=c5b0bb19-b746-485f-b46a-ea8d1315650b
,D/BtGatt.GattService( 2149): onClientRegistered() - UUID=c5b0bb19-b746-485f-b46a-ea8d1315650b, clientIf=6
D/BluetoothLeScanner( 3860): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.GattService( 2149): start scan with filters
D/BtGatt.ScanManager( 2149): handling starting scan
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): startBlePeerDiscovery: OK
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/BtGatt.GattService( 2149): onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,D/BtGatt.ScanManager( 2149): callback done for clientIf - 6 status - 0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3860): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453985772875.3860","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3860): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453985772875.3860","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3860): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1453985772875.3860","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
D/BtGatt.GattService( 2149): onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
D/BtGatt.ScanManager( 2149): callback done for clientIf - 6 status - 0
D/BtGatt.ScanManager( 2149): configureRegularScanParams() - queue=1
,D/BtGatt.ScanManager( 2149): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453985772875.3860
I/wpa_supplicant( 1188): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
I/io.jxcore.node.ConnectionHelper( 3860): start: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): startBlePeerDiscovery: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): start: OK
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3860): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3860): onIsAdvertiserStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3860): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 3860): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/wpa_supplicant( 1188): P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): P2P device discovery stopped successfully
,I/jxcore-log( 3860): ok 70 Should be able to call startBroadcasting without error
I/jxcore-log( 3860): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 3860): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3860): stop: Stopping Bluetooth...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3860): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3860): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3860): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3860): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3860): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3860): release: 1 listener(s) left
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3860): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3860): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): stop: Stopping peer discovery...
D/BtGatt.AdvertiseManager( 2149): message : 1
D/BtGatt.AdvertiseManager( 2149): stop advertise for client 5
,D/BtGatt.GattService( 2149): onAdvertiseInstanceDisabled() - clientIf=5, status=0
,D/BtGatt.GattService( 2149): Client app is not null!
D/BtGatt.GattService( 2149): unregisterClient() - clientIf=5
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3860): onIsAdvertiserStartedChanged: false
,D/BtGatt.GattService( 2149): stopScan() - queue size =1
,D/BtGatt.GattService( 2149): unregisterClient() - clientIf=6
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3860): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3860): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): onIsBlePeerDiscoveryStartedChanged: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3860): stop: Stopping services,
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3860): Local services cleared successfully,
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): onIsWifiPeerDiscoveryStartedChanged: false
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): stopWifiPeerDiscovery: Stopped
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3860): release: No more listeners, de-initializing...
,D/BtGatt.GattService( 2149): onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,D/BtGatt.ScanManager( 2149): callback done for clientIf - 6 status - 0
D/BtGatt.ScanManager( 2149): stop scan
,D/BtGatt.ScanManager( 2149): configureRegularScanParams() - queue=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3860): release: No more listeners, de-initializing...
D/BtGatt.ScanManager( 2149): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
,D/BtGatt.ScanManager( 2149): configureRegularScanParams() - queue emtpy, scan stopped
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): setState: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper( 3860): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3860): Service requests cleared successfully
,I/jxcore-log( 3860): ok 71 Should be able to call stopBroadcasting without error
I/jxcore-log( 3860): 
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3860): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453985772950.3860
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3860): bind: Binding a new listener
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3860): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3860): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453985772950.3860","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3860): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3860): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3860): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3860): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3860): setState: RUNNING,
I/io.jxcore.node.ConnectionHelper( 3860): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3860): start: OK
I/io.jxcore.node.ConnectionHelper( 3860): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453985772950.3860
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3860): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3860): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3860): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): onWifiStateChanged: State changed to 2
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3860): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3860): createAdvertiseData: From: 1453985772950.3860 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3860): F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3860): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3860): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService( 2149): registerClient() - UUID=d6890c7a-7afe-4fd5-9499-a621639fc1f8
,D/BtGatt.GattService( 2149): onClientRegistered() - UUID=d6890c7a-7afe-4fd5-9499-a621639fc1f8, clientIf=5
D/BluetoothLeAdvertiser( 3860): onClientRegistered() - status=0 clientIf=5
D/BtGatt.AdvertiseManager( 2149): message : 0
,D/BtGatt.AdvertiseManager( 2149): starting multi advertising
,D/BtGatt.GattService( 2149): onAdvertiseInstanceEnabled() - clientIf=5, status=0
,D/BtGatt.GattService( 2149): onAdvertiseDataSet() - clientIf=5, status=0
,D/BtGatt.GattService( 2149): registerClient() - UUID=0572124b-0d4e-41b5-97a2-77873f727a01
,D/BtGatt.GattService( 2149): onClientRegistered() - UUID=0572124b-0d4e-41b5-97a2-77873f727a01, clientIf=6
D/BluetoothLeScanner( 3860): onClientRegistered() - status=0 clientIf=6
D/BtGatt.GattService( 2149): start scan with filters
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): startBlePeerDiscovery: OK
D/BtGatt.ScanManager( 2149): handling starting scan
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3860): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453985772950.3860","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3860): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453985772950.3860","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3860): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1453985772950.3860","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
,D/BtGatt.GattService( 2149): onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
D/BtGatt.ScanManager( 2149): callback done for clientIf - 6 status - 0
D/BtGatt.GattService( 2149): onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,D/BtGatt.ScanManager( 2149): callback done for clientIf - 6 status - 0
D/BtGatt.ScanManager( 2149): configureRegularScanParams() - queue=1
D/BtGatt.ScanManager( 2149): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): setState: RUNNING_BLE_AND_WIFI
I/wpa_supplicant( 1188): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453985772950.3860
,I/io.jxcore.node.ConnectionHelper( 3860): start: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): startBlePeerDiscovery: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3860): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3860): onIsAdvertiserStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): setState: RESTARTING
,I/io.jxcore.node.ConnectionHelper( 3860): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3860): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/jxcore-log( 3860): ok 72 Should be able to call startBroadcasting without error
I/jxcore-log( 3860): 
I/io.jxcore.node.ConnectionHelper( 3860): stop
I/wpa_supplicant( 1188): P2P-FIND-STOPPED 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3860): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3860): Shutting down...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3860): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3860): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3860): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3860): setState: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3860): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3860): onServerStopped
,I/io.jxcore.node.ConnectionHelper( 3860): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): stop: Stopping peer discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): setState: RESTARTING
D/BtGatt.AdvertiseManager( 2149): message : 1
D/BtGatt.AdvertiseManager( 2149): stop advertise for client 5
,D/BtGatt.GattService( 2149): onAdvertiseInstanceDisabled() - clientIf=5, status=0
,D/BtGatt.GattService( 2149): Client app is not null!
D/BtGatt.GattService( 2149): unregisterClient() - clientIf=5
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3860): onIsAdvertiserStartedChanged: false
,D/BtGatt.GattService( 2149): stopScan() - queue size =1
,D/BtGatt.GattService( 2149): unregisterClient() - clientIf=6
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3860): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3860): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): stopBlePeerDiscovery: Stopped
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3860): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3860): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3860): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3860): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3860): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3860): onDiscoveryManagerStateChanged: NOT_STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3860): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3860): Service requests cleared successfully
,I/jxcore-log( 3860): ok 73 Should be able to call stopBroadcasting without error
I/jxcore-log( 3860): 
,D/BtGatt.GattService( 2149): onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
D/BtGatt.ScanManager( 2149): callback done for clientIf - 6 status - 0
D/BtGatt.ScanManager( 2149): stop scan
D/BtGatt.ScanManager( 2149): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager( 2149): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
,D/BtGatt.ScanManager( 2149): configureRegularScanParams() - queue emtpy, scan stopped
I/jxcore-log( 3860): # setup
I/jxcore-log( 3860): 
,V/KeepSync( 3788): Connecting to GoogleApiClient
,I/art     (  821): Explicit concurrent mark sweep GC freed 38596(1844KB) AllocSpace objects, 11(741KB) LOS objects, 31% free, 34MB/50MB, paused 1.540ms total 95.168ms
,I/GLSUser ( 1287): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1287): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1287): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1287): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1287): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1287): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1287): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1287): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1287): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1287): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3686): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3686): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3686): 	at jdm.a(PG:82)
E/HttpOperation( 3686): 	at jcs.o(PG:406)
E/HttpOperation( 3686): 	at jcn.a(PG:1379)
E/HttpOperation( 3686): 	at jcs.i(PG:143)
E/HttpOperation( 3686): 	at blb.a(PG:3937)
E/HttpOperation( 3686): 	at czp.a(PG:18188)
E/HttpOperation( 3686): 	at czp.a(PG:9081)
E/HttpOperation( 3686): 	at czq.run(PG:1686)
E/HttpOperation( 3686): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3686): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3686): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3686): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3686): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3686): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3686): 	at jdj.a(PG:4091)
E/HttpOperation( 3686): 	at jdj.a(PG:1125)
E/HttpOperation( 3686): 	at jdm.a(PG:77)
E/HttpOperation( 3686): 	... 12 more
E/HttpOperation( 3686): Caused by: faj: BadAuthentication
E/HttpOperation( 3686): 	at fal.a(PG:38)
E/HttpOperation( 3686): 	at jdj.a(PG:4089)
E/HttpOperation( 3686): 	... 14 more
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
,V/KeepSync( 3788): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3788): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3788): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3788): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1287): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1287): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1287): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1287): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1287): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3686): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3686): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3686): 	at jdm.a(PG:82)
E/HttpOperation( 3686): 	at jcs.o(PG:406)
E/HttpOperation( 3686): 	at jcn.a(PG:1379)
E/HttpOperation( 3686): 	at jcs.i(PG:143)
E/HttpOperation( 3686): 	at hec.a(PG:42)
E/HttpOperation( 3686): 	at hee.a(PG:102)
E/HttpOperation( 3686): 	at czr.a(PG:65)
E/HttpOperation( 3686): 	at kka.a(PG:108)
E/HttpOperation( 3686): 	at czp.a(PG:19176)
E/HttpOperation( 3686): 	at czp.a(PG:9081)
E/HttpOperation( 3686): 	at czq.run(PG:1686)
E/HttpOperation( 3686): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3686): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3686): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3686): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3686): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3686): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3686): 	at jdj.a(PG:4091)
E/HttpOperation( 3686): 	at jdj.a(PG:1125)
E/HttpOperation( 3686): 	at jdm.a(PG:77)
E/HttpOperation( 3686): 	... 15 more
E/HttpOperation( 3686): Caused by: faj: BadAuthentication
E/HttpOperation( 3686): 	at fal.a(PG:38)
E/HttpOperation( 3686): 	at jdj.a(PG:4089)
E/HttpOperation( 3686): 	... 17 more
E/ExperimentLoader( 3686): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3686): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3686): 	at jdm.a(PG:82)
E/ExperimentLoader( 3686): 	at jcs.o(PG:406)
E/ExperimentLoader( 3686): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3686): 	at jcs.i(PG:143)
E/ExperimentLoader( 3686): 	at hec.a(PG:42)
E/ExperimentLoader( 3686): 	at hee.a(PG:102)
E/ExperimentLoader( 3686): 	at czr.a(PG:65)
E/ExperimentLoader( 3686): 	at kka.a(PG:108)
E/ExperimentLoader( 3686): 	at czp.a(PG:19176)
E/ExperimentLoader( 3686): 	at czp.a(PG:9081)
E/ExperimentLoader( 3686): 	at czq.run(PG:1686)
E/ExperimentLoader( 3686): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3686): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3686): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3686): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3686): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3686): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3686): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3686): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3686): 	at jdm.a(PG:77)
E/ExperimentLoader( 3686): 	... 15 more
E/ExperimentLoader( 3686): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3686): 	at fal.a(PG:38)
E/ExperimentLoader( 3686): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3686): 	... 17 more
,I/GLSUser ( 1287): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1287): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1287): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1287): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1287): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3788): IOException
E/KeepSync( 3788): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3788): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3788): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3788): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3788): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3788): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3788): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3788): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3788): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3788): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3788): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3788): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3788): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3788): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3788): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3788): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3788): 	... 10 more
W/KeepSync( 3788): Sync result 2
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 319828, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 319031, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,D/WifiService(  821): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@c396739}
,E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-49,
,D/WifiService(  821): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@c396739}
,E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::injectLocation(GpsExtLocation):857]: error! inject position failed
,V/GLSActivity( 1287): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1287): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1287): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1287): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1287): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1287): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/GLSActivity( 1287): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1287): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1287): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1287): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1287): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1287): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1287): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 3625): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3625): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3625): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 3625): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3625): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/PlayEventLogger( 3625): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3625): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 3625): Ignoring header User-Agent because its value was null.
,D/HeadsetStateMachine( 2149): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2149): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2149): Disconnected process message: 10, size: 0
,V/GoogleAuthProtoRequest( 3920): [429] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1287): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1287): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1287): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1287): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1287): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3920): [429] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3920): [429] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3920): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3920): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3920): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3920): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3920): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3920): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3920): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3920): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3920): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3920): 	at com.a.a.k.run(SourceFile:110)
,I/BooksSync( 3771): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3771): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1287): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1287): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1287): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1287): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1287): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1287): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1287): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1287): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1287): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1287): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3771): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3771): Soft error
E/BooksSync( 3771): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3771): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3771): Sync error
E/BooksSync( 3771): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3771): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3771): Finished books sync
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 434639, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2149): Disconnected process message: 10, size: 0
,V/KeepSync( 3788): Connecting to GoogleApiClient
,I/GLSUser ( 1287): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1287): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1287): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1287): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1287): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3686): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3686): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3686): 	at jdm.a(PG:82)
E/HttpOperation( 3686): 	at jcs.o(PG:406)
E/HttpOperation( 3686): 	at jcn.a(PG:1379)
E/HttpOperation( 3686): 	at jcs.i(PG:143)
E/HttpOperation( 3686): 	at blb.a(PG:3937)
E/HttpOperation( 3686): 	at czp.a(PG:18188)
E/HttpOperation( 3686): 	at czp.a(PG:9081)
E/HttpOperation( 3686): 	at czq.run(PG:1686)
E/HttpOperation( 3686): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3686): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3686): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3686): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3686): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3686): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3686): 	at jdj.a(PG:4091)
E/HttpOperation( 3686): 	at jdj.a(PG:1125)
E/HttpOperation( 3686): 	at jdm.a(PG:77)
E/HttpOperation( 3686): 	... 12 more
E/HttpOperation( 3686): Caused by: faj: BadAuthentication
E/HttpOperation( 3686): 	at fal.a(PG:38)
E/HttpOperation( 3686): 	at jdj.a(PG:4089)
E/HttpOperation( 3686): 	... 14 more
,I/GLSUser ( 1287): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1287): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1287): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1287): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1287): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,V/KeepSync( 3788): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3788): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3788): (284) automatic index on blob_node(is_deleted)
I/GLSUser ( 1287): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1287): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1287): [GLSUser] Extracting token using key: Auth
E/SQLiteLog( 3788): (284) automatic index on blob_node(is_deleted)
W/GLSActivity( 1287): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1287): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1287): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1287): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1287): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1287): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1287): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  821): Explicit concurrent mark sweep GC freed 34475(1582KB) AllocSpace objects, 10(348KB) LOS objects, 31% free, 34MB/50MB, paused 1.825ms total 70.933ms
,E/HttpOperation( 3686): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3686): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3686): 	at jdm.a(PG:82)
E/HttpOperation( 3686): 	at jcs.o(PG:406)
E/HttpOperation( 3686): 	at jcn.a(PG:1379)
E/HttpOperation( 3686): 	at jcs.i(PG:143)
E/HttpOperation( 3686): 	at hec.a(PG:42)
E/HttpOperation( 3686): 	at hee.a(PG:102)
E/HttpOperation( 3686): 	at czr.a(PG:65)
E/HttpOperation( 3686): 	at kka.a(PG:108)
E/HttpOperation( 3686): 	at czp.a(PG:19176)
E/HttpOperation( 3686): 	at czp.a(PG:9081)
E/HttpOperation( 3686): 	at czq.run(PG:1686)
E/HttpOperation( 3686): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3686): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3686): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3686): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3686): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3686): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3686): 	at jdj.a(PG:4091)
E/HttpOperation( 3686): 	at jdj.a(PG:1125)
E/HttpOperation( 3686): 	at jdm.a(PG:77)
E/HttpOperation( 3686): 	... 15 more
E/HttpOperation( 3686): Caused by: faj: BadAuthentication
E/HttpOperation( 3686): 	at fal.a(PG:38)
E/HttpOperation( 3686): 	at jdj.a(PG:4089)
E/HttpOperation( 3686): 	... 17 more
,E/ExperimentLoader( 3686): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3686): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3686): 	at jdm.a(PG:82)
E/ExperimentLoader( 3686): 	at jcs.o(PG:406)
E/ExperimentLoader( 3686): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3686): 	at jcs.i(PG:143)
E/ExperimentLoader( 3686): 	at hec.a(PG:42)
E/ExperimentLoader( 3686): 	at hee.a(PG:102)
E/ExperimentLoader( 3686): 	at czr.a(PG:65)
E/ExperimentLoader( 3686): 	at kka.a(PG:108)
E/ExperimentLoader( 3686): 	at czp.a(PG:19176)
E/ExperimentLoader( 3686): 	at czp.a(PG:9081)
E/ExperimentLoader( 3686): 	at czq.run(PG:1686)
E/ExperimentLoader( 3686): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3686): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3686): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3686): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3686): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3686): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3686): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3686): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3686): 	at jdm.a(PG:77)
E/ExperimentLoader( 3686): 	... 15 more
E/ExperimentLoader( 3686): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3686): 	at fal.a(PG:38)
E/ExperimentLoader( 3686): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3686): 	... 17 more
,E/KeepSync( 3788): IOException
E/KeepSync( 3788): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3788): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3788): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3788): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3788): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3788): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3788): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3788): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3788): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3788): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3788): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3788): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3788): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3788): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3788): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3788): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3788): 	... 10 more
W/KeepSync( 3788): Sync result 2
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 475583, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 473991, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2149): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2149): Disconnected process message: 10, size: 0
,I/ActivityManager(  821): Start proc 4279:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider
,I/art     (  369): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 337us total 22.374ms
,I/art     (  369): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 443us total 16.462ms
,I/art     (  369): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 235us total 14.389ms
,I/GAv4    ( 4279): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4279):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4279):   adb logcat -s GAv4
,W/GAv4    ( 4279): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4279): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4279): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  821): Killing 2497:com.google.android.calendar/u0a37 (adj 15): empty #17
,D/HeadsetStateMachine( 2149): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2149): Disconnected process message: 10, size: 0
,I/art     ( 1287): Explicit concurrent mark sweep GC freed 54396(2MB) AllocSpace objects, 17(1874KB) LOS objects, 36% free, 27MB/43MB, paused 1.798ms total 55.376ms
,V/GoogleAuthProtoRequest( 3920): [430] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1287): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1287): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1287): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1287): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1287): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3920): [430] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3920): [430] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3920): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3920): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3920): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3920): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3920): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3920): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3920): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3920): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3920): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3920): 	at com.a.a.k.run(SourceFile:110)
,I/BooksSync( 3771): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3771): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1287): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1287): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1287): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1287): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1287): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1287): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1287): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1287): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1287): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1287): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3771): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3771): Soft error,
E/BooksSync( 3771): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3771): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3771): Sync error
E/BooksSync( 3771): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3771): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3771): Finished books sync
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 675895, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2149): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2149): Disconnected process message: 10, size: 0
,I/GLSUser ( 1287): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1287): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1287): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1287): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1287): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3686): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3686): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3686): 	at jdm.a(PG:82)
E/HttpOperation( 3686): 	at jcs.o(PG:406)
E/HttpOperation( 3686): 	at jcn.a(PG:1379)
E/HttpOperation( 3686): 	at jcs.i(PG:143)
E/HttpOperation( 3686): 	at blb.a(PG:3937)
E/HttpOperation( 3686): 	at czp.a(PG:18188)
E/HttpOperation( 3686): 	at czp.a(PG:9081)
E/HttpOperation( 3686): 	at czq.run(PG:1686)
E/HttpOperation( 3686): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3686): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237),
E/HttpOperation( 3686): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3686): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3686): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3686): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3686): 	at jdj.a(PG:4091)
E/HttpOperation( 3686): 	at jdj.a(PG:1125)
E/HttpOperation( 3686): 	at jdm.a(PG:77)
E/HttpOperation( 3686): 	... 12 more
E/HttpOperation( 3686): Caused by: faj: BadAuthentication
E/HttpOperation( 3686): 	at fal.a(PG:38)
E/HttpOperation( 3686): 	,at jdj.a(PG:4089)
E/HttpOperation( 3686): 	... 14 more
,I/GLSUser ( 1287): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1287): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1287): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1287): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1287): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3686): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3686): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3686): ,	at jdm.a(PG:82)
E/HttpOperation( 3686): 	at jcs.o(PG:406)
E/HttpOperation( 3686): 	at jcn.a(PG:1379)
E/HttpOperation( 3686): 	at jcs.i(PG:143)
E/HttpOperation( 3686): 	at hec.a(PG:42)
E/HttpOperation( 3686): 	at hee.a(PG:102)
E/HttpOperation( 3686): 	at czr.a(PG:65)
E/HttpOperation( 3686): 	,at kka.a(PG:108)
E/HttpOperation( 3686): 	at czp.a(PG:19176)
E/HttpOperation( 3686): 	at czp.a(PG:9081)
E/HttpOperation( 3686): 	at czq.run(PG:1686)
E/HttpOperation( 3686): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3686): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3686): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3686): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3686): 	,at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3686): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3686): 	at jdj.a(PG:4091)
E/HttpOperation( 3686): 	at jdj.a(PG:1125)
E/HttpOperation( 3686): 	at jdm.a(PG:77)
E/HttpOperation( 3686): 	... 15 more
E/HttpOperation( 3686): Caused by: faj: BadAuthentication
,E/HttpOperation( 3686): 	at fal.a(PG:38)
E/HttpOperation( 3686): 	at jdj.a(PG:4089)
E/HttpOperation( 3686): 	... 17 more
E/ExperimentLoader( 3686): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3686): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3686): 	at jdm.a(PG:82)
E/ExperimentLoader( 3686): 	at jcs.o(PG:406)
E/ExperimentLoader( 3686): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3686): ,	at jcs.i(PG:143)
E/ExperimentLoader( 3686): 	at hec.a(PG:42)
E/ExperimentLoader( 3686): 	at hee.a(PG:102)
E/ExperimentLoader( 3686): 	at czr.a(PG:65)
E/ExperimentLoader( 3686): 	at kka.a(PG:108)
E/ExperimentLoader( 3686): 	at czp.a(PG:19176)
E/ExperimentLoader( 3686): 	at czp.a(PG:9081)
E/ExperimentLoader( 3686): 	at czq.run(PG:1686)
E/ExperimentLoader( 3686): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422),
E/ExperimentLoader( 3686): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3686): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3686): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3686): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3686): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3686): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3686): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3686): 	at jdm.a(PG:77)
E/ExperimentLoader( 3686): 	... 15 more
,E/ExperimentLoader( 3686): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3686): 	at fal.a(PG:38)
E/ExperimentLoader( 3686): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3686): 	... 17 more
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 754391, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,V/KeepSync( 3788): Connecting to GoogleApiClient
,I/GLSUser ( 1287): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1287): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1287): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1287): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1287): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,V/KeepSync( 3788): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3788): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3788): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3788): (284) automatic index on blob_node(is_deleted)
,D/HeadsetStateMachine( 2149): Disconnected process message: 10, size: 0
,I/GLSUser ( 1287): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1287): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1287): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1287): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1287): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3788): IOException
E/KeepSync( 3788): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3788): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3788): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3788): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3788): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3788): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3788): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3788): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3788): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3788): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3788): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3788): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3788): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3788): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3788): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3788): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3788): 	... 10 more
W/KeepSync( 3788): Sync result 2
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 757559, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2149): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2149): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2149): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2149): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2149): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2149): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2149): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2149): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2149): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2149): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2149): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2149): Disconnected process message: 10, size: 0
,I/BooksSync( 3771): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3771): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1287): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1287): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1287): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1287): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1287): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  821): Explicit concurrent mark sweep GC freed 50843(2MB) AllocSpace objects, 10(442KB) LOS objects, 31% free, 34MB/50MB, paused 1.495ms total 110.476ms
,I/GLSUser ( 1287): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1287): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1287): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1287): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1287): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3771): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3771): Soft error
E/BooksSync( 3771): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3771): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3771): Sync error
E/BooksSync( 3771): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3771): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3771): Finished books sync
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1158148, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2149): Disconnected process message: 10, size: 0
,W/bt-btm  ( 2149): Stopping oneshot timer
,I/UsageStatsService(  821): User[0] Flushing usage stats to disk
,D/HeadsetStateMachine( 2149): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2149): Disconnected process message: 10, size: 0
,D/GCM     ( 1287): Message class com.google.f.a.a.i
,V/GoogleAuthProtoRequest( 3920): [431] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1287): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1287): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1287): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1287): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1287): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1287): Explicit concurrent mark sweep GC freed 67914(3MB) AllocSpace objects, 13(1434KB) LOS objects, 36% free, 27MB/43MB, paused 814us total 28.641ms
,W/ExperimentUpdateService( 3920): [431] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3920): [431] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3920): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3920): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3920): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3920): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3920): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3920): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3920): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3920): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3920): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3920): 	at com.a.a.k.run(SourceFile:110)
,I/GLSUser ( 1287): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1287): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1287): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1287): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1287): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3686): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3686): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3686): 	at jdm.a(PG:82)
E/HttpOperation( 3686): 	at jcs.o(PG:406)
E/HttpOperation( 3686): 	at jcn.a(PG:1379)
E/HttpOperation( 3686): 	at jcs.i(PG:143)
E/HttpOperation( 3686): 	at blb.a(PG:3937)
E/HttpOperation( 3686): 	at czp.a(PG:18188)
E/HttpOperation( 3686): 	at czp.a(PG:9081)
E/HttpOperation( 3686): 	at czq.run(PG:1686)
E/HttpOperation( 3686): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3686): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3686): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3686): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3686): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3686): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3686): 	at jdj.a(PG:4091)
E/HttpOperation( 3686): 	at jdj.a(PG:1125)
E/HttpOperation( 3686): 	at jdm.a(PG:77)
E/HttpOperation( 3686): 	... 12 more
E/HttpOperation( 3686): Caused by: faj: BadAuthentication
E/HttpOperation( 3686): 	at fal.a(PG:38)
E/HttpOperation( 3686): 	at jdj.a(PG:4089)
E/HttpOperation( 3686): 	... 14 more
,I/GLSUser ( 1287): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1287): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1287): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1287): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1287): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3686): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3686): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3686): 	at jdm.a(PG:82)
E/HttpOperation( 3686): 	at jcs.o(PG:406)
E/HttpOperation( 3686): 	at jcn.a(PG:1379)
E/HttpOperation( 3686): 	at jcs.i(PG:143)
E/HttpOperation( 3686): 	at hec.a(PG:42)
E/HttpOperation( 3686): 	at hee.a(PG:102)
E/HttpOperation( 3686): 	at czr.a(PG:65)
E/HttpOperation( 3686): 	at kka.a(PG:108)
E/HttpOperation( 3686): 	at czp.a(PG:19176)
E/HttpOperation( 3686): 	at czp.a(PG:9081)
E/HttpOperation( 3686): 	at czq.run(PG:1686)
E/HttpOperation( 3686): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3686): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3686): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3686): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3686): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3686): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3686): 	at jdj.a(PG:4091)
E/HttpOperation( 3686): 	at jdj.a(PG:1125)
E/HttpOperation( 3686): 	at jdm.a(PG:77)
E/HttpOperation( 3686): 	... 15 more
E/HttpOperation( 3686): Caused by: faj: BadAuthentication
E/HttpOperation( 3686): 	at fal.a(PG:38)
E/HttpOperation( 3686): 	at jdj.a(PG:4089)
E/HttpOperation( 3686): 	... 17 more
,E/ExperimentLoader( 3686): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3686): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3686): 	at jdm.a(PG:82)
E/ExperimentLoader( 3686): 	at jcs.o(PG:406)
E/ExperimentLoader( 3686): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3686): 	at jcs.i(PG:143)
E/ExperimentLoader( 3686): 	at hec.a(PG:42)
E/ExperimentLoader( 3686): 	at hee.a(PG:102)
E/ExperimentLoader( 3686): 	at czr.a(PG:65)
E/ExperimentLoader( 3686): 	at kka.a(PG:108)
E/ExperimentLoader( 3686): 	at czp.a(PG:19176)
E/ExperimentLoader( 3686): 	at czp.a(PG:9081)
E/ExperimentLoader( 3686): 	at czq.run(PG:1686)
E/ExperimentLoader( 3686): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3686): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3686): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3686): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3686): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3686): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3686): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3686): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3686): 	at jdm.a(PG:77)
E/ExperimentLoader( 3686): 	... 15 more
E/ExperimentLoader( 3686): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3686): 	at fal.a(PG:38)
E/ExperimentLoader( 3686): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3686): 	... 17 more
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 1273407, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 4453): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 4453): CheckJNI is OFF
D/AndroidRuntime( 4453): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  821): Force stopping com.test.thalitest appid=10265 user=-1: uninstall pkg
I/ActivityManager(  821): Killing 3860:com.test.thalitest/u0a265 (adj 0): stop com.test.thalitest
W/PackageSettings(  821): Skipping PackageSetting{e261ff1 com.example.hello/10273} due to missing metadata
E/libprocessgroup(  821): failed to kill 1 processes for processgroup 3860
W/ActivityManager(  821): Force removing ActivityRecord{2d14a274 u0 com.test.thalitest/.MainActivity t28}: app died, no saved state
E/JavaBinder(  821): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder(  821): !!! FAILED BINDER TRANSACTION !!!
V/ActivityManager(  821): Display changed displayId=0
D/WifiService(  821): Client connection lost with reason: 4
W/DisplayManagerService(  821): Failed to notify process 3860 that displays changed, assuming it died.
W/DisplayManagerService(  821): android.os.DeadObjectException
W/DisplayManagerService(  821): 	at android.os.BinderProxy.transactNative(Native Method)
W/DisplayManagerService(  821): 	at android.os.BinderProxy.transact(Binder.java:496)
W/DisplayManagerService(  821): 	at android.hardware.display.IDisplayManagerCallback$Stub$Proxy.onDisplayEvent(IDisplayManagerCallback.java:81)
W/DisplayManagerService(  821): 	at com.android.server.display.DisplayManagerService$CallbackRecord.notifyDisplayEventAsync(DisplayManagerService.java:1094)
W/DisplayManagerService(  821): 	at com.android.server.display.DisplayManagerService.deliverDisplayEvent(DisplayManagerService.java:932)
W/DisplayManagerService(  821): 	at com.android.server.display.DisplayManagerService.access$500(DisplayManagerService.java:112)
W/DisplayManagerService(  821): 	at com.android.server.display.DisplayManagerService$DisplayManagerHandler.handleMessage(DisplayManagerService.java:1027)
W/DisplayManagerService(  821): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/DisplayManagerService(  821): 	at android.os.Looper.loop(Looper.java:135)
W/DisplayManagerService(  821): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/DisplayManagerService(  821): 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
I/ActivityManager(  821): Force stopping com.test.thalitest appid=10265 user=0: pkg removed
I/InputReader(  821): Reconfiguring input devices.  changes=0x00000010
I/Keyboard.Facilitator( 1230): resetDictionaries() : en_US
D/TaskPersister(  821): removeObsoleteFile: deleting file=28_task.xml
D/BuaReceiver( 3515): ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
I/Keyboard.Facilitator.DecoderInitializer( 1230): run()
I/Decoder ( 1230): createOrResetDecoder
I/ActivityManager(  821): Start proc 4469:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
I/art     (  821): Explicit concurrent mark sweep GC freed 24687(1498KB) AllocSpace objects, 12(474KB) LOS objects, 31% free, 34MB/50MB, paused 3.194ms total 82.780ms
I/art     (  821): WaitForGcToComplete blocked for 79.772ms for cause Explicit
W/InputMethodManagerService(  821): Got RemoteException sending setActive(false) notification to pid 3860 uid 10265
I/Keyboard.Facilitator( 1230): onFinishInput()
I/art     ( 1066): Explicit concurrent mark sweep GC freed 72892(2MB) AllocSpace objects, 0(0B) LOS objects, 18% free, 72MB/88MB, paused 1.194ms total 89.740ms
I/ConfigService( 1287): onCreate
I/art     ( 1528): Explicit concurrent mark sweep GC freed 2304(170KB) AllocSpace objects, 0(0B) LOS objects, 36% free, 27MB/43MB, paused 13.145ms total 121.074ms
I/art     ( 1369): Explicit concurrent mark sweep GC freed 4977(363KB) AllocSpace objects, 11(1298KB) LOS objects, 31% free, 35MB/51MB, paused 782us total 27.892ms
W/LocationOracleImpl( 1528): Best location was null
D/JobSchedulerService(  821): Receieved: android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  821): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/Keyboard.Facilitator.MainLanguageModelLoader( 1230): run()
I/HotwordRecognitionRnr( 1528): Starting hotword detection.
I/MicrophoneInputStream( 1528): mic_starting com.google.android.apps.gsa.speech.audio.u@3a2a61
I/SoundTriggerHwService::Module(  358): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/AudioFlinger(  358): AudioFlinger's thread 0xb4078000 ready to run
I/MicrophoneInputStream( 1528): mic_started com.google.android.apps.gsa.speech.audio.u@3a2a61
D/audio_hw_primary(  358): select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
D/msm8974_platform(  358): platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
E/ACDB-LOADER(  358): Error: ACDB AudProc vol returned = -19
D/audio_hw_primary(  358): enable_snd_device: snd_device(55: voice-rec-mic)
I/Keyboard.Facilitator.MainLanguageModelLoader( 1230): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1230): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1230): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1230): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1230): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1230): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1230): run() : Loading LM = user
D/audio_hw_primary(  358): enable_audio_route: apply and update mixer path: audio-record
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1230): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1230): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1230): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1230): run()
I/StatsUtilsManager( 1230): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1230): shouldRecordStats() = Too Soon
I/art     (  821): Explicit concurrent mark sweep GC freed 6130(290KB) AllocSpace objects, 1(110KB) LOS objects, 31% free, 34MB/50MB, paused 8.620ms total 144.563ms
I/ContactLocale( 4469): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
I/HotwordWorker( 1528): onReady
D/VoicemailCleanupService( 4469): Cleaning up data for package: com.test.thalitest
I/ActivityManager(  821): Start proc 4504:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
I/art     ( 1801): Explicit concurrent mark sweep GC freed 17017(992KB) AllocSpace objects, 8(128KB) LOS objects, 37% free, 26MB/42MB, paused 1.104ms total 25.096ms
E/DataBuffer( 1801): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2ad1a021)
I/ActivityManager(  821): Start proc 4526:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
I/art     ( 4453): System.exit called, status: 0
I/AndroidRuntime( 4453): VM exiting with result code 0.
D/WifiService(  821): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@e36fdc2}
E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=49.25 rxSuccessRate=54.75 targetRoamBSSID=any RSSI=-49
D/Launcher.Workspace( 1369): 11683562 - stripEmptyScreens()
D/Launcher.Workspace( 1369): 11683562 - stripEmptyScreens()
W/ContextImpl( 4526): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2609 
E/NetworkScheduler.SchedulerReceiver( 1287): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1287): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=87.12 rxSuccessRate=192.88 targetRoamBSSID=any RSSI=-49
D/PackageBroadcastService( 1774): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1774): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1774): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1774): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 1774): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1774): Module APK com.google.android.play.games already loaded
I/LocationSettingsChecker( 1774): Removing dialog suppression flag for package com.test.thalitest
I/ActivityManager(  821): Killing 3425:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1702352147
E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
D/GOOGLEHELP_CompatibleDatabase( 1774): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1774): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1774): 0 metrics were deleted when clearing package com.test.thalitest.
D/GOOGLEHELP_CompatibleDatabase( 1774): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/GOOGLEHELP_CompatibleDatabase( 1774): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1774): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/GOOGLEHELP_CompatibleDatabase( 1774): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/GOOGLEHELP_CompatibleDatabase( 1774): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1774): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/GOOGLEHELP_CompatibleDatabase( 1774): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/GOOGLEHELP_CompatibleDatabase( 1774): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/GOOGLEHELP_CompatibleDatabase( 1774): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/GOOGLEHELP_CompatibleDatabase( 1774): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/kickstart(  871): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
I/kickstart(  871): STATUS: Wrote to /sys/power/wake_lock
E/kickstart(  871): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1
I/kickstart(  871): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1' for writing
I/UpdateIcingCorporaServi( 1528): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
E/SQLiteLog( 1528): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
I/ActivityManager(  821): Start proc 4559:com.google.android.gms.wearable/u0a11 for service com.google.android.gms/.wearable.service.WearableControlService
E/SQLiteDatabase( 1774): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
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
E/SQLiteDatabase( 1774): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 1774): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1774): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 1774): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteDatabase( 1774): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1774): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1774): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 1774): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 1774): Couldn't open phenotype.db for writing (will try read-only):
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
E/SQLiteOpenHelper( 1774): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 1774): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 1774): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 1774): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteOpenHelper( 1774): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 1774): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 1774): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteOpenHelper( 1774): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/SQLiteOpenHelper( 1774): Opened phenotype.db in read-only mode
I/ActivityManager(  821): Start proc 4576:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
E/SharedPreferencesImpl( 1528): Couldn't create directory for SharedPreferences file /data/data/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml
--------- beginning of crash
E/AndroidRuntime( 1528): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 1528): Process: com.google.android.googlequicksearchbox:search, PID: 1528
E/AndroidRuntime( 1528): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1528): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 1528): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/AndroidRuntime( 1528): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 1528): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 1528): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/AndroidRuntime( 1528): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/AndroidRuntime( 1528): 	at com.google.android.apps.gsa.extradex.icingsync.b.a(ApplicationsHelperImpl.java:85)
E/AndroidRuntime( 1528): 	at com.google.android.search.core.icingsync.d.i(InternalIcingCorporaProvider.java:623)
E/AndroidRuntime( 1528): 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:298)
E/AndroidRuntime( 1528): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:328)
E/AndroidRuntime( 1528): 	at android.content.ContentResolver.update(ContentResolver.java:1333)
E/AndroidRuntime( 1528): 	at com.google.android.search.core.icingsync.e.JA(UpdateIcingCorporaService.java:408)
E/AndroidRuntime( 1528): 	at com.google.android.search.core.icingsync.g.aTY(UpdateIcingCorporaService.java:347)
E/AndroidRuntime( 1528): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:320)
E/AndroidRuntime( 1528): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.ba(UpdateIcingCorporaService.java:215)
E/AndroidRuntime( 1528): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:201)
E/AndroidRuntime( 1528): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 1528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1528): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 1528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/HeadsetStateMachine( 2149): Disconnected process message: 10, size: 0
W/Launcher( 1369): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@97a95f4 new=com.google.android.velvet.VelvetApplication@97a95f4
E/SQLiteLog( 1369): (3850) statement aborts at 24: [DELETE FROM shortcut_and_widget_previews WHERE name LIKE ? OR name LIKE ?] disk I/O error
W/ResourcesManager( 4559): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4559): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
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
D/OpenGLRenderer(  821): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
D/Atlas   (  821): Validating map...
I/MultiDex( 4559): VM with version 2.1.0 has multidex support
I/MultiDex( 4559): install
I/MultiDex( 4559): VM has multidex support, MultiDex support library is disabled.
I/OpenGLRenderer(  821): Initialized EGL, version 1.4
I/ActivityManager(  821): Start proc 4596:com.google.android.apps.docs/u0a46 for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
D/OpenGLRenderer(  821): Enabling debug mode 0
I/ConfigFetchService( 1774): onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
E/SharedPreferencesImpl( 1774): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/config_removals.xml to backup file /data/data/com.google.android.gms/shared_prefs/config_removals.xml.bak
I/ConfigFetchService( 1774): service connected
W/BaseAppContext( 1774): Using Auth Proxy for data requests.
V/JNIHelp ( 4559): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
I/Icing   ( 1774): doRemovePackageData com.test.thalitest
I/PeopleContactsSync( 1774): CP2 sync disabled
W/BaseAppContext( 1774): Using Auth Proxy for data requests.
E/SQLiteDatabase( 1774): Failed to open database '/data/data/com.google.android.gms/databases/app_state.db'.
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
E/SQLiteDatabase( 1774): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 1774): 	at com.google.android.gms.common.i.a.delete(SourceFile:272)
E/SQLiteDatabase( 1774): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
E/SQLiteDatabase( 1774): 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
E/SQLiteDatabase( 1774): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
E/SQLiteDatabase( 1774): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
E/SQLiteDatabase( 1774): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/SQLiteDatabase( 1774): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 1774): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 1774): 	at java.lang.Thread.run(Thread.java:818)
E/ClearPendingStateOp( 1774): Runtime exception while performing operation
E/ClearPendingStateOp( 1774): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/ClearPendingStateOp( 1774): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/ClearPendingStateOp( 1774): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/ClearPendingStateOp( 1774): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/ClearPendingStateOp( 1774): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/ClearPendingStateOp( 1774): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/ClearPendingStateOp( 1774): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/ClearPendingStateOp( 1774): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/ClearPendingStateOp( 1774): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/ClearPendingStateOp( 1774): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/ClearPendingStateOp( 1774): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/ClearPendingStateOp( 1774): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/ClearPendingStateOp( 1774): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/ClearPendingStateOp( 1774): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/ClearPendingStateOp( 1774): 	at com.google.android.gms.common.i.a.delete(SourceFile:272)
E/ClearPendingStateOp( 1774): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
E/ClearPendingStateOp( 1774): 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
E/ClearPendingStateOp( 1774): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
E/ClearPendingStateOp( 1774): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
E/ClearPendingStateOp( 1774): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearPendingStateOp( 1774): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearPendingStateOp( 1774): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearPendingStateOp( 1774): 	at java.lang.Thread.run(Thread.java:818)
F/ClearPendingStateOp( 1774): Killing (on development devices) due to RuntimeException
F/ClearPendingStateOp( 1774): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
F/ClearPendingStateOp( 1774): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
F/ClearPendingStateOp( 1774): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
F/ClearPendingStateOp( 1774): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
F/ClearPendingStateOp( 1774): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
F/ClearPendingStateOp( 1774): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
F/ClearPendingStateOp( 1774): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
F/ClearPendingStateOp( 1774): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
F/ClearPendingStateOp( 1774): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
F/ClearPendingStateOp( 1774): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
F/ClearPendingStateOp( 1774): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
F/ClearPendingStateOp( 1774): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
F/ClearPendingStateOp( 1774): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
F/ClearPendingStateOp( 1774): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
F/ClearPendingStateOp( 1774): 	at com.google.android.gms.common.i.a.delete(SourceFile:272)
F/ClearPendingStateOp( 1774): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
F/ClearPendingStateOp( 1774): 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
F/ClearPendingStateOp( 1774): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
F/ClearPendingStateOp( 1774): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
F/ClearPendingStateOp( 1774): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
F/ClearPendingStateOp( 1774): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
F/ClearPendingStateOp( 1774): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
F/ClearPendingStateOp( 1774): 	at java.lang.Thread.run(Thread.java:818)
I/ProviderInstaller( 4559): Installed default security provider GmsCore_OpenSSL
E/DropBoxManagerService(  821): Can't write: system_app_wtf
E/DropBoxManagerService(  821): java.io.FileNotFoundException: /data/system/dropbox/drop103.tmp: open failed: EROFS (Read-only file system)
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
W/NativeLibraryUtils( 4559): Failed to open lock file
W/NativeLibraryUtils( 4559): java.io.FileNotFoundException: /data/data/com.google.android.gms/cache/.lib.lock: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 4559): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/NativeLibraryUtils( 4559): 	at java.io.RandomAccessFile.<init>(RandomAccessFile.java:117)
W/NativeLibraryUtils( 4559): 	at com.google.android.gms.common.util.ax.a(SourceFile:305)
W/NativeLibraryUtils( 4559): 	at com.google.android.gms.common.app.a.run(SourceFile:136)
W/NativeLibraryUtils( 4559): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 4559): 	at libcore.io.Posix.open(Native Method)
W/NativeLibraryUtils( 4559): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/NativeLibraryUtils( 4559): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/NativeLibraryUtils( 4559): 	... 3 more
I/ActivityManager(  821): Killing 3405:com.android.providers.calendar/u0a3 (adj 15): empty #17
I/HotwordDetector( 1528): Closing mic
I/MicrophoneInputStream( 1528): mic_close com.google.android.apps.gsa.speech.audio.u@3a2a61
E/Search.SharedPreferencesProto( 1528): Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
D/audio_hw_primary(  358): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  358): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  358): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1528): Stopping hotword detection.
I/HotwordRecognitionRnr( 1528): Hotword detection finished
I/ActivityManager(  821): Killing 3049:com.google.android.music:main/u0a66 (adj 15): empty #17
D/GFEEDBACK_SendErrorReportOperation( 1774): Error doing instant send: java.io.IOException: failed to create reports directory
E/GFEEDBACK_SendErrorReportOperation( 1774): Error saving report: java.io.IOException: failed to create reports directory
E/native  ( 1230): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1230): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1230): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1230): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1230): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1230): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1230): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1230): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
I/GAv4    ( 4596): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4596):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4596):   adb logcat -s GAv4
W/GAv4    ( 4596): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 4596): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
E/SharedPreferencesImpl( 4596): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4596): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4596): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
E/SharedPreferencesImpl( 4596): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/AnalyticsTrackerProxyImpl( 4596): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
E/SQLiteDatabase( 4596): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 4596): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4596): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4596): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4596): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4596): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4596): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4596): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4596): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4596): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4596): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4596): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4596): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4596): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4596): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4596): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 4596): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 4596): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 4596): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 4596): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 4596): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 4596): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4596): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4596): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4596): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4596): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 4596): 	at gir$c.run(Unknown Source)
E/GAv4    ( 4596): Opening the database failed, dropping the table and recreating it
E/SharedPreferencesImpl( 4596): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SQLiteDatabase( 4596): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4596): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4596): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4596): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4596): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4596): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4596): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4596): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4596): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4596): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4596): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4596): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4596): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4596): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4596): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4596): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 4596): 	at ael.a(PG:1521)
E/SQLiteDatabase( 4596): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 4596): 	at aen.run(PG:536)
E/SQLiteDatabase( 4596): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 4596): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4596): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4596): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4596): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4596): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4596): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4596): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4596): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4596): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4596): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4596): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4596): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4596): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4596): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4596): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 4596): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 4596): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 4596): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 4596): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 4596): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 4596): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4596): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4596): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4596): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4596): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 4596): 	at gir$c.run(Unknown Source)
E/GAv4    ( 4596): Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 4596): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4596): Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/GAv4    ( 4596): Job execution failed: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 4596): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4596): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4596): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SQLiteDatabase( 4596): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4596): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4596): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4596): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4596): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4596): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4596): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4596): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4596): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4596): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4596): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4596): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4596): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4596): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4596): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4596): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 4596): 	at ael.a(PG:1521)
E/SQLiteDatabase( 4596): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 4596): 	at aej.c(PG:139)
E/SQLiteDatabase( 4596): 	at aej.b(PG:398)
E/SQLiteDatabase( 4596): 	at agf.f(PG:417)
E/SQLiteDatabase( 4596): 	at oe.run(PG:1112)
E/SQLiteDatabase( 4596): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4596): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4596): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4596): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4596): 	at java.lang.Thread.run(Thread.java:818)
E/AbstractDatabaseInstance( 4596): Failed to delete from CachedSearch133
E/AbstractDatabaseInstance( 4596): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AbstractDatabaseInstance( 4596): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AbstractDatabaseInstance( 4596): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AbstractDatabaseInstance( 4596): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AbstractDatabaseInstance( 4596): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AbstractDatabaseInstance( 4596): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AbstractDatabaseInstance( 4596): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AbstractDatabaseInstance( 4596): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AbstractDatabaseInstance( 4596): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AbstractDatabaseInstance( 4596): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AbstractDatabaseInstance( 4596): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AbstractDatabaseInstance( 4596): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AbstractDatabaseInstance( 4596): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AbstractDatabaseInstance( 4596): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AbstractDatabaseInstance( 4596): 	at aev.getWritableDatabase(PG:238)
E/AbstractDatabaseInstance( 4596): 	at ael.a(PG:1521)
E/AbstractDatabaseInstance( 4596): 	at hix$a.a(PG:125)
E/AbstractDatabaseInstance( 4596): 	at aej.c(PG:139)
E/AbstractDatabaseInstance( 4596): 	at aej.b(PG:398)
E/AbstractDatabaseInstance( 4596): 	at agf.f(PG:417)
E/AbstractDatabaseInstance( 4596): 	at oe.run(PG:1112)
E/AbstractDatabaseInstance( 4596): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/AbstractDatabaseInstance( 4596): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AbstractDatabaseInstance( 4596): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AbstractDatabaseInstance( 4596): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AbstractDatabaseInstance( 4596): 	at java.lang.Thread.run(Thread.java:818)
E/SharedPreferencesImpl( 4596): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4596): Job execution failed: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4596): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4596): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4596): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4596): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4596): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4596): Failed to commit local dispatch transaction: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4596): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4596): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4596): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4596): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4596): Sync local dispatch failed: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4596): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4596): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4596): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4596): syncDispatchLocalHits failed: java.util.concurrent.ExecutionException: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4596): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/CAKEMIX_CRASHED( 4596): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/CAKEMIX_CRASHED( 4596): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/CAKEMIX_CRASHED( 4596): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/CAKEMIX_CRASHED( 4596): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/CAKEMIX_CRASHED( 4596): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/CAKEMIX_CRASHED( 4596): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/CAKEMIX_CRASHED( 4596): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/CAKEMIX_CRASHED( 4596): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/CAKEMIX_CRASHED( 4596): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/CAKEMIX_CRASHED( 4596): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/CAKEMIX_CRASHED( 4596): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/CAKEMIX_CRASHED( 4596): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/CAKEMIX_CRASHED( 4596): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/CAKEMIX_CRASHED( 4596): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/CAKEMIX_CRASHED( 4596): 	at aev.getWritableDatabase(PG:238)
E/CAKEMIX_CRASHED( 4596): 	at ael.a(PG:1521)
E/CAKEMIX_CRASHED( 4596): 	at hix$a.a(PG:125)
E/CAKEMIX_CRASHED( 4596): 	at aen.run(PG:536)
W/ResourcesManager( 4596): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4596): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
V/JNIHelp ( 4596): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
I/ActivityManager(  821): Start proc 4640:com.android.documentsui/u0a45 for broadcast com.android.documentsui/.PackageReceiver
I/ActivityManager(  821): START u0 {act=android.intent.action.BUG_REPORT flg=0x10000000 cmp=com.google.android.apps.docs/.app.ErrorNotificationActivity (has extras)} from uid 10046 on display 0
V/WindowManager(  821): addAppToken: AppWindowToken{29cd8d64 token=Token{109f3af7 ActivityRecord{34e9a6f6 u0 com.google.android.apps.docs/.app.ErrorNotificationActivity t29}}} to stack=1 task=29 at 0
I/Process ( 4596): Sending signal. PID: 4596 SIG: 9
I/ActivityManager(  821): Killing 3946:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
E/kickstart(  871): ERROR: function: rx_data:267 Timeout Occured, No response or command came from the target!
I/kickstart(  871): WARNING: function: sahara_start:892 Retrying memory read request
E/lowmemorykiller(  257): Error opening /proc/4596/oom_score_adj; errno=2
W/ActivityManager(  821): Exception when starting activity com.google.android.apps.docs/.app.ErrorNotificationActivity
W/ActivityManager(  821): android.os.DeadObjectException
W/ActivityManager(  821): 	at android.os.BinderProxy.transactNative(Native Method)
W/ActivityManager(  821): 	at android.os.BinderProxy.transact(Binder.java:496)
W/ActivityManager(  821): 	at android.app.ApplicationThreadProxy.scheduleLaunchActivity(ApplicationThreadNative.java:797)
W/ActivityManager(  821): 	at com.android.server.am.ActivityStackSupervisor.realStartActivityLocked(ActivityStackSupervisor.java:1181)
W/ActivityManager(  821): 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1281)
W/ActivityManager(  821): 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:1891)
W/ActivityManager(  821): 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1455)
W/ActivityManager(  821): 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2473)
W/ActivityManager(  821): 	at com.android.server.am.ActivityStack.completePauseLocked(ActivityStack.java:998)
W/ActivityManager(  821): 	at com.android.server.am.ActivityStack.activityPausedLocked(ActivityStack.java:896)
W/ActivityManager(  821): 	at com.android.server.am.ActivityManagerService.activityPaused(ActivityManagerService.java:6311)
W/ActivityManager(  821): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:512)
W/ActivityManager(  821): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2208)
W/ActivityManager(  821): 	at android.os.Binder.execTransact(Binder.java:446)
I/ActivityManager(  821): Start proc 4657:com.google.android.apps.docs/u0a46 for activity com.google.android.apps.docs/.app.ErrorNotificationActivity
W/ActivityManager(  821): Spurious death for ProcessRecord{57f3659 4657:com.google.android.apps.docs/u0a46}, curProc for 4596: null
W/OpenGLRenderer( 1369): Incorrectly called buildLayer on View: ew, destroying layer...
E/SQLiteDatabase( 4640): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 4640): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4640): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4640): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4640): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4640): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4640): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4640): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4640): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4640): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4640): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4640): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4640): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4640): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4640): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4640): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/SQLiteDatabase( 4640): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/SQLiteDatabase( 4640): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:370)
E/SQLiteDatabase( 4640): 	at android.content.ContentResolver.call(ContentResolver.java:1372)
E/SQLiteDatabase( 4640): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/SQLiteDatabase( 4640): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2609)
E/SQLiteDatabase( 4640): 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
E/SQLiteDatabase( 4640): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1380)
E/SQLiteDatabase( 4640): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4640): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 4640): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
E/SQLiteDatabase( 4640): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 4640): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 4640): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
E/SQLiteDatabase( 4640): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/AndroidRuntime( 4640): Shutting down VM
E/AndroidRuntime( 4640): FATAL EXCEPTION: main
E/AndroidRuntime( 4640): Process: com.android.documentsui, PID: 4640
E/AndroidRuntime( 4640): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4640): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2616)
E/AndroidRuntime( 4640): 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
E/AndroidRuntime( 4640): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1380)
E/AndroidRuntime( 4640): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4640): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 4640): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
E/AndroidRuntime( 4640): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 4640): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 4640): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
E/AndroidRuntime( 4640): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
E/AndroidRuntime( 4640): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4640): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4640): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 4640): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 4640): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4640): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4640): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4640): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDat,abase.java:806)
E/AndroidRuntime( 4640): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AndroidRuntime( 4640): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 4640): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AndroidRuntime( 4640): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 4640): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 4640): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 4640): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/AndroidRuntime( 4640): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/AndroidRuntime( 4640): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:370)
E/AndroidRuntime( 4640): 	at android.content.ContentResolver.call(ContentResolver.java:1372)
E/AndroidRuntime( 4640): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/AndroidRuntime( 4640): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2609)
E/AndroidRuntime( 4640): 	... 9 more
D/GCM     ( 1287): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
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
I/ActivityManager(  821): Start proc 4678:com.android.externalstorage/u0a10 for content provider com.android.externalstorage/.ExternalStorageProvider
D/AuthorizationBluetoothService( 1287): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GmsCoreStatsServiceLauncher( 1774): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }

```
