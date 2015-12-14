#### Test 50650278ec2c976_thali05_motorola-Nexus 6 Logs


```
--------- beginning of main
V/GLSActivity( 1240): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1240): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1240): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1240): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1240): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1240): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 3445): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3445): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3445): [1] 5.onFinished: Scheduling replication attempt 3.
D/AndroidRuntime( 3793): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 3793): CheckJNI is OFF
D/AndroidRuntime( 3793): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  822): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/WindowManager(  822): addAppToken: AppWindowToken{3ec63c92 token=Token{3bc9921d ActivityRecord{2913eaf4 u0 com.test.thalitest/.MainActivity t26}}} to stack=1 task=26 at 0
D/AndroidRuntime( 3793): Shutting down VM
V/WindowManager(  822): Adding window Window{21c215bf u0 Starting com.test.thalitest} at 2 of 7 (after Window{3e313103 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
I/HotwordDetector( 1524): Closing mic
I/MicrophoneInputStream( 1524): mic_close com.google.android.apps.gsa.speech.audio.u@223bdc4
I/ActivityManager(  822): Start proc 3807:com.test.thalitest/u0a265 for activity com.test.thalitest/.MainActivity
D/audio_hw_primary(  358): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  358): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  358): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1524): Hotword detection finished
I/HotwordRecognitionRnr( 1524): Stopping hotword detection.
I/ActivityManager(  822): Killing 3025:com.google.android.music:main/u0a66 (adj 15): empty #17
,I/ActivityManager(  822): Killing 3223:com.google.android.apps.photos/u0a71 (adj 15): empty #18
,I/WebViewFactory( 3807): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3807): Time to load native libraries: 2 ms (timestamps 267-269)
I/LibraryLoader( 3807): Expected native library version number "",actual native library version number ""
,E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1660933395
E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,V/WebViewChromiumFactoryProvider( 3807): Binding Chromium to main looper Looper (main, tid 1) {1da15a6f}
,I/LibraryLoader( 3807): Expected native library version number "",actual native library version number ""
I/chromium( 3807): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3807): Initializing chromium process, singleProcess=true,
W/art     ( 3807): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3807): ApplicationContext is null in ApplicationStatus
,W/chromium( 3807): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3807): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3807): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3807): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,I/kickstart(  872): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
,I/kickstart(  872): STATUS: Wrote to /sys/power/wake_lock
,E/kickstart(  872): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1
I/kickstart(  872): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1' for writing
,D/BluetoothManagerService(  822): Message: 20
D/BluetoothManagerService(  822): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1f1ecaf:true
,W/art     ( 3807): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3807): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3807): CordovaWebView is running on device made by: motorola
,W/art     ( 3807): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 3807): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3807): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,D/Atlas   ( 3807): Validating map...,
,V/WindowManager(  822): Adding window Window{2dfd5f9f u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{21c215bf u0 Starting com.test.thalitest})
,W/chromium( 3807): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3807): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3807): Enabling debug mode 0
,I/ActivityManager(  822): Displayed com.test.thalitest/.MainActivity: +992ms
,I/Keyboard.Facilitator( 1257): onFinishInput()
,W/BindingManager( 3807): Cannot call determinedVisibility() - never saw a connection for the pid: 3807
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=3.52 targetRoamBSSID=any RSSI=-51
,E/WifiStateMachine(  822): WifiStateMachine starting scan for "NG7005g"WPA_PSK with 2412,5220
,D/JsMessageQueue( 3807): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3807): JniHelper::setJavaVM(0xb489d200), pthread_self() = -1576260224
,D/JX-Cordova( 3807): jxcore cordova android initializing
,I/kickstart(  872): STATUS: Received file 'm9kefs1'
I/kickstart(  872): STATUS: 950272 bytes transferred in 0.998752 seconds
I/kickstart(  872): STATUS: Successfully downloaded files from target 
,I/kickstart(  872): STATUS: Wrote to /sys/power/wake_unlock
,I/kickstart(  872): STATUS: Sahara protocol completed
,W/jxcore-log( 3807): Initializing JXcore engine
W/jxcore-log( 3807): JXcore engine is ready
,W/jxcore-log( 3807): Starting JXcore engine,
,W/.test.thalitest( 3807): type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[11430]" dev="sockfs" ino=11430 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 3807): type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0,
W/.test.thalitest( 3807): type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[13126]" dev="sockfs" ino=13126 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 3807): type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[22469]" dev="sockfs" ino=22469 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 3807): Platform android
W/jxcore-log( 3807): 
W/jxcore-log( 3807): Process ARCH arm
W/jxcore-log( 3807): 
,I/jxcore-log( 3807): JXcore Cordova bridge is ready!
I/jxcore-log( 3807): 
W/jxcore-log( 3807): JXcore engine is started
I/Choreographer( 3807): Skipped 127 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3807): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3807): Toggling radios to true
I/jxcore-log( 3807): 
,D/BluetoothAdapter( 3807): enable(): BT is already enabled..!
,D/WifiService(  822): setWifiEnabled: true pid=3807, uid=10265,
E/WifiService(  822): Invoking mWifiStateMachine.setWifiEnabled
D/WifiService(  822): New client listening to asynchronous messages
,I/jxcore-log( 3807): Radios toggled
I/jxcore-log( 3807): ,
,D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/jxcore-log( 3807): Got Device Bluetooth address: F8:CF:C5:D9:E5:61
I/jxcore-log( 3807): 
,I/wpa_supplicant( 1150): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
E/WifiStateMachine(  822): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  822): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  354): Clearing all IP addresses on wlan0
I/jxcore-log( 3807): Perf Test app loaded loaded
,I/jxcore-log( 3807): 
,I/Choreographer( 3807): Skipped 62 frames!  The application may be doing too much work on its main thread.
V/NativeCrypto( 1240): Read error: ssl=0xaec39000: I/O error during system call, Connection timed out,
D/ConnectivityService(  822): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  822): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2,
V/NativeCrypto( 1240): SSL shutdown failed: ssl=0xaec39000: I/O error during system call, Broken pipe
E/WifiStateMachine(  822): Start Disconnecting Watchdog 1
E/WifiStateMachine(  822): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,I/jxcore-log( 3807): check test folder,
I/jxcore-log( 3807): 
I/jxcore-log( 3807): found test : ./testFindPeers.js
I/jxcore-log( 3807): 
,D/ConnectivityService(  822): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10011,
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): DefaultState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler },
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): Forcing reevaluation
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
,I/jxcore-log( 3807): found test : ./testSendData.js
I/jxcore-log( 3807): 
,I/ActivityManager(  822): Start proc 3870:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
,D/CommandListener(  354): Clearing all IP addresses on wlan0
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
,D/ConnectivityService(  822): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/WifiNetworkAgent(  822): NetworkAgent: NetworkAgent channel lost
D/CSLegacyTypeTracker(  822): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 1071): CM callback handler got msg 524292
E/WifiStateMachine(  822): CMD_AUTO_CONNECT sup state CompletedState my state DisconnectedState nid=0 roam=3
E/WifiStateMachine(  822): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=0
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): OfflineState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): Disconnected - quitting
D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  822): MasterInitialState.processMessage what=3
,D/ConnectivityService(  822): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/ConnectivityService(  822): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/ConnectivityService(  822): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
,D/Tethering(  822): MasterInitialState.processMessage what=3
,W/ResourcesManager( 3870): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/PhoneInterfaceManager( 1337): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1337): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  822): getDataEnabled: retVal=false
,E/GpsLocationProvider(  822): No APN found to select.
,D/PhoneInterfaceManager( 1337): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1337): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  822): getDataEnabled: retVal=false
,E/GpsLocationProvider(  822): No APN found to select.
,E/WifiConfigStore(  822): Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiConfigStore(  822): will read network variables netId=0
,E/WifiStateMachine(  822): CMD_AUTO_CONNECT did save config ->  nid=0
,E/WifiConfigStore(  822): will read network variables netId=0
,I/wpa_supplicant( 1150): wlan0: Trying to associate with SSID 'NG7005g'
,I/chromium( 3807): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/Babel_SMS( 3870): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 3870): MmsConfig.loadMmsSettings
I/Babel_SMS( 3870): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
I/Babel_SMS( 3870): MmsConfig.loadFromDatabase
,E/Babel_SMS( 3870): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 3870): MmsConfig.loadFromResources
,E/Babel_SMS( 3870): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 3870): MmsConfig.loadMmsSettings: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,W/Settings( 3870): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 3870): startup - clean
,I/Babel   ( 3870): deleted: false for 0
,I/Babel_telephony( 3870): TeleModule.launchCompleted
,W/Telecom (  822): TelecomServiceImpl: null is not visible for the calling user
,I/Babel_telephony( 3870): TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
W/Babel   ( 3870): BAM#gBA: invalid account id: -1
W/Babel   ( 3870): BAM#gBA: invalid account id: -1
I/Babel_telephony( 3870): TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,W/Telecom (  822): TelecomServiceImpl: null is not visible for the calling user
,I/ActivityManager(  822): Start proc 3901:com.google.android.music:main/u0a66 for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver
,W/VideoCapabilities( 3870): Unrecognized profile 2130706433 for video/avc
,I/VideoCapabilities( 3870): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 3870): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 3870): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 3870): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 3870): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  822): Killing 3368:com.google.android.gm/u0a78 (adj 15): empty #17
,I/art     (  822): Explicit concurrent mark sweep GC freed 42573(2MB) AllocSpace objects, 15(334KB) LOS objects, 32% free, 33MB/49MB, paused 1.260ms total 67.494ms
,I/wpa_supplicant( 1150): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/MusicStore( 3901): Database version: 120
,I/wpa_supplicant( 1150): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1150): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=0 id_str=]
,I/vclib   ( 3870): onServiceConnected
,W/Babel   ( 3870): Attempted to change video mute state without an active call.
,D/ConnectivityService(  822): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} }
E/WifiConfigStore(  822): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  822): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  822): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  354): Setting iface cfg
,E/WifiStateMachine(  822): Start Dhcp Watchdog 2
,E/WifiStateMachine(  822):  WifiLinkLayerStats: 
E/WifiStateMachine(  822):  my bss beacon rx: 543
E/WifiStateMachine(  822):  RSSI mgmt: -51
E/WifiStateMachine(  822):  BE :  rx=211 tx=128 lost=0 retries=1
E/WifiStateMachine(  822):  BK :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  822):  VI :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  822):  VO :  rx=4 tx=0 lost=0 retries=0
E/WifiStateMachine(  822):  on_time : 13325 tx_time=222 rx_time=689 scan_time=0
,D/ConnectivityService(  822): updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,W/art     ( 1524): Suspending all threads took: 10.098ms
,W/ResourcesManager( 3901): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3901): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/native  (  822): do suspend false
,E/WifiStateMachine(  822): scanCount==0 - aborting
,V/JNIHelp ( 3901): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ProviderInstaller( 3901): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 3901): GMSCore installation verified
,I/ConfigStore( 3901): Config Database version: 1
,I/MediaRouter( 3901): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 3901): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/ActivityManager(  822): Start proc 3936:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.steen.receiver.ConnectivityChangeReceiver
,I/GHttpClientFactory( 3901): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 3901): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  822): Killing 3491:com.google.android.gms:car/u0a11 (adj 15): empty #17
,I/dhcpcd  ( 3955): version 5.5.6 starting
,I/dhcpcd  ( 3955): wlan0: rebinding lease of 192.168.1.122
,I/ActivityManager(  822): Start proc 3971:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
I/ActivityManager(  822): Killing 2416:com.google.android.calendar/u0a37 (adj 15): empty #17
,D/SprintDMReceiver( 3971): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3971): simOperator:  IMSI: null,
D/SprintDMReceiver( 3971): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1800): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1800): onCreate
,D/SystemUpdateService( 1800): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1800): active receiver: enabled
,I/SystemUpdateService( 1800): showing system update notification
,I/iu.Environment( 1800): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1800): num queued entries: 0
,I/iu.UploadsManager( 1800): num updated entries: 0
,I/iu.SyncManager( 1800): NEXT; no task
,D/ChimeraCfgMgr( 1800): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/ValidateNoPeople(  822): skipping global notification
,V/SystemUpdateService( 1800): retry (wakeup: false) in 3599937 ms
,I/ActivityManager(  822): Start proc 3991:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,D/SystemUpdateService( 1800): onDestroy
,I/Babel   ( 3870): connection state changed from UNKNOWN to DISCONNECTED
,I/ActivityManager(  822): Killing 3329:com.android.providers.calendar/u0a3 (adj 15): empty #17
,I/GAv4    ( 3991): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3991):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3991):   adb logcat -s GAv4
,W/GAv4    ( 3991): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3991): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3991): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.,
,I/dhcpcd  ( 3955): wlan0: acknowledged 192.168.1.122 from 192.168.1.1
,I/WebViewFactory( 3991): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/dhcpcd  ( 3955): wlan0: leased 192.168.1.122 for 86400 seconds
,I/LibraryLoader( 3991): Time to load native libraries: 2 ms (timestamps 6400-6402)
I/LibraryLoader( 3991): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3991): Binding Chromium to main looper Looper (main, tid 1) {19c2adc2}
,I/LibraryLoader( 3991): Expected native library version number "",actual native library version number ""
,I/chromium( 3991): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3991): Initializing chromium process, singleProcess=true
W/art     ( 3991): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3991): ApplicationContext is null in ApplicationStatus
,W/chromium( 3991): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3991): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3991): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3991): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,W/AudioManagerAndroid( 3991): Requires BLUETOOTH permission
,I/NSApplication( 3991): Starting up...
,I/ActivityManager(  822): Start proc 4060:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,I/ActivityManager(  822): Killing 1428:android.process.acore/u0a5 (adj 15): empty #17
,D/ConnectivityService(  822): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  822): Adding iface wlan0 to network 101
,E/WifiStateMachine(  822): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
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
,D/ConnectivityManager.CallbackHandler( 1071): CM callback handler got msg 524290
D/CSLegacyTypeTracker(  822): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  822): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
,I/ActivityManager(  822): Start proc 4090:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,I/ActivityManager(  822): Killing 3619:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  822): MasterInitialState.processMessage what=3
,D/PhoneInterfaceManager( 1337): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
,E/PhoneInterfaceManager( 1337): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,I/NetworkMonitor( 3901): type=WIFI subType= reason=null isConnected=true
,D/TelephonyManager(  822): getDataEnabled: retVal=false
,E/GpsLocationProvider(  822): No APN found to select.
,V/MusicLeanback( 3901): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/ActivityManager(  822): Killing 3641:com.android.musicfx/u0a18 (adj 15): empty #17
,D/SprintDMReceiver( 3971): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3971): simOperator:  IMSI: null
D/SprintDMReceiver( 3971): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1800): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1800): onCreate
,D/SystemUpdateService( 1800): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1800): active receiver: enabled
,I/SystemUpdateService( 1800): showing system update notification
,I/ValidateNoPeople(  822): skipping global notification
,I/iu.Environment( 1800): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,V/SystemUpdateService( 1800): retry (wakeup: false) in 3599937 ms
,I/iu.UploadsManager( 1800): num queued entries: 0
,I/iu.UploadsManager( 1800): num updated entries: 0
,I/iu.SyncManager( 1800): NEXT; no task
,D/ChimeraCfgMgr( 1800): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/SystemUpdateService( 1800): onDestroy
,D/ChimeraCfgMgr( 1800): Loading module com.google.android.gms.kids from APK com.google.android.gms
,V/MusicLeanback( 3901): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/GLSUser ( 1240): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1240): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1240): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1240): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/SprintDMReceiver( 3971): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,V/GLSActivity( 1240): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SprintDMHelper( 3971): simOperator:  IMSI: null
,D/SprintDMReceiver( 3971): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1800): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1800): onCreate
,D/SystemUpdateService( 1800): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1800): active receiver: enabled
,W/Kids    ( 1800): [AccountUtils] Account not ready
W/Kids    ( 1800): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 1800): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 1800): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 1800): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 1800): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 1800): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 1800): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 1800): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 1800): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 1800): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 1800): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 1800): 	at java.lang.Thread.run(Thread.java:818)
,I/SystemUpdateService( 1800): showing system update notification
,I/Babel   ( 3870): connection state changed from DISCONNECTED to CONNECTED
,D/ChimeraCfgMgr( 1800): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/ValidateNoPeople(  822): skipping global notification
,V/SystemUpdateService( 1800): retry (wakeup: false) in 3599960 ms
,D/SystemUpdateService( 1800): onDestroy
,I/GLSUser ( 1240): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1240): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1240): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1240): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1240): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Kids    ( 1800): [AccountUtils] Account not ready
W/Kids    ( 1800): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 1800): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 1800): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 1800): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 1800): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 1800): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 1800): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 1800): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 1800): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 1800): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 1800): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 1800): 	at java.lang.Thread.run(Thread.java:818)
,D/GCM     ( 1240): Connected
,D/ConnectivityService(  822): reportInetCondition: type=1 ok, revalidate
,D/ConnectivityService(  822): reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10011
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  822): EvaluatingState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
,D/ConnectivityService(  822): reportInetCondition: type=1 ok, revalidate
D/ConnectivityService(  822): reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10011
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  822): EvaluatingState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/GCM     ( 1240): Message class com.google.f.a.a.p
,D/ConnectivityService(  822): reportInetCondition: type=1 ok, revalidate
D/ConnectivityService(  822): reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10011
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  822): EvaluatingState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
,D/ConnectivityService(  822): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/jxcore-log( 3807): BLE supported!!
I/jxcore-log( 3807): 
,I/art     (  822): Explicit concurrent mark sweep GC freed 36551(1740KB) AllocSpace objects, 2(126KB) LOS objects, 32% free, 33MB/49MB, paused 1.471ms total 69.870ms
,I/MusicLeanback( 3901): Conditions not met for autocaching. okToAttempt=false
,I/MusicLeanback( 3901): Stop autocaching.
,I/art     ( 1240): Explicit concurrent mark sweep GC freed 24911(1421KB) AllocSpace objects, 3(330KB) LOS objects, 37% free, 26MB/42MB, paused 905us total 23.334ms
,D/WearableService( 3350): callingUid 10011, callindPid: 3350
,E/GmsUtils( 3901): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 3901): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  822): EvaluatingState{ when=-6ms what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  822): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  822): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 14 Dec 2015 16:10:18 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1450109418883], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1450109418868]}
,D/ConnectivityService(  822): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  822): Validated
,D/ConnectivityService(  822): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  822): rematching NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  822): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  822): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1071): CM callback handler got msg 524290
,D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,V/Herrevad( 1800): NQAS connected
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=9.22 rxSuccessRate=11.23 targetRoamBSSID=any RSSI=-50
E/WifiStateMachine(  822): WifiStateMachine L2Connected CMD_START_SCAN source -2 10, 11 -> obsolete
,V/GLSActivity( 1240): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1240): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1240): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1240): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1240): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1240): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3445): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3445): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3445): [1] 5.onFinished: Scheduling replication attempt 4.,
,I/PowerManagerService(  822): Going to sleep due to screen timeout (uid 1000)...
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=2.55 rxSuccessRate=4.31 targetRoamBSSID=any RSSI=-50
,E/WifiStateMachine(  822): WifiStateMachine L2Connected CMD_START_SCAN source -2 9, 11 -> obsolete
,I/Adreno  (  822): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/PermissionCache(  259): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (247 us)
,I/DisplayManagerService(  822): Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
D/SurfaceFlinger(  259): Set power mode=0, type=0 flinger=0xb6482000
D/qdhwcomposer(  259): hwc_setPowerMode: Setting mode 0 on display: 0
,V/ActivityManager(  822): Display changed displayId=0
,I/qdhwcomposer(  259): handle_blank_event: dpy:0 panel power state: 0
,D/qdhwcomposer(  259): hwc_setPowerMode: Done setting mode 0 on display 0
,D/SurfaceControl(  822): Excessive delay in setPowerMode(): 258ms
,I/DreamManagerService(  822): Entering dreamland.
,I/PowerManagerService(  822): Dozing...
,I/DreamController(  822): Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,D/audio_hw_primary(  358): adev_set_parameters: enter: screen_state=on
D/mot_vr_audio_hw(  358): adev_set_parameters: screen_state=on
,E/WifiStateMachine(  822): cancelDelayedScan -> 12
,E/native  (  822): do suspend false
,I/Keyboard.Facilitator( 1257): onFinishInput()
,E/WifiStateMachine(  822): cancelDelayedScan -> 14,
,E/native  (  822): do suspend true
,D/audio_hw_primary(  358): adev_set_parameters: enter: screen_state=off
,D/mot_vr_audio_hw(  358): adev_set_parameters: screen_state=off
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-50
E/WifiStateMachine(  822): WifiStateMachine L2Connected CMD_START_SCAN source -2 13, 14 -> obsolete
,V/KeepSync( 3715): Connecting to GoogleApiClient
,I/GLSUser ( 1240): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1240): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1240): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1240): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1240): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1800): Handling authorization failure
E/ClientConnectionOperation( 1800): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1800): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1800): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1800): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1800): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1800): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1800): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1800): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1800): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1800): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1800): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1800): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1800): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1800): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1800): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1800): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1800): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1800): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1800): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1800): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1800): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1800): 	... 7 more
,V/KeepSync( 3715): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3715): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3715): (284) automatic index on blob_node(is_deleted),
E/SQLiteLog( 3715): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1240): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1240): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1240): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1240): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1240): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/KeepSync( 3715): IOException
E/KeepSync( 3715): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3715): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3715): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3715): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3715): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3715): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3715): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3715): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3715): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3715): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3715): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3715): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3715): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3715): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3715): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3715): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3715): 	... 10 more
W/KeepSync( 3715): Sync result 2
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 162890, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1240): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1240): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1240): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1240): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1240): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3197): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3197): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3197): 	at jdm.a(PG:82)
E/HttpOperation( 3197): 	at jcs.o(PG:406)
E/HttpOperation( 3197): 	at jcn.a(PG:1379)
E/HttpOperation( 3197): 	at jcs.i(PG:143)
E/HttpOperation( 3197): 	at blb.a(PG:3937)
E/HttpOperation( 3197): 	at czp.a(PG:18188)
E/HttpOperation( 3197): 	at czp.a(PG:9081)
E/HttpOperation( 3197): 	at czq.run(PG:1686)
E/HttpOperation( 3197): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3197): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3197): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3197): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3197): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3197): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3197): 	at jdj.a(PG:4091)
E/HttpOperation( 3197): 	at jdj.a(PG:1125)
E/HttpOperation( 3197): 	at jdm.a(PG:77)
E/HttpOperation( 3197): 	... 12 more
E/HttpOperation( 3197): Caused by: faj: BadAuthentication
E/HttpOperation( 3197): 	at fal.a(PG:38)
E/HttpOperation( 3197): 	at jdj.a(PG:4089)
E/HttpOperation( 3197): 	... 14 more
,I/GLSUser ( 1240): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1240): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1240): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1240): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1240): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3197): [getmobileexperiments] Unexpected exception,
E/HttpOperation( 3197): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3197): 	at jdm.a(PG:82)
E/HttpOperation( 3197): 	at jcs.o(PG:406)
E/HttpOperation( 3197): 	,at jcn.a(PG:1379)
E/HttpOperation( 3197): 	at jcs.i(PG:143)
E/HttpOperation( 3197): 	at hec.a(PG:42)
E/HttpOperation( 3197): 	at hee.a(PG:102)
E/HttpOperation( 3197): 	at czr.a(PG:65)
E/HttpOperation( 3197): 	at kka.a(PG:108)
E/HttpOperation( 3197): 	at czp.a(PG:19176)
E/HttpOperation( 3197): 	at czp.a(PG:9081)
E/HttpOperation( 3197): 	at czq.run(PG:1686)
E/HttpOperation( 3197): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3197): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3197): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3197): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3197): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3197): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3197): 	at jdj.a(PG:4091)
E/HttpOperation( 3197): 	at jdj.a(PG:1125)
E/HttpOperation( 3197): 	at jdm.a(PG:77)
E/HttpOperation( 3197): 	... 15 more
E/HttpOperation( 3197): Caused by: faj: BadAuthentication
E/HttpOperation( 3197): 	at fal.a(PG:38)
E/HttpOperation( 3197): ,	at jdj.a(PG:4089)
E/HttpOperation( 3197): 	... 17 more
E/ExperimentLoader( 3197): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3197): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3197): 	at jdm.a(PG:82)
E/ExperimentLoader( 3197): 	at jcs.o(PG:406)
E/ExperimentLoader( 3197): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3197): 	at jcs.i(PG:143)
E/ExperimentLoader( 3197): 	at hec.a(PG:42)
E/ExperimentLoader( 3197): 	at hee.a(PG:102),
E/ExperimentLoader( 3197): 	at czr.a(PG:65)
E/ExperimentLoader( 3197): 	at kka.a(PG:108)
E/ExperimentLoader( 3197): 	at czp.a(PG:19176)
E/ExperimentLoader( 3197): 	at czp.a(PG:9081)
E/ExperimentLoader( 3197): 	at czq.run(PG:1686)
E/ExperimentLoader( 3197): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3197): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3197): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3197): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3197): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3197): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3197): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3197): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3197): 	at jdm.a(PG:77)
E/ExperimentLoader( 3197): 	... 15 more
E/ExperimentLoader( 3197): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3197): 	at fal.a(PG:38)
E/ExperimentLoader( 3197): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3197): 	... 17 more
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 163380, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-50
E/WifiStateMachine(  822): WifiStateMachine L2Connected CMD_START_SCAN source -2 11, 14 -> obsolete
,V/GLSActivity( 1240): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GoogleAuthProtoRequest( 3936): [425] a.<init>: mAccountName set to: thalitester@gmail.com
,I/VacuumService( 1240): Vacuum at: now=1450109447217 tag=VacuumService
,I/GLSUser ( 1240): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1240): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1240): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1240): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1240): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GoogleURLConnFactory( 1240): Using platform SSLCertificateSocketFactory
,W/ExperimentUpdateService( 3936): [425] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3936): [425] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3936): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3936): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3936): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3936): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3936): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3936): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3936): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3936): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3936): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3936): 	at com.a.a.k.run(SourceFile:110)
,I/GLSUser ( 1240): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1240): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1240): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1240): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1240): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  822): Explicit concurrent mark sweep GC freed 35740(1621KB) AllocSpace objects, 4(252KB) LOS objects, 32% free, 33MB/49MB, paused 1.337ms total 53.825ms
,V/GLSActivity( 1240): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1240): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1240): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1240): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1240): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1240): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3445): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3445): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3445): [1] 5.onFinished: Scheduling replication attempt 5.
E/Uploader( 1240): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1240): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1240): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1240): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1240): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1240): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1240): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1240): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1240): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1240): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1240): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1240): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1240): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1240): No account for auth token provided
,W/Uploader( 1240): No account for auth token provided,
,I/GLSUser ( 1240): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1240): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1240): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1240): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1240): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/Uploader( 1240): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1240): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1240): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1240): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1240): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1240): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1240): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1240): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1240): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1240): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1240): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1240): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1240): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1240): No account for auth token provided
,W/Uploader( 1240): No account for auth token provided,
,W/Uploader( 1240): No account for auth token provided
,I/GLSUser ( 1240): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1240): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1240): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1240): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1240): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1240): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1240): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1240): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1240): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1240): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1240): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1240): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1240): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1240): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1240): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1240): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1240): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1240): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1240): No account for auth token provided
,W/Uploader( 1240): No account for auth token provided
,W/Uploader( 1240): No account for auth token provided
,W/Uploader( 1240): No account for auth token provided
,W/Uploader( 1240): No account for auth token provided
,W/Uploader( 1240): No account for auth token provided
,W/Uploader( 1240):  no longer exists, so no auth token.,
,I/GLSUser ( 1240): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1240): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1240): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1240): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1240): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1240): Failed to get auth token: User intervention required. Notification has been pushed.
,E/Uploader( 1240): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1240): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1240): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1240): 	at com.google.android.gms.auth.p.c(SourceFile:550)
,E/Uploader( 1240): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1240): 	,at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1240): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1240): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1240): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
,E/Uploader( 1240): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1240): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1240): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/GLSUser ( 1240): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1240): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1240): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1240): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1240): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1240): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1240): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.,
E/Uploader( 1240): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1240): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1240): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1240): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1240): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1240): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1240): 	,at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1240): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1240): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1240): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1240): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,D/HeadsetStateMachine( 2136): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2136): Disconnected process message: 10, size: 0
,I/BooksSync( 3746): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3746): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1240): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1240): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1240): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1240): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1240): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1240): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1240): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1240): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1240): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1240): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3746): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3746): Soft error
E/BooksSync( 3746): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3746): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3746): Sync error
E/BooksSync( 3746): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3746): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3746): Finished books sync
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 167006, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1],
,V/GoogleAuthProtoRequest( 3936): [426] a.<init>: mAccountName set to: thalitester@gmail.com
,I/art     ( 1240): Explicit concurrent mark sweep GC freed 62829(3MB) AllocSpace objects, 9(910KB) LOS objects, 36% free, 27MB/43MB, paused 1.110ms total 33.717ms
,I/GLSUser ( 1240): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1240): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1240): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1240): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1240): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3936): [426] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3936): [426] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3936): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3936): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3936): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3936): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3936): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3936): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3936): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3936): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3936): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3936): 	at com.a.a.k.run(SourceFile:110)
,V/GLSActivity( 1240): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1240): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1240): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1240): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1240): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1240): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3445): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3445): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3445): [1] 5.onFinished: Giving up after 6 failures.
,I/Keyboard.Facilitator.LanguageModelFlusher( 1257): run()
I/Keyboard.Facilitator( 1257): flushDynamicLanguageModels()
,I/ConfigService( 1240): onCreate
,V/KeepSync( 3715): Connecting to GoogleApiClient
,I/GLSUser ( 1240): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1240): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1240): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1240): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1240): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1240): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1240): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1240): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1240): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1240): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/HttpOperation( 3197): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3197): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3197): 	at jdm.a(PG:82)
E/HttpOperation( 3197): 	at jcs.o(PG:406)
E/HttpOperation( 3197): 	at jcn.a(PG:1379),
E/HttpOperation( 3197): 	at jcs.i(PG:143)
E/HttpOperation( 3197): 	at blb.a(PG:3937)
E/HttpOperation( 3197): 	at czp.a(PG:18188)
E/HttpOperation( 3197): 	at czp.a(PG:9081)
E/HttpOperation( 3197): 	at czq.run(PG:1686)
E/HttpOperation( 3197): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3197): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
,E/HttpOperation( 3197): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3197): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3197): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3197): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3197): 	at jdj.a(PG:4091)
E/HttpOperation( 3197): 	at jdj.a(PG:1125)
E/HttpOperation( 3197): 	,at jdm.a(PG:77)
E/HttpOperation( 3197): 	... 12 more
E/HttpOperation( 3197): Caused by: faj: BadAuthentication
E/HttpOperation( 3197): 	at fal.a(PG:38)
E/HttpOperation( 3197): 	at jdj.a(PG:4089)
E/HttpOperation( 3197): 	... 14 more
,E/ClientConnectionOperation( 1800): Handling authorization failure
E/ClientConnectionOperation( 1800): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1800): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1800): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1800): ,	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1800): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1800): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1800): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1800): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1800): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1800): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1800): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1800): 	at com.google.android.gms.auth.p.a(SourceFile:365)
,E/ClientConnectionOperation( 1800): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1800): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1800): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1800): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1800): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1800): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1800): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1800): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1800): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1800): 	... 7 more
,V/KeepSync( 3715): GoogleApiClient failed to connect with error code: 4
E/SQLiteLog( 3715): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3715): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3715): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1240): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1240): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1240): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1240): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1240): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3197): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3197): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3197): 	at jdm.a(PG:82)
E/HttpOperation( 3197): 	at jcs.o(PG:406)
E/HttpOperation( 3197): 	at jcn.a(PG:1379)
E/HttpOperation( 3197): 	at jcs.i(PG:143)
E/HttpOperation( 3197): 	at hec.a(PG:42)
E/HttpOperation( 3197): 	at hee.a(PG:102)
E/HttpOperation( 3197): 	at czr.a(PG:65)
E/HttpOperation( 3197): 	at kka.a(PG:108)
E/HttpOperation( 3197): 	at czp.a(PG:19176)
E/HttpOperation( 3197): 	at czp.a(PG:9081)
E/HttpOperation( 3197): 	at czq.run(PG:1686)
E/HttpOperation( 3197): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3197): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3197): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3197): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3197): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3197): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3197): 	at jdj.a(PG:4091)
E/HttpOperation( 3197): 	at jdj.a(PG:1125)
E/HttpOperation( 3197): 	at jdm.a(PG:77)
E/HttpOperation( 3197): 	... 15 more
E/HttpOperation( 3197): Caused by: faj: BadAuthentication
E/HttpOperation( 3197): 	at fal.a(PG:38)
E/HttpOperation( 3197): 	at jdj.a(PG:4089)
E/HttpOperation( 3197): 	... 17 more
,E/ExperimentLoader( 3197): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3197): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3197): 	at jdm.a(PG:82)
E/ExperimentLoader( 3197): 	at jcs.o(PG:406)
E/ExperimentLoader( 3197): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3197): 	at jcs.i(PG:143)
E/ExperimentLoader( 3197): 	at hec.a(PG:42)
E/ExperimentLoader( 3197): 	at hee.a(PG:102)
E/ExperimentLoader( 3197): 	at czr.a(PG:65)
E/ExperimentLoader( 3197): 	at kka.a(PG:108)
E/ExperimentLoader( 3197): 	at czp.a(PG:19176)
E/ExperimentLoader( 3197): 	at czp.a(PG:9081)
E/ExperimentLoader( 3197): 	at czq.run(PG:1686)
,E/ExperimentLoader( 3197): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3197): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3197): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3197): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3197): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3197): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3197): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3197): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3197): 	at jdm.a(PG:77)
E/ExperimentLoader( 3197): 	... 15 more
E/ExperimentLoader( 3197): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3197): ,	at fal.a(PG:38)
E/ExperimentLoader( 3197): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3197): 	... 17 more
,I/GLSUser ( 1240): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1240): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1240): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1240): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1240): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3715): IOException
E/KeepSync( 3715): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3715): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3715): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3715): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3715): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3715): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3715): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3715): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3715): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3715): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3715): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3715): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3715): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3715): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3715): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3715): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3715): 	... 10 more
W/KeepSync( 3715): Sync result 2
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 195524, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 194009, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/ConfigService( 1240): onDestroy
,D/HeadsetStateMachine( 2136): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2136): Disconnected process message: 10, size: 0
,I/BooksSync( 3746): Starting books sync for 61035162, extras: ade
,I/art     (  822): Explicit concurrent mark sweep GC freed 31680(1375KB) AllocSpace objects, 5(174KB) LOS objects, 31% free, 34MB/50MB, paused 2.070ms total 69.350ms
,I/BooksConfig( 3746): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1240): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1240): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1240): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1240): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1240): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1240): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1240): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1240): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1240): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1240): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3746): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3746): Soft error
E/BooksSync( 3746): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3746): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3746): Sync error
E/BooksSync( 3746): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3746): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3746): Finished books sync
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 225190, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2136): Disconnected process message: 10, size: 0
,V/GoogleAuthProtoRequest( 3936): [428] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1240): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1240): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1240): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1240): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1240): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3936): [428] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3936): [428] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3936): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3936): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3936): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3936): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3936): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3936): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3936): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3936): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3936): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3936): 	at com.a.a.k.run(SourceFile:110)
,V/KeepSync( 3715): Connecting to GoogleApiClient
,I/GLSUser ( 1240): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1240): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1240): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1240): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1240): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1240): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1240): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1240): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1240): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1240): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3197): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3197): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3197): 	at jdm.a(PG:82)
E/HttpOperation( 3197): 	at jcs.o(PG:406)
E/HttpOperation( 3197): 	at jcn.a(PG:1379)
E/HttpOperation( 3197): 	at jcs.i(PG:143)
E/HttpOperation( 3197): 	at blb.a(PG:3937)
E/HttpOperation( 3197): 	at czp.a(PG:18188)
E/HttpOperation( 3197): 	at czp.a(PG:9081)
E/HttpOperation( 3197): 	at czq.run(PG:1686)
E/HttpOperation( 3197): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3197): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3197): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3197): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3197): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3197): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3197): 	at jdj.a(PG:4091)
E/HttpOperation( 3197): 	at jdj.a(PG:1125)
E/HttpOperation( 3197): 	at jdm.a(PG:77)
E/HttpOperation( 3197): 	... 12 more
E/HttpOperation( 3197): Caused by: faj: BadAuthentication
E/HttpOperation( 3197): 	at fal.a(PG:38)
E/HttpOperation( 3197): 	at jdj.a(PG:4089)
E/HttpOperation( 3197): 	... 14 more
,E/ClientConnectionOperation( 1800): Handling authorization failure
E/ClientConnectionOperation( 1800): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1800): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1800): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1800): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1800): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1800): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1800): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1800): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1800): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1800): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1800): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1800): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1800): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1800): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1800): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1800): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1800): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1800): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1800): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1800): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1800): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1800): 	... 7 more
,V/KeepSync( 3715): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3715): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3715): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3715): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1240): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1240): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1240): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1240): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1240): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3197): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3197): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3197): 	at jdm.a(PG:82)
E/HttpOperation( 3197): 	at jcs.o(PG:406)
E/HttpOperation( 3197): 	at jcn.a(PG:1379)
E/HttpOperation( 3197): 	at jcs.i(PG:143)
E/HttpOperation( 3197): 	at hec.a(PG:42)
E/HttpOperation( 3197): 	at hee.a(PG:102)
E/HttpOperation( 3197): 	at czr.a(PG:65)
E/HttpOperation( 3197): 	at kka.a(PG:108)
E/HttpOperation( 3197): 	at czp.a(PG:19176)
E/HttpOperation( 3197): 	at czp.a(PG:9081)
E/HttpOperation( 3197): 	at czq.run(PG:1686)
E/HttpOperation( 3197): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3197): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3197): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3197): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3197): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3197): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3197): 	at jdj.a(PG:4091)
E/HttpOperation( 3197): 	at jdj.a(PG:1125)
E/HttpOperation( 3197): 	at jdm.a(PG:77)
E/HttpOperation( 3197): 	... 15 more
E/HttpOperation( 3197): Caused by: faj: BadAuthentication
E/HttpOperation( 3197): 	at fal.a(PG:38)
E/HttpOperation( 3197): 	at jdj.a(PG:4089)
E/HttpOperation( 3197): 	... 17 more
,E/ExperimentLoader( 3197): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3197): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3197): 	at jdm.a(PG:82)
E/ExperimentLoader( 3197): 	at jcs.o(PG:406)
E/ExperimentLoader( 3197): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3197): 	at jcs.i(PG:143)
E/ExperimentLoader( 3197): 	at hec.a(PG:42)
E/ExperimentLoader( 3197): 	at hee.a(PG:102)
E/ExperimentLoader( 3197): 	at czr.a(PG:65),
E/ExperimentLoader( 3197): 	at kka.a(PG:108)
E/ExperimentLoader( 3197): 	at czp.a(PG:19176)
E/ExperimentLoader( 3197): 	at czp.a(PG:9081)
E/ExperimentLoader( 3197): 	at czq.run(PG:1686)
E/ExperimentLoader( 3197): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3197): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3197): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3197): 	,at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3197): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3197): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3197): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3197): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3197): 	at jdm.a(PG:77)
E/ExperimentLoader( 3197): 	... 15 more
E/ExperimentLoader( 3197): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3197): 	at fal.a(PG:38)
E/ExperimentLoader( 3197): ,	at jdj.a(PG:4089)
E/ExperimentLoader( 3197): 	... 17 more
,I/GLSUser ( 1240): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1240): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1240): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1240): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1240): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 283314, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,E/KeepSync( 3715): IOException
E/KeepSync( 3715): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3715): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3715): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3715): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3715): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3715): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3715): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3715): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3715): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3715): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3715): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3715): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3715): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3715): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3715): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3715): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3715): 	... 10 more
W/KeepSync( 3715): Sync result 2
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 287428, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]

```
