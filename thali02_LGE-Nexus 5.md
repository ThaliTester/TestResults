#### Test 5563415007e42e9_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
V/GeofencerHelper( 1604): Initializing geofence's system cache.
D/GeofenceStateCache( 1604): Recovered 0 geofences.
D/BluetoothManagerService(  734): Message: 20
D/BluetoothManagerService(  734): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@8a636fa:true
I/GCoreUlr( 1604): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.location.PROVIDERS_CHANGED}]
D/BluetoothAdapter( 1044): 680196344: getState() :  mService = null. Returning STATE_OFF
I/GeofencerStateMachine( 1604): Network location disabled.
W/art     ( 1604): Suspending all threads took: 16.417ms
I/art     ( 1604): Explicit concurrent mark sweep GC freed 30300(2MB) AllocSpace objects, 15(240KB) LOS objects, 40% free, 19MB/33MB, paused 19.423ms total 133.147ms
E/DataBuffer( 1604): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@4712890)
E/DataBuffer( 1604): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@dea5589)
E/DataBuffer( 1604): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3cc598e)
E/DataBuffer( 1604): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@331f95af)
E/DataBuffer( 1604): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@18683dbc)
E/DataBuffer( 1604): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2299c145)
I/GCoreUlr( 1604): DispatchingService.onCreate()
--------- beginning of system
D/WifiService(  734): New client listening to asynchronous messages
D/BluetoothAdapter( 1044): 680196344: getState() :  mService = null. Returning STATE_OFF
I/ActivityManager(  734): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.audio.MediaButtonIntentReceiver: pid=1758 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/Settings( 1604): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Scheduler( 1604): Use legacy PeriodicScheduler
W/InstanceID/Rpc( 1604): Found 10008
I/GCoreUlr( 1604): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.location.PROVIDERS_CHANGED
W/CursorWrapperInner( 1087): Cursor finalized without prior close()
I/Icing   ( 1691): updateResources: need to parse f{com.google.android.gms}
I/GCoreUlr( 1604): WorldUpdater:android.location.PROVIDERS_CHANGED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
I/GCoreUlr( 1604): Unbound from all location providers
I/GCoreUlr( 1604): Place inference reporting - stopped
I/GAv4-SVC( 1604): Google Analytics 8.4.89 is starting up.
I/GAv4    ( 1758): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 1758):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 1758):   adb logcat -s GAv4
I/art     ( 1501): Explicit concurrent mark sweep GC freed 10615(555KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/26MB, paused 574us total 12.485ms
,D/BluetoothAdapter( 1604): 136660517: getState() :  mService = null. Returning STATE_OFF
I/BleScanCompatLib( 1604): Building BLE scanner compat:  'L/M' hardware access layer is not available: BluetoothAdapter.getBluetoothLeScanner() is null.
W/GAv4    ( 1758): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
I/BleScanCompatLib( 1604): BLE 'JB+' software access layer enabled
W/GeofencerStateMachine( 1604): Ignoring removeGeofence because network location is disabled.
W/GAv4    ( 1758): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 1758): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
I/GCoreUlr( 1604): DispatchingService.onDestroy()
I/GCoreUlr( 1604): Stopping handler for UlrDispSvcFast
I/Places  ( 1604): b.c:195: PlacesBleScanner stop()
I/BleScanCompatLib( 1604): Scan : No clients left, canceling alarm.
I/Icing   ( 1691): Internal init done: storage state 0
I/art     (  734): Explicit concurrent mark sweep GC freed 14671(721KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 26MB/40MB, paused 1.181ms total 59.478ms
I/GCoreUlr( 1604): Unbound from all location providers
I/GCoreUlr( 1604): Place inference reporting - stopped
I/Icing   ( 1691): Post-init done
W/HandlerScheduledExecuto( 1401): Task does not implement UiTask. Consider using NamedUiRunnable for Consumers.consumeAsync
D/AndroidRuntime( 1788): 
D/AndroidRuntime( 1788): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 1788): CheckJNI is OFF
D/AndroidRuntime( 1788): Calling main entry com.android.commands.am.Am
I/ActivityManager(  734): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
I/WebViewFactory( 1758): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
D/AndroidRuntime( 1788): Shutting down VM
I/ActivityManager(  734): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=1830 uid=10278 gids={50278, 9997, 3003} abi=armeabi-v7a
I/MicrophoneInputStream( 1401): mic_close gfk@27437ebf
I/LibraryLoader( 1758): Time to load native libraries: 3 ms (timestamps 7433-7436)
I/LibraryLoader( 1758): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 1758): Binding Chromium to main looper Looper (main, tid 1) {7db222a}
I/LibraryLoader( 1758): Expected native library version number "",actual native library version number ""
I/chromium( 1758): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/WebViewFactory( 1830): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/BrowserStartupController( 1758): Initializing chromium process, singleProcess=true
D/audio_hw_primary(  185): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  185): disable_snd_device: snd_device(55: voice-rec-mic)
I/HotwordRecognitionRnr( 1401): Hotword detection finished
I/HotwordRecognitionRnr( 1401): Stopping hotword detection.
W/art     ( 1758): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 1758): ApplicationContext is null in ApplicationStatus
I/LibraryLoader( 1830): Time to load native libraries: 1 ms (timestamps 7492-7493)
I/LibraryLoader( 1830): Expected native library version number "",actual native library version number ""
W/chromium( 1758): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 1758): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 1758): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 1758): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
V/WebViewChromiumFactoryProvider( 1830): Binding Chromium to main looper Looper (main, tid 1) {288af8f8}
I/LibraryLoader( 1830): Expected native library version number "",actual native library version number ""
I/chromium( 1830): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 1830): Initializing chromium process, singleProcess=true
W/art     ( 1830): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 1830): ApplicationContext is null in ApplicationStatus
W/chromium( 1830): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 1830): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 1830): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 1830): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
W/AudioManagerAndroid( 1758): Requires BLUETOOTH permission
I/NSApplication( 1758): Starting up...
,E/WifiStateMachine(  734): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=4.50 rxSuccessRate=4.00 targetRoamBSSID=c0:ff:d4:d3:aa:4a RSSI=-51
,I/wpa_supplicant( 1027): wlan0: CTRL-EVENT-SCAN-STARTED 
,W/AudioManagerAndroid( 1830): Requires BLUETOOTH permission
,W/art     ( 1830): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 1830): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 1830): CordovaWebView is running on device made by: LGE
,W/art     ( 1830): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 1830): Attempt to remove local handle scope entry from IRT, ignoring
,D/WearableService( 1604): callingUid 10008, callindPid: 1604
,D/OpenGLRenderer( 1830): Render dirty regions requested: true
,E/GmsWearableNodeHelper( 1604): GoogleApiClient connection failed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Atlas   ( 1830): Validating map...
D/LocationInitializer( 1691): Restart initialization of location
,W/chromium( 1830): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,E/MDM     ( 1604): [171] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,I/OpenGLRenderer( 1830): Initialized EGL, version 1.4
,D/OpenGLRenderer( 1830): Enabling debug mode 0
,I/ActivityManager(  734): Displayed com.example.hello/.MainActivity: +472ms (total +6s808ms)
,W/BindingManager( 1830): Cannot call determinedVisibility() - never saw a connection for the pid: 1830
,I/chromium( 1830): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,W/IcingInternalCorpora( 1691): getNumBytesRead when not calculated.
,D/JsMessageQueue( 1830): Set native->JS mode to OnlineEventsBridgeMode
,E/AndroidProtocolHandler( 1830): Unable to open asset URL: file:///android_asset/www/jxcore.js
,D/AuthorizationBluetoothService( 1604): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/a       ( 1604): Opening database auth.proximity.permit_store...
,I/art     ( 1604): Explicit concurrent mark sweep GC freed 28285(2MB) AllocSpace objects, 26(416KB) LOS objects, 39% free, 20MB/34MB, paused 9.131ms total 83.292ms
,V/GLSActivity( 1604): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1604): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1604): No location to return for getLastLocation()
W/FusedLocationProvider( 1604): location=null
,D/ConnectivityService(  734): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  734): MasterInitialState.processMessage what=3
V/UserPresentBroadcastReceiver( 1604): Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
,D/TelephonyProvider( 1225): dbh.onOpen: ok, queried table=siminfo
,D/TelephonyProvider( 1225): dbh.onOpen: ok, queried table=carriers
,E/GpsLocationProvider(  734): No APN found to select.
,I/ActivityManager(  734): Start proc com.google.android.apps.fitness for broadcast com.google.android.apps.fitness/.widget.TodayStatusWidgetProvider: pid=1932 uid=10045 gids={50045, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,D/GpsLocationProvider(  734): NTP server returned: 1452527789781 (Mon Jan 11 16:56:29 GMT+01:00 2016) reference: 28361 certainty: 28 system time offset: 454
E/LocSvc_eng(  734): E/int loc_eng_inject_time(loc_eng_data_s_type&, GpsUtcTime, int64_t, int): log_eng state error: instance not initialized
,D/AlarmManagerService(  734): Setting time of day to sec=1452527789
,W/AlarmManagerService(  734): Unable to set rtc to 1452527789: Invalid argument
,I/FitnessApp( 1932): Initializers took 4 milliseconds
,I/ActivityManager(  734): Start proc com.android.musicfx for broadcast com.android.musicfx/.Compatibility$Receiver: pid=1953 uid=10015 gids={50015, 9997, 3003, 3002} abi=armeabi-v7a
,I/UpdateIcingCorporaServi( 1401): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,D/ChimeraCfgMgr( 1691): Reading stored module config
,D/PackageBroadcastService( 1691): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.example.hello
,D/ChimeraCfgMgr( 1691): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1691): Loading module APK com.google.android.play.games
,D/ChimeraCfgMgr( 1691): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1691): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1691): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/AsyncTaskServiceImpl( 1691): Submit a task: k
,W/BaseAppContext( 1691): Using Auth Proxy for data requests.
,E/BaseAppContext( 1691): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,W/BaseAppContext( 1691): Using Auth Proxy for data requests.
,W/BaseAppContext( 1691): Using Auth Proxy for data requests.
,I/art     ( 1691): Explicit concurrent mark sweep GC freed 52629(3MB) AllocSpace objects, 29(464KB) LOS objects, 40% free, 20MB/34MB, paused 783us total 52.902ms
,W/BaseAppContext( 1691): Using Auth Proxy for data requests.
,W/BaseAppContext( 1691): Using Auth Proxy for data requests.
W/BaseAppContext( 1691): Using Auth Proxy for data requests.
,W/BaseAppContext( 1691): Using Auth Proxy for data requests.
,D/ChimeraCfgMgr( 1691): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/k       ( 1691): Processing package: com.example.hello
,I/art     ( 1501): Explicit concurrent mark sweep GC freed 2642(105KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/26MB, paused 666us total 13.076ms
,D/ChimeraCfgMgr( 1691): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/GassUtils( 1691): Found app info for package com.example.hello:18. Hash: 68ddfd019b48f789223df845f1e49bbdc6edef025bd9dbaddc0e41222bbc602e
D/k       ( 1691): Found info for package com.example.hello in db.
,D/GCM     ( 1604): COMPAT: Multi user ser=0 current=0
,I/PeopleDatabaseHelper( 1691): cleanUpNonGplusAccounts done.
,I/ActivityManager(  734): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=1998 uid=10040 gids={50040, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,I/UpdateIcingCorporaServi( 1401): UpdateCorporaTask done [took 899 ms] updated apps [took 899 ms] 
,D/ChimeraCfgMgr( 1691): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1691): Module APK com.google.android.play.games already loaded
,I/art     (  734): Explicit concurrent mark sweep GC freed 13381(642KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 27MB/40MB, paused 780us total 49.140ms
,I/GAv4    ( 1998): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 1998):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 1998):   adb logcat -s GAv4
,W/GAv4    ( 1998): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 1998): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 1998): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/AnalyticsTrackerProxyImpl( 1998): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
,W/ResourcesManager( 1998): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1998): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  734): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=2032 uid=10016 gids={50016, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/JNIHelp ( 1998): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/System  ( 1998): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 1998): Installed default security provider GmsCore_OpenSSL
,V/GLSActivity( 1604): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Icing   ( 1691): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
,D/Icing   ( 1691): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 1691): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
,D/Finsky  ( 2032): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/Icing   ( 1691): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
,D/Finsky  ( 2032): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,I/Icing   ( 1691): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
,W/Settings( 2032): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 2032): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Ads     ( 2032): Skipping gmscore version check
,I/ActivityManager(  734): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=2075 uid=10067 gids={50067, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/Icing   ( 1691): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
,I/art     (  196): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 250us total 9.500ms
,D/Finsky  ( 2032): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 2032): [1] Libraries$2.run: Finished loading 1 libraries.
,I/art     (  196): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 170us total 7.746ms
,D/Finsky  ( 2032): [1] ExternalReferrer.access$200: Package state data is missing for com.example.hello
,I/art     (  196): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 170us total 7.690ms
,I/Icing   ( 1691): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
,W/ResourcesManager( 2075): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/Finsky  ( 2032): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 2032): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,E/WifiStateMachine(  734): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=4.75 rxSuccessRate=4.00 targetRoamBSSID=c0:ff:d4:d3:aa:4a RSSI=-51
E/WifiStateMachine(  734): WifiStateMachine starting scan for "NG7005g"WPA_PSK with 2412,5220
,I/ConfigService( 1604): onDestroy
,I/wpa_supplicant( 1027): wlan0: CTRL-EVENT-SCAN-STARTED 
,E/MDM     ( 1604): [198] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 1691): Restart initialization of location
,D/AuthorizationBluetoothService( 1604): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1604): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/SystemServiceManager(  734): Starting phase 1000
E/PowerHAL(  734): touch_boost: failed to send: No such file or directory
,I/ANDR-PERF-LOCK( 2106): Listener starting
,I/MP-Decision( 2106): MPDecision server starting
,I/MP-Decision( 2106): OPTION ENABLED: Control sleep modes
,I/MP-Decision( 2106): OPTION ENABLED: Adjusting average
I/MP-Decision( 2106): Decision parameters CPU 0: Nw=0.000000, Tw=0, Ns=0.000000, Ts=0
I/MP-Decision( 2106): util_h_and=0, util_h_or=0, util_low=0
I/MP-Decision( 2106): Decision parameters CPU 1: Nw=1.900000, Tw=140, Ns=1.100000, Ts=190
I/MP-Decision( 2106): util_h_and=35, util_h_or=75, util_low=20
I/MP-Decision( 2106): Decision parameters CPU 2: Nw=2.700000, Tw=90, Ns=2.100000, Ts=240
I/MP-Decision( 2106): util_h_and=0, util_h_or=400, util_low=0
I/MP-Decision( 2106): Decision parameters CPU 3: Nw=3.500000, Tw=90, Ns=3.100000, Ts=240
I/MP-Decision( 2106): util_h_and=0, util_h_or=400, util_low=0
I/MP-Decision( 2106): Decision parameters: poll_ms: 9 decision_ms: 50
,I/ActivityManager(  734): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=2122 uid=10060 gids={50060, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/GCoreFlp( 1604): No location to return for getLastLocation()
,W/FusedLocationProvider( 1604): location=null
,I/MusicStore( 2122): Database version: 120
,W/ResourcesManager( 2122): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2122): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 2122): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 2122): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 2122): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@17a349a6: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 2122): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 2122): GMSCore installation verified
,I/ConfigStore( 2122): Config Database version: 1
,I/MediaRouter( 2122): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=11, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 2122): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 2122): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 2122): type=WIFI subType= reason=null isConnected=true
,I/SystemUpdateService( 1691): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1691): onCreate
,D/SystemUpdateService( 1691): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
I/GHttpClientFactory( 2122): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 2122): Using platform SSLCertificateSocketFactory
,I/SystemUpdateService( 1691): active receiver: enabled
,I/SystemUpdateService( 1691): showing system update notification
,I/iu.SyncManager( 1691): SYNC; picasa accounts
,I/ValidateNoPeople(  734): skipping global notification
,V/SystemUpdateService( 1691): retry (wakeup: false) in 3599948 ms
,W/ResourcesManager(  917): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager(  917): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/NetworkLogImpl( 1691): Loaded NetworkSpeedPredictor
,I/iu.Environment( 1691): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,D/SystemUpdateService( 1691): onDestroy
,I/iu.UploadsManager( 1691): num queued entries: 0
I/iu.UploadsManager( 1691): num updated entries: 0
I/iu.SyncManager( 1691): NEXT; no task
,I/ActivityManager(  734): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=2178 uid=10054 gids={50054, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ResourcesManager( 2178): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/art     ( 1501): Explicit concurrent mark sweep GC freed 2934(114KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/26MB, paused 897us total 12.735ms
,I/art     ( 1604): Explicit concurrent mark sweep GC freed 13329(815KB) AllocSpace objects, 11(176KB) LOS objects, 40% free, 20MB/34MB, paused 636us total 39.298ms
,I/Babel_SMS( 2178): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 2178): MmsConfig.loadMmsSettings
I/Babel_SMS( 2178): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=Nexus5, mUaProfUrl=http://gsm.lge.com/html/gsm/Nexus5-M3.xml
I/Babel_SMS( 2178): MmsConfig.loadFromDatabase
,E/Babel_SMS( 2178): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 2178): MmsConfig.loadFromResources
,E/Babel_SMS( 2178): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 2178): MmsConfig.loadMmsSettings: mUserAgent=Nexus5, mUaProfUrl=http://gsm.lge.com/html/gsm/Nexus5-M3.xml
,I/GCM     ( 1604): GCM config loaded
,I/Babel_SMS( 2178): ApnsOta: OTA version -1
,I/Babel   ( 2178): deleted: false for 0
,W/Settings( 2178): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 2178): startup - clean
,I/ActivityManager(  734): Start proc com.google.android.calendar for broadcast com.google.android.calendar/com.android.calendar.widget.CalendarAppWidgetProvider: pid=2233 uid=10031 gids={50031, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 2178): Unrecognized profile 2130706433 for video/avc
,I/VideoCapabilities( 2178): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 2178): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 2178): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 2178): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 2178): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 2178): onServiceConnected
,W/Babel   ( 2178): Attempted to change video mute state without an active call.
,E/SQLiteLog( 2233): (283) recovered 17 frames from WAL file /data/data/com.google.android.calendar/databases/timelydata.db-wal
,I/Babel   ( 2178): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  734): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=2273 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 2273): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/AnalyticsLogBase( 2233): PlayLogger.onLoggerConnected
,I/ActivityManager(  734): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=2292 uid=10076 gids={50076, 9997} abi=armeabi-v7a
,I/CalendarProvider2( 2273): Created com.android.providers.calendar.CalendarAlarmManager@90f885b(com.android.providers.calendar.CalendarProvider2@288af8f8)
,I/art     (  734): Explicit concurrent mark sweep GC freed 15083(783KB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 27MB/40MB, paused 863us total 53.244ms
,I/ActivityManager(  734): Killing 1044:com.android.settings/1000 (adj 15): empty #17
,D/WifiService(  734): Client connection lost with reason: 4
,D/TimeService( 2292): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1452527794315
D/        ( 2292): TimeServiceNative: User Time to be set is 1452527794315
D/QC-time-services( 2292): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 2292): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 2292): Lib:time_genoff_operation: pargs->ts_val = 1452527794315
D/QC-time-services( 2292): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  199): Daemon: Connection accepted:time_genoff
D/QC-time-services(  199): Daemon:Received base = 2, unit = 1, operation = 0,value = 1452527794315
D/QC-time-services(  199): Daemon:genoff_opr: Base = 2, val = 1452527794315, operation = 0
D/QC-time-services(  199): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS4/15/70 21:47:4
D/QC-time-services(  199): Daemon:Value read from RTC seconds = 11656024000
D/QC-time-services(  199): Daemon:new time 1452527794315 
D/QC-time-services(  199): Daemon: delta 1440871770315 genoff 1440871770315 
D/QC-time-services(  199): Daemon:genoff_persistent_update: Writing genoff = 1440871770315 to memory
D/QC-time-services(  199): Daemon:Opening File: /data/system/time/ats_2
D/QC-time-services(  199): Daemon:time_persistent_memory_opr:Genoff write operation 
,W/libprocessgroup(  734): failed to open /acct/uid_1000/pid_1044/cgroup.procs: No such file or directory
,D/QC-time-services(  199): Updating the TOD offset
D/QC-time-services(  199): Daemon:genoff_persistent_update: Writing genoff = 1440871770315 to memory
D/QC-time-services(  199): Daemon:Opening File: /data/system/time/ats_1
D/QC-time-services(  199): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  199): Daemon:Update to modem bit set
D/QC-time-services(  199): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  199): Daemon: Base = 2, Value being sent to MODEM = 1136562994315
,E/QC-time-services( 2292): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,D/QC-time-services(  199): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,D/QC-time-services(  199): Daemon: Time-services: Waiting to acceptconnection
,I/CheckinService( 1691): Checkin interval check for package: unspecified last checkin: 1452516304580 min interval config: 0 actual interval: 11489781
,I/ActivityManager(  734): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver: pid=2318 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
,I/GAv4    ( 2318): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 2318):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 2318):   adb logcat -s GAv4
,W/GAv4    ( 2318): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 2318): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 2318): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/BluetoothManagerService(  734): Auto-enabling Bluetooth.
,D/BluetoothManagerService(  734): Message: 1
D/BluetoothManagerService(  734): MESSAGE_ENABLE: mBluetooth = null
,I/ActivityManager(  734): Killing 1932:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,W/libprocessgroup(  734): failed to open /acct/uid_10045/pid_1932/cgroup.procs: No such file or directory
,I/ActivityManager(  734): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=2344 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,I/RecoverySystem(  734): No recovery log file
,I/ActivityManager(  734): Start proc com.google.android.dialer for broadcast com.google.android.dialer/com.android.dialer.calllog.CallLogReceiver: pid=2367 uid=10010 gids={50010, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 2344): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,I/BootReceiver(  734): Copying /proc/last_kmsg to DropBox (SYSTEM_LAST_KMSG)
,E/SharedPreferencesImpl(  734): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
,I/BootReceiver(  734): Copying audit failures to DropBox
,I/BootReceiver(  734): Copied 314 worth of audits to DropBox
,E/SharedPreferencesImpl(  734): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
I/ActivityManager(  734): Start proc com.android.keychain for service com.android.keychain/.KeyChainService: pid=2394 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,I/BootReceiver(  734): Checking for fsck errors
I/BootReceiver(  734): Copying /data/tombstones/tombstone_00 to DropBox (SYSTEM_TOMBSTONE)
,E/SharedPreferencesImpl(  734): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
,I/BootReceiver(  734): Copying /data/tombstones/tombstone_01 to DropBox (SYSTEM_TOMBSTONE)
E/SharedPreferencesImpl(  734): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
,D/AdapterServiceConfig( 2344): Adding HeadsetService
D/AdapterServiceConfig( 2344): Adding A2dpService
D/AdapterServiceConfig( 2344): Adding HidService
D/AdapterServiceConfig( 2344): Adding HealthService
D/AdapterServiceConfig( 2344): Adding PanService
D/AdapterServiceConfig( 2344): Adding GattService
D/AdapterServiceConfig( 2344): Adding BluetoothMapService
,W/ResourcesManager( 2367): Asset path '/system/framework/com.google.android.dialer.support.jar' does not exist or contains no resources.
,E/ActivityThread( 1691): Failed to find provider info for com.android.contacts.metadata
,D/SyncManager(  734): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 26249, reason: UserStart, SyncResult: databaseError: true stats []
,D/SyncManager(  734): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 64188, reason: UserStart
,D/BluetoothManagerService(  734): Message: 20
D/BluetoothManagerService(  734): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d674fff:true
,D/BluetoothAdapterState( 2344): make
,I/bluedroid( 2344): init
I/BluetoothAdapterState( 2344): Entering OffState
,I/bte_conf( 2344): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bte_conf( 2344): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 2344): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,I/bte_conf( 2344): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
I/bluedroid( 2344): get_profile_interface socket
I/bluedroid( 2344): get_profile_interface map_client
,D/BluetoothManagerService(  734): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService(  734): Message: 40
D/BluetoothManagerService(  734): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
,I/bluedroid( 2344): config_hci_snoop_log
,D/BluetoothManagerService(  734): Calling onBluetoothServiceUp callbacks
,D/BluetoothManagerService(  734): Broadcasting onBluetoothServiceUp() to 6 receivers.
,I/GKI_LINUX( 2344): gki_task_entry task_id=1 [BTIF] starting
,D/BluetoothAdapterProperties( 2344): Address is:34:FC:EF:11:AE:67
D/BluetoothAdapterProperties( 2344): Name is: Nexus 5
,D/BluetoothManagerService(  734): Bluetooth Adapter name changed to Nexus 5
D/BluetoothManagerService(  734): Stored Bluetooth name: Nexus 5
D/BluetoothAdapterState( 2344): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
,D/BluetoothAdapterProperties( 2344): Setting state to 11
I/BluetoothAdapterState( 2344): Bluetooth adapter state changed: 10-> 11
D/BluetoothManagerService(  734): Message: 60
D/BluetoothManagerService(  734): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
,D/BluetoothManagerService(  734): Bluetooth State Change Intent: 10 -> 11
,D/BluetoothBondStateMachine( 2344): make
,I/BluetoothBondStateMachine( 2344): StableState(): Entering Off State
,I/BluetoothAdapterState( 2344): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,D/BluetoothHeadset(  734): Proxy object connected
,D/BluetoothHeadset( 1186): Proxy object connected
,D/HeadsetService( 2344): Received start request. Starting profile...
,D/BluetoothHeadset( 1186): Proxy object connected
,I/BluetoothHeadsetServiceJni( 2344): classInitNative: succeeds
,D/HeadsetStateMachine( 2344): make
,D/HeadsetStateMachine( 2344): max_hf_connections = 1
I/bluedroid( 2344): get_profile_interface handsfree
,D/HeadsetStateMachine( 2344): Enter Disconnected: -2, size: 0
,D/BluetoothAdapterService( 2344): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22d7c1d1
,D/BluetoothA2dp(  734): Proxy object connected
,D/A2dpService( 2344): Received start request. Starting profile...
I/BluetoothAvrcpServiceJni( 2344): classInitNative: succeeds
I/bluedroid( 2344): get_profile_interface avrcp
,E/RemoteController( 2344): Cannot set synchronization mode on an unregistered RemoteController
I/BluetoothA2dpServiceJni( 2344): classInitNative: succeeds
D/A2dpStateMachine( 2344): make
,I/bluedroid( 2344): get_profile_interface a2dp
,I/GKI_LINUX( 2344): gki_task_entry task_id=2 [A2DP-MEDIA] starting
,D/BluetoothAdapterService( 2344): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22d7c1d1
,I/BluetoothHidServiceJni( 2344): classInitNative: succeeds
D/A2dpStateMachine( 2344): Enter Disconnected: -2
,I/art     ( 1501): Explicit concurrent mark sweep GC freed 2582(105KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/26MB, paused 1.063ms total 18.811ms
,I/ActivityManager(  734): Killing 1484:com.google.android.partnersetup/u0a13 (adj 15): empty #17
,D/HidService( 2344): Received start request. Starting profile...
I/bluedroid( 2344): get_profile_interface hidhost
,D/BluetoothAdapterService( 2344): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22d7c1d1
,I/BluetoothHealthServiceJni( 2344): classInitNative: succeeds
,D/HealthService( 2344): Received start request. Starting profile...
I/bluedroid( 2344): get_profile_interface health
D/BluetoothAdapterService( 2344): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22d7c1d1
I/BluetoothPanServiceJni( 2344): classInitNative(L105): succeeds
,D/PanService( 2344): Received start request. Starting profile...
D/BluetoothPanServiceJni( 2344): initializeNative(L110): pan
I/bluedroid( 2344): get_profile_interface pan
,D/BluetoothAdapterService( 2344): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22d7c1d1
I/BtGatt.JNI( 2344): classInitNative(L863): classInitNative: Success!
,D/BtGatt.DebugUtils( 2344): handleDebugAction() action=null
,D/BtGatt.GattService( 2344): Received start request. Starting profile...
D/BtGatt.GattService( 2344): start()
I/bluedroid( 2344): get_profile_interface gatt
D/BtGatt.AdvertiseManager( 2344): advertise manager created
,W/libprocessgroup(  734): failed to open /acct/uid_10013/pid_1484/cgroup.procs: No such file or directory
,D/BluetoothAdapterService( 2344): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22d7c1d1
,V/BluetoothMapService( 2344): BluetoothMapBinder()
,D/BluetoothMapService( 2344): Received start request. Starting profile...
D/BluetoothMapService( 2344): start()
,E/ConnectivityChangeReceiver( 1691): Ignoring connectivity change
,D/BluetoothMapEmailSettingsLoader( 2344): Found 0 applications
D/BluetoothMapEmailAppObserver( 2344): createReceiver()
,D/BluetoothMapEmailAppObserver( 2344): initObservers()
,D/BluetoothMapEmailAppObserver( 2344): getEnabledAccountItems()
D/BluetoothAdapterService( 2344): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22d7c1d1
D/HeadsetStateMachine( 2344): Proxy object connected
,D/HeadsetStateMachine( 2344): Disconnected process message: 10, size: 0
,V/BluetoothMapService( 2344): Handler(): got msg=1
D/HeadsetPhoneState( 2344): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 2344): Disconnected process message: 11, size: 0
D/BluetoothAdapterState( 2344): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 2344): enable
,D/ConnectivityService(  734): listenForNetwork for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  734): handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  734): apparently satisfied.  currentScore=60
,D/ConnectivityManager.CallbackHandler( 1691): CM callback handler got msg 524290
,D/ConnectivityService(  734): Got NetworkFactory Messenger for Telephony
,I/GKI_LINUX( 2344): gki_task_entry task_id=0 [BTU] starting
I/bt-btu  ( 2344): btu_task pending for preload complete event
I/bt_hci_bdroid( 2344): init
,I/bt_vendor( 2344): init
,I/bt_vnd_conf( 2344): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
I/bt_vnd_conf( 2344): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
D/bt_userial( 2344): userial_init
,I/ActivityManager(  734): Killing 1953:com.android.musicfx/u0a15 (adj 15): empty #17
,I/bt_userial_vendor( 2344): userial vendor open: opening /dev/ttyHS99
,W/libprocessgroup(  734): failed to open /acct/uid_10015/pid_1953/cgroup.procs: No such file or directory
,I/bt_userial_vendor( 2344): device fd = 53 open
D/bt_userial( 2344): Entering userial_read_thread()
,D/DcSwitchState( 1225): [DcSwitchState-0] DcSwitchState constructor E
D/DcSwitchState( 1225): [DcSwitchState-0] DcSwitchState constructor X
D/GpsLocationProvider(  734): received SIM realted action: android.intent.action.SIM_STATE_CHANGED
,D/GpsLocationProvider(  734): SIM MCC/MNC is still not available
,D/DctController( 1225): [DctController] DctController(phones): Connect success: 0
,W/ResourcesManager( 1225): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/CalendarProvider2( 2273): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 2273): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/art     ( 1691): Explicit concurrent mark sweep GC freed 43952(2MB) AllocSpace objects, 29(464KB) LOS objects, 39% free, 21MB/36MB, paused 725us total 40.836ms
,W/DriveInitializer( 1691): Awaiting to be initialized
,W/DriveInitializer( 1691): Background init thread started
,I/bt_hwcfg( 2344): bt vendor lib: set UART baud 4000000
,I/art     (  734): Explicit concurrent mark sweep GC freed 22009(1182KB) AllocSpace objects, 25(2MB) LOS objects, 33% free, 27MB/41MB, paused 888us total 55.614ms
,D/BluetoothManagerService(  734): Message: 20
D/BluetoothManagerService(  734): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@19f2c442:true
,D/bt_hwcfg( 2344): Chipset BCM4335C0
D/bt_hwcfg( 2344): Target name = [BCM4335C0]
,I/bt_hwcfg( 2344): Found patchfile: /vendor/firmware//bcm4335c0.hcd
,D/BluetoothManagerService(  734): Message: 30
,D/ConnectivityService(  734): Got NetworkFactory Messenger for WIFI
D/WIFI    (  734): got request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] with score 60
,I/ActivityManager(  734): Start proc com.google.android.onetimeinitializer for broadcast com.google.android.onetimeinitializer/.OneTimeInitializerReceiver: pid=2478 uid=10012 gids={50012, 9997} abi=armeabi-v7a
,V/OneTimeInitializerReceiver( 2478): OneTimeInitializerReceiver.onReceive
,V/OneTimeService( 2478): OneTimeService.onHandleIntent
,I/ActivityManager(  734): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.GooglePartnerSetup: pid=2498 uid=10013 gids={50013, 9997, 3003} abi=armeabi-v7a
,I/art     (  196): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 178us total 10.439ms
,I/art     (  196): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 206us total 7.993ms
,I/art     (  196): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 223us total 7.810ms
,I/ActivityManager(  734): Killing 1261:com.android.printspooler/u0a72 (adj 15): empty #17
,W/libprocessgroup(  734): failed to open /acct/uid_10072/pid_1261/cgroup.procs: No such file or directory
,I/ActivityManager(  734): Killing 1998:com.google.android.apps.docs/u0a40 (adj 15): empty #17
,W/libprocessgroup(  734): failed to open /acct/uid_10040/pid_1998/cgroup.procs: No such file or directory
,D/TelephonyNetworkFactory( 1225): got request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] with score 60
,D/DctController( 1225): [DctController] EVENT_PHONE1_RADIO_OFF.
,D/TelephonyDebugService( 1225): TelephonyDebugService()
,D/WifiService(  734): New client listening to asynchronous messages
,D/BluetoothHeadset( 1225): Proxy object connected
,D/DctController( 1225): [DctController] DataStateReceiver: phoneId= 0
D/DctController( 1225): [DctController] DataStateReceiver: ignore invalid subId=-1
,I/ActivityManager(  734): Start proc com.android.managedprovisioning for broadcast com.android.managedprovisioning/.BootReminder: pid=2536 uid=10014 gids={50014, 9997, 1028, 3003} abi=armeabi-v7a
,D/GpsLocationProvider(  734): received SIM realted action: android.intent.action.SIM_STATE_CHANGED
,D/GpsLocationProvider(  734): SIM MCC/MNC is still not available
,I/bt_hwcfg( 2344): bt vendor lib: set UART baud 115200
,D/bt_hwcfg( 2344): Settlement delay -- 100 ms
I/bt_hwcfg( 2344): Setting fw settlement delay to 100 
,D/GpsLocationProvider(  734): received SIM realted action: android.intent.action.ACTION_SUBINFO_RECORD_UPDATED
I/MmsService( 1225): mReceiver action: android.intent.action.ACTION_SUBINFO_RECORD_UPDATED
I/Telephony( 1225): : SUBINFO_RECORD_UPDATED : 4.
D/GpsLocationProvider(  734): SIM MCC/MNC is still not available
,I/MmsService( 1225): MmsConfigManager.loadInBackground(): mcc/mnc: 0/0
,E/PhoneInterfaceManager( 1225): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,E/MmsService( 1225): MmsConfigManager.load -- empty getActiveSubInfoList
,W/DriveInitializer( 1691): Background init thread ended
,I/Telephony( 1225): PstnIncomingCallNotifier: Registering: Handler (com.android.internal.telephony.gsm.GSMPhone) {7db222a}
,I/RlzPingService( 2498): Setting next ping for 1453132595832
,I/ActivityManager(  734): Killing 1401:com.google.android.googlequicksearchbox:search/u0a22 (adj 15): empty #17
,D/WifiService(  734): Client connection lost with reason: 4
,W/libprocessgroup(  734): failed to open /acct/uid_10022/pid_1401/cgroup.procs: No such file or directory
,I/bt_hwcfg( 2344): bt vendor lib: set UART baud 4000000
I/bt_hwcfg( 2344): Setting local bd addr to 34:FC:EF:11:AE:67
,I/bt_hwcfg( 2344): vendor lib fwcfg completed
I/bt-btu  ( 2344): btu_task received preload complete event
,I/        ( 2344): BTE_InitTraceLevels -- TRC_HCI
I/        ( 2344): BTE_InitTraceLevels -- TRC_L2CAP
,I/        ( 2344): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 2344): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 2344): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 2344): BTE_InitTraceLevels -- TRC_A2D
I/        ( 2344): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 2344): BTE_InitTraceLevels -- TRC_BTM
I/        ( 2344): BTE_InitTraceLevels -- TRC_GAP
I/        ( 2344): BTE_InitTraceLevels -- TRC_PAN
I/        ( 2344): BTE_InitTraceLevels -- TRC_SDP
I/        ( 2344): BTE_InitTraceLevels -- TRC_GATT
I/        ( 2344): BTE_InitTraceLevels -- TRC_SMP
I/        ( 2344): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 2344): BTE_InitTraceLevels -- TRC_BTIF
,I/ActivityManager(  734): Killing 2032:com.android.vending/u0a16 (adj 15): empty #17
,W/libprocessgroup(  734): failed to open /acct/uid_10016/pid_2032/cgroup.procs: No such file or directory
,E/SQLiteLog(  899): (283) recovered 45 frames from WAL file /data/data/com.android.providers.media/databases/internal.db-wal
,I/ActivityManager(  734): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.StartUpReceiver: pid=2563 uid=10022 gids={50022, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,D/MtpService(  899): updating state; isCurrentUser=true, mMtpLocked=false
,I/ActivityManager(  734): Killing 2122:com.google.android.music:main/u0a60 (adj 15): empty #17
,E/bt-btm  ( 2344): BTM_SecRegister:p_cb_info->p_le_callback == 0xa3fdf9d5 
,E/bt-btm  ( 2344): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa3fdf9d5 
,W/libprocessgroup(  734): failed to open /acct/uid_10060/pid_2122/cgroup.procs: No such file or directory
,W/MediaScanner(  899): Error opening directory '/oem/media/', skipping: No such file or directory.
,I/iu.UploadsManager( 1691): #reloadSettings(); account: -1; IU: disabled; IS: disabled; IS account: -1; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: STANDARD; maxMobile: 157286400
,I/iu.UploadsManager( 1691): End new media; added: 0, uploading: 0, time: 48 ms
,V/MediaScanner(  899): pruneDeadThumbnailFiles... android.database.sqlite.SQLiteCursor@2e065779
,V/MediaScanner(  899): /pruneDeadThumbnailFiles... android.database.sqlite.SQLiteCursor@2e065779
,E/bt-btif ( 2344): Calling BTA_HhEnable
E/bt-btif ( 2344): btif_storage_get_adapter_property service_mask:0x2140040
,D/BluetoothAdapterProperties( 2344): Address is:34:FC:EF:11:AE:67
D/BluetoothAdapterProperties( 2344): Name is: Nexus 5
,D/BluetoothManagerService(  734): Bluetooth Adapter name changed to Nexus 5
D/BluetoothManagerService(  734): Stored Bluetooth name: Nexus 5
,D/BluetoothAdapterProperties( 2344): Scan Mode:20
D/BluetoothAdapterProperties( 2344): Discoverable Timeout:120
,D/bte_conf( 2344): Device ID record 1 : primary
D/bte_conf( 2344):   vendorId            = 000f
D/bte_conf( 2344):   vendorIdSource      = 0001
D/bte_conf( 2344):   product             = 1200
D/bte_conf( 2344):   version             = 1436
D/bte_conf( 2344):   clientExecutableURL = 
D/bte_conf( 2344):   serviceDescription  = 
D/bte_conf( 2344):   documentationURL    = 
D/bte_conf( 2344): bte_load_did_conf no section named DID2.
,D/BluetoothAdapterState( 2344): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothPanServiceJni( 2344): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,D/BluetoothAdapterProperties( 2344): ScanMode =  20
D/BluetoothAdapterProperties( 2344): State =  11
D/BluetoothAdapterProperties( 2344): Setting state to 12
I/BluetoothAdapterState( 2344): Bluetooth adapter state changed: 11-> 12
D/BluetoothManagerService(  734): Message: 60
D/BluetoothManagerService(  734): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
I/BluetoothAdapterState( 2344): Entering On State
D/BluetoothManagerService(  734): Broadcasting onBluetoothStateChange(true) to 5 receivers.
D/BluetoothHeadset( 1186): onBluetoothStateChange: up=true
D/BluetoothAdapterProperties( 2344): Scan Mode:21
D/BluetoothAdapterProperties( 2344): Discoverable Timeout:120
D/BluetoothHeadset( 1225): onBluetoothStateChange: up=true
D/BluetoothHeadset(  734): onBluetoothStateChange: up=true
D/BluetoothA2dp(  734): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1186): onBluetoothStateChange: up=true
,D/BluetoothManagerService(  734): Bluetooth State Change Intent: 11 -> 12
,D/BluetoothManagerService(  734): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/BluetoothManagerService(  734): Message: 40
D/BluetoothManagerService(  734): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,D/BluetoothMapService( 2344): onReceive
D/BluetoothMapService( 2344): STATE_ON
V/BluetoothMapService( 2344): Handler(): got msg=1
,D/BluetoothMapMasInstance( 2344): Map Service startRfcommSocketListener
,D/BluetoothMapMasInstance( 2344): MAS initSocket()
I/Telecom ( 1186): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,D/BluetoothMapMasInstance( 2344):   masId = 00
D/BluetoothMapMasInstance( 2344):   msgTypes = 0e
D/BluetoothMapMasInstance( 2344):   masName = SMS/MMS
D/BluetoothMapMasInstance( 2344):   SDP string = 000eSMS/MMS
,D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 2344): getBluetoothService() called with no BluetoothManagerCallback
,D/HeadsetStateMachine( 2344): Disconnected process message: 9, size: 0
V/BluetoothMapMasInstance( 2344): Succeed to create listening socket 
,D/BluetoothMapMasInstance( 2344): Accepting socket connection...
D/HeadsetStateMachine( 2344): mNumActive: 0 mNumHeld: 0 mCallState: 6
D/HeadsetStateMachine( 2344): mNumber:  mType: 128
D/HeadsetStateMachine( 2344): terminateScoUsingVirtualVoiceCall: Received
E/HeadsetStateMachine( 2344): terminateScoUsingVirtualVoiceCall:No present call to terminate
,I/ContactAccountLoggerTas( 2563): canRun() : Opted Out
,W/bt-smp  ( 2344): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 2344): Plain text(LSB ~ MSB) = 53 99 71 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2344): Encrypted text(LSB ~ MSB) = 49 ca 4c 59 70 12 94 af f2 ca ff b9 b3 5e 86 f4 
W/bt-btm  ( 2344): Stopping oneshot timer
,E/bt_h4   ( 2344): vendor lib postload completed
,W/bt-smp  ( 2344): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 2344): Plain text(LSB ~ MSB) = 25 3b 6b 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2344): Encrypted text(LSB ~ MSB) = fc e5 b7 e6 7f 89 f5 23 73 24 70 cd c6 72 96 cc 
W/bt-btm  ( 2344): Stopping oneshot timer
,W/bt-smp  ( 2344): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 2344): Plain text(LSB ~ MSB) = 46 b3 41 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2344): Encrypted text(LSB ~ MSB) = f9 c2 92 52 0b 02 82 20 24 05 c9 52 de 4a d5 21 
W/bt-btm  ( 2344): Stopping oneshot timer
,W/bt-smp  ( 2344): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 2344): Plain text(LSB ~ MSB) = 6e 95 54 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2344): Encrypted text(LSB ~ MSB) = dc 5b 3b ff 41 1d c9 02 fb 21 b1 62 7a 4b e5 99 
W/bt-btm  ( 2344): Stopping oneshot timer
,W/bt-smp  ( 2344): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 2344): Plain text(LSB ~ MSB) = 60 43 4b 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2344): Encrypted text(LSB ~ MSB) = c2 85 0e 6a 84 a8 71 60 74 79 ad f2 63 82 2c a6 
W/bt-btm  ( 2344): Stopping oneshot timer
,W/bt-smp  ( 2344): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 2344): Plain text(LSB ~ MSB) = a0 61 78 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2344): Encrypted text(LSB ~ MSB) = 94 cf a5 3f 56 cf 5f 94 c5 d2 90 c9 d9 7d 95 df 
W/bt-btm  ( 2344): Stopping oneshot timer
,W/bt-smp  ( 2344): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 2344): Plain text(LSB ~ MSB) = ea ff 5d 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2344): Encrypted text(LSB ~ MSB) = 47 0e 17 65 51 b3 f9 3f 19 e5 47 fd e2 33 08 81 
W/bt-btm  ( 2344): Stopping oneshot timer
,W/GAV2    ( 2563): Thread[Background Non-Blocking-1,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/GAV2    ( 2563): Thread[Background Non-Blocking-1,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,I/ContactAccountLoggerTas( 2563): canRun() : Opted Out
,D/WifiService(  734): New client listening to asynchronous messages
,I/MediaRouter( 2563): Found default route: MediaRouter.RouteInfo{ uniqueId=android/mo:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=11, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,I/FavoriteContactNamesSup( 2563): get() : Execute runnable (UI thread)
,I/ContactLabelSupplier( 2563): get() : Execute runnable (UI thread)
,I/ContactLabelSupplier( 2563): get() : OptedIn = false
,I/ActivityManager(  734): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=2605 uid=10036 gids={50036, 9997, 3003} abi=armeabi-v7a
,I/art     (  734): Explicit concurrent mark sweep GC freed 13387(681KB) AllocSpace objects, 3(52KB) LOS objects, 33% free, 27MB/41MB, paused 728us total 46.868ms
,E/UpdateRequestReceiver( 2605): ignoring update request
,E/UpdateRequestReceiver( 2605): ignoring update request
,E/UpdateRequestReceiver( 2605): ignoring update request
,E/UpdateRequestReceiver( 2605): ignoring update request
,E/UpdateRequestReceiver( 2605): ignoring update request
,E/UpdateRequestReceiver( 2605): ignoring update request
,W/BroadcastQueue(  734): Permission Denial: receiving Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 (has extras) } to com.google.android.gallery3d/com.android.camera.DisableCameraReceiver requires android.permission.RECEIVE_BOOT_COMPLETED due to sender null (uid 1000)
,I/GoogleHttpClient( 1501): GMS http client unavailable, use old client
,I/ActivityManager(  734): Start proc com.lge.SprintHiddenMenu for broadcast com.lge.SprintHiddenMenu/.sprintspec.data.UaproflieSettingReceiver: pid=2643 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,W/ResourcesManager( 2643): Asset path '/system/framework/serviceitems.jar' does not exist or contains no resources.
W/ResourcesManager( 2643): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,I/ActivityManager(  734): Start proc com.qualcomm.qcrilmsgtunnel for broadcast com.qualcomm.qcrilmsgtunnel/.QcrilMsgTunnelAutoboot: pid=2660 uid=1001 gids={41001, 9997, 3003, 2001, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,I/ActivityManager(  734): Killing 2178:com.google.android.talk/u0a54 (adj 15): empty #17
,W/libprocessgroup(  734): failed to open /acct/uid_10054/pid_2178/cgroup.procs: No such file or directory
,D/QcrilMsgTunnelAutoboot( 2660): ComponentInfo{com.qualcomm.qcrilmsgtunnel/com.qualcomm.qcrilmsgtunnel.QcrilMsgTunnelService} started successfully
,D/QcrilMsgTunnelService( 2660): onCreate method
D/QcrilMsgTunnelIfaceManager( 2660): : Instantiated
,V/QcrilMsgTunnelSocket( 2660): Starting QcRil Sender & Receiver threads
,I/QcrilMsgTunnelSocket( 2660): Connected to 'qmux_radio/rild_oem0' socket
,D/QcrilMsgTunnelIfaceManager( 2660):  Registered for UNSOL OEM HOOK Responses to deliver external apps
,D/FileApkUtils( 1691): Spent 21ms computing apk sha1.
,D/FileApkUtils( 1691): Module already staged or being staged:chimera-modules/MapsModule.apk
,I/art     ( 1691): DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@data@com.google.android.gms@app_chimera@chimera-module-root@module-71c764a6f3cb92bdc5525a965b589e7c5ed304f3@MapsModule.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-71c764a6f3cb92bdc5525a965b589e7c5ed304f3/MapsModule.apk': Failed to open oat filename for reading: No such file or directory
,D/DexOptUtils( 1691): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-71c764a6f3cb92bdc5525a965b589e7c5ed304f3/MapsModule.apk is already optimized. Bailing.
,W/InstanceID/Rpc( 1691): Found 10008
,D/FileApkUtils( 1691): Keeping up-to-date module: module-71c764a6f3cb92bdc5525a965b589e7c5ed304f3
,D/GmsModuleFndr( 1691): Beginning GMS chimera module scan
,D/GmsModuleFndr( 1691): Module pkg com.google.android.apps.kids.kidsetup not installed, skipping
,D/ChimeraCfgMgr( 1691): Beginning module configuration check
,D/ChimeraCfgMgr( 1691): Module APKs unchanged, check complete
,D/GCM     ( 1691): COMPAT: Multi user ser=0 current=0
,D/GCM     ( 1604): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
,I/GCoreUlr( 1691): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
,I/GCoreUlr( 1604): DispatchingService.onCreate()
,I/CheckinService( 1691): Checkin interval check for package: unspecified last checkin: 1452516304580 min interval config: 0 actual interval: 11492619
,D/SystemUpdateService( 1691): onCreate
,D/SystemUpdateService( 1691): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/CheckinService( 1691): Disabling old GoogleServicesFramework version
,D/ChimeraCfgMgr( 1691): Loading module com.google.android.gms.gass from APK com.google.android.gms
I/SystemUpdateService( 1691): active receiver: enabled
,I/SystemUpdateService( 1691): showing system update notification
D/BootCompletedReceiver( 1691): Will schedule periodic tasks:android.intent.action.BOOT_COMPLETED.
,D/BootCompletedReceiver( 1691): Got an BootCompleted event.
,D/BootCompletedReceiver( 1691): Will NOT schedule AdAttestation signal task because it's disabled.
,V/AuthZen ( 1691): Handling intent: android.intent.action.BOOT_COMPLETED
,I/GCoreUlr( 1604): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
,V/GLSActivity( 1604): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1604): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/AuthZenEventHandler( 1691): Handling event: android.intent.action.BOOT_COMPLETED
,I/art     ( 1501): Explicit concurrent mark sweep GC freed 3737(162KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/26MB, paused 1.136ms total 16.332ms
,W/BaseAppContext( 1691): Using Auth Proxy for data requests.
,I/ValidateNoPeople(  734): skipping global notification
,V/SystemUpdateService( 1691): retry (wakeup: false) in 3599926 ms
,I/AuthZen ( 1691): Fetching signing key...
,D/SystemUpdateService( 1691): onDestroy
,I/CheckinService( 1691): Checking schedule, now: 1452527797319 next: 1452558471542
,I/CheckinService( 1691): active receiver: disabled
,I/AuthZen ( 1691): Signing key fetched successfully!
,W/BaseAppContext( 1691): Using Auth Proxy for data requests.
,D/a       ( 1691): Opening database auth.proximity.permit_store...
,D/AuthZenTransactionCache( 1691): Initialized cache in: /data/data/com.google.android.gms/files
,D/AuthZenTransactionCache( 1691): Clearing transaction cache
,W/GCoreFlp( 1604): No location to return for getLastLocation()
W/FusedLocationProvider( 1604): location=null
,W/Auth    ( 1604): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
,V/GLSActivity( 1604): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1604): No location to return for getLastLocation()
W/FusedLocationProvider( 1604): location=null
,D/PersistentNotificationBroadcastReceiver( 1604): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,I/GCoreUlr( 1604): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/GCoreUlr( 1604): Unbound from all location providers
I/GCoreUlr( 1604): Place inference reporting - stopped
,I/GCoreUlr( 1604): DispatchingService.onDestroy()
I/GCoreUlr( 1604): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 1604): Unbound from all location providers
I/GCoreUlr( 1604): Place inference reporting - stopped
,I/ActivityManager(  734): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=2714 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 2714): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2714): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 2714): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/System  ( 2714): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 2714): Installed default security provider GmsCore_OpenSSL
,I/dex2oat ( 2754): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads1344490774.jar --oat-fd=25 --oat-location=/data/data/com.google.android.youtube/cache/ads1344490774.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,E/YouTube MDX( 2714): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,I/dex2oat ( 2754): dex2oat took 48.546ms (threads: 4)
,W/InstanceID/Rpc( 2714): Found 10008
,I/ActivityManager(  734): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=2811 uid=10054 gids={50054, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  734): Killing 2292:com.qualcomm.timeservice/u0a76 (adj 15): empty #17
,W/ResourcesManager( 2811): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  734): Killing 1758:com.google.android.apps.magazines/u0a61 (adj 15): empty #18
,W/libprocessgroup(  734): failed to open /acct/uid_10076/pid_2292/cgroup.procs: No such file or directory
,W/libprocessgroup(  734): failed to open /acct/uid_10061/pid_1758/cgroup.procs: No such file or directory
,I/Babel_SMS( 2811): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 2811): MmsConfig.loadMmsSettings
,I/Babel_SMS( 2811): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=Nexus5, mUaProfUrl=http://gsm.lge.com/html/gsm/Nexus5-M3.xml
I/Babel_SMS( 2811): MmsConfig.loadFromDatabase
,E/Babel_SMS( 2811): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 2811): MmsConfig.loadFromResources
,E/Babel_SMS( 2811): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 2811): MmsConfig.loadMmsSettings: mUserAgent=Nexus5, mUaProfUrl=http://gsm.lge.com/html/gsm/Nexus5-M3.xml
,I/Babel_SMS( 2811): ApnsOta: OTA version -1
,W/Settings( 2811): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 2811): startup - clean
,I/Babel   ( 2811): deleted: false for 0
,V/Babel   ( 2811): babel boot account: thalitester@gmail.com
,W/VideoCapabilities( 2811): Unrecognized profile 2130706433 for video/avc
,I/VideoCapabilities( 2811): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 2811): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 2811): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 2811): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 2811): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 2811): onServiceConnected
,W/Babel   ( 2811): Attempted to change video mute state without an active call.
,I/ActivityManager(  734): Start proc com.google.android.apps.fitness for broadcast com.google.android.apps.fitness/.FitnessBootReceiver: pid=2864 uid=10045 gids={50045, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,E/SQLiteLog( 2811): (284) automatic index on conversation_participants_view(conversation_id)
,I/FitnessApp( 2864): Initializers took 0 milliseconds
,I/art     (  734): Explicit concurrent mark sweep GC freed 21427(1008KB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 27MB/41MB, paused 737us total 49.013ms
,W/VideoCapabilities( 2811): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 2811): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 2811): Unrecognized profile 2130706433 for video/avc
,E/SQLiteLog( 2811): (284) automatic index on conversation_participants_view(conversation_id)
,E/SQLiteLog( 2811): (284) automatic index on conversation_participants_view(conversation_id)
,W/ContextImpl( 2233): Implicit intents with startService are not safe: Intent { act=com.google.android.gms.analytics.service.START (has extras) } android.content.ContextWrapper.bindService:538 com.google.analytics.tracking.android.AnalyticsGmsCoreClient.connect:82 com.google.analytics.tracking.android.GAServiceProxy.connectToService:279 
,I/ActivityManager(  734): Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=2885 uid=10070 gids={50070, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  734): Killing 2394:com.android.keychain/1000 (adj 15): empty #17
,W/libprocessgroup(  734): failed to open /acct/uid_1000/pid_2394/cgroup.procs: No such file or directory
,I/GAv4-SVC( 1691): Google Analytics 8.4.89 is starting up.
I/GAV2    ( 2233): Thread[GAThread,5,main]: No campaign data found.
,I/art     ( 1691): Explicit concurrent mark sweep GC freed 30429(2MB) AllocSpace objects, 35(560KB) LOS objects, 25% free, 22MB/30MB, paused 966us total 93.752ms
,W/SQLiteConnectionPool( 1691): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/Gmail   ( 2885): getAccountsCursor
,D/ActivityThread( 2885): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,V/GLSActivity( 1604): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  734): Start proc com.google.android.gm.exchange for service com.google.android.gm.exchange/com.android.exchange.service.EasService: pid=2918 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/GAV2    ( 2885): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager(  734): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,I/Gmail   ( 2885): Observing account changes for notifications
,I/Exchange( 2918): EasService.onCreate
,I/Gmail   ( 2885): getAccountsCursor
,I/ActivityManager(  734): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=2949 uid=10016 gids={50016, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  196): Explicit concurrent mark sweep GC freed 704(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 185us total 8.822ms
,I/art     (  196): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 166us total 7.527ms
,I/art     (  196): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 165us total 7.565ms
,I/Exchange( 2918): RestartPingTask
,V/GLSActivity( 1604): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1604): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SQLiteLog( 2885): (283) recovered 45 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,I/Exchange( 2918): RestartPingsTask did not start any pings.
,I/Exchange( 2918): PSS stopIfIdle
I/Exchange( 2918): PSS has no active accounts; stopping service.
,I/Exchange( 2918): onDestroy
I/ActivityManager(  734): Killing 2367:com.google.android.dialer/u0a10 (adj 15): empty #17
,W/libprocessgroup(  734): failed to open /acct/uid_10010/pid_2367/cgroup.procs: No such file or directory
,I/Gmail   ( 2885): notifyAccountChanged
,I/Gmail   ( 2885): getAccountsCursor
,V/GLSActivity( 1604): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 2885): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 2885): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 2885): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 2885): calculateUnknownSyncRationalesAndPurgeInBackground: running
,D/Finsky  ( 2949): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/Gmail   ( 2885): getAccountsCursor
,V/GLSActivity( 1604): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2949): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 2949): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 2949): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/ActivityManager(  734): Killing 2273:com.android.providers.calendar/u0a2 (adj 15): empty #17
,D/Volley  ( 2949): [281] DiskBasedCache.clear: Cache cleared.
,D/Volley  ( 2949): [288] DiskBasedCache.clear: Cache cleared.
,D/Ads     ( 2949): Skipping gmscore version check
,I/ActivityManager(  734): Killing 2075:com.google.android.apps.plus/u0a67 (adj 15): empty #18
,I/SystemBroadcastReceiver( 1087): Boot has been completed
I/SystemBroadcastReceiver( 1087): toggleAppIcon() : FLAG_SYSTEM = true
W/libprocessgroup(  734): failed to open /acct/uid_10002/pid_2273/cgroup.procs: No such file or directory
,W/libprocessgroup(  734): failed to open /acct/uid_10067/pid_2075/cgroup.procs: No such file or directory
,D/Finsky  ( 2949): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 2949): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 2949): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 2949): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  734): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=3017 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/UserPresentBroadcastReceiver( 1604): Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
,I/ActivityManager(  734): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=3035 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,W/ResourcesManager( 3017): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/CalendarProvider2( 3017): Created com.android.providers.calendar.CalendarAlarmManager@90f885b(com.android.providers.calendar.CalendarProvider2@288af8f8)
,I/ActivityManager(  734): Killing 2478:com.google.android.onetimeinitializer/u0a12 (adj 15): empty #17
,W/libprocessgroup(  734): failed to open /acct/uid_10012/pid_2478/cgroup.procs: No such file or directory
,D/WifiService(  734): New client listening to asynchronous messages
,D/AuthorizationBluetoothService( 1604): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/ActivityManager(  734): Start proc com.android.cellbroadcastreceiver for broadcast com.android.cellbroadcastreceiver/.CellBroadcastReceiver: pid=3057 uid=10003 gids={50003, 9997} abi=armeabi-v7a
,D/CellBroadcastReceiver( 3057): onReceive Intent { act=android.intent.action.SERVICE_STATE flg=0x10 cmp=com.android.cellbroadcastreceiver/.CellBroadcastReceiver (has extras) }
D/CellBroadcastReceiver( 3057): Intent ACTION_SERVICE_STATE_CHANGED
,D/CellBroadcastReceiver( 3057): Service state changed! 3 Full: 3 3 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=false Current state=-1
,I/ActivityManager(  734): Killing 1567:com.android.defcontainer/u0a5 (adj 15): empty #17
,W/libprocessgroup(  734): failed to open /acct/uid_10005/pid_1567/cgroup.procs: No such file or directory
,D/SIP     ( 1225): [SipSharedPreferences] isReceivingCallsEnabled, option not set; use default value, exception: android.provider.Settings$SettingNotFoundException: sip_receive_calls
,I/ActivityManager(  734): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=3077 uid=10060 gids={50060, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/MusicStore( 3077): Database version: 120
,I/art     (  734): Explicit concurrent mark sweep GC freed 7982(398KB) AllocSpace objects, 2(36KB) LOS objects, 33% free, 27MB/41MB, paused 1.029ms total 99.361ms
,W/ResourcesManager( 3077): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3077): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 3077): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 3077): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 3077): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@17a349a6: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3077): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 3077): GMSCore installation verified
,I/ConfigStore( 3077): Config Database version: 1
,I/MediaRouter( 3077): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=11, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,I/NetworkMonitor( 3077): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 3077): type=WIFI subType= reason=null isConnected=true
,I/GHttpClientFactory( 3077): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 3077): Using platform SSLCertificateSocketFactory
,W/ContextImpl( 3035): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/BluetoothManagerService(  734): Message: 20
D/BluetoothManagerService(  734): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a2c3b8f:true
,D/LocalBluetoothProfileManager( 3035): Adding local A2DP profile
,D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 2344): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothManagerService(  734): Message: 30
,D/LocalBluetoothProfileManager( 3035): Adding local HEADSET profile
,D/BluetoothManagerService(  734): Message: 30
,D/BluetoothManagerService(  734): Message: 30
,D/BluetoothManagerService(  734): Message: 30
,D/LocalBluetoothProfileManager( 3035): Adding local MAP profile
D/BluetoothMap( 3035): Create BluetoothMap proxy object
,D/BluetoothManagerService(  734): Message: 30
,D/BluetoothManagerService(  734): Message: 30
,D/LocalBluetoothProfileManager( 3035): LocalBluetoothProfileManager construction complete
,D/DockEventReceiver( 3035): finishStartingService: stopping service
,D/BluetoothA2dp( 3035): Proxy object connected
D/A2dpProfile( 3035): Bluetooth service connected
,D/BluetoothHeadset( 3035): Proxy object connected
D/HeadsetProfile( 3035): Bluetooth service connected
,D/BluetoothInputDevice( 3035): Proxy object connected
D/HidProfile( 3035): Bluetooth service connected
,D/BluetoothPan( 3035): BluetoothPAN Proxy object connected
,D/PanProfile( 3035): Bluetooth service connected
,D/AuthorizationBluetoothService( 1604): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/BluetoothMap( 3035): Proxy object connected
,D/MapProfile( 3035): Bluetooth service connected
D/BluetoothMap( 3035): getConnectedDevices()
,V/BluetoothMapService( 2344): getConnectedDevices()
,D/BluetoothPbap( 3035): Proxy object connected
D/PbapServerProfile( 3035): Bluetooth service connected
,D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 2344): getBluetoothService() called with no BluetoothManagerCallback
,I/BtOppRfcommListener( 2344): Accept thread started.
,W/GCoreFlp( 1604): No location to return for getLastLocation()
W/FusedLocationProvider( 1604): location=null
,I/art     ( 1501): Explicit concurrent mark sweep GC freed 3185(122KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/26MB, paused 538us total 12.145ms
,D/GCM     ( 1604): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/MediaStoreImporter( 3077): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,I/ActivityManager(  734): Killing 2536:com.android.managedprovisioning/u0a14 (adj 15): empty #17
,I/GAV2    ( 2563): Thread[GAThread,5,main]: No campaign data found.
,W/libprocessgroup(  734): failed to open /acct/uid_10014/pid_2536/cgroup.procs: No such file or directory
,I/CalendarProvider2( 3017): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 3017): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  734): Killing 1423:android.process.acore/u0a4 (adj 15): empty #17
,W/libprocessgroup(  734): failed to open /acct/uid_10004/pid_1423/cgroup.procs: No such file or directory
,E/SQLiteLog( 3017): (284) automatic index on view_events(_id)
,W/ResourcesManager( 2811): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 2811): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 2811): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/System  ( 2811): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 2811): Installed default security provider GmsCore_OpenSSL
,I/GAV2    ( 2885): Thread[GAThread,5,main]: No campaign data found.
,D/WearableService( 1604): callingUid 10008, callindPid: 1604
,E/GmsUtils( 3077): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 3077): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/art     (  734): Explicit concurrent mark sweep GC freed 11136(531KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 27MB/41MB, paused 728us total 52.122ms
,I/MusicLeanback( 3077): Conditions not met for autocaching. okToAttempt=false
,I/MusicLeanback( 3077): Stop autocaching.
,I/iu.UploadsManager( 1691): End new media; added: 0, uploading: 0, time: 92 ms
,W/SQLiteConnectionPool( 1501): A SQLiteConnection object for database '/data/user/0/com.google.android.gsf/databases/gservices.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,W/SQLiteConnectionPool( 1501): A SQLiteConnection object for database '/data/user/0/com.google.android.gsf/databases/gservices.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,E/WifiStateMachine(  734): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=3.27 rxSuccessRate=4.16 targetRoamBSSID=c0:ff:d4:d3:aa:4a RSSI=-50
E/WifiStateMachine(  734): WifiStateMachine starting scan for "NG7005g"WPA_PSK with 2412,5220
,I/wpa_supplicant( 1027): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/Finsky  ( 2949): [295] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2949): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/InputReader(  734): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager(  734): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=3226 uid=10004 gids={50004, 9997} abi=armeabi-v7a
,D/BackupManagerService(  734): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  734): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  734): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  734): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  734): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@3b049a15
,W/ResourcesManager( 2811): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2811): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/GCoreNlp( 1604): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Launcher( 1270): Deferring update until onResume
,W/ResourcesManager( 1270): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 2563): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
W/Launcher( 1270): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@22d7c1d1 new=com.google.android.velvet.VelvetApplication@22d7c1d1
,I/art     ( 1604): Explicit concurrent mark sweep GC freed 33746(2MB) AllocSpace objects, 34(544KB) LOS objects, 39% free, 21MB/35MB, paused 714us total 36.991ms
,D/PackageBroadcastService( 1691): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,W/ResourcesManager( 1270): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/Launcher( 1270): Deferring update until onResume
I/ContactLocale( 3226): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  734): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=3259 uid=10067 gids={50067, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/PackageBroadcastService( 1691): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 1691): updateResources: need to parse f{com.google.android.gms}
,W/ResourcesManager( 3259): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  734): Delay finish: com.google.android.apps.plus/.service.PhotosAppTransitionMonitor
,I/ActivityManager(  734): Resuming delayed broadcast
,I/ActivityManager(  734): Killing 2605:com.google.android.configupdater/u0a36 (adj 15): empty #17
,I/UpdateIcingCorporaServi( 2563): UpdateCorporaTask done [took 329 ms] updated apps [took 329 ms] 
,W/libprocessgroup(  734): failed to open /acct/uid_10036/pid_2605/cgroup.procs: No such file or directory
,I/Icing   ( 1691): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
,I/Icing   ( 1691): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
,I/ActivityManager(  734): Waited long enough for: ServiceRecord{3f1cdec6 u0 com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService}
,I/ActivityManager(  734): Waited long enough for: ServiceRecord{158e705a u0 com.google.android.calendar/com.android.calendar.alerts.InitAlarmsService}
,I/ActivityManager(  734): Waited long enough for: ServiceRecord{3cb33826 u0 com.qualcomm.qcrilmsgtunnel/.QcrilMsgTunnelService}
,I/ActivityManager(  734): Killing 1367:com.google.android.keep/u0a71 (adj 15): empty #17
,W/libprocessgroup(  734): failed to open /acct/uid_10071/pid_1367/cgroup.procs: No such file or directory
,I/CheckinService( 1691): Done disabling old GoogleServicesFramework version
,I/PowerManagerService(  734): Going to sleep due to screen timeout (uid 1000)...
I/PowerManagerService(  734): Sleeping (uid 1000)...
,I/Adreno-EGL(  734): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/PermissionCache(  175): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (205 us)
,D/audio_hw_primary(  185): adev_set_parameters: enter: screen_state=on
E/audio_a2dp_hw(  185): adev_set_parameters: ERROR: set param called even when stream out is null
,E/native  (  734): do suspend false
,D/SurfaceFlinger(  175): shader cache generated - 24 shaders in 148.438339 ms
,I/Keyboard.Facilitator( 1087): onFinishInput()
,D/audio_hw_primary(  185): adev_set_parameters: enter: screen_state=off
E/audio_a2dp_hw(  185): adev_set_parameters: ERROR: set param called even when stream out is null
,E/native  (  734): do suspend true
,E/Sensors (  192): sns_acm_mr.c(432):Transport error -45
,I/DisplayManagerService(  734): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 442.451 x 443.345 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,V/ActivityManager(  734): Display changed displayId=0
,D/SurfaceFlinger(  175): Set power mode=0, type=0 flinger=0xb6a62000
D/qdhwcomposer(  175): hwc_blank: Blanking display: 0
,D/qdhwcomposer(  175): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  734): Excessive delay in setPowerMode(): 297ms
,I/ActivityManager(  734): Killing 2643:com.lge.SprintHiddenMenu/1000 (adj 15): empty #17
,W/libprocessgroup(  734): failed to open /acct/uid_1000/pid_2643/cgroup.procs: No such file or directory
,D/Finsky  ( 2949): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/GLSActivity( 1604): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1604): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1604): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1604): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 2949): Failed write_ctrl(u 37) res=-1 errno=22
I/qtaguid ( 2949): Untagging socket 37 failed errno=-22
W/NetworkManagementSocketTagger( 2949): untagSocket(37) failed with errno -22
,D/Finsky  ( 2949): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,V/GLSActivity( 1604): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  734): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=3337 uid=10008 gids={50008, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/ResourcesManager( 3337): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3337): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 3337): VM with version 2.1.0 has multidex support
I/MultiDex( 3337): install
I/MultiDex( 3337): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 3337): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/qtaguid ( 2949): Failed write_ctrl(u 37) res=-1 errno=22
,I/qtaguid ( 2949): Untagging socket 37 failed errno=-22
W/NetworkManagementSocketTagger( 2949): untagSocket(37) failed with errno -22
,W/ActivityThread( 3337): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 3337): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@6ec267a: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3337): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1604): callingUid 10008, callindPid: 1604
,E/MDM     ( 1604): [233] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/ChimeraCfgMgr( 3337): Reading stored module config
D/AuthorizationBluetoothService( 1604): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/LocationInitializer( 1691): Restart initialization of location
,V/GLSActivity( 1604): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ChimeraCfgMgr( 3337): Loading module com.google.android.gms.car from APK com.google.android.gms
,W/GCoreFlp( 1604): No location to return for getLastLocation()
W/FusedLocationProvider( 1604): location=null
,D/CAR.SERVICE( 3337): Connecting to CarCallService...
,I/art     ( 3337): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 3337): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/NativeLibraryUtils( 3337): Install completed successfully. count=14 extracted=0
,D/CAR.SERVICE( 3337): com.google.android.projection.gearhead isn't installed.
,D/CAR.TEL.Service( 3337): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter( 3337): Creating a new PhoneAdapter instance
,W/ActivityManager(  734): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter( 3337): setListener: com.google.android.gms.car.dn@108c2791
W/ActivityManager(  734): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter( 3337): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 3337): Starting CarCallService with initial phone null
,D/CAR.SERVICE( 3337): Package validated; name: com.android.vending
,V/Finsky  ( 2949): [1] GearheadStateMonitor.access$100: mIsProjecting:false
,V/GLSActivity( 1604): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  734): Explicit concurrent mark sweep GC freed 31681(1567KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 27MB/41MB, paused 973us total 85.323ms
,I/qtaguid ( 2949): Failed write_ctrl(u 37) res=-1 errno=22
I/qtaguid ( 2949): Untagging socket 37 failed errno=-22
,W/NetworkManagementSocketTagger( 2949): untagSocket(37) failed with errno -22
,W/ResourcesManager( 2949): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2949): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 2949): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/Finsky  ( 2949): [1] DailyHygiene.access$600: Logging device features
,D/DeviceConnectionService( 1604): client connected with version: 8296000
,D/Finsky  ( 2949): [305] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,V/GLSActivity( 1604): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2949): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/Finsky  ( 2949): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,I/ActivityManager(  734): Killing 2714:com.google.android.youtube/u0a80 (adj 15): empty #17
,W/libprocessgroup(  734): failed to open /acct/uid_10080/pid_2714/cgroup.procs: No such file or directory
,D/CAR.SERVICE( 3337): mConnectedToCar = false, abort
,E/ActivityThread( 3337): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@3ef10659 that was originally bound here
E/ActivityThread( 3337): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@3ef10659 that was originally bound here
E/ActivityThread( 3337): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 3337): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 3337): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 3337): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 3337): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3337): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3337): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3337): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 3337): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 3337): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 3337): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 3337): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 3337): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 3337): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2731)
E/ActivityThread( 3337): 	at android.app.ActivityThread.access$1800(ActivityThread.java:144)
E/ActivityThread( 3337): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1361)
E/ActivityThread( 3337): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3337): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3337): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 3337): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3337): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3337): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 3337): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
,E/ActivityThread( 3337): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@11de5db8 that was originally bound here
E/ActivityThread( 3337): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@11de5db8 that was originally bound here
E/ActivityThread( 3337): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 3337): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 3337): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 3337): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 3337): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3337): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 3337): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 3337): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 3337): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 3337): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 3337): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 3337): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 3337): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2758)
E/ActivityThread( 3337): 	at android.app.ActivityThread.access$1900(ActivityThread.java:144)
E/ActivityThread( 3337): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
E/ActivityThread( 3337): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3337): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3337): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 3337): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3337): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3337): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 3337): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
,W/ActivityManager(  734): Unbind failed: could not find connection for android.os.BinderProxy@3ba72a9b
,D/Finsky  ( 2949): [295] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
D/Finsky  ( 2949): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,V/GLSActivity( 1604): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1604): Vacuum at: now=1452527861731 tag=VacuumService
,I/PhenotypeConfigurator( 1604): Scheduling Phenotype for one-off execution 8490 seconds from now (1452527862059)
,D/GetConfigurationSnapshotOperation( 1604): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1604): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1604): Using platform SSLCertificateSocketFactory
,V/GLSActivity( 1604): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1604): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Keyboard.Facilitator.LanguageModelFlusher( 1087): run()
I/Keyboard.Facilitator( 1087): flushDynamicLanguageModels()
,I/ConfigService( 1604): onCreate
,I/ConfigService( 1604): onDestroy
,I/ClearcutLoggerApiImpl( 1604): disconnect managed GoogleApiClient
,TIME-OUT KILL (timeout was 360000ms)
```
