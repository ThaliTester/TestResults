#### Test 539786637913587_thali05_motorola-Nexus 6 Logs


```
--------- beginning of main
V/GLSActivity( 1267): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 1267): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1267): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1267): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1267): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1267): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 3448): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3448): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3448): [1] 5.onFinished: Scheduling replication attempt 3.
,D/AndroidRuntime( 3796): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 3796): CheckJNI is OFF
D/AndroidRuntime( 3796): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  823): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/WindowManager(  823): addAppToken: AppWindowToken{9247783 token=Token{393b0e32 ActivityRecord{4ee263d u0 com.test.thalitest/.MainActivity t26}}} to stack=1 task=26 at 0
V/WindowManager(  823): Adding window Window{275ae92c u0 Starting com.test.thalitest} at 2 of 7 (after Window{3a1a7dd u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
D/AndroidRuntime( 3796): Shutting down VM
I/HotwordDetector( 1515): Closing mic
I/MicrophoneInputStream( 1515): mic_close com.google.android.apps.gsa.speech.audio.u@18055dfc
I/ActivityManager(  823): Start proc 3810:com.test.thalitest/u0a265 for activity com.test.thalitest/.MainActivity
D/audio_hw_primary(  359): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  359): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  359): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1515): Hotword detection finished
I/HotwordRecognitionRnr( 1515): Stopping hotword detection.
I/ActivityManager(  823): Killing 3243:com.google.android.apps.photos/u0a71 (adj 15): empty #17
E/LocSvc_IzatApiV02(  823): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1658578195
E/LocSvc_IzatApiV02(  823): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
I/WebViewFactory( 3810): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3810): Time to load native libraries: 1 ms (timestamps 1675-1676)
I/LibraryLoader( 3810): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3810): Binding Chromium to main looper Looper (main, tid 1) {3b798787}
,I/LibraryLoader( 3810): Expected native library version number "",actual native library version number "",
I/chromium( 3810): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/kickstart(  875): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
,I/kickstart(  875): STATUS: Wrote to /sys/power/wake_lock
,I/BrowserStartupController( 3810): Initializing chromium process, singleProcess=true
,W/art     ( 3810): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3810): ApplicationContext is null in ApplicationStatus
,W/chromium( 3810): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3810): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3810): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3810): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,E/kickstart(  875): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2
,I/kickstart(  875): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2' for writing
,D/BluetoothManagerService(  823): Message: 20
D/BluetoothManagerService(  823): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@980f55c:true
,W/art     ( 3810): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3810): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3810): CordovaWebView is running on device made by: motorola
,W/art     ( 3810): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3810): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3810): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,D/Atlas   ( 3810): Validating map...
,V/WindowManager(  823): Adding window Window{1d1a6d8c u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{275ae92c u0 Starting com.test.thalitest})
,W/chromium( 3810): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3810): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3810): Enabling debug mode 0
,I/ActivityManager(  823): Displayed com.test.thalitest/.MainActivity: +731ms
,I/Keyboard.Facilitator( 1241): onFinishInput()
,W/BindingManager( 3810): Cannot call determinedVisibility() - never saw a connection for the pid: 3810
,D/JsMessageQueue( 3810): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3810): JniHelper::setJavaVM(0xb489d200), pthread_self() = -1576271360
D/JX-Cordova( 3810): jxcore cordova android initializing
,I/kickstart(  875): STATUS: Received file 'm9kefs2'
I/kickstart(  875): STATUS: 950272 bytes transferred in 0.988002 seconds
I/kickstart(  875): STATUS: Successfully downloaded files from target 
I/kickstart(  875): STATUS: Wrote to /sys/power/wake_unlock
,I/kickstart(  875): STATUS: Sahara protocol completed
,W/jxcore-log( 3810): Initializing JXcore engine
W/jxcore-log( 3810): JXcore engine is ready
,W/jxcore-log( 3810): Starting JXcore engine
,W/.test.thalitest( 3810): type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[10677]" dev="sockfs" ino=10677 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0,
,W/.test.thalitest( 3810): type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0,
,W/.test.thalitest( 3810): type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[12998]" dev="sockfs" ino=12998 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/.test.thalitest( 3810): type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[24685]" dev="sockfs" ino=24685 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 3810): Platform android
W/jxcore-log( 3810): 
W/jxcore-log( 3810): Process ARCH arm
W/jxcore-log( 3810): 
,I/jxcore-log( 3810): JXcore Cordova bridge is ready!
I/jxcore-log( 3810): 
W/jxcore-log( 3810): JXcore engine is started
,I/chromium( 3810): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
I/Choreographer( 3810): Skipped 137 frames!  The application may be doing too much work on its main thread.
,I/ActivityManager(  823): Killing 3047:com.google.android.music:main/u0a66 (adj 15): empty #17
,I/jxcore-log( 3810): Toggling radios to true
I/jxcore-log( 3810): 
,D/BluetoothAdapter( 3810): enable(): BT is already enabled..!
,D/WifiService(  823): New client listening to asynchronous messages
,D/WifiService(  823): setWifiEnabled: true pid=3810, uid=10265
E/WifiService(  823): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3810): Radios toggled
I/jxcore-log( 3810): 
,I/wpa_supplicant( 1190): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
E/WifiStateMachine(  823): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  823): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  355): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1267): Read error: ssl=0xaece5600: I/O error during system call, Connection timed out
,V/NativeCrypto( 1267): SSL shutdown failed: ssl=0xaece5600: I/O error during system call, Broken pipe
,D/ConnectivityService(  823): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10011
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  823): ValidatedState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  823): DefaultState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  823): Forcing reevaluation
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  823): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  823): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  823): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
D/ConnectivityService(  823): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
,D/ConnectivityService(  823): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,I/ActivityManager(  823): Start proc 3869:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
,D/ConnectivityService(  823): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  823): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
E/WifiStateMachine(  823): Start Disconnecting Watchdog 1
,E/WifiStateMachine(  823): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,W/ResourcesManager( 3869): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/CommandListener(  355): Clearing all IP addresses on wlan0
,D/ConnectivityService(  823): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/WifiNetworkAgent(  823): NetworkAgent: NetworkAgent channel lost
D/ConnectivityManager.CallbackHandler( 1073): CM callback handler got msg 524292
E/WifiStateMachine(  823): CMD_AUTO_CONNECT sup state CompletedState my state DisconnectedState nid=0 roam=3
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  823): OfflineState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  823): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=0
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  823): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  823): Disconnected - quitting
D/CSLegacyTypeTracker(  823): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  823): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  823): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  823): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/Tethering(  823): MasterInitialState.processMessage what=3
D/ConnectivityService(  823): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering(  823): MasterInitialState.processMessage what=3
D/ConnectivityService(  823): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/PhoneInterfaceManager( 1338): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1338): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  823): getDataEnabled: retVal=false
E/GpsLocationProvider(  823): No APN found to select.
,D/PhoneInterfaceManager( 1338): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1338): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  823): getDataEnabled: retVal=false
,E/WifiConfigStore(  823): Setting BSSID for "NG7005g"WPA_PSK to any
E/WifiConfigStore(  823): will read network variables netId=0
,E/WifiStateMachine(  823): CMD_AUTO_CONNECT did save config ->  nid=0
,E/WifiConfigStore(  823): will read network variables netId=0
E/GpsLocationProvider(  823): No APN found to select.
,I/Babel_SMS( 3869): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 3869): MmsConfig.loadMmsSettings
,I/Babel_SMS( 3869): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
I/Babel_SMS( 3869): MmsConfig.loadFromDatabase
,E/Babel_SMS( 3869): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 3869): MmsConfig.loadFromResources
E/Babel_SMS( 3869): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 3869): MmsConfig.loadMmsSettings: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,W/Settings( 3869): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 3869): startup - clean,
,I/Babel   ( 3869): deleted: false for 0
,I/Babel_telephony( 3869): TeleModule.launchCompleted
W/Telecom (  823): TelecomServiceImpl: null is not visible for the calling user
,I/Babel_telephony( 3869): TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
W/Babel   ( 3869): BAM#gBA: invalid account id: -1
W/Babel   ( 3869): BAM#gBA: invalid account id: -1
I/Babel_telephony( 3869): TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,W/Telecom (  823): TelecomServiceImpl: null is not visible for the calling user
,I/ActivityManager(  823): Start proc 3902:com.google.android.music:main/u0a66 for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver
,W/VideoCapabilities( 3869): Unrecognized profile 2130706433 for video/avc
,I/MusicStore( 3902): Database version: 120
,I/VideoCapabilities( 3869): Unsupported profile 4 for video/mp4v-es
W/VideoCapabilities( 3869): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 3869): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 3869): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 3869): Unrecognized profile 2130706433 for video/avc
,I/art     (  823): Explicit concurrent mark sweep GC freed 39899(1942KB) AllocSpace objects, 11(270KB) LOS objects, 32% free, 33MB/49MB, paused 1.797ms total 52.408ms
I/ActivityManager(  823): Killing 3391:com.google.android.gm/u0a78 (adj 15): empty #17
,I/vclib   ( 3869): onServiceConnected
,W/Babel   ( 3869): Attempted to change video mute state without an active call.
,W/ResourcesManager( 3902): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3902): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 3902): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ProviderInstaller( 3902): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 3902): GMSCore installation verified,
,I/ConfigStore( 3902): Config Database version: 1
,I/MediaRouter( 3902): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 3902): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/ActivityManager(  823): Start proc 3931:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.steen.receiver.ConnectivityChangeReceiver
,I/GHttpClientFactory( 3902): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 3902): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  823): Killing 3487:com.google.android.gms:car/u0a11 (adj 15): empty #17
,I/ActivityManager(  823): Killing 2473:com.google.android.calendar/u0a37 (adj 15): empty #17
,I/ActivityManager(  823): Start proc 3959:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,D/SprintDMReceiver( 3959): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3959): simOperator:  IMSI: null
D/SprintDMReceiver( 3959): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1805): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1805): onCreate
D/SystemUpdateService( 1805): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1805): active receiver: enabled
,I/SystemUpdateService( 1805): showing system update notification
,I/iu.Environment( 1805): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1805): num queued entries: 0
I/iu.UploadsManager( 1805): num updated entries: 0
I/iu.SyncManager( 1805): NEXT; no task
,I/ValidateNoPeople(  823): skipping global notification
D/ChimeraCfgMgr( 1805): Loading module com.google.android.gms.kids from APK com.google.android.gms
,V/SystemUpdateService( 1805): retry (wakeup: false) in 3599955 ms
,I/art     ( 1515): WaitForGcToComplete blocked for 44.556ms for cause HomogeneousSpaceCompact
,I/ActivityManager(  823): Start proc 3984:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,I/Babel   ( 3869): connection state changed from UNKNOWN to DISCONNECTED
D/SystemUpdateService( 1805): onDestroy
,I/ActivityManager(  823): Killing 3352:com.android.providers.calendar/u0a3 (adj 15): empty #17
,I/wpa_supplicant( 1190): wlan0: Trying to associate with SSID 'NG7005g'
,D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/jxcore-log( 3810): Got Device Bluetooth address: F8:CF:C5:D9:E5:61
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): my name is : motorola-Nexus 6_PT9351
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): attempting to connect to test coordinator
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): check test folder
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): found test : ./testFindPeers.js
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): found test : ./testReConnect.js
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): found test : ./testSendData.js
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): Test app app.js loaded
I/jxcore-log( 3810): 
,I/Choreographer( 3810): Skipped 120 frames!  The application may be doing too much work on its main thread.
,I/GAv4    ( 3984): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3984):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3984):   adb logcat -s GAv4
,I/jxcore-log( 3810): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3810): 
I/chromium( 3810): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,W/GAv4    ( 3984): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3984): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3984): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 3984): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3984): Time to load native libraries: 5 ms (timestamps 7143-7148)
,I/LibraryLoader( 3984): Expected native library version number "",actual native library version number ""
,I/wpa_supplicant( 1190): wlan0: Associated with c0:ff:d4:d3:aa:4a
,V/WebViewChromiumFactoryProvider( 3984): Binding Chromium to main looper Looper (main, tid 1) {26680ba}
,I/LibraryLoader( 3984): Expected native library version number "",actual native library version number ""
,I/chromium( 3984): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3984): Initializing chromium process, singleProcess=true
W/art     ( 3984): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3984): ApplicationContext is null in ApplicationStatus
,W/chromium( 3984): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,I/wpa_supplicant( 1190): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1190): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=0 id_str=]
,D/ConnectivityService(  823): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} }
,E/WifiConfigStore(  823): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  823): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/libEGL  ( 3984): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3984): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3984): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,E/WifiConfigStore(  823): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  355): Setting iface cfg
,E/WifiStateMachine(  823): Start Dhcp Watchdog 2
,E/WifiStateMachine(  823):  WifiLinkLayerStats: 
E/WifiStateMachine(  823):  my bss beacon rx: 490
E/WifiStateMachine(  823):  RSSI mgmt: -46
E/WifiStateMachine(  823):  BE :  rx=191 tx=126 lost=0 retries=1
E/WifiStateMachine(  823):  BK :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  823):  VI :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  823):  VO :  rx=6 tx=0 lost=0 retries=0
E/WifiStateMachine(  823):  on_time : 14739 tx_time=280 rx_time=555 scan_time=0
,D/ConnectivityService(  823): updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,W/AudioManagerAndroid( 3984): Requires BLUETOOTH permission
,I/NSApplication( 3984): Starting up...
,I/ActivityManager(  823): Start proc 4041:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
I/ActivityManager(  823): Killing 2435:android.process.acore/u0a5 (adj 15): empty #17
,E/native  (  823): do suspend false
,E/WifiStateMachine(  823): scanCount==0 - aborting
,I/dhcpcd  ( 4058): version 5.5.6 starting
,I/dhcpcd  ( 4058): wlan0: rebinding lease of 192.168.1.122
,I/ActivityManager(  823): Start proc 4067:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
I/ActivityManager(  823): Killing 3619:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,I/dhcpcd  ( 4058): wlan0: acknowledged 192.168.1.122 from 192.168.1.1
,I/dhcpcd  ( 4058): wlan0: leased 192.168.1.122 for 86400 seconds
,V/MusicLeanback( 3902): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/ActivityManager(  823): Killing 3639:com.android.musicfx/u0a18 (adj 15): empty #17
,D/SprintDMReceiver( 3959): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  823): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/SprintDMHelper( 3959): simOperator:  IMSI: null
,D/SprintDMReceiver( 3959): Not Sprint UICC, don't do anything.
D/ConnectivityService(  823): Adding iface wlan0 to network 101
,E/WifiStateMachine(  823): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,I/SystemUpdateService( 1805): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1805): onCreate
,D/SystemUpdateService( 1805): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1805): active receiver: enabled
,E/ConnectivityService(  823): Unexpected mtu value: 0, wlan0
,D/ConnectivityService(  823): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  823): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  823): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  823): Setting Dns servers for network 101 to [/192.168.1.1]
,I/SystemUpdateService( 1805): showing system update notification
,D/ConnectivityService(  823): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ChimeraCfgMgr( 1805): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ConnectivityService(  823): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  823): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  823):    accepting network in place of null
D/ConnectivityService(  823): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  823): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  823): Connected
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  823): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  823): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
,D/ConnectivityService(  823): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1073): CM callback handler got msg 524290
D/CSLegacyTypeTracker(  823): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  823): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  823): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ChimeraCfgMgr( 1805): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/Tethering(  823): MasterInitialState.processMessage what=3
,I/ValidateNoPeople(  823): skipping global notification
D/PhoneInterfaceManager( 1338): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1338): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
D/TelephonyManager(  823): getDataEnabled: retVal=false
,I/NetworkMonitor( 3902): type=WIFI subType= reason=null isConnected=true
,V/SystemUpdateService( 1805): retry (wakeup: false) in 3599956 ms
,E/GpsLocationProvider(  823): No APN found to select.
,D/SystemUpdateService( 1805): onDestroy
,V/MusicLeanback( 3902): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/GLSUser ( 1267): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1267): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1267): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1267): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/SprintDMReceiver( 3959): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,V/GLSActivity( 1267): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SprintDMHelper( 3959): simOperator:  IMSI: null
D/SprintDMReceiver( 3959): Not Sprint UICC, don't do anything.
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  823): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 18 Dec 2015 12:47:49 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1450442869137], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1450442869118]}
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  823): Validated
,D/ConnectivityService(  823): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null,
D/ConnectivityService(  823): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  823): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  823): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  823): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
I/SystemUpdateService( 1805): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
D/ConnectivityService(  823): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 1073): CM callback handler got msg 524290
,D/SystemUpdateService( 1805): onCreate
,D/SystemUpdateService( 1805): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) },
,I/SystemUpdateService( 1805): active receiver: enabled,
,W/Kids    ( 1805): [AccountUtils] Account not ready
W/Kids    ( 1805): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 1805): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 1805): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 1805): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 1805): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 1805): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 1805): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 1805): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 1805): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 1805): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 1805): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 1805): 	at java.lang.Thread.run(Thread.java:818)
,I/iu.Environment( 1805): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/SystemUpdateService( 1805): showing system update notification
,D/ChimeraCfgMgr( 1805): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/iu.UploadsManager( 1805): num queued entries: 0
I/iu.UploadsManager( 1805): num updated entries: 0
,I/ValidateNoPeople(  823): skipping global notification
,I/iu.SyncManager( 1805): NEXT; no task
,V/SystemUpdateService( 1805): retry (wakeup: false) in 3599965 ms
,I/jxcore-log( 3810): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3810): 
,D/SystemUpdateService( 1805): onDestroy
,I/Babel   ( 3869): connection state changed from DISCONNECTED to CONNECTED
,I/GLSUser ( 1267): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1267): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1267): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1267): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1267): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Kids    ( 1805): [AccountUtils] Account not ready
W/Kids    ( 1805): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 1805): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 1805): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 1805): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 1805): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 1805): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 1805): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 1805): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 1805): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 1805): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 1805): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 1805): 	at java.lang.Thread.run(Thread.java:818)
,V/Herrevad( 1805): NQAS connected
,D/GCM     ( 1267): Connected
,D/GCM     ( 1267): Message class com.google.f.a.a.p,
,D/ConnectivityService(  823): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/art     (  823): Explicit concurrent mark sweep GC freed 38938(1851KB) AllocSpace objects, 6(190KB) LOS objects, 32% free, 33MB/49MB, paused 2.733ms total 91.362ms
,I/MusicLeanback( 3902): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 3902): Stop autocaching.
,D/WearableService( 3372): callingUid 10011, callindPid: 3372
,E/GmsUtils( 3902): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 3902): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/jxcore-log( 3810): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3810): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 3810): BLE supported!!
I/jxcore-log( 3810): 
,E/WifiStateMachine(  823): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=16.88 rxSuccessRate=21.72 targetRoamBSSID=any RSSI=-46
E/WifiStateMachine(  823): WifiStateMachine L2Connected CMD_START_SCAN source -2 8, 10 -> obsolete
,E/WifiStateMachine(  823): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=9.94 rxSuccessRate=12.86 targetRoamBSSID=any RSSI=-46
E/WifiStateMachine(  823): WifiStateMachine L2Connected CMD_START_SCAN source -2 9, 10 -> obsolete
,I/jxcore-log( 3810): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3810): 
,V/GLSActivity( 1267): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1267): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1267): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1267): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1267): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1267): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3448): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3448): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3448): [1] 5.onFinished: Scheduling replication attempt 4.
,I/jxcore-log( 3810): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3810): 
,E/WifiStateMachine(  823): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=1.06 rxSuccessRate=3.93 targetRoamBSSID=any RSSI=-46
,I/jxcore-log( 3810): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3810): 
,I/PowerManagerService(  823): Going to sleep due to screen timeout (uid 1000)...
,I/Adreno  (  823): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/PermissionCache(  280): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (344 us)
,I/DisplayManagerService(  823): Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
D/SurfaceFlinger(  280): Set power mode=0, type=0 flinger=0xb6082000
D/qdhwcomposer(  280): hwc_setPowerMode: Setting mode 0 on display: 0
V/ActivityManager(  823): Display changed displayId=0
,I/qdhwcomposer(  280): handle_blank_event: dpy:0 panel power state: 0
,D/qdhwcomposer(  280): hwc_setPowerMode: Done setting mode 0 on display 0
,D/SurfaceControl(  823): Excessive delay in setPowerMode(): 248ms
,I/DreamManagerService(  823): Entering dreamland.
I/PowerManagerService(  823): Dozing...
I/DreamController(  823): Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,D/audio_hw_primary(  359): adev_set_parameters: enter: screen_state=on
,D/mot_vr_audio_hw(  359): adev_set_parameters: screen_state=on
,E/WifiStateMachine(  823): cancelDelayedScan -> 12,
,E/native  (  823): do suspend false
,I/art     ( 1267): Explicit concurrent mark sweep GC freed 23960(1340KB) AllocSpace objects, 6(661KB) LOS objects, 37% free, 26MB/42MB, paused 2.229ms total 95.646ms
,D/HeadsetStateMachine( 2140): Disconnected process message: 10, size: 0
,I/Keyboard.Facilitator( 1241): onFinishInput()
,E/WifiStateMachine(  823): cancelDelayedScan -> 14
,I/GLSUser ( 1267): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1267): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1267): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1267): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
E/native  (  823): do suspend true
,V/GLSActivity( 1267): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3217): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3217): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3217): 	at jdm.a(PG:82)
E/HttpOperation( 3217): 	at jcs.o(PG:406)
E/HttpOperation( 3217): 	at jcn.a(PG:1379)
E/HttpOperation( 3217): 	at jcs.i(PG:143)
E/HttpOperation( 3217): 	at blb.a(PG:3937)
E/HttpOperation( 3217): 	at czp.a(PG:18188)
E/HttpOperation( 3217): 	at czp.a(PG:9081)
E/HttpOperation( 3217): 	at czq.run(PG:1686)
E/HttpOperation( 3217): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3217): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3217): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3217): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3217): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3217): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3217): 	at jdj.a(PG:4091)
E/HttpOperation( 3217): 	at jdj.a(PG:1125)
E/HttpOperation( 3217): 	at jdm.a(PG:77)
E/HttpOperation( 3217): 	... 12 more
E/HttpOperation( 3217): Caused by: faj: BadAuthentication
E/HttpOperation( 3217): 	at fal.a(PG:38)
E/HttpOperation( 3217): 	at jdj.a(PG:4089)
E/HttpOperation( 3217): 	... 14 more
,I/GLSUser ( 1267): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1267): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1267): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1267): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1267): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3217): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3217): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3217): 	at jdm.a(PG:82)
E/HttpOperation( 3217): 	at jcs.o(PG:406)
E/HttpOperation( 3217): 	at jcn.a(PG:1379)
E/HttpOperation( 3217): 	at jcs.i(PG:143)
E/HttpOperation( 3217): 	at hec.a(PG:42)
E/HttpOperation( 3217): 	at hee.a(PG:102)
E/HttpOperation( 3217): 	at czr.a(PG:65)
E/HttpOperation( 3217): 	at kka.a(PG:108)
E/HttpOperation( 3217): 	at czp.a(PG:19176)
E/HttpOperation( 3217): 	at czp.a(PG:9081)
E/HttpOperation( 3217): 	at czq.run(PG:1686)
E/HttpOperation( 3217): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3217): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3217): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3217): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3217): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3217): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3217): 	at jdj.a(PG:4091)
E/HttpOperation( 3217): 	at jdj.a(PG:1125)
E/HttpOperation( 3217): 	at jdm.a(PG:77)
E/HttpOperation( 3217): 	... 15 more
E/HttpOperation( 3217): Caused by: faj: BadAuthentication
E/HttpOperation( 3217): 	at fal.a(PG:38)
E/HttpOperation( 3217): 	at jdj.a(PG:4089)
E/HttpOperation( 3217): 	... 17 more
E/ExperimentLoader( 3217): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3217): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3217): 	at jdm.a(PG:82)
E/ExperimentLoader( 3217): 	at jcs.o(PG:406)
E/ExperimentLoader( 3217): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3217): 	at jcs.i(PG:143)
E/ExperimentLoader( 3217): 	at hec.a(PG:42)
E/ExperimentLoader( 3217): 	at hee.a(PG:102)
E/ExperimentLoader( 3217): 	at czr.a(PG:65)
E/ExperimentLoader( 3217): 	at kka.a(PG:108)
E/ExperimentLoader( 3217): 	at czp.a(PG:19176)
E/ExperimentLoader( 3217): 	at czp.a(PG:9081)
E/ExperimentLoader( 3217): 	at czq.run(PG:1686)
E/ExperimentLoader( 3217): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3217): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3217): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3217): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3217): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3217): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3217): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3217): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3217): 	at jdm.a(PG:77)
E/ExperimentLoader( 3217): 	... 15 more
E/ExperimentLoader( 3217): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3217): 	at fal.a(PG:38)
E/ExperimentLoader( 3217): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3217): 	... 17 more
,D/audio_hw_primary(  359): adev_set_parameters: enter: screen_state=off
D/mot_vr_audio_hw(  359): adev_set_parameters: screen_state=off
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 163497, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,E/WifiStateMachine(  823): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-46
E/WifiStateMachine(  823): WifiStateMachine L2Connected CMD_START_SCAN source -2 13, 14 -> obsolete
,I/jxcore-log( 3810): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3810): 
,V/GLSActivity( 1267): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1267): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1267): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1267): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1267): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1267): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3448): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3448): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3448): [1] 5.onFinished: Scheduling replication attempt 5.
,I/jxcore-log( 3810): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3810): 
,E/WifiStateMachine(  823): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-46
E/WifiStateMachine(  823): WifiStateMachine L2Connected CMD_START_SCAN source -2 11, 14 -> obsolete
,I/jxcore-log( 3810): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3810): 
,D/HeadsetStateMachine( 2140): Disconnected process message: 10, size: 0
,V/GLSActivity( 1267): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1267): Vacuum at: now=1450442921085 tag=VacuumService
,V/GoogleAuthProtoRequest( 3931): [425] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1267): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1267): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1267): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1267): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1267): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3931): [425] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3931): [425] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3931): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3931): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3931): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3931): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3931): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3931): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3931): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3931): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3931): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3931): 	at com.a.a.k.run(SourceFile:110)
,I/GoogleURLConnFactory( 1267): Using platform SSLCertificateSocketFactory
,W/Uploader( 1267): No account for auth token provided,
,I/GLSUser ( 1267): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1267): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1267): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1267): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1267): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1267): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1267): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1267): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1267): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1267): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1267): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1267): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1267): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1267): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1267): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1267): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1267): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1267): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1267): No account for auth token provided
,W/Uploader( 1267): No account for auth token provided
,I/GLSUser ( 1267): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1267): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1267): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1267): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1267): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1267): Failed to get auth token: User intervention required. Notification has been pushed.,
E/Uploader( 1267): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1267): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1267): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1267): 	at com.google.android.gms.auth.p.c(SourceFile:550)
,E/Uploader( 1267): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1267): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1267): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1267): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1267): ,	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1267): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1267): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1267): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1267): No account for auth token provided
,W/Uploader( 1267): No account for auth token provided
,W/Uploader( 1267): No account for auth token provided
,I/jxcore-log( 3810): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3810): 
,V/GLSActivity( 1267): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Uploader( 1267): No account for auth token provided
,I/GLSUser ( 1267): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1267): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1267): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1267): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1267): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3448): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3448): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3448): [1] 5.onFinished: Giving up after 6 failures.
,W/Uploader( 1267): No account for auth token provided
,I/GLSUser ( 1267): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1267): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1267): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1267): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1267): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  823): Explicit concurrent mark sweep GC freed 40491(1952KB) AllocSpace objects, 7(300KB) LOS objects, 31% free, 34MB/50MB, paused 1.528ms total 101.660ms
,E/Uploader( 1267): Failed to get auth token: User intervention required. Notification has been pushed.,
E/Uploader( 1267): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1267): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1267): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1267): 	at com.google.android.gms.auth.p.c(SourceFile:550)
,E/Uploader( 1267): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1267): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1267): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1267): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263),
E/Uploader( 1267): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1267): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1267): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1267): 	at com.google.android.gms.gcm.am.run(SourceFile:135),
,W/Uploader( 1267): No account for auth token provided
,W/Uploader( 1267): No account for auth token provided
,W/Uploader( 1267): No account for auth token provided
,W/Uploader( 1267): No account for auth token provided,
,W/Uploader( 1267): No account for auth token provided
,W/Uploader( 1267): No account for auth token provided,
,W/Uploader( 1267):  no longer exists, so no auth token.,
,I/GLSUser ( 1267): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog,
I/GLSUser ( 1267): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1267): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1267): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1267): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1267): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1267): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1267): ,	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1267): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1267): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1267): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1267): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1267): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337),
E/Uploader( 1267): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1267): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1267): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1267): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
,E/Uploader( 1267): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/GLSUser ( 1267): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1267): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1267): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1267): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1267): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1267): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1267): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1267): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1267): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1267): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1267): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1267): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1267): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1267): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1267): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1267): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1267): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1267): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/BooksSync( 3716): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3716): GmsCore Version = 7.8.99 (2134222-430)
,V/KeepSync( 3749): Connecting to GoogleApiClient
,I/GLSUser ( 1267): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1267): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1267): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1267): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1267): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1267): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1267): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1267): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1267): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1267): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1805): Handling authorization failure,
E/ClientConnectionOperation( 1805): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
,E/ClientConnectionOperation( 1805): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.common.service.g.run(SourceFile:178),
E/ClientConnectionOperation( 1805): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1805): ,	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1805): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1805): Caused by: com.google.android.gms.auth.ad: BadAuthentication
,E/ClientConnectionOperation( 1805): 	,at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1805): 	,at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1805): 	,at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1805): 	,at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1805): 	... 7 more
,V/KeepSync( 3749): GoogleApiClient failed to connect with error code: 4
E/SQLiteLog( 3749): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3749): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3749): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1267): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1267): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1267): [GLSUser] Extracting token using key: Auth,
W/GLSActivity( 1267): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1267): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3716): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3716): Soft error
E/BooksSync( 3716): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3716): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3716): Sync error
E/BooksSync( 3716): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3716): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3716): Finished books sync
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 164944, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1267): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1267): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1267): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1267): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1267): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3749): IOException
E/KeepSync( 3749): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3749): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3749): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3749): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3749): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3749): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3749): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3749): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3749): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3749): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3749): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3749): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3749): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3749): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3749): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3749): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3749): 	... 10 more
W/KeepSync( 3749): Sync result 2
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 170047, reason: 10079, SyncResult: stats [ numIoExceptions: 1],
,I/jxcore-log( 3810): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): DBG, CoordinatorConnector connect_error called
,I/jxcore-log( 3810): 
,I/jxcore-log( 3810): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3810): 
,V/GoogleAuthProtoRequest( 3931): [426] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1267): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1267): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1267): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1267): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1267): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3931): [426] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3931): [426] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3931): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3931): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3931): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3931): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3931): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3931): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3931): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3931): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3931): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3931): 	at com.a.a.k.run(SourceFile:110)
,I/Keyboard.Facilitator.LanguageModelFlusher( 1241): run()
,I/Keyboard.Facilitator( 1241): flushDynamicLanguageModels()
,I/GLSUser ( 1267): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1267): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1267): [GLSUser] Extracting token using key: Auth,
W/GLSActivity( 1267): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,V/GLSActivity( 1267): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/HeadsetStateMachine( 2140): Disconnected process message: 10, size: 0
,I/art     ( 1267): Explicit concurrent mark sweep GC freed 68354(3MB) AllocSpace objects, 6(580KB) LOS objects, 36% free, 27MB/43MB, paused 1.560ms total 59.107ms,
,I/ConfigService( 1267): onCreate
,E/HttpOperation( 3217): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3217): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3217): 	at jdm.a(PG:82)
E/HttpOperation( 3217): 	at jcs.o(PG:406)
E/HttpOperation( 3217): 	at jcn.a(PG:1379)
E/HttpOperation( 3217): 	at jcs.i(PG:143)
E/HttpOperation( 3217): 	at blb.a(PG:3937)
E/HttpOperation( 3217): 	at czp.a(PG:18188)
E/HttpOperation( 3217): 	at czp.a(PG:9081)
E/HttpOperation( 3217): 	at czq.run(PG:1686)
E/HttpOperation( 3217): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3217): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3217): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3217): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3217): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3217): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3217): 	at jdj.a(PG:4091)
E/HttpOperation( 3217): 	at jdj.a(PG:1125)
E/HttpOperation( 3217): 	at jdm.a(PG:77)
E/HttpOperation( 3217): 	... 12 more
E/HttpOperation( 3217): Caused by: faj: BadAuthentication
E/HttpOperation( 3217): 	at fal.a(PG:38)
E/HttpOperation( 3217): 	at jdj.a(PG:4089)
E/HttpOperation( 3217): 	... 14 more
,I/GLSUser ( 1267): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native,
I/GLSUser ( 1267): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1267): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1267): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1267): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3217): [getmobileexperiments] Unexpected exception,
E/HttpOperation( 3217): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3217): 	at jdm.a(PG:82)
E/HttpOperation( 3217): ,	at jcs.o(PG:406)
E/HttpOperation( 3217): 	,at jcn.a(PG:1379)
E/HttpOperation( 3217): 	at jcs.i(PG:143)
E/HttpOperation( 3217): ,	at hec.a(PG:42)
E/HttpOperation( 3217): 	at hee.a(PG:102)
,E/HttpOperation( 3217): 	at czr.a(PG:65)
E/HttpOperation( 3217): 	at kka.a(PG:108),
E/HttpOperation( 3217): 	at czp.a(PG:19176)
E/HttpOperation( 3217): ,	at czp.a(PG:9081)
E/HttpOperation( 3217): ,	at czq.run(PG:1686)
E/HttpOperation( 3217): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3217): ,	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3217): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3217): 	,at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3217): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3217): Caused by: android.accounts.AuthenticatorException: Recoverable error,
E/HttpOperation( 3217): 	at jdj.a(PG:4091)
E/HttpOperation( 3217): 	at jdj.a(PG:1125)
E/HttpOperation( 3217): 	at jdm.a(PG:77)
E/HttpOperation( 3217): 	... 15 more
E/HttpOperation( 3217): Caused by: faj: BadAuthentication
E/HttpOperation( 3217): 	at fal.a(PG:38)
E/HttpOperation( 3217): 	at jdj.a(PG:4089)
E/HttpOperation( 3217): 	... 17 more
,E/ExperimentLoader( 3217): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3217): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3217): 	at jdm.a(PG:82)
E/ExperimentLoader( 3217): 	at jcs.o(PG:406)
E/ExperimentLoader( 3217): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3217): 	at jcs.i(PG:143)
E/ExperimentLoader( 3217): 	at hec.a(PG:42)
E/ExperimentLoader( 3217): 	at hee.a(PG:102)
E/ExperimentLoader( 3217): 	at czr.a(PG:65)
E/ExperimentLoader( 3217): 	at kka.a(PG:108)
E/ExperimentLoader( 3217): 	at czp.a(PG:19176)
E/ExperimentLoader( 3217): 	at czp.a(PG:9081)
E/ExperimentLoader( 3217): 	at czq.run(PG:1686)
E/ExperimentLoader( 3217): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3217): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3217): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3217): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3217): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3217): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3217): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3217): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3217): 	at jdm.a(PG:77)
E/ExperimentLoader( 3217): 	... 15 more
E/ExperimentLoader( 3217): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3217): 	at fal.a(PG:38)
E/ExperimentLoader( 3217): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3217): 	... 17 more
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 194848, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,I/jxcore-log( 3810): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3810): 
,I/ConfigService( 1267): onDestroy
,I/jxcore-log( 3810): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3810): 
,D/HeadsetStateMachine( 2140): Disconnected process message: 10, size: 0
,I/jxcore-log( 3810): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3810): 
,I/BooksSync( 3716): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3716): GmsCore Version = 7.8.99 (2134222-430)
,V/KeepSync( 3749): Connecting to GoogleApiClient
,I/GLSUser ( 1267): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1267): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1267): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1267): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1267): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1267): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1267): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1267): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1267): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1267): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1805): Handling authorization failure
E/ClientConnectionOperation( 1805): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1805): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1805): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1805): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1805): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1805): 	... 7 more
,V/KeepSync( 3749): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3749): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3749): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3749): (284) automatic index on blob_node(is_deleted)
,I/art     (  823): Explicit concurrent mark sweep GC freed 32236(1393KB) AllocSpace objects, 6(284KB) LOS objects, 31% free, 34MB/50MB, paused 2.501ms total 72.591ms
,I/GLSUser ( 1267): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1267): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1267): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1267): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1267): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3716): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3716): Soft error
E/BooksSync( 3716): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3716): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3716): Sync error
E/BooksSync( 3716): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3716): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3716): Finished books sync
,I/GLSUser ( 1267): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1267): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1267): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1267): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1267): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 226403, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,E/KeepSync( 3749): IOException
E/KeepSync( 3749): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3749): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3749): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3749): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3749): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3749): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3749): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3749): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3749): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3749): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3749): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3749): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3749): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3749): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3749): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3749): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3749): 	... 10 more
W/KeepSync( 3749): Sync result 2
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 227016, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,I/jxcore-log( 3810): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): DBG, CoordinatorConnector connect_error called
,I/jxcore-log( 3810): 
,D/HeadsetStateMachine( 2140): Disconnected process message: 10, size: 0
,I/jxcore-log( 3810): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3810): 
,D/HeadsetStateMachine( 2140): Disconnected process message: 10, size: 0
,I/jxcore-log( 3810): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3810): 
,V/GoogleAuthProtoRequest( 3931): [427] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1267): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1267): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1267): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1267): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1267): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3931): [427] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3931): [427] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3931): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3931): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3931): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3931): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3931): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3931): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3931): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3931): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3931): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3931): 	at com.a.a.k.run(SourceFile:110)
,I/GLSUser ( 1267): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1267): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1267): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1267): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1267): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3217): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3217): java.io.IOException: Cannot obtain authentication token
,E/HttpOperation( 3217): 	at jdm.a(PG:82)
E/HttpOperation( 3217): 	at jcs.o(PG:406)
E/HttpOperation( 3217): 	at jcn.a(PG:1379)
E/HttpOperation( 3217): 	at jcs.i(PG:143)
E/HttpOperation( 3217): 	at blb.a(PG:3937)
E/HttpOperation( 3217): 	,at czp.a(PG:18188)
E/HttpOperation( 3217): 	at czp.a(PG:9081)
E/HttpOperation( 3217): 	at czq.run(PG:1686)
E/HttpOperation( 3217): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3217): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3217): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3217): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587),
E/HttpOperation( 3217): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3217): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3217): 	at jdj.a(PG:4091)
E/HttpOperation( 3217): 	at jdj.a(PG:1125)
E/HttpOperation( 3217): 	at jdm.a(PG:77)
E/HttpOperation( 3217): 	... 12 more
E/HttpOperation( 3217): Caused by: faj: BadAuthentication
E/HttpOperation( 3217): 	,at fal.a(PG:38)
E/HttpOperation( 3217): 	at jdj.a(PG:4089)
E/HttpOperation( 3217): 	... 14 more
,I/GLSUser ( 1267): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1267): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1267): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1267): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1267): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3217): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3217): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3217): 	at jdm.a(PG:82)
E/HttpOperation( 3217): 	at jcs.o(PG:406)
E/HttpOperation( 3217): 	at jcn.a(PG:1379)
E/HttpOperation( 3217): 	at jcs.i(PG:143)
E/HttpOperation( 3217): 	at hec.a(PG:42)
E/HttpOperation( 3217): 	at hee.a(PG:102)
E/HttpOperation( 3217): 	at czr.a(PG:65)
E/HttpOperation( 3217): 	at kka.a(PG:108)
E/HttpOperation( 3217): 	at czp.a(PG:19176)
E/HttpOperation( 3217): 	at czp.a(PG:9081)
E/HttpOperation( 3217): 	at czq.run(PG:1686)
E/HttpOperation( 3217): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3217): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3217): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3217): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3217): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3217): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3217): 	at jdj.a(PG:4091)
E/HttpOperation( 3217): 	at jdj.a(PG:1125)
E/HttpOperation( 3217): 	at jdm.a(PG:77)
E/HttpOperation( 3217): 	... 15 more
E/HttpOperation( 3217): Caused by: faj: BadAuthentication
E/HttpOperation( 3217): 	at fal.a(PG:38)
E/HttpOperation( 3217): 	at jdj.a(PG:4089)
E/HttpOperation( 3217): 	... 17 more
,E/ExperimentLoader( 3217): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3217): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3217): 	at jdm.a(PG:82)
E/ExperimentLoader( 3217): 	at jcs.o(PG:406)
E/ExperimentLoader( 3217): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3217): 	at jcs.i(PG:143)
E/ExperimentLoader( 3217): 	at hec.a(PG:42)
E/ExperimentLoader( 3217): 	at hee.a(PG:102)
E/ExperimentLoader( 3217): 	at czr.a(PG:65)
E/ExperimentLoader( 3217): 	at kka.a(PG:108)
E/ExperimentLoader( 3217): 	at czp.a(PG:19176)
E/ExperimentLoader( 3217): 	at czp.a(PG:9081)
E/ExperimentLoader( 3217): 	at czq.run(PG:1686)
E/ExperimentLoader( 3217): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3217): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3217): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3217): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
,E/ExperimentLoader( 3217): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3217): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3217): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3217): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3217): 	at jdm.a(PG:77)
E/ExperimentLoader( 3217): 	... 15 more
E/ExperimentLoader( 3217): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3217): 	at fal.a(PG:38)
E/ExperimentLoader( 3217): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3217): 	... 17 more
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 285628, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,I/jxcore-log( 3810): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3810): 
,I/BooksSync( 3716): Starting books sync for 61035162, extras: ade
,V/KeepSync( 3749): Connecting to GoogleApiClient
,I/BooksConfig( 3716): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1267): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1267): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1267): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1267): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/HeadsetStateMachine( 2140): Disconnected process message: 10, size: 0
V/GLSActivity( 1267): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1267): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1267): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1267): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1267): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1267): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1805): Handling authorization failure
E/ClientConnectionOperation( 1805): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1805): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1805): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1805): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1805): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1805): 	... 7 more
,V/KeepSync( 3749): GoogleApiClient failed to connect with error code: 4
E/SQLiteLog( 3749): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3749): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3749): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1267): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1267): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1267): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1267): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1267): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3716): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3716): Soft error
E/BooksSync( 3716): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3716): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3716): Sync error
E/BooksSync( 3716): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3716): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3716): Finished books sync
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 319067, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1267): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive,
I/GLSUser ( 1267): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1267): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1267): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1267): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/KeepSync( 3749): IOException
E/KeepSync( 3749): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3749): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3749): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3749): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3749): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3749): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3749): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3749): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3749): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3749): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3749): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3749): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3749): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3749): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3749): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3749): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3749): 	... 10 more
,W/KeepSync( 3749): Sync result 2
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 320157, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,D/WifiService(  823): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@20cfb2f2}
,E/WifiStateMachine(  823): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-46
,D/WifiService(  823): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@20cfb2f2}
,E/LocSvc_IzatApiV02(  823): E/virtual int izat_core::IzatApiV02::injectLocation(GpsExtLocation):857]: error! inject position failed
,I/jxcore-log( 3810): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3810): ,
,I/jxcore-log( 3810): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3810): 
,V/GLSActivity( 1267): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1267): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1267): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1267): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1267): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1267): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/GLSActivity( 1267): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1267): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1267): 	at com.google.android.gms.auth.p.d(SourceFile:599)
,W/GLSActivity( 1267): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1267): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1267): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1267): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 3448): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3448): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3448): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 3448): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3448): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/PlayEventLogger( 3448): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3448): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 3448): Ignoring header User-Agent because its value was null.
,I/jxcore-log( 3810): DBG, CoordinatorConnector connect called
I/jxcore-log( 3810): 
I/jxcore-log( 3810): Coordinator is now connected to the server!
I/jxcore-log( 3810): 
,I/chromium( 3810): [INFO:CONSOLE(63)] "logCallback connected to server", source: file:///android_asset/www/js/thali_main.js (63)
,D/HeadsetStateMachine( 2140): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2140): Disconnected process message: 10, size: 0
,V/GoogleAuthProtoRequest( 3931): [428] a.<init>: mAccountName set to: thalitester@gmail.com
,I/art     (  823): Explicit concurrent mark sweep GC freed 33825(1541KB) AllocSpace objects, 16(821KB) LOS objects, 31% free, 34MB/50MB, paused 1.542ms total 65.558ms
,I/GLSUser ( 1267): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1267): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1267): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1267): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1267): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3931): [428] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3931): [428] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3931): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3931): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3931): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3931): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3931): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3931): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3931): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3931): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3931): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3931): 	at com.a.a.k.run(SourceFile:110)
,I/art     ( 1267): Explicit concurrent mark sweep GC freed 50201(2MB) AllocSpace objects, 17(1874KB) LOS objects, 36% free, 27MB/43MB, paused 1.847ms total 55.743ms
,I/GLSUser ( 1267): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1267): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1267): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1267): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1267): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3217): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3217): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3217): 	at jdm.a(PG:82)
E/HttpOperation( 3217): 	at jcs.o(PG:406)
E/HttpOperation( 3217): 	at jcn.a(PG:1379)
E/HttpOperation( 3217): 	at jcs.i(PG:143)
E/HttpOperation( 3217): 	at blb.a(PG:3937)
E/HttpOperation( 3217): 	at czp.a(PG:18188)
E/HttpOperation( 3217): 	at czp.a(PG:9081)
E/HttpOperation( 3217): 	at czq.run(PG:1686)
E/HttpOperation( 3217): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3217): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3217): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3217): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3217): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3217): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3217): 	at jdj.a(PG:4091)
E/HttpOperation( 3217): 	at jdj.a(PG:1125)
E/HttpOperation( 3217): 	at jdm.a(PG:77)
E/HttpOperation( 3217): 	... 12 more
E/HttpOperation( 3217): Caused by: faj: BadAuthentication
E/HttpOperation( 3217): 	at fal.a(PG:38)
E/HttpOperation( 3217): 	at jdj.a(PG:4089)
E/HttpOperation( 3217): 	... 14 more
,I/GLSUser ( 1267): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1267): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1267): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1267): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1267): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3217): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3217): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3217): 	at jdm.a(PG:82)
E/HttpOperation( 3217): 	at jcs.o(PG:406)
E/HttpOperation( 3217): 	at jcn.a(PG:1379)
E/HttpOperation( 3217): 	at jcs.i(PG:143)
E/HttpOperation( 3217): 	at hec.a(PG:42)
E/HttpOperation( 3217): 	at hee.a(PG:102)
E/HttpOperation( 3217): 	at czr.a(PG:65)
E/HttpOperation( 3217): 	at kka.a(PG:108)
E/HttpOperation( 3217): 	at czp.a(PG:19176)
E/HttpOperation( 3217): 	at czp.a(PG:9081)
E/HttpOperation( 3217): 	at czq.run(PG:1686)
E/HttpOperation( 3217): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3217): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3217): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3217): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3217): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3217): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3217): 	at jdj.a(PG:4091)
E/HttpOperation( 3217): 	at jdj.a(PG:1125)
E/HttpOperation( 3217): 	at jdm.a(PG:77)
E/HttpOperation( 3217): 	... 15 more
E/HttpOperation( 3217): Caused by: faj: BadAuthentication
E/HttpOperation( 3217): 	at fal.a(PG:38)
E/HttpOperation( 3217): 	at jdj.a(PG:4089)
E/HttpOperation( 3217): 	... 17 more
,E/ExperimentLoader( 3217): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3217): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3217): 	at jdm.a(PG:82)
E/ExperimentLoader( 3217): 	at jcs.o(PG:406)
E/ExperimentLoader( 3217): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3217): 	at jcs.i(PG:143)
E/ExperimentLoader( 3217): 	at hec.a(PG:42)
E/ExperimentLoader( 3217): 	at hee.a(PG:102)
E/ExperimentLoader( 3217): 	at czr.a(PG:65)
E/ExperimentLoader( 3217): 	at kka.a(PG:108)
E/ExperimentLoader( 3217): 	at czp.a(PG:19176)
E/ExperimentLoader( 3217): 	at czp.a(PG:9081)
,E/ExperimentLoader( 3217): 	at czq.run(PG:1686)
E/ExperimentLoader( 3217): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3217): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3217): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3217): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3217): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3217): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3217): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3217): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3217): 	,at jdm.a(PG:77)
E/ExperimentLoader( 3217): 	... 15 more
E/ExperimentLoader( 3217): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3217): 	at fal.a(PG:38)
E/ExperimentLoader( 3217): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3217): 	... 17 more
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 437475, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2140): Disconnected process message: 10, size: 0
,I/jxcore-log( 3810): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): DBG, CoordinatorConnector command called
I/jxcore-log( 3810): 
I/jxcore-log( 3810): command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":20000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":16,"addressList":[{"address":"90:E7:C4:F6:69:77","tryCount":0},{"address":"34:FC:EF:11:AE:67","tryCount":0},{"address":"58:3F:54:73:64:C0","tryCount":0},{"address":"08:EC:A9:50:75:41","tryCount":0},{"address":"E0:DB:10:14:E2:C0","tryCount":0},{"address":"B0:C5:59:3F:75:69","tryCount":0},{"address":"44:80:EB:7B:5A:05","tryCount":0},{"address":"F8:95:C7:87:3C:51","tryCount":0},{"address":"7C:F9:0E:37:96:AB","tryCount":0},{"address":"7C:F9:0E:34:8A:A0","tryCount":0},{"address":"E0:DB:10:1F:C9:5E","tryCount":0},{"address":"7C:F9:0E:51:18:22","tryCount":0},{"address":"F8:95:C7:87:85:54","tryCount":0},{"address":"08:EC:A9:50:76:27","tryCount":0},{"address":"00:F4:6F:30:E0:6C","tryCount":0},{"address":"F4:F1:E1:5C:3B:E2","tryCount":0}]}
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): Start now : testSendData.js,
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 16
I/jxcore-log( 3810): ,
,I/jxcore-log( 3810): check server
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): serverPort is 41534
I/jxcore-log( 3810): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): setDiscoveryMode: Mode set to WIFI
,D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3810): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: motorola-Nexus 6_PT9351
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3810): bind: Binding a new listener
D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3810): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3810): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT9351","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3810): setConnectionTimeout: 15000
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3810): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3810): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3810): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3810): setState: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3810): start: OK
I/io.jxcore.node.ConnectionHelper( 3810): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: motorola-Nexus 6_PT9351
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3810): Waiting for incoming connections...
,D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0,
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3810): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT9351","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3810): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT9351","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3810): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT9351","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3810): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3810): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): startWifiPeerDiscovery: Wi-Fi Direct OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 3810): start: OK
,I/jxcore-log( 3810): StartBroadcasting started ok
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): do fake peer & start
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): Connect to fake peer: 08:EC:A9:50:76:27
I/jxcore-log( 3810): 
I/jxcore-log( 3810): 2015-12-18T12:53:32.216Z SendDataConnector.js: Start called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:32.217Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3810): 
I/jxcore-log( 3810): 2015-12-18T12:53:32.218Z SendDataConnector.js: do connect now
I/jxcore-log( 3810): 
I/io.jxcore.node.ConnectionHelper( 3810): connect: Trying to connect to peer with ID 08:EC:A9:50:76:27
D/io.jxcore.node.ConnectionHelper( 3810): hasConnection: No connection with peer with ID 08:EC:A9:50:76:27
W/io.jxcore.node.ConnectionHelper( 3810): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3810): connect: [08:EC:A9:50:76:27 08:EC:A9:50:76:27]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3810): connect: Trying to start connecting to null in address 08:EC:A9:50:76:27
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3810): setInsecureRfcommSocketPort: Using port -1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3810): setMaxNumberOfRetries: 0,
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3810): onConnecting: null 08:EC:A9:50:76:27
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3810): connect: Started connecting to null in address 08:EC:A9:50:76:27
I/io.jxcore.node.ConnectionHelper( 3810): connect: Connection process successfully started (peer ID: 08:EC:A9:50:76:27)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3810): Trying to connect to peer with address 08:EC:A9:50:76:27 (thread ID: 423)
W/BluetoothAdapter( 3810): getBluetoothService() called with no BluetoothManagerCallback
,I/jxcore-log( 3810): 2015-12-18T12:53:32.234Z SendDataTCPServer.js: TCP/IP server is bound to port: 41534
I/jxcore-log( 3810): 
I/chromium( 3810): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
I/io.jxcore.node.ConnectionHelper( 3810): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onWifiStateChanged: State changed to 2
I/io.jxcore.node.ConnectionHelper( 3810): onDiscoveryManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3810): Local service added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3810): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3810): setState: STARTED
D/BTIF_SOCK( 2140): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3810): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,W/bt-btif ( 2140): info:x10,
D/        ( 2140): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
E/BluetoothRemoteDevices( 2140): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2140): process_service_search_attr_rsp,
,E/bt-btif ( 2140): DISCOVERY_COMP_EVT slot id:5, failed to find channle,                                       status:1, scn:0,
W/bt-btif ( 2140): invalid rfc slot id: 5,
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3810): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 423)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3810): Maximum number of allowed retries (0) reached, giving up... (thread ID: 423)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3810): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3810): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [08:EC:A9:50:76:27 08:EC:A9:50:76:27]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3810): Exiting thread (thread ID: 423)
,I/jxcore-log( 3810): 2015-12-18T12:53:32.558Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [08:EC:A9:50:76:27 08:EC:A9:50:76:27] failed
I/jxcore-log( 3810): 
I/jxcore-log( 3810): 2015-12-18T12:53:32.559Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [08:EC:A9:50:76:27 08:EC:A9:50:76:27] failed
I/jxcore-log( 3810): 
I/jxcore-log( 3810): 2015-12-18T12:53:32.560Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3810): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3810): setInsecureRfcommSocketPort: Will use port 1 when trying to connect
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3810): shutdown (thread ID: 423)
,W/bt-btif ( 2140): info:x10
,D/        ( 2140): remote version info [34:fc:ef:11:ae:67]: 7, f, 6109
E/BluetoothRemoteDevices( 2140): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 2140): tBTM_SEC_DEV:0xa2fd607c rs_disc_pending=1
W/bt-btif ( 2140): bta_dm_check_av:0
W/bt-btif ( 2140): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2140): tBTM_SEC_DEV:0xa2fd5eb4 rs_disc_pending=0
W/bt-btif ( 2140): bta_dm_check_av:0
W/bt-btif ( 2140): btif_dm_cback : unhandled event (14)
,D/btif_config( 2140): btif_get_device_type: Device [34:fc:ef:11:ae:67] type 1
,I/BluetoothBondStateMachine( 2140): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:AE:67 newState: 1
,E/bt-btif ( 2140): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2140): Bond State Change Intent:34:FC:EF:11:AE:67 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2140): Entering PendingCommandState State
,I/ActivityManager(  823): Start proc 4271:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.BluetoothPairingRequest
,I/art     (  370): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 354us total 16.974ms
,I/art     (  370): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 348us total 14.914ms
,I/art     (  370): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 1.103ms total 15.292ms
,D/BluetoothManagerService(  823): Message: 20
D/BluetoothManagerService(  823): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@18dd17d6:true
,I/ActivityManager(  823): Killing 3670:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,I/BluetoothBondStateMachine( 2140): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:AE:67 newState: 0
,D/BluetoothAdapterProperties( 2140): Failed to remove device: 34:FC:EF:11:AE:67,
,I/BluetoothBondStateMachine( 2140): Bond State Change Intent:34:FC:EF:11:AE:67 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2140): StableState(): Entering Off State
,W/bt-btif ( 2140): info:x10
D/        ( 2140): remote version info [b0:c5:59:3f:75:69]: 7, f, 610c
E/BluetoothRemoteDevices( 2140): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 2140): tBTM_SEC_DEV:0xa2fd5eb4 rs_disc_pending=1
W/bt-btif ( 2140): bta_dm_check_av:0
,W/bt-btif ( 2140): btif_dm_cback : unhandled event (14)
,D/btif_config( 2140): btif_get_device_type: Device [b0:c5:59:3f:75:69] type 1
,I/BluetoothBondStateMachine( 2140): bondStateChangeCallback: Status: 0 Address: B0:C5:59:3F:75:69 newState: 1
,E/bt-btif ( 2140): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2140): Bond State Change Intent:B0:C5:59:3F:75:69 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 2140): Entering PendingCommandState State
,E/bt-btm  ( 2140): tBTM_SEC_DEV:0xa2fd607c rs_disc_pending=0
W/bt-btif ( 2140): bta_dm_check_av:0
,W/bt-btif ( 2140): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2140): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2140): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 2140): bondStateChangeCallback: Status: 0 Address: B0:C5:59:3F:75:69 newState: 0
,D/BluetoothAdapterProperties( 2140): Failed to remove device: B0:C5:59:3F:75:69
,I/BluetoothBondStateMachine( 2140): Bond State Change Intent:B0:C5:59:3F:75:69 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2140): StableState(): Entering Off State
,W/bt-btif ( 2140): new conn_srvc id:26, app_id:255
W/bt-btif ( 2140): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2140): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3810): Incoming connection accepted
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3810): Incoming connection initialized (thread ID: 425)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3810): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3810): Entering thread (ID: 425)
,E/bt-btm  ( 2140): tBTM_SEC_DEV:0xa2fd607c rs_disc_pending=1
,W/bt-btif ( 2140): bta_dm_check_av:0
W/bt-btif ( 2140): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2140): new conn_srvc id:26, app_id:255
,W/bt-btif ( 2140): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2140): bta_dm_pm_ssr:2, lat:1200
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3810): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3810): Incoming connection initialized (thread ID: 426)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3810): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3810): Entering thread (ID: 426)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3810): onBytesRead: Read 82 bytes successfully (thread ID: 425),
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3810): Got valid identity from [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3110]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3810): onBytesWritten: 82 bytes successfully written (thread ID: 425)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3810): removeThreadFromList: Removing thread with ID 425
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3810): Handshake thread disposed (thread ID: 425)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3810): onIncomingConnectionConnected: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3110]
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3810): Exiting thread (ID: 425)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3810): onConnected: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3110]
,I/io.jxcore.node.ConnectionHelper( 3810): onConnected: Incoming connection to peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3110]
,D/io.jxcore.node.ConnectionHelper( 3810): hasConnection: No connection with peer with ID B0:C5:59:3F:75:69
,D/io.jxcore.node.ConnectionHelper( 3810): notifyPeerAvailability: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3110] is available
I/io.jxcore.node.ConnectionHelper( 3810): onConnected: Incoming socket thread, for peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3110], created successfully
,D/io.jxcore.node.ConnectionHelper( 3810): onConnected: The total number of connections is now 1
,D/io.jxcore.node.IncomingSocketThread( 3810): Entering thread (ID: 427)
,I/io.jxcore.node.IncomingSocketThread( 3810): Local host address: localhost/127.0.0.1, port: 41534,
,D/io.jxcore.node.IncomingSocketThread( 3810): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3810): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3810): setBufferSize: Setting buffer size to 8192 bytes
,I/jxcore-log( 3810): 2015-12-18T12:53:36.957Z SendDataTCPServer.js: TCP/IP server connected,
I/jxcore-log( 3810): 
D/io.jxcore.node.StreamCopyingThread( 3810): Entering thread (ID: 428, name: Sender)
I/io.jxcore.node.IncomingSocketThread( 3810): startStreamCopyingThreads: OK,
D/io.jxcore.node.IncomingSocketThread( 3810): Exiting thread (ID: 427)
,D/io.jxcore.node.StreamCopyingThread( 3810): Entering thread (ID: 429, name: Receiver),
,E/bt-btm  ( 2140): tBTM_SEC_DEV:0xa2fd607c rs_disc_pending=0
,W/bt-btif ( 2140): bta_dm_check_av:0
W/bt-btif ( 2140): btif_dm_cback : unhandled event (14)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3810): onBytesRead: Read 77 bytes successfully (thread ID: 426),
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3810): Got valid identity from [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3810): onBytesWritten: 82 bytes successfully written (thread ID: 426)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3810): removeThreadFromList: Removing thread with ID 426
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3810): Handshake thread disposed (thread ID: 426)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3810): onIncomingConnectionConnected: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301]
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3810): Exiting thread (ID: 426)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3810): onConnected: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301]
,I/io.jxcore.node.ConnectionHelper( 3810): onConnected: Incoming connection to peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301]
D/io.jxcore.node.ConnectionHelper( 3810): hasConnection: No connection with peer with ID 34:FC:EF:11:AE:67
,D/io.jxcore.node.ConnectionHelper( 3810): notifyPeerAvailability: Peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301] is available
I/io.jxcore.node.ConnectionHelper( 3810): onConnected: Incoming socket thread, for peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301], created successfully
,D/io.jxcore.node.ConnectionHelper( 3810): onConnected: The total number of connections is now 2
D/io.jxcore.node.IncomingSocketThread( 3810): Entering thread (ID: 430)
I/io.jxcore.node.IncomingSocketThread( 3810): Local host address: localhost/127.0.0.1, port: 41534
D/io.jxcore.node.IncomingSocketThread( 3810): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3810): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3810): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 3810): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3810): Exiting thread (ID: 430)
,D/io.jxcore.node.StreamCopyingThread( 3810): Entering thread (ID: 432, name: Receiver)
I/jxcore-log( 3810): 2015-12-18T12:53:37.183Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3810): 
D/io.jxcore.node.StreamCopyingThread( 3810): Entering thread (ID: 431, name: Sender)
,I/jxcore-log( 3810): 2015-12-18T12:53:37.563Z SendDataConnector.js: re-try now : 08:EC:A9:50:76:27,
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:37.564Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3810): 
,E/bt-btm  ( 2140): tBTM_SEC_DEV:0xa2fd6244 rs_disc_pending=0
,W/bt-btif ( 2140): bta_dm_check_av:0
W/bt-btif ( 2140): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3810): 2015-12-18T12:53:37.940Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:37.993Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:38.073Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:38.086Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:38.093Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:38.097Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:38.130Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:38.198Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3810): 
,D/HeadsetStateMachine( 2140): Disconnected process message: 10, size: 0,
,I/jxcore-log( 3810): 2015-12-18T12:53:38.228Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:38.232Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:38.237Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:38.280Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 3810): 
,I/wpa_supplicant( 1190): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 1 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
,I/jxcore-log( 3810): 2015-12-18T12:53:38.320Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3810): ,
D/WifiP2pManager( 3810): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): Service request added successfully
,I/jxcore-log( 3810): 2015-12-18T12:53:38.366Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:38.377Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:38.408Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:38.554Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:38.586Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:38.622Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:38.656Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:38.702Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:38.835Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:38.957Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:39.052Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:39.239Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:39.244Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:39.270Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:39.278Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3810): 
,I/wpa_supplicant( 1190): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): Service discovery started successfully
,I/jxcore-log( 3810): 2015-12-18T12:53:39.348Z SendDataTCPServer.js: TCP/IP server has received 32768 bytes of data
I/jxcore-log( 3810): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT9700","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700],
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: a2:39:f7:6f:c9:5d,
,D/io.jxcore.node.ConnectionHelper( 3810): notifyPeerAvailability: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700] is available
,I/jxcore-log( 3810): 2015-12-18T12:53:39.467Z SendDataTCPServer.js: TCP/IP server has received 34748 bytes of data,
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:39.511Z SendDataTCPServer.js: TCP/IP server has received 36728 bytes of data
I/jxcore-log( 3810): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT3932","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local.",
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3932],
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3932],
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3932],
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3932], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Adding new peer: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3932]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3932], Bluetooth address: E0:DB:10:14:E2:C0, device name: Note4-1, device address: 92:b6:86:43:73:1c
D/io.jxcore.node.ConnectionHelper( 3810): notifyPeerAvailability: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3932] is available
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT3565","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3565]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3565]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3565]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3565], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3565]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3565], Bluetooth address: 7C:F9:0E:37:96:AB, device name: , device address: 7e:f9:0e:37:96:ac
,D/io.jxcore.node.ConnectionHelper( 3810): notifyPeerAvailability: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3565] is available
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT548","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT548]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT548]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT548]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT548], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT548]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT548], Bluetooth address: 08:EC:A9:50:76:27, device name: , device address: 0a:ec:a9:50:76:28
D/io.jxcore.node.ConnectionHelper( 3810): notifyPeerAvailability: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT548] is available
,I/jxcore-log( 3810): 2015-12-18T12:53:39.584Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:39.637Z SendDataTCPServer.js: TCP/IP server has received 38708 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:39.699Z SendDataTCPServer.js: TCP/IP server has received 40688 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:39.817Z SendDataTCPServer.js: TCP/IP server has received 42668 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:39.903Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
,I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:39.911Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:39.973Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:40.053Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:40.088Z SendDataTCPServer.js: TCP/IP server has received 32768 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:40.103Z SendDataTCPServer.js: TCP/IP server has received 34748 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:40.108Z SendDataTCPServer.js: TCP/IP server has received 36728 bytes of data,
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:40.136Z SendDataTCPServer.js: TCP/IP server has received 44648 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:40.141Z SendDataTCPServer.js: TCP/IP server has received 46628 bytes of data,
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:40.156Z SendDataTCPServer.js: TCP/IP server has received 38708 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:40.162Z SendDataTCPServer.js: TCP/IP server has received 40688 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:40.191Z SendDataTCPServer.js: TCP/IP server has received 48608 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:40.211Z SendDataTCPServer.js: TCP/IP server has received 42668 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:40.234Z SendDataTCPServer.js: TCP/IP server has received 50588 bytes of data
I/jxcore-log( 3810): ,
,I/jxcore-log( 3810): 2015-12-18T12:53:40.243Z SendDataTCPServer.js: TCP/IP server has received 52568 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:40.249Z SendDataTCPServer.js: TCP/IP server has received 44648 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:40.275Z SendDataTCPServer.js: TCP/IP server has received 46628 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:40.279Z SendDataTCPServer.js: TCP/IP server has received 54548 bytes of data
I/jxcore-log( 3810): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT103","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT103]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT103]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT103]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT103], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT103]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT103], Bluetooth address: 08:EC:A9:50:75:41, device name: , device address: 0a:ec:a9:50:75:42
,D/io.jxcore.node.ConnectionHelper( 3810): notifyPeerAvailability: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT103] is available
,I/jxcore-log( 3810): 2015-12-18T12:53:40.337Z SendDataTCPServer.js: TCP/IP server has received 48608 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:40.357Z SendDataTCPServer.js: TCP/IP server has received 56528 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:40.465Z SendDataTCPServer.js: TCP/IP server has received 50588 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:40.501Z SendDataTCPServer.js: TCP/IP server has received 58508 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:40.542Z SendDataTCPServer.js: TCP/IP server has received 60488 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:40.639Z SendDataTCPServer.js: TCP/IP server has received 52568 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:40.725Z SendDataTCPServer.js: TCP/IP server has received 54548 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:40.753Z SendDataTCPServer.js: TCP/IP server has received 62468 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:40.818Z SendDataTCPServer.js: TCP/IP server has received 64448 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:40.873Z SendDataTCPServer.js: TCP/IP server has received 66428 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:41.080Z SendDataTCPServer.js: TCP/IP server has received 68408 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:41.311Z SendDataTCPServer.js: TCP/IP server has received 56528 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:41.325Z SendDataTCPServer.js: TCP/IP server has received 70388 bytes of data,
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:41.394Z SendDataTCPServer.js: TCP/IP server has received 72368 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:41.440Z SendDataTCPServer.js: TCP/IP server has received 74348 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:41.444Z SendDataTCPServer.js: TCP/IP server has received 76328 bytes of data
I/jxcore-log( 3810): 
,D/btif_config_util( 2140): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT5199","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], Bluetooth address: 58:3F:54:73:64:C0, device name: , device address: 02:9a:02:7b:60:ac
D/io.jxcore.node.ConnectionHelper( 3810): notifyPeerAvailability: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199] is available
,I/jxcore-log( 3810): 2015-12-18T12:53:41.526Z SendDataTCPServer.js: TCP/IP server has received 78308 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:41.568Z SendDataTCPServer.js: TCP/IP server has received 80288 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:41.762Z SendDataTCPServer.js: TCP/IP server has received 82268 bytes of data
I/jxcore-log( 3810): ,
,I/jxcore-log( 3810): 2015-12-18T12:53:41.791Z SendDataTCPServer.js: TCP/IP server has received 58508 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:41.799Z SendDataTCPServer.js: TCP/IP server has received 86228 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:41.813Z SendDataTCPServer.js: TCP/IP server has received 88208 bytes of data,
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:41.816Z SendDataTCPServer.js: TCP/IP server has received 90188 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:41.936Z SendDataTCPServer.js: TCP/IP server has received 92168 bytes of data,
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:41.951Z SendDataTCPServer.js: TCP/IP server has received 60488 bytes of data,
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:41.961Z SendDataTCPServer.js: TCP/IP server has received 62468 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:41.969Z SendDataTCPServer.js: TCP/IP server has received 94148 bytes of data,
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:41.988Z SendDataTCPServer.js: TCP/IP server has received 96128 bytes of data,
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:42.090Z SendDataTCPServer.js: TCP/IP server has received 64448 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:42.142Z SendDataTCPServer.js: TCP/IP server has received 98108 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:42.164Z SendDataTCPServer.js: TCP/IP server has received 66428 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:42.206Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:42.229Z SendDataTCPServer.js: TCP/IP server has received 68408 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:42.370Z SendDataTCPServer.js: TCP/IP server has received 70388 bytes of data
I/jxcore-log( 3810): 
,W/bt-btif ( 2140): invalid rfc slot id: 6
,W/io.jxcore.node.StreamCopyingThread( 3810): Either failed to read from the output stream or write to the input stream (thread ID: 432, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.IncomingSocketThread( 3810): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3810): onDisconnected: Incoming connection, peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,I/io.jxcore.node.ConnectionHelper( 3810): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 430
D/io.jxcore.node.IncomingSocketThread( 3810): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3810): doStop: Thread ID: 432
D/io.jxcore.node.IncomingSocketThread( 3810): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3810): doStop: Thread ID: 431
,D/io.jxcore.node.IncomingSocketThread( 3810): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 3810): closeLocalSocketAndStreams: Closing the local input stream...
D/io.jxcore.node.IncomingSocketThread( 3810): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 3810): closeLocalSocketAndStreams: Closing the localhost socket...
W/io.jxcore.node.StreamCopyingThread( 3810): Either failed to read from the output stream or write to the input stream (thread ID: 431, thread name: Sender): Socket closed
,I/io.jxcore.node.IncomingSocketThread( 3810): closeBluetoothSocketAndStreams
E/io.jxcore.node.IncomingSocketThread( 3810): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.ConnectionHelper( 3810): closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
W/io.jxcore.node.ConnectionHelper( 3810): onDisconnected: Incoming connection, peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.ConnectionHelper( 3810): closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,D/io.jxcore.node.StreamCopyingThread( 3810): Exiting thread (ID: 431, name: Sender)
D/io.jxcore.node.StreamCopyingThread( 3810): Exiting thread (ID: 432, name: Receiver)
,I/jxcore-log( 3810): 2015-12-18T12:53:42.427Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3810): 
,D/io.jxcore.node.ConnectionHelper( 3810): disconnectOutgoingConnection: Trying to close connection to peer with ID 08:EC:A9:50:76:27
,E/io.jxcore.node.ConnectionHelper( 3810): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:76:27
D/io.jxcore.node.ConnectionHelper( 3810): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,W/io.jxcore.node.ConnectionHelper( 3810): disconnectOutgoingConnection: Failed to disconnect (peer ID: 08:EC:A9:50:76:27), either no such connection or failed to close the connection
I/jxcore-log( 3810): 2015-12-18T12:53:42.570Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 3810): 
I/jxcore-log( 3810): 2015-12-18T12:53:42.572Z SendDataConnector.js: Connect (retry count 1) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:42.573Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:42.574Z SendDataConnector.js: do connect now
I/jxcore-log( 3810): 
,I/io.jxcore.node.ConnectionHelper( 3810): connect: Trying to connect to peer with ID 08:EC:A9:50:76:27
,D/io.jxcore.node.ConnectionHelper( 3810): hasConnection: No connection with peer with ID 08:EC:A9:50:76:27
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3810): connect: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT548]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3810): connect: Trying to start connecting to null in address 08:EC:A9:50:76:27
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3810): setInsecureRfcommSocketPort: Using port 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3810): setMaxNumberOfRetries: 0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3810): onConnecting: null 08:EC:A9:50:76:27
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3810): connect: Started connecting to null in address 08:EC:A9:50:76:27
,I/io.jxcore.node.ConnectionHelper( 3810): connect: Connection process successfully started (peer ID: 08:EC:A9:50:76:27)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3810): Trying to connect to peer with address 08:EC:A9:50:76:27 (thread ID: 433)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3810): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3810): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2140): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/jxcore-log( 3810): 2015-12-18T12:53:42.761Z SendDataTCPServer.js: TCP/IP server has received 72368 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:43.160Z SendDataTCPServer.js: TCP/IP server has received 74348 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:43.372Z SendDataTCPServer.js: TCP/IP server has received 76328 bytes of data
I/jxcore-log( 3810): 
,E/bt-btm  ( 2140): tBTM_SEC_DEV:0xa2fd607c rs_disc_pending=1
,W/bt-btif ( 2140): bta_dm_check_av:0
W/bt-btif ( 2140): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3810): 2015-12-18T12:53:43.891Z SendDataTCPServer.js: TCP/IP server has received 78308 bytes of data
I/jxcore-log( 3810): 
,W/bt-rfcomm( 2140): rfc_find_lcid_mcb LCID reused LCID:0x44 current:0x0
,W/bt-rfcomm( 2140): RFCOMM_DisconnectInd LCID:0x44
,E/bt-btm  ( 2140): tBTM_SEC_DEV:0xa2fd6244 rs_disc_pending=1
,W/bt-btif ( 2140): bta_dm_check_av:0
W/bt-btif ( 2140): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2140): info:x10
,D/        ( 2140): remote version info [44:80:eb:7b:5a:05]: 6, 1d, 7d3
E/BluetoothRemoteDevices( 2140): aclStateChangeCallback: Device is NULL
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4778","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: , device address: ee:1f:72:63:11:86
D/io.jxcore.node.ConnectionHelper( 3810): notifyPeerAvailability: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778] is available
,W/bt-btif ( 2140): info:x10
D/        ( 2140): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,E/BluetoothRemoteDevices( 2140): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 2140): tBTM_SEC_DEV:0xa2fd640c rs_disc_pending=0
,W/bt-btif ( 2140): bta_dm_check_av:0
W/bt-btif ( 2140): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2140): tBTM_SEC_DEV:0xa2fd6244 rs_disc_pending=0
,W/bt-btif ( 2140): bta_dm_check_av:0
W/bt-btif ( 2140): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2140): btm_sec_disconnected - Clearing Pending flag,
,D/BluetoothMapService( 2140): onReceive
,D/BluetoothManagerService(  823): Message: 20
D/BluetoothManagerService(  823): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2b073c29:true
,I/BTConnectionReceiver( 1515): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524],
,I/BluetoothClassifier( 1515): Bluetooth Device Name: Nexus 5
,I/jxcore-log( 3810): 2015-12-18T12:53:47.572Z SendDataTCPServer.js: TCP/IP server has received 80288 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:47.600Z SendDataTCPServer.js: TCP/IP server has received 82268 bytes of data
I/jxcore-log( 3810): 
,D/btif_config( 2140): btif_get_device_type: Device [44:80:eb:7b:5a:05] type 1
,I/BluetoothBondStateMachine( 2140): bondStateChangeCallback: Status: 0 Address: 44:80:EB:7B:5A:05 newState: 1
,E/bt-btif ( 2140): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2140): Bond State Change Intent:44:80:EB:7B:5A:05 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2140): Entering PendingCommandState State
,W/bt-sdp  ( 2140): SDP - Rcvd conn cnf with error: 0x4  CID 0x45
,E/bt-btif ( 2140): DISCOVERY_COMP_EVT slot id:8, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2140): invalid rfc slot id: 8
,W/BluetoothAdapter( 3810): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2140): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/BluetoothBondStateMachine( 2140): bondStateChangeCallback: Status: 0 Address: 44:80:EB:7B:5A:05 newState: 0,
D/BluetoothAdapterProperties( 2140): Failed to remove device: 44:80:EB:7B:5A:05
I/BluetoothBondStateMachine( 2140): Bond State Change Intent:44:80:EB:7B:5A:05 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2140): StableState(): Entering Off State
,W/bt-btif ( 2140): new conn_srvc id:26, app_id:255
,W/bt-btif ( 2140): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2140): bta_dm_pm_ssr:2, lat:1200
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3810): Incoming connection accepted
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3810): Incoming connection initialized (thread ID: 434)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3810): Waiting for incoming connections...
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3810): Entering thread (ID: 434)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3810): onBytesRead: Read 81 bytes successfully (thread ID: 434)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3810): Got valid identity from [44:80:EB:7B:5A:05 motorola-XT1072_PT5087]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3810): onBytesWritten: 82 bytes successfully written (thread ID: 434)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3810): removeThreadFromList: Removing thread with ID 434
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3810): Handshake thread disposed (thread ID: 434)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3810): onIncomingConnectionConnected: [44:80:EB:7B:5A:05 motorola-XT1072_PT5087]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3810): Exiting thread (ID: 434)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3810): onConnected: [44:80:EB:7B:5A:05 motorola-XT1072_PT5087]
I/io.jxcore.node.ConnectionHelper( 3810): onConnected: Incoming connection to peer [44:80:EB:7B:5A:05 motorola-XT1072_PT5087]
D/io.jxcore.node.ConnectionHelper( 3810): hasConnection: No connection with peer with ID 44:80:EB:7B:5A:05
,D/io.jxcore.node.ConnectionHelper( 3810): notifyPeerAvailability: Peer [44:80:EB:7B:5A:05 motorola-XT1072_PT5087] is available
I/io.jxcore.node.ConnectionHelper( 3810): onConnected: Incoming socket thread, for peer [44:80:EB:7B:5A:05 motorola-XT1072_PT5087], created successfully
D/io.jxcore.node.ConnectionHelper( 3810): onConnected: The total number of connections is now 2
D/io.jxcore.node.IncomingSocketThread( 3810): Entering thread (ID: 435)
,I/jxcore-log( 3810): 2015-12-18T12:53:48.204Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3810): 
,I/io.jxcore.node.IncomingSocketThread( 3810): Local host address: localhost/127.0.0.1, port: 41534
,D/io.jxcore.node.IncomingSocketThread( 3810): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3810): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread( 3810): setBufferSize: Setting buffer size to 8192 bytes
D/io.jxcore.node.StreamCopyingThread( 3810): Entering thread (ID: 436, name: Sender)
,I/io.jxcore.node.IncomingSocketThread( 3810): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3810): Exiting thread (ID: 435)
,D/io.jxcore.node.StreamCopyingThread( 3810): Entering thread (ID: 437, name: Receiver)
,E/bt-btm  ( 2140): tBTM_SEC_DEV:0xa2fd65d4 rs_disc_pending=0,
W/bt-btif ( 2140): bta_dm_check_av:0
,W/bt-btif ( 2140): btif_dm_cback : unhandled event (14)
,I/BooksSync( 3716): Starting books sync for 61035162, extras: ade
,V/KeepSync( 3749): Connecting to GoogleApiClient
,I/BooksConfig( 3716): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1267): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1267): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1267): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1267): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1267): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1267): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1267): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1267): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1267): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1267): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1805): Handling authorization failure
E/ClientConnectionOperation( 1805): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1805): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1805): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1805): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1805): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1805): 	... 7 more
,V/KeepSync( 3749): GoogleApiClient failed to connect with error code: 4
E/SQLiteLog( 3749): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3749): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3749): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1267): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1267): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1267): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1267): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1267): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3716): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3716): Soft error
E/BooksSync( 3716): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3716): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3716): Sync error
E/BooksSync( 3716): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3716): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3716): Finished books sync
,I/GLSUser ( 1267): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1267): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1267): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1267): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 474064, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
V/GLSActivity( 1267): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3749): IOException
E/KeepSync( 3749): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3749): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3749): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3749): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3749): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3749): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3749): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3749): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3749): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3749): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3749): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3749): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3749): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3749): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3749): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3749): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3749): 	... 10 more
W/KeepSync( 3749): Sync result 2
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 476158, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,E/bt-btm  ( 2140): tBTM_SEC_DEV:0xa2fd640c rs_disc_pending=1
W/bt-btif ( 2140): bta_dm_check_av:0
W/bt-btif ( 2140): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3810): 2015-12-18T12:53:49.170Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:49.177Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:49.241Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data,
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:49.276Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:49.283Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:49.312Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:49.320Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3810): 
,E/bt-btm  ( 2140): tBTM_SEC_DEV:0xa2fd6244 rs_disc_pending=1
,W/bt-btif ( 2140): bta_dm_check_av:0
W/bt-btif ( 2140): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3810): 2015-12-18T12:53:49.380Z SendDataTCPServer.js: TCP/IP server has received 84248 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:49.407Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:49.411Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:49.458Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:49.493Z SendDataTCPServer.js: TCP/IP server has received 86228 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:49.717Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:49.722Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:49.738Z SendDataTCPServer.js: TCP/IP server has received 88208 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:49.759Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:49.762Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:49.769Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:49.779Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3810): 
,D/btif_config( 2140): btif_get_device_type: Device [f8:95:c7:87:85:54] type 1
,I/BluetoothBondStateMachine( 2140): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 1
E/bt-btif ( 2140): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2140): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2140): Entering PendingCommandState State
,I/jxcore-log( 3810): 2015-12-18T12:53:49.877Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:49.920Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:49.934Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:49.940Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:49.993Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:50.062Z SendDataTCPServer.js: TCP/IP server has received 90188 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:50.120Z SendDataTCPServer.js: TCP/IP server has received 92168 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:50.210Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:50.249Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:50.253Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:50.258Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:50.279Z SendDataTCPServer.js: TCP/IP server has received 94148 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:50.283Z SendDataTCPServer.js: TCP/IP server has received 96128 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:50.305Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:50.352Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:50.389Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data
I/jxcore-log( 3810): 
,I/BluetoothBondStateMachine( 2140): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 0
,D/BluetoothAdapterProperties( 2140): Failed to remove device: F8:95:C7:87:85:54,
,I/BluetoothBondStateMachine( 2140): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2140): StableState(): Entering Off State
,I/jxcore-log( 3810): 2015-12-18T12:53:50.536Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:50.550Z SendDataTCPServer.js: TCP/IP server has received 98108 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:50.620Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data,
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:50.659Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:50.687Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:50.781Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:50.822Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data,
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:50.829Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data,
I/jxcore-log( 3810): 
,W/bt-btif ( 2140): new conn_srvc id:26, app_id:255,
W/bt-btif ( 2140): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2140): bta_dm_pm_ssr:2, lat:1200
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3810): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3810): Incoming connection initialized (thread ID: 438)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3810): Waiting for incoming connections...
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3810): Entering thread (ID: 438)
,I/jxcore-log( 3810): 2015-12-18T12:53:50.937Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:51.017Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 3810): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT9178","ra":"E0:DB:10:1F:C9:5E"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT9178]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT9178]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT9178]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT9178], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Adding new peer: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT9178]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT9178], Bluetooth address: E0:DB:10:1F:C9:5E, device name: , device address: ea:50:8b:de:28:a3
,D/io.jxcore.node.ConnectionHelper( 3810): notifyPeerAvailability: Peer [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT9178] is available
,I/jxcore-log( 3810): 2015-12-18T12:53:51.317Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:51.435Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data,
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:51.472Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:51.501Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:51.550Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 3810): ,
,I/jxcore-log( 3810): 2015-12-18T12:53:51.584Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:51.637Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 3810): ,
,I/jxcore-log( 3810): 2015-12-18T12:53:51.729Z SendDataTCPServer.js: TCP/IP server has received 85684 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:51.761Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:51.768Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:51.807Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:51.887Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:51.924Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data
,I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:52.065Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:52.105Z SendDataTCPServer.js: TCP/IP server has received 99544 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:52.108Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3810): 
,W/bt-btif ( 2140): info:x10,
,D/        ( 2140): remote version info [08:ec:a9:50:76:27]: 7, f, 6109
,E/BluetoothRemoteDevices( 2140): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 2140): invalid rfc slot id: 7
W/io.jxcore.node.StreamCopyingThread( 3810): Either failed to read from the output stream or write to the input stream (thread ID: 437, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 3810): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3810): onDisconnected: Incoming connection, peer [44:80:EB:7B:5A:05 motorola-XT1072_PT5087] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3810): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 435
D/io.jxcore.node.IncomingSocketThread( 3810): close: Stopping receiving thread...
,I/io.jxcore.node.StreamCopyingThread( 3810): doStop: Thread ID: 437
D/io.jxcore.node.IncomingSocketThread( 3810): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3810): doStop: Thread ID: 436
D/io.jxcore.node.IncomingSocketThread( 3810): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 3810): closeLocalSocketAndStreams: Closing the local input stream...
D/io.jxcore.node.IncomingSocketThread( 3810): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 3810): closeLocalSocketAndStreams: Closing the localhost socket...
,I/io.jxcore.node.IncomingSocketThread( 3810): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3810): closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3810): Exiting thread (ID: 437, name: Receiver)
W/io.jxcore.node.StreamCopyingThread( 3810): Either failed to read from the output stream or write to the input stream (thread ID: 436, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3810): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3810): onDisconnected: Incoming connection, peer [44:80:EB:7B:5A:05 motorola-XT1072_PT5087] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.ConnectionHelper( 3810): closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3810): Exiting thread (ID: 436, name: Sender)
I/jxcore-log( 3810): 2015-12-18T12:53:53.168Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3810): 
,I/wpa_supplicant( 1190): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 2 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3932], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3932]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): restart: Restarting...
,D/WifiP2pManager( 3810): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): Service request added successfully
,W/bt-sdp  ( 2140): process_service_search_attr_rsp
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): Service discovery started successfully
,D/btif_config_util( 2140): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3810): Connection timeout
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3810): onConnectionTimeout: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT548]
,I/jxcore-log( 3810): 2015-12-18T12:53:57.588Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT548] timed out
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:57.589Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT548] timed out,
I/jxcore-log( 3810): 
I/jxcore-log( 3810): 2015-12-18T12:53:57.590Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3810): 
,D/btif_config( 2140): btif_get_device_type: Device [08:ec:a9:50:76:27] type 1
,I/BluetoothBondStateMachine( 2140): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:76:27 newState: 1
E/bt-btif ( 2140): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2140): Bond State Change Intent:08:EC:A9:50:76:27 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 2140): Entering PendingCommandState State
,E/bt-btm  ( 2140): tBTM_SEC_DEV:0xa2fd65d4 rs_disc_pending=1
W/bt-btif ( 2140): bta_dm_check_av:0
W/bt-btif ( 2140): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 2140): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:76:27 newState: 0
,D/BluetoothAdapterProperties( 2140): Failed to remove device: 08:EC:A9:50:76:27
,I/BluetoothBondStateMachine( 2140): Bond State Change Intent:08:EC:A9:50:76:27 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2140): StableState(): Entering Off State
,W/bt-btif ( 2140): dm_pm_timer expires,
W/bt-btif ( 2140): dm_pm_timer expires 0
W/bt-btif ( 2140): proc dm_pm_timer expires
,E/bt-btm  ( 2140): btm_sec_disconnected - Clearing Pending flag,
,D/BluetoothMapService( 2140): onReceive
,E/bt-btm  ( 2140): tBTM_SEC_DEV:0xa2fd6244 rs_disc_pending=0
W/bt-btif ( 2140): bta_dm_check_av:0
W/bt-btif ( 2140): btif_dm_cback : unhandled event (14)
,I/BTConnectionReceiver( 1515): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1515): Bluetooth Device Name: XT1072,
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3810): onBytesRead: Read 77 bytes successfully (thread ID: 438)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3810): Got valid identity from [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3810): onBytesWritten: 82 bytes successfully written (thread ID: 438)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3810): removeThreadFromList: Removing thread with ID 438
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3810): Handshake thread disposed (thread ID: 438)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3810): onIncomingConnectionConnected: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3810): Exiting thread (ID: 438)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3810): onConnected: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
I/io.jxcore.node.ConnectionHelper( 3810): onConnected: Incoming connection to peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/io.jxcore.node.ConnectionHelper( 3810): hasConnection: No connection with peer with ID F8:95:C7:87:85:54
,D/io.jxcore.node.ConnectionHelper( 3810): notifyPeerAvailability: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638] is available
I/io.jxcore.node.ConnectionHelper( 3810): onConnected: Incoming socket thread, for peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], created successfully
D/io.jxcore.node.ConnectionHelper( 3810): onConnected: The total number of connections is now 2
,D/io.jxcore.node.IncomingSocketThread( 3810): Entering thread (ID: 440)
,I/io.jxcore.node.IncomingSocketThread( 3810): Local host address: localhost/127.0.0.1, port: 41534,
D/io.jxcore.node.IncomingSocketThread( 3810): Setting local streams and starting stream copying threads...
,I/io.jxcore.node.StreamCopyingThread( 3810): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3810): setBufferSize: Setting buffer size to 8192 bytes,
I/jxcore-log( 3810): 2015-12-18T12:53:58.663Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3810): 
D/io.jxcore.node.StreamCopyingThread( 3810): Entering thread (ID: 441, name: Sender)
,I/io.jxcore.node.IncomingSocketThread( 3810): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3810): Exiting thread (ID: 440)
D/io.jxcore.node.StreamCopyingThread( 3810): Entering thread (ID: 442, name: Receiver)
,W/bt-btif ( 2140): invalid rfc slot id: 4,
,W/io.jxcore.node.StreamCopyingThread( 3810): Either failed to read from the output stream or write to the input stream (thread ID: 429, thread name: Receiver): bt socket closed, read return: -1,
E/io.jxcore.node.IncomingSocketThread( 3810): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
,W/io.jxcore.node.ConnectionHelper( 3810): onDisconnected: Incoming connection, peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3110] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3810): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 427
D/io.jxcore.node.IncomingSocketThread( 3810): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3810): doStop: Thread ID: 429
D/io.jxcore.node.IncomingSocketThread( 3810): close: Stopping sending thread...
,I/io.jxcore.node.StreamCopyingThread( 3810): doStop: Thread ID: 428
D/io.jxcore.node.IncomingSocketThread( 3810): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 3810): closeLocalSocketAndStreams: Closing the local input stream...
W/io.jxcore.node.StreamCopyingThread( 3810): Either failed to read from the output stream or write to the input stream (thread ID: 428, thread name: Sender): Socket closed
D/io.jxcore.node.IncomingSocketThread( 3810): closeLocalSocketAndStreams: Closing the local output stream...
E/io.jxcore.node.IncomingSocketThread( 3810): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.IncomingSocketThread( 3810): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 3810): closeBluetoothSocketAndStreams
W/io.jxcore.node.ConnectionHelper( 3810): onDisconnected: Incoming connection, peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3110] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.ConnectionHelper( 3810): closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
D/io.jxcore.node.ConnectionHelper( 3810): closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3810): Exiting thread (ID: 429, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3810): Exiting thread (ID: 428, name: Sender)
I/jxcore-log( 3810): 2015-12-18T12:53:59.239Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:59.901Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:59.935Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
,I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:59.960Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:53:59.963Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3810): 
,W/bt-btif ( 2140): new conn_srvc id:26, app_id:1
,W/bt-btif ( 2140): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2140): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3810): onSocketConnected: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT548]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3810): shutdown (thread ID: 433)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3810): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 433)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3810): Exiting thread (thread ID: 433)
,I/jxcore-log( 3810): 2015-12-18T12:54:00.004Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:54:00.038Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:54:00.056Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:54:00.089Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:54:00.108Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3810): ,
,I/jxcore-log( 3810): 2015-12-18T12:54:00.117Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:54:00.136Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:54:00.169Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:54:00.191Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:54:00.199Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:54:00.210Z SendDataTCPServer.js: TCP/IP server has received 32768 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:54:00.250Z SendDataTCPServer.js: TCP/IP server has received 36728 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:54:00.298Z SendDataTCPServer.js: TCP/IP server has received 38708 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:54:00.318Z SendDataTCPServer.js: TCP/IP server has received 40688 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:54:00.329Z SendDataTCPServer.js: TCP/IP server has received 42668 bytes of data
I/jxcore-log( 3810): 
,W/bt-btif ( 2140): bta_jv_rfc_port_to_cb(port_handle:0xc):jv handle:0x0 not FOUND
,I/jxcore-log( 3810): 2015-12-18T12:54:00.369Z SendDataTCPServer.js: TCP/IP server has received 44648 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:54:00.379Z SendDataTCPServer.js: TCP/IP server has received 46628 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:54:00.397Z SendDataTCPServer.js: TCP/IP server has received 48608 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:54:00.400Z SendDataTCPServer.js: TCP/IP server has received 50588 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:54:00.538Z SendDataTCPServer.js: TCP/IP server has received 52568 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:54:00.615Z SendDataTCPServer.js: TCP/IP server has received 54548 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:54:00.647Z SendDataTCPServer.js: TCP/IP server has received 56528 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:54:00.668Z SendDataTCPServer.js: TCP/IP server has received 58508 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:54:00.673Z SendDataTCPServer.js: TCP/IP server has received 60488 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:54:00.730Z SendDataTCPServer.js: TCP/IP server has received 62468 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:54:00.732Z SendDataTCPServer.js: TCP/IP server has received 66428 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:54:00.748Z SendDataTCPServer.js: TCP/IP server has received 68408 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:54:00.831Z SendDataTCPServer.js: TCP/IP server has received 70388 bytes of data
,I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:54:00.839Z SendDataTCPServer.js: TCP/IP server has received 72368 bytes of data
I/jxcore-log( 3810): 
,E/bt-btm  ( 2140): tBTM_SEC_DEV:0xa2fd5eb4 rs_disc_pending=0
,W/bt-btif ( 2140): bta_dm_check_av:0
W/bt-btif ( 2140): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 2140): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3810): 2015-12-18T12:54:01.133Z SendDataTCPServer.js: TCP/IP server has received 74348 bytes of data
I/jxcore-log( 3810): 
,E/bt-btm  ( 2140): tBTM_SEC_DEV:0xa2fd6244 rs_disc_pending=1
,W/bt-btif ( 2140): bta_dm_check_av:0
W/bt-btif ( 2140): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3810): 2015-12-18T12:54:02.590Z SendDataConnector.js: re-try now : 08:EC:A9:50:76:27
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:54:02.591Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3810): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT9178","ra":"E0:DB:10:1F:C9:5E"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT9178]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT9178]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT9178]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT9178], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT9178]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT9178], Bluetooth address: E0:DB:10:1F:C9:5E, device name: , device address: ea:50:8b:de:28:a3
W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT9178] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4778","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778],
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT9700","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local.",
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT548","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT548]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT548]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT548]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT548], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT548]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT548], Bluetooth address: 08:EC:A9:50:76:27, device name: , device address: 0a:ec:a9:50:76:28
W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT548] already in the list, will not add again
,E/bt-btm  ( 2140): btm_sec_disconnected - Clearing Pending flag,
E/bt-btm  ( 2140): tBTM_SEC_DEV:0xa2fd6244 rs_disc_pending=1
W/bt-btif ( 2140): bta_dm_check_av:0
,W/bt-btif ( 2140): btif_dm_cback : unhandled event (14)
,D/BluetoothMapService( 2140): onReceive
,I/BTConnectionReceiver( 1515): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1515): Bluetooth Device Name: Thali Test (Galaxy A3)
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT9205","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT9205]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT9205]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT9205]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT9205], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Adding new peer: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT9205]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT9205], Bluetooth address: 90:E7:C4:F6:69:77, device name: , device address: 92:e7:c4:e6:4c:f8
D/io.jxcore.node.ConnectionHelper( 3810): notifyPeerAvailability: Peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT9205] is available
,I/jxcore-log( 3810): 2015-12-18T12:54:05.370Z SendDataTCPServer.js: TCP/IP server has received 76328 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:54:05.717Z SendDataTCPServer.js: TCP/IP server has received 78308 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:54:06.360Z SendDataTCPServer.js: TCP/IP server has received 80288 bytes of data,
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:54:07.377Z SendDataTCPServer.js: TCP/IP server has received 82268 bytes of data
I/jxcore-log( 3810): 
,D/io.jxcore.node.ConnectionHelper( 3810): disconnectOutgoingConnection: Trying to close connection to peer with ID 08:EC:A9:50:76:27,
E/io.jxcore.node.ConnectionHelper( 3810): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:76:27
D/io.jxcore.node.ConnectionHelper( 3810): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left,
W/io.jxcore.node.ConnectionHelper( 3810): disconnectOutgoingConnection: Failed to disconnect (peer ID: 08:EC:A9:50:76:27), either no such connection or failed to close the connection
I/jxcore-log( 3810): 2015-12-18T12:54:07.596Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 3810): 
I/jxcore-log( 3810): 2015-12-18T12:54:07.597Z SendDataConnector.js: Connect (retry count 2) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:54:07.598Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3810): 
I/jxcore-log( 3810): 2015-12-18T12:54:07.598Z SendDataConnector.js: do connect now
I/jxcore-log( 3810): 
I/io.jxcore.node.ConnectionHelper( 3810): connect: Trying to connect to peer with ID 08:EC:A9:50:76:27
D/io.jxcore.node.ConnectionHelper( 3810): hasConnection: No connection with peer with ID 08:EC:A9:50:76:27
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3810): connect: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT548]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3810): connect: Trying to start connecting to Thali Test (Galaxy A3) in address 08:EC:A9:50:76:27
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3810): setInsecureRfcommSocketPort: Using port 1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3810): setMaxNumberOfRetries: 0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3810): onConnecting: Thali Test (Galaxy A3) 08:EC:A9:50:76:27
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3810): connect: Started connecting to Thali Test (Galaxy A3) in address 08:EC:A9:50:76:27
I/io.jxcore.node.ConnectionHelper( 3810): connect: Connection process successfully started (peer ID: 08:EC:A9:50:76:27)
,E/bt-btm  ( 2140): btm_sec_disconnected - Clearing Pending flag
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3810): Trying to connect to peer with address 08:EC:A9:50:76:27 (thread ID: 443)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3810): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3810): getBluetoothService() called with no BluetoothManagerCallback
D/BluetoothMapService( 2140): onReceive
D/BTIF_SOCK( 2140): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/BTConnectionReceiver( 1515): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1515): Bluetooth Device Name: Thali Test (Galaxy S5)
,I/jxcore-log( 3810): 2015-12-18T12:54:07.760Z SendDataTCPServer.js: TCP/IP server has received 84248 bytes of data
I/jxcore-log( 3810): 
,W/bt-sdp  ( 2140): SDP - Rcvd conn cnf with error: 0x4  CID 0x4c
E/bt-btif ( 2140): DISCOVERY_COMP_EVT slot id:12, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2140): invalid rfc slot id: 12
W/BluetoothAdapter( 3810): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2140): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66,
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT103","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local.",
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT103]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT103]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT103]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT103], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT103]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT103], Bluetooth address: 08:EC:A9:50:75:41, device name: , device address: 0a:ec:a9:50:75:42
W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT103] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT8301","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Adding new peer: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301], Bluetooth address: 34:FC:EF:11:AE:67, device name: , device address: 52:55:27:f0:fd:0b
W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301] already in the list, will not add again
,W/bt-btif ( 2140): info:x10,
D/        ( 2140): remote version info [08:ec:a9:50:76:27]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1515): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,W/bt-sdp  ( 2140): process_service_search_attr_rsp
,I/BluetoothClassifier( 1515): Bluetooth Device Name: Thali Test (Galaxy A3)
,W/bt-btif ( 2140): new conn_srvc id:26, app_id:1
,W/bt-btif ( 2140): bta_dm_pm_ssr conn_srvc id:26, app_id:1,
W/bt-btif ( 2140): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3810): onSocketConnected: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT548]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3810): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 443)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3810): onBytesWritten: 82 bytes successfully written (thread ID: 444)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3810): Outgoing connection initialized (*handshake* thread ID: 444)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3810): Exiting thread (thread ID: 443)
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3810): Entering thread (ID: 444)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3810): onBytesRead: Read 82 bytes successfully (thread ID: 444),
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3810): Handshake succeeded with [08:EC:A9:50:76:27 samsung-SM-A300FU_PT548]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3810): onHandshakeSucceeded: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT548]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3810): Exiting thread (ID: 444)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3810): onConnected: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT548]
I/io.jxcore.node.ConnectionHelper( 3810): onConnected: Outgoing connection to peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT548]
D/io.jxcore.node.ConnectionHelper( 3810): hasConnection: No connection with peer with ID 08:EC:A9:50:76:27
W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT548] already in the list, will not add again
,I/io.jxcore.node.ConnectionHelper( 3810): onConnected: Outgoing socket thread, for peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT548], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3810): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 3810): onConnected: The total number of connections is now 2
,D/io.jxcore.node.OutgoingSocketThread( 3810): Entering thread (ID: 445)
,D/io.jxcore.node.OutgoingSocketThread( 3810): Server socket local port: 39541,
I/io.jxcore.node.OutgoingSocketThread( 3810): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 3810): onListeningForIncomingConnections: Outgoing connection is using port 39541 (peer ID: 08:EC:A9:50:76:27)
,I/jxcore-log( 3810): 2015-12-18T12:54:13.819Z SendDataConnector.js: CLIENT connected to 39541, error: null
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:54:13.821Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3810): 
,I/io.jxcore.node.OutgoingSocketThread( 3810): Incoming data from address: /127.0.0.1, port: 39541
,D/io.jxcore.node.OutgoingSocketThread( 3810): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3810): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread( 3810): setBufferSize: Setting buffer size to 8192 bytes
D/io.jxcore.node.StreamCopyingThread( 3810): Entering thread (ID: 446, name: Sender)
,I/io.jxcore.node.OutgoingSocketThread( 3810): startStreamCopyingThreads: OK
,D/io.jxcore.node.OutgoingSocketThread( 3810): Exiting thread (ID: 445)
D/io.jxcore.node.StreamCopyingThread( 3810): Entering thread (ID: 447, name: Receiver)
,I/jxcore-log( 3810): 2015-12-18T12:54:13.840Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3810): 
,D/        ( 2140): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23716
,I/jxcore-log( 3810): 2015-12-18T12:54:14.438Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3810): 
,D/        ( 2140): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:14806
,I/jxcore-log( 3810): 2015-12-18T12:54:14.494Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:54:14.503Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3810): 
,D/        ( 2140): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:8866
,I/jxcore-log( 3810): 2015-12-18T12:54:14.576Z SendDataConnector.js: CLIENT is data received : 40000,
I/jxcore-log( 3810): 
,D/        ( 2140): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:1936,
,I/jxcore-log( 3810): 2015-12-18T12:54:14.614Z SendDataConnector.js: CLIENT is data received : 50000,
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:54:14.654Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3810): 
,W/bt-btif ( 2140): dm_pm_timer expires
,W/bt-btif ( 2140): dm_pm_timer expires 0
W/bt-btif ( 2140): proc dm_pm_timer expires
,I/jxcore-log( 3810): 2015-12-18T12:54:14.723Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:54:14.762Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:54:14.803Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:54:14.891Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:54:14.896Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:54:14.900Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3810): 
I/jxcore-log( 3810): 2015-12-18T12:54:14.900Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3810): 
,D/io.jxcore.node.ConnectionHelper( 3810): disconnectOutgoingConnection: Trying to close connection to peer with ID 08:EC:A9:50:76:27
,I/io.jxcore.node.ConnectionHelper( 3810): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 08:EC:A9:50:76:27
,I/io.jxcore.node.OutgoingSocketThread( 3810): close,
D/io.jxcore.node.OutgoingSocketThread( 3810): close: Stopping receiving thread...
,I/io.jxcore.node.StreamCopyingThread( 3810): doStop: Thread ID: 447,
,D/io.jxcore.node.OutgoingSocketThread( 3810): close: Stopping sending thread...,
,I/io.jxcore.node.StreamCopyingThread( 3810): doStop: Thread ID: 446
D/io.jxcore.node.OutgoingSocketThread( 3810): closeLocalSocketAndStreams: Closing...,
,D/io.jxcore.node.OutgoingSocketThread( 3810): closeLocalSocketAndStreams: Closing the local input stream...
D/io.jxcore.node.OutgoingSocketThread( 3810): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 3810): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3810): closeBluetoothSocketAndStreams
W/io.jxcore.node.StreamCopyingThread( 3810): Either failed to read from the output stream or write to the input stream (thread ID: 446, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3810): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
,W/io.jxcore.node.StreamCopyingThread( 3810): Either failed to read from the output stream or write to the input stream (thread ID: 447, thread name: Receiver): bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3810): onDisconnected: Outgoing connection, peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT548] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3810): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3810): onDisconnected: Outgoing connection, peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT548] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
D/io.jxcore.node.ConnectionHelper( 3810): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3810): disconnectOutgoingConnection: Successfully disconnected (peer ID: 08:EC:A9:50:76:27
E/io.jxcore.node.ConnectionHelper( 3810): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:76:27
D/io.jxcore.node.ConnectionHelper( 3810): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3810): Exiting thread (ID: 446, name: Sender)
E/io.jxcore.node.ConnectionHelper( 3810): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:76:27
D/io.jxcore.node.ConnectionHelper( 3810): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,D/io.jxcore.node.StreamCopyingThread( 3810): Exiting thread (ID: 447, name: Receiver)
I/jxcore-log( 3810): 2015-12-18T12:54:14.907Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 3810): 
I/jxcore-log( 3810): ---- round done--------
I/jxcore-log( 3810): 
I/jxcore-log( 3810): do fake peer & start
I/jxcore-log( 3810): 
I/jxcore-log( 3810): Connect to fake peer: E0:DB:10:1F:C9:5E
I/jxcore-log( 3810): 
I/jxcore-log( 3810): 2015-12-18T12:54:14.909Z SendDataConnector.js: Start called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3810): 
I/jxcore-log( 3810): 2015-12-18T12:54:14.909Z SendDataConnector.js: doConnect called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3810): 
I/jxcore-log( 3810): 2015-12-18T12:54:14.909Z SendDataConnector.js: do connect now
I/jxcore-log( 3810): 
I/io.jxcore.node.ConnectionHelper( 3810): connect: Trying to connect to peer with ID E0:DB:10:1F:C9:5E
D/io.jxcore.node.ConnectionHelper( 3810): hasConnection: No connection with peer with ID E0:DB:10:1F:C9:5E
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3810): connect: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT9178]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3810): connect: Trying to start connecting to null in address E0:DB:10:1F:C9:5E
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3810): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3810): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3810): onConnecting: null E0:DB:10:1F:C9:5E
W/bt-btif ( 2140): bta_jv_rfc_port_to_cb(port_handle:0xd):jv handle:0x0 not FOUND
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3810): connect: Started connecting to null in address E0:DB:10:1F:C9:5E
I/io.jxcore.node.ConnectionHelper( 3810): connect: Connection process successfully started (peer ID: E0:DB:10:1F:C9:5E)
I/chromium( 3810): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 08:EC:A9:50:76:27 done with result: OK", source: file:///android_asset/www/js/thali_main.js (63)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3810): Trying to connect to peer with address E0:DB:10:1F:C9:5E (thread ID: 448)
W/BluetoothAdapter( 3810): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 2140): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/HeadsetStateMachine( 2140): Disconnected process message: 10, size: 0
,I/jxcore-log( 3810): 2015-12-18T12:54:15.883Z SendDataTCPServer.js: TCP/IP server has received 86228 bytes of data
I/jxcore-log( 3810): 
,D/btif_config_util( 2140): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3810): 2015-12-18T12:54:16.947Z SendDataTCPServer.js: TCP/IP server has received 88208 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:54:16.955Z SendDataTCPServer.js: TCP/IP server has received 90188 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:54:16.978Z SendDataTCPServer.js: TCP/IP server has received 92168 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:54:17.010Z SendDataTCPServer.js: TCP/IP server has received 94148 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:54:17.035Z SendDataTCPServer.js: TCP/IP server has received 96128 bytes of data,
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:54:17.064Z SendDataTCPServer.js: TCP/IP server has received 98108 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:54:17.086Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3810): 
,W/bt-btif ( 2140): invalid rfc slot id: 10
W/io.jxcore.node.StreamCopyingThread( 3810): Either failed to read from the output stream or write to the input stream (thread ID: 442, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 3810): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3810): onDisconnected: Incoming connection, peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3810): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 440
D/io.jxcore.node.OutgoingSocketThread( 3810): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3810): doStop: Thread ID: 442
,D/io.jxcore.node.OutgoingSocketThread( 3810): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3810): doStop: Thread ID: 441
D/io.jxcore.node.OutgoingSocketThread( 3810): closeLocalSocketAndStreams: Closing...
,D/io.jxcore.node.OutgoingSocketThread( 3810): closeLocalSocketAndStreams: Closing the local input stream...
D/io.jxcore.node.OutgoingSocketThread( 3810): closeLocalSocketAndStreams: Closing the local output stream...
W/io.jxcore.node.StreamCopyingThread( 3810): Either failed to read from the output stream or write to the input stream (thread ID: 441, thread name: Sender): Socket closed
,D/io.jxcore.node.OutgoingSocketThread( 3810): closeLocalSocketAndStreams: Closing the localhost socket...
E/io.jxcore.node.OutgoingSocketThread( 3810): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
I/io.jxcore.node.OutgoingSocketThread( 3810): closeBluetoothSocketAndStreams
W/io.jxcore.node.ConnectionHelper( 3810): onDisconnected: Incoming connection, peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.ConnectionHelper( 3810): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3810): Exiting thread (ID: 442, name: Receiver)
D/io.jxcore.node.ConnectionHelper( 3810): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3810): Exiting thread (ID: 441, name: Sender)
I/jxcore-log( 3810): 2015-12-18T12:54:17.167Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3810): 
,W/bt-rfcomm( 2140): rfc_find_lcid_mcb LCID reused LCID:0x4a current:0x0,
W/bt-rfcomm( 2140): RFCOMM_DisconnectInd LCID:0x4a
,E/bt-btm  ( 2140): tBTM_SEC_DEV:0xa2fd5eb4 rs_disc_pending=0,
W/bt-btif ( 2140): bta_dm_check_av:0
W/bt-btif ( 2140): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT5199","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199],
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], Bluetooth address: 58:3F:54:73:64:C0, device name: , device address: 02:9a:02:7b:60:ac
W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199] already in the list, will not add again
,E/bt-btm  ( 2140): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2140): onReceive
,I/BTConnectionReceiver( 1515): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1515): Bluetooth Device Name: Thali Test (Galaxy A3),
,E/bt-btm  ( 2140): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2140): onReceive
,I/BTConnectionReceiver( 1515): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1515): Bluetooth Device Name: G3s-1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3810): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3810): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3810): setState: RESTARTING
,I/wpa_supplicant( 1190): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1190): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
,I/wpa_supplicant( 1190): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3810): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3810): Connection timeout
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3810): onConnectionTimeout: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT9178]
,I/jxcore-log( 3810): 2015-12-18T12:54:29.917Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT9178] timed out
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:54:29.918Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT9178] timed out
I/jxcore-log( 3810): 
I/jxcore-log( 3810): 2015-12-18T12:54:29.919Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3810): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3810): Start timer timeout, starting now...,
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3810): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3810): setState: STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3810): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1190): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT9205], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT9205]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): restart: Restarting...
,D/WifiP2pManager( 3810): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): Service request added successfully
,I/wpa_supplicant( 1190): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): Service discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT9205","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT9205]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT9205]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT9205]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT9205], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT9205]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT9205], Bluetooth address: 90:E7:C4:F6:69:77, device name: Android_608e, device address: 92:e7:c4:e6:4c:f8
W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT9205] already in the list, will not add again
,I/jxcore-log( 3810): 2015-12-18T12:54:34.920Z SendDataConnector.js: re-try now : E0:DB:10:1F:C9:5E
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:54:34.920Z SendDataConnector.js: ReStart called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3810): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT548","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT548]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT548]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT548]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT548], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT548]
,I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT548], Bluetooth address: 08:EC:A9:50:76:27, device name: , device address: 0a:ec:a9:50:76:28
W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT548] already in the list, will not add again
,D/HeadsetStateMachine( 2140): Disconnected process message: 10, size: 0
,D/io.jxcore.node.ConnectionHelper( 3810): disconnectOutgoingConnection: Trying to close connection to peer with ID E0:DB:10:1F:C9:5E
E/io.jxcore.node.ConnectionHelper( 3810): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID E0:DB:10:1F:C9:5E
D/io.jxcore.node.ConnectionHelper( 3810): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3810): disconnectOutgoingConnection: Failed to disconnect (peer ID: E0:DB:10:1F:C9:5E), either no such connection or failed to close the connection
,I/jxcore-log( 3810): 2015-12-18T12:54:39.930Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3810): 
I/jxcore-log( 3810): 2015-12-18T12:54:39.930Z SendDataConnector.js: Connect (retry count 1) to peer E0:DB:10:1F:C9:5E with availability status: true
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:54:39.931Z SendDataConnector.js: doConnect called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3810): 
I/jxcore-log( 3810): 2015-12-18T12:54:39.932Z SendDataConnector.js: do connect now
I/jxcore-log( 3810): 
,I/io.jxcore.node.ConnectionHelper( 3810): connect: Trying to connect to peer with ID E0:DB:10:1F:C9:5E
,D/io.jxcore.node.ConnectionHelper( 3810): hasConnection: No connection with peer with ID E0:DB:10:1F:C9:5E
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3810): connect: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT9178]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3810): connect: Trying to start connecting to null in address E0:DB:10:1F:C9:5E,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3810): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3810): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3810): onConnecting: null E0:DB:10:1F:C9:5E
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3810): connect: Started connecting to null in address E0:DB:10:1F:C9:5E
I/io.jxcore.node.ConnectionHelper( 3810): connect: Connection process successfully started (peer ID: E0:DB:10:1F:C9:5E)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3810): Trying to connect to peer with address E0:DB:10:1F:C9:5E (thread ID: 450)
W/BluetoothAdapter( 3810): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 2140): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT9700","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700] already in the list, will not add again
,I/wpa_supplicant( 1190): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 2 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT9205], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT9205]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT103","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local.",
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT103]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT103]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT103]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT103], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT103]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT103], Bluetooth address: 08:EC:A9:50:75:41, device name: , device address: 0a:ec:a9:50:75:42
W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT103] already in the list, will not add again
,W/bt-sdp  ( 2140): SDP - Rcvd conn cnf with error: 0x22  CID 0x4f
E/bt-btif ( 2140): DISCOVERY_COMP_EVT slot id:14, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2140): invalid rfc slot id: 14
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3810): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 448)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3810): shutdown (thread ID: 448)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3810): Maximum number of allowed retries (0) reached, giving up... (thread ID: 448)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3810): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3810): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT9178]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3810): Exiting thread (thread ID: 448)
,I/jxcore-log( 3810): 2015-12-18T12:54:45.390Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT9178] failed
I/jxcore-log( 3810): 
I/jxcore-log( 3810): 2015-12-18T12:54:45.392Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT9178] failed
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:54:45.392Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3810): 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3810): setInsecureRfcommSocketPort: Will use port 1 when trying to connect
,W/bt-btif ( 2140): info:x10
,D/        ( 2140): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1515): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1515): Bluetooth Device Name: Thali Test (Galaxy A3)
,W/bt-btif ( 2140): new conn_srvc id:26, app_id:255
W/bt-btif ( 2140): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 2140): bta_dm_pm_ssr:2, lat:1200
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3810): Incoming connection accepted
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3810): Incoming connection initialized (thread ID: 452)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3810): Waiting for incoming connections...
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3810): Entering thread (ID: 452)
,E/bt-btm  ( 2140): tBTM_SEC_DEV:0xa2fd5eb4 rs_disc_pending=0
,W/bt-btif ( 2140): bta_dm_check_av:0
W/bt-btif ( 2140): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 1190): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT548], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT548]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT9205], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT9205]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): restart: Restarting...
,D/WifiP2pManager( 3810): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): Service request added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3810): onBytesRead: Read 82 bytes successfully (thread ID: 452)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3810): Got valid identity from [08:EC:A9:50:76:27 samsung-SM-A300FU_PT548]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3810): onBytesWritten: 82 bytes successfully written (thread ID: 452),
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3810): removeThreadFromList: Removing thread with ID 452
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3810): Handshake thread disposed (thread ID: 452)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3810): onIncomingConnectionConnected: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT548]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3810): Exiting thread (ID: 452)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3810): onConnected: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT548]
I/io.jxcore.node.ConnectionHelper( 3810): onConnected: Incoming connection to peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT548]
D/io.jxcore.node.ConnectionHelper( 3810): hasConnection: No connection with peer with ID 08:EC:A9:50:76:27
W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT548] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 3810): onConnected: Incoming socket thread, for peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT548], created successfully
D/io.jxcore.node.ConnectionHelper( 3810): onConnected: The total number of connections is now 1
D/io.jxcore.node.IncomingSocketThread( 3810): Entering thread (ID: 453)
,I/io.jxcore.node.IncomingSocketThread( 3810): Local host address: localhost/127.0.0.1, port: 41534
D/io.jxcore.node.IncomingSocketThread( 3810): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3810): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread( 3810): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 3810): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3810): Exiting thread (ID: 453)
D/io.jxcore.node.StreamCopyingThread( 3810): Entering thread (ID: 454, name: Sender)
,I/jxcore-log( 3810): 2015-12-18T12:54:47.822Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3810): 
,D/io.jxcore.node.StreamCopyingThread( 3810): Entering thread (ID: 455, name: Receiver)
,I/jxcore-log( 3810): 2015-12-18T12:54:48.609Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3810): 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): Service discovery started successfully
,I/jxcore-log( 3810): 2015-12-18T12:54:48.679Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:54:48.796Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data,
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:54:48.805Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:54:48.829Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:54:48.914Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:54:48.975Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:54:49.009Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:54:49.051Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:54:49.087Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:54:49.104Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:54:49.140Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:54:49.143Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:54:49.151Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:54:49.189Z SendDataTCPServer.js: TCP/IP server has received 32768 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:54:49.196Z SendDataTCPServer.js: TCP/IP server has received 34748 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:54:49.216Z SendDataTCPServer.js: TCP/IP server has received 36728 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:54:49.224Z SendDataTCPServer.js: TCP/IP server has received 38708 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:54:49.234Z SendDataTCPServer.js: TCP/IP server has received 40688 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:54:49.242Z SendDataTCPServer.js: TCP/IP server has received 42668 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:54:49.279Z SendDataTCPServer.js: TCP/IP server has received 46628 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:54:49.284Z SendDataTCPServer.js: TCP/IP server has received 48608 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:54:49.302Z SendDataTCPServer.js: TCP/IP server has received 50588 bytes of data
I/jxcore-log( 3810): 
,D/btif_config_util( 2140): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3810): 2015-12-18T12:54:49.342Z SendDataTCPServer.js: TCP/IP server has received 52568 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:54:49.378Z SendDataTCPServer.js: TCP/IP server has received 56528 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:54:49.388Z SendDataTCPServer.js: TCP/IP server has received 58508 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:54:49.396Z SendDataTCPServer.js: TCP/IP server has received 60488 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:54:49.406Z SendDataTCPServer.js: TCP/IP server has received 62468 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:54:49.439Z SendDataTCPServer.js: TCP/IP server has received 64448 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:54:49.494Z SendDataTCPServer.js: TCP/IP server has received 66428 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:54:49.503Z SendDataTCPServer.js: TCP/IP server has received 68408 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:54:49.512Z SendDataTCPServer.js: TCP/IP server has received 70388 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:54:49.526Z SendDataTCPServer.js: TCP/IP server has received 72368 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:54:49.539Z SendDataTCPServer.js: TCP/IP server has received 74348 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:54:49.569Z SendDataTCPServer.js: TCP/IP server has received 76328 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:54:49.574Z SendDataTCPServer.js: TCP/IP server has received 78308 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:54:49.580Z SendDataTCPServer.js: TCP/IP server has received 80288 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:54:49.592Z SendDataTCPServer.js: TCP/IP server has received 82268 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:54:49.675Z SendDataTCPServer.js: TCP/IP server has received 84248 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:54:49.684Z SendDataTCPServer.js: TCP/IP server has received 86228 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:54:49.693Z SendDataTCPServer.js: TCP/IP server has received 88208 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:54:49.751Z SendDataTCPServer.js: TCP/IP server has received 90188 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:54:49.759Z SendDataTCPServer.js: TCP/IP server has received 92168 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:54:49.799Z SendDataTCPServer.js: TCP/IP server has received 94148 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:54:49.836Z SendDataTCPServer.js: TCP/IP server has received 96128 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:54:49.846Z SendDataTCPServer.js: TCP/IP server has received 98108 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:54:49.879Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3810): 
,W/bt-btif ( 2140): invalid rfc slot id: 11
W/io.jxcore.node.StreamCopyingThread( 3810): Either failed to read from the output stream or write to the input stream (thread ID: 455, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.IncomingSocketThread( 3810): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3810): onDisconnected: Incoming connection, peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT548] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3810): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 453
D/io.jxcore.node.IncomingSocketThread( 3810): close: Stopping receiving thread...
,I/io.jxcore.node.StreamCopyingThread( 3810): doStop: Thread ID: 455
D/io.jxcore.node.IncomingSocketThread( 3810): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3810): doStop: Thread ID: 454
D/io.jxcore.node.IncomingSocketThread( 3810): closeLocalSocketAndStreams: Closing...
,D/io.jxcore.node.IncomingSocketThread( 3810): closeLocalSocketAndStreams: Closing the local input stream...
W/io.jxcore.node.StreamCopyingThread( 3810): Either failed to read from the output stream or write to the input stream (thread ID: 454, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3810): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
,W/io.jxcore.node.ConnectionHelper( 3810): onDisconnected: Incoming connection, peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT548] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.IncomingSocketThread( 3810): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 3810): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 3810): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3810): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,D/io.jxcore.node.ConnectionHelper( 3810): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3810): Exiting thread (ID: 454, name: Sender)
D/io.jxcore.node.StreamCopyingThread( 3810): Exiting thread (ID: 455, name: Receiver)
W/bt-rfcomm( 2140): rfc_find_lcid_mcb LCID reused LCID:0x42 current:0x0
W/bt-rfcomm( 2140): RFCOMM_DisconnectInd LCID:0x42
,I/jxcore-log( 3810): 2015-12-18T12:54:49.974Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:54:50.394Z SendDataConnector.js: re-try now : E0:DB:10:1F:C9:5E
,I/jxcore-log( 3810): 
I/jxcore-log( 3810): 2015-12-18T12:54:50.395Z SendDataConnector.js: ReStart called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3810): 
,E/bt-btm  ( 2140): btm_sec_disconnected - Clearing Pending flag,
,D/BluetoothMapService( 2140): onReceive,
,I/BTConnectionReceiver( 1515): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1515): Bluetooth Device Name: Thali Test (Galaxy A3),
,D/io.jxcore.node.ConnectionHelper( 3810): disconnectOutgoingConnection: Trying to close connection to peer with ID E0:DB:10:1F:C9:5E
E/io.jxcore.node.ConnectionHelper( 3810): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID E0:DB:10:1F:C9:5E
D/io.jxcore.node.ConnectionHelper( 3810): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3810): disconnectOutgoingConnection: Failed to disconnect (peer ID: E0:DB:10:1F:C9:5E), either no such connection or failed to close the connection
,I/jxcore-log( 3810): 2015-12-18T12:54:55.399Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:1F:C9:5E,
I/jxcore-log( 3810): 
I/jxcore-log( 3810): 2015-12-18T12:54:55.400Z SendDataConnector.js: Connect (retry count 2) to peer E0:DB:10:1F:C9:5E with availability status: true
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:54:55.401Z SendDataConnector.js: doConnect called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3810): 
I/jxcore-log( 3810): 2015-12-18T12:54:55.402Z SendDataConnector.js: do connect now
I/jxcore-log( 3810): 
I/io.jxcore.node.ConnectionHelper( 3810): connect: Trying to connect to peer with ID E0:DB:10:1F:C9:5E
,D/io.jxcore.node.ConnectionHelper( 3810): hasConnection: No connection with peer with ID E0:DB:10:1F:C9:5E
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3810): connect: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT9178]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3810): connect: Trying to start connecting to null in address E0:DB:10:1F:C9:5E
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3810): setInsecureRfcommSocketPort: Using port 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3810): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3810): onConnecting: null E0:DB:10:1F:C9:5E
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3810): connect: Started connecting to null in address E0:DB:10:1F:C9:5E
I/io.jxcore.node.ConnectionHelper( 3810): connect: Connection process successfully started (peer ID: E0:DB:10:1F:C9:5E)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3810): Trying to connect to peer with address E0:DB:10:1F:C9:5E (thread ID: 456)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3810): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
,W/BluetoothAdapter( 3810): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2140): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT103","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT103]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT103]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT103]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT103], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT103]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT103], Bluetooth address: 08:EC:A9:50:75:41, device name: , device address: 0a:ec:a9:50:75:42
,W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT103] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT9700","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
,W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700] already in the list, will not add again
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): checkListForExpiredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3565] expired
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): checkListForExpiredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778] expired
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): checkListForExpiredPeers: Peer [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT9178] expired
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3565], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Removed [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3565]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Removed [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT9178], add/update: false
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Removed [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT9178]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerLost: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3565]
D/io.jxcore.node.ConnectionHelper( 3810): hasConnection: No connection with peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3565] removed
D/io.jxcore.node.ConnectionHelper( 3810): notifyPeerAvailability: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3565] not available
,I/io.jxcore.node.ConnectionHelper( 3810): onPeerLost: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/io.jxcore.node.ConnectionHelper( 3810): hasConnection: No connection with peer with ID 7C:F9:0E:34:8A:A0
D/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778] removed
D/io.jxcore.node.ConnectionHelper( 3810): notifyPeerAvailability: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778] not available
I/io.jxcore.node.ConnectionHelper( 3810): onPeerLost: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT9178]
D/io.jxcore.node.ConnectionHelper( 3810): hasConnection: No connection with peer with ID E0:DB:10:1F:C9:5E
,D/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT9178] removed
D/io.jxcore.node.ConnectionHelper( 3810): notifyPeerAvailability: Peer [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT9178] not available
,W/bt-sdp  ( 2140): SDP - Rcvd conn cnf with error: 0x8  CID 0x40
E/bt-btif ( 2140): DISCOVERY_COMP_EVT slot id:15, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2140): invalid rfc slot id: 15
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3810): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 450)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3810): Maximum number of allowed retries (0) reached, giving up... (thread ID: 450)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3810): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3810): Exiting thread (thread ID: 450)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3810): shutdown (thread ID: 450)
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3810): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT9178]
,I/jxcore-log( 3810): 2015-12-18T12:55:09.462Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT9178] failed
I/jxcore-log( 3810): 
I/jxcore-log( 3810): 2015-12-18T12:55:09.462Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT9178] failed
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:55:09.463Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3810): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3810): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
,I/jxcore-log( 3810): 2015-12-18T12:55:14.463Z SendDataConnector.js: re-try now : E0:DB:10:1F:C9:5E
I/jxcore-log( 3810): 
I/jxcore-log( 3810): 2015-12-18T12:55:14.464Z SendDataConnector.js: ReStart called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3810): 
,D/HeadsetStateMachine( 2140): Disconnected process message: 10, size: 0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3810): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3810): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3810): setState: RESTARTING
,I/wpa_supplicant( 1190): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1190): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 1190): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
,I/wpa_supplicant( 1190): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3810): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 0 device(s) discovered
,D/io.jxcore.node.ConnectionHelper( 3810): disconnectOutgoingConnection: Trying to close connection to peer with ID E0:DB:10:1F:C9:5E
E/io.jxcore.node.ConnectionHelper( 3810): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID E0:DB:10:1F:C9:5E
D/io.jxcore.node.ConnectionHelper( 3810): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3810): disconnectOutgoingConnection: Failed to disconnect (peer ID: E0:DB:10:1F:C9:5E), either no such connection or failed to close the connection
I/jxcore-log( 3810): 2015-12-18T12:55:19.472Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:55:19.473Z SendDataConnector.js: Connect (retry count 3) to peer E0:DB:10:1F:C9:5E with availability status: true
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:55:19.474Z SendDataConnector.js: doConnect called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3810): 
I/jxcore-log( 3810): 2015-12-18T12:55:19.475Z SendDataConnector.js: do connect now
I/jxcore-log( 3810): 
I/io.jxcore.node.ConnectionHelper( 3810): connect: Trying to connect to peer with ID E0:DB:10:1F:C9:5E
D/io.jxcore.node.ConnectionHelper( 3810): hasConnection: No connection with peer with ID E0:DB:10:1F:C9:5E
W/io.jxcore.node.ConnectionHelper( 3810): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3810): connect: [E0:DB:10:1F:C9:5E E0:DB:10:1F:C9:5E]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3810): connect: Trying to start connecting to null in address E0:DB:10:1F:C9:5E,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3810): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3810): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3810): onConnecting: null E0:DB:10:1F:C9:5E
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3810): connect: Started connecting to null in address E0:DB:10:1F:C9:5E
I/io.jxcore.node.ConnectionHelper( 3810): connect: Connection process successfully started (peer ID: E0:DB:10:1F:C9:5E)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3810): Trying to connect to peer with address E0:DB:10:1F:C9:5E (thread ID: 458)
,W/BluetoothAdapter( 3810): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 2140): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3810): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3810): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3810): setState: STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3810): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1190): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): restart: Restarting...
,D/WifiP2pManager( 3810): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): Service request added successfully
,I/wpa_supplicant( 1190): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): Service discovery started successfully
,I/wpa_supplicant( 1190): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 2 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT9700","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4778","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
,D/io.jxcore.node.ConnectionHelper( 3810): notifyPeerAvailability: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778] is available
,I/wpa_supplicant( 1190): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 3 device(s) discovered,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT103], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT103]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT103","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local.",
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT103]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT103]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT103]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT103], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT103]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT103], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
,W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT103] already in the list, will not add again
,I/wpa_supplicant( 1190): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 2: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT103], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT103]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT3565","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3565]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3565]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3565]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3565], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3565]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3565], Bluetooth address: 7C:F9:0E:37:96:AB, device name: , device address: 7e:f9:0e:37:96:ac
D/io.jxcore.node.ConnectionHelper( 3810): notifyPeerAvailability: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3565] is available
,I/wpa_supplicant( 1190): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 5 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778],
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 3: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT103], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT103]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT3932","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3932]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3932]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3932]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3932], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Adding new peer: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3932]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3932], Bluetooth address: E0:DB:10:14:E2:C0, device name: Note4-1, device address: 92:b6:86:43:73:1c
,W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3932] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3810): Connection timeout,
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3810): onConnectionTimeout: [E0:DB:10:1F:C9:5E E0:DB:10:1F:C9:5E],
I/jxcore-log( 3810): 2015-12-18T12:55:34.486Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [E0:DB:10:1F:C9:5E E0:DB:10:1F:C9:5E] timed out
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:55:34.487Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [E0:DB:10:1F:C9:5E E0:DB:10:1F:C9:5E] timed out
I/jxcore-log( 3810): 
I/jxcore-log( 3810): 2015-12-18T12:55:34.488Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3810): 
,D/HeadsetStateMachine( 2140): Disconnected process message: 10, size: 0
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): checkListForExpiredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: false
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Removed [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
,I/io.jxcore.node.ConnectionHelper( 3810): onPeerLost: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
,D/io.jxcore.node.ConnectionHelper( 3810): hasConnection: No connection with peer with ID 58:3F:54:73:64:C0
D/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199] removed
,D/io.jxcore.node.ConnectionHelper( 3810): notifyPeerAvailability: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199] not available
,I/jxcore-log( 3810): 2015-12-18T12:55:39.490Z SendDataConnector.js: re-try now : E0:DB:10:1F:C9:5E,
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:55:39.491Z SendDataConnector.js: ReStart called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3810): 
,W/bt-sdp  ( 2140): SDP - Rcvd conn cnf with error: 0x22  CID 0x44
,E/bt-btif ( 2140): DISCOVERY_COMP_EVT slot id:17, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2140): invalid rfc slot id: 17
W/BluetoothAdapter( 3810): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2140): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66,
I/wpa_supplicant( 1190): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1190): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 6 device(s) discovered,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3932], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3932],
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 4: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT103], add/update: true,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT103]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 6 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3932], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3932]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 4: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT103], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT103]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/WifiP2pManager( 3810): Ignored { when=-4ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): Service request added successfully
,I/wpa_supplicant( 1190): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): Service discovery started successfully
,D/io.jxcore.node.ConnectionHelper( 3810): disconnectOutgoingConnection: Trying to close connection to peer with ID E0:DB:10:1F:C9:5E,
E/io.jxcore.node.ConnectionHelper( 3810): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID E0:DB:10:1F:C9:5E
,D/io.jxcore.node.ConnectionHelper( 3810): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3810): disconnectOutgoingConnection: Failed to disconnect (peer ID: E0:DB:10:1F:C9:5E), either no such connection or failed to close the connection
I/jxcore-log( 3810): 2015-12-18T12:55:44.495Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3810): 
I/jxcore-log( 3810): 2015-12-18T12:55:44.496Z SendDataConnector.js: Connect (retry count 4) to peer E0:DB:10:1F:C9:5E with availability status: true
,I/jxcore-log( 3810): 
I/jxcore-log( 3810): 2015-12-18T12:55:44.496Z SendDataConnector.js: doConnect called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3810): 
I/jxcore-log( 3810): 2015-12-18T12:55:44.497Z SendDataConnector.js: do connect now
I/jxcore-log( 3810): 
,I/io.jxcore.node.ConnectionHelper( 3810): connect: Trying to connect to peer with ID E0:DB:10:1F:C9:5E
,D/io.jxcore.node.ConnectionHelper( 3810): hasConnection: No connection with peer with ID E0:DB:10:1F:C9:5E,
W/io.jxcore.node.ConnectionHelper( 3810): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3810): connect: [E0:DB:10:1F:C9:5E E0:DB:10:1F:C9:5E]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3810): connect: Trying to start connecting to null in address E0:DB:10:1F:C9:5E
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3810): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3810): setMaxNumberOfRetries: 0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3810): onConnecting: null E0:DB:10:1F:C9:5E
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3810): connect: Started connecting to null in address E0:DB:10:1F:C9:5E
,I/io.jxcore.node.ConnectionHelper( 3810): connect: Connection process successfully started (peer ID: E0:DB:10:1F:C9:5E)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3810): Trying to connect to peer with address E0:DB:10:1F:C9:5E (thread ID: 461)
W/BluetoothAdapter( 3810): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 2140): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT9178","ra":"E0:DB:10:1F:C9:5E"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT9178]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT9178]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT9178]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT9178], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Adding new peer: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT9178]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT9178], Bluetooth address: E0:DB:10:1F:C9:5E, device name: , device address: ea:50:8b:de:28:a3
D/io.jxcore.node.ConnectionHelper( 3810): notifyPeerAvailability: Peer [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT9178] is available
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT3565","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3565]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3565]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3565]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3565], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3565]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3565], Bluetooth address: 7C:F9:0E:37:96:AB, device name: , device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3565] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT8301","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Adding new peer: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301], Bluetooth address: 34:FC:EF:11:AE:67, device name: Android_8ae2, device address: 52:55:27:f0:fd:0b
W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT9700","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4778","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778] already in the list, will not add again
,I/wpa_supplicant( 1190): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1190): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 7 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3932], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3932]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 5: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3932], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3932]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 5: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,--------- beginning of crash
,F/libc    ( 1190): Fatal signal 11 (SIGSEGV), code 1, fault addr 0xc in tid 1190 (wpa_supplicant)
I/libc    ( 1190): Suppressing debuggerd output because prctl(PR_GET_DUMPABLE)==0
,D/WifiP2pManager( 3810): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): Service request added successfully
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): Failed to start the service discovery, got error code: 3
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3810): Connection timeout
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3810): onConnectionTimeout: [E0:DB:10:1F:C9:5E E0:DB:10:1F:C9:5E]
,I/jxcore-log( 3810): 2015-12-18T12:55:59.512Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [E0:DB:10:1F:C9:5E E0:DB:10:1F:C9:5E] timed out
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:55:59.513Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [E0:DB:10:1F:C9:5E E0:DB:10:1F:C9:5E] timed out
I/jxcore-log( 3810): 
I/jxcore-log( 3810): 2015-12-18T12:55:59.518Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3810): 
D/io.jxcore.node.ConnectionHelper( 3810): disconnectOutgoingConnection: Trying to close connection to peer with ID E0:DB:10:1F:C9:5E
E/io.jxcore.node.ConnectionHelper( 3810): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID E0:DB:10:1F:C9:5E
D/io.jxcore.node.ConnectionHelper( 3810): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3810): disconnectOutgoingConnection: Failed to disconnect (peer ID: E0:DB:10:1F:C9:5E), either no such connection or failed to close the connection
,I/jxcore-log( 3810): 2015-12-18T12:55:59.525Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3810): 
I/jxcore-log( 3810): ---- round done--------
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): ---- gotta redo : E0:DB:10:1F:C9:5E, try count now: 1
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): do fake peer & start
I/jxcore-log( 3810): 
I/jxcore-log( 3810): Connect to fake peer: 7C:F9:0E:37:96:AB
I/jxcore-log( 3810): 
I/jxcore-log( 3810): 2015-12-18T12:55:59.529Z SendDataConnector.js: Start called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3810): 
I/jxcore-log( 3810): 2015-12-18T12:55:59.529Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:55:59.529Z SendDataConnector.js: do connect now
I/jxcore-log( 3810): 
I/io.jxcore.node.ConnectionHelper( 3810): connect: Trying to connect to peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 3810): hasConnection: No connection with peer with ID 7C:F9:0E:37:96:AB
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3810): connect: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3565]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3810): connect: Trying to start connecting to null in address 7C:F9:0E:37:96:AB
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3810): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3810): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3810): onConnecting: null 7C:F9:0E:37:96:AB
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3810): connect: Started connecting to null in address 7C:F9:0E:37:96:AB
I/io.jxcore.node.ConnectionHelper( 3810): connect: Connection process successfully started (peer ID: 7C:F9:0E:37:96:AB)
I/chromium( 3810): [INFO:CONSOLE(63)] "logCallback Round of send data to peer E0:DB:10:1F:C9:5E done with result: Connection to peer [E0:DB:10:1F:C9:5E E0:DB:10:1F:C9:5E] timed out", source: file:///android_asset/www/js/thali_main.js (63)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3810): Trying to connect to peer with address 7C:F9:0E:37:96:AB (thread ID: 463)
W/BluetoothAdapter( 3810): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2140): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): checkListForExpiredPeers: Peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT9205] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT9205], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Removed [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT9205]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerLost: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT9205]
D/io.jxcore.node.ConnectionHelper( 3810): hasConnection: No connection with peer with ID 90:E7:C4:F6:69:77
D/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT9205] removed
D/io.jxcore.node.ConnectionHelper( 3810): notifyPeerAvailability: Peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT9205] not available
,W/bt-sdp  ( 2140): SDP - Rcvd conn cnf with error: 0x22  CID 0x46,
E/bt-btif ( 2140): DISCOVERY_COMP_EVT slot id:18, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2140): invalid rfc slot id: 18
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3810): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 458)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3810): Maximum number of allowed retries (0) reached, giving up... (thread ID: 458)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3810): shutdown (thread ID: 458)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3810): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3810): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [E0:DB:10:1F:C9:5E E0:DB:10:1F:C9:5E]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3810): setInsecureRfcommSocketPort: Will use port 1 when trying to connect
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3810): Exiting thread (thread ID: 458)
,D/HeadsetStateMachine( 2140): Disconnected process message: 10, size: 0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3810): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3810): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3810): setState: RESTARTING
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3810): Failed to shutdown P2P device discovery, got error code: 0
,E/WifiStateMachine(  823): Connection lost, restart supplicant
,E/WifiMonitor(  823): killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,W/Settings( 3869): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,E/WifiConfigStore(  823): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any,
E/WifiConfigStore(  823): failed to set BSSID: any
E/native  (  823): do suspend true
W/Settings( 1773): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.,
,D/CommandListener(  355): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1267): Read error: ssl=0xaece2600: I/O error during system call, Connection timed out
,V/NativeCrypto( 1267): SSL shutdown failed: ssl=0xaece2600: I/O error during system call, Broken pipe
,I/jxcore-log( 3810): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 3810): 
I/jxcore-log( 3810): The Coordinator has disconnected!
I/jxcore-log( 3810): 
,D/ConnectivityService(  823): reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10011
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  823): ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  823): DefaultState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  823): Forcing reevaluation
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  823): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  823): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  823): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
,D/ConnectivityService(  823): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/ConnectivityService(  823): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
E/WifiStateMachine(  823): WifiStateMachine: Leaving Connected state
E/WifiStateMachine(  823): Unexpected BatchedScanResults :null
D/ConnectivityService(  823): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  823): NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
,D/WifiScanningService(  823): SCAN_AVAILABLE : 1
D/RttService(  823): SCAN_AVAILABLE : 1
D/WifiScanningService(  823): StartedState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService(  823): DefaultState
D/RttService(  823): EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3810): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 0 device(s) discovered
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onWifiStateChanged: State changed to 1
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onWifiStateChanged: Wi-Fi disabled, pausing Wi-Fi Direct based peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): stop: Stopping services
,D/WifiNetworkAgent(  823): NetworkAgent: NetworkAgent channel lost
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3810): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3810): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): stopWifiPeerDiscovery: Stopped
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): setState: WAITING_FOR_SERVICES_TO_BE_ENABLED
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3810): Failed to clear local services, got error code: 2
I/io.jxcore.node.ConnectionHelper( 3810): onDiscoveryManagerStateChanged: WAITING_FOR_SERVICES_TO_BE_ENABLED
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3810): Failed to shutdown P2P device discovery, got error code: 2
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): Failed to clear service requests, got error code: 2
,D/ConnectivityService(  823): notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,D/CSLegacyTypeTracker(  823): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  823): OfflineState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  823): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 1073): CM callback handler got msg 524292
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  823): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  823): Disconnected - quitting
D/ConnectivityService(  823): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  823): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/Tethering(  823): MasterInitialState.processMessage what=3
,D/ConnectivityService(  823): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  823): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,V/MusicLeanback( 3902): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/art     (  823): Explicit concurrent mark sweep GC freed 51734(2MB) AllocSpace objects, 10(537KB) LOS objects, 31% free, 34MB/50MB, paused 1.114ms total 74.459ms
,D/Tethering(  823): MasterInitialState.processMessage what=3
,D/PhoneInterfaceManager( 1338): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1338): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  823): getDataEnabled: retVal=false
,D/SprintDMReceiver( 3959): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,E/GpsLocationProvider(  823): No APN found to select.
,D/SprintDMHelper( 3959): simOperator:  IMSI: null
D/SprintDMReceiver( 3959): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1805): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/PhoneInterfaceManager( 1338): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1338): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  823): getDataEnabled: retVal=false
,D/SystemUpdateService( 1805): onCreate
,E/GpsLocationProvider(  823): No APN found to select.
,D/SystemUpdateService( 1805): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1805): active receiver: enabled
,I/SystemUpdateService( 1805): showing system update notification
,I/iu.Environment( 1805): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1805): num queued entries: 0
I/ValidateNoPeople(  823): skipping global notification
,I/iu.UploadsManager( 1805): num updated entries: 0
,D/ChimeraCfgMgr( 1805): Loading module com.google.android.gms.kids from APK com.google.android.gms
I/iu.SyncManager( 1805): NEXT; no task
,V/SystemUpdateService( 1805): retry (wakeup: false) in 3599979 ms
,D/SystemUpdateService( 1805): onDestroy
,I/Babel   ( 3869): connection state changed from CONNECTED to DISCONNECTED
,V/MusicLeanback( 3902): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/SprintDMReceiver( 3959): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3959): simOperator:  IMSI: null
D/SprintDMReceiver( 3959): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1805): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1805): onCreate
,D/SystemUpdateService( 1805): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1805): active receiver: enabled
,I/SystemUpdateService( 1805): showing system update notification
,D/ChimeraCfgMgr( 1805): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/ValidateNoPeople(  823): skipping global notification
,V/SystemUpdateService( 1805): retry (wakeup: false) in 3599972 ms
,D/SystemUpdateService( 1805): onDestroy
,I/jxcore-log( 3810): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): Error type "connect_error" when connecting to the test server
I/jxcore-log( 3810): 
,D/WifiService(  823): setWifiEnabled: false pid=3810, uid=10265
E/WifiService(  823): Invoking mWifiStateMachine.setWifiEnabled
,D/WifiService(  823): setWifiEnabled: true pid=3810, uid=10265
,E/WifiService(  823): Invoking mWifiStateMachine.setWifiEnabled
,D/WifiController(  823): WifiController msg { when=0 what=155656 target=com.android.internal.util.StateMachine$SmHandler } deferred for 484ms
,I/jxcore-log( 3810): Wifi toggled for connection repairment
,I/jxcore-log( 3810): 
,I/chromium( 3810): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,D/WifiController(  823): DEFERRED_TOGGLE handled
,D/SoftapController(  355): Softap fwReload - Ok
,D/CommandListener(  355): Setting iface cfg
,D/CommandListener(  355): Trying to bring down wlan0
,D/Tethering(  823): InitialState.processMessage what=4
,D/CommandListener(  355): Clearing all IP addresses on wlan0
,D/Tethering(  823): sendTetherStateChangedBroadcast 0, 0, 0
,E/WifiMonitor(  823): killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,I/wpa_supplicant( 4395): Successfully initialized wpa_supplicant
,D/WifiMonitor(  823): startMonitoring(wlan0) with mConnected = false
,I/wpa_supplicant( 4395): rfkill: Cannot open RFKILL control device
,I/jxcore-log( 3810): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): Error type "connect_error" when connecting to the test server
I/jxcore-log( 3810): 
,I/chromium( 3810): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,D/Tethering(  823): sendTetherStateChangedBroadcast 1, 0, 0
,I/wpa_supplicant( 4395): rfkill: Cannot open RFKILL control device
E/wpa_supplicant( 4395): Could not read interface p2p-dev-wlan0 flags: No such device
,D/WifiConfigStore(  823): Loading config and enabling all networks 
,E/WifiConfigStore(  823): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,D/WifiNative-HAL(  823): Setting external_sim to 1
,D/WifiStateMachine(  823): Setting OUI to 92-68-C3
I/WifiNative-HAL(  823): startHal
D/wifi    (  823): setting scan oui 0xb4b70f58
D/WifiHAL (  823): Sending mac address OUI
,W/Settings( 3869): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,E/native  (  823): do suspend true
,D/WifiScanningService(  823): SCAN_AVAILABLE : 3
W/CommandListener(  355): Failed to retrieve HW addr for p2p0 (No such device)
D/RttService(  823): SCAN_AVAILABLE : 3
D/WifiScanningService(  823): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  823): startHal
D/wifi    (  823): getting scan capabilities on interface[0] = 0xb4b70f58
,D/WifiHAL (  823): Creating message to get scan capablities; iface = 5
,D/WifiHAL (  823): In GetCapabilities::handleResponse
D/WifiHAL (  823): Id = 0, subcmd = 0, len = 28, expected len = 32
D/WifiScanningService(  823): StartedState
D/RttService(  823): DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  355): Setting iface cfg
E/WifiP2pService(  823): Unable to change interface settings: java.lang.IllegalStateException: command '76 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 76 Failed to set address (No such device)'
D/WifiMonitor(  823): startMonitoring(p2p0) with mConnected = true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: motorola-Nexus 6_PT9351
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT9351","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3810): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT9351","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3810): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3810): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): setState: RUNNING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3810): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3810): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3810): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 3810): onDiscoveryManagerStateChanged: RUNNING
,I/wpa_supplicant( 4395): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,D/WifiNative-HAL(  823): p2pGetDeviceAddress
,D/WifiNative-HAL(  823): p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3810): Local service added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3810): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3810): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3810): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/wpa_supplicant( 4395): P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3810): P2P device discovery stopped successfully,
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3810): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3810): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3810): setState: RESTARTING
,I/art     ( 1773): Explicit concurrent mark sweep GC freed 17643(1042KB) AllocSpace objects, 11(176KB) LOS objects, 37% free, 26MB/42MB, paused 1.719ms total 89.598ms
,D/WifiService(  823): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@2d920bf6}
,E/DataBuffer( 1773): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1f604bf4)
,I/wpa_supplicant( 4395): p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,E/WifiStateMachine(  823): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,E/WifiConfigStore(  823):  rewrite network history for "NG700"WPA_PSK
E/WifiConfigStore(  823):  rewrite network history for "NG7005g"WPA_PSK
,E/WifiStateMachine(  823): CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
,E/WifiConfigStore(  823): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiConfigStore(  823): writeKnownNetworkHistory write linked 1,
E/WifiConfigStore(  823): writeKnownNetworkHistory write linked 1
E/WifiStateMachine(  823): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=0
,E/WifiConfigStore(  823): will read network variables netId=0
,E/WifiStateMachine(  823): CMD_AUTO_CONNECT did save config ->  nid=0
,E/WifiConfigStore(  823): will read network variables netId=0
,I/wpa_supplicant( 4395): wlan0: Trying to associate with SSID 'NG7005g'
,I/jxcore-log( 3810): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): Error type "connect_error" when connecting to the test server
I/jxcore-log( 3810): 
,I/chromium( 3810): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,I/wpa_supplicant( 4395): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 4395): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 4395): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=0 id_str=]
,D/ConnectivityService(  823): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} }
,E/WifiConfigStore(  823): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  823): NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  823): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  355): Setting iface cfg
,E/WifiStateMachine(  823): Start Dhcp Watchdog 3
,E/WifiStateMachine(  823):  WifiLinkLayerStats: 
E/WifiStateMachine(  823):  my bss beacon rx: 2
E/WifiStateMachine(  823):  RSSI mgmt: -46
E/WifiStateMachine(  823):  BE :  rx=0 tx=3 lost=0 retries=0
E/WifiStateMachine(  823):  BK :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  823):  VI :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  823):  VO :  rx=2 tx=0 lost=0 retries=0
E/WifiStateMachine(  823):  on_time : 0 tx_time=180 rx_time=496 scan_time=0
,E/native  (  823): do suspend false
,E/WifiStateMachine(  823): scanCount==0 - aborting
,I/dhcpcd  ( 4405): version 5.5.6 starting
,I/dhcpcd  ( 4405): wlan0: rebinding lease of 192.168.1.122
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3810): Start timer timeout, starting now...
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3810): Failed to P2P device discovery, got error code: 2
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3810): setState: INITIALIZED
,D/WifiService(  823): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@2d920bf6}
,I/dhcpcd  ( 4405): wlan0: acknowledged 192.168.1.122 from 192.168.1.1
,I/dhcpcd  ( 4405): wlan0: leased 192.168.1.122 for 86400 seconds
,E/native  (  823): do suspend true
,D/ConnectivityService(  823): NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService(  823): Adding iface wlan0 to network 102
,E/WifiStateMachine(  823): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  823): Unexpected mtu value: 0, wlan0
,D/ConnectivityService(  823): Adding Route [fe80::/64 -> :: wlan0] to network 102
,D/ConnectivityService(  823): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,D/ConnectivityService(  823): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
D/ConnectivityService(  823): Setting Dns servers for network 102 to [/192.168.1.1]
,D/ConnectivityService(  823): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,D/ConnectivityService(  823): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 102](  823): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 102](  823): Connected
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 102](  823): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 102](  823): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
D/ConnectivityService(  823): rematching NetworkAgentInfo [WIFI () - 102]
D/ConnectivityService(  823):    accepting network in place of null
,D/ConnectivityService(  823): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} }
,D/ConnectivityService(  823): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
D/CSLegacyTypeTracker(  823): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
D/ConnectivityService(  823): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  823): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityManager.CallbackHandler( 1073): CM callback handler got msg 524290
,D/Tethering(  823): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 3902): type=WIFI subType= reason=null isConnected=true
,D/PhoneInterfaceManager( 1338): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
,E/PhoneInterfaceManager( 1338): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
D/TelephonyManager(  823): getDataEnabled: retVal=false
,V/MusicLeanback( 3902): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,E/GpsLocationProvider(  823): No APN found to select.
,D/SprintDMReceiver( 3959): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3959): simOperator:  IMSI: null
D/SprintDMReceiver( 3959): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1805): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1805): onCreate
,D/SystemUpdateService( 1805): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1805): active receiver: enabled
,I/SystemUpdateService( 1805): showing system update notification
,I/iu.Environment( 1805): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1805): num queued entries: 0
,I/iu.UploadsManager( 1805): num updated entries: 0
I/iu.SyncManager( 1805): NEXT; no task
,D/ChimeraCfgMgr( 1805): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/ValidateNoPeople(  823): skipping global notification
,V/SystemUpdateService( 1805): retry (wakeup: false) in 3599971 ms
,D/ChimeraCfgMgr( 1805): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/SystemUpdateService( 1805): onDestroy
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 102](  823): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 18 Dec 2015 12:56:34 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1450443394483], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1450443394463]}
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 102](  823): Validated
,D/ConnectivityService(  823): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/ConnectivityService(  823): Validated NetworkAgentInfo [WIFI () - 102]
D/ConnectivityService(  823): rematching NetworkAgentInfo [WIFI () - 102]
D/ConnectivityService(  823): Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
D/ConnectivityService(  823): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
,D/ConnectivityService(  823): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION,
D/ConnectivityManager.CallbackHandler( 1073): CM callback handler got msg 524290
,I/GLSUser ( 1267): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1267): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1267): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1267): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/Herrevad( 1805): NQAS connected,
,V/GLSActivity( 1267): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Babel   ( 3869): connection state changed from DISCONNECTED to CONNECTED
,W/Kids    ( 1805): [AccountUtils] Account not ready
W/Kids    ( 1805): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 1805): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 1805): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 1805): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 1805): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 1805): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 1805): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 1805): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 1805): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 1805): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 1805): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 1805): 	at java.lang.Thread.run(Thread.java:818)
,D/GCM     ( 1267): Connected
,D/GCM     ( 1267): Message class com.google.f.a.a.p
,D/ConnectivityService(  823): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,I/jxcore-log( 3810): DBG, CoordinatorConnector connect called
I/jxcore-log( 3810): 
I/jxcore-log( 3810): Coordinator is now connected to the server!
I/jxcore-log( 3810): 
,I/chromium( 3810): [INFO:CONSOLE(63)] "logCallback connected to server", source: file:///android_asset/www/js/thali_main.js (63),
,D/HeadsetStateMachine( 2140): Disconnected process message: 10, size: 0
,W/bt-sdp  ( 2140): SDP - Rcvd conn cnf with error: 0x22  CID 0x45
E/bt-btif ( 2140): DISCOVERY_COMP_EVT slot id:19, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2140): invalid rfc slot id: 19
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3810): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 456)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3810): Maximum number of allowed retries (0) reached, giving up... (thread ID: 456)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3810): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3810): Exiting thread (thread ID: 456)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3810): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT9178]
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3810): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3810): shutdown (thread ID: 456)
,V/GoogleAuthProtoRequest( 3931): [430] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1267): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1267): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1267): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1267): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1267): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3931): [430] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3931): [430] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3931): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3931): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3931): ,	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3931): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3931): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3931): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3931): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3931): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3931): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3931): 	at com.a.a.k.run(SourceFile:110)
,I/GLSUser ( 1267): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1267): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1267): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1267): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1267): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/HttpOperation( 3217): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception,
E/HttpOperation( 3217): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3217): 	at jdm.a(PG:82)
E/HttpOperation( 3217): 	at jcs.o(PG:406)
E/HttpOperation( 3217): 	at jcn.a(PG:1379)
E/HttpOperation( 3217): 	at jcs.i(PG:143)
E/HttpOperation( 3217): 	at blb.a(PG:3937)
E/HttpOperation( 3217): 	at czp.a(PG:18188)
E/HttpOperation( 3217): ,	at czp.a(PG:9081)
E/HttpOperation( 3217): 	at czq.run(PG:1686)
E/HttpOperation( 3217): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3217): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3217): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3217): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3217): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3217): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3217): 	at jdj.a(PG:4091)
E/HttpOperation( 3217): 	at jdj.a(PG:1125)
E/HttpOperation( 3217): 	at jdm.a(PG:77)
E/HttpOperation( 3217): 	... 12 more
E/HttpOperation( 3217): Caused by: faj: BadAuthentication
E/HttpOperation( 3217): 	at fal.a(PG:38)
E/HttpOperation( 3217): 	at jdj.a(PG:4089)
E/HttpOperation( 3217): 	... 14 more
,I/GLSUser ( 1267): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1267): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1267): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1267): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1267): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3217): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3217): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3217): 	at jdm.a(PG:82)
E/HttpOperation( 3217): 	at jcs.o(PG:406)
E/HttpOperation( 3217): 	at jcn.a(PG:1379)
E/HttpOperation( 3217): 	at jcs.i(PG:143)
E/HttpOperation( 3217): 	at hec.a(PG:42)
E/HttpOperation( 3217): 	at hee.a(PG:102)
E/HttpOperation( 3217): 	at czr.a(PG:65)
E/HttpOperation( 3217): 	at kka.a(PG:108)
E/HttpOperation( 3217): 	at czp.a(PG:19176)
E/HttpOperation( 3217): 	at czp.a(PG:9081)
E/HttpOperation( 3217): 	at czq.run(PG:1686)
E/HttpOperation( 3217): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3217): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3217): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3217): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3217): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3217): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3217): 	at jdj.a(PG:4091)
E/HttpOperation( 3217): 	at jdj.a(PG:1125)
E/HttpOperation( 3217): 	at jdm.a(PG:77)
E/HttpOperation( 3217): 	... 15 more
E/HttpOperation( 3217): Caused by: faj: BadAuthentication
E/HttpOperation( 3217): 	at fal.a(PG:38)
E/HttpOperation( 3217): 	at jdj.a(PG:4089)
E/HttpOperation( 3217): 	... 17 more
E/ExperimentLoader( 3217): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3217): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3217): 	at jdm.a(PG:82)
E/ExperimentLoader( 3217): 	at jcs.o(PG:406)
E/ExperimentLoader( 3217): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3217): 	at jcs.i(PG:143)
E/ExperimentLoader( 3217): 	at hec.a(PG:42)
E/ExperimentLoader( 3217): 	at hee.a(PG:102)
E/ExperimentLoader( 3217): 	at czr.a(PG:65)
E/ExperimentLoader( 3217): 	at kka.a(PG:108)
E/ExperimentLoader( 3217): 	at czp.a(PG:19176)
E/ExperimentLoader( 3217): 	at czp.a(PG:9081)
E/ExperimentLoader( 3217): 	at czq.run(PG:1686)
E/ExperimentLoader( 3217): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3217): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3217): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3217): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3217): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3217): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3217): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3217): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3217): 	at jdm.a(PG:77)
E/ExperimentLoader( 3217): 	... 15 more
E/ExperimentLoader( 3217): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3217): 	at fal.a(PG:38)
E/ExperimentLoader( 3217): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3217): 	... 17 more
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 683609, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3810): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3810): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3810): setState: RESTARTING
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3810): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3810): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3810): setState: STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3810): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 4395): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 1 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 1: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,D/WifiP2pManager( 3810): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): Service request added successfully
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): checkListForExpiredPeers: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3932] expired
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): checkListForExpiredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778] expired
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): checkListForExpiredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3565] expired
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): checkListForExpiredPeers: Peer [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT9178] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3932], add/update: false
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Removed [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3932]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Removed [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3565], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Removed [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3565]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT9178], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Removed [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT9178]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerLost: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3932]
D/io.jxcore.node.ConnectionHelper( 3810): hasConnection: No connection with peer with ID E0:DB:10:14:E2:C0
,D/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3932] removed
D/io.jxcore.node.ConnectionHelper( 3810): notifyPeerAvailability: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3932] not available
I/io.jxcore.node.ConnectionHelper( 3810): onPeerLost: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
,D/io.jxcore.node.ConnectionHelper( 3810): hasConnection: No connection with peer with ID 7C:F9:0E:34:8A:A0
D/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778] removed
D/io.jxcore.node.ConnectionHelper( 3810): notifyPeerAvailability: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778] not available
,I/io.jxcore.node.ConnectionHelper( 3810): onPeerLost: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3565]
D/io.jxcore.node.ConnectionHelper( 3810): hasConnection: No connection with peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3565] removed
D/io.jxcore.node.ConnectionHelper( 3810): notifyPeerAvailability: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3565] not available
I/io.jxcore.node.ConnectionHelper( 3810): onPeerLost: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT9178]
D/io.jxcore.node.ConnectionHelper( 3810): hasConnection: No connection with peer with ID E0:DB:10:1F:C9:5E
D/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT9178] removed
D/io.jxcore.node.ConnectionHelper( 3810): notifyPeerAvailability: Peer [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT9178] not available
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): Service discovery started successfully
,I/wpa_supplicant( 4395): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 1: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,W/bt-sdp  ( 2140): SDP - Rcvd conn cnf with error: 0x22  CID 0x47
E/bt-btif ( 2140): DISCOVERY_COMP_EVT slot id:20, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2140): invalid rfc slot id: 20
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3810): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 461)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3810): Maximum number of allowed retries (0) reached, giving up... (thread ID: 461)
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3810): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3810): shutdown (thread ID: 461)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3810): Exiting thread (thread ID: 461)
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3810): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [E0:DB:10:1F:C9:5E E0:DB:10:1F:C9:5E]
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3810): setInsecureRfcommSocketPort: Will use port 1 when trying to connect
,W/bt-btif ( 2140): info:x10
,D/        ( 2140): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2140): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2140): process_service_search_attr_rsp
,D/btif_config( 2140): btif_get_device_type: Device [7c:f9:0e:37:96:ab] type 1
,I/BluetoothBondStateMachine( 2140): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:37:96:AB newState: 1
,E/bt-btif ( 2140): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2140): Bond State Change Intent:7C:F9:0E:37:96:AB OldState: 10 NewState: 11,
I/BluetoothBondStateMachine( 2140): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2140): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:37:96:AB newState: 0
,D/BluetoothAdapterProperties( 2140): Failed to remove device: 7C:F9:0E:37:96:AB
,I/BluetoothBondStateMachine( 2140): Bond State Change Intent:7C:F9:0E:37:96:AB OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2140): StableState(): Entering Off State
,W/bt-btif ( 2140): new conn_srvc id:26, app_id:1
,W/bt-btif ( 2140): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2140): bta_dm_pm_ssr:2, lat:1200
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3810): onSocketConnected: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3565]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3810): shutdown (thread ID: 463)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3810): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 463)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3810): Exiting thread (thread ID: 463)
,W/bt-btif ( 2140): bta_jv_rfc_port_to_cb(port_handle:0xf):jv handle:0x0 not FOUND
,D/HeadsetStateMachine( 2140): Disconnected process message: 10, size: 0
,E/bt-btm  ( 2140): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2140): onReceive
,I/BTConnectionReceiver( 1515): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1515): Bluetooth Device Name: A5-1,
,D/btif_config_util( 2140): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT8301","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Adding new peer: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301], Bluetooth address: 34:FC:EF:11:AE:67, device name: , device address: 52:55:27:f0:fd:0b
,W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT3638","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
,I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], Bluetooth address: F8:95:C7:87:85:54, device name: , device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638] already in the list, will not add again
,I/wpa_supplicant( 4395): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 2 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 1: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): restart: Restarting...
,D/WifiP2pManager( 3810): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): Service request added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): Service discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3810): Connection timeout
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3810): onConnectionTimeout
,D/HeadsetStateMachine( 2140): Disconnected process message: 10, size: 0
,I/wpa_supplicant( 4395): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 2 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 1: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700],
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): restart: Restarting...
,F/libc    ( 4395): Fatal signal 11 (SIGSEGV), code 1, fault addr 0xc in tid 4395 (wpa_supplicant)
I/libc    ( 4395): Suppressing debuggerd output because prctl(PR_GET_DUMPABLE)==0
D/WifiP2pManager( 3810): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): Service request added successfully
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): Failed to start the service discovery, got error code: 3
,I/GLSUser ( 1267): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1267): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1267): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1267): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1267): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3217): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3217): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3217): 	at jdm.a(PG:82)
E/HttpOperation( 3217): 	at jcs.o(PG:406)
E/HttpOperation( 3217): 	at jcn.a(PG:1379)
E/HttpOperation( 3217): 	at jcs.i(PG:143)
E/HttpOperation( 3217): 	at blb.a(PG:3937)
E/HttpOperation( 3217): 	at czp.a(PG:18188)
E/HttpOperation( 3217): 	at czp.a(PG:9081)
E/HttpOperation( 3217): 	at czq.run(PG:1686)
E/HttpOperation( 3217): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3217): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3217): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3217): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3217): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3217): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3217): 	at jdj.a(PG:4091)
E/HttpOperation( 3217): 	at jdj.a(PG:1125)
E/HttpOperation( 3217): 	at jdm.a(PG:77)
E/HttpOperation( 3217): 	... 12 more
E/HttpOperation( 3217): Caused by: faj: BadAuthentication
E/HttpOperation( 3217): 	at fal.a(PG:38)
E/HttpOperation( 3217): 	at jdj.a(PG:4089)
E/HttpOperation( 3217): 	... 14 more
,I/GLSUser ( 1267): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1267): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1267): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1267): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1267): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1267): Explicit concurrent mark sweep GC freed 56915(3MB) AllocSpace objects, 13(1434KB) LOS objects, 37% free, 27MB/43MB, paused 1.844ms total 46.185ms
,E/HttpOperation( 3217): [getmobileexperiments] Unexpected exception,
E/HttpOperation( 3217): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3217): 	at jdm.a(PG:82)
E/HttpOperation( 3217): 	at jcs.o(PG:406)
E/HttpOperation( 3217): 	at jcn.a(PG:1379)
E/HttpOperation( 3217): 	at jcs.i(PG:143)
E/HttpOperation( 3217): 	,at hec.a(PG:42)
E/HttpOperation( 3217): 	at hee.a(PG:102)
E/HttpOperation( 3217): 	at czr.a(PG:65)
E/HttpOperation( 3217): 	at kka.a(PG:108)
E/HttpOperation( 3217): 	at czp.a(PG:19176)
E/HttpOperation( 3217): 	at czp.a(PG:9081)
E/HttpOperation( 3217): ,	at czq.run(PG:1686)
E/HttpOperation( 3217): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3217): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3217): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3217): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3217): 	,at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3217): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3217): 	at jdj.a(PG:4091)
E/HttpOperation( 3217): 	at jdj.a(PG:1125)
,E/HttpOperation( 3217): 	at jdm.a(PG:77)
E/HttpOperation( 3217): 	... 15 more
E/HttpOperation( 3217): Caused by: faj: BadAuthentication
E/HttpOperation( 3217): 	at fal.a(PG:38)
E/HttpOperation( 3217): 	at jdj.a(PG:4089)
E/HttpOperation( 3217): 	,... 17 more
E/ExperimentLoader( 3217): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3217): java.io.IOException: Cannot obtain authentication token
,E/ExperimentLoader( 3217): 	at jdm.a(PG:82)
E/ExperimentLoader( 3217): 	at jcs.o(PG:406)
E/ExperimentLoader( 3217): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3217): 	at jcs.i(PG:143)
E/ExperimentLoader( 3217): ,	at hec.a(PG:42)
E/ExperimentLoader( 3217): 	at hee.a(PG:102)
E/ExperimentLoader( 3217): 	at czr.a(PG:65)
E/ExperimentLoader( 3217): 	at kka.a(PG:108)
E/ExperimentLoader( 3217): 	at czp.a(PG:19176)
E/ExperimentLoader( 3217): 	at czp.a(PG:9081),
E/ExperimentLoader( 3217): 	at czq.run(PG:1686)
E/ExperimentLoader( 3217): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3217): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3217): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3217): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
,E/ExperimentLoader( 3217): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3217): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3217): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3217): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3217): 	at jdm.a(PG:77)
E/ExperimentLoader( 3217): 	... 15 more,
E/ExperimentLoader( 3217): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3217): 	at fal.a(PG:38)
E/ExperimentLoader( 3217): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3217): 	... 17 more
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 716035, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3810): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3810): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3810): setState: RESTARTING
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3810): Failed to shutdown P2P device discovery, got error code: 0
,E/WifiStateMachine(  823): Connection lost, restart supplicant
,E/WifiMonitor(  823): killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,W/Settings( 3869): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,E/WifiConfigStore(  823): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,W/Settings( 1773): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/WifiConfigStore(  823): failed to set BSSID: any
E/native  (  823): do suspend true
D/CommandListener(  355): Clearing all IP addresses on wlan0
,I/jxcore-log( 3810): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 3810): 
I/jxcore-log( 3810): The Coordinator has disconnected!
I/jxcore-log( 3810): 
,V/NativeCrypto( 1267): Read error: ssl=0xb4884a00: I/O error during system call, Connection timed out
,D/ConnectivityService(  823): NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
E/WifiStateMachine(  823): WifiStateMachine: Leaving Connected state
D/ConnectivityService(  823): NetworkAgentInfo [WIFI () - 102] got DISCONNECTED, was satisfying 2
,E/WifiStateMachine(  823): Unexpected BatchedScanResults :null
,D/WifiScanningService(  823): SCAN_AVAILABLE : 1
D/RttService(  823): SCAN_AVAILABLE : 1
D/WifiScanningService(  823): StartedState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService(  823): DefaultState
D/RttService(  823): EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiNetworkAgent(  823): NetworkAgent: NetworkAgent channel lost
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3810): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 0 device(s) discovered
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onWifiStateChanged: State changed to 1
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onWifiStateChanged: Wi-Fi disabled, pausing Wi-Fi Direct based peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3810): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3810): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): stopWifiPeerDiscovery: Stopped
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): setState: WAITING_FOR_SERVICES_TO_BE_ENABLED
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3810): Failed to clear local services, got error code: 2
I/io.jxcore.node.ConnectionHelper( 3810): onDiscoveryManagerStateChanged: WAITING_FOR_SERVICES_TO_BE_ENABLED
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3810): Failed to shutdown P2P device discovery, got error code: 2
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): Failed to clear service requests, got error code: 2
,I/art     (  823): Explicit concurrent mark sweep GC freed 69805(3MB) AllocSpace objects, 7(300KB) LOS objects, 31% free, 34MB/50MB, paused 1.571ms total 76.874ms
,V/NativeCrypto( 1267): SSL shutdown failed: ssl=0xb4884a00: I/O error during system call, Broken pipe
D/ConnectivityService(  823): reportBadNetwork(NetworkAgentInfo [WIFI () - 102]) by 10011
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 102](  823): ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 102](  823): DefaultState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 102](  823): Forcing reevaluation
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 102](  823): EvaluatingState{ when=-1ms what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 102](  823): Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 102](  823): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
,D/ConnectivityService(  823): notifyType LOST for NetworkAgentInfo [WIFI () - 102]
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 102](  823): OfflineState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 102](  823): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 102](  823): Disconnected - quitting
,D/CSLegacyTypeTracker(  823): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
D/ConnectivityService(  823): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  823): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityManager.CallbackHandler( 1073): CM callback handler got msg 524292
,D/Tethering(  823): MasterInitialState.processMessage what=3
I/NetworkMonitor( 3902): type=WIFI subType= reason=null isConnected=false
,D/ConnectivityService(  823): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  823): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/MusicLeanback( 3902): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/ConnectivityService(  823): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  823): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
,D/PhoneInterfaceManager( 1338): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1338): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
D/Tethering(  823): MasterInitialState.processMessage what=3
,D/TelephonyManager(  823): getDataEnabled: retVal=false
,E/GpsLocationProvider(  823): No APN found to select.
,D/PhoneInterfaceManager( 1338): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
,E/PhoneInterfaceManager( 1338): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
D/SprintDMReceiver( 3959): Received intent: android.net.conn.CONNECTIVITY_CHANGE
D/TelephonyManager(  823): getDataEnabled: retVal=false
,E/GpsLocationProvider(  823): No APN found to select.
,D/SprintDMHelper( 3959): simOperator:  IMSI: null
D/SprintDMReceiver( 3959): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1805): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1805): onCreate
,D/SystemUpdateService( 1805): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1805): active receiver: enabled
,I/SystemUpdateService( 1805): showing system update notification
,I/iu.Environment( 1805): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1805): num queued entries: 0
I/iu.UploadsManager( 1805): num updated entries: 0
,I/iu.SyncManager( 1805): NEXT; no task
,D/ChimeraCfgMgr( 1805): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/ValidateNoPeople(  823): skipping global notification
I/Babel   ( 3869): connection state changed from CONNECTED to DISCONNECTED
,V/SystemUpdateService( 1805): retry (wakeup: false) in 3599981 ms
,D/SystemUpdateService( 1805): onDestroy
,V/MusicLeanback( 3902): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/SprintDMReceiver( 3959): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3959): simOperator:  IMSI: null
D/SprintDMReceiver( 3959): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1805): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1805): onCreate
,D/SystemUpdateService( 1805): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1805): active receiver: enabled
,I/SystemUpdateService( 1805): showing system update notification
,D/ChimeraCfgMgr( 1805): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/ValidateNoPeople(  823): skipping global notification
,V/SystemUpdateService( 1805): retry (wakeup: false) in 3599980 ms
,D/SystemUpdateService( 1805): onDestroy
,I/jxcore-log( 3810): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): Error type "connect_error" when connecting to the test server,
I/jxcore-log( 3810): 
,D/WifiService(  823): setWifiEnabled: false pid=3810, uid=10265
E/WifiService(  823): Invoking mWifiStateMachine.setWifiEnabled
,D/WifiService(  823): setWifiEnabled: true pid=3810, uid=10265
E/WifiService(  823): Invoking mWifiStateMachine.setWifiEnabled
,D/WifiController(  823): WifiController msg { when=0 what=155656 target=com.android.internal.util.StateMachine$SmHandler } deferred for 484ms,
,I/jxcore-log( 3810): Wifi toggled for connection repairment
I/jxcore-log( 3810): 
I/chromium( 3810): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,D/WifiController(  823): DEFERRED_TOGGLE handled
,D/SoftapController(  355): Softap fwReload - Ok
,D/CommandListener(  355): Setting iface cfg
,D/CommandListener(  355): Trying to bring down wlan0
,D/CommandListener(  355): Clearing all IP addresses on wlan0
,D/Tethering(  823): InitialState.processMessage what=4
,E/WifiMonitor(  823): killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,D/Tethering(  823): sendTetherStateChangedBroadcast 0, 0, 0
,I/wpa_supplicant( 4497): Successfully initialized wpa_supplicant
,D/WifiMonitor(  823): startMonitoring(wlan0) with mConnected = false
,I/wpa_supplicant( 4497): rfkill: Cannot open RFKILL control device
,D/Tethering(  823): sendTetherStateChangedBroadcast 1, 0, 0
,I/wpa_supplicant( 4497): rfkill: Cannot open RFKILL control device
E/wpa_supplicant( 4497): Could not read interface p2p-dev-wlan0 flags: No such device
,D/WifiConfigStore(  823): Loading config and enabling all networks 
,D/WifiService(  823): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@2f961250}
,E/WifiConfigStore(  823): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,D/WifiNative-HAL(  823): Setting external_sim to 1
W/Settings( 3869): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiStateMachine(  823): Setting OUI to 92-68-C3
I/WifiNative-HAL(  823): startHal
D/wifi    (  823): setting scan oui 0xb4b70f58
D/WifiHAL (  823): Sending mac address OUI
,E/native  (  823): do suspend true
,W/CommandListener(  355): Failed to retrieve HW addr for p2p0 (No such device)
,D/WifiScanningService(  823): SCAN_AVAILABLE : 3
D/RttService(  823): SCAN_AVAILABLE : 3
D/RttService(  823): DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler },
D/WifiScanningService(  823): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  823): startHal
,D/CommandListener(  355): Setting iface cfg
D/wifi    (  823): getting scan capabilities on interface[0] = 0xb4b70f58
,D/WifiHAL (  823): Creating message to get scan capablities; iface = 5
E/WifiP2pService(  823): Unable to change interface settings: java.lang.IllegalStateException: command '104 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 104 Failed to set address (No such device)'
,D/WifiHAL (  823): In GetCapabilities::handleResponse
D/WifiMonitor(  823): startMonitoring(p2p0) with mConnected = true
D/WifiHAL (  823): Id = 0, subcmd = 0, len = 28, expected len = 32,
D/WifiScanningService(  823): StartedState
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: motorola-Nexus 6_PT9351
D/WifiNative-HAL(  823): p2pGetDeviceAddress
,D/WifiNative-HAL(  823): p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT9351","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3810): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT9351","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3810): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3810): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onIsWifiPeerDiscoveryStartedChanged: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): setState: RUNNING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3810): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3810): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3810): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 3810): onDiscoveryManagerStateChanged: RUNNING
,I/wpa_supplicant( 4497): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3810): Local service added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3810): P2P device discovery started successfully,
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3810): setState: STARTED
I/wpa_supplicant( 4497): P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3810): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3810): P2P device discovery stopped successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3810): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3810): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3810): setState: RESTARTING
,I/wpa_supplicant( 4497): p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,I/jxcore-log( 3810): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3810): 
I/jxcore-log( 3810): Error type "connect_error" when connecting to the test server
I/jxcore-log( 3810): 
,I/chromium( 3810): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,E/WifiStateMachine(  823): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
E/WifiConfigStore(  823):  rewrite network history for "NG700"WPA_PSK
E/WifiConfigStore(  823):  rewrite network history for "NG7005g"WPA_PSK
E/WifiStateMachine(  823): CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
E/WifiConfigStore(  823): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiConfigStore(  823): writeKnownNetworkHistory write linked 1
E/WifiStateMachine(  823): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=0
E/WifiConfigStore(  823): writeKnownNetworkHistory write linked 1
,E/WifiConfigStore(  823): will read network variables netId=0
,E/WifiStateMachine(  823): CMD_AUTO_CONNECT did save config ->  nid=0
,E/WifiConfigStore(  823): will read network variables netId=0
,I/wpa_supplicant( 4497): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 4497): wlan0: Trying to associate with SSID 'NG7005g'
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 1: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3810): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): Service request added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): Service discovery started successfully
,I/wpa_supplicant( 4497): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 4497): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 4497): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=0 id_str=]
,D/ConnectivityService(  823): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} }
E/WifiConfigStore(  823): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/ConnectivityService(  823): NetworkAgentInfo [WIFI () - 103] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  823): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  355): Setting iface cfg
,E/WifiStateMachine(  823): Start Dhcp Watchdog 4
,E/WifiStateMachine(  823):  WifiLinkLayerStats: 
E/WifiStateMachine(  823):  my bss beacon rx: 1
E/WifiStateMachine(  823):  RSSI mgmt: -46
E/WifiStateMachine(  823):  BE :  rx=0 tx=2 lost=0 retries=0
E/WifiStateMachine(  823):  BK :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  823):  VI :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  823):  VO :  rx=2 tx=0 lost=0 retries=0
,E/WifiStateMachine(  823):  on_time : 0 tx_time=173 rx_time=255 scan_time=0
,E/native  (  823): do suspend false
,E/WifiStateMachine(  823): scanCount==0 - aborting
,I/dhcpcd  ( 4506): version 5.5.6 starting
,I/dhcpcd  ( 4506): wlan0: rebinding lease of 192.168.1.122
,D/WifiService(  823): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@2f961250}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3810): Start timer timeout, starting now...
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3810): Failed to P2P device discovery, got error code: 2
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3810): setState: INITIALIZED
,D/HeadsetStateMachine( 2140): Disconnected process message: 10, size: 0
,I/dhcpcd  ( 4506): wlan0: acknowledged 192.168.1.122 from 192.168.1.1,
,I/dhcpcd  ( 4506): wlan0: leased 192.168.1.122 for 86400 seconds
,I/jxcore-log( 3810): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3810): 
I/jxcore-log( 3810): Error type "connect_error" when connecting to the test server
I/jxcore-log( 3810): 
,I/chromium( 3810): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,E/native  (  823): do suspend true
,D/ConnectivityService(  823): NetworkAgentInfo [WIFI () - 103] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  823): Adding iface wlan0 to network 103
,E/WifiStateMachine(  823): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  823): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  823): Adding Route [fe80::/64 -> :: wlan0] to network 103
,D/ConnectivityService(  823): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 103
,D/ConnectivityService(  823): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 103
,D/ConnectivityService(  823): Setting Dns servers for network 103 to [/192.168.1.1]
,D/ConnectivityService(  823): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,D/ConnectivityService(  823): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 103]
D/ConnectivityService(  823): rematching NetworkAgentInfo [WIFI () - 103]
,D/ConnectivityService(  823):    accepting network in place of null
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 103](  823): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 103](  823): Connected
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 103](  823): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 103](  823): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
D/ConnectivityService(  823): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{103}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} }
,D/ConnectivityService(  823): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 103]
D/CSLegacyTypeTracker(  823): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 103] isDefaultNetwork=true
D/ConnectivityService(  823): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 1073): CM callback handler got msg 524290
D/ConnectivityService(  823): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering(  823): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 3902): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 3902): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/SprintDMReceiver( 3959): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3959): simOperator:  IMSI: null
,D/SprintDMReceiver( 3959): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1805): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1805): onCreate
,D/PhoneInterfaceManager( 1338): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1338): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  823): getDataEnabled: retVal=false
,D/SystemUpdateService( 1805): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1805): active receiver: enabled
E/GpsLocationProvider(  823): No APN found to select.
,I/BooksSync( 3716): Starting books sync for 61035162, extras: ade
,I/SystemUpdateService( 1805): showing system update notification
,I/iu.Environment( 1805): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1805): num queued entries: 0
,I/iu.UploadsManager( 1805): num updated entries: 0
,I/iu.SyncManager( 1805): NEXT; no task
,D/ChimeraCfgMgr( 1805): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/ValidateNoPeople(  823): skipping global notification
,D/ChimeraCfgMgr( 1805): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/BooksConfig( 3716): GmsCore Version = 7.8.99 (2134222-430)
,V/SystemUpdateService( 1805): retry (wakeup: false) in 3599967 ms
,D/SystemUpdateService( 1805): onDestroy
,V/KeepSync( 3749): Connecting to GoogleApiClient
,I/GLSUser ( 1267): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1267): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1267): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1267): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1267): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1267): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1267): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1267): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1267): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1267): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Kids    ( 1805): [AccountUtils] Account not ready
W/Kids    ( 1805): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 1805): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 1805): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 1805): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 1805): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 1805): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 1805): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 1805): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 1805): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 1805): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 1805): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 1805): 	at java.lang.Thread.run(Thread.java:818)
,I/GLSUser ( 1267): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1267): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1267): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1267): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1267): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/ClientConnectionOperation( 1805): Handling authorization failure,
E/ClientConnectionOperation( 1805): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1805): 	,at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1805): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1805): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1805): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.common.server.c.b(SourceFile:109),
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1805): 	... 7 more
,V/KeepSync( 3749): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3749): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1267): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1267): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1267): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1267): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1267): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/SQLiteLog( 3749): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3749): (284) automatic index on blob_node(is_deleted)
,E/BooksAccountManager( 3716): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3716): Soft error
E/BooksSync( 3716): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3716): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3716): Sync error
E/BooksSync( 3716): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3716): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3716): Finished books sync
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 757116, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1267): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1267): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1267): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1267): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1267): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3749): IOException,
E/KeepSync( 3749): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3749): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3749): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3749): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3749): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3749): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3749): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3749): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3749): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3749): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3749): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3749): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3749): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3749): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3749): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3749): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3749): 	... 10 more
W/KeepSync( 3749): Sync result 2
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 761192, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 103](  823): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 18 Dec 2015 12:58:17 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1450443497788], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1450443497570]}
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 103](  823): Validated
,D/ConnectivityService(  823): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/ConnectivityService(  823): Validated NetworkAgentInfo [WIFI () - 103]
D/ConnectivityService(  823): rematching NetworkAgentInfo [WIFI () - 103]
D/ConnectivityService(  823): Network NetworkAgentInfo [WIFI () - 103] was already satisfying request 1. No change.
,D/ConnectivityService(  823): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 103]
D/ConnectivityManager.CallbackHandler( 1073): CM callback handler got msg 524290
,D/ConnectivityService(  823): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,V/Herrevad( 1805): NQAS connected
,I/Babel   ( 3869): connection state changed from DISCONNECTED to CONNECTED
,D/GCM     ( 1267): Connected
,D/GCM     ( 1267): Message class com.google.f.a.a.p
,D/ConnectivityService(  823): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 102] cleared because we found a replacement network
,I/wpa_supplicant( 4497): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 2 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 2: Android_8ae2 52:55:27:f0:fd:0b
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT5199","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
,D/io.jxcore.node.ConnectionHelper( 3810): notifyPeerAvailability: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199] is available
,I/wpa_supplicant( 4497): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 3 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 3: Android_8ae2 52:55:27:f0:fd:0b
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4778","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
D/io.jxcore.node.ConnectionHelper( 3810): notifyPeerAvailability: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778] is available
,I/wpa_supplicant( 4497): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 4: Android_8ae2 52:55:27:f0:fd:0b
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT3638","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638] already in the list, will not add again
,I/jxcore-log( 3810): DBG, CoordinatorConnector connect called
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): Coordinator is now connected to the server!
I/jxcore-log( 3810): 
,I/chromium( 3810): [INFO:CONSOLE(63)] "logCallback connected to server", source: file:///android_asset/www/js/thali_main.js (63)
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT9700","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700] already in the list, will not add again
,I/wpa_supplicant( 4497): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 4 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199],
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 4: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): restart: Restarting...
,D/WifiP2pManager( 3810): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): Service request added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): Service discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT9700","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT3638","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4778","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
,I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT5199","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
,I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199] already in the list, will not add again
,I/wpa_supplicant( 4497): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 4 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 4: Android_8ae2 52:55:27:f0:fd:0b
,I/wpa_supplicant( 4497): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 4 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 4: Android_8ae2 52:55:27:f0:fd:0b
,I/wpa_supplicant( 4497): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 5 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 5: Android_8ae2 52:55:27:f0:fd:0b
,I/wpa_supplicant( 4497): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 4497): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 5 device(s) discovered,
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 5: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 5: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3810): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): Service request added successfully
,D/HeadsetStateMachine( 2140): Disconnected process message: 10, size: 0
,I/wpa_supplicant( 4497): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): Service discovery started successfully
,I/wpa_supplicant( 4497): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 5 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 5: Android_8ae2 52:55:27:f0:fd:0b
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT9700","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700] already in the list, will not add again
,I/BooksSync( 3716): Starting books sync for 61035162, extras: ade
,V/KeepSync( 3749): Connecting to GoogleApiClient
,I/BooksConfig( 3716): GmsCore Version = 7.8.99 (2134222-430)
,I/art     (  823): Explicit concurrent mark sweep GC freed 67655(3MB) AllocSpace objects, 7(206KB) LOS objects, 31% free, 34MB/50MB, paused 2.419ms total 59.368ms
,I/GLSUser ( 1267): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1267): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1267): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1267): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1267): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1267): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books,
I/GLSUser ( 1267): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1267): [GLSUser] Extracting token using key: Auth,
W/GLSActivity( 1267): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1267): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1805): Handling authorization failure,
E/ClientConnectionOperation( 1805): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1805): ,	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1805): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1805): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1805): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1805): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1805): 	... 7 more
,V/KeepSync( 3749): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3749): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3749): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3749): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1267): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1267): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1267): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1267): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1267): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3716): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3716): Soft error
E/BooksSync( 3716): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3716): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3716): Sync error
E/BooksSync( 3716): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3716): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3716): Finished books sync
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 799013, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1],
,I/GLSUser ( 1267): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1267): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1267): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1267): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1267): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3749): IOException
E/KeepSync( 3749): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3749): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3749): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3749): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3749): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3749): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3749): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3749): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3749): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3749): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3749): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3749): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3749): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3749): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3749): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3749): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3749): 	... 10 more
W/KeepSync( 3749): Sync result 2
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 799001, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT3638","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
,W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4778","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT5199","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
,I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199] already in the list, will not add again
,I/wpa_supplicant( 4497): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 5 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199],
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 5: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): restart: Restarting...
,D/WifiP2pManager( 3810): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): Service request added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): Service discovery started successfully
,I/wpa_supplicant( 4497): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 5 device(s) discovered,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 5: Android_8ae2 52:55:27:f0:fd:0b
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT9700","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700] already in the list, will not add again,
,W/bt-btif ( 2140): info:x10
,D/        ( 2140): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
E/BluetoothRemoteDevices( 2140): aclStateChangeCallback: Device is NULL
,D/btif_config( 2140): btif_get_device_type: Device [7c:f9:0e:34:8a:a0] type 1
,I/BluetoothBondStateMachine( 2140): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:34:8A:A0 newState: 1
,E/bt-btif ( 2140): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2140): Bond State Change Intent:7C:F9:0E:34:8A:A0 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2140): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2140): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:34:8A:A0 newState: 0
,D/BluetoothAdapterProperties( 2140): Failed to remove device: 7C:F9:0E:34:8A:A0
,I/BluetoothBondStateMachine( 2140): Bond State Change Intent:7C:F9:0E:34:8A:A0 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2140): StableState(): Entering Off State
,W/bt-btif ( 2140): new conn_srvc id:26, app_id:255
,W/bt-btif ( 2140): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2140): bta_dm_pm_ssr:2, lat:1200
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3810): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3810): Incoming connection initialized (thread ID: 465)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3810): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3810): Entering thread (ID: 465)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3810): onBytesRead: Read 82 bytes successfully (thread ID: 465)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3810): Got valid identity from [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3810): onBytesWritten: 82 bytes successfully written (thread ID: 465)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3810): removeThreadFromList: Removing thread with ID 465
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3810): Handshake thread disposed (thread ID: 465)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3810): onIncomingConnectionConnected: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3810): Exiting thread (ID: 465)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3810): onConnected: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
,I/io.jxcore.node.ConnectionHelper( 3810): onConnected: Incoming connection to peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/io.jxcore.node.ConnectionHelper( 3810): hasConnection: No connection with peer with ID 7C:F9:0E:34:8A:A0
W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 3810): onConnected: Incoming socket thread, for peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], created successfully
D/io.jxcore.node.ConnectionHelper( 3810): onConnected: The total number of connections is now 1
,D/io.jxcore.node.IncomingSocketThread( 3810): Entering thread (ID: 466)
,I/io.jxcore.node.IncomingSocketThread( 3810): Local host address: localhost/127.0.0.1, port: 41534
D/io.jxcore.node.IncomingSocketThread( 3810): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3810): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread( 3810): setBufferSize: Setting buffer size to 8192 bytes
I/jxcore-log( 3810): 2015-12-18T12:59:07.480Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3810): 
D/io.jxcore.node.StreamCopyingThread( 3810): Entering thread (ID: 467, name: Sender)
I/io.jxcore.node.IncomingSocketThread( 3810): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3810): Exiting thread (ID: 466)
,D/io.jxcore.node.StreamCopyingThread( 3810): Entering thread (ID: 468, name: Receiver)
,I/jxcore-log( 3810): 2015-12-18T12:59:08.311Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:59:08.319Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:59:08.322Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:59:08.376Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:59:08.381Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data,
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:59:08.385Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data,
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:59:08.442Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data,
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:59:08.446Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:59:08.450Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:59:08.453Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3810): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT3638","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638] already in the list, will not add again
,I/jxcore-log( 3810): 2015-12-18T12:59:08.613Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data,
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:59:08.649Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data,
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:59:08.655Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3810): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4778","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778] already in the list, will not add again
,I/jxcore-log( 3810): 2015-12-18T12:59:08.718Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:59:08.725Z SendDataTCPServer.js: TCP/IP server has received 32768 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:59:08.825Z SendDataTCPServer.js: TCP/IP server has received 34748 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:59:08.829Z SendDataTCPServer.js: TCP/IP server has received 36728 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:59:08.890Z SendDataTCPServer.js: TCP/IP server has received 38708 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:59:08.897Z SendDataTCPServer.js: TCP/IP server has received 40688 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:59:08.954Z SendDataTCPServer.js: TCP/IP server has received 42668 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:59:08.989Z SendDataTCPServer.js: TCP/IP server has received 46628 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:59:08.993Z SendDataTCPServer.js: TCP/IP server has received 48608 bytes of data,
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:59:08.997Z SendDataTCPServer.js: TCP/IP server has received 50588 bytes of data,
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:59:09.004Z SendDataTCPServer.js: TCP/IP server has received 52568 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:59:09.008Z SendDataTCPServer.js: TCP/IP server has received 54548 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:59:09.039Z SendDataTCPServer.js: TCP/IP server has received 62468 bytes of data,
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:59:09.046Z SendDataTCPServer.js: TCP/IP server has received 64448 bytes of data,
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:59:09.056Z SendDataTCPServer.js: TCP/IP server has received 66428 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:59:09.089Z SendDataTCPServer.js: TCP/IP server has received 76328 bytes of data
I/jxcore-log( 3810): ,
,I/jxcore-log( 3810): 2015-12-18T12:59:09.092Z SendDataTCPServer.js: TCP/IP server has received 78308 bytes of data
,I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:59:09.102Z SendDataTCPServer.js: TCP/IP server has received 80288 bytes of data
,I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:59:09.106Z SendDataTCPServer.js: TCP/IP server has received 82268 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:59:09.139Z SendDataTCPServer.js: TCP/IP server has received 94148 bytes of data,
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:59:09.143Z SendDataTCPServer.js: TCP/IP server has received 96128 bytes of data
,I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:59:09.146Z SendDataTCPServer.js: TCP/IP server has received 98108 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T12:59:09.179Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data,
I/jxcore-log( 3810): 
,W/bt-btif ( 2140): invalid rfc slot id: 16,
,W/io.jxcore.node.StreamCopyingThread( 3810): Either failed to read from the output stream or write to the input stream (thread ID: 468, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 3810): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
,W/io.jxcore.node.ConnectionHelper( 3810): onDisconnected: Incoming connection, peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3810): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 466
D/io.jxcore.node.IncomingSocketThread( 3810): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3810): doStop: Thread ID: 468
,D/io.jxcore.node.IncomingSocketThread( 3810): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3810): doStop: Thread ID: 467
D/io.jxcore.node.IncomingSocketThread( 3810): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 3810): closeLocalSocketAndStreams: Closing the local input stream...
W/io.jxcore.node.StreamCopyingThread( 3810): Either failed to read from the output stream or write to the input stream (thread ID: 467, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3810): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3810): onDisconnected: Incoming connection, peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.IncomingSocketThread( 3810): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 3810): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 3810): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3810): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,I/jxcore-log( 3810): 2015-12-18T12:59:09.289Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3810): 
W/bt-rfcomm( 2140): rfc_find_lcid_mcb LCID reused LCID:0x43 current:0x0
W/bt-rfcomm( 2140): RFCOMM_DisconnectInd LCID:0x43
D/io.jxcore.node.ConnectionHelper( 3810): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3810): Exiting thread (ID: 467, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 3810): Exiting thread (ID: 468, name: Receiver)
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT5199","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
,W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199] already in the list, will not add again
,E/bt-btm  ( 2140): btm_sec_disconnected - Clearing Pending flag,
,D/BluetoothMapService( 2140): onReceive,
,I/BTConnectionReceiver( 1515): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1515): Bluetooth Device Name: S5-1
,D/btif_config_util( 2140): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 4497): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 5: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): restart: Restarting...
,D/WifiP2pManager( 3810): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): Service request added successfully
,I/wpa_supplicant( 4497): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): Service discovery started successfully
,D/HeadsetStateMachine( 2140): Disconnected process message: 10, size: 0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT3638","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638],
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4778","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local.",
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778],
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778],
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
,W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT5199","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199],
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
,W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199] already in the list, will not add again
,I/GLSUser ( 1267): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1267): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1267): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1267): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1267): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3217): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3217): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3217): 	at jdm.a(PG:82)
E/HttpOperation( 3217): 	at jcs.o(PG:406)
E/HttpOperation( 3217): 	at jcn.a(PG:1379)
E/HttpOperation( 3217): 	at jcs.i(PG:143)
E/HttpOperation( 3217): 	at blb.a(PG:3937)
E/HttpOperation( 3217): 	at czp.a(PG:18188)
E/HttpOperation( 3217): 	at czp.a(PG:9081)
E/HttpOperation( 3217): 	at czq.run(PG:1686)
E/HttpOperation( 3217): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3217): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3217): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3217): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3217): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3217): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3217): 	at jdj.a(PG:4091)
E/HttpOperation( 3217): 	at jdj.a(PG:1125)
E/HttpOperation( 3217): 	at jdm.a(PG:77)
E/HttpOperation( 3217): 	... 12 more
E/HttpOperation( 3217): Caused by: faj: BadAuthentication
E/HttpOperation( 3217): 	at fal.a(PG:38)
E/HttpOperation( 3217): 	at jdj.a(PG:4089)
E/HttpOperation( 3217): 	... 14 more
,I/GLSUser ( 1267): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1267): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1267): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1267): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1267): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3217): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3217): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3217): 	at jdm.a(PG:82)
E/HttpOperation( 3217): 	at jcs.o(PG:406)
E/HttpOperation( 3217): 	at jcn.a(PG:1379)
E/HttpOperation( 3217): 	at jcs.i(PG:143)
E/HttpOperation( 3217): 	at hec.a(PG:42)
E/HttpOperation( 3217): 	at hee.a(PG:102)
E/HttpOperation( 3217): 	at czr.a(PG:65)
E/HttpOperation( 3217): 	at kka.a(PG:108)
E/HttpOperation( 3217): 	at czp.a(PG:19176)
E/HttpOperation( 3217): 	at czp.a(PG:9081)
E/HttpOperation( 3217): 	at czq.run(PG:1686)
E/HttpOperation( 3217): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3217): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3217): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3217): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3217): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3217): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3217): 	at jdj.a(PG:4091)
E/HttpOperation( 3217): 	at jdj.a(PG:1125)
E/HttpOperation( 3217): 	at jdm.a(PG:77)
E/HttpOperation( 3217): 	... 15 more
E/HttpOperation( 3217): Caused by: faj: BadAuthentication
E/HttpOperation( 3217): 	at fal.a(PG:38)
E/HttpOperation( 3217): 	at jdj.a(PG:4089)
E/HttpOperation( 3217): 	... 17 more
,E/ExperimentLoader( 3217): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3217): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3217): ,	at jdm.a(PG:82)
E/ExperimentLoader( 3217): 	at jcs.o(PG:406)
E/ExperimentLoader( 3217): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3217): 	at jcs.i(PG:143)
E/ExperimentLoader( 3217): 	at hec.a(PG:42)
,E/ExperimentLoader( 3217): 	at hee.a(PG:102)
E/ExperimentLoader( 3217): 	at czr.a(PG:65)
E/ExperimentLoader( 3217): ,	at kka.a(PG:108)
E/ExperimentLoader( 3217): 	at czp.a(PG:19176)
E/ExperimentLoader( 3217): 	at czp.a(PG:9081)
E/ExperimentLoader( 3217): 	at czq.run(PG:1686)
E/ExperimentLoader( 3217): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3217): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3217): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3217): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3217): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3217): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3217): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3217): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3217): 	at jdm.a(PG:77)
,E/ExperimentLoader( 3217): 	... 15 more
E/ExperimentLoader( 3217): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3217): 	at fal.a(PG:38)
E/ExperimentLoader( 3217): 	at jdj.a(PG:4089)
,E/ExperimentLoader( 3217): 	... 17 more
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 808027, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,I/wpa_supplicant( 4497): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:fd:0b
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): restart: Restarting...
,D/WifiP2pManager( 3810): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): Service request added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): Service discovery started successfully
,I/wpa_supplicant( 4497): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 4497): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 5 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 4: Android_8ae2 52:55:27:f0:fd:0b
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 5 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 4: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT8301","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Adding new peer: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301]
,I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301], Bluetooth address: 34:FC:EF:11:AE:67, device name: Android_8ae2, device address: 52:55:27:f0:fd:0b
W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301] already in the list, will not add again
,I/wpa_supplicant( 4497): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 5 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 4: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT9700","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT3638","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
,I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4778","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT5199","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199],
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199] already in the list, will not add again
,I/ActivityManager(  823): Start proc 4590:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider
,I/GAv4    ( 4590): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4590):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4590):   adb logcat -s GAv4
,W/GAv4    ( 4590): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.,
,W/GAv4    ( 4590): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4590): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  823): Killing 3576:com.android.defcontainer/u0a7 (adj 15): empty #17
,I/wpa_supplicant( 4497): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 4497): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 5 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 4: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 4: Android_8ae2 52:55:27:f0:fd:0b
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,D/WifiP2pManager( 3810): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): Service request added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): Service discovery started successfully
,I/wpa_supplicant( 4497): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 5 device(s) discovered,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 4: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT8301","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301],
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Adding new peer: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301]
,I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301], Bluetooth address: 34:FC:EF:11:AE:67, device name: Android_8ae2, device address: 52:55:27:f0:fd:0b
W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT9700","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700],
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
,W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT3638","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4778","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT5199","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199] already in the list, will not add again
,I/wpa_supplicant( 4497): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 4: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,I/wpa_supplicant( 4497): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 4: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): restart: Restarting...
,D/WifiP2pManager( 3810): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): Service request added successfully
,I/wpa_supplicant( 4497): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): Service discovery started successfully
,I/wpa_supplicant( 4497): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 5 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 4: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT9700","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT3638","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4778","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
,W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT5199","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
,W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199] already in the list, will not add again
,I/wpa_supplicant( 4497): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 5 device(s) discovered,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 4: Android_8ae2 52:55:27:f0:fd:0b
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,I/wpa_supplicant( 4497): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 5 device(s) discovered,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 4: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,V/KeepSync( 3749): Connecting to GoogleApiClient
,I/GLSUser ( 1267): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1267): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1267): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1267): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1267): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1267): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1267): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1267): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1267): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1267): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3217): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3217): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3217): 	at jdm.a(PG:82)
E/HttpOperation( 3217): 	at jcs.o(PG:406)
E/HttpOperation( 3217): 	at jcn.a(PG:1379)
E/HttpOperation( 3217): 	at jcs.i(PG:143)
E/HttpOperation( 3217): 	at blb.a(PG:3937)
E/HttpOperation( 3217): 	at czp.a(PG:18188)
E/HttpOperation( 3217): 	at czp.a(PG:9081)
E/HttpOperation( 3217): 	at czq.run(PG:1686)
E/HttpOperation( 3217): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3217): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3217): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3217): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3217): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3217): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3217): 	at jdj.a(PG:4091)
E/HttpOperation( 3217): 	at jdj.a(PG:1125)
E/HttpOperation( 3217): 	at jdm.a(PG:77)
E/HttpOperation( 3217): 	... 12 more
E/HttpOperation( 3217): Caused by: faj: BadAuthentication
E/HttpOperation( 3217): 	at fal.a(PG:38)
E/HttpOperation( 3217): 	at jdj.a(PG:4089)
E/HttpOperation( 3217): 	... 14 more
,E/ClientConnectionOperation( 1805): Handling authorization failure
E/ClientConnectionOperation( 1805): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1805): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1805): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1805): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1805): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1805): 	... 7 more
V/KeepSync( 3749): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3749): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3749): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3749): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1267): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1267): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1267): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1267): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1267): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3217): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3217): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3217): 	at jdm.a(PG:82)
E/HttpOperation( 3217): 	at jcs.o(PG:406)
E/HttpOperation( 3217): 	at jcn.a(PG:1379)
E/HttpOperation( 3217): 	at jcs.i(PG:143)
E/HttpOperation( 3217): 	at hec.a(PG:42)
E/HttpOperation( 3217): 	at hee.a(PG:102)
E/HttpOperation( 3217): 	at czr.a(PG:65)
E/HttpOperation( 3217): 	at kka.a(PG:108)
E/HttpOperation( 3217): 	at czp.a(PG:19176)
E/HttpOperation( 3217): 	at czp.a(PG:9081)
E/HttpOperation( 3217): 	at czq.run(PG:1686)
E/HttpOperation( 3217): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3217): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3217): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3217): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3217): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3217): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3217): 	at jdj.a(PG:4091)
E/HttpOperation( 3217): 	at jdj.a(PG:1125)
E/HttpOperation( 3217): 	at jdm.a(PG:77)
E/HttpOperation( 3217): 	... 15 more
E/HttpOperation( 3217): Caused by: faj: BadAuthentication
E/HttpOperation( 3217): 	at fal.a(PG:38)
E/HttpOperation( 3217): 	at jdj.a(PG:4089)
E/HttpOperation( 3217): 	... 17 more
E/ExperimentLoader( 3217): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3217): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3217): 	at jdm.a(PG:82)
E/ExperimentLoader( 3217): 	at jcs.o(PG:406)
E/ExperimentLoader( 3217): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3217): 	at jcs.i(PG:143)
E/ExperimentLoader( 3217): 	at hec.a(PG:42)
E/ExperimentLoader( 3217): 	at hee.a(PG:102)
E/ExperimentLoader( 3217): 	at czr.a(PG:65)
E/ExperimentLoader( 3217): 	at kka.a(PG:108)
E/ExperimentLoader( 3217): 	at czp.a(PG:19176)
E/ExperimentLoader( 3217): 	at czp.a(PG:9081)
E/ExperimentLoader( 3217): 	at czq.run(PG:1686)
E/ExperimentLoader( 3217): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3217): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3217): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3217): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3217): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3217): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3217): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3217): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3217): 	at jdm.a(PG:77)
E/ExperimentLoader( 3217): 	... 15 more
E/ExperimentLoader( 3217): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3217): 	at fal.a(PG:38)
E/ExperimentLoader( 3217): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3217): 	... 17 more
,I/GLSUser ( 1267): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1267): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1267): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1267): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1267): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/KeepSync( 3749): IOException
E/KeepSync( 3749): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3749): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3749): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3749): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3749): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3749): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3749): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3749): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3749): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3749): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3749): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3749): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3749): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3749): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3749): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3749): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3749): 	... 10 more
W/KeepSync( 3749): Sync result 2
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 868564, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,I/BooksSync( 3716): Starting books sync for 61035162, extras: ade
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 866636, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,I/BooksConfig( 3716): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1267): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1267): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1267): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1267): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1267): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1267): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1267): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1267): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1267): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1267): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1267): Explicit concurrent mark sweep GC freed 59173(3MB) AllocSpace objects, 9(992KB) LOS objects, 36% free, 27MB/43MB, paused 1.696ms total 27.942ms
,E/BooksAccountManager( 3716): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3716): Soft error
E/BooksSync( 3716): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3716): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3716): Sync error
E/BooksSync( 3716): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3716): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3716): Finished books sync
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 868642, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2140): Disconnected process message: 10, size: 0
,I/wpa_supplicant( 4497): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 5 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 4: Android_8ae2 52:55:27:f0:fd:0b,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): restart: Restarting...
,D/WifiP2pManager( 3810): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): Service request added successfully
,I/wpa_supplicant( 4497): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): Service discovery started successfully
,I/wpa_supplicant( 4497): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 5 device(s) discovered,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 4: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT9700","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT3638","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4778","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT5199","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199] already in the list, will not add again
,I/wpa_supplicant( 4497): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 4: Android_8ae2 52:55:27:f0:fd:0b
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): restart: Restarting...
,D/WifiP2pManager( 3810): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): Service request added successfully
,I/wpa_supplicant( 4497): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): Service discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT8301","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Adding new peer: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301], Bluetooth address: 34:FC:EF:11:AE:67, device name: Android_8ae2, device address: 52:55:27:f0:fd:0b
W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT9700","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
,W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT3638","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local.",
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
,W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4778","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778],
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
,I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT5199","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
,I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199] already in the list, will not add again
,I/wpa_supplicant( 4497): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 5 device(s) discovered,
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 4: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): restart: Restarting...
,D/WifiP2pManager( 3810): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): Service request added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): Service discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT9700","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT3638","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4778","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
,W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778] already in the list, will not add again
,D/HeadsetStateMachine( 2140): Disconnected process message: 10, size: 0
,I/wpa_supplicant( 4497): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1,
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 5 device(s) discovered,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 4: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,I/wpa_supplicant( 4497): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 5 device(s) discovered,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 4: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,I/wpa_supplicant( 4497): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 5 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 4: Android_8ae2 52:55:27:f0:fd:0b
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): restart: Restarting...
,D/WifiP2pManager( 3810): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): Service request added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): Service discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT9700","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
,W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT3638","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
,I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT5199","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199] already in the list, will not add again,
,I/art     (  823): Explicit concurrent mark sweep GC freed 50371(2MB) AllocSpace objects, 11(458KB) LOS objects, 31% free, 34MB/50MB, paused 1.577ms total 114.444ms
,I/GLSUser ( 1267): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1267): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1267): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1267): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1267): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/HttpOperation( 3217): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
,E/HttpOperation( 3217): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3217): 	at jdm.a(PG:82)
E/HttpOperation( 3217): 	at jcs.o(PG:406)
E/HttpOperation( 3217): 	at jcn.a(PG:1379)
E/HttpOperation( 3217): 	at jcs.i(PG:143)
E/HttpOperation( 3217): 	,at blb.a(PG:3937)
E/HttpOperation( 3217): 	at czp.a(PG:18188)
E/HttpOperation( 3217): 	at czp.a(PG:9081)
E/HttpOperation( 3217): 	at czq.run(PG:1686)
E/HttpOperation( 3217): 	,at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3217): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3217): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3217): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3217): 	at java.lang.Thread.run(Thread.java:818),
E/HttpOperation( 3217): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3217): 	at jdj.a(PG:4091)
E/HttpOperation( 3217): 	at jdj.a(PG:1125)
,E/HttpOperation( 3217): 	at jdm.a(PG:77)
E/HttpOperation( 3217): 	... 12 more
E/HttpOperation( 3217): Caused by: faj: BadAuthentication
E/HttpOperation( 3217): 	at fal.a(PG:38)
E/HttpOperation( 3217): 	at jdj.a(PG:4089),
E/HttpOperation( 3217): 	... 14 more
,I/GLSUser ( 1267): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1267): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1267): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1267): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1267): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3217): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3217): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3217): 	at jdm.a(PG:82)
E/HttpOperation( 3217): 	at jcs.o(PG:406)
E/HttpOperation( 3217): 	at jcn.a(PG:1379)
E/HttpOperation( 3217): 	at jcs.i(PG:143)
E/HttpOperation( 3217): 	at hec.a(PG:42)
E/HttpOperation( 3217): 	at hee.a(PG:102)
E/HttpOperation( 3217): 	at czr.a(PG:65)
E/HttpOperation( 3217): 	at kka.a(PG:108)
E/HttpOperation( 3217): 	at czp.a(PG:19176)
E/HttpOperation( 3217): 	at czp.a(PG:9081)
E/HttpOperation( 3217): 	at czq.run(PG:1686)
E/HttpOperation( 3217): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3217): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3217): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3217): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3217): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3217): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3217): 	at jdj.a(PG:4091)
E/HttpOperation( 3217): 	at jdj.a(PG:1125)
E/HttpOperation( 3217): 	at jdm.a(PG:77)
E/HttpOperation( 3217): 	... 15 more
E/HttpOperation( 3217): Caused by: faj: BadAuthentication
E/HttpOperation( 3217): 	at fal.a(PG:38)
E/HttpOperation( 3217): 	at jdj.a(PG:4089)
E/HttpOperation( 3217): 	... 17 more
E/ExperimentLoader( 3217): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3217): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3217): 	at jdm.a(PG:82)
E/ExperimentLoader( 3217): 	at jcs.o(PG:406)
E/ExperimentLoader( 3217): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3217): 	at jcs.i(PG:143)
E/ExperimentLoader( 3217): 	at hec.a(PG:42)
E/ExperimentLoader( 3217): 	at hee.a(PG:102)
E/ExperimentLoader( 3217): 	at czr.a(PG:65)
E/ExperimentLoader( 3217): 	at kka.a(PG:108)
E/ExperimentLoader( 3217): 	at czp.a(PG:19176)
E/ExperimentLoader( 3217): 	at czp.a(PG:9081)
E/ExperimentLoader( 3217): 	at czq.run(PG:1686)
E/ExperimentLoader( 3217): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3217): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3217): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3217): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3217): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3217): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3217): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3217): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3217): 	at jdm.a(PG:77)
E/ExperimentLoader( 3217): 	... 15 more
E/ExperimentLoader( 3217): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3217): 	at fal.a(PG:38)
E/ExperimentLoader( 3217): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3217): 	... 17 more
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 958981, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,I/wpa_supplicant( 4497): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 5 device(s) discovered,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 4: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): restart: Restarting...
,D/WifiP2pManager( 3810): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): Service request added successfully
,I/wpa_supplicant( 4497): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): Service discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT8301","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Adding new peer: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301], Bluetooth address: 34:FC:EF:11:AE:67, device name: Android_8ae2, device address: 52:55:27:f0:fd:0b
W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT9700","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
,W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT3638","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3810): Got discovery timeout, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3810): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3810): setState: RESTARTING
I/wpa_supplicant( 4497): P2P-FIND-STOPPED 
,I/wpa_supplicant( 4497): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:fd:0b
,I/wpa_supplicant( 4497): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 4497): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 4497): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
,I/wpa_supplicant( 4497): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3810): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3810): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3810): setState: STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3810): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 4497): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 4497): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 4497): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 3 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 3 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/WifiP2pManager( 3810): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): Service request added successfully
,I/wpa_supplicant( 4497): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 4 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 3: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): Service discovery started successfully
,I/wpa_supplicant( 4497): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 4 device(s) discovered,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 3: Android_8ae2 52:55:27:f0:fd:0b
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4778","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: , device address: ee:1f:72:63:11:86
W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT8301","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Adding new peer: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301]
,I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301], Bluetooth address: 34:FC:EF:11:AE:67, device name: Android_8ae2, device address: 52:55:27:f0:fd:0b
W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT5199","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
,W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT3638","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638] already in the list, will not add again
,I/wpa_supplicant( 4497): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 3: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,D/HeadsetStateMachine( 2140): Disconnected process message: 10, size: 0
,I/wpa_supplicant( 4497): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 5 device(s) discovered,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 4: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): restart: Restarting...
,D/WifiP2pManager( 3810): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler },
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): Service request added successfully
,I/wpa_supplicant( 4497): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending,
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): Service discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4778","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local.",
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
,I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778] already in the list, will not add again
,W/bt-btif ( 2140): info:x10
D/        ( 2140): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,E/BluetoothRemoteDevices( 2140): aclStateChangeCallback: Device is NULL
,D/btif_config( 2140): btif_get_device_type: Device [f8:95:c7:87:3c:51] type 1
,I/BluetoothBondStateMachine( 2140): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
E/bt-btif ( 2140): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2140): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2140): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2140): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
,D/BluetoothAdapterProperties( 2140): Failed to remove device: F8:95:C7:87:3C:51
,I/BluetoothBondStateMachine( 2140): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2140): StableState(): Entering Off State
,W/bt-btif ( 2140): new conn_srvc id:26, app_id:255
W/bt-btif ( 2140): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2140): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3810): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3810): Incoming connection initialized (thread ID: 469)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3810): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3810): Entering thread (ID: 469)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3810): onBytesRead: Read 77 bytes successfully (thread ID: 469)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3810): Got valid identity from [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3810): onBytesWritten: 82 bytes successfully written (thread ID: 469)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3810): removeThreadFromList: Removing thread with ID 469
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3810): Handshake thread disposed (thread ID: 469)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3810): onIncomingConnectionConnected: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3810): Exiting thread (ID: 469)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3810): onConnected: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
I/io.jxcore.node.ConnectionHelper( 3810): onConnected: Incoming connection to peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/io.jxcore.node.ConnectionHelper( 3810): hasConnection: No connection with peer with ID F8:95:C7:87:3C:51
W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700] already in the list, will not add again
,I/io.jxcore.node.ConnectionHelper( 3810): onConnected: Incoming socket thread, for peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], created successfully
D/io.jxcore.node.ConnectionHelper( 3810): onConnected: The total number of connections is now 1
D/io.jxcore.node.IncomingSocketThread( 3810): Entering thread (ID: 470)
,I/io.jxcore.node.IncomingSocketThread( 3810): Local host address: localhost/127.0.0.1, port: 41534
,D/io.jxcore.node.IncomingSocketThread( 3810): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3810): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3810): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.IncomingSocketThread( 3810): startStreamCopyingThreads: OK
D/io.jxcore.node.StreamCopyingThread( 3810): Entering thread (ID: 471, name: Sender)
D/io.jxcore.node.IncomingSocketThread( 3810): Exiting thread (ID: 470)
,D/io.jxcore.node.StreamCopyingThread( 3810): Entering thread (ID: 472, name: Receiver),
I/jxcore-log( 3810): 2015-12-18T13:02:31.173Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T13:02:31.852Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T13:02:31.856Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data,
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T13:02:31.861Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T13:02:31.909Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T13:02:31.957Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T13:02:31.961Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T13:02:31.968Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data,
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T13:02:31.999Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T13:02:32.029Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T13:02:32.040Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
,I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T13:02:32.092Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data,
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T13:02:32.101Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data,
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T13:02:32.150Z SendDataTCPServer.js: TCP/IP server has received 25740 bytes of data,
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T13:02:32.154Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T13:02:32.159Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T13:02:32.162Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T13:02:32.210Z SendDataTCPServer.js: TCP/IP server has received 33660 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T13:02:32.250Z SendDataTCPServer.js: TCP/IP server has received 39600 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T13:02:32.269Z SendDataTCPServer.js: TCP/IP server has received 41580 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T13:02:32.276Z SendDataTCPServer.js: TCP/IP server has received 43560 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T13:02:32.309Z SendDataTCPServer.js: TCP/IP server has received 47520 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T13:02:32.358Z SendDataTCPServer.js: TCP/IP server has received 49500 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T13:02:32.414Z SendDataTCPServer.js: TCP/IP server has received 51480 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T13:02:32.421Z SendDataTCPServer.js: TCP/IP server has received 55440 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T13:02:32.459Z SendDataTCPServer.js: TCP/IP server has received 59400 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T13:02:32.479Z SendDataTCPServer.js: TCP/IP server has received 61380 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T13:02:32.486Z SendDataTCPServer.js: TCP/IP server has received 65340 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T13:02:32.519Z SendDataTCPServer.js: TCP/IP server has received 67320 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T13:02:32.536Z SendDataTCPServer.js: TCP/IP server has received 69300 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T13:02:32.540Z SendDataTCPServer.js: TCP/IP server has received 71280 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T13:02:32.548Z SendDataTCPServer.js: TCP/IP server has received 75240 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T13:02:32.596Z SendDataTCPServer.js: TCP/IP server has received 77220 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T13:02:32.600Z SendDataTCPServer.js: TCP/IP server has received 79200 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T13:02:32.605Z SendDataTCPServer.js: TCP/IP server has received 81180 bytes of data,
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T13:02:32.609Z SendDataTCPServer.js: TCP/IP server has received 83160 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T13:02:32.654Z SendDataTCPServer.js: TCP/IP server has received 85140 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T13:02:32.689Z SendDataTCPServer.js: TCP/IP server has received 91080 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T13:02:32.715Z SendDataTCPServer.js: TCP/IP server has received 93060 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T13:02:32.750Z SendDataTCPServer.js: TCP/IP server has received 99000 bytes of data
I/jxcore-log( 3810): 
,I/jxcore-log( 3810): 2015-12-18T13:02:32.773Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3810): 
,W/bt-btif ( 2140): invalid rfc slot id: 22
,W/io.jxcore.node.StreamCopyingThread( 3810): Either failed to read from the output stream or write to the input stream (thread ID: 472, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 3810): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
,W/io.jxcore.node.ConnectionHelper( 3810): onDisconnected: Incoming connection, peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3810): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 470
D/io.jxcore.node.IncomingSocketThread( 3810): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3810): doStop: Thread ID: 472
,D/io.jxcore.node.IncomingSocketThread( 3810): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3810): doStop: Thread ID: 471
D/io.jxcore.node.IncomingSocketThread( 3810): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 3810): closeLocalSocketAndStreams: Closing the local input stream...
,D/io.jxcore.node.IncomingSocketThread( 3810): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 3810): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 3810): closeBluetoothSocketAndStreams
,D/io.jxcore.node.ConnectionHelper( 3810): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3810): Exiting thread (ID: 472, name: Receiver)
W/io.jxcore.node.StreamCopyingThread( 3810): Either failed to read from the output stream or write to the input stream (thread ID: 471, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3810): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3810): onDisconnected: Incoming connection, peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.ConnectionHelper( 3810): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3810): Exiting thread (ID: 471, name: Sender)
I/jxcore-log( 3810): 2015-12-18T13:02:32.908Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3810): 
,W/bt-rfcomm( 2140): rfc_find_lcid_mcb LCID reused LCID:0x4d current:0x0
W/bt-rfcomm( 2140): RFCOMM_DisconnectInd LCID:0x4d
,V/KeepSync( 3749): Connecting to GoogleApiClient
,I/GLSUser ( 1267): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1267): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1267): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1267): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1267): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1805): Handling authorization failure
E/ClientConnectionOperation( 1805): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1805): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1805): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1805): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1805): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1805): 	... 7 more
,V/KeepSync( 3749): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3749): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3749): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3749): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1267): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1267): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1267): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1267): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1267): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3749): IOException
E/KeepSync( 3749): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3749): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3749): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3749): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3749): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3749): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3749): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3749): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3749): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3749): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3749): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3749): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3749): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3749): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3749): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3749): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3749): 	... 10 more
W/KeepSync( 3749): Sync result 2
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 1022742, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,D/btif_config_util( 2140): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2140): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2140): onReceive
,I/BTConnectionReceiver( 1515): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1515): Bluetooth Device Name: G4-1
,D/HeadsetStateMachine( 2140): Disconnected process message: 10, size: 0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT8301","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Adding new peer: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301], Bluetooth address: 34:FC:EF:11:AE:67, device name: Android_8ae2, device address: 52:55:27:f0:fd:0b
W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT9700","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT5199","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199],
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
,W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT3638","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638] already in the list, will not add again
,I/wpa_supplicant( 4497): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 4497): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 4: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 4: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/WifiP2pManager( 3810): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): Service request added successfully
,I/wpa_supplicant( 4497): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): Service discovery started successfully
,I/wpa_supplicant( 4497): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 4: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT9700","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
,W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT5199","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT3638","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638],
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
,I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638] already in the list, will not add again,
,I/wpa_supplicant( 4497): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 4: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,I/wpa_supplicant( 4497): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 4497): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 5 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 4: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 4: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,I/BooksSync( 3716): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3716): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1267): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1267): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1267): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1267): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1267): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1267): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1267): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1267): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1267): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1267): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3716): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3716): Soft error
E/BooksSync( 3716): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3716): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3716): Sync error
E/BooksSync( 3716): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3716): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3716): Finished books sync
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1023268, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/wpa_supplicant( 4497): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 4: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): restart: Restarting...
,D/WifiP2pManager( 3810): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler },
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): Service request added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): Service discovery started successfully,
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4778","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local.",
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
,W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778] already in the list, will not add again
,D/HeadsetStateMachine( 2140): Disconnected process message: 10, size: 0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT9700","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
,W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT5199","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT3638","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
,W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638] already in the list, will not add again
,I/wpa_supplicant( 4497): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 4497): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 4: Android_8ae2 52:55:27:f0:fd:0b
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 5 device(s) discovered,
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638],
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 4: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,D/WifiP2pManager( 3810): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): Service request added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): Service discovery started successfully
,I/wpa_supplicant( 4497): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 4497): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 5 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 4: Android_8ae2 52:55:27:f0:fd:0b
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 4: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4778","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT9700","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT5199","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local.",
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199],
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT3638","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638] already in the list, will not add again,
,I/wpa_supplicant( 4497): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 5 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80,
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 4: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,I/wpa_supplicant( 4497): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 4: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,I/wpa_supplicant( 4497): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 4: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): restart: Restarting...
,D/WifiP2pManager( 3810): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): Service request added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): Service discovery started successfully
,I/wpa_supplicant( 4497): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1,
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 5 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 4: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4778","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
,W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT8301","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Adding new peer: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301], Bluetooth address: 34:FC:EF:11:AE:67, device name: Android_8ae2, device address: 52:55:27:f0:fd:0b
W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT9700","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
,W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT5199","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199],
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT3638","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local.",
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638],
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
,W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638] already in the list, will not add again
,I/wpa_supplicant( 4497): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 4: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,I/wpa_supplicant( 4497): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 5 device(s) discovered,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 4: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,I/wpa_supplicant( 4497): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 4: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): restart: Restarting...
,D/WifiP2pManager( 3810): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler },
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): Service request added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): Service discovery started successfully
,I/wpa_supplicant( 4497): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 4: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4778","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT8301","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Adding new peer: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301], Bluetooth address: 34:FC:EF:11:AE:67, device name: Android_8ae2, device address: 52:55:27:f0:fd:0b
W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301] already in the list, will not add again
,I/art     ( 3217): Explicit concurrent mark sweep GC freed 43309(2MB) AllocSpace objects, 0(0B) LOS objects, 16% free, 40MB/48MB, paused 349us total 46.160ms
,I/GLSUser ( 1267): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1267): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1267): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1267): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1267): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3217): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3217): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3217): 	at jdm.a(PG:82)
E/HttpOperation( 3217): 	at jcs.o(PG:406)
E/HttpOperation( 3217): 	at jcn.a(PG:1379)
E/HttpOperation( 3217): 	at jcs.i(PG:143)
E/HttpOperation( 3217): 	at blb.a(PG:3937)
E/HttpOperation( 3217): 	at czp.a(PG:18188)
E/HttpOperation( 3217): 	at czp.a(PG:9081)
E/HttpOperation( 3217): 	at czq.run(PG:1686)
E/HttpOperation( 3217): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3217): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3217): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3217): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3217): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3217): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3217): 	at jdj.a(PG:4091)
E/HttpOperation( 3217): 	at jdj.a(PG:1125)
E/HttpOperation( 3217): 	at jdm.a(PG:77)
E/HttpOperation( 3217): 	... 12 more
E/HttpOperation( 3217): Caused by: faj: BadAuthentication
E/HttpOperation( 3217): 	at fal.a(PG:38)
E/HttpOperation( 3217): 	at jdj.a(PG:4089)
E/HttpOperation( 3217): 	... 14 more
,I/GLSUser ( 1267): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1267): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1267): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1267): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1267): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3217): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3217): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3217): 	at jdm.a(PG:82)
E/HttpOperation( 3217): 	at jcs.o(PG:406)
E/HttpOperation( 3217): 	at jcn.a(PG:1379)
E/HttpOperation( 3217): 	at jcs.i(PG:143)
E/HttpOperation( 3217): 	at hec.a(PG:42)
E/HttpOperation( 3217): 	at hee.a(PG:102)
E/HttpOperation( 3217): 	at czr.a(PG:65)
E/HttpOperation( 3217): 	at kka.a(PG:108)
E/HttpOperation( 3217): 	at czp.a(PG:19176)
E/HttpOperation( 3217): 	at czp.a(PG:9081)
E/HttpOperation( 3217): 	at czq.run(PG:1686)
E/HttpOperation( 3217): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3217): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3217): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3217): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3217): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3217): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3217): 	at jdj.a(PG:4091)
E/HttpOperation( 3217): 	at jdj.a(PG:1125)
E/HttpOperation( 3217): 	at jdm.a(PG:77)
E/HttpOperation( 3217): 	... 15 more
E/HttpOperation( 3217): Caused by: faj: BadAuthentication
E/HttpOperation( 3217): 	at fal.a(PG:38)
E/HttpOperation( 3217): 	at jdj.a(PG:4089)
E/HttpOperation( 3217): 	... 17 more
,E/ExperimentLoader( 3217): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3217): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3217): 	at jdm.a(PG:82)
E/ExperimentLoader( 3217): 	at jcs.o(PG:406)
E/ExperimentLoader( 3217): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3217): 	at jcs.i(PG:143)
E/ExperimentLoader( 3217): 	at hec.a(PG:42)
E/ExperimentLoader( 3217): 	at hee.a(PG:102)
E/ExperimentLoader( 3217): 	at czr.a(PG:65)
E/ExperimentLoader( 3217): 	at kka.a(PG:108)
E/ExperimentLoader( 3217): 	at czp.a(PG:19176)
E/ExperimentLoader( 3217): 	at czp.a(PG:9081)
E/ExperimentLoader( 3217): 	at czq.run(PG:1686)
E/ExperimentLoader( 3217): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3217): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3217): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3217): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3217): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3217): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3217): 	,at jdj.a(PG:4091)
E/ExperimentLoader( 3217): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3217): 	at jdm.a(PG:77)
E/ExperimentLoader( 3217): 	... 15 more
E/ExperimentLoader( 3217): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3217): 	at fal.a(PG:38)
E/ExperimentLoader( 3217): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3217): 	... 17 more
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 1089071, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT9700","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700],
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT5199","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199],
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac,
W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT3638","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local.",
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638] already in the list, will not add again
,I/wpa_supplicant( 4497): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 4497): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86,
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac,
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 4: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301],
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 5 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638],
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 4: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,D/HeadsetStateMachine( 2140): Disconnected process message: 10, size: 0
,I/wpa_supplicant( 4497): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 4: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): restart: Restarting...
,D/WifiP2pManager( 3810): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): Service request added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): Service discovery started successfully
,I/wpa_supplicant( 4497): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 4497): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1,
I/wpa_supplicant( 4497): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 5 device(s) discovered,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 4: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199],
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 4: Android_8ae2 52:55:27:f0:fd:0b
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 4: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4778","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT8301","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Adding new peer: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301], Bluetooth address: 34:FC:EF:11:AE:67, device name: Android_8ae2, device address: 52:55:27:f0:fd:0b
,W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT9700","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT5199","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT3638","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638] already in the list, will not add again
,I/wpa_supplicant( 4497): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 4: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): restart: Restarting...
,D/WifiP2pManager( 3810): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): Service request added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): Service discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4778","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT8301","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301], Bluetooth address: 34:FC:EF:11:AE:67, device name: Android_8ae2, device address: 52:55:27:f0:fd:0b
W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301] already in the list, will not add again
,D/HeadsetStateMachine( 2140): Disconnected process message: 10, size: 0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT9700","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
,W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT5199","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
,I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
,W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT3638","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local.",
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638] already in the list, will not add again
,I/wpa_supplicant( 4497): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 4497): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1,
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 5 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 4: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199],
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 4: Android_8ae2 52:55:27:f0:fd:0b
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,I/wpa_supplicant( 4497): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 4: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,I/wpa_supplicant( 4497): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 4: Android_8ae2 52:55:27:f0:fd:0b
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): restart: Restarting...
D/WifiP2pManager( 3810): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler },
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): Service request added successfully
,I/wpa_supplicant( 4497): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): Service discovery started successfully
,I/wpa_supplicant( 4497): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 4497): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 5 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 4: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301],
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 5 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 4: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4778","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778] already in the list, will not add again
,V/GoogleAuthProtoRequest( 3931): [431] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1267): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1267): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1267): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1267): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1267): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3931): [431] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3931): [431] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3931): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3931): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3931): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3931): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3931): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3931): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3931): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3931): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3931): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3931): 	at com.a.a.k.run(SourceFile:110)
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT5199","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT3638","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
,I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638] already in the list, will not add again
,I/wpa_supplicant( 4497): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 4: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,I/wpa_supplicant( 4497): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 4: Android_8ae2 52:55:27:f0:fd:0b
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,I/wpa_supplicant( 4497): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 4: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): restart: Restarting...
,D/WifiP2pManager( 3810): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): Service request added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): Service discovery started successfully
,I/wpa_supplicant( 4497): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 4: Android_8ae2 52:55:27:f0:fd:0b
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,D/HeadsetStateMachine( 2140): Disconnected process message: 10, size: 0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT9700","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT5199","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT3638","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
,I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638] already in the list, will not add again
,I/wpa_supplicant( 4497): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 4: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): restart: Restarting...
,D/WifiP2pManager( 3810): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): Service request added successfully
,I/wpa_supplicant( 4497): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 5 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 4: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): Service discovery started successfully
,I/wpa_supplicant( 4497): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 5 device(s) discovered,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 4: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,D/HeadsetStateMachine( 2140): Disconnected process message: 10, size: 0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3810): Got discovery timeout, restarting...,
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3810): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3810): setState: RESTARTING
I/wpa_supplicant( 4497): P2P-FIND-STOPPED 
,I/wpa_supplicant( 4497): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
,I/wpa_supplicant( 4497): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:fd:0b
,I/wpa_supplicant( 4497): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 4497): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
,I/wpa_supplicant( 4497): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3810): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3810): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3810): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3810): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3810): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 4497): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 1 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 1: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): restart: Restarting...
,D/WifiP2pManager( 3810): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): Service request added successfully
,I/wpa_supplicant( 4497): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): Service discovery started successfully
,I/wpa_supplicant( 4497): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 1 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 1: Android_8ae2 52:55:27:f0:fd:0b
,I/wpa_supplicant( 4497): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 2 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 2: Android_8ae2 52:55:27:f0:fd:0b
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4778","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778] already in the list, will not add again
,I/UsageStatsService(  823): User[0] Flushing usage stats to disk
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT5199","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199],
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], Bluetooth address: 58:3F:54:73:64:C0, device name: , device address: 02:9a:02:7b:60:ac
,W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT3638","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
,I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], Bluetooth address: F8:95:C7:87:85:54, device name: , device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638] already in the list, will not add again
,I/wpa_supplicant( 4497): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 3 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 3: Android_8ae2 52:55:27:f0:fd:0b
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT9700","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700] already in the list, will not add again
,I/wpa_supplicant( 4497): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 4: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): restart: Restarting...
,D/WifiP2pManager( 3810): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): Service request added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): Service discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT9700","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
,W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT3638","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local.",
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
,I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], Bluetooth address: F8:95:C7:87:85:54, device name: , device address: a2:39:f7:70:12:80
,W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT5199","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199],
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4778","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT8301","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Adding new peer: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301]
,I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301], Bluetooth address: 34:FC:EF:11:AE:67, device name: Android_8ae2, device address: 52:55:27:f0:fd:0b
W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301] already in the list, will not add again
,I/wpa_supplicant( 4497): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 4497): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1,
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 5: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 5: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301]
,I/wpa_supplicant( 4497): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 5: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301]
,I/wpa_supplicant( 4497): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 5: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): restart: Restarting...
,D/WifiP2pManager( 3810): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): Service request added successfully
,I/wpa_supplicant( 4497): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): Service discovery started successfully
,I/wpa_supplicant( 4497): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 5 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 5: Android_8ae2 52:55:27:f0:fd:0b
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301]
,D/HeadsetStateMachine( 2140): Disconnected process message: 10, size: 0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT3638","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT5199","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
,W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199] already in the list, will not add again
,I/wpa_supplicant( 4497): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 5 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 5: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): restart: Restarting...
,D/WifiP2pManager( 3810): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): Service request added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): Service discovery started successfully
,I/wpa_supplicant( 4497): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 5 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 5: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301]
,I/art     ( 3749): Explicit concurrent mark sweep GC freed 19683(2MB) AllocSpace objects, 0(0B) LOS objects, 24% free, 23MB/31MB, paused 488us total 41.948ms
,V/KeepSync( 3749): Connecting to GoogleApiClient
,I/GLSUser ( 1267): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1267): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1267): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1267): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1267): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  823): Explicit concurrent mark sweep GC freed 60919(2MB) AllocSpace objects, 13(585KB) LOS objects, 31% free, 34MB/50MB, paused 2.063ms total 95.840ms
,E/ClientConnectionOperation( 1805): Handling authorization failure
E/ClientConnectionOperation( 1805): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1805): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1805): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1805): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1805): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1805): 	... 7 more
,V/KeepSync( 3749): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3749): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3749): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3749): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1267): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1267): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1267): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1267): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1267): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3749): IOException
E/KeepSync( 3749): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3749): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3749): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3749): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3749): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3749): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3749): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3749): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3749): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3749): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3749): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3749): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3749): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3749): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3749): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3749): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3749): 	... 10 more
W/KeepSync( 3749): Sync result 2
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT3638","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638] already in the list, will not add again
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 1280357, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT5199","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT8301","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301], Bluetooth address: 34:FC:EF:11:AE:67, device name: Android_8ae2, device address: 52:55:27:f0:fd:0b
,W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301] already in the list, will not add again
,I/wpa_supplicant( 4497): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 5 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 5: Android_8ae2 52:55:27:f0:fd:0b
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): restart: Restarting...
,D/WifiP2pManager( 3810): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): Service request added successfully
,I/wpa_supplicant( 4497): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): Service discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT9700","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT3638","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
,W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT5199","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
,W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Identity: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT8301","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): onDnsSdServiceAvailable: Resolved peer properties: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onServiceDiscovered: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onPeerDiscovered: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301]
I/io.jxcore.node.ConnectionHelper( 3810): onPeerDiscovered: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301], Bluetooth address: 34:FC:EF:11:AE:67, device name: Android_8ae2, device address: 52:55:27:f0:fd:0b
,W/io.jxcore.node.ConnectionHelper( 3810): modifyListOfDiscoveredPeers: Peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301] already in the list, will not add again
,I/wpa_supplicant( 4497): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 4497): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 5 device(s) discovered,
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 5: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 5: Android_8ae2 52:55:27:f0:fd:0b
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301]
,I/wpa_supplicant( 4497): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 4 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 4: Android_8ae2 52:55:27:f0:fd:0b
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301]
,I/wpa_supplicant( 4497): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 4 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onP2pDeviceListChanged: Peer 4: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8301]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): restart: Restarting...
,F/libc    ( 4497): Fatal signal 11 (SIGSEGV), code 1, fault addr 0xc in tid 4497 (wpa_supplicant)
,I/libc    ( 4497): Suppressing debuggerd output because prctl(PR_GET_DUMPABLE)==0
,D/WifiP2pManager( 3810): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): Service request added successfully
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3810): Failed to start the service discovery, got error code: 3
,D/HeadsetStateMachine( 2140): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2140): Disconnected process message: 10, size: 0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3810): Got discovery timeout, restarting...,
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3810): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3810): setState: RESTARTING
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3810): Failed to shutdown P2P device discovery, got error code: 0
,E/WifiStateMachine(  823): Connection lost, restart supplicant
,E/WifiMonitor(  823): killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,W/Settings( 3869): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,E/WifiConfigStore(  823): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,W/Settings( 1773): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/WifiConfigStore(  823): failed to set BSSID: any
,E/native  (  823): do suspend true
D/CommandListener(  355): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1267): Read error: ssl=0xb4884a00: I/O error during system call, Connection timed out
I/jxcore-log( 3810): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 3810): 
I/jxcore-log( 3810): The Coordinator has disconnected!
I/jxcore-log( 3810): 
,V/NativeCrypto( 1267): SSL shutdown failed: ssl=0xb4884a00: I/O error during system call, Broken pipe
,D/ConnectivityService(  823): NetworkAgentInfo [WIFI () - 103] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  823): NetworkAgentInfo [WIFI () - 103] got DISCONNECTED, was satisfying 2
E/WifiStateMachine(  823): WifiStateMachine: Leaving Connected state
,E/WifiStateMachine(  823): Unexpected BatchedScanResults :null
D/ConnectivityService(  823): reportBadNetwork(NetworkAgentInfo [WIFI () - 103]) by 10011
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 103](  823): ValidatedState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 103](  823): DefaultState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 103](  823): Forcing reevaluation
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 103](  823): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService(  823): SCAN_AVAILABLE : 1
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 103](  823): Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
D/RttService(  823): SCAN_AVAILABLE : 1
D/RttService(  823): EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3810): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/WifiNetworkAgent(  823): NetworkAgent: NetworkAgent channel lost
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onWifiStateChanged: State changed to 1
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onWifiStateChanged: Wi-Fi disabled, pausing Wi-Fi Direct based peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): stop: Stopping services
D/WifiScanningService(  823): StartedState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService(  823): DefaultState
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3810): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3810): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): onIsWifiPeerDiscoveryStartedChanged: false
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): stopWifiPeerDiscovery: Stopped
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3810): setState: WAITING_FOR_SERVICES_TO_BE_ENABLED
I/io.jxcore.node.ConnectionHelper( 3810): onDiscoveryManagerStateChanged: WAITING_FOR_SERVICES_TO_BE_ENABLED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3810): onP2pDeviceListChanged: 0 device(s) discovered
D/AndroidRuntime( 3810): Shutting down VM
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 103](  823): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
,D/ConnectivityService(  823): notifyType LOST for NetworkAgentInfo [WIFI () - 103]
D/ConnectivityManager.CallbackHandler( 1073): CM callback handler got msg 524292
,D/CSLegacyTypeTracker(  823): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 103] isDefaultNetwork=true
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 103](  823): OfflineState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  823): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 103](  823): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 103](  823): Disconnected - quitting
D/ConnectivityService(  823): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  823): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  823): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  823): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService(  823): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/ConnectivityService(  823): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/Tethering(  823): MasterInitialState.processMessage what=3
D/Tethering(  823): MasterInitialState.processMessage what=3
,V/MusicLeanback( 3902): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/SprintDMReceiver( 3959): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3959): simOperator:  IMSI: null
D/SprintDMReceiver( 3959): Not Sprint UICC, don't do anything.
I/SystemUpdateService( 1805): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/PhoneInterfaceManager( 1338): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1338): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
D/SystemUpdateService( 1805): onCreate
,D/TelephonyManager(  823): getDataEnabled: retVal=false
,D/SystemUpdateService( 1805): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,E/GpsLocationProvider(  823): No APN found to select.
,D/PhoneInterfaceManager( 1338): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
,E/PhoneInterfaceManager( 1338): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
D/TelephonyManager(  823): getDataEnabled: retVal=false
,I/SystemUpdateService( 1805): active receiver: enabled
,E/GpsLocationProvider(  823): No APN found to select.
,I/SystemUpdateService( 1805): showing system update notification
I/iu.Environment( 1805): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1805): num queued entries: 0
,I/iu.UploadsManager( 1805): num updated entries: 0
,I/iu.SyncManager( 1805): NEXT; no task
,D/ChimeraCfgMgr( 1805): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Babel   ( 3869): connection state changed from CONNECTED to DISCONNECTED
,I/ValidateNoPeople(  823): skipping global notification
,V/MusicLeanback( 3902): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,V/SystemUpdateService( 1805): retry (wakeup: false) in 3599973 ms
,D/SystemUpdateService( 1805): onDestroy
,D/SprintDMReceiver( 3959): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3959): simOperator:  IMSI: null
D/SprintDMReceiver( 3959): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1805): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1805): onCreate
,D/SystemUpdateService( 1805): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1805): active receiver: enabled
,I/SystemUpdateService( 1805): showing system update notification
,D/ChimeraCfgMgr( 1805): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/ValidateNoPeople(  823): skipping global notification
,V/SystemUpdateService( 1805): retry (wakeup: false) in 3599981 ms
,D/SystemUpdateService( 1805): onDestroy
,D/SoftapController(  355): Softap fwReload - Ok
,D/CommandListener(  355): Setting iface cfg
,D/CommandListener(  355): Trying to bring down wlan0
,D/Tethering(  823): InitialState.processMessage what=4
D/CommandListener(  355): Clearing all IP addresses on wlan0
,D/Tethering(  823): sendTetherStateChangedBroadcast 0, 0, 0
,E/WifiMonitor(  823): killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,I/wpa_supplicant( 4742): Successfully initialized wpa_supplicant
,D/WifiMonitor(  823): startMonitoring(wlan0) with mConnected = false
,I/wpa_supplicant( 4742): rfkill: Cannot open RFKILL control device
,I/art     ( 1267): Explicit concurrent mark sweep GC freed 52320(2MB) AllocSpace objects, 17(1874KB) LOS objects, 37% free, 27MB/43MB, paused 1.540ms total 45.741ms
,D/Tethering(  823): sendTetherStateChangedBroadcast 1, 0, 0
,I/wpa_supplicant( 4742): rfkill: Cannot open RFKILL control device,
E/wpa_supplicant( 4742): Could not read interface p2p-dev-wlan0 flags: No such device
,D/WifiConfigStore(  823): Loading config and enabling all networks 
,D/WifiService(  823): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@32152dbf}
,E/WifiConfigStore(  823): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,D/WifiNative-HAL(  823): Setting external_sim to 1
,D/WifiStateMachine(  823): Setting OUI to 92-68-C3
I/WifiNative-HAL(  823): startHal
D/wifi    (  823): setting scan oui 0xb4b70f58
D/WifiHAL (  823): Sending mac address OUI
W/Settings( 3869): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,E/native  (  823): do suspend true
,D/WifiScanningService(  823): SCAN_AVAILABLE : 3
,W/CommandListener(  355): Failed to retrieve HW addr for p2p0 (No such device)
D/WifiScanningService(  823): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  823): startHal
,D/RttService(  823): SCAN_AVAILABLE : 3
D/wifi    (  823): getting scan capabilities on interface[0] = 0xb4b70f58
D/WifiHAL (  823): Creating message to get scan capablities; iface = 5
D/WifiHAL (  823): In GetCapabilities::handleResponse
,D/WifiHAL (  823): Id = 0, subcmd = 0, len = 28, expected len = 32
D/WifiScanningService(  823): StartedState
D/RttService(  823): DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,D/CommandListener(  355): Setting iface cfg
E/WifiP2pService(  823): Unable to change interface settings: java.lang.IllegalStateException: command '132 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 132 Failed to set address (No such device)'
D/WifiMonitor(  823): startMonitoring(p2p0) with mConnected = true
,I/wpa_supplicant( 4742): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,D/WifiNative-HAL(  823): p2pGetDeviceAddress
,D/WifiNative-HAL(  823): p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,I/wpa_supplicant( 4742): p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,E/WifiStateMachine(  823): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
E/WifiConfigStore(  823):  rewrite network history for "NG700"WPA_PSK
E/WifiConfigStore(  823):  rewrite network history for "NG7005g"WPA_PSK
,E/WifiStateMachine(  823): CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
,E/WifiConfigStore(  823): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiConfigStore(  823): writeKnownNetworkHistory write linked 1
,E/WifiConfigStore(  823): writeKnownNetworkHistory write linked 1,
E/WifiStateMachine(  823): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=0
,E/WifiConfigStore(  823): will read network variables netId=0
,E/WifiStateMachine(  823): CMD_AUTO_CONNECT did save config ->  nid=0
,E/WifiConfigStore(  823): will read network variables netId=0
,I/wpa_supplicant( 4742): wlan0: Trying to associate with SSID 'NG7005g'
,I/wpa_supplicant( 4742): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 4742): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 4742): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=0 id_str=]
,D/ConnectivityService(  823): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} }
E/WifiConfigStore(  823): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  823): NetworkAgentInfo [WIFI () - 104] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  823): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  355): Setting iface cfg
,E/WifiStateMachine(  823): Start Dhcp Watchdog 5
,E/WifiStateMachine(  823):  WifiLinkLayerStats: 
,E/WifiStateMachine(  823):  my bss beacon rx: 1
E/WifiStateMachine(  823):  RSSI mgmt: -46
E/WifiStateMachine(  823):  BE :  rx=0 tx=2 lost=0 retries=0
E/WifiStateMachine(  823):  BK :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  823):  VI :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  823):  VO :  rx=2 tx=0 lost=0 retries=0
E/WifiStateMachine(  823):  on_time : 0 tx_time=59 rx_time=79 scan_time=0
,E/native  (  823): do suspend false
,E/WifiStateMachine(  823): scanCount==0 - aborting
,I/dhcpcd  ( 4751): version 5.5.6 starting
,I/dhcpcd  ( 4751): wlan0: rebinding lease of 192.168.1.122
,I/dhcpcd  ( 4751): wlan0: acknowledged 192.168.1.122 from 192.168.1.1
,I/dhcpcd  ( 4751): wlan0: leased 192.168.1.122 for 86400 seconds
,E/native  (  823): do suspend true
,D/ConnectivityService(  823): NetworkAgentInfo [WIFI () - 104] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED,
,D/ConnectivityService(  823): Adding iface wlan0 to network 104
,E/WifiStateMachine(  823): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  823): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  823): Adding Route [fe80::/64 -> :: wlan0] to network 104
,D/ConnectivityService(  823): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 104
,D/ConnectivityService(  823): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 104
D/ConnectivityService(  823): Setting Dns servers for network 104 to [/192.168.1.1]
,D/ConnectivityService(  823): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 104]
,D/ConnectivityService(  823): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 104]
,D/ConnectivityService(  823): rematching NetworkAgentInfo [WIFI () - 104]
,D/ConnectivityService(  823):    accepting network in place of null
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 104](  823): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 104](  823): Connected
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 104](  823): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 104](  823): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
D/ConnectivityService(  823): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{104}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} }
D/ConnectivityService(  823): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 104]
D/CSLegacyTypeTracker(  823): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 104] isDefaultNetwork=true,
D/ConnectivityManager.CallbackHandler( 1073): CM callback handler got msg 524290
D/ConnectivityService(  823): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  823): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering(  823): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 3902): type=WIFI subType= reason=null isConnected=true
,D/PhoneInterfaceManager( 1338): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1338): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  823): getDataEnabled: retVal=false
,V/MusicLeanback( 3902): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,E/GpsLocationProvider(  823): No APN found to select.
,D/SprintDMReceiver( 3959): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3959): simOperator:  IMSI: null
D/SprintDMReceiver( 3959): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1805): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,I/BooksSync( 3716): Starting books sync for 61035162, extras: ade
,D/SystemUpdateService( 1805): onCreate
,D/SystemUpdateService( 1805): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1805): active receiver: enabled
,I/BooksConfig( 3716): GmsCore Version = 7.8.99 (2134222-430)
,I/SystemUpdateService( 1805): showing system update notification
,I/iu.Environment( 1805): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1805): num queued entries: 0
I/iu.UploadsManager( 1805): num updated entries: 0
,I/ValidateNoPeople(  823): skipping global notification
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 104](  823): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 18 Dec 2015 13:07:57 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1450444077141], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1450444077128]}
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 104](  823): Validated
D/ConnectivityService(  823): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/ConnectivityService(  823): Validated NetworkAgentInfo [WIFI () - 104]
D/ConnectivityService(  823): rematching NetworkAgentInfo [WIFI () - 104]
D/ConnectivityService(  823): Network NetworkAgentInfo [WIFI () - 104] was already satisfying request 1. No change.
D/ConnectivityService(  823): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 104]
D/ConnectivityService(  823): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1073): CM callback handler got msg 524290
,I/iu.SyncManager( 1805): NEXT; no task
,V/SystemUpdateService( 1805): retry (wakeup: false) in 3599967 ms
,D/ChimeraCfgMgr( 1805): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/GLSUser ( 1267): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1267): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1267): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1267): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/SystemUpdateService( 1805): onDestroy
,V/GLSActivity( 1267): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ChimeraCfgMgr( 1805): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/GLSUser ( 1267): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1267): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1267): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1267): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1267): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/Herrevad( 1805): NQAS connected
,I/GLSUser ( 1267): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1267): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1267): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1267): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1267): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Babel   ( 3869): connection state changed from DISCONNECTED to CONNECTED
,W/Kids    ( 1805): [AccountUtils] Account not ready
W/Kids    ( 1805): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 1805): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 1805): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 1805): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 1805): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 1805): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 1805): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 1805): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 1805): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 1805): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 1805): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 1805): 	at java.lang.Thread.run(Thread.java:818)
,E/BooksAccountManager( 3716): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3716): Soft error
E/BooksSync( 3716): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3716): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3716): Sync error
E/BooksSync( 3716): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3716): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3716): Finished books sync
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1311118, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1],
,D/WifiService(  823): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@32152dbf}
,D/GCM     ( 1267): Connected
,D/GCM     ( 1267): Message class com.google.f.a.a.p
,D/ConnectivityService(  823): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 103] cleared because we found a replacement network
,D/HeadsetStateMachine( 2140): Disconnected process message: 10, size: 0
,I/GLSUser ( 1267): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1267): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1267): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1267): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1267): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/HttpOperation( 3217): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3217): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3217): 	at jdm.a(PG:82)
E/HttpOperation( 3217): 	at jcs.o(PG:406)
E/HttpOperation( 3217): 	at jcn.a(PG:1379)
E/HttpOperation( 3217): 	at jcs.i(PG:143)
E/HttpOperation( 3217): 	at blb.a(PG:3937)
E/HttpOperation( 3217): 	at czp.a(PG:18188)
E/HttpOperation( 3217): 	at czp.a(PG:9081)
E/HttpOperation( 3217): 	at czq.run(PG:1686)
E/HttpOperation( 3217): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3217): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3217): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3217): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3217): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3217): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3217): 	at jdj.a(PG:4091)
E/HttpOperation( 3217): 	at jdj.a(PG:1125)
E/HttpOperation( 3217): 	at jdm.a(PG:77)
E/HttpOperation( 3217): 	... 12 more
E/HttpOperation( 3217): Caused by: faj: BadAuthentication
E/HttpOperation( 3217): 	at fal.a(PG:38)
E/HttpOperation( 3217): 	at jdj.a(PG:4089)
E/HttpOperation( 3217): 	... 14 more
,I/art     (  823): Explicit concurrent mark sweep GC freed 65846(3MB) AllocSpace objects, 7(300KB) LOS objects, 31% free, 34MB/50MB, paused 2.914ms total 113.245ms
,I/GLSUser ( 1267): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1267): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1267): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1267): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1267): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3217): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3217): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3217): 	at jdm.a(PG:82)
E/HttpOperation( 3217): 	at jcs.o(PG:406)
E/HttpOperation( 3217): 	at jcn.a(PG:1379)
E/HttpOperation( 3217): 	at jcs.i(PG:143)
E/HttpOperation( 3217): 	at hec.a(PG:42)
E/HttpOperation( 3217): 	at hee.a(PG:102)
E/HttpOperation( 3217): 	at czr.a(PG:65)
E/HttpOperation( 3217): 	at kka.a(PG:108)
E/HttpOperation( 3217): 	at czp.a(PG:19176)
E/HttpOperation( 3217): 	at czp.a(PG:9081)
E/HttpOperation( 3217): 	at czq.run(PG:1686)
E/HttpOperation( 3217): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3217): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3217): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3217): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3217): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3217): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3217): 	at jdj.a(PG:4091)
E/HttpOperation( 3217): 	at jdj.a(PG:1125)
E/HttpOperation( 3217): 	at jdm.a(PG:77)
E/HttpOperation( 3217): 	... 15 more
E/HttpOperation( 3217): Caused by: faj: BadAuthentication
E/HttpOperation( 3217): 	at fal.a(PG:38)
E/HttpOperation( 3217): 	at jdj.a(PG:4089)
E/HttpOperation( 3217): 	... 17 more
,E/ExperimentLoader( 3217): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3217): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3217): 	at jdm.a(PG:82)
E/ExperimentLoader( 3217): 	at jcs.o(PG:406)
E/ExperimentLoader( 3217): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3217): 	at jcs.i(PG:143)
E/ExperimentLoader( 3217): 	at hec.a(PG:42)
E/ExperimentLoader( 3217): 	at hee.a(PG:102)
E/ExperimentLoader( 3217): 	at czr.a(PG:65)
E/ExperimentLoader( 3217): ,	at kka.a(PG:108)
E/ExperimentLoader( 3217): 	at czp.a(PG:19176)
E/ExperimentLoader( 3217): 	at czp.a(PG:9081)
E/ExperimentLoader( 3217): 	at czq.run(PG:1686)
E/ExperimentLoader( 3217): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3217): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3217): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3217): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587),
E/ExperimentLoader( 3217): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3217): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3217): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3217): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3217): 	at jdm.a(PG:77)
E/ExperimentLoader( 3217): 	... 15 more
E/ExperimentLoader( 3217): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3217): 	at fal.a(PG:38)
E/ExperimentLoader( 3217): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3217): 	... 17 more
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 1372803, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2140): Disconnected process message: 10, size: 0
,I/BooksSync( 3716): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3716): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1267): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1267): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1267): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1267): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1267): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1267): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1267): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1267): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1267): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1267): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3716): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3716): Soft error
E/BooksSync( 3716): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3716): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3716): Sync error
E/BooksSync( 3716): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3716): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3716): Finished books sync
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1377182, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2140): Disconnected process message: 10, size: 0
,I/GLSUser ( 1267): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1267): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1267): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1267): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1267): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3217): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3217): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3217): 	at jdm.a(PG:82)
E/HttpOperation( 3217): 	at jcs.o(PG:406)
E/HttpOperation( 3217): 	at jcn.a(PG:1379)
E/HttpOperation( 3217): 	at jcs.i(PG:143)
E/HttpOperation( 3217): 	at blb.a(PG:3937)
E/HttpOperation( 3217): 	at czp.a(PG:18188)
E/HttpOperation( 3217): 	at czp.a(PG:9081)
E/HttpOperation( 3217): 	at czq.run(PG:1686)
E/HttpOperation( 3217): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3217): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3217): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3217): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3217): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3217): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3217): 	at jdj.a(PG:4091)
E/HttpOperation( 3217): 	at jdj.a(PG:1125)
E/HttpOperation( 3217): 	at jdm.a(PG:77)
E/HttpOperation( 3217): 	... 12 more
E/HttpOperation( 3217): Caused by: faj: BadAuthentication
E/HttpOperation( 3217): 	at fal.a(PG:38)
E/HttpOperation( 3217): 	at jdj.a(PG:4089)
E/HttpOperation( 3217): 	... 14 more
,I/GLSUser ( 1267): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1267): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1267): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1267): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1267): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3217): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3217): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3217): 	at jdm.a(PG:82)
E/HttpOperation( 3217): 	at jcs.o(PG:406)
E/HttpOperation( 3217): 	at jcn.a(PG:1379)
E/HttpOperation( 3217): 	at jcs.i(PG:143)
E/HttpOperation( 3217): 	at hec.a(PG:42)
E/HttpOperation( 3217): 	at hee.a(PG:102)
E/HttpOperation( 3217): 	at czr.a(PG:65)
E/HttpOperation( 3217): 	at kka.a(PG:108)
E/HttpOperation( 3217): 	at czp.a(PG:19176)
E/HttpOperation( 3217): 	at czp.a(PG:9081)
E/HttpOperation( 3217): 	at czq.run(PG:1686)
E/HttpOperation( 3217): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3217): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3217): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3217): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3217): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3217): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3217): 	at jdj.a(PG:4091)
E/HttpOperation( 3217): 	at jdj.a(PG:1125)
E/HttpOperation( 3217): 	at jdm.a(PG:77)
E/HttpOperation( 3217): 	... 15 more
E/HttpOperation( 3217): Caused by: faj: BadAuthentication
E/HttpOperation( 3217): 	at fal.a(PG:38)
E/HttpOperation( 3217): 	at jdj.a(PG:4089)
E/HttpOperation( 3217): 	... 17 more
E/ExperimentLoader( 3217): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3217): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3217): 	at jdm.a(PG:82)
E/ExperimentLoader( 3217): 	at jcs.o(PG:406)
E/ExperimentLoader( 3217): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3217): 	at jcs.i(PG:143)
E/ExperimentLoader( 3217): 	at hec.a(PG:42)
E/ExperimentLoader( 3217): 	at hee.a(PG:102)
E/ExperimentLoader( 3217): 	at czr.a(PG:65)
E/ExperimentLoader( 3217): 	at kka.a(PG:108)
E/ExperimentLoader( 3217): 	at czp.a(PG:19176)
E/ExperimentLoader( 3217): 	at czp.a(PG:9081)
E/ExperimentLoader( 3217): 	at czq.run(PG:1686)
E/ExperimentLoader( 3217): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3217): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3217): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3217): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3217): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3217): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3217): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3217): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3217): 	at jdm.a(PG:77)
E/ExperimentLoader( 3217): 	... 15 more
E/ExperimentLoader( 3217): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3217): 	at fal.a(PG:38)
E/ExperimentLoader( 3217): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3217): 	... 17 more
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 1407795, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2140): Disconnected process message: 10, size: 0
,I/BooksSync( 3716): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3716): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1267): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1267): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1267): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1267): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1267): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1267): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1267): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1267): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1267): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1267): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3716): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3716): Soft error
E/BooksSync( 3716): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3716): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3716): Sync error
E/BooksSync( 3716): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3716): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source),
I/BooksSync( 3716): Finished books sync
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1468193, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2140): Disconnected process message: 10, size: 0
,I/GLSUser ( 1267): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1267): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1267): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1267): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1267): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3217): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3217): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3217): 	at jdm.a(PG:82)
E/HttpOperation( 3217): 	at jcs.o(PG:406)
E/HttpOperation( 3217): 	at jcn.a(PG:1379)
E/HttpOperation( 3217): 	at jcs.i(PG:143)
E/HttpOperation( 3217): 	at blb.a(PG:3937)
E/HttpOperation( 3217): 	at czp.a(PG:18188)
E/HttpOperation( 3217): 	at czp.a(PG:9081)
E/HttpOperation( 3217): 	at czq.run(PG:1686)
E/HttpOperation( 3217): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3217): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3217): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3217): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3217): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3217): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3217): 	at jdj.a(PG:4091)
E/HttpOperation( 3217): 	at jdj.a(PG:1125)
E/HttpOperation( 3217): 	at jdm.a(PG:77)
E/HttpOperation( 3217): 	... 12 more
E/HttpOperation( 3217): Caused by: faj: BadAuthentication
E/HttpOperation( 3217): 	at fal.a(PG:38)
E/HttpOperation( 3217): 	at jdj.a(PG:4089)
E/HttpOperation( 3217): 	... 14 more
,I/GLSUser ( 1267): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1267): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1267): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1267): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1267): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3217): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3217): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3217): 	at jdm.a(PG:82)
E/HttpOperation( 3217): 	at jcs.o(PG:406)
E/HttpOperation( 3217): 	at jcn.a(PG:1379)
E/HttpOperation( 3217): 	at jcs.i(PG:143)
E/HttpOperation( 3217): 	at hec.a(PG:42)
E/HttpOperation( 3217): 	at hee.a(PG:102)
E/HttpOperation( 3217): 	at czr.a(PG:65)
E/HttpOperation( 3217): 	at kka.a(PG:108)
E/HttpOperation( 3217): 	at czp.a(PG:19176)
E/HttpOperation( 3217): 	at czp.a(PG:9081)
E/HttpOperation( 3217): 	at czq.run(PG:1686)
E/HttpOperation( 3217): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3217): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3217): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3217): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3217): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3217): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3217): 	at jdj.a(PG:4091)
E/HttpOperation( 3217): 	at jdj.a(PG:1125)
E/HttpOperation( 3217): 	at jdm.a(PG:77)
E/HttpOperation( 3217): 	... 15 more
E/HttpOperation( 3217): Caused by: faj: BadAuthentication
E/HttpOperation( 3217): 	at fal.a(PG:38)
E/HttpOperation( 3217): 	at jdj.a(PG:4089)
E/HttpOperation( 3217): 	... 17 more
,E/ExperimentLoader( 3217): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3217): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3217): 	at jdm.a(PG:82)
E/ExperimentLoader( 3217): 	at jcs.o(PG:406)
E/ExperimentLoader( 3217): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3217): 	at jcs.i(PG:143)
,E/ExperimentLoader( 3217): 	at hec.a(PG:42)
E/ExperimentLoader( 3217): 	at hee.a(PG:102)
E/ExperimentLoader( 3217): 	at czr.a(PG:65)
E/ExperimentLoader( 3217): 	at kka.a(PG:108)
E/ExperimentLoader( 3217): 	at czp.a(PG:19176)
E/ExperimentLoader( 3217): 	at czp.a(PG:9081)
E/ExperimentLoader( 3217): 	at czq.run(PG:1686)
E/ExperimentLoader( 3217): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3217): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3217): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3217): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3217): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3217): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3217): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3217): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3217): 	at jdm.a(PG:77)
E/ExperimentLoader( 3217): 	... 15 more,
E/ExperimentLoader( 3217): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3217): 	at fal.a(PG:38)
E/ExperimentLoader( 3217): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3217): 	... 17 more
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 1498597, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2140): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2140): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2140): Disconnected process message: 10, size: 0
,I/BooksSync( 3716): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3716): GmsCore Version = 7.8.99 (2134222-430)
,I/art     ( 1267): Explicit concurrent mark sweep GC freed 58339(3MB) AllocSpace objects, 8(882KB) LOS objects, 37% free, 27MB/43MB, paused 1.852ms total 68.878ms
,I/GLSUser ( 1267): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1267): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1267): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1267): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1267): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1267): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1267): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1267): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1267): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1267): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3716): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3716): Soft error
E/BooksSync( 3716): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3716): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3716): Sync error
E/BooksSync( 3716): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3716): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3716): Finished books sync
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1620034, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2140): Disconnected process message: 10, size: 0
,W/bt-btm  ( 2140): Stopping oneshot timer
,I/art     (  823): Explicit concurrent mark sweep GC freed 47579(2MB) AllocSpace objects, 11(458KB) LOS objects, 31% free, 34MB/50MB, paused 1.550ms total 97.789ms
,I/GLSUser ( 1267): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1267): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1267): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1267): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1267): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3217): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3217): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3217): 	at jdm.a(PG:82)
E/HttpOperation( 3217): 	at jcs.o(PG:406)
E/HttpOperation( 3217): 	at jcn.a(PG:1379)
E/HttpOperation( 3217): 	at jcs.i(PG:143)
E/HttpOperation( 3217): 	at blb.a(PG:3937)
E/HttpOperation( 3217): 	at czp.a(PG:18188)
E/HttpOperation( 3217): 	at czp.a(PG:9081)
E/HttpOperation( 3217): 	at czq.run(PG:1686)
E/HttpOperation( 3217): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3217): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3217): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3217): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3217): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3217): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3217): 	at jdj.a(PG:4091)
E/HttpOperation( 3217): 	at jdj.a(PG:1125)
E/HttpOperation( 3217): 	at jdm.a(PG:77)
E/HttpOperation( 3217): 	... 12 more
E/HttpOperation( 3217): Caused by: faj: BadAuthentication
E/HttpOperation( 3217): 	at fal.a(PG:38)
E/HttpOperation( 3217): 	at jdj.a(PG:4089)
E/HttpOperation( 3217): 	... 14 more
,I/GLSUser ( 1267): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1267): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1267): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1267): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1267): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3217): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3217): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3217): 	at jdm.a(PG:82)
E/HttpOperation( 3217): 	at jcs.o(PG:406)
E/HttpOperation( 3217): 	at jcn.a(PG:1379)
E/HttpOperation( 3217): 	at jcs.i(PG:143)
E/HttpOperation( 3217): 	at hec.a(PG:42)
E/HttpOperation( 3217): 	at hee.a(PG:102)
E/HttpOperation( 3217): 	at czr.a(PG:65)
E/HttpOperation( 3217): 	at kka.a(PG:108)
E/HttpOperation( 3217): 	at czp.a(PG:19176)
E/HttpOperation( 3217): 	at czp.a(PG:9081)
E/HttpOperation( 3217): 	at czq.run(PG:1686)
E/HttpOperation( 3217): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3217): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3217): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3217): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3217): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3217): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3217): 	at jdj.a(PG:4091)
E/HttpOperation( 3217): 	at jdj.a(PG:1125)
E/HttpOperation( 3217): 	at jdm.a(PG:77)
E/HttpOperation( 3217): 	... 15 more
E/HttpOperation( 3217): Caused by: faj: BadAuthentication
E/HttpOperation( 3217): 	at fal.a(PG:38)
E/HttpOperation( 3217): 	at jdj.a(PG:4089)
E/HttpOperation( 3217): 	... 17 more
,E/ExperimentLoader( 3217): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3217): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3217): 	at jdm.a(PG:82),
E/ExperimentLoader( 3217): 	at jcs.o(PG:406)
E/ExperimentLoader( 3217): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3217): 	at jcs.i(PG:143)
E/ExperimentLoader( 3217): 	at hec.a(PG:42)
E/ExperimentLoader( 3217): 	at hee.a(PG:102)
E/ExperimentLoader( 3217): ,	at czr.a(PG:65)
E/ExperimentLoader( 3217): 	at kka.a(PG:108)
E/ExperimentLoader( 3217): 	at czp.a(PG:19176)
E/ExperimentLoader( 3217): 	at czp.a(PG:9081)
E/ExperimentLoader( 3217): 	at czq.run(PG:1686)
,E/ExperimentLoader( 3217): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3217): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3217): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3217): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3217): 	at java.lang.Thread.run(Thread.java:818)
,E/ExperimentLoader( 3217): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3217): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3217): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3217): 	at jdm.a(PG:77)
E/ExperimentLoader( 3217): 	... 15 more
E/ExperimentLoader( 3217): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3217): 	at fal.a(PG:38)
E/ExperimentLoader( 3217): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3217): 	... 17 more
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 1650776, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2140): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2140): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2140): Disconnected process message: 10, size: 0
,V/KeepSync( 3749): Connecting to GoogleApiClient
,I/GLSUser ( 1267): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1267): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1267): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1267): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1267): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1805): Handling authorization failure
,E/ClientConnectionOperation( 1805): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1805): ,	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1805): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1805): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1805): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1805): Caused by: com.google.android.gms.auth.ad: BadAuthentication
,E/ClientConnectionOperation( 1805): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1805): ,	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1805): 	,at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1805): 	... 7 more
,V/KeepSync( 3749): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3749): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3749): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3749): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1267): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1267): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1267): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1267): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1267): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3749): IOException
E/KeepSync( 3749): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3749): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3749): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3749): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3749): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3749): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3749): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3749): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3749): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3749): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3749): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3749): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3749): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3749): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3749): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3749): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3749): 	... 10 more
W/KeepSync( 3749): Sync result 2
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 1795283, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2140): Disconnected process message: 10, size: 0
,I/ProcessStatsService(  823): Prepared write state in 15ms
,I/ProcessStatsService(  823): Prepared write state in 6ms
,I/ProcessStatsService(  823): Pruning old procstats: /data/system/procstats/state-2015-12-17-15-09-46.bin
,D/HeadsetStateMachine( 2140): Disconnected process message: 10, size: 0
,V/KeepSync( 3749): Connecting to GoogleApiClient
,I/GLSUser ( 1267): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1267): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1267): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1267): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1267): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1805): Handling authorization failure
E/ClientConnectionOperation( 1805): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1805): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1805): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1805): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1805): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1805): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1805): 	... 7 more
,V/KeepSync( 3749): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3749): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3749): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3749): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1267): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1267): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1267): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1267): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1267): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3749): IOException
E/KeepSync( 3749): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3749): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3749): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3749): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3749): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3749): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3749): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3749): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3749): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3749): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3749): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3749): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3749): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3749): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3749): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3749): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3749): 	... 10 more
,W/KeepSync( 3749): Sync result 2
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 1826968, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2140): Disconnected process message: 10, size: 0
,I/BooksSync( 3716): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3716): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1267): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1267): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1267): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1267): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1267): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1267): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1267): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1267): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1267): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1267): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3716): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3716): Soft error
E/BooksSync( 3716): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3716): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3716): Sync error
E/BooksSync( 3716): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3716): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3716): Finished books sync
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1866578, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2140): Disconnected process message: 10, size: 0
,TIME-OUT KILL (timeout was 1800000ms)
```
