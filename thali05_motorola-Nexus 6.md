#### Test 5198634075bb434_thali05_motorola-Nexus 6 Logs


```
--------- beginning of main
V/GLSActivity( 1423): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1423): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1423): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1423): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1423): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1423): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 3470): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3470): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3470): [1] 5.onFinished: Scheduling replication attempt 3.
D/AndroidRuntime( 3819): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 3819): CheckJNI is OFF
D/AndroidRuntime( 3819): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  822): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/WindowManager(  822): addAppToken: AppWindowToken{3eb92849 token=Token{2e408e50 ActivityRecord{36633c13 u0 com.test.thalitest/.MainActivity t24}}} to stack=1 task=24 at 0
V/WindowManager(  822): Adding window Window{2c06b85a u0 Starting com.test.thalitest} at 3 of 8 (after Window{1d2f112b u0 com.android.chrome/org.chromium.chrome.browser.document.DocumentActivity})
D/AndroidRuntime( 3819): Shutting down VM
I/HotwordDetector( 1535): Closing mic
I/MicrophoneInputStream( 1535): mic_close com.google.android.apps.gsa.speech.audio.u@11d9b916
I/ActivityManager(  822): Start proc 3833:com.test.thalitest/u0a265 for activity com.test.thalitest/.MainActivity
D/audio_hw_primary(  358): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  358): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  358): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1535): Hotword detection finished
I/HotwordRecognitionRnr( 1535): Stopping hotword detection.
I/ActivityManager(  822): Killing 3091:com.google.android.music:main/u0a66 (adj 15): empty #17
,I/ActivityManager(  822): Killing 2814:com.google.android.talk/u0a61 (adj 15): empty #18
I/WebViewFactory( 3833): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3833): Time to load native libraries: 1 ms (timestamps 4087-4088)
I/LibraryLoader( 3833): Expected native library version number "",actual native library version number ""
E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1698190611
E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
V/WebViewChromiumFactoryProvider( 3833): Binding Chromium to main looper Looper (main, tid 1) {f1b009}
I/LibraryLoader( 3833): Expected native library version number "",actual native library version number ""
I/chromium( 3833): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3833): Initializing chromium process, singleProcess=true
W/art     ( 3833): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3833): ApplicationContext is null in ApplicationStatus
W/chromium( 3833): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3833): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3833): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3833): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
I/kickstart(  877): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
I/kickstart(  877): STATUS: Wrote to /sys/power/wake_lock
E/kickstart(  877): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1
I/kickstart(  877): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1' for writing
D/BluetoothManagerService(  822): Message: 20
D/BluetoothManagerService(  822): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2b2dec0a:true
W/art     ( 3833): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 3833): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 3833): CordovaWebView is running on device made by: motorola
W/art     ( 3833): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3833): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 3833): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
D/Atlas   ( 3833): Validating map...
V/WindowManager(  822): Adding window Window{18216bba u0 com.test.thalitest/com.test.thalitest.MainActivity} at 3 of 9 (before Window{2c06b85a u0 Starting com.test.thalitest})
W/chromium( 3833): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/OpenGLRenderer( 3833): Initialized EGL, version 1.4
D/OpenGLRenderer( 3833): Enabling debug mode 0
I/ActivityManager(  822): Displayed com.test.thalitest/.MainActivity: +950ms (total +1m41s549ms)
I/Keyboard.Facilitator( 1261): onFinishInput()
W/BindingManager( 3833): Cannot call determinedVisibility() - never saw a connection for the pid: 3833
,D/JsMessageQueue( 3833): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 3833): JniHelper::setJavaVM(0xb489d200), pthread_self() = -1576275456
D/JX-Cordova( 3833): jxcore cordova android initializing
I/kickstart(  877): STATUS: Received file 'm9kefs1'
I/kickstart(  877): STATUS: 950272 bytes transferred in 0.990803 seconds
I/kickstart(  877): STATUS: Successfully downloaded files from target 
I/kickstart(  877): STATUS: Wrote to /sys/power/wake_unlock
I/kickstart(  877): STATUS: Sahara protocol completed
,W/jxcore-log( 3833): Initializing JXcore engine
W/jxcore-log( 3833): JXcore engine is ready
,W/jxcore-log( 3833): Starting JXcore engine
,W/.test.thalitest( 3833): type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[12961]" dev="sockfs" ino=12961 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 3833): type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,W/.test.thalitest( 3833): type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[10876]" dev="sockfs" ino=10876 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 3833): type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[22260]" dev="sockfs" ino=22260 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 3833): Platform android
W/jxcore-log( 3833): 
W/jxcore-log( 3833): Process ARCH arm
W/jxcore-log( 3833): 
,I/jxcore-log( 3833): JXcore Cordova bridge is ready!
I/jxcore-log( 3833): 
W/jxcore-log( 3833): JXcore engine is started
,I/Choreographer( 3833): Skipped 136 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3833): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3833): Toggling radios to true
I/jxcore-log( 3833): 
,D/BluetoothAdapter( 3833): enable(): BT is already enabled..!,
,D/WifiService(  822): setWifiEnabled: true pid=3833, uid=10265
E/WifiService(  822): Invoking mWifiStateMachine.setWifiEnabled
,D/WifiService(  822): New client listening to asynchronous messages
I/jxcore-log( 3833): Radios toggled
I/jxcore-log( 3833): 
,I/wpa_supplicant( 1194): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  822): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  822): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any,
,D/CommandListener(  354): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1423): Read error: ssl=0xb4886e00: I/O error during system call, Connection timed out
,V/NativeCrypto( 1423): SSL shutdown failed: ssl=0xb4886e00: I/O error during system call, Broken pipe
,D/ConnectivityService(  822): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED,
D/ConnectivityService(  822): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,E/WifiStateMachine(  822): Start Disconnecting Watchdog 1
E/WifiStateMachine(  822): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,D/ConnectivityService(  822): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10011
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): ValidatedState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): DefaultState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): Forcing reevaluation
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
,D/CommandListener(  354): Clearing all IP addresses on wlan0
,I/ActivityManager(  822): Start proc 3894:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
,D/ConnectivityService(  822): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/CSLegacyTypeTracker(  822): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/WifiNetworkAgent(  822): NetworkAgent: NetworkAgent channel lost
D/ConnectivityService(  822): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/WifiStateMachine(  822): CMD_AUTO_CONNECT sup state CompletedState my state DisconnectedState nid=0 roam=3
E/WifiStateMachine(  822): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=0
D/ConnectivityManager.CallbackHandler( 1076): CM callback handler got msg 524292
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): OfflineState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): Disconnected - quitting
D/Tethering(  822): MasterInitialState.processMessage what=3
D/Tethering(  822): MasterInitialState.processMessage what=3
,D/ConnectivityService(  822): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
,D/NetworkChangeNotifierAutoDetect( 1535): Network connectivity changed, type is: 6
,D/PhoneInterfaceManager( 1318): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1318): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  822): getDataEnabled: retVal=false
E/WifiConfigStore(  822): Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiConfigStore(  822): will read network variables netId=0
,E/GpsLocationProvider(  822): No APN found to select.
,E/WifiStateMachine(  822): CMD_AUTO_CONNECT did save config ->  nid=0
,E/WifiConfigStore(  822): will read network variables netId=0
W/ResourcesManager( 3894): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/PhoneInterfaceManager( 1318): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
,E/PhoneInterfaceManager( 1318): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
D/TelephonyManager(  822): getDataEnabled: retVal=false
,E/GpsLocationProvider(  822): No APN found to select.
,I/Babel_SMS( 3894): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 3894): MmsConfig.loadMmsSettings
I/Babel_SMS( 3894): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
I/Babel_SMS( 3894): MmsConfig.loadFromDatabase
,E/Babel_SMS( 3894): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 3894): MmsConfig.loadFromResources
,E/Babel_SMS( 3894): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 3894): MmsConfig.loadMmsSettings: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,W/Settings( 3894): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 3894): startup - clean
,I/Babel   ( 3894): deleted: false for 0
,I/Babel_telephony( 3894): TeleModule.launchCompleted
,W/Telecom (  822): TelecomServiceImpl: null is not visible for the calling user,
,I/Babel_telephony( 3894): TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
W/Babel   ( 3894): BAM#gBA: invalid account id: -1
W/Babel   ( 3894): BAM#gBA: invalid account id: -1
,I/Babel_telephony( 3894): TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
W/Telecom (  822): TelecomServiceImpl: null is not visible for the calling user
,W/VideoCapabilities( 3894): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  822): Start proc 3923:com.google.android.music:main/u0a66 for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver
,I/VideoCapabilities( 3894): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 3894): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 3894): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 3894): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 3894): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  822): Killing 3415:com.google.android.gm/u0a78 (adj 15): empty #17
,I/MusicStore( 3923): Database version: 120
,I/vclib   ( 3894): onServiceConnected
W/Babel   ( 3894): Attempted to change video mute state without an active call.
,W/ResourcesManager( 3923): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3923): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 3923): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ProviderInstaller( 3923): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 3923): GMSCore installation verified
,I/ConfigStore( 3923): Config Database version: 1
,I/art     (  822): Explicit concurrent mark sweep GC freed 36365(1820KB) AllocSpace objects, 12(380KB) LOS objects, 32% free, 33MB/49MB, paused 1.443ms total 82.856ms
,I/MediaRouter( 3923): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
V/MusicLeanback( 3923): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/ActivityManager(  822): Start proc 3952:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.steen.receiver.ConnectivityChangeReceiver
,I/GHttpClientFactory( 3923): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 3923): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  822): Killing 3513:com.google.android.gms:car/u0a11 (adj 15): empty #17
,I/ActivityManager(  822): Start proc 3985:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,D/SprintDMReceiver( 3985): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  822): Killing 2523:com.google.android.calendar/u0a37 (adj 15): empty #17
,D/SprintDMHelper( 3985): simOperator:  IMSI: null
D/SprintDMReceiver( 3985): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1833): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1833): onCreate
,D/SystemUpdateService( 1833): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1833): active receiver: enabled
,I/SystemUpdateService( 1833): showing system update notification
,I/ValidateNoPeople(  822): skipping global notification
I/iu.Environment( 1833): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,V/SystemUpdateService( 1833): retry (wakeup: false) in 3599967 ms
,I/iu.UploadsManager( 1833): num queued entries: 0
,D/ChimeraCfgMgr( 1833): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/iu.UploadsManager( 1833): num updated entries: 0
,D/SystemUpdateService( 1833): onDestroy
,I/iu.SyncManager( 1833): NEXT; no task
,I/wpa_supplicant( 1194): wlan0: Trying to associate with SSID 'NG7005g'
,I/ActivityManager(  822): Start proc 4005:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,I/Babel   ( 3894): connection state changed from UNKNOWN to DISCONNECTED
,I/ActivityManager(  822): Killing 3376:com.android.providers.calendar/u0a3 (adj 15): empty #17
,D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/jxcore-log( 3833): Got Device Bluetooth address: F8:CF:C5:D9:E5:61
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): my name is : motorola-Nexus 6_PT2362
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): attempting to connect to test coordinator
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): check test folder
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): found test : ./testFindPeers.js
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): found test : ./testReConnect.js
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): found test : ./testSendData.js
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): Test app app.js loaded
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/Choreographer( 3833): Skipped 119 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3833): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/GAv4    ( 4005): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4005):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4005):   adb logcat -s GAv4
,W/GAv4    ( 4005): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4005): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4005): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 4005): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 4005): Time to load native libraries: 2 ms (timestamps 9363-9365)
I/LibraryLoader( 4005): Expected native library version number "",actual native library version number ""
,I/wpa_supplicant( 1194): wlan0: Associated with c0:ff:d4:d3:aa:4a
,V/WebViewChromiumFactoryProvider( 4005): Binding Chromium to main looper Looper (main, tid 1) {22a62b64}
,I/LibraryLoader( 4005): Expected native library version number "",actual native library version number ""
,I/chromium( 4005): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4005): Initializing chromium process, singleProcess=true
,W/art     ( 4005): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 4005): ApplicationContext is null in ApplicationStatus
,W/chromium( 4005): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 4005): validate_display:255 error 3008 (EGL_BAD_DISPLAY),
E/libEGL  ( 4005): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno  ( 4005): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,I/wpa_supplicant( 1194): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1194): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=0 id_str=]
,D/ConnectivityService(  822): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} },
E/WifiConfigStore(  822): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  822): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  822): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  354): Setting iface cfg
E/WifiStateMachine(  822): Start Dhcp Watchdog 2
,E/WifiStateMachine(  822):  WifiLinkLayerStats: 
E/WifiStateMachine(  822):  my bss beacon rx: 510
E/WifiStateMachine(  822):  RSSI mgmt: -47
E/WifiStateMachine(  822):  BE :  rx=214 tx=146 lost=0 retries=0
E/WifiStateMachine(  822):  BK :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  822):  VI :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  822):  VO :  rx=4 tx=0 lost=0 retries=0
E/WifiStateMachine(  822):  on_time : 15459 tx_time=273 rx_time=596 scan_time=0
,D/ConnectivityService(  822): updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,W/AudioManagerAndroid( 4005): Requires BLUETOOTH permission
,I/NSApplication( 4005): Starting up...
,I/ActivityManager(  822): Killing 1460:android.process.acore/u0a5 (adj 15): empty #17
,E/native  (  822): do suspend false
,E/WifiStateMachine(  822): scanCount==0 - aborting
,I/dhcpcd  ( 4062): version 5.5.6 starting
,I/ActivityManager(  822): Start proc 4066:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,I/dhcpcd  ( 4062): wlan0: rebinding lease of 192.168.1.110
,V/MusicLeanback( 3923): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/ActivityManager(  822): Killing 3645:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,I/dhcpcd  ( 4062): wlan0: acknowledged 192.168.1.110 from 192.168.1.1
,I/dhcpcd  ( 4062): wlan0: leased 192.168.1.110 for 86400 seconds
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,D/SprintDMReceiver( 3985): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3985): simOperator:  IMSI: null
D/SprintDMReceiver( 3985): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1833): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1833): onCreate
,D/SystemUpdateService( 1833): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1833): active receiver: enabled
,I/SystemUpdateService( 1833): showing system update notification
,I/ValidateNoPeople(  822): skipping global notification
,V/SystemUpdateService( 1833): retry (wakeup: false) in 3599977 ms
,D/ChimeraCfgMgr( 1833): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/SystemUpdateService( 1833): onDestroy
,D/ConnectivityService(  822): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  822): Adding iface wlan0 to network 101
,E/WifiStateMachine(  822): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  822): Unexpected mtu value: 0, wlan0
,D/ConnectivityService(  822): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  822): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  822): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101,
,D/ConnectivityService(  822): Setting Dns servers for network 101 to [/192.168.1.1]
,D/ConnectivityService(  822): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  822): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  822): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  822): Connected
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  822): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  822): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
,D/ConnectivityService(  822): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  822):    accepting network in place of null
,D/ConnectivityService(  822): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.110/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} }
,D/ConnectivityService(  822): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/CSLegacyTypeTracker(  822): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 1076): CM callback handler got msg 524290
D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  822): MasterInitialState.processMessage what=3
,D/PhoneInterfaceManager( 1318): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1318): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
D/TelephonyManager(  822): getDataEnabled: retVal=false
,I/NetworkMonitor( 3923): type=WIFI subType= reason=null isConnected=true
,D/NetworkChangeNotifierAutoDetect( 1535): Network connectivity changed, type is: 2
,E/GpsLocationProvider(  822): No APN found to select.
,V/MusicLeanback( 3923): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/SprintDMReceiver( 3985): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3985): simOperator:  IMSI: null
D/SprintDMReceiver( 3985): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1833): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1833): onCreate
,D/SystemUpdateService( 1833): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1833): active receiver: enabled
,I/SystemUpdateService( 1833): showing system update notification
,I/iu.Environment( 1833): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1833): num queued entries: 0
,I/iu.UploadsManager( 1833): num updated entries: 0
,I/iu.SyncManager( 1833): NEXT; no task
,I/ValidateNoPeople(  822): skipping global notification
,V/SystemUpdateService( 1833): retry (wakeup: false) in 3599977 ms
D/ChimeraCfgMgr( 1833): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 1833): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/SystemUpdateService( 1833): onDestroy
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  822): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 02 Dec 2015 13:33:13 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1449063193895], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1449063193874]}
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  822): Validated
D/ConnectivityService(  822): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/ConnectivityService(  822): Validated NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  822): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  822): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  822): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1076): CM callback handler got msg 524290
,I/GLSUser ( 1423): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1423): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1423): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1423): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1423): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/Herrevad( 1833): NQAS connected
,I/Babel   ( 3894): connection state changed from DISCONNECTED to CONNECTED
,W/Kids    ( 1833): [AccountUtils] Account not ready
W/Kids    ( 1833): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 1833): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 1833): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 1833): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 1833): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 1833): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 1833): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 1833): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 1833): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 1833): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 1833): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 1833): 	at java.lang.Thread.run(Thread.java:818)
,D/GCM     ( 1423): Connected
,D/GCM     ( 1423): Message class com.google.f.a.a.p
,D/ConnectivityService(  822): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=10.00 rxSuccessRate=13.75 targetRoamBSSID=any RSSI=-47
E/WifiStateMachine(  822): WifiStateMachine L2Connected CMD_START_SCAN source -2 8, 10 -> obsolete
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/MusicLeanback( 3923): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 3923): Stop autocaching.
,D/WearableService( 3397): callingUid 10011, callindPid: 3397
,E/GmsUtils( 3923): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
E/GmsUtils( 3923): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/jxcore-log( 3833): BLE supported!!
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=9.25 rxSuccessRate=14.69 targetRoamBSSID=any RSSI=-47
,E/WifiStateMachine(  822): WifiStateMachine L2Connected CMD_START_SCAN source -2 9, 10 -> obsolete
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,V/GLSActivity( 1423): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1423): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1423): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1423): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1423): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1423): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3470): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3470): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3470): [1] 5.onFinished: Scheduling replication attempt 4.
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.82 rxSuccessRate=2.58 targetRoamBSSID=any RSSI=-47
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/PowerManagerService(  822): Going to sleep due to screen timeout (uid 1000)...
,I/Adreno  (  822): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/PermissionCache(  258): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (328 us)
,I/art     (  822): Explicit concurrent mark sweep GC freed 47843(2MB) AllocSpace objects, 9(144KB) LOS objects, 32% free, 33MB/49MB, paused 2.836ms total 108.290ms
,I/BooksSync( 3740): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3740): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1423): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1423): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1423): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1423): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1423): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SurfaceFlinger(  258): Set power mode=0, type=0 flinger=0xb6482000
I/DisplayManagerService(  822): Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
D/qdhwcomposer(  258): hwc_setPowerMode: Setting mode 0 on display: 0
,V/ActivityManager(  822): Display changed displayId=0
,I/art     ( 1423): Explicit concurrent mark sweep GC freed 25076(1430KB) AllocSpace objects, 6(661KB) LOS objects, 37% free, 26MB/42MB, paused 965us total 29.105ms
,I/GLSUser ( 1423): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1423): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1423): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1423): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1423): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/BooksAccountManager( 3740): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3740): Soft error
E/BooksSync( 3740): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3740): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3740): Sync error
E/BooksSync( 3740): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3740): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3740): Finished books sync
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 163290, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/qdhwcomposer(  258): handle_blank_event: dpy:0 panel power state: 0,
D/qdhwcomposer(  258): hwc_setPowerMode: Done setting mode 0 on display 0
,D/SurfaceControl(  822): Excessive delay in setPowerMode(): 257ms
,I/DreamManagerService(  822): Entering dreamland.
I/PowerManagerService(  822): Dozing...
I/DreamController(  822): Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,D/audio_hw_primary(  358): adev_set_parameters: enter: screen_state=on
,D/mot_vr_audio_hw(  358): adev_set_parameters: screen_state=on
,E/WifiStateMachine(  822): cancelDelayedScan -> 12
,E/native  (  822): do suspend false
,I/Keyboard.Facilitator( 1261): onFinishInput()
,E/WifiStateMachine(  822): cancelDelayedScan -> 14
,E/native  (  822): do suspend true
,D/audio_hw_primary(  358): adev_set_parameters: enter: screen_state=off
,D/mot_vr_audio_hw(  358): adev_set_parameters: screen_state=off
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-48
E/WifiStateMachine(  822): WifiStateMachine L2Connected CMD_START_SCAN source -2 13, 14 -> obsolete
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,V/GLSActivity( 1423): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1423): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1423): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1423): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1423): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1423): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3470): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3470): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3470): [1] 5.onFinished: Scheduling replication attempt 5.
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): ,
,V/GLSActivity( 1423): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1423): Vacuum at: now=1449063232771 tag=VacuumService
,V/GoogleAuthProtoRequest( 3952): [426] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1423): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1423): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1423): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1423): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1423): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GoogleURLConnFactory( 1423): Using platform SSLCertificateSocketFactory
,W/ExperimentUpdateService( 3952): [426] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3952): [426] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3952): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3952): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3952): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3952): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3952): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3952): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3952): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3952): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3952): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3952): 	at com.a.a.k.run(SourceFile:110)
,W/Uploader( 1423): No account for auth token provided
,W/Uploader( 1423): No account for auth token provided
,I/GoogleURLConnFactory( 1423): Using platform SSLCertificateSocketFactory
,W/Uploader( 1423): No account for auth token provided
,W/Uploader( 1423): No account for auth token provided
,I/GLSUser ( 1423): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1423): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1423): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1423): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1423): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/Uploader( 1423): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1423): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1423): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1423): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1423): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1423): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1423): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1423): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1423): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1423): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1423): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1423): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1423): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-48
,E/WifiStateMachine(  822): WifiStateMachine L2Connected CMD_START_SCAN source -2 11, 14 -> obsolete
,W/Uploader( 1423): No account for auth token provided
,W/Uploader( 1423): No account for auth token provided
,I/GLSUser ( 1423): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1423): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1423): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1423): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1423): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1423): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1423): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1423): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1423): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1423): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1423): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1423): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1423): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1423): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1423): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1423): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1423): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1423): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/GLSUser ( 1423): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1423): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1423): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1423): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1423): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1423): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1423): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1423): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1423): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1423): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1423): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1423): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1423): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1423): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1423): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1423): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1423): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1423): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1423): No account for auth token provided
,W/Uploader( 1423): No account for auth token provided
,W/Uploader( 1423): No account for auth token provided
,W/Uploader( 1423):  no longer exists, so no auth token.
,I/GLSUser ( 1423): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1423): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1423): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1423): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1423): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1423): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1423): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1423): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1423): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1423): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1423): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1423): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1423): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1423): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1423): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1423): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1423): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1423): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/GLSUser ( 1423): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1423): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1423): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1423): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1423): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1423): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1423): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
,E/Uploader( 1423): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1423): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1423): 	at com.google.android.gms.auth.p.c(SourceFile:550),
E/Uploader( 1423): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1423): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508),
E/Uploader( 1423): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1423): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1423): ,	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1423): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1423): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1423): ,	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,D/HeadsetStateMachine( 2211): Disconnected process message: 10, size: 0
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,D/HeadsetStateMachine( 2211): Disconnected process message: 10, size: 0
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,V/KeepSync( 3757): Connecting to GoogleApiClient
,I/art     (  822): Explicit concurrent mark sweep GC freed 39168(1786KB) AllocSpace objects, 2(126KB) LOS objects, 31% free, 34MB/50MB, paused 1.843ms total 99.298ms
,I/GLSUser ( 1423): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1423): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1423): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1423): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1423): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1423): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1423): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1423): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1423): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1423): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1833): Handling authorization failure
E/ClientConnectionOperation( 1833): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1833): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1833): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1833): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1833): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1833): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1833): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1833): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1833): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1833): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1833): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1833): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1833): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1833): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1833): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1833): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1833): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1833): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1833): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1833): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1833): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1833): 	... 7 more
,E/HttpOperation( 3240): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3240): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3240): 	at jdm.a(PG:82)
E/HttpOperation( 3240): 	at jcs.o(PG:406)
E/HttpOperation( 3240): 	at jcn.a(PG:1379)
E/HttpOperation( 3240): 	at jcs.i(PG:143)
E/HttpOperation( 3240): 	at blb.a(PG:3937)
E/HttpOperation( 3240): 	at czp.a(PG:18188)
E/HttpOperation( 3240): 	at czp.a(PG:9081)
E/HttpOperation( 3240): 	at czq.run(PG:1686),
E/HttpOperation( 3240): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3240): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3240): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3240): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3240): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3240): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3240): 	at jdj.a(PG:4091)
E/HttpOperation( 3240): 	at jdj.a(PG:1125)
,E/HttpOperation( 3240): 	at jdm.a(PG:77)
E/HttpOperation( 3240): 	... 12 more
E/HttpOperation( 3240): Caused by: faj: BadAuthentication
E/HttpOperation( 3240): 	at fal.a(PG:38)
E/HttpOperation( 3240): 	at jdj.a(PG:4089)
E/HttpOperation( 3240): 	... 14 more
V/KeepSync( 3757): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3757): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3757): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3757): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1423): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1423): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1423): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1423): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1423): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3240): [getmobileexperiments] Unexpected exception,
E/HttpOperation( 3240): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3240): 	at jdm.a(PG:82)
E/HttpOperation( 3240): 	at jcs.o(PG:406)
E/HttpOperation( 3240): 	at jcn.a(PG:1379)
E/HttpOperation( 3240): 	at jcs.i(PG:143)
E/HttpOperation( 3240): 	at hec.a(PG:42)
E/HttpOperation( 3240): 	at hee.a(PG:102)
E/HttpOperation( 3240): 	at czr.a(PG:65)
E/HttpOperation( 3240): 	at kka.a(PG:108)
E/HttpOperation( 3240): 	at czp.a(PG:19176)
E/HttpOperation( 3240): 	at czp.a(PG:9081)
E/HttpOperation( 3240): 	at czq.run(PG:1686)
E/HttpOperation( 3240): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3240): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3240): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3240): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3240): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3240): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3240): 	at jdj.a(PG:4091)
E/HttpOperation( 3240): 	at jdj.a(PG:1125)
E/HttpOperation( 3240): 	at jdm.a(PG:77)
E/HttpOperation( 3240): 	... 15 more
E/HttpOperation( 3240): Caused by: faj: BadAuthentication
E/HttpOperation( 3240): 	at fal.a(PG:38)
,E/HttpOperation( 3240): 	at jdj.a(PG:4089)
E/HttpOperation( 3240): 	... 17 more
E/ExperimentLoader( 3240): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3240): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3240): 	at jdm.a(PG:82)
E/ExperimentLoader( 3240): 	at jcs.o(PG:406)
E/ExperimentLoader( 3240): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3240): 	at jcs.i(PG:143)
E/ExperimentLoader( 3240): 	at hec.a(PG:42)
E/ExperimentLoader( 3240): 	at hee.a(PG:102)
E/ExperimentLoader( 3240): 	at czr.a(PG:65)
E/ExperimentLoader( 3240): 	at kka.a(PG:108)
E/ExperimentLoader( 3240): 	,at czp.a(PG:19176)
E/ExperimentLoader( 3240): 	at czp.a(PG:9081)
E/ExperimentLoader( 3240): 	at czq.run(PG:1686)
E/ExperimentLoader( 3240): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3240): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3240): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3240): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3240): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3240): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3240): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3240): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3240): 	at jdm.a(PG:77)
E/ExperimentLoader( 3240): 	... 15 more,
E/ExperimentLoader( 3240): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3240): 	at fal.a(PG:38)
E/ExperimentLoader( 3240): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3240): 	... 17 more
,I/GLSUser ( 1423): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1423): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1423): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1423): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1423): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3757): IOException
E/KeepSync( 3757): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3757): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3757): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3757): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3757): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3757): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3757): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3757): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3757): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3757): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3757): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3757): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3757): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3757): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3757): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3757): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3757): 	... 10 more
W/KeepSync( 3757): Sync result 2
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 166737, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 166319, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,V/GLSActivity( 1423): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1423): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1423): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1423): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1423): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1423): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3470): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3470): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3470): [1] 5.onFinished: Giving up after 6 failures.
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,V/GoogleAuthProtoRequest( 3952): [427] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1423): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1423): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1423): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1423): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1423): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1423): Explicit concurrent mark sweep GC freed 71781(4MB) AllocSpace objects, 10(771KB) LOS objects, 36% free, 27MB/43MB, paused 2.468ms total 58.689ms
,W/ExperimentUpdateService( 3952): [427] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3952): [427] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3952): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3952): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3952): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3952): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3952): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3952): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3952): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3952): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3952): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3952): 	at com.a.a.k.run(SourceFile:110)
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/BooksSync( 3740): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3740): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1423): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1423): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1423): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1423): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1423): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1423): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1423): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1423): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1423): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1423): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3740): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3740): Soft error
E/BooksSync( 3740): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3740): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3740): Sync error
E/BooksSync( 3740): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3740): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3740): Finished books sync
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 194503, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/Keyboard.Facilitator.LanguageModelFlusher( 1261): run()
I/Keyboard.Facilitator( 1261): flushDynamicLanguageModels()
,I/ConfigService( 1423): onCreate
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/ConfigService( 1423): onDestroy
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
,I/jxcore-log( 3833): 
,D/HeadsetStateMachine( 2211): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2211): Disconnected process message: 10, size: 0
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,V/KeepSync( 3757): Connecting to GoogleApiClient
,I/GLSUser ( 1423): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1423): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1423): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1423): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/GLSUser ( 1423): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1423): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1423): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1423): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1423): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1423): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1833): Handling authorization failure
E/ClientConnectionOperation( 1833): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1833): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1833): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1833): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1833): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1833): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1833): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1833): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1833): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1833): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1833): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1833): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1833): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1833): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1833): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1833): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1833): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1833): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1833): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1833): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1833): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1833): 	... 7 more
,V/KeepSync( 3757): GoogleApiClient failed to connect with error code: 4
,E/HttpOperation( 3240): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3240): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3240): 	at jdm.a(PG:82)
E/HttpOperation( 3240): 	at jcs.o(PG:406)
E/HttpOperation( 3240): 	at jcn.a(PG:1379)
E/HttpOperation( 3240): 	at jcs.i(PG:143)
E/HttpOperation( 3240): 	at blb.a(PG:3937)
E/HttpOperation( 3240): 	at czp.a(PG:18188)
E/HttpOperation( 3240): 	at czp.a(PG:9081)
E/HttpOperation( 3240): 	at czq.run(PG:1686)
E/HttpOperation( 3240): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3240): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3240): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3240): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3240): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3240): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3240): 	at jdj.a(PG:4091)
E/HttpOperation( 3240): 	at jdj.a(PG:1125)
E/HttpOperation( 3240): 	at jdm.a(PG:77)
E/HttpOperation( 3240): 	... 12 more
E/HttpOperation( 3240): Caused by: faj: BadAuthentication
E/HttpOperation( 3240): 	at fal.a(PG:38)
E/HttpOperation( 3240): 	at jdj.a(PG:4089)
E/HttpOperation( 3240): 	... 14 more
,E/SQLiteLog( 3757): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3757): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3757): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1423): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1423): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1423): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1423): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1423): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/HttpOperation( 3240): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3240): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3240): 	at jdm.a(PG:82)
E/HttpOperation( 3240): 	at jcs.o(PG:406)
E/HttpOperation( 3240): 	at jcn.a(PG:1379)
E/HttpOperation( 3240): 	at jcs.i(PG:143)
E/HttpOperation( 3240): 	at hec.a(PG:42)
E/HttpOperation( 3240): 	at hee.a(PG:102)
E/HttpOperation( 3240): 	at czr.a(PG:65)
E/HttpOperation( 3240): 	at kka.a(PG:108)
E/HttpOperation( 3240): 	at czp.a(PG:19176)
E/HttpOperation( 3240): 	at czp.a(PG:9081)
E/HttpOperation( 3240): 	at czq.run(PG:1686)
E/HttpOperation( 3240): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3240): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3240): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3240): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3240): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3240): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3240): 	at jdj.a(PG:4091)
E/HttpOperation( 3240): 	at jdj.a(PG:1125)
E/HttpOperation( 3240): 	at jdm.a(PG:77)
E/HttpOperation( 3240): 	... 15 more
E/HttpOperation( 3240): Caused by: faj: BadAuthentication
E/HttpOperation( 3240): 	at fal.a(PG:38)
E/HttpOperation( 3240): 	at jdj.a(PG:4089)
E/HttpOperation( 3240): 	... 17 more
E/ExperimentLoader( 3240): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3240): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3240): 	at jdm.a(PG:82)
E/ExperimentLoader( 3240): 	at jcs.o(PG:406)
E/ExperimentLoader( 3240): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3240): 	at jcs.i(PG:143)
E/ExperimentLoader( 3240): 	at hec.a(PG:42)
E/ExperimentLoader( 3240): 	at hee.a(PG:102)
E/ExperimentLoader( 3240): 	at czr.a(PG:65)
E/ExperimentLoader( 3240): 	at kka.a(PG:108)
E/ExperimentLoader( 3240): 	at czp.a(PG:19176)
E/ExperimentLoader( 3240): 	at czp.a(PG:9081)
E/ExperimentLoader( 3240): 	at czq.run(PG:1686)
E/ExperimentLoader( 3240): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3240): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3240): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3240): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3240): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3240): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3240): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3240): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3240): 	at jdm.a(PG:77)
E/ExperimentLoader( 3240): 	... 15 more
E/ExperimentLoader( 3240): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3240): 	at fal.a(PG:38)
E/ExperimentLoader( 3240): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3240): 	... 17 more
,I/GLSUser ( 1423): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1423): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1423): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1423): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1423): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3757): IOException
E/KeepSync( 3757): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3757): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3757): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3757): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3757): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3757): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3757): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3757): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3757): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3757): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3757): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3757): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3757): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3757): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3757): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3757): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3757): 	... 10 more
W/KeepSync( 3757): Sync result 2
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 225233, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 224379, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,V/GoogleAuthProtoRequest( 3952): [428] a.<init>: mAccountName set to: thalitester@gmail.com
,D/HeadsetStateMachine( 2211): Disconnected process message: 10, size: 0
,I/art     (  822): Explicit concurrent mark sweep GC freed 31498(1361KB) AllocSpace objects, 12(757KB) LOS objects, 31% free, 34MB/50MB, paused 1.583ms total 64.935ms
,I/GLSUser ( 1423): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1423): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1423): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1423): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1423): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3952): [428] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3952): [428] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3952): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3952): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3952): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3952): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3952): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3952): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3952): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3952): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3952): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3952): 	at com.a.a.k.run(SourceFile:110)
,D/HeadsetStateMachine( 2211): Disconnected process message: 10, size: 0
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/BooksSync( 3740): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3740): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1423): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1423): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1423): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1423): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1423): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1423): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1423): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1423): [GLSUser] Extracting token using key: Auth,
W/GLSActivity( 1423): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1423): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3740): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3740): Soft error,
E/BooksSync( 3740): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3740): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3740): Sync error
E/BooksSync( 3740): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3740): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3740): Finished books sync,
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 285440, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,V/KeepSync( 3757): Connecting to GoogleApiClient
,I/GLSUser ( 1423): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1423): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1423): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1423): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1423): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1423): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1423): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1423): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1423): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
E/HttpOperation( 3240): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3240): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3240): 	at jdm.a(PG:82)
E/HttpOperation( 3240): 	at jcs.o(PG:406)
E/HttpOperation( 3240): 	at jcn.a(PG:1379)
E/HttpOperation( 3240): 	at jcs.i(PG:143)
E/HttpOperation( 3240): 	at blb.a(PG:3937)
E/HttpOperation( 3240): 	at czp.a(PG:18188)
E/HttpOperation( 3240): 	at czp.a(PG:9081)
E/HttpOperation( 3240): 	at czq.run(PG:1686)
E/HttpOperation( 3240): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3240): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3240): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3240): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3240): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3240): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3240): 	at jdj.a(PG:4091)
E/HttpOperation( 3240): 	at jdj.a(PG:1125)
E/HttpOperation( 3240): 	at jdm.a(PG:77)
E/HttpOperation( 3240): 	... 12 more
E/HttpOperation( 3240): Caused by: faj: BadAuthentication
E/HttpOperation( 3240): 	at fal.a(PG:38)
E/HttpOperation( 3240): 	at jdj.a(PG:4089)
E/HttpOperation( 3240): 	... 14 more
,V/GLSActivity( 1423): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1833): Handling authorization failure
E/ClientConnectionOperation( 1833): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1833): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1833): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1833): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1833): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1833): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1833): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1833): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1833): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1833): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1833): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1833): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1833): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1833): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1833): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1833): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1833): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1833): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1833): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1833): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1833): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1833): 	... 7 more
,V/KeepSync( 3757): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3757): (284) automatic index on blob_node(is_deleted),
,E/SQLiteLog( 3757): (284) automatic index on blob_node(is_deleted),
,E/SQLiteLog( 3757): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1423): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1423): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1423): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1423): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1423): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3240): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3240): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3240): 	at jdm.a(PG:82)
E/HttpOperation( 3240): 	at jcs.o(PG:406)
E/HttpOperation( 3240): 	at jcn.a(PG:1379)
E/HttpOperation( 3240): 	at jcs.i(PG:143)
E/HttpOperation( 3240): 	at hec.a(PG:42)
E/HttpOperation( 3240): 	at hee.a(PG:102)
E/HttpOperation( 3240): 	at czr.a(PG:65)
E/HttpOperation( 3240): 	at kka.a(PG:108)
E/HttpOperation( 3240): 	at czp.a(PG:19176)
E/HttpOperation( 3240): 	at czp.a(PG:9081)
E/HttpOperation( 3240): 	at czq.run(PG:1686)
E/HttpOperation( 3240): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3240): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3240): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3240): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3240): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3240): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3240): 	at jdj.a(PG:4091)
E/HttpOperation( 3240): 	at jdj.a(PG:1125)
E/HttpOperation( 3240): 	at jdm.a(PG:77)
E/HttpOperation( 3240): 	... 15 more
E/HttpOperation( 3240): Caused by: faj: BadAuthentication
E/HttpOperation( 3240): 	at fal.a(PG:38)
E/HttpOperation( 3240): 	at jdj.a(PG:4089)
E/HttpOperation( 3240): 	... 17 more
,E/ExperimentLoader( 3240): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token,
E/ExperimentLoader( 3240): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3240): 	at jdm.a(PG:82)
E/ExperimentLoader( 3240): 	at jcs.o(PG:406)
E/ExperimentLoader( 3240): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3240): 	at jcs.i(PG:143)
E/ExperimentLoader( 3240): 	at hec.a(PG:42)
E/ExperimentLoader( 3240): 	at hee.a(PG:102)
E/ExperimentLoader( 3240): 	at czr.a(PG:65),
E/ExperimentLoader( 3240): 	at kka.a(PG:108)
E/ExperimentLoader( 3240): 	at czp.a(PG:19176)
E/ExperimentLoader( 3240): 	at czp.a(PG:9081)
E/ExperimentLoader( 3240): 	at czq.run(PG:1686)
E/ExperimentLoader( 3240): 	,at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3240): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3240): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3240): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3240): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3240): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3240): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3240): 	,at jdj.a(PG:1125)
E/ExperimentLoader( 3240): 	at jdm.a(PG:77)
E/ExperimentLoader( 3240): 	... 15 more
E/ExperimentLoader( 3240): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3240): 	at fal.a(PG:38)
E/ExperimentLoader( 3240): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3240): ,	... 17 more
,I/GLSUser ( 1423): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive,
I/GLSUser ( 1423): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1423): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1423): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1423): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3757): IOException
E/KeepSync( 3757): com.google.android.apiary.AuthenticationException: Could not get an auth token,
E/KeepSync( 3757): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3757): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3757): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3757): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3757): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3757): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3757): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3757): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3757): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3757): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3757): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3757): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3757): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3757): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3757): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3757): 	... 10 more
W/KeepSync( 3757): Sync result 2
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 316690, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 314990, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,V/GLSActivity( 1423): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1423): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1423): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1423): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1423): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1423): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1423): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1423): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1423): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1423): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1423): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1423): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1423): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 3470): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3470): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.,
E/PlayEventLogger( 3470): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 3470): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3470): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/PlayEventLogger( 3470): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3470): 	,at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 3470): Ignoring header User-Agent because its value was null.
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): ,
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,D/HeadsetStateMachine( 2211): Disconnected process message: 10, size: 0
,D/WifiService(  822): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@8cceae9}
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-48
,I/art     ( 1423): Explicit concurrent mark sweep GC freed 47128(2MB) AllocSpace objects, 14(1543KB) LOS objects, 36% free, 27MB/43MB, paused 1.449ms total 61.457ms
,D/HeadsetStateMachine( 2211): Disconnected process message: 10, size: 0
,D/WifiService(  822): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@8cceae9}
,E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::injectLocation(GpsExtLocation):857]: error! inject position failed
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): ,
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): ,
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): ,
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,D/HeadsetStateMachine( 2211): Disconnected process message: 10, size: 0
,V/GoogleAuthProtoRequest( 3952): [429] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1423): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1423): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1423): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1423): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1423): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3952): [429] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3952): [429] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3952): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3952): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3952): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3952): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3952): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3952): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3952): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3952): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3952): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3952): 	at com.a.a.k.run(SourceFile:110)
,I/art     (  822): Explicit concurrent mark sweep GC freed 31524(1468KB) AllocSpace objects, 11(458KB) LOS objects, 31% free, 34MB/50MB, paused 2.384ms total 89.916ms
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/BooksSync( 3740): Starting books sync for 61035162, extras: ade,
,I/BooksConfig( 3740): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1423): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1423): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1423): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1423): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1423): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1423): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1423): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1423): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1423): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1423): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3740): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3740): Soft error
,E/BooksSync( 3740): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3740): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3740): Sync error
E/BooksSync( 3740): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3740): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source),
I/BooksSync( 3740): Finished books sync
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 437083, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/GLSUser ( 1423): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1423): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1423): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1423): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1423): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/HttpOperation( 3240): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3240): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3240): 	at jdm.a(PG:82)
E/HttpOperation( 3240): 	at jcs.o(PG:406)
E/HttpOperation( 3240): 	at jcn.a(PG:1379)
E/HttpOperation( 3240): 	at jcs.i(PG:143)
E/HttpOperation( 3240): 	at blb.a(PG:3937)
E/HttpOperation( 3240): 	at czp.a(PG:18188)
E/HttpOperation( 3240): 	at czp.a(PG:9081)
E/HttpOperation( 3240): 	at czq.run(PG:1686)
E/HttpOperation( 3240): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3240): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3240): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3240): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3240): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3240): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3240): 	at jdj.a(PG:4091)
E/HttpOperation( 3240): 	at jdj.a(PG:1125)
E/HttpOperation( 3240): 	at jdm.a(PG:77)
E/HttpOperation( 3240): 	... 12 more
E/HttpOperation( 3240): Caused by: faj: BadAuthentication
E/HttpOperation( 3240): 	at fal.a(PG:38)
E/HttpOperation( 3240): 	at jdj.a(PG:4089)
E/HttpOperation( 3240): 	... 14 more
,I/GLSUser ( 1423): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1423): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1423): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1423): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1423): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3240): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3240): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3240): 	at jdm.a(PG:82)
E/HttpOperation( 3240): 	at jcs.o(PG:406)
E/HttpOperation( 3240): 	at jcn.a(PG:1379)
E/HttpOperation( 3240): 	at jcs.i(PG:143)
E/HttpOperation( 3240): 	at hec.a(PG:42)
E/HttpOperation( 3240): 	at hee.a(PG:102)
E/HttpOperation( 3240): 	at czr.a(PG:65)
E/HttpOperation( 3240): 	at kka.a(PG:108)
E/HttpOperation( 3240): 	at czp.a(PG:19176)
E/HttpOperation( 3240): 	at czp.a(PG:9081)
E/HttpOperation( 3240): 	at czq.run(PG:1686)
E/HttpOperation( 3240): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3240): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3240): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3240): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3240): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3240): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3240): 	at jdj.a(PG:4091)
E/HttpOperation( 3240): 	at jdj.a(PG:1125)
E/HttpOperation( 3240): 	at jdm.a(PG:77)
E/HttpOperation( 3240): 	... 15 more
E/HttpOperation( 3240): Caused by: faj: BadAuthentication
E/HttpOperation( 3240): 	at fal.a(PG:38)
E/HttpOperation( 3240): 	at jdj.a(PG:4089)
E/HttpOperation( 3240): 	... 17 more
,E/ExperimentLoader( 3240): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3240): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3240): 	at jdm.a(PG:82)
E/ExperimentLoader( 3240): 	at jcs.o(PG:406)
E/ExperimentLoader( 3240): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3240): 	at jcs.i(PG:143)
E/ExperimentLoader( 3240): 	at hec.a(PG:42)
E/ExperimentLoader( 3240): 	at hee.a(PG:102)
E/ExperimentLoader( 3240): 	at czr.a(PG:65)
E/ExperimentLoader( 3240): 	at kka.a(PG:108)
E/ExperimentLoader( 3240): 	at czp.a(PG:19176)
E/ExperimentLoader( 3240): 	at czp.a(PG:9081)
E/ExperimentLoader( 3240): 	at czq.run(PG:1686)
E/ExperimentLoader( 3240): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3240): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3240): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3240): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3240): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3240): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3240): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3240): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3240): 	at jdm.a(PG:77)
E/ExperimentLoader( 3240): 	... 15 more
E/ExperimentLoader( 3240): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3240): 	at fal.a(PG:38)
E/ExperimentLoader( 3240): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3240): 	... 17 more
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 466140, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,D/HeadsetStateMachine( 2211): Disconnected process message: 10, size: 0
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 3833): 
,V/KeepSync( 3757): Connecting to GoogleApiClient
,I/GLSUser ( 1423): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1423): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1423): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1423): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1423): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/ClientConnectionOperation( 1833): Handling authorization failure
E/ClientConnectionOperation( 1833): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1833): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1833): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1833): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1833): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1833): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1833): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1833): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1833): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1833): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1833): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1833): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1833): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1833): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1833): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1833): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1833): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1833): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1833): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1833): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1833): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1833): 	... 7 more
,V/KeepSync( 3757): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3757): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3757): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3757): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1423): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1423): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1423): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1423): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1423): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3757): IOException
E/KeepSync( 3757): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3757): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3757): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3757): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3757): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3757): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3757): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3757): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3757): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3757): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3757): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3757): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3757): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3757): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3757): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3757): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3757): 	... 10 more
,W/KeepSync( 3757): Sync result 2
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 469621, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,D/HeadsetStateMachine( 2211): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2211): Disconnected process message: 10, size: 0
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
,I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): ,
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
,I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): ,
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,D/HeadsetStateMachine( 2211): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2211): Disconnected process message: 10, size: 0
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,D/HeadsetStateMachine( 2211): Disconnected process message: 10, size: 0
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,D/HeadsetStateMachine( 2211): Disconnected process message: 10, size: 0
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/BooksSync( 3740): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3740): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1423): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1423): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1423): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1423): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1423): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1423): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1423): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1423): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1423): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1423): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3740): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3740): Soft error
E/BooksSync( 3740): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3740): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3740): Sync error
E/BooksSync( 3740): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3740): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 3740): Finished books sync
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 683974, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/GLSUser ( 1423): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1423): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1423): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1423): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1423): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3240): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3240): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3240): 	at jdm.a(PG:82)
E/HttpOperation( 3240): 	at jcs.o(PG:406)
E/HttpOperation( 3240): 	at jcn.a(PG:1379)
E/HttpOperation( 3240): 	at jcs.i(PG:143)
E/HttpOperation( 3240): 	at blb.a(PG:3937)
E/HttpOperation( 3240): 	at czp.a(PG:18188)
E/HttpOperation( 3240): 	at czp.a(PG:9081)
E/HttpOperation( 3240): 	at czq.run(PG:1686)
E/HttpOperation( 3240): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3240): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3240): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3240): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3240): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3240): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3240): 	at jdj.a(PG:4091)
E/HttpOperation( 3240): 	at jdj.a(PG:1125)
E/HttpOperation( 3240): 	at jdm.a(PG:77)
E/HttpOperation( 3240): 	... 12 more
E/HttpOperation( 3240): Caused by: faj: BadAuthentication
E/HttpOperation( 3240): 	at fal.a(PG:38)
E/HttpOperation( 3240): 	at jdj.a(PG:4089)
E/HttpOperation( 3240): 	... 14 more
,I/GLSUser ( 1423): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1423): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1423): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1423): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1423): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3240): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3240): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3240): 	at jdm.a(PG:82)
E/HttpOperation( 3240): 	at jcs.o(PG:406)
E/HttpOperation( 3240): 	at jcn.a(PG:1379)
E/HttpOperation( 3240): 	at jcs.i(PG:143)
E/HttpOperation( 3240): 	at hec.a(PG:42)
E/HttpOperation( 3240): 	at hee.a(PG:102)
E/HttpOperation( 3240): 	at czr.a(PG:65)
E/HttpOperation( 3240): 	at kka.a(PG:108)
E/HttpOperation( 3240): 	at czp.a(PG:19176)
E/HttpOperation( 3240): 	at czp.a(PG:9081)
E/HttpOperation( 3240): 	at czq.run(PG:1686)
E/HttpOperation( 3240): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3240): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3240): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3240): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3240): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3240): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3240): 	at jdj.a(PG:4091)
E/HttpOperation( 3240): 	at jdj.a(PG:1125)
E/HttpOperation( 3240): 	at jdm.a(PG:77)
E/HttpOperation( 3240): 	... 15 more
E/HttpOperation( 3240): Caused by: faj: BadAuthentication
E/HttpOperation( 3240): 	at fal.a(PG:38)
E/HttpOperation( 3240): 	at jdj.a(PG:4089)
E/HttpOperation( 3240): 	... 17 more
E/ExperimentLoader( 3240): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token,
E/ExperimentLoader( 3240): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3240): 	at jdm.a(PG:82)
E/ExperimentLoader( 3240): 	at jcs.o(PG:406)
E/ExperimentLoader( 3240): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3240): 	at jcs.i(PG:143)
E/ExperimentLoader( 3240): 	at hec.a(PG:42)
E/ExperimentLoader( 3240): 	at hee.a(PG:102)
E/ExperimentLoader( 3240): 	at czr.a(PG:65)
E/ExperimentLoader( 3240): 	at kka.a(PG:108)
E/ExperimentLoader( 3240): 	at czp.a(PG:19176)
E/ExperimentLoader( 3240): 	at czp.a(PG:9081)
E/ExperimentLoader( 3240): 	at czq.run(PG:1686)
E/ExperimentLoader( 3240): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3240): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3240): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3240): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3240): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3240): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3240): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3240): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3240): 	at jdm.a(PG:77)
E/ExperimentLoader( 3240): 	... 15 more,
E/ExperimentLoader( 3240): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3240): 	at fal.a(PG:38)
E/ExperimentLoader( 3240): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3240): 	... 17 more
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 712060, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,D/HeadsetStateMachine( 2211): Disconnected process message: 10, size: 0
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,D/HeadsetStateMachine( 2211): Disconnected process message: 10, size: 0
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
,I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): ,
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,D/Finsky  ( 3470): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/GLSActivity( 1423): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  822): Explicit concurrent mark sweep GC freed 42373(1862KB) AllocSpace objects, 9(426KB) LOS objects, 31% free, 34MB/50MB, paused 1.500ms total 116.545ms
,I/GLSUser ( 1423): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1423): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1423): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1423): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1423): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GoogleAuthProtoRequest( 3952): [430] a.<init>: mAccountName set to: thalitester@gmail.com
,I/art     ( 1423): Explicit concurrent mark sweep GC freed 58259(3MB) AllocSpace objects, 13(1434KB) LOS objects, 36% free, 27MB/43MB, paused 1.109ms total 29.715ms
,I/EventLogService( 1833): Opted in for usage reporting
I/EventLogService( 1833): Aggregate from 1449062009068 (log), 1449062009068 (data)
,V/KeepSync( 3757): Connecting to GoogleApiClient
,W/Finsky  ( 3470): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1423): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1423): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1423): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1423): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1423): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1423): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1423): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1423): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1423): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1423): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1423): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1423): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1423): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1423): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1423): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1423): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/EventLogAggregator( 1833): Unknown tag: snet_gcore
W/EventLogAggregator( 1833): Unknown tag: snet_launch_service
,V/GLSActivity( 1423): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3952): [430] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3952): [430] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3952): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3952): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3952): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3952): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3952): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3952): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3952): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3952): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3952): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3952): 	at com.a.a.k.run(SourceFile:110)
I/GLSUser ( 1423): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1423): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1423): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1423): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1423): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1833): Handling authorization failure
E/ClientConnectionOperation( 1833): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1833): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1833): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1833): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1833): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1833): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1833): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1833): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1833): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1833): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1833): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1833): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1833): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1833): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1833): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1833): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1833): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1833): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1833): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1833): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1833): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1833): 	... 7 more
,V/KeepSync( 3757): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3757): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3757): (284) automatic index on blob_node(is_deleted),
E/SQLiteLog( 3757): (284) automatic index on blob_node(is_deleted)
,W/Finsky  ( 3470): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/ServiceDumpSys( 1833): dumping service [account]
,I/GLSUser ( 1423): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1423): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1423): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1423): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1423): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3757): IOException
E/KeepSync( 3757): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3757): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3757): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3757): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3757): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3757): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3757): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3757): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3757): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3757): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3757): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3757): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3757): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3757): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3757): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3757): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3757): 	... 10 more
W/KeepSync( 3757): Sync result 2
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 749048, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,V/GLSActivity( 1423): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1423): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1423): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1423): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1423): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1423): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/Finsky  ( 3470): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 3470): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 3470): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3470): [1] DailyHygiene.reschedule: Scheduling new run in 31 minutes (failures=2)
,D/DeviceConnectionService( 1858): client connected with version: 7571000
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,V/GLSActivity( 1423): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1423): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1423): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1423): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1423): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1423): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3470): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3470): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3470): [1] 5.onFinished: Scheduling replication attempt 1.
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,D/HeadsetStateMachine( 2211): Disconnected process message: 10, size: 0
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,D/HeadsetStateMachine( 2211): Disconnected process message: 10, size: 0,
,V/GLSActivity( 1423): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1423): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1423): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1423): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1423): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1423): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3470): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3470): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3470): [1] 5.onFinished: Scheduling replication attempt 2.
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,V/GLSActivity( 1423): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1423): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1423): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1423): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1423): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1423): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3470): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3470): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3470): [1] 5.onFinished: Scheduling replication attempt 3.
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,V/GLSActivity( 1423): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1423): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1423): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1423): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1423): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1423): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3470): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3470): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3470): [1] 5.onFinished: Scheduling replication attempt 4.
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,D/HeadsetStateMachine( 2211): Disconnected process message: 10, size: 0
,I/ActivityManager(  822): Start proc 4354:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider
,I/art     (  822): Explicit concurrent mark sweep GC freed 23680(1088KB) AllocSpace objects, 7(394KB) LOS objects, 31% free, 34MB/50MB, paused 1.673ms total 99.556ms
,I/GAv4    ( 4354): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4354):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4354):   adb logcat -s GAv4
,W/GAv4    ( 4354): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4354): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4354): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  822): Killing 3665:com.android.musicfx/u0a18 (adj 15): empty #17
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,D/HeadsetStateMachine( 2211): Disconnected process message: 10, size: 0
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,V/GLSActivity( 1423): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1423): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure,
I/GLSUser ( 1423): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1423): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1423): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1423): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/Finsky  ( 3470): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.,
D/Finsky  ( 3470): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3470): [1] 5.onFinished: Scheduling replication attempt 5.
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,V/GLSActivity( 1423): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1423): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1423): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1423): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1423): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1423): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3470): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3470): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3470): [1] 5.onFinished: Giving up after 6 failures.
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,D/HeadsetStateMachine( 2211): Disconnected process message: 10, size: 0
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,D/HeadsetStateMachine( 2211): Disconnected process message: 10, size: 0
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): ,
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): ,
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,W/bt-btm  ( 2211): Stopping oneshot timer
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,D/HeadsetStateMachine( 2211): Disconnected process message: 10, size: 0
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
,I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
,I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
,I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,D/HeadsetStateMachine( 2211): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2211): Disconnected process message: 10, size: 0
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,D/HeadsetStateMachine( 2211): Disconnected process message: 10, size: 0,
,D/HeadsetStateMachine( 2211): Disconnected process message: 10, size: 0
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): ,
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,D/HeadsetStateMachine( 2211): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2211): Disconnected process message: 10, size: 0
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/BooksSync( 3740): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3740): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1423): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1423): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1423): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1423): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1423): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1423): Explicit concurrent mark sweep GC freed 65827(3MB) AllocSpace objects, 8(882KB) LOS objects, 37% free, 26MB/42MB, paused 1.865ms total 45.028ms
,I/GLSUser ( 1423): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1423): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1423): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1423): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1423): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3740): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3740): Soft error
E/BooksSync( 3740): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3740): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3740): Sync error
E/BooksSync( 3740): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3740): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3740): Finished books sync
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1177479, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,D/HeadsetStateMachine( 2211): Disconnected process message: 10, size: 0
,I/GLSUser ( 1423): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1423): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1423): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1423): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1423): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3240): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3240): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3240): 	at jdm.a(PG:82)
E/HttpOperation( 3240): 	at jcs.o(PG:406)
E/HttpOperation( 3240): 	at jcn.a(PG:1379)
E/HttpOperation( 3240): 	at jcs.i(PG:143)
E/HttpOperation( 3240): 	at blb.a(PG:3937)
E/HttpOperation( 3240): 	at czp.a(PG:18188)
E/HttpOperation( 3240): 	at czp.a(PG:9081)
E/HttpOperation( 3240): 	at czq.run(PG:1686)
E/HttpOperation( 3240): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3240): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3240): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3240): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3240): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3240): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3240): 	at jdj.a(PG:4091)
E/HttpOperation( 3240): 	at jdj.a(PG:1125)
E/HttpOperation( 3240): 	at jdm.a(PG:77)
E/HttpOperation( 3240): 	... 12 more
E/HttpOperation( 3240): Caused by: faj: BadAuthentication
E/HttpOperation( 3240): 	at fal.a(PG:38)
E/HttpOperation( 3240): 	at jdj.a(PG:4089)
E/HttpOperation( 3240): 	... 14 more
,I/GLSUser ( 1423): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1423): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1423): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1423): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1423): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3240): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3240): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3240): 	at jdm.a(PG:82)
E/HttpOperation( 3240): 	at jcs.o(PG:406)
E/HttpOperation( 3240): 	at jcn.a(PG:1379)
E/HttpOperation( 3240): 	at jcs.i(PG:143)
E/HttpOperation( 3240): 	at hec.a(PG:42)
E/HttpOperation( 3240): 	at hee.a(PG:102)
E/HttpOperation( 3240): 	at czr.a(PG:65)
E/HttpOperation( 3240): 	at kka.a(PG:108)
E/HttpOperation( 3240): 	at czp.a(PG:19176)
E/HttpOperation( 3240): 	at czp.a(PG:9081)
E/HttpOperation( 3240): 	at czq.run(PG:1686)
E/HttpOperation( 3240): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3240): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3240): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3240): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3240): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3240): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3240): 	at jdj.a(PG:4091)
E/HttpOperation( 3240): 	at jdj.a(PG:1125)
E/HttpOperation( 3240): 	at jdm.a(PG:77)
E/HttpOperation( 3240): 	... 15 more
E/HttpOperation( 3240): Caused by: faj: BadAuthentication
E/HttpOperation( 3240): 	at fal.a(PG:38)
E/HttpOperation( 3240): 	at jdj.a(PG:4089)
E/HttpOperation( 3240): 	... 17 more
,E/ExperimentLoader( 3240): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3240): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3240): 	at jdm.a(PG:82)
E/ExperimentLoader( 3240): 	at jcs.o(PG:406)
E/ExperimentLoader( 3240): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3240): 	at jcs.i(PG:143)
E/ExperimentLoader( 3240): 	at hec.a(PG:42)
E/ExperimentLoader( 3240): 	at hee.a(PG:102)
E/ExperimentLoader( 3240): 	at czr.a(PG:65)
E/ExperimentLoader( 3240): 	at kka.a(PG:108)
E/ExperimentLoader( 3240): 	at czp.a(PG:19176)
E/ExperimentLoader( 3240): 	at czp.a(PG:9081)
E/ExperimentLoader( 3240): 	at czq.run(PG:1686)
E/ExperimentLoader( 3240): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3240): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3240): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3240): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3240): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3240): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3240): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3240): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3240): 	at jdm.a(PG:77)
E/ExperimentLoader( 3240): 	... 15 more
E/ExperimentLoader( 3240): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3240): 	at fal.a(PG:38)
E/ExperimentLoader( 3240): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3240): 	... 17 more
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 1203515, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/UsageStatsService(  822): User[0] Flushing usage stats to disk
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,D/GCM     ( 1423): Message class com.google.f.a.a.i
,V/GoogleAuthProtoRequest( 3952): [431] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1423): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1423): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1423): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1423): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1423): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3952): [431] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3952): [431] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3952): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3952): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3952): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3952): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3952): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3952): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3952): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3952): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3952): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3952): 	at com.a.a.k.run(SourceFile:110)
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,D/HeadsetStateMachine( 2211): Disconnected process message: 10, size: 0
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,V/KeepSync( 3757): Connecting to GoogleApiClient
,I/GLSUser ( 1423): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1423): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1423): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1423): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1423): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/ClientConnectionOperation( 1833): Handling authorization failure,
E/ClientConnectionOperation( 1833): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1833): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1833): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1833): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1833): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1833): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1833): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
,E/ClientConnectionOperation( 1833): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1833): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1833): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1833): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1833): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1833): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1833): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1833): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1833): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1833): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1833): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1833): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1833): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1833): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1833): 	... 7 more
,V/KeepSync( 3757): GoogleApiClient failed to connect with error code: 4
E/SQLiteLog( 3757): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3757): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3757): (284) automatic index on blob_node(is_deleted)
,I/art     (  822): Explicit concurrent mark sweep GC freed 41406(2003KB) AllocSpace objects, 7(206KB) LOS objects, 32% free, 33MB/49MB, paused 1.771ms total 99.328ms
,I/GLSUser ( 1423): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1423): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1423): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1423): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1423): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3757): IOException
E/KeepSync( 3757): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3757): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3757): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3757): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3757): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3757): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3757): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3757): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3757): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3757): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3757): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3757): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3757): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3757): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3757): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3757): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3757): 	... 10 more
W/KeepSync( 3757): Sync result 2
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 1259618, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2211): Disconnected process message: 10, size: 0
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
,I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
,I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
,I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,D/HeadsetStateMachine( 2211): Disconnected process message: 10, size: 0
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,D/HeadsetStateMachine( 2211): Disconnected process message: 10, size: 0
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,D/HeadsetStateMachine( 2211): Disconnected process message: 10, size: 0
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,D/HeadsetStateMachine( 2211): Disconnected process message: 10, size: 0
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
,I/jxcore-log( 3833): 
,D/HeadsetStateMachine( 2211): Disconnected process message: 10, size: 0
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,D/HeadsetStateMachine( 2211): Disconnected process message: 10, size: 0
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,D/HeadsetStateMachine( 2211): Disconnected process message: 10, size: 0
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,D/HeadsetStateMachine( 2211): Disconnected process message: 10, size: 0
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,D/HeadsetStateMachine( 2211): Disconnected process message: 10, size: 0
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,D/HeadsetStateMachine( 2211): Disconnected process message: 10, size: 0
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,D/HeadsetStateMachine( 2211): Disconnected process message: 10, size: 0
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,D/HeadsetStateMachine( 2211): Disconnected process message: 10, size: 0
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,D/HeadsetStateMachine( 2211): Disconnected process message: 10, size: 0
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,D/HeadsetStateMachine( 2211): Disconnected process message: 10, size: 0
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,D/HeadsetStateMachine( 2211): Disconnected process message: 10, size: 0
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,D/HeadsetStateMachine( 2211): Disconnected process message: 10, size: 0
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,W/bt-btm  ( 2211): Stopping oneshot timer
,I/ProcessStatsService(  822): Prepared write state in 23ms
,I/ProcessStatsService(  822): Prepared write state in 7ms
,I/ProcessStatsService(  822): Pruning old procstats: /data/system/procstats/state-2015-12-01-17-53-10.bin
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,D/HeadsetStateMachine( 2211): Disconnected process message: 10, size: 0
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,D/HeadsetStateMachine( 2211): Disconnected process message: 10, size: 0
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/ActivityManager(  822): Killing 3602:com.android.defcontainer/u0a7 (adj 15): empty for 1835s
,I/ActivityManager(  822): Killing 3696:com.google.android.apps.docs/u0a46 (adj 15): empty for 1835s
,D/HeadsetStateMachine( 2211): Disconnected process message: 10, size: 0
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
,TIME-OUT KILL (timeout was 1800000ms),I/jxcore-log( 3833): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3833): 
D/AndroidRuntime( 4586): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 4586): CheckJNI is OFF
D/AndroidRuntime( 4586): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  822): Force stopping com.test.thalitest appid=10265 user=-1: uninstall pkg
I/ActivityManager(  822): Killing 3833:com.test.thalitest/u0a265 (adj 0): stop com.test.thalitest
I/WindowState(  822): WIN DEATH: Window{18216bba u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  822): Client connection lost with reason: 4
W/PackageSettings(  822): Skipping PackageSetting{229b82d5 com.example.hello/10272} due to missing metadata
W/ActivityManager(  822): Force removing ActivityRecord{36633c13 u0 com.test.thalitest/.MainActivity t24}: app died, no saved state
I/ActivityManager(  822): Killing 3923:com.google.android.music:main/u0a66 (adj 13): empty for 1807s
I/ActivityManager(  822): Killing 3894:com.google.android.talk/u0a61 (adj 13): empty for 1809s
I/ActivityManager(  822): Killing 4066:com.google.android.apps.photos/u0a71 (adj 13): empty for 1809s
I/ActivityManager(  822): Killing 4005:com.google.android.apps.magazines/u0a67 (adj 15): empty for 1809s
I/ActivityManager(  822): Killing 3985:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty for 1809s
V/ActivityManager(  822): Display changed displayId=0
W/ActivityManager(  822): Spurious death for ProcessRecord{128c13b3 3833:com.test.thalitest/u0a265}, curProc for 3833: null
I/ActivityManager(  822): Force stopping com.test.thalitest appid=10265 user=0: pkg removed
D/TaskPersister(  822): removeObsoleteFile: deleting file=24_task.xml
W/BroadcastQueue(  822): Failure sending broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
W/BroadcastQueue(  822): android.os.RemoteException: app.thread must not be null
W/BroadcastQueue(  822): 	at com.android.server.am.BroadcastQueue.performReceiveLocked(BroadcastQueue.java:435)
W/BroadcastQueue(  822): 	at com.android.server.am.BroadcastQueue.deliverToRegisteredReceiverLocked(BroadcastQueue.java:521)
W/BroadcastQueue(  822): 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:569)
W/BroadcastQueue(  822): 	at com.android.server.am.BroadcastQueue$BroadcastHandler.handleMessage(BroadcastQueue.java:149)
W/BroadcastQueue(  822): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/BroadcastQueue(  822): 	at android.os.Looper.loop(Looper.java:135)
W/BroadcastQueue(  822): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/BroadcastQueue(  822): 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
I/Keyboard.Facilitator( 1261): resetDictionaries() : en_US
D/BuaReceiver( 3628): ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
I/InputReader(  822): Reconfiguring input devices.  changes=0x00000010
I/art     ( 1076): Explicit concurrent mark sweep GC freed 84034(3MB) AllocSpace objects, 0(0B) LOS objects, 17% free, 74MB/90MB, paused 2.325ms total 63.079ms
I/Keyboard.Facilitator.DecoderInitializer( 1261): run()
I/Decoder ( 1261): createOrResetDecoder
I/ActivityManager(  822): Start proc 4602:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
I/ConfigService( 1423): onCreate
I/art     (  369): Explicit concurrent mark sweep GC freed 703(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 200us total 17.558ms
I/art     ( 1535): Explicit concurrent mark sweep GC freed 2323(171KB) AllocSpace objects, 1(26KB) LOS objects, 36% free, 27MB/43MB, paused 523us total 124.154ms
I/art     (  822): Explicit concurrent mark sweep GC freed 37532(2MB) AllocSpace objects, 8(302KB) LOS objects, 31% free, 34MB/50MB, paused 1.521ms total 101.422ms
I/art     (  822): WaitForGcToComplete blocked for 66.376ms for cause Explicit
I/art     (  369): Explicit concurrent mark sweep GC freed 8(256B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 305us total 13.034ms
I/Keyboard.Facilitator.MainLanguageModelLoader( 1261): run()
I/art     (  369): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 199us total 9.666ms
I/Keyboard.Facilitator.MainLanguageModelLoader( 1261): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1261): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1261): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1261): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1261): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1261): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1261): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1261): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1261): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1261): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1261): run()
I/StatsUtilsManager( 1261): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1261): shouldRecordStats() = Too Soon
D/VoicemailCleanupService( 4602): Cleaning up data for package: com.test.thalitest
I/art     (  822): Explicit concurrent mark sweep GC freed 4073(201KB) AllocSpace objects, 1(110KB) LOS objects, 32% free, 33MB/49MB, paused 1.426ms total 80.724ms
D/JobSchedulerService(  822): Receieved: android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  822): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
W/InputMethodManagerService(  822): Got RemoteException sending setActive(false) notification to pid 3833 uid 10265
I/Keyboard.Facilitator( 1261): onFinishInput()
I/ActivityManager(  822): Start proc 4626:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
I/ContactLocale( 4602): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
W/LocationOracleImpl( 1535): Best location was null
I/art     ( 1348): Explicit concurrent mark sweep GC freed 5013(365KB) AllocSpace objects, 12(1408KB) LOS objects, 31% free, 35MB/51MB, paused 1ms total 20.532ms
I/HotwordRecognitionRnr( 1535): Starting hotword detection.
I/MicrophoneInputStream( 1535): mic_starting com.google.android.apps.gsa.speech.audio.u@6322289
I/AudioFlinger(  358): AudioFlinger's thread 0xb4d39000 ready to run
I/SoundTriggerHwService::Module(  358): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/MicrophoneInputStream( 1535): mic_started com.google.android.apps.gsa.speech.audio.u@6322289
D/audio_hw_primary(  358): select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
D/msm8974_platform(  358): platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
E/ACDB-LOADER(  358): Error: ACDB AudProc vol returned = -19
D/audio_hw_primary(  358): enable_snd_device: snd_device(55: voice-rec-mic)
D/audio_hw_primary(  358): enable_audio_route: apply and update mixer path: audio-record
I/ActivityManager(  822): Start proc 4656:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
I/art     ( 1423): Explicit concurrent mark sweep GC freed 75152(3MB) AllocSpace objects, 3(330KB) LOS objects, 36% free, 27MB/43MB, paused 945us total 32.141ms
W/LocationOracleImpl( 1535): Best location was null
I/art     ( 4586): System.exit called, status: 0
I/AndroidRuntime( 4586): VM exiting with result code 0.
W/ContextImpl( 4656): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2609 
W/LocationOracleImpl( 1535): Best location was null
D/Launcher.Workspace( 1348): 11683562 - stripEmptyScreens()
I/HotwordWorker( 1535): onReady
D/Launcher.Workspace( 1348): 11683562 - stripEmptyScreens()
E/NetworkScheduler.SchedulerReceiver( 1423): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1423): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
D/ChimeraCfgMgr( 1833): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1833): Module APK com.google.android.play.games already loaded
D/PackageBroadcastService( 1833): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/ChimeraCfgMgr( 1833): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1833): Module APK com.google.android.play.games already loaded
I/ActivityManager(  822): Killing 3397:com.google.android.gms.wearable/u0a11 (adj 15): empty for 1808s
D/AccountUtils( 1833): Clearing selected account for com.test.thalitest
I/art     ( 1858): Explicit concurrent mark sweep GC freed 18830(1091KB) AllocSpace objects, 8(128KB) LOS objects, 37% free, 26MB/42MB, paused 1.178ms total 32.406ms
E/DataBuffer( 1858): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@4f6328b)
E/DataBuffer( 1858): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2bc0f68)
E/SQLiteLog( 1833): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/DriveAsyncService( 1833): disk I/O error (code 3850)
E/DriveAsyncService( 1833): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 1833): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 1833): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/DriveAsyncService( 1833): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 1833): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 1833): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/DriveAsyncService( 1833): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/DriveAsyncService( 1833): 	at com.google.android.gms.drive.database.k.l(SourceFile:596)
E/DriveAsyncService( 1833): 	at com.google.android.gms.drive.database.k.b(SourceFile:570)
E/DriveAsyncService( 1833): 	at com.google.android.gms.drive.database.f.h(SourceFile:1473)
E/DriveAsyncService( 1833): 	at com.google.android.gms.drive.api.a.bc.a(SourceFile:16)
E/DriveAsyncService( 1833): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/DriveAsyncService( 1833): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 1833): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 1833): 	at java.lang.Thread.run(Thread.java:818)
I/LocationSettingsChecker( 1833): Removing dialog suppression flag for package com.test.thalitest
I/UpdateIcingCorporaServi( 1535): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
E/SQLiteDatabase( 1833): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 1833): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1833): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1833): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1833): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1833): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1833): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1833): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1833): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1833): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1833): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1833): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 1833): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 1833): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1833): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 1833): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 1833): 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
E/SQLiteDatabase( 1833): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 1833): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 1833): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1833): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1833): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 1833): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 1833): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 1833): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1833): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1833): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 1833): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 1833): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1833): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1833): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1833): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteOpenHelper( 1833): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteOpenHelper( 1833): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 1833): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteOpenHelper( 1833): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 1833): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 1833): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 1833): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 1833): 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
E/SQLiteOpenHelper( 1833): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 1833): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 1833): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 1833): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 1833): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteOpenHelper( 1833): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/SQLiteOpenHelper( 1833): Opened metrics.db in read-only mode
D/GOOGLEHELP_CompatibleDatabase( 1833): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1833): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
E/SQLiteLog( 1833): (8) statement aborts at 16: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
D/GOOGLEHELP_CompatibleDatabase( 1833): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
--------- beginning of crash
E/AndroidRuntime( 1833): FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
E/AndroidRuntime( 1833): Process: com.google.android.gms, PID: 1833
E/AndroidRuntime( 1833): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/AndroidRuntime( 1833): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1833): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 1833): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1833): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1833): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/AndroidRuntime( 1833): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:281)
E/AndroidRuntime( 1833): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/AndroidRuntime( 1833): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 1833): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1833): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 1833): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 1535): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
I/ActivityManager(  822): Start proc 4693:com.google.android.gms.wearable/u0a11 for service com.google.android.gms/.wearable.service.WearableControlService
E/SQLiteDatabase( 1833): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 1833): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1833): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1833): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1833): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1833): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1833): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1833): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1833): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1833): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1833): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1833): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 1833): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 1833): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 1833): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1833): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 1833): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteDatabase( 1833): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1833): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1833): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 1833): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 1833): Couldn't open phenotype.db for writing (will try read-only):
E/SQLiteOpenHelper( 1833): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1833): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1833): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 1833): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 1833): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1833): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1833): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1833): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteOpenHelper( 1833): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteOpenHelper( 1833): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 1833): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteOpenHelper( 1833): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 1833): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 1833): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 1833): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 1833): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteOpenHelper( 1833): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 1833): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 1833): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteOpenHelper( 1833): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Launcher( 1348): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@455be28 new=com.google.android.velvet.VelvetApplication@455be28
W/SQLiteOpenHelper( 1833): Opened phenotype.db in read-only mode
E/SQLiteLog( 1348): (3850) statement aborts at 24: [DELETE FROM shortcut_and_widget_previews WHERE name LIKE ? OR name LIKE ?] disk I/O error
D/WifiService(  822): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@228ca5ab}
E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=29.00 rxSuccessRate=39.25 targetRoamBSSID=any RSSI=-48
I/ActivityManager(  822): Start proc 4711:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
E/SharedPreferencesImpl( 1535): Couldn't create directory for SharedPreferences file /data/data/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml
E/AndroidRuntime( 1535): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 1535): Process: com.google.android.googlequicksearchbox:search, PID: 1535
E/AndroidRuntime( 1535): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1535): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 1535): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/AndroidRuntime( 1535): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 1535): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 1535): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/AndroidRuntime( 1535): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/AndroidRuntime( 1535): 	at com.google.android.apps.gsa.extradex.icingsync.b.a(ApplicationsHelperImpl.java:85)
E/AndroidRuntime( 1535): 	at com.google.android.search.core.icingsync.d.i(InternalIcingCorporaProvider.java:623)
E/AndroidRuntime( 1535): 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:298)
E/AndroidRuntime( 1535): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:328)
E/AndroidRuntime( 1535): 	at android.content.ContentResolver.update(ContentResolver.java:1333)
E/AndroidRuntime( 1535): 	at com.google.android.search.core.icingsync.e.JA(UpdateIcingCorporaService.java:408)
E/AndroidRuntime( 1535): 	at com.google.android.search.core.icingsync.g.aTY(UpdateIcingCorporaService.java:347)
E/AndroidRuntime( 1535): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:320)
E/AndroidRuntime( 1535): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.ba(UpdateIcingCorporaService.java:215)
E/AndroidRuntime( 1535): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:201)
E/AndroidRuntime( 1535): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 1535): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1535): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 1535): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DropBoxManagerService(  822): Can't write: system_app_crash
E/DropBoxManagerService(  822): java.io.FileNotFoundException: /data/system/dropbox/drop102.tmp: open failed: EROFS (Read-only file system)
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
W/ResourcesManager( 4693): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4693): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/OpenGLRenderer(  822): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
D/Atlas   (  822): Validating map...
E/DropBoxManagerService(  822): Can't write: system_app_crash
E/DropBoxManagerService(  822): java.io.FileNotFoundException: /data/system/dropbox/drop104.tmp: open failed: EROFS (Read-only file system)
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
I/MultiDex( 4693): VM with version 2.1.0 has multidex support
I/MultiDex( 4693): install
I/MultiDex( 4693): VM has multidex support, MultiDex support library is disabled.
E/QMI_FW  (  822): xport_send: Sendto failed for port 4352
E/LocSvc_api_v02(  822): E/locClientSendReq:2446]: send_msg_sync error: -1
E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 11, ind.status = -1698190611
E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
I/ActivityManager(  822): Start proc 4732:com.google.android.apps.docs/u0a46 for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=221.50 rxSuccessRate=402.62 targetRoamBSSID=any RSSI=-48
I/ConfigFetchService( 1833): onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
E/SharedPreferencesImpl( 1833): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/config_removals.xml to backup file /data/data/com.google.android.gms/shared_prefs/config_removals.xml.bak
I/ConfigFetchService( 1833): service connected
V/JNIHelp ( 4693): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
I/PeopleContactsSync( 1833): CP2 sync disabled
W/BaseAppContext( 1833): Using Auth Proxy for data requests.
I/OpenGLRenderer(  822): Initialized EGL, version 1.4
D/OpenGLRenderer(  822): Enabling debug mode 0
W/BaseAppContext( 1833): Using Auth Proxy for data requests.
E/SQLiteDatabase( 1833): Failed to open database '/data/data/com.google.android.gms/databases/app_state.db'.
E/SQLiteDatabase( 1833): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1833): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1833): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1833): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1833): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1833): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1833): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1833): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1833): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1833): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1833): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 1833): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 1833): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1833): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 1833): 	at com.google.android.gms.common.i.a.delete(SourceFile:272)
E/SQLiteDatabase( 1833): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
E/SQLiteDatabase( 1833): 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
E/SQLiteDatabase( 1833): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
E/SQLiteDatabase( 1833): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
E/SQLiteDatabase( 1833): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/SQLiteDatabase( 1833): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 1833): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 1833): 	at java.lang.Thread.run(Thread.java:818)
E/ClearPendingStateOp( 1833): Runtime exception while performing operation
E/ClearPendingStateOp( 1833): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/ClearPendingStateOp( 1833): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/ClearPendingStateOp( 1833): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/ClearPendingStateOp( 1833): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/ClearPendingStateOp( 1833): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/ClearPendingStateOp( 1833): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/ClearPendingStateOp( 1833): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/ClearPendingStateOp( 1833): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/ClearPendingStateOp( 1833): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/ClearPendingStateOp( 1833): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/ClearPendingStateOp( 1833): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/ClearPendingStateOp( 1833): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/ClearPendingStateOp( 1833): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/ClearPendingStateOp( 1833): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/ClearPendingStateOp( 1833): 	at com.google.android.gms.common.i.a.delete(SourceFile:272)
E/ClearPendingStateOp( 1833): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
E/ClearPendingStateOp( 1833): 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
E/ClearPendingStateOp( 1833): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
E/ClearPendingStateOp( 1833): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
E/ClearPendingStateOp( 1833): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearPendingStateOp( 1833): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearPendingStateOp( 1833): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearPendingStateOp( 1833): 	at java.lang.Thread.run(Thread.java:818)
F/ClearPendingStateOp( 1833): Killing (on development devices) due to RuntimeException
F/ClearPendingStateOp( 1833): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
F/ClearPendingStateOp( 1833): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
F/ClearPendingStateOp( 1833): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
F/ClearPendingStateOp( 1833): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
F/ClearPendingStateOp( 1833): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
F/ClearPendingStateOp( 1833): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
F/ClearPendingStateOp( 1833): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
F/ClearPendingStateOp( 1833): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
F/ClearPendingStateOp( 1833): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
F/ClearPendingStateOp( 1833): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
F/ClearPendingStateOp( 1833): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
F/ClearPendingStateOp( 1833): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
F/ClearPendingStateOp( 1833): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
F/ClearPendingStateOp( 1833): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
F/ClearPendingStateOp( 1833): 	at com.google.android.gms.common.i.a.delete(SourceFile:272)
F/ClearPendingStateOp( 1833): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
F/ClearPendingStateOp( 1833): 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
F/ClearPendingStateOp( 1833): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
F/ClearPendingStateOp( 1833): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
F/ClearPendingStateOp( 1833): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
F/ClearPendingStateOp( 1833): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
F/ClearPendingStateOp( 1833): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
F/ClearPendingStateOp( 1833): 	at java.lang.Thread.run(Thread.java:818)
E/DropBoxManagerService(  822): Can't write: system_app_wtf
E/DropBoxManagerService(  822): java.io.FileNotFoundException: /data/system/dropbox/drop105.tmp: open failed: EROFS (Read-only file system)
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
I/Icing   ( 1833): doRemovePackageData com.test.thalitest
I/qdhwcomposer(  258): handle_blank_event: dpy:0 panel power state: 0
I/ProviderInstaller( 4693): Installed default security provider GmsCore_OpenSSL

```
