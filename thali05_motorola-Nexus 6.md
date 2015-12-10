#### Test 50650278b86327b_thali05_motorola-Nexus 6 Logs


```
--------- beginning of main
,E/WifiStateMachine(  825): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=5.03 targetRoamBSSID=any RSSI=-53
E/WifiStateMachine(  825): WifiStateMachine starting scan for "NG7005g"WPA_PSK with 2412,5220
D/AndroidRuntime( 3745): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 3745): CheckJNI is OFF
D/AndroidRuntime( 3745): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  825): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/WindowManager(  825): addAppToken: AppWindowToken{2445390d token=Token{278b17a4 ActivityRecord{128f8637 u0 com.test.thalitest/.MainActivity t24}}} to stack=1 task=24 at 0
V/WindowManager(  825): Adding window Window{3a61d70e u0 Starting com.test.thalitest} at 3 of 8 (after Window{36d0df92 u0 com.android.chrome/org.chromium.chrome.browser.document.DocumentActivity})
D/AndroidRuntime( 3745): Shutting down VM
I/MicrophoneInputStream( 1524): mic_close com.google.android.apps.gsa.speech.audio.u@1f90b957
I/HotwordDetector( 1524): Closing mic
I/ActivityManager(  825): Start proc 3759:com.test.thalitest/u0a265 for activity com.test.thalitest/.MainActivity
D/audio_hw_primary(  359): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  359): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  359): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1524): Stopping hotword detection.
I/HotwordRecognitionRnr( 1524): Hotword detection finished
I/ActivityManager(  825): Killing 3036:com.google.android.music:main/u0a66 (adj 15): empty #17
E/LocSvc_IzatApiV02(  825): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1659188499
E/LocSvc_IzatApiV02(  825): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
I/ActivityManager(  825): Killing 3233:com.google.android.apps.photos/u0a71 (adj 15): empty #18
I/kickstart(  875): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
I/kickstart(  875): STATUS: Wrote to /sys/power/wake_lock
,E/kickstart(  875): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1
I/kickstart(  875): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1' for writing
,I/WebViewFactory( 3759): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3759): Time to load native libraries: 2 ms (timestamps 2640-2642)
I/LibraryLoader( 3759): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3759): Binding Chromium to main looper Looper (main, tid 1) {6a1e3ce}
,I/LibraryLoader( 3759): Expected native library version number "",actual native library version number ""
I/chromium( 3759): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3759): Initializing chromium process, singleProcess=true
,W/art     ( 3759): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3759): ApplicationContext is null in ApplicationStatus
,W/chromium( 3759): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3759): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 3759): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3759): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/BluetoothManagerService(  825): Message: 20
,D/BluetoothManagerService(  825): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b781fbe:true
,W/art     ( 3759): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3759): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3759): CordovaWebView is running on device made by: motorola
,W/art     ( 3759): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 3759): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3759): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,D/Atlas   ( 3759): Validating map...
,V/WindowManager(  825): Adding window Window{32c9f46e u0 com.test.thalitest/com.test.thalitest.MainActivity} at 3 of 9 (before Window{3a61d70e u0 Starting com.test.thalitest})
,W/chromium( 3759): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3759): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3759): Enabling debug mode 0
,I/ActivityManager(  825): Displayed com.test.thalitest/.MainActivity: +962ms (total +1m49s606ms)
,I/Keyboard.Facilitator( 1247): onFinishInput()
,W/BindingManager( 3759): Cannot call determinedVisibility() - never saw a connection for the pid: 3759
,D/JsMessageQueue( 3759): Set native->JS mode to OnlineEventsBridgeMode
,I/kickstart(  875): STATUS: Received file 'm9kefs1'
I/kickstart(  875): STATUS: 950272 bytes transferred in 0.994590 seconds
I/kickstart(  875): STATUS: Successfully downloaded files from target 
I/kickstart(  875): STATUS: Wrote to /sys/power/wake_unlock
,I/kickstart(  875): STATUS: Sahara protocol completed
,D/jxcore_app_log( 3759): JniHelper::setJavaVM(0xb489d200), pthread_self() = -1576266880
,D/JX-Cordova( 3759): jxcore cordova android initializing
,W/jxcore-log( 3759): Initializing JXcore engine
W/jxcore-log( 3759): JXcore engine is ready
,W/jxcore-log( 3759): Starting JXcore engine
,W/.test.thalitest( 3759): type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[10470]" dev="sockfs" ino=10470 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 3759): type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/.test.thalitest( 3759): type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[13370]" dev="sockfs" ino=13370 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/.test.thalitest( 3759): type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[21985]" dev="sockfs" ino=21985 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 3759): Platform android
W/jxcore-log( 3759): 
,W/jxcore-log( 3759): Process ARCH arm
W/jxcore-log( 3759): 
,I/jxcore-log( 3759): JXcore Cordova bridge is ready!
I/jxcore-log( 3759): 
W/jxcore-log( 3759): JXcore engine is started
,I/Choreographer( 3759): Skipped 136 frames!  The application may be doing too much work on its main thread.
I/chromium( 3759): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3759): Toggling radios to true
I/jxcore-log( 3759): 
,D/BluetoothAdapter( 3759): enable(): BT is already enabled..!
,D/WifiService(  825): New client listening to asynchronous messages
,D/WifiService(  825): setWifiEnabled: true pid=3759, uid=10265
E/WifiService(  825): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3759): Radios toggled
I/jxcore-log( 3759): 
,D/BluetoothManagerService(  825): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/wpa_supplicant( 1130): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
E/WifiStateMachine(  825): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  825): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,I/jxcore-log( 3759): Got Device Bluetooth address: F8:CF:C5:D9:E5:61
I/jxcore-log( 3759): 
,D/CommandListener(  355): Clearing all IP addresses on wlan0
,I/jxcore-log( 3759): Perf Test app loaded loaded
I/jxcore-log( 3759): 
V/NativeCrypto( 1276): Read error: ssl=0xb4886000: I/O error during system call, Connection timed out
,I/Choreographer( 3759): Skipped 63 frames!  The application may be doing too much work on its main thread.
D/ConnectivityService(  825): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  825): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,E/WifiStateMachine(  825): Start Disconnecting Watchdog 1
,V/NativeCrypto( 1276): SSL shutdown failed: ssl=0xb4886000: I/O error during system call, Broken pipe
,E/WifiStateMachine(  825): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,D/ConnectivityService(  825): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10011
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  825): ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler },
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  825): DefaultState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  825): Forcing reevaluation
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  825): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  825): Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
,I/jxcore-log( 3759): check test folder
I/jxcore-log( 3759): 
I/jxcore-log( 3759): found test : ./testFindPeers.js
I/jxcore-log( 3759): 
,I/jxcore-log( 3759): found test : ./testSendData.js
I/jxcore-log( 3759): 
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  825): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
,D/CommandListener(  355): Clearing all IP addresses on wlan0
,D/ConnectivityService(  825): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler( 1059): CM callback handler got msg 524292
,D/WifiNetworkAgent(  825): NetworkAgent: NetworkAgent channel lost
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  825): OfflineState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  825): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  825): Disconnected - quitting
E/WifiStateMachine(  825): CMD_AUTO_CONNECT sup state CompletedState my state DisconnectedState nid=0 roam=3
E/WifiStateMachine(  825): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=0
D/CSLegacyTypeTracker(  825): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  825): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  825): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  825): MasterInitialState.processMessage what=3
,D/ConnectivityService(  825): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/PhoneInterfaceManager( 1353): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
,E/PhoneInterfaceManager( 1353): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
D/TelephonyManager(  825): getDataEnabled: retVal=false
,E/WifiConfigStore(  825): Setting BSSID for "NG7005g"WPA_PSK to any
E/WifiConfigStore(  825): will read network variables netId=0
,I/ActivityManager(  825): Start proc 3818:com.google.android.music:main/u0a66 for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver
,D/ConnectivityService(  825): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,E/WifiStateMachine(  825): CMD_AUTO_CONNECT did save config ->  nid=0
D/ConnectivityService(  825): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/WifiConfigStore(  825): will read network variables netId=0
,D/Tethering(  825): MasterInitialState.processMessage what=3
,E/ConnectivityService(  825): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,D/ConnectivityService(  825): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
,E/GpsLocationProvider(  825): No APN found to select.
,D/PhoneInterfaceManager( 1353): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1353): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  825): getDataEnabled: retVal=false
,I/chromium( 3759): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,E/GpsLocationProvider(  825): No APN found to select.
,I/MusicStore( 3818): Database version: 120
,W/ResourcesManager( 3818): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3818): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 3818): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ProviderInstaller( 3818): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 3818): GMSCore installation verified
,I/ConfigStore( 3818): Config Database version: 1
,I/art     ( 1276): Explicit concurrent mark sweep GC freed 24509(1415KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 1.523ms total 23.852ms
,I/art     (  825): Explicit concurrent mark sweep GC freed 41355(2MB) AllocSpace objects, 12(286KB) LOS objects, 32% free, 33MB/49MB, paused 1.149ms total 59.955ms
,I/MediaRouter( 3818): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 3818): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/ActivityManager(  825): Start proc 3851:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.steen.receiver.ConnectivityChangeReceiver
,I/GHttpClientFactory( 3818): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 3818): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  825): Killing 3410:com.google.android.gm/u0a78 (adj 15): empty #17
,I/ActivityManager(  825): Start proc 3879:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,I/ActivityManager(  825): Killing 2507:com.google.android.calendar/u0a37 (adj 15): empty #17
,D/SprintDMReceiver( 3879): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3879): simOperator:  IMSI: null
,D/SprintDMReceiver( 3879): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1816): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1816): onCreate
,D/SystemUpdateService( 1816): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1816): active receiver: enabled
,I/SystemUpdateService( 1816): showing system update notification
,I/iu.Environment( 1816): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1816): num queued entries: 0
I/iu.UploadsManager( 1816): num updated entries: 0
,I/iu.SyncManager( 1816): NEXT; no task
,D/ChimeraCfgMgr( 1816): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/ValidateNoPeople(  825): skipping global notification,
,I/Babel   ( 2797): connection state changed from CONNECTED to DISCONNECTED
,V/SystemUpdateService( 1816): retry (wakeup: false) in 3599936 ms
,I/ActivityManager(  825): Start proc 3899:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,D/SystemUpdateService( 1816): onDestroy
,I/ActivityManager(  825): Killing 3370:com.android.providers.calendar/u0a3 (adj 15): empty #17
,I/wpa_supplicant( 1130): wlan0: Trying to associate with SSID 'NG7005g'
,I/GAv4    ( 3899): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3899):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3899):   adb logcat -s GAv4
,W/GAv4    ( 3899): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3899): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3899): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/wpa_supplicant( 1130): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 1130): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1130): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=0 id_str=]
,D/ConnectivityService(  825): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} }
,E/WifiConfigStore(  825): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  825): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING,
,E/WifiConfigStore(  825): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  355): Setting iface cfg
I/WebViewFactory( 3899): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
E/WifiStateMachine(  825): Start Dhcp Watchdog 2
,E/WifiStateMachine(  825):  WifiLinkLayerStats: 
E/WifiStateMachine(  825):  my bss beacon rx: 564
E/WifiStateMachine(  825):  RSSI mgmt: -53
E/WifiStateMachine(  825):  BE :  rx=246 tx=133 lost=0 retries=1
E/WifiStateMachine(  825):  BK :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  825):  VI :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  825):  VO :  rx=4 tx=0 lost=0 retries=0
E/WifiStateMachine(  825):  on_time : 17170 tx_time=282 rx_time=541 scan_time=0
,D/ConnectivityService(  825): updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,I/LibraryLoader( 3899): Time to load native libraries: 1 ms (timestamps 9048-9049)
,I/LibraryLoader( 3899): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3899): Binding Chromium to main looper Looper (main, tid 1) {1093468d}
,I/LibraryLoader( 3899): Expected native library version number "",actual native library version number ""
I/chromium( 3899): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0,
,I/BrowserStartupController( 3899): Initializing chromium process, singleProcess=true
,W/art     ( 3899): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3899): ApplicationContext is null in ApplicationStatus
,E/native  (  825): do suspend false
,E/WifiStateMachine(  825): scanCount==0 - aborting
,W/chromium( 3899): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3899): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 3899): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3899): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,W/AudioManagerAndroid( 3899): Requires BLUETOOTH permission
,I/NSApplication( 3899): Starting up...
,I/ActivityManager(  825): Killing 3214:android.process.acore/u0a5 (adj 15): empty #17
,I/dhcpcd  ( 3956): version 5.5.6 starting
,I/dhcpcd  ( 3956): wlan0: rebinding lease of 192.168.1.122
,I/ActivityManager(  825): Start proc 3963:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,I/GLSUser ( 1276): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1276): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1276): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1276): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1276): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2873): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 2873): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 2873): [1] 5.onFinished: Scheduling replication attempt 3.
,V/MusicLeanback( 3818): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/ActivityManager(  825): Killing 3572:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,D/SprintDMReceiver( 3879): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3879): simOperator:  IMSI: null
D/SprintDMReceiver( 3879): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1816): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1816): onCreate
,D/SystemUpdateService( 1816): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1816): active receiver: enabled
,I/SystemUpdateService( 1816): showing system update notification
,D/ChimeraCfgMgr( 1816): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/ValidateNoPeople(  825): skipping global notification
,V/SystemUpdateService( 1816): retry (wakeup: false) in 3599931 ms
,D/SystemUpdateService( 1816): onDestroy
,I/dhcpcd  ( 3956): wlan0: acknowledged 192.168.1.122 from 192.168.1.1
,I/dhcpcd  ( 3956): wlan0: leased 192.168.1.122 for 86400 seconds
,D/ConnectivityService(  825): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  825): Adding iface wlan0 to network 101,
,E/WifiStateMachine(  825): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  825): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  825): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  825): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101,
D/ConnectivityService(  825): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  825): Setting Dns servers for network 101 to [/192.168.1.1]
,D/ConnectivityService(  825): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  825): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  825): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  825): Connected
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  825): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  825): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
D/ConnectivityService(  825): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  825):    accepting network in place of null
,D/ConnectivityService(  825): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} }
,D/ConnectivityService(  825): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/CSLegacyTypeTracker(  825): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  825): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 1059): CM callback handler got msg 524290
D/ConnectivityService(  825): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  825): MasterInitialState.processMessage what=3
,D/PhoneInterfaceManager( 1353): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
,E/PhoneInterfaceManager( 1353): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  825): getDataEnabled: retVal=false
,I/NetworkMonitor( 3818): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 3818): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,E/GpsLocationProvider(  825): No APN found to select.
,D/SprintDMReceiver( 3879): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3879): simOperator:  IMSI: null
D/SprintDMReceiver( 3879): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1816): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1816): onCreate
,D/SystemUpdateService( 1816): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1816): active receiver: enabled
,I/SystemUpdateService( 1816): showing system update notification
,I/iu.Environment( 1816): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1816): num queued entries: 0
,I/iu.UploadsManager( 1816): num updated entries: 0
,I/iu.SyncManager( 1816): NEXT; no task
,D/ChimeraCfgMgr( 1816): Loading module com.google.android.gms.kids from APK com.google.android.gms
I/ValidateNoPeople(  825): skipping global notification
,V/SystemUpdateService( 1816): retry (wakeup: false) in 3599976 ms
,D/ChimeraCfgMgr( 1816): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/SystemUpdateService( 1816): onDestroy
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  825): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 10 Dec 2015 14:12:09 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1449756729228], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1449756729203]}
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  825): Validated
D/ConnectivityService(  825): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/ConnectivityService(  825): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  825): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  825): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  825): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  825): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1059): CM callback handler got msg 524290
,I/GLSUser ( 1276): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1276): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1276): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1276): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1276): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/Herrevad( 1816): NQAS connected
,I/Babel   ( 2797): connection state changed from DISCONNECTED to CONNECTED
,W/Kids    ( 1816): [AccountUtils] Account not ready
W/Kids    ( 1816): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 1816): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 1816): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 1816): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 1816): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 1816): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 1816): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 1816): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 1816): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 1816): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 1816): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 1816): 	at java.lang.Thread.run(Thread.java:818)
,D/GCM     ( 1276): Connected
,D/GCM     ( 1276): Message class com.google.f.a.a.p
,I/jxcore-log( 3759): BLE supported!!,
I/jxcore-log( 3759): 
,D/ConnectivityService(  825): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,D/WearableService( 3392): callingUid 10011, callindPid: 3392
,I/MusicLeanback( 3818): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 3818): Stop autocaching.
,I/art     (  825): Explicit concurrent mark sweep GC freed 39020(1841KB) AllocSpace objects, 6(190KB) LOS objects, 32% free, 33MB/49MB, paused 2.044ms total 70.468ms
,E/GmsUtils( 3818): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 3818): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/WifiStateMachine(  825): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=9.25 rxSuccessRate=10.94 targetRoamBSSID=any RSSI=-52
E/WifiStateMachine(  825): WifiStateMachine L2Connected CMD_START_SCAN source -2 10, 11 -> obsolete
,E/WifiStateMachine(  825): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=3.31 rxSuccessRate=4.73 targetRoamBSSID=any RSSI=-52
E/WifiStateMachine(  825): WifiStateMachine L2Connected CMD_START_SCAN source -2 9, 11 -> obsolete
,I/PowerManagerService(  825): Going to sleep due to screen timeout (uid 1000)...
,I/Adreno  (  825): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/PermissionCache(  260): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (238 us)
,I/DisplayManagerService(  825): Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
D/SurfaceFlinger(  260): Set power mode=0, type=0 flinger=0xb6482000
D/qdhwcomposer(  260): hwc_setPowerMode: Setting mode 0 on display: 0
V/ActivityManager(  825): Display changed displayId=0,
,I/qdhwcomposer(  260): handle_blank_event: dpy:0 panel power state: 0
,D/qdhwcomposer(  260): hwc_setPowerMode: Done setting mode 0 on display 0
,D/SurfaceControl(  825): Excessive delay in setPowerMode(): 273ms
,I/DreamManagerService(  825): Entering dreamland.
,I/PowerManagerService(  825): Dozing...
,I/DreamController(  825): Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,D/audio_hw_primary(  359): adev_set_parameters: enter: screen_state=on
,D/mot_vr_audio_hw(  359): adev_set_parameters: screen_state=on,
,E/WifiStateMachine(  825): cancelDelayedScan -> 12
,E/native  (  825): do suspend false
,I/Keyboard.Facilitator( 1247): onFinishInput()
,E/WifiStateMachine(  825): cancelDelayedScan -> 14
,E/native  (  825): do suspend true
,D/audio_hw_primary(  359): adev_set_parameters: enter: screen_state=off
,D/mot_vr_audio_hw(  359): adev_set_parameters: screen_state=off
,E/WifiStateMachine(  825): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-52
,E/WifiStateMachine(  825): WifiStateMachine L2Connected CMD_START_SCAN source -2 13, 14 -> obsolete
,V/KeepSync( 3667): Connecting to GoogleApiClient
,I/GLSUser ( 1276): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1276): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1276): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1276): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,V/GLSActivity( 1276): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1816): Handling authorization failure
E/ClientConnectionOperation( 1816): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1816): 	,at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1816): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1816): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1816): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1816): ,	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1816): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1816): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1816): ,	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1816): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1816): 	at com.google.android.gms.auth.p.b(SourceFile:442)
,E/ClientConnectionOperation( 1816): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1816): 	at com.google.android.gms.auth.p.a(SourceFile:310),
E/ClientConnectionOperation( 1816): 	,at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1816): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
,E/ClientConnectionOperation( 1816): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1816): ,	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1816): 	at com.google.android.gms.common.server.o.a(SourceFile:340),
E/ClientConnectionOperation( 1816): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1816): ,	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1816): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1816): 	... 7 more
V/KeepSync( 3667): GoogleApiClient failed to connect with error code: 4
E/SQLiteLog( 3667): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3667): (284) automatic index on blob_node(is_deleted),
E/SQLiteLog( 3667): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1276): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1276): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1276): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1276): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1276): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3667): IOException
E/KeepSync( 3667): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3667): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3667): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3667): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3667): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3667): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3667): 	,at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3667): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3667): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3667): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3667): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3667): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3667): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3667): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3667): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3667): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3667): 	... 10 more
W/KeepSync( 3667): Sync result 2
D/SyncManager(  825): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 164438, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1276): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1276): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1276): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1276): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1276): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2873): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 2873): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 2873): [1] 5.onFinished: Scheduling replication attempt 4.
,E/WifiStateMachine(  825): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-52
E/WifiStateMachine(  825): WifiStateMachine L2Connected CMD_START_SCAN source -2 11, 14 -> obsolete
,D/HeadsetStateMachine( 2193): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2193): Disconnected process message: 10, size: 0
,I/VacuumService( 1276): Vacuum at: now=1449756767320 tag=VacuumService
,V/GoogleAuthProtoRequest( 3851): [415] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1276): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1276): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1276): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1276): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1276): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3851): [415] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3851): [415] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3851): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3851): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3851): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3851): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3851): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3851): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3851): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3851): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3851): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3851): 	at com.a.a.k.run(SourceFile:110)
,I/GoogleURLConnFactory( 1276): Using platform SSLCertificateSocketFactory
,W/Uploader( 1276): No account for auth token provided
,W/Uploader( 1276): No account for auth token provided
,I/GLSUser ( 1276): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1276): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1276): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1276): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1276): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1276): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1276): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1276): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1276): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1276): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1276): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1276): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1276): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1276): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1276): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1276): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1276): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1276): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/GLSUser ( 1276): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1276): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1276): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1276): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1276): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1276): Explicit concurrent mark sweep GC freed 40963(2MB) AllocSpace objects, 8(689KB) LOS objects, 37% free, 26MB/42MB, paused 1.376ms total 59.710ms
,E/Uploader( 1276): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1276): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1276): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1276): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1276): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1276): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1276): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1276): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1276): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1276): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1276): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1276): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1276): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/GLSUser ( 1276): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure,
I/GLSUser ( 1276): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1276): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1276): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1276): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/Uploader( 1276): No account for auth token provided
,D/Finsky  ( 2873): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 2873): [1] 5.onFinished: Installation state replication failed.,
D/Finsky  ( 2873): [1] 5.onFinished: Scheduling replication attempt 5.
,W/Uploader( 1276): No account for auth token provided
,W/Uploader( 1276): No account for auth token provided,
,I/GLSUser ( 1276): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1276): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1276): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1276): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1276): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1276): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1276): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1276): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1276): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1276): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1276): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1276): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1276): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1276): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1276): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1276): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1276): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1276): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1276): No account for auth token provided
,W/Uploader( 1276): No account for auth token provided
,W/Uploader( 1276): No account for auth token provided
,W/Uploader( 1276): No account for auth token provided
,W/Uploader( 1276): No account for auth token provided
,W/Uploader( 1276):  no longer exists, so no auth token.,
,I/GLSUser ( 1276): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1276): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1276): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1276): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1276): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1276): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1276): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1276): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1276): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1276): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1276): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1276): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1276): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1276): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1276): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1276): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1276): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1276): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/GLSUser ( 1276): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1276): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1276): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1276): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1276): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  825): Explicit concurrent mark sweep GC freed 36514(1672KB) AllocSpace objects, 2(126KB) LOS objects, 31% free, 34MB/50MB, paused 1.520ms total 91.649ms
,E/Uploader( 1276): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1276): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1276): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1276): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1276): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1276): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1276): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1276): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1276): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1276): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1276): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1276): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1276): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/BooksSync( 3698): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3698): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1276): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1276): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1276): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1276): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1276): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1276): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
V/GLSActivity( 1276): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 1276): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1276): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1276): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3194): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3194): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3194): 	at jdm.a(PG:82)
E/HttpOperation( 3194): 	at jcs.o(PG:406)
E/HttpOperation( 3194): 	at jcn.a(PG:1379)
E/HttpOperation( 3194): 	at jcs.i(PG:143)
E/HttpOperation( 3194): 	at blb.a(PG:3937)
E/HttpOperation( 3194): 	at czp.a(PG:18188)
E/HttpOperation( 3194): 	at czp.a(PG:9081)
E/HttpOperation( 3194): 	at czq.run(PG:1686)
E/HttpOperation( 3194): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3194): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3194): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3194): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3194): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3194): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3194): 	at jdj.a(PG:4091)
E/HttpOperation( 3194): 	at jdj.a(PG:1125)
E/HttpOperation( 3194): 	at jdm.a(PG:77)
E/HttpOperation( 3194): 	... 12 more
E/HttpOperation( 3194): Caused by: faj: BadAuthentication
E/HttpOperation( 3194): 	at fal.a(PG:38)
E/HttpOperation( 3194): 	at jdj.a(PG:4089)
E/HttpOperation( 3194): 	... 14 more
,I/GLSUser ( 1276): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1276): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1276): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1276): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1276): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3194): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3194): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3194): 	at jdm.a(PG:82)
E/HttpOperation( 3194): 	at jcs.o(PG:406)
E/HttpOperation( 3194): 	at jcn.a(PG:1379)
E/HttpOperation( 3194): 	at jcs.i(PG:143)
E/HttpOperation( 3194): 	at hec.a(PG:42)
E/HttpOperation( 3194): 	at hee.a(PG:102)
E/HttpOperation( 3194): 	at czr.a(PG:65)
E/HttpOperation( 3194): 	at kka.a(PG:108)
E/HttpOperation( 3194): 	at czp.a(PG:19176)
E/HttpOperation( 3194): 	at czp.a(PG:9081)
E/HttpOperation( 3194): 	at czq.run(PG:1686)
E/HttpOperation( 3194): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3194): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3194): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3194): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3194): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3194): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3194): 	at jdj.a(PG:4091)
E/HttpOperation( 3194): 	at jdj.a(PG:1125)
E/HttpOperation( 3194): 	at jdm.a(PG:77)
E/HttpOperation( 3194): 	... 15 more
E/HttpOperation( 3194): Caused by: faj: BadAuthentication
E/HttpOperation( 3194): 	at fal.a(PG:38)
E/HttpOperation( 3194): 	at jdj.a(PG:4089)
E/HttpOperation( 3194): 	... 17 more
E/ExperimentLoader( 3194): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3194): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3194): 	at jdm.a(PG:82)
E/ExperimentLoader( 3194): 	at jcs.o(PG:406)
E/ExperimentLoader( 3194): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3194): 	at jcs.i(PG:143)
E/ExperimentLoader( 3194): 	at hec.a(PG:42)
E/ExperimentLoader( 3194): 	at hee.a(PG:102)
E/ExperimentLoader( 3194): 	at czr.a(PG:65)
E/ExperimentLoader( 3194): 	at kka.a(PG:108)
E/ExperimentLoader( 3194): 	at czp.a(PG:19176)
E/ExperimentLoader( 3194): 	at czp.a(PG:9081)
E/ExperimentLoader( 3194): 	at czq.run(PG:1686)
E/ExperimentLoader( 3194): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3194): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3194): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3194): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3194): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3194): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3194): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3194): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3194): 	at jdm.a(PG:77)
E/ExperimentLoader( 3194): 	... 15 more
E/ExperimentLoader( 3194): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3194): 	at fal.a(PG:38)
E/ExperimentLoader( 3194): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3194): 	... 17 more
,I/GLSUser ( 1276): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1276): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1276): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1276): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1276): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3698): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3698): Soft error
E/BooksSync( 3698): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3698): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3698): Sync error
E/BooksSync( 3698): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3698): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3698): Finished books sync
,D/SyncManager(  825): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 168344, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1],
,D/SyncManager(  825): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 166204, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,V/GoogleAuthProtoRequest( 3851): [416] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1276): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1276): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1276): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1276): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1276): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3851): [416] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3851): [416] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3851): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3851): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3851): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3851): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3851): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3851): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3851): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3851): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3851): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3851): 	at com.a.a.k.run(SourceFile:110)
,I/GLSUser ( 1276): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1276): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1276): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1276): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1276): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2873): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 2873): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 2873): [1] 5.onFinished: Giving up after 6 failures.
,I/Keyboard.Facilitator.LanguageModelFlusher( 1247): run()
I/Keyboard.Facilitator( 1247): flushDynamicLanguageModels()
,I/ConfigService( 1276): onCreate
,V/KeepSync( 3667): Connecting to GoogleApiClient
,I/GLSUser ( 1276): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1276): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1276): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1276): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1276): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1816): Handling authorization failure
E/ClientConnectionOperation( 1816): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1816): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1816): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1816): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1816): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
,E/ClientConnectionOperation( 1816): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1816): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1816): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1816): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1816): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1816): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1816): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1816): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1816): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1816): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1816): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1816): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1816): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1816): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1816): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1816): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1816): 	... 7 more,
V/KeepSync( 3667): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3667): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3667): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3667): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1276): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1276): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1276): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1276): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1276): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3667): IOException
E/KeepSync( 3667): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3667): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3667): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3667): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3667): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3667): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3667): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3667): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3667): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3667): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3667): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3667): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3667): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3667): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3667): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3667): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3667): 	... 10 more
W/KeepSync( 3667): Sync result 2
,D/SyncManager(  825): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 196656, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,I/ConfigService( 1276): onDestroy
,D/HeadsetStateMachine( 2193): Disconnected process message: 10, size: 0
,I/BooksSync( 3698): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3698): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1276): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1276): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1276): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1276): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1276): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1276): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1276): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1276): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1276): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1276): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1276): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1276): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1276): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1276): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1276): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3194): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3194): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3194): 	at jdm.a(PG:82)
E/HttpOperation( 3194): 	at jcs.o(PG:406)
E/HttpOperation( 3194): 	at jcn.a(PG:1379)
E/HttpOperation( 3194): 	at jcs.i(PG:143)
E/HttpOperation( 3194): 	at blb.a(PG:3937)
E/HttpOperation( 3194): 	at czp.a(PG:18188)
E/HttpOperation( 3194): 	at czp.a(PG:9081)
E/HttpOperation( 3194): 	at czq.run(PG:1686)
E/HttpOperation( 3194): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3194): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3194): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3194): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3194): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3194): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3194): 	at jdj.a(PG:4091)
E/HttpOperation( 3194): 	at jdj.a(PG:1125)
E/HttpOperation( 3194): 	at jdm.a(PG:77)
E/HttpOperation( 3194): 	... 12 more
E/HttpOperation( 3194): Caused by: faj: BadAuthentication
E/HttpOperation( 3194): 	at fal.a(PG:38)
E/HttpOperation( 3194): 	at jdj.a(PG:4089)
E/HttpOperation( 3194): 	,... 14 more
,E/BooksAccountManager( 3698): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3698): Soft error
E/BooksSync( 3698): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3698): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3698): Sync error
E/BooksSync( 3698): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3698): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3698): Finished books sync
,D/SyncManager(  825): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 227191, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1276): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1276): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1276): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1276): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1276): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/HttpOperation( 3194): [getmobileexperiments] Unexpected exception,
E/HttpOperation( 3194): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3194): 	at jdm.a(PG:82)
E/HttpOperation( 3194): 	at jcs.o(PG:406)
E/HttpOperation( 3194): 	at jcn.a(PG:1379)
E/HttpOperation( 3194): 	at jcs.i(PG:143)
E/HttpOperation( 3194): 	at hec.a(PG:42)
E/HttpOperation( 3194): 	at hee.a(PG:102)
E/HttpOperation( 3194): 	at czr.a(PG:65)
E/HttpOperation( 3194): 	at kka.a(PG:108)
,E/HttpOperation( 3194): 	at czp.a(PG:19176)
E/HttpOperation( 3194): 	at czp.a(PG:9081)
E/HttpOperation( 3194): 	at czq.run(PG:1686)
E/HttpOperation( 3194): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3194): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3194): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3194): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3194): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3194): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3194): 	at jdj.a(PG:4091)
,E/HttpOperation( 3194): 	at jdj.a(PG:1125)
E/HttpOperation( 3194): 	at jdm.a(PG:77)
E/HttpOperation( 3194): 	... 15 more
E/HttpOperation( 3194): Caused by: faj: BadAuthentication
E/HttpOperation( 3194): 	at fal.a(PG:38)
E/HttpOperation( 3194): 	at jdj.a(PG:4089)
E/HttpOperation( 3194): 	... 17 more
E/ExperimentLoader( 3194): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
,E/ExperimentLoader( 3194): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3194): 	at jdm.a(PG:82)
E/ExperimentLoader( 3194): 	at jcs.o(PG:406)
E/ExperimentLoader( 3194): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3194): 	at jcs.i(PG:143)
E/ExperimentLoader( 3194): 	at hec.a(PG:42)
E/ExperimentLoader( 3194): 	at hee.a(PG:102)
E/ExperimentLoader( 3194): 	at czr.a(PG:65)
E/ExperimentLoader( 3194): 	at kka.a(PG:108)
E/ExperimentLoader( 3194): ,	at czp.a(PG:19176)
E/ExperimentLoader( 3194): 	at czp.a(PG:9081)
E/ExperimentLoader( 3194): 	at czq.run(PG:1686)
E/ExperimentLoader( 3194): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3194): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3194): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
,E/ExperimentLoader( 3194): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3194): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3194): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3194): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3194): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3194): 	at jdm.a(PG:77)
E/ExperimentLoader( 3194): 	... 15 more
E/ExperimentLoader( 3194): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3194): 	at fal.a(PG:38)
E/ExperimentLoader( 3194): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3194): 	... 17 more
,D/SyncManager(  825): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 225257, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/jxcore-log( 3759): Connected to the server!
I/jxcore-log( 3759): 
,I/chromium( 3759): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,D/HeadsetStateMachine( 2193): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2193): Disconnected process message: 10, size: 0,
,I/art     (  825): Explicit concurrent mark sweep GC freed 34149(1479KB) AllocSpace objects, 11(647KB) LOS objects, 31% free, 34MB/50MB, paused 1.598ms total 82.578ms
,V/GoogleAuthProtoRequest( 3851): [417] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1276): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1276): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1276): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1276): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1276): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1276): Explicit concurrent mark sweep GC freed 58651(3MB) AllocSpace objects, 9(909KB) LOS objects, 36% free, 27MB/43MB, paused 1.188ms total 40.525ms
,W/ExperimentUpdateService( 3851): [417] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3851): [417] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3851): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3851): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3851): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3851): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3851): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3851): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3851): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3851): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3851): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3851): 	at com.a.a.k.run(SourceFile:110)
,V/KeepSync( 3667): Connecting to GoogleApiClient
,I/GLSUser ( 1276): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1276): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1276): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1276): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1276): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1816): Handling authorization failure
E/ClientConnectionOperation( 1816): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1816): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1816): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1816): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1816): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1816): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1816): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1816): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1816): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1816): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1816): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1816): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1816): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1816): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1816): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1816): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1816): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1816): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1816): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1816): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1816): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1816): 	... 7 more
,V/KeepSync( 3667): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3667): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3667): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3667): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1276): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1276): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1276): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1276): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1276): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3667): IOException
E/KeepSync( 3667): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3667): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3667): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3667): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3667): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3667): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3667): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3667): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3667): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3667): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3667): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3667): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3667): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3667): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3667): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3667): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3667): 	... 10 more
W/KeepSync( 3667): Sync result 2
,D/SyncManager(  825): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 288532, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager(  825): Start proc 4124:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider
,I/GAv4    ( 4124): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4124):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4124):   adb logcat -s GAv4
,W/GAv4    ( 4124): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4124): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4124): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  825): Killing 3593:com.android.musicfx/u0a18 (adj 15): empty #17
,I/BooksSync( 3698): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3698): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1276): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1276): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1276): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1276): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1276): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3194): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3194): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3194): 	at jdm.a(PG:82)
E/HttpOperation( 3194): 	at jcs.o(PG:406)
E/HttpOperation( 3194): 	at jcn.a(PG:1379)
E/HttpOperation( 3194): 	at jcs.i(PG:143)
E/HttpOperation( 3194): 	at blb.a(PG:3937)
E/HttpOperation( 3194): 	at czp.a(PG:18188)
E/HttpOperation( 3194): 	at czp.a(PG:9081)
E/HttpOperation( 3194): 	at czq.run(PG:1686)
E/HttpOperation( 3194): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3194): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3194): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3194): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3194): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3194): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3194): 	at jdj.a(PG:4091)
E/HttpOperation( 3194): 	at jdj.a(PG:1125)
E/HttpOperation( 3194): 	at jdm.a(PG:77)
E/HttpOperation( 3194): 	... 12 more
E/HttpOperation( 3194): Caused by: faj: BadAuthentication
E/HttpOperation( 3194): 	at fal.a(PG:38)
E/HttpOperation( 3194): 	at jdj.a(PG:4089)
E/HttpOperation( 3194): 	... 14 more
,I/GLSUser ( 1276): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1276): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1276): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1276): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1276): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1276): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1276): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1276): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1276): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1276): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3194): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3194): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3194): 	at jdm.a(PG:82)
E/HttpOperation( 3194): 	at jcs.o(PG:406)
E/HttpOperation( 3194): 	at jcn.a(PG:1379)
E/HttpOperation( 3194): 	at jcs.i(PG:143)
E/HttpOperation( 3194): 	at hec.a(PG:42)
E/HttpOperation( 3194): 	at hee.a(PG:102)
E/HttpOperation( 3194): 	at czr.a(PG:65)
E/HttpOperation( 3194): 	at kka.a(PG:108)
E/HttpOperation( 3194): 	at czp.a(PG:19176)
E/HttpOperation( 3194): 	at czp.a(PG:9081)
E/HttpOperation( 3194): 	at czq.run(PG:1686)
E/HttpOperation( 3194): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3194): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3194): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3194): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3194): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3194): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3194): 	at jdj.a(PG:4091)
E/HttpOperation( 3194): 	at jdj.a(PG:1125)
E/HttpOperation( 3194): 	at jdm.a(PG:77)
E/HttpOperation( 3194): 	... 15 more
E/HttpOperation( 3194): Caused by: faj: BadAuthentication
E/HttpOperation( 3194): 	at fal.a(PG:38)
E/HttpOperation( 3194): 	at jdj.a(PG:4089)
E/HttpOperation( 3194): 	... 17 more
E/ExperimentLoader( 3194): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3194): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3194): 	at jdm.a(PG:82)
E/ExperimentLoader( 3194): 	at jcs.o(PG:406)
E/ExperimentLoader( 3194): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3194): 	at jcs.i(PG:143)
E/ExperimentLoader( 3194): 	at hec.a(PG:42)
E/ExperimentLoader( 3194): 	at hee.a(PG:102)
E/ExperimentLoader( 3194): 	at czr.a(PG:65)
E/ExperimentLoader( 3194): 	at kka.a(PG:108)
E/ExperimentLoader( 3194): 	at czp.a(PG:19176)
E/ExperimentLoader( 3194): 	at czp.a(PG:9081)
E/ExperimentLoader( 3194): 	at czq.run(PG:1686)
E/ExperimentLoader( 3194): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3194): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3194): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3194): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3194): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3194): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3194): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3194): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3194): 	at jdm.a(PG:77)
E/ExperimentLoader( 3194): 	... 15 more
E/ExperimentLoader( 3194): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3194): 	at fal.a(PG:38)
E/ExperimentLoader( 3194): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3194): 	... 17 more
,I/GLSUser ( 1276): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1276): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1276): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1276): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1276): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3698): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3698): Soft error
E/BooksSync( 3698): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3698): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3698): Sync error
E/BooksSync( 3698): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3698): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3698): Finished books sync
,D/SyncManager(  825): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 319502, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/SyncManager(  825): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 315652, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,D/WifiService(  825): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@26edb2a}
,E/WifiStateMachine(  825): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-52
,D/WifiService(  825): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@26edb2a}
,E/LocSvc_IzatApiV02(  825): E/virtual int izat_core::IzatApiV02::injectLocation(GpsExtLocation):857]: error! inject position failed
,I/GLSUser ( 1276): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1276): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1276): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1276): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1276): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1276): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1276): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1276): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1276): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1276): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1276): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1276): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 2873): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 2873): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 2873): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 2873): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 2873): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/PlayEventLogger( 2873): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 2873): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 2873): Ignoring header User-Agent because its value was null.
,E/PlayEventLogger( 2873): Status 503 without retry-after header
,D/HeadsetStateMachine( 2193): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2193): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2193): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2193): Disconnected process message: 10, size: 0,
,I/ActivityManager(  825): Start proc 4176:com.google.android.youtube/u0a86 for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator
,V/GoogleAuthProtoRequest( 3851): [418] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1276): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1276): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1276): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1276): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1276): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 4176): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 4176): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/art     (  825): Explicit concurrent mark sweep GC freed 30974(1404KB) AllocSpace objects, 12(569KB) LOS objects, 31% free, 34MB/50MB, paused 1.677ms total 55.265ms
V/JNIHelp ( 4176): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/ExperimentUpdateService( 3851): [418] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3851): [418] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3851): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3851): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3851): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3851): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3851): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3851): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3851): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3851): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3851): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3851): 	at com.a.a.k.run(SourceFile:110)
,I/ProviderInstaller( 4176): Installed default security provider GmsCore_OpenSSL
,E/YouTube MDX( 4176): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,I/dex2oat ( 4206): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads517274738.jar --oat-fd=24 --oat-location=/data/data/com.google.android.youtube/cache/ads517274738.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 4206): dex2oat took 35.733ms (threads: 4) arena alloc=114KB java alloc=12KB native alloc=1221KB free=6MB
,W/InstanceID/Rpc( 4176): Found 10011
,I/ActivityManager(  825): Killing 3621:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,V/KeepSync( 3667): Connecting to GoogleApiClient
,I/GLSUser ( 1276): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1276): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1276): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1276): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1276): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1816): Handling authorization failure
E/ClientConnectionOperation( 1816): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1816): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1816): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1816): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1816): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1816): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1816): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1816): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1816): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1816): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1816): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1816): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1816): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1816): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1816): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1816): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1816): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1816): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1816): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1816): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1816): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1816): 	... 7 more
,V/KeepSync( 3667): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3667): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3667): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3667): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1276): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1276): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1276): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1276): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1276): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3667): IOException
E/KeepSync( 3667): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3667): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3667): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3667): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3667): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3667): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3667): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3667): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3667): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3667): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3667): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3667): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3667): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3667): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3667): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3667): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3667): 	... 10 more
W/KeepSync( 3667): Sync result 2
,D/SyncManager(  825): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 442191, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1276): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1276): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1276): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1276): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1276): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3194): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3194): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3194): 	at jdm.a(PG:82)
E/HttpOperation( 3194): 	at jcs.o(PG:406)
E/HttpOperation( 3194): 	at jcn.a(PG:1379)
E/HttpOperation( 3194): 	at jcs.i(PG:143)
E/HttpOperation( 3194): 	at blb.a(PG:3937)
E/HttpOperation( 3194): 	at czp.a(PG:18188)
E/HttpOperation( 3194): 	at czp.a(PG:9081)
E/HttpOperation( 3194): 	at czq.run(PG:1686)
E/HttpOperation( 3194): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3194): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3194): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3194): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3194): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3194): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3194): 	at jdj.a(PG:4091)
E/HttpOperation( 3194): 	at jdj.a(PG:1125)
E/HttpOperation( 3194): 	at jdm.a(PG:77)
E/HttpOperation( 3194): 	... 12 more
E/HttpOperation( 3194): Caused by: faj: BadAuthentication
E/HttpOperation( 3194): 	at fal.a(PG:38)
E/HttpOperation( 3194): 	at jdj.a(PG:4089)
E/HttpOperation( 3194): 	... 14 more
,I/GLSUser ( 1276): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1276): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1276): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1276): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1276): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3194): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3194): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3194): 	at jdm.a(PG:82)
E/HttpOperation( 3194): 	at jcs.o(PG:406)
E/HttpOperation( 3194): 	at jcn.a(PG:1379)
E/HttpOperation( 3194): 	at jcs.i(PG:143)
E/HttpOperation( 3194): 	at hec.a(PG:42)
E/HttpOperation( 3194): 	at hee.a(PG:102)
E/HttpOperation( 3194): 	at czr.a(PG:65)
E/HttpOperation( 3194): 	at kka.a(PG:108)
E/HttpOperation( 3194): 	at czp.a(PG:19176)
E/HttpOperation( 3194): 	at czp.a(PG:9081)
E/HttpOperation( 3194): 	at czq.run(PG:1686)
E/HttpOperation( 3194): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3194): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3194): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3194): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3194): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3194): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3194): 	at jdj.a(PG:4091)
E/HttpOperation( 3194): 	at jdj.a(PG:1125)
E/HttpOperation( 3194): 	at jdm.a(PG:77)
E/HttpOperation( 3194): 	... 15 more
E/HttpOperation( 3194): Caused by: faj: BadAuthentication
E/HttpOperation( 3194): 	at fal.a(PG:38)
E/HttpOperation( 3194): 	at jdj.a(PG:4089)
E/HttpOperation( 3194): 	... 17 more
,E/ExperimentLoader( 3194): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
,E/ExperimentLoader( 3194): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3194): 	at jdm.a(PG:82)
E/ExperimentLoader( 3194): 	at jcs.o(PG:406)
E/ExperimentLoader( 3194): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3194): 	at jcs.i(PG:143)
E/ExperimentLoader( 3194): 	at hec.a(PG:42)
E/ExperimentLoader( 3194): 	at hee.a(PG:102)
E/ExperimentLoader( 3194): 	at czr.a(PG:65)
E/ExperimentLoader( 3194): 	at kka.a(PG:108)
E/ExperimentLoader( 3194): 	at czp.a(PG:19176)
E/ExperimentLoader( 3194): 	at czp.a(PG:9081)
E/ExperimentLoader( 3194): 	at czq.run(PG:1686)
E/ExperimentLoader( 3194): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3194): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3194): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
,E/ExperimentLoader( 3194): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3194): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3194): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3194): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3194): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3194): 	at jdm.a(PG:77)
E/ExperimentLoader( 3194): 	... 15 more
E/ExperimentLoader( 3194): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3194): 	at fal.a(PG:38)
E/ExperimentLoader( 3194): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3194): 	... 17 more
,D/SyncManager(  825): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 466492, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2193): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2193): Disconnected process message: 10, size: 0
,I/BooksSync( 3698): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3698): GmsCore Version = 7.8.99 (2134222-430)
,I/art     ( 1276): Explicit concurrent mark sweep GC freed 49367(2MB) AllocSpace objects, 17(1874KB) LOS objects, 36% free, 27MB/43MB, paused 1.579ms total 40.637ms
,I/GLSUser ( 1276): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1276): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1276): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1276): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1276): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1276): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1276): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1276): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1276): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1276): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3698): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3698): Soft error
E/BooksSync( 3698): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3698): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3698): Sync error
E/BooksSync( 3698): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3698): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3698): Finished books sync
,D/SyncManager(  825): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 474417, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2193): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2193): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2193): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2193): Disconnected process message: 10, size: 0
,V/KeepSync( 3667): Connecting to GoogleApiClient
,I/GLSUser ( 1276): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1276): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1276): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1276): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1276): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1816): Handling authorization failure
E/ClientConnectionOperation( 1816): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1816): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1816): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1816): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1816): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1816): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1816): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1816): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1816): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1816): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1816): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1816): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1816): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1816): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1816): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1816): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1816): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1816): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1816): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1816): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1816): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1816): 	... 7 more
,V/KeepSync( 3667): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3667): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3667): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3667): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1276): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1276): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1276): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1276): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1276): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3667): IOException
E/KeepSync( 3667): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3667): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3667): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3667): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3667): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3667): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3667): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3667): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3667): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3667): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3667): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3667): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3667): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3667): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3667): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3667): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3667): 	... 10 more
,W/KeepSync( 3667): Sync result 2
,D/SyncManager(  825): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 696790, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,D/Finsky  ( 2873): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,I/art     (  825): Explicit concurrent mark sweep GC freed 37367(1626KB) AllocSpace objects, 7(394KB) LOS objects, 31% free, 34MB/50MB, paused 1.388ms total 68.664ms
,V/GoogleAuthProtoRequest( 3851): [419] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1276): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1276): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1276): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1276): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1276): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1276): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1276): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1276): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1276): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1276): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 2873): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,W/ExperimentUpdateService( 3851): [419] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3851): [419] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3851): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3851): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3851): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3851): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3851): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3851): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3851): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3851): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3851): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3851): 	at com.a.a.k.run(SourceFile:110)
,I/GLSUser ( 1276): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1276): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1276): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1276): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1276): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1276): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1276): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1276): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1276): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1276): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 2873): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/GLSUser ( 1276): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1276): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1276): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1276): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1276): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 2873): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 2873): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 2873): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 2873): [1] DailyHygiene.reschedule: Scheduling new run in 28 minutes (failures=2),
,D/DeviceConnectionService( 1841): client connected with version: 7571000
,I/GLSUser ( 1276): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1276): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1276): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1276): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1276): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2873): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 2873): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 2873): [1] 5.onFinished: Scheduling replication attempt 1.
,D/HeadsetStateMachine( 2193): Disconnected process message: 10, size: 0
,I/GLSUser ( 1276): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1276): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1276): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1276): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1276): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3194): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3194): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3194): ,	at jdm.a(PG:82)
E/HttpOperation( 3194): 	at jcs.o(PG:406)
E/HttpOperation( 3194): 	at jcn.a(PG:1379)
E/HttpOperation( 3194): 	at jcs.i(PG:143)
E/HttpOperation( 3194): 	at blb.a(PG:3937)
E/HttpOperation( 3194): 	at czp.a(PG:18188)
E/HttpOperation( 3194): 	at czp.a(PG:9081)
E/HttpOperation( 3194): 	at czq.run(PG:1686)
E/HttpOperation( 3194): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3194): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3194): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3194): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3194): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3194): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3194): 	at jdj.a(PG:4091)
E/HttpOperation( 3194): 	at jdj.a(PG:1125)
E/HttpOperation( 3194): 	at jdm.a(PG:77)
E/HttpOperation( 3194): 	... 12 more
E/HttpOperation( 3194): Caused by: faj: BadAuthentication
E/HttpOperation( 3194): 	at fal.a(PG:38)
E/HttpOperation( 3194): 	at jdj.a(PG:4089)
E/HttpOperation( 3194): 	... 14 more
,I/GLSUser ( 1276): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1276): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1276): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1276): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1276): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3194): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3194): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3194): 	at jdm.a(PG:82)
E/HttpOperation( 3194): 	at jcs.o(PG:406)
E/HttpOperation( 3194): 	at jcn.a(PG:1379)
E/HttpOperation( 3194): 	at jcs.i(PG:143)
E/HttpOperation( 3194): 	at hec.a(PG:42)
E/HttpOperation( 3194): 	at hee.a(PG:102)
E/HttpOperation( 3194): 	at czr.a(PG:65)
E/HttpOperation( 3194): 	at kka.a(PG:108)
E/HttpOperation( 3194): 	at czp.a(PG:19176)
E/HttpOperation( 3194): 	at czp.a(PG:9081)
E/HttpOperation( 3194): 	at czq.run(PG:1686)
E/HttpOperation( 3194): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3194): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3194): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3194): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3194): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3194): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3194): 	at jdj.a(PG:4091)
E/HttpOperation( 3194): 	at jdj.a(PG:1125)
E/HttpOperation( 3194): 	at jdm.a(PG:77)
E/HttpOperation( 3194): 	... 15 more
E/HttpOperation( 3194): Caused by: faj: BadAuthentication
E/HttpOperation( 3194): 	at fal.a(PG:38)
E/HttpOperation( 3194): 	at jdj.a(PG:4089)
E/HttpOperation( 3194): 	... 17 more
E/ExperimentLoader( 3194): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3194): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3194): 	at jdm.a(PG:82)
E/ExperimentLoader( 3194): 	at jcs.o(PG:406)
E/ExperimentLoader( 3194): 	at jcn.a(PG:1379),
E/ExperimentLoader( 3194): 	at jcs.i(PG:143)
E/ExperimentLoader( 3194): 	at hec.a(PG:42)
E/ExperimentLoader( 3194): 	at hee.a(PG:102)
E/ExperimentLoader( 3194): 	at czr.a(PG:65)
E/ExperimentLoader( 3194): 	at kka.a(PG:108)
E/ExperimentLoader( 3194): 	at czp.a(PG:19176)
E/ExperimentLoader( 3194): 	at czp.a(PG:9081)
E/ExperimentLoader( 3194): 	at czq.run(PG:1686)
E/ExperimentLoader( 3194): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3194): 	,at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3194): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3194): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3194): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3194): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3194): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3194): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3194): 	at jdm.a(PG:77)
E/ExperimentLoader( 3194): 	... 15 more
E/ExperimentLoader( 3194): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3194): 	at fal.a(PG:38)
E/ExperimentLoader( 3194): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3194): 	... 17 more
,D/SyncManager(  825): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 715225, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2193): Disconnected process message: 10, size: 0
,I/GLSUser ( 1276): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1276): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1276): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1276): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1276): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/Finsky  ( 2873): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 2873): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 2873): [1] 5.onFinished: Scheduling replication attempt 2.
,I/GLSUser ( 1276): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1276): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1276): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1276): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1276): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2873): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 2873): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 2873): [1] 5.onFinished: Scheduling replication attempt 3.
,I/GLSUser ( 1276): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1276): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1276): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1276): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1276): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2873): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.,
D/Finsky  ( 2873): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 2873): [1] 5.onFinished: Scheduling replication attempt 4.
,D/HeadsetStateMachine( 2193): Disconnected process message: 10, size: 0
,I/BooksSync( 3698): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3698): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1276): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1276): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1276): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1276): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1276): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1276): Explicit concurrent mark sweep GC freed 58670(3MB) AllocSpace objects, 11(1213KB) LOS objects, 37% free, 26MB/42MB, paused 1.625ms total 64.056ms,
,I/GLSUser ( 1276): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1276): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1276): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1276): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1276): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3698): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3698): Soft error
E/BooksSync( 3698): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3698): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3698): Sync error
E/BooksSync( 3698): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3698): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3698): Finished books sync
,D/SyncManager(  825): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 760896, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2193): Disconnected process message: 10, size: 0,
,I/art     (  825): Explicit concurrent mark sweep GC freed 29826(1277KB) AllocSpace objects, 6(378KB) LOS objects, 31% free, 34MB/50MB, paused 2.160ms total 90.769ms
,I/GLSUser ( 1276): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1276): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1276): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1276): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
V/GLSActivity( 1276): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2873): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 2873): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 2873): [1] 5.onFinished: Scheduling replication attempt 5.
,I/GLSUser ( 1276): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1276): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1276): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1276): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1276): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2873): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 2873): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 2873): [1] 5.onFinished: Giving up after 6 failures.
,D/HeadsetStateMachine( 2193): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2193): Disconnected process message: 10, size: 0
,V/GoogleAuthProtoRequest( 3851): [420] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1276): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1276): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1276): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1276): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1276): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3851): [420] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3851): [420] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3851): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3851): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3851): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3851): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3851): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3851): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3851): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3851): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3851): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3851): 	at com.a.a.k.run(SourceFile:110)
,D/HeadsetStateMachine( 2193): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2193): Disconnected process message: 10, size: 0
,V/GoogleAuthProtoRequest( 3851): [421] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1276): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1276): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1276): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1276): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1276): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3851): [421] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3851): [421] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3851): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3851): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3851): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3851): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3851): 	at com.google.android.gms.gcm.c.run(Unknown Source)
,W/ExperimentUpdateService( 3851): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3851): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3851): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3851): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3851): 	,at com.a.a.k.run(SourceFile:110)
,W/bt-btm  ( 2193): Stopping oneshot timer
,D/HeadsetStateMachine( 2193): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2193): Disconnected process message: 10, size: 0
,V/GoogleAuthProtoRequest( 3851): [422] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1276): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1276): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1276): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1276): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1276): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3851): [422] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3851): [422] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3851): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3851): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3851): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3851): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3851): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3851): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3851): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3851): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3851): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3851): 	at com.a.a.k.run(SourceFile:110)
,D/HeadsetStateMachine( 2193): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2193): Disconnected process message: 10, size: 0
,D/GCM     ( 1276): Message class com.google.f.a.a.i
,D/HeadsetStateMachine( 2193): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2193): Disconnected process message: 10, size: 0
,V/GoogleAuthProtoRequest( 3851): [423] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1276): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1276): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1276): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1276): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1276): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3851): [423] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3851): [423] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3851): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3851): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3851): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3851): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3851): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3851): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3851): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3851): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3851): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3851): 	at com.a.a.k.run(SourceFile:110)
,D/HeadsetStateMachine( 2193): Disconnected process message: 10, size: 0
,V/GoogleAuthProtoRequest( 3851): [424] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1276): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1276): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1276): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1276): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1276): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3851): [424] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3851): [424] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3851): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3851): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3851): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3851): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3851): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3851): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3851): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3851): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3851): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3851): 	at com.a.a.k.run(SourceFile:110)
,D/HeadsetStateMachine( 2193): Disconnected process message: 10, size: 0
,V/KeepSync( 3667): Connecting to GoogleApiClient
,I/GLSUser ( 1276): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1276): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1276): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1276): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1276): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1816): Handling authorization failure
E/ClientConnectionOperation( 1816): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1816): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1816): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1816): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1816): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1816): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1816): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1816): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1816): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1816): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1816): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1816): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1816): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1816): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1816): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1816): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1816): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1816): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1816): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1816): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1816): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1816): 	... 7 more
,I/art     (  825): Explicit concurrent mark sweep GC freed 37295(1824KB) AllocSpace objects, 2(126KB) LOS objects, 32% free, 33MB/49MB, paused 1.772ms total 76.885ms
,V/KeepSync( 3667): GoogleApiClient failed to connect with error code: 4
E/SQLiteLog( 3667): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3667): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3667): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1276): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1276): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1276): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1276): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1276): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3667): IOException
E/KeepSync( 3667): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3667): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3667): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3667): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3667): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3667): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3667): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3667): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3667): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3667): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3667): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3667): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3667): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3667): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3667): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3667): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3667): 	... 10 more
W/KeepSync( 3667): Sync result 2
,D/SyncManager(  825): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 1205850, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2193): Disconnected process message: 10, size: 0
,D/WifiService(  825): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@9ebe9}
,D/WifiService(  825): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@9ebe9}
,I/UsageStatsService(  825): User[0] Flushing usage stats to disk
,I/GLSUser ( 1276): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1276): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1276): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1276): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1276): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3194): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3194): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3194): 	at jdm.a(PG:82)
E/HttpOperation( 3194): 	at jcs.o(PG:406)
E/HttpOperation( 3194): 	at jcn.a(PG:1379)
E/HttpOperation( 3194): 	at jcs.i(PG:143)
E/HttpOperation( 3194): 	at blb.a(PG:3937)
E/HttpOperation( 3194): 	at czp.a(PG:18188)
E/HttpOperation( 3194): 	at czp.a(PG:9081)
E/HttpOperation( 3194): 	at czq.run(PG:1686)
E/HttpOperation( 3194): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3194): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3194): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3194): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3194): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3194): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3194): 	at jdj.a(PG:4091)
E/HttpOperation( 3194): 	at jdj.a(PG:1125)
E/HttpOperation( 3194): 	at jdm.a(PG:77)
E/HttpOperation( 3194): 	... 12 more
E/HttpOperation( 3194): Caused by: faj: BadAuthentication
E/HttpOperation( 3194): 	at fal.a(PG:38)
E/HttpOperation( 3194): 	at jdj.a(PG:4089)
E/HttpOperation( 3194): 	... 14 more
,I/GLSUser ( 1276): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1276): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1276): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1276): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1276): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/art     ( 1276): Explicit concurrent mark sweep GC freed 69576(3MB) AllocSpace objects, 6(661KB) LOS objects, 37% free, 27MB/43MB, paused 1.507ms total 62.857ms
,E/HttpOperation( 3194): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3194): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3194): 	at jdm.a(PG:82)
E/HttpOperation( 3194): 	at jcs.o(PG:406)
E/HttpOperation( 3194): 	at jcn.a(PG:1379)
E/HttpOperation( 3194): 	at jcs.i(PG:143)
E/HttpOperation( 3194): 	at hec.a(PG:42)
E/HttpOperation( 3194): 	at hee.a(PG:102)
E/HttpOperation( 3194): 	at czr.a(PG:65)
E/HttpOperation( 3194): 	at kka.a(PG:108)
E/HttpOperation( 3194): 	at czp.a(PG:19176)
E/HttpOperation( 3194): 	at czp.a(PG:9081)
E/HttpOperation( 3194): 	at czq.run(PG:1686)
E/HttpOperation( 3194): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3194): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3194): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3194): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3194): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3194): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3194): 	at jdj.a(PG:4091)
E/HttpOperation( 3194): 	at jdj.a(PG:1125)
E/HttpOperation( 3194): 	at jdm.a(PG:77)
E/HttpOperation( 3194): 	... 15 more
E/HttpOperation( 3194): Caused by: faj: BadAuthentication
E/HttpOperation( 3194): 	at fal.a(PG:38)
E/HttpOperation( 3194): 	at jdj.a(PG:4089)
E/HttpOperation( 3194): 	... 17 more
E/ExperimentLoader( 3194): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3194): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3194): 	at jdm.a(PG:82)
E/ExperimentLoader( 3194): 	at jcs.o(PG:406)
E/ExperimentLoader( 3194): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3194): 	at jcs.i(PG:143)
E/ExperimentLoader( 3194): 	at hec.a(PG:42)
E/ExperimentLoader( 3194): 	at hee.a(PG:102)
E/ExperimentLoader( 3194): 	at czr.a(PG:65)
E/ExperimentLoader( 3194): 	at kka.a(PG:108)
E/ExperimentLoader( 3194): 	at czp.a(PG:19176)
E/ExperimentLoader( 3194): 	at czp.a(PG:9081)
E/ExperimentLoader( 3194): 	at czq.run(PG:1686)
E/ExperimentLoader( 3194): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3194): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3194): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3194): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3194): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3194): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3194): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3194): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3194): 	at jdm.a(PG:77)
E/ExperimentLoader( 3194): 	... 15 more
E/ExperimentLoader( 3194): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3194): 	at fal.a(PG:38)
E/ExperimentLoader( 3194): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3194): 	... 17 more
,D/SyncManager(  825): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 1212414, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/BooksSync( 3698): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3698): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1276): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1276): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1276): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1276): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1276): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1276): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1276): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1276): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1276): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1276): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3698): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3698): Soft error
E/BooksSync( 3698): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3698): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3698): Sync error
E/BooksSync( 3698): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3698): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3698): Finished books sync
,D/SyncManager(  825): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1304109, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2193): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2193): Disconnected process message: 10, size: 0
,V/GoogleAuthProtoRequest( 3851): [425] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1276): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1276): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1276): [GLSUser] Extracting token using key: Auth,
W/GLSActivity( 1276): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1276): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3851): [425] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3851): [425] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3851): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3851): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3851): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3851): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3851): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3851): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3851): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3851): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3851): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3851): 	at com.a.a.k.run(SourceFile:110)
,D/HeadsetStateMachine( 2193): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2193): Disconnected process message: 10, size: 0
,I/GLSUser ( 1276): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/ads_measurement
,I/GLSUser ( 1276): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/ads_measurement without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1276): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1276): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1276): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Ads     ( 1816): [JAMS] Failed to get OAuth token: com.google.android.gms.auth.ad: BadAuthentication
,D/HeadsetStateMachine( 2193): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2193): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2193): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2193): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2193): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2193): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2193): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2193): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2193): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2193): Disconnected process message: 10, size: 0
,I/ProcessStatsService(  825): Prepared write state in 9ms
,I/ProcessStatsService(  825): Prepared write state in 7ms
,I/ProcessStatsService(  825): Prepared write state in 6ms
,I/ProcessStatsService(  825): Pruning old procstats: /data/system/procstats/state-2015-12-09-19-25-24.bin
,I/art     (  825): Explicit concurrent mark sweep GC freed 47564(2MB) AllocSpace objects, 11(257KB) LOS objects, 31% free, 34MB/50MB, paused 1.411ms total 96.407ms
,W/bt-btm  ( 2193): Stopping oneshot timer
,D/HeadsetStateMachine( 2193): Disconnected process message: 10, size: 0
,I/ActivityManager(  825): Killing 3529:com.android.defcontainer/u0a7 (adj 15): empty for 1818s
,D/HeadsetStateMachine( 2193): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2193): Disconnected process message: 10, size: 0
,TIME-OUT KILL (timeout was 1800000ms)
```
