#### Test 506502789b39735_thali05_motorola-Nexus 6 Logs


```
--------- beginning of main
,E/WifiStateMachine(  823): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=6.81 targetRoamBSSID=any RSSI=-48
E/WifiStateMachine(  823): WifiStateMachine starting scan for "NG7005g"WPA_PSK with 2412,5220
D/AndroidRuntime( 3620): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 3620): CheckJNI is OFF
D/AndroidRuntime( 3620): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  823): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/WindowManager(  823): addAppToken: AppWindowToken{1ac181fc token=Token{243e42ef ActivityRecord{13073ce u0 com.test.thalitest/.MainActivity t26}}} to stack=1 task=26 at 0
D/AndroidRuntime( 3620): Shutting down VM
V/WindowManager(  823): Adding window Window{2dd17001 u0 Starting com.test.thalitest} at 2 of 7 (after Window{26143476 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
I/MicrophoneInputStream( 1475): mic_close com.google.android.apps.gsa.speech.audio.u@28f0bd42
I/HotwordDetector( 1475): Closing mic
I/ActivityManager(  823): Start proc 3634:com.test.thalitest/u0a265 for activity com.test.thalitest/.MainActivity
D/audio_hw_primary(  358): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  358): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  358): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1475): Stopping hotword detection.
I/HotwordRecognitionRnr( 1475): Hotword detection finished
I/ActivityManager(  823): Killing 3058:com.google.android.gm/u0a78 (adj 15): empty #17
E/LocSvc_IzatApiV02(  823): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1660413203
E/LocSvc_IzatApiV02(  823): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,I/ActivityManager(  823): Killing 2684:com.google.android.apps.maps/u0a65 (adj 15): empty #18
,I/kickstart(  874): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
I/kickstart(  874): STATUS: Wrote to /sys/power/wake_lock
,E/kickstart(  874): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2
I/kickstart(  874): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2' for writing
,I/WebViewFactory( 3634): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3634): Time to load native libraries: 2 ms (timestamps 1560-1562)
I/LibraryLoader( 3634): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3634): Binding Chromium to main looper Looper (main, tid 1) {20e7f2e5}
,I/LibraryLoader( 3634): Expected native library version number "",actual native library version number ""
I/chromium( 3634): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3634): Initializing chromium process, singleProcess=true
,W/art     ( 3634): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3634): ApplicationContext is null in ApplicationStatus
,W/chromium( 3634): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3634): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3634): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno  ( 3634): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/BluetoothManagerService(  823): Message: 20
D/BluetoothManagerService(  823): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3529d28a:true
,W/art     ( 3634): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3634): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3634): CordovaWebView is running on device made by: motorola
,W/art     ( 3634): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3634): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3634): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,D/Atlas   ( 3634): Validating map...
,V/WindowManager(  823): Adding window Window{2a302e1 u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{2dd17001 u0 Starting com.test.thalitest})
,W/chromium( 3634): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup,
,I/OpenGLRenderer( 3634): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3634): Enabling debug mode 0
,I/ActivityManager(  823): Displayed com.test.thalitest/.MainActivity: +938ms
,I/Keyboard.Facilitator( 1216): onFinishInput()
,W/BindingManager( 3634): Cannot call determinedVisibility() - never saw a connection for the pid: 3634
,D/JsMessageQueue( 3634): Set native->JS mode to OnlineEventsBridgeMode
,I/kickstart(  874): STATUS: Received file 'm9kefs2'
I/kickstart(  874): STATUS: 950272 bytes transferred in 0.997996 seconds
I/kickstart(  874): STATUS: Successfully downloaded files from target 
I/kickstart(  874): STATUS: Wrote to /sys/power/wake_unlock
,I/kickstart(  874): STATUS: Sahara protocol completed
,D/jxcore_app_log( 3634): JniHelper::setJavaVM(0xb489d200), pthread_self() = -1576185344
,D/JX-Cordova( 3634): jxcore cordova android initializing,
,W/jxcore-log( 3634): Initializing JXcore engine
W/jxcore-log( 3634): JXcore engine is ready
,W/jxcore-log( 3634): Starting JXcore engine
,W/.test.thalitest( 3634): type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[12953]" dev="sockfs" ino=12953 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 3634): type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/.test.thalitest( 3634): type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[10519]" dev="sockfs" ino=10519 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/.test.thalitest( 3634): type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[24600]" dev="sockfs" ino=24600 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 3634): Platform android
W/jxcore-log( 3634): 
,W/jxcore-log( 3634): Process ARCH arm
W/jxcore-log( 3634): 
,I/jxcore-log( 3634): JXcore Cordova bridge is ready!,
I/jxcore-log( 3634): 
,W/jxcore-log( 3634): JXcore engine is started,
,I/Choreographer( 3634): Skipped 140 frames!  The application may be doing too much work on its main thread.,
,I/chromium( 3634): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3634): Toggling radios to true
I/jxcore-log( 3634): 
,D/BluetoothAdapter( 3634): enable(): BT is already enabled..!,
,D/WifiService(  823): setWifiEnabled: true pid=3634, uid=10265
E/WifiService(  823): Invoking mWifiStateMachine.setWifiEnabled
D/WifiService(  823): New client listening to asynchronous messages
,I/jxcore-log( 3634): Radios toggled,
I/jxcore-log( 3634): 
,D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0,
,I/jxcore-log( 3634): Got Device Bluetooth address: F8:CF:C5:D9:E5:61,
I/jxcore-log( 3634): 
I/jxcore-log( 3634): Perf Test app loaded loaded
I/jxcore-log( 3634): 
I/Choreographer( 3634): Skipped 63 frames!  The application may be doing too much work on its main thread.
,I/wpa_supplicant( 1202): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  823): WifiStateMachine: Leaving Connected state
,E/WifiConfigStore(  823): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  354): Clearing all IP addresses on wlan0
,I/jxcore-log( 3634): check test folder
I/jxcore-log( 3634): 
,I/jxcore-log( 3634): found test : ./testFindPeers.js
I/jxcore-log( 3634): 
,V/NativeCrypto( 1507): Read error: ssl=0xb4888600: I/O error during system call, Connection timed out
,V/NativeCrypto( 1507): SSL shutdown failed: ssl=0xb4888600: I/O error during system call, Broken pipe
,D/ConnectivityService(  823): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10011
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  823): ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  823): DefaultState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  823): Forcing reevaluation
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  823): EvaluatingState{ when=0 what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  823): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
,I/jxcore-log( 3634): found test : ./testSendData.js,
I/jxcore-log( 3634): 
D/ConnectivityService(  823): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  823): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
E/WifiStateMachine(  823): Start Disconnecting Watchdog 1
,E/WifiStateMachine(  823): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  823): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
,D/CommandListener(  354): Clearing all IP addresses on wlan0
,D/ConnectivityService(  823): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler( 1067): CM callback handler got msg 524292
,D/WifiNetworkAgent(  823): NetworkAgent: NetworkAgent channel lost
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  823): OfflineState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  823): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  823): Disconnected - quitting
D/CSLegacyTypeTracker(  823): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  823): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  823): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
E/WifiStateMachine(  823): CMD_AUTO_CONNECT sup state CompletedState my state DisconnectedState nid=0 roam=3
E/WifiStateMachine(  823): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=0
D/Tethering(  823): MasterInitialState.processMessage what=3
I/NetworkMonitor( 3241): type=WIFI subType= reason=null isConnected=false
D/ConnectivityService(  823): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  823): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  823): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/Tethering(  823): MasterInitialState.processMessage what=3
,E/ConnectivityService(  823): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/ConnectivityService(  823): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
,V/MusicLeanback( 3241): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/PhoneInterfaceManager( 1260): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1260): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  823): getDataEnabled: retVal=false
,E/GpsLocationProvider(  823): No APN found to select.
,D/PhoneInterfaceManager( 1260): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1260): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  823): getDataEnabled: retVal=false
,E/GpsLocationProvider(  823): No APN found to select.
,E/WifiConfigStore(  823): Setting BSSID for "NG7005g"WPA_PSK to any
,I/chromium( 3634): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,E/WifiConfigStore(  823): will read network variables netId=0
,E/WifiStateMachine(  823): CMD_AUTO_CONNECT did save config ->  nid=0
,E/WifiConfigStore(  823): will read network variables netId=0
,I/ActivityManager(  823): Start proc 3695:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.steen.receiver.ConnectivityChangeReceiver
,I/art     (  370): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 332us total 19.158ms
,I/art     (  370): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 279us total 10.058ms
,I/art     (  370): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 203us total 8.527ms
,I/ActivityManager(  823): Start proc 3726:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,V/GLSActivity( 1507): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1507): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1507): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1507): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1507): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/art     (  823): Explicit concurrent mark sweep GC freed 45256(2MB) AllocSpace objects, 11(176KB) LOS objects, 32% free, 33MB/49MB, paused 1.062ms total 51.709ms
V/GLSActivity( 1507): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SprintDMReceiver( 3726): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/Finsky  ( 3000): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3000): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3000): [1] 5.onFinished: Scheduling replication attempt 3.
,D/SprintDMHelper( 3726): simOperator:  IMSI: null
D/SprintDMReceiver( 3726): Not Sprint UICC, don't do anything.
,I/ActivityManager(  823): Killing 2272:com.google.android.calendar/u0a37 (adj 15): empty #17
,I/SystemUpdateService( 1773): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1773): onCreate
,D/SystemUpdateService( 1773): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1773): active receiver: enabled
,I/SystemUpdateService( 1773): showing system update notification
,I/iu.Environment( 1773): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/ValidateNoPeople(  823): skipping global notification
,D/ChimeraCfgMgr( 1773): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/iu.UploadsManager( 1773): num queued entries: 0
I/iu.UploadsManager( 1773): num updated entries: 0
I/iu.SyncManager( 1773): NEXT; no task
,V/SystemUpdateService( 1773): retry (wakeup: false) in 3599977 ms
,I/ActivityManager(  823): Start proc 3747:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,I/Babel   ( 2920): connection state changed from UNKNOWN to DISCONNECTED
,D/SystemUpdateService( 1773): onDestroy
,I/ActivityManager(  823): Killing 3181:com.android.providers.calendar/u0a3 (adj 15): empty #17
,I/GAv4    ( 3747): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3747):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3747):   adb logcat -s GAv4
,W/GAv4    ( 3747): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3747): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3747): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.,
,I/WebViewFactory( 3747): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3747): Time to load native libraries: 3 ms (timestamps 6950-6953),
I/LibraryLoader( 3747): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3747): Binding Chromium to main looper Looper (main, tid 1) {259b7770}
,I/LibraryLoader( 3747): Expected native library version number "",actual native library version number ""
I/chromium( 3747): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3747): Initializing chromium process, singleProcess=true
,W/art     ( 3747): Attempt to remove local handle scope entry from IRT, ignoring,
,E/SysUtils( 3747): ApplicationContext is null in ApplicationStatus
,W/chromium( 3747): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3747): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 3747): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3747): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,W/AudioManagerAndroid( 3747): Requires BLUETOOTH permission
,I/NSApplication( 3747): Starting up...,
,I/ActivityManager(  823): Start proc 3803:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,I/ActivityManager(  823): Killing 2701:android.process.acore/u0a5 (adj 15): empty #17
,E/lowmemorykiller(  256): Error writing /proc/2701/oom_score_adj; errno=22
,I/ActivityManager(  823): Start proc 3824:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,I/ActivityManager(  823): Killing 3443:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,I/wpa_supplicant( 1202): wlan0: Trying to associate with SSID 'NG7005g'
,V/MusicLeanback( 3241): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/ActivityManager(  823): Killing 3464:com.android.musicfx/u0a18 (adj 15): empty #17
,I/wpa_supplicant( 1202): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 1202): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 1202): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=0 id_str=]
,D/SprintDMReceiver( 3726): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  823): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} }
E/WifiConfigStore(  823): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/ConnectivityService(  823): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,D/SprintDMHelper( 3726): simOperator:  IMSI: null
D/SprintDMReceiver( 3726): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1773): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,E/WifiConfigStore(  823): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  354): Setting iface cfg
,D/SystemUpdateService( 1773): onCreate
,E/WifiStateMachine(  823): Start Dhcp Watchdog 2
,E/WifiStateMachine(  823):  WifiLinkLayerStats: 
E/WifiStateMachine(  823):  my bss beacon rx: 546
E/WifiStateMachine(  823):  RSSI mgmt: -48
E/WifiStateMachine(  823):  BE :  rx=208 tx=122 lost=0 retries=1
E/WifiStateMachine(  823):  BK :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  823):  VI :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  823):  VO :  rx=4 tx=0 lost=0 retries=0,
E/WifiStateMachine(  823):  on_time : 13813 tx_time=288 rx_time=561 scan_time=0
,D/SystemUpdateService( 1773): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,D/ConnectivityService(  823): updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,I/SystemUpdateService( 1773): active receiver: enabled
,I/SystemUpdateService( 1773): showing system update notification
,I/ValidateNoPeople(  823): skipping global notification
,D/ChimeraCfgMgr( 1773): Loading module com.google.android.gms.kids from APK com.google.android.gms
,V/SystemUpdateService( 1773): retry (wakeup: false) in 3599962 ms
,D/SystemUpdateService( 1773): onDestroy
,E/native  (  823): do suspend false
,E/WifiStateMachine(  823): scanCount==0 - aborting
,I/dhcpcd  ( 3849): version 5.5.6 starting
,I/dhcpcd  ( 3849): wlan0: rebinding lease of 192.168.1.122
,I/dhcpcd  ( 3849): wlan0: acknowledged 192.168.1.122 from 192.168.1.1
,I/dhcpcd  ( 3849): wlan0: leased 192.168.1.122 for 86400 seconds
,D/ConnectivityService(  823): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  823): Adding iface wlan0 to network 101
,E/WifiStateMachine(  823): Did not find remoteAddress {192.168.1.1} in /proc/net/arp,
,E/ConnectivityService(  823): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  823): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  823): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  823): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  823): Setting Dns servers for network 101 to [/192.168.1.1],
,D/ConnectivityService(  823): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  823): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  823): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  823):    accepting network in place of null
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  823): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  823): Connected
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  823): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  823): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
D/ConnectivityService(  823): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} }
,D/ConnectivityService(  823): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/CSLegacyTypeTracker(  823): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityManager.CallbackHandler( 1067): CM callback handler got msg 524290
D/ConnectivityService(  823): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  823): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  823): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 3241): type=WIFI subType= reason=null isConnected=true
D/PhoneInterfaceManager( 1260): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
,E/PhoneInterfaceManager( 1260): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
D/TelephonyManager(  823): getDataEnabled: retVal=false
,V/MusicLeanback( 3241): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,E/GpsLocationProvider(  823): No APN found to select.
,D/SprintDMReceiver( 3726): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3726): simOperator:  IMSI: null
D/SprintDMReceiver( 3726): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1773): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1773): onCreate
,D/SystemUpdateService( 1773): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) },
,I/SystemUpdateService( 1773): active receiver: enabled
,I/SystemUpdateService( 1773): showing system update notification
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  823): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 16 Dec 2015 01:34:56 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1450229696651], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1450229696637]}
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  823): Validated
D/ConnectivityService(  823): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
,D/ConnectivityService(  823): Validated NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  823): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  823): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  823): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler( 1067): CM callback handler got msg 524290
D/ConnectivityService(  823): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,I/iu.Environment( 1773): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1773): num queued entries: 0
,I/iu.UploadsManager( 1773): num updated entries: 0
,I/iu.SyncManager( 1773): NEXT; no task
,I/ValidateNoPeople(  823): skipping global notification
,D/ChimeraCfgMgr( 1773): Loading module com.google.android.gms.kids from APK com.google.android.gms
,V/SystemUpdateService( 1773): retry (wakeup: false) in 3599952 ms
,D/ChimeraCfgMgr( 1773): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/SystemUpdateService( 1773): onDestroy
,I/GLSUser ( 1507): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1507): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1507): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1507): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1507): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/Herrevad( 1773): NQAS connected
,W/Kids    ( 1773): [AccountUtils] Account not ready
W/Kids    ( 1773): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 1773): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 1773): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 1773): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 1773): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 1773): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 1773): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 1773): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 1773): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 1773): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 1773): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 1773): 	at java.lang.Thread.run(Thread.java:818)
,I/Babel   ( 2920): connection state changed from DISCONNECTED to CONNECTED
,I/jxcore-log( 3634): BLE advertisement not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 3634): 
,D/GCM     ( 1507): Connected
,D/GCM     ( 1507): Message class com.google.f.a.a.p
,D/ConnectivityService(  823): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,E/WifiStateMachine(  823): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=8.83 rxSuccessRate=10.34 targetRoamBSSID=any RSSI=-48
E/WifiStateMachine(  823): WifiStateMachine L2Connected CMD_START_SCAN source -2 10, 11 -> obsolete
,E/WifiStateMachine(  823): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=2.96 rxSuccessRate=4.34 targetRoamBSSID=any RSSI=-48
E/WifiStateMachine(  823): WifiStateMachine L2Connected CMD_START_SCAN source -2 9, 11 -> obsolete
,I/PowerManagerService(  823): Going to sleep due to screen timeout (uid 1000)...
,I/Adreno  (  823): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/PermissionCache(  259): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (204 us)
,I/DisplayManagerService(  823): Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
D/SurfaceFlinger(  259): Set power mode=0, type=0 flinger=0xb6482000
D/qdhwcomposer(  259): hwc_setPowerMode: Setting mode 0 on display: 0
,V/ActivityManager(  823): Display changed displayId=0
,I/qdhwcomposer(  259): handle_blank_event: dpy:0 panel power state: 0
,D/qdhwcomposer(  259): hwc_setPowerMode: Done setting mode 0 on display 0
,D/SurfaceControl(  823): Excessive delay in setPowerMode(): 276ms
,I/DreamManagerService(  823): Entering dreamland.,
,I/DreamController(  823): Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
I/PowerManagerService(  823): Dozing...
,D/audio_hw_primary(  358): adev_set_parameters: enter: screen_state=on
D/mot_vr_audio_hw(  358): adev_set_parameters: screen_state=on
,E/WifiStateMachine(  823): cancelDelayedScan -> 12
,E/native  (  823): do suspend false
,I/Keyboard.Facilitator( 1216): onFinishInput()
,E/WifiStateMachine(  823): cancelDelayedScan -> 14
,E/native  (  823): do suspend true
,D/audio_hw_primary(  358): adev_set_parameters: enter: screen_state=off
D/mot_vr_audio_hw(  358): adev_set_parameters: screen_state=off
,E/WifiStateMachine(  823): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-48
E/WifiStateMachine(  823): WifiStateMachine L2Connected CMD_START_SCAN source -2 13, 14 -> obsolete
,V/KeepSync( 3540): Connecting to GoogleApiClient
,I/GLSUser ( 1507): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1507): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1507): [GLSUser] Extracting token using key: Auth,
W/GLSActivity( 1507): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,V/GLSActivity( 1507): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1773): Handling authorization failure
E/ClientConnectionOperation( 1773): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1773): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1773): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1773): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1773): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1773): 	... 7 more
,V/KeepSync( 3540): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3540): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3540): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3540): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1507): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1507): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1507): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1507): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1507): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3540): IOException
E/KeepSync( 3540): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3540): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3540): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3540): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3540): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3540): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3540): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3540): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3540): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3540): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3540): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3540): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3540): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3540): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3540): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3540): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3540): 	... 10 more
W/KeepSync( 3540): Sync result 2
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 166203, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/art     (  823): Explicit concurrent mark sweep GC freed 52976(2MB) AllocSpace objects, 8(316KB) LOS objects, 31% free, 34MB/50MB, paused 2.494ms total 97.243ms
,V/GLSActivity( 1507): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1507): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1507): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1507): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1507): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1507): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3000): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3000): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3000): [1] 5.onFinished: Scheduling replication attempt 4.
,E/WifiStateMachine(  823): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-48
E/WifiStateMachine(  823): WifiStateMachine L2Connected CMD_START_SCAN source -2 11, 14 -> obsolete
,V/GLSActivity( 1507): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GoogleAuthProtoRequest( 3695): [395] a.<init>: mAccountName set to: thalitester@gmail.com
,I/VacuumService( 1507): Vacuum at: now=1450229733026 tag=VacuumService
,I/GLSUser ( 1507): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1507): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1507): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1507): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1507): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1507): Explicit concurrent mark sweep GC freed 35704(1982KB) AllocSpace objects, 6(661KB) LOS objects, 37% free, 26MB/42MB, paused 860us total 27.775ms
,V/GLSActivity( 1507): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3695): [395] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3695): [395] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3695): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3695): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3695): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3695): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3695): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3695): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3695): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3695): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3695): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3695): 	at com.a.a.k.run(SourceFile:110)
,I/GoogleURLConnFactory( 1507): Using platform SSLCertificateSocketFactory
,D/HeadsetStateMachine( 2357): Disconnected process message: 10, size: 0
,I/GLSUser ( 1507): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1507): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1507): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1507): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1507): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3000): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3000): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3000): [1] 5.onFinished: Scheduling replication attempt 5.
,I/GLSUser ( 1507): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1507): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1507): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1507): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1507): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1507): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1507): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1507): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1507): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1507): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1507): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1507): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1507): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1507): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1507): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1507): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1507): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1507): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1507): No account for auth token provided
,W/Uploader( 1507): No account for auth token provided,
,I/GLSUser ( 1507): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1507): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1507): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1507): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1507): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/HeadsetStateMachine( 2357): Disconnected process message: 10, size: 0
,E/Uploader( 1507): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1507): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1507): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1507): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1507): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1507): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1507): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1507): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1507): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1507): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1507): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1507): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1507): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1507): No account for auth token provided
,W/Uploader( 1507): No account for auth token provided,
,W/Uploader( 1507): No account for auth token provided
,W/Uploader( 1507): No account for auth token provided
,I/GLSUser ( 1507): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1507): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1507): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1507): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1507): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1507): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1507): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1507): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1507): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1507): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1507): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1507): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1507): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1507): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1507): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1507): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1507): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1507): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1507): No account for auth token provided
,W/Uploader( 1507): No account for auth token provided
,W/Uploader( 1507): No account for auth token provided
,W/Uploader( 1507): No account for auth token provided
,W/Uploader( 1507):  no longer exists, so no auth token.
,I/GLSUser ( 1507): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1507): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1507): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1507): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1507): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1507): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1507): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1507): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1507): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1507): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1507): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1507): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1507): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1507): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1507): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1507): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1507): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1507): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/BooksSync( 3572): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3572): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1507): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1507): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1507): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1507): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1507): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1507): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1507): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1507): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1507): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1507): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3340): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3340): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3340): 	at jdm.a(PG:82)
E/HttpOperation( 3340): 	at jcs.o(PG:406)
E/HttpOperation( 3340): 	at jcn.a(PG:1379)
E/HttpOperation( 3340): 	at jcs.i(PG:143)
E/HttpOperation( 3340): 	at blb.a(PG:3937)
E/HttpOperation( 3340): 	at czp.a(PG:18188)
E/HttpOperation( 3340): 	at czp.a(PG:9081)
E/HttpOperation( 3340): 	at czq.run(PG:1686)
E/HttpOperation( 3340): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3340): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3340): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3340): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3340): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3340): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3340): 	at jdj.a(PG:4091)
E/HttpOperation( 3340): 	at jdj.a(PG:1125)
E/HttpOperation( 3340): 	at jdm.a(PG:77)
E/HttpOperation( 3340): 	... 12 more
E/HttpOperation( 3340): Caused by: faj: BadAuthentication
E/HttpOperation( 3340): 	at fal.a(PG:38)
E/HttpOperation( 3340): 	at jdj.a(PG:4089)
E/HttpOperation( 3340): 	... 14 more
,I/GLSUser ( 1507): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1507): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1507): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1507): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1507): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3340): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3340): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3340): 	at jdm.a(PG:82)
E/HttpOperation( 3340): 	at jcs.o(PG:406)
E/HttpOperation( 3340): 	at jcn.a(PG:1379)
E/HttpOperation( 3340): 	at jcs.i(PG:143)
E/HttpOperation( 3340): 	at hec.a(PG:42)
E/HttpOperation( 3340): 	at hee.a(PG:102)
E/HttpOperation( 3340): 	at czr.a(PG:65)
E/HttpOperation( 3340): 	at kka.a(PG:108)
E/HttpOperation( 3340): 	at czp.a(PG:19176)
E/HttpOperation( 3340): 	at czp.a(PG:9081)
E/HttpOperation( 3340): 	at czq.run(PG:1686)
E/HttpOperation( 3340): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3340): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3340): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3340): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3340): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3340): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3340): 	at jdj.a(PG:4091)
E/HttpOperation( 3340): 	at jdj.a(PG:1125)
E/HttpOperation( 3340): 	at jdm.a(PG:77)
E/HttpOperation( 3340): 	... 15 more
E/HttpOperation( 3340): Caused by: faj: BadAuthentication
E/HttpOperation( 3340): 	at fal.a(PG:38)
E/HttpOperation( 3340): 	at jdj.a(PG:4089)
E/HttpOperation( 3340): 	... 17 more
E/ExperimentLoader( 3340): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3340): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3340): 	at jdm.a(PG:82)
E/ExperimentLoader( 3340): 	at jcs.o(PG:406)
E/ExperimentLoader( 3340): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3340): 	at jcs.i(PG:143)
E/ExperimentLoader( 3340): 	at hec.a(PG:42)
E/ExperimentLoader( 3340): 	at hee.a(PG:102)
E/ExperimentLoader( 3340): 	at czr.a(PG:65)
E/ExperimentLoader( 3340): 	at kka.a(PG:108)
E/ExperimentLoader( 3340): 	at czp.a(PG:19176)
E/ExperimentLoader( 3340): 	at czp.a(PG:9081)
E/ExperimentLoader( 3340): 	at czq.run(PG:1686)
E/ExperimentLoader( 3340): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3340): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3340): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3340): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3340): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3340): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3340): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3340): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3340): 	at jdm.a(PG:77)
E/ExperimentLoader( 3340): 	... 15 more
E/ExperimentLoader( 3340): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3340): 	at fal.a(PG:38)
E/ExperimentLoader( 3340): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3340): 	... 17 more
,I/GLSUser ( 1507): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1507): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1507): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1507): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1507): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3572): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3572): Soft error
E/BooksSync( 3572): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3572): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3572): Sync error
E/BooksSync( 3572): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3572): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3572): Finished books sync
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 169042, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 170710, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,V/GoogleAuthProtoRequest( 3695): [396] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1507): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1507): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1507): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1507): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1507): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3695): [396] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3695): [396] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3695): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3695): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3695): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3695): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3695): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3695): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3695): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3695): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3695): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3695): 	at com.a.a.k.run(SourceFile:110)
,V/GLSActivity( 1507): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1507): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1507): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1507): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1507): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1507): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  823): Explicit concurrent mark sweep GC freed 33245(1497KB) AllocSpace objects, 4(158KB) LOS objects, 31% free, 34MB/50MB, paused 1.790ms total 69.430ms
,D/Finsky  ( 3000): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3000): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3000): [1] 5.onFinished: Giving up after 6 failures.
,I/Keyboard.Facilitator.LanguageModelFlusher( 1216): run()
,I/Keyboard.Facilitator( 1216): flushDynamicLanguageModels()
,I/ConfigService( 1507): onCreate
,V/KeepSync( 3540): Connecting to GoogleApiClient
,I/GLSUser ( 1507): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1507): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1507): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1507): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1507): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1773): Handling authorization failure,
E/ClientConnectionOperation( 1773): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1773): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1773): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1773): 	at java.lang.Thread.run(Thread.java:818)
,E/ClientConnectionOperation( 1773): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1773): 	... 7 more
,V/KeepSync( 3540): GoogleApiClient failed to connect with error code: 4
E/SQLiteLog( 3540): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3540): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3540): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1507): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1507): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1507): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1507): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1507): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3540): IOException
E/KeepSync( 3540): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3540): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3540): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3540): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3540): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3540): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3540): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3540): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3540): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3540): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3540): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3540): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3540): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3540): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3540): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3540): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3540): 	... 10 more
,W/KeepSync( 3540): Sync result 2,
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 198076, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1],
,I/ConfigService( 1507): onDestroy
,D/HeadsetStateMachine( 2357): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2357): Disconnected process message: 10, size: 0
,I/BooksSync( 3572): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3572): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1507): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1507): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1507): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1507): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1507): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1507): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1507): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1507): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1507): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1507): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1507): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1507): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1507): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1507): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1507): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3340): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3340): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3340): 	at jdm.a(PG:82)
E/HttpOperation( 3340): 	at jcs.o(PG:406)
E/HttpOperation( 3340): 	at jcn.a(PG:1379)
E/HttpOperation( 3340): 	at jcs.i(PG:143)
E/HttpOperation( 3340): 	at blb.a(PG:3937)
E/HttpOperation( 3340): 	at czp.a(PG:18188)
E/HttpOperation( 3340): 	at czp.a(PG:9081)
E/HttpOperation( 3340): 	at czq.run(PG:1686)
E/HttpOperation( 3340): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3340): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3340): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3340): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3340): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3340): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3340): 	at jdj.a(PG:4091)
E/HttpOperation( 3340): 	at jdj.a(PG:1125)
E/HttpOperation( 3340): 	at jdm.a(PG:77)
E/HttpOperation( 3340): 	... 12 more
E/HttpOperation( 3340): Caused by: faj: BadAuthentication
E/HttpOperation( 3340): 	at fal.a(PG:38)
E/HttpOperation( 3340): 	at jdj.a(PG:4089)
E/HttpOperation( 3340): 	... 14 more
,E/BooksAccountManager( 3572): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3572): Soft error
E/BooksSync( 3572): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3572): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3572): Sync error
E/BooksSync( 3572): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3572): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3572): Finished books sync
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 227380, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1507): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1507): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1507): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1507): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1507): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/art     ( 1507): Explicit concurrent mark sweep GC freed 69166(3MB) AllocSpace objects, 8(729KB) LOS objects, 36% free, 27MB/43MB, paused 1.095ms total 47.609ms
,E/HttpOperation( 3340): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3340): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3340): 	at jdm.a(PG:82)
E/HttpOperation( 3340): 	at jcs.o(PG:406)
E/HttpOperation( 3340): 	at jcn.a(PG:1379)
E/HttpOperation( 3340): 	at jcs.i(PG:143)
E/HttpOperation( 3340): 	at hec.a(PG:42)
E/HttpOperation( 3340): 	at hee.a(PG:102)
E/HttpOperation( 3340): 	at czr.a(PG:65)
E/HttpOperation( 3340): 	at kka.a(PG:108)
E/HttpOperation( 3340): 	at czp.a(PG:19176)
E/HttpOperation( 3340): 	at czp.a(PG:9081)
E/HttpOperation( 3340): 	at czq.run(PG:1686)
E/HttpOperation( 3340): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3340): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3340): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3340): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3340): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3340): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3340): 	at jdj.a(PG:4091)
E/HttpOperation( 3340): 	at jdj.a(PG:1125)
E/HttpOperation( 3340): 	at jdm.a(PG:77)
E/HttpOperation( 3340): 	... 15 more
E/HttpOperation( 3340): Caused by: faj: BadAuthentication
E/HttpOperation( 3340): 	at fal.a(PG:38)
E/HttpOperation( 3340): 	at jdj.a(PG:4089)
E/HttpOperation( 3340): 	... 17 more
E/ExperimentLoader( 3340): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3340): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3340): 	at jdm.a(PG:82)
E/ExperimentLoader( 3340): 	at jcs.o(PG:406)
E/ExperimentLoader( 3340): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3340): 	at jcs.i(PG:143)
E/ExperimentLoader( 3340): 	at hec.a(PG:42)
E/ExperimentLoader( 3340): 	at hee.a(PG:102)
E/ExperimentLoader( 3340): 	at czr.a(PG:65)
E/ExperimentLoader( 3340): 	at kka.a(PG:108)
E/ExperimentLoader( 3340): 	at czp.a(PG:19176)
E/ExperimentLoader( 3340): 	at czp.a(PG:9081)
E/ExperimentLoader( 3340): 	at czq.run(PG:1686)
E/ExperimentLoader( 3340): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3340): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3340): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3340): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3340): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3340): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3340): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3340): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3340): 	at jdm.a(PG:77)
E/ExperimentLoader( 3340): 	... 15 more
E/ExperimentLoader( 3340): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3340): 	at fal.a(PG:38)
E/ExperimentLoader( 3340): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3340): 	... 17 more
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 229125, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2357): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2357): Disconnected process message: 10, size: 0
,V/GoogleAuthProtoRequest( 3695): [397] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1507): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1507): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1507): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1507): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1507): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3695): [397] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3695): [397] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3695): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3695): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3695): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3695): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3695): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3695): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3695): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3695): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3695): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3695): 	at com.a.a.k.run(SourceFile:110)
,V/KeepSync( 3540): Connecting to GoogleApiClient
,I/GLSUser ( 1507): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1507): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1507): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1507): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1507): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1773): Handling authorization failure
E/ClientConnectionOperation( 1773): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1773): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1773): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1773): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1773): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1773): 	... 7 more
,V/KeepSync( 3540): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3540): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3540): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3540): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1507): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1507): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1507): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1507): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1507): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3540): IOException
E/KeepSync( 3540): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3540): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3540): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3540): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3540): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3540): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3540): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3540): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3540): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3540): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3540): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3540): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3540): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3540): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3540): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3540): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3540): 	... 10 more
,W/KeepSync( 3540): Sync result 2
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 289454, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/jxcore-log( 3634): Connected to the server!
I/jxcore-log( 3634): 
,I/chromium( 3634): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63),
,I/BooksSync( 3572): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3572): GmsCore Version = 7.8.99 (2134222-430)
,I/art     (  823): Explicit concurrent mark sweep GC freed 32743(1388KB) AllocSpace objects, 11(741KB) LOS objects, 31% free, 34MB/50MB, paused 1.706ms total 80.623ms
,I/GLSUser ( 1507): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1507): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1507): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1507): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1507): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1507): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1507): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1507): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1507): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1507): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/HttpOperation( 3340): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3340): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3340): 	at jdm.a(PG:82)
E/HttpOperation( 3340): 	at jcs.o(PG:406)
E/HttpOperation( 3340): 	at jcn.a(PG:1379)
E/HttpOperation( 3340): 	at jcs.i(PG:143)
E/HttpOperation( 3340): 	at blb.a(PG:3937)
E/HttpOperation( 3340): 	at czp.a(PG:18188)
E/HttpOperation( 3340): 	at czp.a(PG:9081)
E/HttpOperation( 3340): 	at czq.run(PG:1686)
E/HttpOperation( 3340): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3340): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3340): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3340): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3340): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3340): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3340): 	at jdj.a(PG:4091)
E/HttpOperation( 3340): 	at jdj.a(PG:1125)
E/HttpOperation( 3340): 	at jdm.a(PG:77)
E/HttpOperation( 3340): 	... 12 more
E/HttpOperation( 3340): Caused by: faj: BadAuthentication
E/HttpOperation( 3340): 	at fal.a(PG:38)
E/HttpOperation( 3340): 	at jdj.a(PG:4089)
E/HttpOperation( 3340): 	... 14 more
,I/GLSUser ( 1507): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1507): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1507): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1507): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1507): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1507): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1507): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1507): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
V/GLSActivity( 1507): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1507): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3572): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3572): Soft error
E/BooksSync( 3572): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3572): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3572): Sync error
E/BooksSync( 3572): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3572): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3572): Finished books sync
,E/HttpOperation( 3340): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3340): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3340): 	at jdm.a(PG:82)
E/HttpOperation( 3340): 	at jcs.o(PG:406)
E/HttpOperation( 3340): 	at jcn.a(PG:1379)
E/HttpOperation( 3340): 	at jcs.i(PG:143)
E/HttpOperation( 3340): 	,at hec.a(PG:42)
E/HttpOperation( 3340): 	at hee.a(PG:102)
E/HttpOperation( 3340): 	at czr.a(PG:65)
E/HttpOperation( 3340): 	at kka.a(PG:108)
E/HttpOperation( 3340): 	at czp.a(PG:19176)
E/HttpOperation( 3340): 	at czp.a(PG:9081)
E/HttpOperation( 3340): 	at czq.run(PG:1686)
E/HttpOperation( 3340): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3340): 	,at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3340): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3340): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3340): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3340): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3340): 	at jdj.a(PG:4091)
E/HttpOperation( 3340): 	at jdj.a(PG:1125)
E/HttpOperation( 3340): 	at jdm.a(PG:77)
E/HttpOperation( 3340): ,	... 15 more
E/HttpOperation( 3340): Caused by: faj: BadAuthentication
E/HttpOperation( 3340): 	at fal.a(PG:38)
E/HttpOperation( 3340): 	at jdj.a(PG:4089)
E/HttpOperation( 3340): 	... 17 more
E/ExperimentLoader( 3340): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3340): java.io.IOException: Cannot obtain authentication token,
E/ExperimentLoader( 3340): 	at jdm.a(PG:82)
E/ExperimentLoader( 3340): 	at jcs.o(PG:406)
E/ExperimentLoader( 3340): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3340): 	at jcs.i(PG:143)
E/ExperimentLoader( 3340): 	at hec.a(PG:42)
E/ExperimentLoader( 3340): 	at hee.a(PG:102)
E/ExperimentLoader( 3340): 	at czr.a(PG:65)
E/ExperimentLoader( 3340): 	at kka.a(PG:108)
E/ExperimentLoader( 3340): 	at czp.a(PG:19176)
,E/ExperimentLoader( 3340): 	at czp.a(PG:9081)
E/ExperimentLoader( 3340): 	at czq.run(PG:1686)
E/ExperimentLoader( 3340): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3340): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3340): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3340): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3340): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3340): Caused by: android.accounts.AuthenticatorException: Recoverable error,
E/ExperimentLoader( 3340): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3340): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3340): 	at jdm.a(PG:77)
E/ExperimentLoader( 3340): 	... 15 more
E/ExperimentLoader( 3340): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3340): 	at fal.a(PG:38)
E/ExperimentLoader( 3340): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3340): 	... 17 more
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 318353, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 321817, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/WifiService(  823): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@18c8b782}
,E/WifiStateMachine(  823): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-48
,D/WifiService(  823): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@18c8b782}
,E/LocSvc_IzatApiV02(  823): E/virtual int izat_core::IzatApiV02::injectLocation(GpsExtLocation):857]: error! inject position failed
,V/GLSActivity( 1507): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1507): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1507): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1507): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1507): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1507): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1507): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1507): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1507): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1507): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1507): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1507): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1507): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 3000): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3000): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3000): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 3000): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3000): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/PlayEventLogger( 3000): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3000): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 3000): Ignoring header User-Agent because its value was null.
,D/HeadsetStateMachine( 2357): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2357): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2357): Disconnected process message: 10, size: 0
,V/GoogleAuthProtoRequest( 3695): [398] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1507): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1507): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1507): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1507): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1507): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3695): [398] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3695): [398] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3695): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3695): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3695): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3695): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3695): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3695): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3695): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3695): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3695): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3695): 	at com.a.a.k.run(SourceFile:110)
,V/KeepSync( 3540): Connecting to GoogleApiClient
,I/GLSUser ( 1507): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1507): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1507): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1507): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1507): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1773): Handling authorization failure
E/ClientConnectionOperation( 1773): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1773): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1773): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1773): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1773): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1773): 	... 7 more
,V/KeepSync( 3540): GoogleApiClient failed to connect with error code: 4
E/SQLiteLog( 3540): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3540): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3540): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1507): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1507): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1507): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1507): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1507): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3540): IOException
E/KeepSync( 3540): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3540): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3540): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3540): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3540): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3540): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3540): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3540): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3540): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3540): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3540): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3540): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3540): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3540): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3540): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3540): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3540): 	... 10 more
W/KeepSync( 3540): Sync result 2
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 442254, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/BooksSync( 3572): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3572): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1507): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1507): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1507): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1507): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1507): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1507): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1507): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1507): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1507): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1507): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3572): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3572): Soft error
,E/BooksSync( 3572): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3572): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3572): Sync error
E/BooksSync( 3572): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3572): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3572): Finished books sync
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 470226, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2357): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2357): Disconnected process message: 10, size: 0
,I/art     (  823): Explicit concurrent mark sweep GC freed 37470(1699KB) AllocSpace objects, 14(506KB) LOS objects, 31% free, 34MB/50MB, paused 1.482ms total 79.258ms
,I/art     ( 1507): Explicit concurrent mark sweep GC freed 51409(2MB) AllocSpace objects, 17(1874KB) LOS objects, 36% free, 27MB/43MB, paused 1.130ms total 37.084ms
,I/GLSUser ( 1507): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1507): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1507): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1507): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1507): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3340): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3340): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3340): 	at jdm.a(PG:82)
E/HttpOperation( 3340): 	at jcs.o(PG:406)
E/HttpOperation( 3340): 	at jcn.a(PG:1379)
E/HttpOperation( 3340): 	at jcs.i(PG:143)
E/HttpOperation( 3340): 	at blb.a(PG:3937)
E/HttpOperation( 3340): 	at czp.a(PG:18188)
E/HttpOperation( 3340): 	at czp.a(PG:9087)
E/HttpOperation( 3340): 	at czq.run(PG:1686)
E/HttpOperation( 3340): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3340): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3340): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3340): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3340): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3340): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3340): 	at jdj.a(PG:4091)
E/HttpOperation( 3340): 	at jdj.a(PG:1125)
E/HttpOperation( 3340): 	at jdm.a(PG:77)
E/HttpOperation( 3340): 	... 12 more
E/HttpOperation( 3340): Caused by: faj: BadAuthentication
E/HttpOperation( 3340): 	at fal.a(PG:38)
E/HttpOperation( 3340): 	at jdj.a(PG:4089)
E/HttpOperation( 3340): 	... 14 more
,I/GLSUser ( 1507): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1507): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1507): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1507): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1507): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3340): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3340): java.io.IOException: Cannot obtain authentication token,
E/HttpOperation( 3340): 	at jdm.a(PG:82)
E/HttpOperation( 3340): 	at jcs.o(PG:406)
,E/HttpOperation( 3340): 	at jcn.a(PG:1379),
E/HttpOperation( 3340): 	at jcs.i(PG:143)
E/HttpOperation( 3340): ,	at blb.a(PG:3937)
E/HttpOperation( 3340): 	at czp.a(PG:18188)
E/HttpOperation( 3340): 	at czp.a(PG:9081)
,E/HttpOperation( 3340): 	at czq.run(PG:1686)
E/HttpOperation( 3340): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3340): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237),
E/HttpOperation( 3340): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3340): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3340): ,	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3340): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3340): 	at jdj.a(PG:4091)
E/HttpOperation( 3340): 	at jdj.a(PG:1125),
E/HttpOperation( 3340): 	at jdm.a(PG:77)
E/HttpOperation( 3340): 	... 12 more
E/HttpOperation( 3340): Caused by: faj: BadAuthentication
,E/HttpOperation( 3340): 	at fal.a(PG:38)
E/HttpOperation( 3340): 	at jdj.a(PG:4089)
E/HttpOperation( 3340): 	... 14 more
,I/GLSUser ( 1507): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1507): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1507): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1507): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1507): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3340): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3340): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3340): 	at jdm.a(PG:82)
E/HttpOperation( 3340): 	at jcs.o(PG:406)
E/HttpOperation( 3340): 	at jcn.a(PG:1379)
E/HttpOperation( 3340): 	at jcs.i(PG:143)
E/HttpOperation( 3340): 	at hec.a(PG:42)
E/HttpOperation( 3340): 	at hee.a(PG:102)
E/HttpOperation( 3340): 	at czr.a(PG:65)
E/HttpOperation( 3340): 	at kka.a(PG:108)
E/HttpOperation( 3340): 	at czp.a(PG:19176)
E/HttpOperation( 3340): 	at czp.a(PG:9081)
E/HttpOperation( 3340): 	at czq.run(PG:1686)
E/HttpOperation( 3340): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3340): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3340): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3340): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3340): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3340): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3340): 	at jdj.a(PG:4091)
E/HttpOperation( 3340): 	at jdj.a(PG:1125)
E/HttpOperation( 3340): 	at jdm.a(PG:77)
E/HttpOperation( 3340): 	... 15 more
E/HttpOperation( 3340): Caused by: faj: BadAuthentication
E/HttpOperation( 3340): 	at fal.a(PG:38)
E/HttpOperation( 3340): 	at jdj.a(PG:4089)
E/HttpOperation( 3340): 	... 17 more
,E/ExperimentLoader( 3340): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3340): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3340): 	at jdm.a(PG:82)
E/ExperimentLoader( 3340): ,	at jcs.o(PG:406)
E/ExperimentLoader( 3340): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3340): 	at jcs.i(PG:143),
E/ExperimentLoader( 3340): 	at hec.a(PG:42)
E/ExperimentLoader( 3340): 	at hee.a(PG:102)
E/ExperimentLoader( 3340): 	at czr.a(PG:65),
E/ExperimentLoader( 3340): 	at kka.a(PG:108)
E/ExperimentLoader( 3340): 	at czp.a(PG:19176)
E/ExperimentLoader( 3340): 	at czp.a(PG:9081)
E/ExperimentLoader( 3340): ,	at czq.run(PG:1686)
E/ExperimentLoader( 3340): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3340): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237),
E/ExperimentLoader( 3340): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3340): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3340): 	at java.lang.Thread.run(Thread.java:818)
,E/ExperimentLoader( 3340): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3340): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3340): 	at jdj.a(PG:1125)
,E/ExperimentLoader( 3340): 	at jdm.a(PG:77)
E/ExperimentLoader( 3340): 	... 15 more
E/ExperimentLoader( 3340): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3340): 	,at fal.a(PG:38)
E/ExperimentLoader( 3340): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3340): 	... 17 more
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 347002, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2357): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2357): Disconnected process message: 10, size: 0
,I/GLSUser ( 1507): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1507): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1507): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1507): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1507): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3340): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3340): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3340): 	at jdm.a(PG:82)
E/HttpOperation( 3340): 	at jcs.o(PG:406)
E/HttpOperation( 3340): 	at jcn.a(PG:1379)
E/HttpOperation( 3340): 	at jcs.i(PG:143)
E/HttpOperation( 3340): 	at blb.a(PG:3937)
E/HttpOperation( 3340): 	at czp.a(PG:18188)
E/HttpOperation( 3340): 	at czp.a(PG:9081)
E/HttpOperation( 3340): 	at czq.run(PG:1686)
E/HttpOperation( 3340): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3340): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3340): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3340): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3340): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3340): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3340): 	at jdj.a(PG:4091)
E/HttpOperation( 3340): 	at jdj.a(PG:1125)
E/HttpOperation( 3340): 	at jdm.a(PG:77)
E/HttpOperation( 3340): 	... 12 more
E/HttpOperation( 3340): Caused by: faj: BadAuthentication
E/HttpOperation( 3340): 	at fal.a(PG:38)
E/HttpOperation( 3340): 	at jdj.a(PG:4089)
E/HttpOperation( 3340): 	... 14 more
,I/GLSUser ( 1507): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1507): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1507): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1507): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1507): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3340): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3340): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3340): 	at jdm.a(PG:82)
E/HttpOperation( 3340): 	at jcs.o(PG:406)
E/HttpOperation( 3340): 	at jcn.a(PG:1379)
E/HttpOperation( 3340): 	at jcs.i(PG:143)
E/HttpOperation( 3340): 	at hec.a(PG:42)
E/HttpOperation( 3340): 	at hee.a(PG:102)
E/HttpOperation( 3340): 	at czr.a(PG:65)
E/HttpOperation( 3340): 	at kka.a(PG:108)
E/HttpOperation( 3340): 	at czp.a(PG:19176)
E/HttpOperation( 3340): 	at czp.a(PG:9081)
E/HttpOperation( 3340): 	at czq.run(PG:1686)
E/HttpOperation( 3340): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3340): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3340): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3340): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3340): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3340): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3340): 	at jdj.a(PG:4091)
E/HttpOperation( 3340): 	at jdj.a(PG:1125)
E/HttpOperation( 3340): 	at jdm.a(PG:77)
E/HttpOperation( 3340): 	... 15 more
E/HttpOperation( 3340): Caused by: faj: BadAuthentication
E/HttpOperation( 3340): 	at fal.a(PG:38)
E/HttpOperation( 3340): 	at jdj.a(PG:4089)
E/HttpOperation( 3340): 	... 17 more
E/ExperimentLoader( 3340): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3340): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3340): 	at jdm.a(PG:82)
E/ExperimentLoader( 3340): 	at jcs.o(PG:406)
E/ExperimentLoader( 3340): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3340): 	at jcs.i(PG:143)
E/ExperimentLoader( 3340): 	at hec.a(PG:42)
E/ExperimentLoader( 3340): 	at hee.a(PG:102)
E/ExperimentLoader( 3340): 	at czr.a(PG:65)
E/ExperimentLoader( 3340): 	at kka.a(PG:108)
E/ExperimentLoader( 3340): 	at czp.a(PG:19176)
E/ExperimentLoader( 3340): 	at czp.a(PG:9081)
E/ExperimentLoader( 3340): 	at czq.run(PG:1686)
E/ExperimentLoader( 3340): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3340): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3340): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3340): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3340): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3340): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3340): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3340): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3340): 	at jdm.a(PG:77)
E/ExperimentLoader( 3340): 	... 15 more
E/ExperimentLoader( 3340): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3340): 	at fal.a(PG:38)
E/ExperimentLoader( 3340): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3340): 	... 17 more
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 534576, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2357): Disconnected process message: 10, size: 0
,I/GLSUser ( 1507): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1507): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1507): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1507): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1507): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3340): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3340): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3340): 	at jdm.a(PG:82)
E/HttpOperation( 3340): 	at jcs.o(PG:406)
E/HttpOperation( 3340): 	at jcn.a(PG:1379)
E/HttpOperation( 3340): 	at jcs.i(PG:143)
E/HttpOperation( 3340): 	at blb.a(PG:3937)
E/HttpOperation( 3340): 	at czp.a(PG:18188)
E/HttpOperation( 3340): 	at czp.a(PG:9081)
E/HttpOperation( 3340): 	at czq.run(PG:1686)
E/HttpOperation( 3340): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3340): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3340): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3340): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3340): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3340): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3340): 	at jdj.a(PG:4091)
E/HttpOperation( 3340): 	at jdj.a(PG:1125)
E/HttpOperation( 3340): 	at jdm.a(PG:77)
E/HttpOperation( 3340): 	... 12 more
E/HttpOperation( 3340): Caused by: faj: BadAuthentication
E/HttpOperation( 3340): 	at fal.a(PG:38)
E/HttpOperation( 3340): 	at jdj.a(PG:4089)
E/HttpOperation( 3340): 	... 14 more
,I/GLSUser ( 1507): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1507): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1507): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1507): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1507): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3340): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3340): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3340): 	at jdm.a(PG:82)
E/HttpOperation( 3340): 	at jcs.o(PG:406)
E/HttpOperation( 3340): 	at jcn.a(PG:1379)
E/HttpOperation( 3340): 	at jcs.i(PG:143)
E/HttpOperation( 3340): 	at hec.a(PG:42)
E/HttpOperation( 3340): 	at hee.a(PG:102)
E/HttpOperation( 3340): 	at czr.a(PG:65)
E/HttpOperation( 3340): 	at kka.a(PG:108)
E/HttpOperation( 3340): 	at czp.a(PG:19176)
E/HttpOperation( 3340): 	at czp.a(PG:9081)
E/HttpOperation( 3340): 	at czq.run(PG:1686)
E/HttpOperation( 3340): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3340): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3340): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3340): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3340): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3340): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3340): 	at jdj.a(PG:4091)
E/HttpOperation( 3340): 	at jdj.a(PG:1125)
E/HttpOperation( 3340): 	at jdm.a(PG:77)
E/HttpOperation( 3340): 	... 15 more
E/HttpOperation( 3340): Caused by: faj: BadAuthentication
E/HttpOperation( 3340): 	at fal.a(PG:38)
E/HttpOperation( 3340): 	at jdj.a(PG:4089)
E/HttpOperation( 3340): 	... 17 more
,E/ExperimentLoader( 3340): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3340): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3340): 	at jdm.a(PG:82)
E/ExperimentLoader( 3340): 	at jcs.o(PG:406)
E/ExperimentLoader( 3340): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3340): 	at jcs.i(PG:143)
E/ExperimentLoader( 3340): 	at hec.a(PG:42)
E/ExperimentLoader( 3340): 	at hee.a(PG:102)
E/ExperimentLoader( 3340): 	at czr.a(PG:65)
E/ExperimentLoader( 3340): 	at kka.a(PG:108)
E/ExperimentLoader( 3340): 	at czp.a(PG:19176)
E/ExperimentLoader( 3340): 	at czp.a(PG:9081)
E/ExperimentLoader( 3340): 	at czq.run(PG:1686)
E/ExperimentLoader( 3340): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3340): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3340): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3340): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3340): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3340): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3340): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3340): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3340): 	at jdm.a(PG:77)
E/ExperimentLoader( 3340): 	... 15 more
E/ExperimentLoader( 3340): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3340): 	at fal.a(PG:38)
E/ExperimentLoader( 3340): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3340): 	... 17 more
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 626155, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2357): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2357): Disconnected process message: 10, size: 0
,V/GoogleAuthProtoRequest( 3695): [399] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1507): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1507): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1507): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1507): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1507): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3695): [399] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3695): [399] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3695): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3695): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3695): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3695): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3695): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3695): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3695): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3695): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3695): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3695): 	at com.a.a.k.run(SourceFile:110)
,V/KeepSync( 3540): Connecting to GoogleApiClient
,I/GLSUser ( 1507): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1507): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1507): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1507): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1507): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/ClientConnectionOperation( 1773): Handling authorization failure,
E/ClientConnectionOperation( 1773): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1773): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1773): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1773): 	,at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1773): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1773): 	,at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1773): 	... 7 more
,V/KeepSync( 3540): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3540): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3540): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3540): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1507): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1507): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1507): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1507): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,V/GLSActivity( 1507): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/KeepSync( 3540): IOException
E/KeepSync( 3540): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3540): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3540): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3540): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3540): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3540): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3540): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3540): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3540): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3540): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3540): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3540): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3540): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3540): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3540): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3540): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3540): 	... 10 more
W/KeepSync( 3540): Sync result 2
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 693708, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/BooksSync( 3572): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3572): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1507): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1507): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1507): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1507): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1507): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1507): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1507): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1507): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1507): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1507): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  823): Explicit concurrent mark sweep GC freed 38642(1682KB) AllocSpace objects, 9(521KB) LOS objects, 31% free, 34MB/50MB, paused 1.820ms total 87.948ms
,E/BooksAccountManager( 3572): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3572): Soft error
E/BooksSync( 3572): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3572): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3572): Sync error
E/BooksSync( 3572): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3572): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3572): Finished books sync
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 719242, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2357): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2357): Disconnected process message: 10, size: 0
,I/art     ( 1507): Explicit concurrent mark sweep GC freed 49134(2MB) AllocSpace objects, 13(1434KB) LOS objects, 37% free, 26MB/42MB, paused 1.351ms total 46.257ms
,I/GLSUser ( 1507): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1507): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1507): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1507): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1507): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3340): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3340): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3340): 	at jdm.a(PG:82)
E/HttpOperation( 3340): 	at jcs.o(PG:406)
E/HttpOperation( 3340): 	at jcn.a(PG:1379)
E/HttpOperation( 3340): 	at jcs.i(PG:143)
E/HttpOperation( 3340): 	at blb.a(PG:3937)
E/HttpOperation( 3340): 	at czp.a(PG:18188)
E/HttpOperation( 3340): 	at czp.a(PG:9081)
E/HttpOperation( 3340): 	at czq.run(PG:1686)
E/HttpOperation( 3340): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3340): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3340): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3340): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3340): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3340): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3340): 	at jdj.a(PG:4091)
E/HttpOperation( 3340): 	at jdj.a(PG:1125)
E/HttpOperation( 3340): 	at jdm.a(PG:77)
E/HttpOperation( 3340): 	... 12 more
E/HttpOperation( 3340): Caused by: faj: BadAuthentication
E/HttpOperation( 3340): 	at fal.a(PG:38)
E/HttpOperation( 3340): 	at jdj.a(PG:4089)
E/HttpOperation( 3340): 	... 14 more
,I/GLSUser ( 1507): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1507): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1507): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1507): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1507): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3340): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3340): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3340): 	at jdm.a(PG:82)
E/HttpOperation( 3340): 	at jcs.o(PG:406)
E/HttpOperation( 3340): 	,at jcn.a(PG:1379)
E/HttpOperation( 3340): 	at jcs.i(PG:143)
E/HttpOperation( 3340): 	at hec.a(PG:42)
E/HttpOperation( 3340): 	at hee.a(PG:102)
E/HttpOperation( 3340): 	at czr.a(PG:65)
E/HttpOperation( 3340): 	at kka.a(PG:108)
E/HttpOperation( 3340): 	at czp.a(PG:19176)
E/HttpOperation( 3340): 	at czp.a(PG:9081)
E/HttpOperation( 3340): 	at czq.run(PG:1686)
E/HttpOperation( 3340): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3340): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3340): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
,E/HttpOperation( 3340): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3340): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3340): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3340): 	at jdj.a(PG:4091)
E/HttpOperation( 3340): 	at jdj.a(PG:1125)
E/HttpOperation( 3340): 	at jdm.a(PG:77)
E/HttpOperation( 3340): 	... 15 more
E/HttpOperation( 3340): Caused by: faj: BadAuthentication
E/HttpOperation( 3340): 	at fal.a(PG:38)
E/HttpOperation( 3340): 	at jdj.a(PG:4089)
E/HttpOperation( 3340): 	... 17 more
E/ExperimentLoader( 3340): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3340): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3340): 	at jdm.a(PG:82)
E/ExperimentLoader( 3340): ,	at jcs.o(PG:406)
E/ExperimentLoader( 3340): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3340): 	at jcs.i(PG:143)
E/ExperimentLoader( 3340): 	at hec.a(PG:42)
E/ExperimentLoader( 3340): 	at hee.a(PG:102)
E/ExperimentLoader( 3340): 	at czr.a(PG:65)
E/ExperimentLoader( 3340): 	at kka.a(PG:108)
E/ExperimentLoader( 3340): 	at czp.a(PG:19176)
E/ExperimentLoader( 3340): 	at czp.a(PG:9081)
E/ExperimentLoader( 3340): 	at czq.run(PG:1686)
E/ExperimentLoader( 3340): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3340): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
,E/ExperimentLoader( 3340): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3340): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3340): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3340): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3340): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3340): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3340): 	at jdm.a(PG:77)
E/ExperimentLoader( 3340): 	... 15 more
E/ExperimentLoader( 3340): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3340): 	at fal.a(PG:38)
E/ExperimentLoader( 3340): 	at jdj.a(PG:4089)
,E/ExperimentLoader( 3340): 	... 17 more
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 752787, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager(  823): Start proc 4094:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider
,I/GAv4    ( 4094): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4094):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4094):   adb logcat -s GAv4
,W/GAv4    ( 4094): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4094): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4094): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  823): Killing 3289:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,D/HeadsetStateMachine( 2357): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2357): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2357): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2357): Disconnected process message: 10, size: 0
,V/GLSActivity( 1507): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1507): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/ads_measurement
I/GLSUser ( 1507): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/ads_measurement without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1507): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1507): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1507): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Ads     ( 1773): [JAMS] Failed to get OAuth token: com.google.android.gms.auth.ad: BadAuthentication
,I/ActivityManager(  823): Start proc 4137:com.google.android.youtube/u0a86 for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator
,W/ResourcesManager( 4137): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 4137): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 4137): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ProviderInstaller( 4137): Installed default security provider GmsCore_OpenSSL
,I/dex2oat ( 4166): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads1728637268.jar --oat-fd=24 --oat-location=/data/data/com.google.android.youtube/cache/ads1728637268.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,E/YouTube MDX( 4137): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,I/dex2oat ( 4166): dex2oat took 34.163ms (threads: 4) arena alloc=171KB java alloc=12KB native alloc=1091KB free=6MB
,W/InstanceID/Rpc( 4137): Found 10011
,I/ActivityManager(  823): Killing 3494:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,D/HeadsetStateMachine( 2357): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2357): Disconnected process message: 10, size: 0
,W/bt-btm  ( 2357): Stopping oneshot timer
,D/HeadsetStateMachine( 2357): Disconnected process message: 10, size: 0
,I/GLSUser ( 1507): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1507): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1507): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1507): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1507): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3340): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3340): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3340): 	at jdm.a(PG:82)
E/HttpOperation( 3340): 	at jcs.o(PG:406)
E/HttpOperation( 3340): 	at jcn.a(PG:1379)
E/HttpOperation( 3340): 	at jcs.i(PG:143)
E/HttpOperation( 3340): 	at blb.a(PG:3937)
E/HttpOperation( 3340): 	at czp.a(PG:18188)
E/HttpOperation( 3340): 	at czp.a(PG:9081)
E/HttpOperation( 3340): 	at czq.run(PG:1686)
E/HttpOperation( 3340): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3340): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3340): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3340): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3340): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3340): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3340): 	at jdj.a(PG:4091)
E/HttpOperation( 3340): 	at jdj.a(PG:1125)
E/HttpOperation( 3340): 	at jdm.a(PG:77)
E/HttpOperation( 3340): 	... 12 more
E/HttpOperation( 3340): Caused by: faj: BadAuthentication
E/HttpOperation( 3340): 	at fal.a(PG:38)
E/HttpOperation( 3340): 	at jdj.a(PG:4089)
,E/HttpOperation( 3340): 	... 14 more,
,I/GLSUser ( 1507): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1507): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1507): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1507): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1507): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3340): [getmobileexperiments] Unexpected exception,
E/HttpOperation( 3340): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3340): 	at jdm.a(PG:82)
E/HttpOperation( 3340): 	at jcs.o(PG:406)
E/HttpOperation( 3340): 	at jcn.a(PG:1379)
E/HttpOperation( 3340): 	at jcs.i(PG:143)
E/HttpOperation( 3340): 	,at hec.a(PG:42)
E/HttpOperation( 3340): 	at hee.a(PG:102)
E/HttpOperation( 3340): 	at czr.a(PG:65)
E/HttpOperation( 3340): 	at kka.a(PG:108)
E/HttpOperation( 3340): ,	at czp.a(PG:19176)
E/HttpOperation( 3340): 	at czp.a(PG:9081)
E/HttpOperation( 3340): 	at czq.run(PG:1686)
E/HttpOperation( 3340): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422),
E/HttpOperation( 3340): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3340): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
,E/HttpOperation( 3340): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3340): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3340): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3340): 	at jdj.a(PG:4091)
E/HttpOperation( 3340): 	at jdj.a(PG:1125)
,E/HttpOperation( 3340): 	at jdm.a(PG:77)
E/HttpOperation( 3340): 	... 15 more
E/HttpOperation( 3340): Caused by: faj: BadAuthentication
E/HttpOperation( 3340): 	at fal.a(PG:38)
E/HttpOperation( 3340): 	,at jdj.a(PG:4089)
E/HttpOperation( 3340): 	... 17 more
E/ExperimentLoader( 3340): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3340): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3340): 	at jdm.a(PG:82)
E/ExperimentLoader( 3340): ,	at jcs.o(PG:406)
E/ExperimentLoader( 3340): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3340): 	at jcs.i(PG:143)
E/ExperimentLoader( 3340): 	at hec.a(PG:42)
E/ExperimentLoader( 3340): 	at hee.a(PG:102),
E/ExperimentLoader( 3340): 	at czr.a(PG:65)
E/ExperimentLoader( 3340): 	at kka.a(PG:108)
E/ExperimentLoader( 3340): 	at czp.a(PG:19176)
E/ExperimentLoader( 3340): 	at czp.a(PG:9081)
,E/ExperimentLoader( 3340): 	at czq.run(PG:1686)
E/ExperimentLoader( 3340): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3340): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3340): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
,E/ExperimentLoader( 3340): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3340): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3340): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3340): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3340): 	,at jdj.a(PG:1125)
E/ExperimentLoader( 3340): 	at jdm.a(PG:77)
E/ExperimentLoader( 3340): 	... 15 more
E/ExperimentLoader( 3340): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3340): 	at fal.a(PG:38)
E/ExperimentLoader( 3340): 	,at jdj.a(PG:4089)
E/ExperimentLoader( 3340): 	... 17 more
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 1006717, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2357): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2357): Disconnected process message: 10, size: 0
,D/GCM     ( 1507): Message class com.google.f.a.a.i
,D/HeadsetStateMachine( 2357): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2357): Disconnected process message: 10, size: 0
,V/GoogleAuthProtoRequest( 3695): [400] a.<init>: mAccountName set to: thalitester@gmail.com
,I/EventLogService( 1773): Opted in for usage reporting
,I/EventLogService( 1773): Aggregate from 1450228920942 (log), 1450228920942 (data)
,I/GLSUser ( 1507): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1507): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1507): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1507): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1507): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3695): [400] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3695): [400] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3695): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3695): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3695): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3695): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3695): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3695): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3695): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3695): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3695): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3695): 	at com.a.a.k.run(SourceFile:110)
W/EventLogAggregator( 1773): Unknown tag: snet_gcore
W/EventLogAggregator( 1773): Unknown tag: snet_launch_service
,I/ServiceDumpSys( 1773): dumping service [account]
,I/art     (  823): Explicit concurrent mark sweep GC freed 40471(1939KB) AllocSpace objects, 7(300KB) LOS objects, 32% free, 33MB/49MB, paused 1.696ms total 77.677ms
,V/KeepSync( 3540): Connecting to GoogleApiClient
,I/GLSUser ( 1507): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1507): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1507): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1507): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1507): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1773): Handling authorization failure
E/ClientConnectionOperation( 1773): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1773): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1773): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1773): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1773): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1773): 	... 7 more
,V/KeepSync( 3540): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3540): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3540): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3540): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1507): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1507): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1507): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1507): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1507): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/KeepSync( 3540): IOException
E/KeepSync( 3540): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3540): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3540): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3540): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3540): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3540): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3540): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3540): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3540): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3540): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3540): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3540): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3540): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3540): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3540): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3540): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3540): 	... 10 more
W/KeepSync( 3540): Sync result 2
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 1196060, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/BooksSync( 3572): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3572): GmsCore Version = 7.8.99 (2134222-430)
,I/art     ( 1507): Explicit concurrent mark sweep GC freed 57228(2MB) AllocSpace objects, 6(661KB) LOS objects, 37% free, 26MB/42MB, paused 1.730ms total 34.292ms
,I/GLSUser ( 1507): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1507): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1507): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1507): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1507): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1507): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1507): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1507): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1507): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1507): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3572): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3572): Soft error
E/BooksSync( 3572): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3572): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3572): Sync error
E/BooksSync( 3572): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3572): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3572): Finished books sync
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1217437, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/UsageStatsService(  823): User[0] Flushing usage stats to disk
,D/HeadsetStateMachine( 2357): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2357): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2357): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2357): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2357): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2357): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2357): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2357): Disconnected process message: 10, size: 0
,I/GLSUser ( 1507): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1507): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1507): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1507): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,V/GLSActivity( 1507): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3340): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3340): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3340): 	at jdm.a(PG:82)
E/HttpOperation( 3340): 	at jcs.o(PG:406)
E/HttpOperation( 3340): 	at jcn.a(PG:1379)
E/HttpOperation( 3340): 	at jcs.i(PG:143)
E/HttpOperation( 3340): 	at blb.a(PG:3937)
E/HttpOperation( 3340): 	at czp.a(PG:18188)
E/HttpOperation( 3340): 	at czp.a(PG:9081)
E/HttpOperation( 3340): 	at czq.run(PG:1686)
E/HttpOperation( 3340): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3340): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3340): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3340): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3340): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3340): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3340): 	at jdj.a(PG:4091)
E/HttpOperation( 3340): 	at jdj.a(PG:1125)
E/HttpOperation( 3340): 	at jdm.a(PG:77)
E/HttpOperation( 3340): 	... 12 more
E/HttpOperation( 3340): Caused by: faj: BadAuthentication
E/HttpOperation( 3340): 	at fal.a(PG:38)
E/HttpOperation( 3340): 	at jdj.a(PG:4089)
E/HttpOperation( 3340): 	... 14 more
,I/GLSUser ( 1507): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1507): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1507): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1507): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1507): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3340): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3340): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3340): 	at jdm.a(PG:82)
E/HttpOperation( 3340): 	at jcs.o(PG:406)
E/HttpOperation( 3340): 	at jcn.a(PG:1379)
E/HttpOperation( 3340): 	at jcs.i(PG:143)
E/HttpOperation( 3340): 	at hec.a(PG:42)
E/HttpOperation( 3340): 	at hee.a(PG:102)
E/HttpOperation( 3340): 	at czr.a(PG:65)
E/HttpOperation( 3340): 	at kka.a(PG:108)
E/HttpOperation( 3340): 	at czp.a(PG:19176)
E/HttpOperation( 3340): 	at czp.a(PG:9081)
E/HttpOperation( 3340): 	at czq.run(PG:1686)
E/HttpOperation( 3340): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3340): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3340): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3340): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3340): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3340): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3340): 	at jdj.a(PG:4091)
E/HttpOperation( 3340): 	at jdj.a(PG:1125)
E/HttpOperation( 3340): 	at jdm.a(PG:77)
E/HttpOperation( 3340): 	... 15 more
E/HttpOperation( 3340): Caused by: faj: BadAuthentication
E/HttpOperation( 3340): 	at fal.a(PG:38)
E/HttpOperation( 3340): 	at jdj.a(PG:4089)
E/HttpOperation( 3340): 	... 17 more
E/ExperimentLoader( 3340): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3340): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3340): 	at jdm.a(PG:82)
E/ExperimentLoader( 3340): 	at jcs.o(PG:406)
E/ExperimentLoader( 3340): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3340): 	at jcs.i(PG:143)
E/ExperimentLoader( 3340): 	at hec.a(PG:42)
E/ExperimentLoader( 3340): 	at hee.a(PG:102)
E/ExperimentLoader( 3340): 	at czr.a(PG:65)
E/ExperimentLoader( 3340): 	at kka.a(PG:108)
E/ExperimentLoader( 3340): 	at czp.a(PG:19176)
E/ExperimentLoader( 3340): 	at czp.a(PG:9081)
E/ExperimentLoader( 3340): 	at czq.run(PG:1686)
E/ExperimentLoader( 3340): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3340): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3340): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3340): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3340): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3340): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3340): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3340): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3340): 	at jdm.a(PG:77)
E/ExperimentLoader( 3340): 	... 15 more
E/ExperimentLoader( 3340): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3340): 	at fal.a(PG:38)
E/ExperimentLoader( 3340): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3340): 	... 17 more
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 1512065, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2357): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2357): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2357): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2357): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2357): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2357): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2357): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2357): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2357): Disconnected process message: 10, size: 0
,I/ProcessStatsService(  823): Prepared write state in 19ms
,I/ProcessStatsService(  823): Prepared write state in 6ms
,I/GLSUser ( 1507): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2: email
,I/GLSUser ( 1507): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2: email without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1507): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1507): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/ProcessStatsService(  823): Pruning old procstats: /data/system/procstats/state-2015-12-15-15-43-36.bin
,V/GLSActivity( 1507): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/bt-btm  ( 2357): Stopping oneshot timer
,D/HeadsetStateMachine( 2357): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2357): Disconnected process message: 10, size: 0
,I/ActivityManager(  823): Killing 3394:com.android.defcontainer/u0a7 (adj 15): empty for 1820s
,E/libprocessgroup(  823): failed to kill 1 processes for processgroup 3394
,D/HeadsetStateMachine( 2357): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2357): Disconnected process message: 10, size: 0
,TIME-OUT KILL (timeout was 1800000ms)
```
