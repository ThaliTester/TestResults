#### Test 587523534d3a10e_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
D/ChimeraCfgMgr( 1655): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1655): Module APK com.google.android.play.games already loaded
I/GAv4    ( 3088): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3088):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3088):   adb logcat -s GAv4
W/GAv4    ( 3088): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3088): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3088): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 3088): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
D/Finsky  ( 2640): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
--------- beginning of system
W/ResourcesManager( 3088): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3088): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  762): Killing 2119:com.google.android.deskclock/u0a38 (adj 15): empty #17
V/JNIHelp ( 3088): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/System  ( 3088): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3088): Installed default security provider GmsCore_OpenSSL
W/libprocessgroup(  762): failed to open /acct/uid_10038/pid_2119/cgroup.procs: No such file or directory
V/GLSActivity( 1624): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Icing   ( 1655): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
I/Icing   ( 1655): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1655): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
I/Icing   ( 1655): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
,D/AndroidRuntime( 3144): 
D/AndroidRuntime( 3144): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3144): CheckJNI is OFF
D/AndroidRuntime( 3144): Calling main entry com.android.commands.am.Am
I/ActivityManager(  762): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  762): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3172 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3144): Shutting down VM
V/ActivityManager(  762): Display changed displayId=0
I/WebViewFactory( 3172): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3172): Time to load native libraries: 2 ms (timestamps 6923-6925)
I/LibraryLoader( 3172): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3172): Binding Chromium to main looper Looper (main, tid 1) {25304c69}
I/LibraryLoader( 3172): Expected native library version number "",actual native library version number ""
I/chromium( 3172): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3172): Initializing chromium process, singleProcess=true
W/art     ( 3172): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3172): ApplicationContext is null in ApplicationStatus
,W/chromium( 3172): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3172): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3172): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3172): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  762): Message: 20
,D/BluetoothManagerService(  762): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@30f11874:true
,W/art     ( 3172): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3172): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3172): CordovaWebView is running on device made by: LGE
,W/art     ( 3172): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3172): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3172): Render dirty regions requested: true
,D/Atlas   ( 3172): Validating map...
,W/chromium( 3172): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3172): Initialized EGL, version 1.4
D/OpenGLRenderer( 3172): Enabling debug mode 0
,I/Keyboard.Facilitator( 1091): onFinishInput()
,W/IInputConnectionWrapper( 3172): showStatusIcon on inactive InputConnection
,I/ActivityManager(  762): Displayed com.test.thalitest/.MainActivity: +476ms (total +44s306ms)
,W/BindingManager( 3172): Cannot call determinedVisibility() - never saw a connection for the pid: 3172
,D/JsMessageQueue( 3172): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3172): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257342720
,I/chromium( 3172): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/Finsky  ( 2640): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/GLSActivity( 1624): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1624): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1624): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1624): Explicit concurrent mark sweep GC freed 33799(2MB) AllocSpace objects, 29(464KB) LOS objects, 40% free, 21MB/35MB, paused 615us total 48.037ms
,V/GLSActivity( 1624): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 2640): Failed write_ctrl(u 37) res=-1 errno=22
I/qtaguid ( 2640): Untagging socket 37 failed errno=-22
W/NetworkManagementSocketTagger( 2640): untagSocket(37) failed with errno -22
,D/Finsky  ( 2640): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,V/GLSActivity( 1624): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  762): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=3235 uid=10008 gids={50008, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/ResourcesManager( 3235): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3235): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 3235): VM with version 2.1.0 has multidex support
I/MultiDex( 3235): install
I/MultiDex( 3235): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 3235): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 3235): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 3235): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@12956303: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3235): Installed default security provider GmsCore_OpenSSL
,I/qtaguid ( 2640): Failed write_ctrl(u 37) res=-1 errno=22
I/qtaguid ( 2640): Untagging socket 37 failed errno=-22
W/NetworkManagementSocketTagger( 2640): untagSocket(37) failed with errno -22
,D/WearableService( 1624): callingUid 10008, callindPid: 1624
,D/LocationInitializer( 1655): Restart initialization of location
,D/AuthorizationBluetoothService( 1624): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/MDM     ( 1624): [228] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/ChimeraCfgMgr( 3235): Reading stored module config
,V/GLSActivity( 1624): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1624): No location to return for getLastLocation()
D/ChimeraCfgMgr( 3235): Loading module com.google.android.gms.car from APK com.google.android.gms
W/FusedLocationProvider( 1624): location=null
,D/NativeLibraryUtils( 3235): Install completed successfully. count=14 extracted=0
,D/CAR.SERVICE( 3235): Connecting to CarCallService...
,I/art     ( 3235): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 3235): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/CAR.SERVICE( 3235): com.google.android.projection.gearhead isn't installed.
,D/CAR.TEL.Service( 3235): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter( 3235): Creating a new PhoneAdapter instance
,W/ActivityManager(  762): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 3235): setListener: com.google.android.gms.car.dn@254c01ae
W/ActivityManager(  762): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 3235): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 3235): Starting CarCallService with initial phone null
,D/CAR.SERVICE( 3235): Package validated; name: com.android.vending
,V/Finsky  ( 2640): [1] GearheadStateMonitor.access$100: mIsProjecting:false
,W/jxcore-log( 3172): Initializing JXcore engine
W/jxcore-log( 3172): JXcore engine is ready
,W/Thread-306( 3224): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[6392]" dev="sockfs" ino=6392 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/Thread-306( 3224): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/Thread-306( 3224): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[10330]" dev="sockfs" ino=10330 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-306( 3224): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[19035]" dev="sockfs" ino=19035 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3172): Starting JXcore engine
,W/jxcore-log( 3172): Platform android
W/jxcore-log( 3172): 
W/jxcore-log( 3172): Process ARCH arm
W/jxcore-log( 3172): 
,I/art     (  762): Explicit concurrent mark sweep GC freed 18495(845KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 27MB/41MB, paused 964us total 65.367ms
,V/GLSActivity( 1624): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/jxcore-log( 3172): JXcore Cordova bridge is ready!
I/jxcore-log( 3172): 
W/jxcore-log( 3172): JXcore engine is started
,I/qtaguid ( 2640): Failed write_ctrl(u 37) res=-1 errno=22
I/qtaguid ( 2640): Untagging socket 37 failed errno=-22
,W/NetworkManagementSocketTagger( 2640): untagSocket(37) failed with errno -22
,I/jxcore-log( 3172): Toggling radios to true
I/jxcore-log( 3172): 
,D/BluetoothAdapter( 3172): enable(): BT is already enabled..!
D/WifiService(  762): New client listening to asynchronous messages
D/WifiService(  762): setWifiEnabled: true pid=3172, uid=10270
E/WifiService(  762): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3172): Radios toggled
I/jxcore-log( 3172): 
I/jxcore-log( 3172): My device name is: LGE-Nexus 5
I/jxcore-log( 3172): 
I/wpa_supplicant( 1025): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  762): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  762): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/native  (  762): do suspend true
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1624): Read error: ssl=0x9d657000: I/O error during system call, Connection timed out
,V/NativeCrypto( 1624): SSL shutdown failed: ssl=0x9d657000: I/O error during system call, Broken pipe
,D/ConnectivityService(  762): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): ValidatedState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): DefaultState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): Checking http://clients3.google.com/generate_204 on "NG7005g"
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,E/WifiConfigStore(  762): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  762): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  762): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,E/WifiStateMachine(  762): Start Disconnecting Watchdog 1
I/wpa_supplicant( 1025): wlan0: CTRL-EVENT-SCAN-STARTED 
E/native  (  762): do suspend true
,D/ConnectivityService(  762): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/Nat464Xlat(  762): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  762): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,D/ConnectivityService(  762): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  762): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): Disconnected - quitting
,D/ConnectivityService(  762): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler(  900): CM callback handler got msg 524292
,D/CommandListener(  179): Clearing all IP addresses on wlan0
D/ConnectivityManager.CallbackHandler( 1655): CM callback handler got msg 524292
,D/TelephonyNetworkFactory( 1242): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/WifiNetworkAgent(  762): NetworkAgent: NetworkAgent channel lost
W/ResourcesManager( 2640): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2640): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 2640): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/Finsky  ( 2640): [1] DailyHygiene.access$600: Logging device features
,D/DeviceConnectionService( 1624): client connected with version: 8296000
,D/Finsky  ( 2640): [270] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,V/GLSActivity( 1624): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2640): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 2640): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,I/ActivityManager(  762): Killing 2555:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,I/ActivityManager(  762): Killing 2599:com.google.android.gm.exchange/u0a69 (adj 15): empty #18
,W/libprocessgroup(  762): failed to open /acct/uid_10045/pid_2555/cgroup.procs: No such file or directory
,W/libprocessgroup(  762): failed to open /acct/uid_10069/pid_2599/cgroup.procs: No such file or directory
,I/wpa_supplicant( 1025): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,I/wpa_supplicant( 1025): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 1025): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1025): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  762): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore(  762): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  762): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiConfigStore(  762): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  179): Setting iface cfg
E/WifiStateMachine(  762): Start Dhcp Watchdog 2
,E/native  (  762): do suspend false
,E/WifiStateMachine(  762): scanCount==0 - aborting
,I/dhcpcd  ( 3300): version 5.5.6 starting
E/dhcpcd  ( 3300): get_duid: Read-only file system
,I/dhcpcd  ( 3300): wlan0: rebinding lease of 192.168.1.114
,I/dhcpcd  ( 3300): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3300): wlan0: leased 192.168.1.114 for 86400 seconds
,D/ConnectivityService(  762): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  762): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  762): MasterInitialState.processMessage what=3
,D/Tethering(  762): MasterInitialState.processMessage what=3
,V/MusicLeanback( 2746): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,E/GpsLocationProvider(  762): No APN found to select.
,I/SystemUpdateService( 1655): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1655): onCreate
,D/SystemUpdateService( 1655): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/iu.Environment( 1655): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1655): num queued entries: 0
I/iu.UploadsManager( 1655): num updated entries: 0
I/iu.SyncManager( 1655): NEXT; no task
,I/SystemUpdateService( 1655): active receiver: enabled
E/native  (  762): do suspend true
,I/SystemUpdateService( 1655): showing system update notification
,E/GpsLocationProvider(  762): No APN found to select.
,I/ValidateNoPeople(  762): skipping global notification
,I/Babel   ( 1951): connection state changed from CONNECTED to DISCONNECTED
,V/SystemUpdateService( 1655): retry (wakeup: false) in 3599981 ms
,I/ActivityManager(  762): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3338 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ConnectivityService(  762): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  762): Adding iface wlan0 to network 101
,E/WifiStateMachine(  762): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  762): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  762): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  762): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  762): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  762): Setting Dns servers for network 101 to [/192.168.1.1]
,D/Nat464Xlat(  762): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  762): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  762): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  762): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  762):    accepting network in place of null
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): Checking http://clients3.google.com/generate_204 on "NG7005g"
D/CSLegacyTypeTracker(  762): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  762): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  762): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/ConnectivityService(  762): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/SystemUpdateService( 1655): onDestroy
,D/Nat464Xlat(  762): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  762): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler(  900): CM callback handler got msg 524290
D/ConnectivityManager.CallbackHandler( 1655): CM callback handler got msg 524290
D/ConnectivityManager.CallbackHandler(  900): CM callback handler got msg 524295
D/ConnectivityManager.CallbackHandler( 1655): CM callback handler got msg 524295
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 09 Feb 2016 14:49:33 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1455029373079], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1455029373061]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): Validated
D/ConnectivityService(  762): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  762): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  762): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  762): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  762): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 1655): CM callback handler got msg 524290
D/TelephonyNetworkFactory( 1242): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler(  900): CM callback handler got msg 524290
,I/GAv4    ( 3338): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3338):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3338):   adb logcat -s GAv4
,W/GAv4    ( 3338): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3338): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3338): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 3338): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3338): Time to load native libraries: 2 ms (timestamps 2857-2859)
,I/LibraryLoader( 3338): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3338): Binding Chromium to main looper Looper (main, tid 1) {33a512f3}
I/LibraryLoader( 3338): Expected native library version number "",actual native library version number ""
I/chromium( 3338): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3338): Initializing chromium process, singleProcess=true
,W/art     ( 3338): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3338): ApplicationContext is null in ApplicationStatus
,W/chromium( 3338): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3338): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3338): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3338): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,W/AudioManagerAndroid( 3338): Requires BLUETOOTH permission
,I/NSApplication( 3338): Starting up...
,I/ActivityManager(  762): Killing 2722:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,W/libprocessgroup(  762): failed to open /acct/uid_10003/pid_2722/cgroup.procs: No such file or directory
,V/MusicLeanback( 2746): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1655): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1655): onCreate
,D/SystemUpdateService( 1655): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/iu.Environment( 1655): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/SystemUpdateService( 1655): active receiver: enabled
,I/iu.UploadsManager( 1655): num queued entries: 0
I/iu.UploadsManager( 1655): num updated entries: 0
,I/iu.SyncManager( 1655): NEXT; no task
,I/SystemUpdateService( 1655): showing system update notification
,I/Babel   ( 1951): connection state changed from DISCONNECTED to CONNECTED
,I/ValidateNoPeople(  762): skipping global notification
,V/SystemUpdateService( 1655): retry (wakeup: false) in 3599963 ms
,D/SystemUpdateService( 1655): onDestroy
,I/jxcore-log( 3172): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 3172): 
,I/ActivityManager(  762): Killing 2697:com.android.settings/1000 (adj 15): empty #17
,D/WifiService(  762): Client connection lost with reason: 4
,W/libprocessgroup(  762): failed to open /acct/uid_1000/pid_2697/cgroup.procs: No such file or directory
,D/ConnectivityService(  762): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,D/CAR.SERVICE( 3235): mConnectedToCar = false, abort
,E/ActivityThread( 3235): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@9410dd6 that was originally bound here
E/ActivityThread( 3235): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@9410dd6 that was originally bound here
E/ActivityThread( 3235): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 3235): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 3235): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 3235): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 3235): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3235): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3235): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3235): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 3235): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 3235): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 3235): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 3235): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 3235): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 3235): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2731)
E/ActivityThread( 3235): 	at android.app.ActivityThread.access$1800(ActivityThread.java:144)
E/ActivityThread( 3235): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1361)
E/ActivityThread( 3235): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3235): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3235): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 3235): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3235): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3235): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 3235): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
,E/ActivityThread( 3235): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@33bd0a29 that was originally bound here
E/ActivityThread( 3235): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@33bd0a29 that was originally bound here
E/ActivityThread( 3235): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 3235): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 3235): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 3235): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 3235): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3235): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 3235): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 3235): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 3235): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 3235): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 3235): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 3235): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 3235): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2758)
E/ActivityThread( 3235): 	at android.app.ActivityThread.access$1900(ActivityThread.java:144)
E/ActivityThread( 3235): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
E/ActivityThread( 3235): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3235): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3235): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 3235): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3235): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3235): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 3235): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
W/ActivityManager(  762): Unbind failed: could not find connection for android.os.BinderProxy@21a55666
,I/jxcore-log( 3172): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 3172): 
,I/jxcore-log( 3172): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 3172): 
I/jxcore-log( 3172): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 3172): 
,I/jxcore-log( 3172): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 3172): 
,I/jxcore-log( 3172): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
I/jxcore-log( 3172): 
,D/ConnectivityService(  762): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  762): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2746): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2746): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1655): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1655): onCreate
,D/SystemUpdateService( 1655): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1655): active receiver: enabled
,I/SystemUpdateService( 1655): showing system update notification
,I/ValidateNoPeople(  762): skipping global notification
,V/SystemUpdateService( 1655): retry (wakeup: false) in 3599972 ms
,D/SystemUpdateService( 1655): onDestroy
,E/GpsLocationProvider(  762): No APN found to select.
,I/jxcore-log( 3172): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 3172): 
,I/jxcore-log( 3172): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 3172): 
,I/jxcore-log( 3172): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 3172): 
,I/jxcore-log( 3172): Test app app.js loaded
I/jxcore-log( 3172): 
,I/chromium( 3172): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3172): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3172): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3172): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3172): 	Bluetooth MAC address: 34:FC:EF:11:AE:67, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3172): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3172): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3172): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3172): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3172): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3172): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25c96d80 added. We now have 1 listener(s)
,I/jxcore-log( 3172): BLE advertisement is not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 3172): 
,V/GLSActivity( 1624): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1624): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2640): [260] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2640): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,V/GLSActivity( 1624): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1624): Vacuum at: now=1455029399474 tag=VacuumService
,I/PhenotypeConfigurator( 1624): Scheduling Phenotype for one-off execution 11228 seconds from now (1455029399843)
,D/GetConfigurationSnapshotOperation( 1624): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1624): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1624): Using platform SSLCertificateSocketFactory
,I/Keyboard.Facilitator.LanguageModelFlusher( 1091): run()
I/Keyboard.Facilitator( 1091): flushDynamicLanguageModels()
,I/ConfigService( 1624): onCreate
,I/ConfigService( 1624): onDestroy
,I/ClearcutLoggerApiImpl( 1624): disconnect managed GoogleApiClient
,I/jxcore-log( 3172): --= Surplus to requirements =--
I/jxcore-log( 3172): 
I/jxcore-log( 3172): ****TEST TOOK:  ms ****
I/jxcore-log( 3172): 
I/jxcore-log( 3172): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3172): 
,D/AndroidRuntime( 3549): 
D/AndroidRuntime( 3549): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 3549): CheckJNI is OFF
,D/AndroidRuntime( 3549): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  762): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
I/ActivityManager(  762): Killing 3172:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
,I/WindowState(  762): WIN DEATH: Window{214586a4 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  762): Client connection lost with reason: 4
,W/PackageSettings(  762): Skipping PackageSetting{a6a426d com.example.hello/10278} due to missing metadata
,I/ActivityManager(  762):   Force finishing activity ActivityRecord{2f7bd2b0 u0 com.test.thalitest/.MainActivity t216}
,W/ActivityManager(  762): Spurious death for ProcessRecord{39151ab4 3172:com.test.thalitest/u0a270}, curProc for 3172: null
,I/ActivityManager(  762): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
I/ActivityManager(  762):   Force finishing activity ActivityRecord{2f7bd2b0 u0 com.test.thalitest/.MainActivity t216 f}
,W/ActivityManager(  762): Duplicate finish request for ActivityRecord{2f7bd2b0 u0 com.test.thalitest/.MainActivity t216 f}
,I/art     ( 1655): Explicit concurrent mark sweep GC freed 3916(205KB) AllocSpace objects, 1(16KB) LOS objects, 24% free, 22MB/30MB, paused 658us total 40.486ms
,I/art     ( 1285): Explicit concurrent mark sweep GC freed 3992(295KB) AllocSpace objects, 1(126KB) LOS objects, 23% free, 25MB/33MB, paused 322us total 28.320ms
,I/InputReader(  762): Reconfiguring input devices.  changes=0x00000010
,W/GeofencerStateMachine( 1624): Ignoring removeGeofence because network location is disabled.
,D/NetworkChangeNotifierAutoDetect(  949): Network connectivity changed, type is: 2
,I/Keyboard.Facilitator( 1091): resetDictionaries() : en_US
,I/art     ( 1381): Explicit concurrent mark sweep GC freed 10292(700KB) AllocSpace objects, 1(39KB) LOS objects, 24% free, 18MB/25MB, paused 310us total 20.808ms
,W/art     (  762): Suspending all threads took: 5.244ms
,I/art     (  762): Explicit concurrent mark sweep GC freed 57556(2MB) AllocSpace objects, 9(144KB) LOS objects, 33% free, 27MB/41MB, paused 7.504ms total 92.692ms
,I/Keyboard.Facilitator.DecoderInitializer( 1091): run()
D/VoicemailCleanupService( 2847): Cleaning up data for package: com.test.thalitest
,I/UpdateIcingCorporaServi( 1381): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/Decoder ( 1091): createOrResetDecoder
I/LibraryLoader( 1347): Loading chrome directly from within /data/app/com.android.chrome-1/base.apk
,W/Launcher( 1285): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@f0eb6ee new=com.google.android.velvet.VelvetApplication@f0eb6ee
,I/OpenGLRenderer(  949): Initialized EGL, version 1.4
,D/OpenGLRenderer(  949): Enabling debug mode 0
,I/ActivityManager(  762): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3588 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,I/LibraryLoader( 1347): Time to load native libraries: 73 ms (timestamps 2646-2719)
,I/LibraryLoader( 1347): Expected native library version number "44.0.2403.133",actual native library version number "44.0.2403.133"
,I/chromium( 1347): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,W/art     ( 1347): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 1347): Attempt to remove local handle scope entry from IRT, ignoring
,D/BackupManagerService(  762): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  762): Receieved: android.intent.action.PACKAGE_REMOVED
,I/ConfigService( 1624): onCreate
,D/TaskPersister(  762): removeObsoleteFile: deleting file=216_task.xml
,W/art     (  949): Attempt to remove local handle scope entry from IRT, ignoring
,W/InputMethodManagerService(  762): Focus gain on non-focused client com.android.internal.view.IInputMethodClient$Stub$Proxy@3d89c309 (uid=10034 pid=949)
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1091): run()
,I/UpdateIcingCorporaServi( 1381): UpdateCorporaTask done [took 163 ms] updated apps [took 163 ms] 
,W/ContextImpl( 3588): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
,D/PackageBroadcastService( 1655): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1655): Clearing selected account for com.test.thalitest
,D/ChimeraCfgMgr( 1655): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1655): Module APK com.google.android.play.games already loaded
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1091): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1091): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1091): run() : Loading LM = contacts
,I/LocationSettingsChecker( 1655): Removing dialog suppression flag for package com.test.thalitest
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1091): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1091): run() : Loading LM = history
,W/InputMethodManagerService(  762): Got RemoteException sending setActive(false) notification to pid 3172 uid 10270
,I/Keyboard.Facilitator( 1091): onFinishInput()
I/art     (  762): Explicit concurrent mark sweep GC freed 9902(536KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 1.807ms total 204.737ms
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1091): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1091): run() : Loading LM = user
D/ChimeraCfgMgr( 1655): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1655): Module APK com.google.android.play.games already loaded
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1091): run() : Missing File = Personal.en_US.dict
,I/Keyboard.Facilitator.PersonalDictionaryLoader( 1091): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1091): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1091): run()
,I/StatsUtilsManager( 1091): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1091): shouldRecordStats() = Too Soon
I/Launcher( 1285): Deferring update until onResume
,E/NetworkScheduler.SchedulerReceiver( 1624): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1624): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,W/ResourcesManager( 1285): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 1285): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/Launcher( 1285): Deferring update until onResume
,D/gH_CompatibleDatabase( 1655): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1655): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1655): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1655): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/gH_CompatibleDatabase( 1655): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1655): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1655): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/gH_CompatibleDatabase( 1655): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1655): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1655): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1655): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1655): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1655): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,I/ActivityManager(  762): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3630 uid=10039 gids={50039, 9997} abi=armeabi-v7a
,D/AndroidRuntime( 3549): Shutting down VM
,W/BaseAppContext( 1655): Using Auth Proxy for data requests.
,I/GMPM-SVC( 1655): App measurement is starting up, version: 8489
I/GMPM-SVC( 1655): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
,W/BaseAppContext( 1655): Using Auth Proxy for data requests.
,I/Icing   ( 1655): doRemovePackageData com.test.thalitest
,I/ActivityManager(  762): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3658 uid=10007 gids={50007, 9997, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  762): Killing 2573:com.google.android.gm/u0a70 (adj 15): empty #17
,W/libprocessgroup(  762): failed to open /acct/uid_10070/pid_2573/cgroup.procs: No such file or directory
,I/ActivityManager(  762): Killing 2051:com.google.android.calendar/u0a31 (adj 15): empty #17
,D/ExternalStorage( 3658): After updating volumes, found 1 active roots
,W/libprocessgroup(  762): failed to open /acct/uid_10031/pid_2051/cgroup.procs: No such file or directory
,W/ResourcesManager( 3088): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 3088): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.

```
