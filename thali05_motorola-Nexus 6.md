#### Test 57659382b63fd0b_thali05_motorola-Nexus 6 Logs


```
--------- beginning of main
I/CheckinService( 1783): Done disabling old GoogleServicesFramework version
,D/AndroidRuntime( 3595): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 3595): CheckJNI is OFF
D/AndroidRuntime( 3595): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  819): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/WindowManager(  819): addAppToken: AppWindowToken{3ddae176 token=Token{330fec11 ActivityRecord{25bc6438 u0 com.test.thalitest/.MainActivity t28}}} to stack=1 task=28 at 0
V/WindowManager(  819): Adding window Window{37718013 u0 Starting com.test.thalitest} at 2 of 7 (after Window{220a3a44 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
I/HotwordDetector( 1506): Closing mic
I/MicrophoneInputStream( 1506): mic_close com.google.android.apps.gsa.speech.audio.u@19f3df3e
D/AndroidRuntime( 3595): Shutting down VM
D/audio_hw_primary(  356): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  356): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  356): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/ActivityManager(  819): Start proc 3609:com.test.thalitest/u0a265 for activity com.test.thalitest/.MainActivity
I/HotwordRecognitionRnr( 1506): Hotword detection finished
I/HotwordRecognitionRnr( 1506): Stopping hotword detection.
I/ActivityManager(  819): Killing 3010:com.google.android.apps.fitness/u0a51 (adj 15): empty #17
E/LocSvc_IzatApiV02(  819): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1660003603
E/LocSvc_IzatApiV02(  819): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
I/WebViewFactory( 3609): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3609): Time to load native libraries: 2 ms (timestamps 1357-1359)
I/LibraryLoader( 3609): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3609): Binding Chromium to main looper Looper (main, tid 1) {2b0a52d1}
I/LibraryLoader( 3609): Expected native library version number "",actual native library version number ""
I/chromium( 3609): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3609): Initializing chromium process, singleProcess=true
W/art     ( 3609): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3609): ApplicationContext is null in ApplicationStatus
,W/chromium( 3609): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3609): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3609): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3609): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/BluetoothManagerService(  819): Message: 20
D/BluetoothManagerService(  819): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3812cebd:true
,W/art     ( 3609): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3609): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3609): CordovaWebView is running on device made by: motorola
,W/art     ( 3609): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3609): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3609): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,D/Atlas   ( 3609): Validating map...
,V/WindowManager(  819): Adding window Window{3f79e12d u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{37718013 u0 Starting com.test.thalitest})
,W/chromium( 3609): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3609): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3609): Enabling debug mode 0
,I/Keyboard.Facilitator( 1240): onFinishInput()
,I/ActivityManager(  819): Displayed com.test.thalitest/.MainActivity: +733ms,
,W/BindingManager( 3609): Cannot call determinedVisibility() - never saw a connection for the pid: 3609
,D/JsMessageQueue( 3609): Set native->JS mode to OnlineEventsBridgeMode
,I/ActivityManager(  819): Waited long enough for: ServiceRecord{987199b u0 com.motorola.android.buacontactadapter/.AuthenticationService}
,D/jxcore_app_log( 3609): JniHelper::setJavaVM(0xb489d200), pthread_self() = -1576324608
,I/chromium( 3609): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 3609): Initializing JXcore engine
W/jxcore-log( 3609): JXcore engine is ready
,W/Thread-401( 3663): type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[12961]" dev="sockfs" ino=12961 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/Thread-401( 3663): type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-401( 3663): type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[10836]" dev="sockfs" ino=10836 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-401( 3663): type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[22081]" dev="sockfs" ino=22081 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 3609): Starting JXcore engine
,W/jxcore-log( 3609): Platform android
W/jxcore-log( 3609): 
,W/jxcore-log( 3609): Process ARCH arm
W/jxcore-log( 3609): 
,I/jxcore-log( 3609): JXcore Cordova bridge is ready!
I/jxcore-log( 3609): 
W/jxcore-log( 3609): JXcore engine is started
,I/jxcore-log( 3609): Toggling radios to true
I/jxcore-log( 3609): 
,D/BluetoothAdapter( 3609): enable(): BT is already enabled..!
,D/WifiService(  819): New client listening to asynchronous messages,
D/WifiService(  819): setWifiEnabled: true pid=3609, uid=10265
E/WifiService(  819): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3609): Radios toggled
,I/jxcore-log( 3609): 
,I/wpa_supplicant( 1136): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1,
,I/jxcore-log( 3609): My device name is: motorola-Nexus 6
I/jxcore-log( 3609): 
,E/WifiStateMachine(  819): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  819): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  352): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1382): Read error: ssl=0xb4888800: I/O error during system call, Connection timed out
,V/NativeCrypto( 1382): SSL shutdown failed: ssl=0xb4888800: I/O error during system call, Broken pipe
,D/ConnectivityService(  819): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  819): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
E/WifiStateMachine(  819): Start Disconnecting Watchdog 1
D/ConnectivityService(  819): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10011
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  819): ValidatedState{ when=-2ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  819): DefaultState{ when=-2ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  819): Forcing reevaluation
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  819): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  819): Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
E/WifiStateMachine(  819): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  819): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname,
,D/CommandListener(  352): Clearing all IP addresses on wlan0
,D/ConnectivityService(  819): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/CSLegacyTypeTracker(  819): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  819): OfflineState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  819): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  819): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  819): Disconnected - quitting
D/ConnectivityService(  819): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityManager.CallbackHandler( 1072): CM callback handler got msg 524292
D/ConnectivityService(  819): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/Tethering(  819): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 3287): type=WIFI subType= reason=null isConnected=false
D/WifiNetworkAgent(  819): NetworkAgent: NetworkAgent channel lost
,E/WifiStateMachine(  819): CMD_AUTO_CONNECT sup state CompletedState my state DisconnectedState nid=0 roam=3
E/WifiStateMachine(  819): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=0
D/ConnectivityService(  819): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  819): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/ConnectivityService(  819): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,D/ConnectivityService(  819): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
,D/Tethering(  819): MasterInitialState.processMessage what=3
,D/PhoneInterfaceManager( 1288): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
,E/PhoneInterfaceManager( 1288): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
V/MusicLeanback( 3287): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/TelephonyManager(  819): getDataEnabled: retVal=false
,E/WifiConfigStore(  819): Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiConfigStore(  819): will read network variables netId=0
,I/ActivityManager(  819): Start proc 3671:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.steen.receiver.ConnectivityChangeReceiver
,E/WifiStateMachine(  819): CMD_AUTO_CONNECT did save config ->  nid=0
,E/WifiConfigStore(  819): will read network variables netId=0
,E/GpsLocationProvider(  819): No APN found to select.
,I/art     (  368): Explicit concurrent mark sweep GC freed 705(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 213us total 11.096ms
,D/PhoneInterfaceManager( 1288): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
,E/PhoneInterfaceManager( 1288): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
I/art     (  368): Explicit concurrent mark sweep GC freed 6(208B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 205us total 9.997ms
,D/TelephonyManager(  819): getDataEnabled: retVal=false
,E/GpsLocationProvider(  819): No APN found to select.
,I/art     (  368): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 521us total 8.838ms
,I/art     ( 1382): Explicit concurrent mark sweep GC freed 22786(1118KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 905us total 20.100ms
,V/GLSActivity( 1382): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  819): Start proc 3697:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,I/GLSUser ( 1382): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1382): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1382): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1382): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1382): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SprintDMReceiver( 3697): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/Finsky  ( 3051): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3051): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3051): [1] 5.onFinished: Scheduling replication attempt 1.
,D/SprintDMHelper( 3697): simOperator:  IMSI: null
D/SprintDMReceiver( 3697): Not Sprint UICC, don't do anything.
,I/ActivityManager(  819): Killing 3259:com.android.settings/1000 (adj 15): empty #17
,I/SystemUpdateService( 1783): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,I/ActivityManager(  819): Killing 2728:com.google.android.apps.maps/u0a65 (adj 15): empty #17
,D/SystemUpdateService( 1783): onCreate
,D/SystemUpdateService( 1783): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1783): active receiver: enabled
,I/SystemUpdateService( 1783): showing system update notification
,I/iu.Environment( 1783): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1783): num queued entries: 0
I/iu.UploadsManager( 1783): num updated entries: 0
I/ValidateNoPeople(  819): skipping global notification
I/iu.SyncManager( 1783): NEXT; no task
D/ChimeraCfgMgr( 1783): Loading module com.google.android.gms.kids from APK com.google.android.gms
,V/SystemUpdateService( 1783): retry (wakeup: false) in 3599974 ms
,I/ActivityManager(  819): Start proc 3717:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,D/SystemUpdateService( 1783): onDestroy
,I/Babel   ( 2979): connection state changed from UNKNOWN to DISCONNECTED
,I/GAv4    ( 3717): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3717):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3717):   adb logcat -s GAv4
,W/GAv4    ( 3717): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3717): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3717): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 3717): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3717): Time to load native libraries: 2 ms (timestamps 5101-5103)
,I/LibraryLoader( 3717): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3717): Binding Chromium to main looper Looper (main, tid 1) {59de5cc}
,I/LibraryLoader( 3717): Expected native library version number "",actual native library version number ""
I/chromium( 3717): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3717): Initializing chromium process, singleProcess=true
,W/art     ( 3717): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3717): ApplicationContext is null in ApplicationStatus
,W/chromium( 3717): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3717): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3717): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3717): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,I/NSApplication( 3717): Starting up...
,W/AudioManagerAndroid( 3717): Requires BLUETOOTH permission
,I/ActivityManager(  819): Start proc 3773:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,I/ActivityManager(  819): Killing 3338:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,I/ActivityManager(  819): Start proc 3793:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,I/ActivityManager(  819): Killing 3359:com.android.musicfx/u0a18 (adj 15): empty #17
,I/wpa_supplicant( 1136): wlan0: Trying to associate with SSID 'NG7005g'
,I/art     (  819): Explicit concurrent mark sweep GC freed 33712(1742KB) AllocSpace objects, 10(254KB) LOS objects, 32% free, 33MB/49MB, paused 1.429ms total 86.063ms
,I/ActivityManager(  819): Killing 3405:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,I/wpa_supplicant( 1136): wlan0: Associated with c0:ff:d4:d3:aa:4a
,V/MusicLeanback( 3287): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/wpa_supplicant( 1136): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 1136): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=0 id_str=]
,D/ConnectivityService(  819): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} }
E/WifiConfigStore(  819): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  819): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  819): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  352): Setting iface cfg
E/WifiStateMachine(  819): Start Dhcp Watchdog 2
,E/WifiStateMachine(  819):  WifiLinkLayerStats: 
E/WifiStateMachine(  819):  my bss beacon rx: 187
E/WifiStateMachine(  819):  RSSI mgmt: -49
E/WifiStateMachine(  819):  BE :  rx=149 tx=127 lost=0 retries=0
E/WifiStateMachine(  819):  BK :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  819):  VI :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  819):  VO :  rx=4 tx=0 lost=0 retries=0
E/WifiStateMachine(  819):  on_time : 7367 tx_time=139 rx_time=453 scan_time=0
,D/ConnectivityService(  819): updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,D/SprintDMReceiver( 3697): Received intent: android.net.conn.CONNECTIVITY_CHANGE
D/SprintDMHelper( 3697): simOperator:  IMSI: null
D/SprintDMReceiver( 3697): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1783): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1783): onCreate
,D/SystemUpdateService( 1783): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1783): active receiver: enabled
,I/SystemUpdateService( 1783): showing system update notification
,D/ChimeraCfgMgr( 1783): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/ValidateNoPeople(  819): skipping global notification
,E/native  (  819): do suspend false
,V/SystemUpdateService( 1783): retry (wakeup: false) in 3599981 ms
,D/SystemUpdateService( 1783): onDestroy
,E/WifiStateMachine(  819): scanCount==0 - aborting
,I/dhcpcd  ( 3825): version 5.5.6 starting
,I/dhcpcd  ( 3825): wlan0: rebinding lease of 192.168.1.122
,I/dhcpcd  ( 3825): wlan0: acknowledged 192.168.1.122 from 192.168.1.1
,I/dhcpcd  ( 3825): wlan0: leased 192.168.1.122 for 86400 seconds
,I/jxcore-log( 3609): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 3609): 
,D/ConnectivityService(  819): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  819): Adding iface wlan0 to network 101
,E/WifiStateMachine(  819): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,I/ActivityManager(  819): Killing 3512:com.google.android.gm.exchange/u0a77 (adj 15): empty #17
,E/ConnectivityService(  819): Unexpected mtu value: 0, wlan0
,D/ConnectivityService(  819): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/ConnectivityService(  819): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  819): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  819): Setting Dns servers for network 101 to [/192.168.1.1]
,I/ActivityManager(  819): Killing 3089:com.google.android.gms:car/u0a11 (adj 15): empty #18
,W/ActivityManager(  819): Failed to clear dns cache for: com.google.android.gms
,D/ConnectivityService(  819): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  819): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  819): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  819): Connected
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  819): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  819): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
D/ConnectivityService(  819): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  819):    accepting network in place of null
,D/ConnectivityService(  819): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} }
,D/ConnectivityService(  819): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1072): CM callback handler got msg 524290
D/CSLegacyTypeTracker(  819): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  819): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  819): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE,
,D/Tethering(  819): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 3287): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 3287): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/SprintDMReceiver( 3697): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3697): simOperator:  IMSI: null
D/SprintDMReceiver( 3697): Not Sprint UICC, don't do anything.
,I/jxcore-log( 3609): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 3609): 
,I/ActivityManager(  819): Start proc 3860:com.google.android.keep/u0a79 for service com.google.android.keep/.syncadapter.KeepSyncAdapterService
,I/SystemUpdateService( 1783): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
D/SystemUpdateService( 1783): onCreate
,D/SystemUpdateService( 1783): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1783): active receiver: enabled
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  819): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 29 Jan 2016 15:49:55 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454082595452], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454082595425]}
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  819): Validated
D/ConnectivityService(  819): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/ConnectivityService(  819): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  819): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  819): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  819): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  819): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1072): CM callback handler got msg 524290
,I/SystemUpdateService( 1783): showing system update notification
,I/iu.Environment( 1783): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1783): num queued entries: 0
,I/iu.UploadsManager( 1783): num updated entries: 0
,I/iu.SyncManager( 1783): NEXT; no task
D/PhoneInterfaceManager( 1288): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1288): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  819): getDataEnabled: retVal=false
,E/GpsLocationProvider(  819): No APN found to select.
,D/ChimeraCfgMgr( 1783): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 1783): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/ValidateNoPeople(  819): skipping global notification
,I/jxcore-log( 3609): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 3609): 
,V/SystemUpdateService( 1783): retry (wakeup: false) in 3599960 ms,
,I/jxcore-log( 3609): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 3609): 
,D/SystemUpdateService( 1783): onDestroy
,I/GLSUser ( 1382): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1382): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1382): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1382): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1382): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/jxcore-log( 3609): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 3609): 
,W/Kids    ( 1783): [AccountUtils] Account not ready
W/Kids    ( 1783): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 1783): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 1783): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 1783): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 1783): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 1783): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 1783): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 1783): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 1783): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 1783): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 1783): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 1783): 	at java.lang.Thread.run(Thread.java:818)
,I/Babel   ( 2979): connection state changed from DISCONNECTED to CONNECTED
,I/jxcore-log( 3609): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 3609): 
,V/Herrevad( 1783): NQAS connected
,I/jxcore-log( 3609): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 3609): 
,I/jxcore-log( 3609): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 3609): 
,I/GLSUser ( 1382): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1382): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1382): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1382): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1382): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3446): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3446): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3446): 	at jdm.a(PG:82)
E/HttpOperation( 3446): 	at jcs.o(PG:406)
E/HttpOperation( 3446): 	at jcn.a(PG:1379)
E/HttpOperation( 3446): 	at jcs.i(PG:143)
E/HttpOperation( 3446): 	at blb.a(PG:3937)
E/HttpOperation( 3446): 	at czp.a(PG:18188)
E/HttpOperation( 3446): 	at czp.a(PG:9081)
E/HttpOperation( 3446): 	at czq.run(PG:1686)
E/HttpOperation( 3446): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3446): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3446): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3446): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3446): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3446): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3446): 	at jdj.a(PG:4091)
E/HttpOperation( 3446): 	at jdj.a(PG:1125)
E/HttpOperation( 3446): 	at jdm.a(PG:77)
E/HttpOperation( 3446): 	... 12 more
E/HttpOperation( 3446): Caused by: faj: BadAuthentication
E/HttpOperation( 3446): 	at fal.a(PG:38)
E/HttpOperation( 3446): 	at jdj.a(PG:4089)
E/HttpOperation( 3446): 	... 14 more
,I/GLSUser ( 1382): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1382): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1382): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1382): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1382): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3446): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3446): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3446): 	at jdm.a(PG:82)
E/HttpOperation( 3446): 	at jcs.o(PG:406)
E/HttpOperation( 3446): 	at jcn.a(PG:1379)
E/HttpOperation( 3446): 	at jcs.i(PG:143)
E/HttpOperation( 3446): 	at hec.a(PG:42)
E/HttpOperation( 3446): 	at hee.a(PG:102)
E/HttpOperation( 3446): 	at czr.a(PG:65)
E/HttpOperation( 3446): 	at kka.a(PG:108)
E/HttpOperation( 3446): 	at czp.a(PG:19176)
E/HttpOperation( 3446): 	at czp.a(PG:9081)
E/HttpOperation( 3446): 	at czq.run(PG:1686)
E/HttpOperation( 3446): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3446): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3446): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3446): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3446): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3446): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3446): 	at jdj.a(PG:4091)
E/HttpOperation( 3446): 	at jdj.a(PG:1125)
E/HttpOperation( 3446): 	at jdm.a(PG:77)
E/HttpOperation( 3446): 	... 15 more
E/HttpOperation( 3446): Caused by: faj: BadAuthentication
E/HttpOperation( 3446): 	at fal.a(PG:38)
E/HttpOperation( 3446): 	at jdj.a(PG:4089)
E/HttpOperation( 3446): 	... 17 more
E/ExperimentLoader( 3446): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3446): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3446): 	at jdm.a(PG:82)
E/ExperimentLoader( 3446): 	at jcs.o(PG:406)
E/ExperimentLoader( 3446): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3446): 	at jcs.i(PG:143)
E/ExperimentLoader( 3446): 	at hec.a(PG:42)
E/ExperimentLoader( 3446): 	at hee.a(PG:102)
E/ExperimentLoader( 3446): 	at czr.a(PG:65)
E/ExperimentLoader( 3446): 	at kka.a(PG:108)
E/ExperimentLoader( 3446): 	at czp.a(PG:19176)
E/ExperimentLoader( 3446): 	at czp.a(PG:9081)
E/ExperimentLoader( 3446): 	at czq.run(PG:1686)
E/ExperimentLoader( 3446): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3446): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3446): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3446): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3446): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3446): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3446): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3446): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3446): 	at jdm.a(PG:77)
E/ExperimentLoader( 3446): 	... 15 more
E/ExperimentLoader( 3446): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3446): 	at fal.a(PG:38)
E/ExperimentLoader( 3446): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3446): 	... 17 more
,V/KeepSync( 3860): Connecting to GoogleApiClient
D/GCM     ( 1382): Connected
I/GCM     ( 1783): Message from null null
E/GCM     ( 1783): Dropping message from null
,I/GLSUser ( 1382): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1382): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1382): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1382): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1382): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/GCM     ( 1382): Message class com.google.f.a.a.p
,E/ClientConnectionOperation( 1783): Handling authorization failure
E/ClientConnectionOperation( 1783): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1783): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1783): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1783): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1783): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1783): 	... 7 more
,V/KeepSync( 3860): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3860): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3860): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3860): (284) automatic index on blob_node(is_deleted)
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 78604, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager(  819): Start proc 3904:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,I/GLSUser ( 1382): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1382): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1382): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1382): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1382): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1382): Explicit concurrent mark sweep GC freed 21520(1204KB) AllocSpace objects, 5(551KB) LOS objects, 38% free, 26MB/42MB, paused 685us total 21.245ms
,E/KeepSync( 3860): IOException
E/KeepSync( 3860): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3860): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3860): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3860): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3860): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3860): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3860): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3860): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3860): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3860): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3860): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3860): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3860): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3860): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3860): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3860): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3860): 	... 10 more
W/KeepSync( 3860): Sync result 2
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 78491, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,W/GAV2    ( 3904): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/BooksApp( 3904): Created application version: 3.6.8 (30608)
,I/BooksSync( 3904): Starting books sync for 61035162, extras: ade
,I/art     (  819): Explicit concurrent mark sweep GC freed 44191(1995KB) AllocSpace objects, 4(158KB) LOS objects, 32% free, 33MB/49MB, paused 1.450ms total 49.819ms
,I/BooksConfig( 3904): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1382): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1382): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1382): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1382): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1382): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1382): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1382): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1382): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1382): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1382): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3904): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3904): Soft error
E/BooksSync( 3904): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3904): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3904): Sync error
E/BooksSync( 3904): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3904): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 3904): Finished books sync
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 78995, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager(  819): Killing 3241:com.android.providers.calendar/u0a3 (adj 15): empty #17
,D/ConnectivityService(  819): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,E/WifiStateMachine(  819): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=14.81 rxSuccessRate=15.34 targetRoamBSSID=any RSSI=-48
E/WifiStateMachine(  819): WifiStateMachine L2Connected CMD_START_SCAN source -2 5, 7 -> obsolete
,I/ActivityManager(  819): Start proc 3941:com.android.providers.calendar/u0a3 for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver
,W/ResourcesManager( 3941): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/CalendarProvider2( 3941): Created com.android.providers.calendar.CalendarAlarmManager@18992df8(com.android.providers.calendar.CalendarProvider2@2b0a52d1)
,E/SQLiteLog( 3941): (284) automatic index on view_events(_id)
,D/Finsky  ( 3051): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/GLSActivity( 1382): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1382): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1382): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1382): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1382): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1382): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 3051): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1382): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1382): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1382): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1382): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1382): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1382): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,V/GLSActivity( 1382): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1382): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1382): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1382): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1382): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1382): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 3051): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,E/WifiStateMachine(  819): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=9.41 rxSuccessRate=9.17 targetRoamBSSID=any RSSI=-49
E/WifiStateMachine(  819): WifiStateMachine L2Connected CMD_START_SCAN source -2 6, 7 -> obsolete
,I/jxcore-log( 3609): Test app app.js loaded
I/jxcore-log( 3609): 
,I/chromium( 3609): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3609): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3609): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3609): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3609): 	Bluetooth MAC address: null, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3609): 	Discovery mode: BLE, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3609): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3609): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3609): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3609): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3609): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@257fe37 added. We now have 1 listener(s)
,I/jxcore-log( 3609): BLE advertisement is supported,
I/jxcore-log( 3609): ,
,V/GLSActivity( 1382): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1382): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1382): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1382): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1382): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1382): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 3051): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 3051): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 3051): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3051): [1] DailyHygiene.reschedule: Scheduling new run in 796 minutes (failures=5)
,I/ActivityManager(  819): Killing 2315:com.google.android.calendar/u0a37 (adj 15): empty #17
,D/DeviceConnectionService( 1801): client connected with version: 7571000
,I/GAV2    ( 3904): Thread[GAThread,5,main]: No campaign data found.
,I/CalendarProvider2( 3941): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 3941): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  819): Start proc 3967:com.google.android.calendar/u0a37 for broadcast com.google.android.calendar/com.android.calendar.alerts.AlertReceiver
,I/ActivityManager(  819): Killing 3489:com.google.android.gm/u0a78 (adj 15): empty #17
,E/SQLiteLog( 3967): (283) recovered 17 frames from WAL file /data/data/com.google.android.calendar/databases/timelydata.db-wal
,I/AnalyticsLogBase( 3967): PlayLogger.onLoggerConnected
,D/Finsky  ( 3051): [294] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,V/GLSActivity( 1382): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1382): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1382): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1382): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1382): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1382): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3051): [294] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,I/GAV2    ( 3967): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager(  819): Killing 2745:android.process.acore/u0a5 (adj 15): empty #17
,E/WifiStateMachine(  819): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=1.11 rxSuccessRate=2.91 targetRoamBSSID=any RSSI=-48
,V/GLSActivity( 1382): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1382): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1382): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1382): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1382): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1382): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3051): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3051): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3051): [1] 5.onFinished: Scheduling replication attempt 2.
,E/WifiStateMachine(  819): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=1.07 rxSuccessRate=2.25 targetRoamBSSID=any RSSI=-49
E/WifiStateMachine(  819): WifiStateMachine starting scan for "NG7005g"WPA_PSK with 2412,5220
,I/art     (  819): Explicit concurrent mark sweep GC freed 34380(1617KB) AllocSpace objects, 12(380KB) LOS objects, 32% free, 33MB/49MB, paused 1.456ms total 85.916ms
,D/HeadsetStateMachine( 2401): Disconnected process message: 10, size: 0
,V/GLSActivity( 1382): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1382): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1382): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1382): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1382): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1382): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3051): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3051): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3051): [1] 5.onFinished: Scheduling replication attempt 3.
,D/HeadsetStateMachine( 2401): Disconnected process message: 10, size: 0
,I/Keyboard.Facilitator.LanguageModelFlusher( 1240): run()
I/Keyboard.Facilitator( 1240): flushDynamicLanguageModels()
,I/ConfigService( 1382): onCreate
,I/ConfigService( 1382): onDestroy
,E/WifiStateMachine(  819): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.72 rxSuccessRate=3.10 targetRoamBSSID=any RSSI=-48
,I/BooksSync( 3904): Starting books sync for 61035162, extras: ade
,V/KeepSync( 3860): Connecting to GoogleApiClient
,I/BooksConfig( 3904): GmsCore Version = 7.8.99 (2134222-430)
,I/art     ( 1382): Explicit concurrent mark sweep GC freed 27940(1619KB) AllocSpace objects, 3(330KB) LOS objects, 37% free, 26MB/42MB, paused 2ms total 49.184ms
,I/GLSUser ( 1382): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1382): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1382): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1382): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1382): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1382): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1382): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1382): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1382): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1382): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1783): Handling authorization failure
E/ClientConnectionOperation( 1783): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1783): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1783): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1783): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1783): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1783): 	... 7 more
,V/KeepSync( 3860): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3860): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3860): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3860): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1382): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1382): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1382): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1382): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1382): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1382): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1382): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1382): [GLSUser] Extracting token using key: Auth,
W/GLSActivity( 1382): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,V/GLSActivity( 1382): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3904): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3904): Soft error
E/BooksSync( 3904): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3904): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3904): Sync error
E/BooksSync( 3904): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3904): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3904): Finished books sync
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 111991, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,E/KeepSync( 3860): IOException
E/KeepSync( 3860): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3860): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3860): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3860): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3860): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3860): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3860): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3860): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3860): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3860): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3860): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3860): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3860): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3860): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3860): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3860): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3860): 	... 10 more
W/KeepSync( 3860): Sync result 2
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 109815, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1382): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1382): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1382): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1382): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1382): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3446): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3446): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3446): 	,at jdm.a(PG:82)
E/HttpOperation( 3446): 	at jcs.o(PG:406)
E/HttpOperation( 3446): 	at jcn.a(PG:1379)
E/HttpOperation( 3446): 	at jcs.i(PG:143)
E/HttpOperation( 3446): 	at blb.a(PG:3937)
E/HttpOperation( 3446): 	at czp.a(PG:18188)
,E/HttpOperation( 3446): 	at czp.a(PG:9081)
E/HttpOperation( 3446): 	at czq.run(PG:1686)
E/HttpOperation( 3446): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3446): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3446): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3446): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3446): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3446): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3446): 	at jdj.a(PG:4091)
,E/HttpOperation( 3446): 	at jdj.a(PG:1125)
E/HttpOperation( 3446): 	at jdm.a(PG:77)
E/HttpOperation( 3446): 	... 12 more
E/HttpOperation( 3446): Caused by: faj: BadAuthentication
E/HttpOperation( 3446): 	at fal.a(PG:38)
E/HttpOperation( 3446): 	at jdj.a(PG:4089)
,E/HttpOperation( 3446): 	... 14 more
,I/GLSUser ( 1382): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1382): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1382): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1382): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,V/GLSActivity( 1382): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/HttpOperation( 3446): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3446): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3446): 	at jdm.a(PG:82)
E/HttpOperation( 3446): 	at jcs.o(PG:406)
E/HttpOperation( 3446): 	at jcn.a(PG:1379)
E/HttpOperation( 3446): 	at jcs.i(PG:143)
E/HttpOperation( 3446): 	at hec.a(PG:42)
E/HttpOperation( 3446): 	at hee.a(PG:102)
E/HttpOperation( 3446): 	at czr.a(PG:65)
E/HttpOperation( 3446): 	at kka.a(PG:108)
E/HttpOperation( 3446): 	at czp.a(PG:19176)
E/HttpOperation( 3446): 	at czp.a(PG:9081)
E/HttpOperation( 3446): 	at czq.run(PG:1686)
E/HttpOperation( 3446): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3446): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3446): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3446): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3446): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3446): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3446): 	at jdj.a(PG:4091)
E/HttpOperation( 3446): 	at jdj.a(PG:1125)
E/HttpOperation( 3446): 	at jdm.a(PG:77)
E/HttpOperation( 3446): 	... 15 more
E/HttpOperation( 3446): Caused by: faj: BadAuthentication
E/HttpOperation( 3446): 	at fal.a(PG:38)
E/HttpOperation( 3446): 	at jdj.a(PG:4089)
E/HttpOperation( 3446): 	... 17 more
E/ExperimentLoader( 3446): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3446): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3446): 	at jdm.a(PG:82)
E/ExperimentLoader( 3446): 	at jcs.o(PG:406)
E/ExperimentLoader( 3446): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3446): 	at jcs.i(PG:143)
E/ExperimentLoader( 3446): 	at hec.a(PG:42)
E/ExperimentLoader( 3446): 	at hee.a(PG:102)
E/ExperimentLoader( 3446): 	at czr.a(PG:65)
E/ExperimentLoader( 3446): 	at kka.a(PG:108)
E/ExperimentLoader( 3446): 	at czp.a(PG:19176)
E/ExperimentLoader( 3446): 	at czp.a(PG:9081)
E/ExperimentLoader( 3446): 	at czq.run(PG:1686)
E/ExperimentLoader( 3446): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3446): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3446): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3446): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3446): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3446): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3446): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3446): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3446): 	at jdm.a(PG:77)
E/ExperimentLoader( 3446): 	... 15 more
E/ExperimentLoader( 3446): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3446): 	at fal.a(PG:38)
E/ExperimentLoader( 3446): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3446): 	... 17 more
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 112006, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,V/GLSActivity( 1382): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1382): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1382): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1382): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1382): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1382): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3051): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3051): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3051): [1] 5.onFinished: Scheduling replication attempt 4.
,E/WifiStateMachine(  819): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.80 rxSuccessRate=3.41 targetRoamBSSID=any RSSI=-48
,E/WifiStateMachine(  819): WifiStateMachine starting scan for "NG7005g"WPA_PSK with 2412,5220
,I/PowerManagerService(  819): Going to sleep due to screen timeout (uid 1000)...
,I/Adreno  (  819): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/PermissionCache(  279): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (229 us)
,I/DisplayManagerService(  819): Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,D/SurfaceFlinger(  279): Set power mode=0, type=0 flinger=0xb6482000
,D/qdhwcomposer(  279): hwc_setPowerMode: Setting mode 0 on display: 0
V/ActivityManager(  819): Display changed displayId=0
,I/kickstart(  872): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
I/kickstart(  872): STATUS: Wrote to /sys/power/wake_lock
,E/kickstart(  872): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2
,I/kickstart(  872): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2' for writing
,I/qdhwcomposer(  279): handle_blank_event: dpy:0 panel power state: 0
,D/qdhwcomposer(  279): hwc_setPowerMode: Done setting mode 0 on display 0
,D/SurfaceControl(  819): Excessive delay in setPowerMode(): 275ms
,I/DreamManagerService(  819): Entering dreamland.
,I/DreamController(  819): Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,I/PowerManagerService(  819): Dozing...
,D/audio_hw_primary(  356): adev_set_parameters: enter: screen_state=on
D/mot_vr_audio_hw(  356): adev_set_parameters: screen_state=on
,E/WifiStateMachine(  819): cancelDelayedScan -> 12
,E/native  (  819): do suspend false
,I/Keyboard.Facilitator( 1240): onFinishInput()
,E/WifiStateMachine(  819): cancelDelayedScan -> 14
,E/native  (  819): do suspend true
D/audio_hw_primary(  356): adev_set_parameters: enter: screen_state=off
D/mot_vr_audio_hw(  356): adev_set_parameters: screen_state=off
,E/WifiStateMachine(  819): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-48
E/WifiStateMachine(  819): WifiStateMachine L2Connected CMD_START_SCAN source -2 13, 14 -> obsolete
,I/kickstart(  872): STATUS: Received file 'm9kefs2'
I/kickstart(  872): STATUS: 950272 bytes transferred in 0.993686 seconds
,I/kickstart(  872): STATUS: Successfully downloaded files from target 
I/kickstart(  872): STATUS: Wrote to /sys/power/wake_unlock
,I/kickstart(  872): STATUS: Sahara protocol completed,
,V/GLSActivity( 1382): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1382): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1382): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1382): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1382): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1382): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3051): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3051): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3051): [1] 5.onFinished: Scheduling replication attempt 5.
,E/WifiStateMachine(  819): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-48
E/WifiStateMachine(  819): WifiStateMachine L2Connected CMD_START_SCAN source -2 11, 14 -> obsolete
,V/GLSActivity( 1382): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  819): Explicit concurrent mark sweep GC freed 46690(2MB) AllocSpace objects, 13(302KB) LOS objects, 31% free, 34MB/50MB, paused 1.802ms total 71.210ms
,V/GLSActivity( 1382): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/VacuumService( 1382): Vacuum at: now=1454082702454 tag=VacuumService
,I/GLSUser ( 1382): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1382): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1382): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1382): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1382): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GoogleAuthProtoRequest( 3671): [395] a.<init>: mAccountName set to: thalitester@gmail.com
,D/Finsky  ( 3051): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3051): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3051): [1] 5.onFinished: Giving up after 6 failures.
,I/GLSUser ( 1382): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1382): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1382): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1382): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1382): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3671): [395] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3671): [395] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3671): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3671): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3671): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3671): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3671): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3671): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3671): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3671): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3671): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3671): 	at com.a.a.k.run(SourceFile:110)
,I/GoogleURLConnFactory( 1382): Using platform SSLCertificateSocketFactory
,W/Uploader( 1382): No account for auth token provided,
,W/Uploader( 1382): No account for auth token provided
,I/GLSUser ( 1382): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1382): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1382): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1382): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1382): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1382): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1382): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1382): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1382): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1382): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1382): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1382): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1382): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1382): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1382): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1382): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1382): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1382): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1382): No account for auth token provided
,W/Uploader( 1382): No account for auth token provided
,W/Uploader( 1382): No account for auth token provided
,W/Uploader( 1382): No account for auth token provided
,I/GLSUser ( 1382): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1382): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1382): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1382): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1382): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1382): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1382): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1382): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1382): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1382): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1382): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1382): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1382): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1382): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1382): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1382): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1382): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1382): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1382): No account for auth token provided
,I/GLSUser ( 1382): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1382): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1382): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1382): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1382): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1382): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1382): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1382): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1382): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1382): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1382): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1382): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1382): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1382): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1382): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1382): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1382): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1382): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1382): No account for auth token provided
,W/Uploader( 1382): No account for auth token provided
,W/Uploader( 1382): No account for auth token provided
,W/Uploader( 1382): No account for auth token provided,
,I/GLSUser ( 1382): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog,
I/GLSUser ( 1382): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1382): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1382): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,V/GLSActivity( 1382): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1382): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1382): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1382): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1382): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1382): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1382): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1382): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1382): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1382): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1382): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1382): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1382): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1382): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1382): No account for auth token provided
,W/Uploader( 1382):  no longer exists, so no auth token.
,W/Uploader( 1382): No account for auth token provided
,W/Uploader( 1382): No account for auth token provided
,I/GLSUser ( 1382): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1382): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1382): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1382): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1382): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1382): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1382): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1382): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1382): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1382): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1382): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1382): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1382): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1382): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1382): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1382): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1382): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1382): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/GLSUser ( 1382): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1382): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1382): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1382): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1382): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1382): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1382): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1382): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1382): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1382): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1382): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1382): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1382): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1382): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1382): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1382): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1382): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1382): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/art     ( 1382): Explicit concurrent mark sweep GC freed 75021(4MB) AllocSpace objects, 8(726KB) LOS objects, 36% free, 28MB/44MB, paused 1.807ms total 99.366ms
,V/KeepSync( 3860): Connecting to GoogleApiClient
,I/GLSUser ( 1382): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1382): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1382): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1382): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1382): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1783): Handling authorization failure
E/ClientConnectionOperation( 1783): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1783): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1783): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1783): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1783): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1783): 	... 7 more
,V/KeepSync( 3860): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3860): (284) automatic index on blob_node(is_deleted),
,E/SQLiteLog( 3860): (284) automatic index on blob_node(is_deleted),
,E/SQLiteLog( 3860): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1382): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1382): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1382): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1382): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1382): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3860): IOException
E/KeepSync( 3860): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3860): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3860): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3860): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3860): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3860): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3860): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3860): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3860): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3860): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3860): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3860): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3860): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3860): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3860): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3860): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3860): 	... 10 more
W/KeepSync( 3860): Sync result 2
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 199973, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,V/GoogleAuthProtoRequest( 3671): [396] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1382): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1382): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1382): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1382): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1382): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3671): [396] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3671): [396] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3671): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3671): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3671): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3671): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3671): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3671): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3671): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3671): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3671): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3671): 	at com.a.a.k.run(SourceFile:110)
,I/Keyboard.Facilitator.LanguageModelFlusher( 1240): run()
I/Keyboard.Facilitator( 1240): flushDynamicLanguageModels()
,I/ConfigService( 1382): onCreate
,I/ConfigService( 1382): onDestroy
,I/BooksSync( 3904): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3904): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1382): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1382): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1382): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1382): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1382): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  819): Explicit concurrent mark sweep GC freed 29693(1307KB) AllocSpace objects, 3(236KB) LOS objects, 31% free, 34MB/50MB, paused 2.317ms total 83.428ms
,I/GLSUser ( 1382): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1382): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1382): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1382): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1382): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3446): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3446): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3446): 	at jdm.a(PG:82)
E/HttpOperation( 3446): 	at jcs.o(PG:406)
E/HttpOperation( 3446): 	at jcn.a(PG:1379)
E/HttpOperation( 3446): 	at jcs.i(PG:143)
E/HttpOperation( 3446): 	at blb.a(PG:3937)
E/HttpOperation( 3446): 	at czp.a(PG:18188)
E/HttpOperation( 3446): 	at czp.a(PG:9081)
E/HttpOperation( 3446): 	at czq.run(PG:1686)
E/HttpOperation( 3446): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3446): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3446): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3446): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3446): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3446): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3446): 	at jdj.a(PG:4091)
E/HttpOperation( 3446): 	at jdj.a(PG:1125)
E/HttpOperation( 3446): 	at jdm.a(PG:77)
E/HttpOperation( 3446): 	... 12 more
E/HttpOperation( 3446): Caused by: faj: BadAuthentication
E/HttpOperation( 3446): 	at fal.a(PG:38)
E/HttpOperation( 3446): 	at jdj.a(PG:4089)
E/HttpOperation( 3446): 	... 14 more
,I/GLSUser ( 1382): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1382): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1382): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1382): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1382): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1382): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1382): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1382): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1382): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
E/BooksAccountManager( 3904): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,V/GLSActivity( 1382): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksSync( 3904): Soft error
E/BooksSync( 3904): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3904): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3904): Sync error
E/BooksSync( 3904): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3904): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3904): Finished books sync
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 203564, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,E/HttpOperation( 3446): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3446): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3446): 	at jdm.a(PG:82)
E/HttpOperation( 3446): 	at jcs.o(PG:406)
E/HttpOperation( 3446): 	at jcn.a(PG:1379)
E/HttpOperation( 3446): 	at jcs.i(PG:143)
E/HttpOperation( 3446): 	at hec.a(PG:42)
E/HttpOperation( 3446): 	at hee.a(PG:102)
E/HttpOperation( 3446): 	at czr.a(PG:65)
E/HttpOperation( 3446): 	at kka.a(PG:108)
E/HttpOperation( 3446): 	at czp.a(PG:19176)
E/HttpOperation( 3446): 	at czp.a(PG:9081)
E/HttpOperation( 3446): 	at czq.run(PG:1686)
E/HttpOperation( 3446): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3446): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3446): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3446): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3446): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3446): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3446): 	at jdj.a(PG:4091)
E/HttpOperation( 3446): 	at jdj.a(PG:1125)
E/HttpOperation( 3446): 	at jdm.a(PG:77)
E/HttpOperation( 3446): 	... 15 more
E/HttpOperation( 3446): Caused by: faj: BadAuthentication
E/HttpOperation( 3446): 	at fal.a(PG:38)
E/HttpOperation( 3446): 	at jdj.a(PG:4089)
E/HttpOperation( 3446): 	... 17 more
E/ExperimentLoader( 3446): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3446): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3446): 	at jdm.a(PG:82)
E/ExperimentLoader( 3446): 	at jcs.o(PG:406)
E/ExperimentLoader( 3446): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3446): 	at jcs.i(PG:143)
E/ExperimentLoader( 3446): 	at hec.a(PG:42)
E/ExperimentLoader( 3446): 	at hee.a(PG:102)
E/ExperimentLoader( 3446): 	at czr.a(PG:65)
E/ExperimentLoader( 3446): 	at kka.a(PG:108)
E/ExperimentLoader( 3446): 	at czp.a(PG:19176)
E/ExperimentLoader( 3446): 	at czp.a(PG:9081)
E/ExperimentLoader( 3446): 	at czq.run(PG:1686)
E/ExperimentLoader( 3446): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3446): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3446): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3446): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3446): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3446): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3446): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3446): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3446): 	at jdm.a(PG:77)
E/ExperimentLoader( 3446): 	... 15 more
E/ExperimentLoader( 3446): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3446): 	at fal.a(PG:38)
E/ExperimentLoader( 3446): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3446): 	... 17 more
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 204939, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2401): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2401): Disconnected process message: 10, size: 0
,I/jxcore-log( 3609): --= Surplus to requirements =--
I/jxcore-log( 3609): 
I/jxcore-log( 3609): ****TEST TOOK:  ms ****
I/jxcore-log( 3609): 
I/jxcore-log( 3609): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3609): 
,D/AndroidRuntime( 4077): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,D/AndroidRuntime( 4077): CheckJNI is OFF
,D/AndroidRuntime( 4077): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  819): Force stopping com.test.thalitest appid=10265 user=-1: uninstall pkg
I/ActivityManager(  819): Killing 3609:com.test.thalitest/u0a265 (adj 0): stop com.test.thalitest
,W/PackageSettings(  819): Skipping PackageSetting{bae381d com.example.hello/10273} due to missing metadata
,E/libprocessgroup(  819): failed to kill 1 processes for processgroup 3609
W/ActivityManager(  819): Force removing ActivityRecord{25bc6438 u0 com.test.thalitest/.MainActivity t28}: app died, no saved state
E/JavaBinder(  819): !!! FAILED BINDER TRANSACTION !!!
D/WifiService(  819): Client connection lost with reason: 4
,W/WindowManager(  819): Failed looking up window
W/WindowManager(  819): java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@38c6cc44 does not exist
W/WindowManager(  819): 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8539)
W/WindowManager(  819): 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8530)
W/WindowManager(  819): 	at com.android.server.wm.WindowState$DeathRecipient.binderDied(WindowState.java:1142)
W/WindowManager(  819): 	at android.os.BinderProxy.sendDeathNotice(Binder.java:551)
I/WindowState(  819): WIN DEATH: null
,V/ActivityManager(  819): Display changed displayId=0
,I/ActivityManager(  819): Force stopping com.test.thalitest appid=10265 user=0: pkg removed
,D/TaskPersister(  819): removeObsoleteFile: deleting file=28_task.xml
,I/InputReader(  819): Reconfiguring input devices.  changes=0x00000010
,I/Keyboard.Facilitator( 1240): resetDictionaries() : en_US
,D/BuaReceiver( 3321): ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,I/art     ( 1072): Explicit concurrent mark sweep GC freed 56398(2MB) AllocSpace objects, 0(0B) LOS objects, 18% free, 71MB/87MB, paused 1.971ms total 38.952ms
,I/art     ( 1506): Explicit concurrent mark sweep GC freed 1565(138KB) AllocSpace objects, 1(25KB) LOS objects, 22% free, 26MB/34MB, paused 8.626ms total 45.132ms
,I/Keyboard.Facilitator.DecoderInitializer( 1240): run()
,I/Decoder ( 1240): createOrResetDecoder
,I/ActivityManager(  819): Start proc 4094:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,I/art     (  819): Explicit concurrent mark sweep GC freed 15352(1022KB) AllocSpace objects, 11(835KB) LOS objects, 32% free, 33MB/49MB, paused 1.410ms total 86.528ms
I/art     (  819): WaitForGcToComplete blocked for 71.289ms for cause Explicit
,I/ConfigService( 1382): onCreate
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1240): run()
,W/InputMethodManagerService(  819): Got RemoteException sending setActive(false) notification to pid 3609 uid 10265
I/Keyboard.Facilitator( 1240): onFinishInput()
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1240): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1240): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1240): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1240): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1240): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1240): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1240): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1240): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1240): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1240): run()
,I/Keyboard.Facilitator.RecurringTaskScheduler( 1240): run()
I/StatsUtilsManager( 1240): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1240): shouldRecordStats() = Too Soon
,W/LocationOracleImpl( 1506): Best location was null
D/JobSchedulerService(  819): Receieved: android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  819): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,I/HotwordRecognitionRnr( 1506): Starting hotword detection.
,I/MicrophoneInputStream( 1506): mic_starting com.google.android.apps.gsa.speech.audio.u@1e1b3b83
,I/AudioFlinger(  356): AudioFlinger's thread 0xb4d00000 ready to run
I/art     ( 1321): Explicit concurrent mark sweep GC freed 5166(377KB) AllocSpace objects, 12(1408KB) LOS objects, 31% free, 35MB/51MB, paused 988us total 31.153ms
,I/SoundTriggerHwService::Module(  356): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,I/MicrophoneInputStream( 1506): mic_started com.google.android.apps.gsa.speech.audio.u@1e1b3b83
,D/audio_hw_primary(  356): select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
D/msm8974_platform(  356): platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
E/ACDB-LOADER(  356): Error: ACDB AudProc vol returned = -19
D/audio_hw_primary(  356): enable_snd_device: snd_device(55: voice-rec-mic)
,D/VoicemailCleanupService( 4094): Cleaning up data for package: com.test.thalitest
,D/audio_hw_primary(  356): enable_audio_route: apply and update mixer path: audio-record
,W/LocationOracleImpl( 1506): Best location was null
,I/ActivityManager(  819): Start proc 4129:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,I/art     (  819): Explicit concurrent mark sweep GC freed 6033(291KB) AllocSpace objects, 1(110KB) LOS objects, 32% free, 33MB/49MB, paused 2.276ms total 132.625ms
,I/WebViewFactory( 1506): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/HotwordWorker( 1506): onReady
,I/ActivityManager(  819): Start proc 4152:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,I/art     (  368): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 202us total 9.636ms
,I/art     (  368): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 198us total 8.729ms
,D/WifiService(  819): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@7eff07f}
I/art     (  368): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 205us total 9.222ms
E/WifiStateMachine(  819): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-48
,D/Launcher.Workspace( 1321): 11683562 - stripEmptyScreens()
,D/Launcher.Workspace( 1321): 11683562 - stripEmptyScreens()
,I/ContactLocale( 4094): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/art     ( 4077): System.exit called, status: 0
I/AndroidRuntime( 4077): VM exiting with result code 0.
,W/ContextImpl( 4152): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2609 
,I/LibraryLoader( 1506): Time to load native libraries: 1 ms (timestamps 3139-3140)
I/LibraryLoader( 1506): Expected native library version number "",actual native library version number ""
,E/NetworkScheduler.SchedulerReceiver( 1382): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1382): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,W/art     ( 1506): Attempt to remove local handle scope entry from IRT, ignoring
,V/GoogleAuthProtoRequest( 3671): [397] a.<init>: mAccountName set to: thalitester@gmail.com
,E/LocSvc_IzatApiV02(  819): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1660003603
E/LocSvc_IzatApiV02(  819): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,D/ChimeraCfgMgr( 1783): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1783): Module APK com.google.android.play.games already loaded
,D/PackageBroadcastService( 1783): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,D/AccountUtils( 1783): Clearing selected account for com.test.thalitest
,D/ChimeraCfgMgr( 1783): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1783): Module APK com.google.android.play.games already loaded
,I/UpdateIcingCorporaServi( 1506): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,W/Launcher( 1321): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@1effc410 new=com.google.android.velvet.VelvetApplication@1effc410
,I/LocationSettingsChecker( 1783): Removing dialog suppression flag for package com.test.thalitest
,W/art     ( 1506): Attempt to remove local handle scope entry from IRT, ignoring
,D/GOOGLEHELP_CompatibleDatabase( 1783): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1783): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,D/gH_MetricsDatabase( 1783): 0 metrics were deleted when clearing package com.test.thalitest.
D/GOOGLEHELP_CompatibleDatabase( 1783): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,I/ActivityManager(  819): Start proc 4189:com.google.android.apps.docs/u0a46 for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
,D/GOOGLEHELP_CompatibleDatabase( 1783): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1783): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/GOOGLEHELP_CompatibleDatabase( 1783): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/GOOGLEHELP_CompatibleDatabase( 1783): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1783): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/GOOGLEHELP_CompatibleDatabase( 1783): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
,D/GOOGLEHELP_CompatibleDatabase( 1783): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/GOOGLEHELP_CompatibleDatabase( 1783): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/GOOGLEHELP_CompatibleDatabase( 1783): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,I/art     ( 1801): Explicit concurrent mark sweep GC freed 15785(939KB) AllocSpace objects, 8(128KB) LOS objects, 37% free, 26MB/42MB, paused 987us total 31.387ms
,E/DataBuffer( 1801): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@279176f0)
,I/ConfigFetchService( 1783): onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
E/SharedPreferencesImpl( 1783): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/config_removals.xml to backup file /data/data/com.google.android.gms/shared_prefs/config_removals.xml.bak
,W/BaseAppContext( 1783): Using Auth Proxy for data requests.
,E/SQLiteLog( 1506): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/AppDataSearchHelper( 1506): Exception thrown from onTableChanged
E/AppDataSearchHelper( 1506): java.lang.RuntimeException: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AppDataSearchHelper( 1506): 	at com.google.android.gms.appdatasearch.a.a.a(AppDataSearchDbOpenHelperBase.java:343)
E/AppDataSearchHelper( 1506): 	at com.google.android.gms.appdatasearch.a.a.a(AppDataSearchDbOpenHelperBase.java:261)
E/AppDataSearchHelper( 1506): 	at com.google.android.search.core.icingsync.d.j(InternalIcingCorporaProvider.java:709)
E/AppDataSearchHelper( 1506): 	at com.google.android.search.core.icingsync.d.a(InternalIcingCorporaProvider.java:700)
E/AppDataSearchHelper( 1506): 	at com.google.android.search.core.icingsync.d.i(InternalIcingCorporaProvider.java:627)
E/AppDataSearchHelper( 1506): 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:298)
E/AppDataSearchHelper( 1506): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:328)
E/AppDataSearchHelper( 1506): 	at android.content.ContentResolver.update(ContentResolver.java:1333)
E/AppDataSearchHelper( 1506): 	at com.google.android.search.core.icingsync.e.JA(UpdateIcingCorporaService.java:408)
E/AppDataSearchHelper( 1506): 	at com.google.android.search.core.icingsync.g.aTY(UpdateIcingCorporaService.java:347)
E/AppDataSearchHelper( 1506): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:320)
E/AppDataSearchHelper( 1506): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.ba(UpdateIcingCorporaService.java:215)
E/AppDataSearchHelper( 1506): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:201)
E/AppDataSearchHelper( 1506): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AppDataSearchHelper( 1506): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AppDataSearchHelper( 1506): 	at android.os.Looper.loop(Looper.java:135)
E/AppDataSearchHelper( 1506): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/AppDataSearchHelper( 1506): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AppDataSearchHelper( 1506): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AppDataSearchHelper( 1506): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/AppDataSearchHelper( 1506): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AppDataSearchHelper( 1506): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AppDataSearchHelper( 1506): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/AppDataSearchHelper( 1506): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/AppDataSearchHelper( 1506): 	at com.google.android.gms.appdatasearch.a.a.a(AppDataSearchDbOpenHelperBase.java:661)
E/AppDataSearchHelper( 1506): 	at com.google.android.gms.appdatasearch.a.a$1.JA(AppDataSearchDbOpenHelperBase.java:246)
E/AppDataSearchHelper( 1506): 	at com.google.android.gms.appdatasearch.a.a$1.call(AppDataSearchDbOpenHelperBase.java:227)
E/AppDataSearchHelper( 1506): 	at com.google.android.gms.appdatasearch.a.a.a(AppDataSearchDbOpenHelperBase.java:341)
E/AppDataSearchHelper( 1506): 	... 16 more
W/AppDataSearchHelper( 1506): Table change notification failed for com.google.android.gms.appdatasearch.a.h@be7fd6a1
I/UpdateIcingCorporaServi( 1506): UpdateCorporaTask done [took 87 ms] updated apps [took 87 ms] 
,I/ConfigFetchService( 1783): service connected
I/PeopleContactsSync( 1783): CP2 sync disabled
I/Icing   ( 1783): doRemovePackageData com.test.thalitest
W/BaseAppContext( 1783): Using Auth Proxy for data requests.
E/SQLiteDatabase( 1783): Failed to open database '/data/data/com.google.android.gms/databases/app_state.db'.
E/SQLiteDatabase( 1783): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1783): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1783): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1783): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1783): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1783): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1783): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1783): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1783): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1783): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1783): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 1783): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 1783): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1783): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 1783): 	at com.google.android.gms.common.i.a.delete(SourceFile:272)
E/SQLiteDatabase( 1783): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
E/SQLiteDatabase( 1783): 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
E/SQLiteDatabase( 1783): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
E/SQLiteDatabase( 1783): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
E/SQLiteDatabase( 1783): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/SQLiteDatabase( 1783): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 1783): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 1783): 	at java.lang.Thread.run(Thread.java:818)
E/ClearPendingStateOp( 1783): Runtime exception while performing operation
E/ClearPendingStateOp( 1783): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/ClearPendingStateOp( 1783): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/ClearPendingStateOp( 1783): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/ClearPendingStateOp( 1783): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/ClearPendingStateOp( 1783): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/ClearPendingStateOp( 1783): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/ClearPendingStateOp( 1783): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/ClearPendingStateOp( 1783): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/ClearPendingStateOp( 1783): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/ClearPendingStateOp( 1783): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/ClearPendingStateOp( 1783): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/ClearPendingStateOp( 1783): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/ClearPendingStateOp( 1783): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/ClearPendingStateOp( 1783): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/ClearPendingStateOp( 1783): 	at com.google.android.gms.common.i.a.delete(SourceFile:272)
E/ClearPendingStateOp( 1783): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
E/ClearPendingStateOp( 1783): 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
E/ClearPendingStateOp( 1783): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
E/ClearPendingStateOp( 1783): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
E/ClearPendingStateOp( 1783): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearPendingStateOp( 1783): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearPendingStateOp( 1783): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearPendingStateOp( 1783): 	at java.lang.Thread.run(Thread.java:818)
F/ClearPendingStateOp( 1783): Killing (on development devices) due to RuntimeException
F/ClearPendingStateOp( 1783): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
F/ClearPendingStateOp( 1783): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
F/ClearPendingStateOp( 1783): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
F/ClearPendingStateOp( 1783): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
F/ClearPendingStateOp( 1783): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
F/ClearPendingStateOp( 1783): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
F/ClearPendingStateOp( 1783): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
F/ClearPendingStateOp( 1783): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
F/ClearPendingStateOp( 1783): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
F/ClearPendingStateOp( 1783): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
F/ClearPendingStateOp( 1783): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
F/ClearPendingStateOp( 1783): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
F/ClearPendingStateOp( 1783): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
F/ClearPendingStateOp( 1783): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
F/ClearPendingStateOp( 1783): 	at com.google.android.gms.common.i.a.delete(SourceFile:272)
F/ClearPendingStateOp( 1783): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
F/ClearPendingStateOp( 1783): 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
F/ClearPendingStateOp( 1783): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
F/ClearPendingStateOp( 1783): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
F/ClearPendingStateOp( 1783): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
F/ClearPendingStateOp( 1783): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
F/ClearPendingStateOp( 1783): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
F/ClearPendingStateOp( 1783): 	at java.lang.Thread.run(Thread.java:818)
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
I/GLSUser ( 1382): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1382): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1382): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1382): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1382): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/SQLiteLog( 4094): (3850) statement aborts at 22: [DELETE FROM deleted_contacts WHERE contact_deleted_timestamp < ?] disk I/O error
--------- beginning of crash
E/AndroidRuntime( 4094): FATAL EXCEPTION: ContactsProviderWorker
E/AndroidRuntime( 4094): Process: android.process.acore, PID: 4094
E/AndroidRuntime( 4094): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4094): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 4094): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 4094): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 4094): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 4094): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/AndroidRuntime( 4094): 	at com.android.providers.contacts.database.DeletedContactsTableUtil.deleteOldLogs(DeletedContactsTableUtil.java:78)
E/AndroidRuntime( 4094): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1730)
E/AndroidRuntime( 4094): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1492)
E/AndroidRuntime( 4094): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4094): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 4094): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/ExperimentUpdateService( 3671): [397] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3671): [397] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3671): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3671): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3671): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3671): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3671): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3671): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3671): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3671): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3671): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3671): 	at com.a.a.k.run(SourceFile:110)
E/DropBoxManagerService(  819): Can't write: system_app_crash
E/DropBoxManagerService(  819): java.io.FileNotFoundException: /data/system/dropbox/drop98.tmp: open failed: EROFS (Read-only file system)
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
D/OpenGLRenderer(  819): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
D/Atlas   (  819): Validating map...
I/ActivityManager(  819): Killing 3287:com.google.android.music:main/u0a66 (adj 15): empty #17
,I/OpenGLRenderer(  819): Initialized EGL, version 1.4
,D/OpenGLRenderer(  819): Enabling debug mode 0
,I/GAv4    ( 4189): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4189):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4189):   adb logcat -s GAv4
,W/GAv4    ( 4189): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,E/SharedPreferencesImpl( 4189): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4189): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,E/SharedPreferencesImpl( 4189): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/GAv4    ( 4189): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,E/SharedPreferencesImpl( 4189): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,I/HotwordDetector( 1506): Closing mic
I/MicrophoneInputStream( 1506): mic_close com.google.android.apps.gsa.speech.audio.u@1e1b3b83
,W/AnalyticsTrackerProxyImpl( 4189): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
,E/Search.SharedPreferencesProto( 1506): Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
,E/SQLiteDatabase( 4189): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 4189): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4189): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4189): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4189): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4189): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4189): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4189): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4189): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4189): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4189): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4189): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4189): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4189): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4189): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4189): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 4189): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 4189): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 4189): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 4189): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 4189): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 4189): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4189): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4189): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4189): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4189): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 4189): 	at gir$c.run(Unknown Source)
,E/GAv4    ( 4189): Opening the database failed, dropping the table and recreating it
E/SharedPreferencesImpl( 4189): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SQLiteDatabase( 4189): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 4189): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4189): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4189): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4189): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4189): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4189): 	,at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4189): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4189): ,	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4189): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4189): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4189): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4189): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4189): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4189): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4189): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 4189): 	at fdw.g(Unknown Source)
,E/SQLiteDatabase( 4189): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 4189): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 4189): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 4189): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 4189): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4189): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4189): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4189): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4189): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 4189): 	at gir$c.run(Unknown Source)
,E/GAv4    ( 4189): Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 4189): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4189): Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,E/SharedPreferencesImpl( 4189): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4189): Job execution failed: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 4189): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SQLiteDatabase( 4189): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4189): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4189): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4189): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4189): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4189): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4189): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4189): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4189): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4189): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4189): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4189): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4189): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4189): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4189): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4189): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 4189): 	at ael.a(PG:1521)
E/SQLiteDatabase( 4189): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 4189): 	at aen.run(PG:536)
,D/audio_hw_primary(  356): disable_audio_route: reset and update mixer path: audio-record
,D/audio_hw_primary(  356): disable_snd_device: snd_device(55: voice-rec-mic)
,I/SoundTriggerHwService::Module(  356): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,I/HotwordRecognitionRnr( 1506): Stopping hotword detection.
I/HotwordRecognitionRnr( 1506): Hotword detection finished
,W/GAv4    ( 4189): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4189): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4189): Job execution failed: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4189): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/GAv4    ( 4189): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4189): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SQLiteDatabase( 4189): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4189): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4189): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4189): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4189): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4189): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4189): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4189): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4189): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4189): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4189): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4189): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4189): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4189): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4189): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4189): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 4189): 	at ael.a(PG:1521)
E/SQLiteDatabase( 4189): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 4189): 	at aej.c(PG:139)
E/SQLiteDatabase( 4189): 	at aej.b(PG:398)
E/SQLiteDatabase( 4189): 	at agf.f(PG:417)
E/SQLiteDatabase( 4189): 	at oe.run(PG:1112)
E/SQLiteDatabase( 4189): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4189): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4189): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4189): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4189): 	at java.lang.Thread.run(Thread.java:818)
W/GAv4    ( 4189): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/AbstractDatabaseInstance( 4189): Failed to delete from CachedSearch133
E/AbstractDatabaseInstance( 4189): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AbstractDatabaseInstance( 4189): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AbstractDatabaseInstance( 4189): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AbstractDatabaseInstance( 4189): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AbstractDatabaseInstance( 4189): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AbstractDatabaseInstance( 4189): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AbstractDatabaseInstance( 4189): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AbstractDatabaseInstance( 4189): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AbstractDatabaseInstance( 4189): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E,/AbstractDatabaseInstance( 4189): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AbstractDatabaseInstance( 4189): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AbstractDatabaseInstance( 4189): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AbstractDatabaseInstance( 4189): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AbstractDatabaseInstance( 4189): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AbstractDatabaseInstance( 4189): 	at aev.getWritableDatabase(PG:238)
E/AbstractDatabaseInstance( 4189): 	at ael.a(PG:1521)
E/AbstractDatabaseInstance( 4189): 	at hix$a.a(PG:125)
E/AbstractDatabaseInstance( 4189): 	at aej.c(PG:139)
E/AbstractDatabaseInstance( 4189): 	at aej.b(PG:398)
E/AbstractDatabaseInstance( 4189): 	at agf.f(PG:417)
E/AbstractDatabaseInstance( 4189): 	at oe.run(PG:1112)
E/AbstractDatabaseInstance( 4189): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/AbstractDatabaseInstance( 4189): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AbstractDatabaseInstance( 4189): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AbstractDatabaseInstance( 4189): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AbstractDatabaseInstance( 4189): 	at java.lang.Thread.run(Thread.java:818)
E/SharedPreferencesImpl( 4189): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4189): Failed to commit local dispatch transaction: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4189): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4189): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4189): Error opening database: android.database.sqlite.SQLiteException: Database open failed
,W/ResourcesManager( 4189): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4189): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/GAv4    ( 4189): Sync local dispatch failed: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4189): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/GAv4    ( 4189): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4189): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SharedPreferencesImpl( 4189): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4189): syncDispatchLocalHits failed: java.util.concurrent.ExecutionException: android.database.sqlite.SQLiteException: Database open failed
,E/SharedPreferencesImpl( 4189): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/CAKEMIX_CRASHED( 4189): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/CAKEMIX_CRASHED( 4189): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/CAKEMIX_CRASHED( 4189): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/CAKEMIX_CRASHED( 4189): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/CAKEMIX_CRASHED( 4189): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/CAKEMIX_CRASHED( 4189): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/CAKEMIX_CRASHED( 4189): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/CAKEMIX_CRASHED( 4189): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/CAKEMIX_CRASHED( 4189): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/CAKEMIX_CRASHED( 4189): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/CAKEMIX_CRASHED( 4189): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/CAKEMIX_CRASHED( 4189): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/CAKEMIX_CRASHED( 4189): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/CAKEMIX_CRASHED( 4189): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/CAKEMIX_CRASHED( 4189): 	at aev.getWritableDatabase(PG:238)
E/CAKEMIX_CRASHED( 4189): 	at ael.a(PG:1521)
E/CAKEMIX_CRASHED( 4189): 	at hix$a.a(PG:125)
E/CAKEMIX_CRASHED( 4189): 	at aen.run(PG:536)
,V/JNIHelp ( 4189): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ActivityManager(  819): Start proc 4241:com.android.documentsui/u0a45 for broadcast com.android.documentsui/.PackageReceiver
,I/ActivityManager(  819): START u0 {act=android.intent.action.BUG_REPORT flg=0x10000000 cmp=com.google.android.apps.docs/.app.ErrorNotificationActivity (has extras)} from uid 10046 on display 0
V/WindowManager(  819): addAppToken: AppWindowToken{18df0f0d token=Token{5ae85a4 ActivityRecord{3a83ec37 u0 com.google.android.apps.docs/.app.ErrorNotificationActivity t29}}} to stack=1 task=29 at 0
,I/Process ( 4189): Sending signal. PID: 4189 SIG: 9
,I/ActivityManager(  819): Killing 3697:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,E/Search.SharedPreferencesProto( 1506): Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
,E/lowmemorykiller(  276): Error opening /proc/4189/oom_score_adj; errno=2
,W/ActivityManager(  819): Exception when starting activity com.google.android.apps.docs/.app.ErrorNotificationActivity
W/ActivityManager(  819): android.os.DeadObjectException
W/ActivityManager(  819): 	at android.os.BinderProxy.transactNative(Native Method)
W/ActivityManager(  819): 	at android.os.BinderProxy.transact(Binder.java:496)
W/ActivityManager(  819): 	at android.app.ApplicationThreadProxy.scheduleLaunchActivity(ApplicationThreadNative.java:797)
W/ActivityManager(  819): 	at com.android.server.am.ActivityStackSupervisor.realStartActivityLocked(ActivityStackSupervisor.java:1181)
W/ActivityManager(  819): 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1281)
W/ActivityManager(  819): 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:1891)
W/ActivityManager(  819): 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1455)
W/ActivityManager(  819): ,	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2473)
W/ActivityManager(  819): 	at com.android.server.am.ActivityStack.completePauseLocked(ActivityStack.java:998)
W/ActivityManager(  819): 	at com.android.server.am.ActivityStack.activityPausedLocked(ActivityStack.java:896)
W/ActivityManager(  819): 	at com.android.server.am.ActivityManagerService.activityPaused(ActivityManagerService.java:6311)
W/ActivityManager(  819): 	,at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:512)
W/ActivityManager(  819): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2208)
W/ActivityManager(  819): 	at android.os.Binder.execTransact(Binder.java:446)
,E/native  ( 1240): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1240): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,I/ActivityManager(  819): Start proc 4259:com.google.android.apps.docs/u0a46 for activity com.google.android.apps.docs/.app.ErrorNotificationActivity
,W/ActivityManager(  819): Spurious death for ProcessRecord{14c9b43f 4259:com.google.android.apps.docs/u0a46}, curProc for 4189: null
,W/OpenGLRenderer( 1321): Incorrectly called buildLayer on View: ew, destroying layer...
,E/native  ( 1240): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1240): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,I/ActivityManager(  819): Killing 3717:com.google.android.apps.magazines/u0a67 (adj 15): empty #17
,E/native  ( 1240): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1240): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1240): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1240): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
,E/SQLiteDatabase( 4241): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.,
E/SQLiteDatabase( 4241): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4241): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4241): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4241): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4241): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4241): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4241): ,	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4241): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4241): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4241): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4241): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4241): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4241): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4241): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4241): 	,at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/SQLiteDatabase( 4241): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/SQLiteDatabase( 4241): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:370)
E/SQLiteDatabase( 4241): 	at android.content.ContentResolver.call(ContentResolver.java:1372)
E/SQLiteDatabase( 4241): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/SQLiteDatabase( 4241): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2609)
E/SQLiteDatabase( 4241): 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
E/SQLiteDatabase( 4241): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1380)
E/SQLiteDatabase( 4241): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4241): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 4241): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
E/SQLiteDatabase( 4241): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 4241): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 4241): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
E/SQLiteDatabase( 4241): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,D/AndroidRuntime( 4241): Shutting down VM
E/AndroidRuntime( 4241): FATAL EXCEPTION: main
E/AndroidRuntime( 4241): Process: com.android.documentsui, PID: 4241
E/AndroidRuntime( 4241): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4241): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2616)
E/AndroidRuntime( 4241): 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
E/AndroidRuntime( 4241): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1380)
E/AndroidRuntime( 4241): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4241): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 4241): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
E/AndroidRuntime( 4241): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 4241): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 4241): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
E/AndroidRuntime( 4241): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
E/AndroidRuntime( 4241): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4241): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4241): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 4241): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 4241): 	,at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4241): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4241): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4241): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AndroidRuntime( 4241): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AndroidRuntime( 4241): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 4241): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AndroidRuntime( 4241): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 4241): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 4241): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 4241): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/AndroidRuntime( 4241): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/AndroidRuntime( 4241): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:370)
E/AndroidRuntime( 4241): 	at android.content.ContentResolver.call(ContentResolver.java:1372)
E/AndroidRuntime( 4241): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/AndroidRuntime( 4241): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2609)
E/AndroidRuntime( 4241): 	... 9 more
,I/ActivityManager(  819): Killing 3773:com.android.chrome/u0a40 (adj 15): empty #17
,E/DropBoxManagerService(  819): Can't write: system_app_crash
E/DropBoxManagerService(  819): java.io.FileNotFoundException: /data/system/dropbox/drop102.tmp: open failed: EROFS (Read-only file system)
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
,I/ActivityManager(  819): Start proc 4281:com.android.externalstorage/u0a10 for content provider com.android.externalstorage/.ExternalStorageProvider
,I/GAv4    ( 4259): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4259):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4259):   adb logcat -s GAv4
,I/ActivityManager(  819): Killing 3793:com.google.android.apps.photos/u0a71 (adj 15): empty #17
,W/GAv4    ( 4259): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4259): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,E/SharedPreferencesImpl( 4259): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SharedPreferencesImpl( 4259): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/GAv4    ( 4259): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,E/SharedPreferencesImpl( 4259): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SQLiteDatabase( 4259): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
,E/SQLiteDatabase( 4259): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,E/SQLiteDatabase( 4259): 	,at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4259): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209),
E/SQLiteDatabase( 4259): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4259): ,	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4259): 	,at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4259): 	,at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4259): 	,at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4259): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791),
E/SQLiteDatabase( 4259): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
,E/SQLiteDatabase( 4259): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4259): ,	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4259): 	,at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4259): 	,at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4259): 	at fdw$a.getWritableDatabase(Unknown Source),
E/SQLiteDatabase( 4259): 	at fdw.g(Unknown Source)
,E/SQLiteDatabase( 4259): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 4259): 	at fdw.e(Unknown Source),
E/SQLiteDatabase( 4259): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 4259): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 4259): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4259): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4259): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4259): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4259): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 4259): 	at gir$c.run(Unknown Source)
,E/GAv4    ( 4259): Opening the database failed, dropping the table and recreating it
E/SharedPreferencesImpl( 4259): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SQLiteDatabase( 4259): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 4259): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4259): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4259): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4259): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4259): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4259): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4259): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4259): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4259): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4259): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4259): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4259): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4259): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4259): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4259): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 4259): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 4259): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 4259): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 4259): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 4259): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 4259): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4259): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4259): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4259): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4259): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 4259): 	at gir$c.run(Unknown Source)
,E/GAv4    ( 4259): Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 4259): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4259): Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 4259): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4259): Job execution failed: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 4259): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,D/ExternalStorage( 4281): After updating volumes, found 1 active roots
,W/AnalyticsTrackerProxyImpl( 4259): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
,E/SQLiteDatabase( 4259): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4259): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4259): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4259): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4259): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4259): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4259): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4259): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4259): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4259): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4259): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4259): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4259): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4259): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4259): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4259): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 4259): 	at ael.a(PG:1521)
E/SQLiteDatabase( 4259): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 4259): 	at aen.run(PG:536)
,E/SQLiteDatabase( 4259): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4259): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4259): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4259): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4259): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4259): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4259): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4259): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4259): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4259): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4259): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4259): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4259): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4259): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4259): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4259): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 4259): 	at ael.a(PG:1521)
E/SQLiteDatabase( 4259): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 4259): 	at aej.c(PG:139)
E/SQLiteDatabase( 4259): 	at aej.b(PG:398)
E/SQLiteDatabase( 4259): 	at agf.f(PG:417)
E/SQLiteDatabase( 4259): 	at oe.run(PG:1112)
E/SQLiteDatabase( 4259): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4259): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4259): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4259): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4259): 	at java.lang.Thread.run(Thread.java:818)
,E/AbstractDatabaseInstance( 4259): Failed to delete from CachedSearch133
E/AbstractDatabaseInstance( 4259): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AbstractDatabaseInstance( 4259): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AbstractDatabaseInstance( 4259): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AbstractDatabaseInstance( 4259): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AbstractDatabaseInstance( 4259): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AbstractDatabaseInstance( 4259): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AbstractDatabaseInstance( 4259): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AbstractDatabaseInstance( 4259): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AbstractDatabaseInstance( 4259): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AbstractDatabaseInstance( 4259): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AbstractDatabaseInstance( 4259): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AbstractDatabaseInstance( 4259): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AbstractDatabaseInstance( 4259): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AbstractDatabaseInstance( 4259): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AbstractDatabaseInstance( 4259): 	,at aev.getWritableDatabase(PG:238)
E/AbstractDatabaseInstance( 4259): 	at ael.a(PG:1521)
E/AbstractDatabaseInstance( 4259): 	at hix$a.a(PG:125)
E/AbstractDatabaseInstance( 4259): 	at aej.c(PG:139)
E/AbstractDatabaseInstance( 4259): 	at aej.b(PG:398)
E/AbstractDatabaseInstance( 4259): 	at agf.f(PG:417)
E/AbstractDatabaseInstance( 4259): 	at oe.run(PG:1112)
E/AbstractDatabaseInstance( 4259): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/AbstractDatabaseInstance( 4259): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AbstractDatabaseInstance( 4259): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AbstractDatabaseInstance( 4259): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AbstractDatabaseInstance( 4259): 	at java.lang.Thread.run(Thread.java:818)
,W/ResourcesManager( 4259): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4259): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/ErrorNotificationActivity( 4259): Google Drive has stopped unexpectedly. Please provide additional details to help us diagnose the issue.
,D/WifiService(  819): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@7eff07f}
,V/JNIHelp ( 4259): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ProviderInstaller( 4259): Installed default security provider GmsCore_OpenSSL
,I/art     (  819): Explicit concurrent mark sweep GC freed 22764(1242KB) AllocSpace objects, 4(64KB) LOS objects, 31% free, 34MB/50MB, paused 1.570ms total 68.261ms,
,D/OpenGLRenderer( 4259): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,D/Atlas   ( 4259): Validating map...
,V/WindowManager(  819): Adding window Window{2fe178b3 u0 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity} at 2 of 9 (after Window{220a3a44 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
,V/WindowManager(  819): Adding window Window{213845e9 u0 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity} at 2 of 10 (before Window{2fe178b3 u0 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity})
,W/GAv4    ( 4259): Error opening database: android.database.sqlite.SQLiteException: Database open failed
,E/GAv4    ( 4259): Job execution failed: android.database.sqlite.SQLiteException: Database open failed
W/GAv4    ( 4259): Error opening database: android.database.sqlite.SQLiteException: Database open failed
W/GAv4    ( 4259): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4259): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4259): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4259): Failed to commit local dispatch transaction: android.database.sqlite.SQLiteException: Database open failed
W/GAv4    ( 4259): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/GAv4    ( 4259): Sync local dispatch failed: android.database.sqlite.SQLiteException: Database open failed
W/GAv4    ( 4259): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4259): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4259): syncDispatchLocalHits failed: java.util.concurrent.ExecutionException: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4259): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/CAKEMIX_CRASHED( 4259): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/CAKEMIX_CRASHED( 4259): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/CAKEMIX_CRASHED( 4259): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/CAKEMIX_CRASHED( 4259): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/CAKEMIX_CRASHED( 4259): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/CAKEMIX_CRASHED( 4259): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/CAKEMIX_CRASHED( 4259): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/CAKEMIX_CRASHED( 4259): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/CAKEMIX_CRASHED( 4259): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/CAKEMIX_CRASHED( 4259): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/CAKEMIX_CRASHED( 4259): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/CAKEMIX_CRASHED( 4259): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/CAKEMIX_CRASHED( 4259): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/CAKEMIX_CRASHED( 4259): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/CAKEMIX_CRASHED( 4259): 	at aev.getWritableDatabase(PG:238)
E/CAKEMIX_CRASHED( 4259): 	at ael.a(PG:1521)
E/CAKEMIX_CRASHED( 4259): 	at hix$a.a(PG:125)
E/CAKEMIX_CRASHED( 4259): 	at aen.run(PG:536)
E/SQLiteDatabase( 4259): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4259): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4259): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4259): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4259): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4259): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4259): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4259): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4259): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4259): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4259): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4259): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4259): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4259): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4259): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4259): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 4259): 	at ael.a(PG:1521)
E/SQLiteDatabase( 4259): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 4259): 	at aej.c(PG:139)
E/SQLiteDatabase( 4259): 	at aej.a(PG:358)
E/SQLiteDatabase( 4259): 	at aej.a(PG:345)
E/SQLiteDatabase( 4259): 	at agf.d(PG:281)
E/SQLiteDatabase( 4259): 	at agf.b(PG:312)
E/SQLiteDatabase( 4259): 	at agf.a(PG:221)
E/SQLiteDatabase( 4259): 	at com.google.android.apps.docs.storagebackend.StorageBackendContentProvider.queryRoots(PG:291)
E/SQLiteDatabase( 4259): 	at android.provider.DocumentsProvider.query(DocumentsProvider.java:480)
E/SQLiteDatabase( 4259): 	at android.content.Con,tentProvider.query(ContentProvider.java:966)
E/SQLiteDatabase( 4259): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:211)
E/SQLiteDatabase( 4259): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/SQLiteDatabase( 4259): 	at android.os.Binder.execTransact(Binder.java:446)
E/AbstractDatabaseInstance( 4259): Failed to query Account133 object
E/AbstractDatabaseInstance( 4259): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AbstractDatabaseInstance( 4259): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AbstractDatabaseInstance( 4259): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AbstractDatabaseInstance( 4259): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AbstractDatabaseInstance( 4259): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AbstractDatabaseInstance( 4259): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AbstractDatabaseInstance( 4259): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AbstractDatabaseInstance( 4259): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AbstractDatabaseInstance( 4259): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AbstractDatabaseInstance( 4259): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AbstractDatabaseInstance( 4259): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AbstractDatabaseInstance( 4259): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AbstractDatabaseInstance( 4259): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AbstractDatabaseInstance( 4259): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AbstractDatabaseInstance( 4259): 	at aev.getWritableDatabase(PG:238)
E/AbstractDatabaseInstance( 4259): 	at ael.a(PG:1521)
E/AbstractDatabaseInstance( 4259): 	at hix$a.a(PG:125)
E/AbstractDatabaseInstance( 4259): 	at aej.c(PG:139)
E/AbstractDatabaseInstance( 4259): 	at aej.a(PG:358)
E/AbstractDatabaseInstance( 4259): 	at aej.a(PG:345)
E/AbstractDatabaseInstance( 4259): 	at agf.d(PG:281)
E/AbstractDatabaseInstance( 4259): 	at agf.b(PG:312)
E/AbstractDatabaseInstance( 4259): 	at agf.a(PG:221)
E/AbstractDatabaseInstance( 4259): 	at com.google.android.apps.docs.storagebackend.StorageBackendContentProvider.queryRoots(PG:291)
E/AbstractDatabaseInstance( 4259): 	at android.provider.DocumentsProvider.query(DocumentsProvider.java:480)
E/AbstractDatabaseInstance( 4259): 	at android.content.ContentProvider.query(ContentProvider.java:966)
E/AbstractDatabaseInstance( 4259): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:211)
E/AbstractDatabaseInstance( 4259): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/AbstractDatabaseInstance( 4259): 	at android.os.Binder.execTransact(Binder.java:446)
E/DatabaseUtils( 4259): Writing exception to parcel
E/DatabaseUtils( 4259): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/DatabaseUtils( 4259): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/DatabaseUtils( 4259): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/DatabaseUtils( 4259): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/DatabaseUtils( 4259): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/DatabaseUtils( 4259): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/DatabaseUtils( 4259): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:17,7)
E/DatabaseUtils( 4259): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/DatabaseUtils( 4259): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/DatabaseUtils( 4259): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/DatabaseUtils( 4259): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/DatabaseUtils( 4259): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/DatabaseUtils( 4259): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/DatabaseUtils( 4259): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/DatabaseUtils( 4259): 	at aev.getWritableDatabase(PG:238)
E/DatabaseUtils( 4259): 	at ael.a(PG:1521)
E/DatabaseUtils( 4259): 	at hix$a.a(PG:125)
E/DatabaseUtils( 4259): 	at aej.c(PG:139)
E/DatabaseUtils( 4259): 	at aej.a(PG:358)
E/DatabaseUtils( 4259): 	at aej.a(PG:345)
E/DatabaseUtils( 4259): 	at agf.d(PG:281)
E/DatabaseUtils( 4259): 	at agf.b(PG:312)
E/DatabaseUtils( 4259): 	at agf.a(PG:221)
E/DatabaseUtils( 4259): 	at com.google.android.apps.docs.storagebackend.StorageBackendContentProvider.queryRoots(PG:291)
E/DatabaseUtils( 4259): 	at android.provider.DocumentsProvider.query(DocumentsProvider.java:480)
E/DatabaseUtils( 4259): 	at android.content.ContentProvider.query(ContentProvider.java:966)
E/DatabaseUtils( 4259): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:211)
E/DatabaseUtils( 4259): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/DatabaseUtils( 4259): 	at android.os.Binder.execTransact(Binder.java:446)
E/SharedPreferencesImpl( 4259): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4259): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4259): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4259): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4259): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4259): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SQLiteDatabase( 4259): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4259): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4259): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4259): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4259): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4259): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4259): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4259): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4259): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4259): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4259): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4259): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4259): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4259): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4259): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4259): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 4259): 	at ael.a(PG:1521)
E/SQLiteDatabase( 4259): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 4259): 	at aej.c(PG:139)
E/SQLiteDatabase( 4259): 	at aej.a(PG:358)
E/SQLiteDatabase( 4259): 	at aej.a(PG:345)
E/SQLiteDatabase( 4259): 	at agf.c(PG:884)
E/SQLiteDatabase( 4259): 	at aii.doInBackground(PG:1063)
E/SQLiteDatabase( 4259): 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
E/SQLiteDatabase( 4259): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4259): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4259): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4259): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4259): 	at java.lang.Thread.run(Thread.java:818)
E/AbstractDatabaseInstance( 4259): Failed to query Account133 object
E/AbstractDatabaseInstance( 4259): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AbstractDatabaseInstance( 4259): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AbstractDatabaseInstance( 4259): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AbstractDatabaseInstance( 4259): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AbstractDatabaseInstance( 4259): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AbstractDatabaseInstance( 4259): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AbstractDatabaseInstance( 4259): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AbstractDatabaseInstance( 4259): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AbstractDatabaseInstance( 4259): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AbstractDatabaseInstance( 4259): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AbstractDatabaseInstance( 4259): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AbstractDatabaseInstance( 4259): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AbstractDatabaseInstance( 4259): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AbstractDatabaseInstance( 4259): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AbstractDatabaseInstance( 4259): 	at aev.getWritableDatabase(PG:238)
E/AbstractDatabaseInstance( 4259): 	at ael.a(PG:1521)
E/AbstractDatabaseInstance( 4259): 	at hix$a.a(PG:125)
E/AbstractDatabaseInstance( 4259): 	at aej.c(PG:139)
E/AbstractDatabaseInstance( 4259): 	at aej.a(PG:358)
E/AbstractDatabaseInstance( 4259): 	at aej.a(PG:345)
E/AbstractDatabaseInstance( 4259): 	at agf.c(PG:884)
E/AbstractDatabaseInstance( 4259): 	at aii.doInBackground(PG:1063)
E/AbstractDatabaseInstance( 4259): 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
E/AbstractDatabaseInstance( 4259): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AbstractDatabaseInstance( 4259): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/AbstractDatabaseInstance( 4259): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AbstractDatabaseInstance( 4259): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AbstractDatabaseInstance( 4259): 	at java.lang.Thread.run(Thread.java:818)
W/Documents( 4241): Failed to load some roots from com.google.android.apps.docs.storage: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
D/Documents( 4241): Update found 6 roots in 791ms
W/GAv4    ( 4259): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4259): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4259): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4259): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4259): Failed to commit local dispatch transaction: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4259): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4259): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4259): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4259): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4259): Local dispatch failed: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4259): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4259): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4259): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4259): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4259): Job execution failed: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4259): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
I/ActivityManager(  819): START u0 {act=android.intent.action.BUG_REPORT flg=0x10000000 cmp=com.google.android.apps.docs/.app.ErrorNotificationActivity (has extras)} from uid 10046 on display 0
W/GAv4    ( 4259): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4259): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4259): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4259): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4259): Failed to commit local dispatch transaction: android.database.sqlite.SQLiteException: Database open failed
I/Process ( 4259): Sending signal. PID: 4259 SIG: 9
,I/WindowState(  819): WIN DEATH: Window{2fe178b3 u0 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity}
,I/WindowState(  819): WIN DEATH: Window{213845e9 u0 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity}
,I/ActivityManager(  819): Process com.google.android.apps.docs (pid 4259) has died
,W/ActivityManager(  819): Force removing ActivityRecord{3a83ec37 u0 com.google.android.apps.docs/.app.ErrorNotificationActivity t29}: app died, no saved state
,E/SQLiteDatabase( 1382): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 1382): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1382): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1382): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1382): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1382): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1382): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1382): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1382): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1382): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1382): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1382): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 1382): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 1382): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 1382): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1382): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 1382): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:99)
E/SQLiteDatabase( 1382): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/SQLiteDatabase( 1382): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/SQLiteDatabase( 1382): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/SQLiteDatabase( 1382): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 1382): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 1382): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteOpenHelper( 1382): Couldn't open phenotype.db for writing (will try read-only):
E/SQLiteOpenHelper( 1382): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1382): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1382): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 1382): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 1382): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1382): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1382): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1382): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteOpenHelper( 1382): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteOpenHelper( 1382): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 1382): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteOpenHelper( 1382): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 1382): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 1382): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 1382): 	at android.databa,se.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 1382): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:99)
E/SQLiteOpenHelper( 1382): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/SQLiteOpenHelper( 1382): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/SQLiteOpenHelper( 1382): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/SQLiteOpenHelper( 1382): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteOpenHelper( 1382): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteOpenHelper( 1382): 	at java.lang.Thread.run(Thread.java:818)
,W/SQLiteOpenHelper( 1382): Opened phenotype.db in read-only mode
E/SQLiteLog( 1382): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
,E/ClearcutLoggerIntentService( 1382): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1382): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1382): 	,at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1382): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1382): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1382): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1382): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1382): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1382): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1382): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1382): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1382): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1382): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1382): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1382): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 1382): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1382): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1382): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1382): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1382): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1382): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1382): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1382): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1382): 	,at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1382): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1382): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1382): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1382): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1382): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1382): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1382): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 1382): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1382): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1382): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1382): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1382): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1382): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1382): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1382): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1382): 	,at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1382): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1382): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1382): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1382): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1382): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1382): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1382): 	,at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1382): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1382): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1382): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1382): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1382): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1382): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1382): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1382): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1382): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1382): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1382): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1382): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1382): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1382): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1382): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1382): 	at java.lang.Thread.run(Thread.java:818)
,E/Search.SharedPreferencesProto( 1506): Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
,I/EventLogService( 1783): Opted in for usage reporting
I/EventLogService( 1783): Aggregate from 1454080999577 (log), 1454080999577 (data)
,W/EventLogAggregator( 1783): Unknown tag: snet_gcore
W/EventLogAggregator( 1783): Unknown tag: snet_launch_service
,E/DropBoxManagerService(  819): Can't write: event_log
E/DropBoxManagerService(  819): java.io.FileNotFoundException: /data/system/dropbox/drop45.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  819): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  819): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  819): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  819): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  819): 	at com.android.internal.os.IDropBoxManagerService$Stub.onTransact(IDropBoxManagerService.java:62)
E/DropBoxManagerService(  819): 	at android.os.Binder.execTransact(Binder.java:446)
E/DropBoxManagerService(  819): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  819): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  819): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  819): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  819): 	... 5 more
,E/DropBoxManagerService(  819): Can't write: event_data
E/DropBoxManagerService(  819): java.io.FileNotFoundException: /data/system/dropbox/drop14.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  819): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  819): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  819): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  819): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  819): 	at com.android.internal.os.IDropBoxManagerService$Stub.onTransact(IDropBoxManagerService.java:62)
E/DropBoxManagerService(  819): 	at android.os.Binder.execTransact(Binder.java:446)
E/DropBoxManagerService(  819): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  819): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  819): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  819): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  819): 	... 5 more
,E/SharedPreferencesImpl( 1783): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/EventLogService.xml to backup file /data/data/com.google.android.gms/shared_prefs/EventLogService.xml.bak,
,E/ServiceDumpSys( 1783): Can't dump service: account
E/ServiceDumpSys( 1783): java.io.FileNotFoundException: /data/data/com.google.android.gms/files/dump.tmp: open failed: EROFS (Read-only file system)
E/ServiceDumpSys( 1783): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/ServiceDumpSys( 1783): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/ServiceDumpSys( 1783): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/ServiceDumpSys( 1783): 	at com.google.android.gms.checkin.ak.a(SourceFile:63)
E/ServiceDumpSys( 1783): 	at com.google.android.gms.checkin.ah.a(SourceFile:201)
E/ServiceDumpSys( 1783): 	at com.google.android.gms.checkin.ah.doInBackground(SourceFile:173)
E/ServiceDumpSys( 1783): 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
E/ServiceDumpSys( 1783): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ServiceDumpSys( 1783): 	at java.lang.Thread.run(Thread.java:818)
E/ServiceDumpSys( 1783): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/ServiceDumpSys( 1783): 	at libcore.io.Posix.open(Native Method)
E/ServiceDumpSys( 1783): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/ServiceDumpSys( 1783): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/ServiceDumpSys( 1783): 	... 8 more
,E/SharedPreferencesImpl( 1783): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/EventLogService.xml to backup file /data/data/com.google.android.gms/shared_prefs/EventLogService.xml.bak
,I/ConfigService( 1382): onDestroy
,E/QMI_FW  (  819): xport_send: Sendto failed for port 4352
,E/LocSvc_api_v02(  819): E/locClientSendReq:2446]: send_msg_sync error: -1
E/LocSvc_IzatApiV02(  819): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 11, ind.status = -1660003603
E/LocSvc_IzatApiV02(  819): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
E/QMI_FW  (  819): xport_send: Sendto failed for port 4352
E/LocSvc_api_v02(  819): E/locClientSendReq:2446]: send_msg_sync error: -1
,E/LocSvc_IzatApiV02(  819): E/virtual int izat_core::IzatApiV02::injectLocation(GpsExtLocation):857]: error! inject position failed
E/QMI_FW  (  819): xport_send: Sendto failed for port 4352
E/LocSvc_api_v02(  819): E/locClientSendReq:2446]: send_msg_sync error: -1
E/LocSvc_ApiV02(  819): E/virtual loc_api_adapter_err LocApiV02::injectPosition(double, double, float):565]: error! status = eLOC_CLIENT_FAILURE_INTERNAL, inject_pos_ind.status = eQMI_LOC_SUCCESS_V02
E/QMI_FW  (  819): xport_send: Sendto failed for port 4352
E/LocSvc_api_v02(  819): E/locClientSendReq:2446]: send_msg_sync error: -1
,E/LocSvc_ApiV02(  819): E/virtual loc_api_adapter_err LocApiV02::injectPosition(double, double, float):565]: error! status = eLOC_CLIENT_FAILURE_INTERNAL, inject_pos_ind.status = eQMI_LOC_SUCCESS_V02
E/kickstart(  872): ERROR: function: rx_data:288 Read/Write File descriptor returned error: No such device, error code -1
E/kickstart(  872): ERROR: function: sahara_main:1143 Sahara protocol error
,E/kickstart(  872): ERROR: function: main:268 Uploading  Image using Sahara protocol failed
I/kickstart(  872): STATUS: Wrote to /sys/power/wake_unlock
I/qdhwcomposer(  279): handle_blank_event: dpy:0 panel power state: 0

```
