#### Test 575312431745da8_thali05_motorola-Nexus 6 Logs


```
--------- beginning of system
I/ActivityManager(  822): Waited long enough for: ServiceRecord{250a035b u0 com.motorola.android.buacontactadapter/.AuthenticationService}
,--------- beginning of main
D/AndroidRuntime( 3608): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 3608): CheckJNI is OFF
D/AndroidRuntime( 3608): Calling main entry com.android.commands.am.Am
I/ActivityManager(  822): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/WindowManager(  822): addAppToken: AppWindowToken{37db253 token=Token{7bc3242 ActivityRecord{398c108d u0 com.test.thalitest/.MainActivity t28}}} to stack=1 task=28 at 0
V/WindowManager(  822): Adding window Window{13f86cbc u0 Starting com.test.thalitest} at 2 of 7 (after Window{fe79329 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
D/AndroidRuntime( 3608): Shutting down VM
I/HotwordDetector( 1487): Closing mic
I/MicrophoneInputStream( 1487): mic_close com.google.android.apps.gsa.speech.audio.u@d2a9851
I/ActivityManager(  822): Start proc 3622:com.test.thalitest/u0a265 for activity com.test.thalitest/.MainActivity
D/audio_hw_primary(  357): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  357): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  357): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1487): Hotword detection finished
I/HotwordRecognitionRnr( 1487): Stopping hotword detection.
I/ActivityManager(  822): Killing 3263:com.android.settings/1000 (adj 15): empty #17
E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1660798227
E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,I/WebViewFactory( 3622): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3622): Time to load native libraries: 3 ms (timestamps 4521-4524)
I/LibraryLoader( 3622): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3622): Binding Chromium to main looper Looper (main, tid 1) {7ed4fb0}
,I/LibraryLoader( 3622): Expected native library version number "",actual native library version number ""
I/chromium( 3622): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3622): Initializing chromium process, singleProcess=true
,W/art     ( 3622): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3622): ApplicationContext is null in ApplicationStatus
,W/chromium( 3622): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3622): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3622): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3622): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,I/ActivityManager(  822): Killing 3391:com.google.android.partnersetup/u0a16 (adj 15): empty #17,
,D/BluetoothManagerService(  822): Message: 20
D/BluetoothManagerService(  822): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3149aff2:true
,I/ActivityManager(  822): Killing 3280:com.google.android.apps.maps/u0a65 (adj 15): empty #18
,W/art     ( 3622): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3622): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3622): CordovaWebView is running on device made by: motorola
,W/art     ( 3622): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 3622): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3622): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,D/Atlas   ( 3622): Validating map...
,V/WindowManager(  822): Adding window Window{3aa0f91c u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{13f86cbc u0 Starting com.test.thalitest})
,W/chromium( 3622): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3622): Initialized EGL, version 1.4,
,D/OpenGLRenderer( 3622): Enabling debug mode 0,
,I/ActivityManager(  822): Displayed com.test.thalitest/.MainActivity: +1s94ms
,I/Keyboard.Facilitator( 1234): onFinishInput()
,W/BindingManager( 3622): Cannot call determinedVisibility() - never saw a connection for the pid: 3622
,D/JsMessageQueue( 3622): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3622): JniHelper::setJavaVM(0xb489d200), pthread_self() = -1576402432
,I/chromium( 3622): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 3622): Initializing JXcore engine
W/jxcore-log( 3622): JXcore engine is ready
,W/Thread-398( 3676): type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[12994]" dev="sockfs" ino=12994 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-398( 3676): type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,W/Thread-398( 3676): type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[9935]" dev="sockfs" ino=9935 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/Thread-398( 3676): type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[21999]" dev="sockfs" ino=21999 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 3622): Starting JXcore engine,
,W/jxcore-log( 3622): Platform android
W/jxcore-log( 3622): 
W/jxcore-log( 3622): Process ARCH arm
W/jxcore-log( 3622): 
,I/jxcore-log( 3622): JXcore Cordova bridge is ready!
I/jxcore-log( 3622): 
,W/jxcore-log( 3622): JXcore engine is started
,V/GLSActivity( 1137): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1137): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1137): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1137): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1137): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1137): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3480): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3480): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3480): [1] 5.onFinished: Scheduling replication attempt 1.
,I/jxcore-log( 3622): Toggling radios to true
I/jxcore-log( 3622): 
,D/BluetoothAdapter( 3622): enable(): BT is already enabled..!
,D/WifiService(  822): setWifiEnabled: true pid=3622, uid=10265
E/WifiService(  822): Invoking mWifiStateMachine.setWifiEnabled
D/WifiService(  822): New client listening to asynchronous messages
,I/jxcore-log( 3622): Radios toggled
I/jxcore-log( 3622): 
I/jxcore-log( 3622): My device name is: motorola-Nexus 6,
I/jxcore-log( 3622): 
,I/wpa_supplicant( 1057): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  822): WifiStateMachine: Leaving Connected state
,E/WifiConfigStore(  822): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  353): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1137): Read error: ssl=0xaed57e00: I/O error during system call, Connection timed out
V/NativeCrypto( 1137): SSL shutdown failed: ssl=0xaed57e00: I/O error during system call, Broken pipe
D/ConnectivityService(  822): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10011
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): DefaultState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): Forcing reevaluation
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): EvaluatingState{ when=0 what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
,D/ConnectivityService(  822): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  822): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
,E/WifiStateMachine(  822): Start Disconnecting Watchdog 1
,E/WifiStateMachine(  822): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,D/CommandListener(  353): Clearing all IP addresses on wlan0
,D/ConnectivityService(  822): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/CSLegacyTypeTracker(  822): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/WifiNetworkAgent(  822): NetworkAgent: NetworkAgent channel lost
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): OfflineState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): Disconnected - quitting
D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityManager.CallbackHandler( 1066): CM callback handler got msg 524292
,D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/Tethering(  822): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 3024): type=WIFI subType= reason=null isConnected=false
,E/WifiStateMachine(  822): CMD_AUTO_CONNECT sup state CompletedState my state DisconnectedState nid=0 roam=3
E/WifiStateMachine(  822): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=0
,D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  822): MasterInitialState.processMessage what=3
,D/ConnectivityService(  822): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,V/MusicLeanback( 3024): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/ConnectivityService(  822): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
E/ConnectivityService(  822): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,D/PhoneInterfaceManager( 1325): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
,E/PhoneInterfaceManager( 1325): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
D/TelephonyManager(  822): getDataEnabled: retVal=false
,E/WifiConfigStore(  822): Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiConfigStore(  822): will read network variables netId=0
,I/ActivityManager(  822): Start proc 3684:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,E/WifiStateMachine(  822): CMD_AUTO_CONNECT did save config ->  nid=0
,E/WifiConfigStore(  822): will read network variables netId=0
,E/GpsLocationProvider(  822): No APN found to select.
,D/PhoneInterfaceManager( 1325): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
,E/PhoneInterfaceManager( 1325): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
D/TelephonyManager(  822): getDataEnabled: retVal=false
,E/GpsLocationProvider(  822): No APN found to select.
,D/SprintDMReceiver( 3684): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3684): simOperator:  IMSI: null
D/SprintDMReceiver( 3684): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1769): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1769): onCreate
,D/SystemUpdateService( 1769): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1769): active receiver: enabled
,I/SystemUpdateService( 1769): showing system update notification
,I/iu.Environment( 1769): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1769): num queued entries: 0
I/ValidateNoPeople(  822): skipping global notification
I/iu.UploadsManager( 1769): num updated entries: 0
,V/SystemUpdateService( 1769): retry (wakeup: false) in 3599982 ms
,I/iu.SyncManager( 1769): NEXT; no task
,D/ChimeraCfgMgr( 1769): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 1769): [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
,D/SystemUpdateService( 1769): onDestroy
,I/Babel   ( 2786): connection state changed from CONNECTED to DISCONNECTED
,I/ActivityManager(  822): Start proc 3704:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,I/ActivityManager(  822): Killing 3412:com.android.musicfx/u0a18 (adj 15): empty #17
,I/art     (  368): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 318us total 24.284ms
,I/art     (  368): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 315us total 13.083ms
,I/art     (  368): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 319us total 13.037ms
,I/GAv4    ( 3704): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3704):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3704):   adb logcat -s GAv4
,W/GAv4    ( 3704): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3704): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3704): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 3704): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3704): Time to load native libraries: 1 ms (timestamps 8314-8315),
,I/LibraryLoader( 3704): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3704): Binding Chromium to main looper Looper (main, tid 1) {1a5bf817}
I/LibraryLoader( 3704): Expected native library version number "",actual native library version number ""
I/chromium( 3704): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3704): Initializing chromium process, singleProcess=true
,W/art     ( 3704): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3704): ApplicationContext is null in ApplicationStatus
,W/chromium( 3704): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3704): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3704): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3704): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,I/NSApplication( 3704): Starting up...
,W/AudioManagerAndroid( 3704): Requires BLUETOOTH permission,
,I/ActivityManager(  822): Start proc 3760:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
I/ActivityManager(  822): Killing 3442:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,I/art     (  822): Explicit concurrent mark sweep GC freed 31983(1549KB) AllocSpace objects, 5(80KB) LOS objects, 32% free, 33MB/49MB, paused 1.366ms total 70.168ms
,I/ActivityManager(  822): Killing 1433:android.process.acore/u0a5 (adj 15): empty #17
,V/MusicLeanback( 3024): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/SprintDMReceiver( 3684): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,I/wpa_supplicant( 1057): wlan0: Trying to associate with SSID 'NG7005g'
,D/SprintDMHelper( 3684): simOperator:  IMSI: null
D/SprintDMReceiver( 3684): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1769): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1769): onCreate
,D/SystemUpdateService( 1769): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1769): active receiver: enabled
,I/SystemUpdateService( 1769): showing system update notification
,D/ChimeraCfgMgr( 1769): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 1769): [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
,I/ValidateNoPeople(  822): skipping global notification
,V/SystemUpdateService( 1769): retry (wakeup: false) in 3599972 ms
,D/SystemUpdateService( 1769): onDestroy
,I/art     ( 1487): WaitForGcToComplete blocked for 16.892ms for cause HomogeneousSpaceCompact
,I/wpa_supplicant( 1057): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 1057): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 1057): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=0 id_str=]
,D/ConnectivityService(  822): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} }
D/ConnectivityService(  822): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiConfigStore(  822): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiConfigStore(  822): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  353): Setting iface cfg
,E/WifiStateMachine(  822): Start Dhcp Watchdog 2
,E/WifiStateMachine(  822):  WifiLinkLayerStats: 
E/WifiStateMachine(  822):  my bss beacon rx: 210
E/WifiStateMachine(  822):  RSSI mgmt: -52
E/WifiStateMachine(  822):  BE :  rx=173 tx=145 lost=0 retries=0
E/WifiStateMachine(  822):  BK :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  822):  VI :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  822):  VO :  rx=4 tx=0 lost=0 retries=0
E/WifiStateMachine(  822):  on_time : 8901 tx_time=160 rx_time=342 scan_time=0
,D/ConnectivityService(  822): updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,E/native  (  822): do suspend false
,E/WifiStateMachine(  822): scanCount==0 - aborting
,I/dhcpcd  ( 3791): version 5.5.6 starting
,I/dhcpcd  ( 3791): wlan0: rebinding lease of 192.168.1.122
,I/dhcpcd  ( 3791): wlan0: acknowledged 192.168.1.122 from 192.168.1.1
,I/dhcpcd  ( 3791): wlan0: leased 192.168.1.122 for 86400 seconds
,I/jxcore-log( 3622): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 3622): 
,D/ConnectivityService(  822): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED,
,D/ConnectivityService(  822): Adding iface wlan0 to network 101
,E/WifiStateMachine(  822): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  822): Unexpected mtu value: 0, wlan0
,D/ConnectivityService(  822): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/ConnectivityService(  822): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  822): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  822): Setting Dns servers for network 101 to [/192.168.1.1]
,D/ConnectivityService(  822): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  822): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  822): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  822): Connected
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  822): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  822): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
D/ConnectivityService(  822): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  822):    accepting network in place of null
,D/ConnectivityService(  822): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} }
D/ConnectivityService(  822): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler( 1066): CM callback handler got msg 524290
,D/CSLegacyTypeTracker(  822): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  822): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 3024): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 3024): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/ActivityManager(  822): Start proc 3825:com.google.android.keep/u0a79 for service com.google.android.keep/.syncadapter.KeepSyncAdapterService
,D/PhoneInterfaceManager( 1325): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1325): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/SprintDMReceiver( 3684): Received intent: android.net.conn.CONNECTIVITY_CHANGE
D/TelephonyManager(  822): getDataEnabled: retVal=false
D/AlarmManagerService(  822): Setting time of day to sec=1454593014
W/AlarmManagerService(  822): Unable to set rtc to 1454593014: Invalid argument
D/SprintDMHelper( 3684): simOperator:  IMSI: null
D/SprintDMReceiver( 3684): Not Sprint UICC, don't do anything.
I/SystemUpdateService( 1769): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
D/SystemUpdateService( 1769): onCreate
,D/SystemUpdateService( 1769): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,E/GpsLocationProvider(  822): No APN found to select.
,I/iu.Environment( 1769): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1769): num queued entries: 0
I/iu.UploadsManager( 1769): num updated entries: 0
I/iu.SyncManager( 1769): NEXT; no task
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  822): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 04 Feb 2016 13:36:54 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454593014144], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454593014128]}
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  822): Validated
D/ConnectivityService(  822): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/ConnectivityService(  822): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  822): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  822): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  822): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1066): CM callback handler got msg 524290
,I/SystemUpdateService( 1769): active receiver: enabled
,D/ChimeraCfgMgr( 1769): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 1769): [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
,I/SystemUpdateService( 1769): showing system update notification
,I/ValidateNoPeople(  822): skipping global notification
,V/SystemUpdateService( 1769): retry (wakeup: false) in 3599933 ms
,D/SystemUpdateService( 1769): onDestroy
,I/art     ( 1137): Explicit concurrent mark sweep GC freed 27569(1381KB) AllocSpace objects, 3(330KB) LOS objects, 38% free, 25MB/41MB, paused 2.258ms total 81.746ms
,I/GLSUser ( 1137): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1137): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1137): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1137): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1137): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Babel   ( 2786): connection state changed from DISCONNECTED to CONNECTED
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=9.50 rxSuccessRate=11.19 targetRoamBSSID=any RSSI=-52
E/WifiStateMachine(  822): WifiStateMachine L2Connected CMD_START_SCAN source -2 5, 7 -> obsolete
,E/HttpOperation( 3199): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3199): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3199): 	at jdm.a(PG:82)
E/HttpOperation( 3199): 	at jcs.o(PG:406)
E/HttpOperation( 3199): 	at jcn.a(PG:1379)
E/HttpOperation( 3199): 	at jcs.i(PG:143)
E/HttpOperation( 3199): 	at blb.a(PG:3937)
E/HttpOperation( 3199): 	at czp.a(PG:18188)
E/HttpOperation( 3199): 	at czp.a(PG:9081)
E/HttpOperation( 3199): 	at czq.run(PG:1686)
E/HttpOperation( 3199): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3199): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3199): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3199): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3199): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3199): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3199): 	at jdj.a(PG:4091)
E/HttpOperation( 3199): 	at jdj.a(PG:1125)
E/HttpOperation( 3199): 	at jdm.a(PG:77)
E/HttpOperation( 3199): 	... 12 more
E/HttpOperation( 3199): Caused by: faj: BadAuthentication
E/HttpOperation( 3199): 	at fal.a(PG:38)
E/HttpOperation( 3199): 	at jdj.a(PG:4089)
E/HttpOperation( 3199): 	... 14 more
,I/ActivityManager(  822): Start proc 3863:com.qualcomm.timeservice/1000 for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver
,I/GLSUser ( 1137): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1137): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1137): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1137): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1137): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3199): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3199): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3199): 	at jdm.a(PG:82)
E/HttpOperation( 3199): 	at jcs.o(PG:406)
E/HttpOperation( 3199): 	at jcn.a(PG:1379)
E/HttpOperation( 3199): 	at jcs.i(PG:143)
E/HttpOperation( 3199): 	at hec.a(PG:42)
E/HttpOperation( 3199): 	at hee.a(PG:102)
E/HttpOperation( 3199): 	at czr.a(PG:65)
E/HttpOperation( 3199): 	at kka.a(PG:108)
E/HttpOperation( 3199): 	at czp.a(PG:19176)
E/HttpOperation( 3199): 	at czp.a(PG:9081)
E/HttpOperation( 3199): 	at czq.run(PG:1686)
E/HttpOperation( 3199): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3199): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3199): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3199): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3199): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3199): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3199): 	at jdj.a(PG:4091)
E/HttpOperation( 3199): 	at jdj.a(PG:1125)
E/HttpOperation( 3199): 	at jdm.a(PG:77)
E/HttpOperation( 3199): 	... 15 more
E/HttpOperation( 3199): Caused by: faj: BadAuthentication
E/HttpOperation( 3199): 	at fal.a(PG:38)
E/HttpOperation( 3199): 	at jdj.a(PG:4089)
E/HttpOperation( 3199): 	... 17 more
,E/ExperimentLoader( 3199): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3199): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3199): 	at jdm.a(PG:82)
E/ExperimentLoader( 3199): 	at jcs.o(PG:406)
E/ExperimentLoader( 3199): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3199): 	at jcs.i(PG:143)
E/ExperimentLoader( 3199): 	at hec.a(PG:42)
E/ExperimentLoader( 3199): 	at hee.a(PG:102)
E/ExperimentLoader( 3199): 	at czr.a(PG:65)
E/ExperimentLoader( 3199): 	at kka.a(PG:108)
E/ExperimentLoader( 3199): 	at czp.a(PG:19176)
E/ExperimentLoader( 3199): 	at czp.a(PG:9081)
E/ExperimentLoader( 3199): 	at czq.run(PG:1686)
E/ExperimentLoader( 3199): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3199): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3199): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3199): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3199): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3199): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3199): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3199): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3199): 	at jdm.a(PG:77)
E/ExperimentLoader( 3199): 	... 15 more
E/ExperimentLoader( 3199): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3199): 	at fal.a(PG:38)
E/ExperimentLoader( 3199): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3199): 	... 17 more
,D/TimeService( 3863): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1454593014372
D/        ( 3863): TimeServiceNative: User Time to be set is 1454593014373
D/QC-time-services( 3863): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 3863): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 3863): Lib:time_genoff_operation: pargs->ts_val = 1454593014373
D/QC-time-services(  372): Daemon: Connection accepted:time_genoff
D/QC-time-services( 3863): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  372): Daemon:Received base = 2, unit = 1, operation = 0,value = 1454593014373
D/QC-time-services(  372): Daemon:genoff_opr: Base = 2, val = 1454593014373, operation = 0
D/QC-time-services(  372): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS5/22/70 9:49:16
D/QC-time-services(  372): Daemon:Value read from RTC seconds = 14896156000
D/QC-time-services(  372): Daemon:new time 1454593014373 
D/QC-time-services(  372): Daemon: delta 1439696858373 genoff 1439696858373 
D/QC-time-services(  372): Daemon:genoff_persistent_update: Writing genoff = 1439696858373 to memory
D/QC-time-services(  372): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  372): Daemon:time_persistent_memory_opr:Genoff write operation 
D/QC-time-services(  372): Updating the TOD offset
D/QC-time-services(  372): Daemon:genoff_persistent_update: Writing genoff = 1439696858373 to memory
D/QC-time-services(  372): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  372): Daemon:time_persistent_memory_opr:Genoff write operation 
E/QC-time-services(  372): Daemon:Update to modem bit set
D/QC-time-services(  372): Daemon:genoff_send_modem: Sending data to MODEM !
E/QC-time-services( 3863): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
D/QC-time-services(  372): Daemon: Base = 2, Value being sent to MODEM = 1138628214373
D/GCM     ( 1137): Connected
D/GCM     ( 1137): Message class com.google.f.a.a.p
,V/KeepSync( 3825): Connecting to GoogleApiClient
,E/QC-time-services(  372): Daemon: Time-services: Waiting to acceptconnection
,E/QC-time-services(  372): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,I/ActivityManager(  822): Start proc 3886:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 74116, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1137): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1137): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1137): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1137): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1137): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  822): Start proc 3903:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,I/GAv4    ( 3886): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3886):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3886):   adb logcat -s GAv4
E/ClientConnectionOperation( 1769): Handling authorization failure
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
,V/KeepSync( 3825): GoogleApiClient failed to connect with error code: 4
E/SQLiteLog( 3825): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3825): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3825): (284) automatic index on blob_node(is_deleted)
W/GAv4    ( 3886): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3886): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3886): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/GAV2    ( 3903): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/ActivityManager(  822): Killing 2924:com.google.android.gm/u0a78 (adj 15): empty #17
,I/jxcore-log( 3622): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 3622): 
,V/Herrevad( 1769): NQAS connected
,I/BooksApp( 3903): Created application version: 3.6.8 (30608)
,I/GLSUser ( 1137): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1137): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1137): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1137): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/jxcore-log( 3622): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 3622): 
,I/art     (  822): Explicit concurrent mark sweep GC freed 39980(1919KB) AllocSpace objects, 6(96KB) LOS objects, 32% free, 33MB/49MB, paused 1.180ms total 51.773ms
I/jxcore-log( 3622): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
I/jxcore-log( 3622): 
,I/jxcore-log( 3622): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 3622): 
,V/GLSActivity( 1137): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/BooksSync( 3903): Starting books sync for 61035162, extras: ade
,E/KeepSync( 3825): IOException
E/KeepSync( 3825): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3825): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3825): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3825): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3825): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3825): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3825): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3825): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3825): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3825): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3825): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3825): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3825): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3825): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3825): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3825): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3825): 	... 10 more
W/KeepSync( 3825): Sync result 2
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 74366, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
I/ActivityManager(  822): Killing 3520:com.google.android.gms:car/u0a11 (adj 15): empty #17
,I/BooksConfig( 3903): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1137): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1137): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1137): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1137): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1137): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1137): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1137): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1137): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1137): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1137): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/BooksAccountManager( 3903): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication,
E/BooksSync( 3903): Soft error
E/BooksSync( 3903): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3903): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3903): Sync error
E/BooksSync( 3903): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3903): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3903): Finished books sync
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 76983, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  822): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/ActivityManager(  822): Killing 3347:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,I/GAV2    ( 3903): Thread[GAThread,5,main]: No campaign data found.
,I/jxcore-log( 3622): Test app app.js loaded,
I/jxcore-log( 3622): 
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3622): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3622): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3622): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3622): 	Bluetooth MAC address: F8:CF:C5:D9:E5:61, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3622): 	Discovery mode: BLE_AND_WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3622): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3622): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3622): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3622): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3622): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ec95cba added. We now have 1 listener(s)
,I/chromium( 3622): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/jxcore-log( 3622): BLE advertisement is supported
I/jxcore-log( 3622): 
,I/ActivityManager(  822): Killing 3480:com.android.vending/u0a19 (adj 15): empty #17
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=9.88 rxSuccessRate=12.55 targetRoamBSSID=any RSSI=-52
E/WifiStateMachine(  822): WifiStateMachine L2Connected CMD_START_SCAN source -2 6, 7 -> obsolete
,I/ActivityManager(  822): Start proc 3955:com.android.vending/u0a19 for service com.android.vending/com.google.android.finsky.services.ContentFiltersService
,D/Finsky  ( 3955): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 3955): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,I/ActivityManager(  822): Start proc 3991:com.google.android.gms:car/u0a11 for service com.google.android.gms/.car.CarService
,W/Settings( 3955): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 3955): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ResourcesManager( 3991): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 3991): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  822): Killing 3024:com.google.android.music:main/u0a66 (adj 15): empty #17
,D/Finsky  ( 3955): [414] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,I/MultiDex( 3991): VM with version 2.1.0 has multidex support
I/MultiDex( 3991): install
I/MultiDex( 3991): VM has multidex support, MultiDex support library is disabled.
,V/GLSActivity( 1137): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3955): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3955): [1] 2.run: Finished loading 1 libraries.
,D/Finsky  ( 3955): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,V/JNIHelp ( 3991): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/Finsky  ( 3955): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/GLSUser ( 1137): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1137): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1137): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1137): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1137): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3955): [414] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,I/ProviderInstaller( 3991): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 1137): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1137): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 1769): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,I/ActivityManager(  822): Start proc 4019:com.google.android.gms.wearable/u0a11 for service com.google.android.gms/.wearable.service.WearableService
,D/LocationInitializer( 1769): Restart initialization of location
,W/ResourcesManager( 4019): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 4019): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/art     ( 1137): Explicit concurrent mark sweep GC freed 25325(1499KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 1.650ms total 41.847ms
,I/MultiDex( 4019): VM with version 2.1.0 has multidex support
I/MultiDex( 4019): install
I/MultiDex( 4019): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 4019): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ProviderInstaller( 4019): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 1137): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1137): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 1769): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/WearableService( 4019): callingUid 10011, callindPid: 4019
,E/MDM     ( 1796): [143] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 1769): Restart initialization of location
,E/MDM     ( 1796): [143] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,V/Finsky  ( 3955): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,D/Finsky  ( 3955): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/GLSActivity( 1137): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1137): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1137): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1137): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1137): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1137): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 3955): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1137): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1137): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1137): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
,I/GLSUser ( 1137): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1137): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1137): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1137): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1137): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1137): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1137): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1137): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1137): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 3955): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1137): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  822): Explicit concurrent mark sweep GC freed 31129(1430KB) AllocSpace objects, 3(48KB) LOS objects, 32% free, 33MB/49MB, paused 2.131ms total 99.760ms
,I/GLSUser ( 1137): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1137): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1137): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1137): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1137): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 3955): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 3955): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 3955): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3955): [1] DailyHygiene.reschedule: Scheduling new run in 271 minutes (failures=4)
,D/DeviceConnectionService( 1796): client connected with version: 7571000
,I/ActivityManager(  822): Killing 3684:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,I/ActivityManager(  822): Killing 3704:com.google.android.apps.magazines/u0a67 (adj 15): empty #17
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=1.28 rxSuccessRate=4.52 targetRoamBSSID=any RSSI=-52
,V/GLSActivity( 1137): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1137): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1137): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1137): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1137): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,V/GLSActivity( 1137): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3955): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3955): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3955): [1] 5.onFinished: Scheduling replication attempt 2.
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.79 rxSuccessRate=3.78 targetRoamBSSID=any RSSI=-51
,E/WifiStateMachine(  822): WifiStateMachine starting scan for "NG7005g"WPA_PSK with 2412,5220
,D/HeadsetStateMachine( 2194): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2194): Disconnected process message: 10, size: 0
,I/BooksSync( 3903): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3903): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1137): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1137): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1137): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1137): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1137): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1137): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1137): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1137): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1137): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1137): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3199): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3199): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3199): 	at jdm.a(PG:82)
E/HttpOperation( 3199): 	at jcs.o(PG:406)
E/HttpOperation( 3199): 	at jcn.a(PG:1379)
E/HttpOperation( 3199): 	at jcs.i(PG:143)
E/HttpOperation( 3199): 	at blb.a(PG:3937)
E/HttpOperation( 3199): 	at czp.a(PG:18188)
E/HttpOperation( 3199): 	at czp.a(PG:9081)
E/HttpOperation( 3199): 	at czq.run(PG:1686)
E/HttpOperation( 3199): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3199): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3199): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3199): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3199): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3199): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3199): 	at jdj.a(PG:4091)
E/HttpOperation( 3199): 	at jdj.a(PG:1125)
E/HttpOperation( 3199): 	at jdm.a(PG:77)
E/HttpOperation( 3199): 	... 12 more
E/HttpOperation( 3199): Caused by: faj: BadAuthentication
E/HttpOperation( 3199): 	at fal.a(PG:38)
E/HttpOperation( 3199): 	at jdj.a(PG:4089)
E/HttpOperation( 3199): 	... 14 more
,I/GLSUser ( 1137): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1137): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1137): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1137): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1137): [GLSUser] Extracting token using key: Auth
I/GLSUser ( 1137): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1137): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
W/GLSActivity( 1137): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1137): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
V/GLSActivity( 1137): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3199): [getmobileexperiments] Unexpected exception,
E/HttpOperation( 3199): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3199): 	at jdm.a(PG:82)
E/HttpOperation( 3199): 	at jcs.o(PG:406)
E/HttpOperation( 3199): 	at jcn.a(PG:1379)
E/HttpOperation( 3199): 	at jcs.i(PG:143)
E/HttpOperation( 3199): 	at hec.a(PG:42)
E/HttpOperation( 3199): 	at hee.a(PG:102)
E/HttpOperation( 3199): 	at czr.a(PG:65),
E/HttpOperation( 3199): 	at kka.a(PG:108)
,E/HttpOperation( 3199): 	at czp.a(PG:19176)
E/HttpOperation( 3199): 	at czp.a(PG:9081)
E/HttpOperation( 3199): 	at czq.run(PG:1686)
E/HttpOperation( 3199): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3199): 	,at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3199): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3199): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3199): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3199): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3199): 	at jdj.a(PG:4091)
E/HttpOperation( 3199): 	at jdj.a(PG:1125)
E/HttpOperation( 3199): 	at jdm.a(PG:77)
E/HttpOperation( 3199): 	... 15 more
E/HttpOperation( 3199): Caused by: faj: BadAuthentication
E/HttpOperation( 3199): 	at fal.a(PG:38)
E/HttpOperation( 3199): 	at jdj.a(PG:4089)
E/HttpOperation( 3199): 	... 17 more
,E/ExperimentLoader( 3199): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3199): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3199): 	at jdm.a(PG:82)
E/ExperimentLoader( 3199): 	at jcs.o(PG:406)
E/ExperimentLoader( 3199): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3199): 	at jcs.i(PG:143)
E/ExperimentLoader( 3199): 	at hec.a(PG:42)
E/ExperimentLoader( 3199): 	at hee.a(PG:102)
,E/ExperimentLoader( 3199): 	at czr.a(PG:65)
E/ExperimentLoader( 3199): 	at kka.a(PG:108)
E/ExperimentLoader( 3199): 	at czp.a(PG:19176)
E/ExperimentLoader( 3199): 	at czp.a(PG:9081)
E/ExperimentLoader( 3199): 	at czq.run(PG:1686)
E/ExperimentLoader( 3199): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3199): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3199): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3199): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3199): 	at java.lang.Thread.run(Thread.java:818)
,E/ExperimentLoader( 3199): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3199): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3199): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3199): 	at jdm.a(PG:77)
E/ExperimentLoader( 3199): 	... 15 more
E/ExperimentLoader( 3199): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3199): 	at fal.a(PG:38)
E/ExperimentLoader( 3199): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3199): 	... 17 more
,E/BooksAccountManager( 3903): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3903): Soft error
E/BooksSync( 3903): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3903): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3903): Sync error
E/BooksSync( 3903): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3903): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 3903): Finished books sync
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 113481, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,V/KeepSync( 3825): Connecting to GoogleApiClient
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 114181, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1137): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1137): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1137): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1137): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1137): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1769): Handling authorization failure,
E/ClientConnectionOperation( 1769): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
,E/ClientConnectionOperation( 1769): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62),
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1769): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
,E/ClientConnectionOperation( 1769): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1769): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1769): Caused by: com.google.android.gms.auth.ad: BadAuthentication,
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.auth.p.a(SourceFile:310),
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1769): 	,at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1769): ,	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.common.server.o.a(SourceFile:340),
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1769): ,	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1769): 	,at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1769): 	... 7 more
,V/KeepSync( 3825): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3825): (284) automatic index on blob_node(is_deleted),
,E/SQLiteLog( 3825): (284) automatic index on blob_node(is_deleted),
E/SQLiteLog( 3825): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1137): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1137): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1137): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1137): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1137): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3825): IOException
E/KeepSync( 3825): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3825): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3825): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3825): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3825): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3825): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3825): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3825): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3825): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3825): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3825): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3825): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3825): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3825): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3825): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3825): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3825): 	... 10 more
W/KeepSync( 3825): Sync result 2
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 115349, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,V/GLSActivity( 1137): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1137): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1137): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1137): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1137): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1137): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3955): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3955): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3955): [1] 5.onFinished: Scheduling replication attempt 3.
,I/Keyboard.Facilitator.LanguageModelFlusher( 1234): run()
I/Keyboard.Facilitator( 1234): flushDynamicLanguageModels()
,I/ConfigService( 1137): onCreate
,I/ConfigService( 1137): onDestroy
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.35 rxSuccessRate=2.23 targetRoamBSSID=any RSSI=-51
,V/GLSActivity( 1137): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1137): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1137): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1137): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1137): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1137): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1137): Explicit concurrent mark sweep GC freed 36920(2MB) AllocSpace objects, 6(661KB) LOS objects, 37% free, 26MB/42MB, paused 2.408ms total 64.487ms
,D/Finsky  ( 3955): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3955): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3955): [1] 5.onFinished: Scheduling replication attempt 4.
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.83 rxSuccessRate=2.31 targetRoamBSSID=any RSSI=-51
,E/WifiStateMachine(  822): WifiStateMachine starting scan for "NG7005g"WPA_PSK with 2412,5220
,I/PowerManagerService(  822): Going to sleep due to screen timeout (uid 1000)...
,I/Adreno  (  822): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/PermissionCache(  259): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (378 us)
,I/DisplayManagerService(  822): Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager(  822): Display changed displayId=0
,D/SurfaceFlinger(  259): Set power mode=0, type=0 flinger=0xb6482000,
D/qdhwcomposer(  259): hwc_setPowerMode: Setting mode 0 on display: 0
,I/kickstart(  869): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
I/kickstart(  869): STATUS: Wrote to /sys/power/wake_lock
,E/kickstart(  869): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1,
I/kickstart(  869): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1' for writing
,I/qdhwcomposer(  259): handle_blank_event: dpy:0 panel power state: 0
,D/qdhwcomposer(  259): hwc_setPowerMode: Done setting mode 0 on display 0
D/SurfaceControl(  822): Excessive delay in setPowerMode(): 259ms
,I/DreamManagerService(  822): Entering dreamland.
I/PowerManagerService(  822): Dozing...
I/DreamController(  822): Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,D/audio_hw_primary(  357): adev_set_parameters: enter: screen_state=on
,D/mot_vr_audio_hw(  357): adev_set_parameters: screen_state=on
,E/WifiStateMachine(  822): cancelDelayedScan -> 12
,E/native  (  822): do suspend false
,I/Keyboard.Facilitator( 1234): onFinishInput()
,D/audio_hw_primary(  357): adev_set_parameters: enter: screen_state=off
,D/mot_vr_audio_hw(  357): adev_set_parameters: screen_state=off
,E/WifiStateMachine(  822): cancelDelayedScan -> 14,
E/native  (  822): do suspend true
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-51
E/WifiStateMachine(  822): WifiStateMachine L2Connected CMD_START_SCAN source -2 13, 14 -> obsolete
,I/kickstart(  869): STATUS: Received file 'm9kefs1'
,I/kickstart(  869): STATUS: 950272 bytes transferred in 0.984266 seconds
I/kickstart(  869): STATUS: Successfully downloaded files from target 
I/kickstart(  869): STATUS: Wrote to /sys/power/wake_unlock
,I/kickstart(  869): STATUS: Sahara protocol completed
,I/art     (  822): Explicit concurrent mark sweep GC freed 55083(2MB) AllocSpace objects, 22(540KB) LOS objects, 31% free, 34MB/50MB, paused 1.511ms total 94.409ms
,V/GLSActivity( 1137): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1137): Vacuum at: now=1454593110815 tag=VacuumService
,V/GLSActivity( 1137): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GoogleAuthProtoRequest( 3068): [301] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1137): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1137): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1137): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1137): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1137): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3955): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3955): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3955): [1] 5.onFinished: Scheduling replication attempt 5.
,I/GLSUser ( 1137): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1137): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1137): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1137): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1137): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3068): [301] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3068): [301] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3068): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3068): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3068): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3068): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3068): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3068): Caused by: com.a.a.a: User needs to (re)enter credentials.,
W/ExperimentUpdateService( 3068): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3068): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3068): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3068): 	at com.a.a.k.run(SourceFile:110)
,I/GoogleURLConnFactory( 1137): Using platform SSLCertificateSocketFactory
,I/GLSUser ( 1137): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1137): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1137): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1137): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1137): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1137): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1137): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1137): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1137): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1137): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1137): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1137): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1137): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1137): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1137): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1137): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1137): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1137): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1137): No account for auth token provided
,W/Uploader( 1137): No account for auth token provided
,I/GLSUser ( 1137): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1137): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1137): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1137): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1137): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1137): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1137): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1137): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1137): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1137): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1137): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1137): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1137): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1137): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1137): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1137): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1137): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1137): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1137): No account for auth token provided
,W/Uploader( 1137): No account for auth token provided
,W/Uploader( 1137): No account for auth token provided
,I/GLSUser ( 1137): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1137): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1137): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1137): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1137): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1137): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1137): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1137): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1137): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1137): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1137): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1137): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1137): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1137): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1137): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1137): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1137): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1137): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1137): No account for auth token provided
,W/Uploader( 1137): No account for auth token provided
,W/Uploader( 1137): No account for auth token provided
,W/Uploader( 1137): No account for auth token provided
,W/Uploader( 1137): No account for auth token provided
,W/Uploader( 1137):  no longer exists, so no auth token.
,I/GLSUser ( 1137): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1137): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1137): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1137): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1137): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1137): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1137): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1137): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1137): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1137): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1137): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1137): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1137): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1137): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1137): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1137): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1137): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1137): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-51
E/WifiStateMachine(  822): WifiStateMachine L2Connected CMD_START_SCAN source -2 11, 14 -> obsolete
,D/HeadsetStateMachine( 2194): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2194): Disconnected process message: 10, size: 0
,I/BooksSync( 3903): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3903): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1137): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1137): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1137): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1137): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1137): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1137): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1137): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1137): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1137): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1137): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3903): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3903): Soft error
E/BooksSync( 3903): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3903): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3903): Sync error
E/BooksSync( 3903): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3903): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3903): Finished books sync
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 194240, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,V/GLSActivity( 1137): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1137): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1137): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1137): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1137): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1137): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3955): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3955): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3955): [1] 5.onFinished: Giving up after 6 failures.
,I/Keyboard.Facilitator.LanguageModelFlusher( 1234): run()
I/Keyboard.Facilitator( 1234): flushDynamicLanguageModels()
,V/GoogleAuthProtoRequest( 3068): [302] a.<init>: mAccountName set to: thalitester@gmail.com
,I/ConfigService( 1137): onCreate
,I/GLSUser ( 1137): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1137): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1137): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1137): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1137): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3068): [302] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3068): [302] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3068): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3068): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3068): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3068): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3068): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3068): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3068): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3068): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3068): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3068): 	at com.a.a.k.run(SourceFile:110)
,V/KeepSync( 3825): Connecting to GoogleApiClient
,I/GLSUser ( 1137): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1137): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1137): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1137): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1137): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,V/KeepSync( 3825): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3825): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3825): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3825): (284) automatic index on blob_node(is_deleted)
,I/art     (  822): Explicit concurrent mark sweep GC freed 35027(1523KB) AllocSpace objects, 3(236KB) LOS objects, 31% free, 34MB/50MB, paused 1.362ms total 72.361ms
,I/GLSUser ( 1137): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1137): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1137): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1137): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1137): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3199): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3199): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3199): 	at jdm.a(PG:82)
E/HttpOperation( 3199): 	at jcs.o(PG:406)
E/HttpOperation( 3199): 	at jcn.a(PG:1379)
E/HttpOperation( 3199): 	at jcs.i(PG:143)
E/HttpOperation( 3199): 	at blb.a(PG:3937)
E/HttpOperation( 3199): 	at czp.a(PG:18188)
E/HttpOperation( 3199): 	at czp.a(PG:9081)
E/HttpOperation( 3199): 	at czq.run(PG:1686)
E/HttpOperation( 3199): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3199): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3199): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3199): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3199): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3199): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3199): 	at jdj.a(PG:4091)
E/HttpOperation( 3199): 	at jdj.a(PG:1125)
E/HttpOperation( 3199): 	at jdm.a(PG:77)
E/HttpOperation( 3199): 	... 12 more
E/HttpOperation( 3199): Caused by: faj: BadAuthentication
E/HttpOperation( 3199): 	at fal.a(PG:38)
E/HttpOperation( 3199): 	at jdj.a(PG:4089)
E/HttpOperation( 3199): 	... 14 more
,I/GLSUser ( 1137): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1137): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1137): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1137): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1137): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1137): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1137): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1137): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1137): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,V/GLSActivity( 1137): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1137): Explicit concurrent mark sweep GC freed 70234(3MB) AllocSpace objects, 8(724KB) LOS objects, 36% free, 27MB/43MB, paused 1.196ms total 41.832ms
,E/HttpOperation( 3199): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3199): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3199): 	at jdm.a(PG:82)
E/HttpOperation( 3199): 	at jcs.o(PG:406)
E/HttpOperation( 3199): 	at jcn.a(PG:1379)
E/HttpOperation( 3199): 	at jcs.i(PG:143)
E/HttpOperation( 3199): 	at hec.a(PG:42)
E/HttpOperation( 3199): 	at hee.a(PG:102)
E/HttpOperation( 3199): 	at czr.a(PG:65)
E/HttpOperation( 3199): 	at kka.a(PG:108)
E/HttpOperation( 3199): 	at czp.a(PG:19176)
E/HttpOperation( 3199): 	at czp.a(PG:9081)
E/HttpOperation( 3199): 	at czq.run(PG:1686)
E/HttpOperation( 3199): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3199): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3199): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3199): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3199): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3199): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3199): 	at jdj.a(PG:4091)
E/HttpOperation( 3199): 	at jdj.a(PG:1125)
E/HttpOperation( 3199): 	at jdm.a(PG:77)
E/HttpOperation( 3199): 	... 15 more
E/HttpOperation( 3199): Caused by: faj: BadAuthentication
E/HttpOperation( 3199): 	at fal.a(PG:38)
E/HttpOperation( 3199): 	at jdj.a(PG:4089)
E/HttpOperation( 3199): 	... 17 more
E/ExperimentLoader( 3199): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3199): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3199): 	at jdm.a(PG:82)
E/ExperimentLoader( 3199): 	at jcs.o(PG:406)
E/ExperimentLoader( 3199): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3199): 	at jcs.i(PG:143)
E/ExperimentLoader( 3199): 	at hec.a(PG:42)
E/ExperimentLoader( 3199): 	at hee.a(PG:102)
E/ExperimentLoader( 3199): 	at czr.a(PG:65)
E/ExperimentLoader( 3199): 	at kka.a(PG:108)
E/ExperimentLoader( 3199): 	at czp.a(PG:19176)
E/ExperimentLoader( 3199): 	at czp.a(PG:9081)
E/ExperimentLoader( 3199): 	at czq.run(PG:1686)
E/ExperimentLoader( 3199): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3199): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3199): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3199): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3199): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3199): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3199): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3199): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3199): 	at jdm.a(PG:77)
E/ExperimentLoader( 3199): 	... 15 more
E/ExperimentLoader( 3199): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3199): 	at fal.a(PG:38)
E/ExperimentLoader( 3199): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3199): 	... 17 more
,E/KeepSync( 3825): IOException
E/KeepSync( 3825): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3825): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3825): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3825): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3825): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3825): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3825): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3825): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3825): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3825): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3825): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3825): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3825): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3825): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3825): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3825): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3825): 	... 10 more
W/KeepSync( 3825): Sync result 2
D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 198640, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 196761, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/ConfigService( 1137): onDestroy
,D/HeadsetStateMachine( 2194): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2194): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2194): Disconnected process message: 10, size: 0
,I/BooksSync( 3903): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3903): GmsCore Version = 7.8.99 (2134222-430),
,I/GLSUser ( 1137): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1137): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1137): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1137): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1137): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1137): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1137): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1137): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1137): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1137): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/BooksAccountManager( 3903): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3903): Soft error
E/BooksSync( 3903): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3903): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3903): Sync error
E/BooksSync( 3903): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3903): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3903): Finished books sync
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 317237, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/WifiService(  822): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@280f9ee6}
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-51
,V/GoogleAuthProtoRequest( 3068): [303] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1137): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1137): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1137): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1137): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1137): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3068): [303] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3068): [303] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3068): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3068): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3068): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3068): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3068): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3068): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3068): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3068): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3068): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3068): 	at com.a.a.k.run(SourceFile:110)
,D/WifiService(  822): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@280f9ee6}
,E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::injectLocation(GpsExtLocation):857]: error! inject position failed
,D/HeadsetStateMachine( 2194): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2194): Disconnected process message: 10, size: 0
,V/KeepSync( 3825): Connecting to GoogleApiClient,
,I/GLSUser ( 1137): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1137): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1137): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1137): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1137): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,V/KeepSync( 3825): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3825): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3825): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3825): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1137): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1137): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1137): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1137): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1137): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3199): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3199): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3199): 	at jdm.a(PG:82)
E/HttpOperation( 3199): 	at jcs.o(PG:406)
E/HttpOperation( 3199): 	at jcn.a(PG:1379)
E/HttpOperation( 3199): 	at jcs.i(PG:143)
E/HttpOperation( 3199): 	at blb.a(PG:3937)
E/HttpOperation( 3199): 	at czp.a(PG:18188)
E/HttpOperation( 3199): 	at czp.a(PG:9081)
E/HttpOperation( 3199): 	at czq.run(PG:1686)
E/HttpOperation( 3199): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3199): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3199): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3199): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3199): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3199): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3199): 	at jdj.a(PG:4091)
E/HttpOperation( 3199): 	at jdj.a(PG:1125)
E/HttpOperation( 3199): 	at jdm.a(PG:77)
E/HttpOperation( 3199): 	... 12 more
E/HttpOperation( 3199): Caused by: faj: BadAuthentication
E/HttpOperation( 3199): 	at fal.a(PG:38)
E/HttpOperation( 3199): 	at jdj.a(PG:4089)
E/HttpOperation( 3199): 	... 14 more
,I/GLSUser ( 1137): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1137): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1137): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1137): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1137): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1137): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1137): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1137): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1137): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1137): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/HttpOperation( 3199): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3199): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3199): 	at jdm.a(PG:82)
E/HttpOperation( 3199): 	at jcs.o(PG:406)
E/HttpOperation( 3199): 	at jcn.a(PG:1379)
E/HttpOperation( 3199): 	at jcs.i(PG:143)
E/HttpOperation( 3199): 	at hec.a(PG:42)
E/HttpOperation( 3199): 	at hee.a(PG:102)
E/HttpOperation( 3199): 	at czr.a(PG:65)
E/HttpOperation( 3199): 	at kka.a(PG:108)
E/HttpOperation( 3199): 	at czp.a(PG:19176)
E/HttpOperation( 3199): 	at czp.a(PG:9081)
E/HttpOperation( 3199): 	at czq.run(PG:1686)
E/HttpOperation( 3199): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3199): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3199): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3199): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3199): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3199): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3199): 	at jdj.a(PG:4091)
E/HttpOperation( 3199): 	at jdj.a(PG:1125)
E/HttpOperation( 3199): 	at jdm.a(PG:77)
E/HttpOperation( 3199): 	... 15 more
E/HttpOperation( 3199): Caused by: faj: BadAuthentication
E/HttpOperation( 3199): 	at fal.a(PG:38)
E/HttpOperation( 3199): 	at jdj.a(PG:4089)
E/HttpOperation( 3199): 	... 17 more
,E/ExperimentLoader( 3199): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3199): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3199): 	at jdm.a(PG:82)
E/ExperimentLoader( 3199): 	at jcs.o(PG:406)
E/ExperimentLoader( 3199): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3199): 	at jcs.i(PG:143)
E/ExperimentLoader( 3199): 	at hec.a(PG:42)
E/ExperimentLoader( 3199): 	at hee.a(PG:102)
E/ExperimentLoader( 3199): 	at czr.a(PG:65)
E/ExperimentLoader( 3199): 	at kka.a(PG:108)
E/ExperimentLoader( 3199): 	at czp.a(PG:19176)
E/ExperimentLoader( 3199): 	at czp.a(PG:9081)
E/ExperimentLoader( 3199): 	at czq.run(PG:1686)
E/ExperimentLoader( 3199): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3199): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3199): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3199): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3199): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3199): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3199): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3199): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3199): 	at jdm.a(PG:77)
E/ExperimentLoader( 3199): 	... 15 more
E/ExperimentLoader( 3199): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3199): 	at fal.a(PG:38)
E/ExperimentLoader( 3199): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3199): 	... 17 more
,E/KeepSync( 3825): IOException
E/KeepSync( 3825): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3825): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3825): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3825): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3825): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3825): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3825): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3825): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3825): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3825): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3825): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3825): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3825): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3825): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3825): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3825): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3825): 	... 10 more
W/KeepSync( 3825): Sync result 2
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 355543, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 352246, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,V/GLSActivity( 1137): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1137): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1137): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1137): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1137): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1137): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/GLSActivity( 1137): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1137): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1137): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1137): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1137): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1137): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1137): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 3955): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3955): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3955): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 3955): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3955): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/PlayEventLogger( 3955): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3955): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 3955): Ignoring header User-Agent because its value was null.
,I/art     (  822): Explicit concurrent mark sweep GC freed 34715(1566KB) AllocSpace objects, 15(711KB) LOS objects, 31% free, 34MB/50MB, paused 1.691ms total 104.555ms
,D/HeadsetStateMachine( 2194): Disconnected process message: 10, size: 0
,V/GoogleAuthProtoRequest( 3068): [304] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1137): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1137): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1137): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1137): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1137): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3068): [304] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3068): [304] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3068): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3068): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3068): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3068): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3068): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3068): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3068): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3068): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3068): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3068): 	at com.a.a.k.run(SourceFile:110)
,D/HeadsetStateMachine( 2194): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2194): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2194): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2194): Disconnected process message: 10, size: 0
,I/BooksSync( 3903): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3903): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1137): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1137): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1137): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1137): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1137): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1137): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1137): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1137): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1137): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1137): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3903): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3903): Soft error
E/BooksSync( 3903): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3903): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3903): Sync error
E/BooksSync( 3903): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3903): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3903): Finished books sync
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 562972, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2194): Disconnected process message: 10, size: 0
,I/GLSUser ( 1137): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1137): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1137): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1137): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1137): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1137): Explicit concurrent mark sweep GC freed 54465(2MB) AllocSpace objects, 12(1323KB) LOS objects, 36% free, 27MB/43MB, paused 967us total 32.893ms
,E/HttpOperation( 3199): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3199): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3199): 	at jdm.a(PG:82)
E/HttpOperation( 3199): 	at jcs.o(PG:406)
E/HttpOperation( 3199): 	at jcn.a(PG:1379)
E/HttpOperation( 3199): 	at jcs.i(PG:143)
E/HttpOperation( 3199): 	at blb.a(PG:3937)
E/HttpOperation( 3199): 	at czp.a(PG:18188)
E/HttpOperation( 3199): 	at czp.a(PG:9081)
E/HttpOperation( 3199): 	at czq.run(PG:1686)
E/HttpOperation( 3199): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3199): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3199): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3199): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3199): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3199): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3199): 	at jdj.a(PG:4091)
E/HttpOperation( 3199): 	at jdj.a(PG:1125)
E/HttpOperation( 3199): 	at jdm.a(PG:77)
E/HttpOperation( 3199): 	... 12 more
E/HttpOperation( 3199): Caused by: faj: BadAuthentication
E/HttpOperation( 3199): 	at fal.a(PG:38)
E/HttpOperation( 3199): 	at jdj.a(PG:4089)
E/HttpOperation( 3199): 	... 14 more
,I/GLSUser ( 1137): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1137): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1137): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1137): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1137): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3199): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3199): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3199): 	at jdm.a(PG:82)
E/HttpOperation( 3199): 	at jcs.o(PG:406)
E/HttpOperation( 3199): 	at jcn.a(PG:1379)
E/HttpOperation( 3199): 	at jcs.i(PG:143)
E/HttpOperation( 3199): 	at hec.a(PG:42)
E/HttpOperation( 3199): 	at hee.a(PG:102)
E/HttpOperation( 3199): 	at czr.a(PG:65)
E/HttpOperation( 3199): 	at kka.a(PG:108)
E/HttpOperation( 3199): 	at czp.a(PG:19176)
E/HttpOperation( 3199): 	at czp.a(PG:9081)
E/HttpOperation( 3199): 	at czq.run(PG:1686)
E/HttpOperation( 3199): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3199): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3199): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3199): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3199): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3199): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3199): 	at jdj.a(PG:4091)
E/HttpOperation( 3199): 	at jdj.a(PG:1125)
E/HttpOperation( 3199): 	at jdm.a(PG:77)
E/HttpOperation( 3199): 	... 15 more
E/HttpOperation( 3199): Caused by: faj: BadAuthentication
E/HttpOperation( 3199): 	at fal.a(PG:38)
E/HttpOperation( 3199): 	at jdj.a(PG:4089)
E/HttpOperation( 3199): 	... 17 more
,E/ExperimentLoader( 3199): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3199): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3199): 	at jdm.a(PG:82)
E/ExperimentLoader( 3199): 	at jcs.o(PG:406)
E/ExperimentLoader( 3199): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3199): 	at jcs.i(PG:143)
E/ExperimentLoader( 3199): 	at hec.a(PG:42)
E/ExperimentLoader( 3199): 	at hee.a(PG:102)
E/ExperimentLoader( 3199): 	at czr.a(PG:65)
E/ExperimentLoader( 3199): 	at kka.a(PG:108)
E/ExperimentLoader( 3199): 	at czp.a(PG:19176)
E/ExperimentLoader( 3199): 	at czp.a(PG:9081)
E/ExperimentLoader( 3199): 	at czq.run(PG:1686)
E/ExperimentLoader( 3199): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3199): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3199): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3199): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3199): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3199): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3199): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3199): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3199): 	at jdm.a(PG:77)
E/ExperimentLoader( 3199): 	... 15 more
E/ExperimentLoader( 3199): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3199): 	at fal.a(PG:38)
E/ExperimentLoader( 3199): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3199): 	... 17 more
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 632912, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,V/KeepSync( 3825): Connecting to GoogleApiClient
,I/GLSUser ( 1137): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1137): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1137): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1137): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1137): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,V/KeepSync( 3825): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3825): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3825): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3825): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1137): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1137): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1137): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1137): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1137): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3825): IOException
E/KeepSync( 3825): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3825): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3825): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3825): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3825): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3825): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3825): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3825): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3825): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3825): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3825): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3825): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3825): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3825): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3825): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3825): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3825): 	... 10 more
W/KeepSync( 3825): Sync result 2
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 639573, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2194): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2194): Disconnected process message: 10, size: 0
,V/GoogleAuthProtoRequest( 3068): [305] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1137): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1137): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1137): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1137): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1137): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3068): [305] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3068): [305] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3068): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3068): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3068): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3068): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3068): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3068): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3068): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3068): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3068): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3068): 	at com.a.a.k.run(SourceFile:110)
,D/HeadsetStateMachine( 2194): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2194): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2194): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2194): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2194): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2194): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2194): Disconnected process message: 10, size: 0
,W/bt-btm  ( 2194): Stopping oneshot timer
,D/HeadsetStateMachine( 2194): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2194): Disconnected process message: 10, size: 0
,I/art     (  822): Explicit concurrent mark sweep GC freed 48454(2MB) AllocSpace objects, 9(521KB) LOS objects, 31% free, 34MB/50MB, paused 1.586ms total 75.096ms
,I/BooksSync( 3903): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3903): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1137): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1137): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1137): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1137): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1137): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1137): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1137): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1137): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1137): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1137): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3903): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3903): Soft error
E/BooksSync( 3903): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3903): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3903): Sync error
E/BooksSync( 3903): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3903): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3903): Finished books sync
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1053827, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2194): Disconnected process message: 10, size: 0
,I/GLSUser ( 1137): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1137): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1137): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1137): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1137): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/HttpOperation( 3199): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3199): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3199): 	at jdm.a(PG:82)
E/HttpOperation( 3199): 	at jcs.o(PG:406)
E/HttpOperation( 3199): 	at jcn.a(PG:1379)
E/HttpOperation( 3199): 	at jcs.i(PG:143)
E/HttpOperation( 3199): 	at blb.a(PG:3937)
E/HttpOperation( 3199): 	at czp.a(PG:18188)
E/HttpOperation( 3199): 	at czp.a(PG:9081)
E/HttpOperation( 3199): 	at czq.run(PG:1686)
E/HttpOperation( 3199): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3199): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3199): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3199): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3199): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3199): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3199): 	at jdj.a(PG:4091)
E/HttpOperation( 3199): 	at jdj.a(PG:1125)
E/HttpOperation( 3199): 	at jdm.a(PG:77)
E/HttpOperation( 3199): 	... 12 more
E/HttpOperation( 3199): Caused by: faj: BadAuthentication
E/HttpOperation( 3199): 	at fal.a(PG:38)
E/HttpOperation( 3199): 	at jdj.a(PG:4089)
E/HttpOperation( 3199): 	... 14 more
,I/GLSUser ( 1137): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1137): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1137): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1137): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1137): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3199): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3199): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3199): 	at jdm.a(PG:82)
E/HttpOperation( 3199): 	at jcs.o(PG:406)
E/HttpOperation( 3199): 	at jcn.a(PG:1379)
E/HttpOperation( 3199): 	at jcs.i(PG:143)
E/HttpOperation( 3199): 	at hec.a(PG:42)
E/HttpOperation( 3199): 	at hee.a(PG:102)
E/HttpOperation( 3199): 	at czr.a(PG:65)
E/HttpOperation( 3199): 	at kka.a(PG:108)
E/HttpOperation( 3199): 	at czp.a(PG:19176)
E/HttpOperation( 3199): 	at czp.a(PG:9081)
E/HttpOperation( 3199): 	at czq.run(PG:1686)
E/HttpOperation( 3199): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3199): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3199): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3199): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3199): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3199): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3199): 	at jdj.a(PG:4091)
E/HttpOperation( 3199): 	at jdj.a(PG:1125)
E/HttpOperation( 3199): 	at jdm.a(PG:77)
E/HttpOperation( 3199): 	... 15 more
E/HttpOperation( 3199): Caused by: faj: BadAuthentication
E/HttpOperation( 3199): 	at fal.a(PG:38)
E/HttpOperation( 3199): 	at jdj.a(PG:4089)
E/HttpOperation( 3199): 	... 17 more
,E/ExperimentLoader( 3199): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3199): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3199): 	at jdm.a(PG:82)
E/ExperimentLoader( 3199): ,	at jcs.o(PG:406)
E/ExperimentLoader( 3199): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3199): 	at jcs.i(PG:143)
E/ExperimentLoader( 3199): 	at hec.a(PG:42)
E/ExperimentLoader( 3199): 	at hee.a(PG:102)
E/ExperimentLoader( 3199): 	at czr.a(PG:65)
E/ExperimentLoader( 3199): 	at kka.a(PG:108)
E/ExperimentLoader( 3199): 	at czp.a(PG:19176)
E/ExperimentLoader( 3199): 	at czp.a(PG:9081)
E/ExperimentLoader( 3199): 	at czq.run(PG:1686),
E/ExperimentLoader( 3199): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3199): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3199): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3199): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3199): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3199): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3199): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3199): ,	at jdj.a(PG:1125)
E/ExperimentLoader( 3199): 	at jdm.a(PG:77)
E/ExperimentLoader( 3199): 	... 15 more
E/ExperimentLoader( 3199): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3199): 	at fal.a(PG:38)
E/ExperimentLoader( 3199): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3199): 	... 17 more
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 1143348, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2194): Disconnected process message: 10, size: 0
,D/GCM     ( 1137): Message class com.google.f.a.a.i
,V/GoogleAuthProtoRequest( 3068): [306] a.<init>: mAccountName set to: thalitester@gmail.com
,I/EventLogService( 1769): Opted in for usage reporting
,I/EventLogService( 1769): Aggregate from 1454592312491 (log), 1454592312491 (data)
,I/GLSUser ( 1137): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1137): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1137): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1137): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1137): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3068): [306] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3068): [306] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3068): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3068): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3068): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3068): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3068): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3068): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3068): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3068): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3068): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3068): 	at com.a.a.k.run(SourceFile:110)
,W/EventLogAggregator( 1769): Unknown tag: snet_gcore
W/EventLogAggregator( 1769): Unknown tag: snet_launch_service
,I/art     ( 1137): Explicit concurrent mark sweep GC freed 64612(3MB) AllocSpace objects, 13(1434KB) LOS objects, 37% free, 27MB/43MB, paused 1.206ms total 66.659ms
,I/ServiceDumpSys( 1769): dumping service [account]
,V/KeepSync( 3825): Connecting to GoogleApiClient
,I/GLSUser ( 1137): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1137): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1137): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1137): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1137): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,E/ClientConnectionOperation( 1769): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1769): 	... 7 more
,V/KeepSync( 3825): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3825): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3825): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3825): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1137): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1137): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1137): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1137): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1137): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3825): IOException
E/KeepSync( 3825): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3825): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3825): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3825): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3825): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3825): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3825): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3825): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3825): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3825): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3825): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3825): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3825): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3825): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3825): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3825): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3825): 	... 10 more
W/KeepSync( 3825): Sync result 2
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 1186825, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2194): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2194): Disconnected process message: 10, size: 0
,I/UsageStatsService(  822): User[0] Flushing usage stats to disk
,D/HeadsetStateMachine( 2194): Disconnected process message: 10, size: 0
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 4336): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 4336): CheckJNI is OFF
D/AndroidRuntime( 4336): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  822): Force stopping com.test.thalitest appid=10265 user=-1: uninstall pkg
I/ActivityManager(  822): Killing 3622:com.test.thalitest/u0a265 (adj 0): stop com.test.thalitest
W/PackageSettings(  822): Skipping PackageSetting{8b2202c com.example.hello/10273} due to missing metadata
I/WindowState(  822): WIN DEATH: Window{3aa0f91c u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  822): Client connection lost with reason: 4
E/libprocessgroup(  822): failed to kill 1 processes for processgroup 3622
W/ActivityManager(  822): Force removing ActivityRecord{398c108d u0 com.test.thalitest/.MainActivity t28}: app died, no saved state
V/ActivityManager(  822): Display changed displayId=0
W/ActivityManager(  822): Spurious death for ProcessRecord{26372a7e 3622:com.test.thalitest/u0a265}, curProc for 3622: null
I/ActivityManager(  822): Force stopping com.test.thalitest appid=10265 user=0: pkg removed
D/TaskPersister(  822): removeObsoleteFile: deleting file=28_task.xml
I/Keyboard.Facilitator( 1234): resetDictionaries() : en_US
I/InputReader(  822): Reconfiguring input devices.  changes=0x00000010
I/Keyboard.Facilitator.DecoderInitializer( 1234): run()
I/Decoder ( 1234): createOrResetDecoder
W/InputMethodManagerService(  822): Got RemoteException sending setActive(false) notification to pid 3622 uid 10265
I/art     ( 1066): Explicit concurrent mark sweep GC freed 70582(2MB) AllocSpace objects, 0(0B) LOS objects, 18% free, 71MB/87MB, paused 968us total 38.510ms
D/BuaReceiver( 3371): ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
I/Keyboard.Facilitator( 1234): onFinishInput()
I/art     (  822): Explicit concurrent mark sweep GC freed 32694(1867KB) AllocSpace objects, 12(380KB) LOS objects, 31% free, 34MB/50MB, paused 1.695ms total 76.248ms
I/art     (  822): WaitForGcToComplete blocked for 53.733ms for cause Explicit
I/art     ( 1487): Explicit concurrent mark sweep GC freed 2557(185KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 757us total 77.996ms
I/art     ( 1487): WaitForGcToComplete blocked for 49.387ms for cause HeapTrim
I/ActivityManager(  822): Start proc 4353:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
I/art     ( 1366): Explicit concurrent mark sweep GC freed 5086(371KB) AllocSpace objects, 12(1408KB) LOS objects, 31% free, 35MB/51MB, paused 1.156ms total 25.563ms
I/ConfigService( 1137): onCreate
W/LocationOracleImpl( 1487): Best location was null
I/HotwordRecognitionRnr( 1487): Starting hotword detection.
I/MicrophoneInputStream( 1487): mic_starting com.google.android.apps.gsa.speech.audio.u@16b0d621
I/AudioFlinger(  357): AudioFlinger's thread 0xb4061000 ready to run
I/SoundTriggerHwService::Module(  357): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
D/JobSchedulerService(  822): Receieved: android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  822): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/MicrophoneInputStream( 1487): mic_started com.google.android.apps.gsa.speech.audio.u@16b0d621
I/Keyboard.Facilitator.MainLanguageModelLoader( 1234): run()
D/audio_hw_primary(  357): select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
D/msm8974_platform(  357): platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
E/ACDB-LOADER(  357): Error: ACDB AudProc vol returned = -19
D/audio_hw_primary(  357): enable_snd_device: snd_device(55: voice-rec-mic)
D/audio_hw_primary(  357): enable_audio_route: apply and update mixer path: audio-record
I/Keyboard.Facilitator.MainLanguageModelLoader( 1234): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1234): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1234): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1234): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1234): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1234): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1234): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1234): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1234): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1234): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1234): run()
I/StatsUtilsManager( 1234): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1234): shouldRecordStats() = Too Soon
I/ContactLocale( 4353): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
D/VoicemailCleanupService( 4353): Cleaning up data for package: com.test.thalitest
I/HotwordWorker( 1487): onReady
I/art     (  822): Explicit concurrent mark sweep GC freed 7307(342KB) AllocSpace objects, 2(220KB) LOS objects, 32% free, 33MB/49MB, paused 1.481ms total 169.702ms
I/ActivityManager(  822): Start proc 4391:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
D/WifiService(  822): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@32d57a9e}
E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=23.00 rxSuccessRate=28.50 targetRoamBSSID=any RSSI=-51
I/art     ( 1796): Explicit concurrent mark sweep GC freed 16979(1000KB) AllocSpace objects, 8(128KB) LOS objects, 37% free, 26MB/42MB, paused 894us total 25.419ms
E/DataBuffer( 1796): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@8e0de97)
E/DataBuffer( 1796): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@b5af884)
I/ActivityManager(  822): Start proc 4410:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1660798227
E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
I/art     (  368): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 21MB/36MB, paused 214us total 10.611ms
E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=67.50 rxSuccessRate=172.75 targetRoamBSSID=any RSSI=-51
I/art     (  368): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 211us total 8.923ms
I/art     (  368): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 204us total 8.928ms
I/art     ( 4336): System.exit called, status: 0
I/AndroidRuntime( 4336): VM exiting with result code 0.
W/ContextImpl( 4410): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2609 
D/Launcher.Workspace( 1366): 11683562 - stripEmptyScreens()
D/Launcher.Workspace( 1366): 11683562 - stripEmptyScreens()
E/NetworkScheduler.SchedulerReceiver( 1137): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1137): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
I/ActivityManager(  822): Killing 3760:com.android.chrome/u0a40 (adj 15): empty #17
D/PackageBroadcastService( 1769): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/ChimeraCfgMgr( 1769): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1769): Module APK com.google.android.play.games already loaded
D/AccountUtils( 1769): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1769): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1769): Module APK com.google.android.play.games already loaded
W/Launcher( 1366): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@2696016b new=com.google.android.velvet.VelvetApplication@2696016b
E/SQLiteLog( 1366): (3850) statement aborts at 24: [DELETE FROM shortcut_and_widget_previews WHERE name LIKE ? OR name LIKE ?] disk I/O error
E/SQLiteLog( 1769): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/DriveAsyncService( 1769): disk I/O error (code 3850)
E/DriveAsyncService( 1769): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 1769): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 1769): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/DriveAsyncService( 1769): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 1769): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 1769): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/DriveAsyncService( 1769): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/DriveAsyncService( 1769): 	at com.google.android.gms.drive.database.k.l(SourceFile:596)
E/DriveAsyncService( 1769): 	at com.google.android.gms.drive.database.k.b(SourceFile:570)
E/DriveAsyncService( 1769): 	at com.google.android.gms.drive.database.f.h(SourceFile:1473)
E/DriveAsyncService( 1769): 	at com.google.android.gms.drive.api.a.bc.a(SourceFile:16)
E/DriveAsyncService( 1769): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/DriveAsyncService( 1769): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 1769): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 1769): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 4353): (3850) statement aborts at 22: [DELETE FROM deleted_contacts WHERE contact_deleted_timestamp < ?] disk I/O error
--------- beginning of crash
E/AndroidRuntime( 4353): FATAL EXCEPTION: ContactsProviderWorker
E/AndroidRuntime( 4353): Process: android.process.acore, PID: 4353
E/AndroidRuntime( 4353): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4353): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 4353): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 4353): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 4353): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 4353): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/AndroidRuntime( 4353): 	at com.android.providers.contacts.database.DeletedContactsTableUtil.deleteOldLogs(DeletedContactsTableUtil.java:78)
E/AndroidRuntime( 4353): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1730)
E/AndroidRuntime( 4353): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1492)
E/AndroidRuntime( 4353): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4353): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 4353): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager(  822): Start proc 4439:com.google.android.apps.docs/u0a46 for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
I/UpdateIcingCorporaServi( 1487): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/LocationSettingsChecker( 1769): Removing dialog suppression flag for package com.test.thalitest
E/DropBoxManagerService(  822): Can't write: system_app_crash
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
D/OpenGLRenderer(  822): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
D/Atlas   (  822): Validating map...
E/SQLiteLog( 1487): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDatabase( 1769): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 1769): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1769): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1769): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1769): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1769): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1769): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1769): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1769): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1769): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1769): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1769): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 1769): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 1769): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1769): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 1769): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 1769): 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
E/SQLiteDatabase( 1769): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 1769): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 1769): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1769): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1769): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 1769): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 1769): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 1769): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1769): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1769): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 1769): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 1769): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1769): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1769): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1769): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteOpenHelper( 1769): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteOpenHelper( 1769): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 1769): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteOpenHelper( 1769): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 1769): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 1769): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 1769): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 1769): 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
E/SQLiteOpenHelper( 1769): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 1769): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 1769): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 1769): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 1769): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteOpenHelper( 1769): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/SQLiteOpenHelper( 1769): Opened metrics.db in read-only mode
D/GOOGLEHELP_CompatibleDatabase( 1769): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1769): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
E/SQLiteLog( 1769): (8) statement aborts at 16: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
D/GOOGLEHELP_CompatibleDatabase( 1769): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
E/AndroidRuntime( 1769): FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
E/AndroidRuntime( 1769): Process: com.google.android.gms, PID: 1769
E/AndroidRuntime( 1769): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/AndroidRuntime( 1769): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1769): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 1769): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1769): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1769): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/AndroidRuntime( 1769): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:281)
E/AndroidRuntime( 1769): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/AndroidRuntime( 1769): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 1769): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1769): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 1769): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager(  822): Start proc 4460:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
E/SharedPreferencesImpl( 1487): Couldn't create directory for SharedPreferences file /data/data/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml
E/AndroidRuntime( 1487): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 1487): Process: com.google.android.googlequicksearchbox:search, PID: 1487
E/AndroidRuntime( 1487): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1487): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 1487): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/AndroidRuntime( 1487): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 1487): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 1487): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/AndroidRuntime( 1487): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/AndroidRuntime( 1487): 	at com.google.android.apps.gsa.extradex.icingsync.b.a(ApplicationsHelperImpl.java:85)
E/AndroidRuntime( 1487): 	at com.google.android.search.core.icingsync.d.i(InternalIcingCorporaProvider.java:623)
E/AndroidRuntime( 1487): 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:298)
E/AndroidRuntime( 1487): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:328)
E/AndroidRuntime( 1487): 	at android.content.ContentResolver.update(ContentResolver.java:1333)
E/AndroidRuntime( 1487): 	at com.google.android.search.core.icingsync.e.JA(UpdateIcingCorporaService.java:408)
E/AndroidRuntime( 1487): 	at com.google.android.search.core.icingsync.g.aTY(UpdateIcingCorporaService.java:347)
E/AndroidRuntime( 1487): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:320)
E/AndroidRuntime( 1487): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.ba(UpdateIcingCorporaService.java:215)
E/AndroidRuntime( 1487): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:201)
E/AndroidRuntime( 1487): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 1487): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1487): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 1487): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteDatabase( 1769): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 1769): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1769): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1769): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1769): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1769): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1769): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1769): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1769): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1769): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1769): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1769): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 1769): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 1769): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 1769): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1769): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 1769): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteDatabase( 1769): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1769): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1769): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 1769): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 1769): Couldn't open phenotype.db for writing (will try read-only):
E/SQLiteOpenHelper( 1769): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1769): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1769): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 1769): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 1769): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1769): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1769): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1769): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteOpenHelper( 1769): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteOpenHelper( 1769): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 1769): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteOpenHelper( 1769): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 1769): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 1769): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 1769): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 1769): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteOpenHelper( 1769): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 1769): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 1769): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteOpenHelper( 1769): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/SQLiteOpenHelper( 1769): Opened phenotype.db in read-only mode
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
I/ConfigFetchService( 1769): onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
E/SharedPreferencesImpl( 1769): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/config_removals.xml to backup file /data/data/com.google.android.gms/shared_prefs/config_removals.xml.bak
I/OpenGLRenderer(  822): Initialized EGL, version 1.4
I/Icing   ( 1769): doRemovePackageData com.test.thalitest
I/PeopleContactsSync( 1769): CP2 sync disabled
D/OpenGLRenderer(  822): Enabling debug mode 0
W/BaseAppContext( 1769): Using Auth Proxy for data requests.
W/ResourcesManager(  822): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(  822): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/BaseAppContext( 1769): Using Auth Proxy for data requests.
E/SQLiteDatabase( 1769): Failed to open database '/data/data/com.google.android.gms/databases/app_state.db'.
E/SQLiteDatabase( 1769): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1769): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1769): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1769): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1769): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1769): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1769): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1769): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1769): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1769): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1769): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 1769): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 1769): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1769): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 1769): 	at com.google.android.gms.common.i.a.delete(SourceFile:272)
E/SQLiteDatabase( 1769): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
E/SQLiteDatabase( 1769): 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
E/SQLiteDatabase( 1769): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
E/SQLiteDatabase( 1769): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
E/SQLiteDatabase( 1769): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/SQLiteDatabase( 1769): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 1769): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 1769): 	at java.lang.Thread.run(Thread.java:818)
E/ClearPendingStateOp( 1769): Runtime exception while performing operation
E/ClearPendingStateOp( 1769): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/ClearPendingStateOp( 1769): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/ClearPendingStateOp( 1769): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/ClearPendingStateOp( 1769): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/ClearPendingStateOp( 1769): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/ClearPendingStateOp( 1769): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/ClearPendingStateOp( 1769): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/ClearPendingStateOp( 1769): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/ClearPendingStateOp( 1769): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/ClearPendingStateOp( 1769): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/ClearPendingStateOp( 1769): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/ClearPendingStateOp( 1769): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/ClearPendingStateOp( 1769): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/ClearPendingStateOp( 1769): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/ClearPendingStateOp( 1769): 	at com.google.android.gms.common.i.a.delete(SourceFile:272)
E/ClearPendingStateOp( 1769): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
E/ClearPendingStateOp( 1769): 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
E/ClearPendingStateOp( 1769): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
E/ClearPendingStateOp( 1769): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
E/ClearPendingStateOp( 1769): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearPendingStateOp( 1769): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearPendingStateOp( 1769): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearPendingStateOp( 1769): 	at java.lang.Thread.run(Thread.java:818)
F/ClearPendingStateOp( 1769): Killing (on development devices) due to RuntimeException
F/ClearPendingStateOp( 1769): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
F/ClearPendingStateOp( 1769): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
F/ClearPendingStateOp( 1769): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
F/ClearPendingStateOp( 1769): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
F/ClearPendingStateOp( 1769): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
F/ClearPendingStateOp( 1769): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
F/ClearPendingStateOp( 1769): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
F/ClearPendingStateOp( 1769): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
F/ClearPendingStateOp( 1769): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
F/ClearPendingStateOp( 1769): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
F/ClearPendingStateOp( 1769): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
F/ClearPendingStateOp( 1769): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
F/ClearPendingStateOp( 1769): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
F/ClearPendingStateOp( 1769): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
F/ClearPendingStateOp( 1769): 	at com.google.android.gms.common.i.a.delete(SourceFile:272)
F/ClearPendingStateOp( 1769): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
F/ClearPendingStateOp( 1769): 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
F/ClearPendingStateOp( 1769): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
F/ClearPendingStateOp( 1769): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
F/ClearPendingStateOp( 1769): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
F/ClearPendingStateOp( 1769): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
F/ClearPendingStateOp( 1769): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
F/ClearPendingStateOp( 1769): 	at java.lang.Thread.run(Thread.java:818)
E/DropBoxManagerService(  822): Can't write: system_app_wtf
E/DropBoxManagerService(  822): java.io.FileNotFoundException: /data/system/dropbox/drop102.tmp: open failed: EROFS (Read-only file system)
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
I/ActivityManager(  822): Killing 3863:com.qualcomm.timeservice/1000 (adj 15): empty #17
D/GFEEDBACK_SendErrorReportOperation( 1769): Error doing instant send: java.io.IOException: failed to create reports directory
E/GFEEDBACK_SendErrorReportOperation( 1769): Error saving report: java.io.IOException: failed to create reports directory
I/HotwordDetector( 1487): Closing mic
I/MicrophoneInputStream( 1487): mic_close com.google.android.apps.gsa.speech.audio.u@16b0d621
I/GAv4    ( 4439): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4439):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4439):   adb logcat -s GAv4
E/Search.SharedPreferencesProto( 1487): Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
W/GAv4    ( 4439): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 4439): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
E/SharedPreferencesImpl( 4439): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4439): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
D/audio_hw_primary(  357): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  357): disable_snd_device: snd_device(55: voice-rec-mic)
W/GAv4    ( 4439): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
E/SharedPreferencesImpl( 4439): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
I/SoundTriggerHwService::Module(  357): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1487): Hotword detection finished
I/HotwordRecognitionRnr( 1487): Stopping hotword detection.
W/AnalyticsTrackerProxyImpl( 4439): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
E/SQLiteDatabase( 4439): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4439): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4439): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4439): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4439): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4439): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4439): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4439): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4439): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4439): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4439): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4439): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4439): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4439): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4439): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4439): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 4439): 	at ael.a(PG:1521)
E/SQLiteDatabase( 4439): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 4439): 	at aen.run(PG:536)
E/SQLiteDatabase( 4439): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 4439): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4439): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4439): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4439): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4439): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4439): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4439): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4439): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4439): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4439): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4439): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4439): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4439): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4439): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4439): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 4439): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 4439): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 4439): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 4439): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 4439): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 4439): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4439): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4439): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4439): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4439): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 4439): 	at gir$c.run(Unknown Source)
E/GAv4    ( 4439): Opening the database failed, dropping the table and recreating it
E/SharedPreferencesImpl( 4439): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SQLiteDatabase( 4439): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 4439): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4439): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4439): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4439): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4439): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4439): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4439): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4439): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4439): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4439): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4439): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4439): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4439): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4439): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4439): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 4439): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 4439): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 4439): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 4439): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 4439): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 4439): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4439): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4439): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4439): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4439): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 4439): 	at gir$c.run(Unknown Source)
E/GAv4    ( 4439): Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 4439): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4439): Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 4439): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4439): Job execution failed: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 4439): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4439): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4439): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4439): Job execution failed: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4439): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4439): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SQLiteDatabase( 4439): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4439): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4439): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4439): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4439): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4439): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4439): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4439): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4439): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4439): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4439): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4439): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4439): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4439): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4439): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4439): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 4439): 	at ael.a(PG:1521)
E/SQLiteDatabase( 4439): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 4439): 	at aej.c(PG:139)
E/SQLiteDatabase( 4439): 	at aej.b(PG:398)
E/SQLiteDatabase( 4439): 	at agf.f(PG:417)
E/SQLiteDatabase( 4439): 	at oe.run(PG:1112)
E/SQLiteDatabase( 4439): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4439): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4439): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4439): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4439): 	at java.lang.Thread.run(Thread.java:818)
E/SharedPreferencesImpl( 4439): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4439): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4439): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4439): Failed to commit local dispatch transaction: android.database.sqlite.SQLiteException: Database open failed
E/AbstractDatabaseInstance( 4439): Failed to delete from CachedSearch133
E/AbstractDatabaseInstance( 4439): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AbstractDatabaseInstance( 4439): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AbstractDatabaseInstance( 4439): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AbstractDatabaseInstance( 4439): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AbstractDatabaseInstance( 4439): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AbstractDatabaseInstance( 4439): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AbstractDatabaseInstance( 4439): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AbstractDatabaseInstance( 4439): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AbstractDatabaseInstance( 4439): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AbstractDatabaseInstance( 4439): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AbstractDatabaseInstance( 4439): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AbstractDatabaseInstance( 4439): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AbstractDatabaseInstance( 4439): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AbstractDatabaseInstance( 4439): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AbstractDatabaseInstance( 4439): 	at aev.getWritableDatabase(PG:238)
E/AbstractDatabaseInstance( 4439): 	at ael.a(PG:1521)
E/AbstractDatabaseInstance( 4439): 	at hix$a.a(PG:125)
E/AbstractDatabaseInstance( 4439): 	at aej.c(PG:139)
E/AbstractDatabaseInstance( 4439): 	at aej.b(PG:398)
E/AbstractDatabaseInstance( 4439): 	at agf.f(PG:417)
E/AbstractDatabaseInstance( 4439): 	at oe.run(PG:1112)
E/AbstractDatabaseInstance( 4439): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/AbstractDatabaseInstance( 4439): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AbstractDatabaseInstance( 4439): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AbstractDatabaseInstance( 4439): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AbstractDatabaseInstance( 4439): 	at java.lang.Thread.run(Thread.java:818)
E/SharedPreferencesImpl( 4439): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/ResourcesManager( 4439): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
E/SharedPreferencesImpl( 4439): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/ResourcesManager( 4439): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/GAv4    ( 4439): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4439): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4439): Sync local dispatch failed: android.database.sqlite.SQLiteException: Database open failed
W/GAv4    ( 4439): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4439): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4439): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4439): syncDispatchLocalHits failed: java.util.concurrent.ExecutionException: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4439): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/CAKEMIX_CRASHED( 4439): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/CAKEMIX_CRASHED( 4439): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/CAKEMIX_CRASHED( 4439): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/CAKEMIX_CRASHED( 4439): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/CAKEMIX_CRASHED( 4439): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/CAKEMIX_CRASHED( 4439): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/CAKEMIX_CRASHED( 4439): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/CAKEMIX_CRASHED( 4439): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/CAKEMIX_CRASHED( 4439): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/CAKEMIX_CRASHED( 4439): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/CAKEMIX_CRASHED( 4439): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/CAKEMIX_CRASHED( 4439): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/CAKEMIX_CRASHED( 4439): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/CAKEMIX_CRASHED( 4439): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/CAKEMIX_CRASHED( 4439): 	at aev.getWritableDatabase(PG:238)
E/CAKEMIX_CRASHED( 4439): 	at ael.a(PG:1521)
E/CAKEMIX_CRASHED( 4439): 	at hix$a.a(PG:125)
E/CAKEMIX_CRASHED( 4439): 	at aen.run(PG:536)
I/ActivityManager(  822): Start proc 4506:com.android.documentsui/u0a45 for broadcast com.android.documentsui/.PackageReceiver
I/ActivityManager(  822): START u0 {act=android.intent.action.BUG_REPORT flg=0x10000000 cmp=com.google.android.apps.docs/.app.ErrorNotificationActivity (has extras)} from uid 10046 on display 0
V/WindowManager(  822): addAppToken: AppWindowToken{19fbb370 token=Token{166d41b3 ActivityRecord{53ce322 u0 com.google.android.apps.docs/.app.ErrorNotificationActivity t29}}} to stack=1 task=29 at 0
I/Process ( 4439): Sending signal. PID: 4439 SIG: 9
E/lowmemorykiller(  256): Error writing /proc/4439/oom_score_adj; errno=22
E/JavaBinder(  822): !!! FAILED BINDER TRANSACTION !!!
W/ActivityManager(  822): Exception when starting activity com.google.android.apps.docs/.app.ErrorNotificationActivity
W/ActivityManager(  822): android.os.TransactionTooLargeException
W/ActivityManager(  822): 	at android.os.BinderProxy.transactNative(Native Method)
W/ActivityManager(  822): 	at android.os.BinderProxy.transact(Binder.java:496)
W/ActivityManager(  822): 	at android.app.ApplicationThreadProxy.scheduleLaunchActivity(ApplicationThreadNative.java:797)
W/ActivityManager(  822): 	at com.android.server.am.ActivityStackSupervisor.realStartActivityLocked(ActivityStackSupervisor.java:1181)
W/ActivityManager(  822): 	at com.android.server.am.ActivityStackSuperviso,r.startSpecificActivityLocked(ActivityStackSupervisor.java:1281)
W/ActivityManager(  822): 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:1891)
W/ActivityManager(  822): 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1455)
W/ActivityManager(  822): 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2473)
W/ActivityManager(  822): 	at com.android.server.am.ActivityStack.completePauseLocked(ActivityStack.java:998)
W/ActivityManager(  822): 	at com.android.server.am.ActivityStack.activityPausedLocked(ActivityStack.java:896)
W/ActivityManager(  822): 	at com.android.server.am.ActivityManagerService.activityPaused(ActivityManagerService.java:6311)
W/ActivityManager(  822): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:512)
W/ActivityManager(  822): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2208)
W/ActivityManager(  822): 	at android.os.Binder.execTransact(Binder.java:446)
E/native  ( 1234): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1234): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
I/ActivityManager(  822): Start proc 4525:com.google.android.apps.docs/u0a46 for activity com.google.android.apps.docs/.app.ErrorNotificationActivity
W/OpenGLRenderer( 1366): Incorrectly called buildLayer on View: ew, destroying layer...
W/ActivityManager(  822): Spurious death for ProcessRecord{348b7835 4525:com.google.android.apps.docs/u0a46}, curProc for 4439: null
E/native  ( 1234): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1234): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1234): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1234): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1234): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1234): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/SQLiteDatabase( 4506): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 4506): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4506): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4506): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4506): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4506): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4506): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4506): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4506): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4506): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4506): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4506): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4506): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4506): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4506): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4506): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/SQLiteDatabase( 4506): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/SQLiteDatabase( 4506): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:370)
E/SQLiteDatabase( 4506): 	at android.content.ContentResolver.call(ContentResolver.java:1372)
E/SQLiteDatabase( 4506): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/SQLiteDatabase( 4506): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2609)
E/SQLiteDatabase( 4506): 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
E/SQLiteDatabase( 4506): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1380)
E/SQLiteDatabase( 4506): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4506): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 4506): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
E/SQLiteDatabase( 4506): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 4506): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 4506): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
E/SQLiteDatabase( 4506): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
I/ActivityManager(  822): Killing 3223:com.google.android.apps.photos/u0a71 (adj 15): empty #17
D/AndroidRuntime( 4506): Shutting down VM
E/AndroidRuntime( 4506): FATAL EXCEPTION: main
E/AndroidRuntime( 4506): Process: com.android.documentsui, PID: 4506
E/AndroidRuntime( 4506): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4506): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2616)
E/AndroidRuntime( 4506): 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
E/AndroidRuntime( 4506): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1380)
E/AndroidRuntime( 4506): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4506): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 4506): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
E/AndroidRuntime( 4506): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 4506): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 4506): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
E/AndroidRuntime( 4506): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
E/AndroidRuntime( 4506): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4506): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4506): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 4506): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 4506): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4506): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4506): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4506): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AndroidRuntime( 4506): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AndroidRuntime( 4506): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 4506): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AndroidRuntime( 4506): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 4506): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 4506): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 4506): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/AndroidRuntime( 4506): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/AndroidRuntime( 4506): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:370)
E/AndroidRuntime( 4506): 	at android.content.ContentResolver.call(ContentResolver.java:1372)
E/AndroidRuntime( 4506): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/AndroidRuntime( 4506): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2609)
E/AndroidRuntime( 4506): 	... 9 more
I/ActivityManager(  822): Start proc 4546:com.android.externalstorage/u0a10 for content provider com.android.externalstorage/.ExternalStorageProvider
E/DropBoxManagerService(  822): Can't write: system_app_crash
E/DropBoxManagerService(  822): java.io.FileNotFoundException: /data/system/dropbox/drop106.tmp: open failed: EROFS (Read-only file system)
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
I/ActivityManager(  822): Killing 2786:com.google.android.talk/u0a61 (adj 15): empty #17
I/GAv4    ( 4525): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4525):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4525):   adb logcat -s GAv4
W/GAv4    ( 4525): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 4525): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.

```
