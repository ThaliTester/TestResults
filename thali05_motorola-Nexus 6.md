#### Test 57924002d5e0b14_thali05_motorola-Nexus 6 Logs


```
--------- beginning of main
I/CheckinService( 1776): Done disabling old GoogleServicesFramework version
,D/AndroidRuntime( 3617): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 3617): CheckJNI is OFF
D/AndroidRuntime( 3617): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  819): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/WindowManager(  819): addAppToken: AppWindowToken{1709a4e7 token=Token{1a94c2a6 ActivityRecord{5ccd401 u0 com.test.thalitest/.MainActivity t28}}} to stack=1 task=28 at 0
D/AndroidRuntime( 3617): Shutting down VM
I/MicrophoneInputStream( 1517): mic_close com.google.android.apps.gsa.speech.audio.u@3e3a5c58
I/HotwordDetector( 1517): Closing mic
V/WindowManager(  819): Adding window Window{39eda00 u0 Starting com.test.thalitest} at 2 of 7 (after Window{a0ececd u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
I/ActivityManager(  819): Start proc 3631:com.test.thalitest/u0a265 for activity com.test.thalitest/.MainActivity
D/audio_hw_primary(  358): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  358): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  358): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1517): Hotword detection finished
I/HotwordRecognitionRnr( 1517): Stopping hotword detection.
I/ActivityManager(  819): Killing 3220:com.google.android.apps.photos/u0a71 (adj 15): empty #17
E/LocSvc_IzatApiV02(  819): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1659151635
E/LocSvc_IzatApiV02(  819): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,I/WebViewFactory( 3631): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3631): Time to load native libraries: 5 ms (timestamps 2137-2142)
,I/LibraryLoader( 3631): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3631): Binding Chromium to main looper Looper (main, tid 1) {337f0eea}
,I/LibraryLoader( 3631): Expected native library version number "",actual native library version number ""
I/chromium( 3631): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3631): Initializing chromium process, singleProcess=true
,W/art     ( 3631): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3631): ApplicationContext is null in ApplicationStatus
,W/chromium( 3631): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3631): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3631): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3631): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/BluetoothManagerService(  819): Message: 20
D/BluetoothManagerService(  819): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@56dfce2:true
,W/art     ( 3631): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3631): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3631): CordovaWebView is running on device made by: motorola
,W/art     ( 3631): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3631): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3631): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,D/Atlas   ( 3631): Validating map...
,V/WindowManager(  819): Adding window Window{14d36292 u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{39eda00 u0 Starting com.test.thalitest})
,W/chromium( 3631): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3631): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3631): Enabling debug mode 0
,I/ActivityManager(  819): Displayed com.test.thalitest/.MainActivity: +770ms
,I/Keyboard.Facilitator( 1216): onFinishInput()
,W/BindingManager( 3631): Cannot call determinedVisibility() - never saw a connection for the pid: 3631
,D/JsMessageQueue( 3631): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3631): JniHelper::setJavaVM(0xb489d200), pthread_self() = -1576400896
,I/chromium( 3631): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 3631): Initializing JXcore engine
W/jxcore-log( 3631): JXcore engine is ready
,W/Thread-402( 3685): type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[13048]" dev="sockfs" ino=13048 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/Thread-402( 3685): type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-402( 3685): type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[9853]" dev="sockfs" ino=9853 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-402( 3685): type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[22629]" dev="sockfs" ino=22629 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 3631): Starting JXcore engine
,I/ActivityManager(  819): Waited long enough for: ServiceRecord{3759fd01 u0 com.motorola.android.buacontactadapter/.AuthenticationService}
,W/jxcore-log( 3631): Platform android,
W/jxcore-log( 3631): 
W/jxcore-log( 3631): Process ARCH arm,
W/jxcore-log( 3631): 
,I/jxcore-log( 3631): JXcore Cordova bridge is ready!
I/jxcore-log( 3631): 
W/jxcore-log( 3631): JXcore engine is started
,I/jxcore-log( 3631): Toggling radios to true
,I/jxcore-log( 3631): 
,D/BluetoothAdapter( 3631): enable(): BT is already enabled..!,
,D/WifiService(  819): setWifiEnabled: true pid=3631, uid=10265
E/WifiService(  819): Invoking mWifiStateMachine.setWifiEnabled
D/WifiService(  819): New client listening to asynchronous messages
,I/jxcore-log( 3631): Radios toggled,
,I/jxcore-log( 3631): ,
I/jxcore-log( 3631): My device name is: motorola-Nexus 6
I/jxcore-log( 3631): 
,I/wpa_supplicant( 1187): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  819): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  819): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  354): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1489): Read error: ssl=0xaec97e00: I/O error during system call, Connection timed out
,D/ConnectivityService(  819): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  819): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
V/NativeCrypto( 1489): SSL shutdown failed: ssl=0xaec97e00: I/O error during system call, Broken pipe
,D/ConnectivityService(  819): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10011
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  819): ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  819): DefaultState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  819): Forcing reevaluation
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  819): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  819): Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
,E/WifiStateMachine(  819): Start Disconnecting Watchdog 1
E/WifiStateMachine(  819): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  819): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
,D/CommandListener(  354): Clearing all IP addresses on wlan0
,D/ConnectivityService(  819): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler( 1066): CM callback handler got msg 524292
,D/CSLegacyTypeTracker(  819): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  819): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  819): OfflineState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  819): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  819): Disconnected - quitting
D/ConnectivityService(  819): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/WifiNetworkAgent(  819): NetworkAgent: NetworkAgent channel lost
,E/WifiStateMachine(  819): CMD_AUTO_CONNECT sup state CompletedState my state DisconnectedState nid=0 roam=3
E/WifiStateMachine(  819): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=0
,D/PhoneInterfaceManager( 1261): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1261): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/ConnectivityService(  819): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/Tethering(  819): MasterInitialState.processMessage what=3
D/TelephonyManager(  819): getDataEnabled: retVal=false
,D/NetworkChangeNotifierAutoDetect( 1517): Network connectivity changed, type is: 6
,D/ConnectivityService(  819): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/NetworkMonitor( 3313): type=WIFI subType= reason=null isConnected=false
,D/ConnectivityService(  819): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/Tethering(  819): MasterInitialState.processMessage what=3
E/ConnectivityService(  819): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/ConnectivityService(  819): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
,E/WifiConfigStore(  819): Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiConfigStore(  819): will read network variables netId=0
,E/WifiStateMachine(  819): CMD_AUTO_CONNECT did save config ->  nid=0
,E/WifiConfigStore(  819): will read network variables netId=0
,V/MusicLeanback( 3313): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,E/GpsLocationProvider(  819): No APN found to select.
,D/PhoneInterfaceManager( 1261): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1261): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
D/TelephonyManager(  819): getDataEnabled: retVal=false
,I/ActivityManager(  819): Start proc 3693:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.steen.receiver.ConnectivityChangeReceiver
E/GpsLocationProvider(  819): No APN found to select.
,I/art     (  369): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 323us total 14.614ms
,I/art     (  369): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 329us total 16.396ms
,I/art     (  369): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 332us total 13.672ms
,I/ActivityManager(  819): Start proc 3719:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
I/ActivityManager(  819): Killing 3019:com.google.android.apps.fitness/u0a51 (adj 15): empty #17
,D/SprintDMReceiver( 3719): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3719): simOperator:  IMSI: null
,D/SprintDMReceiver( 3719): Not Sprint UICC, don't do anything.
,I/ActivityManager(  819): Killing 3267:com.android.settings/1000 (adj 15): empty #17
,I/SystemUpdateService( 1776): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1776): onCreate
,D/SystemUpdateService( 1776): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1776): active receiver: enabled
,I/SystemUpdateService( 1776): showing system update notification
,I/iu.Environment( 1776): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1776): num queued entries: 0
I/iu.UploadsManager( 1776): num updated entries: 0
I/iu.SyncManager( 1776): NEXT; no task
,D/ChimeraCfgMgr( 1776): Loading module com.google.android.gms.kids from APK com.google.android.gms
,V/SystemUpdateService( 1776): retry (wakeup: false) in 3599964 ms
I/ValidateNoPeople(  819): skipping global notification
,D/SystemUpdateService( 1776): onDestroy,
,I/ActivityManager(  819): Start proc 3739:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
I/Babel   ( 2971): connection state changed from UNKNOWN to DISCONNECTED
,I/GAv4    ( 3739): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3739):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3739):   adb logcat -s GAv4
,W/GAv4    ( 3739): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3739): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3739): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.,
,I/WebViewFactory( 3739): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3739): Time to load native libraries: 1 ms (timestamps 6236-6237)
I/LibraryLoader( 3739): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3739): Binding Chromium to main looper Looper (main, tid 1) {8249fd9}
,I/LibraryLoader( 3739): Expected native library version number "",actual native library version number ""
,I/chromium( 3739): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3739): Initializing chromium process, singleProcess=true
W/art     ( 3739): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3739): ApplicationContext is null in ApplicationStatus
,W/chromium( 3739): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3739): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3739): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3739): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,W/AudioManagerAndroid( 3739): Requires BLUETOOTH permission
,I/NSApplication( 3739): Starting up...
,I/art     ( 1489): Explicit concurrent mark sweep GC freed 22962(1125KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 661us total 21.605ms
,I/ActivityManager(  819): Start proc 3795:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,I/ActivityManager(  819): Killing 3285:com.google.android.apps.maps/u0a65 (adj 15): empty #17
,I/ActivityManager(  819): Start proc 3817:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,I/ActivityManager(  819): Killing 3374:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,I/wpa_supplicant( 1187): wlan0: Trying to associate with SSID 'NG7005g'
,V/MusicLeanback( 3313): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/SprintDMReceiver( 3719): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3719): simOperator:  IMSI: null
D/SprintDMReceiver( 3719): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1776): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1776): onCreate
,D/SystemUpdateService( 1776): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1776): active receiver: enabled
,I/SystemUpdateService( 1776): showing system update notification
,D/ChimeraCfgMgr( 1776): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/ValidateNoPeople(  819): skipping global notification
,V/SystemUpdateService( 1776): retry (wakeup: false) in 3599978 ms
,D/SystemUpdateService( 1776): onDestroy
,I/wpa_supplicant( 1187): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 1187): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1187): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=0 id_str=]
,D/ConnectivityService(  819): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} }
E/WifiConfigStore(  819): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  819): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  819): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  354): Setting iface cfg
,E/WifiStateMachine(  819): Start Dhcp Watchdog 2
,E/WifiStateMachine(  819):  WifiLinkLayerStats: 
E/WifiStateMachine(  819):  my bss beacon rx: 189
E/WifiStateMachine(  819):  RSSI mgmt: -52
E/WifiStateMachine(  819):  BE :  rx=167 tx=156 lost=0 retries=0
E/WifiStateMachine(  819):  BK :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  819):  VI :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  819):  VO :  rx=7 tx=0 lost=0 retries=0
E/WifiStateMachine(  819):  on_time : 8623 tx_time=152 rx_time=299 scan_time=0
,D/ConnectivityService(  819): updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/native  (  819): do suspend false
,E/WifiStateMachine(  819): scanCount==0 - aborting,
,I/art     (  819): Explicit concurrent mark sweep GC freed 36511(1768KB) AllocSpace objects, 6(190KB) LOS objects, 32% free, 33MB/49MB, paused 1.450ms total 51.214ms
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3061): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3061): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3061): [1] 5.onFinished: Scheduling replication attempt 1.
,I/ActivityManager(  819): Killing 3394:com.android.musicfx/u0a18 (adj 15): empty #17
,I/dhcpcd  ( 3849): version 5.5.6 starting
,I/dhcpcd  ( 3849): wlan0: rebinding lease of 192.168.1.122
,I/dhcpcd  ( 3849): wlan0: acknowledged 192.168.1.122 from 192.168.1.1
,I/dhcpcd  ( 3849): wlan0: leased 192.168.1.122 for 86400 seconds
,I/jxcore-log( 3631): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 3631): 
,I/ActivityManager(  819): Killing 3152:com.google.android.gm.exchange/u0a77 (adj 15): empty #17
,I/ActivityManager(  819): Killing 3448:com.google.android.apps.docs/u0a46 (adj 15): empty #18
,D/ConnectivityService(  819): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  819): Adding iface wlan0 to network 101,
,E/WifiStateMachine(  819): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  819): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  819): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  819): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
D/ConnectivityService(  819): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  819): Setting Dns servers for network 101 to [/192.168.1.1]
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
D/CSLegacyTypeTracker(  819): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  819): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 1066): CM callback handler got msg 524290
,D/ConnectivityService(  819): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  819): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 3313): type=WIFI subType= reason=null isConnected=true
,D/NetworkChangeNotifierAutoDetect( 1517): Network connectivity changed, type is: 2
,V/MusicLeanback( 3313): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/PhoneInterfaceManager( 1261): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1261): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
D/TelephonyManager(  819): getDataEnabled: retVal=false
,I/jxcore-log( 3631): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 3631): 
,E/GpsLocationProvider(  819): No APN found to select.
D/SprintDMReceiver( 3719): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3719): simOperator:  IMSI: null
D/SprintDMReceiver( 3719): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1776): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1776): onCreate
,D/SystemUpdateService( 1776): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1776): active receiver: enabled
,I/SystemUpdateService( 1776): showing system update notification
,I/jxcore-log( 3631): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 3631): 
,I/jxcore-log( 3631): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
I/jxcore-log( 3631): 
,I/jxcore-log( 3631): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 3631): 
,I/ActivityManager(  819): Start proc 3883:com.google.android.keep/u0a79 for service com.google.android.keep/.syncadapter.KeepSyncAdapterService
,I/ValidateNoPeople(  819): skipping global notification
,I/iu.Environment( 1776): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
I/iu.UploadsManager( 1776): num queued entries: 0
I/iu.UploadsManager( 1776): num updated entries: 0
I/iu.SyncManager( 1776): NEXT; no task
,D/ChimeraCfgMgr( 1776): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 1776): Loading module com.google.android.gms.kids from APK com.google.android.gms
,V/SystemUpdateService( 1776): retry (wakeup: false) in 3599907 ms
,D/SystemUpdateService( 1776): onDestroy
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Kids    ( 1776): [AccountUtils] Account not ready
W/Kids    ( 1776): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 1776): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 1776): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 1776): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 1776): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 1776): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 1776): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 1776): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 1776): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 1776): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 1776): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 1776): 	at java.lang.Thread.run(Thread.java:818)
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/Babel   ( 2971): connection state changed from DISCONNECTED to CONNECTED
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/HttpOperation( 3489): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3489): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3489): 	at jdm.a(PG:82)
E/HttpOperation( 3489): 	at jcs.o(PG:406)
E/HttpOperation( 3489): 	at jcn.a(PG:1379)
E/HttpOperation( 3489): 	at jcs.i(PG:143)
E/HttpOperation( 3489): 	at blb.a(PG:3937)
E/HttpOperation( 3489): 	at czp.a(PG:18188)
E/HttpOperation( 3489): 	at czp.a(PG:9081)
E/HttpOperation( 3489): 	at czq.run(PG:1686)
E/HttpOperation( 3489): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3489): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3489): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3489): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3489): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3489): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3489): 	at jdj.a(PG:4091)
E/HttpOperation( 3489): 	at jdj.a(PG:1125)
E/HttpOperation( 3489): 	at jdm.a(PG:77)
E/HttpOperation( 3489): 	... 12 more
E/HttpOperation( 3489): Caused by: faj: BadAuthentication
E/HttpOperation( 3489): 	at fal.a(PG:38)
E/HttpOperation( 3489): 	at jdj.a(PG:4089)
E/HttpOperation( 3489): 	... 14 more
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3489): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3489): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3489): 	at jdm.a(PG:82)
E/HttpOperation( 3489): 	at jcs.o(PG:406)
E/HttpOperation( 3489): 	at jcn.a(PG:1379)
E/HttpOperation( 3489): 	at jcs.i(PG:143)
E/HttpOperation( 3489): 	at hec.a(PG:42)
E/HttpOperation( 3489): 	at hee.a(PG:102)
E/HttpOperation( 3489): 	at czr.a(PG:65)
E/HttpOperation( 3489): 	at kka.a(PG:108)
E/HttpOperation( 3489): 	at czp.a(PG:19176)
E/HttpOperation( 3489): 	at czp.a(PG:9081)
E/HttpOperation( 3489): 	at czq.run(PG:1686)
E/HttpOperation( 3489): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3489): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3489): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3489): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3489): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3489): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3489): 	at jdj.a(PG:4091)
E/HttpOperation( 3489): 	at jdj.a(PG:1125)
E/HttpOperation( 3489): 	at jdm.a(PG:77)
E/HttpOperation( 3489): 	... 15 more
E/HttpOperation( 3489): Caused by: faj: BadAuthentication
E/HttpOperation( 3489): 	at fal.a(PG:38)
E/HttpOperation( 3489): 	at jdj.a(PG:4089)
E/HttpOperation( 3489): 	... 17 more
,E/ExperimentLoader( 3489): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3489): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3489): 	at jdm.a(PG:82)
E/ExperimentLoader( 3489): 	at jcs.o(PG:406)
E/ExperimentLoader( 3489): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3489): 	at jcs.i(PG:143)
E/ExperimentLoader( 3489): 	at hec.a(PG:42)
E/ExperimentLoader( 3489): 	at hee.a(PG:102)
E/ExperimentLoader( 3489): 	at czr.a(PG:65)
E/ExperimentLoader( 3489): 	at kka.a(PG:108)
E/ExperimentLoader( 3489): 	at czp.a(PG:19176)
E/ExperimentLoader( 3489): 	at czp.a(PG:9081)
E/ExperimentLoader( 3489): 	at czq.run(PG:1686)
E/ExperimentLoader( 3489): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3489): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3489): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3489): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3489): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3489): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3489): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3489): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3489): 	at jdm.a(PG:77)
E/ExperimentLoader( 3489): 	... 15 more
E/ExperimentLoader( 3489): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3489): 	at fal.a(PG:38)
E/ExperimentLoader( 3489): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3489): 	... 17 more
D/GCM     ( 1489): Connected
D/ConnectivityService(  819): reportInetCondition: type=1 ok, revalidate
D/ConnectivityService(  819): reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10011
D/ConnectivityService(  819): reportInetCondition: type=1 ok, revalidate
D/ConnectivityService(  819): reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10011
D/GCM     ( 1489): Message class com.google.f.a.a.p
D/ConnectivityService(  819): reportInetCondition: type=1 ok, revalidate
D/ConnectivityService(  819): reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10011
,V/KeepSync( 3883): Connecting to GoogleApiClient
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1776): Handling authorization failure
E/ClientConnectionOperation( 1776): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1776): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1776): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1776): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1776): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1776): 	... 7 more
,V/KeepSync( 3883): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3883): (284) automatic index on blob_node(is_deleted)
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  819): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 02 Feb 2016 19:17:33 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454440653965], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454440653624]}
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  819): Validated
D/ConnectivityService(  819): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  819): ValidatedState{ when=-80ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  819): DefaultState{ when=-80ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  819): Validated NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  819): Forcing reevaluation
D/ConnectivityService(  819): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  819): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  819): EvaluatingState{ when=-74ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  819): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  819): EvaluatingState{ when=-73ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  819): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  819): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
D/ConnectivityService(  819): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 1066): CM callback handler got msg 524290
,E/SQLiteLog( 3883): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3883): (284) automatic index on blob_node(is_deleted)
,V/Herrevad( 1776): NQAS connected
D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 78560, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3883): IOException
E/KeepSync( 3883): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3883): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3883): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3883): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3883): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3883): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3883): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3883): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3883): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3883): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3883): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3883): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3883): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3883): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3883): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3883): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3883): 	... 10 more
W/KeepSync( 3883): Sync result 2
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  819): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 02 Feb 2016 19:17:34 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454440654081], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454440653968]}
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  819): Validated
,D/ConnectivityService(  819): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/ConnectivityService(  819): Validated NetworkAgentInfo [WIFI () - 101]
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 79315, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/art     ( 1489): Explicit concurrent mark sweep GC freed 21479(1207KB) AllocSpace objects, 5(551KB) LOS objects, 37% free, 26MB/42MB, paused 1.124ms total 22.748ms
,D/ConnectivityService(  819): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,E/WifiStateMachine(  819): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=14.94 rxSuccessRate=13.00 targetRoamBSSID=any RSSI=-50
E/WifiStateMachine(  819): WifiStateMachine L2Connected CMD_START_SCAN source -2 5, 7 -> obsolete
,I/jxcore-log( 3631): Test app app.js loaded
I/jxcore-log( 3631): 
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3631): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3631): ,	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3631): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3631): 	Bluetooth MAC address: F8:CF:C5:D9:E5:61, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3631): 	Discovery mode: BLE_AND_WIFI, ,
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3631): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3631): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3631): 	Advertise TX power level: 1, ,
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3631): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3631): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15a83c90 added. We now have 1 listener(s)
,I/jxcore-log( 3631): BLE advertisement is supported
I/jxcore-log( 3631): 
,I/chromium( 3631): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,E/WifiStateMachine(  819): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=10.97 rxSuccessRate=11.50 targetRoamBSSID=any RSSI=-52
,E/WifiStateMachine(  819): WifiStateMachine L2Connected CMD_START_SCAN source -2 6, 7 -> obsolete
,D/Finsky  ( 3061): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 3061): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  819): Explicit concurrent mark sweep GC freed 40848(1910KB) AllocSpace objects, 3(48KB) LOS objects, 32% free, 33MB/49MB, paused 1.474ms total 100.613ms
,W/Finsky  ( 3061): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 3061): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 3061): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 3061): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3061): [1] DailyHygiene.reschedule: Scheduling new run in 270 minutes (failures=4)
,I/ActivityManager(  819): Killing 2740:android.process.acore/u0a5 (adj 15): empty #17
D/DeviceConnectionService( 1803): client connected with version: 7571000
,E/WifiStateMachine(  819): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=1.56 rxSuccessRate=4.77 targetRoamBSSID=any RSSI=-52
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3061): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3061): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3061): [1] 5.onFinished: Scheduling replication attempt 2.
,I/ActivityManager(  819): Start proc 3941:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,W/GAV2    ( 3941): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/BooksApp( 3941): Created application version: 3.6.8 (30608)
,I/BooksSync( 3941): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3941): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3941): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3941): Soft error
E/BooksSync( 3941): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3941): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3941): Sync error
E/BooksSync( 3941): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3941): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 3941): Finished books sync
,I/ActivityManager(  819): Killing 2308:com.google.android.calendar/u0a37 (adj 15): empty #17
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 82043, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/HttpOperation( 3489): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3489): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3489): 	at jdm.a(PG:82)
E/HttpOperation( 3489): 	at jcs.o(PG:406)
E/HttpOperation( 3489): 	at jcn.a(PG:1379)
E/HttpOperation( 3489): 	at jcs.i(PG:143)
E/HttpOperation( 3489): 	at blb.a(PG:3937)
E/HttpOperation( 3489): 	at czp.a(PG:18188)
E/HttpOperation( 3489): 	at czp.a(PG:9081)
E/HttpOperation( 3489): 	at czq.run(PG:1686)
E/HttpOperation( 3489): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3489): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3489): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3489): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3489): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3489): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3489): 	at jdj.a(PG:4091)
E/HttpOperation( 3489): 	at jdj.a(PG:1125)
E/HttpOperation( 3489): 	at jdm.a(PG:77)
E/HttpOperation( 3489): 	... 12 more
E/HttpOperation( 3489): Caused by: faj: BadAuthentication
E/HttpOperation( 3489): 	at fal.a(PG:38)
E/HttpOperation( 3489): 	at jdj.a(PG:4089)
E/HttpOperation( 3489): 	... 14 more
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3489): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3489): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3489): 	at jdm.a(PG:82)
E/HttpOperation( 3489): 	at jcs.o(PG:406)
E/HttpOperation( 3489): 	at jcn.a(PG:1379)
E/HttpOperation( 3489): 	at jcs.i(PG:143)
E/HttpOperation( 3489): 	at hec.a(PG:42)
E/HttpOperation( 3489): 	at hee.a(PG:102)
E/HttpOperation( 3489): 	at czr.a(PG:65)
E/HttpOperation( 3489): 	at kka.a(PG:108)
E/HttpOperation( 3489): 	at czp.a(PG:19176)
E/HttpOperation( 3489): 	at czp.a(PG:9081)
E/HttpOperation( 3489): 	at czq.run(PG:1686)
E/HttpOperation( 3489): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3489): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3489): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3489): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3489): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3489): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3489): 	at jdj.a(PG:4091)
E/HttpOperation( 3489): 	at jdj.a(PG:1125)
E/HttpOperation( 3489): 	at jdm.a(PG:77)
E/HttpOperation( 3489): 	... 15 more
E/HttpOperation( 3489): Caused by: faj: BadAuthentication
E/HttpOperation( 3489): 	at fal.a(PG:38)
E/HttpOperation( 3489): 	at jdj.a(PG:4089)
E/HttpOperation( 3489): 	... 17 more
,E/ExperimentLoader( 3489): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token,
E/ExperimentLoader( 3489): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3489): 	at jdm.a(PG:82)
E/ExperimentLoader( 3489): 	at jcs.o(PG:406)
E/ExperimentLoader( 3489): ,	at jcn.a(PG:1379)
E/ExperimentLoader( 3489): 	at jcs.i(PG:143)
E/ExperimentLoader( 3489): 	at hec.a(PG:42)
E/ExperimentLoader( 3489): 	at hee.a(PG:102)
E/ExperimentLoader( 3489): 	at czr.a(PG:65)
E/ExperimentLoader( 3489): 	at kka.a(PG:108)
E/ExperimentLoader( 3489): 	at czp.a(PG:19176)
E/ExperimentLoader( 3489): 	at czp.a(PG:9081)
E/ExperimentLoader( 3489): 	at czq.run(PG:1686),
,E/ExperimentLoader( 3489): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422),
E/ExperimentLoader( 3489): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3489): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3489): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3489): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3489): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3489): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3489): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3489): 	at jdm.a(PG:77)
E/ExperimentLoader( 3489): 	... 15 more
E/ExperimentLoader( 3489): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3489): 	at fal.a(PG:38)
E/ExperimentLoader( 3489): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3489): 	... 17 more
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 110346, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,V/KeepSync( 3883): Connecting to GoogleApiClient
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1489): Explicit concurrent mark sweep GC freed 25588(1629KB) AllocSpace objects, 6(661KB) LOS objects, 37% free, 26MB/42MB, paused 1.462ms total 62.853ms
,E/ClientConnectionOperation( 1776): Handling authorization failure
E/ClientConnectionOperation( 1776): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1776): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1776): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1776): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1776): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1776): 	... 7 more
,V/KeepSync( 3883): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3883): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3883): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3883): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/KeepSync( 3883): IOException
E/KeepSync( 3883): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3883): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3883): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3883): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3883): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3883): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3883): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3883): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3883): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3883): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3883): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3883): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3883): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3883): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3883): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3883): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3883): 	... 10 more
W/KeepSync( 3883): Sync result 2
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 111291, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/GAV2    ( 3941): Thread[GAThread,5,main]: No campaign data found.
,E/WifiStateMachine(  819): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=1.21 rxSuccessRate=2.20 targetRoamBSSID=any RSSI=-52
E/WifiStateMachine(  819): WifiStateMachine starting scan for "NG7005g"WPA_PSK with 2412,5220
,D/Finsky  ( 3061): [294] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,I/art     (  819): Explicit concurrent mark sweep GC freed 36286(1645KB) AllocSpace objects, 15(428KB) LOS objects, 31% free, 34MB/50MB, paused 2.823ms total 94.336ms
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3061): [294] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,D/HeadsetStateMachine( 2399): Disconnected process message: 10, size: 0
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3061): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3061): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3061): [1] 5.onFinished: Scheduling replication attempt 3.
,D/HeadsetStateMachine( 2399): Disconnected process message: 10, size: 0
,I/Keyboard.Facilitator.LanguageModelFlusher( 1216): run()
I/Keyboard.Facilitator( 1216): flushDynamicLanguageModels()
,I/ConfigService( 1489): onCreate
,I/ConfigService( 1489): onDestroy
,E/WifiStateMachine(  819): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.38 rxSuccessRate=2.54 targetRoamBSSID=any RSSI=-51
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure,
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/Finsky  ( 3061): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3061): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3061): [1] 5.onFinished: Scheduling replication attempt 4.
,E/WifiStateMachine(  819): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.85 rxSuccessRate=3.34 targetRoamBSSID=any RSSI=-51
E/WifiStateMachine(  819): WifiStateMachine starting scan for "NG7005g"WPA_PSK with 2412,5220
,I/PowerManagerService(  819): Going to sleep due to screen timeout (uid 1000)...
,I/Adreno  (  819): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d,
,D/PermissionCache(  258): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (368 us)
,D/SurfaceFlinger(  258): Set power mode=0, type=0 flinger=0xb6482000
D/qdhwcomposer(  258): hwc_setPowerMode: Setting mode 0 on display: 0
,I/DisplayManagerService(  819): Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager(  819): Display changed displayId=0
,I/kickstart(  869): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
I/kickstart(  869): STATUS: Wrote to /sys/power/wake_lock
,E/kickstart(  869): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1
,I/kickstart(  869): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1' for writing
,I/qdhwcomposer(  258): handle_blank_event: dpy:0 panel power state: 0
,D/qdhwcomposer(  258): hwc_setPowerMode: Done setting mode 0 on display 0
,D/SurfaceControl(  819): Excessive delay in setPowerMode(): 271ms
,I/DreamManagerService(  819): Entering dreamland.
,I/PowerManagerService(  819): Dozing...
,I/DreamController(  819): Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,D/audio_hw_primary(  358): adev_set_parameters: enter: screen_state=on
D/mot_vr_audio_hw(  358): adev_set_parameters: screen_state=on
,E/WifiStateMachine(  819): cancelDelayedScan -> 12
,E/native  (  819): do suspend false
,I/Keyboard.Facilitator( 1216): onFinishInput()
,D/audio_hw_primary(  358): adev_set_parameters: enter: screen_state=off
D/mot_vr_audio_hw(  358): adev_set_parameters: screen_state=off
,E/WifiStateMachine(  819): cancelDelayedScan -> 14
,E/native  (  819): do suspend true
,E/WifiStateMachine(  819): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-51
E/WifiStateMachine(  819): WifiStateMachine L2Connected CMD_START_SCAN source -2 13, 14 -> obsolete
,I/kickstart(  869): STATUS: Received file 'm9kefs1'
I/kickstart(  869): STATUS: 950272 bytes transferred in 0.994511 seconds
,I/kickstart(  869): STATUS: Successfully downloaded files from target 
I/kickstart(  869): STATUS: Wrote to /sys/power/wake_unlock
,I/kickstart(  869): STATUS: Sahara protocol completed
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3061): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3061): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3061): [1] 5.onFinished: Scheduling replication attempt 5.
,I/BooksSync( 3941): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3941): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3941): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3941): Soft error,
E/BooksSync( 3941): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3941): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3941): Sync error
E/BooksSync( 3941): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3941): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 3941): Finished books sync
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 142500, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,E/WifiStateMachine(  819): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-51
,E/WifiStateMachine(  819): WifiStateMachine L2Connected CMD_START_SCAN source -2 11, 14 -> obsolete
,D/HeadsetStateMachine( 2399): Disconnected process message: 10, size: 0
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1489): Vacuum at: now=1454440761165 tag=VacuumService
,V/GoogleAuthProtoRequest( 3693): [395] a.<init>: mAccountName set to: thalitester@gmail.com
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GoogleURLConnFactory( 1489): Using platform SSLCertificateSocketFactory
,D/HeadsetStateMachine( 2399): Disconnected process message: 10, size: 0
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3693): [395] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3693): [395] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3693): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3693): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3693): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3693): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3693): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3693): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3693): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3693): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3693): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3693): 	at com.a.a.k.run(SourceFile:110)
,D/Finsky  ( 3061): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3061): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3061): [1] 5.onFinished: Giving up after 6 failures.
,I/art     (  819): Explicit concurrent mark sweep GC freed 48171(2MB) AllocSpace objects, 11(364KB) LOS objects, 31% free, 34MB/50MB, paused 2.246ms total 93.238ms
,I/GoogleURLConnFactory( 1489): Using platform SSLCertificateSocketFactory
,W/Uploader( 1489): No account for auth token provided
,W/Uploader( 1489): No account for auth token provided
,W/Uploader( 1489): No account for auth token provided
,W/Uploader( 1489): No account for auth token provided
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1489): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1489): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1489): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1489): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1489): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1489): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1489): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1489): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1489): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1489): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1489): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1489): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1489): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1489): No account for auth token provided
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1489): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1489): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1489): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1489): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1489): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1489): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1489): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1489): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1489): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1489): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1489): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1489): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1489): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1489): No account for auth token provided
,W/Uploader( 1489): No account for auth token provided
,W/Uploader( 1489): No account for auth token provided
,W/Uploader( 1489): No account for auth token provided
,W/Uploader( 1489): No account for auth token provided
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1489): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1489): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1489): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1489): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1489): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1489): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1489): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1489): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1489): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1489): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1489): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1489): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1489): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1489): No account for auth token provided
,W/Uploader( 1489):  no longer exists, so no auth token.
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1489): Explicit concurrent mark sweep GC freed 73577(4MB) AllocSpace objects, 17(1217KB) LOS objects, 36% free, 27MB/43MB, paused 2.016ms total 62.853ms,
,E/Uploader( 1489): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1489): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1489): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1489): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1489): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1489): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1489): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1489): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1489): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1489): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1489): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1489): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1489): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1489): No account for auth token provided
,W/Uploader( 1489): No account for auth token provided
,V/KeepSync( 3883): Connecting to GoogleApiClient
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3489): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3489): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3489): 	at jdm.a(PG:82)
E/HttpOperation( 3489): 	at jcs.o(PG:406)
E/HttpOperation( 3489): 	at jcn.a(PG:1379)
E/HttpOperation( 3489): 	at jcs.i(PG:143)
E/HttpOperation( 3489): 	at blb.a(PG:3937)
E/HttpOperation( 3489): 	at czp.a(PG:18188)
E/HttpOperation( 3489): 	at czp.a(PG:9081)
E/HttpOperation( 3489): 	at czq.run(PG:1686)
E/HttpOperation( 3489): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3489): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3489): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3489): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3489): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3489): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3489): 	at jdj.a(PG:4091)
E/HttpOperation( 3489): 	at jdj.a(PG:1125)
E/HttpOperation( 3489): 	at jdm.a(PG:77)
E/HttpOperation( 3489): 	... 12 more
E/HttpOperation( 3489): Caused by: faj: BadAuthentication
E/HttpOperation( 3489): 	at fal.a(PG:38)
E/HttpOperation( 3489): 	at jdj.a(PG:4089)
E/HttpOperation( 3489): 	... 14 more
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1776): Handling authorization failure
E/ClientConnectionOperation( 1776): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1776): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1776): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1776): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1776): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1776): 	... 7 more
,V/KeepSync( 3883): GoogleApiClient failed to connect with error code: 4,
,E/SQLiteLog( 3883): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
E/SQLiteLog( 3883): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3883): (284) automatic index on blob_node(is_deleted)
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3489): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3489): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3489): 	at jdm.a(PG:82)
E/HttpOperation( 3489): 	at jcs.o(PG:406)
E/HttpOperation( 3489): 	at jcn.a(PG:1379)
E/HttpOperation( 3489): 	at jcs.i(PG:143)
E/HttpOperation( 3489): 	at hec.a(PG:42)
E/HttpOperation( 3489): 	at hee.a(PG:102)
E/HttpOperation( 3489): 	at czr.a(PG:65)
E/HttpOperation( 3489): 	at kka.a(PG:108)
E/HttpOperation( 3489): 	at czp.a(PG:19176)
E/HttpOperation( 3489): 	at czp.a(PG:9081)
E/HttpOperation( 3489): 	at czq.run(PG:1686)
E/HttpOperation( 3489): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3489): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3489): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3489): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3489): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3489): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3489): 	at jdj.a(PG:4091)
E/HttpOperation( 3489): 	at jdj.a(PG:1125)
E/HttpOperation( 3489): 	at jdm.a(PG:77)
E/HttpOperation( 3489): 	... 15 more
E/HttpOperation( 3489): Caused by: faj: BadAuthentication
E/HttpOperation( 3489): 	at fal.a(PG:38)
E/HttpOperation( 3489): 	at jdj.a(PG:4089)
E/HttpOperation( 3489): 	... 17 more
E/ExperimentLoader( 3489): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3489): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3489): 	at jdm.a(PG:82)
E/ExperimentLoader( 3489): 	at jcs.o(PG:406)
E/ExperimentLoader( 3489): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3489): 	at jcs.i(PG:143)
E/ExperimentLoader( 3489): 	at hec.a(PG:42)
E/ExperimentLoader( 3489): 	at hee.a(PG:102)
E/ExperimentLoader( 3489): 	at czr.a(PG:65)
E/ExperimentLoader( 3489): 	at kka.a(PG:108)
E/ExperimentLoader( 3489): 	at czp.a(PG:19176)
E/ExperimentLoader( 3489): 	at czp.a(PG:9081)
E/ExperimentLoader( 3489): 	at czq.run(PG:1686)
E/ExperimentLoader( 3489): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3489): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3489): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3489): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3489): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3489): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3489): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3489): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3489): 	at jdm.a(PG:77)
E/ExperimentLoader( 3489): 	... 15 more
E/ExperimentLoader( 3489): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3489): 	at fal.a(PG:38)
E/ExperimentLoader( 3489): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3489): 	... 17 more
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3883): IOException
E/KeepSync( 3883): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3883): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3883): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3883): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3883): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3883): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3883): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3883): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3883): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3883): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3883): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3883): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3883): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3883): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3883): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3883): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3883): 	... 10 more
W/KeepSync( 3883): Sync result 2
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 173824, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 171609, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,V/GoogleAuthProtoRequest( 3693): [396] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3693): [396] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3693): [396] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3693): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3693): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3693): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3693): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3693): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3693): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3693): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3693): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3693): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3693): 	at com.a.a.k.run(SourceFile:110)
,I/Keyboard.Facilitator.LanguageModelFlusher( 1216): run()
I/Keyboard.Facilitator( 1216): flushDynamicLanguageModels()
,I/ConfigService( 1489): onCreate
,I/ConfigService( 1489): onDestroy
,D/HeadsetStateMachine( 2399): Disconnected process message: 10, size: 0,
,D/HeadsetStateMachine( 2399): Disconnected process message: 10, size: 0
,I/BooksSync( 3941): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3941): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3941): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication,
,E/BooksSync( 3941): Soft error,
E/BooksSync( 3941): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3941): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3941): Sync error
E/BooksSync( 3941): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3941): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 3941): Finished books sync,
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 233707, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1],
,D/HeadsetStateMachine( 2399): Disconnected process message: 10, size: 0
,I/art     (  819): Explicit concurrent mark sweep GC freed 33206(1452KB) AllocSpace objects, 4(158KB) LOS objects, 31% free, 34MB/50MB, paused 1.396ms total 88.809ms
,V/GoogleAuthProtoRequest( 3693): [397] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3693): [397] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3693): [397] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3693): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3693): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3693): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3693): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3693): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3693): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3693): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3693): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3693): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3693): 	at com.a.a.k.run(SourceFile:110)
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3489): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3489): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3489): 	at jdm.a(PG:82)
E/HttpOperation( 3489): 	at jcs.o(PG:406)
E/HttpOperation( 3489): 	at jcn.a(PG:1379)
E/HttpOperation( 3489): 	at jcs.i(PG:143)
E/HttpOperation( 3489): 	at blb.a(PG:3937)
E/HttpOperation( 3489): 	at czp.a(PG:18188)
E/HttpOperation( 3489): 	at czp.a(PG:9081)
E/HttpOperation( 3489): 	at czq.run(PG:1686)
E/HttpOperation( 3489): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3489): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3489): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3489): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3489): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3489): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3489): 	at jdj.a(PG:4091)
E/HttpOperation( 3489): 	at jdj.a(PG:1125)
E/HttpOperation( 3489): 	at jdm.a(PG:77)
E/HttpOperation( 3489): 	... 12 more
E/HttpOperation( 3489): Caused by: faj: BadAuthentication
E/HttpOperation( 3489): 	at fal.a(PG:38)
E/HttpOperation( 3489): 	at jdj.a(PG:4089)
E/HttpOperation( 3489): 	... 14 more
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3489): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3489): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3489): 	at jdm.a(PG:82)
E/HttpOperation( 3489): 	at jcs.o(PG:406)
E/HttpOperation( 3489): 	at jcn.a(PG:1379)
E/HttpOperation( 3489): 	at jcs.i(PG:143)
E/HttpOperation( 3489): 	at hec.a(PG:42)
E/HttpOperation( 3489): 	at hee.a(PG:102)
E/HttpOperation( 3489): 	at czr.a(PG:65)
E/HttpOperation( 3489): 	at kka.a(PG:108)
E/HttpOperation( 3489): 	at czp.a(PG:19176)
E/HttpOperation( 3489): 	at czp.a(PG:9081)
E/HttpOperation( 3489): 	at czq.run(PG:1686)
E/HttpOperation( 3489): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3489): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3489): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3489): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3489): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3489): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3489): 	at jdj.a(PG:4091)
E/HttpOperation( 3489): 	at jdj.a(PG:1125)
E/HttpOperation( 3489): 	at jdm.a(PG:77)
E/HttpOperation( 3489): 	... 15 more
E/HttpOperation( 3489): Caused by: faj: BadAuthentication
E/HttpOperation( 3489): 	at fal.a(PG:38)
E/HttpOperation( 3489): 	at jdj.a(PG:4089)
E/HttpOperation( 3489): 	... 17 more
E/ExperimentLoader( 3489): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3489): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3489): 	at jdm.a(PG:82)
E/ExperimentLoader( 3489): 	at jcs.o(PG:406)
E/ExperimentLoader( 3489): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3489): 	at jcs.i(PG:143)
E/ExperimentLoader( 3489): 	at hec.a(PG:42)
E/ExperimentLoader( 3489): 	at hee.a(PG:102)
E/ExperimentLoader( 3489): 	at czr.a(PG:65)
E/ExperimentLoader( 3489): 	at kka.a(PG:108)
E/ExperimentLoader( 3489): 	at czp.a(PG:19176)
E/ExperimentLoader( 3489): 	at czp.a(PG:9081)
E/ExperimentLoader( 3489): 	at czq.run(PG:1686)
E/ExperimentLoader( 3489): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3489): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3489): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3489): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3489): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3489): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3489): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3489): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3489): 	at jdm.a(PG:77)
E/ExperimentLoader( 3489): 	... 15 more
E/ExperimentLoader( 3489): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3489): 	at fal.a(PG:38)
E/ExperimentLoader( 3489): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3489): 	... 17 more
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 320583, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,V/KeepSync( 3883): Connecting to GoogleApiClient
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1776): Handling authorization failure
E/ClientConnectionOperation( 1776): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1776): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1776): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1776): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1776): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1776): 	... 7 more
,V/KeepSync( 3883): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3883): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3883): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3883): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3883): IOException
E/KeepSync( 3883): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3883): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3883): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3883): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3883): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3883): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3883): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3883): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3883): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3883): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3883): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3883): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3883): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3883): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3883): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3883): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3883): 	... 10 more
W/KeepSync( 3883): Sync result 2
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 323961, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/WifiService(  819): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@29b92fc5}
,E/WifiStateMachine(  819): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-51
,D/WifiService(  819): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@29b92fc5}
,E/LocSvc_IzatApiV02(  819): E/virtual int izat_core::IzatApiV02::injectLocation(GpsExtLocation):857]: error! inject position failed
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1489): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1489): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1489): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1489): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1489): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1489): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1489): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 3061): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3061): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3061): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 3061): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3061): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/PlayEventLogger( 3061): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3061): 	at android.os.Binder.execTransact(Binder.java:446)
,I/art     ( 1489): Explicit concurrent mark sweep GC freed 52532(2MB) AllocSpace objects, 14(1469KB) LOS objects, 36% free, 27MB/43MB, paused 1.510ms total 41.934ms
,W/System  ( 3061): Ignoring header User-Agent because its value was null.
,D/HeadsetStateMachine( 2399): Disconnected process message: 10, size: 0,
,D/HeadsetStateMachine( 2399): Disconnected process message: 10, size: 0
,I/BooksSync( 3941): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3941): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books,
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3941): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3941): Soft error
E/BooksSync( 3941): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3941): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3941): Sync error
E/BooksSync( 3941): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3941): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3941): Finished books sync
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 387072, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2399): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2399): Disconnected process message: 10, size: 0,
,V/GoogleAuthProtoRequest( 3693): [398] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3693): [398] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3693): [398] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3693): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3693): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3693): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3693): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3693): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3693): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3693): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3693): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3693): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3693): 	at com.a.a.k.run(SourceFile:110)
,I/art     (  819): Explicit concurrent mark sweep GC freed 34445(1573KB) AllocSpace objects, 16(821KB) LOS objects, 31% free, 34MB/50MB, paused 1.927ms total 55.165ms
,D/HeadsetStateMachine( 2399): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2399): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2399): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2399): Disconnected process message: 10, size: 0
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth,
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3489): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3489): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3489): 	at jdm.a(PG:82)
E/HttpOperation( 3489): 	at jcs.o(PG:406)
E/HttpOperation( 3489): 	at jcn.a(PG:1379)
E/HttpOperation( 3489): 	at jcs.i(PG:143)
E/HttpOperation( 3489): 	at blb.a(PG:3937)
E/HttpOperation( 3489): 	at czp.a(PG:18188)
E/HttpOperation( 3489): 	at czp.a(PG:9087)
E/HttpOperation( 3489): 	at czq.run(PG:1686)
E/HttpOperation( 3489): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3489): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3489): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3489): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3489): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3489): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3489): 	at jdj.a(PG:4091)
E/HttpOperation( 3489): 	at jdj.a(PG:1125)
E/HttpOperation( 3489): 	at jdm.a(PG:77)
E/HttpOperation( 3489): 	... 12 more
E/HttpOperation( 3489): Caused by: faj: BadAuthentication
E/HttpOperation( 3489): 	at fal.a(PG:38)
E/HttpOperation( 3489): 	at jdj.a(PG:4089)
E/HttpOperation( 3489): 	... 14 more
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3489): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3489): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3489): 	at jdm.a(PG:82)
E/HttpOperation( 3489): 	at jcs.o(PG:406)
E/HttpOperation( 3489): 	at jcn.a(PG:1379)
E/HttpOperation( 3489): 	at jcs.i(PG:143)
E/HttpOperation( 3489): 	at blb.a(PG:3937)
E/HttpOperation( 3489): 	at czp.a(PG:18188)
E/HttpOperation( 3489): 	at czp.a(PG:9081)
E/HttpOperation( 3489): 	at czq.run(PG:1686)
E/HttpOperation( 3489): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3489): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3489): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3489): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3489): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3489): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3489): 	at jdj.a(PG:4091)
E/HttpOperation( 3489): 	at jdj.a(PG:1125)
E/HttpOperation( 3489): 	at jdm.a(PG:77)
E/HttpOperation( 3489): 	... 12 more
E/HttpOperation( 3489): Caused by: faj: BadAuthentication
E/HttpOperation( 3489): 	at fal.a(PG:38)
E/HttpOperation( 3489): 	at jdj.a(PG:4089)
E/HttpOperation( 3489): 	... 14 more
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3489): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3489): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3489): 	at jdm.a(PG:82)
E/HttpOperation( 3489): 	at jcs.o(PG:406)
E/HttpOperation( 3489): 	at jcn.a(PG:1379)
E/HttpOperation( 3489): 	at jcs.i(PG:143)
E/HttpOperation( 3489): 	at hec.a(PG:42)
E/HttpOperation( 3489): 	at hee.a(PG:102)
E/HttpOperation( 3489): 	at czr.a(PG:65)
E/HttpOperation( 3489): 	at kka.a(PG:108)
E/HttpOperation( 3489): 	at czp.a(PG:19176)
E/HttpOperation( 3489): 	at czp.a(PG:9081)
E/HttpOperation( 3489): 	at czq.run(PG:1686)
E/HttpOperation( 3489): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3489): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3489): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3489): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3489): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3489): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3489): 	at jdj.a(PG:4091)
E/HttpOperation( 3489): 	at jdj.a(PG:1125)
E/HttpOperation( 3489): 	at jdm.a(PG:77)
E/HttpOperation( 3489): 	... 15 more
E/HttpOperation( 3489): Caused by: faj: BadAuthentication
E/HttpOperation( 3489): 	at fal.a(PG:38)
E/HttpOperation( 3489): 	at jdj.a(PG:4089)
E/HttpOperation( 3489): 	... 17 more
,E/ExperimentLoader( 3489): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3489): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3489): 	at jdm.a(PG:82)
E/ExperimentLoader( 3489): 	at jcs.o(PG:406)
E/ExperimentLoader( 3489): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3489): 	,at jcs.i(PG:143)
E/ExperimentLoader( 3489): 	at hec.a(PG:42)
E/ExperimentLoader( 3489): 	at hee.a(PG:102)
E/ExperimentLoader( 3489): 	at czr.a(PG:65)
E/ExperimentLoader( 3489): 	at kka.a(PG:108)
E/ExperimentLoader( 3489): 	at czp.a(PG:19176)
E/ExperimentLoader( 3489): 	,at czp.a(PG:9081)
E/ExperimentLoader( 3489): 	at czq.run(PG:1686)
E/ExperimentLoader( 3489): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3489): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3489): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3489): ,	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3489): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3489): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3489): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3489): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3489): 	at jdm.a(PG:77)
E/ExperimentLoader( 3489): 	... 15 more
E/ExperimentLoader( 3489): Caused by: faj: BadAuthentication
,E/ExperimentLoader( 3489): 	at fal.a(PG:38)
E/ExperimentLoader( 3489): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3489): 	... 17 more
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 321222, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2399): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2399): Disconnected process message: 10, size: 0
,V/KeepSync( 3883): Connecting to GoogleApiClient
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1776): Handling authorization failure
E/ClientConnectionOperation( 1776): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1776): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1776): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1776): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1776): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1776): 	... 7 more
,V/KeepSync( 3883): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3883): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3883): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3883): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3489): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3489): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3489): 	at jdm.a(PG:82)
E/HttpOperation( 3489): 	at jcs.o(PG:406)
E/HttpOperation( 3489): 	at jcn.a(PG:1379)
E/HttpOperation( 3489): 	at jcs.i(PG:143)
E/HttpOperation( 3489): 	at blb.a(PG:3937)
E/HttpOperation( 3489): 	at czp.a(PG:18188)
E/HttpOperation( 3489): 	at czp.a(PG:9081)
E/HttpOperation( 3489): 	at czq.run(PG:1686)
E/HttpOperation( 3489): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3489): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3489): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3489): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3489): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3489): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3489): 	at jdj.a(PG:4091)
E/HttpOperation( 3489): 	at jdj.a(PG:1125)
E/HttpOperation( 3489): 	at jdm.a(PG:77)
E/HttpOperation( 3489): 	... 12 more
E/HttpOperation( 3489): Caused by: faj: BadAuthentication
E/HttpOperation( 3489): 	at fal.a(PG:38)
E/HttpOperation( 3489): 	at jdj.a(PG:4089)
E/HttpOperation( 3489): 	... 14 more
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3489): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3489): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3489): 	at jdm.a(PG:82)
E/HttpOperation( 3489): 	at jcs.o(PG:406)
E/HttpOperation( 3489): 	at jcn.a(PG:1379)
E/HttpOperation( 3489): 	at jcs.i(PG:143)
E/HttpOperation( 3489): 	at hec.a(PG:42)
E/HttpOperation( 3489): 	at hee.a(PG:102)
E/HttpOperation( 3489): 	at czr.a(PG:65)
E/HttpOperation( 3489): 	at kka.a(PG:108)
E/HttpOperation( 3489): 	at czp.a(PG:19176)
E/HttpOperation( 3489): 	at czp.a(PG:9081)
E/HttpOperation( 3489): 	at czq.run(PG:1686)
E/HttpOperation( 3489): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3489): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3489): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3489): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3489): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3489): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3489): 	at jdj.a(PG:4091)
E/HttpOperation( 3489): 	at jdj.a(PG:1125)
E/HttpOperation( 3489): 	at jdm.a(PG:77)
E/HttpOperation( 3489): 	... 15 more
E/HttpOperation( 3489): Caused by: faj: BadAuthentication
E/HttpOperation( 3489): 	at fal.a(PG:38)
E/HttpOperation( 3489): 	at jdj.a(PG:4089)
E/HttpOperation( 3489): 	... 17 more
,E/ExperimentLoader( 3489): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3489): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3489): 	at jdm.a(PG:82)
E/ExperimentLoader( 3489): 	at jcs.o(PG:406)
E/ExperimentLoader( 3489): ,	at jcn.a(PG:1379)
E/ExperimentLoader( 3489): 	at jcs.i(PG:143)
E/ExperimentLoader( 3489): 	at hec.a(PG:42)
E/ExperimentLoader( 3489): 	at hee.a(PG:102)
E/ExperimentLoader( 3489): 	at czr.a(PG:65)
E/ExperimentLoader( 3489): 	at kka.a(PG:108)
E/ExperimentLoader( 3489): 	at czp.a(PG:19176)
E/ExperimentLoader( 3489): 	at czp.a(PG:9081)
E/ExperimentLoader( 3489): ,	at czq.run(PG:1686)
E/ExperimentLoader( 3489): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3489): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3489): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3489): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3489): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3489): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3489): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3489): 	at jdj.a(PG:1125),
E/ExperimentLoader( 3489): 	at jdm.a(PG:77)
E/ExperimentLoader( 3489): 	... 15 more
E/ExperimentLoader( 3489): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3489): 	at fal.a(PG:38)
E/ExperimentLoader( 3489): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3489): 	... 17 more
,E/KeepSync( 3883): IOException
E/KeepSync( 3883): com.google.android.apiary.AuthenticationException: Could not get an auth token
,E/KeepSync( 3883): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3883): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3883): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3883): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
,E/KeepSync( 3883): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3883): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3883): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3883): 	at com.google.android.keep.util.m.a(SourceFile:207),
E/KeepSync( 3883): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3883): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3883): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3883): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3883): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3883): ,	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3883): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3883): 	... 10 more
,W/KeepSync( 3883): Sync result 2
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 597897, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 594342, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2399): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2399): Disconnected process message: 10, size: 0
,V/GoogleAuthProtoRequest( 3693): [399] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3693): [399] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3693): [399] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3693): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3693): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3693): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3693): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3693): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3693): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3693): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3693): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3693): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3693): 	at com.a.a.k.run(SourceFile:110)
,I/BooksSync( 3941): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3941): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1489): Explicit concurrent mark sweep GC freed 52762(2MB) AllocSpace objects, 14(1544KB) LOS objects, 37% free, 27MB/43MB, paused 2.307ms total 58.993ms
,E/BooksAccountManager( 3941): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3941): Soft error
E/BooksSync( 3941): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3941): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3941): Sync error
E/BooksSync( 3941): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3941): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3941): Finished books sync
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 664310, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3489): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3489): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3489): 	at jdm.a(PG:82)
,E/HttpOperation( 3489): 	at jcs.o(PG:406)
E/HttpOperation( 3489): 	at jcn.a(PG:1379)
E/HttpOperation( 3489): 	at jcs.i(PG:143)
E/HttpOperation( 3489): 	at blb.a(PG:3937)
E/HttpOperation( 3489): 	at czp.a(PG:18188)
E/HttpOperation( 3489): 	at czp.a(PG:9081)
E/HttpOperation( 3489): 	at czq.run(PG:1686)
E/HttpOperation( 3489): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3489): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3489): 	,at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3489): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3489): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3489): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3489): 	at jdj.a(PG:4091)
E/HttpOperation( 3489): 	at jdj.a(PG:1125)
E/HttpOperation( 3489): 	at jdm.a(PG:77)
E/HttpOperation( 3489): 	... 12 more
E/HttpOperation( 3489): Caused by: faj: BadAuthentication,
E/HttpOperation( 3489): 	at fal.a(PG:38)
E/HttpOperation( 3489): 	at jdj.a(PG:4089)
E/HttpOperation( 3489): 	... 14 more
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3489): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3489): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3489): 	at jdm.a(PG:82)
E/HttpOperation( 3489): 	at jcs.o(PG:406)
E/HttpOperation( 3489): 	at jcn.a(PG:1379)
E/HttpOperation( 3489): 	at jcs.i(PG:143)
E/HttpOperation( 3489): 	at hec.a(PG:42)
E/HttpOperation( 3489): 	at hee.a(PG:102)
E/HttpOperation( 3489): 	at czr.a(PG:65)
E/HttpOperation( 3489): 	at kka.a(PG:108)
E/HttpOperation( 3489): 	at czp.a(PG:19176)
E/HttpOperation( 3489): 	at czp.a(PG:9081)
E/HttpOperation( 3489): 	at czq.run(PG:1686)
E/HttpOperation( 3489): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3489): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3489): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3489): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3489): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3489): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3489): 	at jdj.a(PG:4091)
E/HttpOperation( 3489): 	at jdj.a(PG:1125)
E/HttpOperation( 3489): 	at jdm.a(PG:77)
E/HttpOperation( 3489): 	... 15 more
E/HttpOperation( 3489): Caused by: faj: BadAuthentication
E/HttpOperation( 3489): 	at fal.a(PG:38)
E/HttpOperation( 3489): 	at jdj.a(PG:4089)
E/HttpOperation( 3489): 	... 17 more
E/ExperimentLoader( 3489): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3489): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3489): 	at jdm.a(PG:82)
E/ExperimentLoader( 3489): 	at jcs.o(PG:406)
E/ExperimentLoader( 3489): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3489): 	at jcs.i(PG:143)
E/ExperimentLoader( 3489): 	at hec.a(PG:42)
E/ExperimentLoader( 3489): 	at hee.a(PG:102)
E/ExperimentLoader( 3489): 	at czr.a(PG:65)
E/ExperimentLoader( 3489): 	at kka.a(PG:108)
E/ExperimentLoader( 3489): 	at czp.a(PG:19176)
E/ExperimentLoader( 3489): 	at czp.a(PG:9081)
E/ExperimentLoader( 3489): 	at czq.run(PG:1686)
E/ExperimentLoader( 3489): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3489): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3489): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3489): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3489): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3489): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3489): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3489): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3489): 	at jdm.a(PG:77)
E/ExperimentLoader( 3489): 	... 15 more
E/ExperimentLoader( 3489): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3489): 	at fal.a(PG:38)
E/ExperimentLoader( 3489): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3489): 	... 17 more
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 686450, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2399): Disconnected process message: 10, size: 0
,I/art     (  819): Explicit concurrent mark sweep GC freed 44996(1953KB) AllocSpace objects, 9(426KB) LOS objects, 31% free, 34MB/50MB, paused 1.546ms total 97.079ms
,D/HeadsetStateMachine( 2399): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2399): Disconnected process message: 10, size: 0
,I/ActivityManager(  819): Start proc 4184:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider
,I/GAv4    ( 4184): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4184):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4184):   adb logcat -s GAv4
,W/GAv4    ( 4184): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.,
,W/GAv4    ( 4184): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4184): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  819): Killing 3527:com.google.android.gm/u0a78 (adj 15): empty #17
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/HttpOperation( 3489): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3489): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3489): 	at jdm.a(PG:82)
E/HttpOperation( 3489): 	at jcs.o(PG:406)
E/HttpOperation( 3489): 	at jcn.a(PG:1379)
E/HttpOperation( 3489): 	at jcs.i(PG:143)
E/HttpOperation( 3489): 	at blb.a(PG:3937)
E/HttpOperation( 3489): 	at czp.a(PG:18188)
E/HttpOperation( 3489): 	at czp.a(PG:9081)
E/HttpOperation( 3489): 	at czq.run(PG:1686)
E/HttpOperation( 3489): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3489): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3489): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3489): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3489): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3489): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3489): 	at jdj.a(PG:4091)
E/HttpOperation( 3489): 	at jdj.a(PG:1125)
E/HttpOperation( 3489): 	at jdm.a(PG:77)
E/HttpOperation( 3489): 	... 12 more
E/HttpOperation( 3489): Caused by: faj: BadAuthentication
E/HttpOperation( 3489): 	at fal.a(PG:38)
E/HttpOperation( 3489): 	at jdj.a(PG:4089)
E/HttpOperation( 3489): 	... 14 more
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/HttpOperation( 3489): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3489): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3489): 	at jdm.a(PG:82)
E/HttpOperation( 3489): 	at jcs.o(PG:406)
E/HttpOperation( 3489): 	at jcn.a(PG:1379)
E/HttpOperation( 3489): 	at jcs.i(PG:143)
E/HttpOperation( 3489): 	at hec.a(PG:42)
E/HttpOperation( 3489): 	at hee.a(PG:102)
E/HttpOperation( 3489): 	at czr.a(PG:65)
E/HttpOperation( 3489): 	at kka.a(PG:108)
E/HttpOperation( 3489): 	at czp.a(PG:19176)
E/HttpOperation( 3489): 	at czp.a(PG:9081)
E/HttpOperation( 3489): 	at czq.run(PG:1686)
E/HttpOperation( 3489): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3489): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3489): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3489): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3489): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3489): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3489): 	at jdj.a(PG:4091)
E/HttpOperation( 3489): 	at jdj.a(PG:1125)
E/HttpOperation( 3489): 	at jdm.a(PG:77)
E/HttpOperation( 3489): 	... 15 more
E/HttpOperation( 3489): Caused by: faj: BadAuthentication
E/HttpOperation( 3489): 	at fal.a(PG:38)
E/HttpOperation( 3489): 	at jdj.a(PG:4089)
E/HttpOperation( 3489): 	... 17 more
,E/ExperimentLoader( 3489): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token,
E/ExperimentLoader( 3489): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3489): 	at jdm.a(PG:82)
E/ExperimentLoader( 3489): 	at jcs.o(PG:406)
E/ExperimentLoader( 3489): 	,at jcn.a(PG:1379)
E/ExperimentLoader( 3489): 	at jcs.i(PG:143)
E/ExperimentLoader( 3489): 	at hec.a(PG:42)
E/ExperimentLoader( 3489): 	at hee.a(PG:102)
E/ExperimentLoader( 3489): ,	at czr.a(PG:65)
E/ExperimentLoader( 3489): 	at kka.a(PG:108)
E/ExperimentLoader( 3489): 	at czp.a(PG:19176),
E/ExperimentLoader( 3489): 	at czp.a(PG:9081)
E/ExperimentLoader( 3489): 	at czq.run(PG:1686)
E/ExperimentLoader( 3489): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3489): ,	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3489): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3489): 	,at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3489): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3489): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3489): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3489): ,	at jdj.a(PG:1125)
E/ExperimentLoader( 3489): 	at jdm.a(PG:77)
E/ExperimentLoader( 3489): 	... 15 more
E/ExperimentLoader( 3489): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3489): 	at fal.a(PG:38)
E/ExperimentLoader( 3489): ,	at jdj.a(PG:4089)
E/ExperimentLoader( 3489): 	... 17 more
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 841429, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2399): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2399): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2399): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2399): Disconnected process message: 10, size: 0
,W/bt-btm  ( 2399): Stopping oneshot timer
,D/HeadsetStateMachine( 2399): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2399): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2399): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2399): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2399): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2399): Disconnected process message: 10, size: 0
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3489): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3489): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3489): 	at jdm.a(PG:82)
E/HttpOperation( 3489): 	at jcs.o(PG:406)
E/HttpOperation( 3489): 	at jcn.a(PG:1379)
E/HttpOperation( 3489): 	at jcs.i(PG:143)
E/HttpOperation( 3489): 	at blb.a(PG:3937)
E/HttpOperation( 3489): 	at czp.a(PG:18188)
E/HttpOperation( 3489): 	at czp.a(PG:9081)
E/HttpOperation( 3489): 	at czq.run(PG:1686)
E/HttpOperation( 3489): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3489): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3489): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3489): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3489): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3489): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3489): 	at jdj.a(PG:4091)
E/HttpOperation( 3489): 	at jdj.a(PG:1125)
E/HttpOperation( 3489): 	at jdm.a(PG:77)
E/HttpOperation( 3489): 	... 12 more
E/HttpOperation( 3489): Caused by: faj: BadAuthentication
E/HttpOperation( 3489): 	at fal.a(PG:38)
E/HttpOperation( 3489): 	at jdj.a(PG:4089)
E/HttpOperation( 3489): 	... 14 more
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3489): [getmobileexperiments] Unexpected exception,
E/HttpOperation( 3489): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3489): 	at jdm.a(PG:82)
E/HttpOperation( 3489): 	at jcs.o(PG:406)
E/HttpOperation( 3489): 	at jcn.a(PG:1379),
E/HttpOperation( 3489): 	at jcs.i(PG:143)
E/HttpOperation( 3489): 	at hec.a(PG:42)
E/HttpOperation( 3489): 	at hee.a(PG:102)
E/HttpOperation( 3489): 	at czr.a(PG:65)
E/HttpOperation( 3489): 	at kka.a(PG:108)
E/HttpOperation( 3489): 	at czp.a(PG:19176)
E/HttpOperation( 3489): 	at czp.a(PG:9081)
E/HttpOperation( 3489): 	at czq.run(PG:1686)
,E/HttpOperation( 3489): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3489): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3489): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3489): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3489): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3489): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3489): 	at jdj.a(PG:4091),
E/HttpOperation( 3489): 	at jdj.a(PG:1125)
E/HttpOperation( 3489): 	at jdm.a(PG:77)
E/HttpOperation( 3489): 	... 15 more
E/HttpOperation( 3489): Caused by: faj: BadAuthentication
,E/HttpOperation( 3489): 	at fal.a(PG:38)
E/HttpOperation( 3489): 	at jdj.a(PG:4089)
E/HttpOperation( 3489): 	... 17 more
E/ExperimentLoader( 3489): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3489): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3489): ,	at jdm.a(PG:82)
E/ExperimentLoader( 3489): 	at jcs.o(PG:406)
E/ExperimentLoader( 3489): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3489): 	at jcs.i(PG:143)
E/ExperimentLoader( 3489): 	at hec.a(PG:42)
,E/ExperimentLoader( 3489): 	at hee.a(PG:102)
E/ExperimentLoader( 3489): 	at czr.a(PG:65)
E/ExperimentLoader( 3489): 	at kka.a(PG:108)
E/ExperimentLoader( 3489): 	at czp.a(PG:19176)
E/ExperimentLoader( 3489): 	at czp.a(PG:9081),
E/ExperimentLoader( 3489): 	at czq.run(PG:1686)
E/ExperimentLoader( 3489): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3489): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3489): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112),
E/ExperimentLoader( 3489): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3489): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3489): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3489): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3489): 	,at jdj.a(PG:1125)
E/ExperimentLoader( 3489): 	at jdm.a(PG:77)
E/ExperimentLoader( 3489): 	... 15 more
E/ExperimentLoader( 3489): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3489): 	at fal.a(PG:38)
E/ExperimentLoader( 3489): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3489): 	... 17 more
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 1100743, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,V/KeepSync( 3883): Connecting to GoogleApiClient
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/ClientConnectionOperation( 1776): Handling authorization failure
E/ClientConnectionOperation( 1776): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1776): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1776): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1776): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1776): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1776): 	... 7 more
,V/KeepSync( 3883): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3883): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3883): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3883): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3883): IOException
E/KeepSync( 3883): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3883): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3883): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3883): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3883): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3883): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3883): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3883): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3883): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3883): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3883): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3883): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3883): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3883): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3883): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3883): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3883): 	... 10 more
W/KeepSync( 3883): Sync result 2
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 1115294, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2399): Disconnected process message: 10, size: 0
,D/GCM     ( 1489): Message class com.google.f.a.a.i
,V/GoogleAuthProtoRequest( 3693): [400] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3693): [400] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3693): [400] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3693): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3693): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3693): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3693): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3693): 	,at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3693): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3693): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3693): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3693): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3693): 	at com.a.a.k.run(SourceFile:110)
,I/BooksSync( 3941): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3941): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1489): Explicit concurrent mark sweep GC freed 58576(2MB) AllocSpace objects, 8(882KB) LOS objects, 37% free, 27MB/43MB, paused 1.411ms total 71.507ms
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  819): Explicit concurrent mark sweep GC freed 41463(1875KB) AllocSpace objects, 7(300KB) LOS objects, 31% free, 34MB/50MB, paused 1.223ms total 63.640ms
,E/BooksAccountManager( 3941): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3941): Soft error
E/BooksSync( 3941): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3941): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3941): Sync error
E/BooksSync( 3941): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3941): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3941): Finished books sync
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1187938, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2399): Disconnected process message: 10, size: 0
,I/UsageStatsService(  819): User[0] Flushing usage stats to disk
,D/HeadsetStateMachine( 2399): Disconnected process message: 10, size: 0
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 4297): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 4297): CheckJNI is OFF
D/AndroidRuntime( 4297): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  819): Force stopping com.test.thalitest appid=10265 user=-1: uninstall pkg
I/ActivityManager(  819): Killing 3631:com.test.thalitest/u0a265 (adj 0): stop com.test.thalitest
W/PackageSettings(  819): Skipping PackageSetting{15980286 com.example.hello/10273} due to missing metadata
E/libprocessgroup(  819): failed to kill 1 processes for processgroup 3631
W/ActivityManager(  819): Force removing ActivityRecord{5ccd401 u0 com.test.thalitest/.MainActivity t28}: app died, no saved state
E/JavaBinder(  819): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder(  819): !!! FAILED BINDER TRANSACTION !!!
V/ActivityManager(  819): Display changed displayId=0
D/WifiService(  819): Client connection lost with reason: 4
W/DisplayManagerService(  819): Failed to notify process 3631 that displays changed, assuming it died.
W/DisplayManagerService(  819): android.os.DeadObjectException
W/DisplayManagerService(  819): 	at android.os.BinderProxy.transactNative(Native Method)
W/DisplayManagerService(  819): 	at android.os.BinderProxy.transact(Binder.java:496)
W/DisplayManagerService(  819): 	at android.hardware.display.IDisplayManagerCallback$Stub$Proxy.onDisplayEvent(IDisplayManagerCallback.java:81)
W/DisplayManagerService(  819): 	at com.android.server.display.DisplayManagerService$CallbackRecord.notifyDisplayEventAsync(DisplayManagerService.java:1094)
W/DisplayManagerService(  819): 	at com.android.server.display.DisplayManagerService.deliverDisplayEvent(DisplayManagerService.java:932)
W/DisplayManagerService(  819): 	at com.android.server.display.DisplayManagerService.access$500(DisplayManagerService.java:112)
W/DisplayManagerService(  819): 	at com.android.server.display.DisplayManagerService$DisplayManagerHandler.handleMessage(DisplayManagerService.java:1027)
W/DisplayManagerService(  819): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/DisplayManagerService(  819): 	at android.os.Looper.loop(Looper.java:135)
W/DisplayManagerService(  819): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/DisplayManagerService(  819): 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
I/ActivityManager(  819): Force stopping com.test.thalitest appid=10265 user=0: pkg removed
I/Keyboard.Facilitator( 1216): resetDictionaries() : en_US
I/InputReader(  819): Reconfiguring input devices.  changes=0x00000010
D/TaskPersister(  819): removeObsoleteFile: deleting file=28_task.xml
D/BuaReceiver( 3357): ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
I/Keyboard.Facilitator.DecoderInitializer( 1216): run()
I/art     ( 1066): Explicit concurrent mark sweep GC freed 73370(2MB) AllocSpace objects, 0(0B) LOS objects, 18% free, 72MB/88MB, paused 2.414ms total 44.710ms
I/ActivityManager(  819): Start proc 4313:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
I/art     ( 1517): Explicit concurrent mark sweep GC freed 2390(173KB) AllocSpace objects, 0(0B) LOS objects, 22% free, 27MB/35MB, paused 368us total 75.998ms
I/art     (  819): Explicit concurrent mark sweep GC freed 12492(949KB) AllocSpace objects, 9(332KB) LOS objects, 31% free, 34MB/50MB, paused 1.666ms total 72.512ms
I/art     (  819): WaitForGcToComplete blocked for 68.001ms for cause Explicit
I/Decoder ( 1216): createOrResetDecoder
W/InputMethodManagerService(  819): Got RemoteException sending setActive(false) notification to pid 3631 uid 10265
I/Keyboard.Facilitator( 1216): onFinishInput()
I/ConfigService( 1489): onCreate
I/Keyboard.Facilitator.MainLanguageModelLoader( 1216): run()
W/LocationOracleImpl( 1517): Best location was null
D/JobSchedulerService(  819): Receieved: android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  819): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/Keyboard.Facilitator.MainLanguageModelLoader( 1216): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1216): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1216): run() : Loading LM = contacts
I/art     ( 1293): Explicit concurrent mark sweep GC freed 5345(392KB) AllocSpace objects, 12(1408KB) LOS objects, 31% free, 35MB/51MB, paused 1.206ms total 23.978ms
I/HotwordRecognitionRnr( 1517): Starting hotword detection.
I/MicrophoneInputStream( 1517): mic_starting com.google.android.apps.gsa.speech.audio.u@1922145b
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1216): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1216): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1216): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1216): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1216): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1216): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1216): run()
I/SoundTriggerHwService::Module(  358): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/AudioFlinger(  358): AudioFlinger's thread 0xb4047000 ready to run
I/Keyboard.Facilitator.RecurringTaskScheduler( 1216): run()
I/StatsUtilsManager( 1216): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1216): shouldRecordStats() = Too Soon
I/MicrophoneInputStream( 1517): mic_started com.google.android.apps.gsa.speech.audio.u@1922145b
D/audio_hw_primary(  358): select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
D/msm8974_platform(  358): platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
E/ACDB-LOADER(  358): Error: ACDB AudProc vol returned = -19
D/audio_hw_primary(  358): enable_snd_device: snd_device(55: voice-rec-mic)
D/audio_hw_primary(  358): enable_audio_route: apply and update mixer path: audio-record
D/VoicemailCleanupService( 4313): Cleaning up data for package: com.test.thalitest
I/ActivityManager(  819): Start proc 4349:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
I/ContactLocale( 4313): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
I/art     (  819): Explicit concurrent mark sweep GC freed 5333(244KB) AllocSpace objects, 0(0B) LOS objects, 31% free, 34MB/50MB, paused 2.352ms total 173.294ms
I/HotwordWorker( 1517): onReady
I/art     ( 1803): Explicit concurrent mark sweep GC freed 16659(974KB) AllocSpace objects, 8(128KB) LOS objects, 37% free, 26MB/42MB, paused 937us total 29.902ms
E/DataBuffer( 1803): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3d4906ff)
I/ActivityManager(  819): Start proc 4370:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
D/WifiService(  819): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@194ef2d6}
E/WifiStateMachine(  819): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=38.50 rxSuccessRate=36.50 targetRoamBSSID=any RSSI=-51
E/WifiStateMachine(  819): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=75.25 rxSuccessRate=160.75 targetRoamBSSID=any RSSI=-51
W/ContextImpl( 4370): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2609 
E/LocSvc_IzatApiV02(  819): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1659151635
E/LocSvc_IzatApiV02(  819): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
I/art     ( 4297): System.exit called, status: 0
I/AndroidRuntime( 4297): VM exiting with result code 0.
E/NetworkScheduler.SchedulerReceiver( 1489): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1489): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
D/PackageBroadcastService( 1776): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/ChimeraCfgMgr( 1776): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1776): Module APK com.google.android.play.games already loaded
D/AccountUtils( 1776): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1776): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1776): Module APK com.google.android.play.games already loaded
I/LocationSettingsChecker( 1776): Removing dialog suppression flag for package com.test.thalitest
I/UpdateIcingCorporaServi( 1517): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
D/Launcher.Workspace( 1293): 11683562 - stripEmptyScreens()
D/Launcher.Workspace( 1293): 11683562 - stripEmptyScreens()
D/GOOGLEHELP_CompatibleDatabase( 1776): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1776): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1776): 0 metrics were deleted when clearing package com.test.thalitest.
D/GOOGLEHELP_CompatibleDatabase( 1776): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/GOOGLEHELP_CompatibleDatabase( 1776): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1776): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/GOOGLEHELP_CompatibleDatabase( 1776): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/GOOGLEHELP_CompatibleDatabase( 1776): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1776): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/GOOGLEHELP_CompatibleDatabase( 1776): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/GOOGLEHELP_CompatibleDatabase( 1776): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/GOOGLEHELP_CompatibleDatabase( 1776): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/GOOGLEHELP_CompatibleDatabase( 1776): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/ConfigFetchService( 1776): onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
I/kickstart(  869): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
I/kickstart(  869): STATUS: Wrote to /sys/power/wake_lock
W/BaseAppContext( 1776): Using Auth Proxy for data requests.
W/BaseAppContext( 1776): Using Auth Proxy for data requests.
I/ActivityManager(  819): Killing 3313:com.google.android.music:main/u0a66 (adj 15): empty #17
W/Launcher( 1293): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@36708b8d new=com.google.android.velvet.VelvetApplication@36708b8d
E/kickstart(  869): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2
I/kickstart(  869): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2' for writing
I/ConfigFetchService( 1776): service connected
I/ActivityManager(  819): Start proc 4403:com.google.android.apps.docs/u0a46 for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
E/SQLiteLog( 1517): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/AppDataSearchHelper( 1517): Exception thrown from onTableChanged
E/AppDataSearchHelper( 1517): java.lang.RuntimeException: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AppDataSearchHelper( 1517): 	at com.google.android.gms.appdatasearch.a.a.a(AppDataSearchDbOpenHelperBase.java:343)
E/AppDataSearchHelper( 1517): 	at com.google.android.gms.appdatasearch.a.a.a(AppDataSearchDbOpenHelperBase.java:261)
E/AppDataSearchHelper( 1517): 	at com.google.android.search.core.icingsync.d.j(InternalIcingCorporaProvider.java:709)
E/AppDataSearchHelper( 1517): 	at com.google.android.search.core.icingsync.d.a(InternalIcingCorporaProvider.java:700)
E/AppDataSearchHelper( 1517): 	at com.google.android.search.core.icingsync.d.i(InternalIcingCorporaProvider.java:627)
E/AppDataSearchHelper( 1517): 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:298)
E/AppDataSearchHelper( 1517): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:328)
E/AppDataSearchHelper( 1517): 	at android.content.ContentResolver.update(ContentResolver.java:1333)
E/AppDataSearchHelper( 1517): 	at com.google.android.search.core.icingsync.e.JA(UpdateIcingCorporaService.java:408)
E/AppDataSearchHelper( 1517): 	at com.google.android.search.core.icingsync.g.aTY(UpdateIcingCorporaService.java:347)
E/AppDataSearchHelper( 1517): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:320)
E/AppDataSearchHelper( 1517): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.ba(UpdateIcingCorporaService.java:215)
E/AppDataSearchHelper( 1517): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:201)
E/AppDataSearchHelper( 1517): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AppDataSearchHelper( 1517): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AppDataSearchHelper( 1517): 	at android.os.Looper.loop(Looper.java:135)
E/AppDataSearchHelper( 1517): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/AppDataSearchHelper( 1517): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AppDataSearchHelper( 1517): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AppDataSearchHelper( 1517): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/AppDataSearchHelper( 1517): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AppDataSearchHelper( 1517): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AppDataSearchHelper( 1517): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/AppDataSearchHelper( 1517): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/AppDataSearchHelper( 1517): 	at com.google.android.gms.appdatasearch.a.a.a(AppDataSearchDbOpenHelperBase.java:661)
E/AppDataSearchHelper( 1517): 	at com.google.android.gms.appdatasearch.a.a$1.JA(AppDataSearchDbOpenHelperBase.java:246)
E/AppDataSearchHelper( 1517): 	at com.google.android.gms.appdatasearch.a.a$1.call(AppDataSearchDbOpenHelperBase.java:227)
E/AppDataSearchHelper( 1517): 	at com.google.android.gms.appdatasearch.a.a.a(AppDataSearchDbOpenHelperBase.java:341)
E/AppDataSearchHelper( 1517): 	... 16 more
W/AppDataSearchHelper( 1517): Table change notification failed for com.google.android.gms.appdatasearch.a.h@be7fd6a1
I/UpdateIcingCorporaServi( 1517): UpdateCorporaTask done [took 200 ms] updated apps [took 200 ms] 
I/PeopleContactsSync( 1776): CP2 sync disabled
I/art     (  369): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 221us total 19.779ms
I/Icing   ( 1776): doRemovePackageData com.test.thalitest
I/art     (  369): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 208us total 10.595ms
I/art     (  369): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 209us total 9.163ms
E/SQLiteLog( 4313): (3850) statement aborts at 22: [DELETE FROM deleted_contacts WHERE contact_deleted_timestamp < ?] disk I/O error
--------- beginning of crash
E/AndroidRuntime( 4313): FATAL EXCEPTION: ContactsProviderWorker
E/AndroidRuntime( 4313): Process: android.process.acore, PID: 4313
E/AndroidRuntime( 4313): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4313): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 4313): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 4313): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 4313): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 4313): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/AndroidRuntime( 4313): 	at com.android.providers.contacts.database.DeletedContactsTableUtil.deleteOldLogs(DeletedContactsTableUtil.java:78)
E/AndroidRuntime( 4313): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1730)
E/AndroidRuntime( 4313): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1492)
E/AndroidRuntime( 4313): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4313): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 4313): 	at android.os.HandlerThread.run(HandlerThread.java:61)
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
I/OpenGLRenderer(  819): Initialized EGL, version 1.4
D/OpenGLRenderer(  819): Enabling debug mode 0
I/HotwordDetector( 1517): Closing mic
I/MicrophoneInputStream( 1517): mic_close com.google.android.apps.gsa.speech.audio.u@1922145b
E/Search.SharedPreferencesProto( 1517): Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
I/ActivityManager(  819): Killing 3719:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
D/audio_hw_primary(  358): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  358): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  358): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1517): Stopping hotword detection.
I/HotwordRecognitionRnr( 1517): Hotword detection finished
I/GAv4    ( 4403): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4403):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4403):   adb logcat -s GAv4
I/ActivityManager(  819): Killing 3739:com.google.android.apps.magazines/u0a67 (adj 15): empty #17
W/GAv4    ( 4403): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
E/native  ( 1216): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1216): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/SharedPreferencesImpl( 4403): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4403): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
E/SharedPreferencesImpl( 4403): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4403): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
E/SharedPreferencesImpl( 4403): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/AnalyticsTrackerProxyImpl( 4403): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
E/SQLiteDatabase( 4403): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4403): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4403): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4403): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4403): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4403): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4403): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4403): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4403): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4403): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4403): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4403): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4403): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4403): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4403): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4403): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 4403): 	at ael.a(PG:1521)
E/SQLiteDatabase( 4403): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 4403): 	at aen.run(PG:536)
E/SQLiteDatabase( 4403): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 4403): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4403): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4403): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4403): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4403): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4403): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4403): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4403): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4403): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4403): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4403): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4403): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4403): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4403): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4403): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 4403): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 4403): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 4403): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 4403): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 4403): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 4403): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4403): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4403): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4403): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4403): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 4403): 	at gir$c.run(Unknown Source)
E/GAv4    ( 4403): Opening the database failed, dropping the table and recreating it
E/SharedPreferencesImpl( 4403): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SQLiteDatabase( 4403): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 4403): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4403): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4403): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4403): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4403): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4403): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4403): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4403): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4403): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4403): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4403): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4403): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4403): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4403): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4403): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 4403): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 4403): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 4403): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 4403): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 4403): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 4403): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4403): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4403): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4403): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4403): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 4403): 	at gir$c.run(Unknown Source)
E/GAv4    ( 4403): Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 4403): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4403): Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 4403): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4403): Job execution failed: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 4403): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/native  ( 1216): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1216): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1216): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1216): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1216): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1216): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
W/GAv4    ( 4403): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SQLiteDatabase( 4403): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4403): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4403): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4403): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4403): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4403): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4403): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4403): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4403): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4403): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4403): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4403): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4403): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4403): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4403): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4403): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 4403): 	at ael.a(PG:1521)
E/SQLiteDatabase( 4403): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 4403): 	at aej.c(PG:139)
E/SQLiteDatabase( 4403): 	at aej.b(PG:398)
E/SQLiteDatabase( 4403): 	at agf.f(PG:417)
E/SQLiteDatabase( 4403): 	at oe.run(PG:1112)
E/SQLiteDatabase( 4403): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4403): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4403): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4403): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4403): 	at java.lang.Thread.run(Thread.java:818)
E/AbstractDatabaseInstance( 4403): Failed to delete from CachedSearch133
E/AbstractDatabaseInstance( 4403): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AbstractDatabaseInstance( 4403): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AbstractDatabaseInstance( 4403): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AbstractDatabaseInstance( 4403): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AbstractDatabaseInstance( 4403): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AbstractDatabaseInstance( 4403): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AbstractDatabaseInstance( 4403): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AbstractDatabaseInstance( 4403): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AbstractDatabaseInstance( 4403): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AbstractDatabaseInstance( 4403): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AbstractDatabaseInstance( 4403): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AbstractDatabaseInstance( 4403): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AbstractDatabaseInstance( 4403): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AbstractDatabaseInstance( 4403): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AbstractDatabaseInstance( 4403): 	at aev.getWritableDatabase(PG:238)
E/AbstractDatabaseInstance( 4403): 	at ael.a(PG:1521)
E/AbstractDatabaseInstance( 4403): 	at hix$a.a(PG:125)
E/AbstractDatabaseInstance( 4403): 	at aej.c(PG:139)
E/AbstractDatabaseInstance( 4403): 	at aej.b(PG:398)
E/AbstractDatabaseInstance( 4403): 	at agf.f(PG:417)
E/AbstractDatabaseInstance( 4403): 	at oe.run(PG:1112)
E/AbstractDatabaseInstance( 4403): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/AbstractDatabaseInstance( 4403): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AbstractDatabaseInstance( 4403): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AbstractDatabaseInstance( 4403): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AbstractDatabaseInstance( 4403): 	at java.lang.Thread.run(Thread.java:818)
E/SharedPreferencesImpl( 4403): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4403): Job execution failed: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4403): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4403): Error opening database: android.database.sqlite.SQLiteException: Database open failed
W/GAv4    ( 4403): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4403): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4403): Failed to commit local dispatch transaction: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4403): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4403): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4403): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4403): Sync local dispatch failed: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4403): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4403): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4403): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4403): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4403): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4403): syncDispatchLocalHits failed: java.util.concurrent.ExecutionException: android.database.sqlite.SQLiteException: Database open failed
E/CAKEMIX_CRASHED( 4403): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/CAKEMIX_CRASHED( 4403): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/CAKEMIX_CRASHED( 4403): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/CAKEMIX_CRASHED( 4403): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/CAKEMIX_CRASHED( 4403): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/CAKEMIX_CRASHED( 4403): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/CAKEMIX_CRASHED( 4403): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/CAKEMIX_CRASHED( 4403): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/CAKEMIX_CRASHED( 4403): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/CAKEMIX_CRASHED( 4403): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/CAKEMIX_CRASHED( 4403): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/CAKEMIX_CRASHED( 4403): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/CAKEMIX_CRASHED( 4403): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/CAKEMIX_CRASHED( 4403): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/CAKEMIX_CRASHED( 4403): 	at aev.getWritableDatabase(PG:238)
E/CAKEMIX_CRASHED( 4403): 	at ael.a(PG:1521)
E/CAKEMIX_CRASHED( 4403): 	at hix$a.a(PG:125)
E/CAKEMIX_CRASHED( 4403): 	at aen.run(PG:536)
E/SharedPreferencesImpl( 4403): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/ResourcesManager( 4403): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4403): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  819): Start proc 4445:com.android.documentsui/u0a45 for broadcast com.android.documentsui/.PackageReceiver
I/ActivityManager(  819): START u0 {act=android.intent.action.BUG_REPORT flg=0x10000000 cmp=com.google.android.apps.docs/.app.ErrorNotificationActivity (has extras)} from uid 10046 on display 0
V/WindowManager(  819): addAppToken: AppWindowToken{15a22ed token=Token{165bfd04 ActivityRecord{fe92517 u0 com.google.android.apps.docs/.app.ErrorNotificationActivity t29}}} to stack=1 task=29 at 0
I/Process ( 4403): Sending signal. PID: 4403 SIG: 9
E/lowmemorykiller(  255): Error writing /proc/4403/oom_score_adj; errno=22
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
E/kickstart(  869): ERROR: function: rx_data:267 Timeout Occured, No response or command came from the target!
I/kickstart(  869): WARNING: function: sahara_start:892 Retrying memory read request
I/ActivityManager(  819): Start proc 4462:com.google.android.apps.docs/u0a46 for activity com.google.android.apps.docs/.app.ErrorNotificationActivity
W/ActivityManager(  819): Spurious death for ProcessRecord{9217cbe 4462:com.google.android.apps.docs/u0a46}, curProc for 4403: null
W/OpenGLRenderer( 1293): Incorrectly called buildLayer on View: ew, destroying layer...
E/SQLiteDatabase( 4445): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 4445): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4445): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4445): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4445): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4445): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4445): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4445): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4445): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4445): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4445): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4445): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4445): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4445): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4445): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4445): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/SQLiteDatabase( 4445): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/SQLiteDatabase( 4445): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:370)
E/SQLiteDatabase( 4445): 	at android.content.ContentResolver.call(ContentResolver.java:1372)
E/SQLiteDatabase( 4445): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/SQLiteDatabase( 4445): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2609)
E/SQLiteDatabase( 4445): 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
E/SQLiteDatabase( 4445): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1380)
E/SQLiteDatabase( 4445): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4445): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 4445): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
E/SQLiteDatabase( 4445): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 4445): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 4445): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
E/SQLiteDatabase( 4445): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/AndroidRuntime( 4445): Shutting down VM
I/ActivityManager(  819): Killing 3795:com.android.chrome/u0a40 (adj 15): empty #17
E/AndroidRuntime( 4445): FATAL EXCEPTION: main
E/AndroidRuntime( 4445): Process: com.android.documentsui, PID: 4445
E/AndroidRuntime( 4445): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4445): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2616)
E/AndroidRuntime( 4445): 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
E/AndroidRuntime( 4445): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1380)
E/AndroidRuntime( 4445): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4445): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 4445): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
E/AndroidRuntime( 4445): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 4445): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 4445): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
E/AndroidRuntime( 4445): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
E/AndroidRuntime( 4445): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4445): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4445): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 4445): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 4445): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4445): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4445): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4445): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AndroidRuntime( 4445): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AndroidRuntime( 4445): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 4445): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AndroidRuntime( 4445): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 4445): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 4445): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 4445): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/AndroidRuntime( 4445): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/AndroidRuntime( 4445): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:370)
E/AndroidRuntime( 4445): 	at android.content.ContentResolver.call(ContentResolver.java:1372)
E/AndroidRuntime( 4445): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/AndroidRuntime( 4445): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2609)
E/AndroidRuntime( 4445): 	... 9 more
I/ActivityManager(  819): Start proc 4483:com.android.externalstorage/u0a10 for content provider com.android.externalstorage/.ExternalStorageProvider
E/DropBoxManagerService(  819): Can't write: system_app_crash
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
I/ActivityManager(  819): Killing 3817:com.google.android.apps.photos/u0a71 (adj 15): empty #17
I/GAv4    ( 4462): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4462):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4462):   adb logcat -s GAv4
W/GAv4    ( 4462): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 4462): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
E/SharedPreferencesImpl( 4462): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4462): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4462): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
E/SharedPreferencesImpl( 4462): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SQLiteDatabase( 4462): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 4462): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4462): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4462): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4462): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4462): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4462): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4462): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4462): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4462): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4462): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4462): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4462): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4462): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4462): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4462): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 4462): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 4462): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 4462): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 4462): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 4462): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 4462): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4462): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4462): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4462): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4462): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 4462): 	at gir$c.run(Unknown Source)
E/GAv4    ( 4462): Opening the database failed, dropping the table and recreating it
E/SharedPreferencesImpl( 4462): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SQLiteDatabase( 4462): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 4462): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4462): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4462): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4462): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4462): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4462): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4462): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4462): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4462): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4462): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4462): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4462): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4462): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4462): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4462): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 4462): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 4462): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 4462): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 4462): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 4462): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 4462): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4462): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4462): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4462): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4462): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 4462): 	at gir$c.run(Unknown Source)
E/GAv4    ( 4462): Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/AnalyticsTrackerProxyImpl( 4462): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
E/SharedPreferencesImpl( 4462): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4462): Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 4462): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4462): Job execution failed: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
D/WifiService(  819): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@194ef2d6}
E/SharedPreferencesImpl( 4462): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
D/ExternalStorage( 4483): After updating volumes, found 1 active roots
E/SQLiteDatabase( 4462): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4462): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4462): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4462): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4462): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4462): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4462): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4462): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4462): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4462): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4462): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4462): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4462): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4462): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4462): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4462): 	at aev.,getWritableDatabase(PG:238)
E/SQLiteDatabase( 4462): 	at ael.a(PG:1521)
E/SQLiteDatabase( 4462): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 4462): 	at aen.run(PG:536)
E/SQLiteDatabase( 4462): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4462): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4462): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4462): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4462): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4462): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4462): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4462): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4462): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4462): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4462): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4462): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4462): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4462): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4462): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4462): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 4462): 	at ael.a(PG:1521)
E/SQLiteDatabase( 4462): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 4462): 	at aej.c(PG:139)
E/SQLiteDatabase( 4462): 	at aej.b(PG:398)
E/SQLiteDatabase( 4462): 	at agf.f(PG:417)
E/SQLiteDatabase( 4462): 	at oe.run(PG:1112)
E/SQLiteDatabase( 4462): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4462): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4462): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4462): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4462): 	at java.lang.Thread.run(Thread.java:818)
E/AbstractDatabaseInstance( 4462): Failed to delete from CachedSearch133
E/AbstractDatabaseInstance( 4462): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AbstractDatabaseInstance( 4462): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AbstractDatabaseInstance( 4462): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AbstractDatabaseInstance( 4462): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AbstractDatabaseInstance( 4462): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AbstractDatabaseInstance( 4462): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AbstractDatabaseInstance( 4462): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AbstractDatabaseInstance( 4462): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AbstractDatabaseInstance( 4462): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AbstractDatabaseInstance( 4462): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AbstractDatabaseInstance( 4462): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AbstractDatabaseInstance( 4462): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AbstractDatabaseInstance( 4462): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AbstractDatabaseInstance( 4462): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AbstractDatabaseInstance( 4462): 	at aev.getWritableDatabase(PG:238)
E/AbstractDatabaseInstance( 4462): 	at ael.a(PG:1521)
E/AbstractDatabaseInstance( 4462): 	at hix$a.a(PG:125)
E/AbstractDatabaseInstance( 4462): 	at aej.c(PG:139)
E/AbstractDatabaseInstance( 4462): 	at aej.b(PG:398)
E/AbstractDatabaseInstance( 4462): 	at agf.f(PG:417)
E/AbstractDatabaseInstance( 4462): 	at oe.run(PG:1112)
E/AbstractDatabaseInstance( 4462): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/AbstractDatabaseInstance( 4462): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AbstractDatabaseInstance( 4462): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AbstractDatabaseInstance( 4462): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AbstractDatabaseInstance( 4462): 	at java.lang.Thread.run(Thread.java:818)
W/ResourcesManager( 4462): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
```
