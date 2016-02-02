#### Test 575312431f256a6_thali05_motorola-Nexus 6 Logs


```
--------- beginning of main
I/CheckinService( 1789): Done disabling old GoogleServicesFramework version
,D/AndroidRuntime( 3577): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 3577): CheckJNI is OFF
D/AndroidRuntime( 3577): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  821): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/WindowManager(  821): addAppToken: AppWindowToken{24f59896 token=Token{3cd48bb1 ActivityRecord{19773e58 u0 com.test.thalitest/.MainActivity t28}}} to stack=1 task=28 at 0
V/WindowManager(  821): Adding window Window{177022b3 u0 Starting com.test.thalitest} at 2 of 7 (after Window{103100cd u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
D/AndroidRuntime( 3577): Shutting down VM
I/HotwordDetector( 1507): Closing mic
I/MicrophoneInputStream( 1507): mic_close com.google.android.apps.gsa.speech.audio.u@9be841
I/ActivityManager(  821): Start proc 3591:com.test.thalitest/u0a265 for activity com.test.thalitest/.MainActivity
D/audio_hw_primary(  357): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  357): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  357): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1507): Hotword detection finished
I/HotwordRecognitionRnr( 1507): Stopping hotword detection.
I/ActivityManager(  821): Killing 3190:com.google.android.apps.messaging/u0a75 (adj 15): empty #17
I/WebViewFactory( 3591): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3591): Time to load native libraries: 1 ms (timestamps 1183-1184)
I/LibraryLoader( 3591): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3591): Binding Chromium to main looper Looper (main, tid 1) {9e2b760}
I/LibraryLoader( 3591): Expected native library version number "",actual native library version number ""
I/chromium( 3591): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3591): Initializing chromium process, singleProcess=true
,W/art     ( 3591): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3591): ApplicationContext is null in ApplicationStatus
,W/chromium( 3591): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3591): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3591): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3591): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1703011603
E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,D/BluetoothManagerService(  821): Message: 20
,D/BluetoothManagerService(  821): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1e13705d:true
,W/art     ( 3591): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3591): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3591): CordovaWebView is running on device made by: motorola
,W/art     ( 3591): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3591): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3591): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,D/Atlas   ( 3591): Validating map...
,V/WindowManager(  821): Adding window Window{14362acd u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{177022b3 u0 Starting com.test.thalitest})
,W/chromium( 3591): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3591): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3591): Enabling debug mode 0
,I/ActivityManager(  821): Displayed com.test.thalitest/.MainActivity: +631ms
,I/Keyboard.Facilitator( 1225): onFinishInput()
,W/BindingManager( 3591): Cannot call determinedVisibility() - never saw a connection for the pid: 3591
,D/JsMessageQueue( 3591): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3591): JniHelper::setJavaVM(0xb489d200), pthread_self() = -1576332800
,I/chromium( 3591): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 3591): Initializing JXcore engine
W/jxcore-log( 3591): JXcore engine is ready
,W/Thread-398( 3647): type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[9768]" dev="sockfs" ino=9768 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-398( 3647): type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,W/Thread-398( 3647): type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[9878]" dev="sockfs" ino=9878 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-398( 3647): type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[21662]" dev="sockfs" ino=21662 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 3591): Starting JXcore engine
,I/ActivityManager(  821): Waited long enough for: ServiceRecord{17f40cad u0 com.motorola.android.buacontactadapter/.AuthenticationService}
,W/jxcore-log( 3591): Platform android
,W/jxcore-log( 3591): 
W/jxcore-log( 3591): Process ARCH arm
W/jxcore-log( 3591): 
,I/jxcore-log( 3591): JXcore Cordova bridge is ready!
I/jxcore-log( 3591): 
W/jxcore-log( 3591): JXcore engine is started
,I/jxcore-log( 3591): Toggling radios to true
,I/jxcore-log( 3591): 
,D/BluetoothAdapter( 3591): enable(): BT is already enabled..!,
,D/WifiService(  821): setWifiEnabled: true pid=3591, uid=10265
E/WifiService(  821): Invoking mWifiStateMachine.setWifiEnabled,
,D/WifiService(  821): New client listening to asynchronous messages,
,I/jxcore-log( 3591): Radios toggled,
I/jxcore-log( 3591): 
,I/jxcore-log( 3591): My device name is: motorola-Nexus 6,
I/jxcore-log( 3591): 
,I/wpa_supplicant( 1137): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1,
,E/WifiStateMachine(  821): WifiStateMachine: Leaving Connected state,
E/WifiConfigStore(  821): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  353): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1249): Read error: ssl=0xb4888800: I/O error during system call, Connection timed out,
,V/NativeCrypto( 1249): SSL shutdown failed: ssl=0xb4888800: I/O error during system call, Broken pipe,
,D/ConnectivityService(  821): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED,
,D/ConnectivityService(  821): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2,
D/ConnectivityService(  821): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10011
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): DefaultState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler },
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): Forcing reevaluation
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): EvaluatingState{ when=-1ms what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
,E/WifiStateMachine(  821): Start Disconnecting Watchdog 1,
,E/WifiStateMachine(  821): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,D/CommandListener(  353): Clearing all IP addresses on wlan0
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
,D/WifiNetworkAgent(  821): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine(  821): CMD_AUTO_CONNECT sup state CompletedState my state DisconnectedState nid=0 roam=3
E/WifiStateMachine(  821): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=0
,D/ConnectivityService(  821): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler( 1062): CM callback handler got msg 524292
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): OfflineState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): Disconnected - quitting
D/CSLegacyTypeTracker(  821): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/Tethering(  821): MasterInitialState.processMessage what=3
,D/NetworkChangeNotifierAutoDetect( 1507): Network connectivity changed, type is: 6
,D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  821): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService(  821): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/ConnectivityService(  821): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
,I/NetworkMonitor( 3322): type=WIFI subType= reason=null isConnected=false
,D/Tethering(  821): MasterInitialState.processMessage what=3
,D/PhoneInterfaceManager( 1308): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
,E/PhoneInterfaceManager( 1308): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  821): getDataEnabled: retVal=false
,V/MusicLeanback( 3322): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,E/GpsLocationProvider(  821): No APN found to select.
,D/PhoneInterfaceManager( 1308): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1308): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  821): getDataEnabled: retVal=false
,E/WifiConfigStore(  821): Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiConfigStore(  821): will read network variables netId=0
,I/ActivityManager(  821): Start proc 3655:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.steen.receiver.ConnectivityChangeReceiver
,E/WifiStateMachine(  821): CMD_AUTO_CONNECT did save config ->  nid=0
E/GpsLocationProvider(  821): No APN found to select.
,E/WifiConfigStore(  821): will read network variables netId=0
,I/ActivityManager(  821): Start proc 3681:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
I/ActivityManager(  821): Killing 3224:com.google.android.apps.photos/u0a71 (adj 15): empty #17
,I/art     (  368): Explicit concurrent mark sweep GC freed 704(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 21MB/36MB, paused 401us total 24.284ms
,I/art     (  368): Explicit concurrent mark sweep GC freed 7(224B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 326us total 13.832ms
,I/art     (  368): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 323us total 14.125ms
,D/SprintDMReceiver( 3681): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3681): simOperator:  IMSI: null
D/SprintDMReceiver( 3681): Not Sprint UICC, don't do anything.
,I/ActivityManager(  821): Killing 3020:com.google.android.apps.fitness/u0a51 (adj 15): empty #17
,I/SystemUpdateService( 1789): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1789): onCreate,
,D/SystemUpdateService( 1789): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1789): active receiver: enabled
,I/SystemUpdateService( 1789): showing system update notification
,I/iu.Environment( 1789): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1789): num queued entries: 0
I/iu.UploadsManager( 1789): num updated entries: 0
,I/iu.SyncManager( 1789): NEXT; no task
,I/ValidateNoPeople(  821): skipping global notification
V/SystemUpdateService( 1789): retry (wakeup: false) in 3599959 ms
,D/ChimeraCfgMgr( 1789): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/SystemUpdateService( 1789): onDestroy
,I/ActivityManager(  821): Start proc 3701:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,I/Babel   ( 2973): connection state changed from UNKNOWN to DISCONNECTED
,I/GAv4    ( 3701): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3701):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3701):   adb logcat -s GAv4
,W/GAv4    ( 3701): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3701): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3701): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 3701): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3701): Time to load native libraries: 2 ms (timestamps 4993-4995)
I/LibraryLoader( 3701): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3701): Binding Chromium to main looper Looper (main, tid 1) {141fb987}
,I/LibraryLoader( 3701): Expected native library version number "",actual native library version number ""
,I/chromium( 3701): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3701): Initializing chromium process, singleProcess=true
,W/art     ( 3701): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3701): ApplicationContext is null in ApplicationStatus
,W/chromium( 3701): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3701): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3701): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3701): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,W/AudioManagerAndroid( 3701): Requires BLUETOOTH permission
,I/NSApplication( 3701): Starting up...
,I/ActivityManager(  821): Start proc 3757:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,I/ActivityManager(  821): Killing 3270:com.android.settings/1000 (adj 15): empty #17
,I/ActivityManager(  821): Start proc 3779:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,I/wpa_supplicant( 1137): wlan0: Trying to associate with SSID 'NG7005g'
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  821): Killing 3289:com.google.android.apps.maps/u0a65 (adj 15): empty #17
,V/MusicLeanback( 3322): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/SprintDMReceiver( 3681): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3681): simOperator:  IMSI: null
D/SprintDMReceiver( 3681): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1789): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/Finsky  ( 3061): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/SystemUpdateService( 1789): onCreate
D/Finsky  ( 3061): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3061): [1] 5.onFinished: Scheduling replication attempt 1.
,D/SystemUpdateService( 1789): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1789): active receiver: enabled
,I/ActivityManager(  821): Killing 3382:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,I/SystemUpdateService( 1789): showing system update notification
,I/wpa_supplicant( 1137): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 1137): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1137): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=0 id_str=]
,D/ConnectivityService(  821): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} }
E/WifiConfigStore(  821): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  821): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  821): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  353): Setting iface cfg
E/WifiStateMachine(  821): Start Dhcp Watchdog 2
E/WifiStateMachine(  821):  WifiLinkLayerStats: 
E/WifiStateMachine(  821):  my bss beacon rx: 196
E/WifiStateMachine(  821):  RSSI mgmt: -51
E/WifiStateMachine(  821):  BE :  rx=170 tx=151 lost=0 retries=1
E/WifiStateMachine(  821):  BK :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  821):  VI :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  821):  VO :  rx=4 tx=0 lost=0 retries=0
E/WifiStateMachine(  821):  on_time : 8274 tx_time=157 rx_time=330 scan_time=0
,D/ChimeraCfgMgr( 1789): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ConnectivityService(  821): updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,I/ValidateNoPeople(  821): skipping global notification
,V/SystemUpdateService( 1789): retry (wakeup: false) in 3599746 ms
,D/SystemUpdateService( 1789): onDestroy
,E/native  (  821): do suspend false
,E/WifiStateMachine(  821): scanCount==0 - aborting
,I/dhcpcd  ( 3810): version 5.5.6 starting
,I/dhcpcd  ( 3810): wlan0: rebinding lease of 192.168.1.122
,I/dhcpcd  ( 3810): wlan0: acknowledged 192.168.1.122 from 192.168.1.1
,I/dhcpcd  ( 3810): wlan0: leased 192.168.1.122 for 86400 seconds
,I/jxcore-log( 3591): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 3591): 
,D/ConnectivityService(  821): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  821): Adding iface wlan0 to network 101
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
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  821): EvaluatingState{ when=-1ms what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  821): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
,D/ConnectivityService(  821): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} }
,D/ConnectivityService(  821): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/CSLegacyTypeTracker(  821): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 1062): CM callback handler got msg 524290
D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  821): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 3322): type=WIFI subType= reason=null isConnected=true
,D/NetworkChangeNotifierAutoDetect( 1507): Network connectivity changed, type is: 2
,D/PhoneInterfaceManager( 1308): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1308): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
V/MusicLeanback( 3322): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/TelephonyManager(  821): getDataEnabled: retVal=false
,D/SprintDMReceiver( 3681): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,E/GpsLocationProvider(  821): No APN found to select.
,D/SprintDMHelper( 3681): simOperator:  IMSI: null
D/SprintDMReceiver( 3681): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1789): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1789): onCreate
,D/SystemUpdateService( 1789): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1789): active receiver: enabled
,I/SystemUpdateService( 1789): showing system update notification
,I/iu.Environment( 1789): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1789): num queued entries: 0
,I/iu.UploadsManager( 1789): num updated entries: 0
,I/iu.SyncManager( 1789): NEXT; no task
,D/ChimeraCfgMgr( 1789): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/ValidateNoPeople(  821): skipping global notification
,V/SystemUpdateService( 1789): retry (wakeup: false) in 3599971 ms
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  821): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 02 Feb 2016 17:25:54 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454433954154], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454433954132]}
,I/art     (  821): Explicit concurrent mark sweep GC freed 49724(2MB) AllocSpace objects, 7(206KB) LOS objects, 32% free, 33MB/49MB, paused 1.980ms total 75.219ms
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  821): Validated
D/ConnectivityService(  821): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/ConnectivityService(  821): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  821): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  821): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  821): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1062): CM callback handler got msg 524290
,D/ChimeraCfgMgr( 1789): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/SystemUpdateService( 1789): onDestroy
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Kids    ( 1789): [AccountUtils] Account not ready
W/Kids    ( 1789): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 1789): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 1789): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 1789): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 1789): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 1789): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 1789): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 1789): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 1789): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 1789): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 1789): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 1789): 	at java.lang.Thread.run(Thread.java:818)
,V/Herrevad( 1789): NQAS connected
,I/Babel   ( 2973): connection state changed from DISCONNECTED to CONNECTED
,D/GCM     ( 1249): Connected
,D/GCM     ( 1249): Message class com.google.f.a.a.p
,I/ActivityManager(  821): Killing 3404:com.android.musicfx/u0a18 (adj 15): empty #17
,I/jxcore-log( 3591): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 3591): 
,I/jxcore-log( 3591): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
,I/jxcore-log( 3591): 
,I/jxcore-log( 3591): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
,I/jxcore-log( 3591): 
,I/jxcore-log( 3591): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,I/jxcore-log( 3591): 
,D/ConnectivityService(  821): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=16.28 rxSuccessRate=15.50 targetRoamBSSID=any RSSI=-51
E/WifiStateMachine(  821): WifiStateMachine L2Connected CMD_START_SCAN source -2 5, 7 -> obsolete
,I/ActivityManager(  821): Killing 3453:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,I/jxcore-log( 3591): Test app app.js loaded
I/jxcore-log( 3591): 
,I/chromium( 3591): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3591): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3591): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3591): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3591): 	Bluetooth MAC address: F8:CF:C5:D9:E5:61, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3591): 	Discovery mode: BLE_AND_WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3591): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3591): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3591): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3591): 	Scan mode: 1
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3591): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@383b27b6 added. We now have 1 listener(s)
,I/jxcore-log( 3591): BLE advertisement is supported
I/jxcore-log( 3591): 
,E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=8.64 rxSuccessRate=8.25 targetRoamBSSID=any RSSI=-51
E/WifiStateMachine(  821): WifiStateMachine L2Connected CMD_START_SCAN source -2 6, 7 -> obsolete
,D/Finsky  ( 3061): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1249): Explicit concurrent mark sweep GC freed 25513(1357KB) AllocSpace objects, 3(330KB) LOS objects, 37% free, 26MB/42MB, paused 1.259ms total 59.497ms
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/Finsky  ( 3061): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.,
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 3061): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 3061): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 3061): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 3061): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3061): [1] DailyHygiene.reschedule: Giving up. (failures=6)
,D/DeviceConnectionService( 1773): client connected with version: 7571000
,E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=1.24 rxSuccessRate=5.57 targetRoamBSSID=any RSSI=-51
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3061): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3061): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3061): [1] 5.onFinished: Scheduling replication attempt 2.
,I/ActivityManager(  821): Start proc 3872:com.google.android.keep/u0a79 for service com.google.android.keep/.syncadapter.KeepSyncAdapterService
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3495): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3495): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3495): 	at jdm.a(PG:82)
E/HttpOperation( 3495): 	at jcs.o(PG:406)
E/HttpOperation( 3495): 	at jcn.a(PG:1379)
E/HttpOperation( 3495): 	at jcs.i(PG:143)
E/HttpOperation( 3495): 	at blb.a(PG:3937)
E/HttpOperation( 3495): 	at czp.a(PG:18188)
E/HttpOperation( 3495): 	at czp.a(PG:9081)
E/HttpOperation( 3495): 	at czq.run(PG:1686)
E/HttpOperation( 3495): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3495): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3495): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3495): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3495): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3495): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3495): 	at jdj.a(PG:4091)
E/HttpOperation( 3495): 	at jdj.a(PG:1125)
E/HttpOperation( 3495): 	at jdm.a(PG:77)
E/HttpOperation( 3495): 	... 12 more
E/HttpOperation( 3495): Caused by: faj: BadAuthentication
E/HttpOperation( 3495): 	at fal.a(PG:38)
E/HttpOperation( 3495): 	at jdj.a(PG:4089)
E/HttpOperation( 3495): 	... 14 more
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/art     ( 1249): Explicit concurrent mark sweep GC freed 20627(1183KB) AllocSpace objects, 5(551KB) LOS objects, 38% free, 25MB/41MB, paused 910us total 21.058ms
,E/HttpOperation( 3495): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3495): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3495): 	at jdm.a(PG:82)
E/HttpOperation( 3495): 	at jcs.o(PG:406)
E/HttpOperation( 3495): 	at jcn.a(PG:1379)
E/HttpOperation( 3495): 	at jcs.i(PG:143)
E/HttpOperation( 3495): 	at hec.a(PG:42)
E/HttpOperation( 3495): 	at hee.a(PG:102)
E/HttpOperation( 3495): 	at czr.a(PG:65)
E/HttpOperation( 3495): 	at kka.a(PG:108)
E/HttpOperation( 3495): 	at czp.a(PG:19176)
E/HttpOperation( 3495): 	at czp.a(PG:9081)
E/HttpOperation( 3495): 	at czq.run(PG:1686)
E/HttpOperation( 3495): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3495): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3495): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3495): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3495): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3495): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3495): 	at jdj.a(PG:4091)
E/HttpOperation( 3495): 	at jdj.a(PG:1125)
E/HttpOperation( 3495): 	at jdm.a(PG:77)
E/HttpOperation( 3495): 	... 15 more
E/HttpOperation( 3495): Caused by: faj: BadAuthentication
E/HttpOperation( 3495): 	at fal.a(PG:38)
E/HttpOperation( 3495): 	at jdj.a(PG:4089)
E/HttpOperation( 3495): 	... 17 more
,E/ExperimentLoader( 3495): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3495): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3495): 	at jdm.a(PG:82)
E/ExperimentLoader( 3495): 	at jcs.o(PG:406)
E/ExperimentLoader( 3495): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3495): 	at jcs.i(PG:143)
E/ExperimentLoader( 3495): 	at hec.a(PG:42)
E/ExperimentLoader( 3495): 	at hee.a(PG:102)
E/ExperimentLoader( 3495): 	at czr.a(PG:65)
E/ExperimentLoader( 3495): 	at kka.a(PG:108)
E/ExperimentLoader( 3495): 	at czp.a(PG:19176)
E/ExperimentLoader( 3495): 	at czp.a(PG:9081)
E/ExperimentLoader( 3495): 	at czq.run(PG:1686)
E/ExperimentLoader( 3495): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3495): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3495): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3495): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3495): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3495): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3495): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3495): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3495): 	at jdm.a(PG:77)
E/ExperimentLoader( 3495): 	... 15 more
E/ExperimentLoader( 3495): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3495): 	at fal.a(PG:38)
E/ExperimentLoader( 3495): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3495): 	... 17 more
,V/KeepSync( 3872): Connecting to GoogleApiClient
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 80026, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager(  821): Start proc 3901:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,I/art     (  821): Explicit concurrent mark sweep GC freed 36181(1683KB) AllocSpace objects, 6(96KB) LOS objects, 32% free, 33MB/49MB, paused 1.748ms total 69.786ms
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1789): Handling authorization failure
E/ClientConnectionOperation( 1789): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1789): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1789): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1789): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1789): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1789): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1789): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1789): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1789): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1789): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1789): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1789): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1789): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1789): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1789): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1789): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1789): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1789): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1789): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1789): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1789): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1789): 	... 7 more
,V/KeepSync( 3872): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3872): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3872): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3872): (284) automatic index on blob_node(is_deleted)
,W/GAV2    ( 3901): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/BooksApp( 3901): Created application version: 3.6.8 (30608)
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/BooksSync( 3901): Starting books sync for 61035162, extras: ade
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3872): IOException
E/KeepSync( 3872): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3872): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3872): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3872): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3872): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3872): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3872): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3872): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3872): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3872): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3872): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3872): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3872): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3872): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3872): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3872): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3872): 	... 10 more
W/KeepSync( 3872): Sync result 2
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 78775, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/BooksConfig( 3901): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3901): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3901): Soft error
E/BooksSync( 3901): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3901): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3901): Sync error
E/BooksSync( 3901): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3901): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3901): Finished books sync
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 80915, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager(  821): Killing 3121:com.google.android.gm/u0a78 (adj 15): empty #17
,E/libprocessgroup(  821): failed to kill 1 processes for processgroup 3121
,I/ActivityManager(  821): Killing 2743:android.process.acore/u0a5 (adj 15): empty #18
,I/GAV2    ( 3901): Thread[GAThread,5,main]: No campaign data found.
,E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.41 rxSuccessRate=1.50 targetRoamBSSID=any RSSI=-52
,E/WifiStateMachine(  821): WifiStateMachine starting scan for "NG7005g"WPA_PSK with 2412,5220
,D/Finsky  ( 3061): [294] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3061): [294] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3061): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3061): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3061): [1] 5.onFinished: Scheduling replication attempt 3.
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,I/Keyboard.Facilitator.LanguageModelFlusher( 1225): run()
I/Keyboard.Facilitator( 1225): flushDynamicLanguageModels()
,I/ConfigService( 1249): onCreate
,I/ConfigService( 1249): onDestroy
,E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.41 rxSuccessRate=2.46 targetRoamBSSID=any RSSI=-51
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3061): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3061): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3061): [1] 5.onFinished: Scheduling replication attempt 4.
,E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=1.33 rxSuccessRate=3.38 targetRoamBSSID=any RSSI=-51
E/WifiStateMachine(  821): WifiStateMachine starting scan for "NG7005g"WPA_PSK with 2412,5220
,I/PowerManagerService(  821): Going to sleep due to screen timeout (uid 1000)...
,I/Adreno  (  821): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/PermissionCache(  259): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (241 us)
,D/SurfaceFlinger(  259): Set power mode=0, type=0 flinger=0xb6482000
I/DisplayManagerService(  821): Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
D/qdhwcomposer(  259): hwc_setPowerMode: Setting mode 0 on display: 0
,V/ActivityManager(  821): Display changed displayId=0
,I/kickstart(  874): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
,I/kickstart(  874): STATUS: Wrote to /sys/power/wake_lock
,E/kickstart(  874): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2
,I/kickstart(  874): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2' for writing
,I/qdhwcomposer(  259): handle_blank_event: dpy:0 panel power state: 0
,D/qdhwcomposer(  259): hwc_setPowerMode: Done setting mode 0 on display 0
,D/SurfaceControl(  821): Excessive delay in setPowerMode(): 286ms
,I/DreamManagerService(  821): Entering dreamland.
,I/PowerManagerService(  821): Dozing...
,I/DreamController(  821): Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,D/audio_hw_primary(  357): adev_set_parameters: enter: screen_state=on
D/mot_vr_audio_hw(  357): adev_set_parameters: screen_state=on
,E/WifiStateMachine(  821): cancelDelayedScan -> 12
,E/native  (  821): do suspend false
,I/Keyboard.Facilitator( 1225): onFinishInput()
,D/audio_hw_primary(  357): adev_set_parameters: enter: screen_state=off
,D/mot_vr_audio_hw(  357): adev_set_parameters: screen_state=off
,E/WifiStateMachine(  821): cancelDelayedScan -> 14
E/native  (  821): do suspend true
,E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-51
E/WifiStateMachine(  821): WifiStateMachine L2Connected CMD_START_SCAN source -2 13, 14 -> obsolete
,I/kickstart(  874): STATUS: Received file 'm9kefs2'
I/kickstart(  874): STATUS: 950272 bytes transferred in 1.002465 seconds
I/kickstart(  874): STATUS: Successfully downloaded files from target 
I/kickstart(  874): STATUS: Wrote to /sys/power/wake_unlock
,I/kickstart(  874): STATUS: Sahara protocol completed
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  821): Explicit concurrent mark sweep GC freed 45702(2MB) AllocSpace objects, 13(302KB) LOS objects, 31% free, 34MB/50MB, paused 1.571ms total 94.598ms
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3061): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3061): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3061): [1] 5.onFinished: Scheduling replication attempt 5.
,V/KeepSync( 3872): Connecting to GoogleApiClient
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/HttpOperation( 3495): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3495): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3495): 	at jdm.a(PG:82)
E/HttpOperation( 3495): 	at jcs.o(PG:406)
E/HttpOperation( 3495): 	at jcn.a(PG:1379)
E/HttpOperation( 3495): 	at jcs.i(PG:143)
E/HttpOperation( 3495): 	at blb.a(PG:3937)
E/HttpOperation( 3495): 	at czp.a(PG:18188)
E/HttpOperation( 3495): 	at czp.a(PG:9081)
E/HttpOperation( 3495): 	at czq.run(PG:1686)
E/HttpOperation( 3495): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3495): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3495): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3495): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3495): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3495): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3495): 	at jdj.a(PG:4091)
E/HttpOperation( 3495): 	at jdj.a(PG:1125)
E/HttpOperation( 3495): 	at jdm.a(PG:77)
E/HttpOperation( 3495): 	... 12 more
E/HttpOperation( 3495): Caused by: faj: BadAuthentication
E/HttpOperation( 3495): 	at fal.a(PG:38)
E/HttpOperation( 3495): 	at jdj.a(PG:4089)
E/HttpOperation( 3495): 	... 14 more
,E/ClientConnectionOperation( 1789): Handling authorization failure
E/ClientConnectionOperation( 1789): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1789): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1789): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1789): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1789): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1789): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1789): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1789): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1789): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1789): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1789): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1789): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1789): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1789): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1789): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1789): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1789): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1789): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1789): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1789): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1789): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1789): 	... 7 more
,V/KeepSync( 3872): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3872): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3872): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3872): (284) automatic index on blob_node(is_deleted),
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3495): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3495): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3495): 	at jdm.a(PG:82)
E/HttpOperation( 3495): 	at jcs.o(PG:406)
E/HttpOperation( 3495): 	at jcn.a(PG:1379)
E/HttpOperation( 3495): 	at jcs.i(PG:143)
E/HttpOperation( 3495): 	at hec.a(PG:42)
E/HttpOperation( 3495): 	at hee.a(PG:102)
E/HttpOperation( 3495): 	at czr.a(PG:65)
E/HttpOperation( 3495): 	at kka.a(PG:108)
E/HttpOperation( 3495): 	at czp.a(PG:19176)
E/HttpOperation( 3495): 	at czp.a(PG:9081)
E/HttpOperation( 3495): 	at czq.run(PG:1686)
E/HttpOperation( 3495): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3495): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3495): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3495): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3495): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3495): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3495): 	at jdj.a(PG:4091)
E/HttpOperation( 3495): 	at jdj.a(PG:1125)
E/HttpOperation( 3495): 	at jdm.a(PG:77)
E/HttpOperation( 3495): 	... 15 more
E/HttpOperation( 3495): Caused by: faj: BadAuthentication
E/HttpOperation( 3495): 	at fal.a(PG:38)
E/HttpOperation( 3495): 	at jdj.a(PG:4089)
E/HttpOperation( 3495): 	... 17 more
,E/ExperimentLoader( 3495): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3495): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3495): 	at jdm.a(PG:82)
E/ExperimentLoader( 3495): 	,at jcs.o(PG:406)
E/ExperimentLoader( 3495): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3495): 	at jcs.i(PG:143)
E/ExperimentLoader( 3495): 	at hec.a(PG:42)
E/ExperimentLoader( 3495): 	at hee.a(PG:102)
E/ExperimentLoader( 3495): 	at czr.a(PG:65)
,E/ExperimentLoader( 3495): 	at kka.a(PG:108)
E/ExperimentLoader( 3495): 	at czp.a(PG:19176)
E/ExperimentLoader( 3495): 	at czp.a(PG:9081)
E/ExperimentLoader( 3495): 	at czq.run(PG:1686)
E/ExperimentLoader( 3495): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3495): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3495): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3495): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3495): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3495): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3495): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3495): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3495): 	at jdm.a(PG:77)
E/ExperimentLoader( 3495): 	... 15 more
E/ExperimentLoader( 3495): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3495): 	at fal.a(PG:38)
E/ExperimentLoader( 3495): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3495): 	,... 17 more
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1249): Explicit concurrent mark sweep GC freed 30738(1838KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 1.136ms total 35.151ms,
,E/KeepSync( 3872): IOException
E/KeepSync( 3872): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3872): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3872): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3872): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3872): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3872): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3872): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3872): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3872): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3872): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3872): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3872): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3872): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3872): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3872): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3872): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3872): 	... 10 more
W/KeepSync( 3872): Sync result 2
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 140894, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 139416, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/BooksSync( 3901): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3901): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3901): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3901): Soft error
E/BooksSync( 3901): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3901): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3901): Sync error
E/BooksSync( 3901): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3901): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 3901): Finished books sync
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 142073, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-51
,E/WifiStateMachine(  821): WifiStateMachine L2Connected CMD_START_SCAN source -2 11, 14 -> obsolete
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GoogleAuthProtoRequest( 3655): [391] a.<init>: mAccountName set to: thalitester@gmail.com
,I/VacuumService( 1249): Vacuum at: now=1454434062569 tag=VacuumService
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3061): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3061): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3061): [1] 5.onFinished: Giving up after 6 failures.
,I/GoogleURLConnFactory( 1249): Using platform SSLCertificateSocketFactory
,W/ExperimentUpdateService( 3655): [391] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3655): [391] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3655): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3655): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3655): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3655): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3655): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3655): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3655): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3655): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3655): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3655): 	at com.a.a.k.run(SourceFile:110)
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1249): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1249): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1249): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1249): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1249): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1249): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1249): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1249): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1249): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1249): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1249): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1249): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1249): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1249): No account for auth token provided
,W/Uploader( 1249): No account for auth token provided
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1249): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1249): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1249): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1249): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1249): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1249): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1249): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1249): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1249): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1249): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1249): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1249): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1249): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,W/Uploader( 1249): No account for auth token provided
,W/Uploader( 1249): No account for auth token provided
,W/Uploader( 1249): No account for auth token provided
,W/Uploader( 1249): No account for auth token provided
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1249): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1249): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1249): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1249): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1249): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1249): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1249): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1249): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1249): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1249): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1249): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1249): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1249): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1249): No account for auth token provided
,W/Uploader( 1249): No account for auth token provided
,W/Uploader( 1249): No account for auth token provided
,W/Uploader( 1249): No account for auth token provided
,W/Uploader( 1249): No account for auth token provided
,W/Uploader( 1249):  no longer exists, so no auth token.
,I/art     (  821): Explicit concurrent mark sweep GC freed 33301(1455KB) AllocSpace objects, 6(284KB) LOS objects, 31% free, 34MB/50MB, paused 1.185ms total 91.172ms
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1249): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1249): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1249): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1249): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1249): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1249): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1249): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1249): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1249): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1249): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1249): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1249): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1249): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,V/GoogleAuthProtoRequest( 3655): [392] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3655): [392] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3655): [392] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3655): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3655): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3655): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3655): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3655): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3655): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3655): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3655): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3655): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3655): 	at com.a.a.k.run(SourceFile:110)
,I/Keyboard.Facilitator.LanguageModelFlusher( 1225): run()
,I/Keyboard.Facilitator( 1225): flushDynamicLanguageModels()
,I/ConfigService( 1249): onCreate
,I/ConfigService( 1249): onDestroy
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3495): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3495): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3495): 	at jdm.a(PG:82)
E/HttpOperation( 3495): 	at jcs.o(PG:406)
E/HttpOperation( 3495): 	at jcn.a(PG:1379)
E/HttpOperation( 3495): 	at jcs.i(PG:143)
E/HttpOperation( 3495): 	at blb.a(PG:3937)
E/HttpOperation( 3495): 	at czp.a(PG:18188)
E/HttpOperation( 3495): 	at czp.a(PG:9081)
E/HttpOperation( 3495): 	at czq.run(PG:1686)
E/HttpOperation( 3495): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3495): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3495): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3495): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3495): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3495): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3495): 	at jdj.a(PG:4091)
E/HttpOperation( 3495): 	at jdj.a(PG:1125)
E/HttpOperation( 3495): 	at jdm.a(PG:77)
E/HttpOperation( 3495): 	... 12 more
E/HttpOperation( 3495): Caused by: faj: BadAuthentication
E/HttpOperation( 3495): 	at fal.a(PG:38)
E/HttpOperation( 3495): 	at jdj.a(PG:4089)
E/HttpOperation( 3495): 	... 14 more
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3495): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3495): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3495): 	at jdm.a(PG:82)
E/HttpOperation( 3495): 	at jcs.o(PG:406)
E/HttpOperation( 3495): 	at jcn.a(PG:1379)
E/HttpOperation( 3495): 	at jcs.i(PG:143)
E/HttpOperation( 3495): 	at hec.a(PG:42)
E/HttpOperation( 3495): 	at hee.a(PG:102)
E/HttpOperation( 3495): 	at czr.a(PG:65)
E/HttpOperation( 3495): 	at kka.a(PG:108)
E/HttpOperation( 3495): 	at czp.a(PG:19176)
E/HttpOperation( 3495): 	at czp.a(PG:9081)
E/HttpOperation( 3495): 	at czq.run(PG:1686)
E/HttpOperation( 3495): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3495): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3495): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3495): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3495): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3495): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3495): 	at jdj.a(PG:4091)
E/HttpOperation( 3495): 	at jdj.a(PG:1125)
E/HttpOperation( 3495): 	at jdm.a(PG:77)
E/HttpOperation( 3495): 	... 15 more
E/HttpOperation( 3495): Caused by: faj: BadAuthentication
E/HttpOperation( 3495): 	at fal.a(PG:38)
E/HttpOperation( 3495): 	at jdj.a(PG:4089)
E/HttpOperation( 3495): 	... 17 more
,E/ExperimentLoader( 3495): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3495): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3495): 	at jdm.a(PG:82)
E/ExperimentLoader( 3495): 	at jcs.o(PG:406)
E/ExperimentLoader( 3495): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3495): 	at jcs.i(PG:143)
E/ExperimentLoader( 3495): 	at hec.a(PG:42)
E/ExperimentLoader( 3495): ,	at hee.a(PG:102)
E/ExperimentLoader( 3495): 	at czr.a(PG:65)
E/ExperimentLoader( 3495): 	at kka.a(PG:108)
E/ExperimentLoader( 3495): 	at czp.a(PG:19176)
E/ExperimentLoader( 3495): 	at czp.a(PG:9081)
E/ExperimentLoader( 3495): 	at czq.run(PG:1686)
E/ExperimentLoader( 3495): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3495): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3495): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3495): 	,at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3495): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3495): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3495): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3495): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3495): 	at jdm.a(PG:77)
E/ExperimentLoader( 3495): 	... 15 more
E/ExperimentLoader( 3495): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3495): ,	at fal.a(PG:38)
E/ExperimentLoader( 3495): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3495): 	... 17 more
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 230072, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,I/BooksSync( 3901): Starting books sync for 61035162, extras: ade
,V/KeepSync( 3872): Connecting to GoogleApiClient
,I/BooksConfig( 3901): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1789): Handling authorization failure
E/ClientConnectionOperation( 1789): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1789): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1789): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1789): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1789): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1789): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1789): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1789): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1789): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1789): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1789): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1789): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1789): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1789): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1789): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1789): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1789): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1789): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1789): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1789): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1789): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1789): 	... 7 more
,V/KeepSync( 3872): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3872): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3872): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3872): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1249): Explicit concurrent mark sweep GC freed 72828(4MB) AllocSpace objects, 8(642KB) LOS objects, 36% free, 28MB/44MB, paused 1.407ms total 46.208ms,
,E/BooksAccountManager( 3901): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3901): Soft error
E/BooksSync( 3901): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3901): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3901): Sync error
E/BooksSync( 3901): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3901): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 3901): Finished books sync
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 233889, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,E/KeepSync( 3872): IOException
E/KeepSync( 3872): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3872): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3872): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3872): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3872): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3872): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3872): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3872): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3872): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3872): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3872): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3872): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3872): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3872): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3872): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3872): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3872): 	... 10 more
W/KeepSync( 3872): Sync result 2
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 232420, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,V/GoogleAuthProtoRequest( 3655): [393] a.<init>: mAccountName set to: thalitester@gmail.com,
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3655): [393] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3655): [393] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3655): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3655): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3655): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3655): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3655): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3655): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3655): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3655): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3655): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3655): 	at com.a.a.k.run(SourceFile:110)
,I/ActivityManager(  821): Start proc 4024:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider
,I/GAv4    ( 4024): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4024):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4024):   adb logcat -s GAv4
,W/GAv4    ( 4024): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4024): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4024): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  821): Killing 2307:com.google.android.calendar/u0a37 (adj 15): empty #17,
,D/WifiService(  821): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@25d984bb}
,E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-51,
,D/WifiService(  821): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@25d984bb}
,E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::injectLocation(GpsExtLocation):857]: error! inject position failed
,I/art     (  821): Explicit concurrent mark sweep GC freed 33820(1535KB) AllocSpace objects, 13(679KB) LOS objects, 31% free, 34MB/50MB, paused 2.493ms total 107.426ms
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3495): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3495): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3495): 	at jdm.a(PG:82)
E/HttpOperation( 3495): 	at jcs.o(PG:406)
E/HttpOperation( 3495): 	at jcn.a(PG:1379)
E/HttpOperation( 3495): 	at jcs.i(PG:143)
E/HttpOperation( 3495): 	at blb.a(PG:3937)
E/HttpOperation( 3495): 	at czp.a(PG:18188)
E/HttpOperation( 3495): 	at czp.a(PG:9081)
E/HttpOperation( 3495): 	at czq.run(PG:1686)
E/HttpOperation( 3495): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3495): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3495): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3495): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3495): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3495): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3495): 	at jdj.a(PG:4091)
E/HttpOperation( 3495): 	at jdj.a(PG:1125)
E/HttpOperation( 3495): 	at jdm.a(PG:77)
E/HttpOperation( 3495): 	... 12 more
E/HttpOperation( 3495): Caused by: faj: BadAuthentication
E/HttpOperation( 3495): 	at fal.a(PG:38)
E/HttpOperation( 3495): 	at jdj.a(PG:4089)
E/HttpOperation( 3495): 	... 14 more
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3495): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3495): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3495): 	at jdm.a(PG:82)
E/HttpOperation( 3495): 	at jcs.o(PG:406)
E/HttpOperation( 3495): 	at jcn.a(PG:1379)
E/HttpOperation( 3495): 	at jcs.i(PG:143)
E/HttpOperation( 3495): 	at hec.a(PG:42)
E/HttpOperation( 3495): 	at hee.a(PG:102)
E/HttpOperation( 3495): 	at czr.a(PG:65)
E/HttpOperation( 3495): 	at kka.a(PG:108)
E/HttpOperation( 3495): 	at czp.a(PG:19176)
E/HttpOperation( 3495): 	at czp.a(PG:9081)
E/HttpOperation( 3495): 	at czq.run(PG:1686)
E/HttpOperation( 3495): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3495): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3495): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3495): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3495): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3495): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3495): 	at jdj.a(PG:4091)
E/HttpOperation( 3495): 	at jdj.a(PG:1125)
E/HttpOperation( 3495): 	at jdm.a(PG:77)
E/HttpOperation( 3495): 	... 15 more
E/HttpOperation( 3495): Caused by: faj: BadAuthentication
E/HttpOperation( 3495): 	at fal.a(PG:38)
E/HttpOperation( 3495): 	at jdj.a(PG:4089)
E/HttpOperation( 3495): 	... 17 more
E/ExperimentLoader( 3495): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3495): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3495): 	at jdm.a(PG:82)
E/ExperimentLoader( 3495): 	at jcs.o(PG:406)
E/ExperimentLoader( 3495): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3495): 	at jcs.i(PG:143)
E/ExperimentLoader( 3495): 	at hec.a(PG:42)
E/ExperimentLoader( 3495): 	at hee.a(PG:102)
E/ExperimentLoader( 3495): 	at czr.a(PG:65)
E/ExperimentLoader( 3495): 	at kka.a(PG:108)
E/ExperimentLoader( 3495): 	at czp.a(PG:19176)
E/ExperimentLoader( 3495): 	at czp.a(PG:9081)
E/ExperimentLoader( 3495): 	at czq.run(PG:1686)
E/ExperimentLoader( 3495): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3495): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3495): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3495): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3495): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3495): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3495): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3495): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3495): 	at jdm.a(PG:77)
E/ExperimentLoader( 3495): 	... 15 more
E/ExperimentLoader( 3495): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3495): 	at fal.a(PG:38)
E/ExperimentLoader( 3495): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3495): 	... 17 more
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 352740, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/GLSActivity( 1249): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1249): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1249): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1249): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1249): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1249): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1249): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 3061): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3061): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3061): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 3061): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3061): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/PlayEventLogger( 3061): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3061): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 3061): Ignoring header User-Agent because its value was null.
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,I/BooksSync( 3901): Starting books sync for 61035162, extras: ade
,V/KeepSync( 3872): Connecting to GoogleApiClient
,I/BooksConfig( 3901): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1789): Handling authorization failure
E/ClientConnectionOperation( 1789): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1789): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1789): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1789): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1789): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1789): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1789): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1789): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1789): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1789): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1789): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1789): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1789): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1789): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1789): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1789): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1789): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1789): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1789): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1789): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1789): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1789): 	... 7 more
,V/KeepSync( 3872): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3872): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3872): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3872): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3901): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3901): Soft error
E/BooksSync( 3901): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3901): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3901): Sync error
E/BooksSync( 3901): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3901): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3901): Finished books sync
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 390036, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3872): IOException
E/KeepSync( 3872): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3872): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3872): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3872): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3872): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3872): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3872): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3872): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3872): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3872): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3872): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3872): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3872): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3872): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3872): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3872): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3872): 	... 10 more
W/KeepSync( 3872): Sync result 2
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 387447, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,V/GoogleAuthProtoRequest( 3655): [394] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3655): [394] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3655): [394] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3655): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3655): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3655): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3655): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3655): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3655): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3655): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3655): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3655): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3655): 	at com.a.a.k.run(SourceFile:110)
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3495): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception,
E/HttpOperation( 3495): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3495): ,	at jdm.a(PG:82)
E/HttpOperation( 3495): 	at jcs.o(PG:406),
E/HttpOperation( 3495): 	at jcn.a(PG:1379)
E/HttpOperation( 3495): 	,at jcs.i(PG:143)
E/HttpOperation( 3495): 	at blb.a(PG:3937)
E/HttpOperation( 3495): ,	at czp.a(PG:18188)
E/HttpOperation( 3495): 	at czp.a(PG:9081)
E/HttpOperation( 3495): ,	at czq.run(PG:1686)
E/HttpOperation( 3495): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3495): ,	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3495): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
,E/HttpOperation( 3495): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3495): 	at java.lang.Thread.run(Thread.java:818),
E/HttpOperation( 3495): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3495): 	at jdj.a(PG:4091)
,E/HttpOperation( 3495): 	at jdj.a(PG:1125)
E/HttpOperation( 3495): 	at jdm.a(PG:77)
E/HttpOperation( 3495): 	... 12 more
E/HttpOperation( 3495): Caused by: faj: BadAuthentication
E/HttpOperation( 3495): 	at fal.a(PG:38)
E/HttpOperation( 3495): 	at jdj.a(PG:4089)
E/HttpOperation( 3495): 	... 14 more
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3495): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3495): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3495): 	at jdm.a(PG:82)
E/HttpOperation( 3495): 	at jcs.o(PG:406)
E/HttpOperation( 3495): 	at jcn.a(PG:1379)
E/HttpOperation( 3495): 	at jcs.i(PG:143)
E/HttpOperation( 3495): 	at hec.a(PG:42)
E/HttpOperation( 3495): 	at hee.a(PG:102)
E/HttpOperation( 3495): 	at czr.a(PG:65)
E/HttpOperation( 3495): 	at kka.a(PG:108)
E/HttpOperation( 3495): 	at czp.a(PG:19176)
E/HttpOperation( 3495): 	at czp.a(PG:9081)
E/HttpOperation( 3495): 	at czq.run(PG:1686)
E/HttpOperation( 3495): 	,at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3495): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3495): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3495): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3495): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3495): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3495): 	at jdj.a(PG:4091)
E/HttpOperation( 3495): 	at jdj.a(PG:1125)
E/HttpOperation( 3495): 	at jdm.a(PG:77)
E/HttpOperation( 3495): 	... 15 more
E/HttpOperation( 3495): Caused by: faj: BadAuthentication
E/HttpOperation( 3495): 	at fal.a(PG:38)
E/HttpOperation( 3495): 	at jdj.a(PG:4089)
E/HttpOperation( 3495): 	... 17 more
E/ExperimentLoader( 3495): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3495): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3495): 	at jdm.a(PG:82)
E/ExperimentLoader( 3495): 	at jcs.o(PG:406)
E/ExperimentLoader( 3495): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3495): 	at jcs.i(PG:143)
E/ExperimentLoader( 3495): 	at hec.a(PG:42)
E/ExperimentLoader( 3495): 	at hee.a(PG:102),
E/ExperimentLoader( 3495): 	at czr.a(PG:65)
E/ExperimentLoader( 3495): 	at kka.a(PG:108)
E/ExperimentLoader( 3495): 	at czp.a(PG:19176)
E/ExperimentLoader( 3495): 	at czp.a(PG:9081)
E/ExperimentLoader( 3495): 	at czq.run(PG:1686)
E/ExperimentLoader( 3495): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3495): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3495): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3495): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3495): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3495): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3495): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3495): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3495): 	at jdm.a(PG:77)
E/ExperimentLoader( 3495): 	... 15 more
E/ExperimentLoader( 3495): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3495): 	at fal.a(PG:38)
E/ExperimentLoader( 3495): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3495): 	... 17 more
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 597569, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,V/CheckinService( 1789): unknown intent received for checkin (Intent { flg=0x14 cmp=com.google.android.gms/.checkin.CheckinService$Receiver (has extras) })
,I/EventLogService( 1789): Opted in for usage reporting
,I/EventLogService( 1789): Aggregate from 1454432727483 (log), 1454432727483 (data)
,I/CheckinService( 1789): Checking schedule, now: 1454434542792 next: 1454434541913
I/CheckinService( 1789): active receiver: enabled
,V/GoogleAuthProtoRequest( 3655): [395] a.<init>: mAccountName set to: thalitester@gmail.com
,I/CheckinService( 1789): Preparing to send checkin request
,V/KeepSync( 3872): Connecting to GoogleApiClient
,I/art     ( 1249): Explicit concurrent mark sweep GC freed 55759(2MB) AllocSpace objects, 17(1874KB) LOS objects, 36% free, 27MB/43MB, paused 1.032ms total 59.324ms
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/art     (  821): Explicit concurrent mark sweep GC freed 40419(1810KB) AllocSpace objects, 9(426KB) LOS objects, 31% free, 34MB/50MB, paused 1.049ms total 53.950ms
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3655): [395] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3655): [395] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3655): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3655): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3655): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3655): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3655): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3655): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3655): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3655): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3655): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3655): 	at com.a.a.k.run(SourceFile:110)
,W/EventLogAggregator( 1789): Unknown tag: snet_gcore
W/EventLogAggregator( 1789): Unknown tag: snet_launch_service
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/EventLogService( 1789): Accumulating logs since 1454434542951
,I/EventLogService( 1789): Opted in for usage reporting
,E/ClientConnectionOperation( 1789): Handling authorization failure
E/ClientConnectionOperation( 1789): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1789): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1789): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1789): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1789): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1789): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1789): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1789): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1789): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1789): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1789): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1789): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1789): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1789): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1789): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1789): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1789): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1789): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1789): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1789): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1789): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1789): 	... 7 more
,V/KeepSync( 3872): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3872): (284) automatic index on blob_node(is_deleted)
,I/ServiceDumpSys( 1789): dumping service [account]
,E/SQLiteLog( 3872): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3872): (284) automatic index on blob_node(is_deleted)
,I/CheckinRequestBuilder( 1789): Checkin reason type: 11 attempt count: 1
,E/ActivityThread( 1789): Failed to find provider info for com.google.android.wearable.settings
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3872): IOException
E/KeepSync( 3872): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3872): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3872): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3872): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3872): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3872): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3872): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3872): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3872): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3872): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3872): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3872): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3872): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3872): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3872): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3872): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3872): 	... 10 more
W/KeepSync( 3872): Sync result 2
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 667010, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/CheckinRequestBuilder( 1789): awaiting user notification for token
,I/ActivityManager(  821): Start proc 4136:com.google.android.gms.unstable/u0a11 for service com.google.android.gms/.droidguard.DroidGuardService
,W/ResourcesManager( 4136): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 4136): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 4136): VM with version 2.1.0 has multidex support
I/MultiDex( 4136): install
I/MultiDex( 4136): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 4136): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ProviderInstaller( 4136): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 1249): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1249): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 1789): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/WearableService( 3424): callingUid 10011, callindPid: 3424
,E/MDM     ( 1773): [138] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 1789): Restart initialization of location
,D/WVCdm   (  357): Instantiating CDM.
,I/WVCdm   (  357): CdmEngine::OpenSession
I/WVCdm   (  357): Level3 Library Dec 11 2014 16:13:16
,W/WVCdm   (  357): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  357): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x11
D/DrmWidevineDash(  357): Service_Initialize: starts!
D/QSEECOMAPI: (  357): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  357): App is not loaded in QSEE
,I/GoogleURLConnFactory( 4136): Using platform SSLCertificateSocketFactory
,D/QSEECOMAPI: (  357): Loaded image: APP id = 3
,D/DrmWidevineDash(  357): Service_Initialize: ends! returns 0
,D/DrmWidevineDash(  357): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb3a92000
E/DrmWidevineDash(  357): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb3a92000
,D/DrmLibTime(  312): got the req here! ret=0
,D/DrmLibTime(  312): command id, time_cmd_id = 770
D/DrmLibTime(  312): time_getutcsec starts!
D/DrmLibTime(  312): QSEE Time Listener: time_getutcsec
D/DrmLibTime(  312): QSEE Time Listener: get_utc_seconds
D/DrmLibTime(  312): QSEE Time Listener: seconds: 1454434543
D/DrmLibTime(  312): QSEE Time Listener: nano seconds: 966149031
D/DrmLibTime(  312): time_getutcsec returns 0, sec = 1454434543; nsec = 966149031
D/DrmLibTime(  312): time_getutcsec finished! 
D/DrmLibTime(  312): iotcl_continue_command finished! and return 0 
D/DrmLibTime(  312): before calling ioctl to read the next time_cmd
,D/DrmWidevineDash(  357): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  357): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  357): hlos api version =  9
D/DrmWidevineDash(  357): tz api version =  9,
D/DrmWidevineDash(  357): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  357): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  357): OEMCrypto_IsKeyboxValid: ends! returns 0
,D/WVCdm   (  357): OEMCrypto_Initialize Level 1 success. I will use level 1.
,D/DrmWidevineDash(  357): OEMCrypto_OpenSession: starts! SID=0xb3e03940,
D/DrmWidevineDash(  357): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  357): OEMCrypto_OpenSession: ends! returns 0,
D/DrmWidevineDash(  357): OEMCrypto_GetRandom: starts! randomData=0xb5876968, dataLength=8
,D/DrmWidevineDash(  357): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  357): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb400e000, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  357): OEMCrypto_LoadDeviceRSAKey: ends! returns 0,
I/WVCdm   (  357): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  357): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  357): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  357): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  357): OEMCrypto_GetDeviceID: starts! deviceID=0xb4c71440, idLength=0xb3d05710
,D/DrmWidevineDash(  357): OEMCrypto_GetDeviceID: ends! returns 0
,D/DrmWidevineDash(  357): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  357): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  357): OEMCrypto_SupportsUsageTable: wv_app_version = 21
D/DrmWidevineDash(  357): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  357): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  357): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  357): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  357): hlos api version =  9
D/DrmWidevineDash(  357): tz api version =  9
D/DrmWidevineDash(  357): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  357): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  357): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  357): PrepareKeyRequest: nonce=175678880
D/DrmWidevineDash(  357): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb4cf6600
D/DrmWidevineDash(  357): message_length=1598, signature=0xb4c52780, signature_length=3016775412
,D/DrmWidevineDash(  357): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  357): CdmEngine::CloseSession
D/DrmWidevineDash(  357): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  357): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  357): L3 Terminate.
D/DrmWidevineDash(  357): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  357): Service_Uninitialize: starts!
D/QSEECOMAPI: (  357): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  357): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  357): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  357): OEMCrypto_Terminate: ends! returns 0
,I/WVCdm   (  357): CdmEngine::OpenSession
I/WVCdm   (  357): Level3 Library Dec 11 2014 16:13:16
,W/WVCdm   (  357): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory,
,D/DrmWidevineDash(  357): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x11
,D/DrmWidevineDash(  357): Service_Initialize: starts!
,D/QSEECOMAPI: (  357): QSEECom_get_handle sb_length = 0x19000
,D/QSEECOMAPI: (  357): App is not loaded in QSEE
,D/QSEECOMAPI: (  357): Loaded image: APP id = 3
,D/DrmWidevineDash(  357): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  357): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb3a92000
E/DrmWidevineDash(  357): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb3a92000
,D/DrmLibTime(  312): got the req here! ret=0,
D/DrmLibTime(  312): command id, time_cmd_id = 770
D/DrmLibTime(  312): time_getutcsec starts!
D/DrmLibTime(  312): QSEE Time Listener: time_getutcsec
,D/DrmLibTime(  312): QSEE Time Listener: get_utc_seconds
D/DrmLibTime(  312): QSEE Time Listener: seconds: 1454434544
D/DrmLibTime(  312): QSEE Time Listener: nano seconds: 758929239
D/DrmLibTime(  312): time_getutcsec returns 0, sec = 1454434544; nsec = 758929239
D/DrmLibTime(  312): time_getutcsec finished! ,
D/DrmLibTime(  312): iotcl_continue_command finished! and return 0 
D/DrmLibTime(  312): before calling ioctl to read the next time_cmd,
D/DrmWidevineDash(  357): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  357): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  357): hlos api version =  9
D/DrmWidevineDash(  357): tz api version =  9
,D/DrmWidevineDash(  357): OEMCrypto_APIVersion: ends! returns version 9
,D/DrmWidevineDash(  357): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  357): OEMCrypto_IsKeyboxValid: ends! returns 0,
D/WVCdm   (  357): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  357): OEMCrypto_OpenSession: starts! SID=0xb3f01940
,D/DrmWidevineDash(  357): OEMCrypto_OpenSession SID = 1,
,D/DrmWidevineDash(  357): OEMCrypto_OpenSession: ends! returns 0
,D/DrmWidevineDash(  357): OEMCrypto_GetRandom: starts! randomData=0xb4c4e3f0, dataLength=8
D/DrmWidevineDash(  357): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  357): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb4cc0600, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  357): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  357): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  357): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  357): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  357): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  357): OEMCrypto_GetDeviceID: starts! deviceID=0xb4c71480, idLength=0xb3d05710
,D/DrmWidevineDash(  357): OEMCrypto_GetDeviceID: ends! returns 0,
D/DrmWidevineDash(  357): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  357): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  357): OEMCrypto_SupportsUsageTable: wv_app_version = 21
D/DrmWidevineDash(  357): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  357): OEMCrypto_GetHDCPCapability: starts!
,D/DrmWidevineDash(  357): OEMCrypto_GetHDCPCapability: ends! returns 0x0
,D/DrmWidevineDash(  357): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  357): hlos api version =  9
D/DrmWidevineDash(  357): tz api version =  9
D/DrmWidevineDash(  357): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  357): OEMCrypto_GenerateNonce: starts! SID=1
,D/DrmWidevineDash(  357): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  357): PrepareKeyRequest: nonce=458190644
,D/DrmWidevineDash(  357): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb4cf6600
D/DrmWidevineDash(  357): message_length=1634, signature=0xb4c52780, signature_length=3016775412
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,D/DrmWidevineDash(  357): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  357): CdmEngine::CloseSession,
D/DrmWidevineDash(  357): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  357): OEMCrypto_CloseSession: ends! returns 0
,I/WVCdm   (  357): L3 Terminate.
D/DrmWidevineDash(  357): OEMCrypto_Terminate: starts!
,D/DrmWidevineDash(  357): Service_Uninitialize: starts!,
D/QSEECOMAPI: (  357): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  357): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  357): Service_Uninitialize: ends! returns 0x0,
D/DrmWidevineDash(  357): OEMCrypto_Terminate: ends! returns 0
,I/dex2oat ( 4167): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=39 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 4167): dex2oat took 56.151ms (threads: 4) arena alloc=96KB java alloc=18KB native alloc=1246KB free=6MB
,I/Adreno  ( 4136): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,I/Adreno  ( 4136): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,I/EventLogService( 1789): Opted in for usage reporting
,I/CheckinTask( 1789): Sending checkin request (9971 bytes)
,I/CheckinRequestBuilder( 1789): Checkin reason type: 11 attempt count: 1
,E/ActivityThread( 1789): Failed to find provider info for com.google.android.wearable.settings
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/CheckinRequestBuilder( 1789): awaiting user notification for token
,I/EventLogService( 1789): Opted in for usage reporting
,I/CheckinTask( 1789): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1789): Checking schedule, now: 1454434546481 next: 1454475689468
I/CheckinService( 1789): active receiver: disabled
,D/ChimeraCfgMgr( 1789): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 1789): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/GCM     ( 1249): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Kids    ( 1789): [AccountUtils] Account not ready
W/Kids    ( 1789): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 1789): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 1789): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 1789): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 1789): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 1789): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 1789): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 1789): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 1789): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 1789): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 1789): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 1789): 	at java.lang.Thread.run(Thread.java:818)
,I/ActivityManager(  821): Killing 3322:com.google.android.music:main/u0a66 (adj 15): empty #17
,I/InputReader(  821): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager(  821): Start proc 4184:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,V/GmsNetworkLocationProvi( 1773): DISABLE
,D/BackupManagerService(  821): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  821): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  821): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,D/PackageBroadcastService( 1789): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1789): Null package name or gms related package.  Ignoreing.
,I/UpdateIcingCorporaServi( 1507): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/Launcher( 1338): Deferring update until onResume
,W/Launcher( 1338): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@86f17db new=com.google.android.velvet.VelvetApplication@86f17db
,I/Icing   ( 1789): updateResources: need to parse f{com.google.android.gms}
,I/art     ( 1249): Explicit concurrent mark sweep GC freed 31016(1561KB) AllocSpace objects, 11(1213KB) LOS objects, 37% free, 27MB/43MB, paused 1.082ms total 43.803ms
,V/GmsNetworkLocationProvi( 1773): onSetRequest: ProviderRequestUnbundled, reportLocation is true and interval is 86400000
,V/BackupManagerService(  821): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  821): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@23c06344
,V/GmsNetworkLocationProvi( 1773): ENABLE
,V/GmsNetworkLocationProvi( 1773): SET-REQUEST
,V/GmsNetworkLocationProvi( 1773): in Handler: ProviderRequestUnbundled, reportLocation is true and interval is 86400000
,I/ContactLocale( 4184): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,V/BackupManagerService(  821): Scheduling immediate backup pass
V/BackupManagerService(  821): Running a backup pass
V/BackupManagerService(  821): clearing pending backups
,V/PerformBackupTask(  821): Beginning backup of 14 targets
,D/PerformBackupTask(  821): invokeAgentForBackup on @pm@
,V/BackupServiceBinder(  821): doBackup() invoked
,I/PMBA    (  821): Previous metadata 1570415 mismatch vs 1743759 - rewriting
,I/art     (  821): Explicit concurrent mark sweep GC freed 24975(1242KB) AllocSpace objects, 6(378KB) LOS objects, 31% free, 34MB/50MB, paused 1.458ms total 59.446ms
,I/BackupRestoreController(  821): Getting widget state for user: 0
,I/UpdateIcingCorporaServi( 1507): UpdateCorporaTask done [took 94 ms] updated apps [took 94 ms] 
,W/GmsBackupTransport( 1773): Unknown package in backup request: @pm@
,V/GmsBackupTransport( 1773): starting performBackup for @pm@
,V/GmsBackupTransport( 1773): performBackup done for @pm@
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: android
,I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> android without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1249): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1249): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1249): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1249): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1249): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1249): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1249): 	at android.os.Binder.execTransact(Binder.java:446)
,W/GmsBackupTransport( 1773): Error sending final backup to server: 
W/GmsBackupTransport( 1773): com.google.android.gms.backup.d.d: Can not get client auth token
W/GmsBackupTransport( 1773): 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:1080)
W/GmsBackupTransport( 1773): 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:65)
W/GmsBackupTransport( 1773): 	at com.google.android.gms.backup.aa.finishBackup(SourceFile:409)
W/GmsBackupTransport( 1773): 	at android.app.backup.BackupTransport$TransportImpl.finishBackup(BackupTransport.java:547)
W/GmsBackupTransport( 1773): 	at com.android.internal.backup.IBackupTransport$Stub.onTransact(IBackupTransport.java:162)
W/GmsBackupTransport( 1773): 	at android.os.Binder.execTransact(Binder.java:446)
W/GmsBackupTransport( 1773): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
W/GmsBackupTransport( 1773): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
W/GmsBackupTransport( 1773): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
W/GmsBackupTransport( 1773): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
W/GmsBackupTransport( 1773): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
W/GmsBackupTransport( 1773): 	... 1 more
,D/BackupManagerService(  821): Now staging backup of com.google.android.talk
,D/BackupManagerService(  821): Now staging backup of com.google.android.dialer
,D/BackupManagerService(  821): Now staging backup of com.android.providers.settings
,D/BackupManagerService(  821): Now staging backup of com.android.sharedstoragebackup
,D/BackupManagerService(  821): Now staging backup of com.google.android.gm
,D/BackupManagerService(  821): Now staging backup of com.android.providers.userdictionary
,D/BackupManagerService(  821): Now staging backup of com.android.nfc
,D/BackupManagerService(  821): Now staging backup of com.google.android.apps.genie.geniewidget
,D/BackupManagerService(  821): Now staging backup of com.google.android.marvin.talkback
,D/BackupManagerService(  821): Now staging backup of com.google.android.inputmethod.latin
,D/BackupManagerService(  821): Now staging backup of com.google.android.calendar
,D/BackupManagerService(  821): Now staging backup of com.android.vending
,D/BackupManagerService(  821): Now staging backup of android
,D/BackupManagerService(  821): Now staging backup of com.google.android.googlequicksearchbox
,I/GmsBackupTransport( 1773): Next backup will happen in 43199964 millis.
,I/BackupManagerService(  821): Backup pass finished.
,I/ActivityManager(  821): Killing 3681:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,I/BooksSync( 3901): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3901): GmsCore Version = 7.8.99 (2134222-430)
,V/GoogleAuthProtoRequest( 3655): [396] a.<init>: mAccountName set to: thalitester@gmail.com
,V/GoogleAuthProtoRequest( 3655): [397] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3655): [397] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3655): [396] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3655): [396] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3655): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3655): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3655): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3655): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3655): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3655): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3655): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3655): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3655): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3655): 	at com.a.a.k.run(SourceFile:110)
,W/ExperimentUpdateService( 3655): [397] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3655): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3655): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3655): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3655): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3655): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3655): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3655): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3655): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3655): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3655): 	at com.a.a.k.run(SourceFile:110)
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3901): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3901): Soft error
E/BooksSync( 3901): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3901): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source),
E/BooksSync( 3901): Sync error
E/BooksSync( 3901): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3901): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3901): Finished books sync
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 672187, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,V/GoogleAuthProtoRequest( 3655): [398] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3655): [398] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3655): [398] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3655): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3655): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3655): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3655): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3655): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3655): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3655): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3655): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3655): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3655): 	at com.a.a.k.run(SourceFile:110)
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,V/GoogleAuthProtoRequest( 3655): [399] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3655): [399] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3655): [399] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3655): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3655): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3655): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3655): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3655): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3655): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3655): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3655): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3655): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3655): 	at com.a.a.k.run(SourceFile:110)
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,W/bt-btm  ( 2395): Stopping oneshot timer
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,D/GCM     ( 1249): Message class com.google.f.a.a.i
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3495): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3495): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3495): 	at jdm.a(PG:82)
E/HttpOperation( 3495): 	at jcs.o(PG:406)
E/HttpOperation( 3495): 	at jcn.a(PG:1379)
E/HttpOperation( 3495): 	at jcs.i(PG:143)
E/HttpOperation( 3495): 	at blb.a(PG:3937)
E/HttpOperation( 3495): 	at czp.a(PG:18188)
E/HttpOperation( 3495): 	at czp.a(PG:9081)
E/HttpOperation( 3495): 	at czq.run(PG:1686)
E/HttpOperation( 3495): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3495): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3495): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3495): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3495): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3495): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3495): 	at jdj.a(PG:4091)
E/HttpOperation( 3495): 	at jdj.a(PG:1125)
E/HttpOperation( 3495): 	at jdm.a(PG:77)
E/HttpOperation( 3495): 	... 12 more
E/HttpOperation( 3495): Caused by: faj: BadAuthentication
E/HttpOperation( 3495): 	at fal.a(PG:38)
E/HttpOperation( 3495): 	at jdj.a(PG:4089)
E/HttpOperation( 3495): 	... 14 more
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3495): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3495): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3495): 	at jdm.a(PG:82)
E/HttpOperation( 3495): 	at jcs.o(PG:406)
E/HttpOperation( 3495): 	at jcn.a(PG:1379)
E/HttpOperation( 3495): 	at jcs.i(PG:143)
E/HttpOperation( 3495): 	at hec.a(PG:42)
E/HttpOperation( 3495): 	at hee.a(PG:102)
E/HttpOperation( 3495): 	at czr.a(PG:65)
E/HttpOperation( 3495): 	at kka.a(PG:108)
E/HttpOperation( 3495): 	at czp.a(PG:19176)
E/HttpOperation( 3495): 	at czp.a(PG:9081)
E/HttpOperation( 3495): 	at czq.run(PG:1686)
E/HttpOperation( 3495): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3495): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3495): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3495): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3495): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3495): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3495): 	at jdj.a(PG:4091)
E/HttpOperation( 3495): 	at jdj.a(PG:1125)
E/HttpOperation( 3495): 	at jdm.a(PG:77)
E/HttpOperation( 3495): 	... 15 more
E/HttpOperation( 3495): Caused by: faj: BadAuthentication
E/HttpOperation( 3495): 	at fal.a(PG:38)
E/HttpOperation( 3495): 	at jdj.a(PG:4089)
E/HttpOperation( 3495): 	... 17 more
,E/ExperimentLoader( 3495): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3495): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3495): 	at jdm.a(PG:82)
E/ExperimentLoader( 3495): 	at jcs.o(PG:406)
E/ExperimentLoader( 3495): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3495): 	at jcs.i(PG:143)
E/ExperimentLoader( 3495): 	at hec.a(PG:42)
E/ExperimentLoader( 3495): 	at hee.a(PG:102)
E/ExperimentLoader( 3495): 	at czr.a(PG:65)
E/ExperimentLoader( 3495): 	at kka.a(PG:108)
E/ExperimentLoader( 3495): 	at czp.a(PG:19176)
E/ExperimentLoader( 3495): 	at czp.a(PG:9081)
E/ExperimentLoader( 3495): 	at czq.run(PG:1686)
E/ExperimentLoader( 3495): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3495): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3495): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3495): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3495): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3495): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3495): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3495): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3495): 	at jdm.a(PG:77)
E/ExperimentLoader( 3495): 	... 15 more
E/ExperimentLoader( 3495): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3495): 	at fal.a(PG:38)
E/ExperimentLoader( 3495): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3495): 	... 17 more
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 1086809, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,V/GoogleAuthProtoRequest( 3655): [400] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3655): [400] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3655): [400] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3655): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3655): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3655): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3655): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3655): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3655): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3655): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3655): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3655): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3655): 	at com.a.a.k.run(SourceFile:110)
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,I/art     (  821): Explicit concurrent mark sweep GC freed 41240(2024KB) AllocSpace objects, 7(489KB) LOS objects, 31% free, 34MB/50MB, paused 1.674ms total 80.756ms
,V/KeepSync( 3872): Connecting to GoogleApiClient
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1789): Handling authorization failure,
E/ClientConnectionOperation( 1789): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1789): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1789): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1789): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1789): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1789): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1789): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1789): 	,at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1789): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1789): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1789): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1789): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1789): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1789): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1789): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1789): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1789): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1789): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1789): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1789): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
,E/ClientConnectionOperation( 1789): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1789): 	... 7 more
V/KeepSync( 3872): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3872): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3872): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3872): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3872): IOException
E/KeepSync( 3872): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3872): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3872): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3872): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3872): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3872): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3872): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3872): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3872): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3872): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3872): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3872): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3872): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3872): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3872): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3872): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3872): 	... 10 more
,W/KeepSync( 3872): Sync result 2
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 1174950, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,V/GoogleAuthProtoRequest( 3655): [401] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1249): Explicit concurrent mark sweep GC freed 59905(3MB) AllocSpace objects, 10(1102KB) LOS objects, 36% free, 27MB/43MB, paused 1.562ms total 62.205ms
,W/ExperimentUpdateService( 3655): [401] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3655): [401] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3655): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3655): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3655): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3655): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3655): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3655): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3655): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3655): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3655): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3655): 	at com.a.a.k.run(SourceFile:110)
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,I/UsageStatsService(  821): User[0] Flushing usage stats to disk
,I/BooksSync( 3901): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3901): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3901): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3901): Soft error
E/BooksSync( 3901): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3901): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3901): Sync error
E/BooksSync( 3901): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3901): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 3901): Finished books sync,
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1215683, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0,
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 4332): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 4332): CheckJNI is OFF
D/AndroidRuntime( 4332): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  821): Force stopping com.test.thalitest appid=10265 user=-1: uninstall pkg
I/ActivityManager(  821): Killing 3591:com.test.thalitest/u0a265 (adj 0): stop com.test.thalitest
W/PackageSettings(  821): Skipping PackageSetting{c74a6dc com.example.hello/10273} due to missing metadata
D/WifiService(  821): Client connection lost with reason: 4
E/libprocessgroup(  821): failed to kill 1 processes for processgroup 3591
W/ActivityManager(  821): Force removing ActivityRecord{19773e58 u0 com.test.thalitest/.MainActivity t28}: app died, no saved state
W/WindowManager(  821): Failed looking up window
W/WindowManager(  821): java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@3345b864 does not exist
W/WindowManager(  821): 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8539)
W/WindowManager(  821): 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8530)
W/WindowManager(  821): 	at com.android.server.wm.WindowState$DeathRecipient.binderDied(WindowState.java:1142)
W/WindowManager(  821): 	at android.os.BinderProxy.sendDeathNotice(Binder.java:551)
I/WindowState(  821): WIN DEATH: null
V/ActivityManager(  821): Display changed displayId=0
I/ActivityManager(  821): Force stopping com.test.thalitest appid=10265 user=0: pkg removed
D/TaskPersister(  821): removeObsoleteFile: deleting file=28_task.xml
I/InputReader(  821): Reconfiguring input devices.  changes=0x00000010
D/BuaReceiver( 3365): ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
I/Keyboard.Facilitator( 1225): resetDictionaries() : en_US
I/art     ( 1062): Explicit concurrent mark sweep GC freed 75500(3MB) AllocSpace objects, 0(0B) LOS objects, 18% free, 72MB/88MB, paused 708us total 50.158ms
I/art     ( 1773): Explicit concurrent mark sweep GC freed 18318(1105KB) AllocSpace objects, 13(208KB) LOS objects, 37% free, 26MB/42MB, paused 8.534ms total 44.499ms
E/DataBuffer( 1773): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2b1e94ce)
I/Keyboard.Facilitator.DecoderInitializer( 1225): run()
I/Decoder ( 1225): createOrResetDecoder
I/art     (  821): Explicit concurrent mark sweep GC freed 23440(1378KB) AllocSpace objects, 10(348KB) LOS objects, 31% free, 34MB/50MB, paused 1.142ms total 81.093ms
I/art     (  821): WaitForGcToComplete blocked for 36.083ms for cause Explicit
I/art     ( 1507): Explicit concurrent mark sweep GC freed 7911(591KB) AllocSpace objects, 1(24KB) LOS objects, 22% free, 27MB/35MB, paused 383us total 102.992ms
I/ActivityManager(  821): Start proc 4348:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
I/ConfigService( 1249): onCreate
D/VoicemailCleanupService( 4184): Cleaning up data for package: com.test.thalitest
W/InputMethodManagerService(  821): Got RemoteException sending setActive(false) notification to pid 3591 uid 10265
I/Keyboard.Facilitator( 1225): onFinishInput()
I/Keyboard.Facilitator.MainLanguageModelLoader( 1225): run()
D/JobSchedulerService(  821): Receieved: android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  821): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/Keyboard.Facilitator.MainLanguageModelLoader( 1225): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/ActivityManager(  821): Start proc 4374:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1225): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1225): run() : Loading LM = contacts
W/LocationOracleImpl( 1507): Best location was null
I/art     ( 1338): Explicit concurrent mark sweep GC freed 12393(709KB) AllocSpace objects, 12(1408KB) LOS objects, 31% free, 35MB/51MB, paused 636us total 26.775ms
I/HotwordRecognitionRnr( 1507): Starting hotword detection.
I/MicrophoneInputStream( 1507): mic_starting com.google.android.apps.gsa.speech.audio.u@2d577447
I/AudioFlinger(  357): AudioFlinger's thread 0xb409d000 ready to run
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1225): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1225): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1225): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1225): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1225): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1225): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1225): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1225): run()
I/StatsUtilsManager( 1225): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1225): shouldRecordStats() = Too Soon
I/SoundTriggerHwService::Module(  357): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/MicrophoneInputStream( 1507): mic_started com.google.android.apps.gsa.speech.audio.u@2d577447
D/audio_hw_primary(  357): select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
D/msm8974_platform(  357): platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
E/ACDB-LOADER(  357): Error: ACDB AudProc vol returned = -19
D/audio_hw_primary(  357): enable_snd_device: snd_device(55: voice-rec-mic)
I/art     (  821): Explicit concurrent mark sweep GC freed 5352(256KB) AllocSpace objects, 2(220KB) LOS objects, 31% free, 34MB/50MB, paused 2.822ms total 140.465ms
D/audio_hw_primary(  357): enable_audio_route: apply and update mixer path: audio-record
W/ContextImpl( 4374): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2609 
E/NetworkScheduler.SchedulerReceiver( 1249): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1249): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
D/WifiService(  821): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@44770d4}
D/PackageBroadcastService( 1789): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/ChimeraCfgMgr( 1789): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1789): Module APK com.google.android.play.games already loaded
E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=25.00 rxSuccessRate=39.00 targetRoamBSSID=any RSSI=-51
D/AccountUtils( 1789): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1789): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1789): Module APK com.google.android.play.games already loaded
I/LocationSettingsChecker( 1789): Removing dialog suppression flag for package com.test.thalitest
W/Launcher( 1338): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@86f17db new=com.google.android.velvet.VelvetApplication@86f17db
D/GOOGLEHELP_CompatibleDatabase( 1789): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1789): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1789): 0 metrics were deleted when clearing package com.test.thalitest.
D/GOOGLEHELP_CompatibleDatabase( 1789): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
I/HotwordWorker( 1507): onReady
D/GOOGLEHELP_CompatibleDatabase( 1789): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1789): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/GOOGLEHELP_CompatibleDatabase( 1789): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
I/UpdateIcingCorporaServi( 1507): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
D/GOOGLEHELP_CompatibleDatabase( 1789): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1789): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/GOOGLEHELP_CompatibleDatabase( 1789): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/GOOGLEHELP_CompatibleDatabase( 1789): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/GOOGLEHELP_CompatibleDatabase( 1789): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/GOOGLEHELP_CompatibleDatabase( 1789): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/ActivityManager(  821): Start proc 4417:com.google.android.apps.docs/u0a46 for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
I/ConfigFetchService( 1789): onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1703011603
E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
I/art     (  368): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 21MB/36MB, paused 234us total 15.853ms
I/ConfigFetchService( 1789): service connected
W/BaseAppContext( 1789): Using Auth Proxy for data requests.
I/PeopleContactsSync( 1789): CP2 sync disabled
I/Icing   ( 1789): doRemovePackageData com.test.thalitest
W/BaseAppContext( 1789): Using Auth Proxy for data requests.
E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=95.50 rxSuccessRate=223.50 targetRoamBSSID=any RSSI=-51
I/art     (  368): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 1.558ms total 18.699ms
I/art     (  368): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 193us total 9.951ms
I/UpdateIcingCorporaServi( 1507): UpdateCorporaTask done [took 74 ms] updated apps [took 74 ms] 
I/art     ( 4332): System.exit called, status: 0
I/AndroidRuntime( 4332): VM exiting with result code 0.
D/Launcher.Workspace( 1338): 11683562 - stripEmptyScreens()
D/Launcher.Workspace( 1338): 11683562 - stripEmptyScreens()
I/kickstart(  874): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
I/kickstart(  874): STATUS: Wrote to /sys/power/wake_lock
E/kickstart(  874): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1
I/kickstart(  874): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1' for writing
I/GAv4    ( 4417): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4417):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4417):   adb logcat -s GAv4
W/GAv4    ( 4417): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 4417): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
E/SharedPreferencesImpl( 4417): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4417): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4417): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
E/SharedPreferencesImpl( 4417): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/AnalyticsTrackerProxyImpl( 4417): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
E/SQLiteDatabase( 4417): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 4417): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4417): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4417): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4417): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4417): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4417): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4417): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4417): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4417): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4417): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4417): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4417): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4417): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4417): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4417): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 4417): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 4417): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 4417): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 4417): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 4417): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 4417): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4417): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4417): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4417): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4417): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 4417): 	at gir$c.run(Unknown Source)
E/GAv4    ( 4417): Opening the database failed, dropping the table and recreating it
E/SharedPreferencesImpl( 4417): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SQLiteDatabase( 4417): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 4417): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4417): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4417): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4417): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4417): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4417): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4417): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4417): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4417): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4417): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4417): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4417): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4417): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4417): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4417): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 4417): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 4417): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 4417): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 4417): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 4417): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 4417): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4417): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4417): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4417): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4417): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 4417): 	at gir$c.run(Unknown Source)
E/GAv4    ( 4417): Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 4417): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4417): Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 4417): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4417): Job execution failed: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 4417): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SQLiteDatabase( 4417): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4417): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4417): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4417): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4417): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4417): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4417): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4417): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4417): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4417): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4417): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4417): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4417): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4417): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4417): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4417): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 4417): 	at ael.a(PG:1521)
E/SQLiteDatabase( 4417): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 4417): 	at aen.run(PG:536)
W/GAv4    ( 4417): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SQLiteDatabase( 4417): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4417): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4417): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4417): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4417): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4417): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4417): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4417): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4417): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4417): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4417): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4417): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4417): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4417): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4417): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4417): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 4417): 	at ael.a(PG:1521)
E/SQLiteDatabase( 4417): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 4417): 	at aej.c(PG:139)
E/SQLiteDatabase( 4417): 	at aej.b(PG:398)
E/SQLiteDatabase( 4417): 	at agf.f(PG:417)
E/SQLiteDatabase( 4417): 	at oe.run(PG:1112)
E/SQLiteDatabase( 4417): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4417): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4417): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4417): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4417): 	at java.lang.Thread.run(Thread.java:818)
E/AbstractDatabaseInstance( 4417): Failed to delete from CachedSearch133
E/AbstractDatabaseInstance( 4417): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AbstractDatabaseInstance( 4417): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AbstractDatabaseInstance( 4417): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AbstractDatabaseInstance( 4417): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AbstractDatabaseInstance( 4417): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AbstractDatabaseInstance( 4417): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AbstractDatabaseInstance( 4417): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AbstractDatabaseInstance( 4417): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AbstractDatabaseInstance( 4417): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AbstractDatabaseInstance( 4417): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AbstractDatabaseInstance( 4417): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AbstractDatabaseInstance( 4417): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AbstractDatabaseInstance( 4417): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AbstractDatabaseInstance( 4417): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AbstractDatabaseInstance( 4417): 	at aev.getWritableDatabase(PG:238)
E/AbstractDatabaseInstance( 4417): 	at ael.a(PG:1521)
E/AbstractDatabaseInstance( 4417): 	at hix$a.a(PG:125)
E/AbstractDatabaseInstance( 4417): 	at aej.c(PG:139)
E/AbstractDatabaseInstance( 4417): 	at aej.b(PG:398)
E/AbstractDatabaseInstance( 4417): 	at agf.f(PG:417)
E/AbstractDatabaseInstance( 4417): 	at oe.run(PG:1112)
E/AbstractDatabaseInstance( 4417): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/AbstractDatabaseInstance( 4417): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AbstractDatabaseInstance( 4417): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AbstractDatabaseInstance( 4417): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AbstractDatabaseInstance( 4417): 	at java.lang.Thread.run(Thread.java:818)
E/SharedPreferencesImpl( 4417): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4417): Job execution failed: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4417): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4417): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4417): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4417): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4417): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4417): Failed to commit local dispatch transaction: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4417): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4417): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4417): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4417): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4417): Sync local dispatch failed: android.database.sqlite.SQLiteException: Database open failed
W/GAv4    ( 4417): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4417): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4417): syncDispatchLocalHits failed: java.util.concurrent.ExecutionException: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4417): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4417): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/CAKEMIX_CRASHED( 4417): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/CAKEMIX_CRASHED( 4417): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/CAKEMIX_CRASHED( 4417): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/CAKEMIX_CRASHED( 4417): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/CAKEMIX_CRASHED( 4417): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/CAKEMIX_CRASHED( 4417): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/CAKEMIX_CRASHED( 4417): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/CAKEMIX_CRASHED( 4417): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/CAKEMIX_CRASHED( 4417): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/CAKEMIX_CRASHED( 4417): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/CAKEMIX_CRASHED( 4417): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/CAKEMIX_CRASHED( 4417): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/CAKEMIX_CRASHED( 4417): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/CAKEMIX_CRASHED( 4417): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/CAKEMIX_CRASHED( 4417): 	at aev.getWritableDatabase(PG:238)
E/CAKEMIX_CRASHED( 4417): 	at ael.a(PG:1521)
E/CAKEMIX_CRASHED( 4417): 	at hix$a.a(PG:125)
E/CAKEMIX_CRASHED( 4417): 	at aen.run(PG:536)
W/ResourcesManager( 4417): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4417): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  821): Start proc 4455:com.android.documentsui/u0a45 for broadcast com.android.documentsui/.PackageReceiver
I/ActivityManager(  821): START u0 {act=android.intent.action.BUG_REPORT flg=0x10000000 cmp=com.google.android.apps.docs/.app.ErrorNotificationActivity (has extras)} from uid 10046 on display 0
V/WindowManager(  821): addAppToken: AppWindowToken{372ee00b token=Token{2b9323da ActivityRecord{13f7e985 u0 com.google.android.apps.docs/.app.ErrorNotificationActivity t29}}} to stack=1 task=29 at 0
I/Process ( 4417): Sending signal. PID: 4417 SIG: 9
I/HotwordDetector( 1507): Closing mic
I/MicrophoneInputStream( 1507): mic_close com.google.android.apps.gsa.speech.audio.u@2d577447
E/lowmemorykiller(  256): Error writing /proc/4417/oom_score_adj; errno=22
E/JavaBinder(  821): !!! FAILED BINDER TRANSACTION !!!
W/ActivityManager(  821): Exception when starting activity com.google.android.apps.docs/.app.ErrorNotificationActivity
W/ActivityManager(  821): android.os.TransactionTooLargeException
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
D/audio_hw_primary(  357): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  357): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  357): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1507): Hotword detection finished
I/HotwordRecognitionRnr( 1507): Stopping hotword detection.
I/ActivityManager(  821): Start proc 4472:com.google.android.apps.docs/u0a46 for activity com.google.android.apps.docs/.app.ErrorNotificationActivity
W/ActivityManager(  821): Spurious death for ProcessRecord{11e0764 4472:com.google.android.apps.docs/u0a46}, curProc for 4417: null
W/OpenGLRenderer( 1338): Incorrectly called buildLayer on View: ew, destroying layer...
E/Search.SharedPreferencesProto( 1507): Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
I/ActivityManager(  821): Killing 3701:com.google.android.apps.magazines/u0a67 (adj 15): empty #17
E/SQLiteDatabase( 4455): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 4455): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4455): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4455): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4455): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4455): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4455): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4455): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4455): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4455): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4455): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4455): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4455): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4455): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4455): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4455): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/SQLiteDatabase( 4455): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/SQLiteDatabase( 4455): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:370)
E/SQLiteDatabase( 4455): 	at android.content.ContentResolver.call(ContentResolver.java:1372)
E/SQLiteDatabase( 4455): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/SQLiteDatabase( 4455): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2609)
E/SQLiteDatabase( 4455): 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
E/SQLiteDatabase( 4455): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1380)
E/SQLiteDatabase( 4455): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4455): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 4455): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
E/SQLiteDatabase( 4455): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 4455): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 4455): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
E/SQLiteDatabase( 4455): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/AndroidRuntime( 4455): Shutting down VM
--------- beginning of crash
E/AndroidRuntime( 4455): FATAL EXCEPTION: main
E/AndroidRuntime( 4455): Process: com.android.documentsui, PID: 4455
E/AndroidRuntime( 4455): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4455): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2616)
E/AndroidRuntime( 4455): 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
E/AndroidRuntime( 4455): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1380)
E/AndroidRuntime( 4455): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4455): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 4455): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
E/AndroidRuntime( 4455): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 4455): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 4455): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
E/AndroidRuntime( 4455): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
E/AndroidRuntime( 4455): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4455): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4455): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 4455): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 4455): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4455): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4455): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4455): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AndroidRuntime( 4455): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AndroidRuntime( 4455): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 4455): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AndroidRuntime( 4455): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 4455): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 4455): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 4455): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/AndroidRuntime( 4455): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/AndroidRuntime( 4455): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:370)
E/AndroidRuntime( 4455): 	at android.content.ContentResolver.call(ContentResolver.java:1372)
E/AndroidRuntime( 4455): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/AndroidRuntime( 4455): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2609)
E/AndroidRuntime( 4455): 	... 9 more
I/ActivityManager(  821): Killing 3757:com.android.chrome/u0a40 (adj 15): empty #17
E/native  ( 1225): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1225): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
I/Icing   ( 1789): Indexing 0A4562BF807829C124E952811A67787B55D6217E from com.google.android.googlequicksearchbox
I/ActivityManager(  821): Start proc 4495:com.android.externalstorage/u0a10 for content provider com.android.externalstorage/.ExternalStorageProvider
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
E/Icing   ( 1789): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.deleted for write failed: Read-only file system
E/Icing   ( 1789): Could not init tag ds.tag.deleted
I/OpenGLRenderer(  821): Initialized EGL, version 1.4
I/GAv4    ( 4472): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4472):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4472):   adb logcat -s GAv4
D/OpenGLRenderer(  821): Enabling debug mode 0
W/GAv4    ( 4472): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
E/native  ( 1225): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1225): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/SharedPreferencesImpl( 4472): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4472): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
D/ExternalStorage( 4495): After updating volumes, found 1 active roots
E/SharedPreferencesImpl( 4472): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/native  ( 1225): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1225): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
W/AnalyticsTrackerProxyImpl( 4472): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
E/native  ( 1225): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1225): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
I/ActivityManager(  821): Killing 3779:com.google.android.apps.photos/u0a71 (adj 15): empty #17
W/GAv4    ( 4472): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
E/SharedPreferencesImpl( 4472): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/kickstart(  874): ERROR: function: rx_data:267 Timeout Occured, No response or command came from the target!
I/kickstart(  874): WARNING: function: sahara_start:892 Retrying memory read request
E/SQLiteDatabase( 4472): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 4472): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4472): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4472): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4472): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4472): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4472): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4472): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4472): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4472): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4472): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4472): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4472): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4472): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4472): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4472): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 4472): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 4472): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 4472): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 4472): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 4472): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 4472): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4472): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4472): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4472): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4472): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 4472): 	at gir$c.run(Unknown Source)
E/GAv4    ( 4472): Opening the database failed, dropping the table and recreating it
E/SharedPreferencesImpl( 4472): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SQLiteDatabase( 4472): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 4472): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4472): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4472): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4472): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4472): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4472): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4472): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4472): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4472): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4472): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4472): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4472): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4472): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4472): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4472): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 4472): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 4472): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 4472): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 4472): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 4472): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 4472): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4472): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4472): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4472): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4472): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 4472): 	at gir$c.run(Unknown Source)
E/GAv4    ( 4472): Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 4472): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4472): Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 4472): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SQLiteDatabase( 4472): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4472): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4472): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4472): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4472): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4472): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4472): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4472): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4472): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4472): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4472): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4472): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4472): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4472): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4472): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4472): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 4472): 	at ael.a(PG:1521)
E/SQLiteDatabase( 4472): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 4472): 	at aen.run(PG:536)
E/GAv4    ( 4472): Job execution failed: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 4472): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SQLiteDatabase( 4472): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4472): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4472): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4472): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4472): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4472): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4472): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4472): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4472): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4472): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4472): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4472): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4472): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4472): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4472): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4472): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 4472): 	at ael.a(PG:1521)
E/SQLiteDatabase( 4472): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 4472): 	at aej.c(PG:139)
E/SQLiteDatabase( 4472): 	at aej.b(PG:398)
E/SQLiteDatabase( 4472): 	at agf.f(PG:417)
E/SQLiteDatabase( 4472): 	at oe.run(PG:1112)
E/SQLiteDatabase( 4472): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4472): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4472): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4472): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4472): 	at java.lang.Thread.run(Thread.java:818)
E/AbstractDatabaseInstance( 4472): Failed to delete from CachedSearch133
E/AbstractDatabaseInstance( 4472): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AbstractDatabaseInstance( 4472): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AbstractDatabaseInstance( 4472): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AbstractDatabaseInstance( 4472): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AbstractDatabaseInstance( 4472): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AbstractDatabaseInstance( 4472): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AbstractDatabaseInstance( 4472): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AbstractDatabaseInstance( 4472): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AbstractDatabaseInstance( 4472): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AbstractDatabaseInstance( 4472): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AbstractDatabaseInstance( 4472): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AbstractDatabaseInstance( 4472): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AbstractDatabaseInstance( 4472): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AbstractDatabaseInstance( 4472): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AbstractDatabaseInstance( 4472): 	at aev.getWritableDatabase(PG:238)
E/AbstractDatabaseInstance( 4472): 	at ael.a(PG:1521)
E/AbstractDatabaseInstance( 4472): 	at hix$a.a(PG:125)
E/AbstractDatabaseInstance( 4472): 	at aej.c(PG:139)
E/AbstractDatabaseInstance( 4472): 	at aej.b(PG:398)
E/AbstractDatabaseInstance( 4472): 	at agf.f(PG:417)
E/AbstractDatabaseInstance( 4472): 	at oe.run(PG:1112)
E/AbstractDatabaseInstance( 4472): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/AbstractDatabaseInstance( 4472): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AbstractDatabaseInstance( 4472): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AbstractDatabaseInstance( 4472): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AbstractDatabaseInstance( 4472): 	at java.lang.Thread.run(Thread.java:818)
I/Icing   ( 1789): Indexing done 0A4562BF807829C124E952811A67787B55D6217E
W/ResourcesManager( 4472): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4472): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
E/Icing   ( 1789): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.status for write failed: Read-only file system
E/Icing   ( 1789): Writing status failed
E/Icing   ( 1789): Error while writing to AppDataSearch-main-config-corpus-scratch-data.tmp: java.io.FileNotFoundException: /data/data/com.google.android.gms/files/AppDataSearch/main/AppDataSearch-main-config-corpus-scratch-data.tmp: open failed: EROFS (Read-only file system)
E/ErrorNotificationActivity( 4472): Google Drive has stopped unexpectedly. Please provide additional details to help us diagnose the issue.
D/WifiService(  821): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@44770d4}
V/JNIHelp ( 4472): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
D/OpenGLRenderer( 4472): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
D/Atlas   ( 4472): Validating map...
V/WindowManager(  821): Adding window Window{1d1bb160 u0 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity} at 2 of 8 (after Window{103100cd u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
V/WindowManager(  821): Adding window Window{2bab96de u0 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity} at 2 of 9 (before Window{1d1bb160 u0 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity})
W/GAv4    ( 4472): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4472): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4472): Job execution failed: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4472): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4472): Error opening database: android.database.sqlite.SQLiteException: Database open failed
W/GAv4    ( 4472): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4472): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4472): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.goog,le.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4472): Failed to commit local dispatch transaction: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4472): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4472): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4472): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4472): Sync local dispatch failed: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4472): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4472): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4472): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4472): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4472): syncDispatchLocalHits failed: java.util.concurrent.ExecutionException: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4472): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/CAKEMIX_CRASHED( 4472): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/CAKEMIX_CRASHED( 4472): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/CAKEMIX_CRASHED( 4472): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/CAKEMIX_CRASHED( 4472): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/CAKEMIX_CRASHED( 4472): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/CAKEMIX_CRASHED( 4472): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/CAKEMIX_CRASHED( 4472): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/CAKEMIX_CRASHED( 4472): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/CAKEMIX_CRASHED( 4472): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/CAKEMIX_CRASHED( 4472): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/CAKEMIX_CRASHED( 4472): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/CAKEMIX_CRASHED( 4472): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/CAKEMIX_CRASHED( 4472): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/CAKEMIX_CRASHED( 4472): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/CAKEMIX_CRASHED( 4472): 	at aev.getWritableDatabase(PG:238)
E/CAKEMIX_CRASHED( 4472): 	at ael.a(PG:1521)
E/CAKEMIX_CRASHED( 4472): 	at hix$a.a(PG:125)
E/CAKEMIX_CRASHED( 4472): 	at aen.run(PG:536)
I/ProviderInstaller( 4472): Installed default security provider GmsCore_OpenSSL
I/ActivityManager(  821): START u0 {act=android.intent.action.BUG_REPORT flg=0x10000000 cmp=com.google.android.apps.docs/.app.ErrorNotificationActivity (has extras)} from uid 10046 on display 0
I/Process ( 4472): Sending signal. PID: 4472 SIG: 9
I/WindowState(  821): WIN DEATH: Window{1d1bb160 u0 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity}
I/ActivityThread( 4455): Removing dead content provider:android.content.ContentProviderProxy@3abe98c
I/ActivityManager(  821): Process com.google.android.apps.docs (pid 4472) has died
W/InputDispatcher(  821): channel '2bab96de com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
E/InputDispatcher(  821): channel '2bab96de com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity (server)' ~ Channel is unrecoverably broken and will be disposed!
I/WindowState(  821): WIN DEATH: Window{2bab96de u0 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity}
W/InputDispatcher(  821): Attempted to unregister already unregistered input channel '2bab96de com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity (server)'
W/ActivityManager(  821): Force removing ActivityRecord{13f7e985 u0 com.google.android.apps.docs/.app.ErrorNotificationActivity t29}: app died, no saved state
W/Documents( 4455): Failed to load some roots from com.google.android.apps.docs.storage: android.os.DeadObjectException
D/Documents( 4455): Update found 6 roots in 985ms
I/ActivityManager(  821): Killing 3251:com.android.providers.calendar/u0a3 (adj 15): empty #17
E/SharedPreferencesImpl( 1789): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/tron_prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/tron_prefs.xml.bak
E/SQLiteDatabase( 1249): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 1249): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1249): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1249): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1249): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1249): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1249): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1249): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1249): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1249): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1249): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1249): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 1249): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 1249): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 1249): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1249): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 1249): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:99)
E/SQLiteDatabase( 1249): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/SQLiteDatabase( 1249): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/SQLiteDatabase( 1249): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/SQLiteDatabase( 1249): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 1249): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 1249): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteOpenHelper( 1249): Couldn't open phenotype.db for writing (will try read-only):
E/SQLiteOpenHelper( 1249): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1249): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1249): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 1249): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 1249): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1249): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1249): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1249): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteOpenHelper( 1249): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteOpenHelper( 1249): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 1249): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteOpenHelper( 1249): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 1249): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 1249): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 1249): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 1249): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:99)
E/SQLiteOpenHelper( 1249): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/SQLiteOpenHelper( 1249): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/SQLiteOpenHelper( 1249): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/SQLiteOpenHelper( 1249): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteOpenHelper( 1249): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteOpenHelper( 1249): 	at java.lang.Thread.run(Thread.java:818)
W/SQLiteOpenHelper( 1249): Opened phenotype.db in read-only mode

```
