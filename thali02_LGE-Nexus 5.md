#### Test 58741471ee11130_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
D/ChimeraCfgMgr( 1613): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1613): Module APK com.google.android.play.games already loaded
I/GAv4    ( 3031): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3031):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3031):   adb logcat -s GAv4
W/GAv4    ( 3031): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3031): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3031): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/AnalyticsTrackerProxyImpl( 3031): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
D/Finsky  ( 2589): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
--------- beginning of system
W/ResourcesManager( 3031): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3031): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  761): Killing 2401:com.google.android.youtube/u0a80 (adj 15): empty #17
V/JNIHelp ( 3031): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/System  ( 3031): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3031): Installed default security provider GmsCore_OpenSSL
D/AndroidRuntime( 3082): 
D/AndroidRuntime( 3082): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3082): CheckJNI is OFF
W/libprocessgroup(  761): failed to open /acct/uid_10080/pid_2401/cgroup.procs: No such file or directory
V/GLSActivity( 1567): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/AndroidRuntime( 3082): Calling main entry com.android.commands.am.Am
I/ActivityManager(  761): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  761): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3113 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3082): Shutting down VM
V/ActivityManager(  761): Display changed displayId=0
I/Icing   ( 1613): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
I/Icing   ( 1613): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/WebViewFactory( 3113): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3113): Time to load native libraries: 2 ms (timestamps 3731-3733)
I/LibraryLoader( 3113): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3113): Binding Chromium to main looper Looper (main, tid 1) {3669c0}
I/LibraryLoader( 3113): Expected native library version number "",actual native library version number ""
I/chromium( 3113): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/Icing   ( 1613): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
,I/BrowserStartupController( 3113): Initializing chromium process, singleProcess=true
W/art     ( 3113): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3113): ApplicationContext is null in ApplicationStatus
W/chromium( 3113): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
I/Icing   ( 1613): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
E/libEGL  ( 3113): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3113): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3113): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
D/BluetoothManagerService(  761): Message: 20
D/BluetoothManagerService(  761): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@26211a5a:true
W/art     ( 3113): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 3113): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 3113): CordovaWebView is running on device made by: LGE
W/art     ( 3113): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3113): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 3113): Render dirty regions requested: true
D/Atlas   ( 3113): Validating map...
W/chromium( 3113): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/OpenGLRenderer( 3113): Initialized EGL, version 1.4
D/OpenGLRenderer( 3113): Enabling debug mode 0
W/IInputConnectionWrapper( 3113): showStatusIcon on inactive InputConnection
I/ActivityManager(  761): Displayed com.test.thalitest/.MainActivity: +432ms (total +42s197ms)
W/BindingManager( 3113): Cannot call determinedVisibility() - never saw a connection for the pid: 3113
I/ActivityManager(  761): Killing 2057:com.google.android.deskclock/u0a38 (adj 15): empty #17
D/JsMessageQueue( 3113): Set native->JS mode to OnlineEventsBridgeMode
W/libprocessgroup(  761): failed to open /acct/uid_10038/pid_2057/cgroup.procs: No such file or directory
D/jxcore_app_log( 3113): JniHelper::setJavaVM(0xb4f5c280), pthread_self() = -1258391936
I/chromium( 3113): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 3113): Initializing JXcore engine
W/jxcore-log( 3113): JXcore engine is ready
,W/Thread-301( 3167): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[8610]" dev="sockfs" ino=8610 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/Thread-301( 3167): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3095 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/Thread-301( 3167): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[7073]" dev="sockfs" ino=7073 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/Thread-301( 3167): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[18360]" dev="sockfs" ino=18360 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3113): Starting JXcore engine
,W/jxcore-log( 3113): Platform android
W/jxcore-log( 3113): 
W/jxcore-log( 3113): Process ARCH arm
W/jxcore-log( 3113): 
,I/jxcore-log( 3113): JXcore Cordova bridge is ready!
I/jxcore-log( 3113): 
,W/jxcore-log( 3113): JXcore engine is started
,I/jxcore-log( 3113): Toggling radios to true
I/jxcore-log( 3113): 
,D/BluetoothAdapter( 3113): enable(): BT is already enabled..!
,D/WifiService(  761): New client listening to asynchronous messages
,D/WifiService(  761): setWifiEnabled: true pid=3113, uid=10270
E/WifiService(  761): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3113): Radios toggled
I/jxcore-log( 3113): 
,I/jxcore-log( 3113): My device name is: LGE-Nexus 5
I/jxcore-log( 3113): 
,I/wpa_supplicant( 1024): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  761): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  761): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
E/native  (  761): do suspend true
,D/CommandListener(  181): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1567): Read error: ssl=0x9ae2fe00: I/O error during system call, Connection timed out
V/NativeCrypto( 1567): SSL shutdown failed: ssl=0x9ae2fe00: I/O error during system call, Broken pipe
,D/ConnectivityService(  761): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): ValidatedState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): DefaultState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/ConnectivityService(  761): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  761): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,E/WifiConfigStore(  761): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiStateMachine(  761): Start Disconnecting Watchdog 1
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,I/wpa_supplicant( 1024): wlan0: CTRL-EVENT-SCAN-STARTED 
,E/native  (  761): do suspend true
,D/CommandListener(  181): Clearing all IP addresses on wlan0
D/ConnectivityService(  761): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityManager.CallbackHandler(  898): CM callback handler got msg 524292
D/Nat464Xlat(  761): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  761): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityManager.CallbackHandler( 1613): CM callback handler got msg 524292
D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Disconnected - quitting
,D/ConnectivityService(  761): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory( 1231): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/ConnectivityService(  761): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,D/WifiNetworkAgent(  761): NetworkAgent: NetworkAgent channel lost
,I/ActivityManager(  761): Killing 2546:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
,W/libprocessgroup(  761): failed to open /acct/uid_10069/pid_2546/cgroup.procs: No such file or directory
,D/Finsky  ( 2589): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/GLSActivity( 1567): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1567): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1567): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1567): Explicit concurrent mark sweep GC freed 34466(2MB) AllocSpace objects, 29(464KB) LOS objects, 40% free, 21MB/35MB, paused 875us total 45.922ms
,W/Finsky  ( 2589): [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,V/GLSActivity( 1567): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1567): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  761): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=3212 uid=10008 gids={50008, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/wpa_supplicant( 1024): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,I/wpa_supplicant( 1024): wlan0: Associated with c0:ff:d4:d3:aa:4a
,W/Finsky  ( 2589): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,W/ResourcesManager( 3212): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3212): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/wpa_supplicant( 1024): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1024): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  761): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore(  761): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/ConnectivityService(  761): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  761): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  181): Setting iface cfg
,E/WifiStateMachine(  761): Start Dhcp Watchdog 2
,I/MultiDex( 3212): VM with version 2.1.0 has multidex support
,I/MultiDex( 3212): install
I/MultiDex( 3212): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 3212): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 3212): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 3212): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3d1afe02: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 3212): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1567): callingUid 10008, callindPid: 1567
,D/ChimeraCfgMgr( 3212): Reading stored module config
E/MDM     ( 1567): [221] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
E/native  (  761): do suspend false
D/AuthorizationBluetoothService( 1567): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/LocationInitializer( 1613): Restart initialization of location
,E/WifiStateMachine(  761): scanCount==0 - aborting
,V/GLSActivity( 1567): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ChimeraCfgMgr( 3212): Loading module com.google.android.gms.car from APK com.google.android.gms
,W/GCoreFlp( 1567): No location to return for getLastLocation()
W/FusedLocationProvider( 1567): location=null
,D/NativeLibraryUtils( 3212): Install completed successfully. count=14 extracted=0
,D/CAR.SERVICE( 3212): Connecting to CarCallService...
,I/art     ( 3212): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 3212): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/CAR.SERVICE( 3212): com.google.android.projection.gearhead isn't installed.
,D/CAR.TEL.Service( 3212): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter( 3212): Creating a new PhoneAdapter instance
,W/ActivityManager(  761): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter( 3212): setListener: com.google.android.gms.car.dn@3b2584b9
,W/ActivityManager(  761): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 3212): Returning an existing PhoneAdapter instance.
,D/CAR.TEL.Service( 3212): Starting CarCallService with initial phone null
,I/dhcpcd  ( 3245): version 5.5.6 starting
E/dhcpcd  ( 3245): get_duid: Read-only file system
,D/CAR.SERVICE( 3212): Package validated; name: com.android.vending
,V/Finsky  ( 2589): [1] GearheadStateMonitor.access$100: mIsProjecting:false
,I/dhcpcd  ( 3245): wlan0: rebinding lease of 192.168.1.114
,V/GLSActivity( 1567): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  761): Explicit concurrent mark sweep GC freed 35320(1701KB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 27MB/41MB, paused 1.076ms total 67.841ms
,W/Finsky  ( 2589): [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,D/Finsky  ( 2589): [1] DailyHygiene.access$600: Logging device features
,D/Finsky  ( 2589): [1] DailyHygiene.reschedule: Scheduling new run in 273 minutes (failures=4)
,D/DeviceConnectionService( 1567): client connected with version: 8296000
,D/Finsky  ( 2589): [265] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,V/GLSActivity( 1567): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2589): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 2589): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,I/ActivityManager(  761): Killing 2499:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,W/libprocessgroup(  761): failed to open /acct/uid_10045/pid_2499/cgroup.procs: No such file or directory
,I/dhcpcd  ( 3245): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3245): wlan0: leased 192.168.1.114 for 86400 seconds
,D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  761): MasterInitialState.processMessage what=3
,D/Tethering(  761): MasterInitialState.processMessage what=3
,V/MusicLeanback( 2709): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,E/GpsLocationProvider(  761): No APN found to select.
,I/SystemUpdateService( 1613): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1613): onCreate
,D/SystemUpdateService( 1613): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1613): active receiver: enabled
,E/GpsLocationProvider(  761): No APN found to select.
,I/iu.Environment( 1613): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/SystemUpdateService( 1613): showing system update notification
,I/iu.UploadsManager( 1613): num queued entries: 0
,I/iu.UploadsManager( 1613): num updated entries: 0
I/iu.SyncManager( 1613): NEXT; no task
,I/Babel   ( 1890): connection state changed from CONNECTED to DISCONNECTED
,I/ValidateNoPeople(  761): skipping global notification
,V/SystemUpdateService( 1613): retry (wakeup: false) in 3599973 ms
,I/ActivityManager(  761): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3303 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/native  (  761): do suspend true
,D/SystemUpdateService( 1613): onDestroy
,D/ConnectivityService(  761): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService(  761): Adding iface wlan0 to network 101
E/WifiStateMachine(  761): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  761): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  761): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/ConnectivityService(  761): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
D/ConnectivityService(  761): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/ConnectivityService(  761): Setting Dns servers for network 101 to [/192.168.1.1]
D/Nat464Xlat(  761): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  761): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  761): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  761): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  761):    accepting network in place of null
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): EvaluatingState{ when=-1ms what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/CSLegacyTypeTracker(  761): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  761): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::5255:27ff:fef0:fd0b/64,192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  761): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  898): CM callback handler got msg 524290
D/ConnectivityManager.CallbackHandler( 1613): CM callback handler got msg 524290
,I/GAv4    ( 3303): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3303):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3303):   adb logcat -s GAv4
,W/GAv4    ( 3303): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 09 Feb 2016 13:06:05 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1455023165842], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1455023165821]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Don't send network conditions - lacking user consent.
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Validated
,D/ConnectivityService(  761): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  761): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  761): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
,D/ConnectivityService(  761): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler(  898): CM callback handler got msg 524290
,D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/TelephonyNetworkFactory( 1231): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1613): CM callback handler got msg 524290
,W/GAv4    ( 3303): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3303): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 3303): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3303): Time to load native libraries: 1 ms (timestamps 9438-9439)
,I/LibraryLoader( 3303): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3303): Binding Chromium to main looper Looper (main, tid 1) {34d2ebb2}
I/LibraryLoader( 3303): Expected native library version number "",actual native library version number ""
I/chromium( 3303): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3303): Initializing chromium process, singleProcess=true
W/art     ( 3303): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3303): ApplicationContext is null in ApplicationStatus
,W/chromium( 3303): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3303): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3303): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3303): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,W/AudioManagerAndroid( 3303): Requires BLUETOOTH permission
,I/NSApplication( 3303): Starting up...
,I/ActivityManager(  761): Killing 2687:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,W/libprocessgroup(  761): failed to open /acct/uid_10003/pid_2687/cgroup.procs: No such file or directory
,V/MusicLeanback( 2709): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1613): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1613): onCreate
,D/SystemUpdateService( 1613): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1613): active receiver: enabled
,I/SystemUpdateService( 1613): showing system update notification
,I/iu.Environment( 1613): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1613): num queued entries: 0
I/iu.UploadsManager( 1613): num updated entries: 0
,I/iu.SyncManager( 1613): NEXT; no task
,I/ValidateNoPeople(  761): skipping global notification
,V/SystemUpdateService( 1613): retry (wakeup: false) in 3599960 ms
,D/SystemUpdateService( 1613): onDestroy
,I/Babel   ( 1890): connection state changed from DISCONNECTED to CONNECTED
,I/jxcore-log( 3113): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 3113): 
,D/ConnectivityService(  761): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/jxcore-log( 3113): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 3113): 
,I/jxcore-log( 3113): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 3113): 
,I/jxcore-log( 3113): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 3113): 
,I/jxcore-log( 3113): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 3113): 
,I/jxcore-log( 3113): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
I/jxcore-log( 3113): 
,D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  761): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2709): type=WIFI subType= reason=null isConnected=true
V/MusicLeanback( 2709): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1613): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
D/SystemUpdateService( 1613): onCreate
,D/SystemUpdateService( 1613): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1613): active receiver: enabled
E/GpsLocationProvider(  761): No APN found to select.
I/SystemUpdateService( 1613): showing system update notification
,I/ValidateNoPeople(  761): skipping global notification
,V/SystemUpdateService( 1613): retry (wakeup: false) in 3599967 ms
,D/SystemUpdateService( 1613): onDestroy
,D/CAR.SERVICE( 3212): mConnectedToCar = false, abort
,E/ActivityThread( 3212): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@98f8681 that was originally bound here
E/ActivityThread( 3212): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@98f8681 that was originally bound here
E/ActivityThread( 3212): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 3212): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 3212): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 3212): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 3212): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3212): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3212): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3212): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 3212): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 3212): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 3212): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 3212): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 3212): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 3212): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2731)
E/ActivityThread( 3212): 	at android.app.ActivityThread.access$1800(ActivityThread.java:144)
E/ActivityThread( 3212): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1361)
E/ActivityThread( 3212): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3212): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3212): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 3212): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3212): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3212): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 3212): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
,E/ActivityThread( 3212): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@2acbd680 that was originally bound here
E/ActivityThread( 3212): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@2acbd680 that was originally bound here
E/ActivityThread( 3212): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 3212): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 3212): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 3212): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 3212): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3212): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 3212): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 3212): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 3212): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 3212): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 3212): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 3212): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 3212): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2758)
E/ActivityThread( 3212): 	at android.app.ActivityThread.access$1900(ActivityThread.java:144)
E/ActivityThread( 3212): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
E/ActivityThread( 3212): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3212): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3212): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 3212): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3212): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3212): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 3212): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
W/ActivityManager(  761): Unbind failed: could not find connection for android.os.BinderProxy@2f485563
,I/jxcore-log( 3113): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 3113): 
,I/jxcore-log( 3113): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 3113): 
,I/jxcore-log( 3113): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 3113): 
,I/jxcore-log( 3113): Test app app.js loaded
I/jxcore-log( 3113): 
,I/chromium( 3113): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3113): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3113): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3113): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3113): 	Bluetooth MAC address: 34:FC:EF:11:AE:67, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3113): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3113): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3113): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3113): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3113): 	Scan mode: 1
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3113): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a22a13 added. We now have 1 listener(s)
,I/jxcore-log( 3113): BLE advertisement is not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 3113): 
,V/GLSActivity( 1567): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1567): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2589): [255] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2589): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,V/GLSActivity( 1567): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1567): Vacuum at: now=1455023195342 tag=VacuumService
,I/ClearcutLoggerApiImpl( 1567): disconnect managed GoogleApiClient
,I/jxcore-log( 3113): --= Surplus to requirements =--
I/jxcore-log( 3113): 
I/jxcore-log( 3113): ****TEST TOOK:  ms ****
I/jxcore-log( 3113): 
I/jxcore-log( 3113): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3113): 
,D/AndroidRuntime( 3499): 
D/AndroidRuntime( 3499): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3499): CheckJNI is OFF
,D/AndroidRuntime( 3499): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  761): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
I/ActivityManager(  761): Killing 3113:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
,I/WindowState(  761): WIN DEATH: Window{39a4ce0a u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  761): Client connection lost with reason: 4
,W/PackageSettings(  761): Skipping PackageSetting{2e0a1854 com.example.hello/10278} due to missing metadata
,I/ActivityManager(  761):   Force finishing activity ActivityRecord{1ba4f977 u0 com.test.thalitest/.MainActivity t216}
,I/ActivityManager(  761): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
,I/ActivityManager(  761):   Force finishing activity ActivityRecord{1ba4f977 u0 com.test.thalitest/.MainActivity t216 f}
W/ActivityManager(  761): Duplicate finish request for ActivityRecord{1ba4f977 u0 com.test.thalitest/.MainActivity t216 f}
,I/art     ( 1281): Explicit concurrent mark sweep GC freed 3938(293KB) AllocSpace objects, 1(126KB) LOS objects, 23% free, 25MB/33MB, paused 225us total 16.662ms
,W/ActivityManager(  761): Spurious death for ProcessRecord{6be3690 3113:com.test.thalitest/u0a270}, curProc for 3113: null
,I/Keyboard.Facilitator( 1110): resetDictionaries() : en_US
,W/GeofencerStateMachine( 1567): Ignoring removeGeofence because network location is disabled.
,I/art     ( 1613): Explicit concurrent mark sweep GC freed 3909(205KB) AllocSpace objects, 1(16KB) LOS objects, 25% free, 22MB/29MB, paused 2.425ms total 46.094ms
I/Keyboard.Facilitator.DecoderInitializer( 1110): run()
,I/InputReader(  761): Reconfiguring input devices.  changes=0x00000010
,I/art     ( 1346): Explicit concurrent mark sweep GC freed 10092(692KB) AllocSpace objects, 1(39KB) LOS objects, 24% free, 19MB/25MB, paused 335us total 41.331ms
,I/Decoder ( 1110): createOrResetDecoder
,D/VoicemailCleanupService( 2821): Cleaning up data for package: com.test.thalitest
,I/UpdateIcingCorporaServi( 1346): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,W/Launcher( 1281): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@35e3b6f9 new=com.google.android.velvet.VelvetApplication@35e3b6f9
,I/Adreno-EGL(  943): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
I/OpenGLRenderer(  943): Initialized EGL, version 1.4
,D/OpenGLRenderer(  943): Enabling debug mode 0
,I/art     (  761): Explicit concurrent mark sweep GC freed 36673(1928KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 27MB/41MB, paused 1.055ms total 98.738ms
,I/ActivityManager(  761): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3540 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,I/art     (  761): WaitForGcToComplete blocked for 96.337ms for cause Explicit
,I/ConfigService( 1567): onCreate
,D/BackupManagerService(  761): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/JobSchedulerService(  761): Receieved: android.intent.action.PACKAGE_REMOVED
,D/TaskPersister(  761): removeObsoleteFile: deleting file=216_task.xml
,W/InputMethodManagerService(  761): Focus gain on non-focused client com.android.internal.view.IInputMethodClient$Stub$Proxy@454f350 (uid=10034 pid=943)
,W/ContextImpl( 3540): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1110): run()
,D/ChimeraCfgMgr( 1613): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1613): Module APK com.google.android.play.games already loaded
,D/PackageBroadcastService( 1613): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1613): Clearing selected account for com.test.thalitest
,I/UpdateIcingCorporaServi( 1346): UpdateCorporaTask done [took 161 ms] updated apps [took 161 ms] 
,D/ChimeraCfgMgr( 1613): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1613): Module APK com.google.android.play.games already loaded
,E/NetworkScheduler.SchedulerReceiver( 1567): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1567): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1110): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/LocationSettingsChecker( 1613): Removing dialog suppression flag for package com.test.thalitest
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1110): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1110): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1110): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1110): run() : Loading LM = history
I/art     (  761): Explicit concurrent mark sweep GC freed 6627(355KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 2.165ms total 166.486ms
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1110): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1110): run() : Loading LM = user
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1110): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1110): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1110): run()
,I/Keyboard.Facilitator.RecurringTaskScheduler( 1110): run()
I/StatsUtilsManager( 1110): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1110): shouldRecordStats() = Too Soon
,D/gH_CompatibleDatabase( 1613): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1613): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,D/gH_MetricsDatabase( 1613): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1613): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/gH_CompatibleDatabase( 1613): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1613): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1613): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/gH_CompatibleDatabase( 1613): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1613): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 1613): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
,D/gH_CompatibleDatabase( 1613): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1613): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1613): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,I/ActivityManager(  761): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3577 uid=10039 gids={50039, 9997} abi=armeabi-v7a
,I/Launcher( 1281): Deferring update until onResume
,D/AndroidRuntime( 3499): Shutting down VM
,I/GMPM-SVC( 1613): App measurement is starting up, version: 8489
I/GMPM-SVC( 1613): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
,W/BaseAppContext( 1613): Using Auth Proxy for data requests.
,I/ActivityManager(  761): Killing 2653:com.android.settings/1000 (adj 15): empty #17
,W/ResourcesManager( 1281): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/WifiService(  761): Client connection lost with reason: 4
,W/ResourcesManager( 1281): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/Launcher( 1281): Deferring update until onResume
,W/libprocessgroup(  761): failed to open /acct/uid_1000/pid_2653/cgroup.procs: No such file or directory
,W/BaseAppContext( 1613): Using Auth Proxy for data requests.
,I/Icing   ( 1613): doRemovePackageData com.test.thalitest
,I/ActivityManager(  761): Killing 2520:com.google.android.gm/u0a70 (adj 15): empty #17
,W/libprocessgroup(  761): failed to open /acct/uid_10070/pid_2520/cgroup.procs: No such file or directory
,I/ActivityManager(  761): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3604 uid=10007 gids={50007, 9997, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  761): Killing 1994:com.google.android.calendar/u0a31 (adj 15): empty #17
,W/libprocessgroup(  761): failed to open /acct/uid_10031/pid_1994/cgroup.procs: No such file or directory
,D/ExternalStorage( 3604): After updating volumes, found 1 active roots

```
