#### Test 50650278cd699a4_thali05_motorola-Nexus 6 Logs


```
--------- beginning of main
E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=4.46 targetRoamBSSID=any RSSI=-48
E/WifiStateMachine(  821): WifiStateMachine starting scan for "NG7005g"WPA_PSK with 2412,5220
,D/AndroidRuntime( 3594): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 3594): CheckJNI is OFF
D/AndroidRuntime( 3594): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  821): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/WindowManager(  821): addAppToken: AppWindowToken{380e21e6 token=Token{265f2841 ActivityRecord{3eef3328 u0 com.test.thalitest/.MainActivity t26}}} to stack=1 task=26 at 0
D/AndroidRuntime( 3594): Shutting down VM
V/WindowManager(  821): Adding window Window{16375ac3 u0 Starting com.test.thalitest} at 2 of 7 (after Window{19e85daa u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
I/HotwordDetector( 1498): Closing mic
I/MicrophoneInputStream( 1498): mic_close com.google.android.apps.gsa.speech.audio.u@10e7fb83
I/ActivityManager(  821): Start proc 3608:com.test.thalitest/u0a265 for activity com.test.thalitest/.MainActivity
D/audio_hw_primary(  358): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  358): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  358): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1498): Hotword detection finished
I/HotwordRecognitionRnr( 1498): Stopping hotword detection.
I/ActivityManager(  821): Killing 3041:com.google.android.gm/u0a78 (adj 15): empty #17
E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1659688211
E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
I/ActivityManager(  821): Killing 2692:com.google.android.apps.maps/u0a65 (adj 15): empty #18
,I/kickstart(  873): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
I/kickstart(  873): STATUS: Wrote to /sys/power/wake_lock
,E/kickstart(  873): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2
I/kickstart(  873): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2' for writing
,I/WebViewFactory( 3608): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3608): Time to load native libraries: 2 ms (timestamps 1715-1717)
I/LibraryLoader( 3608): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3608): Binding Chromium to main looper Looper (main, tid 1) {3d545caa}
,I/LibraryLoader( 3608): Expected native library version number "",actual native library version number "",
I/chromium( 3608): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3608): Initializing chromium process, singleProcess=true
,W/art     ( 3608): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3608): ApplicationContext is null in ApplicationStatus
,W/chromium( 3608): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3608): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3608): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3608): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/BluetoothManagerService(  821): Message: 20
,D/BluetoothManagerService(  821): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@22947ab3:true
,W/art     ( 3608): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3608): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3608): CordovaWebView is running on device made by: motorola
,W/art     ( 3608): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3608): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3608): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,D/Atlas   ( 3608): Validating map...,
,V/WindowManager(  821): Adding window Window{193176a3 u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{16375ac3 u0 Starting com.test.thalitest})
,W/chromium( 3608): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup,
,I/OpenGLRenderer( 3608): Initialized EGL, version 1.4,
,D/OpenGLRenderer( 3608): Enabling debug mode 0
,I/ActivityManager(  821): Displayed com.test.thalitest/.MainActivity: +760ms
,I/Keyboard.Facilitator( 1214): onFinishInput()
,W/BindingManager( 3608): Cannot call determinedVisibility() - never saw a connection for the pid: 3608
,D/JsMessageQueue( 3608): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3608): JniHelper::setJavaVM(0xb489d200), pthread_self() = -1576269440
D/JX-Cordova( 3608): jxcore cordova android initializing
,I/kickstart(  873): STATUS: Received file 'm9kefs2'
I/kickstart(  873): STATUS: 950272 bytes transferred in 0.995619 seconds
I/kickstart(  873): STATUS: Successfully downloaded files from target 
I/kickstart(  873): STATUS: Wrote to /sys/power/wake_unlock
,I/kickstart(  873): STATUS: Sahara protocol completed
,W/jxcore-log( 3608): Initializing JXcore engine
W/jxcore-log( 3608): JXcore engine is ready
,W/jxcore-log( 3608): Starting JXcore engine
,W/.test.thalitest( 3608): type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[13036]" dev="sockfs" ino=13036 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 3608): type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/.test.thalitest( 3608): type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[9883]" dev="sockfs" ino=9883 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/.test.thalitest( 3608): type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[19456]" dev="sockfs" ino=19456 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0,
,W/jxcore-log( 3608): Platform android,
W/jxcore-log( 3608): ,
W/jxcore-log( 3608): Process ARCH arm
W/jxcore-log( 3608): 
,I/jxcore-log( 3608): JXcore Cordova bridge is ready!
I/jxcore-log( 3608): 
W/jxcore-log( 3608): JXcore engine is started
,I/Choreographer( 3608): Skipped 135 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3608): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3608): Toggling radios to true
I/jxcore-log( 3608): 
,D/BluetoothAdapter( 3608): enable(): BT is already enabled..!
,D/WifiService(  821): setWifiEnabled: true pid=3608, uid=10265
E/WifiService(  821): Invoking mWifiStateMachine.setWifiEnabled
D/WifiService(  821): New client listening to asynchronous messages
,I/jxcore-log( 3608): Radios toggled
I/jxcore-log( 3608): 
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/jxcore-log( 3608): Got Device Bluetooth address: F8:CF:C5:D9:E5:61
I/jxcore-log( 3608): 
,I/jxcore-log( 3608): Perf Test app loaded loaded
I/jxcore-log( 3608): 
,I/wpa_supplicant( 1148): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,I/Choreographer( 3608): Skipped 64 frames!  The application may be doing too much work on its main thread.
E/WifiStateMachine(  821): WifiStateMachine: Leaving Connected state
,E/WifiConfigStore(  821): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  354): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1472): Read error: ssl=0xb4886400: I/O error during system call, Connection timed out
V/NativeCrypto( 1472): SSL shutdown failed: ssl=0xb4886400: I/O error during system call, Broken pipe
,D/ConnectivityService(  821): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10011
D/ConnectivityService(  821): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): DefaultState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  821): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): Forcing reevaluation
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
,I/jxcore-log( 3608): check test folder
I/jxcore-log( 3608): 
,E/WifiStateMachine(  821): Start Disconnecting Watchdog 1
,I/jxcore-log( 3608): found test : ./testFindPeers.js
I/jxcore-log( 3608): 
,E/WifiStateMachine(  821): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,I/jxcore-log( 3608): found test : ./testSendData.js
I/jxcore-log( 3608): 
,D/CommandListener(  354): Clearing all IP addresses on wlan0
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
,D/ConnectivityService(  821): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler( 1063): CM callback handler got msg 524292
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): OfflineState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): Disconnected - quitting
,D/CSLegacyTypeTracker(  821): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/WifiNetworkAgent(  821): NetworkAgent: NetworkAgent channel lost
,E/WifiStateMachine(  821): CMD_AUTO_CONNECT sup state CompletedState my state DisconnectedState nid=0 roam=3
,D/Tethering(  821): MasterInitialState.processMessage what=3
,D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
E/WifiStateMachine(  821): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=0
D/ConnectivityService(  821): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/ConnectivityService(  821): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/ConnectivityService(  821): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/Tethering(  821): MasterInitialState.processMessage what=3
,V/MusicLeanback( 3211): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/PhoneInterfaceManager( 1256): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1256): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  821): getDataEnabled: retVal=false
,E/WifiConfigStore(  821): Setting BSSID for "NG7005g"WPA_PSK to any
E/WifiConfigStore(  821): will read network variables netId=0
,I/ActivityManager(  821): Start proc 3670:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.steen.receiver.ConnectivityChangeReceiver
,E/WifiStateMachine(  821): CMD_AUTO_CONNECT did save config ->  nid=0
,E/GpsLocationProvider(  821): No APN found to select.
,E/WifiConfigStore(  821): will read network variables netId=0
,I/chromium( 3608): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/PhoneInterfaceManager( 1256): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1256): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
D/TelephonyManager(  821): getDataEnabled: retVal=false
,E/GpsLocationProvider(  821): No APN found to select.
,V/GLSActivity( 1472): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1472): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1472): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1472): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1472): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1472): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2981): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 2981): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 2981): [1] 5.onFinished: Scheduling replication attempt 3.
,I/ActivityManager(  821): Start proc 3697:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,I/ActivityManager(  821): Killing 2275:com.google.android.calendar/u0a37 (adj 15): empty #17
,I/art     (  369): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 226us total 10.620ms
,I/art     (  369): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 199us total 9.627ms
,I/art     (  369): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 198us total 8.845ms
,D/SprintDMReceiver( 3697): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3697): simOperator:  IMSI: null,
D/SprintDMReceiver( 3697): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1771): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1771): onCreate
,D/SystemUpdateService( 1771): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1771): active receiver: enabled
,I/SystemUpdateService( 1771): showing system update notification
,I/iu.Environment( 1771): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1771): num queued entries: 0
,I/iu.UploadsManager( 1771): num updated entries: 0
,I/iu.SyncManager( 1771): NEXT; no task
,I/ValidateNoPeople(  821): skipping global notification
,D/ChimeraCfgMgr( 1771): Loading module com.google.android.gms.kids from APK com.google.android.gms
,V/SystemUpdateService( 1771): retry (wakeup: false) in 3599947 ms
,I/art     ( 1498): WaitForGcToComplete blocked for 38.604ms for cause HomogeneousSpaceCompact
,D/SystemUpdateService( 1771): onDestroy
,I/art     (  821): Explicit concurrent mark sweep GC freed 44988(2MB) AllocSpace objects, 12(286KB) LOS objects, 32% free, 33MB/49MB, paused 1.406ms total 67.442ms
,I/ActivityManager(  821): Start proc 3722:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,I/Babel   ( 2906): connection state changed from UNKNOWN to DISCONNECTED
,I/ActivityManager(  821): Killing 3165:com.android.providers.calendar/u0a3 (adj 15): empty #17
,I/GAv4    ( 3722): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3722):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3722):   adb logcat -s GAv4
,W/GAv4    ( 3722): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3722): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3722): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 3722): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3722): Time to load native libraries: 2 ms (timestamps 7119-7121)
I/LibraryLoader( 3722): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3722): Binding Chromium to main looper Looper (main, tid 1) {24410099}
,I/LibraryLoader( 3722): Expected native library version number "",actual native library version number ""
I/chromium( 3722): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3722): Initializing chromium process, singleProcess=true
W/art     ( 3722): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3722): ApplicationContext is null in ApplicationStatus
,W/chromium( 3722): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3722): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3722): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3722): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,W/AudioManagerAndroid( 3722): Requires BLUETOOTH permission
,I/NSApplication( 3722): Starting up...
,I/ActivityManager(  821): Start proc 3778:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,I/ActivityManager(  821): Killing 1355:android.process.acore/u0a5 (adj 15): empty #17
,I/wpa_supplicant( 1148): wlan0: Trying to associate with SSID 'NG7005g'
,I/ActivityManager(  821): Start proc 3799:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,I/ActivityManager(  821): Killing 3416:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,I/wpa_supplicant( 1148): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 1148): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP],
I/wpa_supplicant( 1148): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=0 id_str=],
,D/ConnectivityService(  821): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} }
,D/ConnectivityService(  821): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  821): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiConfigStore(  821): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any,
,D/CommandListener(  354): Setting iface cfg
,E/WifiStateMachine(  821): Start Dhcp Watchdog 2
,E/WifiStateMachine(  821):  WifiLinkLayerStats: 
E/WifiStateMachine(  821):  my bss beacon rx: 555
E/WifiStateMachine(  821):  RSSI mgmt: -48
E/WifiStateMachine(  821):  BE :  rx=216 tx=127 lost=0 retries=1
E/WifiStateMachine(  821):  BK :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  821):  VI :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  821):  VO :  rx=4 tx=0 lost=0 retries=0
E/WifiStateMachine(  821):  on_time : 15098 tx_time=285 rx_time=606 scan_time=0
,D/ConnectivityService(  821): updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,E/native  (  821): do suspend false
,E/WifiStateMachine(  821): scanCount==0 - aborting
,V/MusicLeanback( 3211): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/ActivityManager(  821): Killing 3437:com.android.musicfx/u0a18 (adj 15): empty #17
,D/SprintDMReceiver( 3697): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,I/dhcpcd  ( 3817): version 5.5.6 starting
,D/SprintDMHelper( 3697): simOperator:  IMSI: null
D/SprintDMReceiver( 3697): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1771): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1771): onCreate
,D/SystemUpdateService( 1771): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1771): active receiver: enabled
,I/SystemUpdateService( 1771): showing system update notification
,D/ChimeraCfgMgr( 1771): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/ValidateNoPeople(  821): skipping global notification
,I/dhcpcd  ( 3817): wlan0: rebinding lease of 192.168.1.122
,V/SystemUpdateService( 1771): retry (wakeup: false) in 3599956 ms
,D/SystemUpdateService( 1771): onDestroy
,I/dhcpcd  ( 3817): wlan0: acknowledged 192.168.1.122 from 192.168.1.1
,I/dhcpcd  ( 3817): wlan0: leased 192.168.1.122 for 86400 seconds,
,D/ConnectivityService(  821): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  821): Adding iface wlan0 to network 101
,E/WifiStateMachine(  821): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  821): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  821): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  821): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101,
,D/ConnectivityService(  821): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  821): Setting Dns servers for network 101 to [/192.168.1.1]
,D/ConnectivityService(  821): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  821): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  821): rematching NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  821):    accepting network in place of null
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  821): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  821): Connected
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  821): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  821): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
,D/ConnectivityService(  821): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} }
D/ConnectivityService(  821): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/CSLegacyTypeTracker(  821): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 1063): CM callback handler got msg 524290
D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  821): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 3211): type=WIFI subType= reason=null isConnected=true
,D/PhoneInterfaceManager( 1256): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1256): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  821): getDataEnabled: retVal=false
,V/MusicLeanback( 3211): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,E/GpsLocationProvider(  821): No APN found to select.
,D/SprintDMReceiver( 3697): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3697): simOperator:  IMSI: null
D/SprintDMReceiver( 3697): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1771): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1771): onCreate
,D/SystemUpdateService( 1771): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1771): active receiver: enabled
,I/SystemUpdateService( 1771): showing system update notification
,I/iu.Environment( 1771): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1771): num queued entries: 0
I/iu.UploadsManager( 1771): num updated entries: 0
,I/iu.SyncManager( 1771): NEXT; no task
,D/ChimeraCfgMgr( 1771): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/ValidateNoPeople(  821): skipping global notification
,D/ChimeraCfgMgr( 1771): Loading module com.google.android.gms.kids from APK com.google.android.gms
,V/SystemUpdateService( 1771): retry (wakeup: false) in 3599969 ms
,D/SystemUpdateService( 1771): onDestroy
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  821): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 16 Dec 2015 04:38:45 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1450240725188], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1450240725157]}
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  821): Validated
D/ConnectivityService(  821): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/ConnectivityService(  821): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  821): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  821): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  821): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 1063): CM callback handler got msg 524290
,I/GLSUser ( 1472): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1472): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1472): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1472): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/Herrevad( 1771): NQAS connected
,V/GLSActivity( 1472): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Babel   ( 2906): connection state changed from DISCONNECTED to CONNECTED
,W/Kids    ( 1771): [AccountUtils] Account not ready
W/Kids    ( 1771): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 1771): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 1771): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 1771): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 1771): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 1771): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 1771): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 1771): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 1771): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 1771): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 1771): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 1771): 	at java.lang.Thread.run(Thread.java:818)
,D/GCM     ( 1472): Connected
,D/GCM     ( 1472): Message class com.google.f.a.a.p
,I/jxcore-log( 3608): BLE advertisement not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 3608): 
,D/ConnectivityService(  821): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=8.91 rxSuccessRate=10.22 targetRoamBSSID=any RSSI=-48
E/WifiStateMachine(  821): WifiStateMachine L2Connected CMD_START_SCAN source -2 10, 11 -> obsolete
,E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=3.23 rxSuccessRate=4.55 targetRoamBSSID=any RSSI=-48
E/WifiStateMachine(  821): WifiStateMachine L2Connected CMD_START_SCAN source -2 9, 11 -> obsolete
,I/PowerManagerService(  821): Going to sleep due to screen timeout (uid 1000)...
,I/Adreno  (  821): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d,
,D/PermissionCache(  259): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (342 us)
,D/SurfaceFlinger(  259): Set power mode=0, type=0 flinger=0xb6082000
,D/qdhwcomposer(  259): hwc_setPowerMode: Setting mode 0 on display: 0
I/DisplayManagerService(  821): Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager(  821): Display changed displayId=0,
,I/qdhwcomposer(  259): handle_blank_event: dpy:0 panel power state: 0
,D/qdhwcomposer(  259): hwc_setPowerMode: Done setting mode 0 on display 0
D/SurfaceControl(  821): Excessive delay in setPowerMode(): 281ms
,I/DreamManagerService(  821): Entering dreamland.
,I/PowerManagerService(  821): Dozing...
I/DreamController(  821): Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,D/audio_hw_primary(  358): adev_set_parameters: enter: screen_state=on
D/mot_vr_audio_hw(  358): adev_set_parameters: screen_state=on
,E/WifiStateMachine(  821): cancelDelayedScan -> 12
,E/native  (  821): do suspend false
,I/Keyboard.Facilitator( 1214): onFinishInput()
,E/WifiStateMachine(  821): cancelDelayedScan -> 14,
,E/native  (  821): do suspend true
,D/audio_hw_primary(  358): adev_set_parameters: enter: screen_state=off,
D/mot_vr_audio_hw(  358): adev_set_parameters: screen_state=off
,E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-48
E/WifiStateMachine(  821): WifiStateMachine L2Connected CMD_START_SCAN source -2 13, 14 -> obsolete
,V/GLSActivity( 1472): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1472): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1472): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1472): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1472): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1472): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/Finsky  ( 2981): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 2981): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 2981): [1] 5.onFinished: Scheduling replication attempt 4.
,I/BooksSync( 3515): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3515): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1472): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1472): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1472): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1472): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1472): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1472): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1472): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1472): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1472): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1472): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3515): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3515): Soft error
E/BooksSync( 3515): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3515): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3515): Sync error
E/BooksSync( 3515): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3515): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3515): Finished books sync
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 168129, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/art     (  821): Explicit concurrent mark sweep GC freed 53702(2MB) AllocSpace objects, 8(222KB) LOS objects, 31% free, 34MB/50MB, paused 2.456ms total 78.349ms
,I/GLSUser ( 1472): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1472): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1472): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1472): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1472): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3313): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3313): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3313): 	at jdm.a(PG:82)
E/HttpOperation( 3313): 	at jcs.o(PG:406)
E/HttpOperation( 3313): 	at jcn.a(PG:1379)
E/HttpOperation( 3313): 	at jcs.i(PG:143)
E/HttpOperation( 3313): 	at blb.a(PG:3937)
E/HttpOperation( 3313): 	at czp.a(PG:18188)
E/HttpOperation( 3313): 	at czp.a(PG:9081)
E/HttpOperation( 3313): 	at czq.run(PG:1686)
E/HttpOperation( 3313): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3313): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3313): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3313): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3313): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3313): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3313): 	at jdj.a(PG:4091)
E/HttpOperation( 3313): 	at jdj.a(PG:1125)
E/HttpOperation( 3313): 	at jdm.a(PG:77)
E/HttpOperation( 3313): 	... 12 more
E/HttpOperation( 3313): Caused by: faj: BadAuthentication
E/HttpOperation( 3313): 	at fal.a(PG:38)
E/HttpOperation( 3313): 	at jdj.a(PG:4089)
E/HttpOperation( 3313): 	... 14 more
,I/GLSUser ( 1472): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1472): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1472): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1472): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1472): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/HttpOperation( 3313): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3313): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3313): 	at jdm.a(PG:82)
E/HttpOperation( 3313): 	at jcs.o(PG:406)
E/HttpOperation( 3313): 	at jcn.a(PG:1379)
E/HttpOperation( 3313): 	at jcs.i(PG:143)
E/HttpOperation( 3313): 	at hec.a(PG:42)
E/HttpOperation( 3313): 	at hee.a(PG:102)
E/HttpOperation( 3313): 	at czr.a(PG:65)
E/HttpOperation( 3313): 	at kka.a(PG:108)
E/HttpOperation( 3313): 	at czp.a(PG:19176)
E/HttpOperation( 3313): 	at czp.a(PG:9081)
E/HttpOperation( 3313): 	at czq.run(PG:1686)
E/HttpOperation( 3313): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3313): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3313): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3313): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3313): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3313): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3313): 	at jdj.a(PG:4091)
E/HttpOperation( 3313): 	at jdj.a(PG:1125)
E/HttpOperation( 3313): 	at jdm.a(PG:77)
E/HttpOperation( 3313): 	... 15 more
E/HttpOperation( 3313): Caused by: faj: BadAuthentication
E/HttpOperation( 3313): 	at fal.a(PG:38)
E/HttpOperation( 3313): 	at jdj.a(PG:4089)
E/HttpOperation( 3313): 	... 17 more
,E/ExperimentLoader( 3313): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3313): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3313): 	at jdm.a(PG:82)
E/ExperimentLoader( 3313): 	at jcs.o(PG:406)
E/ExperimentLoader( 3313): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3313): 	at jcs.i(PG:143)
E/ExperimentLoader( 3313): 	at hec.a(PG:42)
E/ExperimentLoader( 3313): 	at hee.a(PG:102)
E/ExperimentLoader( 3313): 	at czr.a(PG:65)
E/ExperimentLoader( 3313): 	at kka.a(PG:108)
E/ExperimentLoader( 3313): 	at czp.a(PG:19176)
E/ExperimentLoader( 3313): 	at czp.a(PG:9081)
E/ExperimentLoader( 3313): 	at czq.run(PG:1686)
E/ExperimentLoader( 3313): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3313): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3313): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3313): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3313): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3313): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3313): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3313): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3313): 	at jdm.a(PG:77)
E/ExperimentLoader( 3313): 	... 15 more
E/ExperimentLoader( 3313): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3313): 	at fal.a(PG:38)
E/ExperimentLoader( 3313): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3313): 	... 17 more
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 168394, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-48
E/WifiStateMachine(  821): WifiStateMachine L2Connected CMD_START_SCAN source -2 11, 14 -> obsolete
,V/GLSActivity( 1472): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GoogleAuthProtoRequest( 3670): [391] a.<init>: mAccountName set to: thalitester@gmail.com
,I/VacuumService( 1472): Vacuum at: now=1450240761587 tag=VacuumService
,I/art     ( 1472): Explicit concurrent mark sweep GC freed 34704(2014KB) AllocSpace objects, 6(661KB) LOS objects, 37% free, 26MB/42MB, paused 1.220ms total 41.347ms
,I/GLSUser ( 1472): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1472): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1472): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1472): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1472): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3670): [391] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,V/GLSActivity( 1472): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ExperimentUpdateService( 3670): [391] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
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
,D/HeadsetStateMachine( 2363): Disconnected process message: 10, size: 0
,I/GoogleURLConnFactory( 1472): Using platform SSLCertificateSocketFactory
,I/GLSUser ( 1472): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1472): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1472): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1472): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1472): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2981): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 2981): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 2981): [1] 5.onFinished: Scheduling replication attempt 5.
,I/GLSUser ( 1472): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1472): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1472): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1472): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1472): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1472): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1472): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1472): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1472): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1472): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1472): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1472): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1472): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1472): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1472): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1472): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1472): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1472): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1472): No account for auth token provided
,D/HeadsetStateMachine( 2363): Disconnected process message: 10, size: 0
,W/Uploader( 1472): No account for auth token provided,
,W/Uploader( 1472): No account for auth token provided
,I/GLSUser ( 1472): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog,
,I/GLSUser ( 1472): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1472): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1472): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1472): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1472): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1472): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1472): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1472): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1472): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1472): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1472): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1472): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1472): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1472): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1472): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1472): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1472): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1472): No account for auth token provided
,W/Uploader( 1472): No account for auth token provided
,W/Uploader( 1472): No account for auth token provided
,I/GLSUser ( 1472): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1472): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1472): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1472): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1472): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1472): Failed to get auth token: User intervention required. Notification has been pushed.,
E/Uploader( 1472): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1472): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1472): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1472): 	at com.google.android.gms.auth.p.c(SourceFile:550)
,E/Uploader( 1472): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1472): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1472): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1472): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1472): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
,E/Uploader( 1472): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1472): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1472): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1472): No account for auth token provided
,W/Uploader( 1472): No account for auth token provided
,W/Uploader( 1472): No account for auth token provided
,W/Uploader( 1472): No account for auth token provided
,W/Uploader( 1472):  no longer exists, so no auth token.
,I/GLSUser ( 1472): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1472): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1472): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1472): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1472): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1472): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1472): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1472): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1472): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1472): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1472): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1472): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1472): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1472): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1472): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1472): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1472): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1472): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,V/KeepSync( 3547): Connecting to GoogleApiClient
,I/GLSUser ( 1472): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1472): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1472): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1472): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1472): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/ClientConnectionOperation( 1771): Handling authorization failure
E/ClientConnectionOperation( 1771): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1771): ,	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1771): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1771): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1771): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1771): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1771): 	... 7 more
,V/KeepSync( 3547): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3547): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3547): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3547): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1472): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1472): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1472): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1472): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1472): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3547): IOException
E/KeepSync( 3547): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3547): ,	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
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
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 171448, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,V/GoogleAuthProtoRequest( 3670): [392] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1472): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1472): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1472): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1472): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1472): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3670): [392] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3670): [392] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
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
,V/GLSActivity( 1472): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  821): Explicit concurrent mark sweep GC freed 31873(1449KB) AllocSpace objects, 4(252KB) LOS objects, 31% free, 34MB/50MB, paused 1.644ms total 95.547ms
,I/GLSUser ( 1472): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1472): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1472): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1472): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1472): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2981): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 2981): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 2981): [1] 5.onFinished: Giving up after 6 failures.
,I/Keyboard.Facilitator.LanguageModelFlusher( 1214): run()
I/Keyboard.Facilitator( 1214): flushDynamicLanguageModels()
,I/ConfigService( 1472): onCreate
,I/BooksSync( 3515): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3515): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1472): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1472): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1472): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1472): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1472): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1472): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native,
I/GLSUser ( 1472): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1472): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1472): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1472): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/HttpOperation( 3313): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3313): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3313): 	at jdm.a(PG:82)
E/HttpOperation( 3313): 	at jcs.o(PG:406)
E/HttpOperation( 3313): 	at jcn.a(PG:1379)
E/HttpOperation( 3313): 	at jcs.i(PG:143)
E/HttpOperation( 3313): 	at blb.a(PG:3937)
E/HttpOperation( 3313): 	at czp.a(PG:18188)
E/HttpOperation( 3313): 	at czp.a(PG:9081)
E/HttpOperation( 3313): 	at czq.run(PG:1686)
E/HttpOperation( 3313): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3313): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3313): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3313): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3313): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3313): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3313): 	at jdj.a(PG:4091)
E/HttpOperation( 3313): 	at jdj.a(PG:1125)
E/HttpOperation( 3313): 	at jdm.a(PG:77)
E/HttpOperation( 3313): 	... 12 more
E/HttpOperation( 3313): Caused by: faj: BadAuthentication
E/HttpOperation( 3313): 	at fal.a(PG:38)
E/HttpOperation( 3313): 	at jdj.a(PG:4089)
E/HttpOperation( 3313): 	... 14 more
,I/GLSUser ( 1472): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1472): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1472): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1472): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1472): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1472): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books,
I/GLSUser ( 1472): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1472): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1472): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1472): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3313): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3313): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3313): 	at jdm.a(PG:82)
E/HttpOperation( 3313): 	at jcs.o(PG:406)
E/HttpOperation( 3313): 	at jcn.a(PG:1379)
E/HttpOperation( 3313): 	at jcs.i(PG:143)
E/HttpOperation( 3313): 	at hec.a(PG:42)
E/HttpOperation( 3313): 	at hee.a(PG:102)
E/HttpOperation( 3313): 	at czr.a(PG:65)
E/HttpOperation( 3313): 	at kka.a(PG:108)
E/HttpOperation( 3313): 	at czp.a(PG:19176)
E/HttpOperation( 3313): 	at czp.a(PG:9081)
E/HttpOperation( 3313): 	at czq.run(PG:1686)
E/HttpOperation( 3313): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3313): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3313): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3313): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3313): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3313): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3313): 	at jdj.a(PG:4091)
E/HttpOperation( 3313): 	at jdj.a(PG:1125)
E/HttpOperation( 3313): 	at jdm.a(PG:77)
E/HttpOperation( 3313): 	... 15 more
E/HttpOperation( 3313): Caused by: faj: BadAuthentication
E/HttpOperation( 3313): 	at fal.a(PG:38)
E/HttpOperation( 3313): 	at jdj.a(PG:4089)
E/HttpOperation( 3313): 	... 17 more
E/ExperimentLoader( 3313): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3313): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3313): 	at jdm.a(PG:82)
E/ExperimentLoader( 3313): 	at jcs.o(PG:406)
E/ExperimentLoader( 3313): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3313): 	at jcs.i(PG:143)
E/ExperimentLoader( 3313): 	at hec.a(PG:42)
E/ExperimentLoader( 3313): 	at hee.a(PG:102)
E/ExperimentLoader( 3313): 	at czr.a(PG:65)
E/ExperimentLoader( 3313): 	at kka.a(PG:108)
E/ExperimentLoader( 3313): 	at czp.a(PG:19176)
E/ExperimentLoader( 3313): 	at czp.a(PG:9081)
E/ExperimentLoader( 3313): 	at czq.run(PG:1686)
E/ExperimentLoader( 3313): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3313): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3313): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3313): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3313): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3313): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3313): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3313): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3313): 	at jdm.a(PG:77)
E/ExperimentLoader( 3313): 	... 15 more
E/ExperimentLoader( 3313): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3313): 	at fal.a(PG:38)
E/ExperimentLoader( 3313): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3313): 	... 17 more
,E/BooksAccountManager( 3515): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3515): Soft error
E/BooksSync( 3515): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3515): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3515): Sync error
E/BooksSync( 3515): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3515): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3515): Finished books sync
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 198925, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/ConfigService( 1472): onDestroy
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 201262, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2363): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2363): Disconnected process message: 10, size: 0,
,V/KeepSync( 3547): Connecting to GoogleApiClient
,I/GLSUser ( 1472): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1472): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1472): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1472): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1472): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1771): Handling authorization failure
E/ClientConnectionOperation( 1771): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1771): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1771): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1771): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1771): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1771): 	... 7 more
,V/KeepSync( 3547): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3547): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3547): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3547): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1472): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1472): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1472): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1472): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1472): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 228723, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2363): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2363): Disconnected process message: 10, size: 0
,V/GoogleAuthProtoRequest( 3670): [393] a.<init>: mAccountName set to: thalitester@gmail.com
,I/art     ( 1472): Explicit concurrent mark sweep GC freed 69214(3MB) AllocSpace objects, 8(729KB) LOS objects, 36% free, 28MB/44MB, paused 976us total 44.177ms
,I/GLSUser ( 1472): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1472): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1472): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1472): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1472): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3670): [393] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3670): [393] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
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
,I/BooksSync( 3515): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3515): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1472): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1472): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1472): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1472): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1472): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1472): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1472): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1472): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1472): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,V/GLSActivity( 1472): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3313): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3313): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3313): 	at jdm.a(PG:82)
E/HttpOperation( 3313): 	at jcs.o(PG:406)
E/HttpOperation( 3313): 	at jcn.a(PG:1379)
E/HttpOperation( 3313): 	at jcs.i(PG:143)
E/HttpOperation( 3313): 	at blb.a(PG:3937)
E/HttpOperation( 3313): 	at czp.a(PG:18188)
E/HttpOperation( 3313): 	at czp.a(PG:9081)
E/HttpOperation( 3313): 	at czq.run(PG:1686)
E/HttpOperation( 3313): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3313): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3313): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3313): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3313): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3313): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3313): 	at jdj.a(PG:4091)
E/HttpOperation( 3313): 	at jdj.a(PG:1125)
E/HttpOperation( 3313): 	at jdm.a(PG:77)
E/HttpOperation( 3313): 	... 12 more
E/HttpOperation( 3313): Caused by: faj: BadAuthentication
E/HttpOperation( 3313): 	at fal.a(PG:38)
E/HttpOperation( 3313): 	at jdj.a(PG:4089)
E/HttpOperation( 3313): 	... 14 more
,I/GLSUser ( 1472): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1472): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1472): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1472): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1472): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/HttpOperation( 3313): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3313): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3313): 	at jdm.a(PG:82)
E/HttpOperation( 3313): 	at jcs.o(PG:406)
E/HttpOperation( 3313): 	at jcn.a(PG:1379)
E/HttpOperation( 3313): 	at jcs.i(PG:143)
E/HttpOperation( 3313): 	at hec.a(PG:42)
E/HttpOperation( 3313): 	at hee.a(PG:102)
E/HttpOperation( 3313): 	at czr.a(PG:65)
E/HttpOperation( 3313): 	at kka.a(PG:108)
E/HttpOperation( 3313): 	at czp.a(PG:19176)
E/HttpOperation( 3313): 	at czp.a(PG:9081)
E/HttpOperation( 3313): 	at czq.run(PG:1686)
E/HttpOperation( 3313): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3313): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3313): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3313): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3313): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3313): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3313): 	at jdj.a(PG:4091)
E/HttpOperation( 3313): 	at jdj.a(PG:1125)
E/HttpOperation( 3313): 	at jdm.a(PG:77)
E/HttpOperation( 3313): 	... 15 more
E/HttpOperation( 3313): Caused by: faj: BadAuthentication
E/HttpOperation( 3313): 	at fal.a(PG:38)
E/HttpOperation( 3313): 	at jdj.a(PG:4089)
E/HttpOperation( 3313): 	... 17 more
,E/ExperimentLoader( 3313): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3313): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3313): 	at jdm.a(PG:82)
,E/ExperimentLoader( 3313): 	at jcs.o(PG:406)
E/ExperimentLoader( 3313): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3313): 	at jcs.i(PG:143)
E/ExperimentLoader( 3313): 	at hec.a(PG:42)
E/ExperimentLoader( 3313): 	at hee.a(PG:102)
,E/ExperimentLoader( 3313): 	at czr.a(PG:65)
E/ExperimentLoader( 3313): 	at kka.a(PG:108)
E/ExperimentLoader( 3313): 	at czp.a(PG:19176)
E/ExperimentLoader( 3313): 	at czp.a(PG:9081)
E/ExperimentLoader( 3313): 	at czq.run(PG:1686)
E/ExperimentLoader( 3313): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3313): ,	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3313): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3313): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3313): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3313): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3313): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3313): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3313): 	at jdm.a(PG:77)
E/ExperimentLoader( 3313): ,	... 15 more
E/ExperimentLoader( 3313): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3313): 	at fal.a(PG:38)
E/ExperimentLoader( 3313): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3313): 	... 17 more
,I/GLSUser ( 1472): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1472): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1472): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1472): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1472): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3515): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3515): Soft error
E/BooksSync( 3515): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3515): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3515): Sync error
E/BooksSync( 3515): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3515): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3515): Finished books sync
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 289373, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 293078, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/jxcore-log( 3608): Connected to the server!
I/jxcore-log( 3608): 
,I/chromium( 3608): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,V/KeepSync( 3547): Connecting to GoogleApiClient
,I/art     (  821): Explicit concurrent mark sweep GC freed 34936(1507KB) AllocSpace objects, 11(647KB) LOS objects, 31% free, 34MB/50MB, paused 2.470ms total 94.026ms
,I/GLSUser ( 1472): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1472): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1472): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1472): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1472): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1771): Handling authorization failure
E/ClientConnectionOperation( 1771): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1771): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1771): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1771): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1771): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1771): 	... 7 more
,V/KeepSync( 3547): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3547): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3547): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3547): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1472): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1472): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1472): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1472): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1472): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 319057, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/WifiService(  821): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@7610b4b}
,E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-48
,D/WifiService(  821): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@7610b4b}
,E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::injectLocation(GpsExtLocation):857]: error! inject position failed
,V/GLSActivity( 1472): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1472): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1472): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1472): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1472): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1472): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1472): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1472): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1472): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1472): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1472): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1472): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1472): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 2981): Failed to get auth token: User intervention required. Notification has been pushed.,
E/PlayEventLogger( 2981): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 2981): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 2981): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 2981): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/PlayEventLogger( 2981): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 2981): ,	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 2981): Ignoring header User-Agent because its value was null.
,D/HeadsetStateMachine( 2363): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2363): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2363): Disconnected process message: 10, size: 0
,V/GoogleAuthProtoRequest( 3670): [394] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1472): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1472): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1472): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1472): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1472): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3670): [394] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3670): [394] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
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
,I/BooksSync( 3515): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3515): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1472): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1472): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1472): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1472): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1472): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1472): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1472): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1472): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1472): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1472): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3515): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3515): Soft error
E/BooksSync( 3515): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3515): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3515): Sync error
E/BooksSync( 3515): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3515): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3515): Finished books sync
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 440383, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,V/KeepSync( 3547): Connecting to GoogleApiClient
,I/GLSUser ( 1472): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1472): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1472): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1472): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1472): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1472): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1472): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1472): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1472): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1472): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3313): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3313): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3313): 	at jdm.a(PG:82)
E/HttpOperation( 3313): 	at jcs.o(PG:406)
E/HttpOperation( 3313): 	at jcn.a(PG:1379)
E/HttpOperation( 3313): 	at jcs.i(PG:143)
E/HttpOperation( 3313): 	at blb.a(PG:3937)
E/HttpOperation( 3313): 	at czp.a(PG:18188)
E/HttpOperation( 3313): 	at czp.a(PG:9081)
E/HttpOperation( 3313): 	at czq.run(PG:1686)
E/HttpOperation( 3313): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3313): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3313): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3313): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3313): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3313): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3313): 	at jdj.a(PG:4091)
E/HttpOperation( 3313): 	at jdj.a(PG:1125)
E/HttpOperation( 3313): 	at jdm.a(PG:77)
E/HttpOperation( 3313): 	... 12 more
E/HttpOperation( 3313): Caused by: faj: BadAuthentication
E/HttpOperation( 3313): 	at fal.a(PG:38)
E/HttpOperation( 3313): 	at jdj.a(PG:4089)
E/HttpOperation( 3313): 	... 14 more
,E/ClientConnectionOperation( 1771): Handling authorization failure
E/ClientConnectionOperation( 1771): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1771): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1771): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1771): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1771): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1771): 	... 7 more
,V/KeepSync( 3547): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3547): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3547): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3547): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1472): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1472): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1472): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1472): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1472): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3313): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3313): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3313): 	at jdm.a(PG:82)
E/HttpOperation( 3313): 	at jcs.o(PG:406)
E/HttpOperation( 3313): 	at jcn.a(PG:1379)
E/HttpOperation( 3313): 	at jcs.i(PG:143)
E/HttpOperation( 3313): 	at hec.a(PG:42)
E/HttpOperation( 3313): 	at hee.a(PG:102)
E/HttpOperation( 3313): 	at czr.a(PG:65)
E/HttpOperation( 3313): 	at kka.a(PG:108)
E/HttpOperation( 3313): 	at czp.a(PG:19176)
E/HttpOperation( 3313): 	at czp.a(PG:9081)
E/HttpOperation( 3313): 	at czq.run(PG:1686)
E/HttpOperation( 3313): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3313): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3313): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3313): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3313): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3313): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3313): 	at jdj.a(PG:4091)
E/HttpOperation( 3313): 	at jdj.a(PG:1125)
E/HttpOperation( 3313): 	at jdm.a(PG:77)
E/HttpOperation( 3313): 	... 15 more
E/HttpOperation( 3313): Caused by: faj: BadAuthentication
E/HttpOperation( 3313): 	at fal.a(PG:38)
E/HttpOperation( 3313): 	at jdj.a(PG:4089)
E/HttpOperation( 3313): 	... 17 more
E/ExperimentLoader( 3313): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3313): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3313): 	at jdm.a(PG:82)
E/ExperimentLoader( 3313): 	at jcs.o(PG:406)
E/ExperimentLoader( 3313): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3313): 	at jcs.i(PG:143)
E/ExperimentLoader( 3313): 	at hec.a(PG:42)
E/ExperimentLoader( 3313): 	at hee.a(PG:102)
E/ExperimentLoader( 3313): 	at czr.a(PG:65)
E/ExperimentLoader( 3313): 	at kka.a(PG:108)
E/ExperimentLoader( 3313): 	at czp.a(PG:19176)
E/ExperimentLoader( 3313): 	at czp.a(PG:9081)
E/ExperimentLoader( 3313): 	at czq.run(PG:1686)
E/ExperimentLoader( 3313): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3313): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3313): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3313): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3313): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3313): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3313): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3313): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3313): 	at jdm.a(PG:77)
E/ExperimentLoader( 3313): 	... 15 more
E/ExperimentLoader( 3313): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3313): 	at fal.a(PG:38)
E/ExperimentLoader( 3313): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3313): 	... 17 more
,I/GLSUser ( 1472): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1472): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1472): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1472): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1472): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 447613, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 469435, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/art     (  821): Explicit concurrent mark sweep GC freed 31428(1429KB) AllocSpace objects, 12(474KB) LOS objects, 31% free, 34MB/50MB, paused 1.594ms total 55.715ms
,D/HeadsetStateMachine( 2363): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2363): Disconnected process message: 10, size: 0
,I/ActivityManager(  821): Start proc 4011:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider
,I/GAv4    ( 4011): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4011):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4011):   adb logcat -s GAv4
,W/GAv4    ( 4011): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.,
,W/GAv4    ( 4011): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4011): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  821): Killing 3260:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,D/HeadsetStateMachine( 2363): Disconnected process message: 10, size: 0,
,D/HeadsetStateMachine( 2363): Disconnected process message: 10, size: 0
,I/art     ( 1472): Explicit concurrent mark sweep GC freed 55735(2MB) AllocSpace objects, 17(1874KB) LOS objects, 36% free, 27MB/43MB, paused 1.078ms total 54.183ms
,D/HeadsetStateMachine( 2363): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2363): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2363): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2363): Disconnected process message: 10, size: 0
,V/GoogleAuthProtoRequest( 3670): [395] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1472): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1472): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1472): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1472): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1472): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3670): [395] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3670): [395] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
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
,I/BooksSync( 3515): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3515): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1472): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1472): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1472): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1472): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1472): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1472): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1472): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1472): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1472): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1472): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/BooksAccountManager( 3515): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3515): Soft error
E/BooksSync( 3515): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3515): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3515): Sync error
E/BooksSync( 3515): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3515): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 3515): Finished books sync
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 684039, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,V/KeepSync( 3547): Connecting to GoogleApiClient
,I/GLSUser ( 1472): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1472): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1472): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1472): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1472): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1771): Handling authorization failure
E/ClientConnectionOperation( 1771): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1771): ,	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1771): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1771): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1771): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1771): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1771): ,	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1771): 	... 7 more
,V/KeepSync( 3547): GoogleApiClient failed to connect with error code: 4
E/SQLiteLog( 3547): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3547): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3547): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1472): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1472): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1472): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1472): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1472): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 711749, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2363): Disconnected process message: 10, size: 0
,I/GLSUser ( 1472): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1472): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1472): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1472): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1472): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/HttpOperation( 3313): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3313): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3313): 	at jdm.a(PG:82)
E/HttpOperation( 3313): 	at jcs.o(PG:406)
E/HttpOperation( 3313): 	at jcn.a(PG:1379)
E/HttpOperation( 3313): 	at jcs.i(PG:143)
E/HttpOperation( 3313): 	at blb.a(PG:3937)
E/HttpOperation( 3313): 	at czp.a(PG:18188)
E/HttpOperation( 3313): 	at czp.a(PG:9081)
E/HttpOperation( 3313): 	at czq.run(PG:1686)
E/HttpOperation( 3313): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3313): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3313): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3313): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3313): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3313): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3313): 	at jdj.a(PG:4091)
E/HttpOperation( 3313): 	at jdj.a(PG:1125)
E/HttpOperation( 3313): 	at jdm.a(PG:77)
E/HttpOperation( 3313): 	... 12 more
E/HttpOperation( 3313): Caused by: faj: BadAuthentication
E/HttpOperation( 3313): 	at fal.a(PG:38)
E/HttpOperation( 3313): 	at jdj.a(PG:4089)
E/HttpOperation( 3313): 	... 14 more
,I/GLSUser ( 1472): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1472): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1472): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1472): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1472): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3313): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3313): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3313): 	at jdm.a(PG:82)
E/HttpOperation( 3313): 	at jcs.o(PG:406)
E/HttpOperation( 3313): 	at jcn.a(PG:1379)
E/HttpOperation( 3313): 	at jcs.i(PG:143)
E/HttpOperation( 3313): 	at hec.a(PG:42)
E/HttpOperation( 3313): 	at hee.a(PG:102)
E/HttpOperation( 3313): 	at czr.a(PG:65)
E/HttpOperation( 3313): 	at kka.a(PG:108)
E/HttpOperation( 3313): 	at czp.a(PG:19176)
E/HttpOperation( 3313): 	at czp.a(PG:9081)
E/HttpOperation( 3313): 	at czq.run(PG:1686)
E/HttpOperation( 3313): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3313): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3313): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3313): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3313): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3313): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3313): 	at jdj.a(PG:4091)
E/HttpOperation( 3313): 	at jdj.a(PG:1125)
E/HttpOperation( 3313): 	at jdm.a(PG:77)
E/HttpOperation( 3313): 	... 15 more
E/HttpOperation( 3313): Caused by: faj: BadAuthentication
E/HttpOperation( 3313): 	at fal.a(PG:38)
E/HttpOperation( 3313): 	at jdj.a(PG:4089)
E/HttpOperation( 3313): 	... 17 more
E/ExperimentLoader( 3313): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3313): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3313): 	at jdm.a(PG:82)
E/ExperimentLoader( 3313): 	at jcs.o(PG:406)
E/ExperimentLoader( 3313): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3313): 	at jcs.i(PG:143)
E/ExperimentLoader( 3313): 	at hec.a(PG:42)
E/ExperimentLoader( 3313): 	at hee.a(PG:102)
E/ExperimentLoader( 3313): 	at czr.a(PG:65)
E/ExperimentLoader( 3313): 	at kka.a(PG:108)
E/ExperimentLoader( 3313): 	at czp.a(PG:19176)
E/ExperimentLoader( 3313): 	at czp.a(PG:9081)
E/ExperimentLoader( 3313): 	at czq.run(PG:1686)
E/ExperimentLoader( 3313): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3313): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3313): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3313): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3313): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3313): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3313): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3313): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3313): 	at jdm.a(PG:77)
E/ExperimentLoader( 3313): 	... 15 more
E/ExperimentLoader( 3313): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3313): 	at fal.a(PG:38)
E/ExperimentLoader( 3313): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3313): 	... 17 more
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 728498, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2363): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2363): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2363): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2363): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2363): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2363): Disconnected process message: 10, size: 0
,W/bt-btm  ( 2363): Stopping oneshot timer
,D/HeadsetStateMachine( 2363): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2363): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2363): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2363): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2363): Disconnected process message: 10, size: 0
,I/EventLogService( 1771): Opted in for usage reporting
I/EventLogService( 1771): Aggregate from 1450239793827 (log), 1450239793827 (data)
,D/GCM     ( 1472): Message class com.google.f.a.a.i
,W/EventLogAggregator( 1771): Unknown tag: snet_gcore
W/EventLogAggregator( 1771): Unknown tag: snet_launch_service
,I/ServiceDumpSys( 1771): dumping service [account]
,I/art     (  821): Explicit concurrent mark sweep GC freed 44141(2MB) AllocSpace objects, 9(521KB) LOS objects, 31% free, 34MB/50MB, paused 1.563ms total 60.495ms
,V/GoogleAuthProtoRequest( 3670): [396] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1472): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1472): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1472): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1472): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1472): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3670): [396] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3670): [396] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
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
,I/BooksSync( 3515): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3515): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1472): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1472): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1472): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1472): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1472): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1472): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1472): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1472): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1472): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1472): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1472): Explicit concurrent mark sweep GC freed 66720(3MB) AllocSpace objects, 13(1434KB) LOS objects, 36% free, 27MB/43MB, paused 1.422ms total 84.789ms
,E/BooksAccountManager( 3515): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3515): Soft error
E/BooksSync( 3515): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3515): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3515): Sync error
E/BooksSync( 3515): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3515): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3515): Finished books sync
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1170893, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,V/KeepSync( 3547): Connecting to GoogleApiClient
,I/GLSUser ( 1472): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1472): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1472): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1472): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1472): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1771): Handling authorization failure
E/ClientConnectionOperation( 1771): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1771): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1771): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1771): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1771): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1771): 	... 7 more
,V/KeepSync( 3547): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3547): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3547): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3547): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1472): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1472): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1472): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1472): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1472): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
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
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 1196259, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2363): Disconnected process message: 10, size: 0
,I/UsageStatsService(  821): User[0] Flushing usage stats to disk
,I/GLSUser ( 1472): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1472): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1472): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1472): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1472): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3313): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3313): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3313): 	at jdm.a(PG:82)
E/HttpOperation( 3313): 	at jcs.o(PG:406)
E/HttpOperation( 3313): 	at jcn.a(PG:1379)
E/HttpOperation( 3313): 	at jcs.i(PG:143)
E/HttpOperation( 3313): 	at blb.a(PG:3937)
E/HttpOperation( 3313): 	at czp.a(PG:18188)
E/HttpOperation( 3313): 	at czp.a(PG:9081)
E/HttpOperation( 3313): 	at czq.run(PG:1686)
E/HttpOperation( 3313): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3313): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3313): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3313): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3313): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3313): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3313): 	at jdj.a(PG:4091)
E/HttpOperation( 3313): 	at jdj.a(PG:1125)
E/HttpOperation( 3313): 	at jdm.a(PG:77)
E/HttpOperation( 3313): 	... 12 more
E/HttpOperation( 3313): Caused by: faj: BadAuthentication
E/HttpOperation( 3313): 	at fal.a(PG:38)
E/HttpOperation( 3313): 	at jdj.a(PG:4089)
E/HttpOperation( 3313): 	... 14 more
,I/GLSUser ( 1472): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1472): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1472): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1472): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1472): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3313): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3313): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3313): 	at jdm.a(PG:82)
E/HttpOperation( 3313): 	at jcs.o(PG:406)
E/HttpOperation( 3313): 	at jcn.a(PG:1379)
E/HttpOperation( 3313): 	at jcs.i(PG:143)
E/HttpOperation( 3313): 	at hec.a(PG:42)
E/HttpOperation( 3313): 	at hee.a(PG:102)
E/HttpOperation( 3313): 	at czr.a(PG:65)
E/HttpOperation( 3313): 	at kka.a(PG:108)
E/HttpOperation( 3313): 	at czp.a(PG:19176)
E/HttpOperation( 3313): 	at czp.a(PG:9081)
E/HttpOperation( 3313): 	at czq.run(PG:1686)
E/HttpOperation( 3313): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3313): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3313): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3313): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3313): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3313): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3313): 	at jdj.a(PG:4091)
E/HttpOperation( 3313): 	at jdj.a(PG:1125)
E/HttpOperation( 3313): 	at jdm.a(PG:77)
E/HttpOperation( 3313): 	... 15 more
E/HttpOperation( 3313): Caused by: faj: BadAuthentication
E/HttpOperation( 3313): 	at fal.a(PG:38)
E/HttpOperation( 3313): 	at jdj.a(PG:4089)
E/HttpOperation( 3313): 	... 17 more
,E/ExperimentLoader( 3313): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3313): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3313): 	at jdm.a(PG:82)
E/ExperimentLoader( 3313): 	at jcs.o(PG:406)
E/ExperimentLoader( 3313): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3313): 	at jcs.i(PG:143)
E/ExperimentLoader( 3313): 	at hec.a(PG:42)
E/ExperimentLoader( 3313): 	at hee.a(PG:102)
E/ExperimentLoader( 3313): 	at czr.a(PG:65)
E/ExperimentLoader( 3313): 	at kka.a(PG:108)
E/ExperimentLoader( 3313): 	at czp.a(PG:19176)
E/ExperimentLoader( 3313): 	at czp.a(PG:9081)
E/ExperimentLoader( 3313): 	at czq.run(PG:1686)
E/ExperimentLoader( 3313): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3313): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3313): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3313): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3313): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3313): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3313): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3313): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3313): 	at jdm.a(PG:77)
E/ExperimentLoader( 3313): 	... 15 more
E/ExperimentLoader( 3313): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3313): 	at fal.a(PG:38)
E/ExperimentLoader( 3313): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3313): 	... 17 more
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 1259857, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2363): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2363): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2363): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2363): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2363): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2363): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2363): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2363): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2363): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2363): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2363): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2363): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2363): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2363): Disconnected process message: 10, size: 0
,I/ProcessStatsService(  821): Prepared write state in 15ms
,I/ProcessStatsService(  821): Pruning old procstats: /data/system/procstats/state-2015-12-15-18-46-21.bin
,I/art     (  821): Explicit concurrent mark sweep GC freed 51828(2MB) AllocSpace objects, 16(523KB) LOS objects, 31% free, 34MB/50MB, paused 1.854ms total 92.924ms
,W/bt-btm  ( 2363): Stopping oneshot timer
,D/HeadsetStateMachine( 2363): Disconnected process message: 10, size: 0
,I/ActivityManager(  821): Killing 3365:com.android.defcontainer/u0a7 (adj 15): empty for 1816s
,I/ActivityManager(  821): Killing 3465:com.google.android.apps.docs/u0a46 (adj 15): empty for 1817s
,D/HeadsetStateMachine( 2363): Disconnected process message: 10, size: 0
,TIME-OUT KILL (timeout was 1800000ms)
```
