#### Test 5667282762e056f_thali05_motorola-Nexus 6 Logs


```
--------- beginning of main
I/GAV2    ( 3758): Thread[GAThread,5,main]: No campaign data found.
,D/AndroidRuntime( 3812): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 3812): CheckJNI is OFF
D/AndroidRuntime( 3812): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  822): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/WindowManager(  822): addAppToken: AppWindowToken{392de371 token=Token{16041d18 ActivityRecord{92428fb u0 com.test.thalitest/.MainActivity t28}}} to stack=1 task=28 at 0
V/WindowManager(  822): Adding window Window{1aa290e2 u0 Starting com.test.thalitest} at 2 of 7 (after Window{13029841 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
I/HotwordDetector( 1518): Closing mic
I/MicrophoneInputStream( 1518): mic_close com.google.android.apps.gsa.speech.audio.u@191c97ec
D/AndroidRuntime( 3812): Shutting down VM
I/ActivityManager(  822): Start proc 3826:com.test.thalitest/u0a265 for activity com.test.thalitest/.MainActivity
D/audio_hw_primary(  357): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  357): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  357): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1518): Stopping hotword detection.
I/HotwordRecognitionRnr( 1518): Hotword detection finished
I/ActivityManager(  822): Killing 3538:com.google.android.partnersetup/u0a16 (adj 15): empty #17
I/WebViewFactory( 3826): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/ActivityManager(  822): Killing 3285:com.google.android.apps.photos/u0a71 (adj 15): empty #18
,I/LibraryLoader( 3826): Time to load native libraries: 5 ms (timestamps 273-278)
,I/LibraryLoader( 3826): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3826): Binding Chromium to main looper Looper (main, tid 1) {3372c0d}
,I/LibraryLoader( 3826): Expected native library version number "",actual native library version number ""
I/chromium( 3826): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3826): Initializing chromium process, singleProcess=true
,W/art     ( 3826): Attempt to remove local handle scope entry from IRT, ignoring,
E/SysUtils( 3826): ApplicationContext is null in ApplicationStatus
,E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1660863763,
E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,W/chromium( 3826): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3826): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3826): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3826): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,I/kickstart(  871): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
,I/kickstart(  871): STATUS: Wrote to /sys/power/wake_lock
,E/kickstart(  871): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1
,I/kickstart(  871): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1' for writing
,D/BluetoothManagerService(  822): Message: 20
D/BluetoothManagerService(  822): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3a54f692:true
,W/art     ( 3826): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3826): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3826): CordovaWebView is running on device made by: motorola
,W/art     ( 3826): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 3826): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3826): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,D/Atlas   ( 3826): Validating map...
,V/WindowManager(  822): Adding window Window{2042842 u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{1aa290e2 u0 Starting com.test.thalitest})
,W/chromium( 3826): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3826): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3826): Enabling debug mode 0
,I/ActivityManager(  822): Displayed com.test.thalitest/.MainActivity: +1s23ms
,I/Keyboard.Facilitator( 1236): onFinishInput()
,W/BindingManager( 3826): Cannot call determinedVisibility() - never saw a connection for the pid: 3826
,D/JsMessageQueue( 3826): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3826): JniHelper::setJavaVM(0xb489d200), pthread_self() = -1580388096
,I/kickstart(  871): STATUS: Received file 'm9kefs1'
I/kickstart(  871): STATUS: 950272 bytes transferred in 0.990139 seconds
I/kickstart(  871): STATUS: Successfully downloaded files from target 
I/kickstart(  871): STATUS: Wrote to /sys/power/wake_unlock
,I/kickstart(  871): STATUS: Sahara protocol completed
,I/chromium( 3826): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 3826): Initializing JXcore engine
W/jxcore-log( 3826): JXcore engine is ready
,W/Thread-432( 3882): type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[10591]" dev="sockfs" ino=10591 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/Thread-432( 3882): type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,W/Thread-432( 3882): type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[13035]" dev="sockfs" ino=13035 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-432( 3882): type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[23747]" dev="sockfs" ino=23747 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 3826): Starting JXcore engine
,W/jxcore-log( 3826): Platform android
,W/jxcore-log( 3826): 
W/jxcore-log( 3826): Process ARCH arm
W/jxcore-log( 3826): 
,I/jxcore-log( 3826): JXcore Cordova bridge is ready!
I/jxcore-log( 3826): 
,W/jxcore-log( 3826): JXcore engine is started
,I/jxcore-log( 3826): Toggling radios to true
I/jxcore-log( 3826): 
,D/BluetoothAdapter( 3826): enable(): BT is already enabled..!
,D/WifiService(  822): New client listening to asynchronous messages
,D/WifiService(  822): setWifiEnabled: true pid=3826, uid=10265
E/WifiService(  822): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3826): Radios toggled
I/jxcore-log( 3826): 
,I/jxcore-log( 3826): My device name is: motorola-Nexus 6
I/jxcore-log( 3826): 
,I/wpa_supplicant( 1150): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  822): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  822): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  353): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1262): Read error: ssl=0x9cc46800: I/O error during system call, Connection timed out
,V/NativeCrypto( 1262): SSL shutdown failed: ssl=0x9cc46800: I/O error during system call, Broken pipe
,D/ConnectivityService(  822): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  822): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,D/ConnectivityService(  822): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10011
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): ValidatedState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): DefaultState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): Forcing reevaluation
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): EvaluatingState{ when=0 what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
,E/WifiStateMachine(  822): Start Disconnecting Watchdog 1
,E/WifiStateMachine(  822): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,D/CommandListener(  353): Clearing all IP addresses on wlan0
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
,D/ConnectivityService(  822): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/CSLegacyTypeTracker(  822): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 1069): CM callback handler got msg 524292
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): OfflineState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): Disconnected - quitting
,D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/WifiNetworkAgent(  822): NetworkAgent: NetworkAgent channel lost
D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  822): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/WifiStateMachine(  822): CMD_AUTO_CONNECT sup state CompletedState my state DisconnectedState nid=0 roam=3
E/WifiStateMachine(  822): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=0
,D/Tethering(  822): MasterInitialState.processMessage what=3
D/Tethering(  822): MasterInitialState.processMessage what=3
D/ConnectivityService(  822): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
,D/PhoneInterfaceManager( 1349): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
,E/PhoneInterfaceManager( 1349): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,V/MusicLeanback( 3066): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/TelephonyManager(  822): getDataEnabled: retVal=false
,E/WifiConfigStore(  822): Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiConfigStore(  822): will read network variables netId=0
,I/ActivityManager(  822): Start proc 3891:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.steen.receiver.ConnectivityChangeReceiver
,E/WifiStateMachine(  822): CMD_AUTO_CONNECT did save config ->  nid=0
,E/WifiConfigStore(  822): will read network variables netId=0
,E/GpsLocationProvider(  822): No APN found to select.
,D/PhoneInterfaceManager( 1349): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1349): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  822): getDataEnabled: retVal=false
,E/GpsLocationProvider(  822): No APN found to select.
,I/art     (  822): Explicit concurrent mark sweep GC freed 39425(1818KB) AllocSpace objects, 5(80KB) LOS objects, 32% free, 33MB/49MB, paused 1.396ms total 63.867ms
,I/ActivityManager(  822): Start proc 3918:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,I/ActivityManager(  822): Killing 3558:com.android.musicfx/u0a18 (adj 15): empty #17
,D/Finsky  ( 3623): [389] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,D/SprintDMReceiver( 3918): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3918): simOperator:  IMSI: null
D/SprintDMReceiver( 3918): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1781): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/SystemUpdateService( 1781): onCreate
,D/SystemUpdateService( 1781): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1781): active receiver: enabled
,I/SystemUpdateService( 1781): showing system update notification
,I/GLSUser ( 1262): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1262): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1262): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1262): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/iu.Environment( 1781): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1781): num queued entries: 0
,I/iu.UploadsManager( 1781): num updated entries: 0
I/iu.SyncManager( 1781): NEXT; no task
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ValidateNoPeople(  822): skipping global notification
,D/ChimeraCfgMgr( 1781): Loading module com.google.android.gms.kids from APK com.google.android.gms
,V/SystemUpdateService( 1781): retry (wakeup: false) in 3599974 ms
,D/SystemUpdateService( 1781): onDestroy
,I/Babel   ( 2804): connection state changed from CONNECTED to DISCONNECTED
,I/ActivityManager(  822): Start proc 3939:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,D/Finsky  ( 3623): [389] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,I/ActivityManager(  822): Killing 3587:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,I/GAv4    ( 3939): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3939):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3939):   adb logcat -s GAv4
,W/GAv4    ( 3939): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3939): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3939): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/art     ( 1262): Explicit concurrent mark sweep GC freed 21095(1243KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 1.149ms total 27.194ms
,I/WebViewFactory( 3939): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3939): Time to load native libraries: 1 ms (timestamps 4801-4802)
I/LibraryLoader( 3939): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3939): Binding Chromium to main looper Looper (main, tid 1) {d8607b8}
I/LibraryLoader( 3939): Expected native library version number "",actual native library version number ""
,I/chromium( 3939): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3939): Initializing chromium process, singleProcess=true
W/art     ( 3939): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3939): ApplicationContext is null in ApplicationStatus
,W/chromium( 3939): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3939): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3939): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3939): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,W/AudioManagerAndroid( 3939): Requires BLUETOOTH permission
,I/NSApplication( 3939): Starting up...
,I/ActivityManager(  822): Start proc 3997:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,I/ActivityManager(  822): Killing 3266:android.process.acore/u0a5 (adj 15): empty #17
,I/ActivityManager(  822): Start proc 4021:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
I/ActivityManager(  822): Killing 3437:com.google.android.gm/u0a78 (adj 15): empty #17
,I/wpa_supplicant( 1150): wlan0: Trying to associate with SSID 'NG7005g'
,I/ActivityManager(  822): Killing 3665:com.google.android.gms:car/u0a11 (adj 15): empty #17
,I/wpa_supplicant( 1150): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 1150): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
V/MusicLeanback( 3066): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/wpa_supplicant( 1150): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=0 id_str=]
,D/ConnectivityService(  822): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} }
,E/WifiConfigStore(  822): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  822): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  822): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  353): Setting iface cfg
,E/WifiStateMachine(  822): Start Dhcp Watchdog 2
,E/WifiStateMachine(  822):  WifiLinkLayerStats: 
E/WifiStateMachine(  822):  my bss beacon rx: 386
E/WifiStateMachine(  822):  RSSI mgmt: -49
E/WifiStateMachine(  822):  BE :  rx=183 tx=135 lost=0 retries=0
E/WifiStateMachine(  822):  BK :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  822):  VI :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  822):  VO :  rx=6 tx=0 lost=0 retries=0
E/WifiStateMachine(  822):  on_time : 12222 tx_time=220 rx_time=584 scan_time=0
,D/SprintDMReceiver( 3918): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3918): simOperator:  IMSI: null
D/SprintDMReceiver( 3918): Not Sprint UICC, don't do anything.
,D/ConnectivityService(  822): updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,I/SystemUpdateService( 1781): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1781): onCreate
,D/SystemUpdateService( 1781): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1781): active receiver: enabled
,I/SystemUpdateService( 1781): showing system update notification
,D/ChimeraCfgMgr( 1781): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/ValidateNoPeople(  822): skipping global notification
,V/SystemUpdateService( 1781): retry (wakeup: false) in 3599985 ms
,D/SystemUpdateService( 1781): onDestroy
,E/native  (  822): do suspend false
,E/WifiStateMachine(  822): scanCount==0 - aborting
,I/dhcpcd  ( 4046): version 5.5.6 starting
,I/dhcpcd  ( 4046): wlan0: rebinding lease of 192.168.1.122
,I/dhcpcd  ( 4046): wlan0: acknowledged 192.168.1.122 from 192.168.1.1
,I/jxcore-log( 3826): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js,
I/jxcore-log( 3826): 
,I/dhcpcd  ( 4046): wlan0: leased 192.168.1.122 for 86400 seconds
,D/ConnectivityService(  822): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  822): Adding iface wlan0 to network 101
,I/jxcore-log( 3826): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 3826): 
E/WifiStateMachine(  822): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  822): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  822): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  822): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  822): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  822): Setting Dns servers for network 101 to [/192.168.1.1]
,D/ConnectivityService(  822): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  822): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  822): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  822): Connected
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  822): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  822): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
,D/ConnectivityService(  822): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  822):    accepting network in place of null
,D/ConnectivityService(  822): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} }
,D/ConnectivityService(  822): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/CSLegacyTypeTracker(  822): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 1069): CM callback handler got msg 524290
D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  822): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 3066): type=WIFI subType= reason=null isConnected=true
,D/PhoneInterfaceManager( 1349): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1349): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  822): getDataEnabled: retVal=false
,V/MusicLeanback( 3066): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,E/GpsLocationProvider(  822): No APN found to select.
,D/SprintDMReceiver( 3918): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3918): simOperator:  IMSI: null
,D/SprintDMReceiver( 3918): Not Sprint UICC, don't do anything.
I/SystemUpdateService( 1781): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
D/SystemUpdateService( 1781): onCreate
I/jxcore-log( 3826): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 3826): 
D/SystemUpdateService( 1781): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
I/jxcore-log( 3826): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 3826): 
I/SystemUpdateService( 1781): active receiver: enabled
I/SystemUpdateService( 1781): showing system update notification
I/iu.Environment( 1781): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
I/iu.UploadsManager( 1781): num queued entries: 0
I/iu.UploadsManager( 1781): num updated entries: 0
D/ChimeraCfgMgr( 1781): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 1781): Loading module com.google.android.gms.kids from APK com.google.android.gms
I/iu.SyncManager( 1781): NEXT; no task
,I/ValidateNoPeople(  822): skipping global notification
,V/SystemUpdateService( 1781): retry (wakeup: false) in 3599952 ms
,D/SystemUpdateService( 1781): onDestroy
,I/GLSUser ( 1262): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1262): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1262): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1262): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/jxcore-log( 3826): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 3826): 
,W/Kids    ( 1781): [AccountUtils] Account not ready
W/Kids    ( 1781): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 1781): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 1781): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 1781): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 1781): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 1781): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 1781): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 1781): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 1781): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 1781): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 1781): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 1781): 	at java.lang.Thread.run(Thread.java:818)
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  822): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 26 Jan 2016 17:56:23 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1453830983130], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1453830983110]}
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  822): Validated
,D/ConnectivityService(  822): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/ConnectivityService(  822): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  822): rematching NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  822): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  822): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler( 1069): CM callback handler got msg 524290
D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/jxcore-log( 3826): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 3826): 
,I/jxcore-log( 3826): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 3826): 
,I/Babel   ( 2804): connection state changed from DISCONNECTED to CONNECTED
,I/GLSUser ( 1262): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1262): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1262): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1262): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/Herrevad( 1781): NQAS connected
,I/jxcore-log( 3826): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 3826): 
,D/Finsky  ( 3623): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3623): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3623): [1] 5.onFinished: Scheduling replication attempt 3.
,D/ConnectivityService(  822): reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10011
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  822): ValidatedState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  822): DefaultState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  822): Forcing reevaluation
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  822): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  822): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  822): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 26 Jan 2016 17:56:23 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1453830983532], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1453830983514]}
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  822): Validated
D/ConnectivityService(  822): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
,D/ConnectivityService(  822): Validated NetworkAgentInfo [WIFI () - 101]
,I/jxcore-log( 3826): Test app app.js loaded
I/jxcore-log( 3826): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3826): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 3826): BLE advertisement is supported,
I/jxcore-log( 3826): 
I/chromium( 3826): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/ConnectivityService(  822): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=8.33 rxSuccessRate=7.73 targetRoamBSSID=any RSSI=-49
E/WifiStateMachine(  822): WifiStateMachine L2Connected CMD_START_SCAN source -2 7, 9 -> obsolete
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=8.33 rxSuccessRate=7.73 targetRoamBSSID=any RSSI=-49
E/WifiStateMachine(  822): WifiStateMachine L2Connected CMD_START_SCAN source -2 8, 9 -> obsolete
,D/GCM     ( 1262): Connected
,D/GCM     ( 1262): Message class com.google.f.a.a.p
,D/HeadsetStateMachine( 2132): Disconnected process message: 10, size: 0
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.95 rxSuccessRate=2.12 targetRoamBSSID=any RSSI=-49
,D/HeadsetStateMachine( 2132): Disconnected process message: 10, size: 0
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1262): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1262): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1262): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1262): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  822): Explicit concurrent mark sweep GC freed 47885(2MB) AllocSpace objects, 7(300KB) LOS objects, 32% free, 33MB/49MB, paused 1.618ms total 98.759ms
,D/Finsky  ( 3623): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3623): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3623): [1] 5.onFinished: Scheduling replication attempt 4.
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=1.14 rxSuccessRate=2.70 targetRoamBSSID=any RSSI=-49
,E/WifiStateMachine(  822): WifiStateMachine starting scan for "NG7005g"WPA_PSK with 2412,5220
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1262): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1262): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1262): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1262): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/Finsky  ( 3623): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3623): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3623): [1] 5.onFinished: Scheduling replication attempt 5.
,I/PowerManagerService(  822): Going to sleep due to screen timeout (uid 1000)...
,I/Adreno  (  822): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/PermissionCache(  258): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (341 us)
,I/DisplayManagerService(  822): Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
D/SurfaceFlinger(  258): Set power mode=0, type=0 flinger=0xb6082000
D/qdhwcomposer(  258): hwc_setPowerMode: Setting mode 0 on display: 0
,V/ActivityManager(  822): Display changed displayId=0
,I/qdhwcomposer(  258): handle_blank_event: dpy:0 panel power state: 0
,D/qdhwcomposer(  258): hwc_setPowerMode: Done setting mode 0 on display 0
,D/SurfaceControl(  822): Excessive delay in setPowerMode(): 261ms
,I/DreamManagerService(  822): Entering dreamland.
I/PowerManagerService(  822): Dozing...
I/DreamController(  822): Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,D/audio_hw_primary(  357): adev_set_parameters: enter: screen_state=on
D/mot_vr_audio_hw(  357): adev_set_parameters: screen_state=on
,E/WifiStateMachine(  822): cancelDelayedScan -> 12
,E/native  (  822): do suspend false
,I/Keyboard.Facilitator( 1236): onFinishInput()
,E/WifiStateMachine(  822): cancelDelayedScan -> 14
,E/native  (  822): do suspend true
,D/audio_hw_primary(  357): adev_set_parameters: enter: screen_state=off
,D/mot_vr_audio_hw(  357): adev_set_parameters: screen_state=off
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-49
E/WifiStateMachine(  822): WifiStateMachine L2Connected CMD_START_SCAN source -2 13, 14 -> obsolete
,V/KeepSync( 3741): Connecting to GoogleApiClient
,I/GLSUser ( 1262): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1262): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1262): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1262): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1781): Handling authorization failure
E/ClientConnectionOperation( 1781): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
,E/ClientConnectionOperation( 1781): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1781): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1781): 	,at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1781): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1781): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1781): 	... 7 more
,V/KeepSync( 3741): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3741): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3741): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3741): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1262): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1262): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1262): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1262): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3741): IOException
E/KeepSync( 3741): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3741): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3741): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3741): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3741): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3741): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3741): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3741): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3741): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3741): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3741): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3741): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3741): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3741): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3741): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3741): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3741): 	... 10 more
W/KeepSync( 3741): Sync result 2
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 167314, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1],
,I/BooksSync( 3758): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3758): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1262): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1262): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1262): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1262): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1262): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1262): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1262): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1262): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/BooksAccountManager( 3758): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication,
,E/BooksSync( 3758): Soft error
E/BooksSync( 3758): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3758): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3758): Sync error
E/BooksSync( 3758): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3758): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3758): Finished books sync
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 167580, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-49
E/WifiStateMachine(  822): WifiStateMachine L2Connected CMD_START_SCAN source -2 11, 14 -> obsolete
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1262): Vacuum at: now=1453831046180 tag=VacuumService
,V/GoogleAuthProtoRequest( 3891): [425] a.<init>: mAccountName set to: thalitester@gmail.com
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GoogleURLConnFactory( 1262): Using platform SSLCertificateSocketFactory
,I/GLSUser ( 1262): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1262): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1262): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1262): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Uploader( 1262): No account for auth token provided
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1262): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1262): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1262): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1262): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3623): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3623): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3623): [1] 5.onFinished: Giving up after 6 failures.
,W/ExperimentUpdateService( 3891): [425] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3891): [425] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3891): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3891): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3891): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3891): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3891): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3891): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3891): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3891): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3891): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3891): 	at com.a.a.k.run(SourceFile:110)
,W/Uploader( 1262): No account for auth token provided
,I/art     ( 1262): Explicit concurrent mark sweep GC freed 47005(2MB) AllocSpace objects, 6(661KB) LOS objects, 37% free, 26MB/42MB, paused 2.878ms total 56.151ms
,I/GLSUser ( 1262): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1262): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1262): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1262): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1262): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1262): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1262): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1262): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1262): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1262): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1262): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1262): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1262): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1262): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1262): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1262): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1262): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1262): No account for auth token provided
,W/Uploader( 1262): No account for auth token provided
,W/Uploader( 1262): No account for auth token provided
,W/Uploader( 1262): No account for auth token provided
,W/Uploader( 1262): No account for auth token provided
,I/GLSUser ( 1262): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1262): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1262): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1262): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  822): Explicit concurrent mark sweep GC freed 43111(2MB) AllocSpace objects, 11(270KB) LOS objects, 31% free, 34MB/50MB, paused 1.943ms total 88.895ms
,E/Uploader( 1262): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1262): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1262): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1262): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1262): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1262): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1262): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1262): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1262): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1262): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1262): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1262): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1262): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/GLSUser ( 1262): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1262): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1262): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1262): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1262): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1262): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1262): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1262): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1262): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1262): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1262): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1262): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1262): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1262): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1262): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1262): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1262): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1262): No account for auth token provided
,W/Uploader( 1262): No account for auth token provided
,W/Uploader( 1262): No account for auth token provided
,W/Uploader( 1262):  no longer exists, so no auth token.
,I/GLSUser ( 1262): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1262): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1262): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1262): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1262): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1262): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1262): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1262): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1262): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1262): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1262): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1262): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1262): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1262): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1262): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1262): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1262): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,D/HeadsetStateMachine( 2132): Disconnected process message: 10, size: 0
,I/GLSUser ( 1262): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1262): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1262): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1262): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/HttpOperation( 3246): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception,
E/HttpOperation( 3246): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3246): 	at jdm.a(PG:82)
E/HttpOperation( 3246): 	at jcs.o(PG:406)
E/HttpOperation( 3246): 	at jcn.a(PG:1379)
E/HttpOperation( 3246): 	at jcs.i(PG:143),
E/HttpOperation( 3246): 	at blb.a(PG:3937)
E/HttpOperation( 3246): 	at czp.a(PG:18188)
E/HttpOperation( 3246): 	at czp.a(PG:9081)
E/HttpOperation( 3246): 	at czq.run(PG:1686)
E/HttpOperation( 3246): 	,at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3246): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3246): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3246): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3246): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3246): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3246): 	at jdj.a(PG:4091)
E/HttpOperation( 3246): 	at jdj.a(PG:1125)
E/HttpOperation( 3246): 	at jdm.a(PG:77)
E/HttpOperation( 3246): 	,... 12 more
E/HttpOperation( 3246): Caused by: faj: BadAuthentication
E/HttpOperation( 3246): 	at fal.a(PG:38)
E/HttpOperation( 3246): 	at jdj.a(PG:4089)
E/HttpOperation( 3246): 	... 14 more
,I/GLSUser ( 1262): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1262): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1262): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1262): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3246): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3246): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3246): 	at jdm.a(PG:82)
E/HttpOperation( 3246): 	at jcs.o(PG:406)
E/HttpOperation( 3246): 	at jcn.a(PG:1379)
E/HttpOperation( 3246): 	at jcs.i(PG:143)
E/HttpOperation( 3246): 	at hec.a(PG:42)
E/HttpOperation( 3246): 	at hee.a(PG:102)
E/HttpOperation( 3246): 	at czr.a(PG:65)
E/HttpOperation( 3246): 	at kka.a(PG:108)
E/HttpOperation( 3246): 	at czp.a(PG:19176)
E/HttpOperation( 3246): 	at czp.a(PG:9081)
E/HttpOperation( 3246): 	at czq.run(PG:1686)
E/HttpOperation( 3246): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3246): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3246): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3246): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3246): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3246): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3246): 	at jdj.a(PG:4091)
E/HttpOperation( 3246): 	at jdj.a(PG:1125)
E/HttpOperation( 3246): 	at jdm.a(PG:77)
E/HttpOperation( 3246): 	... 15 more
E/HttpOperation( 3246): Caused by: faj: BadAuthentication
E/HttpOperation( 3246): 	at fal.a(PG:38)
E/HttpOperation( 3246): 	at jdj.a(PG:4089)
E/HttpOperation( 3246): 	... 17 more
,E/ExperimentLoader( 3246): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3246): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3246): 	at jdm.a(PG:82)
E/ExperimentLoader( 3246): 	at jcs.o(PG:406)
,E/ExperimentLoader( 3246): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3246): 	at jcs.i(PG:143)
E/ExperimentLoader( 3246): 	at hec.a(PG:42)
E/ExperimentLoader( 3246): 	at hee.a(PG:102)
,E/ExperimentLoader( 3246): 	at czr.a(PG:65)
E/ExperimentLoader( 3246): 	at kka.a(PG:108)
E/ExperimentLoader( 3246): ,	at czp.a(PG:19176)
E/ExperimentLoader( 3246): 	at czp.a(PG:9081)
E/ExperimentLoader( 3246): 	at czq.run(PG:1686)
E/ExperimentLoader( 3246): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3246): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
,E/ExperimentLoader( 3246): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3246): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3246): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3246): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3246): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3246): ,	at jdj.a(PG:1125)
E/ExperimentLoader( 3246): 	at jdm.a(PG:77)
E/ExperimentLoader( 3246): 	... 15 more
E/ExperimentLoader( 3246): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3246): 	at fal.a(PG:38)
E/ExperimentLoader( 3246): 	at jdj.a(PG:4089)
,E/ExperimentLoader( 3246): 	... 17 more
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 169049, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2132): Disconnected process message: 10, size: 0
,V/GoogleAuthProtoRequest( 3891): [426] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1262): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1262): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1262): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1262): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3891): [426] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3891): [426] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3891): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3891): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3891): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3891): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3891): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3891): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3891): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3891): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3891): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3891): 	at com.a.a.k.run(SourceFile:110)
,I/Keyboard.Facilitator.LanguageModelFlusher( 1236): run()
I/Keyboard.Facilitator( 1236): flushDynamicLanguageModels()
,I/ConfigService( 1262): onCreate
,I/BooksSync( 3758): Starting books sync for 61035162, extras: ade
,V/KeepSync( 3741): Connecting to GoogleApiClient
,I/BooksConfig( 3758): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1262): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1262): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1262): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1262): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1262): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1262): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1262): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1262): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1781): Handling authorization failure
E/ClientConnectionOperation( 1781): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1781): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1781): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1781): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1781): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1781): 	... 7 more
,V/KeepSync( 3741): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3741): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3741): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3741): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1262): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1262): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1262): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1262): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3758): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3758): Soft error
E/BooksSync( 3758): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3758): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3758): Sync error
E/BooksSync( 3758): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3758): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3758): Finished books sync
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 198476, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1262): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1262): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1262): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1262): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3741): IOException
,E/KeepSync( 3741): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3741): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3741): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3741): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3741): ,	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3741): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3741): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3741): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
,E/KeepSync( 3741): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3741): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3741): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3741): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,E/KeepSync( 3741): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3741): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3741): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3741): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
,E/KeepSync( 3741): 	... 10 more
W/KeepSync( 3741): Sync result 2
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 198212, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/ConfigService( 1262): onDestroy
,D/HeadsetStateMachine( 2132): Disconnected process message: 10, size: 0
,I/GLSUser ( 1262): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1262): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1262): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1262): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3246): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3246): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3246): 	at jdm.a(PG:82)
E/HttpOperation( 3246): 	at jcs.o(PG:406)
E/HttpOperation( 3246): 	at jcn.a(PG:1379)
E/HttpOperation( 3246): 	at jcs.i(PG:143)
E/HttpOperation( 3246): 	at blb.a(PG:3937)
E/HttpOperation( 3246): 	at czp.a(PG:18188)
E/HttpOperation( 3246): 	at czp.a(PG:9081)
E/HttpOperation( 3246): 	at czq.run(PG:1686)
E/HttpOperation( 3246): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3246): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3246): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3246): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3246): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3246): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3246): 	at jdj.a(PG:4091)
E/HttpOperation( 3246): 	at jdj.a(PG:1125)
E/HttpOperation( 3246): 	at jdm.a(PG:77)
E/HttpOperation( 3246): 	... 12 more
E/HttpOperation( 3246): Caused by: faj: BadAuthentication
E/HttpOperation( 3246): 	at fal.a(PG:38)
E/HttpOperation( 3246): 	at jdj.a(PG:4089)
E/HttpOperation( 3246): 	... 14 more
,I/GLSUser ( 1262): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1262): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1262): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1262): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3246): [getmobileexperiments] Unexpected exception,
E/HttpOperation( 3246): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3246): 	at jdm.a(PG:82)
E/HttpOperation( 3246): 	at jcs.o(PG:406)
E/HttpOperation( 3246): 	at jcn.a(PG:1379)
E/HttpOperation( 3246): 	at jcs.i(PG:143)
E/HttpOperation( 3246): 	at hec.a(PG:42)
E/HttpOperation( 3246): 	at hee.a(PG:102)
E/HttpOperation( 3246): 	at czr.a(PG:65)
E/HttpOperation( 3246): 	at kka.a(PG:108)
E/HttpOperation( 3246): 	at czp.a(PG:19176)
E/HttpOperation( 3246): 	at czp.a(PG:9081)
E/HttpOperation( 3246): 	at czq.run(PG:1686)
E/HttpOperation( 3246): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3246): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3246): 	,at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3246): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3246): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3246): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3246): 	at jdj.a(PG:4091)
E/HttpOperation( 3246): 	at jdj.a(PG:1125)
E/HttpOperation( 3246): 	at jdm.a(PG:77)
E/HttpOperation( 3246): 	... 15 more
E/HttpOperation( 3246): Caused by: faj: BadAuthentication
E/HttpOperation( 3246): 	at fal.a(PG:38)
E/HttpOperation( 3246): 	at jdj.a(PG:4089)
E/HttpOperation( 3246): 	... 17 more
,E/ExperimentLoader( 3246): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3246): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3246): 	at jdm.a(PG:82)
E/ExperimentLoader( 3246): 	at jcs.o(PG:406)
E/ExperimentLoader( 3246): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3246): 	at jcs.i(PG:143)
E/ExperimentLoader( 3246): 	at hec.a(PG:42)
E/ExperimentLoader( 3246): 	at hee.a(PG:102)
E/ExperimentLoader( 3246): 	at czr.a(PG:65)
E/ExperimentLoader( 3246): 	at kka.a(PG:108)
E/ExperimentLoader( 3246): 	at czp.a(PG:19176)
E/ExperimentLoader( 3246): 	at czp.a(PG:9081)
E/ExperimentLoader( 3246): 	at czq.run(PG:1686)
E/ExperimentLoader( 3246): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3246): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3246): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3246): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3246): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3246): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3246): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3246): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3246): 	at jdm.a(PG:77)
E/ExperimentLoader( 3246): 	... 15 more
E/ExperimentLoader( 3246): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3246): 	at fal.a(PG:38)
E/ExperimentLoader( 3246): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3246): 	... 17 more
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 230491, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2132): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2132): Disconnected process message: 10, size: 0
,I/jxcore-log( 3826): --= Surplus to requirements =--
I/jxcore-log( 3826): 
I/jxcore-log( 3826): ****TEST TOOK:  ms ****
I/jxcore-log( 3826): 
I/jxcore-log( 3826): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3826): 
,D/AndroidRuntime( 4176): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,D/AndroidRuntime( 4176): CheckJNI is OFF
,D/AndroidRuntime( 4176): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  822): Force stopping com.test.thalitest appid=10265 user=-1: uninstall pkg,
,I/ActivityManager(  822): Killing 3826:com.test.thalitest/u0a265 (adj 0): stop com.test.thalitest
,W/PackageSettings(  822): Skipping PackageSetting{3642ea19 com.example.hello/10273} due to missing metadata
,I/WindowState(  822): WIN DEATH: Window{2042842 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  822): Client connection lost with reason: 4
,W/ActivityManager(  822): Force removing ActivityRecord{92428fb u0 com.test.thalitest/.MainActivity t28}: app died, no saved state
,V/ActivityManager(  822): Display changed displayId=0
,I/ActivityManager(  822): Force stopping com.test.thalitest appid=10265 user=0: pkg removed
,W/ActivityManager(  822): Spurious death for ProcessRecord{5aea1d4 3826:com.test.thalitest/u0a265}, curProc for 3826: null
,I/Keyboard.Facilitator( 1236): resetDictionaries() : en_US
,I/InputReader(  822): Reconfiguring input devices.  changes=0x00000010
,D/TaskPersister(  822): removeObsoleteFile: deleting file=28_task.xml
,D/BuaReceiver( 3518): ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,I/Keyboard.Facilitator.DecoderInitializer( 1236): run()
,I/Decoder ( 1236): createOrResetDecoder
I/art     ( 1069): Explicit concurrent mark sweep GC freed 56882(2MB) AllocSpace objects, 0(0B) LOS objects, 18% free, 71MB/87MB, paused 4.100ms total 59.533ms
,I/art     (  368): Background concurrent mark sweep GC freed 789(33KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 21MB/36MB, paused 5.251ms total 13.521ms
,I/ActivityManager(  822): Start proc 4192:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,I/art     ( 1518): Explicit concurrent mark sweep GC freed 3417(320KB) AllocSpace objects, 1(25KB) LOS objects, 37% free, 26MB/42MB, paused 1.944ms total 87.981ms
W/InputMethodManagerService(  822): Got RemoteException sending setActive(false) notification to pid 3826 uid 10265
,I/ConfigService( 1262): onCreate
,I/art     (  368): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 1.561ms total 19.704ms
,I/Keyboard.Facilitator( 1236): onFinishInput()
,I/art     (  368): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 210us total 14.020ms
,I/art     (  822): Explicit concurrent mark sweep GC freed 39242(2024KB) AllocSpace objects, 10(442KB) LOS objects, 31% free, 34MB/50MB, paused 2.274ms total 125.534ms
I/art     (  822): WaitForGcToComplete blocked for 88.392ms for cause Explicit
,I/art     (  368): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 200us total 9.862ms
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1236): run()
I/art     ( 1372): Explicit concurrent mark sweep GC freed 5087(371KB) AllocSpace objects, 12(1408KB) LOS objects, 31% free, 35MB/51MB, paused 865us total 22.020ms
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1236): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1236): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1236): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1236): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1236): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1236): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1236): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1236): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1236): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1236): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1236): run()
I/StatsUtilsManager( 1236): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1236): shouldRecordStats() = Too Soon
,I/ContactLocale( 4192): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/art     (  822): Explicit concurrent mark sweep GC freed 2829(127KB) AllocSpace objects, 5(551KB) LOS objects, 32% free, 33MB/49MB, paused 1.701ms total 82.830ms
,I/art     (  822): WaitForGcToComplete blocked for 96.936ms for cause Explicit
,D/JobSchedulerService(  822): Receieved: android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  822): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,I/art     (  822): Explicit concurrent mark sweep GC freed 1595(71KB) AllocSpace objects, 0(0B) LOS objects, 32% free, 33MB/49MB, paused 1.501ms total 44.896ms
,W/LocationOracleImpl( 1518): Best location was null
,I/HotwordRecognitionRnr( 1518): Starting hotword detection.
,I/MicrophoneInputStream( 1518): mic_starting com.google.android.apps.gsa.speech.audio.u@20c8deda
,D/VoicemailCleanupService( 4192): Cleaning up data for package: com.test.thalitest
,I/AudioFlinger(  357): AudioFlinger's thread 0xb406d000 ready to run
,I/SoundTriggerHwService::Module(  357): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,I/MicrophoneInputStream( 1518): mic_started com.google.android.apps.gsa.speech.audio.u@20c8deda
,I/art     ( 4176): System.exit called, status: 0
I/AndroidRuntime( 4176): VM exiting with result code 0.
,I/ActivityManager(  822): Start proc 4223:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,D/audio_hw_primary(  357): select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
D/msm8974_platform(  357): platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
,E/ACDB-LOADER(  357): Error: ACDB AudProc vol returned = -19
D/audio_hw_primary(  357): enable_snd_device: snd_device(55: voice-rec-mic)
,D/audio_hw_primary(  357): enable_audio_route: apply and update mixer path: audio-record
,I/ActivityManager(  822): Start proc 4249:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,I/HotwordWorker( 1518): onReady
,W/ContextImpl( 4249): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2609 
,E/SQLiteLog( 1262): (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,D/AndroidRuntime( 1262): Shutting down VM
,--------- beginning of crash
E/AndroidRuntime( 1262): FATAL EXCEPTION: main
E/AndroidRuntime( 1262): Process: com.google.process.gapps, PID: 1262
E/AndroidRuntime( 1262): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1262): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2616)
E/AndroidRuntime( 1262): 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
E/AndroidRuntime( 1262): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1380)
E/AndroidRuntime( 1262): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1262): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 1262): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
E/AndroidRuntime( 1262): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 1262): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 1262): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
E/AndroidRuntime( 1262): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
E/AndroidRuntime( 1262): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1262): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1262): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 1262): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1262): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1262): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/AndroidRuntime( 1262): 	at com.google.android.gms.gcm.bh.a(SourceFile:310)
E/AndroidRuntime( 1262): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:127)
E/AndroidRuntime( 1262): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:321)
E/AndroidRuntime( 1262): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2609)
E/AndroidRuntime( 1262): 	... 9 more
,I/art     ( 1798): Explicit concurrent mark sweep GC freed 17242(1004KB) AllocSpace objects, 8(128KB) LOS objects, 37% free, 26MB/42MB, paused 1.101ms total 32.896ms
E/DropBoxManagerService(  822): Can't write: system_app_crash
E/DropBoxManagerService(  822): java.io.FileNotFoundException: /data/system/dropbox/drop98.tmp: open failed: EROFS (Read-only file system)
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
E/DataBuffer( 1798): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2d6359b9)
E/SQLiteDatabase( 4249): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4249): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4249): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4249): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4249): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4249): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4249): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4249): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4249): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4249): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4249): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4249): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4249): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4249): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4249): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4249): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
E/SQLiteDatabase( 4249): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
E/SQLiteDatabase( 4249): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4249): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4249): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 4249): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/AndroidRuntime( 4249): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4249): Process: com.android.keychain, PID: 4249
E/AndroidRuntime( 4249): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4249): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4249): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 4249): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 4249): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4249): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4249): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4249): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AndroidRuntime( 4249): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AndroidRuntime( 4249): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 4249): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AndroidRuntime( 4249): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 4249): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 4249): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 4249): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
E/AndroidRuntime( 4249): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
E/AndroidRuntime( 4249): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4249): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4249): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 4249): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/OpenGLRenderer(  822): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
D/Atlas   (  822): Validating map...
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
D/Launcher.Workspace( 1372): 11683562 - stripEmptyScreens()
D/Launcher.Workspace( 1372): 11683562 - stripEmptyScreens()
,E/SQLiteLog( 1372): (3850) statement aborts at 24: [DELETE FROM shortcut_and_widget_previews WHERE name LIKE ? OR name LIKE ?] disk I/O error
I/art     ( 1262): Explicit concurrent mark sweep GC freed 50948(3MB) AllocSpace objects, 12(1050KB) LOS objects, 36% free, 27MB/43MB, paused 1.041ms total 27.984ms
D/WifiService(  822): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@147e1087}
E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-49
I/OpenGLRenderer(  822): Initialized EGL, version 1.4
D/OpenGLRenderer(  822): Enabling debug mode 0
,I/HotwordDetector( 1518): Closing mic
,I/MicrophoneInputStream( 1518): mic_close com.google.android.apps.gsa.speech.audio.u@20c8deda
,E/Search.SharedPreferencesProto( 1518): Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
,I/ActivityManager(  822): Killing 3419:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,D/audio_hw_primary(  357): disable_audio_route: reset and update mixer path: audio-record
,D/audio_hw_primary(  357): disable_snd_device: snd_device(55: voice-rec-mic)
,I/SoundTriggerHwService::Module(  357): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,I/HotwordRecognitionRnr( 1518): Hotword detection finished
I/HotwordRecognitionRnr( 1518): Stopping hotword detection.
,I/ActivityManager(  822): Killing 2416:com.google.android.calendar/u0a37 (adj 15): empty #18
,E/native  ( 1236): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1236): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,E/native  ( 1236): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1236): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,E/native  ( 1236): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp,
E/native  ( 1236): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1236): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
,E/native  ( 1236): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
,D/WifiService(  822): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@147e1087}
,D/HeadsetStateMachine( 2132): Disconnected process message: 10, size: 0
,E/Search.SharedPreferencesProto( 1518): Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
,E/QMI_FW  (  822): xport_send: Sendto failed for port 4608
E/LocSvc_api_v02(  822): E/locClientSendReq:2446]: send_msg_sync error: -1
E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 11, ind.status = -1660863763
E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,E/QMI_FW  (  822): xport_send: Sendto failed for port 4608
E/LocSvc_api_v02(  822): E/locClientSendReq:2446]: send_msg_sync error: -1
,E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 11, ind.status = -1660863763
E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
E/QMI_FW  (  822): xport_send: Sendto failed for port 4608
E/LocSvc_api_v02(  822): E/locClientSendReq:2446]: send_msg_sync error: -1
E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::injectLocation(GpsExtLocation):857]: error! inject position failed
E/QMI_FW  (  822): xport_send: Sendto failed for port 4608
E/LocSvc_api_v02(  822): E/locClientSendReq:2446]: send_msg_sync error: -1
,E/LocSvc_ApiV02(  822): E/virtual loc_api_adapter_err LocApiV02::injectPosition(double, double, float):565]: error! status = eLOC_CLIENT_FAILURE_INTERNAL, inject_pos_ind.status = eQMI_LOC_SUCCESS_V02
E/QMI_FW  (  822): xport_send: Sendto failed for port 4608
E/LocSvc_api_v02(  822): E/locClientSendReq:2446]: send_msg_sync error: -1
E/LocSvc_ApiV02(  822): E/virtual loc_api_adapter_err LocApiV02::injectPosition(double, double, float):565]: error! status = eLOC_CLIENT_FAILURE_INTERNAL, inject_pos_ind.status = eQMI_LOC_SUCCESS_V02
,I/qdhwcomposer(  258): handle_blank_event: dpy:0 panel power state: 0
E/kickstart(  871): ERROR: function: rx_data:288 Read/Write File descriptor returned error: No such device, error code -1
E/kickstart(  871): ERROR: function: sahara_main:1143 Sahara protocol error
,E/kickstart(  871): ERROR: function: main:268 Uploading  Image using Sahara protocol failed
I/kickstart(  871): STATUS: Wrote to /sys/power/wake_unlock

```
