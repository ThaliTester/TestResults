#### Test 525354860130a71_thali05_motorola-Nexus 6 Logs


```
--------- beginning of main
D/HeadsetStateMachine( 2177): Disconnected process message: 10, size: 0
,D/AndroidRuntime( 3809): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 3809): CheckJNI is OFF
D/AndroidRuntime( 3809): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  820): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/WindowManager(  820): addAppToken: AppWindowToken{344b7a88 token=Token{2401d62b ActivityRecord{1fdd9e7a u0 com.test.thalitest/.MainActivity t24}}} to stack=1 task=24 at 0
D/AndroidRuntime( 3809): Shutting down VM
V/WindowManager(  820): Adding window Window{25a5095d u0 Starting com.test.thalitest} at 3 of 8 (after Window{37d37a33 u0 com.android.chrome/org.chromium.chrome.browser.document.DocumentActivity})
I/HotwordDetector( 1523): Closing mic
I/MicrophoneInputStream( 1523): mic_close com.google.android.apps.gsa.speech.audio.u@2f1c2f2b
I/ActivityManager(  820): Start proc 3823:com.test.thalitest/u0a265 for activity com.test.thalitest/.MainActivity
D/audio_hw_primary(  358): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  358): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  358): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1523): Hotword detection finished
I/HotwordRecognitionRnr( 1523): Stopping hotword detection.
I/ActivityManager(  820): Killing 3389:com.google.android.gm/u0a78 (adj 15): empty #17
I/ActivityManager(  820): Killing 3063:com.google.android.music:main/u0a66 (adj 15): empty #18
,I/WebViewFactory( 3823): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3823): Time to load native libraries: 4 ms (timestamps 216-220)
I/LibraryLoader( 3823): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3823): Binding Chromium to main looper Looper (main, tid 1) {3b361789}
,I/LibraryLoader( 3823): Expected native library version number "",actual native library version number ""
I/chromium( 3823): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3823): Initializing chromium process, singleProcess=true
W/art     ( 3823): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3823): ApplicationContext is null in ApplicationStatus
,E/LocSvc_IzatApiV02(  820): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1703691539
,E/LocSvc_IzatApiV02(  820): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,W/chromium( 3823): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3823): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3823): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3823): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,I/kickstart(  871): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000,
I/kickstart(  871): STATUS: Wrote to /sys/power/wake_lock
,D/BluetoothManagerService(  820): Message: 20
D/BluetoothManagerService(  820): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@fa02ef6:true
,E/kickstart(  871): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1
I/kickstart(  871): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1' for writing
,W/art     ( 3823): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3823): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3823): CordovaWebView is running on device made by: motorola
,W/art     ( 3823): Attempt to remove local handle scope entry from IRT, ignoring,
W/art     ( 3823): Attempt to remove local handle scope entry from IRT, ignoring,
,D/OpenGLRenderer( 3823): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,D/Atlas   ( 3823): Validating map...,
,V/WindowManager(  820): Adding window Window{2ec67a3d u0 com.test.thalitest/com.test.thalitest.MainActivity} at 3 of 9 (before Window{25a5095d u0 Starting com.test.thalitest})
,W/chromium( 3823): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3823): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3823): Enabling debug mode 0
,I/ActivityManager(  820): Displayed com.test.thalitest/.MainActivity: +904ms (total +1m47s671ms)
,I/Keyboard.Facilitator( 1212): onFinishInput()
,W/BindingManager( 3823): Cannot call determinedVisibility() - never saw a connection for the pid: 3823
,D/JsMessageQueue( 3823): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3823): JniHelper::setJavaVM(0xb489d200), pthread_self() = -1576194432
,D/JX-Cordova( 3823): jxcore cordova android initializing
,I/kickstart(  871): STATUS: Received file 'm9kefs1'
I/kickstart(  871): STATUS: 950272 bytes transferred in 0.995353 seconds
I/kickstart(  871): STATUS: Successfully downloaded files from target 
I/kickstart(  871): STATUS: Wrote to /sys/power/wake_unlock
,I/kickstart(  871): STATUS: Sahara protocol completed
,E/WifiStateMachine(  820): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=3.37 targetRoamBSSID=any RSSI=-46
,E/WifiStateMachine(  820): WifiStateMachine starting scan for "NG7005g"WPA_PSK with 2462,5220
,W/jxcore-log( 3823): Initializing JXcore engine
W/jxcore-log( 3823): JXcore engine is ready
,W/jxcore-log( 3823): Starting JXcore engine
,W/.test.thalitest( 3823): type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[10727]" dev="sockfs" ino=10727 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 3823): type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,W/.test.thalitest( 3823): type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[9967]" dev="sockfs" ino=9967 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 3823): type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[23899]" dev="sockfs" ino=23899 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 3823): Platform android
W/jxcore-log( 3823): 
W/jxcore-log( 3823): Process ARCH arm
W/jxcore-log( 3823): 
,I/jxcore-log( 3823): JXcore Cordova bridge is ready!
I/jxcore-log( 3823): 
W/jxcore-log( 3823): JXcore engine is started
I/Choreographer( 3823): Skipped 146 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3823): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3823): Toggling radios to true
I/jxcore-log( 3823): 
,D/BluetoothAdapter( 3823): enable(): BT is already enabled..!
,D/WifiService(  820): setWifiEnabled: true pid=3823, uid=10265
E/WifiService(  820): Invoking mWifiStateMachine.setWifiEnabled
D/WifiService(  820): New client listening to asynchronous messages
,I/jxcore-log( 3823): Radios toggled
I/jxcore-log( 3823): 
,I/wpa_supplicant( 1236): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  820): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  820): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  354): Clearing all IP addresses on wlan0,
,V/NativeCrypto( 1492): Read error: ssl=0xaec59c00: I/O error during system call, Connection timed out
V/NativeCrypto( 1492): SSL shutdown failed: ssl=0xaec59c00: I/O error during system call, Broken pipe
D/ConnectivityService(  820): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  820): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
D/ConnectivityService(  820): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10011
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): ValidatedState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): DefaultState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): Forcing reevaluation
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
,E/WifiStateMachine(  820): Start Disconnecting Watchdog 1,
,E/WifiStateMachine(  820): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,I/ActivityManager(  820): Start proc 3883:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
,D/CommandListener(  354): Clearing all IP addresses on wlan0
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
,D/ConnectivityService(  820): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler( 1064): CM callback handler got msg 524292
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): OfflineState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): Disconnected - quitting
D/WifiNetworkAgent(  820): NetworkAgent: NetworkAgent channel lost
,D/CSLegacyTypeTracker(  820): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,E/WifiStateMachine(  820): CMD_AUTO_CONNECT sup state CompletedState my state DisconnectedState nid=0 roam=3
E/WifiStateMachine(  820): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=0
D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering(  820): MasterInitialState.processMessage what=3
,D/ConnectivityService(  820): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/ConnectivityService(  820): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/ConnectivityService(  820): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
,D/Tethering(  820): MasterInitialState.processMessage what=3
,D/PhoneInterfaceManager( 1278): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1278): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  820): getDataEnabled: retVal=false
,E/GpsLocationProvider(  820): No APN found to select.
,D/PhoneInterfaceManager( 1278): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1278): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
D/TelephonyManager(  820): getDataEnabled: retVal=false
E/GpsLocationProvider(  820): No APN found to select.
,W/ResourcesManager( 3883): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,E/WifiConfigStore(  820): Setting BSSID for "NG7005g"WPA_PSK to any
E/WifiConfigStore(  820): will read network variables netId=0
,E/WifiStateMachine(  820): CMD_AUTO_CONNECT did save config ->  nid=0
,E/WifiConfigStore(  820): will read network variables netId=0
,I/wpa_supplicant( 1236): wlan0: Trying to associate with SSID 'NG7005g'
,I/Babel_SMS( 3883): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 3883): MmsConfig.loadMmsSettings
,I/Babel_SMS( 3883): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
I/Babel_SMS( 3883): MmsConfig.loadFromDatabase
,E/Babel_SMS( 3883): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 3883): MmsConfig.loadFromResources
,E/Babel_SMS( 3883): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 3883): MmsConfig.loadMmsSettings: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,W/Settings( 3883): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 3883): startup - clean
,I/Babel   ( 3883): deleted: false for 0
,I/Babel_telephony( 3883): TeleModule.launchCompleted
,W/Telecom (  820): TelecomServiceImpl: null is not visible for the calling user
,I/Babel_telephony( 3883): TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
W/Babel   ( 3883): BAM#gBA: invalid account id: -1
W/Babel   ( 3883): BAM#gBA: invalid account id: -1
I/Babel_telephony( 3883): TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,W/Telecom (  820): TelecomServiceImpl: null is not visible for the calling user
,I/ActivityManager(  820): Start proc 3914:com.google.android.music:main/u0a66 for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver
,W/VideoCapabilities( 3883): Unrecognized profile 2130706433 for video/avc
,I/VideoCapabilities( 3883): Unsupported profile 4 for video/mp4v-es
,I/MusicStore( 3914): Database version: 120
W/VideoCapabilities( 3883): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 3883): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 3883): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 3883): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  820): Killing 3487:com.google.android.gms:car/u0a11 (adj 15): empty #17
,I/vclib   ( 3883): onServiceConnected
W/Babel   ( 3883): Attempted to change video mute state without an active call.
,I/wpa_supplicant( 1236): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 1236): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1236): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=0 id_str=]
,D/ConnectivityService(  820): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} }
D/ConnectivityService(  820): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiConfigStore(  820): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiConfigStore(  820): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  354): Setting iface cfg
E/WifiStateMachine(  820): Start Dhcp Watchdog 2
I/art     (  820): Explicit concurrent mark sweep GC freed 43851(2MB) AllocSpace objects, 16(444KB) LOS objects, 32% free, 33MB/49MB, paused 3.091ms total 58.416ms
,E/WifiStateMachine(  820):  WifiLinkLayerStats: 
E/WifiStateMachine(  820):  my bss beacon rx: 534
E/WifiStateMachine(  820):  RSSI mgmt: -47
E/WifiStateMachine(  820):  BE :  rx=211 tx=124 lost=0 retries=0
E/WifiStateMachine(  820):  BK :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  820):  VI :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  820):  VO :  rx=4 tx=0 lost=0 retries=0
E/WifiStateMachine(  820):  on_time : 13015 tx_time=213 rx_time=499 scan_time=0
,D/ConnectivityService(  820): updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,W/ResourcesManager( 3914): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 3914): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/native  (  820): do suspend false
,V/JNIHelp ( 3914): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,E/WifiStateMachine(  820): scanCount==0 - aborting
,I/ProviderInstaller( 3914): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 3914): GMSCore installation verified
,I/ConfigStore( 3914): Config Database version: 1
,I/art     ( 1492): Explicit concurrent mark sweep GC freed 29775(1676KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 1.199ms total 22.666ms
,I/MediaRouter( 3914): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 3914): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/ActivityManager(  820): Start proc 3945:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.steen.receiver.ConnectivityChangeReceiver
,I/dhcpcd  ( 3955): version 5.5.6 starting
,I/GHttpClientFactory( 3914): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 3914): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  820): Killing 2480:com.google.android.calendar/u0a37 (adj 15): empty #17
,I/dhcpcd  ( 3955): wlan0: rebinding lease of 192.168.1.110
,I/ActivityManager(  820): Start proc 3980:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,I/ActivityManager(  820): Killing 3349:com.android.providers.calendar/u0a3 (adj 15): empty #17
,D/SprintDMReceiver( 3980): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3980): simOperator:  IMSI: null
D/SprintDMReceiver( 3980): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1822): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1822): onCreate
,D/SystemUpdateService( 1822): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1822): active receiver: enabled
,I/SystemUpdateService( 1822): showing system update notification
,I/iu.Environment( 1822): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1822): num queued entries: 0
,I/iu.UploadsManager( 1822): num updated entries: 0
I/iu.SyncManager( 1822): NEXT; no task
,D/ChimeraCfgMgr( 1822): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/ValidateNoPeople(  820): skipping global notification
,V/SystemUpdateService( 1822): retry (wakeup: false) in 3599970 ms
,I/ActivityManager(  820): Start proc 4005:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,D/SystemUpdateService( 1822): onDestroy
,I/Babel   ( 3883): connection state changed from UNKNOWN to DISCONNECTED
,I/ActivityManager(  820): Killing 1393:android.process.acore/u0a5 (adj 15): empty #17
,D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/jxcore-log( 3823): Got Device Bluetooth address: F8:CF:C5:D9:E5:61
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): my name is : motorola-Nexus 6_PT1135
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): attempting to connect to test coordinator
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): check test folder
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): found test : ./testFindPeers.js
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): found test : ./testReConnect.js
I/jxcore-log( 3823): 
,I/GAv4    ( 4005): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4005):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4005):   adb logcat -s GAv4
,I/jxcore-log( 3823): found test : ./testSendData.js
I/jxcore-log( 3823): 
,W/GAv4    ( 4005): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/jxcore-log( 3823): Test app app.js loaded
I/jxcore-log( 3823): 
,W/GAv4    ( 4005): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,I/jxcore-log( 3823): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3823): 
,I/Choreographer( 3823): Skipped 118 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3823): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,W/GAv4    ( 4005): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 4005): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 4005): Time to load native libraries: 3 ms (timestamps 5716-5719)
,I/LibraryLoader( 4005): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 4005): Binding Chromium to main looper Looper (main, tid 1) {88ca8e4}
,I/LibraryLoader( 4005): Expected native library version number "",actual native library version number ""
I/chromium( 4005): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4005): Initializing chromium process, singleProcess=true,
W/art     ( 4005): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 4005): ApplicationContext is null in ApplicationStatus,
,W/chromium( 4005): [WARNING:resource_bundle.cc(285)] locale_file_path.empty(),
I/dhcpcd  ( 3955): wlan0: acknowledged 192.168.1.110 from 192.168.1.1
,E/libEGL  ( 4005): validate_display:255 error 3008 (EGL_BAD_DISPLAY),
E/libEGL  ( 4005): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno  ( 4005): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,I/dhcpcd  ( 3955): wlan0: leased 192.168.1.110 for 86400 seconds
,W/AudioManagerAndroid( 4005): Requires BLUETOOTH permission
,I/NSApplication( 4005): Starting up...
,I/ActivityManager(  820): Killing 3614:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,I/ActivityManager(  820): Start proc 4081:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,D/ConnectivityService(  820): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  820): Adding iface wlan0 to network 101
,E/WifiStateMachine(  820): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  820): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  820): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  820): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
D/ConnectivityService(  820): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/ConnectivityService(  820): Setting Dns servers for network 101 to [/192.168.1.1]
,D/ConnectivityService(  820): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  820): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  820): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  820):    accepting network in place of null
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): Connected
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  820): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.110/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
,D/ConnectivityService(  820): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/CSLegacyTypeTracker(  820): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityManager.CallbackHandler( 1064): CM callback handler got msg 524290
D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  820): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 3914): type=WIFI subType= reason=null isConnected=true
,D/PhoneInterfaceManager( 1278): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1278): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  820): getDataEnabled: retVal=false
,E/GpsLocationProvider(  820): No APN found to select.
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 04 Dec 2015 08:45:19 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1449218719338], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1449218719320]}
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): Validated
D/ConnectivityService(  820): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/ConnectivityService(  820): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  820): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  820): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  820): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1064): CM callback handler got msg 524290
D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,V/MusicLeanback( 3914): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/ActivityManager(  820): Killing 3634:com.android.musicfx/u0a18 (adj 15): empty #17
,D/SprintDMReceiver( 3980): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3980): simOperator:  IMSI: null
D/SprintDMReceiver( 3980): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1822): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1822): onCreate
,D/SystemUpdateService( 1822): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1822): active receiver: enabled
,I/SystemUpdateService( 1822): showing system update notification
,I/ValidateNoPeople(  820): skipping global notification
,V/SystemUpdateService( 1822): retry (wakeup: false) in 3599982 ms
,I/iu.Environment( 1822): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
D/SystemUpdateService( 1822): onDestroy
,I/iu.UploadsManager( 1822): num queued entries: 0
,I/iu.UploadsManager( 1822): num updated entries: 0,
I/iu.SyncManager( 1822): NEXT; no task
,D/ChimeraCfgMgr( 1822): Loading module com.google.android.gms.kids from APK com.google.android.gms,
,D/ChimeraCfgMgr( 1822): Loading module com.google.android.gms.kids from APK com.google.android.gms,
,V/MusicLeanback( 3914): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/GLSUser ( 1492): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1492): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1492): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1492): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/SprintDMReceiver( 3980): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,V/GLSActivity( 1492): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SprintDMHelper( 3980): simOperator:  IMSI: null
D/SprintDMReceiver( 3980): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1822): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1822): onCreate
,D/SystemUpdateService( 1822): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1822): active receiver: enabled
,I/Babel   ( 3883): connection state changed from DISCONNECTED to CONNECTED
,W/Kids    ( 1822): [AccountUtils] Account not ready
W/Kids    ( 1822): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 1822): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 1822): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 1822): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 1822): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 1822): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 1822): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 1822): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 1822): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 1822): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 1822): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 1822): 	at java.lang.Thread.run(Thread.java:818)
,I/SystemUpdateService( 1822): showing system update notification
,I/ValidateNoPeople(  820): skipping global notification
,V/SystemUpdateService( 1822): retry (wakeup: false) in 3599972 ms
,D/SystemUpdateService( 1822): onDestroy
,D/ChimeraCfgMgr( 1822): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/GLSUser ( 1492): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1492): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1492): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1492): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1492): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Kids    ( 1822): [AccountUtils] Account not ready
W/Kids    ( 1822): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 1822): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 1822): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 1822): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 1822): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 1822): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 1822): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 1822): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 1822): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 1822): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 1822): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 1822): 	at java.lang.Thread.run(Thread.java:818)
,V/Herrevad( 1822): NQAS connected
,D/GCM     ( 1492): Connected
,D/GCM     ( 1492): Message class com.google.f.a.a.p
,I/jxcore-log( 3823): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3823): 
,D/ConnectivityService(  820): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/jxcore-log( 3823): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3823): 
,D/WearableService( 3369): callingUid 10011, callindPid: 3369
,I/art     (  820): Explicit concurrent mark sweep GC freed 35598(1639KB) AllocSpace objects, 1(16KB) LOS objects, 32% free, 33MB/49MB, paused 1.917ms total 91.484ms
,I/MusicLeanback( 3914): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 3914): Stop autocaching.
,E/GmsUtils( 3914): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 3914): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/jxcore-log( 3823): BLE supported!!
I/jxcore-log( 3823): 
,V/GLSActivity( 1492): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1492): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1492): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1492): [GLSUser] Extracting token using key: Auth,
W/GLSActivity( 1492): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1492): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3446): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3446): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3446): [1] 5.onFinished: Scheduling replication attempt 4.
,E/WifiStateMachine(  820): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=7.03 rxSuccessRate=9.73 targetRoamBSSID=any RSSI=-47
E/WifiStateMachine(  820): WifiStateMachine L2Connected CMD_START_SCAN source -2 10, 11 -> obsolete
,I/jxcore-log( 3823): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3823): 
,E/WifiStateMachine(  820): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=2.51 rxSuccessRate=3.93 targetRoamBSSID=any RSSI=-47
E/WifiStateMachine(  820): WifiStateMachine L2Connected CMD_START_SCAN source -2 9, 11 -> obsolete
,I/PowerManagerService(  820): Going to sleep due to screen timeout (uid 1000)...,
,I/Adreno  (  820): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/PermissionCache(  260): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (230 us)
,I/DisplayManagerService(  820): Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
D/SurfaceFlinger(  260): Set power mode=0, type=0 flinger=0xb6082000
D/qdhwcomposer(  260): hwc_setPowerMode: Setting mode 0 on display: 0
V/ActivityManager(  820): Display changed displayId=0
,I/BooksSync( 3710): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3710): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1492): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1492): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1492): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1492): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1492): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1492): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1492): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1492): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1492): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/qdhwcomposer(  260): handle_blank_event: dpy:0 panel power state: 0
V/GLSActivity( 1492): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/qdhwcomposer(  260): hwc_setPowerMode: Done setting mode 0 on display 0
D/SurfaceControl(  820): Excessive delay in setPowerMode(): 263ms
,I/DreamManagerService(  820): Entering dreamland.,
I/PowerManagerService(  820): Dozing...
I/DreamController(  820): Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,D/audio_hw_primary(  358): adev_set_parameters: enter: screen_state=on
D/mot_vr_audio_hw(  358): adev_set_parameters: screen_state=on
,E/BooksAccountManager( 3710): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3710): Soft error
E/BooksSync( 3710): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3710): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3710): Sync error
E/BooksSync( 3710): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3710): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3710): Finished books sync
,E/WifiStateMachine(  820): cancelDelayedScan -> 12
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 163214, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,E/native  (  820): do suspend false
,I/Keyboard.Facilitator( 1212): onFinishInput()
,E/WifiStateMachine(  820): cancelDelayedScan -> 14
,E/native  (  820): do suspend true,
,D/audio_hw_primary(  358): adev_set_parameters: enter: screen_state=off
,D/mot_vr_audio_hw(  358): adev_set_parameters: screen_state=off
,E/WifiStateMachine(  820): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-46
E/WifiStateMachine(  820): WifiStateMachine L2Connected CMD_START_SCAN source -2 13, 14 -> obsolete
,I/jxcore-log( 3823): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3823): 
,E/WifiStateMachine(  820): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-46
E/WifiStateMachine(  820): WifiStateMachine L2Connected CMD_START_SCAN source -2 11, 14 -> obsolete
,I/jxcore-log( 3823): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3823): 
,V/GLSActivity( 1492): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1492): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1492): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1492): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1492): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1492): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3446): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3446): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3446): [1] 5.onFinished: Scheduling replication attempt 5.
,I/jxcore-log( 3823): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3823): 
,V/GLSActivity( 1492): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1492): Vacuum at: now=1449218752823 tag=VacuumService
,V/GoogleAuthProtoRequest( 3945): [430] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1492): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1492): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1492): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1492): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1492): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/ExperimentUpdateService( 3945): [430] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3945): [430] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3945): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3945): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3945): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3945): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3945): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3945): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3945): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3945): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3945): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3945): 	at com.a.a.k.run(SourceFile:110)
,I/GoogleURLConnFactory( 1492): Using platform SSLCertificateSocketFactory
,I/GLSUser ( 1492): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1492): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1492): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1492): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1492): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1492): Explicit concurrent mark sweep GC freed 37682(2MB) AllocSpace objects, 6(661KB) LOS objects, 37% free, 26MB/42MB, paused 1.703ms total 54.571ms
,E/Uploader( 1492): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1492): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1492): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1492): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1492): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1492): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1492): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1492): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1492): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1492): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1492): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1492): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1492): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1492): No account for auth token provided
,W/Uploader( 1492): No account for auth token provided
,W/Uploader( 1492): No account for auth token provided
,I/GLSUser ( 1492): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1492): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1492): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1492): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1492): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1492): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1492): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1492): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1492): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1492): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1492): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1492): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1492): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1492): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1492): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1492): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1492): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1492): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1492): No account for auth token provided
,W/Uploader( 1492): No account for auth token provided
,W/Uploader( 1492): No account for auth token provided
,I/GLSUser ( 1492): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1492): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1492): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1492): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1492): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1492): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1492): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1492): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1492): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1492): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1492): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1492): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1492): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1492): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1492): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1492): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1492): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1492): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1492): No account for auth token provided
,W/Uploader( 1492): No account for auth token provided
,W/Uploader( 1492): No account for auth token provided
,W/Uploader( 1492): No account for auth token provided
,W/Uploader( 1492): No account for auth token provided
,W/Uploader( 1492):  no longer exists, so no auth token.
,I/GLSUser ( 1492): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1492): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1492): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1492): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,V/GLSActivity( 1492): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1492): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1492): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1492): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1492): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1492): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1492): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1492): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1492): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1492): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1492): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1492): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1492): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1492): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/jxcore-log( 3823): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3823): 
,D/HeadsetStateMachine( 2177): Disconnected process message: 10, size: 0
,I/jxcore-log( 3823): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3823): 
,I/art     (  820): Explicit concurrent mark sweep GC freed 38508(1839KB) AllocSpace objects, 4(252KB) LOS objects, 31% free, 34MB/50MB, paused 1.610ms total 79.622ms
,V/KeepSync( 3727): Connecting to GoogleApiClient
,I/GLSUser ( 1492): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1492): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1492): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1492): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1492): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3215): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3215): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3215): 	at jdm.a(PG:82)
E/HttpOperation( 3215): 	at jcs.o(PG:406)
E/HttpOperation( 3215): 	at jcn.a(PG:1379)
E/HttpOperation( 3215): 	at jcs.i(PG:143)
E/HttpOperation( 3215): 	at blb.a(PG:3937)
E/HttpOperation( 3215): 	at czp.a(PG:18188)
E/HttpOperation( 3215): 	at czp.a(PG:9081)
E/HttpOperation( 3215): 	at czq.run(PG:1686)
E/HttpOperation( 3215): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3215): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3215): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3215): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3215): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3215): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3215): 	at jdj.a(PG:4091)
E/HttpOperation( 3215): 	at jdj.a(PG:1125)
E/HttpOperation( 3215): 	at jdm.a(PG:77)
E/HttpOperation( 3215): 	... 12 more
E/HttpOperation( 3215): Caused by: faj: BadAuthentication
E/HttpOperation( 3215): 	at fal.a(PG:38)
E/HttpOperation( 3215): 	at jdj.a(PG:4089)
E/HttpOperation( 3215): 	... 14 more
,I/GLSUser ( 1492): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1492): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1492): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1492): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1492): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1822): Handling authorization failure
E/ClientConnectionOperation( 1822): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1822): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1822): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1822): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1822): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1822): 	... 7 more
,V/KeepSync( 3727): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3727): (284) automatic index on blob_node(is_deleted)
I/GLSUser ( 1492): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1492): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1492): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1492): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1492): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SQLiteLog( 3727): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3727): (284) automatic index on blob_node(is_deleted)
,E/HttpOperation( 3215): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3215): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3215): 	at jdm.a(PG:82)
E/HttpOperation( 3215): 	at jcs.o(PG:406)
E/HttpOperation( 3215): 	at jcn.a(PG:1379)
E/HttpOperation( 3215): 	at jcs.i(PG:143)
E/HttpOperation( 3215): 	at hec.a(PG:42)
E/HttpOperation( 3215): 	at hee.a(PG:102)
E/HttpOperation( 3215): 	at czr.a(PG:65)
E/HttpOperation( 3215): 	at kka.a(PG:108)
E/HttpOperation( 3215): 	at czp.a(PG:19176)
E/HttpOperation( 3215): 	at czp.a(PG:9081)
E/HttpOperation( 3215): 	at czq.run(PG:1686)
E/HttpOperation( 3215): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3215): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3215): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3215): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3215): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3215): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3215): 	at jdj.a(PG:4091)
E/HttpOperation( 3215): 	at jdj.a(PG:1125)
E/HttpOperation( 3215): 	at jdm.a(PG:77)
E/HttpOperation( 3215): 	... 15 more
E/HttpOperation( 3215): Caused by: faj: BadAuthentication
E/HttpOperation( 3215): 	at fal.a(PG:38)
E/HttpOperation( 3215): 	at jdj.a(PG:4089)
E/HttpOperation( 3215): 	... 17 more
,E/ExperimentLoader( 3215): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token,
E/ExperimentLoader( 3215): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3215): 	at jdm.a(PG:82)
E/ExperimentLoader( 3215): 	at jcs.o(PG:406)
E/ExperimentLoader( 3215): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3215): 	at jcs.i(PG:143)
E/ExperimentLoader( 3215): 	at hec.a(PG:42)
E/ExperimentLoader( 3215): 	at hee.a(PG:102)
E/ExperimentLoader( 3215): 	at czr.a(PG:65)
E/ExperimentLoader( 3215): 	at kka.a(PG:108)
E/ExperimentLoader( 3215): 	at czp.a(PG:19176)
E/ExperimentLoader( 3215): 	at czp.a(PG:9081)
E/ExperimentLoader( 3215): 	at czq.run(PG:1686)
E/ExperimentLoader( 3215): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3215): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3215): 	,at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3215): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3215): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3215): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3215): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3215): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3215): 	at jdm.a(PG:77)
E/ExperimentLoader( 3215): 	... 15 more
E/ExperimentLoader( 3215): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3215): 	at fal.a(PG:38)
E/ExperimentLoader( 3215): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3215): 	,... 17 more
,I/GLSUser ( 1492): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1492): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1492): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1492): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1492): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3727): IOException
E/KeepSync( 3727): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3727): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3727): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3727): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3727): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3727): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3727): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3727): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3727): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3727): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3727): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3727): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3727): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3727): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3727): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3727): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3727): 	... 10 more
W/KeepSync( 3727): Sync result 2
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 167546, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 169521, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,V/GLSActivity( 1492): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1492): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1492): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1492): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1492): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1492): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3446): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.,
D/Finsky  ( 3446): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3446): [1] 5.onFinished: Giving up after 6 failures.
,I/jxcore-log( 3823): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3823): ,
,D/HeadsetStateMachine( 2177): Disconnected process message: 10, size: 0
,I/jxcore-log( 3823): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3823): 
,V/GoogleAuthProtoRequest( 3945): [431] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1492): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1492): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1492): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1492): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1492): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3945): [431] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3945): [431] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3945): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3945): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3945): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3945): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3945): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3945): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3945): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3945): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3945): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3945): 	at com.a.a.k.run(SourceFile:110)
,I/jxcore-log( 3823): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3823): 
,I/BooksSync( 3710): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3710): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1492): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1492): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1492): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1492): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1492): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Keyboard.Facilitator.LanguageModelFlusher( 1212): run()
I/Keyboard.Facilitator( 1212): flushDynamicLanguageModels()
,I/ConfigService( 1492): onCreate
,I/GLSUser ( 1492): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1492): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1492): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1492): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1492): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3710): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3710): Soft error
E/BooksSync( 3710): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3710): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3710): Sync error
E/BooksSync( 3710): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3710): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3710): Finished books sync
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 195117, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/jxcore-log( 3823): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3823): 
,I/ConfigService( 1492): onDestroy
,I/jxcore-log( 3823): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3823): 
,D/HeadsetStateMachine( 2177): Disconnected process message: 10, size: 0,
,I/jxcore-log( 3823): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3823): 
,V/KeepSync( 3727): Connecting to GoogleApiClient
,I/GLSUser ( 1492): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1492): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1492): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1492): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1492): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1492): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1492): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1492): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1492): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1492): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/ClientConnectionOperation( 1822): Handling authorization failure
E/ClientConnectionOperation( 1822): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1822): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1822): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1822): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1822): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1822): 	... 7 more
,V/KeepSync( 3727): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3727): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3727): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3727): (284) automatic index on blob_node(is_deleted)
,E/HttpOperation( 3215): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3215): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3215): 	at jdm.a(PG:82)
E/HttpOperation( 3215): 	at jcs.o(PG:406)
E/HttpOperation( 3215): 	at jcn.a(PG:1379)
E/HttpOperation( 3215): 	at jcs.i(PG:143)
E/HttpOperation( 3215): 	at blb.a(PG:3937)
E/HttpOperation( 3215): 	at czp.a(PG:18188)
E/HttpOperation( 3215): 	at czp.a(PG:9081)
E/HttpOperation( 3215): 	at czq.run(PG:1686)
E/HttpOperation( 3215): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3215): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3215): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3215): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3215): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3215): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3215): 	at jdj.a(PG:4091)
E/HttpOperation( 3215): 	at jdj.a(PG:1125)
E/HttpOperation( 3215): 	at jdm.a(PG:77)
E/HttpOperation( 3215): 	... 12 more
E/HttpOperation( 3215): Caused by: faj: BadAuthentication
E/HttpOperation( 3215): 	at fal.a(PG:38)
E/HttpOperation( 3215): 	at jdj.a(PG:4089)
E/HttpOperation( 3215): 	... 14 more
,I/GLSUser ( 1492): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1492): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1492): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1492): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1492): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3215): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3215): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3215): 	at jdm.a(PG:82)
E/HttpOperation( 3215): 	at jcs.o(PG:406)
E/HttpOperation( 3215): 	at jcn.a(PG:1379)
E/HttpOperation( 3215): 	at jcs.i(PG:143)
E/HttpOperation( 3215): 	at hec.a(PG:42)
E/HttpOperation( 3215): 	at hee.a(PG:102)
E/HttpOperation( 3215): 	at czr.a(PG:65)
E/HttpOperation( 3215): 	at kka.a(PG:108)
E/HttpOperation( 3215): 	at czp.a(PG:19176)
E/HttpOperation( 3215): 	at czp.a(PG:9081)
E/HttpOperation( 3215): 	at czq.run(PG:1686)
E/HttpOperation( 3215): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3215): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3215): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3215): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3215): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3215): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3215): 	at jdj.a(PG:4091)
E/HttpOperation( 3215): 	at jdj.a(PG:1125),
E/HttpOperation( 3215): 	,at jdm.a(PG:77)
E/HttpOperation( 3215): 	... 15 more
E/HttpOperation( 3215): Caused by: faj: BadAuthentication
E/HttpOperation( 3215): ,	at fal.a(PG:38)
E/HttpOperation( 3215): 	at jdj.a(PG:4089)
E/HttpOperation( 3215): 	... 17 more
,E/ExperimentLoader( 3215): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3215): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3215): 	at jdm.a(PG:82)
E/ExperimentLoader( 3215): 	at jcs.o(PG:406)
E/ExperimentLoader( 3215): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3215): 	at jcs.i(PG:143)
,E/ExperimentLoader( 3215): 	at hec.a(PG:42)
E/ExperimentLoader( 3215): 	at hee.a(PG:102)
E/ExperimentLoader( 3215): 	at czr.a(PG:65)
E/ExperimentLoader( 3215): 	at kka.a(PG:108)
E/ExperimentLoader( 3215): 	at czp.a(PG:19176)
E/ExperimentLoader( 3215): 	at czp.a(PG:9081)
E/ExperimentLoader( 3215): 	at czq.run(PG:1686)
E/ExperimentLoader( 3215): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3215): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237),
E/ExperimentLoader( 3215): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3215): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3215): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3215): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3215): 	at jdj.a(PG:4091)
,E/ExperimentLoader( 3215): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3215): 	at jdm.a(PG:77)
E/ExperimentLoader( 3215): 	... 15 more
,E/ExperimentLoader( 3215): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3215): 	at fal.a(PG:38)
E/ExperimentLoader( 3215): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3215): 	,... 17 more
,I/GLSUser ( 1492): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1492): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1492): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1492): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1492): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  820): Explicit concurrent mark sweep GC freed 27864(1192KB) AllocSpace objects, 9(615KB) LOS objects, 32% free, 33MB/49MB, paused 1.744ms total 66.689ms
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 225507, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,E/KeepSync( 3727): IOException
E/KeepSync( 3727): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3727): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3727): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3727): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3727): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3727): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3727): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3727): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3727): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3727): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3727): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3727): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3727): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3727): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3727): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3727): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3727): 	... 10 more
W/KeepSync( 3727): Sync result 2
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 225870, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/jxcore-log( 3823): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3823): 
,D/HeadsetStateMachine( 2177): Disconnected process message: 10, size: 0
,I/jxcore-log( 3823): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3823): ,
,I/jxcore-log( 3823): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3823): ,
,I/jxcore-log( 3823): DBG, CoordinatorConnector connect called
I/jxcore-log( 3823): 
I/jxcore-log( 3823): Coordinator is now connected to the server!
I/jxcore-log( 3823): 
,I/chromium( 3823): [INFO:CONSOLE(63)] "logCallback connected to server", source: file:///android_asset/www/js/thali_main.js (63)
,V/GoogleAuthProtoRequest( 3945): [432] a.<init>: mAccountName set to: thalitester@gmail.com
,I/art     ( 1492): Explicit concurrent mark sweep GC freed 57576(3MB) AllocSpace objects, 8(799KB) LOS objects, 36% free, 27MB/43MB, paused 1.689ms total 43.812ms
,I/GLSUser ( 1492): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1492): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1492): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1492): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1492): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3945): [432] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3945): [432] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3945): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3945): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3945): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3945): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3945): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3945): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3945): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3945): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3945): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3945): 	at com.a.a.k.run(SourceFile:110)
,D/HeadsetStateMachine( 2177): Disconnected process message: 10, size: 0
,I/BooksSync( 3710): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3710): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1492): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1492): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1492): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1492): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1492): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1492): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1492): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1492): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1492): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1492): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3710): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication,
E/BooksSync( 3710): Soft error
,E/BooksSync( 3710): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3710): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3710): Sync error,
E/BooksSync( 3710): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3710): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3710): Finished books sync,
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 286827, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2177): Disconnected process message: 10, size: 0
,V/KeepSync( 3727): Connecting to GoogleApiClient
,I/GLSUser ( 1492): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1492): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1492): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1492): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1492): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1822): Handling authorization failure
E/ClientConnectionOperation( 1822): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1822): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1822): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1822): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1822): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1822): 	... 7 more
,V/KeepSync( 3727): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3727): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3727): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3727): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1492): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1492): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1492): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1492): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1492): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3215): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3215): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3215): 	at jdm.a(PG:82)
E/HttpOperation( 3215): 	at jcs.o(PG:406)
E/HttpOperation( 3215): 	at jcn.a(PG:1379)
E/HttpOperation( 3215): 	at jcs.i(PG:143)
E/HttpOperation( 3215): 	at blb.a(PG:3937)
E/HttpOperation( 3215): 	at czp.a(PG:18188)
E/HttpOperation( 3215): 	at czp.a(PG:9081)
E/HttpOperation( 3215): 	at czq.run(PG:1686)
E/HttpOperation( 3215): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3215): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3215): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3215): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3215): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3215): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3215): 	at jdj.a(PG:4091)
E/HttpOperation( 3215): 	at jdj.a(PG:1125)
E/HttpOperation( 3215): 	at jdm.a(PG:77)
E/HttpOperation( 3215): 	... 12 more
E/HttpOperation( 3215): Caused by: faj: BadAuthentication
E/HttpOperation( 3215): 	at fal.a(PG:38)
E/HttpOperation( 3215): 	at jdj.a(PG:4089)
E/HttpOperation( 3215): 	... 14 more
,I/GLSUser ( 1492): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1492): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1492): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1492): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1492): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1492): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1492): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1492): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1492): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,E/HttpOperation( 3215): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3215): java.io.IOException: Cannot obtain authentication token
,E/HttpOperation( 3215): 	at jdm.a(PG:82)
E/HttpOperation( 3215): 	at jcs.o(PG:406)
E/HttpOperation( 3215): 	at jcn.a(PG:1379)
E/HttpOperation( 3215): 	at jcs.i(PG:143)
E/HttpOperation( 3215): 	at hec.a(PG:42)
E/HttpOperation( 3215): 	at hee.a(PG:102)
E/HttpOperation( 3215): 	at czr.a(PG:65)
E/HttpOperation( 3215): 	at kka.a(PG:108)
E/HttpOperation( 3215): 	at czp.a(PG:19176)
E/HttpOperation( 3215): ,	at czp.a(PG:9081)
E/HttpOperation( 3215): 	at czq.run(PG:1686)
E/HttpOperation( 3215): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3215): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3215): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3215): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3215): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3215): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3215): 	at jdj.a(PG:4091)
E/HttpOperation( 3215): 	at jdj.a(PG:1125)
E/HttpOperation( 3215): 	at jdm.a(PG:77)
E/HttpOperation( 3215): 	... 15 more
E/HttpOperation( 3215): Caused by: faj: BadAuthentication
E/HttpOperation( 3215): 	at fal.a(PG:38)
E/HttpOperation( 3215): 	at jdj.a(PG:4089)
E/HttpOperation( 3215): 	... 17 more
V/GLSActivity( 1492): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/ExperimentLoader( 3215): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3215): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3215): 	at jdm.a(PG:82)
E/ExperimentLoader( 3215): 	at jcs.o(PG:406)
E/ExperimentLoader( 3215): 	,at jcn.a(PG:1379)
E/ExperimentLoader( 3215): 	at jcs.i(PG:143)
E/ExperimentLoader( 3215): 	at hec.a(PG:42)
E/ExperimentLoader( 3215): 	at hee.a(PG:102)
E/ExperimentLoader( 3215): 	at czr.a(PG:65)
E/ExperimentLoader( 3215): 	at kka.a(PG:108)
E/ExperimentLoader( 3215): 	at czp.a(PG:19176)
E/ExperimentLoader( 3215): 	at czp.a(PG:9081)
E/ExperimentLoader( 3215): 	at czq.run(PG:1686)
E/ExperimentLoader( 3215): 	,at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3215): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3215): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3215): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3215): 	at java.lang.Thread.run(Thread.java:818)
,E/ExperimentLoader( 3215): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3215): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3215): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3215): 	at jdm.a(PG:77)
E/ExperimentLoader( 3215): 	... 15 more
E/ExperimentLoader( 3215): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3215): 	at fal.a(PG:38)
E/ExperimentLoader( 3215): 	,at jdj.a(PG:4089)
E/ExperimentLoader( 3215): 	... 17 more
,E/KeepSync( 3727): IOException
E/KeepSync( 3727): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3727): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3727): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3727): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3727): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3727): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3727): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3727): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3727): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3727): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3727): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3727): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3727): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3727): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3727): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3727): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3727): 	... 10 more
W/KeepSync( 3727): Sync result 2
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 318227, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 317422, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,V/GLSActivity( 1492): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1492): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1492): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1492): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1492): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1492): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1492): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1492): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1492): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1492): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1492): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1492): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1492): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 3446): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3446): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3446): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 3446): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3446): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/PlayEventLogger( 3446): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3446): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 3446): Ignoring header User-Agent because its value was null.
,D/WifiService(  820): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@243db6ea}
,E/WifiStateMachine(  820): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-46
,I/EventLogService( 1822): Opted in for usage reporting
I/EventLogService( 1822): Aggregate from 1449217140128 (log), 1449217140128 (data)
,D/HeadsetStateMachine( 2177): Disconnected process message: 10, size: 0
,W/EventLogAggregator( 1822): Unknown tag: snet_gcore
W/EventLogAggregator( 1822): Unknown tag: snet_launch_service
,I/ServiceDumpSys( 1822): dumping service [account]
,D/WifiService(  820): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@243db6ea}
,E/LocSvc_IzatApiV02(  820): E/virtual int izat_core::IzatApiV02::injectLocation(GpsExtLocation):857]: error! inject position failed
,I/jxcore-log( 3823): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): DBG, CoordinatorConnector command called
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":10000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":20,"addressList":[{"address":"B0:C5:59:3F:75:69","tryCount":0},{"address":"7C:F9:0E:37:96:AB","tryCount":0},{"address":"F8:95:C7:87:85:54","tryCount":0},{"address":"F8:95:C7:87:3C:51","tryCount":0},{"address":"08:EC:A9:50:76:27","tryCount":0},{"address":"34:FC:EF:9D:93:0B","tryCount":0},{"address":"7C:F9:0E:34:8A:A0","tryCount":0},{"address":"E0:DB:10:1F:C9:5E","tryCount":0},{"address":"E0:DB:10:14:E2:C0","tryCount":0},{"address":"58:3F:54:73:64:C0","tryCount":0},{"address":"F4:F1:E1:5C:3B:E2","tryCount":0},{"address":"58:2A:F7:ED:96:BE","tryCount":0},{"address":"34:FC:EF:11:B1:66","tryCount":0},{"address":"B4:CE:F6:AB:A4:6A","tryCount":0},{"address":"80:01:84:8A:B3:68","tryCount":0},{"address":"44:80:EB:7B:5A:05","tryCount":0},{"address":"08:EC:A9:50:75:41","tryCount":0},{"address":"38:94:96:B5:06
,I/jxcore-log( 3823): Start now : testSendData.js,
,I/jxcore-log( 3823): 
I/jxcore-log( 3823): testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 20
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): check server
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): serverPort is 48599
I/jxcore-log( 3823): 
,D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0,
,I/        ( 3823): Stoping All
,I/        ( 3823): Stopping services
,I/        ( 3823): Stop Bluetooth
D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/        ( 3823): Start-My BT: F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/        ( 3823):  mInstanceString : {"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT1135","ra":"F8:CF:C5:D9:E5:61"}
,I/        ( 3823): All stuff available and enabled
,I/        ( 3823): Stoping All
I/        ( 3823): Stopping services
I/        ( 3823): Stop Bluetooth
,I/        ( 3823): Starting All
I/        ( 3823): Stopping services
I/        ( 3823): Starting services address: {"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT1135","ra":"F8:CF:C5:D9:E5:61"}, org.thaliproject.p2p.btconnectorlib.BTConnectorSettings@3731150a
I/        ( 3823): Stopping services
,I/        ( 3823): Starting services address: {"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT1135","ra":"F8:CF:C5:D9:E5:61"}
,I/        ( 3823): Add local service :{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT1135","ra":"F8:CF:C5:D9:E5:61"}, length : 82
,I/        ( 3823): peerDiscoveryTimer timeout value:8596
I/        ( 3823): Stop Bluetooth
,I/        ( 3823): StartBluetooth listener
I/        ( 3823): StartBluetooth listener
D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3823): getBluetoothService() called with no BluetoothManagerCallback
,I/jxcore-log( 3823): StartBroadcasting started ok
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): do fake peer & start
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): Connect to fake peer: 34:FC:EF:11:B1:66
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:49:52.499Z SendDataConnector.js: Start called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:49:52.500Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T08:49:52.500Z SendDataConnector.js: do connect now
I/jxcore-log( 3823): 
,I/BTListenerThread( 3823): starting to listen
I/BTListenerThread( 3823): waiting to accept incoming Connection
I/        ( 3823): Selected device address: 34:FC:EF:11:B1:66, name: null
,I/        ( 3823): Connecting to null, at 34:FC:EF:11:B1:66
,I/jxcore-log( 3823): 2015-12-04T08:49:52.510Z SendDataTCPServer.js: TCP/IP server is bound to port: 48599
I/jxcore-log( 3823): 
I/BTConnectToThread( 3823): Starting to connect
I/chromium( 3823): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
,W/BluetoothAdapter( 3823): getBluetoothService() called with no BluetoothManagerCallback
I/WB      ( 3823): We already were running, thus doing nothing
I/        ( 3823): Added local service
,I/        ( 3823): Cleared service requests
I/        ( 3823): Stopped peer discovery
I/        ( 3823): Started peer discovery
,I/        ( 3823): Discovery state changed to Started.
,D/BTIF_SOCK( 2177): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-btif ( 2177): info:x10
D/        ( 2177): remote version info [34:fc:ef:11:b1:66]: 6, f, 6109
E/BluetoothRemoteDevices( 2177): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2177): process_service_search_attr_rsp
,D/btif_config( 2177): btif_get_device_type: Device [34:fc:ef:11:b1:66] type 1
,I/BluetoothBondStateMachine( 2177): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:B1:66 newState: 1
E/bt-btif ( 2177): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2177): Bond State Change Intent:34:FC:EF:11:B1:66 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 2177): Entering PendingCommandState State
,I/ActivityManager(  820): Start proc 4243:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.BluetoothPairingRequest
,I/art     (  370): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 350us total 15.923ms
,I/art     (  370): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 352us total 14.945ms
,I/art     (  370): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 236us total 14.373ms
,I/art     (  820): Explicit concurrent mark sweep GC freed 32685(1549KB) AllocSpace objects, 12(380KB) LOS objects, 31% free, 34MB/50MB, paused 1.580ms total 115.208ms
D/BluetoothManagerService(  820): Message: 20
D/BluetoothManagerService(  820): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1cf157a8:true
,I/ActivityManager(  820): Killing 3665:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,I/BluetoothBondStateMachine( 2177): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:B1:66 newState: 0
,D/BluetoothAdapterProperties( 2177): Failed to remove device: 34:FC:EF:11:B1:66
,I/BluetoothBondStateMachine( 2177): Bond State Change Intent:34:FC:EF:11:B1:66 OldState: 11 NewState: 10
,I/wpa_supplicant( 1236): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3823): Found 1 peers.
,I/SS      ( 3823): Peer(1): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3823): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3823): Added service request
,I/BluetoothBondStateMachine( 2177): StableState(): Entering Off State
,I/wpa_supplicant( 1236): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1236): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0,
,I/wpa_supplicant( 1236): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3823): Started service discovery
,W/bt-btif ( 2177): new conn_srvc id:26, app_id:1,
W/bt-btif ( 2177): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2177): bta_dm_pm_ssr:2, lat:1200,
I/BTConnectToThread( 3823): Starting to Handshake
,I/BTHandshakeSocketThread( 3823): Creating BTHandshakeSocketThread,
,I/BTConnectToThread( 3823): MESSAGE_WRITE 82 bytes.,
,I/BTHandshakeSocketThread( 3823): BTHandshakeSocketThread started
,I/BTConnectToThread( 3823): got MESSAGE_READ 77 bytes.
,I/BTConnectToThread( 3823): Got JSON from encryption:{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT6585"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3823): HandshakeOk : LGE-Nexus 5_PT6585
I/HS      ( 3823): Hand Shake finished outgoing for : LGE-Nexus 5_PT6585
,I/BTHandshakeSocketThread( 3823): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3823): Starting the connected thread incoming : false, LGE-Nexus 5_PT6585
,I/BtToSocketBase( 3823): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3823): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3823): mHTTPPort  set to : 56859
,I/BtConnectorHelper( 3823): Request socket is using : 56859
I/BtToRequestSocket( 3823): Now accepting connections
,I/BtConnectorHelper( 3823): Calling ConnectionStatusUpdate with port :56859
,I/jxcore-log( 3823): 2015-12-04T08:49:57.472Z SendDataConnector.js: CLIENT connected to 56859, error: null
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:49:57.472Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3823): 
,I/BtToRequestSocket( 3823): incoming data from: /127.0.0.1, port: 56859
,I/BtToRequestSocket( 3823): Set local streams,
,I/BtToRequestSocket( 3823): rin ended ---------------------------;
,I/jxcore-log( 3823): 2015-12-04T08:49:57.495Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3823): 
,D/        ( 2177): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:11977
,I/wpa_supplicant( 1236): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3823): 2015-12-04T08:49:58.464Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3823): 
,I/        ( 3823): Found Service, :{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2104","ra":"B0:C5:59:3F:75:69"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2104","ra":"B0:C5:59:3F:75:69"} -- peerIdentifier:B0:C5:59:3F:75:69, peerName: samsung-SM-G900F_PT2104, peerAddress: B0:C5:59:3F:75:69
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : B0:C5:59:3F:75:69, Name: samsung-SM-G900F_PT2104, WifiDirectName: Thali Test (Galaxy S5), WifiDirect Address: ee:1f:72:18:8b:78, peerId: B0:C5:59:3F:75:69
,D/        ( 2177): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:18320
,I/jxcore-log( 3823): 2015-12-04T08:49:59.250Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3823): 
,D/btif_config_util( 2177): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3823): 2015-12-04T08:49:59.358Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3823): 
,D/        ( 2177): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:7430
,I/jxcore-log( 3823): 2015-12-04T08:49:59.787Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3823): 
,W/bt-btif ( 2177): info:x10
,D/        ( 2177): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
E/BluetoothRemoteDevices( 2177): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 2177): tBTM_SEC_DEV:0xa2f16eb4 rs_disc_pending=1
,W/bt-btif ( 2177): bta_dm_check_av:0
W/bt-btif ( 2177): btif_dm_cback : unhandled event (14)
,V/GoogleAuthProtoRequest( 3945): [433] a.<init>: mAccountName set to: thalitester@gmail.com
,D/HeadsetStateMachine( 2177): Disconnected process message: 10, size: 0
,I/jxcore-log( 3823): 2015-12-04T08:50:00.437Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3823): 
,I/GLSUser ( 1492): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1492): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1492): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1492): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1492): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3945): [433] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3945): [433] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3945): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3945): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3945): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3945): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3945): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3945): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3945): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3945): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3945): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3945): 	at com.a.a.k.run(SourceFile:110)
,I/jxcore-log( 3823): 2015-12-04T08:50:00.556Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3823): 
,E/bt-btm  ( 2177): tBTM_SEC_DEV:0xa2f1707c rs_disc_pending=0,
W/bt-btif ( 2177): bta_dm_check_av:0
W/bt-btif ( 2177): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3823): 2015-12-04T08:50:01.068Z SendDataConnector.js: CLIENT is data received : 70000,
I/jxcore-log( 3823): 
,E/bt-btm  ( 2177): tBTM_SEC_DEV:0xa2f16eb4 rs_disc_pending=0
W/bt-btif ( 2177): bta_dm_check_av:0,
W/bt-btif ( 2177): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3823): 2015-12-04T08:50:01.759Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:50:01.988Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3823): 
,D/btif_config_util( 2177): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/btif_config( 2177): btif_get_device_type: Device [00:f4:6f:30:e0:6c] type 1
,I/BluetoothBondStateMachine( 2177): bondStateChangeCallback: Status: 0 Address: 00:F4:6F:30:E0:6C newState: 1
,E/bt-btif ( 2177): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2177): Bond State Change Intent:00:F4:6F:30:E0:6C OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 2177): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2177): bondStateChangeCallback: Status: 0 Address: 00:F4:6F:30:E0:6C newState: 0
D/BluetoothAdapterProperties( 2177): Failed to remove device: 00:F4:6F:30:E0:6C
,I/BluetoothBondStateMachine( 2177): Bond State Change Intent:00:F4:6F:30:E0:6C OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2177): StableState(): Entering Off State
,W/bt-btif ( 2177): new conn_srvc id:26, app_id:255,
W/bt-btif ( 2177): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2177): bta_dm_pm_ssr:2, lat:1200
I/BTListenerThread( 3823): we got incoming connection,
I/BTHandshakeSocketThread( 3823): Creating BTHandshakeSocketThread
I/BTListenerThread( 3823): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3823): BTHandshakeSocketThread started,
,I/BTListenerThread( 3823): got MESSAGE_READ 82 bytes.
,I/BTListenerThread( 3823): Got JSON from encryption:{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT5039"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTListenerThread( 3823): MESSAGE_WRITE 82 bytes.
,I/HS      ( 3823): Incoming connection Hand Shake finished for : samsung-SM-G800F_PT5039
,I/BtConnectorHelper( 3823): Starting the connected thread incoming : true, samsung-SM-G800F_PT5039
,I/BtToSocketBase( 3823): BtToSocketBase BtConnectedRequestSocket
I/BTHandshakeSocketThread( 3823): BTHandshakeSocketThread fully stopped
I/BtToRequestSocket( 3823): Creating BTConnectedThread
I/BtConnectorHelper( 3823): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3823): --DoOneRunRound started
,I/BtToRequestSocket( 3823): LocalHost address: localhost/127.0.0.1, port: 48599
,I/BtToRequestSocket( 3823): --DoOneRunRound ended
,I/jxcore-log( 3823): 2015-12-04T08:50:05.076Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3823): 
,E/bt-btm  ( 2177): tBTM_SEC_DEV:0xa2f16eb4 rs_disc_pending=1
,W/bt-btif ( 2177): bta_dm_check_av:0
W/bt-btif ( 2177): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2177): tBTM_SEC_DEV:0xa2f1707c rs_disc_pending=1
,W/bt-btif ( 2177): bta_dm_check_av:0
W/bt-btif ( 2177): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3823): 2015-12-04T08:50:06.245Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
,I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:50:06.281Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data,
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:50:06.286Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data,
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:50:06.491Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data,
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:50:06.590Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3823): ,
,I/jxcore-log( 3823): 2015-12-04T08:50:06.622Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 3823): 
,E/bt-btm  ( 2177): tBTM_SEC_DEV:0xa2f16eb4 rs_disc_pending=0
,W/bt-btif ( 2177): bta_dm_check_av:0
W/bt-btif ( 2177): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3823): 2015-12-04T08:50:06.952Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 3823): 
,W/bt-btif ( 2177): dm_pm_timer expires
W/bt-btif ( 2177): dm_pm_timer expires 0
W/bt-btif ( 2177): proc dm_pm_timer expires
,D/btif_config_util( 2177): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3823): 2015-12-04T08:50:07.270Z SendDataTCPServer.js: TCP/IP server has received 14132 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:50:07.325Z SendDataTCPServer.js: TCP/IP server has received 16112 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:50:07.436Z SendDataTCPServer.js: TCP/IP server has received 18092 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:50:07.444Z SendDataTCPServer.js: TCP/IP server has received 20072 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:50:07.492Z SendDataTCPServer.js: TCP/IP server has received 22052 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:50:07.549Z SendDataTCPServer.js: TCP/IP server has received 24032 bytes of data
I/jxcore-log( 3823): ,
,I/jxcore-log( 3823): 2015-12-04T08:50:07.574Z SendDataTCPServer.js: TCP/IP server has received 26012 bytes of data
I/jxcore-log( 3823): 
,I/        ( 3823): Cleared service requests
,I/jxcore-log( 3823): 2015-12-04T08:50:07.600Z SendDataTCPServer.js: TCP/IP server has received 27992 bytes of data
I/jxcore-log( 3823): 
I/        ( 3823): Started peer discovery
,I/jxcore-log( 3823): 2015-12-04T08:50:07.604Z SendDataTCPServer.js: TCP/IP server has received 29972 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:50:07.907Z SendDataTCPServer.js: TCP/IP server has received 31952 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:50:07.933Z SendDataTCPServer.js: TCP/IP server has received 32768 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:50:08.048Z SendDataTCPServer.js: TCP/IP server has received 34748 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:50:08.081Z SendDataTCPServer.js: TCP/IP server has received 36728 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:50:08.222Z SendDataTCPServer.js: TCP/IP server has received 38708 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:50:08.445Z SendDataTCPServer.js: TCP/IP server has received 40688 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:50:08.475Z SendDataTCPServer.js: TCP/IP server has received 42668 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:50:08.510Z SendDataTCPServer.js: TCP/IP server has received 44648 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:50:08.553Z SendDataTCPServer.js: TCP/IP server has received 46628 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:50:08.556Z SendDataTCPServer.js: TCP/IP server has received 48608 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:50:08.662Z SendDataTCPServer.js: TCP/IP server has received 50588 bytes of data,
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:50:08.786Z SendDataTCPServer.js: TCP/IP server has received 52568 bytes of data,
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:50:08.892Z SendDataTCPServer.js: TCP/IP server has received 54548 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:50:08.937Z SendDataTCPServer.js: TCP/IP server has received 56528 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:50:08.977Z SendDataTCPServer.js: TCP/IP server has received 58508 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:50:09.033Z SendDataTCPServer.js: TCP/IP server has received 60488 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:50:09.039Z SendDataTCPServer.js: TCP/IP server has received 62468 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:50:09.099Z SendDataTCPServer.js: TCP/IP server has received 64448 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:50:09.142Z SendDataTCPServer.js: TCP/IP server has received 66428 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:50:09.147Z SendDataTCPServer.js: TCP/IP server has received 68408 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:50:09.263Z SendDataTCPServer.js: TCP/IP server has received 70388 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:50:09.320Z SendDataTCPServer.js: TCP/IP server has received 72368 bytes of data,
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:50:09.364Z SendDataTCPServer.js: TCP/IP server has received 74348 bytes of data,
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:50:09.371Z SendDataTCPServer.js: TCP/IP server has received 76328 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:50:09.426Z SendDataTCPServer.js: TCP/IP server has received 78308 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:50:09.489Z SendDataTCPServer.js: TCP/IP server has received 80288 bytes of data
I/jxcore-log( 3823): 
,I/wpa_supplicant( 1236): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/jxcore-log( 3823): 2015-12-04T08:50:09.496Z SendDataTCPServer.js: TCP/IP server has received 82268 bytes of data
I/jxcore-log( 3823): 
,I/SS      ( 3823): Found 6 peers.
,I/SS      ( 3823): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3823): Peer(2): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/SS      ( 3823): Peer(3): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3823): Peer(4): Android_8ae2 52:55:27:f0:fd:0b
I/SS      ( 3823): Peer(5): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3823): Peer(6): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3823): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3823): Added service request
,I/jxcore-log( 3823): 2015-12-04T08:50:09.745Z SendDataTCPServer.js: TCP/IP server has received 84248 bytes of data
,I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:50:09.797Z SendDataTCPServer.js: TCP/IP server has received 86228 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:50:09.803Z SendDataTCPServer.js: TCP/IP server has received 88208 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:50:09.851Z SendDataTCPServer.js: TCP/IP server has received 90188 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:50:09.903Z SendDataTCPServer.js: TCP/IP server has received 92168 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:50:09.940Z SendDataTCPServer.js: TCP/IP server has received 94148 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:50:09.994Z SendDataTCPServer.js: TCP/IP server has received 96128 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:50:10.077Z SendDataTCPServer.js: TCP/IP server has received 98108 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:50:10.081Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3823): 
,I/wpa_supplicant( 1236): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/        ( 3823): Started service discovery
,I/jxcore-log( 3823): 2015-12-04T08:50:11.989Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:50:11.990Z SendDataConnector.js: CLIENT closeClientSocket,
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:50:11.996Z SendDataConnector.js: CLIENT closeClientSocket
,I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T08:50:11.997Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3823): ,
,I/jxcore-log( 3823): 2015-12-04T08:50:11.998Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3823): 
,I/BtToSocketBase( 3823): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3823): Disconnect outgoing peer: LGE-Nexus 5_PT6585
I/BtToSocketBase( 3823): Stop ReceivingThread
I/BtToSocketBase( 3823): Stop SendingThread
,I/BtToSocketBase( 3823): Close local in
I/BtToSocketBase( 3823): Close LocalOutputStream
I/BtToSocketBase( 3823): Close localHostSocket
I/BtToSocketBase( 3823): Close bt in
,I/BtToSocketBase( 3823): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtToSocketBase( 3823): Close bt out
I/BtToSocketBase( 3823): Close bt socket
I/BtToRequestSocket( 3823): Close server socket
,I/wpa_supplicant( 1236): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1236): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3823): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT5230","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT5230","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT5230, peerAddress: F8:95:C7:87:85:54
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT5230, WifiDirectName: G3s-1, WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,I/BooksSync( 3710): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3710): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1492): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1492): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1492): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1492): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1492): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1492): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1492): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1492): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1492): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1492): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/BooksAccountManager( 3710): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication,
,E/BooksSync( 3710): Soft error
E/BooksSync( 3710): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication,
E/BooksSync( 3710): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3710): Sync error
E/BooksSync( 3710): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication,
E/BooksSync( 3710): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3710): Finished books sync
,D/HeadsetStateMachine( 2177): Disconnected process message: 10, size: 0
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 439907, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,E/bt-btm  ( 2177): tBTM_SEC_DEV:0xa2f16eb4 rs_disc_pending=1
W/bt-btif ( 2177): bta_dm_check_av:0
W/bt-btif ( 2177): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2177): bta_jv_rfc_port_to_cb(port_handle:0x8):jv handle:0x0 not FOUND
,E/bt-btm  ( 2177): tBTM_SEC_DEV:0xa2f1707c rs_disc_pending=0
W/bt-btif ( 2177): bta_dm_check_av:0
W/bt-btif ( 2177): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3823): 2015-12-04T08:50:17.002Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:50:17.003Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3823): 
,E/bt-btm  ( 2177): btm_sec_disconnected - Clearing Pending flag,
,D/BluetoothMapService( 2177): onReceive,
,D/BluetoothManagerService(  820): Message: 20
D/BluetoothManagerService(  820): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2eeeed23:true
,I/BTConnectionReceiver( 1523): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:B1:66, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1523): Bluetooth Device Name: Nexus 5
,I/BtToSocketBase( 3823): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
W/bt-btif ( 2177): invalid rfc slot id: 4
,I/BtConnectorHelper( 3823): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3823): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G800F_PT5039
I/BtToSocketBase( 3823): Stop ReceivingThread
I/BtToSocketBase( 3823): Stop SendingThread
I/BtToSocketBase( 3823): Close local in,
I/BtToSocketBase( 3823): Close LocalOutputStream
I/BtToSocketBase( 3823): Close localHostSocket
I/BtToSocketBase( 3823): Close bt in
I/BtToSocketBase( 3823): Close bt out
I/BtToSocketBase( 3823): Close bt socket
I/BtToSocketBase( 3823): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtConnectorHelper( 3823): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3823): 2015-12-04T08:50:20.261Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3823): 
,I/        ( 3823): Cleared service requests
,I/        ( 3823): Started peer discovery
,W/bt-rfcomm( 2177): rfc_find_lcid_mcb LCID reused LCID:0x45 current:0x0
W/bt-rfcomm( 2177): RFCOMM_DisconnectInd LCID:0x45
,I/jxcore-log( 3823): 2015-12-04T08:50:22.010Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:50:22.010Z SendDataConnector.js: Connect (retry count 1) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T08:50:22.011Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:50:22.013Z SendDataConnector.js: do connect now
I/jxcore-log( 3823): 
,I/        ( 3823): Selected device address: 34:FC:EF:11:B1:66, name: Nexus 5
,I/        ( 3823): Connecting to Nexus 5, at 34:FC:EF:11:B1:66
,I/BTConnectToThread( 3823): Starting to connect
W/BluetoothAdapter( 3823): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2177): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,E/bt-btm  ( 2177): tBTM_SEC_DEV:0xa2f1707c rs_disc_pending=1
W/bt-btif ( 2177): bta_dm_check_av:0
W/bt-btif ( 2177): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2177): info:x10
,D/        ( 2177): remote version info [34:fc:ef:11:b1:66]: 6, f, 6109
,I/BTConnectionReceiver( 1523): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:B1:66, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1523): Bluetooth Device Name: Nexus 5
,E/bt-btm  ( 2177): tBTM_SEC_DEV:0xa2f16eb4 rs_disc_pending=1
W/bt-btif ( 2177): bta_dm_check_av:0
W/bt-btif ( 2177): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 2177): process_service_search_attr_rsp
,E/bt-btm  ( 2177): tBTM_SEC_DEV:0xa2f16eb4 rs_disc_pending=0
W/bt-btif ( 2177): bta_dm_check_av:0
,W/bt-btif ( 2177): btif_dm_cback : unhandled event (14),
,W/bt-btif ( 2177): new conn_srvc id:26, app_id:1
,W/bt-btif ( 2177): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2177): bta_dm_pm_ssr:2, lat:1200,
I/BTConnectToThread( 3823): Starting to Handshake
I/BTHandshakeSocketThread( 3823): Creating BTHandshakeSocketThread
I/BTConnectToThread( 3823): MESSAGE_WRITE 82 bytes.
,I/BTHandshakeSocketThread( 3823): BTHandshakeSocketThread started
,D/btif_config_util( 2177): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2177): btm_sec_disconnected - Clearing Pending flag,
,D/BluetoothMapService( 2177): onReceive
,I/BTConnectionReceiver( 1523): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1523): Bluetooth Device Name: S5mini-1,
,E/bt-btm  ( 2177): tBTM_SEC_DEV:0xa2f16eb4 rs_disc_pending=1
W/bt-btif ( 2177): bta_dm_check_av:0
W/bt-btif ( 2177): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 1236): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0,
,I/SS      ( 3823): Found 8 peers.
I/SS      ( 3823): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3823): Peer(2): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3823): Peer(3): G3s-1 a2:39:f7:70:12:80
,I/SS      ( 3823): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3823): Peer(5): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3823): Peer(6): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3823): Peer(7): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 3823): Peer(8): Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pManager( 3823): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3823): Added service request
,I/BTConnectToThread( 3823): got MESSAGE_READ 77 bytes.
,I/BTConnectToThread( 3823): Got JSON from encryption:{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT6585"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3823): HandshakeOk : LGE-Nexus 5_PT6585
I/HS      ( 3823): Hand Shake finished outgoing for : LGE-Nexus 5_PT6585
I/BTHandshakeSocketThread( 3823): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3823): Starting the connected thread incoming : false, LGE-Nexus 5_PT6585
I/BtToSocketBase( 3823): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3823): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3823): mHTTPPort  set to : 40282,
I/BtConnectorHelper( 3823): Request socket is using : 40282
I/BtToRequestSocket( 3823): Now accepting connections
,I/BtConnectorHelper( 3823): Calling ConnectionStatusUpdate with port :40282
,I/jxcore-log( 3823): 2015-12-04T08:50:26.953Z SendDataConnector.js: CLIENT connected to 40282, error: null
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:50:26.954Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3823): 
,I/BtToRequestSocket( 3823): incoming data from: /127.0.0.1, port: 40282
,I/BtToRequestSocket( 3823): Set local streams
I/BtToRequestSocket( 3823): rin ended ---------------------------;
,I/jxcore-log( 3823): 2015-12-04T08:50:26.970Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 3823): 
,I/        ( 3823): Started service discovery
,E/bt-btm  ( 2177): tBTM_SEC_DEV:0xa2f16eb4 rs_disc_pending=0
,W/bt-btif ( 2177): bta_dm_check_av:0
W/bt-btif ( 2177): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 1236): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1236): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1236): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/        ( 3823): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT4869"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT4869"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT4869, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT4869, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/        ( 3823): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5358"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5358"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT5358, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT5358, WifiDirectName: , WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,W/ProcessCpuTracker(  820): Skipping unknown process pid 4288
,I/        ( 3823): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT5230","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT5230","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT5230, peerAddress: F8:95:C7:87:85:54
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT5230, WifiDirectName: G3s-1, WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,W/bt-btif ( 2177): info:x10
,D/        ( 2177): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,I/BTConnectionReceiver( 1523): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1523): Bluetooth Device Name: S5mini-1
,E/bt-btm  ( 2177): tBTM_SEC_DEV:0xa2f16eb4 rs_disc_pending=1
,W/bt-btif ( 2177): bta_dm_check_av:0
W/bt-btif ( 2177): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2177): tBTM_SEC_DEV:0xa2f1707c rs_disc_pending=0
,W/bt-btif ( 2177): bta_dm_check_av:0
W/bt-btif ( 2177): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2177): dm_pm_timer expires
,W/bt-btif ( 2177): dm_pm_timer expires 0
W/bt-btif ( 2177): proc dm_pm_timer expires
,I/BTListenerThread( 3823): we got incoming connection,
I/BTHandshakeSocketThread( 3823): Creating BTHandshakeSocketThread
I/BTListenerThread( 3823): waiting to accept incoming Connection
,W/bt-btif ( 2177): new conn_srvc id:26, app_id:255
W/bt-btif ( 2177): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2177): bta_dm_pm_ssr:2, lat:1200
,I/BTHandshakeSocketThread( 3823): BTHandshakeSocketThread started
,E/bt-btm  ( 2177): tBTM_SEC_DEV:0xa2f1707c rs_disc_pending=1,
W/bt-btif ( 2177): bta_dm_check_av:0
W/bt-btif ( 2177): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2177): tBTM_SEC_DEV:0xa2f1707c rs_disc_pending=0
,W/bt-btif ( 2177): bta_dm_check_av:0
W/bt-btif ( 2177): btif_dm_cback : unhandled event (14)
,I/BTListenerThread( 3823): got MESSAGE_READ 82 bytes.
,I/BTListenerThread( 3823): Got JSON from encryption:{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT5039"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTListenerThread( 3823): MESSAGE_WRITE 82 bytes.
I/HS      ( 3823): Incoming connection Hand Shake finished for : samsung-SM-G800F_PT5039
,I/BTHandshakeSocketThread( 3823): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3823): Starting the connected thread incoming : true, samsung-SM-G800F_PT5039
I/BtToSocketBase( 3823): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3823): Creating BTConnectedThread
I/BtConnectorHelper( 3823): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3823): --DoOneRunRound started
,I/BtToRequestSocket( 3823): LocalHost address: localhost/127.0.0.1, port: 48599
,I/BtToRequestSocket( 3823): --DoOneRunRound ended
,I/jxcore-log( 3823): 2015-12-04T08:50:33.301Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:50:33.804Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:50:33.815Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:50:33.837Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:50:33.844Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:50:33.861Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 3823): 
,D/btif_config_util( 2177): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2177): tBTM_SEC_DEV:0xa2f16eb4 rs_disc_pending=0
,W/bt-btif ( 2177): bta_dm_check_av:0
W/bt-btif ( 2177): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3823): 2015-12-04T08:50:37.040Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:50:37.041Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T08:50:37.042Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T08:50:37.043Z SendDataConnector.js: tryAgain afer: 5000 ms.,
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T08:50:37.044Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3823): 
I/BtToSocketBase( 3823): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3823): Disconnect outgoing peer: LGE-Nexus 5_PT6585
,I/BtToSocketBase( 3823): Stop ReceivingThread
I/BtToSocketBase( 3823): Stop SendingThread
I/BtToSocketBase( 3823): Close local in
,I/BtToSocketBase( 3823): Close LocalOutputStream
I/BtToSocketBase( 3823): Close localHostSocket
I/BtToSocketBase( 3823): Close bt in
I/BtToSocketBase( 3823): Close bt out
I/BtToSocketBase( 3823): Close bt socket
I/BtToRequestSocket( 3823): Close server socket
I/BtToSocketBase( 3823): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,E/bt-btm  ( 2177): tBTM_SEC_DEV:0xa2f16eb4 rs_disc_pending=1
W/bt-btif ( 2177): bta_dm_check_av:0
W/bt-btif ( 2177): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2177): tBTM_SEC_DEV:0xa2f1707c rs_disc_pending=1
W/bt-btif ( 2177): bta_dm_check_av:0
W/bt-btif ( 2177): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2177): tBTM_SEC_DEV:0xa2f16eb4 rs_disc_pending=0
,W/bt-btif ( 2177): bta_dm_check_av:0
W/bt-btif ( 2177): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2177): bta_jv_rfc_port_to_cb(port_handle:0xa):jv handle:0x0 not FOUND
,I/        ( 3823): Cleared service requests
,I/        ( 3823): Started peer discovery
,E/bt-btm  ( 2177): tBTM_SEC_DEV:0xa2f1707c rs_disc_pending=0
W/bt-btif ( 2177): bta_dm_check_av:0
W/bt-btif ( 2177): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2177): btm_sec_disconnected - Clearing Pending flag,
,D/BluetoothMapService( 2177): onReceive
,I/BTConnectionReceiver( 1523): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:B1:66, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1523): Bluetooth Device Name: Nexus 5,
,I/jxcore-log( 3823): 2015-12-04T08:50:42.044Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:50:42.045Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3823): 
,W/bt-btif ( 2177): invalid rfc slot id: 6
,I/BtToSocketBase( 3823): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3823): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3823): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G800F_PT5039
,I/BtToSocketBase( 3823): Stop ReceivingThread
I/BtToSocketBase( 3823): Stop SendingThread
,I/BtToSocketBase( 3823): Close local in
I/BtToSocketBase( 3823): Close LocalOutputStream
I/BtToSocketBase( 3823): Close localHostSocket
I/BtToSocketBase( 3823): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3823): Close bt in
I/BtConnectorHelper( 3823): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3823): Close bt out
I/BtConnectorHelper( 3823): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G800F_PT5039
I/BtToSocketBase( 3823): Close bt socket
I/BtToSocketBase( 3823): Close bt in
,I/BtToSocketBase( 3823): Close bt out
I/BtToSocketBase( 3823): Close bt socket
,I/jxcore-log( 3823): 2015-12-04T08:50:44.628Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3823): 
,W/bt-rfcomm( 2177): rfc_find_lcid_mcb LCID reused LCID:0x49 current:0x0
W/bt-rfcomm( 2177): RFCOMM_DisconnectInd LCID:0x49
,I/jxcore-log( 3823): 2015-12-04T08:50:47.051Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T08:50:47.052Z SendDataConnector.js: Connect (retry count 2) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:50:47.053Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T08:50:47.054Z SendDataConnector.js: do connect now
I/jxcore-log( 3823): 
,I/        ( 3823): Selected device address: 34:FC:EF:11:B1:66, name: Nexus 5
,I/BTConnectToThread( 3823): Starting to connect
W/BluetoothAdapter( 3823): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3823): Connecting to Nexus 5, at 34:FC:EF:11:B1:66,
D/BTIF_SOCK( 2177): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,E/bt-btm  ( 2177): tBTM_SEC_DEV:0xa2f1707c rs_disc_pending=1
W/bt-btif ( 2177): bta_dm_check_av:0
,W/bt-btif ( 2177): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2177): info:x10
,D/        ( 2177): remote version info [34:fc:ef:11:b1:66]: 6, f, 6109
,I/BTConnectionReceiver( 1523): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:B1:66, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1523): Bluetooth Device Name: Nexus 5
,I/wpa_supplicant( 1236): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 3823): Found 10 peers.
I/SS      ( 3823): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3823): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3823): Peer(3): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3823): Peer(4): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3823): Peer(5): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3823): Peer(6): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3823): Peer(7): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3823): Peer(8): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3823): Peer(9): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 3823): Peer(10): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3823): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3823): Added service request
,E/bt-btm  ( 2177): tBTM_SEC_DEV:0xa2f16eb4 rs_disc_pending=1
W/bt-btif ( 2177): bta_dm_check_av:0
,W/bt-btif ( 2177): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 2177): process_service_search_attr_rsp
,E/bt-btif ( 2177): DISCOVERY_COMP_EVT slot id:9, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2177): invalid rfc slot id: 9,
I/BTConnectToThread( 3823): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3823): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3823): 2015-12-04T08:50:48.587Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:B1:66 failed,
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T08:50:48.587Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:50:48.590Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3823): 
,I/        ( 3823): Started service discovery
,E/bt-btm  ( 2177): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2177): onReceive,
,I/BTConnectionReceiver( 1523): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1523): Bluetooth Device Name: S5mini-1
,I/wpa_supplicant( 1236): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1236): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1,
,D/btif_config_util( 2177): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2177): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2177): onReceive
,I/        ( 3823): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT4869"}, typeCordovap2p._tcp.local.:
I/        ( 3823): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT4869"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT4869, peerAddress: 80:01:84:8A:B3:68
,I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT4869, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/BTConnectionReceiver( 1523): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:B1:66, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1523): Bluetooth Device Name: Nexus 5
,I/        ( 3823): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5358"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5358"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT5358, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT5358, WifiDirectName: , WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/jxcore-log( 3823): 2015-12-04T08:50:53.591Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:50:53.592Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3823): 
,W/bt-btif ( 2177): info:x10
D/        ( 2177): remote version info [00:f4:6f:30:e0:6c]: 6, f, 6109
,I/BTConnectionReceiver( 1523): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1523): Bluetooth Device Name: S5mini-1
,W/bt-btif ( 2177): new conn_srvc id:26, app_id:255
W/bt-btif ( 2177): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2177): bta_dm_pm_ssr:2, lat:1200
I/BTListenerThread( 3823): we got incoming connection
I/BTHandshakeSocketThread( 3823): Creating BTHandshakeSocketThread
I/BTListenerThread( 3823): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3823): BTHandshakeSocketThread started
,I/BTListenerThread( 3823): got MESSAGE_READ 82 bytes.
,I/BTListenerThread( 3823): Got JSON from encryption:{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT5039"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3823): MESSAGE_WRITE 82 bytes.
I/HS      ( 3823): Incoming connection Hand Shake finished for : samsung-SM-G800F_PT5039
I/BTHandshakeSocketThread( 3823): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3823): Starting the connected thread incoming : true, samsung-SM-G800F_PT5039
,I/BtToSocketBase( 3823): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3823): Creating BTConnectedThread
I/BtConnectorHelper( 3823): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3823): --DoOneRunRound started
,I/BtToRequestSocket( 3823): LocalHost address: localhost/127.0.0.1, port: 48599
,I/BtToRequestSocket( 3823): --DoOneRunRound ended
,I/jxcore-log( 3823): 2015-12-04T08:50:56.952Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3823): 
,I/wpa_supplicant( 1236): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
,I/wpa_supplicant( 1236): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:fd:0b
,I/jxcore-log( 3823): 2015-12-04T08:50:57.364Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:50:57.394Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:50:57.400Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:50:57.404Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:50:57.408Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:50:58.596Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T08:50:58.597Z SendDataConnector.js: Connect (retry count 3) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:50:58.597Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T08:50:58.598Z SendDataConnector.js: do connect now
I/jxcore-log( 3823): 
,I/        ( 3823): Selected device address: 34:FC:EF:11:B1:66, name: Nexus 5
,I/BTConnectToThread( 3823): Starting to connect
W/BluetoothAdapter( 3823): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3823): Connecting to Nexus 5, at 34:FC:EF:11:B1:66
,D/BTIF_SOCK( 2177): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,D/btif_config_util( 2177): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2177): tBTM_SEC_DEV:0xa2f1707c rs_disc_pending=1,
W/bt-btif ( 2177): bta_dm_check_av:0
W/bt-btif ( 2177): btif_dm_cback : unhandled event (14)
,D/HeadsetStateMachine( 2177): Disconnected process message: 10, size: 0
,W/bt-btif ( 2177): info:x10
,D/        ( 2177): remote version info [34:fc:ef:11:b1:66]: 6, f, 410d
,I/BTConnectionReceiver( 1523): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:B1:66, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1523): Bluetooth Device Name: Nexus 5
,I/        ( 3823): Cleared service requests
,I/        ( 3823): Started peer discovery
,W/bt-sdp  ( 2177): process_service_search_attr_rsp
,D/btif_config_util( 2177): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 1236): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3823): Found 8 peers.
I/SS      ( 3823): Peer(1): S5-1 ee:1f:72:63:11:86
,I/SS      ( 3823): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3823): Peer(3): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3823): Peer(4): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3823): Peer(5): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3823): Peer(6): Thali Test's G2 36:fc:ef:de:0a:e2
,I/SS      ( 3823): Peer(7): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3823): Peer(8): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiP2pManager( 3823): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3823): Added service request
,W/bt-btif ( 2177): dm_pm_timer expires
W/bt-btif ( 2177): dm_pm_timer expires 0
W/bt-btif ( 2177): proc dm_pm_timer expires
,I/wpa_supplicant( 1236): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3823): Started service discovery
,I/wpa_supplicant( 1236): P2P-DEVICE-FOUND 3a:94:96:b5:06:dd p2p_dev_addr=3a:94:96:b5:06:dd pri_dev_type=10-0050F204-5 name='Galaxy S5-2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1236): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1236): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3823): Found Service, :{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT8320"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT8320"} -- peerIdentifier:38:94:96:B5:06:DC, peerName: samsung-SM-G800H_PT8320, peerAddress: 38:94:96:B5:06:DC
,I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : 38:94:96:B5:06:DC, Name: samsung-SM-G800H_PT8320, WifiDirectName: Galaxy S5-2, WifiDirect Address: 3a:94:96:b5:06:dd, peerId: 38:94:96:B5:06:DC
,I/        ( 3823): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT5039"}, typeCordovap2p._tcp.local.:
I/        ( 3823): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT5039"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT5039, peerAddress: 00:F4:6F:30:E0:6C
,I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT5039, WifiDirectName: S5mini-1, WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,I/        ( 3823): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT4869"}, typeCordovap2p._tcp.local.:
I/        ( 3823): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT4869"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT4869, peerAddress: 80:01:84:8A:B3:68
,I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT4869, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,E/bt-btm  ( 2177): tBTM_SEC_DEV:0xa2f1707c rs_disc_pending=0
,W/bt-btif ( 2177): bta_dm_check_av:0
W/bt-btif ( 2177): btif_dm_cback : unhandled event (14)
,E/bt-btif ( 2177): bta_dm_pm_btm_status  hci_status=35
,I/        ( 3823): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5358"}, typeCordovap2p._tcp.local.:
I/        ( 3823): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5358"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT5358, peerAddress: F4:F1:E1:5C:3B:E2
,I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT5358, WifiDirectName: , WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,W/bt-btif ( 2177): invalid rfc slot id: 8,
,I/BtToSocketBase( 3823): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3823): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3823): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G800F_PT5039
I/BtToSocketBase( 3823): Stop ReceivingThread
I/BtToSocketBase( 3823): Stop SendingThread
,I/BtToSocketBase( 3823): Close local in
I/BtToSocketBase( 3823): Close LocalOutputStream
I/BtToSocketBase( 3823): Close localHostSocket
,I/BtToSocketBase( 3823): Close bt in
I/BtToSocketBase( 3823): Close bt out
I/BtToSocketBase( 3823): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3823): Close bt socket
I/BtConnectorHelper( 3823): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3823): 2015-12-04T08:51:10.071Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3823): 
I/        ( 3823): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT5230","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
I/        ( 3823): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT5230","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT5230, peerAddress: F8:95:C7:87:85:54
,I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT5230, WifiDirectName: G3s-1, WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,I/        ( 3823): Found Service, :{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2104","ra":"B0:C5:59:3F:75:69"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2104","ra":"B0:C5:59:3F:75:69"} -- peerIdentifier:B0:C5:59:3F:75:69, peerName: samsung-SM-G900F_PT2104, peerAddress: B0:C5:59:3F:75:69
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : B0:C5:59:3F:75:69, Name: samsung-SM-G900F_PT2104, WifiDirectName: Thali Test (Galaxy S5), WifiDirect Address: ee:1f:72:18:8b:78, peerId: B0:C5:59:3F:75:69
,I/        ( 3823): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT3722"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT3722"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT3722, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT3722, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,E/bt-btm  ( 2177): tBTM_SEC_DEV:0xa2f16eb4 rs_disc_pending=1
,W/bt-rfcomm( 2177): PORT_StartCnf failed result:5
E/bt-btm  ( 2177): btm_sec_disconnected - Clearing Pending flag
,W/bt-btif ( 2177): bta_dm_check_av:0
W/bt-btif ( 2177): btif_dm_cback : unhandled event (14)
I/BTConnectToThread( 3823): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
W/bt-btif ( 2177): invalid rfc slot id: 11
I/CONNEC  ( 3823): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3823): 2015-12-04T08:51:11.830Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T08:51:11.831Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T08:51:11.832Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3823): 
,D/BluetoothMapService( 2177): onReceive
,I/BTConnectionReceiver( 1523): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:B1:66, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1523): Bluetooth Device Name: Nexus 5
,E/bt-btm  ( 2177): tBTM_SEC_DEV:0xa2f1707c rs_disc_pending=1
W/bt-btif ( 2177): bta_dm_check_av:0
W/bt-btif ( 2177): btif_dm_cback : unhandled event (14)
,V/KeepSync( 3727): Connecting to GoogleApiClient
,I/GLSUser ( 1492): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1492): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1492): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1492): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1492): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1492): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1492): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1492): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1492): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1492): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3215): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3215): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3215): 	at jdm.a(PG:82)
E/HttpOperation( 3215): 	at jcs.o(PG:406)
E/HttpOperation( 3215): 	at jcn.a(PG:1379)
E/HttpOperation( 3215): 	at jcs.i(PG:143)
E/HttpOperation( 3215): 	at blb.a(PG:3937)
E/HttpOperation( 3215): 	at czp.a(PG:18188)
E/HttpOperation( 3215): 	at czp.a(PG:9081)
E/HttpOperation( 3215): 	at czq.run(PG:1686)
E/HttpOperation( 3215): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3215): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3215): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3215): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3215): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3215): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3215): 	at jdj.a(PG:4091)
E/HttpOperation( 3215): 	at jdj.a(PG:1125)
E/HttpOperation( 3215): 	at jdm.a(PG:77)
E/HttpOperation( 3215): 	... 12 more
E/HttpOperation( 3215): Caused by: faj: BadAuthentication
E/HttpOperation( 3215): 	at fal.a(PG:38)
E/HttpOperation( 3215): 	at jdj.a(PG:4089)
E/HttpOperation( 3215): 	... 14 more
E/ClientConnectionOperation( 1822): Handling authorization failure
E/ClientConnectionOperation( 1822): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1822): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1822): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1822): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1822): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1822): 	... 7 more
,V/KeepSync( 3727): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3727): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3727): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3727): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1492): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1492): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1492): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1492): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1492): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/art     ( 1492): Explicit concurrent mark sweep GC freed 47456(2MB) AllocSpace objects, 18(1984KB) LOS objects, 37% free, 27MB/43MB, paused 2.642ms total 41.475ms
,D/HeadsetStateMachine( 2177): Disconnected process message: 10, size: 0
,E/HttpOperation( 3215): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3215): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3215): 	at jdm.a(PG:82)
E/HttpOperation( 3215): 	at jcs.o(PG:406)
E/HttpOperation( 3215): 	at jcn.a(PG:1379)
E/HttpOperation( 3215): 	at jcs.i(PG:143)
E/HttpOperation( 3215): 	at hec.a(PG:42)
E/HttpOperation( 3215): 	at hee.a(PG:102)
E/HttpOperation( 3215): 	at czr.a(PG:65)
E/HttpOperation( 3215): 	at kka.a(PG:108)
E/HttpOperation( 3215): 	at czp.a(PG:19176)
E/HttpOperation( 3215): 	at czp.a(PG:9081)
E/HttpOperation( 3215): 	at czq.run(PG:1686)
E/HttpOperation( 3215): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3215): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3215): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3215): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3215): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3215): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3215): 	at jdj.a(PG:4091)
E/HttpOperation( 3215): 	at jdj.a(PG:1125)
E/HttpOperation( 3215): 	at jdm.a(PG:77)
E/HttpOperation( 3215): 	... 15 more
E/HttpOperation( 3215): Caused by: faj: BadAuthentication
E/HttpOperation( 3215): 	at fal.a(PG:38)
E/HttpOperation( 3215): 	at jdj.a(PG:4089)
E/HttpOperation( 3215): 	... 17 more
E/ExperimentLoader( 3215): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3215): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3215): 	at jdm.a(PG:82)
E/ExperimentLoader( 3215): 	at jcs.o(PG:406)
E/ExperimentLoader( 3215): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3215): 	at jcs.i(PG:143)
E/ExperimentLoader( 3215): 	at hec.a(PG:42)
E/ExperimentLoader( 3215): 	at hee.a(PG:102)
E/ExperimentLoader( 3215): 	at czr.a(PG:65)
E/ExperimentLoader( 3215): 	at kka.a(PG:108)
E/ExperimentLoader( 3215): 	at czp.a(PG:19176)
E/ExperimentLoader( 3215): 	at czp.a(PG:9081)
E/ExperimentLoader( 3215): 	at czq.run(PG:1686)
E/ExperimentLoader( 3215): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3215): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3215): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3215): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3215): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3215): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3215): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3215): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3215): 	at jdm.a(PG:77)
E/ExperimentLoader( 3215): 	... 15 more
E/ExperimentLoader( 3215): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3215): 	at fal.a(PG:38)
E/ExperimentLoader( 3215): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3215): 	... 17 more
,I/GLSUser ( 1492): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1492): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1492): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1492): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1492): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/KeepSync( 3727): IOException
,E/KeepSync( 3727): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3727): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3727): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3727): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3727): 	,at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3727): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3727): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3727): 	,at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3727): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3727): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
,E/KeepSync( 3727): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3727): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3727): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3727): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3727): 	,at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3727): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3727): 	... 10 more
W/KeepSync( 3727): Sync result 2
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 472565, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 471078, reason: 10074, SyncResult: stats [ numIoExceptions: 1],
,E/bt-btm  ( 2177): tBTM_SEC_DEV:0xa2f1707c rs_disc_pending=0,
,W/bt-btif ( 2177): bta_dm_check_av:0
W/bt-btif ( 2177): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2177): btm_sec_disconnected - Clearing Pending flag,
,D/BluetoothMapService( 2177): onReceive,
,I/BTConnectionReceiver( 1523): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1523): Bluetooth Device Name: S5mini-1
,I/jxcore-log( 3823): 2015-12-04T08:51:16.833Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:51:16.834Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3823): 
,W/bt-btif ( 2177): info:x10
,D/        ( 2177): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,I/BTConnectionReceiver( 1523): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1523): Bluetooth Device Name: S5mini-1
,W/bt-btif ( 2177): new conn_srvc id:26, app_id:255
,W/bt-btif ( 2177): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 2177): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3823): we got incoming connection
I/BTHandshakeSocketThread( 3823): Creating BTHandshakeSocketThread
I/BTListenerThread( 3823): waiting to accept incoming Connection
I/BTHandshakeSocketThread( 3823): BTHandshakeSocketThread started
,I/BTListenerThread( 3823): got MESSAGE_READ 82 bytes.
,I/BTListenerThread( 3823): Got JSON from encryption:{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT5039"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTListenerThread( 3823): MESSAGE_WRITE 82 bytes.
I/HS      ( 3823): Incoming connection Hand Shake finished for : samsung-SM-G800F_PT5039
I/BTHandshakeSocketThread( 3823): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3823): Starting the connected thread incoming : true, samsung-SM-G800F_PT5039
,I/BtToSocketBase( 3823): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3823): Creating BTConnectedThread
I/BtConnectorHelper( 3823): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3823): --DoOneRunRound started
,I/jxcore-log( 3823): 2015-12-04T08:51:19.058Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3823): 
I/BtToRequestSocket( 3823): LocalHost address: localhost/127.0.0.1, port: 48599
,I/BtToRequestSocket( 3823): --DoOneRunRound ended
,I/jxcore-log( 3823): 2015-12-04T08:51:19.515Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:51:19.566Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:51:19.646Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:51:19.690Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:51:19.770Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 3823): 
,I/        ( 3823): Cleared service requests
,I/        ( 3823): Started peer discovery
,D/btif_config_util( 2177): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3823): 2015-12-04T08:51:21.839Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66,
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T08:51:21.839Z SendDataConnector.js: Connect (retry count 4) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T08:51:21.840Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T08:51:21.841Z SendDataConnector.js: do connect now
I/jxcore-log( 3823): 
,I/        ( 3823): Selected device address: 34:FC:EF:11:B1:66, name: Nexus 5
,I/BTConnectToThread( 3823): Starting to connect
,W/BluetoothAdapter( 3823): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3823): Connecting to Nexus 5, at 34:FC:EF:11:B1:66
,D/BTIF_SOCK( 2177): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae,
,I/wpa_supplicant( 1236): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3823): Found 10 peers.
I/SS      ( 3823): Peer(1): S5-1 ee:1f:72:63:11:86
,I/SS      ( 3823): Peer(2): Galaxy S5-2 3a:94:96:b5:06:dd
I/SS      ( 3823): Peer(3): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3823): Peer(4): A5-1 7e:f9:0e:37:96:ac
,I/SS      ( 3823): Peer(5): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3823): Peer(6): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3823): Peer(7): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3823): Peer(8): G4-1 a2:39:f7:6f:c9:5d
,I/SS      ( 3823): Peer(9): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3823): Peer(10): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiP2pManager( 3823): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3823): Added service request
,E/bt-btm  ( 2177): tBTM_SEC_DEV:0xa2f1707c rs_disc_pending=1
,W/bt-btif ( 2177): bta_dm_check_av:0
W/bt-btif ( 2177): btif_dm_cback : unhandled event (14)
,I/        ( 3823): Started service discovery
,W/bt-btif ( 2177): info:x10
,D/        ( 2177): remote version info [34:fc:ef:11:b1:66]: 6, f, 6109,
,I/BTConnectionReceiver( 1523): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:B1:66, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1523): Bluetooth Device Name: Nexus 5
,E/bt-btm  ( 2177): tBTM_SEC_DEV:0xa2f16eb4 rs_disc_pending=1
W/bt-btif ( 2177): bta_dm_check_av:0
,W/bt-btif ( 2177): btif_dm_cback : unhandled event (14),
,W/bt-sdp  ( 2177): process_service_search_attr_rsp
,E/bt-btm  ( 2177): tBTM_SEC_DEV:0xa2f16eb4 rs_disc_pending=0,
W/bt-btif ( 2177): bta_dm_check_av:0
W/bt-btif ( 2177): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2177): new conn_srvc id:26, app_id:1
,W/bt-btif ( 2177): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2177): bta_dm_pm_ssr:2, lat:1200
I/BTConnectToThread( 3823): Starting to Handshake
I/BTHandshakeSocketThread( 3823): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3823): MESSAGE_WRITE 82 bytes.,
I/BTHandshakeSocketThread( 3823): BTHandshakeSocketThread started
,E/bt-btm  ( 2177): tBTM_SEC_DEV:0xa2f16eb4 rs_disc_pending=1
,W/bt-btif ( 2177): bta_dm_check_av:0
W/bt-btif ( 2177): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 1236): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
,I/BTConnectToThread( 3823): got MESSAGE_READ 77 bytes.
,I/BTConnectToThread( 3823): Got JSON from encryption:{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT6585"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3823): HandshakeOk : LGE-Nexus 5_PT6585
,I/HS      ( 3823): Hand Shake finished outgoing for : LGE-Nexus 5_PT6585
I/BTHandshakeSocketThread( 3823): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3823): Starting the connected thread incoming : false, LGE-Nexus 5_PT6585
I/BtToSocketBase( 3823): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3823): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3823): mHTTPPort  set to : 35508
I/BtConnectorHelper( 3823): Request socket is using : 35508
,I/BtToRequestSocket( 3823): Now accepting connections
,I/BtConnectorHelper( 3823): Calling ConnectionStatusUpdate with port :35508,
I/jxcore-log( 3823): 2015-12-04T08:51:27.594Z SendDataConnector.js: CLIENT connected to 35508, error: null
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T08:51:27.595Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3823): 
,I/BtToRequestSocket( 3823): incoming data from: /127.0.0.1, port: 35508,
,I/BtToRequestSocket( 3823): Set local streams
I/BtToRequestSocket( 3823): rin ended ---------------------------;
,I/jxcore-log( 3823): 2015-12-04T08:51:27.611Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 3823): 
,D/btif_config_util( 2177): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2177): tBTM_SEC_DEV:0xa2f16eb4 rs_disc_pending=0
W/bt-btif ( 2177): bta_dm_check_av:0
W/bt-btif ( 2177): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2177): tBTM_SEC_DEV:0xa2f1707c rs_disc_pending=0
,W/bt-btif ( 2177): bta_dm_check_av:0
W/bt-btif ( 2177): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2177): invalid rfc slot id: 10
,I/BtToSocketBase( 3823): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3823): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3823): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G800F_PT5039
I/BtToSocketBase( 3823): Stop ReceivingThread
I/BtToSocketBase( 3823): Stop SendingThread,
I/BtToSocketBase( 3823): Close local in
I/BtToSocketBase( 3823): Close LocalOutputStream
I/BtToSocketBase( 3823): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtConnectorHelper( 3823): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3823): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G800F_PT5039
I/BtToSocketBase( 3823): Close bt in,
I/BtToSocketBase( 3823): Close bt out
I/BtToSocketBase( 3823): Close bt socket
I/BtToSocketBase( 3823): Close localHostSocket
,I/BtToSocketBase( 3823): Close bt in
I/BtToSocketBase( 3823): Close bt out
,I/BtToSocketBase( 3823): Close bt socket,
I/jxcore-log( 3823): 2015-12-04T08:51:30.901Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3823): 
,E/bt-btm  ( 2177): tBTM_SEC_DEV:0xa2f1707c rs_disc_pending=1,
W/bt-btif ( 2177): bta_dm_check_av:0
W/bt-btif ( 2177): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2177): tBTM_SEC_DEV:0xa2f16eb4 rs_disc_pending=1
,W/bt-btif ( 2177): bta_dm_check_av:0
W/bt-btif ( 2177): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2177): dm_pm_timer expires
,W/bt-btif ( 2177): dm_pm_timer expires 0
W/bt-btif ( 2177): proc dm_pm_timer expires
,E/bt-btm  ( 2177): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2177): onReceive
,I/BTConnectionReceiver( 1523): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524],
,I/BluetoothClassifier( 1523): Bluetooth Device Name: S5mini-1
,E/bt-btm  ( 2177): tBTM_SEC_DEV:0xa2f16eb4 rs_disc_pending=0
,W/bt-btif ( 2177): bta_dm_check_av:0
W/bt-btif ( 2177): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3823): 2015-12-04T08:51:37.676Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:51:37.677Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:51:37.679Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T08:51:37.686Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:51:37.686Z SendDataConnector.js: Stop data retrieving timer
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:51:37.687Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3823): 
,I/BtConnectorHelper( 3823): Disconnect outgoing peer: 34:FC:EF:11:B1:66
,I/BtToSocketBase( 3823): Stop ReceivingThread
I/BtToSocketBase( 3823): Stop SendingThread
I/BtToSocketBase( 3823): Close local in
I/BtToSocketBase( 3823): Close LocalOutputStream
,I/BtToSocketBase( 3823): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3823): Close localHostSocket,
I/BtToSocketBase( 3823): Close bt in
I/BtToSocketBase( 3823): Close bt out,
I/BtToSocketBase( 3823): Close bt socket
,I/BtToRequestSocket( 3823): Close server socket
I/BtToSocketBase( 3823): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/jxcore-log( 3823): 2015-12-04T08:51:37.695Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3823): 
I/jxcore-log( 3823): ---- round done--------
I/jxcore-log( 3823): 
I/jxcore-log( 3823): ---- gotta redo : 34:FC:EF:11:B1:66, try count now: 1
I/jxcore-log( 3823): 
I/jxcore-log( 3823): do fake peer & start
I/jxcore-log( 3823): 
I/jxcore-log( 3823): Connect to fake peer: F8:95:C7:87:85:54
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T08:51:37.701Z SendDataConnector.js: Start called with peer F8:95:C7:87:85:54
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T08:51:37.702Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T08:51:37.702Z SendDataConnector.js: do connect now
I/jxcore-log( 3823): 
,I/        ( 3823): Selected device address: F8:95:C7:87:85:54, name: null
I/BTConnectToThread( 3823): Starting to connect
,W/BluetoothAdapter( 3823): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3823): Connecting to null, at F8:95:C7:87:85:54
I/jxcore-log( 3823): 2015-12-04T08:51:37.713Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3823): 
I/chromium( 3823): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 34:FC:EF:11:B1:66 done with result: DATA-TIMEOUT", source: file:///android_asset/www/js/thali_main.js (63)
D/BTIF_SOCK( 2177): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-btif ( 2177): bta_jv_rfc_port_to_cb(port_handle:0xf):jv handle:0x0 not FOUND
,E/bt-btm  ( 2177): tBTM_SEC_DEV:0xa2f16eb4 rs_disc_pending=1
W/bt-btif ( 2177): bta_dm_check_av:0
W/bt-btif ( 2177): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2177): tBTM_SEC_DEV:0xa2f16eb4 rs_disc_pending=0
,W/bt-btif ( 2177): bta_dm_check_av:0
W/bt-btif ( 2177): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2177): info:x10,
D/        ( 2177): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
E/BluetoothRemoteDevices( 2177): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 2177): tBTM_SEC_DEV:0xa2f16eb4 rs_disc_pending=1
,W/bt-btif ( 2177): bta_dm_check_av:0
W/bt-btif ( 2177): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 2177): process_service_search_attr_rsp
,E/bt-btm  ( 2177): tBTM_SEC_DEV:0xa2f17244 rs_disc_pending=1
,W/bt-btif ( 2177): bta_dm_check_av:0
W/bt-btif ( 2177): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2177): info:x10,
D/        ( 2177): remote version info [00:f4:6f:30:e0:6c]: 0, 0, 0
,I/BTConnectionReceiver( 1523): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1523): Bluetooth Device Name: S5mini-1
,W/bt-btif ( 2177): new conn_srvc id:26, app_id:255
W/bt-btif ( 2177): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2177): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3823): we got incoming connection
I/BTHandshakeSocketThread( 3823): Creating BTHandshakeSocketThread
I/BTListenerThread( 3823): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3823): BTHandshakeSocketThread started
,I/BTListenerThread( 3823): got MESSAGE_READ 82 bytes.
I/BTListenerThread( 3823): Got JSON from encryption:{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT5039"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3823): MESSAGE_WRITE 82 bytes.
I/HS      ( 3823): Incoming connection Hand Shake finished for : samsung-SM-G800F_PT5039
I/BTHandshakeSocketThread( 3823): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3823): Starting the connected thread incoming : true, samsung-SM-G800F_PT5039
I/BtToSocketBase( 3823): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3823): Creating BTConnectedThread
,I/BtConnectorHelper( 3823): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3823): --DoOneRunRound started
,I/BtToRequestSocket( 3823): LocalHost address: localhost/127.0.0.1, port: 48599,
I/BtToRequestSocket( 3823): --DoOneRunRound ended
,I/jxcore-log( 3823): 2015-12-04T08:51:41.809Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3823): 
,D/btif_config( 2177): btif_get_device_type: Device [f8:95:c7:87:85:54] type 1
,I/BluetoothBondStateMachine( 2177): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 1
,E/bt-btif ( 2177): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2177): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2177): Entering PendingCommandState State
E/bt-btm  ( 2177): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2177): onReceive
,I/BTConnectionReceiver( 1523): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:B1:66, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1523): Bluetooth Device Name: Nexus 5
,I/jxcore-log( 3823): 2015-12-04T08:51:42.273Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:51:42.284Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:51:42.296Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:51:42.300Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:51:42.306Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:51:42.313Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 3823): 
,I/BluetoothBondStateMachine( 2177): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 0
D/BluetoothAdapterProperties( 2177): Failed to remove device: F8:95:C7:87:85:54
,I/BluetoothBondStateMachine( 2177): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2177): StableState(): Entering Off State
,E/bt-btm  ( 2177): tBTM_SEC_DEV:0xa2f17244 rs_disc_pending=0
,W/bt-btif ( 2177): bta_dm_check_av:0
W/bt-btif ( 2177): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2177): new conn_srvc id:26, app_id:1
W/bt-btif ( 2177): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2177): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3823): Starting to Handshake,
I/BTHandshakeSocketThread( 3823): Creating BTHandshakeSocketThread
I/BTConnectToThread( 3823): MESSAGE_WRITE 82 bytes.
,I/BTHandshakeSocketThread( 3823): BTHandshakeSocketThread started
,E/bt-btm  ( 2177): tBTM_SEC_DEV:0xa2f17244 rs_disc_pending=1
W/bt-btif ( 2177): bta_dm_check_av:0
,W/bt-btif ( 2177): btif_dm_cback : unhandled event (14)
,I/BTConnectToThread( 3823): got MESSAGE_READ 77 bytes.
I/BTConnectToThread( 3823): Got JSON from encryption:{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT5230","ra":"F8:95:C7:87:85:54"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTConnectToThread( 3823): HandshakeOk : LGE-LG-D722_PT5230
I/HS      ( 3823): Hand Shake finished outgoing for : LGE-LG-D722_PT5230
I/BTHandshakeSocketThread( 3823): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3823): Starting the connected thread incoming : false, LGE-LG-D722_PT5230
,I/BtToSocketBase( 3823): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3823): Creating BtConnectedRequestSocket
I/BtToRequestSocket( 3823): mHTTPPort  set to : 45075
,I/BtConnectorHelper( 3823): Request socket is using : 45075
,I/BtToRequestSocket( 3823): Now accepting connections
,I/BtConnectorHelper( 3823): Calling ConnectionStatusUpdate with port :45075
,I/jxcore-log( 3823): 2015-12-04T08:51:44.425Z SendDataConnector.js: CLIENT connected to 45075, error: null
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T08:51:44.426Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3823): 
,I/BtToRequestSocket( 3823): incoming data from: /127.0.0.1, port: 45075
,I/BtToRequestSocket( 3823): Set local streams
,I/jxcore-log( 3823): 2015-12-04T08:51:44.438Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3823): 
,I/BtToRequestSocket( 3823): rin ended ---------------------------;
,I/jxcore-log( 3823): 2015-12-04T08:51:44.969Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:51:44.976Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:51:45.099Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:51:45.191Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:51:45.244Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:51:45.294Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:51:45.356Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:51:45.391Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3823): 
,D/btif_config_util( 2177): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3823): 2015-12-04T08:51:45.561Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3823): 
,E/bt-btm  ( 2177): tBTM_SEC_DEV:0xa2f17244 rs_disc_pending=0
,W/bt-btif ( 2177): bta_dm_check_av:0
W/bt-btif ( 2177): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2177): dm_pm_timer expires
W/bt-btif ( 2177): dm_pm_timer expires 1
W/bt-btif ( 2177): proc dm_pm_timer expires
,E/bt-btm  ( 2177): tBTM_SEC_DEV:0xa2f1707c rs_disc_pending=0
,W/bt-btif ( 2177): bta_dm_check_av:0
W/bt-btif ( 2177): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2177): invalid rfc slot id: 12
,I/BtToSocketBase( 3823): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3823): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3823): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G800F_PT5039
I/BtToSocketBase( 3823): Stop ReceivingThread
I/BtToSocketBase( 3823): Stop SendingThread
,I/BtToSocketBase( 3823): Close local in
I/BtToSocketBase( 3823): Close LocalOutputStream
I/BtToSocketBase( 3823): Close localHostSocket
I/BtToSocketBase( 3823): Close bt in
I/BtToSocketBase( 3823): Close bt out
,I/BtToSocketBase( 3823): Close bt socket
I/BtToSocketBase( 3823): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3823): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/jxcore-log( 3823): 2015-12-04T08:51:53.358Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3823): 
,E/bt-btm  ( 2177): tBTM_SEC_DEV:0xa2f1707c rs_disc_pending=1
,W/bt-btif ( 2177): bta_dm_check_av:0
W/bt-btif ( 2177): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 2177): rfc_find_lcid_mcb LCID reused LCID:0x46 current:0x0
,W/bt-rfcomm( 2177): RFCOMM_DisconnectInd LCID:0x46
,E/bt-btm  ( 2177): tBTM_SEC_DEV:0xa2f17244 rs_disc_pending=1
W/bt-btif ( 2177): bta_dm_check_av:0
,W/bt-btif ( 2177): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2177): tBTM_SEC_DEV:0xa2f1707c rs_disc_pending=0
,W/bt-btif ( 2177): bta_dm_check_av:0
W/bt-btif ( 2177): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3823): 2015-12-04T08:51:55.562Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:51:55.563Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:51:55.564Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T08:51:55.565Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T08:51:55.566Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3823): 
I/BtToSocketBase( 3823): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3823): Disconnect outgoing peer: LGE-LG-D722_PT5230
I/BtToSocketBase( 3823): Stop ReceivingThread
I/BtToSocketBase( 3823): Stop SendingThread
I/BtToSocketBase( 3823): Close local in
,I/BtToSocketBase( 3823): Close LocalOutputStream
I/BtToSocketBase( 3823): Close localHostSocket
I/BtToSocketBase( 3823): Close bt in
I/BtToSocketBase( 3823): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtToSocketBase( 3823): Close bt out
I/BtToSocketBase( 3823): Close bt socket
,I/BtToRequestSocket( 3823): Close server socket
,E/bt-btm  ( 2177): tBTM_SEC_DEV:0xa2f17244 rs_disc_pending=0
,W/bt-btif ( 2177): bta_dm_check_av:0
W/bt-btif ( 2177): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2177): bta_jv_rfc_port_to_cb(port_handle:0x10):jv handle:0x0 not FOUND
,E/bt-btm  ( 2177): tBTM_SEC_DEV:0xa2f1707c rs_disc_pending=1
,W/bt-btif ( 2177): bta_dm_check_av:0
W/bt-btif ( 2177): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 1236): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
I/wpa_supplicant( 1236): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 1236): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,E/bt-btm  ( 2177): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2177): onReceive
,I/BTConnectionReceiver( 1523): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1523): Bluetooth Device Name: S5mini-1
,E/bt-btm  ( 2177): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2177): onReceive
,I/BTConnectionReceiver( 1523): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1523): Bluetooth Device Name: G3s-1
,I/jxcore-log( 3823): 2015-12-04T08:52:00.566Z SendDataConnector.js: re-try now : F8:95:C7:87:85:54
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T08:52:00.566Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:85:54
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:52:05.572Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:52:05.573Z SendDataConnector.js: Connect (retry count 1) to peer F8:95:C7:87:85:54 with availability status: true
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:52:05.573Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:52:05.574Z SendDataConnector.js: do connect now
I/jxcore-log( 3823): 
,I/        ( 3823): Selected device address: F8:95:C7:87:85:54, name: G3s-1
,I/        ( 3823): Connecting to G3s-1, at F8:95:C7:87:85:54
,I/BTConnectToThread( 3823): Starting to connect
,W/BluetoothAdapter( 3823): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2177): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-btif ( 2177): info:x10
D/        ( 2177): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,I/BTConnectionReceiver( 1523): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1523): Bluetooth Device Name: G3s-1
,W/bt-sdp  ( 2177): process_service_search_attr_rsp
,D/btif_config( 2177): btif_get_device_type: Device [f8:95:c7:87:85:54] type 1
,I/BluetoothBondStateMachine( 2177): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 1
,E/bt-btif ( 2177): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2177): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 10 NewState: 11,
I/BluetoothBondStateMachine( 2177): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2177): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 0
D/BluetoothAdapterProperties( 2177): Failed to remove device: F8:95:C7:87:85:54
,I/BluetoothBondStateMachine( 2177): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2177): StableState(): Entering Off State
,W/bt-btif ( 2177): new conn_srvc id:26, app_id:1
,W/bt-btif ( 2177): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2177): bta_dm_pm_ssr:2, lat:1200
I/BTConnectToThread( 3823): Starting to Handshake
I/BTHandshakeSocketThread( 3823): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3823): MESSAGE_WRITE 82 bytes.
I/BTHandshakeSocketThread( 3823): BTHandshakeSocketThread started
,I/BTConnectToThread( 3823): got MESSAGE_READ 77 bytes.
,I/BTConnectToThread( 3823): Got JSON from encryption:{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT5230","ra":"F8:95:C7:87:85:54"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3823): HandshakeOk : LGE-LG-D722_PT5230
I/HS      ( 3823): Hand Shake finished outgoing for : LGE-LG-D722_PT5230
I/BTHandshakeSocketThread( 3823): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3823): Starting the connected thread incoming : false, LGE-LG-D722_PT5230,
I/BtToSocketBase( 3823): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3823): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3823): mHTTPPort  set to : 54925
I/BtConnectorHelper( 3823): Request socket is using : 54925
,I/BtToRequestSocket( 3823): Now accepting connections
,I/BtConnectorHelper( 3823): Calling ConnectionStatusUpdate with port :54925
,I/jxcore-log( 3823): 2015-12-04T08:52:09.337Z SendDataConnector.js: CLIENT connected to 54925, error: null
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:52:09.338Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:52:09.349Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 3823): 
,I/BtToRequestSocket( 3823): incoming data from: /127.0.0.1, port: 54925
I/BtToRequestSocket( 3823): Set local streams
,I/BtToRequestSocket( 3823): rin ended ---------------------------;
,D/btif_config_util( 2177): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/HeadsetStateMachine( 2177): Disconnected process message: 10, size: 0
,W/bt-btif ( 2177): dm_pm_timer expires,
W/bt-btif ( 2177): dm_pm_timer expires 0
W/bt-btif ( 2177): proc dm_pm_timer expires
,I/jxcore-log( 3823): 2015-12-04T08:52:19.425Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:52:19.426Z SendDataConnector.js: CLIENT closeClientSocket,
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T08:52:19.427Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:52:19.428Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T08:52:19.429Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3823): 
I/BtToSocketBase( 3823): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3823): Disconnect outgoing peer: LGE-LG-D722_PT5230
I/BtToSocketBase( 3823): Stop ReceivingThread
I/BtToSocketBase( 3823): Stop SendingThread
,I/BtToSocketBase( 3823): Close local in
I/BtToSocketBase( 3823): Close LocalOutputStream
I/BtToSocketBase( 3823): Close localHostSocket
I/BtToSocketBase( 3823): Close bt in
I/BtToSocketBase( 3823): Close bt out
I/BtToSocketBase( 3823): Close bt socket
I/BtToRequestSocket( 3823): Close server socket
I/BtToSocketBase( 3823): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,W/bt-btif ( 2177): bta_jv_rfc_port_to_cb(port_handle:0x12):jv handle:0x0 not FOUND
,I/        ( 3823): Cleared service requests
,I/        ( 3823): Started peer discovery
,E/bt-btm  ( 2177): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2177): onReceive,
,I/BTConnectionReceiver( 1523): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1523): Bluetooth Device Name: G3s-1
,I/jxcore-log( 3823): 2015-12-04T08:52:24.429Z SendDataConnector.js: re-try now : F8:95:C7:87:85:54
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T08:52:24.430Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:85:54
I/jxcore-log( 3823): 
,I/wpa_supplicant( 1236): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1236): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3823): Found 6 peers.
,I/SS      ( 3823): Peer(1): Galaxy S5-2 3a:94:96:b5:06:dd
I/SS      ( 3823): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3823): Peer(3): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3823): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3823): Peer(5): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3823): Peer(6): Thali Test's G2 36:fc:ef:de:0a:e2
,D/WifiP2pManager( 3823): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3823): Added service request
,I/wpa_supplicant( 1236): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3823): Started service discovery
,I/wpa_supplicant( 1236): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1236): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3823): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1124","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
I/        ( 3823): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1124","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT1124, peerAddress: F8:95:C7:87:3C:51
,I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT1124, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/wpa_supplicant( 1236): P2P-DEVICE-LOST p2p_dev_addr=3a:94:96:b5:06:dd
I/wpa_supplicant( 1236): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
I/wpa_supplicant( 1236): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
,I/        ( 3823): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT8263","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT8263","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT8263, peerAddress: 08:EC:A9:50:75:41
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT8263, WifiDirectName: , WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,I/        ( 3823): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT4869"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT4869"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT4869, peerAddress: 80:01:84:8A:B3:68
,I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT4869, WifiDirectName: , WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/        ( 3823): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5092","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5092","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT5092, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT5092, WifiDirectName: , WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/jxcore-log( 3823): 2015-12-04T08:52:29.433Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:52:29.434Z SendDataConnector.js: Connect (retry count 2) to peer F8:95:C7:87:85:54 with availability status: true
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T08:52:29.435Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:52:29.435Z SendDataConnector.js: do connect now
I/jxcore-log( 3823): 
,I/        ( 3823): Selected device address: F8:95:C7:87:85:54, name: G3s-1
,I/BTConnectToThread( 3823): Starting to connect
W/BluetoothAdapter( 3823): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3823): Connecting to G3s-1, at F8:95:C7:87:85:54
,D/BTIF_SOCK( 2177): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-btif ( 2177): info:x10
,D/        ( 2177): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,I/BTConnectionReceiver( 1523): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1523): Bluetooth Device Name: G3s-1
,W/bt-sdp  ( 2177): process_service_search_attr_rsp
,D/btif_config( 2177): btif_get_device_type: Device [f8:95:c7:87:85:54] type 1
,I/BluetoothBondStateMachine( 2177): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 1
E/bt-btif ( 2177): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2177): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2177): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2177): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 0
D/BluetoothAdapterProperties( 2177): Failed to remove device: F8:95:C7:87:85:54
,I/BluetoothBondStateMachine( 2177): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2177): StableState(): Entering Off State
,W/bt-btif ( 2177): new conn_srvc id:26, app_id:1
,W/bt-btif ( 2177): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 2177): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3823): Starting to Handshake,
,I/BTHandshakeSocketThread( 3823): Creating BTHandshakeSocketThread
I/BTConnectToThread( 3823): MESSAGE_WRITE 82 bytes.
I/BTHandshakeSocketThread( 3823): BTHandshakeSocketThread started
,I/BTConnectToThread( 3823): got MESSAGE_READ 77 bytes.
,I/BTConnectToThread( 3823): Got JSON from encryption:{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT5230","ra":"F8:95:C7:87:85:54"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3823): HandshakeOk : LGE-LG-D722_PT5230
I/HS      ( 3823): Hand Shake finished outgoing for : LGE-LG-D722_PT5230
,I/BTHandshakeSocketThread( 3823): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3823): Starting the connected thread incoming : false, LGE-LG-D722_PT5230
I/BtToSocketBase( 3823): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3823): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3823): mHTTPPort  set to : 49866
,I/BtConnectorHelper( 3823): Request socket is using : 49866
I/BtToRequestSocket( 3823): Now accepting connections
,I/BtConnectorHelper( 3823): Calling ConnectionStatusUpdate with port :49866
,I/jxcore-log( 3823): 2015-12-04T08:52:30.879Z SendDataConnector.js: CLIENT connected to 49866, error: null
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:52:30.880Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3823): 
,I/BtToRequestSocket( 3823): incoming data from: /127.0.0.1, port: 49866
I/BtToRequestSocket( 3823): Set local streams
,I/BtToRequestSocket( 3823): rin ended ---------------------------;
,I/jxcore-log( 3823): 2015-12-04T08:52:30.890Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 3823): 
,W/bt-btif ( 2177): dm_pm_timer expires,
W/bt-btif ( 2177): dm_pm_timer expires 0
,W/bt-btif ( 2177): proc dm_pm_timer expires
,D/btif_config_util( 2177): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 3823): Cleared service requests
,I/        ( 3823): Started peer discovery
,I/wpa_supplicant( 1236): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3823): Found 5 peers.
,I/SS      ( 3823): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3823): Peer(2): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3823): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3823): Peer(4): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3823): Peer(5): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3823): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3823): Added service request
,I/        ( 3823): Started service discovery
,I/jxcore-log( 3823): 2015-12-04T08:52:40.948Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:52:40.949Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T08:52:40.954Z SendDataConnector.js: CLIENT closeClientSocket,
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T08:52:40.955Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T08:52:40.956Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3823): 
I/BtToSocketBase( 3823): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3823): Disconnect outgoing peer: LGE-LG-D722_PT5230
I/BtToSocketBase( 3823): Stop ReceivingThread
I/BtToSocketBase( 3823): Stop SendingThread
I/BtToSocketBase( 3823): Close local in
I/BtToSocketBase( 3823): Close LocalOutputStream
I/BtToSocketBase( 3823): Close localHostSocket
I/BtToSocketBase( 3823): Close bt in
I/BtToSocketBase( 3823): Close bt out
I/BtToSocketBase( 3823): Close bt socket
I/BtToRequestSocket( 3823): Close server socket
,I/BtToSocketBase( 3823): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/wpa_supplicant( 1236): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant( 1236): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3823): Found Service, :{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT6585"}, typeCordovap2p._tcp.local.:
I/        ( 3823): JsonLine: {"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT6585"} -- peerIdentifier:34:FC:EF:11:B1:66, peerName: LGE-Nexus 5_PT6585, peerAddress: 34:FC:EF:11:B1:66
,I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : 34:FC:EF:11:B1:66, Name: LGE-Nexus 5_PT6585, WifiDirectName: Android_2dc2, WifiDirect Address: 52:55:27:f0:ff:f0, peerId: 34:FC:EF:11:B1:66
,W/bt-btif ( 2177): bta_jv_rfc_port_to_cb(port_handle:0x13):jv handle:0x0 not FOUND
I/        ( 3823): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT6559"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT6559"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT6559, peerAddress: B4:CE:F6:AB:A4:6A
,I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT6559, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/        ( 3823): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT8263","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
I/        ( 3823): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT8263","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT8263, peerAddress: 08:EC:A9:50:75:41
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT8263, WifiDirectName: , WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,I/        ( 3823): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT4869"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT4869"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT4869, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT4869, WifiDirectName: , WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/        ( 3823): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5092","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 3823): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5092","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT5092, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT5092, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 3823): Found Service, :{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT2124","ra":"E0:DB:10:14:E2:C0"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT2124","ra":"E0:DB:10:14:E2:C0"} -- peerIdentifier:E0:DB:10:14:E2:C0, peerName: samsung-SM-N910C_PT2124, peerAddress: E0:DB:10:14:E2:C0
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : E0:DB:10:14:E2:C0, Name: samsung-SM-N910C_PT2124, WifiDirectName: , WifiDirect Address: 92:b6:86:43:73:1c, peerId: E0:DB:10:14:E2:C0
,I/        ( 3823): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT5039"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT5039"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT5039, peerAddress: 00:F4:6F:30:E0:6C
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT5039, WifiDirectName: S5mini-1, WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,I/        ( 3823): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT5230","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT5230","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT5230, peerAddress: F8:95:C7:87:85:54
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT5230, WifiDirectName: G3s-1, WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,I/jxcore-log( 3823): 2015-12-04T08:52:45.956Z SendDataConnector.js: re-try now : F8:95:C7:87:85:54
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:52:45.957Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:85:54
I/jxcore-log( 3823): 
,E/bt-btm  ( 2177): btm_sec_disconnected - Clearing Pending flag,
,D/BluetoothMapService( 2177): onReceive,
,I/BTConnectionReceiver( 1523): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524],
,I/BluetoothClassifier( 1523): Bluetooth Device Name: G3s-1,
,I/jxcore-log( 3823): 2015-12-04T08:52:50.960Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T08:52:50.961Z SendDataConnector.js: Connect (retry count 3) to peer F8:95:C7:87:85:54 with availability status: true
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:52:50.962Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T08:52:50.962Z SendDataConnector.js: do connect now
I/jxcore-log( 3823): 
,I/        ( 3823): Selected device address: F8:95:C7:87:85:54, name: G3s-1,
,I/BTConnectToThread( 3823): Starting to connect,
W/BluetoothAdapter( 3823): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3823): Connecting to G3s-1, at F8:95:C7:87:85:54,
D/BTIF_SOCK( 2177): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae,
,W/bt-btif ( 2177): info:x10,
D/        ( 2177): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,I/BTConnectionReceiver( 1523): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1523): Bluetooth Device Name: G3s-1
,W/bt-sdp  ( 2177): process_service_search_attr_rsp
,D/btif_config( 2177): btif_get_device_type: Device [f8:95:c7:87:85:54] type 1
,I/BluetoothBondStateMachine( 2177): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 1
,E/bt-btif ( 2177): check_cod: remote_cod = 0x5a020c
I/BluetoothBondStateMachine( 2177): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2177): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2177): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 0
D/BluetoothAdapterProperties( 2177): Failed to remove device: F8:95:C7:87:85:54
,I/BluetoothBondStateMachine( 2177): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2177): StableState(): Entering Off State
,W/bt-btif ( 2177): new conn_srvc id:26, app_id:1
,W/bt-btif ( 2177): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2177): bta_dm_pm_ssr:2, lat:1200
I/BTConnectToThread( 3823): Starting to Handshake
,I/BTHandshakeSocketThread( 3823): Creating BTHandshakeSocketThread
I/BTConnectToThread( 3823): MESSAGE_WRITE 82 bytes.
I/BTHandshakeSocketThread( 3823): BTHandshakeSocketThread started
,I/BTConnectToThread( 3823): got MESSAGE_READ 77 bytes.
,I/BTConnectToThread( 3823): Got JSON from encryption:{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT5230","ra":"F8:95:C7:87:85:54"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3823): HandshakeOk : LGE-LG-D722_PT5230
I/HS      ( 3823): Hand Shake finished outgoing for : LGE-LG-D722_PT5230
,I/BTHandshakeSocketThread( 3823): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3823): Starting the connected thread incoming : false, LGE-LG-D722_PT5230
I/BtToSocketBase( 3823): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3823): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3823): mHTTPPort  set to : 54354
I/BtConnectorHelper( 3823): Request socket is using : 54354
I/BtToRequestSocket( 3823): Now accepting connections
,I/BtConnectorHelper( 3823): Calling ConnectionStatusUpdate with port :54354
,I/jxcore-log( 3823): 2015-12-04T08:52:53.060Z SendDataConnector.js: CLIENT connected to 54354, error: null
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:52:53.061Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3823): 
,I/BtToRequestSocket( 3823): incoming data from: /127.0.0.1, port: 54354
,I/BtToRequestSocket( 3823): Set local streams
I/BtToRequestSocket( 3823): rin ended ---------------------------;
,I/jxcore-log( 3823): 2015-12-04T08:52:53.083Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 3823): 
,I/        ( 3823): Cleared service requests
,I/        ( 3823): Started peer discovery
,D/btif_config_util( 2177): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 2177): dm_pm_timer expires
W/bt-btif ( 2177): dm_pm_timer expires 0
W/bt-btif ( 2177): proc dm_pm_timer expires
,D/HeadsetStateMachine( 2177): Disconnected process message: 10, size: 0
,I/wpa_supplicant( 1236): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3823): Found 7 peers.
I/SS      ( 3823): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3823): Peer(2): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3823): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3823): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3823): Peer(5): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3823): Peer(6): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3823): Peer(7): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3823): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3823): Added service request
,I/wpa_supplicant( 1236): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3823): Started service discovery
,I/wpa_supplicant( 1236): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3823): Found Service, :{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2104","ra":"B0:C5:59:3F:75:69"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2104","ra":"B0:C5:59:3F:75:69"} -- peerIdentifier:B0:C5:59:3F:75:69, peerName: samsung-SM-G900F_PT2104, peerAddress: B0:C5:59:3F:75:69
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : B0:C5:59:3F:75:69, Name: samsung-SM-G900F_PT2104, WifiDirectName: , WifiDirect Address: ee:1f:72:18:8b:78, peerId: B0:C5:59:3F:75:69
,I/jxcore-log( 3823): 2015-12-04T08:53:03.138Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T08:53:03.139Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T08:53:03.140Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T08:53:03.141Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T08:53:03.142Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3823): 
I/BtToSocketBase( 3823): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3823): Disconnect outgoing peer: LGE-LG-D722_PT5230
,I/BtToSocketBase( 3823): Stop ReceivingThread
I/BtToSocketBase( 3823): Stop SendingThread
I/BtToSocketBase( 3823): Close local in
I/BtToSocketBase( 3823): Close LocalOutputStream
I/BtToSocketBase( 3823): Close localHostSocket
I/BtToSocketBase( 3823): Close bt in
I/BtToSocketBase( 3823): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtToSocketBase( 3823): Close bt out
I/BtToSocketBase( 3823): Close bt socket,
I/BtToRequestSocket( 3823): Close server socket
,W/bt-btif ( 2177): bta_jv_rfc_port_to_cb(port_handle:0x14):jv handle:0x0 not FOUND
,I/        ( 3823): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5358"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5358"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT5358, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT5358, WifiDirectName: , WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/        ( 3823): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT3722"}, typeCordovap2p._tcp.local.:,
I/        ( 3823): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT3722"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT3722, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT3722, WifiDirectName: , WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/        ( 3823): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT6559"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT6559"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT6559, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT6559, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,E/bt-btm  ( 2177): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2177): onReceive
,I/BTConnectionReceiver( 1523): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1523): Bluetooth Device Name: G3s-1
,I/        ( 3823): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT4869"}, typeCordovap2p._tcp.local.:,
I/        ( 3823): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT4869"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT4869, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT4869, WifiDirectName: , WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/        ( 3823): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5092","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:,
I/        ( 3823): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5092","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT5092, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT5092, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/jxcore-log( 3823): 2015-12-04T08:53:08.143Z SendDataConnector.js: re-try now : F8:95:C7:87:85:54
,I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T08:53:08.144Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:85:54
I/jxcore-log( 3823): 
,I/        ( 3823): Found Service, :{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT2124","ra":"E0:DB:10:14:E2:C0"}, typeCordovap2p._tcp.local.:
I/        ( 3823): JsonLine: {"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT2124","ra":"E0:DB:10:14:E2:C0"} -- peerIdentifier:E0:DB:10:14:E2:C0, peerName: samsung-SM-N910C_PT2124, peerAddress: E0:DB:10:14:E2:C0
,I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : E0:DB:10:14:E2:C0, Name: samsung-SM-N910C_PT2124, WifiDirectName: , WifiDirect Address: 92:b6:86:43:73:1c, peerId: E0:DB:10:14:E2:C0
,I/jxcore-log( 3823): 2015-12-04T08:53:13.147Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:53:13.147Z SendDataConnector.js: Connect (retry count 4) to peer F8:95:C7:87:85:54 with availability status: true
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T08:53:13.148Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T08:53:13.149Z SendDataConnector.js: do connect now
I/jxcore-log( 3823): 
,I/        ( 3823): Selected device address: F8:95:C7:87:85:54, name: G3s-1
,I/BTConnectToThread( 3823): Starting to connect
,W/BluetoothAdapter( 3823): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3823): Connecting to G3s-1, at F8:95:C7:87:85:54
,D/BTIF_SOCK( 2177): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,I/art     (  820): Explicit concurrent mark sweep GC freed 46173(2MB) AllocSpace objects, 8(505KB) LOS objects, 31% free, 34MB/50MB, paused 2.381ms total 103.168ms
,W/bt-btif ( 2177): info:x10
D/        ( 2177): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,I/BTConnectionReceiver( 1523): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1523): Bluetooth Device Name: G3s-1
,W/bt-sdp  ( 2177): process_service_search_attr_rsp
,D/btif_config( 2177): btif_get_device_type: Device [f8:95:c7:87:85:54] type 1
,I/BluetoothBondStateMachine( 2177): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 1
E/bt-btif ( 2177): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2177): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2177): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2177): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 0
,D/BluetoothAdapterProperties( 2177): Failed to remove device: F8:95:C7:87:85:54
,I/BluetoothBondStateMachine( 2177): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2177): StableState(): Entering Off State
,W/bt-btif ( 2177): new conn_srvc id:26, app_id:1
W/bt-btif ( 2177): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2177): bta_dm_pm_ssr:2, lat:1200
I/BTConnectToThread( 3823): Starting to Handshake
,I/BTHandshakeSocketThread( 3823): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3823): MESSAGE_WRITE 82 bytes.
I/BTHandshakeSocketThread( 3823): BTHandshakeSocketThread started
,I/BTConnectToThread( 3823): got MESSAGE_READ 77 bytes.
,I/BTConnectToThread( 3823): Got JSON from encryption:{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT5230","ra":"F8:95:C7:87:85:54"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTConnectToThread( 3823): HandshakeOk : LGE-LG-D722_PT5230
,I/HS      ( 3823): Hand Shake finished outgoing for : LGE-LG-D722_PT5230
I/BTHandshakeSocketThread( 3823): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3823): Starting the connected thread incoming : false, LGE-LG-D722_PT5230
I/BtToSocketBase( 3823): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3823): Creating BtConnectedRequestSocket
I/BtToRequestSocket( 3823): mHTTPPort  set to : 32897
I/BtConnectorHelper( 3823): Request socket is using : 32897
I/BtToRequestSocket( 3823): Now accepting connections
,I/        ( 3823): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT5230","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT5230","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT5230, peerAddress: F8:95:C7:87:85:54
,I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT5230, WifiDirectName: G3s-1, WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,I/BtConnectorHelper( 3823): Calling ConnectionStatusUpdate with port :32897
,I/jxcore-log( 3823): 2015-12-04T08:53:15.389Z SendDataConnector.js: CLIENT connected to 32897, error: null
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:53:15.390Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3823): 
,I/BtToRequestSocket( 3823): incoming data from: /127.0.0.1, port: 32897
,I/BtToRequestSocket( 3823): Set local streams
I/BtToRequestSocket( 3823): rin ended ---------------------------;
,I/jxcore-log( 3823): 2015-12-04T08:53:15.407Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 3823): 
,D/btif_config_util( 2177): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 2177): dm_pm_timer expires
,W/bt-btif ( 2177): dm_pm_timer expires 0
W/bt-btif ( 2177): proc dm_pm_timer expires
,I/        ( 3823): Cleared service requests
,I/        ( 3823): Started peer discovery
,I/jxcore-log( 3823): 2015-12-04T08:53:25.469Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T08:53:25.469Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T08:53:25.470Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:53:25.473Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T08:53:25.474Z SendDataConnector.js: Stop data retrieving timer
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T08:53:25.474Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3823): 
,I/BtConnectorHelper( 3823): Disconnect outgoing peer: F8:95:C7:87:85:54
,I/BtToSocketBase( 3823): Stop ReceivingThread
,I/BtToSocketBase( 3823): Stop SendingThread
I/BtToSocketBase( 3823): Close local in
I/BtToSocketBase( 3823): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3823): Close LocalOutputStream
I/BtToSocketBase( 3823): Close localHostSocket
I/BtToSocketBase( 3823): Close bt in
I/BtToSocketBase( 3823): Close bt out
I/BtToSocketBase( 3823): Close bt socket
I/BtToRequestSocket( 3823): Close server socket
I/BtToSocketBase( 3823): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/jxcore-log( 3823): 2015-12-04T08:53:25.481Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 3823): 
I/jxcore-log( 3823): ---- round done--------
I/jxcore-log( 3823): 
I/jxcore-log( 3823): ---- gotta redo : F8:95:C7:87:85:54, try count now: 1
I/jxcore-log( 3823): 
I/jxcore-log( 3823): do fake peer & start
I/jxcore-log( 3823): 
I/jxcore-log( 3823): Connect to fake peer: 80:01:84:8A:B3:68
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T08:53:25.483Z SendDataConnector.js: Start called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T08:53:25.483Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T08:53:25.484Z SendDataConnector.js: do connect now
I/jxcore-log( 3823): 
,I/        ( 3823): Selected device address: 80:01:84:8A:B3:68, name: null
,I/BTConnectToThread( 3823): Starting to connect
W/BluetoothAdapter( 3823): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3823): Connecting to null, at 80:01:84:8A:B3:68
D/BTIF_SOCK( 2177): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
I/jxcore-log( 3823): 2015-12-04T08:53:25.519Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3823): 
,I/chromium( 3823): [INFO:CONSOLE(63)] "logCallback Round of send data to peer F8:95:C7:87:85:54 done with result: DATA-TIMEOUT", source: file:///android_asset/www/js/thali_main.js (63)
,W/bt-btif ( 2177): bta_jv_rfc_port_to_cb(port_handle:0x15):jv handle:0x0 not FOUND
,E/bt-btm  ( 2177): tBTM_SEC_DEV:0xa2f17244 rs_disc_pending=1,
W/bt-btif ( 2177): bta_dm_check_av:0
W/bt-btif ( 2177): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 1236): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 1236): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
,I/SS      ( 3823): Found 5 peers.
,I/SS      ( 3823): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3823): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3823): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3823): Peer(4): Android_2dc2 52:55:27:f0:ff:f0
,I/SS      ( 3823): Peer(5): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3823): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3823): Added service request
,I/wpa_supplicant( 1236): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3823): Started service discovery
,E/bt-btm  ( 2177): tBTM_SEC_DEV:0xa2f17244 rs_disc_pending=0
,W/bt-btif ( 2177): bta_dm_check_av:0
W/bt-btif ( 2177): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 1236): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3823): Found Service, :{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2104","ra":"B0:C5:59:3F:75:69"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2104","ra":"B0:C5:59:3F:75:69"} -- peerIdentifier:B0:C5:59:3F:75:69, peerName: samsung-SM-G900F_PT2104, peerAddress: B0:C5:59:3F:75:69
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : B0:C5:59:3F:75:69, Name: samsung-SM-G900F_PT2104, WifiDirectName: , WifiDirect Address: ee:1f:72:18:8b:78, peerId: B0:C5:59:3F:75:69
,E/bt-btm  ( 2177): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2177): onReceive,
,I/BTConnectionReceiver( 1523): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1523): Bluetooth Device Name: G3s-1
,W/bt-btif ( 2177): info:x10
,D/        ( 2177): remote version info [80:01:84:8a:b3:68]: 7, 1d, 7d3
E/BluetoothRemoteDevices( 2177): aclStateChangeCallback: Device is NULL
,I/        ( 3823): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5358"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5358"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT5358, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT5358, WifiDirectName: , WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,W/bt-sdp  ( 2177): process_service_search_attr_rsp
,D/btif_config( 2177): btif_get_device_type: Device [80:01:84:8a:b3:68] type 1,
,I/BluetoothBondStateMachine( 2177): bondStateChangeCallback: Status: 0 Address: 80:01:84:8A:B3:68 newState: 1,
E/bt-btif ( 2177): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2177): Bond State Change Intent:80:01:84:8A:B3:68 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 2177): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2177): bondStateChangeCallback: Status: 0 Address: 80:01:84:8A:B3:68 newState: 0
,D/BluetoothAdapterProperties( 2177): Failed to remove device: 80:01:84:8A:B3:68
,I/BluetoothBondStateMachine( 2177): Bond State Change Intent:80:01:84:8A:B3:68 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2177): StableState(): Entering Off State
,W/bt-btif ( 2177): new conn_srvc id:26, app_id:1
W/bt-btif ( 2177): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2177): bta_dm_pm_ssr:2, lat:1200
I/BTConnectToThread( 3823): Starting to Handshake
I/BTHandshakeSocketThread( 3823): Creating BTHandshakeSocketThread
I/BTConnectToThread( 3823): MESSAGE_WRITE 82 bytes.
,I/BTHandshakeSocketThread( 3823): BTHandshakeSocketThread started
,I/BTConnectToThread( 3823): got MESSAGE_READ 84 bytes.
,I/BTConnectToThread( 3823): Got JSON from encryption:{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT4869"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3823): HandshakeOk : HTC-HTC Desire 820_PT4869
I/HS      ( 3823): Hand Shake finished outgoing for : HTC-HTC Desire 820_PT4869
I/BTHandshakeSocketThread( 3823): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3823): Starting the connected thread incoming : false, HTC-HTC Desire 820_PT4869
I/BtToSocketBase( 3823): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3823): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3823): mHTTPPort  set to : 40804
,I/BtConnectorHelper( 3823): Request socket is using : 40804
I/BtToRequestSocket( 3823): Now accepting connections
,I/BtConnectorHelper( 3823): Calling ConnectionStatusUpdate with port :40804
,I/jxcore-log( 3823): 2015-12-04T08:53:34.138Z SendDataConnector.js: CLIENT connected to 40804, error: null
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:53:34.139Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3823): 
,I/BtToRequestSocket( 3823): incoming data from: /127.0.0.1, port: 40804
,I/BtToRequestSocket( 3823): Set local streams
I/BtToRequestSocket( 3823): rin ended ---------------------------;
,I/jxcore-log( 3823): 2015-12-04T08:53:34.153Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:53:34.658Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:53:34.753Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:53:34.812Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:53:34.909Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:53:34.915Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:53:35.088Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:53:35.185Z SendDataConnector.js: CLIENT is data received : 70000,
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:53:35.191Z SendDataConnector.js: CLIENT is data received : 80000,
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:53:35.270Z SendDataConnector.js: CLIENT is data received : 90000,
I/jxcore-log( 3823): 
,D/btif_config_util( 2177): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 2177): dm_pm_timer expires
,W/bt-btif ( 2177): dm_pm_timer expires 0
W/bt-btif ( 2177): proc dm_pm_timer expires
,I/        ( 3823): Cleared service requests
I/        ( 3823): Started peer discovery
,I/wpa_supplicant( 1236): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3823): Found 6 peers.
,I/SS      ( 3823): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3823): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3823): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3823): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3823): Peer(5): Android_2dc2 52:55:27:f0:ff:f0
,I/SS      ( 3823): Peer(6): G4-1 a2:39:f7:6f:c9:5d
D/WifiP2pManager( 3823): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3823): Added service request
,I/jxcore-log( 3823): 2015-12-04T08:53:45.270Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:53:45.271Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T08:53:45.274Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T08:53:45.275Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T08:53:45.276Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3823): 
,I/BtToSocketBase( 3823): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3823): Disconnect outgoing peer: HTC-HTC Desire 820_PT4869
I/BtToSocketBase( 3823): Stop ReceivingThread
I/BtToSocketBase( 3823): Stop SendingThread
I/BtToSocketBase( 3823): Close local in
,I/BtToSocketBase( 3823): Close LocalOutputStream
I/BtToSocketBase( 3823): Close localHostSocket
I/BtToSocketBase( 3823): Close bt in
,I/BtToSocketBase( 3823): Close bt out
I/BtToSocketBase( 3823): Close bt socket
I/BtToSocketBase( 3823): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtToRequestSocket( 3823): Close server socket
,W/bt-btif ( 2177): bta_jv_rfc_port_to_cb(port_handle:0x16):jv handle:0x0 not FOUND
,I/wpa_supplicant( 1236): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3823): Started service discovery
,I/wpa_supplicant( 1236): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3823): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT4869"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT4869"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT4869, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT4869, WifiDirectName: , WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/        ( 3823): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5358"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5358"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT5358, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT5358, WifiDirectName: , WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/        ( 3823): Found Service, :{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT6585"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT6585"} -- peerIdentifier:34:FC:EF:11:B1:66, peerName: LGE-Nexus 5_PT6585, peerAddress: 34:FC:EF:11:B1:66
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : 34:FC:EF:11:B1:66, Name: LGE-Nexus 5_PT6585, WifiDirectName: Android_2dc2, WifiDirect Address: 52:55:27:f0:ff:f0, peerId: 34:FC:EF:11:B1:66
,I/        ( 3823): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT6559"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT6559"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT6559, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT6559, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/jxcore-log( 3823): 2015-12-04T08:53:50.276Z SendDataConnector.js: re-try now : 80:01:84:8A:B3:68
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:53:50.277Z SendDataConnector.js: ReStart called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3823): 
,E/bt-btm  ( 2177): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2177): onReceive
,I/BTConnectionReceiver( 1523): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1523): Bluetooth Device Name: HTC Desire 820
,I/        ( 3823): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT5039"}, typeCordovap2p._tcp.local.:
I/        ( 3823): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT5039"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT5039, peerAddress: 00:F4:6F:30:E0:6C
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT5039, WifiDirectName: S5mini-1, WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,I/jxcore-log( 3823): 2015-12-04T08:53:55.282Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T08:53:55.283Z SendDataConnector.js: Connect (retry count 1) to peer 80:01:84:8A:B3:68 with availability status: true
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T08:53:55.284Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T08:53:55.285Z SendDataConnector.js: do connect now
I/jxcore-log( 3823): 
,I/        ( 3823): Selected device address: 80:01:84:8A:B3:68, name: HTC Desire 820
,I/BTConnectToThread( 3823): Starting to connect
,W/BluetoothAdapter( 3823): getBluetoothService() called with no BluetoothManagerCallback
,I/wpa_supplicant( 1236): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
D/BTIF_SOCK( 2177): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,I/        ( 3823): Connecting to HTC Desire 820, at 80:01:84:8A:B3:68
,I/wpa_supplicant( 1236): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1236): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3823): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT8263","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT8263","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT8263, peerAddress: 08:EC:A9:50:75:41
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT8263, WifiDirectName: A3-1, WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,I/        ( 3823): Found Service, :{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT8320"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT8320"} -- peerIdentifier:38:94:96:B5:06:DC, peerName: samsung-SM-G800H_PT8320, peerAddress: 38:94:96:B5:06:DC
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : 38:94:96:B5:06:DC, Name: samsung-SM-G800H_PT8320, WifiDirectName: , WifiDirect Address: 3a:94:96:b5:06:dd, peerId: 38:94:96:B5:06:DC
,I/wpa_supplicant( 1236): P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6:ad:a4:6b
,V/GoogleAuthProtoRequest( 3945): [434] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1492): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1492): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1492): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1492): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1492): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3945): [434] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3945): [434] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3945): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3945): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3945): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3945): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3945): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3945): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3945): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3945): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3945): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3945): 	at com.a.a.k.run(SourceFile:110)
,I/        ( 3823): Cleared service requests
,I/        ( 3823): Started peer discovery
,I/wpa_supplicant( 1236): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3823): Found 7 peers.
,I/SS      ( 3823): Peer(1): S5-1 ee:1f:72:63:11:86
,I/SS      ( 3823): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3823): Peer(3): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3823): Peer(4): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3823): Peer(5): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 3823): Peer(6): A3-1 0a:ec:a9:50:75:42,
I/SS      ( 3823): Peer(7): G4-1 a2:39:f7:6f:c9:5d
D/WifiP2pManager( 3823): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3823): Added service request
,I/        ( 3823): Started service discovery,
,I/wpa_supplicant( 1236): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1236): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3823): Found Service, :{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT8320"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT8320"} -- peerIdentifier:38:94:96:B5:06:DC, peerName: samsung-SM-G800H_PT8320, peerAddress: 38:94:96:B5:06:DC
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : 38:94:96:B5:06:DC, Name: samsung-SM-G800H_PT8320, WifiDirectName: , WifiDirect Address: 3a:94:96:b5:06:dd, peerId: 38:94:96:B5:06:DC
,I/        ( 3823): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT7300","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
I/        ( 3823): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT7300","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT7300, peerAddress: 08:EC:A9:50:76:27
,I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT7300, WifiDirectName: , WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,I/        ( 3823): Cleared service requests
,I/        ( 3823): Started peer discovery
,W/bt-sdp  ( 2177): SDP - Rcvd conn cnf with error: 0xd  CID 0x44
,E/bt-btif ( 2177): DISCOVERY_COMP_EVT slot id:21, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2177): invalid rfc slot id: 21
I/BTConnectToThread( 3823): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3823): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3823): 2015-12-04T08:54:24.335Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:54:24.336Z SendDataConnector.js: CLIENT Can not Connect: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T08:54:24.337Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3823): 
,I/BooksSync( 3710): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3710): GmsCore Version = 7.8.99 (2134222-430)
,I/wpa_supplicant( 1236): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3823): Found 7 peers.
I/SS      ( 3823): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3823): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3823): Peer(3): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3823): Peer(4): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3823): Peer(5): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 3823): Peer(6): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3823): Peer(7): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3823): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3823): Added service request
,I/GLSUser ( 1492): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1492): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1492): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1492): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1492): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1492): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1492): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1492): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1492): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1492): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/BooksAccountManager( 3710): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3710): Soft error
E/BooksSync( 3710): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3710): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3710): Sync error
E/BooksSync( 3710): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication,
E/BooksSync( 3710): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3710): Finished books sync
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 692325, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/        ( 3823): Started service discovery
,W/bt-btif ( 2177): info:x10
,D/        ( 2177): remote version info [f4:f1:e1:5c:3b:e2]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 2177): aclStateChangeCallback: Device is NULL
,D/btif_config( 2177): btif_get_device_type: Device [f4:f1:e1:5c:3b:e2] type 1
,I/BluetoothBondStateMachine( 2177): bondStateChangeCallback: Status: 0 Address: F4:F1:E1:5C:3B:E2 newState: 1
,E/bt-btif ( 2177): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2177): Bond State Change Intent:F4:F1:E1:5C:3B:E2 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 2177): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2177): bondStateChangeCallback: Status: 0 Address: F4:F1:E1:5C:3B:E2 newState: 0
D/BluetoothAdapterProperties( 2177): Failed to remove device: F4:F1:E1:5C:3B:E2
,I/BluetoothBondStateMachine( 2177): Bond State Change Intent:F4:F1:E1:5C:3B:E2 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2177): StableState(): Entering Off State
,W/bt-btif ( 2177): new conn_srvc id:26, app_id:255
,W/bt-btif ( 2177): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2177): bta_dm_pm_ssr:2, lat:1200
I/BTListenerThread( 3823): we got incoming connection
I/BTHandshakeSocketThread( 3823): Creating BTHandshakeSocketThread
I/BTListenerThread( 3823): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3823): BTHandshakeSocketThread started
,I/BTListenerThread( 3823): got MESSAGE_READ 81 bytes.
I/BTListenerThread( 3823): Got JSON from encryption:{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5358"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������,
I/BTListenerThread( 3823): MESSAGE_WRITE 82 bytes.
I/HS      ( 3823): Incoming connection Hand Shake finished for : motorola-XT1039_PT5358
,I/BtConnectorHelper( 3823): Starting the connected thread incoming : true, motorola-XT1039_PT5358
I/BTHandshakeSocketThread( 3823): BTHandshakeSocketThread fully stopped
,I/BtToSocketBase( 3823): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3823): Creating BTConnectedThread
,I/BtConnectorHelper( 3823): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3823): --DoOneRunRound started
,I/BtToRequestSocket( 3823): LocalHost address: localhost/127.0.0.1, port: 48599
,I/BtToRequestSocket( 3823): --DoOneRunRound ended
I/jxcore-log( 3823): 2015-12-04T08:54:28.260Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:54:29.130Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:54:29.139Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data,
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:54:29.142Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:54:29.149Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:54:29.215Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:54:29.223Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:54:29.231Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:54:29.259Z SendDataTCPServer.js: TCP/IP server has received 14132 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:54:29.331Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data,
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:54:29.338Z SendDataConnector.js: re-try now : 80:01:84:8A:B3:68,
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T08:54:29.339Z SendDataConnector.js: ReStart called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:54:29.341Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:54:29.348Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:54:29.361Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:54:29.518Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:54:29.525Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 3823): ,
,I/jxcore-log( 3823): 2015-12-04T08:54:29.532Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:54:29.540Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:54:29.547Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data,
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:54:29.616Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data
I/jxcore-log( 3823): ,
,I/jxcore-log( 3823): 2015-12-04T08:54:29.642Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:54:29.649Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:54:29.690Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:54:29.739Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:54:29.745Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:54:29.752Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:54:29.811Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:54:29.850Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:54:29.857Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:54:29.922Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:54:29.929Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:54:29.936Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:54:29.971Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:54:30.037Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:54:30.048Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:54:30.061Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:54:30.099Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:54:30.104Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data,
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:54:30.107Z SendDataTCPServer.js: TCP/IP server has received 85684 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:54:30.140Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data,
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:54:30.149Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data,
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:54:30.154Z SendDataTCPServer.js: TCP/IP server has received 99544 bytes of data,
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:54:30.464Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data,
I/jxcore-log( 3823): 
,W/bt-btif ( 2177): invalid rfc slot id: 15,
I/BtToSocketBase( 3823): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3823): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1,
,I/BtConnectorHelper( 3823): Disconnect:::Stop : mBtToServerSocket :motorola-XT1039_PT5358
I/BtToSocketBase( 3823): Stop ReceivingThread
I/BtToSocketBase( 3823): Stop SendingThread
,I/BtToSocketBase( 3823): Close local in
I/BtToSocketBase( 3823): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3823): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3823): Disconnect:::Stop : mBtToServerSocket :motorola-XT1039_PT5358,
I/BtToSocketBase( 3823): Close LocalOutputStream
I/BtToSocketBase( 3823): Close localHostSocket
,I/BtToSocketBase( 3823): Close bt in
I/BtToSocketBase( 3823): Close bt out
I/BtToSocketBase( 3823): Close bt socket
I/BtToSocketBase( 3823): Close bt in
I/BtToSocketBase( 3823): Close bt out
I/BtToSocketBase( 3823): Close bt socket
I/jxcore-log( 3823): 2015-12-04T08:54:30.595Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3823): 
,W/bt-rfcomm( 2177): rfc_find_lcid_mcb LCID reused LCID:0x41 current:0x0
,W/bt-rfcomm( 2177): RFCOMM_DisconnectInd LCID:0x41
,D/btif_config_util( 2177): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3823): 2015-12-04T08:54:34.345Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:54:34.346Z SendDataConnector.js: Connect (retry count 2) to peer 80:01:84:8A:B3:68 with availability status: true
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T08:54:34.346Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T08:54:34.347Z SendDataConnector.js: do connect now
I/jxcore-log( 3823): 
,I/        ( 3823): Selected device address: 80:01:84:8A:B3:68, name: HTC Desire 820
,I/BTConnectToThread( 3823): Starting to connect
,W/BluetoothAdapter( 3823): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3823): Connecting to HTC Desire 820, at 80:01:84:8A:B3:68
D/BTIF_SOCK( 2177): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,E/bt-btm  ( 2177): tBTM_SEC_DEV:0xa2f175d4 rs_disc_pending=1
,W/bt-btif ( 2177): bta_dm_check_av:0
W/bt-btif ( 2177): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2177): btm_sec_disconnected - Clearing Pending flag,
,D/BluetoothMapService( 2177): onReceive
,I/BTConnectionReceiver( 1523): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1523): Bluetooth Device Name: XT1039
,W/bt-btif ( 2177): info:x10
D/        ( 2177): remote version info [80:01:84:8a:b3:68]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1523): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1523): Bluetooth Device Name: HTC Desire 820
,W/bt-sdp  ( 2177): process_service_search_attr_rsp
,W/bt-btif ( 2177): new conn_srvc id:26, app_id:1
W/bt-btif ( 2177): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2177): bta_dm_pm_ssr:2, lat:1200
I/BTConnectToThread( 3823): Starting to Handshake
I/BTHandshakeSocketThread( 3823): Creating BTHandshakeSocketThread
I/BTConnectToThread( 3823): MESSAGE_WRITE 82 bytes.
,I/BTHandshakeSocketThread( 3823): BTHandshakeSocketThread started
,I/BTConnectToThread( 3823): got MESSAGE_READ 84 bytes.
I/BTConnectToThread( 3823): Got JSON from encryption:{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT4869"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTConnectToThread( 3823): HandshakeOk : HTC-HTC Desire 820_PT4869
I/HS      ( 3823): Hand Shake finished outgoing for : HTC-HTC Desire 820_PT4869
,I/BTHandshakeSocketThread( 3823): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3823): Starting the connected thread incoming : false, HTC-HTC Desire 820_PT4869
I/BtToSocketBase( 3823): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3823): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3823): mHTTPPort  set to : 56492
I/BtConnectorHelper( 3823): Request socket is using : 56492
I/BtToRequestSocket( 3823): Now accepting connections
,I/BtConnectorHelper( 3823): Calling ConnectionStatusUpdate with port :56492
,I/jxcore-log( 3823): 2015-12-04T08:54:49.451Z SendDataConnector.js: CLIENT connected to 56492, error: null
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:54:49.453Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3823): 
,I/BtToRequestSocket( 3823): incoming data from: /127.0.0.1, port: 56492
,I/BtToRequestSocket( 3823): Set local streams
,I/BtToRequestSocket( 3823): rin ended ---------------------------;
I/jxcore-log( 3823): 2015-12-04T08:54:49.466Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 3823): 
,D/btif_config_util( 2177): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 2177): dm_pm_timer expires
,W/bt-btif ( 2177): dm_pm_timer expires 0
W/bt-btif ( 2177): proc dm_pm_timer expires
,I/wpa_supplicant( 1236): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
,I/wpa_supplicant( 1236): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant( 1236): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d,
,I/jxcore-log( 3823): 2015-12-04T08:54:59.528Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:54:59.529Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T08:54:59.530Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T08:54:59.531Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T08:54:59.532Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3823): 
I/BtToSocketBase( 3823): SendingThread thread got error: input stream got -1 on read,
I/BtConnectorHelper( 3823): Disconnect outgoing peer: HTC-HTC Desire 820_PT4869
I/BtToSocketBase( 3823): Stop ReceivingThread
I/BtToSocketBase( 3823): Stop SendingThread
I/BtToSocketBase( 3823): Close local in
I/BtToSocketBase( 3823): Close LocalOutputStream
,I/BtToSocketBase( 3823): Close localHostSocket
I/BtToSocketBase( 3823): Close bt in
I/BtToSocketBase( 3823): Close bt out
I/BtToSocketBase( 3823): Close bt socket
I/BtToRequestSocket( 3823): Close server socket
I/BtToSocketBase( 3823): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,W/bt-btif ( 2177): bta_jv_rfc_port_to_cb(port_handle:0x18):jv handle:0x0 not FOUND
,D/HeadsetStateMachine( 2177): Disconnected process message: 10, size: 0
,I/jxcore-log( 3823): 2015-12-04T08:55:04.533Z SendDataConnector.js: re-try now : 80:01:84:8A:B3:68
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:55:04.535Z SendDataConnector.js: ReStart called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3823): 
,E/bt-btm  ( 2177): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2177): onReceive
,I/BTConnectionReceiver( 1523): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1523): Bluetooth Device Name: HTC Desire 820
,I/jxcore-log( 3823): 2015-12-04T08:55:09.541Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:55:09.542Z SendDataConnector.js: Connect (retry count 3) to peer 80:01:84:8A:B3:68 with availability status: true
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T08:55:09.542Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T08:55:09.543Z SendDataConnector.js: do connect now
I/jxcore-log( 3823): 
,I/        ( 3823): Selected device address: 80:01:84:8A:B3:68, name: HTC Desire 820
,I/        ( 3823): Connecting to HTC Desire 820, at 80:01:84:8A:B3:68
,I/BTConnectToThread( 3823): Starting to connect
W/BluetoothAdapter( 3823): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2177): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,D/HeadsetStateMachine( 2177): Disconnected process message: 10, size: 0
,W/bt-sdp  ( 2177): SDP - Rcvd conn cnf with error: 0x4  CID 0x4a
,E/bt-btif ( 2177): DISCOVERY_COMP_EVT slot id:24, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2177): invalid rfc slot id: 24
I/BTConnectToThread( 3823): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3823): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3823): 2015-12-04T08:55:14.698Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:55:14.699Z SendDataConnector.js: CLIENT Can not Connect: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T08:55:14.700Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:55:19.700Z SendDataConnector.js: re-try now : 80:01:84:8A:B3:68
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T08:55:19.701Z SendDataConnector.js: ReStart called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3823): 
,W/bt-btif ( 2177): info:x10
D/        ( 2177): remote version info [34:fc:ef:9d:93:0b]: 6, f, 4106
,E/BluetoothRemoteDevices( 2177): aclStateChangeCallback: Device is NULL
,D/btif_config( 2177): btif_get_device_type: Device [34:fc:ef:9d:93:0b] type 1
,I/BluetoothBondStateMachine( 2177): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:9D:93:0B newState: 1
E/bt-btif ( 2177): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2177): Bond State Change Intent:34:FC:EF:9D:93:0B OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 2177): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2177): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:9D:93:0B newState: 0
D/BluetoothAdapterProperties( 2177): Failed to remove device: 34:FC:EF:9D:93:0B
,I/BluetoothBondStateMachine( 2177): Bond State Change Intent:34:FC:EF:9D:93:0B OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2177): StableState(): Entering Off State
,W/bt-btif ( 2177): new conn_srvc id:26, app_id:255
,W/bt-btif ( 2177): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2177): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3823): we got incoming connection
I/BTHandshakeSocketThread( 3823): Creating BTHandshakeSocketThread
I/BTListenerThread( 3823): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3823): BTHandshakeSocketThread started
,I/BTListenerThread( 3823): got MESSAGE_READ 77 bytes.
,I/BTListenerThread( 3823): Got JSON from encryption:{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT3722"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTListenerThread( 3823): MESSAGE_WRITE 82 bytes.
,I/HS      ( 3823): Incoming connection Hand Shake finished for : LGE-LG-D802_PT3722
I/BTHandshakeSocketThread( 3823): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3823): Starting the connected thread incoming : true, LGE-LG-D802_PT3722,
I/BtToSocketBase( 3823): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3823): Creating BTConnectedThread
I/BtConnectorHelper( 3823): Server socket is using : 0, and is now connected.
I/BtToRequestSocket( 3823): --DoOneRunRound started
,I/BtToRequestSocket( 3823): LocalHost address: localhost/127.0.0.1, port: 48599,
,I/BtToRequestSocket( 3823): --DoOneRunRound ended,
,I/jxcore-log( 3823): 2015-12-04T08:55:21.278Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3823): ,
,I/jxcore-log( 3823): 2015-12-04T08:55:22.396Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:55:22.402Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:55:22.408Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:55:22.414Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:55:22.420Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:55:22.426Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:55:22.460Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:55:22.486Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:55:22.490Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:55:22.497Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:55:22.516Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:55:22.550Z SendDataTCPServer.js: TCP/IP server has received 34748 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:55:22.556Z SendDataTCPServer.js: TCP/IP server has received 36728 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:55:22.612Z SendDataTCPServer.js: TCP/IP server has received 38708 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:55:22.669Z SendDataTCPServer.js: TCP/IP server has received 40688 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:55:22.698Z SendDataTCPServer.js: TCP/IP server has received 42668 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:55:22.730Z SendDataTCPServer.js: TCP/IP server has received 44648 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:55:22.864Z SendDataTCPServer.js: TCP/IP server has received 46628 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:55:22.886Z SendDataTCPServer.js: TCP/IP server has received 48608 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:55:22.921Z SendDataTCPServer.js: TCP/IP server has received 50588 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:55:22.926Z SendDataTCPServer.js: TCP/IP server has received 52568 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:55:22.960Z SendDataTCPServer.js: TCP/IP server has received 54548 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:55:23.032Z SendDataTCPServer.js: TCP/IP server has received 56528 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:55:23.052Z SendDataTCPServer.js: TCP/IP server has received 58508 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:55:23.060Z SendDataTCPServer.js: TCP/IP server has received 60488 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:55:23.075Z SendDataTCPServer.js: TCP/IP server has received 62468 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:55:23.110Z SendDataTCPServer.js: TCP/IP server has received 76328 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:55:23.137Z SendDataTCPServer.js: TCP/IP server has received 78308 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:55:23.165Z SendDataTCPServer.js: TCP/IP server has received 80288 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:55:23.200Z SendDataTCPServer.js: TCP/IP server has received 82268 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:55:23.305Z SendDataTCPServer.js: TCP/IP server has received 84248 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:55:23.447Z SendDataTCPServer.js: TCP/IP server has received 86228 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:55:23.505Z SendDataTCPServer.js: TCP/IP server has received 88208 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:55:23.533Z SendDataTCPServer.js: TCP/IP server has received 90188 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:55:23.562Z SendDataTCPServer.js: TCP/IP server has received 92168 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:55:23.818Z SendDataTCPServer.js: TCP/IP server has received 94148 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:55:23.824Z SendDataTCPServer.js: TCP/IP server has received 96128 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:55:23.825Z SendDataTCPServer.js: TCP/IP server has received 98108 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:55:23.836Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3823): ,
,I/jxcore-log( 3823): 2015-12-04T08:55:24.704Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:55:24.705Z SendDataConnector.js: Connect (retry count 4) to peer 80:01:84:8A:B3:68 with availability status: true
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T08:55:24.706Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:55:24.706Z SendDataConnector.js: do connect now
I/jxcore-log( 3823): 
,I/        ( 3823): Selected device address: 80:01:84:8A:B3:68, name: HTC Desire 820,
,I/BTConnectToThread( 3823): Starting to connect
W/BluetoothAdapter( 3823): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3823): Connecting to HTC Desire 820, at 80:01:84:8A:B3:68
,D/BTIF_SOCK( 2177): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,I/        ( 3823): Cleared service requests
,I/        ( 3823): Started peer discovery
,D/btif_config_util( 2177): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 1236): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3823): Found 5 peers.
I/SS      ( 3823): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3823): Peer(2): Note4-1 92:b6:86:43:73:1c
,I/SS      ( 3823): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3823): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3823): Peer(5): Android_2dc2 52:55:27:f0:ff:f0
,D/WifiP2pManager( 3823): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3823): Added service request
,I/wpa_supplicant( 1236): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
,I/GLSUser ( 1492): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1492): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1492): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1492): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1492): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3215): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3215): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3215): 	at jdm.a(PG:82)
E/HttpOperation( 3215): 	at jcs.o(PG:406)
E/HttpOperation( 3215): 	at jcn.a(PG:1379)
E/HttpOperation( 3215): 	at jcs.i(PG:143)
E/HttpOperation( 3215): 	at blb.a(PG:3937)
E/HttpOperation( 3215): 	at czp.a(PG:18188)
E/HttpOperation( 3215): 	at czp.a(PG:9081)
E/HttpOperation( 3215): 	at czq.run(PG:1686)
E/HttpOperation( 3215): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3215): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3215): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3215): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3215): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3215): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3215): 	at jdj.a(PG:4091)
E/HttpOperation( 3215): 	at jdj.a(PG:1125)
E/HttpOperation( 3215): 	at jdm.a(PG:77)
E/HttpOperation( 3215): 	... 12 more
,E/HttpOperation( 3215): Caused by: faj: BadAuthentication
E/HttpOperation( 3215): 	at fal.a(PG:38)
E/HttpOperation( 3215): 	at jdj.a(PG:4089),
E/HttpOperation( 3215): 	... 14 more
,I/GLSUser ( 1492): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1492): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1492): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1492): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1492): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3215): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3215): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3215): 	at jdm.a(PG:82)
E/HttpOperation( 3215): 	at jcs.o(PG:406)
E/HttpOperation( 3215): 	at jcn.a(PG:1379)
E/HttpOperation( 3215): 	at jcs.i(PG:143)
E/HttpOperation( 3215): 	at hec.a(PG:42)
E/HttpOperation( 3215): 	at hee.a(PG:102)
E/HttpOperation( 3215): 	at czr.a(PG:65)
E/HttpOperation( 3215): 	at kka.a(PG:108)
E/HttpOperation( 3215): 	at czp.a(PG:19176)
E/HttpOperation( 3215): 	at czp.a(PG:9081)
E/HttpOperation( 3215): 	at czq.run(PG:1686)
E/HttpOperation( 3215): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3215): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3215): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3215): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3215): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3215): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3215): 	at jdj.a(PG:4091)
E/HttpOperation( 3215): 	at jdj.a(PG:1125)
E/HttpOperation( 3215): 	at jdm.a(PG:77)
E/HttpOperation( 3215): 	... 15 more
E/HttpOperation( 3215): Caused by: faj: BadAuthentication
E/HttpOperation( 3215): 	at fal.a(PG:38)
E/HttpOperation( 3215): 	at jdj.a(PG:4089)
E/HttpOperation( 3215): 	... 17 more
E/ExperimentLoader( 3215): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3215): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3215): 	at jdm.a(PG:82)
E/ExperimentLoader( 3215): 	at jcs.o(PG:406)
E/ExperimentLoader( 3215): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3215): 	at jcs.i(PG:143)
E/ExperimentLoader( 3215): 	at hec.a(PG:42)
E/ExperimentLoader( 3215): 	at hee.a(PG:102)
E/ExperimentLoader( 3215): 	at czr.a(PG:65)
E/ExperimentLoader( 3215): 	at kka.a(PG:108)
E/ExperimentLoader( 3215): 	at czp.a(PG:19176)
E/ExperimentLoader( 3215): 	at czp.a(PG:9081)
E/ExperimentLoader( 3215): 	at czq.run(PG:1686)
E/ExperimentLoader( 3215): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3215): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3215): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3215): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3215): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3215): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3215): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3215): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3215): 	at jdm.a(PG:77)
E/ExperimentLoader( 3215): 	... 15 more
E/ExperimentLoader( 3215): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3215): 	at fal.a(PG:38)
E/ExperimentLoader( 3215): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3215): 	... 17 more
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 754707, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,I/        ( 3823): Started service discovery
,W/bt-btif ( 2177): dm_pm_timer expires
W/bt-btif ( 2177): dm_pm_timer expires 0
,W/bt-btif ( 2177): proc dm_pm_timer expires
,I/        ( 3823): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5092","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5092","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT5092, peerAddress: 7C:F9:0E:34:8A:A0
,I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT5092, WifiDirectName: , WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 3823): Found Service, :{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT2124","ra":"E0:DB:10:14:E2:C0"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT2124","ra":"E0:DB:10:14:E2:C0"} -- peerIdentifier:E0:DB:10:14:E2:C0, peerName: samsung-SM-N910C_PT2124, peerAddress: E0:DB:10:14:E2:C0
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : E0:DB:10:14:E2:C0, Name: samsung-SM-N910C_PT2124, WifiDirectName: Note4-1, WifiDirect Address: 92:b6:86:43:73:1c, peerId: E0:DB:10:14:E2:C0
,E/bt-btif ( 2177): DISCOVERY_COMP_EVT slot id:26, failed to find channle,                                       status:1, scn:0,
,W/bt-btif ( 2177): invalid rfc slot id: 26,
I/BTConnectToThread( 3823): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3823): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3823): 2015-12-04T08:55:34.683Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T08:55:34.683Z SendDataConnector.js: CLIENT Can not Connect: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T08:55:34.687Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T08:55:34.687Z SendDataConnector.js: Stop data retrieving timer
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:55:34.690Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 3823): 
I/jxcore-log( 3823): ---- round done--------
I/jxcore-log( 3823): 
I/jxcore-log( 3823): ---- gotta redo : 80:01:84:8A:B3:68, try count now: 1
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): do fake peer & start
I/jxcore-log( 3823): 
I/jxcore-log( 3823): Connect to fake peer: 34:FC:EF:11:AE:67
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:55:34.694Z SendDataConnector.js: Start called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:55:34.695Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T08:55:34.695Z SendDataConnector.js: do connect now
I/jxcore-log( 3823): 
,I/        ( 3823): Selected device address: 34:FC:EF:11:AE:67, name: null
,I/BTConnectToThread( 3823): Starting to connect
W/BluetoothAdapter( 3823): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3823): Connecting to null, at 34:FC:EF:11:AE:67,
I/chromium( 3823): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 80:01:84:8A:B3:68 done with result: Connection to 80:01:84:8A:B3:68 failed", source: file:///android_asset/www/js/thali_main.js (63)
,D/BTIF_SOCK( 2177): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-sdp  ( 2177): SDP - Rcvd conn cnf with error: 0x4  CID 0x40
E/bt-btif ( 2177): DISCOVERY_COMP_EVT slot id:27, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2177): invalid rfc slot id: 27
,I/BTConnectToThread( 3823): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3823): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3823): 2015-12-04T08:55:39.839Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:AE:67 failed
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:55:39.840Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:AE:67 failed
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T08:55:39.840Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3823): 
,I/        ( 3823): Cleared service requests
,I/        ( 3823): Started peer discovery
,I/jxcore-log( 3823): 2015-12-04T08:55:44.842Z SendDataConnector.js: re-try now : 34:FC:EF:11:AE:67
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:55:44.843Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 3823): 
,I/wpa_supplicant( 1236): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 1236): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1236): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/SS      ( 3823): Found 5 peers.
I/SS      ( 3823): Peer(1): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3823): Peer(2): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3823): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3823): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3823): Peer(5): Android_2dc2 52:55:27:f0:ff:f0
,D/WifiP2pManager( 3823): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3823): Added service request
,I/wpa_supplicant( 1236): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1236): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/        ( 3823): Started service discovery
,I/jxcore-log( 3823): 2015-12-04T08:55:49.846Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:AE:67
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:55:49.847Z SendDataConnector.js: Connect (retry count 1) to peer 34:FC:EF:11:AE:67 with availability status: true,
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T08:55:49.847Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:55:49.848Z SendDataConnector.js: do connect now
I/jxcore-log( 3823): 
,I/        ( 3823): Selected device address: 34:FC:EF:11:AE:67, name: null
,I/BTConnectToThread( 3823): Starting to connect
,W/BluetoothAdapter( 3823): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3823): Connecting to null, at 34:FC:EF:11:AE:67
,D/BTIF_SOCK( 2177): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,I/wpa_supplicant( 1236): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3823): Found Service, :{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT4244","ra":"7C:F9:0E:37:96:AB"}, typeCordovap2p._tcp.local.:
I/        ( 3823): JsonLine: {"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT4244","ra":"7C:F9:0E:37:96:AB"} -- peerIdentifier:7C:F9:0E:37:96:AB, peerName: samsung-SM-A500FU_PT4244, peerAddress: 7C:F9:0E:37:96:AB
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : 7C:F9:0E:37:96:AB, Name: samsung-SM-A500FU_PT4244, WifiDirectName: A5-1, WifiDirect Address: 7e:f9:0e:37:96:ac, peerId: 7C:F9:0E:37:96:AB
,I/        ( 3823): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5358"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5358"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT5358, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT5358, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/        ( 3823): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5092","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:,
I/        ( 3823): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5092","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT5092, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT5092, WifiDirectName: , WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 3823): Found Service, :{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT2124","ra":"E0:DB:10:14:E2:C0"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT2124","ra":"E0:DB:10:14:E2:C0"} -- peerIdentifier:E0:DB:10:14:E2:C0, peerName: samsung-SM-N910C_PT2124, peerAddress: E0:DB:10:14:E2:C0
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : E0:DB:10:14:E2:C0, Name: samsung-SM-N910C_PT2124, WifiDirectName: Note4-1, WifiDirect Address: 92:b6:86:43:73:1c, peerId: E0:DB:10:14:E2:C0
,W/bt-sdp  ( 2177): SDP - Rcvd conn cnf with error: 0x4  CID 0x43
E/bt-btif ( 2177): DISCOVERY_COMP_EVT slot id:28, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2177): invalid rfc slot id: 28
,I/BTConnectToThread( 3823): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3823): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3823): 2015-12-04T08:55:55.004Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:AE:67 failed
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:55:55.005Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:AE:67 failed
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:55:55.006Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3823): 
,I/        ( 3823): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT3722"}, typeCordovap2p._tcp.local.:
I/        ( 3823): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT3722"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT3722, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT3722, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/        ( 3823): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT5039"}, typeCordovap2p._tcp.local.:
I/        ( 3823): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT5039"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT5039, peerAddress: 00:F4:6F:30:E0:6C
,I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT5039, WifiDirectName: S5mini-1, WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,I/wpa_supplicant( 1236): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,V/KeepSync( 3727): Connecting to GoogleApiClient
,I/GLSUser ( 1492): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1492): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1492): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1492): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1492): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1822): Handling authorization failure
E/ClientConnectionOperation( 1822): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1822): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1822): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1822): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1822): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1822): 	... 7 more
,V/KeepSync( 3727): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3727): (284) automatic index on blob_node(is_deleted),
,E/SQLiteLog( 3727): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3727): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1492): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1492): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1492): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1492): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,V/GLSActivity( 1492): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3727): IOException
E/KeepSync( 3727): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3727): 	,at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3727): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3727): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3727): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3727): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3727): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3727): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3727): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3727): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305),
E/KeepSync( 3727): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3727): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3727): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3727): ,	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3727): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3727): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3727): ,	... 10 more
W/KeepSync( 3727): Sync result 2
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 757765, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/wpa_supplicant( 1236): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/        ( 3823): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT7300","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
I/        ( 3823): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT7300","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT7300, peerAddress: 08:EC:A9:50:76:27
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT7300, WifiDirectName: Thali Test (Galaxy A3), WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,I/jxcore-log( 3823): 2015-12-04T08:56:00.007Z SendDataConnector.js: re-try now : 34:FC:EF:11:AE:67
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:56:00.008Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 3823): 
,I/wpa_supplicant( 1236): P2P-DEVICE-FOUND 3a:94:96:b5:06:dd p2p_dev_addr=3a:94:96:b5:06:dd pri_dev_type=10-0050F204-5 name='Galaxy S5-2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/        ( 3823): Found Service, :{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT8320"}, typeCordovap2p._tcp.local.:
I/        ( 3823): JsonLine: {"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT8320"} -- peerIdentifier:38:94:96:B5:06:DC, peerName: samsung-SM-G800H_PT8320, peerAddress: 38:94:96:B5:06:DC
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : 38:94:96:B5:06:DC, Name: samsung-SM-G800H_PT8320, WifiDirectName: Galaxy S5-2, WifiDirect Address: 3a:94:96:b5:06:dd, peerId: 38:94:96:B5:06:DC
,I/wpa_supplicant( 1236): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 1236): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1236): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1236): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3823): Found Service, :{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2104","ra":"B0:C5:59:3F:75:69"}, typeCordovap2p._tcp.local.:
I/        ( 3823): JsonLine: {"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2104","ra":"B0:C5:59:3F:75:69"} -- peerIdentifier:B0:C5:59:3F:75:69, peerName: samsung-SM-G900F_PT2104, peerAddress: B0:C5:59:3F:75:69
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : B0:C5:59:3F:75:69, Name: samsung-SM-G900F_PT2104, WifiDirectName: Thali Test (Galaxy S5), WifiDirect Address: ee:1f:72:18:8b:78, peerId: B0:C5:59:3F:75:69
,I/jxcore-log( 3823): 2015-12-04T08:56:05.012Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:AE:67
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T08:56:05.013Z SendDataConnector.js: Connect (retry count 2) to peer 34:FC:EF:11:AE:67 with availability status: true
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:56:05.013Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T08:56:05.014Z SendDataConnector.js: do connect now
I/jxcore-log( 3823): 
,I/        ( 3823): Selected device address: 34:FC:EF:11:AE:67, name: null,
,I/BTConnectToThread( 3823): Starting to connect
W/BluetoothAdapter( 3823): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3823): Connecting to null, at 34:FC:EF:11:AE:67
,D/BTIF_SOCK( 2177): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-sdp  ( 2177): SDP - Rcvd conn cnf with error: 0x4  CID 0x42
E/bt-btif ( 2177): DISCOVERY_COMP_EVT slot id:29, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2177): invalid rfc slot id: 29
I/BTConnectToThread( 3823): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3823): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1,
I/jxcore-log( 3823): 2015-12-04T08:56:10.169Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:AE:67 failed
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T08:56:10.170Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:AE:67 failed
I/jxcore-log( 3823): ,
I/jxcore-log( 3823): 2015-12-04T08:56:10.171Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3823): 
,I/wpa_supplicant( 1236): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3823): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1124","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
I/        ( 3823): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1124","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT1124, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT1124, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,D/HeadsetStateMachine( 2177): Disconnected process message: 10, size: 0
,I/jxcore-log( 3823): 2015-12-04T08:56:15.171Z SendDataConnector.js: re-try now : 34:FC:EF:11:AE:67
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T08:56:15.172Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 3823): 
,I/wpa_supplicant( 1236): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/        ( 3823): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT3544","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT3544","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT3544, peerAddress: 58:3F:54:73:64:C0
,I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT3544, WifiDirectName: G3-1, WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,I/jxcore-log( 3823): 2015-12-04T08:56:20.176Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:AE:67
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:56:20.177Z SendDataConnector.js: Connect (retry count 3) to peer 34:FC:EF:11:AE:67 with availability status: true
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T08:56:20.177Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T08:56:20.178Z SendDataConnector.js: do connect now
I/jxcore-log( 3823): 
,I/        ( 3823): Selected device address: 34:FC:EF:11:AE:67, name: null
I/BTConnectToThread( 3823): Starting to connect
,W/BluetoothAdapter( 3823): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3823): Connecting to null, at 34:FC:EF:11:AE:67
,D/BTIF_SOCK( 2177): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae,
,W/bt-btif ( 2177): info:x10,
D/        ( 2177): remote version info [34:fc:ef:11:ae:67]: 7, f, 6109
E/BluetoothRemoteDevices( 2177): aclStateChangeCallback: Device is NULL,
,W/bt-sdp  ( 2177): process_service_search_attr_rsp,
,D/btif_config( 2177): btif_get_device_type: Device [34:fc:ef:11:ae:67] type 1
,I/BluetoothBondStateMachine( 2177): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:AE:67 newState: 1
,E/bt-btif ( 2177): check_cod: remote_cod = 0x5a020c,
,I/BluetoothBondStateMachine( 2177): Bond State Change Intent:34:FC:EF:11:AE:67 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 2177): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2177): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:AE:67 newState: 0
D/BluetoothAdapterProperties( 2177): Failed to remove device: 34:FC:EF:11:AE:67
,I/BluetoothBondStateMachine( 2177): Bond State Change Intent:34:FC:EF:11:AE:67 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2177): StableState(): Entering Off State
,W/bt-btif ( 2177): new conn_srvc id:26, app_id:1
W/bt-btif ( 2177): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 2177): bta_dm_pm_ssr:2, lat:1200
I/BTConnectToThread( 3823): Starting to Handshake
,I/BTHandshakeSocketThread( 3823): Creating BTHandshakeSocketThread
I/BTConnectToThread( 3823): MESSAGE_WRITE 82 bytes.
,I/BTHandshakeSocketThread( 3823): BTHandshakeSocketThread started
,I/wpa_supplicant( 1236): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3823): Cleared service requests
,I/        ( 3823): Started peer discovery
,I/wpa_supplicant( 1236): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1236): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 1236): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3823): Found 14 peers.
,I/SS      ( 3823): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3823): Peer(2): Galaxy S5-2 3a:94:96:b5:06:dd
I/SS      ( 3823): Peer(3): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3823): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3823): Peer(5): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3823): Peer(6): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3823): Peer(7): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 3823): Peer(8): Android_8ae2 52:55:27:f0:fd:0b
I/SS      ( 3823): Peer(9): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3823): Peer(10): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3823): Peer(11): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3823): Peer(12): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3823): Peer(13): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3823): Peer(14): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 3823): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3823): Added service request
,D/btif_config_util( 2177): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 3823): Started service discovery
,I/        ( 3823): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT3544","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
I/        ( 3823): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT3544","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT3544, peerAddress: 58:3F:54:73:64:C0
,I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT3544, WifiDirectName: G3-1, WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,I/        ( 3823): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1124","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1124","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT1124, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT1124, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/        ( 3823): Cleared service requests
,I/        ( 3823): Started peer discovery
,E/bt-rfcomm( 2177): Port error state 0 event 5
W/bt-btif ( 2177): invalid rfc slot id: 30
,I/BTHandshakeSocketThread( 3823): BTHandshakeSocketThread disconnected: java.io.IOException: bt socket closed, read return: -1
I/BTConnectToThread( 3823): HandshakeFailed : SOCKET_DISCONNECTED
,I/BTHandshakeSocketThread( 3823): BTHandshakeSocketThread fully stopped
I/CONNEC  ( 3823): Error: handshake: SOCKET_DISCONNECTED
I/jxcore-log( 3823): 2015-12-04T08:56:43.208Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:AE:67 failed
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:56:43.208Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:AE:67 failed
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T08:56:43.209Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3823): 
,E/bt-btm  ( 2177): tBTM_SEC_DEV:0xa2f1779c rs_disc_pending=1
,E/bt-btm  ( 2177): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 2177): invalid rfc slot id: 22
W/bt-btif ( 2177): invalid rfc slot 
W/bt-btif ( 2177): btif_dm_cback : unhandled event (14)
I/BtToSocketBase( 3823): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3823): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3823): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D802_PT3722
I/BtToSocketBase( 3823): Stop ReceivingThread
I/BtToSocketBase( 3823): Stop SendingThread
I/BtToSocketBase( 3823): Close local in
I/BtToSocketBase( 3823): Close LocalOutputStream
,I/BtToSocketBase( 3823): Close localHostSocket
I/BtToSocketBase( 3823): Close bt in
,I/BtToSocketBase( 3823): Close bt out
I/BtToSocketBase( 3823): Close bt socket
I/BtToSocketBase( 3823): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3823): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
D/BluetoothMapService( 2177): onReceive
,I/jxcore-log( 3823): 2015-12-04T08:56:47.940Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3823): 
,I/BTConnectionReceiver( 1523): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:9D:93:0B, alias=null, name=Thali Test's G2, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1523): Bluetooth Device Name: Thali Test's G2
,E/bt-btm  ( 2177): tBTM_SEC_DEV:0xa2f17964 rs_disc_pending=0
W/bt-btif ( 2177): bta_dm_check_av:0
,W/bt-btif ( 2177): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3823): 2015-12-04T08:56:48.211Z SendDataConnector.js: re-try now : 34:FC:EF:11:AE:67,
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T08:56:48.212Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 3823): 
,I/wpa_supplicant( 1236): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 1236): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1236): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1236): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3823): Found 14 peers.
,I/SS      ( 3823): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3823): Peer(2): Galaxy S5-2 3a:94:96:b5:06:dd
I/SS      ( 3823): Peer(3): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3823): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3823): Peer(5): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3823): Peer(6): G3-1 02:9a:02:7b:60:ac
,I/SS      ( 3823): Peer(7): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/SS      ( 3823): Peer(8): Android_8ae2 52:55:27:f0:fd:0b
,I/SS      ( 3823): Peer(9): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3823): Peer(10): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3823): Peer(11): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3823): Peer(12): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3823): Peer(13): XT1039_8c05 f4:f1:e1:5c:43:c8
,I/SS      ( 3823): Peer(14): S5mini-1 02:f4:6f:30:e0:6d
D/WifiP2pManager( 3823): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3823): Added service request
,E/bt-btm  ( 2177): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2177): onReceive
,I/BTConnectionReceiver( 1523): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1523): Bluetooth Device Name: Nexus 5,
,I/wpa_supplicant( 1236): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3823): Started service discovery,
,I/jxcore-log( 3823): 2015-12-04T08:56:53.216Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:AE:67
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T08:56:53.217Z SendDataConnector.js: Connect (retry count 4) to peer 34:FC:EF:11:AE:67 with availability status: true
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:56:53.218Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T08:56:53.219Z SendDataConnector.js: do connect now
I/jxcore-log( 3823): 
,I/        ( 3823): Selected device address: 34:FC:EF:11:AE:67, name: Nexus 5,
,I/        ( 3823): Connecting to Nexus 5, at 34:FC:EF:11:AE:67,
I/BTConnectToThread( 3823): Starting to connect
W/BluetoothAdapter( 3823): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2177): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae,
,W/bt-btif ( 2177): info:x10,
D/        ( 2177): remote version info [34:fc:ef:11:ae:67]: 6, f, 4106
,I/BTConnectionReceiver( 1523): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1523): Bluetooth Device Name: Nexus 5
,W/bt-sdp  ( 2177): process_service_search_attr_rsp
,W/bt-btif ( 2177): new conn_srvc id:26, app_id:1
W/bt-btif ( 2177): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2177): bta_dm_pm_ssr:2, lat:1200
I/BTConnectToThread( 3823): Starting to Handshake
I/BTHandshakeSocketThread( 3823): Creating BTHandshakeSocketThread
I/BTConnectToThread( 3823): MESSAGE_WRITE 82 bytes.
,I/BTHandshakeSocketThread( 3823): BTHandshakeSocketThread started
,I/BTConnectToThread( 3823): got MESSAGE_READ 75 bytes.
I/BTConnectToThread( 3823): Got JSON from encryption:{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT74","ra":"34:FC:EF:11:AE:67"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3823): HandshakeOk : LGE-Nexus 5_PT74
I/HS      ( 3823): Hand Shake finished outgoing for : LGE-Nexus 5_PT74
I/BTHandshakeSocketThread( 3823): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3823): Starting the connected thread incoming : false, LGE-Nexus 5_PT74
I/BtToSocketBase( 3823): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3823): Creating BtConnectedRequestSocket,
,I/BtToRequestSocket( 3823): mHTTPPort  set to : 37529
I/BtConnectorHelper( 3823): Request socket is using : 37529
I/BtToRequestSocket( 3823): Now accepting connections
,I/BtConnectorHelper( 3823): Calling ConnectionStatusUpdate with port :37529,
I/jxcore-log( 3823): 2015-12-04T08:56:55.182Z SendDataConnector.js: CLIENT connected to 37529, error: null
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T08:56:55.183Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3823): 
,I/BtToRequestSocket( 3823): incoming data from: /127.0.0.1, port: 37529
I/BtToRequestSocket( 3823): Set local streams
,I/jxcore-log( 3823): 2015-12-04T08:56:55.193Z SendDataConnector.js: CLIENT now sending 100000 bytes of data,
I/jxcore-log( 3823): 
I/BtToRequestSocket( 3823): rin ended ---------------------------;
,W/bt-btif ( 2177): info:x10
D/        ( 2177): remote version info [34:fc:ef:9d:93:0b]: 7, f, 6109
,I/BTConnectionReceiver( 1523): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:9D:93:0B, alias=null, name=Thali Test's G2, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1523): Bluetooth Device Name: Thali Test's G2
,E/bt-btm  ( 2177): tBTM_SEC_DEV:0xa2f17964 rs_disc_pending=1
W/bt-btif ( 2177): bta_dm_check_av:0
W/bt-btif ( 2177): btif_dm_cback : unhandled event (14)
,D/        ( 2177): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:24978
,I/jxcore-log( 3823): 2015-12-04T08:56:56.609Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3823): 
,I/        ( 3823): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT3544","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT3544","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT3544, peerAddress: 58:3F:54:73:64:C0
,I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT3544, WifiDirectName: G3-1, WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,I/jxcore-log( 3823): 2015-12-04T08:56:56.715Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3823): 
,D/        ( 2177): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:13098
,I/jxcore-log( 3823): 2015-12-04T08:56:56.889Z SendDataConnector.js: CLIENT is data received : 30000,
I/jxcore-log( 3823): 
,I/        ( 3823): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1124","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1124","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT1124, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT1124, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/jxcore-log( 3823): 2015-12-04T08:56:57.077Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3823): 
,D/        ( 2177): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:3198
,I/jxcore-log( 3823): 2015-12-04T08:56:57.217Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:56:57.264Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:56:57.660Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:56:57.783Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:56:57.966Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3823): 
,D/HeadsetStateMachine( 2177): Disconnected process message: 10, size: 0
,D/btif_config_util( 2177): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 3823): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT3940","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT3940","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT3940, peerAddress: E0:DB:10:1F:C9:5E,
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT3940, WifiDirectName: , WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,W/bt-btif ( 2177): dm_pm_timer expires
,W/bt-btif ( 2177): dm_pm_timer expires 0
W/bt-btif ( 2177): proc dm_pm_timer expires
,I/jxcore-log( 3823): 2015-12-04T08:57:07.968Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:57:07.969Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T08:57:07.970Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:57:07.975Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:57:07.976Z SendDataConnector.js: Stop data retrieving timer
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:57:07.978Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3823): 
I/BtConnectorHelper( 3823): Disconnect outgoing peer: 34:FC:EF:11:AE:67
I/BtToSocketBase( 3823): Stop ReceivingThread
,I/BtToSocketBase( 3823): Stop SendingThread
I/BtToSocketBase( 3823): Close local in
I/BtToSocketBase( 3823): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3823): Close LocalOutputStream
,I/BtToSocketBase( 3823): Close localHostSocket
I/BtToSocketBase( 3823): Close bt in
I/BtToSocketBase( 3823): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtToSocketBase( 3823): Close bt out
,I/BtToSocketBase( 3823): Close bt socket
I/BtToRequestSocket( 3823): Close server socket
I/jxcore-log( 3823): 2015-12-04T08:57:07.990Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:AE:67
I/jxcore-log( 3823): 
I/jxcore-log( 3823): ---- round done--------
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): ---- gotta redo : 34:FC:EF:11:AE:67, try count now: 1
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): do fake peer & start
I/jxcore-log( 3823): ,
I/jxcore-log( 3823): Connect to fake peer: 7C:F9:0E:37:96:AB
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:57:07.996Z SendDataConnector.js: Start called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T08:57:07.996Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T08:57:07.997Z SendDataConnector.js: do connect now
,I/jxcore-log( 3823): 
I/        ( 3823): Selected device address: 7C:F9:0E:37:96:AB, name: null
,I/BTConnectToThread( 3823): Starting to connect
,W/BluetoothAdapter( 3823): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3823): Connecting to null, at 7C:F9:0E:37:96:AB
,I/jxcore-log( 3823): 2015-12-04T08:57:08.010Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3823): 
,D/BTIF_SOCK( 2177): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,I/chromium( 3823): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 34:FC:EF:11:AE:67 done with result: DATA-TIMEOUT", source: file:///android_asset/www/js/thali_main.js (63)
,W/bt-btif ( 2177): bta_jv_rfc_port_to_cb(port_handle:0x1b):jv handle:0x0 not FOUND
,I/        ( 3823): Cleared service requests
I/        ( 3823): Started peer discovery
,W/bt-sdp  ( 2177): SDP - Rcvd conn cnf with error: 0x4  CID 0x47
E/bt-btif ( 2177): DISCOVERY_COMP_EVT slot id:32, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2177): invalid rfc slot id: 32
I/BTConnectToThread( 3823): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3823): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3823): 2015-12-04T08:57:13.143Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:57:13.144Z SendDataConnector.js: CLIENT Can not Connect: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T08:57:13.145Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3823): 
,I/wpa_supplicant( 1236): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3823): Found 14 peers.
,I/SS      ( 3823): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3823): Peer(2): Galaxy S5-2 3a:94:96:b5:06:dd
I/SS      ( 3823): Peer(3): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3823): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3823): Peer(5): Android_2dc2 52:55:27:f0:ff:f0
,I/SS      ( 3823): Peer(6): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3823): Peer(7): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 3823): Peer(8): Android_8ae2 52:55:27:f0:fd:0b
I/SS      ( 3823): Peer(9): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3823): Peer(10): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3823): Peer(11): G3s-1 a2:39:f7:70:12:80
,I/SS      ( 3823): Peer(12): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3823): Peer(13): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3823): Peer(14): S5mini-1 02:f4:6f:30:e0:6d
D/WifiP2pManager( 3823): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3823): Added service request
,E/bt-btm  ( 2177): btm_sec_disconnected - Clearing Pending flag,
,D/BluetoothMapService( 2177): onReceive
,I/BTConnectionReceiver( 1523): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1523): Bluetooth Device Name: Nexus 5
,D/HeadsetStateMachine( 2177): Disconnected process message: 10, size: 0
,I/        ( 3823): Started service discovery
,I/wpa_supplicant( 1236): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1236): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1236): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1236): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3823): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT3544","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT3544","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT3544, peerAddress: 58:3F:54:73:64:C0
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT3544, WifiDirectName: G3-1, WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,I/        ( 3823): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1124","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1124","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT1124, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT1124, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/        ( 3823): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT3940","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT3940","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT3940, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT3940, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/jxcore-log( 3823): 2015-12-04T08:57:18.145Z SendDataConnector.js: re-try now : 7C:F9:0E:37:96:AB
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:57:18.146Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:57:23.150Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T08:57:23.151Z SendDataConnector.js: Connect (retry count 1) to peer 7C:F9:0E:37:96:AB with availability status: true
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T08:57:23.152Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T08:57:23.152Z SendDataConnector.js: do connect now
I/jxcore-log( 3823): 
,I/        ( 3823): Selected device address: 7C:F9:0E:37:96:AB, name: null
,I/BTConnectToThread( 3823): Starting to connect
,W/BluetoothAdapter( 3823): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3823): Connecting to null, at 7C:F9:0E:37:96:AB
,D/BTIF_SOCK( 2177): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae,
,I/        ( 3823): Cleared service requests
,I/        ( 3823): Started peer discovery
,I/wpa_supplicant( 1236): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant( 1236): P2P-DEVICE-LOST p2p_dev_addr=3a:94:96:b5:06:dd
,I/wpa_supplicant( 1236): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant( 1236): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
,I/wpa_supplicant( 1236): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
,I/wpa_supplicant( 1236): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:fd:0b
,I/SS      ( 3823): Found 9 peers.
I/SS      ( 3823): Peer(1): Note4-1 92:b6:86:43:73:1c,
I/SS      ( 3823): Peer(2): A5-1 7e:f9:0e:37:96:ac
,I/SS      ( 3823): Peer(3): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3823): Peer(4): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3823): Peer(5): G3s-1 a2:39:f7:70:12:80,
I/SS      ( 3823): Peer(6): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3823): Peer(7): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3823): Peer(8): S5mini-1 02:f4:6f:30:e0:6d
,I/SS      ( 3823): Peer(9): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiP2pManager( 3823): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3823): Added service request
,W/bt-sdp  ( 2177): SDP - Rcvd conn cnf with error: 0x4  CID 0x49
E/bt-btif ( 2177): DISCOVERY_COMP_EVT slot id:33, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2177): invalid rfc slot id: 33
,I/BTConnectToThread( 3823): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3823): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3823): 2015-12-04T08:57:28.314Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T08:57:28.315Z SendDataConnector.js: CLIENT Can not Connect: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T08:57:28.316Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3823): 
,I/        ( 3823): Started service discovery
,I/        ( 3823): Found Service, :{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT8320"}, typeCordovap2p._tcp.local.:
I/        ( 3823): JsonLine: {"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT8320"} -- peerIdentifier:38:94:96:B5:06:DC, peerName: samsung-SM-G800H_PT8320, peerAddress: 38:94:96:B5:06:DC
,I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : 38:94:96:B5:06:DC, Name: samsung-SM-G800H_PT8320, WifiDirectName: , WifiDirect Address: 3a:94:96:b5:06:dd, peerId: 38:94:96:B5:06:DC
,I/        ( 3823): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT3940","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT3940","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT3940, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT3940, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/jxcore-log( 3823): 2015-12-04T08:57:33.316Z SendDataConnector.js: re-try now : 7C:F9:0E:37:96:AB
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:57:33.317Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:57:38.322Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:57:38.322Z SendDataConnector.js: Connect (retry count 2) to peer 7C:F9:0E:37:96:AB with availability status: true
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:57:38.323Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T08:57:38.324Z SendDataConnector.js: do connect now
I/jxcore-log( 3823): 
,I/        ( 3823): Selected device address: 7C:F9:0E:37:96:AB, name: null,
,I/        ( 3823): Connecting to null, at 7C:F9:0E:37:96:AB
,I/BTConnectToThread( 3823): Starting to connect
,W/BluetoothAdapter( 3823): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 2177): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,I/        ( 3823): Cleared service requests
,I/        ( 3823): Started peer discovery,
,I/wpa_supplicant( 1236): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0,
,I/SS      ( 3823): Found 10 peers.
I/SS      ( 3823): Peer(1): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3823): Peer(2): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3823): Peer(3): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3823): Peer(4): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3823): Peer(5): G3s-1 a2:39:f7:70:12:80
,I/SS      ( 3823): Peer(6): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3823): Peer(7): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3823): Peer(8): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3823): Peer(9): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3823): Peer(10): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 3823): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3823): Added service request
,I/wpa_supplicant( 1236): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1236): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3823): Started service discovery
,W/bt-sdp  ( 2177): SDP - Rcvd conn cnf with error: 0x4  CID 0x4a
E/bt-btif ( 2177): DISCOVERY_COMP_EVT slot id:34, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2177): invalid rfc slot id: 34
,I/BTConnectToThread( 3823): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3823): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3823): 2015-12-04T08:57:43.480Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T08:57:43.481Z SendDataConnector.js: CLIENT Can not Connect: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:57:43.481Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3823): 
,I/wpa_supplicant( 1236): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1,
,I/        ( 3823): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5092","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5092","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT5092, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT5092, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 3823): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT8263","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
I/        ( 3823): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT8263","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT8263, peerAddress: 08:EC:A9:50:75:41
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT8263, WifiDirectName: A3-1, WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,I/        ( 3823): Found Service, :{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT8320"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT8320"} -- peerIdentifier:38:94:96:B5:06:DC, peerName: samsung-SM-G800H_PT8320, peerAddress: 38:94:96:B5:06:DC
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : 38:94:96:B5:06:DC, Name: samsung-SM-G800H_PT8320, WifiDirectName: , WifiDirect Address: 3a:94:96:b5:06:dd, peerId: 38:94:96:B5:06:DC
,I/        ( 3823): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1124","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1124","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT1124, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT1124, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/        ( 3823): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT3940","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT3940","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT3940, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT3940, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/jxcore-log( 3823): 2015-12-04T08:57:48.482Z SendDataConnector.js: re-try now : 7C:F9:0E:37:96:AB,
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T08:57:48.483Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:57:53.487Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:57:53.488Z SendDataConnector.js: Connect (retry count 3) to peer 7C:F9:0E:37:96:AB with availability status: true
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T08:57:53.489Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T08:57:53.489Z SendDataConnector.js: do connect now
I/jxcore-log( 3823): 
,I/        ( 3823): Selected device address: 7C:F9:0E:37:96:AB, name: null
,I/BTConnectToThread( 3823): Starting to connect
,W/BluetoothAdapter( 3823): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3823): Connecting to null, at 7C:F9:0E:37:96:AB
,D/BTIF_SOCK( 2177): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,I/        ( 3823): Cleared service requests
,I/        ( 3823): Started peer discovery
,I/wpa_supplicant( 1236): P2P-DEVICE-FOUND 3a:94:96:b5:06:dd p2p_dev_addr=3a:94:96:b5:06:dd pri_dev_type=10-0050F204-5 name='Galaxy S5-2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 3823): Found 12 peers.
,I/SS      ( 3823): Peer(1): S5-1 ee:1f:72:63:11:86,
I/SS      ( 3823): Peer(2): Galaxy S5-2 3a:94:96:b5:06:dd
I/SS      ( 3823): Peer(3): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3823): Peer(4): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3823): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3823): Peer(6): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3823): Peer(7): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3823): Peer(8): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3823): Peer(9): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3823): Peer(10): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3823): Peer(11): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3823): Peer(12): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiP2pManager( 3823): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3823): Added service request
,I/wpa_supplicant( 1236): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1236): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/        ( 3823): Started service discovery
,I/wpa_supplicant( 1236): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant( 1236): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
,W/bt-sdp  ( 2177): SDP - Rcvd conn cnf with error: 0x4  CID 0x4b
,E/bt-btif ( 2177): DISCOVERY_COMP_EVT slot id:35, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2177): invalid rfc slot id: 35
I/BTConnectToThread( 3823): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3823): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3823): 2015-12-04T08:57:58.652Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:57:58.653Z SendDataConnector.js: CLIENT Can not Connect: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T08:57:58.653Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3823): 
,W/bt-btm  ( 2177): btm_acl_role_changed -> Issuing delayed HCI_Disconnect!!!,
E/bt-btm  ( 2177): tBTM_SEC_DEV:0xa2f1779c rs_disc_pending=2
E/bt-btm  ( 2177): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 2177): bta_dm_check_av:0
W/bt-btif ( 2177): btif_dm_cback : unhandled event (14)
,D/BluetoothMapService( 2177): onReceive
,I/BTConnectionReceiver( 1523): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:9D:93:0B, alias=null, name=Thali Test's G2, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1523): Bluetooth Device Name: Thali Test's G2
,W/bt-btif ( 2177): info:x10
D/        ( 2177): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
E/BluetoothRemoteDevices( 2177): aclStateChangeCallback: Device is NULL
,D/HeadsetStateMachine( 2177): Disconnected process message: 10, size: 0
,E/bt-btm  ( 2177): tBTM_SEC_DEV:0xa2f17cf4 rs_disc_pending=0
,W/bt-btif ( 2177): bta_dm_check_av:0
W/bt-btif ( 2177): btif_dm_cback : unhandled event (14)
,D/btif_config( 2177): btif_get_device_type: Device [f8:95:c7:87:3c:51] type 1
,I/BluetoothBondStateMachine( 2177): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1,
E/bt-btif ( 2177): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2177): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2177): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2177): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
D/BluetoothAdapterProperties( 2177): Failed to remove device: F8:95:C7:87:3C:51
,I/BluetoothBondStateMachine( 2177): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2177): StableState(): Entering Off State
,W/bt-btif ( 2177): new conn_srvc id:26, app_id:255
,W/bt-btif ( 2177): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2177): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3823): we got incoming connection
I/BTHandshakeSocketThread( 3823): Creating BTHandshakeSocketThread
I/BTListenerThread( 3823): waiting to accept incoming Connection
I/BTHandshakeSocketThread( 3823): BTHandshakeSocketThread started
,I/BTListenerThread( 3823): got MESSAGE_READ 77 bytes.
,I/BTListenerThread( 3823): Got JSON from encryption:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1124","ra":"F8:95:C7:87:3C:51"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTListenerThread( 3823): MESSAGE_WRITE 82 bytes.
I/HS      ( 3823): Incoming connection Hand Shake finished for : LGE-LG-H815_PT1124
,I/BTHandshakeSocketThread( 3823): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3823): Starting the connected thread incoming : true, LGE-LG-H815_PT1124
I/BtToSocketBase( 3823): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3823): Creating BTConnectedThread
I/BtConnectorHelper( 3823): Server socket is using : 0, and is now connected.
I/BtToRequestSocket( 3823): --DoOneRunRound started
,I/BtToRequestSocket( 3823): LocalHost address: localhost/127.0.0.1, port: 48599
,I/jxcore-log( 3823): 2015-12-04T08:58:02.059Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3823): 
,I/BtToRequestSocket( 3823): --DoOneRunRound ended
,I/jxcore-log( 3823): 2015-12-04T08:58:02.767Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:58:02.823Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:58:02.886Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:58:02.892Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:58:02.895Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
,I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:58:02.929Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:58:02.984Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:58:03.020Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 3823): 
,I/        ( 3823): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT3544","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT3544","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT3544, peerAddress: 58:3F:54:73:64:C0
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT3544, WifiDirectName: G3-1, WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,I/jxcore-log( 3823): 2015-12-04T08:58:03.060Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:58:03.119Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:58:03.123Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:58:03.155Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:58:03.190Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:58:03.193Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:58:03.212Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:58:03.220Z SendDataTCPServer.js: TCP/IP server has received 33660 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:58:03.268Z SendDataTCPServer.js: TCP/IP server has received 35640 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:58:03.433Z SendDataTCPServer.js: TCP/IP server has received 37620 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:58:03.437Z SendDataTCPServer.js: TCP/IP server has received 39600 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:58:03.485Z SendDataTCPServer.js: TCP/IP server has received 41580 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:58:03.493Z SendDataTCPServer.js: TCP/IP server has received 43560 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:58:03.530Z SendDataTCPServer.js: TCP/IP server has received 49500 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:58:03.557Z SendDataTCPServer.js: TCP/IP server has received 51480 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:58:03.565Z SendDataTCPServer.js: TCP/IP server has received 53460 bytes of data
I/jxcore-log( 3823): 
,I/        ( 3823): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5092","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5092","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT5092, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT5092, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 3823): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT8263","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT8263","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT8263, peerAddress: 08:EC:A9:50:75:41
,I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT8263, WifiDirectName: A3-1, WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,I/jxcore-log( 3823): 2015-12-04T08:58:03.596Z SendDataTCPServer.js: TCP/IP server has received 55440 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:58:03.629Z SendDataTCPServer.js: TCP/IP server has received 63360 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:58:03.649Z SendDataTCPServer.js: TCP/IP server has received 65340 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:58:03.654Z SendDataConnector.js: re-try now : 7C:F9:0E:37:96:AB
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:58:03.655Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:58:03.680Z SendDataTCPServer.js: TCP/IP server has received 75240 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:58:03.691Z SendDataTCPServer.js: TCP/IP server has received 77220 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:58:03.694Z SendDataTCPServer.js: TCP/IP server has received 79200 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:58:03.731Z SendDataTCPServer.js: TCP/IP server has received 89100 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:58:03.752Z SendDataTCPServer.js: TCP/IP server has received 91080 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:58:03.759Z SendDataTCPServer.js: TCP/IP server has received 93060 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:58:03.789Z SendDataTCPServer.js: TCP/IP server has received 97020 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:58:03.794Z SendDataTCPServer.js: TCP/IP server has received 99000 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:58:03.798Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3823): 
,D/btif_config_util( 2177): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 2177): info:x10
D/        ( 2177): remote version info [34:fc:ef:9d:93:0b]: 6, f, 4106
,I/BTConnectionReceiver( 1523): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:9D:93:0B, alias=null, name=Thali Test's G2, majorDeviceClass=512, deviceClass=524],
,I/BluetoothClassifier( 1523): Bluetooth Device Name: Thali Test's G2
,I/art     (  820): Explicit concurrent mark sweep GC freed 55018(2MB) AllocSpace objects, 6(284KB) LOS objects, 31% free, 34MB/50MB, paused 2.261ms total 98.736ms
,E/bt-btm  ( 2177): tBTM_SEC_DEV:0xa2f17cf4 rs_disc_pending=1
W/bt-btif ( 2177): bta_dm_check_av:0
W/bt-btif ( 2177): btif_dm_cback : unhandled event (14)
,D/btif_config( 2177): btif_get_device_type: Device [34:fc:ef:9d:93:0b] type 1
,I/BluetoothBondStateMachine( 2177): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:9D:93:0B newState: 1
,E/bt-btif ( 2177): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2177): Bond State Change Intent:34:FC:EF:9D:93:0B OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2177): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2177): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:9D:93:0B newState: 0
,D/BluetoothAdapterProperties( 2177): Failed to remove device: 34:FC:EF:9D:93:0B
,I/BluetoothBondStateMachine( 2177): Bond State Change Intent:34:FC:EF:9D:93:0B OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2177): StableState(): Entering Off State
,I/jxcore-log( 3823): 2015-12-04T08:58:08.659Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:58:08.660Z SendDataConnector.js: Connect (retry count 4) to peer 7C:F9:0E:37:96:AB with availability status: true
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:58:08.661Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T08:58:08.661Z SendDataConnector.js: do connect now
I/jxcore-log( 3823): 
,I/        ( 3823): Selected device address: 7C:F9:0E:37:96:AB, name: null
,I/BTConnectToThread( 3823): Starting to connect
W/BluetoothAdapter( 3823): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3823): Connecting to null, at 7C:F9:0E:37:96:AB
,D/BTIF_SOCK( 2177): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,I/        ( 3823): Cleared service requests
,I/        ( 3823): Started peer discovery
,D/btif_config_util( 2177): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-sdp  ( 2177): SDP - Rcvd conn cnf with error: 0x4  CID 0x42
E/bt-btif ( 2177): DISCOVERY_COMP_EVT slot id:37, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2177): invalid rfc slot id: 37
,I/BTConnectToThread( 3823): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3823): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3823): 2015-12-04T08:58:13.815Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T08:58:13.816Z SendDataConnector.js: CLIENT Can not Connect: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:58:13.823Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:58:13.826Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3823): 
I/jxcore-log( 3823): ---- round done--------
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): ---- gotta redo : 7C:F9:0E:37:96:AB, try count now: 1
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): do fake peer & start
I/jxcore-log( 3823): 
I/jxcore-log( 3823): Connect to fake peer: B4:CE:F6:AB:A4:6A
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:58:13.829Z SendDataConnector.js: Start called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T08:58:13.831Z SendDataConnector.js: doConnect called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T08:58:13.832Z SendDataConnector.js: do connect now
I/jxcore-log( 3823): 
,I/        ( 3823): Selected device address: B4:CE:F6:AB:A4:6A, name: null
,I/BTConnectToThread( 3823): Starting to connect
,W/BluetoothAdapter( 3823): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3823): Connecting to null, at B4:CE:F6:AB:A4:6A
,I/chromium( 3823): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 7C:F9:0E:37:96:AB done with result: Connection to 7C:F9:0E:37:96:AB failed", source: file:///android_asset/www/js/thali_main.js (63)
D/BTIF_SOCK( 2177): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-btif ( 2177): invalid rfc slot id: 25
I/BtToSocketBase( 3823): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3823): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3823): Disconnect:::Stop : mBtToServerSocket :LGE-LG-H815_PT1124
I/BtToSocketBase( 3823): Stop ReceivingThread
I/BtToSocketBase( 3823): Stop SendingThread
I/BtToSocketBase( 3823): Close local in
,I/BtToSocketBase( 3823): Close LocalOutputStream
,I/BtToSocketBase( 3823): Close localHostSocket
I/BtToSocketBase( 3823): Close bt in
I/BtToSocketBase( 3823): Close bt out
I/BtToSocketBase( 3823): Close bt socket
I/BtToSocketBase( 3823): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtConnectorHelper( 3823): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3823): 2015-12-04T08:58:14.286Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3823): 
,D/HeadsetStateMachine( 2177): Disconnected process message: 10, size: 0
,I/wpa_supplicant( 1236): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 1236): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3823): Found 11 peers.
,I/SS      ( 3823): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3823): Peer(2): Galaxy S5-2 3a:94:96:b5:06:dd
,I/SS      ( 3823): Peer(3): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3823): Peer(4): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3823): Peer(5): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3823): Peer(6): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3823): Peer(7): A3-1 0a:ec:a9:50:75:42
,I/SS      ( 3823): Peer(8): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3823): Peer(9): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3823): Peer(10): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3823): Peer(11): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 3823): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3823): Added service request
,I/        ( 3823): Started service discovery
,I/wpa_supplicant( 1236): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3823): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT3722"}, typeCordovap2p._tcp.local.:
I/        ( 3823): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT3722"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT3722, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT3722, WifiDirectName: , WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/        ( 3823): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT3544","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT3544","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT3544, peerAddress: 58:3F:54:73:64:C0
,I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT3544, WifiDirectName: G3-1, WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,I/        ( 3823): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5092","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 3823): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5092","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT5092, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT5092, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/wpa_supplicant( 1236): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,I/wpa_supplicant( 1236): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant( 1236): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
,E/bt-btm  ( 2177): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2177): onReceive,
,I/BTConnectionReceiver( 1523): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1523): Bluetooth Device Name: G4-1
,I/        ( 3823): Cleared service requests
,I/        ( 3823): Started peer discovery
,W/bt-btif ( 2177): info:x10
,D/        ( 2177): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,I/BTConnectionReceiver( 1523): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1523): Bluetooth Device Name: G4-1,
,W/bt-btif ( 2177): new conn_srvc id:26, app_id:255
W/bt-btif ( 2177): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 2177): bta_dm_pm_ssr:2, lat:1200
I/BTListenerThread( 3823): we got incoming connection
I/BTHandshakeSocketThread( 3823): Creating BTHandshakeSocketThread
I/BTListenerThread( 3823): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3823): BTHandshakeSocketThread started
,D/btif_config_util( 2177): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/BTListenerThread( 3823): got MESSAGE_READ 77 bytes.
,I/BTListenerThread( 3823): Got JSON from encryption:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1124","ra":"F8:95:C7:87:3C:51"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTListenerThread( 3823): MESSAGE_WRITE 82 bytes.
I/HS      ( 3823): Incoming connection Hand Shake finished for : LGE-LG-H815_PT1124
I/BTHandshakeSocketThread( 3823): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3823): Starting the connected thread incoming : true, LGE-LG-H815_PT1124
I/BtToSocketBase( 3823): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3823): Creating BTConnectedThread
I/BtConnectorHelper( 3823): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3823): --DoOneRunRound started
,I/BtToRequestSocket( 3823): LocalHost address: localhost/127.0.0.1, port: 48599
,I/BtToRequestSocket( 3823): --DoOneRunRound ended
,I/jxcore-log( 3823): 2015-12-04T08:58:39.008Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3823): 
,I/wpa_supplicant( 1236): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/jxcore-log( 3823): 2015-12-04T08:58:39.795Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:58:40.169Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:58:40.220Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:58:40.223Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:58:40.228Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 3823): 
,I/wpa_supplicant( 1236): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1236): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3823): Found 9 peers.
,I/SS      ( 3823): Peer(1): S5-1 ee:1f:72:63:11:86
,I/SS      ( 3823): Peer(2): Galaxy S5-2 3a:94:96:b5:06:dd
I/SS      ( 3823): Peer(3): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3823): Peer(4): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3823): Peer(5): A3-1 0a:ec:a9:50:75:42
,I/SS      ( 3823): Peer(6): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3823): Peer(7): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3823): Peer(8): S5mini-1 02:f4:6f:30:e0:6d
,I/SS      ( 3823): Peer(9): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiP2pManager( 3823): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3823): Added service request
,I/        ( 3823): Started service discovery
,I/        ( 3823): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5358"}, typeCordovap2p._tcp.local.:
I/        ( 3823): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5358"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT5358, peerAddress: F4:F1:E1:5C:3B:E2
,I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT5358, WifiDirectName: , WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,W/bt-sdp  ( 2177): SDP - Rcvd conn cnf with error: 0x22  CID 0x44
E/bt-btif ( 2177): DISCOVERY_COMP_EVT slot id:38, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2177): invalid rfc slot id: 38
I/BTConnectToThread( 3823): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3823): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3823): 2015-12-04T08:58:46.609Z SendDataConnector.js: CLIENT connected to -1, error: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:58:46.609Z SendDataConnector.js: CLIENT Can not Connect: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:58:46.610Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3823): 
,I/        ( 3823): Found Service, :{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2104","ra":"B0:C5:59:3F:75:69"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2104","ra":"B0:C5:59:3F:75:69"} -- peerIdentifier:B0:C5:59:3F:75:69, peerName: samsung-SM-G900F_PT2104, peerAddress: B0:C5:59:3F:75:69
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : B0:C5:59:3F:75:69, Name: samsung-SM-G900F_PT2104, WifiDirectName: Thali Test (Galaxy S5), WifiDirect Address: ee:1f:72:18:8b:78, peerId: B0:C5:59:3F:75:69
,W/bt-btif ( 2177): dm_pm_timer expires
,W/bt-btif ( 2177): dm_pm_timer expires 0
W/bt-btif ( 2177): proc dm_pm_timer expires
,I/jxcore-log( 3823): 2015-12-04T08:58:51.611Z SendDataConnector.js: re-try now : B4:CE:F6:AB:A4:6A
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:58:51.612Z SendDataConnector.js: ReStart called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3823): 
,I/        ( 3823): Cleared service requests
,I/        ( 3823): Started peer discovery
,I/jxcore-log( 3823): 2015-12-04T08:58:56.616Z SendDataConnector.js: Mobile.Disconnect() callback with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:58:56.617Z SendDataConnector.js: Connect (retry count 1) to peer B4:CE:F6:AB:A4:6A with availability status: true
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T08:58:56.618Z SendDataConnector.js: doConnect called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3823): ,
I/jxcore-log( 3823): 2015-12-04T08:58:56.618Z SendDataConnector.js: do connect now
I/jxcore-log( 3823): 
,I/        ( 3823): Selected device address: B4:CE:F6:AB:A4:6A, name: null
,I/BTConnectToThread( 3823): Starting to connect
,W/BluetoothAdapter( 3823): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3823): Connecting to null, at B4:CE:F6:AB:A4:6A
D/BTIF_SOCK( 2177): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,I/wpa_supplicant( 1236): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
,I/SS      ( 3823): Found 8 peers.
,I/SS      ( 3823): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3823): Peer(2): Galaxy S5-2 3a:94:96:b5:06:dd
,I/SS      ( 3823): Peer(3): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3823): Peer(4): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3823): Peer(5): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3823): Peer(6): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3823): Peer(7): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3823): Peer(8): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiP2pManager( 3823): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3823): Added service request
,I/        ( 3823): Started service discovery
,D/HeadsetStateMachine( 2177): Disconnected process message: 10, size: 0
,W/bt-sdp  ( 2177): SDP - Rcvd conn cnf with error: 0x4  CID 0x46
E/bt-btif ( 2177): DISCOVERY_COMP_EVT slot id:40, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2177): invalid rfc slot id: 40
,I/BTConnectToThread( 3823): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3823): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3823): 2015-12-04T08:59:01.774Z SendDataConnector.js: CLIENT connected to -1, error: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:59:01.775Z SendDataConnector.js: CLIENT Can not Connect: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T08:59:01.776Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3823): 
,I/wpa_supplicant( 1236): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 1236): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1236): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3823): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5358"}, typeCordovap2p._tcp.local.:
I/        ( 3823): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5358"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT5358, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT5358, WifiDirectName: , WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/        ( 3823): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1124","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1124","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT1124, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT1124, WifiDirectName: , WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/        ( 3823): Found Service, :{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2104","ra":"B0:C5:59:3F:75:69"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2104","ra":"B0:C5:59:3F:75:69"} -- peerIdentifier:B0:C5:59:3F:75:69, peerName: samsung-SM-G900F_PT2104, peerAddress: B0:C5:59:3F:75:69
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : B0:C5:59:3F:75:69, Name: samsung-SM-G900F_PT2104, WifiDirectName: Thali Test (Galaxy S5), WifiDirect Address: ee:1f:72:18:8b:78, peerId: B0:C5:59:3F:75:69
,I/jxcore-log( 3823): 2015-12-04T08:59:06.776Z SendDataConnector.js: re-try now : B4:CE:F6:AB:A4:6A
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T08:59:06.777Z SendDataConnector.js: ReStart called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3823): 
,I/        ( 3823): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT3722"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT3722"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT3722, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT3722, WifiDirectName: , WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,E/bt-btm  ( 2177): tBTM_SEC_DEV:0xa2f17cf4 rs_disc_pending=0
,W/bt-btif ( 2177): bta_dm_check_av:0
W/bt-btif ( 2177): btif_dm_cback : unhandled event (14)
,E/bt-btif ( 2177): bta_dm_pm_btm_status  hci_status=35,
,W/bt-btif ( 2177): invalid rfc slot id: 36
,I/BtToSocketBase( 3823): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3823): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3823): Disconnect:::Stop : mBtToServerSocket :LGE-LG-H815_PT1124
I/BtToSocketBase( 3823): Stop ReceivingThread
I/BtToSocketBase( 3823): Stop SendingThread
I/BtToSocketBase( 3823): Close local in
,I/BtToSocketBase( 3823): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3823): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3823): Disconnect:::Stop : mBtToServerSocket :LGE-LG-H815_PT1124
I/BtToSocketBase( 3823): Close LocalOutputStream
I/BtToSocketBase( 3823): Close localHostSocket
I/BtToSocketBase( 3823): Close bt in
,I/BtToSocketBase( 3823): Close bt in
I/BtToSocketBase( 3823): Close bt out
I/BtToSocketBase( 3823): Close bt out
I/BtToSocketBase( 3823): Close bt socket
I/BtToSocketBase( 3823): Close bt socket
I/jxcore-log( 3823): 2015-12-04T08:59:08.468Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3823): 
,W/bt-rfcomm( 2177): rfc_find_lcid_mcb LCID reused LCID:0x45 current:0x0
,W/bt-rfcomm( 2177): RFCOMM_DisconnectInd LCID:0x45
,E/bt-btm  ( 2177): tBTM_SEC_DEV:0xa2f17cf4 rs_disc_pending=1
W/bt-btif ( 2177): bta_dm_check_av:0
,W/bt-btif ( 2177): btif_dm_cback : unhandled event (14)
,W/bt-btm  ( 2177): btm_acl_role_changed -> Issuing delayed HCI_Disconnect!!!
,E/bt-btm  ( 2177): tBTM_SEC_DEV:0xa2f1779c rs_disc_pending=2
E/bt-btm  ( 2177): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 2177): bta_dm_check_av:0
W/bt-btif ( 2177): btif_dm_cback : unhandled event (14)
D/BluetoothMapService( 2177): onReceive
,I/BTConnectionReceiver( 1523): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:9D:93:0B, alias=null, name=Thali Test's G2, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1523): Bluetooth Device Name: Thali Test's G2
,W/bt-btif ( 2177): new conn_srvc id:26, app_id:255
,I/BTListenerThread( 3823): we got incoming connection
,I/BTHandshakeSocketThread( 3823): Creating BTHandshakeSocketThread
I/BTListenerThread( 3823): waiting to accept incoming Connection
I/BTHandshakeSocketThread( 3823): BTHandshakeSocketThread started
,I/jxcore-log( 3823): 2015-12-04T08:59:11.781Z SendDataConnector.js: Mobile.Disconnect() callback with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:59:11.782Z SendDataConnector.js: Connect (retry count 2) to peer B4:CE:F6:AB:A4:6A with availability status: true
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:59:11.783Z SendDataConnector.js: doConnect called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T08:59:11.783Z SendDataConnector.js: do connect now
I/jxcore-log( 3823): 
,I/        ( 3823): Selected device address: B4:CE:F6:AB:A4:6A, name: null
,I/        ( 3823): Connecting to null, at B4:CE:F6:AB:A4:6A
I/BTConnectToThread( 3823): Starting to connect
,W/BluetoothAdapter( 3823): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2177): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae,
,E/bt-btm  ( 2177): tBTM_SEC_DEV:0xa2f17cf4 rs_disc_pending=1
W/bt-btif ( 2177): bta_dm_check_av:0
,W/bt-btif ( 2177): btif_dm_cback : unhandled event (14)
,I/BTListenerThread( 3823): got MESSAGE_READ 77 bytes.
,I/BTListenerThread( 3823): Got JSON from encryption:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1124","ra":"F8:95:C7:87:3C:51"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTListenerThread( 3823): MESSAGE_WRITE 82 bytes.
I/HS      ( 3823): Incoming connection Hand Shake finished for : LGE-LG-H815_PT1124
I/BTHandshakeSocketThread( 3823): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3823): Starting the connected thread incoming : true, LGE-LG-H815_PT1124
I/BtToSocketBase( 3823): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3823): Creating BTConnectedThread
I/BtConnectorHelper( 3823): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3823): --DoOneRunRound started
,I/BtToRequestSocket( 3823): LocalHost address: localhost/127.0.0.1, port: 48599
,I/BtToRequestSocket( 3823): --DoOneRunRound ended
,I/jxcore-log( 3823): 2015-12-04T08:59:13.756Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3823): 
,W/bt-btif ( 2177): info:x10,
D/        ( 2177): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2177): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3823): 2015-12-04T08:59:14.240Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:59:14.243Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:59:14.263Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:59:14.303Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:59:14.309Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 3823): 
,E/bt-btm  ( 2177): tBTM_SEC_DEV:0xa2f18084 rs_disc_pending=0
W/bt-btif ( 2177): bta_dm_check_av:0
W/bt-btif ( 2177): btif_dm_cback : unhandled event (14)
,D/btif_config( 2177): btif_get_device_type: Device [08:ec:a9:50:76:27] type 1
,I/BluetoothBondStateMachine( 2177): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:76:27 newState: 1
,E/bt-btif ( 2177): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2177): Bond State Change Intent:08:EC:A9:50:76:27 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2177): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2177): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:76:27 newState: 0
,D/BluetoothAdapterProperties( 2177): Failed to remove device: 08:EC:A9:50:76:27
,I/BluetoothBondStateMachine( 2177): Bond State Change Intent:08:EC:A9:50:76:27 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2177): StableState(): Entering Off State
,W/bt-btif ( 2177): new conn_srvc id:26, app_id:255
W/bt-btif ( 2177): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2177): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3823): we got incoming connection
I/BTHandshakeSocketThread( 3823): Creating BTHandshakeSocketThread
,I/BTListenerThread( 3823): waiting to accept incoming Connection
I/BTHandshakeSocketThread( 3823): BTHandshakeSocketThread started
,I/        ( 3823): Cleared service requests
,I/        ( 3823): Started peer discovery
,E/bt-btm  ( 2177): tBTM_SEC_DEV:0xa2f18084 rs_disc_pending=1
,W/bt-btif ( 2177): bta_dm_check_av:0
W/bt-btif ( 2177): btif_dm_cback : unhandled event (14)
,I/BTListenerThread( 3823): got MESSAGE_READ 83 bytes.
,I/BTListenerThread( 3823): Got JSON from encryption:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT7300","ra":"08:EC:A9:50:76:27"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3823): MESSAGE_WRITE 82 bytes.
,I/HS      ( 3823): Incoming connection Hand Shake finished for : samsung-SM-A300FU_PT7300
,I/BTHandshakeSocketThread( 3823): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3823): Starting the connected thread incoming : true, samsung-SM-A300FU_PT7300
I/BtToSocketBase( 3823): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3823): Creating BTConnectedThread
I/BtConnectorHelper( 3823): Server socket is using : 0, and is now connected.
I/BtToRequestSocket( 3823): --DoOneRunRound started
,I/BtToRequestSocket( 3823): LocalHost address: localhost/127.0.0.1, port: 48599
,I/BtToRequestSocket( 3823): --DoOneRunRound ended
,I/jxcore-log( 3823): 2015-12-04T08:59:17.090Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3823): 
,W/bt-btif ( 2177): info:x10
,D/        ( 2177): remote version info [34:fc:ef:9d:93:0b]: 6, f, 410d
,I/BTConnectionReceiver( 1523): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:9D:93:0B, alias=null, name=Thali Test's G2, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1523): Bluetooth Device Name: Thali Test's G2
,I/jxcore-log( 3823): 2015-12-04T08:59:18.687Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:59:18.748Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:59:18.845Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data,
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T08:59:18.847Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:59:18.876Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:59:18.993Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:59:19.072Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:59:19.110Z SendDataTCPServer.js: TCP/IP server has received 14132 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:59:19.136Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:59:19.144Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:59:19.196Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:59:19.209Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data,
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:59:19.273Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:59:19.277Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:59:19.281Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:59:19.400Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:59:19.445Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:59:19.480Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:59:19.496Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data,
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:59:19.501Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data,
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:59:19.509Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data,
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:59:19.545Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:59:19.550Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:59:19.554Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:59:19.559Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:59:19.597Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:59:19.602Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:59:19.605Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:59:19.610Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:59:19.612Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:59:19.653Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:59:19.691Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:59:19.703Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:59:19.708Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data,
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:59:19.763Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data,
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:59:19.800Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data,
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:59:19.824Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
,I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:59:19.827Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:59:19.833Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:59:19.838Z SendDataTCPServer.js: TCP/IP server has received 85684 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:59:19.871Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:59:19.880Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:59:19.885Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:59:19.892Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:59:19.920Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3823): 
,I/wpa_supplicant( 1236): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,D/btif_config_util( 2177): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 1236): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1,
,I/SS      ( 3823): Found 9 peers.
,I/SS      ( 3823): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3823): Peer(2): Galaxy S5-2 3a:94:96:b5:06:dd,
I/SS      ( 3823): Peer(3): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3823): Peer(4): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3823): Peer(5): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3823): Peer(6): G4-1 a2:39:f7:6f:c9:5d
,I/SS      ( 3823): Peer(7): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3823): Peer(8): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3823): Peer(9): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiP2pManager( 3823): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3823): Added service request
,I/wpa_supplicant( 1236): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3823): Started service discovery
,I/wpa_supplicant( 1236): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1236): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3823): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5358"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5358"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT5358, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT5358, WifiDirectName: , WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,W/bt-btif ( 2177): dm_pm_timer expires,
W/bt-btif ( 2177): dm_pm_timer expires 1
W/bt-btif ( 2177): proc dm_pm_timer expires
,I/        ( 3823): Found Service, :{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2104","ra":"B0:C5:59:3F:75:69"}, typeCordovap2p._tcp.local.:,
I/        ( 3823): JsonLine: {"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2104","ra":"B0:C5:59:3F:75:69"} -- peerIdentifier:B0:C5:59:3F:75:69, peerName: samsung-SM-G900F_PT2104, peerAddress: B0:C5:59:3F:75:69
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : B0:C5:59:3F:75:69, Name: samsung-SM-G900F_PT2104, WifiDirectName: Thali Test (Galaxy S5), WifiDirect Address: ee:1f:72:18:8b:78, peerId: B0:C5:59:3F:75:69
,W/bt-btif ( 2177): invalid rfc slot id: 41,
,I/BtToSocketBase( 3823): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3823): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1,
,I/BtConnectorHelper( 3823): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A300FU_PT7300
I/BtToSocketBase( 3823): Stop ReceivingThread
,I/BtToSocketBase( 3823): Stop SendingThread
I/BtToSocketBase( 3823): Close local in
I/BtToSocketBase( 3823): Close LocalOutputStream
I/BtToSocketBase( 3823): Close localHostSocket
,I/BtToSocketBase( 3823): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3823): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3823): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A300FU_PT7300
I/BtToSocketBase( 3823): Close bt in
I/BtToSocketBase( 3823): Close bt out
,I/BtToSocketBase( 3823): Close bt socket
I/BtToSocketBase( 3823): Close bt in
I/BtToSocketBase( 3823): Close bt out
I/BtToSocketBase( 3823): Close bt socket
I/jxcore-log( 3823): 2015-12-04T08:59:30.492Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3823): 
,W/bt-rfcomm( 2177): rfc_find_lcid_mcb LCID reused LCID:0x4a current:0x0
W/bt-rfcomm( 2177): RFCOMM_DisconnectInd LCID:0x4a
,I/        ( 3823): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT3722"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT3722"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT3722, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT3722, WifiDirectName: , WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,E/bt-btm  ( 2177): btm_sec_disconnected - Clearing Pending flag,
,D/BluetoothMapService( 2177): onReceive
,I/BTConnectionReceiver( 1523): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1523): Bluetooth Device Name: Thali Test (Galaxy A3)
,I/        ( 3823): Cleared service requests
,I/        ( 3823): Started peer discovery
,W/bt-sdp  ( 2177): SDP - Rcvd conn cnf with error: 0x22  CID 0x47
,E/bt-btif ( 2177): DISCOVERY_COMP_EVT slot id:42, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2177): invalid rfc slot id: 42
I/BTConnectToThread( 3823): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3823): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3823): 2015-12-04T08:59:44.116Z SendDataConnector.js: CLIENT connected to -1, error: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T08:59:44.117Z SendDataConnector.js: CLIENT Can not Connect: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:59:44.120Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3823): 
,I/wpa_supplicant( 1236): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 1236): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3823): Found 10 peers.
,I/SS      ( 3823): Peer(1): S5-1 ee:1f:72:63:11:86
,I/SS      ( 3823): Peer(2): Galaxy S5-2 3a:94:96:b5:06:dd
,I/SS      ( 3823): Peer(3): Android_2dc2 52:55:27:f0:ff:f0
,I/SS      ( 3823): Peer(4): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3823): Peer(5): A3-1 0a:ec:a9:50:75:42
,I/SS      ( 3823): Peer(6): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3823): Peer(7): G3-1 02:9a:02:7b:60:ac
,I/SS      ( 3823): Peer(8): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3823): Peer(9): S5mini-1 02:f4:6f:30:e0:6d
,I/SS      ( 3823): Peer(10): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiP2pManager( 3823): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3823): Added service request
,W/bt-btif ( 2177): info:x10
D/        ( 2177): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1523): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1523): Bluetooth Device Name: Thali Test (Galaxy A3)
,I/wpa_supplicant( 1236): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3823): Started service discovery
,D/btif_config( 2177): btif_get_device_type: Device [34:fc:ef:9d:93:0b] type 1,
,I/BluetoothBondStateMachine( 2177): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:9D:93:0B newState: 1,
E/bt-btif ( 2177): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2177): Bond State Change Intent:34:FC:EF:9D:93:0B OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2177): Entering PendingCommandState State
,I/jxcore-log( 3823): 2015-12-04T08:59:49.121Z SendDataConnector.js: re-try now : B4:CE:F6:AB:A4:6A,
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T08:59:49.122Z SendDataConnector.js: ReStart called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3823): 
,I/BluetoothBondStateMachine( 2177): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:9D:93:0B newState: 0,
D/BluetoothAdapterProperties( 2177): Failed to remove device: 34:FC:EF:9D:93:0B
I/BluetoothBondStateMachine( 2177): Bond State Change Intent:34:FC:EF:9D:93:0B OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2177): StableState(): Entering Off State,
,W/bt-btif ( 2177): new conn_srvc id:26, app_id:255
,W/bt-btif ( 2177): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2177): bta_dm_pm_ssr:2, lat:1200
I/BTListenerThread( 3823): we got incoming connection
,I/BTHandshakeSocketThread( 3823): Creating BTHandshakeSocketThread
I/BTListenerThread( 3823): waiting to accept incoming Connection
I/BTHandshakeSocketThread( 3823): BTHandshakeSocketThread started
,E/bt-btm  ( 2177): tBTM_SEC_DEV:0xa2f17cf4 rs_disc_pending=0
,W/bt-btif ( 2177): bta_dm_check_av:0
W/bt-btif ( 2177): btif_dm_cback : unhandled event (14)
,I/BTListenerThread( 3823): got MESSAGE_READ 83 bytes.
,I/BTListenerThread( 3823): Got JSON from encryption:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT7300","ra":"08:EC:A9:50:76:27"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3823): MESSAGE_WRITE 82 bytes.,
I/HS      ( 3823): Incoming connection Hand Shake finished for : samsung-SM-A300FU_PT7300,
I/BtConnectorHelper( 3823): Starting the connected thread incoming : true, samsung-SM-A300FU_PT7300
I/BtToSocketBase( 3823): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3823): Creating BTConnectedThread
I/BtConnectorHelper( 3823): Server socket is using : 0, and is now connected.
,I/BTHandshakeSocketThread( 3823): BTHandshakeSocketThread fully stopped
,I/BtToRequestSocket( 3823): --DoOneRunRound started
,I/BtToRequestSocket( 3823): LocalHost address: localhost/127.0.0.1, port: 48599
,I/BtToRequestSocket( 3823): --DoOneRunRound ended
I/jxcore-log( 3823): 2015-12-04T08:59:49.813Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3823): 
,W/bt-btif ( 2177): invalid rfc slot id: 39
,I/BtToSocketBase( 3823): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3823): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3823): Disconnect:::Stop : mBtToServerSocket :LGE-LG-H815_PT1124
,I/BtToSocketBase( 3823): Stop ReceivingThread
I/BtToSocketBase( 3823): Stop SendingThread
I/BtToSocketBase( 3823): Close local in
,I/BtToSocketBase( 3823): Close LocalOutputStream
I/BtToSocketBase( 3823): Close localHostSocket
I/BtToSocketBase( 3823): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3823): Close bt in
I/BtConnectorHelper( 3823): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3823): Close bt out
,I/BtToSocketBase( 3823): Close bt socket
I/BtConnectorHelper( 3823): Disconnect:::Stop : mBtToServerSocket :LGE-LG-H815_PT1124
I/BtToSocketBase( 3823): Close bt in
,I/BtToSocketBase( 3823): Close bt out
I/BtToSocketBase( 3823): Close bt socket
I/jxcore-log( 3823): 2015-12-04T08:59:49.861Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3823): 
,W/bt-rfcomm( 2177): rfc_find_lcid_mcb LCID reused LCID:0x48 current:0x0
,W/bt-rfcomm( 2177): RFCOMM_DisconnectInd LCID:0x48
,I/jxcore-log( 3823): 2015-12-04T08:59:50.381Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:59:50.412Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:59:50.417Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:59:50.421Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:59:50.479Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:59:50.485Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 3823): 
,W/bt-btif ( 2177): new conn_srvc id:26, app_id:255,
I/BTListenerThread( 3823): we got incoming connection
,I/BTHandshakeSocketThread( 3823): Creating BTHandshakeSocketThread
I/BTListenerThread( 3823): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3823): BTHandshakeSocketThread started
,I/        ( 3823): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT3940","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:,
I/        ( 3823): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT3940","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT3940, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT3940, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/        ( 3823): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT7300","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:,
I/        ( 3823): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT7300","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT7300, peerAddress: 08:EC:A9:50:76:27
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT7300, WifiDirectName: , WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,I/BTListenerThread( 3823): got MESSAGE_READ 77 bytes.
,I/BTListenerThread( 3823): Got JSON from encryption:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1124","ra":"F8:95:C7:87:3C:51"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3823): MESSAGE_WRITE 82 bytes.
,I/HS      ( 3823): Incoming connection Hand Shake finished for : LGE-LG-H815_PT1124
I/BTHandshakeSocketThread( 3823): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3823): Starting the connected thread incoming : true, LGE-LG-H815_PT1124
I/BtToSocketBase( 3823): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3823): Creating BTConnectedThread
I/BtConnectorHelper( 3823): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3823): --DoOneRunRound started
I/BtToRequestSocket( 3823): LocalHost address: localhost/127.0.0.1, port: 48599,
I/jxcore-log( 3823): 2015-12-04T08:59:51.565Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3823): 
,I/BtToRequestSocket( 3823): --DoOneRunRound ended
,I/jxcore-log( 3823): 2015-12-04T08:59:52.359Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:59:52.637Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:59:52.682Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:59:52.742Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:59:52.787Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:59:54.126Z SendDataConnector.js: Mobile.Disconnect() callback with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T08:59:54.127Z SendDataConnector.js: Connect (retry count 3) to peer B4:CE:F6:AB:A4:6A with availability status: true
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T08:59:54.127Z SendDataConnector.js: doConnect called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T08:59:54.128Z SendDataConnector.js: do connect now
I/jxcore-log( 3823): 
,I/        ( 3823): Selected device address: B4:CE:F6:AB:A4:6A, name: null
,I/BTConnectToThread( 3823): Starting to connect
W/BluetoothAdapter( 3823): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3823): Connecting to null, at B4:CE:F6:AB:A4:6A
D/BTIF_SOCK( 2177): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,D/btif_config_util( 2177): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 1236): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
,I/wpa_supplicant( 1236): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,W/bt-sdp  ( 2177): SDP - Rcvd conn cnf with error: 0x4  CID 0x4e
E/bt-btif ( 2177): DISCOVERY_COMP_EVT slot id:46, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2177): invalid rfc slot id: 46
,I/BTConnectToThread( 3823): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3823): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3823): 2015-12-04T08:59:59.271Z SendDataConnector.js: CLIENT connected to -1, error: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T08:59:59.272Z SendDataConnector.js: CLIENT Can not Connect: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T08:59:59.273Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3823): 
,I/        ( 3823): Cleared service requests,
,I/        ( 3823): Started peer discovery
,D/HeadsetStateMachine( 2177): Disconnected process message: 10, size: 0
,W/bt-btif ( 2177): invalid rfc slot id: 43
,I/BtToSocketBase( 3823): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3823): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3823): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A300FU_PT7300
I/BtToSocketBase( 3823): Stop ReceivingThread
I/BtToSocketBase( 3823): Stop SendingThread
I/BtToSocketBase( 3823): Close local in
,I/BtToSocketBase( 3823): Close LocalOutputStream
I/BtToSocketBase( 3823): Close localHostSocket
I/BtToSocketBase( 3823): Close bt in
I/BtToSocketBase( 3823): Close bt out
I/BtToSocketBase( 3823): Close bt socket
I/BtToSocketBase( 3823): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtConnectorHelper( 3823): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/jxcore-log( 3823): 2015-12-04T09:00:00.927Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3823): 
,W/bt-rfcomm( 2177): rfc_find_lcid_mcb LCID reused LCID:0x4f current:0x0
,W/bt-rfcomm( 2177): RFCOMM_DisconnectInd LCID:0x4f
,W/bt-btif ( 2177): invalid rfc slot id: 44
,I/BtToSocketBase( 3823): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3823): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3823): Disconnect:::Stop : mBtToServerSocket :LGE-LG-H815_PT1124
I/BtToSocketBase( 3823): Stop ReceivingThread
I/BtToSocketBase( 3823): Stop SendingThread
I/BtToSocketBase( 3823): Close local in
,I/BtToSocketBase( 3823): Close LocalOutputStream
I/BtToSocketBase( 3823): Close localHostSocket
I/BtToSocketBase( 3823): Close bt in
I/BtToSocketBase( 3823): Close bt out
I/BtToSocketBase( 3823): Close bt socket
I/BtToSocketBase( 3823): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtConnectorHelper( 3823): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/jxcore-log( 3823): 2015-12-04T09:00:02.128Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3823): 
,W/bt-rfcomm( 2177): rfc_find_lcid_mcb LCID reused LCID:0x42 current:0x0
,W/bt-rfcomm( 2177): RFCOMM_DisconnectInd LCID:0x42
,I/wpa_supplicant( 1236): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/jxcore-log( 3823): 2015-12-04T09:00:04.274Z SendDataConnector.js: re-try now : B4:CE:F6:AB:A4:6A
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:00:04.275Z SendDataConnector.js: ReStart called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3823): 
,E/bt-btm  ( 2177): btm_sec_disconnected - Clearing Pending flag,
,D/BluetoothMapService( 2177): onReceive
,I/BTConnectionReceiver( 1523): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1523): Bluetooth Device Name: Thali Test (Galaxy A3)
,I/wpa_supplicant( 1236): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3823): Found 8 peers.,
I/SS      ( 3823): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3823): Peer(2): Galaxy S5-2 3a:94:96:b5:06:dd
,I/SS      ( 3823): Peer(3): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3823): Peer(4): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3823): Peer(5): G4-1 a2:39:f7:6f:c9:5d
,I/SS      ( 3823): Peer(6): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3823): Peer(7): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3823): Peer(8): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 3823): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3823): Added service request
,E/bt-btm  ( 2177): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2177): onReceive
,I/BTConnectionReceiver( 1523): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1523): Bluetooth Device Name: G4-1
,I/wpa_supplicant( 1236): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1236): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3823): Started service discovery
,I/wpa_supplicant( 1236): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1236): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3823): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT3940","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
I/        ( 3823): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT3940","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT3940, peerAddress: E0:DB:10:1F:C9:5E
,I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT3940, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/        ( 3823): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT7300","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT7300","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT7300, peerAddress: 08:EC:A9:50:76:27
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT7300, WifiDirectName: , WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,I/jxcore-log( 3823): 2015-12-04T09:00:09.278Z SendDataConnector.js: Mobile.Disconnect() callback with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:00:09.279Z SendDataConnector.js: Connect (retry count 4) to peer B4:CE:F6:AB:A4:6A with availability status: true
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:00:09.280Z SendDataConnector.js: doConnect called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:00:09.280Z SendDataConnector.js: do connect now
I/jxcore-log( 3823): 
I/        ( 3823): Selected device address: B4:CE:F6:AB:A4:6A, name: null
,I/BTConnectToThread( 3823): Starting to connect,
W/BluetoothAdapter( 3823): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3823): Connecting to null, at B4:CE:F6:AB:A4:6A
,D/BTIF_SOCK( 2177): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,I/        ( 3823): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1124","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1124","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT1124, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT1124, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/        ( 3823): Found Service, :{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2104","ra":"B0:C5:59:3F:75:69"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2104","ra":"B0:C5:59:3F:75:69"} -- peerIdentifier:B0:C5:59:3F:75:69, peerName: samsung-SM-G900F_PT2104, peerAddress: B0:C5:59:3F:75:69
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : B0:C5:59:3F:75:69, Name: samsung-SM-G900F_PT2104, WifiDirectName: Thali Test (Galaxy S5), WifiDirect Address: ee:1f:72:18:8b:78, peerId: B0:C5:59:3F:75:69
,W/bt-sdp  ( 2177): SDP - Rcvd conn cnf with error: 0x4  CID 0x4c
E/bt-btif ( 2177): DISCOVERY_COMP_EVT slot id:47, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2177): invalid rfc slot id: 47
,I/BTConnectToThread( 3823): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1,
I/CONNEC  ( 3823): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3823): 2015-12-04T09:00:14.425Z SendDataConnector.js: CLIENT connected to -1, error: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:00:14.426Z SendDataConnector.js: CLIENT Can not Connect: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:00:14.445Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:00:14.447Z SendDataConnector.js: Mobile.Disconnect() callback with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): ---- round done--------,
I/jxcore-log( 3823): 
I/jxcore-log( 3823): ---- gotta redo : B4:CE:F6:AB:A4:6A, try count now: 1
I/jxcore-log( 3823): 
I/jxcore-log( 3823): do fake peer & start
I/jxcore-log( 3823): 
I/jxcore-log( 3823): Connect to fake peer: E0:DB:10:14:E2:C0
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:00:14.449Z SendDataConnector.js: Start called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T09:00:14.449Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:00:14.449Z SendDataConnector.js: do connect now
I/jxcore-log( 3823): 
,I/        ( 3823): Selected device address: E0:DB:10:14:E2:C0, name: null
,I/        ( 3823): Connecting to null, at E0:DB:10:14:E2:C0,
I/chromium( 3823): [INFO:CONSOLE(63)] "logCallback Round of send data to peer B4:CE:F6:AB:A4:6A done with result: Connection to B4:CE:F6:AB:A4:6A failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 3823): Starting to connect,
W/BluetoothAdapter( 3823): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2177): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae,
,D/HeadsetStateMachine( 2177): Disconnected process message: 10, size: 0
,W/bt-btif ( 2177): info:x10,
D/        ( 2177): remote version info [08:ec:a9:50:76:27]: 7, f, 6109
,I/BTConnectionReceiver( 1523): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1523): Bluetooth Device Name: Thali Test (Galaxy A3)
,W/bt-btif ( 2177): info:x10
D/        ( 2177): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,E/BluetoothRemoteDevices( 2177): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 2177): new conn_srvc id:26, app_id:255,
W/bt-btif ( 2177): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 2177): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3823): we got incoming connection
I/BTHandshakeSocketThread( 3823): Creating BTHandshakeSocketThread
,I/BTListenerThread( 3823): waiting to accept incoming Connection
I/BTHandshakeSocketThread( 3823): BTHandshakeSocketThread started
,--------- beginning of crash
F/libc    ( 1236): Fatal signal 11 (SIGSEGV), code 1, fault addr 0xc in tid 1236 (wpa_supplicant)
I/libc    ( 1236): Suppressing debuggerd output because prctl(PR_GET_DUMPABLE)==0
I/        ( 3823): Cleared service requests
,I/BTListenerThread( 3823): got MESSAGE_READ 83 bytes.
,I/BTListenerThread( 3823): Got JSON from encryption:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT7300","ra":"08:EC:A9:50:76:27"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3823): MESSAGE_WRITE 82 bytes.
I/HS      ( 3823): Incoming connection Hand Shake finished for : samsung-SM-A300FU_PT7300
,I/BTHandshakeSocketThread( 3823): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3823): Starting the connected thread incoming : true, samsung-SM-A300FU_PT7300
I/BtToSocketBase( 3823): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3823): Creating BTConnectedThread
,I/BtConnectorHelper( 3823): Server socket is using : 0, and is now connected.
I/BtToRequestSocket( 3823): --DoOneRunRound started
,I/BtToRequestSocket( 3823): LocalHost address: localhost/127.0.0.1, port: 48599
I/BtToRequestSocket( 3823): --DoOneRunRound ended
,I/jxcore-log( 3823): 2015-12-04T09:00:19.261Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3823): 
,W/bt-sdp  ( 2177): process_service_search_attr_rsp
,I/jxcore-log( 3823): 2015-12-04T09:00:19.700Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:00:19.753Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:00:19.783Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:00:19.815Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:00:19.822Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:00:19.844Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 3823): 
,D/GCM     ( 1492): Message class com.google.f.a.a.i
,D/btif_config( 2177): btif_get_device_type: Device [e0:db:10:14:e2:c0] type 1
,I/BluetoothBondStateMachine( 2177): bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 1
,E/bt-btif ( 2177): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2177): Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2177): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2177): bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 0
D/BluetoothAdapterProperties( 2177): Failed to remove device: E0:DB:10:14:E2:C0
,I/BluetoothBondStateMachine( 2177): Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 11 NewState: 10,
,I/BluetoothBondStateMachine( 2177): StableState(): Entering Off State
,W/bt-btif ( 2177): new conn_srvc id:26, app_id:1
,W/bt-btif ( 2177): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 2177): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3823): Starting to Handshake,
I/BTHandshakeSocketThread( 3823): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3823): MESSAGE_WRITE 82 bytes.
I/BTHandshakeSocketThread( 3823): BTHandshakeSocketThread started
,I/BTConnectToThread( 3823): got MESSAGE_READ 82 bytes.,
I/BTConnectToThread( 3823): Got JSON from encryption:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT2124","ra":"E0:DB:10:14:E2:C0"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������,
I/BTConnectToThread( 3823): HandshakeOk : samsung-SM-N910C_PT2124
I/HS      ( 3823): Hand Shake finished outgoing for : samsung-SM-N910C_PT2124
I/BTHandshakeSocketThread( 3823): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3823): Starting the connected thread incoming : false, samsung-SM-N910C_PT2124,
I/BtToSocketBase( 3823): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3823): Creating BtConnectedRequestSocket
I/BtToRequestSocket( 3823): mHTTPPort  set to : 46755
I/BtConnectorHelper( 3823): Request socket is using : 46755
I/BtToRequestSocket( 3823): Now accepting connections
,I/BtConnectorHelper( 3823): Calling ConnectionStatusUpdate with port :46755
,I/jxcore-log( 3823): 2015-12-04T09:00:23.465Z SendDataConnector.js: CLIENT connected to 46755, error: null
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:00:23.467Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3823): 
,I/BtToRequestSocket( 3823): incoming data from: /127.0.0.1, port: 46755
,I/BtToRequestSocket( 3823): Set local streams
I/BtToRequestSocket( 3823): rin ended ---------------------------;
,I/jxcore-log( 3823): 2015-12-04T09:00:23.495Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3823): 
,D/btif_config_util( 2177): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3823): 2015-12-04T09:00:24.565Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:00:24.922Z SendDataConnector.js: CLIENT is data received : 20000,
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:00:25.109Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:00:25.305Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:00:25.664Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3823): ,
,I/jxcore-log( 3823): 2015-12-04T09:00:25.763Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:00:25.818Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:00:25.911Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:00:25.967Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3823): 
,D/WifiHW  (  820): 'P2P_FIND 120' command timed out.
I/        ( 3823): Starting peer discovery failed, error code 0
,E/WifiStateMachine(  820): Connection lost, restart supplicant,
E/WifiMonitor(  820): killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,E/WifiConfigStore(  820): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
E/WifiConfigStore(  820): failed to set BSSID: any
E/native  (  820): do suspend true
,W/Settings( 3883): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings( 1847): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/CommandListener(  354): Clearing all IP addresses on wlan0
,I/jxcore-log( 3823): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 3823): 
I/jxcore-log( 3823): The Coordinator has disconnected!
I/jxcore-log( 3823): 
,V/NativeCrypto( 1492): Read error: ssl=0xaec58800: I/O error during system call, Connection timed out
,V/NativeCrypto( 1492): SSL shutdown failed: ssl=0xaec58800: I/O error during system call, Broken pipe
,E/WifiStateMachine(  820): WifiStateMachine: Leaving Connected state
D/ConnectivityService(  820): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  820): NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
,E/WifiStateMachine(  820): Unexpected BatchedScanResults :null
,D/WifiScanningService(  820): SCAN_AVAILABLE : 1
D/RttService(  820): SCAN_AVAILABLE : 1
D/WifiNetworkAgent(  820): NetworkAgent: NetworkAgent channel lost
D/RttService(  820): EnabledState got{ when=-3ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
I/        ( 3823): Discovery state changed to Stopped.
I/WB      ( 3823): Wifi is DISABLED !!
I/        ( 3823): Stoping All
I/        ( 3823): Stopping services
I/        ( 3823): Stopping services
D/ConnectivityService(  820): reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10011
,I/        ( 3823): Stop Bluetooth
I/        ( 3823): Stop Bluetooth
I/BTListenerThread( 3823): Stopped
I/SS      ( 3823): We got empty peers list
I/        ( 3823): Starting peer discovery failed, error code 2
D/WifiScanningService(  820): StartedState got{ when=-5ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService(  820): DefaultState
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): ValidatedState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): DefaultState{ when=-2ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): Forcing reevaluation
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
I/        ( 3823): Clearing local services failed, error code 2
I/        ( 3823): Clearing service requests failed, error code 2
I/        ( 3823): Stopping peer discovery failed, error code 2
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
,D/ConnectivityService(  820): notifyType LOST for NetworkAgentInfo [WIFI () - 101]
D/CSLegacyTypeTracker(  820): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): OfflineState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): Disconnected - quitting
D/ConnectivityManager.CallbackHandler( 1064): CM callback handler got msg 524292
,D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  820): MasterInitialState.processMessage what=3
,D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  820): MasterInitialState.processMessage what=3
,D/ConnectivityService(  820): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  820): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
I/NetworkMonitor( 3914): type=WIFI subType= reason=null isConnected=false
,V/MusicLeanback( 3914): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/SprintDMReceiver( 3980): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3980): simOperator:  IMSI: null
D/SprintDMReceiver( 3980): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1822): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1822): onCreate
,D/SystemUpdateService( 1822): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1822): active receiver: enabled
,I/iu.Environment( 1822): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1822): num queued entries: 0
I/iu.UploadsManager( 1822): num updated entries: 0
,I/iu.SyncManager( 1822): NEXT; no task
,I/art     ( 1847): Explicit concurrent mark sweep GC freed 21261(1218KB) AllocSpace objects, 11(176KB) LOS objects, 37% free, 26MB/42MB, paused 1.471ms total 56.236ms
,D/ChimeraCfgMgr( 1822): Loading module com.google.android.gms.kids from APK com.google.android.gms
,E/DataBuffer( 1847): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2fcccdb8)
I/SystemUpdateService( 1822): showing system update notification
,I/Babel   ( 3883): connection state changed from CONNECTED to DISCONNECTED
,I/ValidateNoPeople(  820): skipping global notification
,V/SystemUpdateService( 1822): retry (wakeup: false) in 3599966 ms
,V/MusicLeanback( 3914): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/SystemUpdateService( 1822): onDestroy
,D/SprintDMReceiver( 3980): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3980): simOperator:  IMSI: null
,D/SprintDMReceiver( 3980): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1822): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1822): onCreate
,D/SystemUpdateService( 1822): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1822): active receiver: enabled
,I/SystemUpdateService( 1822): showing system update notification
,D/ChimeraCfgMgr( 1822): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/ValidateNoPeople(  820): skipping global notification
,D/PhoneInterfaceManager( 1278): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
,E/PhoneInterfaceManager( 1278): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
V/SystemUpdateService( 1822): retry (wakeup: false) in 3599982 ms
,D/TelephonyManager(  820): getDataEnabled: retVal=false
,D/SystemUpdateService( 1822): onDestroy
,E/GpsLocationProvider(  820): No APN found to select.
,D/PhoneInterfaceManager( 1278): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1278): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
D/TelephonyManager(  820): getDataEnabled: retVal=false
,E/GpsLocationProvider(  820): No APN found to select.
,W/bt-btif ( 2177): invalid rfc slot id: 45
,I/BtToSocketBase( 3823): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3823): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3823): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A300FU_PT7300
I/BtToSocketBase( 3823): Stop ReceivingThread
I/BtToSocketBase( 3823): Stop SendingThread
,I/BtToSocketBase( 3823): Close local in
I/BtToSocketBase( 3823): Close LocalOutputStream
I/BtToSocketBase( 3823): Close localHostSocket
I/BtToSocketBase( 3823): Close bt in
I/BtToSocketBase( 3823): Close bt out
,I/BtToSocketBase( 3823): Close bt socket
I/BtToSocketBase( 3823): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3823): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3823): 2015-12-04T09:00:29.917Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3823): 
,W/bt-rfcomm( 2177): rfc_find_lcid_mcb LCID reused LCID:0x45 current:0x0
,W/bt-rfcomm( 2177): RFCOMM_DisconnectInd LCID:0x45
,I/jxcore-log( 3823): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3823): ,
I/jxcore-log( 3823): Error type "connect_error" when connecting to the test server
I/jxcore-log( 3823): 
,D/WifiService(  820): setWifiEnabled: false pid=3823, uid=10265
E/WifiService(  820): Invoking mWifiStateMachine.setWifiEnabled
,D/WifiService(  820): setWifiEnabled: true pid=3823, uid=10265
E/WifiService(  820): Invoking mWifiStateMachine.setWifiEnabled
,D/WifiController(  820): WifiController msg { when=0 what=155656 target=com.android.internal.util.StateMachine$SmHandler } deferred for 473ms
,I/jxcore-log( 3823): Wifi toggled for connection repairment
I/jxcore-log( 3823): 
,I/chromium( 3823): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,D/WifiController(  820): DEFERRED_TOGGLE handled
,D/SoftapController(  354): Softap fwReload - Ok
,D/CommandListener(  354): Setting iface cfg
D/CommandListener(  354): Trying to bring down wlan0
,D/Tethering(  820): InitialState.processMessage what=4,
D/CommandListener(  354): Clearing all IP addresses on wlan0
,E/WifiMonitor(  820): killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,D/Tethering(  820): sendTetherStateChangedBroadcast 0, 0, 0
,I/wpa_supplicant( 4566): Successfully initialized wpa_supplicant
,D/WifiMonitor(  820): startMonitoring(wlan0) with mConnected = false
,I/wpa_supplicant( 4566): rfkill: Cannot open RFKILL control device
,W/bt-btif ( 2177): dm_pm_timer expires
W/bt-btif ( 2177): dm_pm_timer expires 0
W/bt-btif ( 2177): proc dm_pm_timer expires
,I/jxcore-log( 3823): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): Error type "connect_error" when connecting to the test server,
I/jxcore-log( 3823): 
,I/chromium( 3823): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,D/Tethering(  820): sendTetherStateChangedBroadcast 1, 0, 0
,I/wpa_supplicant( 4566): rfkill: Cannot open RFKILL control device
E/wpa_supplicant( 4566): Could not read interface p2p-dev-wlan0 flags: No such device
,D/WifiConfigStore(  820): Loading config and enabling all networks ,
E/WifiConfigStore(  820): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,D/WifiNative-HAL(  820): Setting external_sim to 1
,D/WifiStateMachine(  820): Setting OUI to 92-68-C3
I/WifiNative-HAL(  820): startHal
W/Settings( 3883): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/wifi    (  820): setting scan oui 0xb4b8af40
D/WifiHAL (  820): Sending mac address OUI
D/WifiService(  820): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@a9db442}
,E/native  (  820): do suspend true
,W/CommandListener(  354): Failed to retrieve HW addr for p2p0 (No such device)
,D/WifiScanningService(  820): SCAN_AVAILABLE : 3
D/RttService(  820): SCAN_AVAILABLE : 3
D/WifiScanningService(  820): DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  820): startHal
D/wifi    (  820): getting scan capabilities on interface[0] = 0xb4b8af40
D/WifiHAL (  820): Creating message to get scan capablities; iface = 5
D/RttService(  820): DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiHAL (  820): In GetCapabilities::handleResponse
D/WifiHAL (  820): Id = 0, subcmd = 0, len = 28, expected len = 32
D/WifiScanningService(  820): StartedState
D/CommandListener(  354): Setting iface cfg
E/WifiP2pService(  820): Unable to change interface settings: java.lang.IllegalStateException: command '76 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 76 Failed to set address (No such device)'
D/WifiMonitor(  820): startMonitoring(p2p0) with mConnected = true
,I/WB      ( 3823): Wifi is now enabled !
I/        ( 3823): Stoping All
I/        ( 3823): Stopping services
I/        ( 3823): Stop Bluetooth
I/        ( 3823): Starting All
I/        ( 3823): Stopping services
I/        ( 3823): Starting services address: {"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT1135","ra":"F8:CF:C5:D9:E5:61"}, org.thaliproject.p2p.btconnectorlib.BTConnectorSettings@3731150a
I/        ( 3823): Stopping services
,I/        ( 3823): Starting services address: {"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT1135","ra":"F8:CF:C5:D9:E5:61"}
I/        ( 3823): Add local service :{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT1135","ra":"F8:CF:C5:D9:E5:61"}, length : 82
I/        ( 3823): peerDiscoveryTimer timeout value:6396
D/WifiNative-HAL(  820): p2pGetDeviceAddress
D/WifiNative-HAL(  820): p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,I/        ( 3823): Stop Bluetooth
I/        ( 3823): StartBluetooth listener
I/        ( 3823): StartBluetooth listener
D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
W/BluetoothAdapter( 3823): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3823): Discovery state changed to Stopped.
,I/BTListenerThread( 3823): starting to listen
I/BTListenerThread( 3823): waiting to accept incoming Connection
,I/wpa_supplicant( 4566): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,I/        ( 3823): Added local service
,I/        ( 3823): Cleared service requests
,I/        ( 3823): Stopped peer discovery
,I/        ( 3823): Started peer discovery
,I/        ( 3823): Discovery state changed to Started.
,I/        ( 3823): Started peer discovery
,I/wpa_supplicant( 4566): p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,E/WifiStateMachine(  820): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,E/WifiConfigStore(  820):  rewrite network history for "NG700"WPA_PSK
E/WifiConfigStore(  820):  rewrite network history for "NG7005g"WPA_PSK
,E/WifiStateMachine(  820): CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3,
E/WifiConfigStore(  820): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiStateMachine(  820): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=0
,E/WifiConfigStore(  820): will read network variables netId=0
,E/WifiStateMachine(  820): CMD_AUTO_CONNECT did save config ->  nid=0
,E/WifiConfigStore(  820): will read network variables netId=0
,E/bt-btm  ( 2177): btm_sec_disconnected - Clearing Pending flag,
,D/BluetoothMapService( 2177): onReceive
,I/BTConnectionReceiver( 1523): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1523): Bluetooth Device Name: Thali Test (Galaxy A3)
,I/wpa_supplicant( 4566): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 4566): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 4566): wlan0: Trying to associate with SSID 'NG7005g'
,I/SS      ( 3823): Found 2 peers.
I/SS      ( 3823): Peer(1): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3823): Peer(2): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3823): Ignored { when=-3ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3823): Added service request
,I/        ( 3823): Started service discovery
,I/wpa_supplicant( 4566): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 4566): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 4566): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=0 id_str=]
,D/ConnectivityService(  820): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} }
,E/WifiConfigStore(  820): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  820): NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  820): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any,
,D/CommandListener(  354): Setting iface cfg,
,E/WifiStateMachine(  820): Start Dhcp Watchdog 3
,E/WifiStateMachine(  820):  WifiLinkLayerStats: 
E/WifiStateMachine(  820):  my bss beacon rx: 1
E/WifiStateMachine(  820):  RSSI mgmt: -47
E/WifiStateMachine(  820):  BE :  rx=0 tx=2 lost=0 retries=0
E/WifiStateMachine(  820):  BK :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  820):  VI :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  820):  VO :  rx=2 tx=0 lost=0 retries=0
E/WifiStateMachine(  820):  on_time : 0 tx_time=172 rx_time=725 scan_time=0
,E/native  (  820): do suspend false
,E/WifiStateMachine(  820): scanCount==0 - aborting,
,I/wpa_supplicant( 4566): P2P-FIND-STOPPED 
,I/        ( 3823): Discovery state changed to Stopped.
,I/        ( 3823): Starting peer discovery failed, error code 2
,I/jxcore-log( 3823): 2015-12-04T09:00:35.968Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:00:35.968Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T09:00:35.970Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:00:35.970Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T09:00:35.971Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3823): 
I/BtToSocketBase( 3823): SendingThread thread got error: input stream got -1 on read
,I/BtConnectorHelper( 3823): Disconnect outgoing peer: samsung-SM-N910C_PT2124
I/BtToSocketBase( 3823): Stop ReceivingThread
I/BtToSocketBase( 3823): Stop SendingThread
,I/BtToSocketBase( 3823): Close local in
I/BtToSocketBase( 3823): Close LocalOutputStream
I/BtToSocketBase( 3823): Close localHostSocket
,I/BtToSocketBase( 3823): Close bt in
,I/BtToSocketBase( 3823): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtToSocketBase( 3823): Close bt out
I/BtToSocketBase( 3823): Close bt socket
I/BtToRequestSocket( 3823): Close server socket
,I/dhcpcd  ( 4578): version 5.5.6 starting
,I/dhcpcd  ( 4578): wlan0: rebinding lease of 192.168.1.110
,I/wpa_supplicant( 4566): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1,
,I/SS      ( 3823): Found 2 peers.,
I/SS      ( 3823): Peer(1): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3823): Peer(2): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3823): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3823): Added service request
,I/jxcore-log( 3823): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3823): 
I/jxcore-log( 3823): Error type "connect_error" when connecting to the test server
I/jxcore-log( 3823): 
,I/chromium( 3823): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,D/WifiService(  820): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@a9db442}
,W/bt-btif ( 2177): bta_jv_rfc_port_to_cb(port_handle:0xa):jv handle:0x0 not FOUND
,I/        ( 3823): Starting service discovery failed, error code 2
,I/        ( 3823): Cleared service requests
,I/dhcpcd  ( 4578): wlan0: acknowledged 192.168.1.110 from 192.168.1.1
,I/dhcpcd  ( 4578): wlan0: leased 192.168.1.110 for 86400 seconds
,E/native  (  820): do suspend true,
,D/ConnectivityService(  820): NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  820): Adding iface wlan0 to network 102
,E/WifiStateMachine(  820): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  820): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  820): Adding Route [fe80::/64 -> :: wlan0] to network 102
D/ConnectivityService(  820): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,D/ConnectivityService(  820): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,D/ConnectivityService(  820): Setting Dns servers for network 102 to [/192.168.1.1],
,D/ConnectivityService(  820): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,D/ConnectivityService(  820): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102],
D/ConnectivityService(  820): rematching NetworkAgentInfo [WIFI () - 102]
D/ConnectivityService(  820):    accepting network in place of null
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 102](  820): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler },
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 102](  820): Connected
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 102](  820): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  820): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.110/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 102](  820): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g",
D/ConnectivityService(  820): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
,D/CSLegacyTypeTracker(  820): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 1064): CM callback handler got msg 524290
D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering(  820): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 3914): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 3914): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/PhoneInterfaceManager( 1278): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
,E/PhoneInterfaceManager( 1278): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  820): getDataEnabled: retVal=false
,E/GpsLocationProvider(  820): No APN found to select.
,D/SprintDMReceiver( 3980): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3980): simOperator:  IMSI: null
D/SprintDMReceiver( 3980): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1822): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1822): onCreate
,D/SystemUpdateService( 1822): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1822): active receiver: enabled
,I/SystemUpdateService( 1822): showing system update notification
,I/iu.Environment( 1822): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1822): num queued entries: 0
I/iu.UploadsManager( 1822): num updated entries: 0
,I/ValidateNoPeople(  820): skipping global notification
,I/iu.SyncManager( 1822): NEXT; no task
,V/SystemUpdateService( 1822): retry (wakeup: false) in 3599982 ms
D/ChimeraCfgMgr( 1822): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 1822): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/SystemUpdateService( 1822): onDestroy
,I/GLSUser ( 1492): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1492): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1492): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1492): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1492): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 102](  820): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 04 Dec 2015 09:00:38 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1449219638836], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1449219638817]},
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 102](  820): Validated
D/ConnectivityService(  820): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/ConnectivityService(  820): Validated NetworkAgentInfo [WIFI () - 102]
D/ConnectivityService(  820): rematching NetworkAgentInfo [WIFI () - 102]
D/ConnectivityService(  820): Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
D/ConnectivityService(  820): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
,D/ConnectivityManager.CallbackHandler( 1064): CM callback handler got msg 524290
,D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
W/Kids    ( 1822): [AccountUtils] Account not ready
,W/Kids    ( 1822): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 1822): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 1822): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 1822): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 1822): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 1822): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 1822): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 1822): 	,at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 1822): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 1822): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 1822): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 1822): 	at java.lang.Thread.run(Thread.java:818)
,V/Herrevad( 1822): NQAS connected
,I/wpa_supplicant( 4566): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 4566): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3823): Found 4 peers.
,I/SS      ( 3823): Peer(1): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3823): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 3823): Peer(3): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3823): Peer(4): G4-1 a2:39:f7:6f:c9:5d,
D/WifiP2pManager( 3823): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3823): Added service request
,I/Babel   ( 3883): connection state changed from DISCONNECTED to CONNECTED
,D/GCM     ( 1492): Connected
,D/GCM     ( 1492): Message class com.google.f.a.a.p
,D/ConnectivityService(  820): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,I/        ( 3823): Started service discovery
,I/wpa_supplicant( 4566): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3823): 2015-12-04T09:00:40.998Z SendDataConnector.js: re-try now : E0:DB:10:14:E2:C0
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T09:00:40.999Z SendDataConnector.js: ReStart called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3823): 
,E/bt-btm  ( 2177): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2177): onReceive
,I/BTConnectionReceiver( 1523): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1523): Bluetooth Device Name: Note4-1,
,I/        ( 3823): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT3722"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT3722"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT3722, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT3722, WifiDirectName: , WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/jxcore-log( 3823): DBG, CoordinatorConnector connect called
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): Coordinator is now connected to the server!
I/jxcore-log( 3823): 
,I/chromium( 3823): [INFO:CONSOLE(63)] "logCallback connected to server", source: file:///android_asset/www/js/thali_main.js (63)
,I/        ( 3823): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5092","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 3823): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5092","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT5092, peerAddress: 7C:F9:0E:34:8A:A0
,I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT5092, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 3823): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1124","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
I/        ( 3823): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1124","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT1124, peerAddress: F8:95:C7:87:3C:51
,I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT1124, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/        ( 3823): Found Service, :{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT2124","ra":"E0:DB:10:14:E2:C0"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT2124","ra":"E0:DB:10:14:E2:C0"} -- peerIdentifier:E0:DB:10:14:E2:C0, peerName: samsung-SM-N910C_PT2124, peerAddress: E0:DB:10:14:E2:C0
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : E0:DB:10:14:E2:C0, Name: samsung-SM-N910C_PT2124, WifiDirectName: Note4-1, WifiDirect Address: 92:b6:86:43:73:1c, peerId: E0:DB:10:14:E2:C0
,I/wpa_supplicant( 4566): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3823): Found Service, :{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT8320"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT8320"} -- peerIdentifier:38:94:96:B5:06:DC, peerName: samsung-SM-G800H_PT8320, peerAddress: 38:94:96:B5:06:DC
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : 38:94:96:B5:06:DC, Name: samsung-SM-G800H_PT8320, WifiDirectName: , WifiDirect Address: 3a:94:96:b5:06:dd, peerId: 38:94:96:B5:06:DC
,I/jxcore-log( 3823): 2015-12-04T09:00:46.025Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T09:00:46.025Z SendDataConnector.js: Connect (retry count 1) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:00:46.026Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T09:00:46.026Z SendDataConnector.js: do connect now
I/jxcore-log( 3823): 
,I/        ( 3823): Selected device address: E0:DB:10:14:E2:C0, name: Note4-1
,I/BTConnectToThread( 3823): Starting to connect
,W/BluetoothAdapter( 3823): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3823): Connecting to Note4-1, at E0:DB:10:14:E2:C0
,D/BTIF_SOCK( 2177): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,I/        ( 3823): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT5039"}, typeCordovap2p._tcp.local.:
I/        ( 3823): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT5039"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT5039, peerAddress: 00:F4:6F:30:E0:6C
,I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT5039, WifiDirectName: , WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,I/        ( 3823): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5358"}, typeCordovap2p._tcp.local.:
I/        ( 3823): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5358"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT5358, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT5358, WifiDirectName: , WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,W/bt-sdp  ( 2177): SDP - Rcvd conn cnf with error: 0x4  CID 0x49
,E/bt-btif ( 2177): DISCOVERY_COMP_EVT slot id:51, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2177): invalid rfc slot id: 51
I/BTConnectToThread( 3823): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3823): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3823): 2015-12-04T09:00:51.173Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T09:00:51.174Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T09:00:51.175Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3823): 
,I/wpa_supplicant( 4566): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3823): Found Service, :{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2104","ra":"B0:C5:59:3F:75:69"}, typeCordovap2p._tcp.local.:
I/        ( 3823): JsonLine: {"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2104","ra":"B0:C5:59:3F:75:69"} -- peerIdentifier:B0:C5:59:3F:75:69, peerName: samsung-SM-G900F_PT2104, peerAddress: B0:C5:59:3F:75:69
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : B0:C5:59:3F:75:69, Name: samsung-SM-G900F_PT2104, WifiDirectName: , WifiDirect Address: ee:1f:72:18:8b:78, peerId: B0:C5:59:3F:75:69
,W/bt-btm  ( 2177): btm_acl_role_changed -> Issuing delayed HCI_Disconnect!!!
,E/bt-btm  ( 2177): tBTM_SEC_DEV:0xa2f1779c rs_disc_pending=2
E/bt-btm  ( 2177): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 2177): bta_dm_check_av:0
W/bt-btif ( 2177): btif_dm_cback : unhandled event (14)
,D/BluetoothMapService( 2177): onReceive,
,I/BTConnectionReceiver( 1523): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:9D:93:0B, alias=null, name=Thali Test's G2, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1523): Bluetooth Device Name: Thali Test's G2,
,W/bt-btif ( 2177): info:x10
,D/        ( 2177): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1523): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1523): Bluetooth Device Name: Thali Test (Galaxy A3)
,W/bt-btif ( 2177): new conn_srvc id:26, app_id:255
W/bt-btif ( 2177): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 2177): bta_dm_pm_ssr:2, lat:1200,
I/BTListenerThread( 3823): we got incoming connection
I/BTHandshakeSocketThread( 3823): Creating BTHandshakeSocketThread
I/BTListenerThread( 3823): waiting to accept incoming Connection
I/BTHandshakeSocketThread( 3823): BTHandshakeSocketThread started
,I/BTListenerThread( 3823): got MESSAGE_READ 83 bytes.
I/BTListenerThread( 3823): Got JSON from encryption:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT7300","ra":"08:EC:A9:50:76:27"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3823): MESSAGE_WRITE 82 bytes.
I/HS      ( 3823): Incoming connection Hand Shake finished for : samsung-SM-A300FU_PT7300
,I/BTHandshakeSocketThread( 3823): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3823): Starting the connected thread incoming : true, samsung-SM-A300FU_PT7300
I/BtToSocketBase( 3823): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3823): Creating BTConnectedThread
,I/BtConnectorHelper( 3823): Server socket is using : 0, and is now connected.
I/BtToRequestSocket( 3823): --DoOneRunRound started
,I/BtToRequestSocket( 3823): LocalHost address: localhost/127.0.0.1, port: 48599
,I/BtToRequestSocket( 3823): --DoOneRunRound ended
,I/jxcore-log( 3823): 2015-12-04T09:00:53.336Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:00:53.827Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:00:53.850Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:00:53.854Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:00:53.864Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:00:53.872Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 3823): 
,W/bt-btif ( 2177): info:x10,
D/        ( 2177): remote version info [34:fc:ef:11:ae:67]: 7, f, 2205
,I/BTConnectionReceiver( 1523): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524],
,I/BluetoothClassifier( 1523): Bluetooth Device Name: Nexus 5,
,I/jxcore-log( 3823): 2015-12-04T09:00:56.177Z SendDataConnector.js: re-try now : E0:DB:10:14:E2:C0,
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T09:00:56.178Z SendDataConnector.js: ReStart called with peer E0:DB:10:14:E2:C0
,I/jxcore-log( 3823): 
,I/wpa_supplicant( 4566): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3823): Cleared service requests,
D/btif_config_util( 2177): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 3823): Started peer discovery
,I/        ( 3823): Discovery state changed to Started.
,I/wpa_supplicant( 4566): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3823): Found 6 peers.
I/SS      ( 3823): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3823): Peer(2): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3823): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3823): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3823): Peer(5): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3823): Peer(6): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3823): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3823): Added service request
,D/HeadsetStateMachine( 2177): Disconnected process message: 10, size: 0
,I/art     ( 1492): Explicit concurrent mark sweep GC freed 65977(3MB) AllocSpace objects, 11(1213KB) LOS objects, 36% free, 27MB/43MB, paused 1.901ms total 58.372ms
,I/wpa_supplicant( 4566): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3823): Started service discovery
,I/wpa_supplicant( 4566): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 4566): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 4566): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 4566): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3823): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT3940","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
I/        ( 3823): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT3940","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT3940, peerAddress: E0:DB:10:1F:C9:5E
,I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT3940, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/jxcore-log( 3823): 2015-12-04T09:01:01.181Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:01:01.182Z SendDataConnector.js: Connect (retry count 2) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T09:01:01.183Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:01:01.183Z SendDataConnector.js: do connect now
I/jxcore-log( 3823): 
,I/        ( 3823): Selected device address: E0:DB:10:14:E2:C0, name: Note4-1
,I/BTConnectToThread( 3823): Starting to connect,
W/BluetoothAdapter( 3823): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3823): Connecting to Note4-1, at E0:DB:10:14:E2:C0
,D/BTIF_SOCK( 2177): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-btif ( 2177): invalid rfc slot id: 50
,I/BtToSocketBase( 3823): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3823): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3823): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A300FU_PT7300
I/BtToSocketBase( 3823): Stop ReceivingThread
I/BtToSocketBase( 3823): Stop SendingThread
I/BtToSocketBase( 3823): Close local in
I/BtToSocketBase( 3823): Close LocalOutputStream
I/BtToSocketBase( 3823): Close localHostSocket
I/BtToSocketBase( 3823): Close bt in
,I/BtToSocketBase( 3823): Close bt out
I/BtToSocketBase( 3823): Close bt socket
I/jxcore-log( 3823): 2015-12-04T09:01:03.977Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3823): 
I/BtToSocketBase( 3823): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3823): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,W/bt-rfcomm( 2177): rfc_find_lcid_mcb LCID reused LCID:0x4a current:0x0
W/bt-rfcomm( 2177): RFCOMM_DisconnectInd LCID:0x4a
,W/bt-sdp  ( 2177): SDP - Rcvd conn cnf with error: 0x4  CID 0x4d,
E/bt-btif ( 2177): DISCOVERY_COMP_EVT slot id:53, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2177): invalid rfc slot id: 53
I/BTConnectToThread( 3823): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3823): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3823): 2015-12-04T09:01:06.343Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:01:06.344Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T09:01:06.345Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3823): 
,I/        ( 3823): Cleared service requests,
I/        ( 3823): Started peer discovery
,E/bt-btm  ( 2177): btm_sec_disconnected - Clearing Pending flag,
,D/BluetoothMapService( 2177): onReceive
,I/BTConnectionReceiver( 1523): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1523): Bluetooth Device Name: Thali Test (Galaxy A3)
,I/wpa_supplicant( 4566): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3823): Found 7 peers.
I/SS      ( 3823): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3823): Peer(2): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3823): Peer(3): Note3-1 ea:50:8b:de:28:a3
,I/SS      ( 3823): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3823): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3823): Peer(6): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3823): Peer(7): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3823): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3823): Added service request
,I/jxcore-log( 3823): 2015-12-04T09:01:11.347Z SendDataConnector.js: re-try now : E0:DB:10:14:E2:C0
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T09:01:11.348Z SendDataConnector.js: ReStart called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3823): 
,I/wpa_supplicant( 4566): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3823): Started service discovery
,I/wpa_supplicant( 4566): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 4566): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3823): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT3940","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT3940","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT3940, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT3940, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/jxcore-log( 3823): 2015-12-04T09:01:16.352Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:01:16.352Z SendDataConnector.js: Connect (retry count 3) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T09:01:16.353Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T09:01:16.354Z SendDataConnector.js: do connect now
I/jxcore-log( 3823): 
,I/        ( 3823): Selected device address: E0:DB:10:14:E2:C0, name: Note4-1
I/BTConnectToThread( 3823): Starting to connect
W/BluetoothAdapter( 3823): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3823): Connecting to Note4-1, at E0:DB:10:14:E2:C0
,D/BTIF_SOCK( 2177): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,I/        ( 3823): Cleared service requests
,I/        ( 3823): Started peer discovery
,W/bt-sdp  ( 2177): SDP - Rcvd conn cnf with error: 0x4  CID 0x48
,E/bt-btif ( 2177): DISCOVERY_COMP_EVT slot id:54, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2177): invalid rfc slot id: 54
I/BTConnectToThread( 3823): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3823): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3823): 2015-12-04T09:01:21.498Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:01:21.499Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T09:01:21.499Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3823): 
,I/wpa_supplicant( 4566): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 4566): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1,
,I/SS      ( 3823): Found 7 peers.
I/SS      ( 3823): Peer(1): S5-1 ee:1f:72:63:11:86,
I/SS      ( 3823): Peer(2): Note4-1 92:b6:86:43:73:1c
,I/SS      ( 3823): Peer(3): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3823): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3823): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3823): Peer(6): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3823): Peer(7): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3823): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3823): Added service request
,I/jxcore-log( 3823): 2015-12-04T09:01:26.500Z SendDataConnector.js: re-try now : E0:DB:10:14:E2:C0
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:01:26.501Z SendDataConnector.js: ReStart called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3823): 
,I/wpa_supplicant( 4566): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3823): Started service discovery
,I/wpa_supplicant( 4566): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/        ( 3823): Cleared service requests
,I/        ( 3823): Started peer discovery
,I/jxcore-log( 3823): 2015-12-04T09:01:31.504Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:01:31.504Z SendDataConnector.js: Connect (retry count 4) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T09:01:31.505Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T09:01:31.505Z SendDataConnector.js: do connect now
I/jxcore-log( 3823): 
I/        ( 3823): Selected device address: E0:DB:10:14:E2:C0, name: Note4-1
,I/BTConnectToThread( 3823): Starting to connect
W/BluetoothAdapter( 3823): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3823): Connecting to Note4-1, at E0:DB:10:14:E2:C0
,D/BTIF_SOCK( 2177): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-sdp  ( 2177): SDP - Rcvd conn cnf with error: 0x4  CID 0x43
,E/bt-btif ( 2177): DISCOVERY_COMP_EVT slot id:55, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2177): invalid rfc slot id: 55
I/BTConnectToThread( 3823): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3823): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3823): 2015-12-04T09:01:36.657Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:14:E2:C0 failed,
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T09:01:36.658Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:01:36.670Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T09:01:36.671Z SendDataConnector.js: Stop data retrieving timer
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:01:36.673Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3823): 
I/jxcore-log( 3823): ---- round done--------
,I/jxcore-log( 3823): 
I/jxcore-log( 3823): ---- gotta redo : E0:DB:10:14:E2:C0, try count now: 1
I/jxcore-log( 3823): 
I/jxcore-log( 3823): do fake peer & start
I/jxcore-log( 3823): 
I/jxcore-log( 3823): Connect to fake peer: E0:DB:10:1F:C9:5E
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T09:01:36.676Z SendDataConnector.js: Start called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:01:36.677Z SendDataConnector.js: doConnect called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:01:36.679Z SendDataConnector.js: do connect now
I/jxcore-log( 3823): 
I/        ( 3823): Selected device address: E0:DB:10:1F:C9:5E, name: null
,I/        ( 3823): Connecting to null, at E0:DB:10:1F:C9:5E
,I/chromium( 3823): [INFO:CONSOLE(63)] "logCallback Round of send data to peer E0:DB:10:14:E2:C0 done with result: Connection to E0:DB:10:14:E2:C0 failed", source: file:///android_asset/www/js/thali_main.js (63)
I/BTConnectToThread( 3823): Starting to connect
,W/BluetoothAdapter( 3823): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 2177): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,I/wpa_supplicant( 4566): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 4566): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 4566): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 4566): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 4566): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 4566): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,W/bt-btif ( 2177): info:x10
D/        ( 2177): remote version info [e0:db:10:1f:c9:5e]: 7, f, 6109
,E/BluetoothRemoteDevices( 2177): aclStateChangeCallback: Device is NULL,
,I/wpa_supplicant( 4566): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,W/bt-sdp  ( 2177): process_service_search_attr_rsp
,D/btif_config( 2177): btif_get_device_type: Device [e0:db:10:1f:c9:5e] type 1
,I/BluetoothBondStateMachine( 2177): bondStateChangeCallback: Status: 0 Address: E0:DB:10:1F:C9:5E newState: 1
,E/bt-btif ( 2177): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2177): Bond State Change Intent:E0:DB:10:1F:C9:5E OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2177): Entering PendingCommandState State
,I/wpa_supplicant( 4566): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/BluetoothBondStateMachine( 2177): bondStateChangeCallback: Status: 0 Address: E0:DB:10:1F:C9:5E newState: 0
,D/BluetoothAdapterProperties( 2177): Failed to remove device: E0:DB:10:1F:C9:5E
,I/BluetoothBondStateMachine( 2177): Bond State Change Intent:E0:DB:10:1F:C9:5E OldState: 11 NewState: 10,
,I/BluetoothBondStateMachine( 2177): StableState(): Entering Off State
,D/btif_config_util( 2177): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2177): tBTM_SEC_DEV:0xa2f185dc rs_disc_pending=0
W/bt-btif ( 2177): bta_dm_check_av:0
W/bt-btif ( 2177): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2177): new conn_srvc id:26, app_id:1
W/bt-btif ( 2177): bta_dm_pm_ssr conn_srvc id:26, app_id:1
I/BTConnectToThread( 3823): Starting to Handshake
W/bt-btif ( 2177): bta_dm_pm_ssr:2, lat:1200
I/BTHandshakeSocketThread( 3823): Creating BTHandshakeSocketThread
I/BTConnectToThread( 3823): MESSAGE_WRITE 82 bytes.
,I/BTHandshakeSocketThread( 3823): BTHandshakeSocketThread started,
,I/BTConnectToThread( 3823): got MESSAGE_READ 82 bytes.
,I/BTConnectToThread( 3823): Got JSON from encryption:{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT3940","ra":"E0:DB:10:1F:C9:5E"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTConnectToThread( 3823): HandshakeOk : samsung-SM-N9005_PT3940
I/HS      ( 3823): Hand Shake finished outgoing for : samsung-SM-N9005_PT3940
I/BTHandshakeSocketThread( 3823): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3823): Starting the connected thread incoming : false, samsung-SM-N9005_PT3940
,I/BtToSocketBase( 3823): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3823): Creating BtConnectedRequestSocket
I/BtToRequestSocket( 3823): mHTTPPort  set to : 45762
I/BtConnectorHelper( 3823): Request socket is using : 45762
,I/BtToRequestSocket( 3823): Now accepting connections
,I/BtConnectorHelper( 3823): Calling ConnectionStatusUpdate with port :45762
,I/jxcore-log( 3823): 2015-12-04T09:01:54.641Z SendDataConnector.js: CLIENT connected to 45762, error: null
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:01:54.641Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3823): 
,I/BtToRequestSocket( 3823): incoming data from: /127.0.0.1, port: 45762
,I/BtToRequestSocket( 3823): Set local streams
I/BtToRequestSocket( 3823): rin ended ---------------------------;
,I/jxcore-log( 3823): 2015-12-04T09:01:54.652Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3823): 
,I/wpa_supplicant( 4566): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3823): 2015-12-04T09:01:58.598Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3823): 
,D/HeadsetStateMachine( 2177): Disconnected process message: 10, size: 0
,I/jxcore-log( 3823): 2015-12-04T09:02:00.594Z SendDataConnector.js: CLIENT is data received : 20000,
I/jxcore-log( 3823): 
,V/GoogleAuthProtoRequest( 3945): [436] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1492): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1492): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1492): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1492): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1492): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  820): Explicit concurrent mark sweep GC freed 79153(3MB) AllocSpace objects, 3(236KB) LOS objects, 31% free, 34MB/50MB, paused 2.072ms total 81.945ms,
,W/ExperimentUpdateService( 3945): [436] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3945): [436] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3945): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3945): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3945): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3945): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3945): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3945): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3945): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3945): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3945): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3945): 	at com.a.a.k.run(SourceFile:110)
,I/jxcore-log( 3823): 2015-12-04T09:02:03.341Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3823): 
,W/bt-btm  ( 2177): btm_acl_role_changed -> Issuing delayed HCI_Disconnect!!!
E/bt-btm  ( 2177): tBTM_SEC_DEV:0xa2f17964 rs_disc_pending=2
,E/bt-btm  ( 2177): btm_sec_disconnected - Clearing Pending flag
,W/bt-btif ( 2177): bta_dm_check_av:0
,W/bt-btif ( 2177): btif_dm_cback : unhandled event (14)
D/BluetoothMapService( 2177): onReceive
,I/BTConnectionReceiver( 1523): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
I/BluetoothClassifier( 1523): Bluetooth Device Name: Nexus 5
,I/wpa_supplicant( 4566): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,W/bt-btif ( 2177): dm_pm_timer expires
W/bt-btif ( 2177): dm_pm_timer expires 0
W/bt-btif ( 2177): proc dm_pm_timer expires
,I/jxcore-log( 3823): 2015-12-04T09:02:13.341Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:02:13.341Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T09:02:13.342Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:02:13.343Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:02:13.344Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3823): 
,I/BtToSocketBase( 3823): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3823): Disconnect outgoing peer: samsung-SM-N9005_PT3940
I/BtToSocketBase( 3823): Stop ReceivingThread
I/BtToSocketBase( 3823): Stop SendingThread
,I/BtToSocketBase( 3823): Close local in
I/BtToSocketBase( 3823): Close LocalOutputStream
I/BtToSocketBase( 3823): Close localHostSocket
I/BtToSocketBase( 3823): Close bt in
I/BtToSocketBase( 3823): Close bt out
,I/BtToSocketBase( 3823): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtToSocketBase( 3823): Close bt socket
I/BtToRequestSocket( 3823): Close server socket
,D/HeadsetStateMachine( 2177): Disconnected process message: 10, size: 0
,W/bt-btif ( 2177): bta_jv_rfc_port_to_cb(port_handle:0xd):jv handle:0x0 not FOUND
,I/wpa_supplicant( 4566): P2P-DEVICE-FOUND 3a:94:96:b5:06:dd p2p_dev_addr=3a:94:96:b5:06:dd pri_dev_type=10-0050F204-5 name='Galaxy S5-2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,W/bt-btif ( 2177): info:x10
D/        ( 2177): remote version info [b0:c5:59:3f:75:69]: 7, f, 610c
,E/BluetoothRemoteDevices( 2177): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3823): 2015-12-04T09:02:18.345Z SendDataConnector.js: re-try now : E0:DB:10:1F:C9:5E
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T09:02:18.346Z SendDataConnector.js: ReStart called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3823): 
,D/btif_config( 2177): btif_get_device_type: Device [b0:c5:59:3f:75:69] type 1
,I/BluetoothBondStateMachine( 2177): bondStateChangeCallback: Status: 0 Address: B0:C5:59:3F:75:69 newState: 1
,E/bt-btif ( 2177): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2177): Bond State Change Intent:B0:C5:59:3F:75:69 OldState: 10 NewState: 11,
I/BluetoothBondStateMachine( 2177): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2177): bondStateChangeCallback: Status: 0 Address: B0:C5:59:3F:75:69 newState: 0
D/BluetoothAdapterProperties( 2177): Failed to remove device: B0:C5:59:3F:75:69
,I/BluetoothBondStateMachine( 2177): Bond State Change Intent:B0:C5:59:3F:75:69 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2177): StableState(): Entering Off State
,W/bt-btif ( 2177): new conn_srvc id:26, app_id:255
,W/bt-btif ( 2177): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2177): bta_dm_pm_ssr:2, lat:1200
I/BTListenerThread( 3823): we got incoming connection
,I/BTHandshakeSocketThread( 3823): Creating BTHandshakeSocketThread
I/BTListenerThread( 3823): waiting to accept incoming Connection
I/BTHandshakeSocketThread( 3823): BTHandshakeSocketThread started
,I/BTListenerThread( 3823): got MESSAGE_READ 82 bytes.,
I/BTListenerThread( 3823): Got JSON from encryption:{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2104","ra":"B0:C5:59:3F:75:69"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTListenerThread( 3823): MESSAGE_WRITE 82 bytes.,
I/HS      ( 3823): Incoming connection Hand Shake finished for : samsung-SM-G900F_PT2104
I/BTHandshakeSocketThread( 3823): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3823): Starting the connected thread incoming : true, samsung-SM-G900F_PT2104
I/BtToSocketBase( 3823): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3823): Creating BTConnectedThread
,I/BtConnectorHelper( 3823): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3823): --DoOneRunRound started
,I/BtToRequestSocket( 3823): LocalHost address: localhost/127.0.0.1, port: 48599
,I/BtToRequestSocket( 3823): --DoOneRunRound ended
,I/jxcore-log( 3823): 2015-12-04T09:02:20.084Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:02:21.015Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:02:21.063Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:02:21.069Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:02:21.072Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:02:21.118Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:02:21.121Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:02:21.179Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:02:21.220Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
,I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:02:21.445Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:02:21.451Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:02:21.505Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:02:21.643Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:02:21.871Z SendDataTCPServer.js: TCP/IP server has received 24576 bytes of data,
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:02:21.879Z SendDataTCPServer.js: TCP/IP server has received 26556 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:02:21.882Z SendDataTCPServer.js: TCP/IP server has received 28536 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:02:21.885Z SendDataTCPServer.js: TCP/IP server has received 30516 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:02:21.937Z SendDataTCPServer.js: TCP/IP server has received 32496 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:02:21.970Z SendDataTCPServer.js: TCP/IP server has received 34476 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:02:21.999Z SendDataTCPServer.js: TCP/IP server has received 36456 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:02:22.004Z SendDataTCPServer.js: TCP/IP server has received 38436 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:02:22.006Z SendDataTCPServer.js: TCP/IP server has received 40416 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:02:22.013Z SendDataTCPServer.js: TCP/IP server has received 42396 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:02:22.016Z SendDataTCPServer.js: TCP/IP server has received 44376 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:02:22.129Z SendDataTCPServer.js: TCP/IP server has received 46356 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:02:22.132Z SendDataTCPServer.js: TCP/IP server has received 48336 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:02:22.376Z SendDataTCPServer.js: TCP/IP server has received 50316 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:02:22.433Z SendDataTCPServer.js: TCP/IP server has received 52296 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:02:22.752Z SendDataTCPServer.js: TCP/IP server has received 54276 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:02:22.755Z SendDataTCPServer.js: TCP/IP server has received 56256 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:02:22.814Z SendDataTCPServer.js: TCP/IP server has received 58236 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:02:22.871Z SendDataTCPServer.js: TCP/IP server has received 60216 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:02:22.935Z SendDataTCPServer.js: TCP/IP server has received 62196 bytes of data
I/jxcore-log( 3823): 
,D/btif_config_util( 2177): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3823): 2015-12-04T09:02:22.970Z SendDataTCPServer.js: TCP/IP server has received 64176 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:02:22.987Z SendDataTCPServer.js: TCP/IP server has received 66156 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:02:22.994Z SendDataTCPServer.js: TCP/IP server has received 68136 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:02:23.041Z SendDataTCPServer.js: TCP/IP server has received 70116 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:02:23.046Z SendDataTCPServer.js: TCP/IP server has received 72096 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:02:23.094Z SendDataTCPServer.js: TCP/IP server has received 74076 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:02:23.154Z SendDataTCPServer.js: TCP/IP server has received 76056 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:02:23.163Z SendDataTCPServer.js: TCP/IP server has received 78036 bytes of data
,I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:02:23.166Z SendDataTCPServer.js: TCP/IP server has received 80016 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:02:23.172Z SendDataTCPServer.js: TCP/IP server has received 81996 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:02:23.210Z SendDataTCPServer.js: TCP/IP server has received 83976 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:02:23.220Z SendDataTCPServer.js: TCP/IP server has received 85956 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:02:23.224Z SendDataTCPServer.js: TCP/IP server has received 87936 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:02:23.228Z SendDataTCPServer.js: TCP/IP server has received 89916 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:02:23.332Z SendDataTCPServer.js: TCP/IP server has received 91896 bytes of data,
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:02:23.341Z SendDataTCPServer.js: TCP/IP server has received 93876 bytes of data,
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:02:23.350Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:02:23.351Z SendDataConnector.js: Connect (retry count 1) to peer E0:DB:10:1F:C9:5E with availability status: true
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T09:02:23.351Z SendDataConnector.js: doConnect called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T09:02:23.352Z SendDataConnector.js: do connect now
,I/jxcore-log( 3823): 
,I/        ( 3823): Selected device address: E0:DB:10:1F:C9:5E, name: Note3-1
,I/        ( 3823): Connecting to Note3-1, at E0:DB:10:1F:C9:5E
I/BTConnectToThread( 3823): Starting to connect
W/BluetoothAdapter( 3823): getBluetoothService() called with no BluetoothManagerCallback,
,D/BTIF_SOCK( 2177): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,I/jxcore-log( 3823): 2015-12-04T09:02:23.380Z SendDataTCPServer.js: TCP/IP server has received 95856 bytes of data
,I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:02:23.826Z SendDataTCPServer.js: TCP/IP server has received 97836 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:02:23.959Z SendDataTCPServer.js: TCP/IP server has received 99816 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:02:23.962Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3823): 
,E/bt-btif ( 2177): DISCOVERY_COMP_EVT slot id:58, failed to find channle,                                       status:1, scn:0,
,W/bt-btif ( 2177): invalid rfc slot id: 58
I/BTConnectToThread( 3823): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,E/bt-btm  ( 2177): btm_sec_disconnected - Clearing Pending flag
I/CONNEC  ( 3823): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3823): 2015-12-04T09:02:25.417Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:1F:C9:5E failed,
I/jxcore-log( 3823): 
,D/BluetoothMapService( 2177): onReceive
I/jxcore-log( 3823): 2015-12-04T09:02:25.420Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:1F:C9:5E failed
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T09:02:25.422Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3823): 
,I/BTConnectionReceiver( 1523): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1523): Bluetooth Device Name: Note3-1,
,I/        ( 3823): Cleared service requests
,I/        ( 3823): Started peer discovery,
,I/wpa_supplicant( 4566): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 4566): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 4566): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3823): Found 13 peers.
I/SS      ( 3823): Peer(1): S5-1 ee:1f:72:63:11:86
,I/SS      ( 3823): Peer(2): Galaxy S5-2 3a:94:96:b5:06:dd
I/SS      ( 3823): Peer(3): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3823): Peer(4): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3823): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3823): Peer(6): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3823): Peer(7): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3823): Peer(8): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3823): Peer(9): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3823): Peer(10): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3823): Peer(11): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3823): Peer(12): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 3823): Peer(13): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3823): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3823): Added service request
,I/wpa_supplicant( 4566): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3823): Started service discovery
,I/wpa_supplicant( 4566): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3823): 2015-12-04T09:02:30.422Z SendDataConnector.js: re-try now : E0:DB:10:1F:C9:5E
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:02:30.423Z SendDataConnector.js: ReStart called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3823): 
,I/        ( 3823): Found Service, :{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2104","ra":"B0:C5:59:3F:75:69"}, typeCordovap2p._tcp.local.:
I/        ( 3823): JsonLine: {"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2104","ra":"B0:C5:59:3F:75:69"} -- peerIdentifier:B0:C5:59:3F:75:69, peerName: samsung-SM-G900F_PT2104, peerAddress: B0:C5:59:3F:75:69
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : B0:C5:59:3F:75:69, Name: samsung-SM-G900F_PT2104, WifiDirectName: Thali Test (Galaxy S5), WifiDirect Address: ee:1f:72:18:8b:78, peerId: B0:C5:59:3F:75:69
,W/bt-btif ( 2177): invalid rfc slot id: 52,
,I/BtToSocketBase( 3823): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3823): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3823): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G900F_PT2104
I/BtToSocketBase( 3823): Stop ReceivingThread
I/BtToSocketBase( 3823): Stop SendingThread
I/BtToSocketBase( 3823): Close local in
I/BtToSocketBase( 3823): Close LocalOutputStream
I/BtToSocketBase( 3823): Close localHostSocket
I/BtToSocketBase( 3823): Close bt in
I/BtToSocketBase( 3823): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3823): Close bt out
I/BtConnectorHelper( 3823): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3823): Close bt socket
I/BtConnectorHelper( 3823): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G900F_PT2104
I/BtToSocketBase( 3823): Close bt in
I/BtToSocketBase( 3823): Close bt out
I/BtToSocketBase( 3823): Close bt socket
I/jxcore-log( 3823): 2015-12-04T09:02:33.629Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3823): 
,I/        ( 3823): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT5230","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
I/        ( 3823): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT5230","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT5230, peerAddress: F8:95:C7:87:85:54
,I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT5230, WifiDirectName: G3s-1, WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54,
,I/        ( 3823): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT7300","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT7300","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT7300, peerAddress: 08:EC:A9:50:76:27
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT7300, WifiDirectName: Thali Test (Galaxy A3), WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,I/        ( 3823): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT3940","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT3940","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT3940, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT3940, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/jxcore-log( 3823): 2015-12-04T09:02:35.427Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:02:35.428Z SendDataConnector.js: Connect (retry count 2) to peer E0:DB:10:1F:C9:5E with availability status: true
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T09:02:35.429Z SendDataConnector.js: doConnect called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:02:35.429Z SendDataConnector.js: do connect now
I/jxcore-log( 3823): 
,I/        ( 3823): Selected device address: E0:DB:10:1F:C9:5E, name: Note3-1
,I/BTConnectToThread( 3823): Starting to connect
,W/BluetoothAdapter( 3823): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3823): Connecting to Note3-1, at E0:DB:10:1F:C9:5E
,D/BTIF_SOCK( 2177): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-rfcomm( 2177): rfc_find_lcid_mcb LCID reused LCID:0x4c current:0x0
,W/bt-rfcomm( 2177): RFCOMM_DisconnectInd LCID:0x4c
,I/        ( 3823): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5358"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5358"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT5358, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT5358, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,W/bt-btif ( 2177): info:x10
,D/        ( 2177): remote version info [e0:db:10:1f:c9:5e]: 7, f, 6109
,I/BTConnectionReceiver( 1523): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1523): Bluetooth Device Name: Note3-1
,E/bt-btm  ( 2177): tBTM_SEC_DEV:0xa2f185dc rs_disc_pending=1
W/bt-btif ( 2177): bta_dm_check_av:0
W/bt-btif ( 2177): btif_dm_cback : unhandled event (14),
,E/bt-btm  ( 2177): tBTM_SEC_DEV:0xa2f185dc rs_disc_pending=0
,W/bt-btif ( 2177): bta_dm_check_av:0
,W/bt-btif ( 2177): btif_dm_cback : unhandled event (14)
,I/        ( 3823): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1124","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1124","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT1124, peerAddress: F8:95:C7:87:3C:51
,I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT1124, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,E/bt-btm  ( 2177): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2177): onReceive
,I/BTConnectionReceiver( 1523): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1523): Bluetooth Device Name: Thali Test (Galaxy S5),
,W/bt-sdp  ( 2177): process_service_search_attr_rsp
,D/btif_config_util( 2177): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 2177): new conn_srvc id:26, app_id:1
,W/bt-btif ( 2177): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2177): bta_dm_pm_ssr:2, lat:1200
I/BTConnectToThread( 3823): Starting to Handshake
,I/BTHandshakeSocketThread( 3823): Creating BTHandshakeSocketThread
I/BTConnectToThread( 3823): MESSAGE_WRITE 82 bytes.
,I/BTHandshakeSocketThread( 3823): BTHandshakeSocketThread started
,I/wpa_supplicant( 4566): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1,
,I/wpa_supplicant( 4566): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/BTConnectToThread( 3823): got MESSAGE_READ 82 bytes.
I/BTConnectToThread( 3823): Got JSON from encryption:{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT3940","ra":"E0:DB:10:1F:C9:5E"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3823): HandshakeOk : samsung-SM-N9005_PT3940
I/HS      ( 3823): Hand Shake finished outgoing for : samsung-SM-N9005_PT3940
I/BTHandshakeSocketThread( 3823): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3823): Starting the connected thread incoming : false, samsung-SM-N9005_PT3940
I/BtToSocketBase( 3823): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3823): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3823): mHTTPPort  set to : 34535
,I/BtConnectorHelper( 3823): Request socket is using : 34535
I/BtToRequestSocket( 3823): Now accepting connections
,I/BtConnectorHelper( 3823): Calling ConnectionStatusUpdate with port :34535
,I/jxcore-log( 3823): 2015-12-04T09:02:41.820Z SendDataConnector.js: CLIENT connected to 34535, error: null,
,I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:02:41.821Z SendDataConnector.js: CLIENT starting client ,
I/jxcore-log( 3823): 
,I/BtToRequestSocket( 3823): incoming data from: /127.0.0.1, port: 34535
,I/BtToRequestSocket( 3823): Set local streams
,I/BtToRequestSocket( 3823): rin ended ---------------------------;
,I/jxcore-log( 3823): 2015-12-04T09:02:41.827Z SendDataConnector.js: CLIENT now sending 70000 bytes of data
,I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:02:44.279Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3823): 
,W/bt-btif ( 2177): info:x10
,D/        ( 2177): remote version info [b0:c5:59:3f:75:69]: 7, f, 610c
,I/BTConnectionReceiver( 1523): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1523): Bluetooth Device Name: Thali Test (Galaxy S5),
,E/bt-btm  ( 2177): tBTM_SEC_DEV:0xa2f185dc rs_disc_pending=1
W/bt-btif ( 2177): bta_dm_check_av:0
W/bt-btif ( 2177): btif_dm_cback : unhandled event (14)
,I/        ( 3823): Cleared service requests
,I/        ( 3823): Started peer discovery
,I/jxcore-log( 3823): 2015-12-04T09:02:45.427Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3823): 
,I/wpa_supplicant( 4566): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 4566): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3823): Found 13 peers.
I/SS      ( 3823): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3823): Peer(2): Galaxy S5-2 3a:94:96:b5:06:dd
I/SS      ( 3823): Peer(3): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3823): Peer(4): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3823): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3823): Peer(6): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3823): Peer(7): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3823): Peer(8): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3823): Peer(9): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3823): Peer(10): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3823): Peer(11): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3823): Peer(12): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 3823): Peer(13): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3823): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3823): Added service request
,I/jxcore-log( 3823): 2015-12-04T09:02:45.828Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3823): 
,W/bt-btif ( 2177): new conn_srvc id:26, app_id:255
,W/bt-btif ( 2177): bta_dm_pm_ssr conn_srvc id:26, app_id:255,
W/bt-btif ( 2177): bta_dm_pm_ssr:2, lat:1200
I/BTListenerThread( 3823): we got incoming connection
I/BTHandshakeSocketThread( 3823): Creating BTHandshakeSocketThread
I/BTListenerThread( 3823): waiting to accept incoming Connection
I/BTHandshakeSocketThread( 3823): BTHandshakeSocketThread started
,I/jxcore-log( 3823): 2015-12-04T09:02:46.183Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3823): 
,I/BTListenerThread( 3823): got MESSAGE_READ 82 bytes.,
,I/BTListenerThread( 3823): Got JSON from encryption:{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2104","ra":"B0:C5:59:3F:75:69"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3823): MESSAGE_WRITE 82 bytes.
I/HS      ( 3823): Incoming connection Hand Shake finished for : samsung-SM-G900F_PT2104
I/BTHandshakeSocketThread( 3823): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3823): Starting the connected thread incoming : true, samsung-SM-G900F_PT2104
I/BtToSocketBase( 3823): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3823): Creating BTConnectedThread
,I/BtConnectorHelper( 3823): Server socket is using : 0, and is now connected.
I/BtToRequestSocket( 3823): --DoOneRunRound started
,I/BtToRequestSocket( 3823): LocalHost address: localhost/127.0.0.1, port: 48599
,I/BtToRequestSocket( 3823): --DoOneRunRound ended
I/jxcore-log( 3823): 2015-12-04T09:02:46.281Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:02:46.364Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3823): 
,I/wpa_supplicant( 4566): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 4566): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3823): Started service discovery
,I/jxcore-log( 3823): 2015-12-04T09:02:46.835Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:02:46.861Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:02:46.916Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:02:47.046Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3823): 
,I/wpa_supplicant( 4566): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 4566): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 4566): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3823): 2015-12-04T09:02:47.340Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:02:47.394Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 3823): 
,I/        ( 3823): Found Service, :{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT8320"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT8320"} -- peerIdentifier:38:94:96:B5:06:DC, peerName: samsung-SM-G800H_PT8320, peerAddress: 38:94:96:B5:06:DC
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : 38:94:96:B5:06:DC, Name: samsung-SM-G800H_PT8320, WifiDirectName: Galaxy S5-2, WifiDirect Address: 3a:94:96:b5:06:dd, peerId: 38:94:96:B5:06:DC
,D/btif_config_util( 2177): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2177): tBTM_SEC_DEV:0xa2f185dc rs_disc_pending=0
,W/bt-btif ( 2177): bta_dm_check_av:0
W/bt-btif ( 2177): btif_dm_cback : unhandled event (14)
,I/        ( 3823): Found Service, :{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2104","ra":"B0:C5:59:3F:75:69"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2104","ra":"B0:C5:59:3F:75:69"} -- peerIdentifier:B0:C5:59:3F:75:69, peerName: samsung-SM-G900F_PT2104, peerAddress: B0:C5:59:3F:75:69
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : B0:C5:59:3F:75:69, Name: samsung-SM-G900F_PT2104, WifiDirectName: Thali Test (Galaxy S5), WifiDirect Address: ee:1f:72:18:8b:78, peerId: B0:C5:59:3F:75:69
,I/BooksSync( 3710): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3710): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1492): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1492): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1492): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1492): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1492): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1492): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1492): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1492): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1492): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1492): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3710): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3710): Soft error
E/BooksSync( 3710): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3710): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3710): Sync error
E/BooksSync( 3710): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3710): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3710): Finished books sync
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1197079, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,W/bt-btif ( 2177): dm_pm_timer expires
W/bt-btif ( 2177): dm_pm_timer expires 0
W/bt-btif ( 2177): proc dm_pm_timer expires
,I/        ( 3823): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT5230","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT5230","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT5230, peerAddress: F8:95:C7:87:85:54
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT5230, WifiDirectName: G3s-1, WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,I/        ( 3823): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT7300","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
I/        ( 3823): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT7300","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT7300, peerAddress: 08:EC:A9:50:76:27
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT7300, WifiDirectName: Thali Test (Galaxy A3), WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,I/jxcore-log( 3823): 2015-12-04T09:02:56.835Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T09:02:56.836Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:02:56.837Z SendDataConnector.js: CLIENT closeClientSocket,
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T09:02:56.838Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T09:02:56.840Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3823): 
I/BtToSocketBase( 3823): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3823): Disconnect outgoing peer: samsung-SM-N9005_PT3940
I/BtToSocketBase( 3823): Stop ReceivingThread
,I/BtToSocketBase( 3823): Stop SendingThread
I/BtToSocketBase( 3823): Close local in
,I/BtToSocketBase( 3823): Close LocalOutputStream
,I/BtToSocketBase( 3823): Close localHostSocket
I/BtToSocketBase( 3823): Close bt in
I/BtToSocketBase( 3823): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3823): Close bt out
,I/BtToSocketBase( 3823): Close bt socket
I/BtToRequestSocket( 3823): Close server socket
,W/bt-btif ( 2177): invalid rfc slot id: 57,
,I/BtToSocketBase( 3823): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1,
I/BtConnectorHelper( 3823): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3823): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G900F_PT2104
I/BtToSocketBase( 3823): Stop ReceivingThread
I/BtToSocketBase( 3823): Stop SendingThread
,I/BtToSocketBase( 3823): Close local in
I/BtToSocketBase( 3823): Close LocalOutputStream
I/BtToSocketBase( 3823): Close localHostSocket
I/BtToSocketBase( 3823): Close bt in
I/BtToSocketBase( 3823): Close bt out
,I/BtToSocketBase( 3823): Close bt socket
I/BtToSocketBase( 3823): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3823): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/jxcore-log( 3823): 2015-12-04T09:02:57.065Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3823): 
,E/bt-btm  ( 2177): tBTM_SEC_DEV:0xa2f185dc rs_disc_pending=1,
W/bt-btif ( 2177): bta_dm_check_av:0
,W/bt-btif ( 2177): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2177): bta_jv_rfc_port_to_cb(port_handle:0xf):jv handle:0x0 not FOUND
,E/bt-btm  ( 2177): tBTM_SEC_DEV:0xa2f185dc rs_disc_pending=0
W/bt-btif ( 2177): bta_dm_check_av:0
,W/bt-btif ( 2177): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 2177): rfc_find_lcid_mcb LCID reused LCID:0x41 current:0x0
,W/bt-rfcomm( 2177): RFCOMM_DisconnectInd LCID:0x41
,I/        ( 3823): Cleared service requests
,I/        ( 3823): Started peer discovery
,D/HeadsetStateMachine( 2177): Disconnected process message: 10, size: 0
,E/bt-btm  ( 2177): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2177): onReceive
,I/BTConnectionReceiver( 1523): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1523): Bluetooth Device Name: Note3-1
,I/jxcore-log( 3823): 2015-12-04T09:03:01.840Z SendDataConnector.js: re-try now : E0:DB:10:1F:C9:5E
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T09:03:01.841Z SendDataConnector.js: ReStart called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3823): 
,E/bt-btm  ( 2177): btm_sec_disconnected - Clearing Pending flag,
,D/BluetoothMapService( 2177): onReceive
,I/BTConnectionReceiver( 1523): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1523): Bluetooth Device Name: Thali Test (Galaxy S5),
,I/wpa_supplicant( 4566): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 4566): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 4566): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 4566): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/SS      ( 3823): Found 13 peers.
I/SS      ( 3823): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3823): Peer(2): Galaxy S5-2 3a:94:96:b5:06:dd
I/SS      ( 3823): Peer(3): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3823): Peer(4): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3823): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3823): Peer(6): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3823): Peer(7): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3823): Peer(8): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3823): Peer(9): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3823): Peer(10): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3823): Peer(11): S5mini-1 02:f4:6f:30:e0:6d
,I/SS      ( 3823): Peer(12): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 3823): Peer(13): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3823): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3823): Added service request
,I/jxcore-log( 3823): 2015-12-04T09:03:06.845Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:03:06.846Z SendDataConnector.js: Connect (retry count 3) to peer E0:DB:10:1F:C9:5E with availability status: true
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T09:03:06.846Z SendDataConnector.js: doConnect called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:03:06.847Z SendDataConnector.js: do connect now
I/jxcore-log( 3823): 
,I/        ( 3823): Selected device address: E0:DB:10:1F:C9:5E, name: Note3-1
,I/BTConnectToThread( 3823): Starting to connect
,W/BluetoothAdapter( 3823): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3823): Connecting to Note3-1, at E0:DB:10:1F:C9:5E
,D/BTIF_SOCK( 2177): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,I/wpa_supplicant( 4566): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 4566): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3823): Started service discovery
,W/bt-btif ( 2177): info:x10,
D/        ( 2177): remote version info [e0:db:10:1f:c9:5e]: 7, f, 6109
,I/BTConnectionReceiver( 1523): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1523): Bluetooth Device Name: Note3-1
,I/wpa_supplicant( 4566): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 4566): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,W/bt-sdp  ( 2177): process_service_search_attr_rsp
,W/bt-btif ( 2177): info:x10
,D/        ( 2177): remote version info [b0:c5:59:3f:75:69]: 7, f, 610c
,I/BTConnectionReceiver( 1523): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1523): Bluetooth Device Name: Thali Test (Galaxy S5),
,E/bt-btm  ( 2177): tBTM_SEC_DEV:0xa2f185dc rs_disc_pending=1
W/bt-btif ( 2177): bta_dm_check_av:0
,W/bt-btif ( 2177): btif_dm_cback : unhandled event (14)
,I/        ( 3823): Found Service, :{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT8320"}, typeCordovap2p._tcp.local.:,
I/        ( 3823): JsonLine: {"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT8320"} -- peerIdentifier:38:94:96:B5:06:DC, peerName: samsung-SM-G800H_PT8320, peerAddress: 38:94:96:B5:06:DC
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : 38:94:96:B5:06:DC, Name: samsung-SM-G800H_PT8320, WifiDirectName: Galaxy S5-2, WifiDirect Address: 3a:94:96:b5:06:dd, peerId: 38:94:96:B5:06:DC
,I/        ( 3823): Found Service, :{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2104","ra":"B0:C5:59:3F:75:69"}, typeCordovap2p._tcp.local.:,
I/        ( 3823): JsonLine: {"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2104","ra":"B0:C5:59:3F:75:69"} -- peerIdentifier:B0:C5:59:3F:75:69, peerName: samsung-SM-G900F_PT2104, peerAddress: B0:C5:59:3F:75:69
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : B0:C5:59:3F:75:69, Name: samsung-SM-G900F_PT2104, WifiDirectName: Thali Test (Galaxy S5), WifiDirect Address: ee:1f:72:18:8b:78, peerId: B0:C5:59:3F:75:69
,W/bt-btif ( 2177): new conn_srvc id:26, app_id:1
,W/bt-btif ( 2177): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2177): bta_dm_pm_ssr:2, lat:1200
I/BTConnectToThread( 3823): Starting to Handshake
,I/BTHandshakeSocketThread( 3823): Creating BTHandshakeSocketThread
I/BTConnectToThread( 3823): MESSAGE_WRITE 82 bytes.
I/BTHandshakeSocketThread( 3823): BTHandshakeSocketThread started
,I/BTConnectToThread( 3823): got MESSAGE_READ 82 bytes.
,I/BTConnectToThread( 3823): Got JSON from encryption:{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT3940","ra":"E0:DB:10:1F:C9:5E"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3823): HandshakeOk : samsung-SM-N9005_PT3940
I/HS      ( 3823): Hand Shake finished outgoing for : samsung-SM-N9005_PT3940
,I/BTHandshakeSocketThread( 3823): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3823): Starting the connected thread incoming : false, samsung-SM-N9005_PT3940
,I/BtToSocketBase( 3823): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3823): Creating BtConnectedRequestSocket
I/BtToRequestSocket( 3823): mHTTPPort  set to : 45258
,I/BtConnectorHelper( 3823): Request socket is using : 45258
I/BtToRequestSocket( 3823): Now accepting connections
,W/bt-btif ( 2177): new conn_srvc id:26, app_id:255
,W/bt-btif ( 2177): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2177): bta_dm_pm_ssr:2, lat:1200
I/BTListenerThread( 3823): we got incoming connection
I/BTHandshakeSocketThread( 3823): Creating BTHandshakeSocketThread
,I/BTListenerThread( 3823): waiting to accept incoming Connection
I/BTHandshakeSocketThread( 3823): BTHandshakeSocketThread started
,I/BTListenerThread( 3823): got MESSAGE_READ 82 bytes.
,I/BTListenerThread( 3823): Got JSON from encryption:{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2104","ra":"B0:C5:59:3F:75:69"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTListenerThread( 3823): MESSAGE_WRITE 82 bytes.
I/HS      ( 3823): Incoming connection Hand Shake finished for : samsung-SM-G900F_PT2104
I/BTHandshakeSocketThread( 3823): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3823): Starting the connected thread incoming : true, samsung-SM-G900F_PT2104
I/BtToSocketBase( 3823): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3823): Creating BTConnectedThread
,I/BtConnectorHelper( 3823): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3823): --DoOneRunRound started
,I/BtToRequestSocket( 3823): LocalHost address: localhost/127.0.0.1, port: 48599
,I/jxcore-log( 3823): 2015-12-04T09:03:09.264Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3823): 
I/BtToRequestSocket( 3823): --DoOneRunRound ended
,I/BtConnectorHelper( 3823): Calling ConnectionStatusUpdate with port :45258
,I/jxcore-log( 3823): 2015-12-04T09:03:09.336Z SendDataConnector.js: CLIENT connected to 45258, error: null
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T09:03:09.337Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3823): 
,I/BtToRequestSocket( 3823): incoming data from: /127.0.0.1, port: 45258
I/BtToRequestSocket( 3823): Set local streams
,I/BtToRequestSocket( 3823): rin ended ---------------------------;
,I/jxcore-log( 3823): 2015-12-04T09:03:09.345Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:03:09.803Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:03:09.810Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:03:09.874Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:03:09.879Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:03:09.934Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:03:09.941Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 3823): 
,D/btif_config_util( 2177): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 2177): dm_pm_timer expires,
W/bt-btif ( 2177): dm_pm_timer expires 0
W/bt-btif ( 2177): proc dm_pm_timer expires
,D/HeadsetStateMachine( 2177): Disconnected process message: 10, size: 0
,I/        ( 3823): Cleared service requests
I/        ( 3823): Started peer discovery
,I/wpa_supplicant( 4566): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3823): Found 13 peers.
I/SS      ( 3823): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3823): Peer(2): Galaxy S5-2 3a:94:96:b5:06:dd
I/SS      ( 3823): Peer(3): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3823): Peer(4): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3823): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
,I/SS      ( 3823): Peer(6): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3823): Peer(7): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3823): Peer(8): G4-1 a2:39:f7:6f:c9:5d
,I/SS      ( 3823): Peer(9): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3823): Peer(10): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3823): Peer(11): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3823): Peer(12): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 3823): Peer(13): Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pManager( 3823): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3823): Added service request
,I/wpa_supplicant( 4566): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3823): Started service discovery
,I/wpa_supplicant( 4566): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 4566): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3823): Found Service, :{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT8320"}, typeCordovap2p._tcp.local.:,
I/        ( 3823): JsonLine: {"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT8320"} -- peerIdentifier:38:94:96:B5:06:DC, peerName: samsung-SM-G800H_PT8320, peerAddress: 38:94:96:B5:06:DC
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : 38:94:96:B5:06:DC, Name: samsung-SM-G800H_PT8320, WifiDirectName: Galaxy S5-2, WifiDirect Address: 3a:94:96:b5:06:dd, peerId: 38:94:96:B5:06:DC
,I/        ( 3823): Found Service, :{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2104","ra":"B0:C5:59:3F:75:69"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2104","ra":"B0:C5:59:3F:75:69"} -- peerIdentifier:B0:C5:59:3F:75:69, peerName: samsung-SM-G900F_PT2104, peerAddress: B0:C5:59:3F:75:69
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : B0:C5:59:3F:75:69, Name: samsung-SM-G900F_PT2104, WifiDirectName: Thali Test (Galaxy S5), WifiDirect Address: ee:1f:72:18:8b:78, peerId: B0:C5:59:3F:75:69
,I/        ( 3823): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT5230","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT5230","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT5230, peerAddress: F8:95:C7:87:85:54
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT5230, WifiDirectName: G3s-1, WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,I/jxcore-log( 3823): 2015-12-04T09:03:19.407Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:03:19.407Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T09:03:19.409Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:03:19.410Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:03:19.411Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3823): 
,I/BtToSocketBase( 3823): SendingThread thread got error: input stream got -1 on read,
I/BtConnectorHelper( 3823): Disconnect outgoing peer: samsung-SM-N9005_PT3940
I/BtToSocketBase( 3823): Stop ReceivingThread
,I/BtToSocketBase( 3823): Stop SendingThread
I/BtToSocketBase( 3823): Close local in
,I/BtToSocketBase( 3823): Close LocalOutputStream
I/BtToSocketBase( 3823): Close localHostSocket
,I/BtToSocketBase( 3823): Close bt in
I/BtToSocketBase( 3823): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1,
I/BtToSocketBase( 3823): Close bt out
I/BtToSocketBase( 3823): Close bt socket
I/BtToRequestSocket( 3823): Close server socket
,W/bt-btif ( 2177): bta_jv_rfc_port_to_cb(port_handle:0x11):jv handle:0x0 not FOUND,
,I/GLSUser ( 1492): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1492): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1492): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1492): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1492): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3215): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3215): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3215): 	at jdm.a(PG:82)
E/HttpOperation( 3215): 	at jcs.o(PG:406)
E/HttpOperation( 3215): 	at jcn.a(PG:1379)
E/HttpOperation( 3215): 	at jcs.i(PG:143)
E/HttpOperation( 3215): 	at blb.a(PG:3937)
E/HttpOperation( 3215): 	at czp.a(PG:18188)
E/HttpOperation( 3215): 	at czp.a(PG:9087)
E/HttpOperation( 3215): 	at czq.run(PG:1686)
E/HttpOperation( 3215): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3215): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3215): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3215): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3215): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3215): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3215): 	at jdj.a(PG:4091)
E/HttpOperation( 3215): 	at jdj.a(PG:1125)
E/HttpOperation( 3215): 	at jdm.a(PG:77)
E/HttpOperation( 3215): 	... 12 more
E/HttpOperation( 3215): Caused by: faj: BadAuthentication
E/HttpOperation( 3215): 	at fal.a(PG:38)
E/HttpOperation( 3215): 	at jdj.a(PG:4089)
E/HttpOperation( 3215): 	... 14 more
,E/bt-btm  ( 2177): tBTM_SEC_DEV:0xa2f18414 rs_disc_pending=0
W/bt-btif ( 2177): bta_dm_check_av:0
W/bt-btif ( 2177): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2177): invalid rfc slot id: 60,
I/BtToSocketBase( 3823): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1,
I/BtConnectorHelper( 3823): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3823): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G900F_PT2104
I/BtToSocketBase( 3823): Stop ReceivingThread
I/BtToSocketBase( 3823): Stop SendingThread
I/BtToSocketBase( 3823): Close local in
,I/BtToSocketBase( 3823): Close LocalOutputStream
I/BtToSocketBase( 3823): Close localHostSocket
I/BtToSocketBase( 3823): Close bt in
I/BtToSocketBase( 3823): Close bt out
I/BtToSocketBase( 3823): Close bt socket
I/BtToSocketBase( 3823): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3823): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3823): 2015-12-04T09:03:20.408Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3823): 
,I/GLSUser ( 1492): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1492): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1492): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1492): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1492): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/HttpOperation( 3215): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3215): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3215): 	at jdm.a(PG:82)
E/HttpOperation( 3215): 	at jcs.o(PG:406)
E/HttpOperation( 3215): 	at jcn.a(PG:1379)
E/HttpOperation( 3215): 	at jcs.i(PG:143)
E/HttpOperation( 3215): 	at blb.a(PG:3937)
E/HttpOperation( 3215): 	at czp.a(PG:18188)
E/HttpOperation( 3215): 	at czp.a(PG:9081)
E/HttpOperation( 3215): 	at czq.run(PG:1686)
E/HttpOperation( 3215): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3215): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3215): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3215): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3215): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3215): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3215): 	at jdj.a(PG:4091)
E/HttpOperation( 3215): 	at jdj.a(PG:1125)
E/HttpOperation( 3215): 	at jdm.a(PG:77)
E/HttpOperation( 3215): 	... 12 more
E/HttpOperation( 3215): Caused by: faj: BadAuthentication
E/HttpOperation( 3215): 	at fal.a(PG:38)
E/HttpOperation( 3215): 	at jdj.a(PG:4089)
E/HttpOperation( 3215): 	... 14 more
,I/GLSUser ( 1492): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1492): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1492): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1492): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1492): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/        ( 3823): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT7300","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
I/        ( 3823): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT7300","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT7300, peerAddress: 08:EC:A9:50:76:27
,I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT7300, WifiDirectName: Thali Test (Galaxy A3), WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,E/HttpOperation( 3215): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3215): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3215): 	at jdm.a(PG:82)
E/HttpOperation( 3215): 	at jcs.o(PG:406)
E/HttpOperation( 3215): 	at jcn.a(PG:1379)
E/HttpOperation( 3215): 	at jcs.i(PG:143)
E/HttpOperation( 3215): 	at hec.a(PG:42)
E/HttpOperation( 3215): 	at hee.a(PG:102)
E/HttpOperation( 3215): 	at czr.a(PG:65)
E/HttpOperation( 3215): 	at kka.a(PG:108)
E/HttpOperation( 3215): 	at czp.a(PG:19176)
E/HttpOperation( 3215): 	at czp.a(PG:9081)
E/HttpOperation( 3215): 	at czq.run(PG:1686)
E/HttpOperation( 3215): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3215): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3215): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3215): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3215): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3215): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3215): 	at jdj.a(PG:4091)
E/HttpOperation( 3215): 	at jdj.a(PG:1125)
E/HttpOperation( 3215): 	at jdm.a(PG:77)
E/HttpOperation( 3215): 	... 15 more
E/HttpOperation( 3215): Caused by: faj: BadAuthentication
E/HttpOperation( 3215): 	at fal.a(PG:38)
E/HttpOperation( 3215): 	at jdj.a(PG:4089)
E/HttpOperation( 3215): 	... 17 more
,E/ExperimentLoader( 3215): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3215): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3215): 	at jdm.a(PG:82)
E/ExperimentLoader( 3215): 	at jcs.o(PG:406)
E/ExperimentLoader( 3215): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3215): 	at jcs.i(PG:143)
E/ExperimentLoader( 3215): 	at hec.a(PG:42)
E/ExperimentLoader( 3215): 	at hee.a(PG:102)
E/ExperimentLoader( 3215): 	at czr.a(PG:65)
E/ExperimentLoader( 3215): 	at kka.a(PG:108)
E/ExperimentLoader( 3215): 	at czp.a(PG:19176)
E/ExperimentLoader( 3215): 	at czp.a(PG:9081)
E/ExperimentLoader( 3215): 	at czq.run(PG:1686)
E/ExperimentLoader( 3215): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422),
E/ExperimentLoader( 3215): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3215): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3215): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3215): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3215): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3215): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3215): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3215): 	at jdm.a(PG:77)
E/ExperimentLoader( 3215): 	... 15 more
,E/ExperimentLoader( 3215): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3215): 	at fal.a(PG:38)
E/ExperimentLoader( 3215): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3215): 	... 17 more
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 755203, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,E/bt-btm  ( 2177): tBTM_SEC_DEV:0xa2f18414 rs_disc_pending=1
,W/bt-btif ( 2177): bta_dm_check_av:0
W/bt-btif ( 2177): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 2177): rfc_find_lcid_mcb LCID reused LCID:0x4a current:0x0
,W/bt-rfcomm( 2177): RFCOMM_DisconnectInd LCID:0x4a
,E/bt-btm  ( 2177): tBTM_SEC_DEV:0xa2f18414 rs_disc_pending=0
W/bt-btif ( 2177): bta_dm_check_av:0
W/bt-btif ( 2177): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3823): 2015-12-04T09:03:24.412Z SendDataConnector.js: re-try now : E0:DB:10:1F:C9:5E
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T09:03:24.412Z SendDataConnector.js: ReStart called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3823): 
,I/UsageStatsService(  820): User[0] Flushing usage stats to disk
,E/bt-btm  ( 2177): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2177): onReceive
,I/BTConnectionReceiver( 1523): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1523): Bluetooth Device Name: Thali Test (Galaxy S5)
,E/bt-btm  ( 2177): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2177): onReceive
,I/BTConnectionReceiver( 1523): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1523): Bluetooth Device Name: Note3-1
,I/        ( 3823): Cleared service requests
F/libc    ( 4566): Fatal signal 11 (SIGSEGV), code 1, fault addr 0xc in tid 4566 (wpa_supplicant)
,I/libc    ( 4566): Suppressing debuggerd output because prctl(PR_GET_DUMPABLE)==0
,I/jxcore-log( 3823): 2015-12-04T09:03:29.416Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:03:29.416Z SendDataConnector.js: Connect (retry count 4) to peer E0:DB:10:1F:C9:5E with availability status: true
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T09:03:29.417Z SendDataConnector.js: doConnect called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T09:03:29.417Z SendDataConnector.js: do connect now
I/jxcore-log( 3823): 
,I/        ( 3823): Selected device address: E0:DB:10:1F:C9:5E, name: Note3-1
,I/BTConnectToThread( 3823): Starting to connect,
I/        ( 3823): Connecting to Note3-1, at E0:DB:10:1F:C9:5E
W/BluetoothAdapter( 3823): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2177): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-btif ( 2177): info:x10,
D/        ( 2177): remote version info [e0:db:10:1f:c9:5e]: 7, f, 6109
,I/BTConnectionReceiver( 1523): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1523): Bluetooth Device Name: Note3-1
,W/bt-sdp  ( 2177): process_service_search_attr_rsp
,W/bt-btif ( 2177): new conn_srvc id:26, app_id:1
W/bt-btif ( 2177): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2177): bta_dm_pm_ssr:2, lat:1200
I/BTConnectToThread( 3823): Starting to Handshake
I/BTHandshakeSocketThread( 3823): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3823): MESSAGE_WRITE 82 bytes.
,I/BTHandshakeSocketThread( 3823): BTHandshakeSocketThread started
,D/btif_config_util( 2177): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/BTConnectToThread( 3823): got MESSAGE_READ 82 bytes.
,I/BTConnectToThread( 3823): Got JSON from encryption:{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT3940","ra":"E0:DB:10:1F:C9:5E"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3823): HandshakeOk : samsung-SM-N9005_PT3940
I/HS      ( 3823): Hand Shake finished outgoing for : samsung-SM-N9005_PT3940
I/BTHandshakeSocketThread( 3823): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3823): Starting the connected thread incoming : false, samsung-SM-N9005_PT3940
I/BtToSocketBase( 3823): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3823): Creating BtConnectedRequestSocket
I/BtToRequestSocket( 3823): mHTTPPort  set to : 49701
I/BtConnectorHelper( 3823): Request socket is using : 49701
,I/BtToRequestSocket( 3823): Now accepting connections
,I/BtConnectorHelper( 3823): Calling ConnectionStatusUpdate with port :49701
,I/jxcore-log( 3823): 2015-12-04T09:03:33.479Z SendDataConnector.js: CLIENT connected to 49701, error: null,
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T09:03:33.482Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3823): ,
,I/BtToRequestSocket( 3823): incoming data from: /127.0.0.1, port: 49701
I/BtToRequestSocket( 3823): Set local streams
,I/BtToRequestSocket( 3823): rin ended ---------------------------;
I/jxcore-log( 3823): 2015-12-04T09:03:33.494Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 3823): 
,D/WifiHW  (  820): 'P2P_FIND 120' command timed out.
,I/        ( 3823): Starting peer discovery failed, error code 0
,E/WifiStateMachine(  820): Connection lost, restart supplicant
,E/WifiMonitor(  820): killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,W/Settings( 3883): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/WifiConfigStore(  820): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiConfigStore(  820): failed to set BSSID: any
,E/native  (  820): do suspend true
W/Settings( 1847): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/CommandListener(  354): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1492): Read error: ssl=0x9d16a200: I/O error during system call, Connection timed out
,V/NativeCrypto( 1492): SSL shutdown failed: ssl=0x9d16a200: I/O error during system call, Broken pipe
I/jxcore-log( 3823): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): The Coordinator has disconnected!
,I/jxcore-log( 3823): 
,D/ConnectivityService(  820): reportBadNetwork(NetworkAgentInfo [WIFI () - 102]) by 10011
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 102](  820): ValidatedState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 102](  820): DefaultState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 102](  820): Forcing reevaluation
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 102](  820): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  820): NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 102](  820): Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
,E/WifiStateMachine(  820): WifiStateMachine: Leaving Connected state
,E/WifiStateMachine(  820): Unexpected BatchedScanResults :null
D/ConnectivityService(  820): NetworkAgentInfo [WIFI () - 102] got DISCONNECTED, was satisfying 2
D/WifiScanningService(  820): SCAN_AVAILABLE : 1
D/RttService(  820): SCAN_AVAILABLE : 1
D/WifiScanningService(  820): StartedState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService(  820): DefaultState
,D/RttService(  820): EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
I/        ( 3823): Discovery state changed to Stopped.
,I/WB      ( 3823): Wifi is DISABLED !!
I/        ( 3823): Stoping All
I/        ( 3823): Stopping services
I/        ( 3823): Stopping services
I/        ( 3823): Stop Bluetooth
I/        ( 3823): Stop Bluetooth
I/BTListenerThread( 3823): Stopped
I/SS      ( 3823): We got empty peers list
I/        ( 3823): Starting peer discovery failed, error code 2
,D/WifiNetworkAgent(  820): NetworkAgent: NetworkAgent channel lost
,I/        ( 3823): Clearing local services failed, error code 2
I/        ( 3823): Clearing service requests failed, error code 2
I/        ( 3823): Stopping peer discovery failed, error code 2
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 102](  820): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
,D/ConnectivityService(  820): notifyType LOST for NetworkAgentInfo [WIFI () - 102]
,D/ConnectivityManager.CallbackHandler( 1064): CM callback handler got msg 524292
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 102](  820): OfflineState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 102](  820): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 102](  820): Disconnected - quitting
,D/CSLegacyTypeTracker(  820): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  820): MasterInitialState.processMessage what=3
D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/PhoneInterfaceManager( 1278): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1278): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  820): getDataEnabled: retVal=false
D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  820): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  820): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
,I/NetworkMonitor( 3914): type=WIFI subType= reason=null isConnected=false
,D/Tethering(  820): MasterInitialState.processMessage what=3
,V/MusicLeanback( 3914): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,E/GpsLocationProvider(  820): No APN found to select.
,D/SprintDMReceiver( 3980): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/PhoneInterfaceManager( 1278): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1278): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  820): getDataEnabled: retVal=false
,D/SprintDMHelper( 3980): simOperator:  IMSI: null
D/SprintDMReceiver( 3980): Not Sprint UICC, don't do anything.
I/SystemUpdateService( 1822): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,E/GpsLocationProvider(  820): No APN found to select.
,D/SystemUpdateService( 1822): onCreate
,D/SystemUpdateService( 1822): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1822): active receiver: enabled
,I/SystemUpdateService( 1822): showing system update notification
,I/iu.Environment( 1822): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1822): num queued entries: 0,
I/iu.UploadsManager( 1822): num updated entries: 0,
I/iu.SyncManager( 1822): NEXT; no task
,D/ChimeraCfgMgr( 1822): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/ValidateNoPeople(  820): skipping global notification
,V/SystemUpdateService( 1822): retry (wakeup: false) in 3599983 ms
,D/SystemUpdateService( 1822): onDestroy
,I/Babel   ( 3883): connection state changed from CONNECTED to DISCONNECTED
,V/MusicLeanback( 3914): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/SprintDMReceiver( 3980): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3980): simOperator:  IMSI: null
D/SprintDMReceiver( 3980): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1822): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1822): onCreate
,D/SystemUpdateService( 1822): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1822): active receiver: enabled
,I/SystemUpdateService( 1822): showing system update notification
,I/ValidateNoPeople(  820): skipping global notification
,D/ChimeraCfgMgr( 1822): Loading module com.google.android.gms.kids from APK com.google.android.gms
,V/SystemUpdateService( 1822): retry (wakeup: false) in 3599978 ms
,D/SystemUpdateService( 1822): onDestroy
,W/bt-btif ( 2177): dm_pm_timer expires
,W/bt-btif ( 2177): dm_pm_timer expires 0
W/bt-btif ( 2177): proc dm_pm_timer expires
,I/jxcore-log( 3823): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 3823): 
I/jxcore-log( 3823): Error type "connect_error" when connecting to the test server
I/jxcore-log( 3823): 
,D/WifiService(  820): setWifiEnabled: false pid=3823, uid=10265
,E/WifiService(  820): Invoking mWifiStateMachine.setWifiEnabled
,D/WifiService(  820): setWifiEnabled: true pid=3823, uid=10265
E/WifiService(  820): Invoking mWifiStateMachine.setWifiEnabled
,D/WifiController(  820): WifiController msg { when=-1ms what=155656 target=com.android.internal.util.StateMachine$SmHandler } deferred for 476ms
,I/jxcore-log( 3823): Wifi toggled for connection repairment
I/jxcore-log( 3823): 
,I/chromium( 3823): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,D/WifiController(  820): DEFERRED_TOGGLE handled
,D/SoftapController(  354): Softap fwReload - Ok
,D/CommandListener(  354): Setting iface cfg
,D/CommandListener(  354): Trying to bring down wlan0
,D/Tethering(  820): InitialState.processMessage what=4
,D/CommandListener(  354): Clearing all IP addresses on wlan0
,D/Tethering(  820): sendTetherStateChangedBroadcast 0, 0, 0
,E/WifiMonitor(  820): killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
D/WifiMonitor(  820): startMonitoring(wlan0) with mConnected = false
E/WifiHW  (  820): Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,I/wpa_supplicant( 4733): Successfully initialized wpa_supplicant
,I/wpa_supplicant( 4733): rfkill: Cannot open RFKILL control device
,D/Tethering(  820): sendTetherStateChangedBroadcast 1, 0, 0
,I/wpa_supplicant( 4733): rfkill: Cannot open RFKILL control device
E/wpa_supplicant( 4733): Could not read interface p2p-dev-wlan0 flags: No such device,
,D/WifiConfigStore(  820): Loading config and enabling all networks 
,D/WifiService(  820): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@27601104},
,E/WifiConfigStore(  820): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,D/WifiNative-HAL(  820): Setting external_sim to 1
D/WifiStateMachine(  820): Setting OUI to 92-68-C3
,I/WifiNative-HAL(  820): startHal
D/wifi    (  820): setting scan oui 0xb4b8af40
D/WifiHAL (  820): Sending mac address OUI
W/Settings( 3883): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,E/native  (  820): do suspend true
,D/WifiScanningService(  820): SCAN_AVAILABLE : 3
D/RttService(  820): SCAN_AVAILABLE : 3
D/RttService(  820): DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService(  820): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  820): startHal
,D/wifi    (  820): getting scan capabilities on interface[0] = 0xb4b8af40
D/WifiHAL (  820): Creating message to get scan capablities; iface = 5
D/WifiHAL (  820): In GetCapabilities::handleResponse
D/WifiHAL (  820): Id = 0, subcmd = 0, len = 28, expected len = 32
W/CommandListener(  354): Failed to retrieve HW addr for p2p0 (No such device)
,D/WifiScanningService(  820): StartedState
D/CommandListener(  354): Setting iface cfg
,E/WifiP2pService(  820): Unable to change interface settings: java.lang.IllegalStateException: command '104 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 104 Failed to set address (No such device)'
D/WifiMonitor(  820): startMonitoring(p2p0) with mConnected = true
,I/WB      ( 3823): Wifi is now enabled !
,I/        ( 3823): Stoping All
I/        ( 3823): Stopping services
I/        ( 3823): Stop Bluetooth
I/        ( 3823): Starting All
I/        ( 3823): Stopping services
,I/        ( 3823): Starting services address: {"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT1135","ra":"F8:CF:C5:D9:E5:61"}, org.thaliproject.p2p.btconnectorlib.BTConnectorSettings@3731150a
I/        ( 3823): Stopping services
I/        ( 3823): Starting services address: {"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT1135","ra":"F8:CF:C5:D9:E5:61"}
,I/        ( 3823): Add local service :{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT1135","ra":"F8:CF:C5:D9:E5:61"}, length : 82
I/        ( 3823): peerDiscoveryTimer timeout value:5050
,I/        ( 3823): Stop Bluetooth
,I/        ( 3823): StartBluetooth listener
I/        ( 3823): StartBluetooth listener
D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3823): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3823): Discovery state changed to Stopped.
,I/BTListenerThread( 3823): starting to listen
I/BTListenerThread( 3823): waiting to accept incoming Connection
,I/wpa_supplicant( 4733): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,D/WifiNative-HAL(  820): p2pGetDeviceAddress
D/WifiNative-HAL(  820): p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,I/        ( 3823): Added local service
,I/        ( 3823): Cleared service requests
I/        ( 3823): Stopped peer discovery
I/        ( 3823): Started peer discovery
I/        ( 3823): Discovery state changed to Started.
I/        ( 3823): Started peer discovery
,I/jxcore-log( 3823): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): Error type "connect_error" when connecting to the test server
I/jxcore-log( 3823): 
,I/chromium( 3823): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,I/wpa_supplicant( 4733): p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,E/WifiStateMachine(  820): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000,
,E/WifiConfigStore(  820):  rewrite network history for "NG700"WPA_PSK
,E/WifiConfigStore(  820):  rewrite network history for "NG7005g"WPA_PSK
E/WifiStateMachine(  820): CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
,E/WifiConfigStore(  820): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
E/WifiConfigStore(  820): writeKnownNetworkHistory write linked 1
E/WifiConfigStore(  820): writeKnownNetworkHistory write linked 1
,E/WifiStateMachine(  820): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=0
,E/WifiConfigStore(  820): will read network variables netId=0
,E/WifiStateMachine(  820): CMD_AUTO_CONNECT did save config ->  nid=0
,E/WifiConfigStore(  820): will read network variables netId=0
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 4733): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 4733): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 4733): wlan0: Trying to associate with SSID 'NG7005g'
I/SS      ( 3823): Found 4 peers.
I/SS      ( 3823): Peer(1): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3823): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3823): Peer(3): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3823): Peer(4): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3823): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3823): Added service request
,I/jxcore-log( 3823): 2015-12-04T09:03:43.549Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:03:43.549Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T09:03:43.550Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:03:43.554Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:03:43.555Z SendDataConnector.js: Stop data retrieving timer
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T09:03:43.555Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3823): 
,I/BtConnectorHelper( 3823): Disconnect outgoing peer: E0:DB:10:1F:C9:5E,
I/BtToSocketBase( 3823): Stop ReceivingThread
,I/BtToSocketBase( 3823): Stop SendingThread
,I/BtToSocketBase( 3823): Close local in
I/BtToSocketBase( 3823): Close LocalOutputStream
,I/BtToSocketBase( 3823): Close localHostSocket
I/BtToSocketBase( 3823): Close bt in
,I/BtToSocketBase( 3823): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3823): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3823): Close bt out,
,I/BtToSocketBase( 3823): Close bt socket
,I/BtToRequestSocket( 3823): Close server socket,
,I/jxcore-log( 3823): 2015-12-04T09:03:43.563Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3823): 
I/jxcore-log( 3823): ---- round done--------
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): ---- gotta redo : E0:DB:10:1F:C9:5E, try count now: 1
I/jxcore-log( 3823): 
I/jxcore-log( 3823): do fake peer & start
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): Connect to fake peer: 58:3F:54:73:64:C0
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T09:03:43.566Z SendDataConnector.js: Start called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:03:43.567Z SendDataConnector.js: doConnect called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T09:03:43.567Z SendDataConnector.js: do connect now
I/jxcore-log( 3823): 
,I/        ( 3823): Selected device address: 58:3F:54:73:64:C0, name: null
I/        ( 3823): Connecting to null, at 58:3F:54:73:64:C0
I/BTConnectToThread( 3823): Starting to connect
,W/BluetoothAdapter( 3823): getBluetoothService() called with no BluetoothManagerCallback
I/jxcore-log( 3823): 2015-12-04T09:03:43.580Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3823): 
,I/chromium( 3823): [INFO:CONSOLE(63)] "logCallback Round of send data to peer E0:DB:10:1F:C9:5E done with result: DATA-TIMEOUT", source: file:///android_asset/www/js/thali_main.js (63)
D/BTIF_SOCK( 2177): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,I/        ( 3823): Started service discovery
,W/bt-btif ( 2177): bta_jv_rfc_port_to_cb(port_handle:0x13):jv handle:0x0 not FOUND
,I/wpa_supplicant( 4733): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 4733): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 4733): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=0 id_str=]
,D/ConnectivityService(  820): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} }
,E/WifiConfigStore(  820): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  820): NetworkAgentInfo [WIFI () - 103] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  820): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  354): Setting iface cfg
,E/WifiStateMachine(  820): Start Dhcp Watchdog 4
,E/WifiStateMachine(  820):  WifiLinkLayerStats: 
E/WifiStateMachine(  820):  my bss beacon rx: 1
E/WifiStateMachine(  820):  RSSI mgmt: -47
E/WifiStateMachine(  820):  BE :  rx=0 tx=2 lost=0 retries=0
E/WifiStateMachine(  820):  BK :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  820):  VI :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  820):  VO :  rx=2 tx=0 lost=0 retries=0
E/WifiStateMachine(  820):  on_time : 0 tx_time=170 rx_time=510 scan_time=0
,E/native  (  820): do suspend false
,E/WifiStateMachine(  820): scanCount==0 - aborting
,I/wpa_supplicant( 4733): P2P-FIND-STOPPED 
,I/        ( 3823): Discovery state changed to Stopped.
,I/        ( 3823): Starting peer discovery failed, error code 2
,I/dhcpcd  ( 4742): version 5.5.6 starting
,I/dhcpcd  ( 4742): wlan0: rebinding lease of 192.168.1.110
,I/jxcore-log( 3823): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): Error type "connect_error" when connecting to the test server
I/jxcore-log( 3823): 
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/chromium( 3823): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,I/SS      ( 3823): Found 4 peers.
I/SS      ( 3823): Peer(1): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3823): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3823): Peer(3): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3823): Peer(4): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3823): Ignored { when=-3ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3823): Added service request
,E/bt-btm  ( 2177): tBTM_SEC_DEV:0xa2f185dc rs_disc_pending=1
,W/bt-btif ( 2177): bta_dm_check_av:0
W/bt-btif ( 2177): btif_dm_cback : unhandled event (14)
,D/WifiService(  820): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@27601104}
,I/        ( 3823): Starting service discovery failed, error code 2
,I/        ( 3823): Cleared service requests
,W/bt-btif ( 2177): info:x10,
D/        ( 2177): remote version info [58:3f:54:73:64:c0]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 2177): aclStateChangeCallback: Device is NULL,
,I/dhcpcd  ( 4742): wlan0: acknowledged 192.168.1.110 from 192.168.1.1
,I/dhcpcd  ( 4742): wlan0: leased 192.168.1.110 for 86400 seconds
,W/bt-sdp  ( 2177): process_service_search_attr_rsp
,E/bt-btif ( 2177): DISCOVERY_COMP_EVT slot id:65, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2177): invalid rfc slot id: 65
,I/BTConnectToThread( 3823): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3823): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3823): 2015-12-04T09:03:46.855Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:3F:54:73:64:C0 failed
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:03:46.856Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:3F:54:73:64:C0 failed
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:03:46.857Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3823): 
,E/native  (  820): do suspend true
,D/ConnectivityService(  820): NetworkAgentInfo [WIFI () - 103] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  820): Adding iface wlan0 to network 103
,E/WifiStateMachine(  820): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  820): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  820): Adding Route [fe80::/64 -> :: wlan0] to network 103
,D/ConnectivityService(  820): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 103
,D/ConnectivityService(  820): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 103
D/ConnectivityService(  820): Setting Dns servers for network 103 to [/192.168.1.1]
,D/ConnectivityService(  820): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,D/ConnectivityService(  820): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 103]
D/ConnectivityService(  820): rematching NetworkAgentInfo [WIFI () - 103]
D/ConnectivityService(  820):    accepting network in place of null
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 103](  820): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 103](  820): Connected
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 103](  820): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 103](  820): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
D/ConnectivityService(  820): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{103}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.110/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} }
,D/ConnectivityService(  820): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 103],
D/CSLegacyTypeTracker(  820): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 103] isDefaultNetwork=true
D/ConnectivityManager.CallbackHandler( 1064): CM callback handler got msg 524290
D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  820): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 3914): type=WIFI subType= reason=null isConnected=true
,D/PhoneInterfaceManager( 1278): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
,E/PhoneInterfaceManager( 1278): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
D/TelephonyManager(  820): getDataEnabled: retVal=false
,V/MusicLeanback( 3914): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,E/GpsLocationProvider(  820): No APN found to select.
,D/SprintDMReceiver( 3980): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3980): simOperator:  IMSI: null
D/SprintDMReceiver( 3980): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1822): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,I/BooksSync( 3710): Starting books sync for 61035162, extras: ade
,D/SystemUpdateService( 1822): onCreate
,D/SystemUpdateService( 1822): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1822): active receiver: enabled
,I/SystemUpdateService( 1822): showing system update notification
,I/ValidateNoPeople(  820): skipping global notification
,V/SystemUpdateService( 1822): retry (wakeup: false) in 3599971 ms
,I/art     (  820): Explicit concurrent mark sweep GC freed 79586(3MB) AllocSpace objects, 13(302KB) LOS objects, 31% free, 34MB/50MB, paused 1.762ms total 76.440ms
,D/SystemUpdateService( 1822): onDestroy,
,I/BooksConfig( 3710): GmsCore Version = 7.8.99 (2134222-430)
,I/iu.Environment( 1822): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1822): num queued entries: 0
,I/iu.UploadsManager( 1822): num updated entries: 0
,I/iu.SyncManager( 1822): NEXT; no task
,D/ChimeraCfgMgr( 1822): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 1822): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 103](  820): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 04 Dec 2015 09:03:47 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1449219827555], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1449219827537]}
,I/GLSUser ( 1492): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 103](  820): Validated
I/GLSUser ( 1492): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1492): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1492): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/ConnectivityService(  820): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/ConnectivityService(  820): Validated NetworkAgentInfo [WIFI () - 103]
D/ConnectivityService(  820): rematching NetworkAgentInfo [WIFI () - 103]
D/ConnectivityService(  820): Network NetworkAgentInfo [WIFI () - 103] was already satisfying request 1. No change.
D/ConnectivityService(  820): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 103]
D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1064): CM callback handler got msg 524290
,V/GLSActivity( 1492): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1492): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1492): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1492): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1492): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1492): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/Herrevad( 1822): NQAS connected
,I/GLSUser ( 1492): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1492): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1492): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1492): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1492): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Kids    ( 1822): [AccountUtils] Account not ready
W/Kids    ( 1822): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 1822): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 1822): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 1822): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 1822): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 1822): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 1822): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 1822): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 1822): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 1822): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 1822): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 1822): 	at java.lang.Thread.run(Thread.java:818)
,E/BooksAccountManager( 3710): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3710): Soft error
E/BooksSync( 3710): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3710): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3710): Sync error
E/BooksSync( 3710): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3710): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 3710): Finished books sync
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1228030, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,E/bt-btm  ( 2177): tBTM_SEC_DEV:0xa2f185dc rs_disc_pending=0
,W/bt-btif ( 2177): bta_dm_check_av:0
W/bt-btif ( 2177): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1,
I/wpa_supplicant( 4733): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3823): Found 5 peers.
I/SS      ( 3823): Peer(1): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3823): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3823): Peer(3): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3823): Peer(4): G3s-1 a2:39:f7:70:12:80
,I/SS      ( 3823): Peer(5): G4-1 a2:39:f7:6f:c9:5d
D/WifiP2pManager( 3823): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3823): Added service request
,I/Babel   ( 3883): connection state changed from DISCONNECTED to CONNECTED
,D/GCM     ( 1492): Connected
,D/GCM     ( 1492): Message class com.google.f.a.a.p
,D/ConnectivityService(  820): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 102] cleared because we found a replacement network
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3823): Started service discovery
,E/bt-btm  ( 2177): btm_sec_disconnected - Clearing Pending flag,
,D/BluetoothMapService( 2177): onReceive
,I/BTConnectionReceiver( 1523): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1523): Bluetooth Device Name: Note3-1
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032,
,D/btif_config_util( 2177): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3823): DBG, CoordinatorConnector connect called
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): Coordinator is now connected to the server!,
I/jxcore-log( 3823): 
,I/chromium( 3823): [INFO:CONSOLE(63)] "logCallback connected to server", source: file:///android_asset/www/js/thali_main.js (63)
,E/bt-btm  ( 2177): btm_sec_disconnected - Clearing Pending flag,
,E/BluetoothRemoteDevices( 2177): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3823): 2015-12-04T09:03:51.859Z SendDataConnector.js: re-try now : 58:3F:54:73:64:C0
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:03:51.860Z SendDataConnector.js: ReStart called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3823): 
,I/        ( 3823): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT5230","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
I/        ( 3823): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT5230","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT5230, peerAddress: F8:95:C7:87:85:54
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT5230, WifiDirectName: G3s-1, WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,I/        ( 3823): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1124","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
I/        ( 3823): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1124","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT1124, peerAddress: F8:95:C7:87:3C:51
,I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT1124, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/        ( 3823): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT3722"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT3722"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT3722, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT3722, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/        ( 3823): Found Service, :{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT2124","ra":"E0:DB:10:14:E2:C0"}, typeCordovap2p._tcp.local.:
I/        ( 3823): JsonLine: {"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT2124","ra":"E0:DB:10:14:E2:C0"} -- peerIdentifier:E0:DB:10:14:E2:C0, peerName: samsung-SM-N910C_PT2124, peerAddress: E0:DB:10:14:E2:C0
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : E0:DB:10:14:E2:C0, Name: samsung-SM-N910C_PT2124, WifiDirectName: Note4-1, WifiDirect Address: 92:b6:86:43:73:1c, peerId: E0:DB:10:14:E2:C0
,I/jxcore-log( 3823): 2015-12-04T09:03:56.864Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:3F:54:73:64:C0
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T09:03:56.864Z SendDataConnector.js: Connect (retry count 1) to peer 58:3F:54:73:64:C0 with availability status: true
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:03:56.865Z SendDataConnector.js: doConnect called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:03:56.865Z SendDataConnector.js: do connect now
I/jxcore-log( 3823): 
I/        ( 3823): Selected device address: 58:3F:54:73:64:C0, name: null
,I/BTConnectToThread( 3823): Starting to connect
,W/BluetoothAdapter( 3823): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3823): Connecting to null, at 58:3F:54:73:64:C0
D/BTIF_SOCK( 2177): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/        ( 3823): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5358"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5358"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT5358, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT5358, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,W/bt-btif ( 2177): info:x10
D/        ( 2177): remote version info [58:3f:54:73:64:c0]: 7, f, 6109
,E/BluetoothRemoteDevices( 2177): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2177): process_service_search_attr_rsp
,E/bt-btif ( 2177): DISCOVERY_COMP_EVT slot id:66, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2177): invalid rfc slot id: 66
,I/BTConnectToThread( 3823): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3823): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3823): 2015-12-04T09:03:58.175Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:3F:54:73:64:C0 failed
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:03:58.176Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:3F:54:73:64:C0 failed
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T09:03:58.176Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3823): 
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1,
,I/        ( 3823): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5092","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5092","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT5092, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT5092, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,D/btif_config_util( 2177): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2177): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2177): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 4733): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3823): 2015-12-04T09:04:03.177Z SendDataConnector.js: re-try now : 58:3F:54:73:64:C0
I/jxcore-log( 3823): ,
I/jxcore-log( 3823): 2015-12-04T09:04:03.178Z SendDataConnector.js: ReStart called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3823): 
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3823): Cleared service requests,
,I/        ( 3823): Started peer discovery
I/        ( 3823): Discovery state changed to Started.
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/SS      ( 3823): Found 10 peers.
,I/SS      ( 3823): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3823): Peer(2): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3823): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3823): Peer(4): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3823): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
,I/SS      ( 3823): Peer(6): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3823): Peer(7): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3823): Peer(8): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3823): Peer(9): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3823): Peer(10): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiP2pManager( 3823): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3823): Added service request
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3823): Started service discovery
,I/jxcore-log( 3823): 2015-12-04T09:04:08.182Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:3F:54:73:64:C0,
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T09:04:08.183Z SendDataConnector.js: Connect (retry count 2) to peer 58:3F:54:73:64:C0 with availability status: true
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T09:04:08.183Z SendDataConnector.js: doConnect called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:04:08.184Z SendDataConnector.js: do connect now
I/jxcore-log( 3823): 
I/        ( 3823): Selected device address: 58:3F:54:73:64:C0, name: null
,I/BTConnectToThread( 3823): Starting to connect
,W/BluetoothAdapter( 3823): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3823): Connecting to null, at 58:3F:54:73:64:C0
,D/BTIF_SOCK( 2177): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-btif ( 2177): info:x10
D/        ( 2177): remote version info [58:3f:54:73:64:c0]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 2177): aclStateChangeCallback: Device is NULL,
,I/        ( 3823): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5092","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 3823): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5092","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT5092, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT5092, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,W/bt-sdp  ( 2177): process_service_search_attr_rsp
,I/        ( 3823): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5358"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5358"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT5358, peerAddress: F4:F1:E1:5C:3B:E2
,I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT5358, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
E/bt-btif ( 2177): DISCOVERY_COMP_EVT slot id:67, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2177): invalid rfc slot id: 67
,I/BTConnectToThread( 3823): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3823): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3823): 2015-12-04T09:04:09.794Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:3F:54:73:64:C0 failed,
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T09:04:09.795Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:3F:54:73:64:C0 failed
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T09:04:09.796Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3823): 
,I/        ( 3823): Found Service, :{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT6585"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT6585"} -- peerIdentifier:34:FC:EF:11:B1:66, peerName: LGE-Nexus 5_PT6585, peerAddress: 34:FC:EF:11:B1:66
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : 34:FC:EF:11:B1:66, Name: LGE-Nexus 5_PT6585, WifiDirectName: Android_2dc2, WifiDirect Address: 52:55:27:f0:ff:f0, peerId: 34:FC:EF:11:B1:66
,D/btif_config_util( 2177): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2177): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2177): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3823): 2015-12-04T09:04:14.798Z SendDataConnector.js: re-try now : 58:3F:54:73:64:C0
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T09:04:14.799Z SendDataConnector.js: ReStart called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3823): 
,I/        ( 3823): Cleared service requests
,I/        ( 3823): Started peer discovery
,I/jxcore-log( 3823): 2015-12-04T09:04:19.803Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:3F:54:73:64:C0
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:04:19.803Z SendDataConnector.js: Connect (retry count 3) to peer 58:3F:54:73:64:C0 with availability status: true
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T09:04:19.804Z SendDataConnector.js: doConnect called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T09:04:19.804Z SendDataConnector.js: do connect now
I/jxcore-log( 3823): 
,I/        ( 3823): Selected device address: 58:3F:54:73:64:C0, name: null,
I/BTConnectToThread( 3823): Starting to connect
W/BluetoothAdapter( 3823): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3823): Connecting to null, at 58:3F:54:73:64:C0
,D/BTIF_SOCK( 2177): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,I/BooksSync( 3710): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3710): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1492): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1492): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1492): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1492): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1492): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1492): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1492): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1492): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1492): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1492): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3215): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3215): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3215): 	at jdm.a(PG:82)
E/HttpOperation( 3215): 	at jcs.o(PG:406)
E/HttpOperation( 3215): 	at jcn.a(PG:1379)
E/HttpOperation( 3215): 	at jcs.i(PG:143)
E/HttpOperation( 3215): 	at blb.a(PG:3937)
E/HttpOperation( 3215): 	at czp.a(PG:18188)
E/HttpOperation( 3215): 	at czp.a(PG:9081)
E/HttpOperation( 3215): 	at czq.run(PG:1686)
E/HttpOperation( 3215): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3215): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3215): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3215): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3215): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3215): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3215): 	at jdj.a(PG:4091)
E/HttpOperation( 3215): 	at jdj.a(PG:1125)
E/HttpOperation( 3215): 	at jdm.a(PG:77)
E/HttpOperation( 3215): 	... 12 more
E/HttpOperation( 3215): Caused by: faj: BadAuthentication
E/HttpOperation( 3215): 	at fal.a(PG:38)
E/HttpOperation( 3215): 	at jdj.a(PG:4089)
E/HttpOperation( 3215): 	... 14 more
,I/GLSUser ( 1492): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1492): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1492): [GLSUser] Extracting token using key: Auth
,I/GLSUser ( 1492): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
W/GLSActivity( 1492): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/GLSUser ( 1492): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1492): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1492): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1492): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1492): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3710): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3710): Soft error
E/BooksSync( 3710): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3710): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3710): Sync error
E/BooksSync( 3710): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3710): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3710): Finished books sync
,E/HttpOperation( 3215): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3215): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3215): 	at jdm.a(PG:82)
E/HttpOperation( 3215): 	at jcs.o(PG:406)
E/HttpOperation( 3215): 	at jcn.a(PG:1379)
E/HttpOperation( 3215): 	at jcs.i(PG:143)
E/HttpOperation( 3215): 	at hec.a(PG:42)
E/HttpOperation( 3215): 	at hee.a(PG:102)
E/HttpOperation( 3215): 	at czr.a(PG:65)
E/HttpOperation( 3215): 	at kka.a(PG:108)
E/HttpOperation( 3215): 	at czp.a(PG:19176)
E/HttpOperation( 3215): 	at czp.a(PG:9081)
E/HttpOperation( 3215): 	at czq.run(PG:1686)
E/HttpOperation( 3215): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3215): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3215): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3215): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3215): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3215): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3215): 	at jdj.a(PG:4091)
E/HttpOperation( 3215): 	at jdj.a(PG:1125)
E/HttpOperation( 3215): 	at jdm.a(PG:77)
E/HttpOperation( 3215): 	... 15 more
E/HttpOperation( 3215): Caused by: faj: BadAuthentication
E/HttpOperation( 3215): 	at fal.a(PG:38)
E/HttpOperation( 3215): 	at jdj.a(PG:4089)
E/HttpOperation( 3215): 	... 17 more
E/ExperimentLoader( 3215): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3215): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3215): 	at jdm.a(PG:82)
E/ExperimentLoader( 3215): 	at jcs.o(PG:406)
E/ExperimentLoader( 3215): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3215): 	at jcs.i(PG:143)
E/ExperimentLoader( 3215): 	at hec.a(PG:42)
E/ExperimentLoader( 3215): 	at hee.a(PG:102)
E/ExperimentLoader( 3215): 	at czr.a(PG:65)
E/ExperimentLoader( 3215): 	at kka.a(PG:108)
E/ExperimentLoader( 3215): 	at czp.a(PG:19176)
E/ExperimentLoader( 3215): 	at czp.a(PG:9081)
E/ExperimentLoader( 3215): 	at czq.run(PG:1686)
E/ExperimentLoader( 3215): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3215): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3215): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3215): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3215): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3215): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3215): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3215): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3215): 	at jdm.a(PG:77)
E/ExperimentLoader( 3215): 	... 15 more
E/ExperimentLoader( 3215): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3215): 	at fal.a(PG:38)
E/ExperimentLoader( 3215): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3215): 	... 17 more
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1287039, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1],
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 1259936, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,W/bt-btif ( 2177): info:x10
D/        ( 2177): remote version info [58:3f:54:73:64:c0]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 2177): aclStateChangeCallback: Device is NULL,
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/SS      ( 3823): Found 10 peers.
I/SS      ( 3823): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3823): Peer(2): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3823): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
,I/SS      ( 3823): Peer(4): Android_2dc2 52:55:27:f0:ff:f0
,I/SS      ( 3823): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3823): Peer(6): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3823): Peer(7): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3823): Peer(8): XT1039_8c05 f4:f1:e1:5c:43:c8
,I/SS      ( 3823): Peer(9): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3823): Peer(10): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiP2pManager( 3823): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3823): Added service request
,W/bt-sdp  ( 2177): process_service_search_attr_rsp
,E/bt-btif ( 2177): DISCOVERY_COMP_EVT slot id:68, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2177): invalid rfc slot id: 68
I/BTConnectToThread( 3823): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3823): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3823): 2015-12-04T09:04:21.750Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:3F:54:73:64:C0 failed
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:04:21.751Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:3F:54:73:64:C0 failed
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:04:21.752Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3823): 
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/        ( 3823): Started service discovery
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3823): Found Service, :{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT8320"}, typeCordovap2p._tcp.local.:
I/        ( 3823): JsonLine: {"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT8320"} -- peerIdentifier:38:94:96:B5:06:DC, peerName: samsung-SM-G800H_PT8320, peerAddress: 38:94:96:B5:06:DC
,I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : 38:94:96:B5:06:DC, Name: samsung-SM-G800H_PT8320, WifiDirectName: , WifiDirect Address: 3a:94:96:b5:06:dd, peerId: 38:94:96:B5:06:DC
,D/btif_config_util( 2177): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 3823): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5092","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5092","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT5092, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT5092, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,E/bt-btm  ( 2177): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2177): aclStateChangeCallback: Device is NULL,
,I/        ( 3823): Found Service, :{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT6585"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT6585"} -- peerIdentifier:34:FC:EF:11:B1:66, peerName: LGE-Nexus 5_PT6585, peerAddress: 34:FC:EF:11:B1:66
,I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : 34:FC:EF:11:B1:66, Name: LGE-Nexus 5_PT6585, WifiDirectName: Android_2dc2, WifiDirect Address: 52:55:27:f0:ff:f0, peerId: 34:FC:EF:11:B1:66
,W/bt-btif ( 2177): info:x10
,D/        ( 2177): remote version info [34:fc:ef:11:ae:67]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1523): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1523): Bluetooth Device Name: Nexus 5
,W/bt-btif ( 2177): new conn_srvc id:26, app_id:255
W/bt-btif ( 2177): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 2177): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3823): we got incoming connection
I/BTHandshakeSocketThread( 3823): Creating BTHandshakeSocketThread
I/BTListenerThread( 3823): waiting to accept incoming Connection
I/BTHandshakeSocketThread( 3823): BTHandshakeSocketThread started
,I/BTListenerThread( 3823): got MESSAGE_READ 75 bytes.
,I/BTListenerThread( 3823): Got JSON from encryption:{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT74","ra":"34:FC:EF:11:AE:67"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTListenerThread( 3823): MESSAGE_WRITE 82 bytes.
I/HS      ( 3823): Incoming connection Hand Shake finished for : LGE-Nexus 5_PT74
I/BTHandshakeSocketThread( 3823): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3823): Starting the connected thread incoming : true, LGE-Nexus 5_PT74
I/BtToSocketBase( 3823): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3823): Creating BTConnectedThread
I/BtConnectorHelper( 3823): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3823): --DoOneRunRound started
,I/BtToRequestSocket( 3823): LocalHost address: localhost/127.0.0.1, port: 48599
,I/BtToRequestSocket( 3823): --DoOneRunRound ended
I/jxcore-log( 3823): 2015-12-04T09:04:26.129Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:04:26.754Z SendDataConnector.js: re-try now : 58:3F:54:73:64:C0
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:04:26.754Z SendDataConnector.js: ReStart called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:04:26.893Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:04:26.897Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:04:26.907Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:04:26.915Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:04:26.919Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:04:26.923Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:04:26.929Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:04:26.970Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:04:26.975Z SendDataTCPServer.js: TCP/IP server has received 32768 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:04:26.983Z SendDataTCPServer.js: TCP/IP server has received 34748 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:04:27.021Z SendDataTCPServer.js: TCP/IP server has received 48608 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:04:27.028Z SendDataTCPServer.js: TCP/IP server has received 52568 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:04:27.033Z SendDataTCPServer.js: TCP/IP server has received 54548 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:04:27.071Z SendDataTCPServer.js: TCP/IP server has received 62468 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:04:27.077Z SendDataTCPServer.js: TCP/IP server has received 66428 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:04:27.110Z SendDataTCPServer.js: TCP/IP server has received 76328 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:04:27.116Z SendDataTCPServer.js: TCP/IP server has received 78308 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:04:27.151Z SendDataTCPServer.js: TCP/IP server has received 90188 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:04:27.158Z SendDataTCPServer.js: TCP/IP server has received 92168 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:04:27.189Z SendDataTCPServer.js: TCP/IP server has received 96128 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:04:27.197Z SendDataTCPServer.js: TCP/IP server has received 98108 bytes of data
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:04:27.199Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3823): 
,D/btif_config_util( 2177): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 3823): Cleared service requests
,I/        ( 3823): Started peer discovery
,W/ProcessCpuTracker(  820): Skipping unknown process pid 4814
,I/jxcore-log( 3823): 2015-12-04T09:04:31.758Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:3F:54:73:64:C0
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T09:04:31.759Z SendDataConnector.js: Connect (retry count 4) to peer 58:3F:54:73:64:C0 with availability status: true
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T09:04:31.760Z SendDataConnector.js: doConnect called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T09:04:31.760Z SendDataConnector.js: do connect now
I/jxcore-log( 3823): 
,I/        ( 3823): Selected device address: 58:3F:54:73:64:C0, name: null
,I/BTConnectToThread( 3823): Starting to connect
W/BluetoothAdapter( 3823): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3823): Connecting to null, at 58:3F:54:73:64:C0
,D/BTIF_SOCK( 2177): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-btif ( 2177): dm_pm_timer expires
,W/bt-btif ( 2177): dm_pm_timer expires 0
W/bt-btif ( 2177): proc dm_pm_timer expires
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3823): Found 10 peers.
I/SS      ( 3823): Peer(1): S5-1 ee:1f:72:63:11:86
,I/SS      ( 3823): Peer(2): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3823): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3823): Peer(4): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3823): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3823): Peer(6): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3823): Peer(7): G4-1 a2:39:f7:6f:c9:5d
,I/SS      ( 3823): Peer(8): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3823): Peer(9): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3823): Peer(10): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiP2pManager( 3823): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3823): Added service request
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3823): Cleared service requests
,I/        ( 3823): Started peer discovery
,I/        ( 3823): Starting service discovery failed, error code 3
,I/        ( 3823): Cleared service requests
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 3823): Found 11 peers.
I/SS      ( 3823): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3823): Peer(2): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3823): Peer(3): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3823): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3823): Peer(5): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3823): Peer(6): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3823): Peer(7): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3823): Peer(8): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3823): Peer(9): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3823): Peer(10): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3823): Peer(11): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 3823): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3823): Added service request
,I/        ( 3823): Started service discovery
,I/        ( 3823): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT7300","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT7300","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT7300, peerAddress: 08:EC:A9:50:76:27
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT7300, WifiDirectName: Thali Test (Galaxy A3), WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,E/bt-btif ( 2177): DISCOVERY_COMP_EVT slot id:70, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2177): invalid rfc slot id: 70
I/BTConnectToThread( 3823): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3823): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3823): 2015-12-04T09:04:41.730Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:3F:54:73:64:C0 failed
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:04:41.732Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:3F:54:73:64:C0 failed
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:04:41.739Z SendDataConnector.js: CLIENT Stop now,
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:04:41.746Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:3F:54:73:64:C0,
I/jxcore-log( 3823): 
I/jxcore-log( 3823): ---- round done--------
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): ---- gotta redo : 58:3F:54:73:64:C0, try count now: 1
I/jxcore-log( 3823): 
I/jxcore-log( 3823): do fake peer & start
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): Connect to fake peer: F4:F1:E1:5C:3B:E2
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T09:04:41.751Z SendDataConnector.js: Start called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:04:41.754Z SendDataConnector.js: doConnect called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:04:41.756Z SendDataConnector.js: do connect now
I/jxcore-log( 3823): 
,I/        ( 3823): Selected device address: F4:F1:E1:5C:3B:E2, name: XT1039
,I/        ( 3823): Connecting to XT1039, at F4:F1:E1:5C:3B:E2
,I/chromium( 3823): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 58:3F:54:73:64:C0 done with result: Connection to 58:3F:54:73:64:C0 failed", source: file:///android_asset/www/js/thali_main.js (63)
I/BTConnectToThread( 3823): Starting to connect
W/BluetoothAdapter( 3823): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2177): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae,
,I/        ( 3823): Cleared service requests
,I/        ( 3823): Started peer discovery
,W/bt-sdp  ( 2177): SDP - Rcvd conn cnf with error: 0x4  CID 0x45
,E/bt-btif ( 2177): DISCOVERY_COMP_EVT slot id:71, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2177): invalid rfc slot id: 71
,I/BTConnectToThread( 3823): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3823): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3823): 2015-12-04T09:04:46.904Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F4:F1:E1:5C:3B:E2 failed
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:04:46.905Z SendDataConnector.js: CLIENT Can not Connect: Connection to F4:F1:E1:5C:3B:E2 failed
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T09:04:46.906Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3823): 
,V/KeepSync( 3727): Connecting to GoogleApiClient
,I/GLSUser ( 1492): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1492): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1492): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1492): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1492): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1492): Explicit concurrent mark sweep GC freed 64151(3MB) AllocSpace objects, 11(1212KB) LOS objects, 37% free, 27MB/43MB, paused 2.027ms total 47.246ms
,E/ClientConnectionOperation( 1822): Handling authorization failure
E/ClientConnectionOperation( 1822): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1822): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1822): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1822): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1822): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1822): 	... 7 more
,V/KeepSync( 3727): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3727): (284) automatic index on blob_node(is_deleted),
,E/SQLiteLog( 3727): (284) automatic index on blob_node(is_deleted),
,E/SQLiteLog( 3727): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1492): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1492): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1492): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1492): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1492): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3727): IOException
E/KeepSync( 3727): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3727): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3727): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3727): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3727): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3727): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3727): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3727): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3727): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3727): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3727): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3727): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3727): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3727): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3727): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3727): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3727): 	... 10 more
W/KeepSync( 3727): Sync result 2
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 1299719, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/jxcore-log( 3823): 2015-12-04T09:04:51.907Z SendDataConnector.js: re-try now : F4:F1:E1:5C:3B:E2
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T09:04:51.908Z SendDataConnector.js: ReStart called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3823): 
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3823): Found 11 peers.
I/SS      ( 3823): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3823): Peer(2): Note4-1 92:b6:86:43:73:1c
,I/SS      ( 3823): Peer(3): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3823): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3823): Peer(5): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3823): Peer(6): Thali Test's G2 36:fc:ef:de:0a:e2
,I/SS      ( 3823): Peer(7): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3823): Peer(8): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3823): Peer(9): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3823): Peer(10): S5mini-1 02:f4:6f:30:e0:6d
,I/SS      ( 3823): Peer(11): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiP2pManager( 3823): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3823): Added service request
,I/wpa_supplicant( 4733): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3823): Started service discovery
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3823): 2015-12-04T09:04:56.912Z SendDataConnector.js: Mobile.Disconnect() callback with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:04:56.913Z SendDataConnector.js: Connect (retry count 1) to peer F4:F1:E1:5C:3B:E2 with availability status: true
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:04:56.913Z SendDataConnector.js: doConnect called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T09:04:56.914Z SendDataConnector.js: do connect now,
I/jxcore-log( 3823): 
,I/        ( 3823): Selected device address: F4:F1:E1:5C:3B:E2, name: XT1039
,I/BTConnectToThread( 3823): Starting to connect
W/BluetoothAdapter( 3823): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3823): Connecting to XT1039, at F4:F1:E1:5C:3B:E2,
,D/BTIF_SOCK( 2177): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,D/HeadsetStateMachine( 2177): Disconnected process message: 10, size: 0
,W/bt-sdp  ( 2177): SDP - Rcvd conn cnf with error: 0x4  CID 0x40
E/bt-btif ( 2177): DISCOVERY_COMP_EVT slot id:72, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2177): invalid rfc slot id: 72
I/BTConnectToThread( 3823): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3823): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3823): 2015-12-04T09:05:02.075Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F4:F1:E1:5C:3B:E2 failed
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T09:05:02.076Z SendDataConnector.js: CLIENT Can not Connect: Connection to F4:F1:E1:5C:3B:E2 failed
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:05:02.077Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3823): 
,W/bt-btif ( 2177): invalid rfc slot id: 64
,I/BtToSocketBase( 3823): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3823): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3823): Disconnect:::Stop : mBtToServerSocket :LGE-Nexus 5_PT74
I/BtToSocketBase( 3823): Stop ReceivingThread
I/BtToSocketBase( 3823): Stop SendingThread
I/BtToSocketBase( 3823): Close local in
I/BtToSocketBase( 3823): Close LocalOutputStream
I/BtToSocketBase( 3823): Close localHostSocket
I/BtToSocketBase( 3823): Close bt in
I/BtToSocketBase( 3823): Close bt out
I/BtToSocketBase( 3823): Close bt socket
,I/BtToSocketBase( 3823): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3823): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,E/bt-btm  ( 2177): btm_sec_disconnected - Clearing Pending flag
I/jxcore-log( 3823): 2015-12-04T09:05:03.111Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3823): 
D/BluetoothMapService( 2177): onReceive
,I/BTConnectionReceiver( 1523): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1523): Bluetooth Device Name: Nexus 5
,I/jxcore-log( 3823): 2015-12-04T09:05:07.078Z SendDataConnector.js: re-try now : F4:F1:E1:5C:3B:E2
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T09:05:07.079Z SendDataConnector.js: ReStart called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3823): 
,I/wpa_supplicant( 4733): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 4733): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,I/wpa_supplicant( 4733): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
,I/jxcore-log( 3823): 2015-12-04T09:05:12.083Z SendDataConnector.js: Mobile.Disconnect() callback with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:05:12.083Z SendDataConnector.js: Connect (retry count 2) to peer F4:F1:E1:5C:3B:E2 with availability status: true
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T09:05:12.084Z SendDataConnector.js: doConnect called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T09:05:12.085Z SendDataConnector.js: do connect now
I/jxcore-log( 3823): 
,I/        ( 3823): Selected device address: F4:F1:E1:5C:3B:E2, name: XT1039
,I/BTConnectToThread( 3823): Starting to connect
,W/BluetoothAdapter( 3823): getBluetoothService() called with no BluetoothManagerCallback,
I/        ( 3823): Connecting to XT1039, at F4:F1:E1:5C:3B:E2
,D/BTIF_SOCK( 2177): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-btif ( 2177): info:x10
D/        ( 2177): remote version info [f4:f1:e1:5c:3b:e2]: 7, f, 6109
,I/BTConnectionReceiver( 1523): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1523): Bluetooth Device Name: XT1039
,W/bt-sdp  ( 2177): process_service_search_attr_rsp
,W/bt-btif ( 2177): new conn_srvc id:26, app_id:1
W/bt-btif ( 2177): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2177): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3823): Starting to Handshake
I/BTHandshakeSocketThread( 3823): Creating BTHandshakeSocketThread
I/BTConnectToThread( 3823): MESSAGE_WRITE 82 bytes.
,I/BTHandshakeSocketThread( 3823): BTHandshakeSocketThread started
,I/BTConnectToThread( 3823): got MESSAGE_READ 81 bytes.,
I/BTConnectToThread( 3823): Got JSON from encryption:{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5358"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3823): HandshakeOk : motorola-XT1039_PT5358
,I/HS      ( 3823): Hand Shake finished outgoing for : motorola-XT1039_PT5358
I/BTHandshakeSocketThread( 3823): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3823): Starting the connected thread incoming : false, motorola-XT1039_PT5358
I/BtToSocketBase( 3823): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3823): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3823): mHTTPPort  set to : 38934
,I/BtConnectorHelper( 3823): Request socket is using : 38934
I/BtToRequestSocket( 3823): Now accepting connections
,D/HeadsetStateMachine( 2177): Disconnected process message: 10, size: 0
,I/BtConnectorHelper( 3823): Calling ConnectionStatusUpdate with port :38934,
I/jxcore-log( 3823): 2015-12-04T09:05:15.796Z SendDataConnector.js: CLIENT connected to 38934, error: null
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T09:05:15.796Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3823): 
,I/BtToRequestSocket( 3823): incoming data from: /127.0.0.1, port: 38934
,I/BtToRequestSocket( 3823): Set local streams
I/BtToRequestSocket( 3823): rin ended ---------------------------;
I/jxcore-log( 3823): 2015-12-04T09:05:15.805Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3823): 
,D/        ( 2177): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:544
,D/        ( 2177): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:18184
,D/        ( 2177): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:6304
,I/jxcore-log( 3823): 2015-12-04T09:05:16.503Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:05:16.510Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:05:16.532Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:05:16.543Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:05:16.590Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:05:16.678Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:05:16.763Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:05:16.798Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3823): 
,D/btif_config_util( 2177): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/art     (  820): Explicit concurrent mark sweep GC freed 43065(1889KB) AllocSpace objects, 6(190KB) LOS objects, 31% free, 34MB/50MB, paused 2.708ms total 73.894ms
,I/GLSUser ( 1492): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1492): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1492): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1492): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1492): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3215): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3215): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3215): 	at jdm.a(PG:82)
E/HttpOperation( 3215): 	at jcs.o(PG:406)
E/HttpOperation( 3215): 	at jcn.a(PG:1379)
E/HttpOperation( 3215): 	at jcs.i(PG:143)
E/HttpOperation( 3215): 	at blb.a(PG:3937)
E/HttpOperation( 3215): 	at czp.a(PG:18188)
E/HttpOperation( 3215): 	at czp.a(PG:9081)
E/HttpOperation( 3215): 	at czq.run(PG:1686)
E/HttpOperation( 3215): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3215): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3215): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3215): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3215): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3215): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3215): 	at jdj.a(PG:4091)
E/HttpOperation( 3215): 	at jdj.a(PG:1125)
E/HttpOperation( 3215): 	at jdm.a(PG:77)
E/HttpOperation( 3215): 	... 12 more
E/HttpOperation( 3215): Caused by: faj: BadAuthentication
E/HttpOperation( 3215): 	at fal.a(PG:38)
E/HttpOperation( 3215): 	at jdj.a(PG:4089)
E/HttpOperation( 3215): 	... 14 more
,I/GLSUser ( 1492): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1492): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1492): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1492): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1492): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3215): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3215): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3215): 	at jdm.a(PG:82)
E/HttpOperation( 3215): 	at jcs.o(PG:406)
E/HttpOperation( 3215): 	at jcn.a(PG:1379)
E/HttpOperation( 3215): 	at jcs.i(PG:143)
E/HttpOperation( 3215): 	at hec.a(PG:42)
E/HttpOperation( 3215): 	at hee.a(PG:102)
E/HttpOperation( 3215): 	at czr.a(PG:65)
E/HttpOperation( 3215): 	at kka.a(PG:108)
E/HttpOperation( 3215): 	at czp.a(PG:19176)
E/HttpOperation( 3215): 	at czp.a(PG:9081)
E/HttpOperation( 3215): 	at czq.run(PG:1686)
E/HttpOperation( 3215): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3215): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3215): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3215): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3215): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3215): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3215): 	at jdj.a(PG:4091)
E/HttpOperation( 3215): 	at jdj.a(PG:1125)
E/HttpOperation( 3215): 	at jdm.a(PG:77)
E/HttpOperation( 3215): 	... 15 more
E/HttpOperation( 3215): Caused by: faj: BadAuthentication
E/HttpOperation( 3215): 	at fal.a(PG:38)
E/HttpOperation( 3215): 	at jdj.a(PG:4089)
E/HttpOperation( 3215): 	... 17 more
,E/ExperimentLoader( 3215): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3215): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3215): 	at jdm.a(PG:82)
E/ExperimentLoader( 3215): 	at jcs.o(PG:406)
E/ExperimentLoader( 3215): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3215): 	at jcs.i(PG:143)
E/ExperimentLoader( 3215): 	at hec.a(PG:42)
E/ExperimentLoader( 3215): 	at hee.a(PG:102)
E/ExperimentLoader( 3215): 	at czr.a(PG:65)
E/ExperimentLoader( 3215): 	at kka.a(PG:108)
E/ExperimentLoader( 3215): 	at czp.a(PG:19176)
E/ExperimentLoader( 3215): 	at czp.a(PG:9081)
E/ExperimentLoader( 3215): 	at czq.run(PG:1686)
E/ExperimentLoader( 3215): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3215): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3215): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3215): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3215): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3215): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3215): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3215): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3215): 	at jdm.a(PG:77)
E/ExperimentLoader( 3215): 	... 15 more
E/ExperimentLoader( 3215): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3215): 	at fal.a(PG:38)
E/ExperimentLoader( 3215): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3215): 	... 17 more
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 1318326, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,W/bt-btif ( 2177): dm_pm_timer expires
,W/bt-btif ( 2177): dm_pm_timer expires 0
W/bt-btif ( 2177): proc dm_pm_timer expires
,I/jxcore-log( 3823): 2015-12-04T09:05:26.798Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T09:05:26.799Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T09:05:26.800Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T09:05:26.800Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T09:05:26.801Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3823): 
,I/BtToSocketBase( 3823): SendingThread thread got error: input stream got -1 on read,
,I/BtConnectorHelper( 3823): Disconnect outgoing peer: motorola-XT1039_PT5358
,I/BtToSocketBase( 3823): Stop ReceivingThread
I/BtToSocketBase( 3823): Stop SendingThread
,I/BtToSocketBase( 3823): Close local in
I/BtToSocketBase( 3823): Close LocalOutputStream
I/BtToSocketBase( 3823): Close localHostSocket
I/BtToSocketBase( 3823): Close bt in
,I/BtToSocketBase( 3823): Close bt out
I/BtToSocketBase( 3823): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtToSocketBase( 3823): Close bt socket
I/BtToRequestSocket( 3823): Close server socket
,I/        ( 3823): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT7300","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
I/        ( 3823): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT7300","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT7300, peerAddress: 08:EC:A9:50:76:27
,I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT7300, WifiDirectName: Thali Test (Galaxy A3), WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,I/        ( 3823): Found Service, :{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT8320"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT8320"} -- peerIdentifier:38:94:96:B5:06:DC, peerName: samsung-SM-G800H_PT8320, peerAddress: 38:94:96:B5:06:DC
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : 38:94:96:B5:06:DC, Name: samsung-SM-G800H_PT8320, WifiDirectName: , WifiDirect Address: 3a:94:96:b5:06:dd, peerId: 38:94:96:B5:06:DC
,W/bt-btif ( 2177): bta_jv_rfc_port_to_cb(port_handle:0x16):jv handle:0x0 not FOUND
,I/        ( 3823): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5358"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5358"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT5358, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT5358, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/jxcore-log( 3823): 2015-12-04T09:05:31.802Z SendDataConnector.js: re-try now : F4:F1:E1:5C:3B:E2
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:05:31.802Z SendDataConnector.js: ReStart called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3823): 
,E/bt-btm  ( 2177): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2177): onReceive
,I/BTConnectionReceiver( 1523): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1523): Bluetooth Device Name: XT1039
,I/        ( 3823): Cleared service requests
,I/        ( 3823): Started peer discovery
,I/jxcore-log( 3823): 2015-12-04T09:05:36.806Z SendDataConnector.js: Mobile.Disconnect() callback with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T09:05:36.807Z SendDataConnector.js: Connect (retry count 3) to peer F4:F1:E1:5C:3B:E2 with availability status: true
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:05:36.807Z SendDataConnector.js: doConnect called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T09:05:36.808Z SendDataConnector.js: do connect now
I/jxcore-log( 3823): 
,I/        ( 3823): Selected device address: F4:F1:E1:5C:3B:E2, name: XT1039
,I/BTConnectToThread( 3823): Starting to connect
,W/BluetoothAdapter( 3823): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3823): Connecting to XT1039, at F4:F1:E1:5C:3B:E2
,D/BTIF_SOCK( 2177): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-btif ( 2177): info:x10
,D/        ( 2177): remote version info [f4:f1:e1:5c:3b:e2]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1523): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1523): Bluetooth Device Name: XT1039
,I/wpa_supplicant( 4733): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant( 4733): P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6:ad:a4:6b
I/wpa_supplicant( 4733): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:ff:f0
,I/SS      ( 3823): Found 5 peers.
I/SS      ( 3823): Peer(1): XT1039_8c05 f4:f1:e1:5c:43:c8
,I/SS      ( 3823): Peer(2): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3823): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3823): Peer(4): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/SS      ( 3823): Peer(5): G3s-1 a2:39:f7:70:12:80
D/WifiP2pManager( 3823): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3823): Added service request
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 4733): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,W/bt-sdp  ( 2177): process_service_search_attr_rsp
,I/        ( 3823): Started service discovery
,W/bt-btif ( 2177): new conn_srvc id:26, app_id:1
,W/bt-btif ( 2177): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 2177): bta_dm_pm_ssr:2, lat:1200
I/BTConnectToThread( 3823): Starting to Handshake
,I/BTHandshakeSocketThread( 3823): Creating BTHandshakeSocketThread
I/BTConnectToThread( 3823): MESSAGE_WRITE 82 bytes.
I/BTHandshakeSocketThread( 3823): BTHandshakeSocketThread started
,I/BTConnectToThread( 3823): got MESSAGE_READ 81 bytes.
,I/BTConnectToThread( 3823): Got JSON from encryption:{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5358"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3823): HandshakeOk : motorola-XT1039_PT5358
I/HS      ( 3823): Hand Shake finished outgoing for : motorola-XT1039_PT5358
,I/BTHandshakeSocketThread( 3823): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3823): Starting the connected thread incoming : false, motorola-XT1039_PT5358
I/BtToSocketBase( 3823): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3823): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3823): mHTTPPort  set to : 33041
I/BtConnectorHelper( 3823): Request socket is using : 33041
I/BtToRequestSocket( 3823): Now accepting connections
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/BtConnectorHelper( 3823): Calling ConnectionStatusUpdate with port :33041
,I/jxcore-log( 3823): 2015-12-04T09:05:42.668Z SendDataConnector.js: CLIENT connected to 33041, error: null
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T09:05:42.668Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3823): 
,I/BtToRequestSocket( 3823): incoming data from: /127.0.0.1, port: 33041
,I/BtToRequestSocket( 3823): Set local streams
I/BtToRequestSocket( 3823): rin ended ---------------------------;
,I/jxcore-log( 3823): 2015-12-04T09:05:42.685Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 3823): 
,I/        ( 3823): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT7300","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
I/        ( 3823): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT7300","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT7300, peerAddress: 08:EC:A9:50:76:27
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT7300, WifiDirectName: Thali Test (Galaxy A3), WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,D/btif_config_util( 2177): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 3823): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5358"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5358"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT5358, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT5358, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/        ( 3823): Found Service, :{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2104","ra":"B0:C5:59:3F:75:69"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2104","ra":"B0:C5:59:3F:75:69"} -- peerIdentifier:B0:C5:59:3F:75:69, peerName: samsung-SM-G900F_PT2104, peerAddress: B0:C5:59:3F:75:69
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : B0:C5:59:3F:75:69, Name: samsung-SM-G900F_PT2104, WifiDirectName: Thali Test (Galaxy S5), WifiDirect Address: ee:1f:72:18:8b:78, peerId: B0:C5:59:3F:75:69
,I/        ( 3823): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT5230","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT5230","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT5230, peerAddress: F8:95:C7:87:85:54
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT5230, WifiDirectName: G3s-1, WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,W/bt-btif ( 2177): dm_pm_timer expires,
W/bt-btif ( 2177): dm_pm_timer expires 0
,W/bt-btif ( 2177): proc dm_pm_timer expires,
,I/BooksSync( 3710): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3710): GmsCore Version = 7.8.99 (2134222-430)
,V/KeepSync( 3727): Connecting to GoogleApiClient
,I/GLSUser ( 1492): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1492): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1492): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1492): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1492): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1492): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1492): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1492): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1492): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1492): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1822): Handling authorization failure
E/ClientConnectionOperation( 1822): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1822): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1822): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1822): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1822): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1822): 	... 7 more
,V/KeepSync( 3727): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3727): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3727): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3727): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1492): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1492): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1492): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1492): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1492): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3710): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3710): Soft error
E/BooksSync( 3710): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3710): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3710): Sync error
E/BooksSync( 3710): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3710): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3710): Finished books sync
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1352443, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1492): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1492): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1492): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1492): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1492): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3727): IOException
,E/KeepSync( 3727): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3727): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3727): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3727): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3727): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3727): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3727): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3727): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3727): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3727): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3727): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3727): 	,at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3727): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3727): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3727): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3727): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3727): 	... 10 more
W/KeepSync( 3727): Sync result 2
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 1348744, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/        ( 3823): Cleared service requests
,I/        ( 3823): Started peer discovery
,I/jxcore-log( 3823): 2015-12-04T09:05:52.754Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:05:52.755Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:05:52.756Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T09:05:52.757Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:05:52.758Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3823): 
,I/BtToSocketBase( 3823): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3823): Disconnect outgoing peer: motorola-XT1039_PT5358
,I/BtToSocketBase( 3823): Stop ReceivingThread
I/BtToSocketBase( 3823): Stop SendingThread
I/BtToSocketBase( 3823): Close local in
,I/BtToSocketBase( 3823): Close LocalOutputStream
I/BtToSocketBase( 3823): Close localHostSocket
I/BtToSocketBase( 3823): Close bt in
I/BtToSocketBase( 3823): Close bt out
,I/BtToSocketBase( 3823): Close bt socket
I/BtToRequestSocket( 3823): Close server socket
I/BtToSocketBase( 3823): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,W/bt-btif ( 2177): bta_jv_rfc_port_to_cb(port_handle:0x17):jv handle:0x0 not FOUND
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3823): Found 8 peers.
,I/SS      ( 3823): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3823): Peer(2): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3823): Peer(3): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3823): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
,I/SS      ( 3823): Peer(5): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3823): Peer(6): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3823): Peer(7): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3823): Peer(8): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 3823): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3823): Added service request
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3823): 2015-12-04T09:05:57.757Z SendDataConnector.js: re-try now : F4:F1:E1:5C:3B:E2
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:05:57.758Z SendDataConnector.js: ReStart called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3823): 
,E/bt-btm  ( 2177): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2177): onReceive,
,I/        ( 3823): Started service discovery
,I/BTConnectionReceiver( 1523): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1523): Bluetooth Device Name: XT1039
,D/HeadsetStateMachine( 2177): Disconnected process message: 10, size: 0
,I/jxcore-log( 3823): 2015-12-04T09:06:02.762Z SendDataConnector.js: Mobile.Disconnect() callback with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:06:02.763Z SendDataConnector.js: Connect (retry count 4) to peer F4:F1:E1:5C:3B:E2 with availability status: true
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T09:06:02.763Z SendDataConnector.js: doConnect called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T09:06:02.764Z SendDataConnector.js: do connect now
I/jxcore-log( 3823): 
,I/        ( 3823): Selected device address: F4:F1:E1:5C:3B:E2, name: XT1039
,I/BTConnectToThread( 3823): Starting to connect
,W/BluetoothAdapter( 3823): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3823): Connecting to XT1039, at F4:F1:E1:5C:3B:E2
,D/BTIF_SOCK( 2177): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-btif ( 2177): info:x10
D/        ( 2177): remote version info [f4:f1:e1:5c:3b:e2]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1523): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1523): Bluetooth Device Name: XT1039
,W/bt-sdp  ( 2177): process_service_search_attr_rsp
,W/bt-btif ( 2177): new conn_srvc id:26, app_id:1,
W/bt-btif ( 2177): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2177): bta_dm_pm_ssr:2, lat:1200
I/BTConnectToThread( 3823): Starting to Handshake
,I/BTHandshakeSocketThread( 3823): Creating BTHandshakeSocketThread
I/BTConnectToThread( 3823): MESSAGE_WRITE 82 bytes.
,I/BTHandshakeSocketThread( 3823): BTHandshakeSocketThread started
,I/BTConnectToThread( 3823): got MESSAGE_READ 81 bytes.,
I/BTConnectToThread( 3823): Got JSON from encryption:{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5358"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3823): HandshakeOk : motorola-XT1039_PT5358
,I/HS      ( 3823): Hand Shake finished outgoing for : motorola-XT1039_PT5358
I/BTHandshakeSocketThread( 3823): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3823): Starting the connected thread incoming : false, motorola-XT1039_PT5358
I/BtToSocketBase( 3823): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3823): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3823): mHTTPPort  set to : 60853
,I/BtConnectorHelper( 3823): Request socket is using : 60853
I/BtToRequestSocket( 3823): Now accepting connections
,I/BtConnectorHelper( 3823): Calling ConnectionStatusUpdate with port :60853
,I/jxcore-log( 3823): 2015-12-04T09:06:05.282Z SendDataConnector.js: CLIENT connected to 60853, error: null
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:06:05.282Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3823): 
,I/BtToRequestSocket( 3823): incoming data from: /127.0.0.1, port: 60853
,I/BtToRequestSocket( 3823): Set local streams
I/BtToRequestSocket( 3823): rin ended ---------------------------;
I/jxcore-log( 3823): 2015-12-04T09:06:05.291Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 3823): 
,I/        ( 3823): Found Service, :{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT6585"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT6585"} -- peerIdentifier:34:FC:EF:11:B1:66, peerName: LGE-Nexus 5_PT6585, peerAddress: 34:FC:EF:11:B1:66
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : 34:FC:EF:11:B1:66, Name: LGE-Nexus 5_PT6585, WifiDirectName: , WifiDirect Address: 52:55:27:f0:ff:f0, peerId: 34:FC:EF:11:B1:66
,I/        ( 3823): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5092","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5092","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT5092, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT5092, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 3823): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT7300","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT7300","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT7300, peerAddress: 08:EC:A9:50:76:27
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT7300, WifiDirectName: Thali Test (Galaxy A3), WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,I/        ( 3823): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT3722"}, typeCordovap2p._tcp.local.:
I/        ( 3823): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT3722"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT3722, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT3722, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,D/btif_config_util( 2177): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 3823): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5358"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5358"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT5358, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT5358, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/        ( 3823): Found Service, :{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2104","ra":"B0:C5:59:3F:75:69"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2104","ra":"B0:C5:59:3F:75:69"} -- peerIdentifier:B0:C5:59:3F:75:69, peerName: samsung-SM-G900F_PT2104, peerAddress: B0:C5:59:3F:75:69
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : B0:C5:59:3F:75:69, Name: samsung-SM-G900F_PT2104, WifiDirectName: Thali Test (Galaxy S5), WifiDirect Address: ee:1f:72:18:8b:78, peerId: B0:C5:59:3F:75:69
,I/        ( 3823): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT5230","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT5230","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT5230, peerAddress: F8:95:C7:87:85:54
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT5230, WifiDirectName: G3s-1, WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,W/bt-btif ( 2177): dm_pm_timer expires
,W/bt-btif ( 2177): dm_pm_timer expires 0
W/bt-btif ( 2177): proc dm_pm_timer expires
,I/wpa_supplicant( 4733): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78,
,I/wpa_supplicant( 4733): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
,I/        ( 3823): Found Service, :{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT8320"}, typeCordovap2p._tcp.local.:
I/        ( 3823): JsonLine: {"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT8320"} -- peerIdentifier:38:94:96:B5:06:DC, peerName: samsung-SM-G800H_PT8320, peerAddress: 38:94:96:B5:06:DC
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : 38:94:96:B5:06:DC, Name: samsung-SM-G800H_PT8320, WifiDirectName: , WifiDirect Address: 3a:94:96:b5:06:dd, peerId: 38:94:96:B5:06:DC
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3823): 2015-12-04T09:06:15.356Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T09:06:15.356Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T09:06:15.357Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:06:15.362Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T09:06:15.362Z SendDataConnector.js: Stop data retrieving timer
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:06:15.364Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3823): 
,I/BtConnectorHelper( 3823): Disconnect outgoing peer: F4:F1:E1:5C:3B:E2
,I/BtToSocketBase( 3823): Stop ReceivingThread
I/BtToSocketBase( 3823): Stop SendingThread
I/BtToSocketBase( 3823): Close local in
I/BtToSocketBase( 3823): Close LocalOutputStream
I/BtToSocketBase( 3823): Close localHostSocket,
I/BtToSocketBase( 3823): Close bt in
I/BtToSocketBase( 3823): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3823): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtToSocketBase( 3823): Close bt out
I/BtToSocketBase( 3823): Close bt socket
I/BtToRequestSocket( 3823): Close server socket
I/jxcore-log( 3823): 2015-12-04T09:06:15.370Z SendDataConnector.js: Mobile.Disconnect() callback with peer F4:F1:E1:5C:3B:E2,
I/jxcore-log( 3823): 
I/jxcore-log( 3823): ---- round done--------
I/jxcore-log( 3823): 
I/jxcore-log( 3823): ---- gotta redo : F4:F1:E1:5C:3B:E2, try count now: 1
I/jxcore-log( 3823): 
I/jxcore-log( 3823): do fake peer & start
I/jxcore-log( 3823): 
I/jxcore-log( 3823): Connect to fake peer: 58:2A:F7:ED:96:BE
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T09:06:15.373Z SendDataConnector.js: Start called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T09:06:15.374Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
,I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T09:06:15.374Z SendDataConnector.js: do connect now
I/jxcore-log( 3823): 
I/        ( 3823): Selected device address: 58:2A:F7:ED:96:BE, name: null
,I/BTConnectToThread( 3823): Starting to connect,
W/BluetoothAdapter( 3823): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 2177): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
I/        ( 3823): Connecting to null, at 58:2A:F7:ED:96:BE
I/jxcore-log( 3823): 2015-12-04T09:06:15.385Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3823): 
,I/chromium( 3823): [INFO:CONSOLE(63)] "logCallback Round of send data to peer F4:F1:E1:5C:3B:E2 done with result: DATA-TIMEOUT", source: file:///android_asset/www/js/thali_main.js (63)
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/HeadsetStateMachine( 2177): Disconnected process message: 10, size: 0
,E/bt-btm  ( 2177): tBTM_SEC_DEV:0xa2f175d4 rs_disc_pending=1
,W/bt-btif ( 2177): bta_dm_check_av:0
W/bt-btif ( 2177): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2177): tBTM_SEC_DEV:0xa2f175d4 rs_disc_pending=0
W/bt-btif ( 2177): bta_dm_check_av:0
W/bt-btif ( 2177): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2177): bta_jv_rfc_port_to_cb(port_handle:0x18):jv handle:0x0 not FOUND
,I/        ( 3823): Cleared service requests
I/wpa_supplicant( 4733): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3823): Started peer discovery
,E/bt-btm  ( 2177): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2177): onReceive
,I/BTConnectionReceiver( 1523): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1523): Bluetooth Device Name: XT1039
,W/bt-sdp  ( 2177): SDP - Rcvd conn cnf with error: 0x4  CID 0x48
E/bt-btif ( 2177): DISCOVERY_COMP_EVT slot id:76, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2177): invalid rfc slot id: 76
I/BTConnectToThread( 3823): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3823): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3823): 2015-12-04T09:06:21.248Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:06:21.249Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T09:06:21.249Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3823): 
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1,
,I/SS      ( 3823): Found 7 peers.
,I/SS      ( 3823): Peer(1): S5-1 ee:1f:72:63:11:86
,I/SS      ( 3823): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3823): Peer(3): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3823): Peer(4): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,I/SS      ( 3823): Peer(5): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3823): Peer(6): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3823): Peer(7): G3s-1 a2:39:f7:70:12:80
,D/WifiP2pManager( 3823): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3823): Added service request
,I/wpa_supplicant( 4733): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3823): Started service discovery
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3823): 2015-12-04T09:06:26.250Z SendDataConnector.js: re-try now : 58:2A:F7:ED:96:BE
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T09:06:26.251Z SendDataConnector.js: ReStart called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3823): 
,I/        ( 3823): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT3940","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
I/        ( 3823): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT3940","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT3940, peerAddress: E0:DB:10:1F:C9:5E
,I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT3940, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/        ( 3823): Found Service, :{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT8320"}, typeCordovap2p._tcp.local.:
I/        ( 3823): JsonLine: {"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT8320"} -- peerIdentifier:38:94:96:B5:06:DC, peerName: samsung-SM-G800H_PT8320, peerAddress: 38:94:96:B5:06:DC
,I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : 38:94:96:B5:06:DC, Name: samsung-SM-G800H_PT8320, WifiDirectName: , WifiDirect Address: 3a:94:96:b5:06:dd, peerId: 38:94:96:B5:06:DC
,I/jxcore-log( 3823): 2015-12-04T09:06:31.255Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T09:06:31.256Z SendDataConnector.js: Connect (retry count 1) to peer 58:2A:F7:ED:96:BE with availability status: true
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:06:31.257Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T09:06:31.257Z SendDataConnector.js: do connect now
I/jxcore-log( 3823): 
,I/        ( 3823): Selected device address: 58:2A:F7:ED:96:BE, name: null
,I/BTConnectToThread( 3823): Starting to connect
W/BluetoothAdapter( 3823): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3823): Connecting to null, at 58:2A:F7:ED:96:BE
,D/BTIF_SOCK( 2177): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,I/        ( 3823): Found Service, :{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT6585"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT6585"} -- peerIdentifier:34:FC:EF:11:B1:66, peerName: LGE-Nexus 5_PT6585, peerAddress: 34:FC:EF:11:B1:66
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : 34:FC:EF:11:B1:66, Name: LGE-Nexus 5_PT6585, WifiDirectName: , WifiDirect Address: 52:55:27:f0:ff:f0, peerId: 34:FC:EF:11:B1:66
,I/jxcore-log( 3823): timeout now
I/jxcore-log( 3823): 
I/jxcore-log( 3823): dun
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): weAreDoneNow , resultArray.length: 0
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): done, now sending data to server
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): DBG, CoordinatorConnector sendData called
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): -- RESULT DATA {"name:":"motorola-Nexus 6_PT1135","time":1000074,"result":"TIMEOUT","sendList":[{"connections":1,"name":"58:2A:F7:ED:96:BE","time":0,"result":"Fail"},{"connections":0,"name":"00:F4:6F:30:E0:6C","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:34:8A:A0","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:3C:51","time":0,"result":"Fail"},{"connections":0,"name":"34:FC:EF:9D:93:0B","time":0,"result":"Fail"},{"connections":0,"name":"B0:C5:59:3F:75:69","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:75:41","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:76:27","time":0,"result":"Fail"},{"connections":0,"name":"44:80:EB:7B:5A:05","time":0,"result":"Fail"},{"connections":0,"name":"38:94:96:B5:06:DC","time":0,"result":"Fail"},{"connections":1,"name":"34:FC:EF:11:B1:66","time":0,"result":"Fail"},{"connections":1,"name":"F8:95:C7:87:85:54","time":0,"result":"Fail"},{"connections":1,"name":"80:01:84:8A:B3:68","time":0,"result":"Fail"},{"connections":1,
,I/jxcore-log( 3823): sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
I/jxcore-log( 3823): 
I/jxcore-log( 3823): Results list does not contain any items
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): sendList failed peers count : 11 [100 %]
I/jxcore-log( 3823): 
I/jxcore-log( 3823): - Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
I/jxcore-log( 3823): 
I/jxcore-log( 3823): - Peer ID : 34:FC:EF:11:B1:66, Tried : 1
I/jxcore-log( 3823): 
I/jxcore-log( 3823): - Peer ID : F8:95:C7:87:85:54, Tried : 1
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): - Peer ID : 80:01:84:8A:B3:68, Tried : 1
I/jxcore-log( 3823): 
I/jxcore-log( 3823): - Peer ID : 34:FC:EF:11:AE:67, Tried : 1
I/jxcore-log( 3823): 
I/jxcore-log( 3823): - Peer ID : 7C:F9:0E:37:96:AB, Tried : 1
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): - Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1
I/jxcore-log( 3823): 
I/jxcore-log( 3823): - Peer ID : E0:DB:10:14:E2:C0, Tried : 1
I/jxcore-log( 3823): 
I/jxcore-log( 3823): - Peer ID : E0:DB:10:1F:C9:5E, Tried : 1
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): - Peer ID : 58:3F:54:73:64:C0, Tried : 1
I/jxcore-log( 3823): 
I/jxcore-log( 3823): - Peer ID : F4:F1:E1:5C:3B:E2, Tried : 1
I/jxcore-log( 3823): 
I/jxcore-log( 3823): sendList never tried peers count : 9 [45 %]
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): - Peer ID : 00:F4:6F:30:E0:6C
I/jxcore-log( 3823): 
I/jxcore-log( 3823): - Peer ID : 7C:F9:0E:34:8A:A0
I/jxcore-log( 3823): 
I/jxcore-log( 3823): - Peer ID : F8:95:C7:87:3C:51
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): - Peer ID : 34:FC:EF:9D:93:0B
I/jxcore-log( 3823): 
I/jxcore-log( 3823): - Peer ID : B0:C5:59:3F:75:69
I/jxcore-log( 3823): 
I/jxcore-log( 3823): - Peer ID : 08:EC:A9:50:75:41
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): - Peer ID : 08:EC:A9:50:76:27
I/jxcore-log( 3823): 
I/jxcore-log( 3823): - Peer ID : 44:80:EB:7B:5A:05
I/jxcore-log( 3823): 
I/jxcore-log( 3823): - Peer ID : 38:94:96:B5:06:DC
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:06:32.541Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T09:06:32.542Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3823): 
I/chromium( 3823): [INFO:CONSOLE(63)] "logCallback *** TIMEOUT ***", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3823): [INFO:CONSOLE(63)] "logCallback ---- finished : send-data -- ", source: file:///android_asset/www/js/thali_main.js (63)
,I/        ( 3823): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5358"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5358"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT5358, peerAddress: F4:F1:E1:5C:3B:E2
,I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT5358, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/        ( 3823): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT5230","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT5230","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT5230, peerAddress: F8:95:C7:87:85:54
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT5230, WifiDirectName: G3s-1, WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,W/bt-sdp  ( 2177): SDP - Rcvd conn cnf with error: 0x4  CID 0x43
,E/bt-btif ( 2177): DISCOVERY_COMP_EVT slot id:77, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2177): invalid rfc slot id: 77
I/BTConnectToThread( 3823): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3823): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3823): 2015-12-04T09:06:36.417Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T09:06:36.418Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:06:36.419Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3823): 
,I/        ( 3823): Found Service, :{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2104","ra":"B0:C5:59:3F:75:69"}, typeCordovap2p._tcp.local.:
I/        ( 3823): JsonLine: {"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2104","ra":"B0:C5:59:3F:75:69"} -- peerIdentifier:B0:C5:59:3F:75:69, peerName: samsung-SM-G900F_PT2104, peerAddress: B0:C5:59:3F:75:69
,I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : B0:C5:59:3F:75:69, Name: samsung-SM-G900F_PT2104, WifiDirectName: , WifiDirect Address: ee:1f:72:18:8b:78, peerId: B0:C5:59:3F:75:69
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 4733): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,I/jxcore-log( 3823): 2015-12-04T09:06:41.420Z SendDataConnector.js: re-try now : 58:2A:F7:ED:96:BE
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T09:06:41.421Z SendDataConnector.js: ReStart called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3823): 
,I/        ( 3823): Cleared service requests
I/wpa_supplicant( 4733): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3823): Started peer discovery
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3823): Found 7 peers.
,I/SS      ( 3823): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3823): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3823): Peer(3): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3823): Peer(4): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3823): Peer(5): S5mini-1 02:f4:6f:30:e0:6d
,I/SS      ( 3823): Peer(6): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3823): Peer(7): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiP2pManager( 3823): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3823): Added service request
,I/        ( 3823): Started service discovery
,I/jxcore-log( 3823): 2015-12-04T09:06:46.424Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:06:46.425Z SendDataConnector.js: Connect (retry count 2) to peer 58:2A:F7:ED:96:BE with availability status: true
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T09:06:46.425Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T09:06:46.426Z SendDataConnector.js: do connect now
I/jxcore-log( 3823): 
,I/        ( 3823): Selected device address: 58:2A:F7:ED:96:BE, name: null
,I/BTConnectToThread( 3823): Starting to connect
,W/BluetoothAdapter( 3823): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3823): Connecting to null, at 58:2A:F7:ED:96:BE
,D/BTIF_SOCK( 2177): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3823): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT5230","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT5230","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT5230, peerAddress: F8:95:C7:87:85:54
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT5230, WifiDirectName: G3s-1, WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,I/        ( 3823): Found Service, :{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2104","ra":"B0:C5:59:3F:75:69"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2104","ra":"B0:C5:59:3F:75:69"} -- peerIdentifier:B0:C5:59:3F:75:69, peerName: samsung-SM-G900F_PT2104, peerAddress: B0:C5:59:3F:75:69
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : B0:C5:59:3F:75:69, Name: samsung-SM-G900F_PT2104, WifiDirectName: Thali Test (Galaxy S5), WifiDirect Address: ee:1f:72:18:8b:78, peerId: B0:C5:59:3F:75:69
,I/        ( 3823): Found Service, :{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT8320"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT8320"} -- peerIdentifier:38:94:96:B5:06:DC, peerName: samsung-SM-G800H_PT8320, peerAddress: 38:94:96:B5:06:DC
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : 38:94:96:B5:06:DC, Name: samsung-SM-G800H_PT8320, WifiDirectName: , WifiDirect Address: 3a:94:96:b5:06:dd, peerId: 38:94:96:B5:06:DC
,I/GLSUser ( 1492): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1492): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1492): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1492): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1492): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3215): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3215): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3215): 	at jdm.a(PG:82)
E/HttpOperation( 3215): 	at jcs.o(PG:406)
E/HttpOperation( 3215): 	at jcn.a(PG:1379)
E/HttpOperation( 3215): 	at jcs.i(PG:143)
E/HttpOperation( 3215): 	at blb.a(PG:3937)
E/HttpOperation( 3215): 	at czp.a(PG:18188)
E/HttpOperation( 3215): 	at czp.a(PG:9081)
E/HttpOperation( 3215): 	at czq.run(PG:1686)
E/HttpOperation( 3215): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3215): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3215): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3215): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3215): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3215): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3215): 	at jdj.a(PG:4091)
E/HttpOperation( 3215): 	at jdj.a(PG:1125)
E/HttpOperation( 3215): 	at jdm.a(PG:77)
E/HttpOperation( 3215): 	... 12 more
E/HttpOperation( 3215): Caused by: faj: BadAuthentication
E/HttpOperation( 3215): 	at fal.a(PG:38)
E/HttpOperation( 3215): 	at jdj.a(PG:4089)
E/HttpOperation( 3215): 	... 14 more
,I/GLSUser ( 1492): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1492): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1492): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1492): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1492): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3215): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3215): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3215): 	at jdm.a(PG:82)
E/HttpOperation( 3215): 	at jcs.o(PG:406)
E/HttpOperation( 3215): 	at jcn.a(PG:1379)
E/HttpOperation( 3215): 	at jcs.i(PG:143)
E/HttpOperation( 3215): 	at hec.a(PG:42)
E/HttpOperation( 3215): 	at hee.a(PG:102)
E/HttpOperation( 3215): 	at czr.a(PG:65)
,E/HttpOperation( 3215): 	at kka.a(PG:108)
E/HttpOperation( 3215): 	at czp.a(PG:19176)
E/HttpOperation( 3215): 	at czp.a(PG:9081)
E/HttpOperation( 3215): 	at czq.run(PG:1686)
E/HttpOperation( 3215): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3215): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3215): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112),
E/HttpOperation( 3215): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3215): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3215): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3215): 	at jdj.a(PG:4091)
E/HttpOperation( 3215): 	at jdj.a(PG:1125)
E/HttpOperation( 3215): 	at jdm.a(PG:77)
E/HttpOperation( 3215): 	... 15 more
E/HttpOperation( 3215): Caused by: faj: BadAuthentication
E/HttpOperation( 3215): 	at fal.a(PG:38)
E/HttpOperation( 3215): 	at jdj.a(PG:4089)
E/HttpOperation( 3215): 	... 17 more
,E/ExperimentLoader( 3215): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3215): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3215): 	at jdm.a(PG:82)
E/ExperimentLoader( 3215): 	at jcs.o(PG:406)
E/ExperimentLoader( 3215): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3215): 	at jcs.i(PG:143)
E/ExperimentLoader( 3215): 	at hec.a(PG:42)
E/ExperimentLoader( 3215): 	at hee.a(PG:102)
E/ExperimentLoader( 3215): 	at czr.a(PG:65)
E/ExperimentLoader( 3215): 	at kka.a(PG:108)
E/ExperimentLoader( 3215): 	at czp.a(PG:19176)
,E/ExperimentLoader( 3215): 	at czp.a(PG:9081)
E/ExperimentLoader( 3215): 	at czq.run(PG:1686)
E/ExperimentLoader( 3215): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3215): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3215): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3215): ,	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3215): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3215): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3215): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3215): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3215): 	at jdm.a(PG:77)
E/ExperimentLoader( 3215): 	... 15 more
E/ExperimentLoader( 3215): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3215): 	at fal.a(PG:38)
E/ExperimentLoader( 3215): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3215): 	... 17 more
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 1408969, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,W/bt-sdp  ( 2177): SDP - Rcvd conn cnf with error: 0x4  CID 0x4e,
E/bt-btif ( 2177): DISCOVERY_COMP_EVT slot id:78, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2177): invalid rfc slot id: 78
I/BTConnectToThread( 3823): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3823): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3823): 2015-12-04T09:06:51.588Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:06:51.589Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:06:51.590Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3823): 
,I/        ( 3823): Cleared service requests
,I/        ( 3823): Started peer discovery
,I/jxcore-log( 3823): 2015-12-04T09:06:56.590Z SendDataConnector.js: re-try now : 58:2A:F7:ED:96:BE
I/jxcore-log( 3823): ,
I/jxcore-log( 3823): 2015-12-04T09:06:56.591Z SendDataConnector.js: ReStart called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3823): 
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3823): Found 8 peers.
,I/SS      ( 3823): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3823): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3823): Peer(3): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3823): Peer(4): G3s-1 a2:39:f7:70:12:80
,I/SS      ( 3823): Peer(5): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3823): Peer(6): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3823): Peer(7): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3823): Peer(8): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 3823): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3823): Added service request
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/        ( 3823): Started service discovery
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3823): 2015-12-04T09:07:01.595Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:07:01.596Z SendDataConnector.js: Connect (retry count 3) to peer 58:2A:F7:ED:96:BE with availability status: true
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T09:07:01.596Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:07:01.597Z SendDataConnector.js: do connect now
I/jxcore-log( 3823): 
,I/        ( 3823): Selected device address: 58:2A:F7:ED:96:BE, name: null
,I/        ( 3823): Connecting to null, at 58:2A:F7:ED:96:BE
,I/BTConnectToThread( 3823): Starting to connect
W/BluetoothAdapter( 3823): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2177): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,I/        ( 3823): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT5230","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT5230","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT5230, peerAddress: F8:95:C7:87:85:54
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT5230, WifiDirectName: G3s-1, WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,I/        ( 3823): Found Service, :{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2104","ra":"B0:C5:59:3F:75:69"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2104","ra":"B0:C5:59:3F:75:69"} -- peerIdentifier:B0:C5:59:3F:75:69, peerName: samsung-SM-G900F_PT2104, peerAddress: B0:C5:59:3F:75:69
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : B0:C5:59:3F:75:69, Name: samsung-SM-G900F_PT2104, WifiDirectName: Thali Test (Galaxy S5), WifiDirect Address: ee:1f:72:18:8b:78, peerId: B0:C5:59:3F:75:69
,I/        ( 3823): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT3940","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT3940","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT3940, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT3940, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/        ( 3823): Found Service, :{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT8320"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT8320"} -- peerIdentifier:38:94:96:B5:06:DC, peerName: samsung-SM-G800H_PT8320, peerAddress: 38:94:96:B5:06:DC
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : 38:94:96:B5:06:DC, Name: samsung-SM-G800H_PT8320, WifiDirectName: , WifiDirect Address: 3a:94:96:b5:06:dd, peerId: 38:94:96:B5:06:DC
,I/        ( 3823): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5092","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5092","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT5092, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT5092, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,W/bt-sdp  ( 2177): SDP - Rcvd conn cnf with error: 0x4  CID 0x42
E/bt-btif ( 2177): DISCOVERY_COMP_EVT slot id:79, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2177): invalid rfc slot id: 79
I/BTConnectToThread( 3823): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3823): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3823): 2015-12-04T09:07:06.755Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:07:06.756Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:07:06.757Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3823): 
,I/        ( 3823): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT3722"}, typeCordovap2p._tcp.local.:,
,I/        ( 3823): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT3722"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT3722, peerAddress: 34:FC:EF:9D:93:0B
,I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT3722, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/        ( 3823): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5358"}, typeCordovap2p._tcp.local.:
I/        ( 3823): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5358"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT5358, peerAddress: F4:F1:E1:5C:3B:E2
,I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT5358, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0,
I/wpa_supplicant( 4733): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 4733): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
,I/jxcore-log( 3823): 2015-12-04T09:07:11.760Z SendDataConnector.js: re-try now : 58:2A:F7:ED:96:BE
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T09:07:11.760Z SendDataConnector.js: ReStart called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3823): 
,I/        ( 3823): Cleared service requests
I/wpa_supplicant( 4733): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3823): Started peer discovery
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3823): Found 8 peers.
,I/SS      ( 3823): Peer(1): S5-1 ee:1f:72:63:11:86
,I/SS      ( 3823): Peer(2): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3823): Peer(3): Thali Test's G2 36:fc:ef:de:0a:e2,
I/SS      ( 3823): Peer(4): G3s-1 a2:39:f7:70:12:80,
I/SS      ( 3823): Peer(5): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3823): Peer(6): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3823): Peer(7): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3823): Peer(8): Thali Test (Galaxy S5) ee:1f:72:18:8b:78,
D/WifiP2pManager( 3823): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3823): Added service request
,I/wpa_supplicant( 4733): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3823): Started service discovery
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3823): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT5230","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
I/        ( 3823): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT5230","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT5230, peerAddress: F8:95:C7:87:85:54
,I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT5230, WifiDirectName: G3s-1, WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54,
,I/        ( 3823): Found Service, :{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2104","ra":"B0:C5:59:3F:75:69"}, typeCordovap2p._tcp.local.:
I/        ( 3823): JsonLine: {"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2104","ra":"B0:C5:59:3F:75:69"} -- peerIdentifier:B0:C5:59:3F:75:69, peerName: samsung-SM-G900F_PT2104, peerAddress: B0:C5:59:3F:75:69
,I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : B0:C5:59:3F:75:69, Name: samsung-SM-G900F_PT2104, WifiDirectName: Thali Test (Galaxy S5), WifiDirect Address: ee:1f:72:18:8b:78, peerId: B0:C5:59:3F:75:69
,D/HeadsetStateMachine( 2177): Disconnected process message: 10, size: 0
,I/        ( 3823): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT3940","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
I/        ( 3823): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT3940","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT3940, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT3940, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/        ( 3823): Found Service, :{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT8320"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT8320"} -- peerIdentifier:38:94:96:B5:06:DC, peerName: samsung-SM-G800H_PT8320, peerAddress: 38:94:96:B5:06:DC
,I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : 38:94:96:B5:06:DC, Name: samsung-SM-G800H_PT8320, WifiDirectName: , WifiDirect Address: 3a:94:96:b5:06:dd, peerId: 38:94:96:B5:06:DC
,I/        ( 3823): Found Service, :{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT6585"}, typeCordovap2p._tcp.local.:
I/        ( 3823): JsonLine: {"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT6585"} -- peerIdentifier:34:FC:EF:11:B1:66, peerName: LGE-Nexus 5_PT6585, peerAddress: 34:FC:EF:11:B1:66
,I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : 34:FC:EF:11:B1:66, Name: LGE-Nexus 5_PT6585, WifiDirectName: Android_2dc2, WifiDirect Address: 52:55:27:f0:ff:f0, peerId: 34:FC:EF:11:B1:66
,I/        ( 3823): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5092","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 3823): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5092","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT5092, peerAddress: 7C:F9:0E:34:8A:A0
,I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT5092, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/jxcore-log( 3823): 2015-12-04T09:07:16.763Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:07:16.764Z SendDataConnector.js: Connect (retry count 4) to peer 58:2A:F7:ED:96:BE with availability status: true
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:07:16.765Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3823): 
I/jxcore-log( 3823): 2015-12-04T09:07:16.765Z SendDataConnector.js: do connect now
I/jxcore-log( 3823): 
,I/        ( 3823): Selected device address: 58:2A:F7:ED:96:BE, name: null
,I/BTConnectToThread( 3823): Starting to connect
,W/BluetoothAdapter( 3823): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3823): Connecting to null, at 58:2A:F7:ED:96:BE
,D/BTIF_SOCK( 2177): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,I/        ( 3823): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT3722"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT3722"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT3722, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT3722, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/        ( 3823): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5358"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5358"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT5358, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT5358, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,V/KeepSync( 3727): Connecting to GoogleApiClient
,I/GLSUser ( 1492): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1492): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1492): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1492): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1492): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1822): Handling authorization failure
E/ClientConnectionOperation( 1822): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1822): 	,at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1822): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1822): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1822): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1822): Caused by: com.google.android.gms.auth.ad: BadAuthentication
,E/ClientConnectionOperation( 1822): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1822): 	,at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1822): 	... 7 more
,V/KeepSync( 3727): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3727): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3727): (284) automatic index on blob_node(is_deleted),
E/SQLiteLog( 3727): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1492): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive,
I/GLSUser ( 1492): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1492): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1492): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1492): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3727): IOException
E/KeepSync( 3727): com.google.android.apiary.AuthenticationException: Could not get an auth token
,E/KeepSync( 3727): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3727): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3727): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3727): 	,at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3727): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3727): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3727): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3727): 	at com.google.android.keep.util.m.a(SourceFile:207)
,E/KeepSync( 3727): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3727): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3727): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3727): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3727): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
,E/KeepSync( 3727): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3727): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3727): 	... 10 more
W/KeepSync( 3727): Sync result 2
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 1439612, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1],
,W/bt-sdp  ( 2177): SDP - Rcvd conn cnf with error: 0x4  CID 0x4f
,E/bt-btif ( 2177): DISCOVERY_COMP_EVT slot id:80, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2177): invalid rfc slot id: 80
I/BTConnectToThread( 3823): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3823): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3823): 2015-12-04T09:07:21.931Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:07:21.932Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:07:21.939Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:07:21.942Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3823): 
,I/        ( 3823): Cleared service requests
,I/wpa_supplicant( 4733): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3823): Started peer discovery
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 4733): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3823): Found 8 peers.
,I/SS      ( 3823): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3823): Peer(2): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3823): Peer(3): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3823): Peer(4): G3s-1 a2:39:f7:70:12:80
,I/SS      ( 3823): Peer(5): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3823): Peer(6): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3823): Peer(7): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3823): Peer(8): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 3823): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3823): Added service request
,I/wpa_supplicant( 4733): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3823): Started service discovery
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1,
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/        ( 3823): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT5230","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:,
I/        ( 3823): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT5230","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT5230, peerAddress: F8:95:C7:87:85:54
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT5230, WifiDirectName: G3s-1, WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,I/        ( 3823): Cleared service requests
,I/        ( 3823): Started peer discovery,
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/SS      ( 3823): Found 8 peers.
I/SS      ( 3823): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3823): Peer(2): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3823): Peer(3): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3823): Peer(4): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3823): Peer(5): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3823): Peer(6): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3823): Peer(7): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3823): Peer(8): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 3823): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3823): Added service request
,I/        ( 3823): Started service discovery
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND 3a:94:96:b5:06:dd p2p_dev_addr=3a:94:96:b5:06:dd pri_dev_type=10-0050F204-5 name='Galaxy S5-2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/        ( 3823): Found Service, :{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT4244","ra":"7C:F9:0E:37:96:AB"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT4244","ra":"7C:F9:0E:37:96:AB"} -- peerIdentifier:7C:F9:0E:37:96:AB, peerName: samsung-SM-A500FU_PT4244, peerAddress: 7C:F9:0E:37:96:AB
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : 7C:F9:0E:37:96:AB, Name: samsung-SM-A500FU_PT4244, WifiDirectName: , WifiDirect Address: 7e:f9:0e:37:96:ac, peerId: 7C:F9:0E:37:96:AB
,I/        ( 3823): Cleared service requests
,I/        ( 3823): Started peer discovery
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND 3a:94:96:b5:06:dd p2p_dev_addr=3a:94:96:b5:06:dd pri_dev_type=10-0050F204-5 name='Galaxy S5-2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 3823): Found 10 peers.
,I/SS      ( 3823): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3823): Peer(2): Galaxy S5-2 3a:94:96:b5:06:dd,
I/SS      ( 3823): Peer(3): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3823): Peer(4): Android_2dc2 52:55:27:f0:ff:f0
,I/SS      ( 3823): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3823): Peer(6): G3s-1 a2:39:f7:70:12:80
,I/SS      ( 3823): Peer(7): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3823): Peer(8): Note3-1 ea:50:8b:de:28:a3
,I/SS      ( 3823): Peer(9): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3823): Peer(10): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 3823): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3823): Added service request
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3823): Started service discovery
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 4733): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3823): Found Service, :{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT4244","ra":"7C:F9:0E:37:96:AB"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT4244","ra":"7C:F9:0E:37:96:AB"} -- peerIdentifier:7C:F9:0E:37:96:AB, peerName: samsung-SM-A500FU_PT4244, peerAddress: 7C:F9:0E:37:96:AB
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : 7C:F9:0E:37:96:AB, Name: samsung-SM-A500FU_PT4244, WifiDirectName: A5-1, WifiDirect Address: 7e:f9:0e:37:96:ac, peerId: 7C:F9:0E:37:96:AB
,I/        ( 3823): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT5230","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT5230","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT5230, peerAddress: F8:95:C7:87:85:54
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT5230, WifiDirectName: G3s-1, WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,I/        ( 3823): Cleared service requests
,I/        ( 3823): Started peer discovery
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1,
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0,
I/wpa_supplicant( 4733): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1,
,I/SS      ( 3823): Found 10 peers.,
I/SS      ( 3823): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3823): Peer(2): Galaxy S5-2 3a:94:96:b5:06:dd
I/SS      ( 3823): Peer(3): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3823): Peer(4): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3823): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3823): Peer(6): G3s-1 a2:39:f7:70:12:80,
I/SS      ( 3823): Peer(7): XT1039_8c05 f4:f1:e1:5c:43:c8
,I/SS      ( 3823): Peer(8): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3823): Peer(9): S5mini-1 02:f4:6f:30:e0:6d,
I/SS      ( 3823): Peer(10): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiP2pManager( 3823): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3823): Added service request
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND 3a:94:96:b5:06:dd p2p_dev_addr=3a:94:96:b5:06:dd pri_dev_type=10-0050F204-5 name='Galaxy S5-2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1,
I/wpa_supplicant( 4733): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3823): Started service discovery
,I/        ( 3823): Found Service, :{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT4244","ra":"7C:F9:0E:37:96:AB"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT4244","ra":"7C:F9:0E:37:96:AB"} -- peerIdentifier:7C:F9:0E:37:96:AB, peerName: samsung-SM-A500FU_PT4244, peerAddress: 7C:F9:0E:37:96:AB
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : 7C:F9:0E:37:96:AB, Name: samsung-SM-A500FU_PT4244, WifiDirectName: A5-1, WifiDirect Address: 7e:f9:0e:37:96:ac, peerId: 7C:F9:0E:37:96:AB
,I/        ( 3823): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT5230","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT5230","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT5230, peerAddress: F8:95:C7:87:85:54
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT5230, WifiDirectName: G3s-1, WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,I/        ( 3823): Cleared service requests
,I/        ( 3823): Started peer discovery
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 4733): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3823): Found 10 peers.
I/SS      ( 3823): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3823): Peer(2): Galaxy S5-2 3a:94:96:b5:06:dd
I/SS      ( 3823): Peer(3): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3823): Peer(4): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3823): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3823): Peer(6): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3823): Peer(7): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3823): Peer(8): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3823): Peer(9): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3823): Peer(10): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 3823): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3823): Added service request
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3823): Started service discovery
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3823): Found Service, :{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT4244","ra":"7C:F9:0E:37:96:AB"}, typeCordovap2p._tcp.local.:,
I/        ( 3823): JsonLine: {"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT4244","ra":"7C:F9:0E:37:96:AB"} -- peerIdentifier:7C:F9:0E:37:96:AB, peerName: samsung-SM-A500FU_PT4244, peerAddress: 7C:F9:0E:37:96:AB
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : 7C:F9:0E:37:96:AB, Name: samsung-SM-A500FU_PT4244, WifiDirectName: A5-1, WifiDirect Address: 7e:f9:0e:37:96:ac, peerId: 7C:F9:0E:37:96:AB
,I/        ( 3823): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT5230","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:,
I/        ( 3823): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT5230","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT5230, peerAddress: F8:95:C7:87:85:54
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT5230, WifiDirectName: G3s-1, WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,I/        ( 3823): Found Service, :{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2104","ra":"B0:C5:59:3F:75:69"}, typeCordovap2p._tcp.local.:,
I/        ( 3823): JsonLine: {"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2104","ra":"B0:C5:59:3F:75:69"} -- peerIdentifier:B0:C5:59:3F:75:69, peerName: samsung-SM-G900F_PT2104, peerAddress: B0:C5:59:3F:75:69
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : B0:C5:59:3F:75:69, Name: samsung-SM-G900F_PT2104, WifiDirectName: Thali Test (Galaxy S5), WifiDirect Address: ee:1f:72:18:8b:78, peerId: B0:C5:59:3F:75:69
,I/        ( 3823): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT3940","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:,
I/        ( 3823): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT3940","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT3940, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT3940, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/        ( 3823): Found Service, :{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT8320"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT8320"} -- peerIdentifier:38:94:96:B5:06:DC, peerName: samsung-SM-G800H_PT8320, peerAddress: 38:94:96:B5:06:DC
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : 38:94:96:B5:06:DC, Name: samsung-SM-G800H_PT8320, WifiDirectName: Galaxy S5-2, WifiDirect Address: 3a:94:96:b5:06:dd, peerId: 38:94:96:B5:06:DC
,I/        ( 3823): Found Service, :{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT6585"}, typeCordovap2p._tcp.local.:
I/        ( 3823): JsonLine: {"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT6585"} -- peerIdentifier:34:FC:EF:11:B1:66, peerName: LGE-Nexus 5_PT6585, peerAddress: 34:FC:EF:11:B1:66
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : 34:FC:EF:11:B1:66, Name: LGE-Nexus 5_PT6585, WifiDirectName: Android_2dc2, WifiDirect Address: 52:55:27:f0:ff:f0, peerId: 34:FC:EF:11:B1:66
,D/HeadsetStateMachine( 2177): Disconnected process message: 10, size: 0
,I/        ( 3823): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5092","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 3823): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5092","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT5092, peerAddress: 7C:F9:0E:34:8A:A0
,I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT5092, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 3823): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT3722"}, typeCordovap2p._tcp.local.:,
I/        ( 3823): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT3722"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT3722, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT3722, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/        ( 3823): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5358"}, typeCordovap2p._tcp.local.:,
I/        ( 3823): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5358"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT5358, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT5358, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0,
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/        ( 3823): Found Service, :{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT74","ra":"34:FC:EF:11:AE:67"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT74","ra":"34:FC:EF:11:AE:67"} -- peerIdentifier:34:FC:EF:11:AE:67, peerName: LGE-Nexus 5_PT74, peerAddress: 34:FC:EF:11:AE:67
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : 34:FC:EF:11:AE:67, Name: LGE-Nexus 5_PT74, WifiDirectName: , WifiDirect Address: 52:55:27:f0:fd:0b, peerId: 34:FC:EF:11:AE:67
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 4733): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 4733): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 4733): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/BooksSync( 3710): Starting books sync for 61035162, extras: ade
,I/art     (  820): Explicit concurrent mark sweep GC freed 54645(2MB) AllocSpace objects, 10(537KB) LOS objects, 31% free, 34MB/50MB, paused 1.481ms total 94.551ms
,I/BooksConfig( 3710): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1492): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1492): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1492): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1492): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1492): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1492): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1492): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1492): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1492): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1492): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3710): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3710): Soft error
E/BooksSync( 3710): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3710): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3710): Sync error
E/BooksSync( 3710): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3710): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3710): Finished books sync
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1507308, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND 3a:94:96:b5:06:dd p2p_dev_addr=3a:94:96:b5:06:dd pri_dev_type=10-0050F204-5 name='Galaxy S5-2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/        ( 3823): Cleared service requests
,I/        ( 3823): Started peer discovery
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3823): Found 11 peers.
,I/SS      ( 3823): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3823): Peer(2): Galaxy S5-2 3a:94:96:b5:06:dd
,I/SS      ( 3823): Peer(3): A5-1 7e:f9:0e:37:96:ac
,I/SS      ( 3823): Peer(4): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3823): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3823): Peer(6): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3823): Peer(7): XT1039_8c05 f4:f1:e1:5c:43:c8
,I/SS      ( 3823): Peer(8): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3823): Peer(9): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3823): Peer(10): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 3823): Peer(11): Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pManager( 3823): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3823): Added service request
,I/wpa_supplicant( 4733): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3823): Started service discovery
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1,
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 4733): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3823): Found Service, :{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT74","ra":"34:FC:EF:11:AE:67"}, typeCordovap2p._tcp.local.:
I/        ( 3823): JsonLine: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT74","ra":"34:FC:EF:11:AE:67"} -- peerIdentifier:34:FC:EF:11:AE:67, peerName: LGE-Nexus 5_PT74, peerAddress: 34:FC:EF:11:AE:67
,I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : 34:FC:EF:11:AE:67, Name: LGE-Nexus 5_PT74, WifiDirectName: Android_8ae2, WifiDirect Address: 52:55:27:f0:fd:0b, peerId: 34:FC:EF:11:AE:67
,I/        ( 3823): Found Service, :{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT4244","ra":"7C:F9:0E:37:96:AB"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT4244","ra":"7C:F9:0E:37:96:AB"} -- peerIdentifier:7C:F9:0E:37:96:AB, peerName: samsung-SM-A500FU_PT4244, peerAddress: 7C:F9:0E:37:96:AB
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : 7C:F9:0E:37:96:AB, Name: samsung-SM-A500FU_PT4244, WifiDirectName: A5-1, WifiDirect Address: 7e:f9:0e:37:96:ac, peerId: 7C:F9:0E:37:96:AB
,I/        ( 3823): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT5230","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:,
I/        ( 3823): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT5230","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT5230, peerAddress: F8:95:C7:87:85:54,
,I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT5230, WifiDirectName: G3s-1, WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,I/        ( 3823): Found Service, :{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2104","ra":"B0:C5:59:3F:75:69"}, typeCordovap2p._tcp.local.:
I/        ( 3823): JsonLine: {"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2104","ra":"B0:C5:59:3F:75:69"} -- peerIdentifier:B0:C5:59:3F:75:69, peerName: samsung-SM-G900F_PT2104, peerAddress: B0:C5:59:3F:75:69
,I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : B0:C5:59:3F:75:69, Name: samsung-SM-G900F_PT2104, WifiDirectName: Thali Test (Galaxy S5), WifiDirect Address: ee:1f:72:18:8b:78, peerId: B0:C5:59:3F:75:69
,I/        ( 3823): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT3940","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT3940","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT3940, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT3940, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/        ( 3823): Found Service, :{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT8320"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT8320"} -- peerIdentifier:38:94:96:B5:06:DC, peerName: samsung-SM-G800H_PT8320, peerAddress: 38:94:96:B5:06:DC
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : 38:94:96:B5:06:DC, Name: samsung-SM-G800H_PT8320, WifiDirectName: Galaxy S5-2, WifiDirect Address: 3a:94:96:b5:06:dd, peerId: 38:94:96:B5:06:DC
,I/        ( 3823): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5092","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 3823): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5092","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT5092, peerAddress: 7C:F9:0E:34:8A:A0
,I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT5092, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 3823): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT3722"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT3722"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT3722, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT3722, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/        ( 3823): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5358"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5358"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT5358, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT5358, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND 3a:94:96:b5:06:dd p2p_dev_addr=3a:94:96:b5:06:dd pri_dev_type=10-0050F204-5 name='Galaxy S5-2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3823): Cleared service requests
I/        ( 3823): Started peer discovery
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3823): Found 11 peers.
,I/SS      ( 3823): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3823): Peer(2): Galaxy S5-2 3a:94:96:b5:06:dd
I/SS      ( 3823): Peer(3): A5-1 7e:f9:0e:37:96:ac
,I/SS      ( 3823): Peer(4): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3823): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3823): Peer(6): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3823): Peer(7): XT1039_8c05 f4:f1:e1:5c:43:c8
,I/SS      ( 3823): Peer(8): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3823): Peer(9): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3823): Peer(10): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 3823): Peer(11): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3823): Ignored { when=-4ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3823): Added service request
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3823): Started service discovery
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3823): Found Service, :{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT4244","ra":"7C:F9:0E:37:96:AB"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT4244","ra":"7C:F9:0E:37:96:AB"} -- peerIdentifier:7C:F9:0E:37:96:AB, peerName: samsung-SM-A500FU_PT4244, peerAddress: 7C:F9:0E:37:96:AB
,I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : 7C:F9:0E:37:96:AB, Name: samsung-SM-A500FU_PT4244, WifiDirectName: A5-1, WifiDirect Address: 7e:f9:0e:37:96:ac, peerId: 7C:F9:0E:37:96:AB
,I/        ( 3823): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT5230","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
I/        ( 3823): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT5230","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT5230, peerAddress: F8:95:C7:87:85:54
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT5230, WifiDirectName: G3s-1, WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,I/        ( 3823): Found Service, :{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2104","ra":"B0:C5:59:3F:75:69"}, typeCordovap2p._tcp.local.:
I/        ( 3823): JsonLine: {"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2104","ra":"B0:C5:59:3F:75:69"} -- peerIdentifier:B0:C5:59:3F:75:69, peerName: samsung-SM-G900F_PT2104, peerAddress: B0:C5:59:3F:75:69
,I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : B0:C5:59:3F:75:69, Name: samsung-SM-G900F_PT2104, WifiDirectName: Thali Test (Galaxy S5), WifiDirect Address: ee:1f:72:18:8b:78, peerId: B0:C5:59:3F:75:69
,I/        ( 3823): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT3940","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT3940","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT3940, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT3940, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/        ( 3823): Found Service, :{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT8320"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT8320"} -- peerIdentifier:38:94:96:B5:06:DC, peerName: samsung-SM-G800H_PT8320, peerAddress: 38:94:96:B5:06:DC
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : 38:94:96:B5:06:DC, Name: samsung-SM-G800H_PT8320, WifiDirectName: Galaxy S5-2, WifiDirect Address: 3a:94:96:b5:06:dd, peerId: 38:94:96:B5:06:DC
,I/        ( 3823): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT3722"}, typeCordovap2p._tcp.local.:
I/        ( 3823): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT3722"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT3722, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT3722, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/        ( 3823): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5358"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5358"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT5358, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT5358, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3823): Cleared service requests
,I/        ( 3823): Started peer discovery
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 3823): Found 11 peers.
I/SS      ( 3823): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3823): Peer(2): Galaxy S5-2 3a:94:96:b5:06:dd
I/SS      ( 3823): Peer(3): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3823): Peer(4): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3823): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3823): Peer(6): G3s-1 a2:39:f7:70:12:80
,I/SS      ( 3823): Peer(7): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3823): Peer(8): Note3-1 ea:50:8b:de:28:a3,
I/SS      ( 3823): Peer(9): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3823): Peer(10): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 3823): Peer(11): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3823): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3823): Added service request
,I/        ( 3823): Started service discovery
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 4733): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3823): Found Service, :{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT4244","ra":"7C:F9:0E:37:96:AB"}, typeCordovap2p._tcp.local.:,
I/        ( 3823): JsonLine: {"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT4244","ra":"7C:F9:0E:37:96:AB"} -- peerIdentifier:7C:F9:0E:37:96:AB, peerName: samsung-SM-A500FU_PT4244, peerAddress: 7C:F9:0E:37:96:AB
,I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : 7C:F9:0E:37:96:AB, Name: samsung-SM-A500FU_PT4244, WifiDirectName: A5-1, WifiDirect Address: 7e:f9:0e:37:96:ac, peerId: 7C:F9:0E:37:96:AB
,I/        ( 3823): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT5230","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:,
I/        ( 3823): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT5230","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT5230, peerAddress: F8:95:C7:87:85:54
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT5230, WifiDirectName: G3s-1, WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,I/        ( 3823): Found Service, :{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2104","ra":"B0:C5:59:3F:75:69"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2104","ra":"B0:C5:59:3F:75:69"} -- peerIdentifier:B0:C5:59:3F:75:69, peerName: samsung-SM-G900F_PT2104, peerAddress: B0:C5:59:3F:75:69
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : B0:C5:59:3F:75:69, Name: samsung-SM-G900F_PT2104, WifiDirectName: Thali Test (Galaxy S5), WifiDirect Address: ee:1f:72:18:8b:78, peerId: B0:C5:59:3F:75:69
,I/        ( 3823): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT3940","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:,
I/        ( 3823): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT3940","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT3940, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT3940, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/        ( 3823): Cleared service requests
,I/        ( 3823): Started peer discovery
,D/HeadsetStateMachine( 2177): Disconnected process message: 10, size: 0
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3823): Found 11 peers.
,I/SS      ( 3823): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3823): Peer(2): Galaxy S5-2 3a:94:96:b5:06:dd
,I/SS      ( 3823): Peer(3): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3823): Peer(4): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3823): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
,I/SS      ( 3823): Peer(6): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3823): Peer(7): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3823): Peer(8): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3823): Peer(9): S5mini-1 02:f4:6f:30:e0:6d
,I/SS      ( 3823): Peer(10): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 3823): Peer(11): Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pManager( 3823): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3823): Added service request
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3823): Started service discovery
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3823): Found Service, :{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT4244","ra":"7C:F9:0E:37:96:AB"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT4244","ra":"7C:F9:0E:37:96:AB"} -- peerIdentifier:7C:F9:0E:37:96:AB, peerName: samsung-SM-A500FU_PT4244, peerAddress: 7C:F9:0E:37:96:AB
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : 7C:F9:0E:37:96:AB, Name: samsung-SM-A500FU_PT4244, WifiDirectName: A5-1, WifiDirect Address: 7e:f9:0e:37:96:ac, peerId: 7C:F9:0E:37:96:AB
,I/        ( 3823): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT5230","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT5230","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT5230, peerAddress: F8:95:C7:87:85:54
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT5230, WifiDirectName: G3s-1, WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,D/HeadsetStateMachine( 2177): Disconnected process message: 10, size: 0
,I/        ( 3823): Found Service, :{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2104","ra":"B0:C5:59:3F:75:69"}, typeCordovap2p._tcp.local.:
I/        ( 3823): JsonLine: {"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2104","ra":"B0:C5:59:3F:75:69"} -- peerIdentifier:B0:C5:59:3F:75:69, peerName: samsung-SM-G900F_PT2104, peerAddress: B0:C5:59:3F:75:69
,I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : B0:C5:59:3F:75:69, Name: samsung-SM-G900F_PT2104, WifiDirectName: Thali Test (Galaxy S5), WifiDirect Address: ee:1f:72:18:8b:78, peerId: B0:C5:59:3F:75:69
,I/art     ( 3215): Explicit concurrent mark sweep GC freed 43859(2MB) AllocSpace objects, 0(0B) LOS objects, 16% free, 40MB/48MB, paused 538us total 42.808ms
,I/art     ( 1492): Explicit concurrent mark sweep GC freed 53618(2MB) AllocSpace objects, 10(1102KB) LOS objects, 36% free, 27MB/43MB, paused 952us total 32.460ms
,I/GLSUser ( 1492): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1492): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1492): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1492): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1492): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3215): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
,E/HttpOperation( 3215): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3215): 	at jdm.a(PG:82)
E/HttpOperation( 3215): 	at jcs.o(PG:406)
E/HttpOperation( 3215): 	at jcn.a(PG:1379)
E/HttpOperation( 3215): 	at jcs.i(PG:143)
E/HttpOperation( 3215): 	at blb.a(PG:3937)
,E/HttpOperation( 3215): 	at czp.a(PG:18188)
E/HttpOperation( 3215): 	at czp.a(PG:9081)
E/HttpOperation( 3215): 	at czq.run(PG:1686)
E/HttpOperation( 3215): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3215): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3215): 	,at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3215): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3215): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3215): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3215): 	at jdj.a(PG:4091),
E/HttpOperation( 3215): 	at jdj.a(PG:1125)
E/HttpOperation( 3215): 	at jdm.a(PG:77)
E/HttpOperation( 3215): 	... 12 more
E/HttpOperation( 3215): Caused by: faj: BadAuthentication
,E/HttpOperation( 3215): 	at fal.a(PG:38)
E/HttpOperation( 3215): 	at jdj.a(PG:4089)
E/HttpOperation( 3215): 	... 14 more
,I/GLSUser ( 1492): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1492): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1492): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1492): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1492): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/HttpOperation( 3215): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3215): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3215): 	at jdm.a(PG:82)
E/HttpOperation( 3215): 	at jcs.o(PG:406)
E/HttpOperation( 3215): 	at jcn.a(PG:1379)
E/HttpOperation( 3215): 	at jcs.i(PG:143)
E/HttpOperation( 3215): 	at hec.a(PG:42)
E/HttpOperation( 3215): 	at hee.a(PG:102)
E/HttpOperation( 3215): 	at czr.a(PG:65)
E/HttpOperation( 3215): 	at kka.a(PG:108)
E/HttpOperation( 3215): 	at czp.a(PG:19176)
E/HttpOperation( 3215): 	at czp.a(PG:9081)
E/HttpOperation( 3215): 	at czq.run(PG:1686)
E/HttpOperation( 3215): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3215): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3215): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3215): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3215): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3215): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3215): ,	at jdj.a(PG:4091)
E/HttpOperation( 3215): 	at jdj.a(PG:1125)
E/HttpOperation( 3215): 	at jdm.a(PG:77)
E/HttpOperation( 3215): ,	... 15 more
E/HttpOperation( 3215): Caused by: faj: BadAuthentication
E/HttpOperation( 3215): 	at fal.a(PG:38)
E/HttpOperation( 3215): 	at jdj.a(PG:4089)
E/HttpOperation( 3215): 	,... 17 more
E/ExperimentLoader( 3215): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3215): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3215): 	at jdm.a(PG:82)
E/ExperimentLoader( 3215): 	at jcs.o(PG:406)
E/ExperimentLoader( 3215): ,	at jcn.a(PG:1379)
E/ExperimentLoader( 3215): 	at jcs.i(PG:143)
E/ExperimentLoader( 3215): 	at hec.a(PG:42)
E/ExperimentLoader( 3215): 	at hee.a(PG:102)
E/ExperimentLoader( 3215): ,	at czr.a(PG:65)
E/ExperimentLoader( 3215): 	at kka.a(PG:108)
E/ExperimentLoader( 3215): 	at czp.a(PG:19176)
E/ExperimentLoader( 3215): 	at czp.a(PG:9081),
E/ExperimentLoader( 3215): 	at czq.run(PG:1686)
E/ExperimentLoader( 3215): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3215): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3215): 	,at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3215): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3215): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3215): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3215): 	at jdj.a(PG:4091)
,E/ExperimentLoader( 3215): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3215): 	at jdm.a(PG:77)
E/ExperimentLoader( 3215): 	... 15 more
E/ExperimentLoader( 3215): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3215): ,	at fal.a(PG:38)
E/ExperimentLoader( 3215): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3215): 	... 17 more
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 1560416, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,I/        ( 3823): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT3940","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT3940","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT3940, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT3940, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/        ( 3823): Cleared service requests,
,I/        ( 3823): Started peer discovery
,W/bt-btm  ( 2177): Stopping oneshot timer
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1,
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3823): Found 11 peers.
,I/SS      ( 3823): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3823): Peer(2): Galaxy S5-2 3a:94:96:b5:06:dd
I/SS      ( 3823): Peer(3): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3823): Peer(4): Android_2dc2 52:55:27:f0:ff:f0
,I/SS      ( 3823): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3823): Peer(6): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3823): Peer(7): XT1039_8c05 f4:f1:e1:5c:43:c8
,I/SS      ( 3823): Peer(8): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3823): Peer(9): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3823): Peer(10): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/SS      ( 3823): Peer(11): Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pManager( 3823): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3823): Added service request
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3823): Started service discovery
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3823): Found Service, :{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT4244","ra":"7C:F9:0E:37:96:AB"}, typeCordovap2p._tcp.local.:
I/        ( 3823): JsonLine: {"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT4244","ra":"7C:F9:0E:37:96:AB"} -- peerIdentifier:7C:F9:0E:37:96:AB, peerName: samsung-SM-A500FU_PT4244, peerAddress: 7C:F9:0E:37:96:AB
,I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : 7C:F9:0E:37:96:AB, Name: samsung-SM-A500FU_PT4244, WifiDirectName: A5-1, WifiDirect Address: 7e:f9:0e:37:96:ac, peerId: 7C:F9:0E:37:96:AB
,I/        ( 3823): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT5230","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
I/        ( 3823): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT5230","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT5230, peerAddress: F8:95:C7:87:85:54
,I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT5230, WifiDirectName: G3s-1, WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,I/        ( 3823): Found Service, :{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2104","ra":"B0:C5:59:3F:75:69"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2104","ra":"B0:C5:59:3F:75:69"} -- peerIdentifier:B0:C5:59:3F:75:69, peerName: samsung-SM-G900F_PT2104, peerAddress: B0:C5:59:3F:75:69
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : B0:C5:59:3F:75:69, Name: samsung-SM-G900F_PT2104, WifiDirectName: Thali Test (Galaxy S5), WifiDirect Address: ee:1f:72:18:8b:78, peerId: B0:C5:59:3F:75:69
,I/        ( 3823): Cleared service requests
,I/        ( 3823): Started peer discovery,
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3823): Found 11 peers.
I/SS      ( 3823): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3823): Peer(2): Galaxy S5-2 3a:94:96:b5:06:dd
I/SS      ( 3823): Peer(3): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3823): Peer(4): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3823): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3823): Peer(6): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3823): Peer(7): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3823): Peer(8): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3823): Peer(9): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3823): Peer(10): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 3823): Peer(11): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3823): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3823): Added service request
,I/        ( 3823): Started service discovery
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3823): Found Service, :{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT4244","ra":"7C:F9:0E:37:96:AB"}, typeCordovap2p._tcp.local.:
I/        ( 3823): JsonLine: {"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT4244","ra":"7C:F9:0E:37:96:AB"} -- peerIdentifier:7C:F9:0E:37:96:AB, peerName: samsung-SM-A500FU_PT4244, peerAddress: 7C:F9:0E:37:96:AB
,I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : 7C:F9:0E:37:96:AB, Name: samsung-SM-A500FU_PT4244, WifiDirectName: A5-1, WifiDirect Address: 7e:f9:0e:37:96:ac, peerId: 7C:F9:0E:37:96:AB
,I/        ( 3823): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT5230","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT5230","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT5230, peerAddress: F8:95:C7:87:85:54
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT5230, WifiDirectName: G3s-1, WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,I/        ( 3823): Found Service, :{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2104","ra":"B0:C5:59:3F:75:69"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2104","ra":"B0:C5:59:3F:75:69"} -- peerIdentifier:B0:C5:59:3F:75:69, peerName: samsung-SM-G900F_PT2104, peerAddress: B0:C5:59:3F:75:69
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : B0:C5:59:3F:75:69, Name: samsung-SM-G900F_PT2104, WifiDirectName: Thali Test (Galaxy S5), WifiDirect Address: ee:1f:72:18:8b:78, peerId: B0:C5:59:3F:75:69
,I/art     ( 3727): Explicit concurrent mark sweep GC freed 19765(2MB) AllocSpace objects, 0(0B) LOS objects, 25% free, 23MB/31MB, paused 497us total 42.265ms
,V/KeepSync( 3727): Connecting to GoogleApiClient
,I/GLSUser ( 1492): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1492): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1492): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1492): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1492): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1822): Handling authorization failure
E/ClientConnectionOperation( 1822): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1822): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1822): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1822): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1822): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1822): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1822): 	... 7 more
,V/KeepSync( 3727): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3727): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3727): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3727): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1492): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1492): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1492): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1492): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1492): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3727): IOException
E/KeepSync( 3727): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3727): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3727): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3727): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3727): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3727): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3727): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3727): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3727): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3727): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3727): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3727): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3727): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3727): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3727): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3727): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3727): 	... 10 more
,W/KeepSync( 3727): Sync result 2
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 1591596, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/        ( 3823): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT3940","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
I/        ( 3823): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT3940","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT3940, peerAddress: E0:DB:10:1F:C9:5E
,I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT3940, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/        ( 3823): Found Service, :{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT8320"}, typeCordovap2p._tcp.local.:,
I/        ( 3823): JsonLine: {"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT8320"} -- peerIdentifier:38:94:96:B5:06:DC, peerName: samsung-SM-G800H_PT8320, peerAddress: 38:94:96:B5:06:DC
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : 38:94:96:B5:06:DC, Name: samsung-SM-G800H_PT8320, WifiDirectName: Galaxy S5-2, WifiDirect Address: 3a:94:96:b5:06:dd, peerId: 38:94:96:B5:06:DC
,I/        ( 3823): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5092","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 3823): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5092","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT5092, peerAddress: 7C:F9:0E:34:8A:A0
,I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT5092, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 3823): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT3722"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT3722"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT3722, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT3722, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/        ( 3823): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5358"}, typeCordovap2p._tcp.local.:
,I/        ( 3823): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5358"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT5358, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3823): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT5358, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/HeadsetStateMachine( 2177): Disconnected process message: 10, size: 0
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3823): Cleared service requests
,I/        ( 3823): Started peer discovery
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3823): Found 11 peers.,
I/SS      ( 3823): Peer(1): S5-1 ee:1f:72:63:11:86
,I/SS      ( 3823): Peer(2): Galaxy S5-2 3a:94:96:b5:06:dd
,I/SS      ( 3823): Peer(3): A5-1 7e:f9:0e:37:96:ac
,I/SS      ( 3823): Peer(4): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3823): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2,
I/SS      ( 3823): Peer(6): G3s-1 a2:39:f7:70:12:80
,I/SS      ( 3823): Peer(7): XT1039_8c05 f4:f1:e1:5c:43:c8
,I/SS      ( 3823): Peer(8): Note3-1 ea:50:8b:de:28:a3
,I/SS      ( 3823): Peer(9): S5mini-1 02:f4:6f:30:e0:6d
,I/SS      ( 3823): Peer(10): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 3823): Peer(11): Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pManager( 3823): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3823): Added service request
,I/wpa_supplicant( 4733): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3823): Started service discovery
,I/wpa_supplicant( 4733): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 4733): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
,I/wpa_supplicant( 4733): P2P-DEVICE-LOST p2p_dev_addr=3a:94:96:b5:06:dd
,D/HeadsetStateMachine( 2177): Disconnected process message: 10, size: 0
,I/wpa_supplicant( 4733): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:fd:0b
I/wpa_supplicant( 4733): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
,I/jxcore-log( 3823): DBG, CoordinatorConnector command called
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): stop tests now !
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): stop current!
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): testSendData stopped
I/jxcore-log( 3823): 
,I/        ( 3823): Stoping All
,I/        ( 3823): Stopping services
I/        ( 3823): Stopping services
,I/        ( 3823): Stop Bluetooth
,I/        ( 3823): Stop Bluetooth
I/BTListenerThread( 3823): Stopped
,I/jxcore-log( 3823): StopBroadcasting went ok
,I/jxcore-log( 3823): 
,I/jxcore-log( 3823): 2015-12-04T09:10:52.560Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
I/jxcore-log( 3823): 
,I/chromium( 3823): [INFO:CONSOLE(63)] "logCallback stop", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3823): DBG, CoordinatorConnector command called,
I/jxcore-log( 3823): 
I/jxcore-log( 3823): command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[],\"sendError\":{\"failedPeer\":[{\"connections\":1,\"name\":\"58:2A:F7:ED:96:BE\",\"time\":0,\"result\":\"Fail\"},{\"connections\":1,\"name\":\"34:FC:EF:11:B1:66\",\"time\":0,\"result\":\"Fail\"},{\"connections\":1,\"name\":\"F8:95:C7:87:85:54\",\"time\":0,\"result\":\"Fail\"},{\"connections\":1,\"name\":\"80:01:84:8A:B3:68\",\"time\":0,\"result\":\"Fail\"},{\"connections\":1,\"name\":\"34:FC:EF:11:AE:67\",\"time\":0,\"result\":\"Fail\"},{\"connections\":1,\"name\":\"7C:F9:0E:37:96:AB\",\"time\":0,\"result\":\"Fail\"},{\"connections\":1,\"name\":\"B4:CE:F6:AB:A4:6A\",\"time\":0,\"result\":\"Fail\"},{\"connections\":1,\"name\":\"E0:DB:10:14:E2:C0\",\"time\":0,\"result\":\"Fail\"},{\"connections\":1,\"name\":\"E0:DB:10:1F:C9:5E\",\"time\":0,\"result\":\"Fail\"},{\"connections\":1,\"name\":\"58:3F:54:73:64:C0\",\"time\":0,\"result\":\"Fail\"},{\"connections\":1,\"name\":\"F4:F1:E1:5C:3B:E2\",\"time\":0,\"result\":\"
I/jxcore-log( 3823): ****TEST TOOK:  ms ****
I/jxcore-log( 3823): 
I/jxcore-log( 3823): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3823): 
I/jxcore-log( 3823): stop tests now !
I/jxcore-log( 3823): 
I/jxcore-log( 3823): end, event received
I/jxcore-log( 3823): 
I/jxcore-log( 3823): CoordinatorConnector close called
I/jxcore-log( 3823): 
,I/jxcore-log( 3823): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 3823): 
I/jxcore-log( 3823): The Coordinator has disconnected!
I/jxcore-log( 3823): 
I/jxcore-log( 3823): The Coordinator has closed!
I/jxcore-log( 3823): 
I/jxcore-log( 3823): stop tests now !
I/jxcore-log( 3823): 
I/jxcore-log( 3823): turning Radios off
I/jxcore-log( 3823): 
I/jxcore-log( 3823): Toggling radios to false
I/jxcore-log( 3823): 
D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
D/BluetoothManagerService(  820): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@33080ea7 mBinding = false
,D/BluetoothManagerService(  820): Message: 2
,D/WifiService(  820): setWifiEnabled: false pid=3823, uid=10265,
E/WifiService(  820): Invoking mWifiStateMachine.setWifiEnabled
D/BluetoothManagerService(  820): Sending off request.
D/BluetoothAdapterState( 2177): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 2177): Setting state to 13
I/BluetoothAdapterState( 2177): Bluetooth adapter state changed: 12-> 13
D/BluetoothAdapterProperties( 2177): onBluetoothDisable()
I/BluetoothAdapterState( 2177): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,D/BluetoothAdapterProperties( 2177): Scan Mode:20
D/BluetoothAdapterState( 2177): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,V/BluetoothMapMasInstance( 2177): Accept exception: (expected at shutdown)
V/BluetoothMapMasInstance( 2177): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 2177): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
V/BluetoothMapMasInstance( 2177): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:489)
V/BluetoothMapMasInstance( 2177): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:399)
V/BluetoothMapMasInstance( 2177): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
V/BluetoothMapMasInstance( 2177): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
V/BluetoothMapMasInstance( 2177): 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
,D/btif_config_util( 2177): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
D/BluetoothManagerService(  820): Message: 60
D/BluetoothManagerService(  820): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService(  820): Bluetooth State Change Intent: 12 -> 13
E/BtOppRfcommListener( 2177): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
W/bt-btif ( 2177): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
W/bt-l2cap( 2177): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2177): L2CAP - PSM: 0x0017 not found for deregistration
D/BluetoothMapService( 2177): onReceive
D/BluetoothMapService( 2177): STATE_TURNING_OFF
D/BluetoothMapService( 2177): MAP Service closeService in
D/BluetoothMapMasInstance( 2177): MAP Service shutdown
I/BtOppRfcommListener( 2177): stopping Accept Thread
I/BtOppRfcommListener( 2177): BluetoothSocket listen thread finished
I/jxcore-log( 3823): Radios toggled
I/jxcore-log( 3823): 
I/chromium( 3823): [INFO:CONSOLE(63)] "logCallback fully-closed", source: file:///android_asset/www/js/thali_main.js (63)
E/WifiStateMachine(  820): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  820): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,W/ContextImpl( 4243): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,I/ActivityManager(  820): Start proc 4939:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,D/BluetoothManagerService(  820): Message: 30
,D/BluetoothManagerService(  820): Message: 30
,D/LocalBluetoothProfileManager( 4243): Adding local MAP profile
D/BluetoothMap( 4243): Create BluetoothMap proxy object
,D/BluetoothManagerService(  820): Message: 30
,D/BluetoothManagerService(  820): Message: 30
,D/LocalBluetoothProfileManager( 4243): LocalBluetoothProfileManager construction complete
,D/DockEventReceiver( 4243): finishStartingService: stopping service
,D/BluetoothInputDevice( 4243): Proxy object connected
,D/HidProfile( 4243): Bluetooth service connected
,D/BluetoothPan( 4243): BluetoothPAN Proxy object connected
,D/PanProfile( 4243): Bluetooth service connected
,D/BluetoothMap( 4243): Proxy object connected
,D/MapProfile( 4243): Bluetooth service connected
D/BluetoothMap( 4243): getConnectedDevices()
D/BluetoothMap( 4243): Bluetooth is Not enabled
,D/AndroidRuntime( 4935): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,D/AndroidRuntime( 4935): CheckJNI is OFF
,W/bt-btif ( 2177): ag scb idx 1 not allocated
E/bt-btif ( 2177): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 2177): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2177): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2177): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2177): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2177): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2177): L2CAP - PSM: 0x0017 not found for deregistration
D/bt_userial( 2177): RX termination
W/bt_userial( 2177): select_read return size <=0:-1, exiting userial_read_thread
D/bt_userial( 2177): Leaving userial_read_thread()
,D/bt_userial( 2177): userial_close_reader Joined userial reader thread: 0
D/bt_hwcfg( 2177): hw_epilog_process
I/bt_userial_vendor( 2177): device fd = 53 close
,D/AndroidRuntime( 4935): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  820): Force stopping com.test.thalitest appid=10265 user=-1: uninstall pkg
I/ActivityManager(  820): Killing 3823:com.test.thalitest/u0a265 (adj 0): stop com.test.thalitest
,I/GKI_LINUX( 2177): gki_task task_id=0 [BTU] terminating
,W/PackageSettings(  820): Skipping PackageSetting{1fdf0255 com.example.hello/10272} due to missing metadata
,I/GKI_LINUX( 2177): GKI_exit_task 0 done
I/GKI_LINUX( 2177): GKI_shutdown(): task [BTU] terminated
,D/BluetoothAdapterState( 2177): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,I/WindowState(  820): WIN DEATH: Window{2ec67a3d u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  820): Client connection lost with reason: 4
,W/ActivityManager(  820): Force removing ActivityRecord{1fdd9e7a u0 com.test.thalitest/.MainActivity t24}: app died, no saved state
,V/ActivityManager(  820): Display changed displayId=0
,I/ActivityManager(  820): Force stopping com.test.thalitest appid=10265 user=0: pkg removed
,W/ActivityManager(  820): Spurious death for ProcessRecord{420316d 3823:com.test.thalitest/u0a265}, curProc for 3823: null
,D/TaskPersister(  820): removeObsoleteFile: deleting file=24_task.xml
,D/HeadsetService( 2177): Received stop request...Stopping profile...
D/HeadsetStateMachine( 2177): Exit Disconnected: -1
D/AsyncChannel(  820): TODO: handle replyToMessage RemoteExceptionandroid.os.DeadObjectException
W/System.err(  820): android.os.DeadObjectException
W/System.err(  820): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err(  820): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err(  820): 	at android.os.IMessenger$Stub$Proxy.send(IMessenger.java:89)
W/System.err(  820): 	at android.os.Messenger.send(Messenger.java:57)
W/System.err(  820): 	at com.android.internal.util.AsyncChannel.replyToMessage(AsyncChannel.java:568)
W/System.err(  820): 	at com.android.server.wifi.p2p.WifiP2pServiceImpl$P2pStateMachine.replyToMessage(WifiP2pServiceImpl.java:2815)
W/System.err(  820): 	at com.android.server.wifi.p2p.WifiP2pServiceImpl$P2pStateMachine.access$3500(WifiP2pServiceImpl.java:477)
W/System.err(  820): 	at com.android.server.wifi.p2p.WifiP2pServiceImpl$P2pStateMachine$P2pEnabledState.processMessage(WifiP2pServiceImpl.java:1098)
W/System.err(  820): 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:967)
W/System.err(  820): 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:790)
W/System.err(  820): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  820): 	at android.os.Looper.loop(Looper.java:135)
W/System.err(  820): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/A2dpService( 2177): Received stop request...Stopping profile...
,D/A2dpStateMachine( 2177): Exit Disconnected: -1
,I/InputReader(  820): Reconfiguring input devices.  changes=0x00000010
,D/BluetoothAdapterState( 2177): Stopping profile services that were post enabled
,D/HidService( 2177): Received stop request...Stopping profile...
,D/HeadsetStateMachine( 2177): Unbinding service...
D/BluetoothInputDevice( 4243): Proxy object disconnected
D/HidProfile( 4243): Bluetooth service disconnected
,W/BluetoothHeadsetServiceJni( 2177): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 2177): Cleaning up Bluetooth Handsfree callback object
D/HealthService( 2177): Received stop request...Stopping profile...
,D/PanService( 2177): Received stop request...Stopping profile...,
D/BtGatt.DebugUtils( 2177): handleDebugAction() action=null
D/BtGatt.GattService( 2177): Received stop request...Stopping profile...
D/BtGatt.GattService( 2177): stop()
D/BtGatt.AdvertiseManager( 2177): advertise clients cleared
I/GKI_LINUX( 2177): gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 2177): GKI_exit_task 2 done
I/GKI_LINUX( 2177): GKI_shutdown(): task [A2DP-MEDIA] terminated
D/BluetoothMapService( 2177): Received stop request...Stopping profile...
D/BluetoothMapService( 2177): stop()
D/BluetoothMapEmailAppObserver( 2177): deinitObservers(),
D/BluetoothMapEmailAppObserver( 2177): removeReceiver()
W/BluetoothHidServiceJni( 2177): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 2177): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 2177): Cleaning up Bluetooth GID callback object
,D/BluetoothPan( 4243): BluetoothPAN Proxy object disconnected
W/BluetoothHealthServiceJni( 2177): Cleaning up Bluetooth Health Interface...
D/PanProfile( 4243): Bluetooth service disconnected
W/BluetoothHealthServiceJni( 2177): Cleaning up Bluetooth Health object
W/BluetoothPanServiceJni( 2177): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 2177): Cleaning up Bluetooth PAN callback object
D/BluetoothMapService( 2177): MAP Service closeService in
,D/BluetoothAdapterState( 2177): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothMapService( 2177): cleanup()
D/BluetoothAdapterProperties( 2177): Setting state to 10
,D/BluetoothMapService( 2177): MAP Service closeService in
I/BluetoothAdapterState( 2177): Bluetooth adapter state changed: 13-> 10
I/BluetoothAdapterState( 2177): Entering OffState
,D/BluetoothManagerService(  820): Message: 60
D/BluetoothManagerService(  820): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10,
D/BluetoothManagerService(  820): Broadcasting onBluetoothStateChange(false) to 17 receivers.
D/BluetoothA2dp(  820): onBluetoothStateChange: up=false
D/BluetoothA2dp( 1064): onBluetoothStateChange: up=false
D/BluetoothMap( 4243): onBluetoothStateChange: up=false
,I/art     ( 1064): Explicit concurrent mark sweep GC freed 91525(3MB) AllocSpace objects, 0(0B) LOS objects, 17% free, 75MB/91MB, paused 1.379ms total 75.228ms,
D/BluetoothInputDevice( 1064): Proxy object disconnected
D/BluetoothMap( 1064): Proxy object disconnected
,I/Keyboard.Facilitator( 1212): resetDictionaries() : en_US
,I/art     (  820): Explicit concurrent mark sweep GC freed 43865(2MB) AllocSpace objects, 10(442KB) LOS objects, 31% free, 34MB/50MB, paused 3.323ms total 95.297ms
,D/BluetoothMap( 4243): Proxy object disconnected
D/MapProfile( 4243): Bluetooth service disconnected
,D/BluetoothHeadset( 1278): Proxy object disconnected
,D/BluetoothHeadset(  820): Proxy object disconnected
D/BluetoothHeadset( 1064): Proxy object disconnected
D/BluetoothHeadset(  820): Proxy object disconnected
D/BluetoothHeadset(  820): Proxy object disconnected
,D/BluetoothHeadset( 1278): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1064): onBluetoothStateChange: up=false
D/BluetoothHeadset(  820): onBluetoothStateChange: up=false
D/BluetoothPbap( 4243): onBluetoothStateChange: up=false
,I/Keyboard.Facilitator.DecoderInitializer( 1212): run()
,D/BluetoothHeadset(  820): onBluetoothStateChange: up=false
D/BluetoothHeadset(  820): onBluetoothStateChange: up=false
D/BluetoothAvrcpController( 1064): onBluetoothStateChange: up=false
,E/BluetoothAvrcpController( 1064): 
E/BluetoothAvrcpController( 1064): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothAvrcpController$2@74e57de
E/BluetoothAvrcpController( 1064): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1029)
E/BluetoothAvrcpController( 1064): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1808)
E/BluetoothAvrcpController( 1064): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:551)
E/BluetoothAvrcpController( 1064): 	at android.bluetooth.BluetoothAvrcpController$1.onBluetoothStateChange(BluetoothAvrcpController.java:80)
E/BluetoothAvrcpController( 1064): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothAvrcpController( 1064): 	at android.os.Binder.execTransact(Binder.java:446)
D/BluetoothMap( 1064): onBluetoothStateChange: up=false
,I/Decoder ( 1212): createOrResetDecoder
I/art     ( 1523): Explicit concurrent mark sweep GC freed 68697(3MB) AllocSpace objects, 15(248KB) LOS objects, 37% free, 26MB/42MB, paused 649us total 118.586ms
,D/BluetoothHeadsetClient( 1064): onBluetoothStateChange: up=false
E/BluetoothHeadsetClient( 1064): 
E/BluetoothHeadsetClient( 1064): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothHeadsetClient$2@ed53dbf
E/BluetoothHeadsetClient( 1064): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1029)
E/BluetoothHeadsetClient( 1064): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1808)
E/BluetoothHeadsetClient( 1064): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:551)
E/BluetoothHeadsetClient( 1064): 	at android.bluetooth.BluetoothHeadsetClient$1.onBluetoothStateChange(BluetoothHeadsetClient.java:382)
E/BluetoothHeadsetClient( 1064): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothHeadsetClient( 1064): 	at android.os.Binder.execTransact(Binder.java:446)
,D/BluetoothInputDevice( 4243): onBluetoothStateChange: up=false
,D/BluetoothInputDevice( 1064): onBluetoothStateChange: up=false
,D/BluetoothA2dpSink( 1064): onBluetoothStateChange: up=false
E/BluetoothA2dpSink( 1064): 
E/BluetoothA2dpSink( 1064): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothA2dpSink$2@a55ac8c
E/BluetoothA2dpSink( 1064): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1029)
E/BluetoothA2dpSink( 1064): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1808)
E/BluetoothA2dpSink( 1064): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:551)
E/BluetoothA2dpSink( 1064): 	at android.bluetooth.BluetoothA2dpSink$1.onBluetoothStateChange(BluetoothA2dpSink.java:139)
E/BluetoothA2dpSink( 1064): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothA2dpSink( 1064): 	at android.os.Binder.execTransact(Binder.java:446)
,D/BluetoothManagerService(  820): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService(  820): Broadcasting onBluetoothServiceDown() to 8 receivers.
,D/BluetoothManagerService(  820): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@33080ea7 mBinding = false
,D/BluetoothManagerService(  820): Sending unbind request.
D/BluetoothManagerService(  820): Bluetooth State Change Intent: 13 -> 10
,D/BluetoothAdapter( 1064): 172309662: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1064): 172309662: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1064): 172309662: getState() :  mService = null. Returning STATE_OFF
,I/GKI_LINUX( 2177): gki_task task_id=1 [BTIF] terminating
,I/GKI_LINUX( 2177): GKI_exit_task 1 done
I/GKI_LINUX( 2177): GKI_shutdown(): task [BTIF] terminated
I/BluetoothServiceJni( 2177): cleanupNative: return from cleanup
,I/art     ( 2177): System.exit called, status: 0
I/AndroidRuntime( 2177): VM exiting with result code 0, cleanup skipped.
,I/ConfigService( 1492): onCreate
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1212): run()
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1212): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1212): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1212): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1212): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1212): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1212): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1212): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1212): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1212): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1212): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1212): run()
I/StatsUtilsManager( 1212): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1212): shouldRecordStats() = Too Soon
W/InputMethodManagerService(  820): Got RemoteException sending setActive(false) notification to pid 3823 uid 10265
,I/Keyboard.Facilitator( 1212): onFinishInput()
,D/JobSchedulerService(  820): Receieved: android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  820): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,I/ActivityManager(  820): Process com.android.bluetooth (pid 2177) has died
,D/StrictMode( 4939): StrictMode policy violation; ~duration=628 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4939): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4939): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 4939): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 4939): 	at java.io.File.exists(File.java:363)
D/StrictMode( 4939): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:995)
D/StrictMode( 4939): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1018)
D/StrictMode( 4939): 	at android.content.ContextWrapper.getFilesDir(ContextWrapper.java:202)
D/StrictMode( 4939): 	at com.google.android.libraries.stitch.incompat.missinglibs.a.a(PG:31)
D/StrictMode( 4939): 	at com.google.android.libraries.stitch.incompat.b.a(PG:116)
D/StrictMode( 4939): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:510)
D/StrictMode( 4939): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4939): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4939): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4939): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4939): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4939): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4939): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4939): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4939): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4939): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4939): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4939): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 4939): StrictMode policy violation; ~duration=628 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4939): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4939): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 4939): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 4939): 	at java.io.File.exists(File.java:363)
D/StrictMode( 4939): 	at com.google.android.libraries.stitch.incompat.b.a(PG:116)
D/StrictMode( 4939): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:510)
D/StrictMode( 4939): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4939): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4939): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4939): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4939): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4939): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4939): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4939): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4939): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4939): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4939): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4939): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 4939): StrictMode policy violation; ~duration=626 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4939): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4939): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 4939): 	at libcore.io.IoUtils,.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 4939): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 4939): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 4939): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 4939): 	at java.lang.System.loadLibrary(System.java:988)
D/StrictMode( 4939): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:182)
D/StrictMode( 4939): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:81)
D/StrictMode( 4939): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:524)
D/StrictMode( 4939): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4939): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4939): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4939): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4939): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4939): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4939): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4939): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4939): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4939): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4939): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4939): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 4939): StrictMode policy violation; ~duration=580 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4939): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4939): 	at android.app.SharedPreferencesImpl.awaitLoadedLocked(SharedPreferencesImpl.java:202)
D/StrictMode( 4939): 	at android.app.SharedPreferencesImpl.getBoolean(SharedPreferencesImpl.java:259)
D/StrictMode( 4939): 	at android.preference.PreferenceManager.setDefaultValues(PreferenceManager.java:481)
D/StrictMode( 4939): 	at com.google.android.apps.gmm.shared.b.a.a(PG:938)
D/StrictMode( 4939): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 4939): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4939): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4939): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4939): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4939): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4939): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4939): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4939): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4939): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4939): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4939): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4939): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 4939): StrictMode policy violation; ~duration=570 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4939): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4939): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 4939): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 4939): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 4939): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 4939): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 4939): 	at java.lang.System.loadLibrary(System.java:988)
D/StrictMode( 4939): 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:42)
D/StrictMode( 4939): 	at com.google.android.apps.gmm.map.n.f.<clinit>(PG:80)
D/StrictMode( 4939): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 4939): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4939): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4939): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4939): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4939): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4939): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4939): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4939): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4939): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4939): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4939): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4939): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 4939): StrictMode policy violation; ~duration=481 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=287 violation=2
D/StrictMode( 4939): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4939): 	at android.database.sqlite.SQLiteConnection.applyBlockGuardPolicy(SQLiteConnection.java:1041)
D/StrictMode( 4939): 	at android.database.sqlite.SQLiteConnection.executeForCursorWindow(SQLiteConnection.java:842)
D/StrictMode( 4939): 	at android.database.sqlite.SQLiteSession.executeForCursorWindow(SQLiteSession.java:836)
D/StrictMode( 4939): 	at android.database.sqlite.SQLiteQuery.fillWindow(SQLiteQuery.java:62)
D/StrictMode( 4939): 	at android.database.sqlite.SQLiteCursor.fillWindow(SQLiteCursor.java:144)
D/StrictMode( 4939): 	at android.database.sqlite.SQLiteCursor.getCount(SQLiteCursor.java:133)
D/StrictMode( 4939): 	at android.database.CursorToBulkCursorAdaptor.getBulkCursorDescriptor(CursorToBulkCursorAdaptor.java:145)
D/StrictMode( 4939): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:122)
D/StrictMode( 4939): 	at android.os.Binder.execTransact(Binder.java:446)
D/StrictMode( 4939): # via Binder call with stack:
D/StrictMode( 4939): android.os.StrictMode$LogStackTrace
D/StrictMode( 4939): 	at android.os.StrictMode.readAndHandleBinderCallViolations(StrictMode.java:1717)
D/StrictMode( 4939): 	at android.os.Parcel.readExceptionCode(Parcel.java:1527)
D/StrictMode( 4939): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:134)
D/StrictMode( 4939): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:421)
D/StrictMode( 4939): 	at android.content.ContentResolver.query(ContentResolver.java:478)
D/StrictMode( 4939): 	at android.content.ContentResolver.query(ContentResolver.java:422)
D/StrictMode( 4939): 	at com.google.android.c.c.a(PG:87)
D/StrictMode( 4939): 	at com.google.android.c.c.a(PG:107)
D/StrictMode( 4939): 	at com.google.android.apps.gmm.shared.net.s.a(PG:325)
D/StrictMode( 4939): 	at com.google.android.apps.gmm.shared.net.s.a(PG:175)
D/StrictMode( 4939): 	at com.google.android.apps.gmm.map.n.o.a(PG:134)
D/StrictMode( 4939): 	at com.google.b.a.by.a(PG:125)
D/StrictMode( 4939): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 4939): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 4939): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4939): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4939): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4939): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4939): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4939): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4939): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4939): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4939): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4939): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4939): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4939): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 4939): StrictMode policy violation; ~duration=64 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4939): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4939): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 4939): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 4939): 	at java.io.File.exists(File.java:363)
D/StrictMode( 4939): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:995)
D/StrictMode( 4939): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1018)
D/StrictMode( 4939): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:960)
D/StrictMode( 4939): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 4939): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 4939): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 4939): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 4939): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 4939): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4939): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4939): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4939): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4939): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4939): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4939): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4939): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4939): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4939): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4939): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4939): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 4939): StrictMode policy violation; ~duration=63 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4939): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4939): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 4939): 	at libcore.io.IoBridge.open(IoBridge.java:442)
D/StrictMode( 4939): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 4939): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:961)
D/StrictMode( 4939): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 4939): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 4939): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 4939): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 4939): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 4939): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4939): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4939): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4939): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4939): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4939): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4939): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4939): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4939): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4939): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4939): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4939): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 4939): StrictMode policy violation; ~duration=63 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4939): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4939): 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
D/StrictMode( 4939): 	at libcore.io.IoBridge.open(IoBridge.java:445)
D/StrictMode( 4939): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 4939): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:961)
D/StrictMode( 4939): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 4939): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 4939): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 4939): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 4939): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 4939): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4939): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4939): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4939): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4939): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4939): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4939): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4939): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4939): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4939): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4939): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4939): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 4939): StrictMode policy violation; ~duration=62 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4939): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4939): 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
D/StrictMode( 4939): 	at libcore.io.IoBridge.read(IoBridge.java:472)
D/StrictMode( 4939): 	at java.io.FileInputStream.read(FileInputStream.java:177)
D/StrictMode( 4939): 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
D/StrictMode( 4939): 	at java.io.DataInputStream.read(DataInputStream.java:63)
D/StrictMode( 4939): 	at com.google.p.j.c(PG:1152)
D/StrictMode( 4939): 	at com.google.p.j.a(PG:121)
D/StrictMode( 4939): 	at com.google.t.b.a.dr.<init>(PG:24)
D/StrictMode( 4939): 	at com.google.t.b.a.ds.a(PG:61)
D/StrictMode( 4939): 	at com.google.p.e.a(PG:170)
D/StrictMode( 4939): 	at com.google.p.e.b(PG:21)
D/StrictMode( 4939): 	at com.google.android.apps.gmm.shared.c.h.a(PG:150)
D/StrictMode( 4939): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 4939): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 4939): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 4939): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4939): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4939): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4939): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4939): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4939): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4939): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4939): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4939): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4939): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4939): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4939): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
W/ActivityThread( 4939): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/LocationOracleImpl( 1523): Best location was null
I/HotwordRecognitionRnr( 1523): Starting hotword detection.
W/com.google.a.a.a.b.a( 4939): Application name is not set. Call Builder#setApplicationName.
,I/MicrophoneInputStream( 1523): mic_starting com.google.android.apps.gsa.speech.audio.u@11f646ae
I/AudioFlinger(  358): AudioFlinger's thread 0xb4cd0000 ready to run
I/SoundTriggerHwService::Module(  358): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/MicrophoneInputStream( 1523): mic_started com.google.android.apps.gsa.speech.audio.u@11f646ae
I/art     ( 1309): Explicit concurrent mark sweep GC freed 5687(418KB) AllocSpace objects, 12(1408KB) LOS objects, 31% free, 35MB/51MB, paused 1.429ms total 40.277ms
D/audio_hw_primary(  358): select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
D/msm8974_platform(  358): platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
E/ACDB-LOADER(  358): Error: ACDB AudProc vol returned = -19
D/audio_hw_primary(  358): enable_snd_device: snd_device(55: voice-rec-mic)
D/audio_hw_primary(  358): enable_audio_route: apply and update mixer path: audio-record
D/Launcher.Workspace( 1309): 11683562 - stripEmptyScreens()
D/Launcher.Workspace( 1309): 11683562 - stripEmptyScreens()
,D/BluetoothManagerService(  820): Message: 20
,D/BluetoothManagerService(  820): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@29b3b31f:true
,D/AuthorizationBluetoothService( 1492): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
W/LocationOracleImpl( 1523): Best location was null
,D/BuaReceiver( 3597): ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,I/art     (  820): Explicit concurrent mark sweep GC freed 11763(607KB) AllocSpace objects, 2(220KB) LOS objects, 31% free, 34MB/50MB, paused 3.200ms total 194.031ms
,I/ActivityManager(  820): Start proc 5006:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,W/LocationOracleImpl( 1523): Best location was null
,I/HotwordWorker( 1523): onReady
,D/WifiService(  820): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@31bb5b6e}
,I/art     ( 4935): System.exit called, status: 0
I/AndroidRuntime( 4935): VM exiting with result code 0.
,D/AsyncChannel(  820): TODO: handle replyToMessage RemoteExceptionandroid.os.DeadObjectException
W/System.err(  820): android.os.DeadObjectException
W/System.err(  820): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err(  820): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err(  820): 	at android.os.IMessenger$Stub$Proxy.send(IMessenger.java:89)
W/System.err(  820): 	at android.os.Messenger.send(Messenger.java:57)
W/System.err(  820): 	at com.android.internal.util.AsyncChannel.replyToMessage(AsyncChannel.java:568)
W/System.err(  820): 	at com.android.server.wifi.p2p.WifiP2pServiceImpl$P2pStateMachine.replyToMessage(WifiP2pServiceImpl.java:2815)
W/System.err(  820): 	at com.android.server.wifi.p2p.WifiP2pServiceImpl$P2pStateMachine.access$3500(WifiP2pServiceImpl.java:477)
W/System.err(  820): 	at com.android.server.wifi.p2p.WifiP2pServiceImpl$P2pStateMachine$P2pEnabledState.processMessage(WifiP2pServiceImpl.java:1116)
W/System.err(  820): 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:967)
W/System.err(  820): 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:790)
W/System.err(  820): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  820): 	at android.os.Looper.loop(Looper.java:135)
W/System.err(  820): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/native  (  820): do suspend true
,D/VoicemailCleanupService( 5006): Cleaning up data for package: com.test.thalitest
,I/wpa_supplicant( 4733): P2P-FIND-STOPPED 
,I/wpa_supplicant( 4733): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant( 4733): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 4733): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:ff:f0
I/wpa_supplicant( 4733): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 4733): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
I/wpa_supplicant( 4733): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
I/wpa_supplicant( 4733): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
D/AsyncChannel(  820): TODO: handle replyToMessage RemoteExceptionandroid.os.DeadObjectException
W/System.err(  820): android.os.DeadObjectException
W/System.err(  820): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err(  820): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err(  820): 	at android.os.IMessenger$Stub$Proxy.send(IMessenger.java:89)
W/System.err(  820): 	at android.os.Messenger.send(Messenger.java:57)
W/System.err(  820): 	at com.android.internal.util.AsyncChannel.replyToMessage(AsyncChannel.java:568)
W/System.err(  820): 	at com.android.server.wifi.p2p.WifiP2pServiceImpl$P2pStateMachine.replyToMessage(WifiP2pServiceImpl.java:2815)
W/System.err(  820): 	at com.android.server.wifi.p2p.WifiP2pServiceImpl$P2pStateMachine.access$3500(WifiP2pServiceImpl.java:477)
W/System.err(  820): 	at com.android.server.wifi.p2p.WifiP2pServiceImpl$P2pStateMachine$InactiveState.processMessage(WifiP2pServiceImpl.java:1244)
W/System.err(  820): 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:967)
W/System.err(  820): 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:790)
W/System.err(  820): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  820): 	at android.os.Looper.loop(Looper.java:135)
W/System.err(  820): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/CommandListener(  354): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1492): Read error: ssl=0xaec58a00: I/O error during system call, Connection timed out
V/NativeCrypto( 1492): SSL shutdown failed: ssl=0xaec58a00: I/O error during system call, Broken pipe
,D/ConnectivityService(  820): reportBadNetwork(NetworkAgentInfo [WIFI () - 103]) by 10011
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 103](  820): ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 103](  820): DefaultState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 103](  820): Forcing reevaluation
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 103](  820): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 103](  820): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 103](  820): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
,D/ConnectivityService(  820): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
E/LocSvc_IzatApiV02(  820): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1703691539
E/LocSvc_IzatApiV02(  820): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,I/ActivityManager(  820): Start proc 5032:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,D/ConnectivityService(  820): NetworkAgentInfo [WIFI () - 103] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  820): NetworkAgentInfo [WIFI () - 103] got DISCONNECTED, was satisfying 2
,E/WifiStateMachine(  820): scanCount==0 - aborting
,D/WifiScanningService(  820): SCAN_AVAILABLE : 1
D/RttService(  820): SCAN_AVAILABLE : 1
D/RttService(  820): EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService(  820): StartedState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService(  820): DefaultState
,D/WifiNetworkAgent(  820): NetworkAgent: NetworkAgent channel lost
,E/native  (  820): do suspend true
,I/ContactLocale( 5006): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,E/Netd    (  354): failed to create /data/misc/net/rt_tables (Read-only file system)
D/CommandListener(  354): Clearing all IP addresses on wlan0
,I/ActivityManager(  820): Start proc 5056:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,D/ConnectivityService(  820): notifyType LOST for NetworkAgentInfo [WIFI () - 103]
E/WifiStateMachine(  820): SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
D/CSLegacyTypeTracker(  820): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 103] isDefaultNetwork=true
D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 103](  820): OfflineState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 103](  820): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 103](  820): Disconnected - quitting
D/ConnectivityManager.CallbackHandler( 1064): CM callback handler got msg 524292
,D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/Tethering(  820): MasterInitialState.processMessage what=3
D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/kickstart(  871): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
I/kickstart(  871): STATUS: Wrote to /sys/power/wake_lock
D/ConnectivityService(  820): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/SharedPreferencesImpl( 1847): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/GmsBackupTransport.backupScheduler.xml to backup file /data/data/com.google.android.gms/shared_prefs/GmsBackupTransport.backupScheduler.xml.bak
,I/NetworkMonitor( 3914): type=WIFI subType= reason=null isConnected=false
I/ActivityManager(  820): Killing 3572:com.android.defcontainer/u0a7 (adj 15): empty #17
D/Tethering(  820): MasterInitialState.processMessage what=3
,W/FileUtils( 5006): Failed to chmod(/data/data/com.android.providers.contacts/databases/profile.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,D/PhoneInterfaceManager( 1278): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1278): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
D/TelephonyManager(  820): getDataEnabled: retVal=false
,E/kickstart(  871): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2
I/kickstart(  871): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2' for writing
,I/wpa_supplicant( 4733): p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,I/wpa_supplicant( 4733): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1,
,E/GpsLocationProvider(  820): No APN found to select.
,D/PhoneInterfaceManager( 1278): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1278): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  820): getDataEnabled: retVal=false
,E/GpsLocationProvider(  820): No APN found to select.
,W/ContextImpl( 5056): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2609 
,E/SQLiteLog( 5006): (3850) statement aborts at 22: [DELETE FROM deleted_contacts WHERE contact_deleted_timestamp < ?] disk I/O error
,E/AndroidRuntime( 5006): FATAL EXCEPTION: ContactsProviderWorker
E/AndroidRuntime( 5006): Process: android.process.acore, PID: 5006
E/AndroidRuntime( 5006): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 5006): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 5006): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 5006): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 5006): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 5006): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/AndroidRuntime( 5006): 	at com.android.providers.contacts.database.DeletedContactsTableUtil.deleteOldLogs(DeletedContactsTableUtil.java:78)
E/AndroidRuntime( 5006): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1730)
E/AndroidRuntime( 5006): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1492)
E/AndroidRuntime( 5006): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5006): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 5006): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteLog( 1492): (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
D/AndroidRuntime( 1492): Shutting down VM
E/AndroidRuntime( 1492): FATAL EXCEPTION: main
E/AndroidRuntime( 1492): Process: com.google.process.gapps, PID: 1492
E/AndroidRuntime( 1492): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1492): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2616)
E/AndroidRuntime( 1492): 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
E/AndroidRuntime( 1492): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1380)
E/AndroidRuntime( 1492): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1492): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 1492): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
E/AndroidRuntime( 1492): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 1492): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 1492): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
E/AndroidRuntime( 1492): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
E/AndroidRuntime( 1492): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1492): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1492): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 1492): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1492): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1492): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/AndroidRuntime( 1492): 	at com.google.android.gms.gcm.bh.a(SourceFile:310)
E/AndroidRuntime( 1492): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:127)
E/AndroidRuntime( 1492): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:321)
E/AndroidRuntime( 1492): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2609)
E/AndroidRuntime( 1492): 	... 9 more
E/DropBoxManagerService(  820): Can't write: system_app_crash
E/DropBoxManagerService(  820): java.io.FileNotFoundException: /data/system/dropbox/drop117.tmp: open failed: EROFS (Read-only file system),
E/DropBoxManagerService(  820): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  820): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  820): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  820): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  820): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  820): 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
E/DropBoxManagerService(  820): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  820): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  820): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  820): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  820): 	... 5 more
,E/SQLiteDatabase( 5056): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 5056): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5056): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5056): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 5056): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 5056): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5056): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5056): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5056): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 5056): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 5056): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 5056): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 5056): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 5056): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5056): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 5056): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
E/SQLiteDatabase( 5056): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
E/SQLiteDatabase( 5056): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 5056): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5056): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 5056): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/AndroidRuntime( 5056): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 5056): Process: com.android.keychain, PID: 5056
E/AndroidRuntime( 5056): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5056): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5056): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 5056): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 5056): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5056): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5056): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5056): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AndroidRuntime( 5056): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AndroidRuntime( 5056): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 5056): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AndroidRuntime( 5056): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 5056): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 5056): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 5056): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
E/AndroidRuntime( 5056): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396,)
E/AndroidRuntime( 5056): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 5056): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5056): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 5056): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/OpenGLRenderer(  820): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,D/Atlas   (  820): Validating map...
,E/DropBoxManagerService(  820): Can't write: system_app_crash
E/DropBoxManagerService(  820): java.io.FileNotFoundException: /data/system/dropbox/drop120.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  820): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  820): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  820): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  820): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  820): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  820): 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
E/DropBoxManagerService(  820): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  820): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  820): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  820): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  820): 	... 5 more
E/DropBoxManagerService(  820): Can't write: system_app_crash
E/DropBoxManagerService(  820): java.io.FileNotFoundException: /data/system/dropbox/drop119.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  820): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  820): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  820): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  820): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  820): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  820): 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
E/DropBoxManagerService(  820): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  820): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  820): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  820): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  820): 	... 5 more
,I/OpenGLRenderer(  820): Initialized EGL, version 1.4
,D/OpenGLRenderer(  820): Enabling debug mode 0
,I/wpa_supplicant( 4733): wlan0: CTRL-EVENT-TERMINATING 
D/Tethering(  820): InitialState.processMessage what=4
E/WifiMonitor(  820): killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,D/Tethering(  820): sendTetherStateChangedBroadcast 0, 0, 0,
E/wpa_supplicant( 4733): random: Could not open entropy file /data/misc/wifi/entropy.bin for writing
,I/HotwordDetector( 1523): Closing mic
I/MicrophoneInputStream( 1523): mic_close com.google.android.apps.gsa.speech.audio.u@11f646ae
,D/audio_hw_primary(  358): disable_audio_route: reset and update mixer path: audio-record
,D/audio_hw_primary(  358): disable_snd_device: snd_device(55: voice-rec-mic)
,I/ActivityManager(  820): Killing 3446:com.android.vending/u0a19 (adj 15): empty #17
,I/SoundTriggerHwService::Module(  358): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,I/HotwordRecognitionRnr( 1523): Stopping hotword detection.
I/HotwordRecognitionRnr( 1523): Hotword detection finished
,I/ActivityManager(  820): Killing 3369:com.google.android.gms.wearable/u0a11 (adj 15): empty #18
,E/native  ( 1212): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1212): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,E/native  ( 1212): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1212): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,E/native  ( 1212): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1212): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1212): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1212): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
,E/kickstart(  871): ERROR: function: rx_data:267 Timeout Occured, No response or command came from the target!
,I/kickstart(  871): WARNING: function: sahara_start:892 Retrying memory read request
,E/kickstart(  871): ERROR: function: rx_data:267 Timeout Occured, No response or command came from the target!
,I/kickstart(  871): WARNING: function: sahara_start:892 Retrying memory read request
,E/kickstart(  871): ERROR: function: rx_data:267 Timeout Occured, No response or command came from the target!
,I/kickstart(  871): WARNING: function: sahara_start:892 Retrying memory read request
,E/kickstart(  871): ERROR: function: rx_data:267 Timeout Occured, No response or command came from the target!
I/kickstart(  871): WARNING: function: sahara_start:892 Retrying memory read request
,E/Search.SharedPreferencesProto( 1523): Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
,E/kickstart(  871): ERROR: function: rx_data:267 Timeout Occured, No response or command came from the target!
E/kickstart(  871): ERROR: function: sahara_main:1143 Sahara protocol error
,E/kickstart(  871): ERROR: function: main:268 Uploading  Image using Sahara protocol failed
I/kickstart(  871): STATUS: Wrote to /sys/power/wake_unlock
,E/QMI_FW  (  820): xport_send: Sendto failed for port 3840
,E/LocSvc_api_v02(  820): E/locClientSendReq:2446]: send_msg_sync error: -1
E/LocSvc_IzatApiV02(  820): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 11, ind.status = -1703691539
E/LocSvc_IzatApiV02(  820): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching ,
,I/qdhwcomposer(  260): handle_blank_event: dpy:0 panel power state: 0

```
