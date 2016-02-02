#### Test 575312431be71d2_thali05_motorola-Nexus 6 Logs


```
--------- beginning of system
,I/ActivityManager(  821): Waited long enough for: ServiceRecord{1465236a u0 com.motorola.android.buacontactadapter/.AuthenticationService}
--------- beginning of main
D/AndroidRuntime( 3770): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 3770): CheckJNI is OFF
D/AndroidRuntime( 3770): Calling main entry com.android.commands.am.Am
I/ActivityManager(  821): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/WindowManager(  821): addAppToken: AppWindowToken{21809f23 token=Token{10969052 ActivityRecord{59bdcdd u0 com.test.thalitest/.MainActivity t28}}} to stack=1 task=28 at 0
D/AndroidRuntime( 3770): Shutting down VM
I/MicrophoneInputStream( 1528): mic_close com.google.android.apps.gsa.speech.audio.u@1f5d3701
I/HotwordDetector( 1528): Closing mic
V/WindowManager(  821): Adding window Window{2c155a4c u0 Starting com.test.thalitest} at 2 of 7 (after Window{1efe96b4 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
I/ActivityManager(  821): Start proc 3784:com.test.thalitest/u0a265 for activity com.test.thalitest/.MainActivity
D/audio_hw_primary(  357): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  357): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  357): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1528): Stopping hotword detection.
I/HotwordRecognitionRnr( 1528): Hotword detection finished
I/ActivityManager(  821): Killing 3308:com.android.settings/1000 (adj 15): empty #17
,I/WebViewFactory( 3784): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3784): Time to load native libraries: 1 ms (timestamps 3820-3821)
,I/LibraryLoader( 3784): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3784): Binding Chromium to main looper Looper (main, tid 1) {2d3a2120}
I/LibraryLoader( 3784): Expected native library version number "",actual native library version number ""
I/chromium( 3784): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3784): Initializing chromium process, singleProcess=true
,W/art     ( 3784): Attempt to remove local handle scope entry from IRT, ignoring,
,E/SysUtils( 3784): ApplicationContext is null in ApplicationStatus
E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1660642579
E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
W/chromium( 3784): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3784): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3784): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno  ( 3784): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,I/art     (  821): Explicit concurrent mark sweep GC freed 23345(1090KB) AllocSpace objects, 0(0B) LOS objects, 32% free, 33MB/49MB, paused 1.859ms total 94.313ms
,D/BluetoothManagerService(  821): Message: 20
,D/BluetoothManagerService(  821): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@177aec4e:true
,W/art     ( 3784): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3784): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3784): CordovaWebView is running on device made by: motorola
,W/art     ( 3784): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3784): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3784): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,D/Atlas   ( 3784): Validating map...
,V/WindowManager(  821): Adding window Window{ca104fe u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{2c155a4c u0 Starting com.test.thalitest})
,W/chromium( 3784): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3784): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3784): Enabling debug mode 0
,I/ActivityManager(  821): Killing 3438:com.google.android.gm.exchange/u0a77 (adj 15): empty #17
,I/Keyboard.Facilitator( 1254): onFinishInput()
,I/ActivityManager(  821): Killing 3327:com.google.android.apps.maps/u0a65 (adj 15): empty #18
,W/BindingManager( 3784): Cannot call determinedVisibility() - never saw a connection for the pid: 3784
,I/ActivityManager(  821): Displayed com.test.thalitest/.MainActivity: +715ms
,D/JsMessageQueue( 3784): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3784): JniHelper::setJavaVM(0xb489d200), pthread_self() = -1576393600
,I/chromium( 3784): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 3784): Initializing JXcore engine
W/jxcore-log( 3784): JXcore engine is ready
,W/Thread-427( 3838): type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[9557]" dev="sockfs" ino=9557 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-427( 3838): type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-427( 3838): type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[9654]" dev="sockfs" ino=9654 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/Thread-427( 3838): type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[22158]" dev="sockfs" ino=22158 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 3784): Starting JXcore engine,
,W/jxcore-log( 3784): Platform android
W/jxcore-log( 3784): 
W/jxcore-log( 3784): Process ARCH arm
W/jxcore-log( 3784): 
,I/jxcore-log( 3784): JXcore Cordova bridge is ready!
I/jxcore-log( 3784): 
W/jxcore-log( 3784): JXcore engine is started
,I/jxcore-log( 3784): Toggling radios to true
I/jxcore-log( 3784): 
,D/BluetoothAdapter( 3784): enable(): BT is already enabled..!,
,D/WifiService(  821): New client listening to asynchronous messages
,D/WifiService(  821): setWifiEnabled: true pid=3784, uid=10265
,E/WifiService(  821): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3784): Radios toggled
I/jxcore-log( 3784): 
,I/jxcore-log( 3784): My device name is: motorola-Nexus 6,
I/jxcore-log( 3784): 
,I/wpa_supplicant( 1135): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  821): WifiStateMachine: Leaving Connected state
,E/WifiConfigStore(  821): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  353): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1203): Read error: ssl=0xaec58c00: I/O error during system call, Connection timed out
,V/NativeCrypto( 1203): SSL shutdown failed: ssl=0xaec58c00: I/O error during system call, Broken pipe
,D/ConnectivityService(  821): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED,
,D/ConnectivityService(  821): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,E/WifiStateMachine(  821): Start Disconnecting Watchdog 1
,D/ConnectivityService(  821): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10011
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): ValidatedState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): DefaultState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): Forcing reevaluation
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
,E/WifiStateMachine(  821): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,D/CommandListener(  353): Clearing all IP addresses on wlan0
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
,D/WifiNetworkAgent(  821): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine(  821): CMD_AUTO_CONNECT sup state CompletedState my state DisconnectedState nid=0 roam=3
,E/WifiStateMachine(  821): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=0
D/ConnectivityService(  821): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): OfflineState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityManager.CallbackHandler( 1066): CM callback handler got msg 524292
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): Disconnected - quitting
,D/CSLegacyTypeTracker(  821): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true,
D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/PhoneInterfaceManager( 1352): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1352): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  821): getDataEnabled: retVal=false
,D/Tethering(  821): MasterInitialState.processMessage what=3
D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,E/WifiConfigStore(  821): Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiConfigStore(  821): will read network variables netId=0
,D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  821): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/ConnectivityService(  821): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/ConnectivityService(  821): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
,D/Tethering(  821): MasterInitialState.processMessage what=3
E/WifiStateMachine(  821): CMD_AUTO_CONNECT did save config ->  nid=0
,E/WifiConfigStore(  821): will read network variables netId=0
I/NetworkMonitor( 3018): type=WIFI subType= reason=null isConnected=false
,V/MusicLeanback( 3018): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,E/GpsLocationProvider(  821): No APN found to select.
,D/PhoneInterfaceManager( 1352): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
,E/PhoneInterfaceManager( 1352): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  821): getDataEnabled: retVal=false
,I/ActivityManager(  821): Start proc 3847:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.steen.receiver.ConnectivityChangeReceiver
,E/GpsLocationProvider(  821): No APN found to select.
,I/ActivityManager(  821): Start proc 3873:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
I/ActivityManager(  821): Killing 3492:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,D/SprintDMReceiver( 3873): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3873): simOperator:  IMSI: null
D/SprintDMReceiver( 3873): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1771): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1771): onCreate
,D/SystemUpdateService( 1771): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1771): active receiver: enabled
,I/SystemUpdateService( 1771): showing system update notification
,I/iu.Environment( 1771): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1771): num queued entries: 0
,I/iu.UploadsManager( 1771): num updated entries: 0
,I/iu.SyncManager( 1771): NEXT; no task
,D/ChimeraCfgMgr( 1771): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/ValidateNoPeople(  821): skipping global notification
,V/SystemUpdateService( 1771): retry (wakeup: false) in 3599976 ms
,I/Babel   ( 3649): connection state changed from CONNECTED to DISCONNECTED
,I/ActivityManager(  821): Start proc 3893:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,D/SystemUpdateService( 1771): onDestroy
,I/ActivityManager(  821): Killing 3519:com.android.musicfx/u0a18 (adj 15): empty #17
,I/GAv4    ( 3893): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3893):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3893):   adb logcat -s GAv4
,W/GAv4    ( 3893): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3893): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3893): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 3893): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3893): Time to load native libraries: 2 ms (timestamps 7598-7600)
I/LibraryLoader( 3893): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3893): Binding Chromium to main looper Looper (main, tid 1) {28b86647}
,I/LibraryLoader( 3893): Expected native library version number "",actual native library version number ""
I/chromium( 3893): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3893): Initializing chromium process, singleProcess=true
,W/art     ( 3893): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3893): ApplicationContext is null in ApplicationStatus
,W/chromium( 3893): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3893): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3893): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3893): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,W/AudioManagerAndroid( 3893): Requires BLUETOOTH permission
,I/NSApplication( 3893): Starting up...
,I/ActivityManager(  821): Start proc 3949:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,I/art     ( 1203): Explicit concurrent mark sweep GC freed 27359(1472KB) AllocSpace objects, 5(551KB) LOS objects, 37% free, 26MB/42MB, paused 904us total 21.272ms
,I/ActivityManager(  821): Killing 3548:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,I/wpa_supplicant( 1135): wlan0: Trying to associate with SSID 'NG7005g'
,V/MusicLeanback( 3018): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/SprintDMReceiver( 3873): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3873): simOperator:  IMSI: null
D/SprintDMReceiver( 3873): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1771): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) },
,D/SystemUpdateService( 1771): onCreate,
,D/SystemUpdateService( 1771): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1771): active receiver: enabled
,I/SystemUpdateService( 1771): showing system update notification
,V/GLSActivity( 1203): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ValidateNoPeople(  821): skipping global notification
,V/SystemUpdateService( 1771): retry (wakeup: false) in 3599970 ms
,D/ChimeraCfgMgr( 1771): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/GLSUser ( 1203): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1203): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1203): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1203): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1203): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SystemUpdateService( 1771): onDestroy
,D/Finsky  ( 3585): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3585): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3585): [1] 5.onFinished: Scheduling replication attempt 1.
,I/ActivityManager(  821): Killing 1456:android.process.acore/u0a5 (adj 15): empty #17
,I/wpa_supplicant( 1135): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 1135): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 1135): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=0 id_str=]
,D/ConnectivityService(  821): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} }
,E/WifiConfigStore(  821): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  821): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  821): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any,
,D/CommandListener(  353): Setting iface cfg
E/WifiStateMachine(  821): Start Dhcp Watchdog 2
,E/WifiStateMachine(  821):  WifiLinkLayerStats: 
E/WifiStateMachine(  821):  my bss beacon rx: 205
E/WifiStateMachine(  821):  RSSI mgmt: -51
E/WifiStateMachine(  821):  BE :  rx=164 tx=140 lost=0 retries=0
E/WifiStateMachine(  821):  BK :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  821):  VI :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  821):  VO :  rx=4 tx=0 lost=0 retries=0
E/WifiStateMachine(  821):  on_time : 9073 tx_time=157 rx_time=340 scan_time=0
,D/ConnectivityService(  821): updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,E/native  (  821): do suspend false
,E/WifiStateMachine(  821): scanCount==0 - aborting
,I/art     ( 1528): WaitForGcToComplete blocked for 49.058ms for cause HomogeneousSpaceCompact
,I/dhcpcd  ( 3979): version 5.5.6 starting
,I/dhcpcd  ( 3979): wlan0: rebinding lease of 192.168.1.122
,I/dhcpcd  ( 3979): wlan0: acknowledged 192.168.1.122 from 192.168.1.1
,I/dhcpcd  ( 3979): wlan0: leased 192.168.1.122 for 86400 seconds
,D/ConnectivityService(  821): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  821): Adding iface wlan0 to network 101
,E/WifiStateMachine(  821): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  821): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  821): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/ConnectivityService(  821): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  821): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  821): Setting Dns servers for network 101 to [/192.168.1.1],
,D/ConnectivityService(  821): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  821): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  821): rematching NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  821):    accepting network in place of null
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  821): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  821): Connected
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  821): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  821): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
D/ConnectivityService(  821): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} }
,D/ConnectivityService(  821): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1066): CM callback handler got msg 524290
D/CSLegacyTypeTracker(  821): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  821): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 3018): type=WIFI subType= reason=null isConnected=true,
D/PhoneInterfaceManager( 1352): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1352): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
D/TelephonyManager(  821): getDataEnabled: retVal=false
,V/MusicLeanback( 3018): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,E/GpsLocationProvider(  821): No APN found to select.
,D/SprintDMReceiver( 3873): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3873): simOperator:  IMSI: null
D/SprintDMReceiver( 3873): Not Sprint UICC, don't do anything.
,I/ActivityManager(  821): Start proc 4015:com.google.android.keep/u0a79 for service com.google.android.keep/.syncadapter.KeepSyncAdapterService
,I/SystemUpdateService( 1771): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1771): onCreate
,D/SystemUpdateService( 1771): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  821): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 02 Feb 2016 13:17:24 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454419044350], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454419044326]}
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  821): Validated
D/ConnectivityService(  821): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
,D/ConnectivityService(  821): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  821): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  821): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  821): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1066): CM callback handler got msg 524290
,I/SystemUpdateService( 1771): active receiver: enabled
,I/jxcore-log( 3784): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 3784): 
,I/iu.Environment( 1771): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/SystemUpdateService( 1771): showing system update notification
D/ChimeraCfgMgr( 1771): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/iu.UploadsManager( 1771): num queued entries: 0
I/iu.UploadsManager( 1771): num updated entries: 0
,I/iu.SyncManager( 1771): NEXT; no task
,I/ValidateNoPeople(  821): skipping global notification
,D/ChimeraCfgMgr( 1771): Loading module com.google.android.gms.kids from APK com.google.android.gms
,V/SystemUpdateService( 1771): retry (wakeup: false) in 3599903 ms
,I/Babel   ( 3649): connection state changed from DISCONNECTED to CONNECTED
,I/art     (  821): Explicit concurrent mark sweep GC freed 45641(2MB) AllocSpace objects, 7(206KB) LOS objects, 32% free, 33MB/49MB, paused 1.527ms total 53.080ms
,D/SystemUpdateService( 1771): onDestroy
,I/GLSUser ( 1203): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1203): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1203): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1203): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1203): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3196): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3196): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3196): 	at jdm.a(PG:82)
E/HttpOperation( 3196): 	at jcs.o(PG:406)
E/HttpOperation( 3196): 	at jcn.a(PG:1379)
E/HttpOperation( 3196): 	at jcs.i(PG:143)
E/HttpOperation( 3196): 	at blb.a(PG:3937)
E/HttpOperation( 3196): 	at czp.a(PG:18188)
E/HttpOperation( 3196): 	at czp.a(PG:9081)
E/HttpOperation( 3196): 	at czq.run(PG:1686)
E/HttpOperation( 3196): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3196): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3196): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3196): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3196): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3196): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3196): 	at jdj.a(PG:4091)
E/HttpOperation( 3196): 	at jdj.a(PG:1125)
E/HttpOperation( 3196): 	at jdm.a(PG:77)
E/HttpOperation( 3196): 	... 12 more
E/HttpOperation( 3196): Caused by: faj: BadAuthentication
E/HttpOperation( 3196): 	at fal.a(PG:38)
E/HttpOperation( 3196): 	at jdj.a(PG:4089)
E/HttpOperation( 3196): 	... 14 more
V/Herrevad( 1771): NQAS connected
,I/GLSUser ( 1203): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1203): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1203): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1203): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1203): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1203): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1203): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1203): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1203): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1203): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,E/HttpOperation( 3196): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3196): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3196): 	at jdm.a(PG:82)
E/HttpOperation( 3196): 	at jcs.o(PG:406)
E/HttpOperation( 3196): 	at jcn.a(PG:1379)
E/HttpOperation( 3196): 	at jcs.i(PG:143)
E/HttpOperation( 3196): 	at hec.a(PG:42)
E/HttpOperation( 3196): 	at hee.a(PG:102)
E/HttpOperation( 3196): 	at czr.a(PG:65)
E/HttpOperation( 3196): 	at kka.a(PG:108)
E/HttpOperation( 3196): 	at czp.a(PG:19176)
E/HttpOperation( 3196): 	at czp.a(PG:9081)
E/HttpOperation( 3196): 	at czq.run(PG:1686)
E/HttpOperation( 3196): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3196): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3196): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3196): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3196): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3196): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3196): 	at jdj.a(PG:4091)
E/HttpOperation( 3196): 	at jdj.a(PG:1125)
E/HttpOperation( 3196): 	at jdm.a(PG:77)
E/HttpOperation( 3196): 	... 15 more
E/HttpOperation( 3196): Caused by: faj: BadAuthentication
E/HttpOperation( 3196): 	at fal.a(PG:38)
E/HttpOperation( 3196): 	at jdj.a(PG:4089)
E/HttpOperation( 3196): 	... 17 more
E/ExperimentLoader( 3196): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3196): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3196): 	at jdm.a(PG:82)
E/ExperimentLoader( 3196): 	at jcs.o(PG:406)
E/ExperimentLoader( 3196): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3196): 	at jcs.i(PG:143)
E/ExperimentLoader( 3196): 	at hec.a(PG:42)
E/ExperimentLoader( 3196): 	at hee.a(PG:102)
E/ExperimentLoader( 3196): 	,at czr.a(PG:65)
E/ExperimentLoader( 3196): 	at kka.a(PG:108)
E/ExperimentLoader( 3196): 	at czp.a(PG:19176)
E/ExperimentLoader( 3196): 	at czp.a(PG:9081)
E/ExperimentLoader( 3196): 	at czq.run(PG:1686)
E/ExperimentLoader( 3196): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3196): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3196): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3196): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3196): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3196): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3196): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3196): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3196): 	at jdm.a(PG:77)
E/ExperimentLoader( 3196): 	... 15 more
E/ExperimentLoader( 3196): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3196): 	at fal.a(PG:38)
E/ExperimentLoader( 3196): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3196): 	... 17 more
D/GCM     ( 1203): Connected
D/GCM     ( 1203): Message class com.google.f.a.a.p
,V/KeepSync( 4015): Connecting to GoogleApiClient
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 74809, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager(  821): Start proc 4056:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,I/GLSUser ( 1203): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1203): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1203): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1203): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1203): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/ClientConnectionOperation( 1771): Handling authorization failure
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
,V/KeepSync( 4015): GoogleApiClient failed to connect with error code: 4
E/SQLiteLog( 4015): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 4015): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 4015): (284) automatic index on blob_node(is_deleted)
,W/GAV2    ( 4056): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/GLSUser ( 1203): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1203): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1203): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1203): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1203): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1203): Explicit concurrent mark sweep GC freed 19040(1095KB) AllocSpace objects, 3(330KB) LOS objects, 38% free, 26MB/42MB, paused 850us total 19.947ms
I/BooksApp( 4056): Created application version: 3.6.8 (30608)
,E/KeepSync( 4015): IOException
E/KeepSync( 4015): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 4015): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 4015): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 4015): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 4015): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 4015): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 4015): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 4015): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 4015): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 4015): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 4015): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 4015): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 4015): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 4015): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 4015): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 4015): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 4015): 	... 10 more
W/KeepSync( 4015): Sync result 2
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 75280, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/BooksSync( 4056): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 4056): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1203): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1203): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1203): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1203): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1203): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/jxcore-log( 3784): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 3784): 
,I/GLSUser ( 1203): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1203): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1203): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1203): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1203): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 4056): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 4056): Soft error
E/BooksSync( 4056): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4056): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 4056): Sync error
E/BooksSync( 4056): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4056): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 4056): Finished books sync
,I/ActivityManager(  821): Killing 3625:com.google.android.gms:car/u0a11 (adj 15): empty #17
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 77102, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/jxcore-log( 3784): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 3784): 
,I/jxcore-log( 3784): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
I/jxcore-log( 3784): 
,I/jxcore-log( 3784): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 3784): 
,D/ConnectivityService(  821): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=15.81 rxSuccessRate=15.81 targetRoamBSSID=any RSSI=-51
E/WifiStateMachine(  821): WifiStateMachine L2Connected CMD_START_SCAN source -2 5, 7 -> obsolete
,I/ActivityManager(  821): Killing 3415:com.google.android.gm/u0a78 (adj 15): empty #17
,I/GAV2    ( 4056): Thread[GAThread,5,main]: No campaign data found.
,I/jxcore-log( 3784): Test app app.js loaded
I/jxcore-log( 3784): 
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3784): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3784): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3784): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3784): 	Bluetooth MAC address: F8:CF:C5:D9:E5:61, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3784): 	Discovery mode: BLE_AND_WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3784): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3784): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3784): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3784): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3784): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d5d3f76 added. We now have 1 listener(s)
,I/chromium( 3784): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51),
,I/jxcore-log( 3784): BLE advertisement is supported,
I/jxcore-log( 3784): 
,E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=8.41 rxSuccessRate=9.91 targetRoamBSSID=any RSSI=-51
E/WifiStateMachine(  821): WifiStateMachine L2Connected CMD_START_SCAN source -2 6, 7 -> obsolete
,D/Finsky  ( 3585): [384] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,V/GLSActivity( 1203): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1203): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1203): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1203): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1203): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1203): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3585): [384] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,V/GLSActivity( 1203): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  821): Explicit concurrent mark sweep GC freed 32258(1451KB) AllocSpace objects, 4(64KB) LOS objects, 31% free, 34MB/50MB, paused 1.833ms total 103.748ms
,I/GLSUser ( 1203): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1203): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1203): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1203): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1203): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3585): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3585): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3585): [1] 5.onFinished: Scheduling replication attempt 2.
,E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=1.58 rxSuccessRate=3.34 targetRoamBSSID=any RSSI=-51
,E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.83 rxSuccessRate=2.15 targetRoamBSSID=any RSSI=-51
E/WifiStateMachine(  821): WifiStateMachine starting scan for "NG7005g"WPA_PSK with 2412,5220
,V/GLSActivity( 1203): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1203): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1203): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1203): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1203): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1203): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3585): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3585): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3585): [1] 5.onFinished: Scheduling replication attempt 3.
,D/HeadsetStateMachine( 2181): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2181): Disconnected process message: 10, size: 0
,W/ProcessCpuTracker(  821): Skipping unknown process pid 4106
,I/BooksSync( 4056): Starting books sync for 61035162, extras: ade
,V/KeepSync( 4015): Connecting to GoogleApiClient
,I/BooksConfig( 4056): GmsCore Version = 7.8.99 (2134222-430),
,I/GLSUser ( 1203): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1203): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1203): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1203): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1203): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1203): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1203): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1203): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1203): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1203): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
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
,V/KeepSync( 4015): GoogleApiClient failed to connect with error code: 4,
,E/SQLiteLog( 4015): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4015): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4015): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1203): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1203): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1203): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1203): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1203): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 4056): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication,
,E/BooksSync( 4056): Soft error
E/BooksSync( 4056): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4056): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 4056): Sync error,
E/BooksSync( 4056): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4056): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 4056): Finished books sync
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 111552, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1203): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1203): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1203): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1203): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1203): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 4015): IOException
E/KeepSync( 4015): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 4015): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 4015): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 4015): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 4015): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 4015): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 4015): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 4015): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 4015): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 4015): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 4015): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 4015): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 4015): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 4015): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 4015): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 4015): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 4015): 	... 10 more
W/KeepSync( 4015): Sync result 2
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 111807, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1203): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1203): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1203): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1203): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1203): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3196): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3196): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3196): 	at jdm.a(PG:82)
E/HttpOperation( 3196): 	at jcs.o(PG:406)
E/HttpOperation( 3196): 	at jcn.a(PG:1379)
E/HttpOperation( 3196): 	at jcs.i(PG:143)
E/HttpOperation( 3196): 	at blb.a(PG:3937)
E/HttpOperation( 3196): 	at czp.a(PG:18188)
E/HttpOperation( 3196): 	at czp.a(PG:9081)
E/HttpOperation( 3196): 	at czq.run(PG:1686)
E/HttpOperation( 3196): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3196): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3196): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3196): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3196): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3196): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3196): 	at jdj.a(PG:4091)
E/HttpOperation( 3196): 	at jdj.a(PG:1125)
E/HttpOperation( 3196): 	at jdm.a(PG:77)
E/HttpOperation( 3196): 	... 12 more
E/HttpOperation( 3196): Caused by: faj: BadAuthentication
E/HttpOperation( 3196): 	at fal.a(PG:38)
E/HttpOperation( 3196): 	at jdj.a(PG:4089)
E/HttpOperation( 3196): 	... 14 more
,I/GLSUser ( 1203): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1203): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1203): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1203): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1203): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3196): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3196): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3196): 	at jdm.a(PG:82)
E/HttpOperation( 3196): 	at jcs.o(PG:406)
E/HttpOperation( 3196): 	at jcn.a(PG:1379)
E/HttpOperation( 3196): 	at jcs.i(PG:143)
E/HttpOperation( 3196): 	at hec.a(PG:42)
E/HttpOperation( 3196): 	at hee.a(PG:102)
E/HttpOperation( 3196): 	at czr.a(PG:65)
E/HttpOperation( 3196): 	at kka.a(PG:108)
E/HttpOperation( 3196): 	at czp.a(PG:19176)
E/HttpOperation( 3196): 	at czp.a(PG:9081)
E/HttpOperation( 3196): 	at czq.run(PG:1686)
E/HttpOperation( 3196): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3196): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3196): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3196): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3196): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3196): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3196): 	at jdj.a(PG:4091)
E/HttpOperation( 3196): 	at jdj.a(PG:1125)
E/HttpOperation( 3196): 	at jdm.a(PG:77)
E/HttpOperation( 3196): 	... 15 more
E/HttpOperation( 3196): Caused by: faj: BadAuthentication
E/HttpOperation( 3196): 	at fal.a(PG:38)
E/HttpOperation( 3196): 	at jdj.a(PG:4089)
E/HttpOperation( 3196): 	... 17 more
E/ExperimentLoader( 3196): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3196): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3196): 	at jdm.a(PG:82)
E/ExperimentLoader( 3196): 	at jcs.o(PG:406)
E/ExperimentLoader( 3196): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3196): 	at jcs.i(PG:143)
E/ExperimentLoader( 3196): 	at hec.a(PG:42)
E/ExperimentLoader( 3196): 	at hee.a(PG:102)
E/ExperimentLoader( 3196): 	at czr.a(PG:65)
E/ExperimentLoader( 3196): 	at kka.a(PG:108)
E/ExperimentLoader( 3196): 	at czp.a(PG:19176)
E/ExperimentLoader( 3196): 	at czp.a(PG:9081)
E/ExperimentLoader( 3196): 	at czq.run(PG:1686)
E/ExperimentLoader( 3196): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3196): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3196): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3196): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3196): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3196): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3196): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3196): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3196): 	at jdm.a(PG:77)
E/ExperimentLoader( 3196): 	... 15 more
E/ExperimentLoader( 3196): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3196): 	at fal.a(PG:38)
E/ExperimentLoader( 3196): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3196): 	... 17 more
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 113628, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/Keyboard.Facilitator.LanguageModelFlusher( 1254): run()
I/Keyboard.Facilitator( 1254): flushDynamicLanguageModels()
,I/ConfigService( 1203): onCreate
,I/ConfigService( 1203): onDestroy
,E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.77 rxSuccessRate=3.54 targetRoamBSSID=any RSSI=-51
,V/GLSActivity( 1203): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1203): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1203): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1203): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1203): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1203): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3585): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3585): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3585): [1] 5.onFinished: Scheduling replication attempt 4.
,E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.77 rxSuccessRate=2.68 targetRoamBSSID=any RSSI=-51
E/WifiStateMachine(  821): WifiStateMachine starting scan for "NG7005g"WPA_PSK with 2412,5220
,I/PowerManagerService(  821): Going to sleep due to screen timeout (uid 1000)...
,I/Adreno  (  821): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/PermissionCache(  259): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (345 us)
,V/GLSActivity( 1203): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/DisplayManagerService(  821): Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager(  821): Display changed displayId=0
,D/SurfaceFlinger(  259): Set power mode=0, type=0 flinger=0xb6482000
D/qdhwcomposer(  259): hwc_setPowerMode: Setting mode 0 on display: 0
,I/art     ( 1203): Explicit concurrent mark sweep GC freed 32224(1909KB) AllocSpace objects, 3(330KB) LOS objects, 37% free, 26MB/42MB, paused 2.375ms total 64.397ms
,I/GLSUser ( 1203): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1203): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1203): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1203): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1203): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3585): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3585): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3585): [1] 5.onFinished: Scheduling replication attempt 5.
,I/kickstart(  871): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
,I/kickstart(  871): STATUS: Wrote to /sys/power/wake_lock
,E/kickstart(  871): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1
,I/kickstart(  871): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1' for writing
,I/qdhwcomposer(  259): handle_blank_event: dpy:0 panel power state: 0
,D/qdhwcomposer(  259): hwc_setPowerMode: Done setting mode 0 on display 0
,D/SurfaceControl(  821): Excessive delay in setPowerMode(): 275ms
,I/DreamManagerService(  821): Entering dreamland.
I/PowerManagerService(  821): Dozing...
I/DreamController(  821): Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,D/audio_hw_primary(  357): adev_set_parameters: enter: screen_state=on
,D/mot_vr_audio_hw(  357): adev_set_parameters: screen_state=on
,E/WifiStateMachine(  821): cancelDelayedScan -> 12
,E/native  (  821): do suspend false
,I/Keyboard.Facilitator( 1254): onFinishInput()
,E/WifiStateMachine(  821): cancelDelayedScan -> 14
,E/native  (  821): do suspend true
,D/audio_hw_primary(  357): adev_set_parameters: enter: screen_state=off
D/mot_vr_audio_hw(  357): adev_set_parameters: screen_state=off
,E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-51
E/WifiStateMachine(  821): WifiStateMachine L2Connected CMD_START_SCAN source -2 13, 14 -> obsolete
,I/kickstart(  871): STATUS: Received file 'm9kefs1'
,I/kickstart(  871): STATUS: 950272 bytes transferred in 0.985478 seconds
I/kickstart(  871): STATUS: Successfully downloaded files from target 
,I/kickstart(  871): STATUS: Wrote to /sys/power/wake_unlock
,I/kickstart(  871): STATUS: Sahara protocol completed,
,I/art     (  821): Explicit concurrent mark sweep GC freed 53448(2MB) AllocSpace objects, 23(651KB) LOS objects, 31% free, 34MB/50MB, paused 1.397ms total 76.442ms
,V/GLSActivity( 1203): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GoogleAuthProtoRequest( 3847): [420] a.<init>: mAccountName set to: thalitester@gmail.com
,I/VacuumService( 1203): Vacuum at: now=1454419141213 tag=VacuumService
,I/GLSUser ( 1203): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1203): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1203): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1203): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1203): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3847): [420] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3847): [420] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3847): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3847): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3847): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3847): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3847): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3847): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3847): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3847): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3847): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3847): 	at com.a.a.k.run(SourceFile:110)
,I/GoogleURLConnFactory( 1203): Using platform SSLCertificateSocketFactory
,I/GLSUser ( 1203): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1203): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1203): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1203): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1203): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1203): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1203): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1203): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1203): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1203): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1203): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1203): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1203): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1203): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1203): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1203): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1203): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1203): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/GLSUser ( 1203): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1203): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1203): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1203): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1203): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1203): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1203): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1203): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1203): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1203): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1203): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1203): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1203): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1203): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1203): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1203): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1203): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1203): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1203): No account for auth token provided
,W/Uploader( 1203): No account for auth token provided
,W/Uploader( 1203): No account for auth token provided
,W/Uploader( 1203): No account for auth token provided
,W/Uploader( 1203): No account for auth token provided
,W/Uploader( 1203): No account for auth token provided
,I/GLSUser ( 1203): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1203): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1203): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1203): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1203): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1203): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1203): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1203): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1203): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1203): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1203): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1203): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1203): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1203): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1203): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1203): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1203): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1203): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1203): No account for auth token provided,
,W/Uploader( 1203): No account for auth token provided
,W/Uploader( 1203): No account for auth token provided
,W/Uploader( 1203): No account for auth token provided
,W/Uploader( 1203): No account for auth token provided
,W/Uploader( 1203):  no longer exists, so no auth token.
,I/GLSUser ( 1203): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1203): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1203): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1203): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1203): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1203): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1203): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1203): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1203): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1203): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1203): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1203): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1203): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1203): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1203): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1203): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1203): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1203): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-51
E/WifiStateMachine(  821): WifiStateMachine L2Connected CMD_START_SCAN source -2 11, 14 -> obsolete
,V/GLSActivity( 1203): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1203): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1203): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1203): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1203): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1203): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3585): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3585): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3585): [1] 5.onFinished: Giving up after 6 failures.
,D/HeadsetStateMachine( 2181): Disconnected process message: 10, size: 0
,I/BooksSync( 4056): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 4056): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1203): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1203): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1203): [GLSUser] Extracting token using key: Auth,
W/GLSActivity( 1203): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1203): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1203): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1203): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1203): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1203): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1203): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 4056): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 4056): Soft error,
E/BooksSync( 4056): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4056): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 4056): Sync error
E/BooksSync( 4056): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4056): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 4056): Finished books sync
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 193000, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,V/GoogleAuthProtoRequest( 3847): [421] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1203): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1203): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1203): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1203): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1203): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3847): [421] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3847): [421] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3847): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3847): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3847): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3847): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3847): 	at com.google.android.gms.gcm.c.run(Unknown Source)
,W/ExperimentUpdateService( 3847): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3847): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3847): 	at com.a.a.a.g.a(SourceFile:79)
,W/ExperimentUpdateService( 3847): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3847): 	at com.a.a.k.run(SourceFile:110)
,V/KeepSync( 4015): Connecting to GoogleApiClient
,I/GLSUser ( 1203): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1203): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1203): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1203): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1203): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1203): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1203): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1203): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1203): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1203): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,V/KeepSync( 4015): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 4015): (284) automatic index on blob_node(is_deleted)
,E/HttpOperation( 3196): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3196): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3196): 	at jdm.a(PG:82)
E/HttpOperation( 3196): 	at jcs.o(PG:406)
E/HttpOperation( 3196): 	at jcn.a(PG:1379)
E/HttpOperation( 3196): 	at jcs.i(PG:143)
E/HttpOperation( 3196): 	at blb.a(PG:3937)
E/HttpOperation( 3196): 	at czp.a(PG:18188)
E/HttpOperation( 3196): 	at czp.a(PG:9081)
E/HttpOperation( 3196): 	at czq.run(PG:1686)
E/HttpOperation( 3196): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3196): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3196): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3196): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3196): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3196): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3196): 	at jdj.a(PG:4091)
E/HttpOperation( 3196): 	at jdj.a(PG:1125)
E/HttpOperation( 3196): 	at jdm.a(PG:77)
E/HttpOperation( 3196): 	... 12 more
E/HttpOperation( 3196): Caused by: faj: BadAuthentication
E/HttpOperation( 3196): 	at fal.a(PG:38)
E/HttpOperation( 3196): 	at jdj.a(PG:4089)
E/HttpOperation( 3196): 	... 14 more
,E/SQLiteLog( 4015): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4015): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1203): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1203): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1203): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1203): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1203): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3196): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3196): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3196): 	at jdm.a(PG:82)
E/HttpOperation( 3196): 	at jcs.o(PG:406)
E/HttpOperation( 3196): 	at jcn.a(PG:1379)
E/HttpOperation( 3196): 	at jcs.i(PG:143)
E/HttpOperation( 3196): 	at hec.a(PG:42)
E/HttpOperation( 3196): 	at hee.a(PG:102)
E/HttpOperation( 3196): 	at czr.a(PG:65)
E/HttpOperation( 3196): 	at kka.a(PG:108)
E/HttpOperation( 3196): 	at czp.a(PG:19176)
E/HttpOperation( 3196): 	at czp.a(PG:9081)
E/HttpOperation( 3196): 	at czq.run(PG:1686)
E/HttpOperation( 3196): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3196): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3196): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3196): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3196): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3196): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3196): 	at jdj.a(PG:4091)
E/HttpOperation( 3196): 	at jdj.a(PG:1125)
E/HttpOperation( 3196): 	at jdm.a(PG:77)
E/HttpOperation( 3196): 	... 15 more
E/HttpOperation( 3196): Caused by: faj: BadAuthentication
E/HttpOperation( 3196): 	at fal.a(PG:38)
E/HttpOperation( 3196): 	at jdj.a(PG:4089)
E/HttpOperation( 3196): 	... 17 more
,E/ExperimentLoader( 3196): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3196): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3196): 	at jdm.a(PG:82)
E/ExperimentLoader( 3196): 	at jcs.o(PG:406)
E/ExperimentLoader( 3196): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3196): 	at jcs.i(PG:143)
E/ExperimentLoader( 3196): 	at hec.a(PG:42)
E/ExperimentLoader( 3196): 	at hee.a(PG:102)
E/ExperimentLoader( 3196): 	at czr.a(PG:65)
E/ExperimentLoader( 3196): 	at kka.a(PG:108)
E/ExperimentLoader( 3196): 	at czp.a(PG:19176)
E/ExperimentLoader( 3196): 	at czp.a(PG:9081)
E/ExperimentLoader( 3196): 	at czq.run(PG:1686)
E/ExperimentLoader( 3196): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3196): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3196): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3196): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3196): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3196): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3196): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3196): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3196): 	at jdm.a(PG:77)
E/ExperimentLoader( 3196): 	... 15 more
E/ExperimentLoader( 3196): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3196): 	at fal.a(PG:38)
E/ExperimentLoader( 3196): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3196): 	... 17 more
,I/art     (  821): Explicit concurrent mark sweep GC freed 34744(1530KB) AllocSpace objects, 4(252KB) LOS objects, 31% free, 34MB/50MB, paused 1.925ms total 67.225ms
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 198197, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1203): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1203): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1203): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1203): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1203): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 4015): IOException
E/KeepSync( 4015): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 4015): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 4015): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 4015): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 4015): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 4015): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 4015): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 4015): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 4015): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 4015): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 4015): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 4015): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 4015): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 4015): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 4015): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 4015): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 4015): 	... 10 more
W/KeepSync( 4015): Sync result 2
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 193977, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/Keyboard.Facilitator.LanguageModelFlusher( 1254): run()
I/Keyboard.Facilitator( 1254): flushDynamicLanguageModels()
,I/ConfigService( 1203): onCreate
,I/ConfigService( 1203): onDestroy
,V/GoogleAuthProtoRequest( 3847): [422] a.<init>: mAccountName set to: thalitester@gmail.com
,I/art     ( 1203): Explicit concurrent mark sweep GC freed 66640(3MB) AllocSpace objects, 12(1132KB) LOS objects, 36% free, 27MB/43MB, paused 1.382ms total 61.721ms
,I/GLSUser ( 1203): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1203): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1203): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1203): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1203): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3847): [422] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3847): [422] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3847): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3847): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3847): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3847): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3847): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3847): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3847): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3847): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3847): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3847): 	at com.a.a.k.run(SourceFile:110)
,D/HeadsetStateMachine( 2181): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2181): Disconnected process message: 10, size: 0
,I/BooksSync( 4056): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 4056): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1203): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1203): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1203): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1203): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1203): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1203): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1203): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1203): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1203): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1203): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 4056): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 4056): Soft error
E/BooksSync( 4056): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4056): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 4056): Sync error
E/BooksSync( 4056): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4056): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 4056): Finished books sync
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 314192, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,V/GLSActivity( 1203): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1203): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1203): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1203): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1203): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1203): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1203): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1203): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1203): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1203): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1203): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1203): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1203): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 3585): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3585): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3585): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 3585): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3585): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/PlayEventLogger( 3585): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3585): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 3585): Ignoring header User-Agent because its value was null.
,D/WifiService(  821): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@ce92e22}
,E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-51
,D/HeadsetStateMachine( 2181): Disconnected process message: 10, size: 0
,D/WifiService(  821): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@ce92e22}
,D/WifiService(  821): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@1ac47670}
,E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::injectLocation(GpsExtLocation):857]: error! inject position failed
,D/HeadsetStateMachine( 2181): Disconnected process message: 10, size: 0
,V/KeepSync( 4015): Connecting to GoogleApiClient
,I/GLSUser ( 1203): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1203): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1203): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1203): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1203): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3196): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3196): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3196): 	at jdm.a(PG:82)
E/HttpOperation( 3196): 	at jcs.o(PG:406)
E/HttpOperation( 3196): 	at jcn.a(PG:1379)
E/HttpOperation( 3196): 	at jcs.i(PG:143)
E/HttpOperation( 3196): 	at blb.a(PG:3937)
E/HttpOperation( 3196): 	at czp.a(PG:18188)
E/HttpOperation( 3196): 	at czp.a(PG:9081)
E/HttpOperation( 3196): 	at czq.run(PG:1686)
E/HttpOperation( 3196): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3196): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3196): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3196): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3196): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3196): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3196): 	at jdj.a(PG:4091)
E/HttpOperation( 3196): 	at jdj.a(PG:1125)
E/HttpOperation( 3196): 	at jdm.a(PG:77)
E/HttpOperation( 3196): 	... 12 more
E/HttpOperation( 3196): Caused by: faj: BadAuthentication
E/HttpOperation( 3196): 	at fal.a(PG:38)
E/HttpOperation( 3196): 	at jdj.a(PG:4089)
E/HttpOperation( 3196): 	... 14 more
,I/GLSUser ( 1203): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1203): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1203): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1203): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1203): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,V/KeepSync( 4015): GoogleApiClient failed to connect with error code: 4
I/GLSUser ( 1203): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1203): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1203): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1203): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1203): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SQLiteLog( 4015): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4015): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4015): (284) automatic index on blob_node(is_deleted)
,E/HttpOperation( 3196): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3196): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3196): 	at jdm.a(PG:82)
E/HttpOperation( 3196): 	at jcs.o(PG:406)
E/HttpOperation( 3196): 	at jcn.a(PG:1379)
E/HttpOperation( 3196): 	at jcs.i(PG:143)
E/HttpOperation( 3196): 	at hec.a(PG:42)
E/HttpOperation( 3196): 	at hee.a(PG:102)
E/HttpOperation( 3196): 	at czr.a(PG:65)
E/HttpOperation( 3196): 	at kka.a(PG:108)
E/HttpOperation( 3196): 	at czp.a(PG:19176)
E/HttpOperation( 3196): 	at czp.a(PG:9081)
E/HttpOperation( 3196): 	at czq.run(PG:1686)
E/HttpOperation( 3196): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3196): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3196): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3196): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3196): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3196): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3196): 	at jdj.a(PG:4091)
E/HttpOperation( 3196): 	at jdj.a(PG:1125)
E/HttpOperation( 3196): 	at jdm.a(PG:77)
E/HttpOperation( 3196): 	... 15 more
E/HttpOperation( 3196): Caused by: faj: BadAuthentication
E/HttpOperation( 3196): 	at fal.a(PG:38)
E/HttpOperation( 3196): 	at jdj.a(PG:4089)
E/HttpOperation( 3196): 	... 17 more
,E/ExperimentLoader( 3196): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3196): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3196): 	at jdm.a(PG:82)
E/ExperimentLoader( 3196): 	at jcs.o(PG:406)
E/ExperimentLoader( 3196): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3196): 	at jcs.i(PG:143)
E/ExperimentLoader( 3196): ,	at hec.a(PG:42)
E/ExperimentLoader( 3196): 	at hee.a(PG:102)
E/ExperimentLoader( 3196): 	at czr.a(PG:65)
E/ExperimentLoader( 3196): 	at kka.a(PG:108)
E/ExperimentLoader( 3196): 	,at czp.a(PG:19176)
E/ExperimentLoader( 3196): 	at czp.a(PG:9081)
E/ExperimentLoader( 3196): 	at czq.run(PG:1686)
E/ExperimentLoader( 3196): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3196): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237),
E/ExperimentLoader( 3196): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3196): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3196): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3196): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3196): ,	at jdj.a(PG:4091)
E/ExperimentLoader( 3196): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3196): 	at jdm.a(PG:77)
E/ExperimentLoader( 3196): 	... 15 more
E/ExperimentLoader( 3196): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3196): 	,at fal.a(PG:38)
E/ExperimentLoader( 3196): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3196): 	... 17 more
,I/art     (  821): Explicit concurrent mark sweep GC freed 32423(1470KB) AllocSpace objects, 12(663KB) LOS objects, 31% free, 34MB/50MB, paused 1.839ms total 81.993ms
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 354082, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1203): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1203): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1203): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1203): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1203): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 4015): IOException
E/KeepSync( 4015): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 4015): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 4015): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 4015): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 4015): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 4015): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 4015): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 4015): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 4015): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 4015): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 4015): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 4015): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 4015): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 4015): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 4015): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 4015): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 4015): 	... 10 more
W/KeepSync( 4015): Sync result 2
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 346067, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/WifiService(  821): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@1ac47670}
,V/GoogleAuthProtoRequest( 3847): [423] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1203): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1203): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1203): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1203): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1203): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3847): [423] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3847): [423] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3847): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3847): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3847): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3847): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3847): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3847): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3847): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3847): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3847): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3847): 	at com.a.a.k.run(SourceFile:110)
,D/HeadsetStateMachine( 2181): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2181): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2181): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2181): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2181): Disconnected process message: 10, size: 0,
,I/BooksSync( 4056): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 4056): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1203): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1203): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1203): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1203): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1203): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1203): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1203): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1203): [GLSUser] Extracting token using key: Auth,
,W/GLSActivity( 1203): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,V/GLSActivity( 1203): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/BooksAccountManager( 4056): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 4056): Soft error
E/BooksSync( 4056): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 4056): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 4056): Sync error
E/BooksSync( 4056): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4056): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 4056): Finished books sync
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 556012, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2181): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2181): Disconnected process message: 10, size: 0
,V/KeepSync( 4015): Connecting to GoogleApiClient
,I/GLSUser ( 1203): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1203): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1203): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1203): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1203): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 1203): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1203): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1203): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1203): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1203): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,V/KeepSync( 4015): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 4015): (284) automatic index on blob_node(is_deleted)
,E/HttpOperation( 3196): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3196): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3196): 	at jdm.a(PG:82)
E/HttpOperation( 3196): 	at jcs.o(PG:406)
E/HttpOperation( 3196): 	at jcn.a(PG:1379)
E/HttpOperation( 3196): 	at jcs.i(PG:143)
E/HttpOperation( 3196): 	at blb.a(PG:3937)
E/HttpOperation( 3196): 	at czp.a(PG:18188)
E/HttpOperation( 3196): 	at czp.a(PG:9081)
E/HttpOperation( 3196): 	at czq.run(PG:1686)
E/HttpOperation( 3196): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3196): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3196): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3196): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3196): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3196): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3196): 	at jdj.a(PG:4091)
E/HttpOperation( 3196): 	at jdj.a(PG:1125)
E/HttpOperation( 3196): 	at jdm.a(PG:77)
E/HttpOperation( 3196): 	... 12 more
E/HttpOperation( 3196): Caused by: faj: BadAuthentication
E/HttpOperation( 3196): 	at fal.a(PG:38)
E/HttpOperation( 3196): 	at jdj.a(PG:4089)
E/HttpOperation( 3196): 	... 14 more
,E/SQLiteLog( 4015): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 4015): (284) automatic index on blob_node(is_deleted)
,I/art     ( 1203): Explicit concurrent mark sweep GC freed 56921(2MB) AllocSpace objects, 15(1653KB) LOS objects, 36% free, 27MB/43MB, paused 1.374ms total 42.899ms
,I/GLSUser ( 1203): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1203): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1203): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1203): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1203): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3196): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3196): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3196): 	at jdm.a(PG:82)
E/HttpOperation( 3196): 	at jcs.o(PG:406)
E/HttpOperation( 3196): 	at jcn.a(PG:1379)
E/HttpOperation( 3196): 	at jcs.i(PG:143)
E/HttpOperation( 3196): 	at hec.a(PG:42)
E/HttpOperation( 3196): 	at hee.a(PG:102)
E/HttpOperation( 3196): 	at czr.a(PG:65)
E/HttpOperation( 3196): 	at kka.a(PG:108)
E/HttpOperation( 3196): 	at czp.a(PG:19176)
E/HttpOperation( 3196): 	at czp.a(PG:9081)
E/HttpOperation( 3196): 	at czq.run(PG:1686)
E/HttpOperation( 3196): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3196): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3196): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3196): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3196): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3196): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3196): 	at jdj.a(PG:4091)
E/HttpOperation( 3196): 	at jdj.a(PG:1125)
E/HttpOperation( 3196): 	at jdm.a(PG:77)
E/HttpOperation( 3196): 	... 15 more
E/HttpOperation( 3196): Caused by: faj: BadAuthentication
E/HttpOperation( 3196): 	at fal.a(PG:38)
E/HttpOperation( 3196): 	at jdj.a(PG:4089)
E/HttpOperation( 3196): 	... 17 more
E/ExperimentLoader( 3196): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3196): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3196): 	at jdm.a(PG:82)
E/ExperimentLoader( 3196): 	at jcs.o(PG:406)
E/ExperimentLoader( 3196): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3196): 	at jcs.i(PG:143)
E/ExperimentLoader( 3196): 	at hec.a(PG:42)
E/ExperimentLoader( 3196): 	at hee.a(PG:102)
E/ExperimentLoader( 3196): 	at czr.a(PG:65)
E/ExperimentLoader( 3196): 	at kka.a(PG:108)
E/ExperimentLoader( 3196): 	at czp.a(PG:19176)
E/ExperimentLoader( 3196): 	at czp.a(PG:9081)
E/ExperimentLoader( 3196): 	at czq.run(PG:1686)
E/ExperimentLoader( 3196): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3196): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3196): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3196): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3196): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3196): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3196): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3196): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3196): 	at jdm.a(PG:77)
E/ExperimentLoader( 3196): 	... 15 more
E/ExperimentLoader( 3196): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3196): 	at fal.a(PG:38)
E/ExperimentLoader( 3196): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3196): 	... 17 more
,I/GLSUser ( 1203): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1203): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1203): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1203): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1203): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 4015): IOException
E/KeepSync( 4015): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 4015): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 4015): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 4015): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 4015): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 4015): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 4015): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 4015): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 4015): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 4015): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 4015): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 4015): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 4015): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 4015): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 4015): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 4015): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 4015): 	... 10 more
W/KeepSync( 4015): Sync result 2
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 619648, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 635793, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2181): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2181): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2181): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2181): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2181): Disconnected process message: 10, size: 0
,V/GoogleAuthProtoRequest( 3847): [424] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1203): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1203): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1203): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1203): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1203): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3847): [424] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3847): [424] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3847): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3847): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3847): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3847): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3847): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3847): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3847): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3847): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3847): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3847): 	at com.a.a.k.run(SourceFile:110)
,I/ActivityManager(  821): Start proc 4298:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider
,I/art     (  368): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 416us total 19.523ms
,I/art     (  368): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 359us total 15.192ms
,I/art     (  368): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 232us total 13.681ms
,I/GAv4    ( 4298): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4298):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4298):   adb logcat -s GAv4
,W/GAv4    ( 4298): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4298): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4298): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  821): Killing 3395:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,D/HeadsetStateMachine( 2181): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2181): Disconnected process message: 10, size: 0
,I/art     (  821): Explicit concurrent mark sweep GC freed 45691(2MB) AllocSpace objects, 10(442KB) LOS objects, 31% free, 34MB/50MB, paused 2.635ms total 120.476ms
,I/EventLogService( 1771): Opted in for usage reporting
,I/EventLogService( 1771): Aggregate from 1454418061260 (log), 1454418061260 (data)
,W/EventLogAggregator( 1771): Unknown tag: snet_gcore
W/EventLogAggregator( 1771): Unknown tag: snet_launch_service
,I/ServiceDumpSys( 1771): dumping service [account]
,D/HeadsetStateMachine( 2181): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2181): Disconnected process message: 10, size: 0
,W/bt-btm  ( 2181): Stopping oneshot timer
,D/HeadsetStateMachine( 2181): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2181): Disconnected process message: 10, size: 0,
,D/GCM     ( 1203): Message class com.google.f.a.a.i
,D/HeadsetStateMachine( 2181): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2181): Disconnected process message: 10, size: 0
,I/BooksSync( 4056): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 4056): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1203): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1203): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1203): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1203): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1203): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1203): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1203): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1203): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1203): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1203): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 4056): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 4056): Soft error
E/BooksSync( 4056): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4056): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 4056): Sync error
E/BooksSync( 4056): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4056): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 4056): Finished books sync
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1039367, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2181): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2181): Disconnected process message: 10, size: 0
,V/KeepSync( 4015): Connecting to GoogleApiClient
,I/GLSUser ( 1203): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1203): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1203): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1203): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1203): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,V/KeepSync( 4015): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 4015): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4015): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4015): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1203): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1203): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1203): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1203): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1203): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 4015): IOException
E/KeepSync( 4015): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 4015): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 4015): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 4015): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 4015): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 4015): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 4015): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 4015): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 4015): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 4015): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 4015): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 4015): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 4015): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 4015): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 4015): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 4015): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 4015): 	... 10 more
W/KeepSync( 4015): Sync result 2
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 1136372, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2181): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2181): Disconnected process message: 10, size: 0
,I/GLSUser ( 1203): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1203): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1203): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1203): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1203): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3196): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3196): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3196): 	at jdm.a(PG:82)
E/HttpOperation( 3196): 	at jcs.o(PG:406)
E/HttpOperation( 3196): 	at jcn.a(PG:1379)
E/HttpOperation( 3196): 	at jcs.i(PG:143)
E/HttpOperation( 3196): 	at blb.a(PG:3937)
E/HttpOperation( 3196): 	at czp.a(PG:18188)
E/HttpOperation( 3196): 	at czp.a(PG:9081)
E/HttpOperation( 3196): 	at czq.run(PG:1686)
E/HttpOperation( 3196): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3196): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3196): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3196): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3196): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3196): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3196): 	at jdj.a(PG:4091)
E/HttpOperation( 3196): 	at jdj.a(PG:1125)
E/HttpOperation( 3196): 	at jdm.a(PG:77)
E/HttpOperation( 3196): 	... 12 more
E/HttpOperation( 3196): Caused by: faj: BadAuthentication
E/HttpOperation( 3196): 	at fal.a(PG:38)
E/HttpOperation( 3196): 	at jdj.a(PG:4089)
E/HttpOperation( 3196): 	... 14 more
,I/GLSUser ( 1203): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1203): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1203): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1203): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1203): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3196): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3196): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3196): 	at jdm.a(PG:82)
E/HttpOperation( 3196): 	at jcs.o(PG:406)
E/HttpOperation( 3196): 	at jcn.a(PG:1379)
E/HttpOperation( 3196): 	at jcs.i(PG:143)
E/HttpOperation( 3196): 	at hec.a(PG:42)
E/HttpOperation( 3196): 	at hee.a(PG:102)
E/HttpOperation( 3196): 	at czr.a(PG:65)
E/HttpOperation( 3196): 	at kka.a(PG:108)
E/HttpOperation( 3196): 	at czp.a(PG:19176)
E/HttpOperation( 3196): 	at czp.a(PG:9081)
E/HttpOperation( 3196): 	at czq.run(PG:1686)
E/HttpOperation( 3196): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3196): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3196): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3196): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3196): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3196): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3196): 	at jdj.a(PG:4091)
E/HttpOperation( 3196): 	at jdj.a(PG:1125)
E/HttpOperation( 3196): 	at jdm.a(PG:77)
E/HttpOperation( 3196): 	... 15 more
E/HttpOperation( 3196): Caused by: faj: BadAuthentication
E/HttpOperation( 3196): 	at fal.a(PG:38)
E/HttpOperation( 3196): 	at jdj.a(PG:4089)
E/HttpOperation( 3196): 	... 17 more
E/ExperimentLoader( 3196): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3196): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3196): 	at jdm.a(PG:82)
E/ExperimentLoader( 3196): 	at jcs.o(PG:406)
E/ExperimentLoader( 3196): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3196): 	at jcs.i(PG:143)
E/ExperimentLoader( 3196): 	at hec.a(PG:42)
E/ExperimentLoader( 3196): 	at hee.a(PG:102)
E/ExperimentLoader( 3196): 	at czr.a(PG:65)
E/ExperimentLoader( 3196): 	at kka.a(PG:108)
E/ExperimentLoader( 3196): 	at czp.a(PG:19176)
E/ExperimentLoader( 3196): 	at czp.a(PG:9081)
E/ExperimentLoader( 3196): 	at czq.run(PG:1686)
E/ExperimentLoader( 3196): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3196): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3196): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3196): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3196): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3196): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3196): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3196): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3196): 	at jdm.a(PG:77)
E/ExperimentLoader( 3196): 	... 15 more
E/ExperimentLoader( 3196): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3196): 	at fal.a(PG:38)
E/ExperimentLoader( 3196): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3196): 	... 17 more
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 1168834, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2181): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2181): Disconnected process message: 10, size: 0
,I/UsageStatsService(  821): User[0] Flushing usage stats to disk
,D/HeadsetStateMachine( 2181): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2181): Disconnected process message: 10, size: 0
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 4408): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 4408): CheckJNI is OFF
D/AndroidRuntime( 4408): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  821): Force stopping com.test.thalitest appid=10265 user=-1: uninstall pkg
I/ActivityManager(  821): Killing 3784:com.test.thalitest/u0a265 (adj 0): stop com.test.thalitest
W/PackageSettings(  821): Skipping PackageSetting{c237c9c com.example.hello/10273} due to missing metadata
E/libprocessgroup(  821): failed to kill 1 processes for processgroup 3784
W/ActivityManager(  821): Force removing ActivityRecord{59bdcdd u0 com.test.thalitest/.MainActivity t28}: app died, no saved state
D/WifiService(  821): Client connection lost with reason: 4
W/InputDispatcher(  821): channel 'ca104fe com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
E/InputDispatcher(  821): channel 'ca104fe com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Channel is unrecoverably broken and will be disposed!
W/InputDispatcher(  821): Attempted to unregister already unregistered input channel 'ca104fe com.test.thalitest/com.test.thalitest.MainActivity (server)'
W/WindowManager(  821): Failed looking up window
W/WindowManager(  821): java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@721c8b9 does not exist
W/WindowManager(  821): 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8539)
W/WindowManager(  821): 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8530)
W/WindowManager(  821): 	at com.android.server.wm.WindowState$DeathRecipient.binderDied(WindowState.java:1142)
W/WindowManager(  821): 	at android.os.BinderProxy.sendDeathNotice(Binder.java:551)
I/WindowState(  821): WIN DEATH: null
V/ActivityManager(  821): Display changed displayId=0
I/ActivityManager(  821): Force stopping com.test.thalitest appid=10265 user=0: pkg removed
D/TaskPersister(  821): removeObsoleteFile: deleting file=28_task.xml
I/Keyboard.Facilitator( 1254): resetDictionaries() : en_US
I/Keyboard.Facilitator.DecoderInitializer( 1254): run()
I/InputReader(  821): Reconfiguring input devices.  changes=0x00000010
D/BuaReceiver( 3474): ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
I/Decoder ( 1254): createOrResetDecoder
I/art     ( 1066): Explicit concurrent mark sweep GC freed 74360(2MB) AllocSpace objects, 0(0B) LOS objects, 18% free, 72MB/88MB, paused 1.479ms total 52.235ms
I/ActivityManager(  821): Start proc 4425:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
I/art     ( 1528): Explicit concurrent mark sweep GC freed 2808(231KB) AllocSpace objects, 0(0B) LOS objects, 22% free, 26MB/34MB, paused 326us total 34.427ms
W/InputMethodManagerService(  821): Got RemoteException sending setActive(false) notification to pid 3784 uid 10265
I/Keyboard.Facilitator( 1254): onFinishInput()
I/art     (  821): Explicit concurrent mark sweep GC freed 40096(2MB) AllocSpace objects, 13(490KB) LOS objects, 31% free, 34MB/50MB, paused 2.104ms total 83.009ms
I/art     (  821): WaitForGcToComplete blocked for 51.999ms for cause Explicit
W/LocationOracleImpl( 1528): Best location was null
I/HotwordRecognitionRnr( 1528): Starting hotword detection.
I/MicrophoneInputStream( 1528): mic_starting com.google.android.apps.gsa.speech.audio.u@156ff561
I/AudioFlinger(  357): AudioFlinger's thread 0xb40ef000 ready to run
I/art     ( 1375): Explicit concurrent mark sweep GC freed 4992(364KB) AllocSpace objects, 12(1408KB) LOS objects, 31% free, 35MB/51MB, paused 1.235ms total 28.167ms
I/SoundTriggerHwService::Module(  357): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/MicrophoneInputStream( 1528): mic_started com.google.android.apps.gsa.speech.audio.u@156ff561
I/ConfigService( 1203): onCreate
D/audio_hw_primary(  357): select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
D/msm8974_platform(  357): platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
E/ACDB-LOADER(  357): Error: ACDB AudProc vol returned = -19
D/audio_hw_primary(  357): enable_snd_device: snd_device(55: voice-rec-mic)
D/audio_hw_primary(  357): enable_audio_route: apply and update mixer path: audio-record
D/JobSchedulerService(  821): Receieved: android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  821): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/art     ( 1203): Explicit concurrent mark sweep GC freed 63198(3MB) AllocSpace objects, 11(1213KB) LOS objects, 36% free, 27MB/43MB, paused 1.064ms total 42.463ms
I/HotwordWorker( 1528): onReady
I/Keyboard.Facilitator.MainLanguageModelLoader( 1254): run()
D/VoicemailCleanupService( 4425): Cleaning up data for package: com.test.thalitest
I/Keyboard.Facilitator.MainLanguageModelLoader( 1254): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1254): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1254): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1254): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1254): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1254): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1254): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1254): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1254): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1254): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1254): run()
I/StatsUtilsManager( 1254): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1254): shouldRecordStats() = Too Soon
I/WebViewFactory( 1528): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/ActivityManager(  821): Start proc 4467:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
I/ContactLocale( 4425): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
I/art     (  821): Explicit concurrent mark sweep GC freed 8112(382KB) AllocSpace objects, 2(220KB) LOS objects, 31% free, 34MB/50MB, paused 2.141ms total 191.373ms
D/WifiService(  821): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@2bcd5b8f}
E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=25.75 rxSuccessRate=31.25 targetRoamBSSID=any RSSI=-51
I/LibraryLoader( 1528): Time to load native libraries: 2 ms (timestamps 3036-3038)
I/LibraryLoader( 1528): Expected native library version number "",actual native library version number ""
W/art     ( 1528): Attempt to remove local handle scope entry from IRT, ignoring
I/ActivityManager(  821): Start proc 4491:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
D/Launcher.Workspace( 1375): 11683562 - stripEmptyScreens()
D/Launcher.Workspace( 1375): 11683562 - stripEmptyScreens()
E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=62.38 rxSuccessRate=190.12 targetRoamBSSID=any RSSI=-51
E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1660642579
E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
W/ContextImpl( 4491): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2609 
E/NetworkScheduler.SchedulerReceiver( 1203): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1203): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
D/PackageBroadcastService( 1771): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1771): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1771): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1771): Module APK com.google.android.play.games already loaded
I/ActivityManager(  821): Killing 2489:com.google.android.calendar/u0a37 (adj 15): empty #17
W/art     ( 1528): Attempt to remove local handle scope entry from IRT, ignoring
I/art     ( 4408): System.exit called, status: 0
I/AndroidRuntime( 4408): VM exiting with result code 0.
I/kickstart(  871): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
I/kickstart(  871): STATUS: Wrote to /sys/power/wake_lock
E/kickstart(  871): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2
I/kickstart(  871): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2' for writing
D/ChimeraCfgMgr( 1771): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1771): Module APK com.google.android.play.games already loaded
I/LocationSettingsChecker( 1771): Removing dialog suppression flag for package com.test.thalitest
E/SQLiteLog( 1771): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/DriveAsyncService( 1771): disk I/O error (code 3850)
E/DriveAsyncService( 1771): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 1771): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 1771): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/DriveAsyncService( 1771): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 1771): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 1771): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/DriveAsyncService( 1771): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/DriveAsyncService( 1771): 	at com.google.android.gms.drive.database.k.l(SourceFile:596)
E/DriveAsyncService( 1771): 	at com.google.android.gms.drive.database.k.b(SourceFile:570)
E/DriveAsyncService( 1771): 	at com.google.android.gms.drive.database.f.h(SourceFile:1473)
E/DriveAsyncService( 1771): 	at com.google.android.gms.drive.api.a.bc.a(SourceFile:16)
E/DriveAsyncService( 1771): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/DriveAsyncService( 1771): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 1771): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 1771): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1771): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
--------- beginning of crash
E/AndroidRuntime( 1771): FATAL EXCEPTION: PlayGamesAsyncThread1
E/AndroidRuntime( 1771): Process: com.google.android.gms, PID: 1771
E/AndroidRuntime( 1771): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1771): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 1771): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/AndroidRuntime( 1771): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 1771): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 1771): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/AndroidRuntime( 1771): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:469)
E/AndroidRuntime( 1771): 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
E/AndroidRuntime( 1771): 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
E/AndroidRuntime( 1771): 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
E/AndroidRuntime( 1771): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
E/AndroidRuntime( 1771): 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
E/AndroidRuntime( 1771): 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3044)
E/AndroidRuntime( 1771): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
E/AndroidRuntime( 1771): 	at com.google.android.gms.games.service.PlayGamesAsyncService$OperationAdapter.execute(PlayGamesAsyncService.java:920)
E/AndroidRuntime( 1771): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
E/AndroidRuntime( 1771): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 1771): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 1771): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 1771): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 1771): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1771): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1771): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1771): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1771): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1771): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1771): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1771): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1771): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1771): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1771): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 1771): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 1771): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1771): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 1771): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 1771): 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
E/SQLiteDatabase( 1771): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 1771): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 1771): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1771): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1771): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 1771): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 1771): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 1771): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1771): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1771): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 1771): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 1771): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1771): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1771): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1771): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteOpenHelper( 1771): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteOpenHelper( 1771): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 1771): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteOpenHelper( 1771): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 1771): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 1771): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 1771): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 1771): 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
E/SQLiteOpenHelper( 1771): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 1771): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 1771): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 1771): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 1771): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteOpenHelper( 1771): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/SQLiteOpenHelper( 1771): Opened metrics.db in read-only mode
D/GOOGLEHELP_CompatibleDatabase( 1771): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1771): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
I/ActivityManager(  821): Start proc 4528:com.google.android.gms.wearable/u0a11 for service com.google.android.gms/.wearable.service.WearableControlService
E/SQLiteDatabase( 1771): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 1771): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1771): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1771): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1771): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1771): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1771): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1771): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1771): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1771): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1771): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1771): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 1771): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 1771): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 1771): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1771): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 1771): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteDatabase( 1771): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1771): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1771): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 1771): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 1771): Couldn't open phenotype.db for writing (will try read-only):
E/SQLiteOpenHelper( 1771): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1771): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1771): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 1771): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 1771): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1771): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1771): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1771): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteOpenHelper( 1771): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteOpenHelper( 1771): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 1771): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteOpenHelper( 1771): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 1771): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 1771): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 1771): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 1771): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteOpenHelper( 1771): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 1771): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 1771): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteOpenHelper( 1771): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 1771): (8) statement aborts at 16: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
D/GOOGLEHELP_CompatibleDatabase( 1771): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
I/Process ( 1771): Sending signal. PID: 1771 SIG: 9
E/DataBuffer( 1800): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2570a0e1)
W/ResourcesManager(  821): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(  821): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/art     ( 1800): Explicit concurrent mark sweep GC freed 16843(991KB) AllocSpace objects, 8(128KB) LOS objects, 37% free, 26MB/42MB, paused 1.270ms total 40.821ms
E/DropBoxManagerService(  821): Can't write: system_app_crash
E/DropBoxManagerService(  821): java.io.FileNotFoundException: /data/system/dropbox/drop97.tmp: open failed: EROFS (Read-only file system)
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
W/ResourcesManager( 4528): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4528): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/Launcher( 1375): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@352d689b new=com.google.android.velvet.VelvetApplication@352d689b
E/SQLiteLog( 1375): (3850) statement aborts at 24: [DELETE FROM shortcut_and_widget_previews WHERE name LIKE ? OR name LIKE ?] disk I/O error
I/MultiDex( 4528): VM with version 2.1.0 has multidex support
I/MultiDex( 4528): install
I/MultiDex( 4528): VM has multidex support, MultiDex support library is disabled.
D/WifiService(  821): Client connection lost with reason: 4
I/ActivityManager(  821): Start proc 4553:com.google.android.apps.docs/u0a46 for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
I/UpdateIcingCorporaServi( 1528): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/ActivityManager(  821): Process com.google.android.gms (pid 1771) has died
W/ActivityManager(  821): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 1000ms
W/ActivityManager(  821): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 1000ms
W/ActivityManager(  821): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 1000ms
W/ActivityManager(  821): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
W/ActivityManager(  821): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 1000ms
W/ActivityManager(  821): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 1000ms
V/JNIHelp ( 4528): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
I/OpenGLRenderer(  821): Initialized EGL, version 1.4
E/SQLiteLog( 1528): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
D/OpenGLRenderer(  821): Enabling debug mode 0
W/InputMethodManagerService(  821): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@17332e29 attribute=null, token = android.os.BinderProxy@2b545787
I/ProviderInstaller( 4528): Installed default security provider GmsCore_OpenSSL
I/ActivityManager(  821): Start proc 4570:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
E/SharedPreferencesImpl( 1528): Couldn't create directory for SharedPreferences file /data/data/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml
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
W/NativeLibraryUtils( 4528): Failed to open lock file
W/NativeLibraryUtils( 4528): java.io.FileNotFoundException: /data/data/com.google.android.gms/cache/.lib.lock: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 4528): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/NativeLibraryUtils( 4528): 	at java.io.RandomAccessFile.<init>(RandomAccessFile.java:117)
W/NativeLibraryUtils( 4528): 	at com.google.android.gms.common.util.ax.a(SourceFile:305)
W/NativeLibraryUtils( 4528): 	at com.google.android.gms.common.app.a.run(SourceFile:136)
W/NativeLibraryUtils( 4528): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 4528): 	at libcore.io.Posix.open(Native Method)
W/NativeLibraryUtils( 4528): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/NativeLibraryUtils( 4528): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/NativeLibraryUtils( 4528): 	... 3 more
I/ActivityManager(  821): Killing 3374:com.android.providers.calendar/u0a3 (adj 15): empty #17
I/OpenGLRenderer(  821): Initialized EGL, version 1.4
I/ActivityManager(  821): Start proc 4593:com.google.android.gms/u0a11 for service com.google.android.gms/.feedback.FeedbackService
W/ResourcesManager( 4593): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4593): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/MultiDex( 4593): VM with version 2.1.0 has multidex support
I/MultiDex( 4593): install
I/MultiDex( 4593): VM has multidex support, MultiDex support library is disabled.
E/SQLiteDatabase( 4593): Failed to open database '/data/data/com.google.android.gms/databases/snet_safe_browsing.db'.
E/SQLiteDatabase( 4593): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4593): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4593): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4593): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4593): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4593): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4593): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4593): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4593): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4593): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4593): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4593): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4593): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4593): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4593): 	at com.google.android.gms.security.snet.ab.a(SourceFile:1181)
E/SQLiteDatabase( 4593): 	at com.google.android.gms.security.snet.ab.a(SourceFile:1200)
E/SQLiteDatabase( 4593): 	at com.google.android.gms.security.snet.w.doInBackground(SourceFile:133)
E/SQLiteDatabase( 4593): 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
E/SQLiteDatabase( 4593): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4593): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4593): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4593): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4593): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 4593): Failed to open database '/data/data/com.google.android.gms/databases/snet_safe_browsing.db'.
E/SQLiteDatabase( 4593): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4593): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4593): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4593): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4593): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4593): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4593): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4593): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4593): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4593): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4593): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4593): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4593): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4593): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4593): 	at com.google.android.gms.security.snet.aa.b(SourceFile:826)
E/SQLiteDatabase( 4593): 	at com.google.android.gms.security.snet.aa.a(SourceFile:847)
E/SQLiteDatabase( 4593): 	at com.google.android.gms.security.snet.w.doInBackground(SourceFile:133)
E/SQLiteDatabase( 4593): 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
E/SQLiteDatabase( 4593): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4593): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4593): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4593): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4593): 	at java.lang.Thread.run(Thread.java:818)
I/HotwordDetector( 1528): Closing mic
I/MicrophoneInputStream( 1528): mic_close com.google.android.apps.gsa.speech.audio.u@156ff561
E/Search.SharedPreferencesProto( 1528): Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
V/JNIHelp ( 4593): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
I/ProviderInstaller( 4593): Installed default security provider GmsCore_OpenSSL
W/NativeLibraryUtils( 4593): Failed to open lock file
W/NativeLibraryUtils( 4593): java.io.FileNotFoundException: /data/data/com.google.android.gms/cache/.lib.lock: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 4593): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/NativeLibraryUtils( 4593): 	at java.io.RandomAccessFile.<init>(RandomAccessFile.java:117)
W/NativeLibraryUtils( 4593): 	at com.google.android.gms.common.util.ax.a(SourceFile:305)
W/NativeLibraryUtils( 4593): 	at com.google.android.gms.common.app.a.run(SourceFile:136)
W/NativeLibraryUtils( 4593): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 4593): 	at libcore.io.Posix.open(Native Method)
W/NativeLibraryUtils( 4593): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/NativeLibraryUtils( 4593): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/NativeLibraryUtils( 4593): 	... 3 more
D/audio_hw_primary(  357): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  357): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  357): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1528): Hotword detection finished
I/HotwordRecognitionRnr( 1528): Stopping hotword detection.
E/SQLiteDatabase( 4593): Failed to open database '/data/data/com.google.android.gms/databases/reminders.db'.
E/SQLiteDatabase( 4593): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4593): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4593): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4593): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4593): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4593): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4593): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4593): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4593): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4593): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4593): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4593): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4593): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4593): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 4593): 	at com.google.android.gms.reminders.provider.RemindersProvider.query(SourceFile:419)
E/SQLiteDatabase( 4593): 	at android.content.ContentProvider.query(ContentProvider.java:966)
E/SQLiteDatabase( 4593): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:211)
E/SQLiteDatabase( 4593): 	at android.content.ContentResolver.query(ContentResolver.java:478)
E/SQLiteDatabase( 4593): 	at android.content.ContentResolver.query(ContentResolver.java:422)
E/SQLiteDatabase( 4593): 	at com.google.android.gms.reminders.a.a.a(SourceFile:71)
E/SQLiteDatabase( 4593): 	at com.google.android.gms.reminders.a.c.doInBackground(SourceFile:39)
E/SQLiteDatabase( 4593): 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
E/SQLiteDatabase( 4593): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4593): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4593): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4593): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4593): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteOpenHelper( 4593): Couldn't open reminders.db for writing (will try read-only):
E/SQLiteOpenHelper( 4593): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4593): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4593): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 4593): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 4593): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4593): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4593): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4593): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteOpenHelper( 4593): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteOpenHelper( 4593): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 4593): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteOpenHelper( 4593): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 4593): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 4593): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 4593): 	at com.google.android.gms.reminders.provider.RemindersProvider.query(SourceFile:419)
E/SQLiteOpenHelper( 4593): 	at android.content.ContentProvider.query(ContentProvider.java:966)
E/SQLiteOpenHelper( 4593): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:211)
E/SQLiteOpenHelper( 4593): 	at android.content.ContentResolver.query(ContentResolver.java:478)
E/SQLiteOpenHelper( 4593): 	at android.content.ContentResolver.query(ContentResolver.java:422)
E/SQLiteOpenHelper( 4593): 	at com.google.android.gms.reminders.a.a.a(SourceFile:71)
E/SQLiteOpenHelper( 4593): 	at com.google.android.gms.reminders.a.c.doInBackground(SourceFile:39)
E/SQLiteOpenHelper( 4593): 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
E/SQLiteOpenHelper( 4593): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteOpenHelper( 4593): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteOpenHelper( 4593): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteOpenHelper( 4593): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteOpenHelper( 4593): 	at java.lang.Thread.run(Thread.java:818)
I/ActivityManager(  821): Killing 3018:com.google.android.music:main/u0a66 (adj 15): empty #17
W/SQLiteOpenHelper( 4593): Opened reminders.db in read-only mode
E/SQLiteDatabase( 4593): Failed to open database '/data/data/com.google.android.gms/databases/plus.db'.
E/SQLiteDatabase( 4593): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4593): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4593): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4593): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4593): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4593): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4593): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4593): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4593): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4593): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4593): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4593): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4593): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4593): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4593): 	at com.google.android.gms.plus.provider.PlusProvider.a(SourceFile:329)
E/SQLiteDatabase( 4593): 	at com.google.android.gms.plus.provider.b.a(SourceFile:146)
E/SQLiteDatabase( 4593): 	at com.google.android.gms.plus.provider.b.doInBackground(SourceFile:143)
E/SQLiteDatabase( 4593): 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
E/SQLiteDatabase( 4593): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4593): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4593): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4593): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4593): 	at java.lang.Thread.run(Thread.java:818)
E/AndroidRuntime( 4593): FATAL EXCEPTION: AsyncTask #3
E/AndroidRuntime( 4593): Process: com.google.android.gms, PID: 4593
E/AndroidRuntime( 4593): java.lang.RuntimeException: An error occured while executing doInBackground()
E/AndroidRuntime( 4593): 	at android.os.AsyncTask$3.done(AsyncTask.java:304)
E/AndroidRuntime( 4593): 	at java.util.concurrent.FutureTask.finishCompletion(FutureTask.java:355)
E/AndroidRuntime( 4593): 	at java.util.concurrent.FutureTask.setException(FutureTask.java:222)
E/AndroidRuntime( 4593): 	at java.util.concurrent.FutureTask.run(FutureTask.java:242)
E/AndroidRuntime( 4593): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/AndroidRuntime( 4593): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 4593): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 4593): 	at java.lang.Thread.run(Thread.java:818)
E/AndroidRuntime( 4593): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4593): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4593): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 4593): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 4593): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4593): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4593): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4593): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AndroidRuntime( 4593): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AndroidRuntime( 4593): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 4593): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AndroidRuntime( 4593): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 4593): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 4593): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 4593): 	at com.google.android.gms.plus.provider.PlusProvider.a(SourceFile:329)
E/AndroidRuntime( 4593): 	at com.google.android.gms.plus.provider.b.a(SourceFile:146)
E/AndroidRuntime( 4593): 	at com.google.android.gms.plus.provider.b.doInBackground(SourceFile:143)
E/AndroidRuntime( 4593): 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
E/AndroidRuntime( 4593): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AndroidRuntime( 4593): 	... 4 more
E/native  ( 1254): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1254): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/Search.SharedPreferencesProto( 1528): Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
E/Search.SharedPreferencesProto( 1528): Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
E/DropBoxManagerService(  821): Can't write: system_app_crash
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
E/native  ( 1254): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1254): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1254): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1254): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1254): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1254): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
I/Icing   ( 4593): Storage manager: low false usage 1.98MB avail 20.74GB capacity 22.09GB
E/kickstart(  871): ERROR: function: rx_data:267 Timeout Occured, No response or command came from the target!
I/kickstart(  871): WARNING: function: sahara_start:892 Retrying memory read request
D/GFEEDBACK_SendErrorReportOperation( 4593): Error doing instant send: java.io.IOException: failed to create reports directory
E/GFEEDBACK_SendErrorReportOperation( 4593): Error saving report: java.io.IOException: failed to create reports directory
I/GAv4    ( 4553): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4553):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4553):   adb logcat -s GAv4
W/Icing   ( 4593): Received bad json for section weights override -- ignoring.
W/GAv4    ( 4553): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/Icing   ( 4593): Received bad json for corpus context scoring override -- ignoring.
W/Icing   ( 4593): Received bad json for section weights override -- ignoring.
W/Icing   ( 4593): Received bad json for corpus context scoring override -- ignoring.
W/GAv4    ( 4553): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
E/SharedPreferencesImpl( 4553): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4553): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4553): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
E/SharedPreferencesImpl( 4553): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/Icing   ( 4593): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.docids for write failed: Read-only file system
E/Icing   ( 4593): Could not open file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.docids
E/Icing   ( 4593): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.perdocdata for write failed: Read-only file system
E/Icing   ( 4593): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.perdocdata failed: Read-only file system
E/Icing   ( 4593): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.cscoring for write failed: Read-only file system
E/Icing   ( 4593): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.cscoring failed: Read-only file system
E/Icing   ( 4593): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.docs for write failed: Read-only file system
E/Icing   ( 4593): Could not open file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.docs
E/Icing   ( 4593): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tagacct.tags.h for write failed: Read-only file system
E/Icing   ( 4593): Trie initialize fail
E/Icing   ( 4593): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tagacct.counts failed: Read-only file system
E/Icing   ( 4593): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.h for write failed: Read-only file system
E/Icing   ( 4593): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.h failed: Read-only file system
E/Icing   ( 4593): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.n failed: Read-only file system
E/Icing   ( 4593): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.x failed: Read-only file system
E/Icing   ( 4593): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.s failed: Read-only file system
E/Icing   ( 4593): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.deleted failed: Read-only file system
E/Icing   ( 4593): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.usage for write failed: Read-only file system
E/Icing   ( 4593): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.usage failed: Read-only file system
E/Icing   ( 4593): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.delusage for write failed: Read-only file system
E/Icing   ( 4593): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.delusage failed: Read-only file system
E/Icing   ( 4593): Init docstore failed
E/Icing   ( 4593): Index init failed, resetting corpora
E/Icing   ( 4593): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/idx.index failed: Read-only file system
E/Icing   ( 4593): Clearing index failed
E/Icing   ( 4593): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.docids failed: Read-only file system
E/Icing   ( 4593): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.perdocdata failed: Read-only file system
E/Icing   ( 4593): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.cscoring failed: Read-only file system
E/Icing   ( 4593): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.docs failed: Read-only file system
E/Icing   ( 4593): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-0 failed: Read-only file system
E/Icing   ( 4593): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-24 failed: Read-only file system
E/Icing   ( 4593): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-30 failed: Read-only file system
E/Icing   ( 4593): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user.__unseen__i.43133bd20a9b3232 failed: Read-only file system
E/Icing   ( 4593): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._i.e66c36715ed1937e failed: Read-only file system
E/Icing   ( 4593): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._iim.c6e5dff4518fbbd9 failed: Read-only file system
E/Icing   ( 4593): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._io_im.1f9d7d94f051768f failed: Read-only file system
E/Icing   ( 4593): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._io_unim.b8d0a49354216c2f failed: Read-only file system
E/Icing   ( 4593): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._o.0f0f93445ed1937e failed: Read-only file system
E/Icing   ( 4593): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._sq_ig_i_person.df4a28e480c88f1e failed: Read-only file system
E/Icing   ( 4593): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._u.f26d6a3e5ed1937e failed: Read-only file system
E/Icing   ( 4593): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._us.da9dbfca5ed1937e failed: Read-only file system
E/Icing   ( 4593): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.deleted failed: Read-only file system
E/Icing   ( 4593): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tagacct.counts failed: Read-only file system
E/Icing   ( 4593): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.h failed: Read-only file system
E/Icing   ( 4593): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.n failed: Read-only file system
E/Icing   ( 4593): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.x failed: Read-only file system
E/Icing   ( 4593): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.s failed: Read-only file system
E/Icing   ( 4593): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.deleted failed: Read-only file system
E/Icing   ( 4593): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.usage failed: Read-only file system
E/Icing   ( 4593): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.delusage failed: Read-only file, system
E/Icing   ( 4593): Clearing docstore failed
E/Icing   ( 4593): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/compact_status failed: Read-only file system
E/Icing   ( 4593): Deleting compact status failed
W/AnalyticsTrackerProxyImpl( 4553): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
E/SQLiteDatabase( 4553): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 4553): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4553): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4553): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4553): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4553): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4553): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4553): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4553): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4553): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4553): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4553): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4553): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4553): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4553): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4553): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 4553): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 4553): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 4553): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 4553): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 4553): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 4553): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4553): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4553): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4553): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4553): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 4553): 	at gir$c.run(Unknown Source)
E/GAv4    ( 4553): Opening the database failed, dropping the table and recreating it
E/SharedPreferencesImpl( 4553): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SQLiteDatabase( 4553): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 4553): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4553): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4553): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4553): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4553): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4553): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4553): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4553): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4553): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4553): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4553): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4553): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4553): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4553): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4553): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 4553): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 4553): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 4553): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 4553): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 4553): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 4553): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4553): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4553): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4553): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4553): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 4553): 	at gir$c.run(Unknown Source)
E/GAv4    ( 4553): Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 4553): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4553): Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.

```
