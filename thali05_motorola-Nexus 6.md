#### Test 575312430087a60_thali05_motorola-Nexus 6 Logs


```
--------- beginning of main
I/art     (  819): Explicit concurrent mark sweep GC freed 29477(1605KB) AllocSpace objects, 5(174KB) LOS objects, 32% free, 33MB/49MB, paused 2.828ms total 105.457ms
,--------- beginning of system
I/ActivityManager(  819): Killing 3148:com.google.android.apps.messaging/u0a75 (adj 15): empty #17
D/AndroidRuntime( 3528): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 3528): CheckJNI is OFF
D/AndroidRuntime( 3528): Calling main entry com.android.commands.am.Am
I/ActivityManager(  819): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/WindowManager(  819): addAppToken: AppWindowToken{35a18b17 token=Token{1580a396 ActivityRecord{39c8e2b1 u0 com.test.thalitest/.MainActivity t28}}} to stack=1 task=28 at 0
V/WindowManager(  819): Adding window Window{1abe3370 u0 Starting com.test.thalitest} at 2 of 7 (after Window{1700ef9 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
D/AndroidRuntime( 3528): Shutting down VM
I/HotwordDetector( 1515): Closing mic
I/MicrophoneInputStream( 1515): mic_close com.google.android.apps.gsa.speech.audio.u@2f4d5534
I/ActivityManager(  819): Start proc 3542:com.test.thalitest/u0a265 for activity com.test.thalitest/.MainActivity
D/audio_hw_primary(  357): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  357): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  357): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1515): Stopping hotword detection.
I/HotwordRecognitionRnr( 1515): Hotword detection finished
I/ActivityManager(  819): Killing 3184:com.google.android.apps.photos/u0a71 (adj 15): empty #17
E/LocSvc_IzatApiV02(  819): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1722508563
E/LocSvc_IzatApiV02(  819): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
I/WebViewFactory( 3542): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3542): Time to load native libraries: 2 ms (timestamps 8745-8747)
I/LibraryLoader( 3542): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3542): Binding Chromium to main looper Looper (main, tid 1) {1a377fd8}
I/LibraryLoader( 3542): Expected native library version number "",actual native library version number ""
I/chromium( 3542): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3542): Initializing chromium process, singleProcess=true,
W/art     ( 3542): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3542): ApplicationContext is null in ApplicationStatus
,W/chromium( 3542): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3542): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3542): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3542): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/BluetoothManagerService(  819): Message: 20
,D/BluetoothManagerService(  819): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@adfac59:true
,W/art     ( 3542): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3542): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3542): CordovaWebView is running on device made by: motorola
,V/GLSActivity( 1281): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/art     ( 3542): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3542): Attempt to remove local handle scope entry from IRT, ignoring
,I/GLSUser ( 1281): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1281): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1281): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1281): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1281): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/OpenGLRenderer( 3542): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,D/Finsky  ( 3024): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3024): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3024): [1] 5.onFinished: Scheduling replication attempt 1.
D/Atlas   ( 3542): Validating map...
,V/WindowManager(  819): Adding window Window{288b2832 u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{1abe3370 u0 Starting com.test.thalitest})
,W/chromium( 3542): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/ActivityManager(  819): Killing 2982:com.google.android.apps.fitness/u0a51 (adj 15): empty #17
,I/OpenGLRenderer( 3542): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3542): Enabling debug mode 0
,I/Keyboard.Facilitator( 1233): onFinishInput()
,I/ActivityManager(  819): Displayed com.test.thalitest/.MainActivity: +645ms
,W/BindingManager( 3542): Cannot call determinedVisibility() - never saw a connection for the pid: 3542
,D/JsMessageQueue( 3542): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3542): JniHelper::setJavaVM(0xb489d200), pthread_self() = -1576396416
,I/chromium( 3542): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 3542): Initializing JXcore engine
W/jxcore-log( 3542): JXcore engine is ready
,W/Thread-392( 3594): type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[12987]" dev="sockfs" ino=12987 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/Thread-392( 3594): type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-392( 3594): type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[11589]" dev="sockfs" ino=11589 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/jxcore-log( 3542): Starting JXcore engine
W/Thread-392( 3594): type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[23602]" dev="sockfs" ino=23602 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 3542): Platform android
W/jxcore-log( 3542): 
W/jxcore-log( 3542): Process ARCH arm
W/jxcore-log( 3542): 
,I/jxcore-log( 3542): JXcore Cordova bridge is ready!
I/jxcore-log( 3542): 
W/jxcore-log( 3542): JXcore engine is started
,E/WifiStateMachine(  819): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.03 rxSuccessRate=2.50 targetRoamBSSID=any RSSI=-49
,E/WifiStateMachine(  819): WifiStateMachine starting scan for "NG7005g"WPA_PSK with 2412,5220
,I/jxcore-log( 3542): Toggling radios to true
I/jxcore-log( 3542): 
,D/BluetoothAdapter( 3542): enable(): BT is already enabled..!
,D/WifiService(  819): New client listening to asynchronous messages
,D/WifiService(  819): setWifiEnabled: true pid=3542, uid=10265
E/WifiService(  819): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3542): Radios toggled,
I/jxcore-log( 3542): 
,I/jxcore-log( 3542): My device name is: motorola-Nexus 6
I/jxcore-log( 3542): 
,I/wpa_supplicant( 1128): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  819): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  819): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  353): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1281): Read error: ssl=0xb4888400: I/O error during system call, Connection timed out
V/NativeCrypto( 1281): SSL shutdown failed: ssl=0xb4888400: I/O error during system call, Broken pipe
,D/ConnectivityService(  819): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  819): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,D/ConnectivityService(  819): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10011
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  819): ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  819): DefaultState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  819): Forcing reevaluation
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  819): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  819): Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
,E/WifiStateMachine(  819): Start Disconnecting Watchdog 1
,E/WifiStateMachine(  819): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  819): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
,D/CommandListener(  353): Clearing all IP addresses on wlan0
,D/ConnectivityService(  819): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/WifiNetworkAgent(  819): NetworkAgent: NetworkAgent channel lost
D/ConnectivityManager.CallbackHandler( 1064): CM callback handler got msg 524292
E/WifiStateMachine(  819): CMD_AUTO_CONNECT sup state CompletedState my state DisconnectedState nid=0 roam=3
E/WifiStateMachine(  819): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=0
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  819): OfflineState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  819): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  819): Disconnected - quitting
D/CSLegacyTypeTracker(  819): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  819): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  819): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering(  819): MasterInitialState.processMessage what=3
D/ConnectivityService(  819): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  819): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  819): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService(  819): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/ConnectivityService(  819): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
,D/Tethering(  819): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 3258): type=WIFI subType= reason=null isConnected=false
,D/PhoneInterfaceManager( 1355): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
V/MusicLeanback( 3258): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
E/PhoneInterfaceManager( 1355): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,E/WifiConfigStore(  819): Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiConfigStore(  819): will read network variables netId=0
,E/WifiStateMachine(  819): CMD_AUTO_CONNECT did save config ->  nid=0
,E/WifiConfigStore(  819): will read network variables netId=0
D/TelephonyManager(  819): getDataEnabled: retVal=false
I/wpa_supplicant( 1128): wlan0: Trying to associate with SSID 'NG7005g'
,I/ActivityManager(  819): Start proc 3602:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.steen.receiver.ConnectivityChangeReceiver
,E/GpsLocationProvider(  819): No APN found to select.
,D/PhoneInterfaceManager( 1355): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1355): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
D/TelephonyManager(  819): getDataEnabled: retVal=false
,E/GpsLocationProvider(  819): No APN found to select.
,I/ActivityManager(  819): Start proc 3629:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
I/ActivityManager(  819): Killing 3229:com.android.settings/1000 (adj 15): empty #17
,D/SprintDMReceiver( 3629): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3629): simOperator:  IMSI: null
,D/SprintDMReceiver( 3629): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1774): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1774): onCreate
,D/SystemUpdateService( 1774): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1774): active receiver: enabled
,I/SystemUpdateService( 1774): showing system update notification
,I/iu.Environment( 1774): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1774): num queued entries: 0
I/iu.UploadsManager( 1774): num updated entries: 0
,I/iu.SyncManager( 1774): NEXT; no task
,I/wpa_supplicant( 1128): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/ValidateNoPeople(  819): skipping global notification
,D/ChimeraCfgMgr( 1774): Loading module com.google.android.gms.kids from APK com.google.android.gms
,V/SystemUpdateService( 1774): retry (wakeup: false) in 3599939 ms
,D/SystemUpdateService( 1774): onDestroy
,I/wpa_supplicant( 1128): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 1128): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=0 id_str=]
,I/ActivityManager(  819): Start proc 3649:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,I/Babel   ( 2950): connection state changed from UNKNOWN to DISCONNECTED
,I/ActivityManager(  819): Killing 2728:com.google.android.apps.maps/u0a65 (adj 15): empty #17
,I/art     (  368): Explicit concurrent mark sweep GC freed 703(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 338us total 18.057ms
,D/ConnectivityService(  819): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} }
E/WifiConfigStore(  819): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  819): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,I/art     (  368): Explicit concurrent mark sweep GC freed 8(256B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 226us total 14.226ms
,I/art     (  368): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 224us total 9.648ms
,E/WifiConfigStore(  819): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  353): Setting iface cfg
,E/WifiStateMachine(  819): Start Dhcp Watchdog 2
,E/WifiStateMachine(  819):  WifiLinkLayerStats: 
E/WifiStateMachine(  819):  my bss beacon rx: 225
E/WifiStateMachine(  819):  RSSI mgmt: -49
E/WifiStateMachine(  819):  BE :  rx=148 tx=122 lost=0 retries=0
E/WifiStateMachine(  819):  BK :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  819):  VI :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  819):  VO :  rx=4 tx=0 lost=0 retries=0
E/WifiStateMachine(  819):  on_time : 7838 tx_time=141 rx_time=360 scan_time=0
,D/ConnectivityService(  819): updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,I/GAv4    ( 3649): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3649):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3649):   adb logcat -s GAv4
,W/GAv4    ( 3649): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,E/native  (  819): do suspend false,
,W/GAv4    ( 3649): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,E/WifiStateMachine(  819): scanCount==0 - aborting
,W/GAv4    ( 3649): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 3649): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3649): Time to load native libraries: 1 ms (timestamps 2490-2491)
I/LibraryLoader( 3649): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3649): Binding Chromium to main looper Looper (main, tid 1) {2550cb5f}
I/LibraryLoader( 3649): Expected native library version number "",actual native library version number ""
I/chromium( 3649): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3649): Initializing chromium process, singleProcess=true
W/art     ( 3649): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3649): ApplicationContext is null in ApplicationStatus
,W/chromium( 3649): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3649): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3649): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3649): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,I/dhcpcd  ( 3694): version 5.5.6 starting
,W/AudioManagerAndroid( 3649): Requires BLUETOOTH permission
I/NSApplication( 3649): Starting up...
,I/dhcpcd  ( 3694): wlan0: rebinding lease of 192.168.1.122
,I/ActivityManager(  819): Start proc 3713:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
I/ActivityManager(  819): Killing 3339:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,I/ActivityManager(  819): Start proc 3733:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,I/ActivityManager(  819): Killing 3360:com.android.musicfx/u0a18 (adj 15): empty #17
,I/ActivityManager(  819): Killing 3412:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,V/MusicLeanback( 3258): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/SprintDMReceiver( 3629): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3629): simOperator:  IMSI: null
D/SprintDMReceiver( 3629): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1774): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1774): onCreate
,D/SystemUpdateService( 1774): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1774): active receiver: enabled
,I/SystemUpdateService( 1774): showing system update notification
,I/ValidateNoPeople(  819): skipping global notification
,V/SystemUpdateService( 1774): retry (wakeup: false) in 3599984 ms
,D/ChimeraCfgMgr( 1774): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/SystemUpdateService( 1774): onDestroy
,D/Finsky  ( 3024): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/GLSActivity( 1281): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1281): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1281): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1281): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1281): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1281): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  819): Explicit concurrent mark sweep GC freed 40680(2017KB) AllocSpace objects, 6(190KB) LOS objects, 32% free, 33MB/49MB, paused 1.122ms total 49.481ms
,W/Finsky  ( 3024): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1281): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1281): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1281): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1281): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1281): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1281): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1281): Explicit concurrent mark sweep GC freed 22574(1164KB) AllocSpace objects, 3(330KB) LOS objects, 37% free, 26MB/42MB, paused 871us total 19.923ms
,V/GLSActivity( 1281): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1281): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1281): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1281): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1281): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1281): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 3024): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/dhcpcd  ( 3694): wlan0: acknowledged 192.168.1.122 from 192.168.1.1
,I/dhcpcd  ( 3694): wlan0: leased 192.168.1.122 for 86400 seconds
,V/GLSActivity( 1281): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1281): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1281): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1281): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1281): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1281): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 3024): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
D/Finsky  ( 3024): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 3024): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3024): [1] DailyHygiene.reschedule: Scheduling new run in 9 minutes (failures=1)
,D/DeviceConnectionService( 1799): client connected with version: 7571000
,D/ConnectivityService(  819): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  819): Adding iface wlan0 to network 101,
E/WifiStateMachine(  819): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  819): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  819): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  819): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  819): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  819): Setting Dns servers for network 101 to [/192.168.1.1]
,D/ConnectivityService(  819): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  819): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  819): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  819):    accepting network in place of null
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  819): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  819): Connected
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  819): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  819): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
D/ConnectivityService(  819): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} }
,D/ConnectivityService(  819): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101],
,D/ConnectivityManager.CallbackHandler( 1064): CM callback handler got msg 524290
D/CSLegacyTypeTracker(  819): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  819): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  819): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  819): MasterInitialState.processMessage what=3,
,I/NetworkMonitor( 3258): type=WIFI subType= reason=null isConnected=true
,D/PhoneInterfaceManager( 1355): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
V/MusicLeanback( 3258): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,E/PhoneInterfaceManager( 1355): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  819): getDataEnabled: retVal=false
,D/SprintDMReceiver( 3629): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,E/GpsLocationProvider(  819): No APN found to select.
,D/SprintDMHelper( 3629): simOperator:  IMSI: null
D/SprintDMReceiver( 3629): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1774): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1774): onCreate
,D/SystemUpdateService( 1774): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1774): active receiver: enabled
,I/SystemUpdateService( 1774): showing system update notification
,I/ActivityManager(  819): Start proc 3797:com.google.android.keep/u0a79 for service com.google.android.keep/.syncadapter.KeepSyncAdapterService
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  819): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 29 Jan 2016 18:25:36 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454091936636], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454091936609]}
,I/ValidateNoPeople(  819): skipping global notification
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  819): Validated
,D/ConnectivityService(  819): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/ConnectivityService(  819): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  819): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  819): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  819): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  819): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1064): CM callback handler got msg 524290
,V/SystemUpdateService( 1774): retry (wakeup: false) in 3599923 ms
,I/iu.Environment( 1774): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,D/SystemUpdateService( 1774): onDestroy
,D/ChimeraCfgMgr( 1774): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/iu.UploadsManager( 1774): num queued entries: 0
,I/iu.UploadsManager( 1774): num updated entries: 0
,I/iu.SyncManager( 1774): NEXT; no task
,D/ChimeraCfgMgr( 1774): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/GLSUser ( 1281): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1281): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1281): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1281): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1281): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,I/Babel   ( 2950): connection state changed from DISCONNECTED to CONNECTED
,I/GLSUser ( 1281): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1281): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1281): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1281): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1281): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/Herrevad( 1774): NQAS connected
,E/HttpOperation( 3454): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3454): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3454): 	at jdm.a(PG:82)
E/HttpOperation( 3454): 	at jcs.o(PG:406)
E/HttpOperation( 3454): 	at jcn.a(PG:1379)
E/HttpOperation( 3454): 	at jcs.i(PG:143)
E/HttpOperation( 3454): 	at blb.a(PG:3937)
E/HttpOperation( 3454): 	at czp.a(PG:18188)
E/HttpOperation( 3454): 	at czp.a(PG:9081)
E/HttpOperation( 3454): 	at czq.run(PG:1686)
E/HttpOperation( 3454): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3454): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3454): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3454): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3454): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3454): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3454): 	at jdj.a(PG:4091)
E/HttpOperation( 3454): 	at jdj.a(PG:1125)
E/HttpOperation( 3454): 	at jdm.a(PG:77)
E/HttpOperation( 3454): 	... 12 more
E/HttpOperation( 3454): Caused by: faj: BadAuthentication
E/HttpOperation( 3454): 	at fal.a(PG:38)
E/HttpOperation( 3454): 	at jdj.a(PG:4089)
E/HttpOperation( 3454): 	... 14 more
,D/GCM     ( 1281): Connected
,I/GLSUser ( 1281): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1281): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1281): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1281): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1281): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/GCM     ( 1281): Message class com.google.f.a.a.p
,E/HttpOperation( 3454): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3454): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3454): 	at jdm.a(PG:82)
E/HttpOperation( 3454): 	at jcs.o(PG:406)
E/HttpOperation( 3454): 	at jcn.a(PG:1379)
E/HttpOperation( 3454): 	at jcs.i(PG:143)
E/HttpOperation( 3454): 	at hec.a(PG:42)
E/HttpOperation( 3454): 	at hee.a(PG:102)
E/HttpOperation( 3454): 	at czr.a(PG:65)
E/HttpOperation( 3454): 	at kka.a(PG:108)
E/HttpOperation( 3454): 	at czp.a(PG:19176)
E/HttpOperation( 3454): 	at czp.a(PG:9081)
E/HttpOperation( 3454): 	at czq.run(PG:1686)
E/HttpOperation( 3454): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3454): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3454): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3454): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3454): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3454): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3454): 	at jdj.a(PG:4091)
E/HttpOperation( 3454): 	at jdj.a(PG:1125)
E/HttpOperation( 3454): 	at jdm.a(PG:77)
E/HttpOperation( 3454): 	... 15 more
E/HttpOperation( 3454): Caused by: faj: BadAuthentication
E/HttpOperation( 3454): 	at fal.a(PG:38)
E/HttpOperation( 3454): 	at jdj.a(PG:4089)
E/HttpOperation( 3454): 	... 17 more
E/ExperimentLoader( 3454): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3454): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3454): 	at jdm.a(PG:82)
E/ExperimentLoader( 3454): 	at jcs.o(PG:406)
E/ExperimentLoader( 3454): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3454): 	at jcs.i(PG:143)
E/ExperimentLoader( 3454): 	at hec.a(PG:42)
E/ExperimentLoader( 3454): 	at hee.a(PG:102)
E/ExperimentLoader( 3454): 	at czr.a(PG:65)
E/ExperimentLoader( 3454): 	at kka.a(PG:108)
E/ExperimentLoader( 3454): 	at czp.a(PG:19176)
E/ExperimentLoader( 3454): 	at czp.a(PG:9081)
E/ExperimentLoader( 3454): 	at czq.run(PG:1686)
E/ExperimentLoader( 3454): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3454): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3454): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3454): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3454): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3454): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3454): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3454): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3454): 	at jdm.a(PG:77)
E/ExperimentLoader( 3454): 	... 15 more
E/ExperimentLoader( 3454): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3454): 	at fal.a(PG:38)
E/ExperimentLoader( 3454): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3454): 	... 17 more
,V/KeepSync( 3797): Connecting to GoogleApiClient
,I/GLSUser ( 1281): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1281): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1281): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1281): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1281): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 79456, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
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
,V/KeepSync( 3797): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3797): (284) automatic index on blob_node(is_deleted),
E/SQLiteLog( 3797): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3797): (284) automatic index on blob_node(is_deleted)
,I/ActivityManager(  819): Start proc 3840:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,I/GLSUser ( 1281): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1281): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1281): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1281): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1281): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1281): Explicit concurrent mark sweep GC freed 21888(1257KB) AllocSpace objects, 3(330KB) LOS objects, 37% free, 26MB/42MB, paused 1.055ms total 20.917ms
,E/KeepSync( 3797): IOException
E/KeepSync( 3797): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3797): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3797): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3797): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3797): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3797): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3797): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3797): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3797): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3797): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3797): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3797): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3797): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3797): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3797): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3797): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3797): 	... 10 more
,W/KeepSync( 3797): Sync result 2
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 79123, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,W/GAV2    ( 3840): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/BooksApp( 3840): Created application version: 3.6.8 (30608)
,I/art     (  819): Explicit concurrent mark sweep GC freed 32149(1435KB) AllocSpace objects, 3(48KB) LOS objects, 32% free, 33MB/49MB, paused 1.229ms total 54.343ms
,I/BooksSync( 3840): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3840): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1281): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1281): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1281): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1281): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1281): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService(  819): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network,
,I/GLSUser ( 1281): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1281): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1281): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1281): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1281): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3840): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3840): Soft error
E/BooksSync( 3840): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3840): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3840): Sync error
E/BooksSync( 3840): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3840): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 3840): Finished books sync
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 80070, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1],
I/ActivityManager(  819): Killing 3319:android.process.acore/u0a5 (adj 15): empty #17
,I/jxcore-log( 3542): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 3542): 
,I/jxcore-log( 3542): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 3542): 
,I/jxcore-log( 3542): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js,
I/jxcore-log( 3542): ,
,I/jxcore-log( 3542): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
I/jxcore-log( 3542): 
,I/jxcore-log( 3542): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 3542): 
,I/ActivityManager(  819): Killing 3082:com.google.android.gm/u0a78 (adj 15): empty #17
,I/GAV2    ( 3840): Thread[GAThread,5,main]: No campaign data found.
,E/WifiStateMachine(  819): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=6.09 rxSuccessRate=7.38 targetRoamBSSID=any RSSI=-49
E/WifiStateMachine(  819): WifiStateMachine L2Connected CMD_START_SCAN source -2 7, 8 -> obsolete
,I/jxcore-log( 3542): Test app app.js loaded
I/jxcore-log( 3542): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3542): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 3542): BLE advertisement is supported,
I/jxcore-log( 3542): 
,I/chromium( 3542): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51),
,D/Finsky  ( 3024): [314] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,V/GLSActivity( 1281): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1281): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1281): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1281): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1281): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1281): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3024): [314] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,E/WifiStateMachine(  819): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=1.76 rxSuccessRate=3.42 targetRoamBSSID=any RSSI=-49
E/WifiStateMachine(  819): WifiStateMachine L2Connected CMD_START_SCAN source -2 6, 8 -> obsolete
,V/GLSActivity( 1281): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1281): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1281): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1281): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1281): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1281): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3024): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3024): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3024): [1] 5.onFinished: Scheduling replication attempt 2.
,E/WifiStateMachine(  819): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=1.38 rxSuccessRate=3.21 targetRoamBSSID=any RSSI=-49
,E/WifiStateMachine(  819): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.41 rxSuccessRate=1.45 targetRoamBSSID=any RSSI=-49
,E/WifiStateMachine(  819): WifiStateMachine starting scan for "NG7005g"WPA_PSK with 2412,5220
,V/GLSActivity( 1281): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1281): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1281): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1281): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1281): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1281): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3024): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3024): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3024): [1] 5.onFinished: Scheduling replication attempt 3.
,D/HeadsetStateMachine( 2403): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2403): Disconnected process message: 10, size: 0
,V/KeepSync( 3797): Connecting to GoogleApiClient
,I/GLSUser ( 1281): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1281): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1281): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1281): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1281): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1281): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1281): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1281): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1281): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,E/HttpOperation( 3454): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3454): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3454): 	,at jdm.a(PG:82)
E/HttpOperation( 3454): 	at jcs.o(PG:406)
E/HttpOperation( 3454): 	at jcn.a(PG:1379)
E/HttpOperation( 3454): 	at jcs.i(PG:143)
E/HttpOperation( 3454): 	at blb.a(PG:3937)
E/HttpOperation( 3454): 	at czp.a(PG:18188),
E/HttpOperation( 3454): 	at czp.a(PG:9081)
E/HttpOperation( 3454): 	,at czq.run(PG:1686)
E/HttpOperation( 3454): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3454): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237),
E/HttpOperation( 3454): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3454): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3454): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3454): Caused by: android.accounts.AuthenticatorException: Recoverable error,
E/HttpOperation( 3454): 	at jdj.a(PG:4091)
E/HttpOperation( 3454): 	,at jdj.a(PG:1125)
E/HttpOperation( 3454): 	at jdm.a(PG:77)
E/HttpOperation( 3454): 	... 12 more
E/HttpOperation( 3454): Caused by: faj: BadAuthentication
E/HttpOperation( 3454): 	at fal.a(PG:38)
E/HttpOperation( 3454): 	at jdj.a(PG:4089)
E/HttpOperation( 3454): 	... 14 more
,V/GLSActivity( 1281): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1774): Handling authorization failure
E/ClientConnectionOperation( 1774): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1774): 	,at com.google.android.gms.common.service.g.run(SourceFile:178)
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
E/ClientConnectionOperation( 1774),: 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1774): 	... 7 more
,V/KeepSync( 3797): GoogleApiClient failed to connect with error code: 4
E/SQLiteLog( 3797): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3797): (284) automatic index on blob_node(is_deleted)
I/GLSUser ( 1281): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,E/SQLiteLog( 3797): (284) automatic index on blob_node(is_deleted)
I/GLSUser ( 1281): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1281): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1281): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1281): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3454): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3454): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3454): 	at jdm.a(PG:82)
E/HttpOperation( 3454): 	at jcs.o(PG:406)
E/HttpOperation( 3454): 	at jcn.a(PG:1379)
E/HttpOperation( 3454): 	at jcs.i(PG:143)
E/HttpOperation( 3454): 	at hec.a(PG:42)
E/HttpOperation( 3454): 	at hee.a(PG:102)
E/HttpOperation( 3454): 	at czr.a(PG:65)
E/HttpOperation( 3454): 	at kka.a(PG:108)
E/HttpOperation( 3454): 	at czp.a(PG:19176)
E/HttpOperation( 3454): 	at czp.a(PG:9081)
E/HttpOperation( 3454): 	at czq.run(PG:1686)
E/HttpOperation( 3454): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3454): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3454): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3454): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3454): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3454): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3454): 	at jdj.a(PG:4091)
E/HttpOperation( 3454): 	at jdj.a(PG:1125)
E/HttpOperation( 3454): 	at jdm.a(PG:77)
E/HttpOperation( 3454): 	... 15 more
E/HttpOperation( 3454): Caused by: faj: BadAuthentication
E/HttpOperation( 3454): 	at fal.a(PG:38)
E/HttpOperation( 3454): 	at jdj.a(PG:4089)
E/HttpOperation( 3454): 	... 17 more
E/ExperimentLoader( 3454): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3454): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3454): 	at jdm.a(PG:82)
E/ExperimentLoader( 3454): 	at jcs.o(PG:406)
E/ExperimentLoader( 3454): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3454): 	at jcs.i(PG:143)
E/ExperimentLoader( 3454): 	at hec.a(PG:42)
E/ExperimentLoader( 3454): 	at hee.a(PG:102)
E/ExperimentLoader( 3454): 	at czr.a(PG:65)
E/ExperimentLoader( 3454): 	at kka.a(PG:108)
E/ExperimentLoader( 3454): 	at czp.a(PG:19176)
E/ExperimentLoader( 3454): 	at czp.a(PG:9081)
E/ExperimentLoader( 3454): 	at czq.run(PG:1686)
E/ExperimentLoader( 3454): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3454): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3454): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3454): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3454): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3454): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3454): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3454): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3454): 	at jdm.a(PG:77)
E/ExperimentLoader( 3454): 	... 15 more
E/ExperimentLoader( 3454): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3454): 	at fal.a(PG:38)
E/ExperimentLoader( 3454): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3454): 	... 17 more
,I/GLSUser ( 1281): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1281): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1281): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1281): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1281): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3797): IOException
E/KeepSync( 3797): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3797): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3797): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3797): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3797): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3797): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3797): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3797): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3797): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3797): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3797): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3797): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3797): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3797): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3797): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3797): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3797): 	... 10 more
,W/KeepSync( 3797): Sync result 2
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 117657, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 117049, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/BooksSync( 3840): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3840): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1281): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1281): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1281): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1281): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1281): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  819): Explicit concurrent mark sweep GC freed 44088(2032KB) AllocSpace objects, 15(428KB) LOS objects, 31% free, 34MB/50MB, paused 1.392ms total 93.945ms
,I/GLSUser ( 1281): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1281): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1281): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1281): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1281): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3840): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3840): Soft error
E/BooksSync( 3840): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3840): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3840): Sync error
E/BooksSync( 3840): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3840): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3840): Finished books sync
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 118463, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/Keyboard.Facilitator.LanguageModelFlusher( 1233): run()
I/Keyboard.Facilitator( 1233): flushDynamicLanguageModels()
,I/ConfigService( 1281): onCreate
,I/art     ( 1281): Explicit concurrent mark sweep GC freed 31214(1895KB) AllocSpace objects, 3(330KB) LOS objects, 37% free, 27MB/43MB, paused 2.388ms total 64.871ms
,I/ConfigService( 1281): onDestroy
,E/WifiStateMachine(  819): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.44 rxSuccessRate=2.18 targetRoamBSSID=any RSSI=-49,
,V/GLSActivity( 1281): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1281): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1281): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1281): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1281): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1281): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3024): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3024): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3024): [1] 5.onFinished: Scheduling replication attempt 4.
,I/PowerManagerService(  819): Going to sleep due to screen timeout (uid 1000)...
,I/Adreno  (  819): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/PermissionCache(  258): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (382 us)
,I/DisplayManagerService(  819): Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
D/SurfaceFlinger(  258): Set power mode=0, type=0 flinger=0xb6482000
D/qdhwcomposer(  258): hwc_setPowerMode: Setting mode 0 on display: 0
V/ActivityManager(  819): Display changed displayId=0
,I/kickstart(  871): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
,I/kickstart(  871): STATUS: Wrote to /sys/power/wake_lock
,E/kickstart(  871): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1
,I/kickstart(  871): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1' for writing
,I/qdhwcomposer(  258): handle_blank_event: dpy:0 panel power state: 0
,D/qdhwcomposer(  258): hwc_setPowerMode: Done setting mode 0 on display 0
,D/SurfaceControl(  819): Excessive delay in setPowerMode(): 259ms
,I/DreamManagerService(  819): Entering dreamland.
,I/PowerManagerService(  819): Dozing...
,I/DreamController(  819): Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,D/audio_hw_primary(  357): adev_set_parameters: enter: screen_state=on
,D/mot_vr_audio_hw(  357): adev_set_parameters: screen_state=on
,E/WifiStateMachine(  819): cancelDelayedScan -> 12
,E/native  (  819): do suspend false
,D/audio_hw_primary(  357): adev_set_parameters: enter: screen_state=off
D/mot_vr_audio_hw(  357): adev_set_parameters: screen_state=off
I/Keyboard.Facilitator( 1233): onFinishInput()
,E/WifiStateMachine(  819): cancelDelayedScan -> 14,
,E/native  (  819): do suspend true,
,E/WifiStateMachine(  819): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-49
E/WifiStateMachine(  819): WifiStateMachine L2Connected CMD_START_SCAN source -2 13, 14 -> obsolete
,E/WifiStateMachine(  819): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-49
E/WifiStateMachine(  819): WifiStateMachine L2Connected CMD_START_SCAN source -2 11, 14 -> obsolete
,I/kickstart(  871): STATUS: Received file 'm9kefs1'
,I/kickstart(  871): STATUS: 950272 bytes transferred in 1.050317 seconds
I/kickstart(  871): STATUS: Successfully downloaded files from target 
I/kickstart(  871): STATUS: Wrote to /sys/power/wake_unlock
,I/kickstart(  871): STATUS: Sahara protocol completed,
,V/GLSActivity( 1281): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1281): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1281): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1281): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1281): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1281): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3024): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3024): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3024): [1] 5.onFinished: Scheduling replication attempt 5.
,D/HeadsetStateMachine( 2403): Disconnected process message: 10, size: 0
,V/GLSActivity( 1281): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GoogleAuthProtoRequest( 3602): [385] a.<init>: mAccountName set to: thalitester@gmail.com
,I/VacuumService( 1281): Vacuum at: now=1454092037789 tag=VacuumService
,V/GLSActivity( 1281): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GoogleURLConnFactory( 1281): Using platform SSLCertificateSocketFactory
,I/GLSUser ( 1281): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1281): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1281): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1281): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1281): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1281): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1281): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1281): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1281): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/Finsky  ( 3024): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3024): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3024): [1] 5.onFinished: Giving up after 6 failures.
,V/GLSActivity( 1281): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1281): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1281): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1281): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1281): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1281): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/ExperimentUpdateService( 3602): [385] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3602): [385] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3602): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3602): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3602): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3602): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3602): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3602): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3602): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3602): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3602): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3602): 	at com.a.a.k.run(SourceFile:110)
,E/Uploader( 1281): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1281): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1281): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1281): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1281): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1281): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1281): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1281): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1281): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1281): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1281): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1281): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1281): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1281): No account for auth token provided
,W/Uploader( 1281): No account for auth token provided,
,I/GLSUser ( 1281): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1281): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1281): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1281): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1281): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1281): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1281): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1281): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1281): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1281): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1281): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1281): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1281): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1281): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1281): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1281): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1281): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1281): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1281): No account for auth token provided
,W/Uploader( 1281): No account for auth token provided
,W/Uploader( 1281): No account for auth token provided
,W/Uploader( 1281): No account for auth token provided
,W/Uploader( 1281): No account for auth token provided
,I/GLSUser ( 1281): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1281): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1281): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1281): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1281): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1281): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1281): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1281): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1281): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1281): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1281): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1281): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1281): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1281): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1281): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1281): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1281): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1281): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1281): No account for auth token provided
,W/Uploader( 1281): No account for auth token provided
,W/Uploader( 1281): No account for auth token provided
,W/Uploader( 1281): No account for auth token provided
,W/Uploader( 1281): No account for auth token provided
,W/Uploader( 1281): No account for auth token provided
,W/Uploader( 1281): No account for auth token provided
,W/Uploader( 1281):  no longer exists, so no auth token.
,I/GLSUser ( 1281): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1281): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1281): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1281): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1281): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1281): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1281): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1281): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1281): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1281): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1281): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1281): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1281): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1281): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1281): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1281): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1281): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1281): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/GLSUser ( 1281): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1281): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1281): [GLSUser] Extracting token using key: Auth,
W/GLSActivity( 1281): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1281): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3454): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3454): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3454): 	at jdm.a(PG:82)
E/HttpOperation( 3454): 	at jcs.o(PG:406)
E/HttpOperation( 3454): 	at jcn.a(PG:1379)
E/HttpOperation( 3454): 	at jcs.i(PG:143)
E/HttpOperation( 3454): 	at blb.a(PG:3937)
E/HttpOperation( 3454): 	at czp.a(PG:18188)
E/HttpOperation( 3454): 	at czp.a(PG:9081)
E/HttpOperation( 3454): 	at czq.run(PG:1686)
E/HttpOperation( 3454): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3454): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3454): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3454): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3454): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3454): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3454): 	at jdj.a(PG:4091)
E/HttpOperation( 3454): 	at jdj.a(PG:1125)
E/HttpOperation( 3454): 	at jdm.a(PG:77)
E/HttpOperation( 3454): 	... 12 more
E/HttpOperation( 3454): Caused by: faj: BadAuthentication
E/HttpOperation( 3454): 	at fal.a(PG:38)
E/HttpOperation( 3454): 	at jdj.a(PG:4089)
E/HttpOperation( 3454): 	... 14 more
,I/GLSUser ( 1281): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1281): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1281): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1281): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1281): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  819): Explicit concurrent mark sweep GC freed 42249(1988KB) AllocSpace objects, 7(300KB) LOS objects, 31% free, 34MB/50MB, paused 1.573ms total 84.848ms
,E/HttpOperation( 3454): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3454): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3454): 	at jdm.a(PG:82)
E/HttpOperation( 3454): 	at jcs.o(PG:406)
E/HttpOperation( 3454): 	at jcn.a(PG:1379)
E/HttpOperation( 3454): 	at jcs.i(PG:143)
E/HttpOperation( 3454): 	at hec.a(PG:42)
E/HttpOperation( 3454): 	at hee.a(PG:102)
E/HttpOperation( 3454): 	at czr.a(PG:65)
E/HttpOperation( 3454): 	at kka.a(PG:108)
E/HttpOperation( 3454): 	at czp.a(PG:19176)
E/HttpOperation( 3454): 	at czp.a(PG:9081)
E/HttpOperation( 3454): 	at czq.run(PG:1686)
E/HttpOperation( 3454): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3454): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3454): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3454): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3454): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3454): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3454): 	at jdj.a(PG:4091)
E/HttpOperation( 3454): 	at jdj.a(PG:1125)
E/HttpOperation( 3454): 	at jdm.a(PG:77)
E/HttpOperation( 3454): 	... 15 more
E/HttpOperation( 3454): Caused by: faj: BadAuthentication
E/HttpOperation( 3454): 	at fal.a(PG:38)
E/HttpOperation( 3454): 	at jdj.a(PG:4089)
E/HttpOperation( 3454): 	... 17 more
,E/ExperimentLoader( 3454): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3454): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3454): 	at jdm.a(PG:82)
E/ExperimentLoader( 3454): 	at jcs.o(PG:406)
E/ExperimentLoader( 3454): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3454): 	at jcs.i(PG:143)
E/ExperimentLoader( 3454): 	at hec.a(PG:42)
E/ExperimentLoader( 3454): 	at hee.a(PG:102)
E/ExperimentLoader( 3454): 	at czr.a(PG:65)
E/ExperimentLoader( 3454): 	at kka.a(PG:108)
E/ExperimentLoader( 3454): 	at czp.a(PG:19176)
E/ExperimentLoader( 3454): 	at czp.a(PG:9081)
E/ExperimentLoader( 3454): 	at czq.run(PG:1686)
E/ExperimentLoader( 3454): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3454): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3454): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3454): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3454): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3454): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3454): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3454): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3454): 	at jdm.a(PG:77)
E/ExperimentLoader( 3454): 	... 15 more
E/ExperimentLoader( 3454): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3454): 	at fal.a(PG:38)
E/ExperimentLoader( 3454): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3454): 	... 17 more
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 200897, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,V/GoogleAuthProtoRequest( 3602): [386] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1281): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1281): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1281): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1281): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1281): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3602): [386] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3602): [386] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3602): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3602): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3602): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3602): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3602): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3602): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3602): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3602): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3602): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3602): 	at com.a.a.k.run(SourceFile:110)
,I/Keyboard.Facilitator.LanguageModelFlusher( 1233): run()
I/Keyboard.Facilitator( 1233): flushDynamicLanguageModels()
,I/ConfigService( 1281): onCreate
,I/ConfigService( 1281): onDestroy
,I/BooksSync( 3840): Starting books sync for 61035162, extras: ade
,V/KeepSync( 3797): Connecting to GoogleApiClient
,I/BooksConfig( 3840): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1281): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1281): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1281): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1281): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1281): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1281): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1281): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1281): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1281): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1281): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,V/KeepSync( 3797): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3797): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3797): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3797): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1281): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1281): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1281): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1281): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1281): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1281): Explicit concurrent mark sweep GC freed 63958(3MB) AllocSpace objects, 12(1238KB) LOS objects, 36% free, 27MB/43MB, paused 1.414ms total 58.918ms
,E/BooksAccountManager( 3840): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3840): Soft error,
E/BooksSync( 3840): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3840): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3840): Sync error
E/BooksSync( 3840): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3840): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3840): Finished books sync
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 202772, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1281): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1281): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1281): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1281): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1281): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3797): IOException
E/KeepSync( 3797): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3797): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3797): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3797): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3797): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858),
E/KeepSync( 3797): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3797): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3797): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3797): 	at com.google.android.keep.util.m.a(SourceFile:207)
,E/KeepSync( 3797): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3797): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3797): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3797): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
,E/KeepSync( 3797): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3797): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
,E/KeepSync( 3797): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3797): 	... 10 more
W/KeepSync( 3797): Sync result 2
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 201847, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2403): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2403): Disconnected process message: 10, size: 0
,V/GoogleAuthProtoRequest( 3602): [388] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1281): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1281): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1281): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1281): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1281): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3602): [388] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3602): [388] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3602): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3602): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3602): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3602): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3602): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3602): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3602): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3602): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3602): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3602): 	at com.a.a.k.run(SourceFile:110)
,V/GoogleAuthProtoRequest( 3602): [389] a.<init>: mAccountName set to: thalitester@gmail.com
,V/GoogleAuthProtoRequest( 3602): [390] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1281): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1281): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1281): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1281): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1281): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1281): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1281): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1281): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1281): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1281): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3602): [389] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3602): [390] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3602): [389] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3602): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3602): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3602): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3602): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3602): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3602): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3602): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3602): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3602): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3602): 	at com.a.a.k.run(SourceFile:110)
W/ExperimentUpdateService( 3602): [390] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3602): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3602): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3602): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3602): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3602): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3602): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3602): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3602): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3602): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3602): 	at com.a.a.k.run(SourceFile:110)
,D/HeadsetStateMachine( 2403): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2403): Disconnected process message: 10, size: 0
,D/WifiService(  819): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@18bad9b5}
,E/WifiStateMachine(  819): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-49
,D/WifiService(  819): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@18bad9b5}
,E/LocSvc_IzatApiV02(  819): E/virtual int izat_core::IzatApiV02::injectLocation(GpsExtLocation):857]: error! inject position failed
,I/GLSUser ( 1281): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1281): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1281): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1281): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1281): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3454): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3454): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3454): 	at jdm.a(PG:82)
E/HttpOperation( 3454): 	at jcs.o(PG:406)
E/HttpOperation( 3454): 	at jcn.a(PG:1379)
E/HttpOperation( 3454): 	at jcs.i(PG:143)
E/HttpOperation( 3454): 	at blb.a(PG:3937)
E/HttpOperation( 3454): 	at czp.a(PG:18188)
E/HttpOperation( 3454): 	at czp.a(PG:9081)
E/HttpOperation( 3454): 	at czq.run(PG:1686)
E/HttpOperation( 3454): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3454): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3454): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3454): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3454): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3454): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3454): 	at jdj.a(PG:4091)
E/HttpOperation( 3454): 	at jdj.a(PG:1125)
E/HttpOperation( 3454): 	at jdm.a(PG:77)
E/HttpOperation( 3454): 	... 12 more
E/HttpOperation( 3454): Caused by: faj: BadAuthentication
E/HttpOperation( 3454): 	at fal.a(PG:38)
E/HttpOperation( 3454): 	at jdj.a(PG:4089)
E/HttpOperation( 3454): 	... 14 more
,I/GLSUser ( 1281): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1281): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1281): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1281): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1281): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/HttpOperation( 3454): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3454): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3454): 	at jdm.a(PG:82)
E/HttpOperation( 3454): 	at jcs.o(PG:406)
E/HttpOperation( 3454): 	at jcn.a(PG:1379)
E/HttpOperation( 3454): 	at jcs.i(PG:143)
E/HttpOperation( 3454): 	at hec.a(PG:42)
E/HttpOperation( 3454): 	at hee.a(PG:102)
E/HttpOperation( 3454): 	at czr.a(PG:65)
E/HttpOperation( 3454): 	at kka.a(PG:108)
E/HttpOperation( 3454): 	at czp.a(PG:19176)
E/HttpOperation( 3454): 	at czp.a(PG:9081)
E/HttpOperation( 3454): 	at czq.run(PG:1686)
E/HttpOperation( 3454): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3454): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3454): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3454): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3454): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3454): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3454): 	at jdj.a(PG:4091)
E/HttpOperation( 3454): 	at jdj.a(PG:1125)
E/HttpOperation( 3454): 	at jdm.a(PG:77)
E/HttpOperation( 3454): 	... 15 more
E/HttpOperation( 3454): Caused by: faj: BadAuthentication
E/HttpOperation( 3454): 	at fal.a(PG:38)
E/HttpOperation( 3454): 	at jdj.a(PG:4089)
E/HttpOperation( 3454): 	... 17 more
E/ExperimentLoader( 3454): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3454): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3454): 	at jdm.a(PG:82)
E/ExperimentLoader( 3454): 	at jcs.o(PG:406)
E/ExperimentLoader( 3454): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3454): 	at jcs.i(PG:143)
E/ExperimentLoader( 3454): 	at hec.a(PG:42)
E/ExperimentLoader( 3454): 	at hee.a(PG:102)
E/ExperimentLoader( 3454): 	at czr.a(PG:65)
E/ExperimentLoader( 3454): 	at kka.a(PG:108)
E/ExperimentLoader( 3454): 	at czp.a(PG:19176)
E/ExperimentLoader( 3454): 	at czp.a(PG:9081)
E/ExperimentLoader( 3454): 	at czq.run(PG:1686)
E/ExperimentLoader( 3454): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3454): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3454): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3454): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3454): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3454): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3454): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3454): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3454): 	at jdm.a(PG:77)
E/ExperimentLoader( 3454): 	... 15 more
E/ExperimentLoader( 3454): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3454): 	at fal.a(PG:38)
E/ExperimentLoader( 3454): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3454): 	... 17 more
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 330032, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager(  819): Start proc 3972:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider
,I/GAv4    ( 3972): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3972):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3972):   adb logcat -s GAv4
,W/GAv4    ( 3972): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3972): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3972): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/art     (  819): Explicit concurrent mark sweep GC freed 34022(1563KB) AllocSpace objects, 14(695KB) LOS objects, 31% free, 34MB/50MB, paused 1.402ms total 68.489ms
,I/ActivityManager(  819): Killing 2311:com.google.android.calendar/u0a37 (adj 15): empty #17
,V/GoogleAuthProtoRequest( 3602): [391] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1281): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1281): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1281): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1281): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1281): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3602): [391] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.,
,W/ExperimentUpdateService( 3602): [391] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3602): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3602): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3602): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3602): 	,at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3602): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3602): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3602): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3602): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3602): 	at com.a.a.a.a.a(SourceFile:93),
W/ExperimentUpdateService( 3602): 	at com.a.a.k.run(SourceFile:110)
,V/GLSActivity( 1281): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1281): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1281): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1281): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1281): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1281): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1281): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1281): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1281): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1281): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1281): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1281): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1281): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 3024): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3024): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3024): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 3024): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3024): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/PlayEventLogger( 3024): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3024): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 3024): Ignoring header User-Agent because its value was null.
,D/HeadsetStateMachine( 2403): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2403): Disconnected process message: 10, size: 0
,I/BooksSync( 3840): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3840): GmsCore Version = 7.8.99 (2134222-430)
,V/KeepSync( 3797): Connecting to GoogleApiClient
,I/GLSUser ( 1281): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1281): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1281): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1281): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1281): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1281): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata,
I/GLSUser ( 1281): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1281): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1281): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1281): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
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
,V/KeepSync( 3797): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3797): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3797): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3797): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1281): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1281): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1281): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1281): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1281): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3840): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3840): Soft error
E/BooksSync( 3840): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3840): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3840): Sync error
E/BooksSync( 3840): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3840): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3840): Finished books sync
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 363015, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1281): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1281): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1281): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1281): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1281): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3797): IOException
E/KeepSync( 3797): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3797): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3797): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3797): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3797): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3797): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3797): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3797): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3797): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3797): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3797): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3797): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3797): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3797): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3797): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3797): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3797): 	... 10 more
W/KeepSync( 3797): Sync result 2
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 361923, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,V/GoogleAuthProtoRequest( 3602): [392] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1281): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1281): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1281): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1281): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1281): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3602): [392] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3602): [392] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3602): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3602): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3602): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3602): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3602): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3602): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3602): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3602): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3602): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3602): 	at com.a.a.k.run(SourceFile:110)
,D/HeadsetStateMachine( 2403): Disconnected process message: 10, size: 0
,V/GoogleAuthProtoRequest( 3602): [393] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1281): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1281): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1281): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1281): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1281): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1281): Explicit concurrent mark sweep GC freed 54236(2MB) AllocSpace objects, 12(1323KB) LOS objects, 36% free, 27MB/43MB, paused 1.140ms total 47.849ms
,W/ExperimentUpdateService( 3602): [393] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3602): [393] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3602): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3602): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3602): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3602): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3602): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3602): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3602): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3602): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3602): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3602): 	at com.a.a.k.run(SourceFile:110)
,D/HeadsetStateMachine( 2403): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2403): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2403): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2403): Disconnected process message: 10, size: 0
,I/GLSUser ( 1281): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1281): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1281): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1281): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1281): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/HttpOperation( 3454): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3454): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3454): 	at jdm.a(PG:82)
E/HttpOperation( 3454): 	at jcs.o(PG:406)
E/HttpOperation( 3454): 	at jcn.a(PG:1379)
E/HttpOperation( 3454): 	at jcs.i(PG:143)
E/HttpOperation( 3454): 	at blb.a(PG:3937)
E/HttpOperation( 3454): 	at czp.a(PG:18188)
E/HttpOperation( 3454): 	at czp.a(PG:9081)
E/HttpOperation( 3454): 	at czq.run(PG:1686)
E/HttpOperation( 3454): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3454): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3454): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3454): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3454): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3454): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3454): 	at jdj.a(PG:4091)
E/HttpOperation( 3454): 	at jdj.a(PG:1125)
E/HttpOperation( 3454): 	at jdm.a(PG:77)
E/HttpOperation( 3454): 	... 12 more
E/HttpOperation( 3454): Caused by: faj: BadAuthentication
E/HttpOperation( 3454): 	at fal.a(PG:38)
E/HttpOperation( 3454): 	at jdj.a(PG:4089)
E/HttpOperation( 3454): 	... 14 more
,I/GLSUser ( 1281): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1281): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1281): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1281): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1281): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3454): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3454): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3454): 	at jdm.a(PG:82)
E/HttpOperation( 3454): 	at jcs.o(PG:406)
E/HttpOperation( 3454): 	at jcn.a(PG:1379)
E/HttpOperation( 3454): 	at jcs.i(PG:143)
E/HttpOperation( 3454): 	at hec.a(PG:42)
E/HttpOperation( 3454): 	at hee.a(PG:102)
E/HttpOperation( 3454): 	at czr.a(PG:65)
E/HttpOperation( 3454): 	at kka.a(PG:108)
E/HttpOperation( 3454): 	at czp.a(PG:19176)
E/HttpOperation( 3454): 	at czp.a(PG:9081)
E/HttpOperation( 3454): 	at czq.run(PG:1686)
E/HttpOperation( 3454): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3454): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3454): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3454): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3454): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3454): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3454): 	at jdj.a(PG:4091)
E/HttpOperation( 3454): 	at jdj.a(PG:1125)
E/HttpOperation( 3454): 	at jdm.a(PG:77)
E/HttpOperation( 3454): 	... 15 more
E/HttpOperation( 3454): Caused by: faj: BadAuthentication
E/HttpOperation( 3454): 	at fal.a(PG:38)
E/HttpOperation( 3454): 	at jdj.a(PG:4089)
E/HttpOperation( 3454): 	... 17 more
,E/ExperimentLoader( 3454): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3454): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3454): 	at jdm.a(PG:82)
E/ExperimentLoader( 3454): 	at jcs.o(PG:406)
E/ExperimentLoader( 3454): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3454): 	at jcs.i(PG:143)
E/ExperimentLoader( 3454): 	at hec.a(PG:42)
E/ExperimentLoader( 3454): 	at hee.a(PG:102)
E/ExperimentLoader( 3454): 	at czr.a(PG:65)
E/ExperimentLoader( 3454): 	at kka.a(PG:108)
E/ExperimentLoader( 3454): 	at czp.a(PG:19176)
E/ExperimentLoader( 3454): 	at czp.a(PG:9081)
E/ExperimentLoader( 3454): 	at czq.run(PG:1686)
E/ExperimentLoader( 3454): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3454): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3454): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3454): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3454): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3454): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3454): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3454): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3454): 	at jdm.a(PG:77)
E/ExperimentLoader( 3454): 	... 15 more
E/ExperimentLoader( 3454): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3454): 	at fal.a(PG:38)
E/ExperimentLoader( 3454): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3454): 	... 17 more
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 587847, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2403): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2403): Disconnected process message: 10, size: 0,
,D/Finsky  ( 3024): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,I/art     (  819): Explicit concurrent mark sweep GC freed 35839(1588KB) AllocSpace objects, 5(268KB) LOS objects, 31% free, 34MB/50MB, paused 1.524ms total 69.971ms
,V/GoogleAuthProtoRequest( 3602): [394] a.<init>: mAccountName set to: thalitester@gmail.com
,V/GLSActivity( 1281): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1281): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1281): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1281): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1281): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1281): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 3024): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1281): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1281): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1281): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1281): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1281): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1281): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3602): [394] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3602): [394] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3602): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3602): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3602): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3602): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3602): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3602): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3602): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3602): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3602): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3602): 	at com.a.a.k.run(SourceFile:110)
,I/GLSUser ( 1281): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1281): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1281): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1281): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1281): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1281): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1281): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1281): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1281): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1281): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1281): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 3024): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1281): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1281): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1281): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1281): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1281): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1281): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 3024): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 3024): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 3024): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3024): [1] DailyHygiene.reschedule: Scheduling new run in 27 minutes (failures=2)
,D/DeviceConnectionService( 1799): client connected with version: 7571000
,V/KeepSync( 3797): Connecting to GoogleApiClient
,I/GLSUser ( 1281): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1281): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1281): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1281): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1281): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,V/KeepSync( 3797): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3797): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3797): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3797): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1281): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1281): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1281): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1281): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1281): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3797): IOException
E/KeepSync( 3797): com.google.android.apiary.AuthenticationException: Could not get an auth token
,E/KeepSync( 3797): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3797): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3797): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3797): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3797): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3797): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3797): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3797): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3797): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3797): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3797): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,E/KeepSync( 3797): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3797): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3797): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3797): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3797): 	... 10 more
W/KeepSync( 3797): Sync result 2
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 651660, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2403): Disconnected process message: 10, size: 0
,V/GLSActivity( 1281): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1281): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure,
I/GLSUser ( 1281): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1281): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1281): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1281): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3024): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3024): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3024): [1] 5.onFinished: Scheduling replication attempt 1.
,D/HeadsetStateMachine( 2403): Disconnected process message: 10, size: 0
,I/BooksSync( 3840): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3840): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1281): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1281): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1281): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1281): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1281): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1281): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1281): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1281): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1281): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1281): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3840): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3840): Soft error
E/BooksSync( 3840): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3840): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3840): Sync error
E/BooksSync( 3840): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3840): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3840): Finished books sync
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 653854, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,V/GLSActivity( 1281): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1281): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1281): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1281): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1281): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1281): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3024): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3024): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3024): [1] 5.onFinished: Scheduling replication attempt 2.
,V/GoogleAuthProtoRequest( 3602): [395] a.<init>: mAccountName set to: thalitester@gmail.com
,I/art     (  819): Explicit concurrent mark sweep GC freed 26046(1092KB) AllocSpace objects, 6(378KB) LOS objects, 31% free, 34MB/50MB, paused 1.856ms total 55.792ms
,V/GLSActivity( 1281): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1281): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1281): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1281): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1281): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/GLSUser ( 1281): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1281): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1281): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1281): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/art     ( 1281): Explicit concurrent mark sweep GC freed 51679(2MB) AllocSpace objects, 11(1213KB) LOS objects, 37% free, 26MB/42MB, paused 1.041ms total 30.127ms
V/GLSActivity( 1281): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1281): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3024): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3024): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3024): [1] 5.onFinished: Scheduling replication attempt 3.
,W/ExperimentUpdateService( 3602): [395] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3602): [395] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3602): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3602): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3602): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3602): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3602): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3602): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3602): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3602): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3602): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3602): 	at com.a.a.k.run(SourceFile:110)
,D/HeadsetStateMachine( 2403): Disconnected process message: 10, size: 0
,V/GLSActivity( 1281): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1281): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1281): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1281): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1281): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1281): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3024): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3024): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3024): [1] 5.onFinished: Scheduling replication attempt 4.
,V/GLSActivity( 1281): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1281): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1281): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1281): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1281): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1281): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3024): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3024): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3024): [1] 5.onFinished: Scheduling replication attempt 5.
,V/GLSActivity( 1281): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1281): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1281): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1281): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1281): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1281): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3024): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3024): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3024): [1] 5.onFinished: Giving up after 6 failures.
,D/HeadsetStateMachine( 2403): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2403): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2403): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2403): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2403): Disconnected process message: 10, size: 0
,W/bt-btm  ( 2403): Stopping oneshot timer
,D/HeadsetStateMachine( 2403): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2403): Disconnected process message: 10, size: 0
,D/GCM     ( 1281): Message class com.google.f.a.a.i
,D/HeadsetStateMachine( 2403): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2403): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2403): Disconnected process message: 10, size: 0
,I/GLSUser ( 1281): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1281): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1281): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1281): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1281): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3454): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3454): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3454): 	at jdm.a(PG:82)
E/HttpOperation( 3454): 	at jcs.o(PG:406)
E/HttpOperation( 3454): 	at jcn.a(PG:1379)
E/HttpOperation( 3454): 	at jcs.i(PG:143)
E/HttpOperation( 3454): 	at blb.a(PG:3937)
E/HttpOperation( 3454): 	at czp.a(PG:18188)
E/HttpOperation( 3454): 	at czp.a(PG:9081)
E/HttpOperation( 3454): 	at czq.run(PG:1686)
E/HttpOperation( 3454): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3454): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3454): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3454): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3454): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3454): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3454): 	at jdj.a(PG:4091)
E/HttpOperation( 3454): 	at jdj.a(PG:1125)
E/HttpOperation( 3454): 	at jdm.a(PG:77)
E/HttpOperation( 3454): 	... 12 more
E/HttpOperation( 3454): Caused by: faj: BadAuthentication
E/HttpOperation( 3454): 	at fal.a(PG:38)
E/HttpOperation( 3454): 	at jdj.a(PG:4089)
E/HttpOperation( 3454): 	... 14 more
,I/GLSUser ( 1281): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1281): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1281): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1281): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1281): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3454): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3454): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3454): 	at jdm.a(PG:82)
E/HttpOperation( 3454): 	at jcs.o(PG:406)
E/HttpOperation( 3454): 	at jcn.a(PG:1379)
E/HttpOperation( 3454): 	at jcs.i(PG:143)
E/HttpOperation( 3454): 	at hec.a(PG:42)
E/HttpOperation( 3454): 	at hee.a(PG:102)
E/HttpOperation( 3454): 	at czr.a(PG:65)
E/HttpOperation( 3454): 	at kka.a(PG:108)
E/HttpOperation( 3454): 	at czp.a(PG:19176)
E/HttpOperation( 3454): 	at czp.a(PG:9081)
E/HttpOperation( 3454): 	at czq.run(PG:1686)
E/HttpOperation( 3454): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3454): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3454): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3454): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3454): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3454): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3454): 	at jdj.a(PG:4091)
E/HttpOperation( 3454): 	at jdj.a(PG:1125)
E/HttpOperation( 3454): 	at jdm.a(PG:77)
E/HttpOperation( 3454): 	... 15 more
E/HttpOperation( 3454): Caused by: faj: BadAuthentication
E/HttpOperation( 3454): 	at fal.a(PG:38)
E/HttpOperation( 3454): 	at jdj.a(PG:4089)
E/HttpOperation( 3454): 	... 17 more
,E/ExperimentLoader( 3454): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3454): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3454): 	at jdm.a(PG:82)
E/ExperimentLoader( 3454): 	at jcs.o(PG:406)
E/ExperimentLoader( 3454): 	at jcn.a(PG:1379),
E/ExperimentLoader( 3454): 	at jcs.i(PG:143)
E/ExperimentLoader( 3454): 	at hec.a(PG:42)
E/ExperimentLoader( 3454): 	at hee.a(PG:102)
,E/ExperimentLoader( 3454): 	at czr.a(PG:65)
E/ExperimentLoader( 3454): 	at kka.a(PG:108)
E/ExperimentLoader( 3454): 	at czp.a(PG:19176)
,E/ExperimentLoader( 3454): 	at czp.a(PG:9081)
E/ExperimentLoader( 3454): 	at czq.run(PG:1686)
E/ExperimentLoader( 3454): 	,at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3454): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3454): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
,E/ExperimentLoader( 3454): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3454): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3454): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3454): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3454): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3454): 	at jdm.a(PG:77)
E/ExperimentLoader( 3454): 	... 15 more
E/ExperimentLoader( 3454): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3454): 	at fal.a(PG:38)
E/ExperimentLoader( 3454): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3454): 	... 17 more
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 1102885, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,V/GoogleAuthProtoRequest( 3602): [396] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1281): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1281): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1281): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1281): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1281): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3602): [396] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3602): [396] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3602): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3602): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3602): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3602): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3602): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3602): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3602): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3602): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3602): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3602): 	at com.a.a.k.run(SourceFile:110)
,D/HeadsetStateMachine( 2403): Disconnected process message: 10, size: 0
,V/KeepSync( 3797): Connecting to GoogleApiClient
,I/GLSUser ( 1281): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1281): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1281): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1281): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1281): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,V/KeepSync( 3797): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3797): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3797): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3797): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1281): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1281): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1281): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1281): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1281): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  819): Explicit concurrent mark sweep GC freed 37570(1772KB) AllocSpace objects, 4(252KB) LOS objects, 31% free, 34MB/50MB, paused 3.361ms total 81.552ms
,E/KeepSync( 3797): IOException
E/KeepSync( 3797): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3797): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3797): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3797): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3797): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3797): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3797): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3797): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3797): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3797): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3797): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3797): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3797): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3797): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3797): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3797): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3797): 	... 10 more
W/KeepSync( 3797): Sync result 2
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 1174385, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1],
,V/GoogleAuthProtoRequest( 3602): [397] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1281): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1281): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1281): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1281): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1281): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3602): [397] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3602): [397] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3602): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3602): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3602): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3602): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3602): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3602): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3602): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3602): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3602): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3602): 	at com.a.a.k.run(SourceFile:110)
,D/HeadsetStateMachine( 2403): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2403): Disconnected process message: 10, size: 0
,I/UsageStatsService(  819): User[0] Flushing usage stats to disk
,I/BooksSync( 3840): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3840): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1281): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1281): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1281): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1281): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1281): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1281): Explicit concurrent mark sweep GC freed 63738(3MB) AllocSpace objects, 6(661KB) LOS objects, 37% free, 26MB/42MB, paused 1.696ms total 63.497ms
,I/GLSUser ( 1281): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1281): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1281): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1281): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1281): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3840): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3840): Soft error
E/BooksSync( 3840): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3840): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3840): Sync error
E/BooksSync( 3840): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3840): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 3840): Finished books sync
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1208952, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2403): Disconnected process message: 10, size: 0
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 4200): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 4200): CheckJNI is OFF
D/AndroidRuntime( 4200): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  819): Force stopping com.test.thalitest appid=10265 user=-1: uninstall pkg
I/ActivityManager(  819): Killing 3542:com.test.thalitest/u0a265 (adj 0): stop com.test.thalitest
I/WindowState(  819): WIN DEATH: Window{288b2832 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  819): Client connection lost with reason: 4
W/PackageSettings(  819): Skipping PackageSetting{3ff700d4 com.example.hello/10273} due to missing metadata
W/ActivityManager(  819): Force removing ActivityRecord{39c8e2b1 u0 com.test.thalitest/.MainActivity t28}: app died, no saved state
V/ActivityManager(  819): Display changed displayId=0
W/ActivityManager(  819): Spurious death for ProcessRecord{3a2642f2 3542:com.test.thalitest/u0a265}, curProc for 3542: null
I/ActivityManager(  819): Force stopping com.test.thalitest appid=10265 user=0: pkg removed
D/TaskPersister(  819): removeObsoleteFile: deleting file=28_task.xml
I/Keyboard.Facilitator( 1233): resetDictionaries() : en_US
I/InputReader(  819): Reconfiguring input devices.  changes=0x00000010
D/BuaReceiver( 3301): ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
I/Keyboard.Facilitator.DecoderInitializer( 1233): run()
I/ActivityManager(  819): Start proc 4216:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
I/Decoder ( 1233): createOrResetDecoder
I/art     ( 1064): Explicit concurrent mark sweep GC freed 72906(2MB) AllocSpace objects, 0(0B) LOS objects, 18% free, 72MB/88MB, paused 5.333ms total 81.682ms
W/InputMethodManagerService(  819): Got RemoteException sending setActive(false) notification to pid 3542 uid 10265
I/art     ( 1515): Explicit concurrent mark sweep GC freed 1582(134KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 1.488ms total 106.600ms
I/Keyboard.Facilitator( 1233): onFinishInput()
I/art     (  819): Explicit concurrent mark sweep GC freed 21162(1296KB) AllocSpace objects, 8(128KB) LOS objects, 31% free, 34MB/50MB, paused 1.500ms total 118.730ms
I/art     (  819): WaitForGcToComplete blocked for 92.355ms for cause Explicit
I/art     ( 1385): Explicit concurrent mark sweep GC freed 4989(364KB) AllocSpace objects, 12(1408KB) LOS objects, 31% free, 35MB/51MB, paused 794us total 24.584ms
I/ConfigService( 1281): onCreate
W/LocationOracleImpl( 1515): Best location was null
I/HotwordRecognitionRnr( 1515): Starting hotword detection.
I/MicrophoneInputStream( 1515): mic_starting com.google.android.apps.gsa.speech.audio.u@2e917e86
I/AudioFlinger(  357): AudioFlinger's thread 0xb407a000 ready to run
I/SoundTriggerHwService::Module(  357): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/MicrophoneInputStream( 1515): mic_started com.google.android.apps.gsa.speech.audio.u@2e917e86
I/Keyboard.Facilitator.MainLanguageModelLoader( 1233): run()
D/JobSchedulerService(  819): Receieved: android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  819): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/audio_hw_primary(  357): select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
D/msm8974_platform(  357): platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
E/ACDB-LOADER(  357): Error: ACDB AudProc vol returned = -19
D/audio_hw_primary(  357): enable_snd_device: snd_device(55: voice-rec-mic)
D/audio_hw_primary(  357): enable_audio_route: apply and update mixer path: audio-record
D/VoicemailCleanupService( 4216): Cleaning up data for package: com.test.thalitest
I/Keyboard.Facilitator.MainLanguageModelLoader( 1233): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1233): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1233): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1233): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1233): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1233): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1233): run() : Loading LM = user
I/ActivityManager(  819): Start proc 4251:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1233): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1233): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1233): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1233): run()
I/StatsUtilsManager( 1233): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1233): shouldRecordStats() = Too Soon
I/art     (  819): Explicit concurrent mark sweep GC freed 6520(311KB) AllocSpace objects, 2(220KB) LOS objects, 32% free, 33MB/49MB, paused 2.214ms total 130.205ms
I/ContactLocale( 4216): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
I/HotwordWorker( 1515): onReady
I/ActivityManager(  819): Start proc 4274:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
D/WifiService(  819): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@304d350c}
E/WifiStateMachine(  819): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=25.50 rxSuccessRate=33.50 targetRoamBSSID=any RSSI=-49
W/ContextImpl( 4274): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2609 
E/NetworkScheduler.SchedulerReceiver( 1281): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1281): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
E/WifiStateMachine(  819): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=69.25 rxSuccessRate=179.25 targetRoamBSSID=any RSSI=-49
I/art     ( 4200): System.exit called, status: 0
I/AndroidRuntime( 4200): VM exiting with result code 0.
D/ChimeraCfgMgr( 1774): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1774): Module APK com.google.android.play.games already loaded
D/PackageBroadcastService( 1774): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1774): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1774): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1774): Module APK com.google.android.play.games already loaded
I/LocationSettingsChecker( 1774): Removing dialog suppression flag for package com.test.thalitest
I/UpdateIcingCorporaServi( 1515): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
W/Launcher( 1385): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@3fedea33 new=com.google.android.velvet.VelvetApplication@3fedea33
I/ActivityManager(  819): Killing 3380:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
E/LocSvc_IzatApiV02(  819): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1722508563
E/LocSvc_IzatApiV02(  819): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
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
E/kickstart(  871): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2
I/kickstart(  871): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2' for writing
I/ActivityManager(  819): Start proc 4306:com.google.android.apps.docs/u0a46 for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
D/Launcher.Workspace( 1385): 11683562 - stripEmptyScreens()
D/Launcher.Workspace( 1385): 11683562 - stripEmptyScreens()
E/SQLiteLog( 1515): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/AppDataSearchHelper( 1515): Exception thrown from onTableChanged
E/AppDataSearchHelper( 1515): java.lang.RuntimeException: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AppDataSearchHelper( 1515): 	at com.google.android.gms.appdatasearch.a.a.a(AppDataSearchDbOpenHelperBase.java:343)
E/AppDataSearchHelper( 1515): 	at com.google.android.gms.appdatasearch.a.a.a(AppDataSearchDbOpenHelperBase.java:261)
E/AppDataSearchHelper( 1515): 	at com.google.android.search.core.icingsync.d.j(InternalIcingCorporaProvider.java:709)
E/AppDataSearchHelper( 1515): 	at com.google.android.search.core.icingsync.d.a(InternalIcingCorporaProvider.java:700)
E/AppDataSearchHelper( 1515): 	at com.google.android.search.core.icingsync.d.i(InternalIcingCorporaProvider.java:627)
E/AppDataSearchHelper( 1515): 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:298)
E/AppDataSearchHelper( 1515): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:328)
E/AppDataSearchHelper( 1515): 	at android.content.ContentResolver.update(ContentResolver.java:1333)
E/AppDataSearchHelper( 1515): 	at com.google.android.search.core.icingsync.e.JA(UpdateIcingCorporaService.java:408)
E/AppDataSearchHelper( 1515): 	at com.google.android.search.core.icingsync.g.aTY(UpdateIcingCorporaService.java:347)
E/AppDataSearchHelper( 1515): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:320)
E/AppDataSearchHelper( 1515): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.ba(UpdateIcingCorporaService.java:215)
E/AppDataSearchHelper( 1515): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:201)
E/AppDataSearchHelper( 1515): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AppDataSearchHelper( 1515): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AppDataSearchHelper( 1515): 	at android.os.Looper.loop(Looper.java:135)
E/AppDataSearchHelper( 1515): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/AppDataSearchHelper( 1515): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AppDataSearchHelper( 1515): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AppDataSearchHelper( 1515): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/AppDataSearchHelper( 1515): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AppDataSearchHelper( 1515): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AppDataSearchHelper( 1515): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/AppDataSearchHelper( 1515): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/AppDataSearchHelper( 1515): 	at com.google.android.gms.appdatasearch.a.a.a(AppDataSearchDbOpenHelperBase.java:661)
E/AppDataSearchHelper( 1515): 	at com.google.android.gms.appdatasearch.a.a$1.JA(AppDataSearchDbOpenHelperBase.java:246)
E/AppDataSearchHelper( 1515): 	at com.google.android.gms.appdatasearch.a.a$1.call(AppDataSearchDbOpenHelperBase.java:227)
E/AppDataSearchHelper( 1515): 	at com.google.android.gms.appdatasearch.a.a.a(AppDataSearchDbOpenHelperBase.java:341)
E/AppDataSearchHelper( 1515): 	... 16 more
W/AppDataSearchHelper( 1515): Table change notification failed for com.google.android.gms.appdatasearch.a.h@be7fd6a1
I/UpdateIcingCorporaServi( 1515): UpdateCorporaTask done [took 284 ms] updated apps [took 284 ms] 
E/SQLiteLog( 1385): (3850) statement aborts at 24: [DELETE FROM shortcut_and_widget_previews WHERE name LIKE ? OR name LIKE ?] disk I/O error
I/ActivityManager(  819): Start proc 4324:com.google.android.gms.wearable/u0a11 for service com.google.android.gms/.wearable.service.WearableControlService
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
I/ConfigFetchService( 1774): onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
E/SharedPreferencesImpl( 1774): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/config_removals.xml to backup file /data/data/com.google.android.gms/shared_prefs/config_removals.xml.bak
I/ConfigFetchService( 1774): service connected
W/BaseAppContext( 1774): Using Auth Proxy for data requests.
W/ResourcesManager( 4324): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4324): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/BaseAppContext( 1774): Using Auth Proxy for data requests.
I/PeopleContactsSync( 1774): CP2 sync disabled
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
I/Icing   ( 1774): doRemovePackageData com.test.thalitest
E/DropBoxManagerService(  819): Can't write: system_app_wtf
E/DropBoxManagerService(  819): java.io.FileNotFoundException: /data/system/dropbox/drop97.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  819): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  819): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  819): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  819): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  819): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  819): 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
E/DropBoxManagerService(  819): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  819): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  819): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  819): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  819): 	... 5 more
I/MultiDex( 4324): VM with version 2.1.0 has multidex support
I/MultiDex( 4324): install
I/MultiDex( 4324): VM has multidex support, MultiDex support library is disabled.
V/JNIHelp ( 4324): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
I/ProviderInstaller( 4324): Installed default security provider GmsCore_OpenSSL
W/NativeLibraryUtils( 4324): Failed to open lock file
W/NativeLibraryUtils( 4324): java.io.FileNotFoundException: /data/data/com.google.android.gms/cache/.lib.lock: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 4324): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/NativeLibraryUtils( 4324): 	at java.io.RandomAccessFile.<init>(RandomAccessFile.java:117)
W/NativeLibraryUtils( 4324): 	at com.google.android.gms.common.util.ax.a(SourceFile:305)
W/NativeLibraryUtils( 4324): 	at com.google.android.gms.common.app.a.run(SourceFile:136)
W/NativeLibraryUtils( 4324): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 4324): 	at libcore.io.Posix.open(Native Method)
W/NativeLibraryUtils( 4324): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/NativeLibraryUtils( 4324): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/NativeLibraryUtils( 4324): 	... 3 more
I/ActivityManager(  819): Killing 3208:com.android.providers.calendar/u0a3 (adj 15): empty #17
I/GAv4    ( 4306): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4306):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4306):   adb logcat -s GAv4
W/GAv4    ( 4306): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 4306): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
E/SharedPreferencesImpl( 4306): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4306): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4306): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
E/SharedPreferencesImpl( 4306): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/AnalyticsTrackerProxyImpl( 4306): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
E/SQLiteDatabase( 4306): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 4306): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4306): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4306): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4306): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4306): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4306): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4306): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4306): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4306): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4306): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4306): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4306): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4306): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4306): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4306): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 4306): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 4306): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 4306): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 4306): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 4306): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 4306): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4306): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4306): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4306): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4306): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 4306): 	at gir$c.run(Unknown Source)
E/GAv4    ( 4306): Opening the database failed, dropping the table and recreating it
E/SharedPreferencesImpl( 4306): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SQLiteDatabase( 4306): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4306): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4306): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4306): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4306): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4306): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4306): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4306): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4306): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4306): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4306): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4306): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4306): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4306): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4306): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4306): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 4306): 	at ael.a(PG:1521)
E/SQLiteDatabase( 4306): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 4306): 	at aen.run(PG:536)
E/SQLiteDatabase( 4306): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 4306): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4306): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4306): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4306): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4306): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4306): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4306): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4306): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4306): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4306): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4306): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4306): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4306): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4306): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4306): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 4306): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 4306): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 4306): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 4306): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 4306): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 4306): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4306): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4306): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4306): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4306): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 4306): 	at gir$c.run(Unknown Source)
E/GAv4    ( 4306): Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/GAv4    ( 4306): Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 4306): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4306): Job execution failed: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 4306): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4306): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4306): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/GAv4    ( 4306): Job execution failed: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4306): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4306): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SQLiteDatabase( 4306): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4306): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4306): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4306): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4306): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4306): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4306): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4306): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4306): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4306): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4306): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4306): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4306): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4306): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4306): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4306): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 4306): 	at ael.a(PG:1521)
E/SQLiteDatabase( 4306): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 4306): 	at aej.c(PG:139)
E/SQLiteDatabase( 4306): 	at aej.b(PG:398)
E/SQLiteDatabase( 4306): 	at agf.f(PG:417)
E/SQLiteDatabase( 4306): 	at oe.run(PG:1112)
E/SQLiteDatabase( 4306): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4306): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4306): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4306): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4306): 	at java.lang.Thread.run(Thread.java:818)
E/AbstractDatabaseInstance( 4306): Failed to delete from CachedSearch133
E/AbstractDatabaseInstance( 4306): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AbstractDatabaseInstance( 4306): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AbstractDatabaseInstance( 4306): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AbstractDatabaseInstance( 4306): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AbstractDatabaseInstance( 4306): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AbstractDatabaseInstance( 4306): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AbstractDatabaseInstance( 4306): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AbstractDatabaseInstance( 4306): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AbstractDatabaseInstance( 4306): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AbstractDatabaseInstance( 4306): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AbstractDatabaseInstance( 4306): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AbstractDatabaseInstance( 4306): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AbstractDatabaseInstance( 4306): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AbstractDatabaseInstance( 4306): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AbstractDatabaseInstance( 4306): 	at aev.getWritableDatabase(PG:238)
E/AbstractDatabaseInstance( 4306): 	at ael.a(PG:1521)
E/AbstractDatabaseInstance( 4306): 	at hix$a.a(PG:125)
E/AbstractDatabaseInstance( 4306): 	at aej.c(PG:139)
E/AbstractDatabaseInstance( 4306): 	at aej.b(PG:398)
E/AbstractDatabaseInstance( 4306): 	at agf.f(PG:417)
E/AbstractDatabaseInstance( 4306): 	at oe.run(PG:1112)
E/AbstractDatabaseInstance( 4306): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/AbstractDatabaseInstance( 4306): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AbstractDatabaseInstance( 4306): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AbstractDatabaseInstance( 4306): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AbstractDatabaseInstance( 4306): 	at java.lang.Thread.run(Thread.java:818)
W/GAv4    ( 4306): Error opening database: android.database.sqlite.SQLiteException: Database open failed
W/GAv4    ( 4306): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/GAv4    ( 4306): Failed to commit local dispatch transaction: android.database.sqlite.SQLiteException: Database open failed
W/GAv4    ( 4306): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/GAv4    ( 4306): Sync local dispatch failed: android.database.sqlite.SQLiteException: Database open failed
W/GAv4    ( 4306): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/GAv4    ( 4306): syncDispatchLocalHits failed: java.util.concurrent.ExecutionException: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4306): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4306): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4306): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4306): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/CAKEMIX_CRASHED( 4306): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/CAKEMIX_CRASHED( 4306): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/CAKEMIX_CRASHED( 4306): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/CAKEMIX_CRASHED( 4306): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/CAKEMIX_CRASHED( 4306): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/CAKEMIX_CRASHED( 4306): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/CAKEMIX_CRASHED( 4306): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/CAKEMIX_CRASHED( 4306): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/CAKEMIX_CRASHED( 4306): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/CAKEMIX_CRASHED( 4306): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/CAKEMIX_CRASHED( 4306): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/CAKEMIX_CRASHED( 4306): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/CAKEMIX_CRASHED( 4306): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/CAKEMIX_CRASHED( 4306): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/CAKEMIX_CRASHED( 4306): 	at aev.getWritableDatabase(PG:238)
E/CAKEMIX_CRASHED( 4306): 	at ael.a(PG:1521)
E/CAKEMIX_CRASHED( 4306): 	at hix$a.a(PG:125)
E/CAKEMIX_CRASHED( 4306): 	at aen.run(PG:536)
E/SharedPreferencesImpl( 4306): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4306): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4306): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4306): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/ResourcesManager( 4306): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4306): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  819): START u0 {act=android.intent.action.BUG_REPORT flg=0x10000000 cmp=com.google.android.apps.docs/.app.ErrorNotificationActivity (has extras)} from uid 10046 on display 0
V/WindowManager(  819): addAppToken: AppWindowToken{3f6998a3 token=Token{8097fd2 ActivityRecord{3b4eda5d u0 com.google.android.apps.docs/.app.ErrorNotificationActivity t29}}} to stack=1 task=29 at 0
I/Process ( 4306): Sending signal. PID: 4306 SIG: 9
I/HotwordDetector( 1515): Closing mic
I/MicrophoneInputStream( 1515): mic_close com.google.android.apps.gsa.speech.audio.u@2e917e86
E/lowmemorykiller(  255): Error writing /proc/4306/oom_score_adj; errno=22
E/JavaBinder(  819): !!! FAILED BINDER TRANSACTION !!!
W/ActivityManager(  819): Exception when starting activity com.google.android.apps.docs/.app.ErrorNotificationActivity
W/ActivityManager(  819): android.os.TransactionTooLargeException
W/ActivityManager(  819): 	at android.os.BinderProxy.transactNative(Native Method)
W/ActivityManager(  819): 	at android.os.BinderProxy.transact(Binder.java:496)
W/ActivityManager(  819): 	at android.app.ApplicationThreadProxy.scheduleLaunchActivity(ApplicationThreadNative.java:797)
W/ActivityManager(  819): 	at com.android.server.am.ActivityStackSupervisor.realStartActivityLocked(ActivityStackSupervisor.java:1181)
W/ActivityManager(  819): 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1281)
W/ActivityManager(  819): 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:1891)
W/ActivityManager(  819): 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1455)
W/ActivityManager(  819): 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2473)
W/ActivityManager(  819): 	at com.android.server.am.ActivityStack.completePauseLocked(ActivityStack.java:998)
W/ActivityManager(  819): 	at com.android.server.am.ActivityStack.activityPausedLocked(ActivityStack.java:896)
W/ActivityManager(  819): 	at com.android.server.am.ActivityManagerService.activityPaused(ActivityManagerService.java:6311)
W/ActivityManager(  819): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:512)
W/ActivityManager(  819): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2208)
W/ActivityManager(  819): 	at android.os.Binder.execTransact(Binder.java:446)
D/audio_hw_primary(  357): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  357): disable_snd_device: snd_device(55: voice-rec-mic)
E/native  ( 1233): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1233): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
I/SoundTriggerHwService::Module(  357): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1515): Stopping hotword detection.
I/HotwordRecognitionRnr( 1515): Hotword detection finished
I/ActivityManager(  819): Start proc 4364:com.google.android.apps.docs/u0a46 for activity com.google.android.apps.docs/.app.ErrorNotificationActivity
W/ActivityManager(  819): Spurious death for ProcessRecord{62afb7a 4364:com.google.android.apps.docs/u0a46}, curProc for 4306: null
W/OpenGLRenderer( 1385): Incorrectly called buildLayer on View: ew, destroying layer...
I/art     (  368): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 583us total 39.381ms
I/art     (  368): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 385us total 16.751ms
I/art     (  368): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 282us total 14.245ms
I/ActivityManager(  819): Start proc 4382:com.android.documentsui/u0a45 for broadcast com.android.documentsui/.PackageReceiver
E/Search.SharedPreferencesProto( 1515): Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
I/ActivityManager(  819): Killing 3258:com.google.android.music:main/u0a66 (adj 15): empty #17
E/kickstart(  871): ERROR: function: rx_data:267 Timeout Occured, No response or command came from the target!
I/kickstart(  871): WARNING: function: sahara_start:892 Retrying memory read request
E/native  ( 1233): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1233): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
I/ActivityManager(  819): Killing 3629:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
E/native  ( 1233): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1233): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1233): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1233): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/SQLiteDatabase( 4382): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 4382): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4382): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4382): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4382): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4382): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4382): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4382): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4382): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4382): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4382): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4382): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4382): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4382): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4382): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4382): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/SQLiteDatabase( 4382): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/SQLiteDatabase( 4382): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:370)
E/SQLiteDatabase( 4382): 	at android.content.ContentResolver.call(ContentResolver.java:1372)
E/SQLiteDatabase( 4382): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/SQLiteDatabase( 4382): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2609)
E/SQLiteDatabase( 4382): 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
E/SQLiteDatabase( 4382): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1380)
E/SQLiteDatabase( 4382): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4382): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 4382): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
E/SQLiteDatabase( 4382): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 4382): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 4382): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
E/SQLiteDatabase( 4382): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/AndroidRuntime( 4382): Shutting down VM
--------- beginning of crash
E/AndroidRuntime( 4382): FATAL EXCEPTION: main
E/AndroidRuntime( 4382): Process: com.android.documentsui, PID: 4382
E/AndroidRuntime( 4382): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4382): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2616)
E/AndroidRuntime( 4382): 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
E/AndroidRuntime( 4382): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1380)
E/AndroidRuntime( 4382): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4382): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 4382): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
E/AndroidRuntime( 4382): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 4382): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 4382): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
E/AndroidRuntime( 4382): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
E/AndroidRuntime( 4382): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4382): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4382): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 4382): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 4382): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4382): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4382): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4382): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AndroidRuntime( 4382): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AndroidRuntime( 4382): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 4382): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AndroidRuntime( 4382): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 4382): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 4382): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 4382): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/AndroidRuntime( 4382): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/AndroidRuntime( 4382): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:370)
E/AndroidRuntime( 4382): 	at android.content.ContentResolver.call(ContentResolver.java:1372)
E/AndroidRuntime( 4382): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/AndroidRuntime( 4382): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2609)
E/AndroidRuntime( 4382): 	... 9 more
I/ActivityManager(  819): Start proc 4404:com.android.externalstorage/u0a10 for content provider com.android.externalstorage/.ExternalStorageProvider
I/ActivityManager(  819): Killing 3649:com.google.android.apps.magazines/u0a67 (adj 15): empty #17
I/ActivityManager(  819): Killing 3713:com.android.chrome/u0a40 (adj 15): empty #17
D/GCM     ( 1281): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
E/DropBoxManagerService(  819): Can't write: system_app_crash
E/DropBoxManagerService(  819): java.io.FileNotFoundException: /data/system/dropbox/drop98.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  819): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  819): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  819): 	at java.io,.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  819): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  819): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  819): 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
E/DropBoxManagerService(  819): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  819): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  819): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  819): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  819): 	... 5 more
D/ExternalStorage( 4404): After updating volumes, found 1 active roots
D/OpenGLRenderer(  819): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
D/Atlas   (  819): Validating map...
D/AuthorizationBluetoothService( 1281): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GmsCoreStatsServiceLauncher( 1774): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
D/WearableService( 4324): callingUid 10011, callindPid: 4324
D/LocationInitializer( 1774): Restart initialization of location
D/WifiService(  819): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@304d350c}
I/OpenGLRenderer(  819): Initialized EGL, version 1.4
I/GAv4    ( 4364): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4364):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4364):   adb logcat -s GAv4
D/OpenGLRenderer(  819): Enabling debug mode 0
W/GAv4    ( 4364): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
E/SQLiteDatabase( 1281): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 1281): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1281): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1281): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1281): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1281): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1281): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1281): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1281): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1281): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1281): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1281): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 1281): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 1281): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 1281): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1281): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 1281): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:99)
E/SQLiteDatabase( 1281): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/SQLiteDatabase( 1281): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/SQLiteDatabase( 1281): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/SQLiteDatabase( 1281): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 1281): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 1281): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteOpenHelper( 1281): Couldn't open phenotype.db for writing (will try read-only):
E/SQLiteOpenHelper( 1281): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1281): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1281): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 1281): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 1281): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1281): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1281): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1281): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteOpenHelper( 1281): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteOpenHelper( 1281): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 1281): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteOpenHelper( 1281): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 1281): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 1281): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 1281): 	at android.databa
```
