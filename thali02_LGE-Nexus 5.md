#### Test 57617811ecc172f_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
W/GAv4    ( 3026): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3026): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 3026): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
D/Finsky  ( 2631): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
--------- beginning of system
W/ResourcesManager( 3026): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3026): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  764): Killing 2438:com.google.android.youtube/u0a80 (adj 15): empty #17
V/JNIHelp ( 3026): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/libprocessgroup(  764): failed to open /acct/uid_10080/pid_2438/cgroup.procs: No such file or directory
W/System  ( 3026): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3026): Installed default security provider GmsCore_OpenSSL
V/GLSActivity( 1571): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Icing   ( 1614): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
I/Icing   ( 1614): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1614): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
I/Icing   ( 1614): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
I/ActivityManager(  764): Killing 2062:com.google.android.deskclock/u0a38 (adj 15): empty #17
W/libprocessgroup(  764): failed to open /acct/uid_10038/pid_2062/cgroup.procs: No such file or directory
,D/AndroidRuntime( 3096): 
D/AndroidRuntime( 3096): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3096): CheckJNI is OFF
D/AndroidRuntime( 3096): Calling main entry com.android.commands.am.Am
I/ActivityManager(  764): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  764): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3116 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3096): Shutting down VM
V/ActivityManager(  764): Display changed displayId=0
I/WebViewFactory( 3116): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3116): Time to load native libraries: 1 ms (timestamps 4302-4303)
I/LibraryLoader( 3116): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3116): Binding Chromium to main looper Looper (main, tid 1) {3a20f975}
I/LibraryLoader( 3116): Expected native library version number "",actual native library version number ""
I/chromium( 3116): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3116): Initializing chromium process, singleProcess=true
W/art     ( 3116): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3116): ApplicationContext is null in ApplicationStatus
W/chromium( 3116): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3116): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3116): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3116): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  764): Message: 20
,D/BluetoothManagerService(  764): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@263c58b1:true
,W/art     ( 3116): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3116): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3116): CordovaWebView is running on device made by: LGE
,W/art     ( 3116): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3116): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3116): Render dirty regions requested: true
,D/Atlas   ( 3116): Validating map...
,W/chromium( 3116): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3116): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3116): Enabling debug mode 0
,W/IInputConnectionWrapper( 3116): showStatusIcon on inactive InputConnection
,W/BindingManager( 3116): Cannot call determinedVisibility() - never saw a connection for the pid: 3116
,I/ActivityManager(  764): Displayed com.test.thalitest/.MainActivity: +406ms (total +42s638ms)
,D/JsMessageQueue( 3116): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3116): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257343360
,I/chromium( 3116): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/ActivityManager(  764): Killing 2594:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
,W/libprocessgroup(  764): failed to open /acct/uid_10069/pid_2594/cgroup.procs: No such file or directory
,W/jxcore-log( 3116): Initializing JXcore engine
W/jxcore-log( 3116): JXcore engine is ready
,W/Thread-301( 3166): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[9448]" dev="sockfs" ino=9448 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-301( 3166): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/Thread-301( 3166): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[7945]" dev="sockfs" ino=7945 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/Thread-301( 3166): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[19971]" dev="sockfs" ino=19971 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3116): Starting JXcore engine
,W/jxcore-log( 3116): Platform android
W/jxcore-log( 3116): 
W/jxcore-log( 3116): Process ARCH arm
W/jxcore-log( 3116): 
,I/jxcore-log( 3116): JXcore Cordova bridge is ready!
I/jxcore-log( 3116): 
W/jxcore-log( 3116): JXcore engine is started
,I/jxcore-log( 3116): Toggling radios to true
I/jxcore-log( 3116): 
,D/BluetoothAdapter( 3116): enable(): BT is already enabled..!
,D/WifiService(  764): New client listening to asynchronous messages
D/WifiService(  764): setWifiEnabled: true pid=3116, uid=10270
,E/WifiService(  764): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3116): Radios toggled
I/jxcore-log( 3116): 
,I/jxcore-log( 3116): My device name is: LGE-Nexus 5
I/jxcore-log( 3116): 
,I/wpa_supplicant( 1054): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  764): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  764): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/native  (  764): do suspend true
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1571): Read error: ssl=0xb3ff7e00: I/O error during system call, Connection timed out
V/NativeCrypto( 1571): SSL shutdown failed: ssl=0xb3ff7e00: I/O error during system call, Broken pipe
D/ConnectivityService(  764): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  764): ValidatedState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  764): DefaultState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  764): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  764): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  764): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  764): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,D/ConnectivityService(  764): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  764): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,E/WifiConfigStore(  764): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiStateMachine(  764): Start Disconnecting Watchdog 1
E/native  (  764): do suspend true
,I/wpa_supplicant( 1054): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,D/ConnectivityService(  764): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler(  900): CM callback handler got msg 524292
D/Nat464Xlat(  764): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  764): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  764): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  764): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  764): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  764): Disconnected - quitting
D/ConnectivityService(  764): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  764): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory( 1252): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/ConnectivityService(  764): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,D/ConnectivityManager.CallbackHandler( 1614): CM callback handler got msg 524292
,D/WifiNetworkAgent(  764): NetworkAgent: NetworkAgent channel lost
,D/Finsky  ( 2631): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/GLSActivity( 1571): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1571): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1571): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 2631): [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,V/GLSActivity( 1571): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  764): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=3191 uid=10008 gids={50008, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,V/GLSActivity( 1571): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 3191): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3191): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 3191): VM with version 2.1.0 has multidex support
I/MultiDex( 3191): install
I/MultiDex( 3191): VM has multidex support, MultiDex support library is disabled.
,W/Finsky  ( 2631): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,V/JNIHelp ( 3191): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 3191): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 3191): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@36d1b72f: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3191): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1571): callingUid 10008, callindPid: 1571
,E/MDM     ( 1571): [228] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 1614): Restart initialization of location
,D/AuthorizationBluetoothService( 1571): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/ChimeraCfgMgr( 3191): Reading stored module config
,V/GLSActivity( 1571): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1571): No location to return for getLastLocation()
,W/FusedLocationProvider( 1571): location=null
D/ChimeraCfgMgr( 3191): Loading module com.google.android.gms.car from APK com.google.android.gms
,D/NativeLibraryUtils( 3191): Install completed successfully. count=14 extracted=0
,D/CAR.SERVICE( 3191): Connecting to CarCallService...
,I/art     ( 3191): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 3191): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/CAR.SERVICE( 3191): com.google.android.projection.gearhead isn't installed.
,D/CAR.TEL.Service( 3191): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter( 3191): Creating a new PhoneAdapter instance
,W/ActivityManager(  764): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter( 3191): setListener: com.google.android.gms.car.dn@618d3ca
,W/ActivityManager(  764): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 3191): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 3191): Starting CarCallService with initial phone null
,D/CAR.SERVICE( 3191): Package validated; name: com.android.vending
,V/Finsky  ( 2631): [1] GearheadStateMonitor.access$100: mIsProjecting:false
,V/GLSActivity( 1571): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  764): Explicit concurrent mark sweep GC freed 28061(1355KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 1.017ms total 84.449ms
,W/Finsky  ( 2631): [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,D/Finsky  ( 2631): [1] DailyHygiene.access$600: Logging device features
,D/Finsky  ( 2631): [1] DailyHygiene.reschedule: Scheduling new run in 9 minutes (failures=1)
,D/DeviceConnectionService( 1571): client connected with version: 8296000
,D/Finsky  ( 2631): [266] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,V/GLSActivity( 1571): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2631): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 2631): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,I/ActivityManager(  764): Killing 2549:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,W/libprocessgroup(  764): failed to open /acct/uid_10045/pid_2549/cgroup.procs: No such file or directory
,I/wpa_supplicant( 1054): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,I/wpa_supplicant( 1054): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 1054): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1054): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  764): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
,E/WifiConfigStore(  764): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  764): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiConfigStore(  764): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  179): Setting iface cfg
,E/WifiStateMachine(  764): Start Dhcp Watchdog 2
,E/native  (  764): do suspend false
,E/WifiStateMachine(  764): scanCount==0 - aborting
,I/dhcpcd  ( 3258): version 5.5.6 starting
,E/dhcpcd  ( 3258): get_duid: Read-only file system
,I/dhcpcd  ( 3258): wlan0: rebinding lease of 192.168.1.114
,I/dhcpcd  ( 3258): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3258): wlan0: leased 192.168.1.114 for 86400 seconds
,D/ConnectivityService(  764): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  764): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  764): MasterInitialState.processMessage what=3
,D/Tethering(  764): MasterInitialState.processMessage what=3
,V/MusicLeanback( 2722): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1614): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1614): onCreate
,E/GpsLocationProvider(  764): No APN found to select.
,D/SystemUpdateService( 1614): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1614): active receiver: enabled
,I/iu.Environment( 1614): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1614): num queued entries: 0
I/iu.UploadsManager( 1614): num updated entries: 0
I/iu.SyncManager( 1614): NEXT; no task
,I/SystemUpdateService( 1614): showing system update notification
,I/Babel   ( 1892): connection state changed from CONNECTED to DISCONNECTED,
,I/ValidateNoPeople(  764): skipping global notification
,V/SystemUpdateService( 1614): retry (wakeup: false) in 3599956 ms
,E/native  (  764): do suspend true
,I/ActivityManager(  764): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3300 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/GpsLocationProvider(  764): No APN found to select.
,D/ConnectivityService(  764): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService(  764): Adding iface wlan0 to network 101
,E/WifiStateMachine(  764): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  764): Unexpected mtu value: 0, wlan0
,D/ConnectivityService(  764): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  764): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
D/ConnectivityService(  764): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  764): Setting Dns servers for network 101 to [/192.168.1.1]
,D/Nat464Xlat(  764): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  764): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  764): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  764): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  764):    accepting network in place of null
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  764): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  764): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  764): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  764): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/CSLegacyTypeTracker(  764): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  764): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  764): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  764): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/SystemUpdateService( 1614): onDestroy
,D/ConnectivityManager.CallbackHandler( 1614): CM callback handler got msg 524290
D/ConnectivityManager.CallbackHandler(  900): CM callback handler got msg 524290
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  764): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 29 Jan 2016 10:29:10 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454063350216], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454063350193]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  764): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  764): Validated
D/ConnectivityService(  764): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  764): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  764): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  764): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  900): CM callback handler got msg 524290
D/ConnectivityService(  764): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 1614): CM callback handler got msg 524290
,D/TelephonyNetworkFactory( 1252): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/GAv4    ( 3300): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3300):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3300):   adb logcat -s GAv4
,W/GAv4    ( 3300): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,D/Nat464Xlat(  764): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  764): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler( 1614): CM callback handler got msg 524295
D/ConnectivityManager.CallbackHandler(  900): CM callback handler got msg 524295
,W/GAv4    ( 3300): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3300): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 3300): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3300): Time to load native libraries: 2 ms (timestamps 9-11)
,I/LibraryLoader( 3300): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3300): Binding Chromium to main looper Looper (main, tid 1) {1a4ca1f}
I/LibraryLoader( 3300): Expected native library version number "",actual native library version number ""
I/chromium( 3300): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3300): Initializing chromium process, singleProcess=true
,W/art     ( 3300): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3300): ApplicationContext is null in ApplicationStatus
,W/chromium( 3300): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3300): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3300): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3300): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,W/AudioManagerAndroid( 3300): Requires BLUETOOTH permission
,I/NSApplication( 3300): Starting up...
,I/ActivityManager(  764): Killing 2696:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,W/libprocessgroup(  764): failed to open /acct/uid_10003/pid_2696/cgroup.procs: No such file or directory
,V/MusicLeanback( 2722): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1614): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1614): onCreate
D/SystemUpdateService( 1614): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
I/iu.Environment( 1614): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/SystemUpdateService( 1614): active receiver: enabled
,I/iu.UploadsManager( 1614): num queued entries: 0
I/iu.UploadsManager( 1614): num updated entries: 0
I/iu.SyncManager( 1614): NEXT; no task
,I/SystemUpdateService( 1614): showing system update notification
,I/ValidateNoPeople(  764): skipping global notification
,V/SystemUpdateService( 1614): retry (wakeup: false) in 3599957 ms
,D/SystemUpdateService( 1614): onDestroy
,I/jxcore-log( 3116): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 3116): 
,I/Babel   ( 1892): connection state changed from DISCONNECTED to CONNECTED
,D/ConnectivityService(  764): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/jxcore-log( 3116): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 3116): 
,I/jxcore-log( 3116): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 3116): 
,I/jxcore-log( 3116): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 3116): 
,I/jxcore-log( 3116): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 3116): 
,I/jxcore-log( 3116): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 3116): 
,I/jxcore-log( 3116): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 3116): 
,I/jxcore-log( 3116): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 3116): 
,D/CAR.SERVICE( 3191): mConnectedToCar = false, abort
,E/ActivityThread( 3191): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@15c0a872 that was originally bound here
E/ActivityThread( 3191): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@15c0a872 that was originally bound here
E/ActivityThread( 3191): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 3191): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 3191): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 3191): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 3191): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3191): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3191): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3191): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 3191): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 3191): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 3191): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 3191): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 3191): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 3191): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2731)
E/ActivityThread( 3191): 	at android.app.ActivityThread.access$1800(ActivityThread.java:144)
E/ActivityThread( 3191): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1361)
E/ActivityThread( 3191): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3191): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3191): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 3191): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3191): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3191): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 3191): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
,E/ActivityThread( 3191): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@7a7a335 that was originally bound here
E/ActivityThread( 3191): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@7a7a335 that was originally bound here
E/ActivityThread( 3191): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 3191): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 3191): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 3191): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 3191): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3191): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 3191): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 3191): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 3191): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 3191): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 3191): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 3191): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 3191): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2758)
E/ActivityThread( 3191): 	at android.app.ActivityThread.access$1900(ActivityThread.java:144)
E/ActivityThread( 3191): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
E/ActivityThread( 3191): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3191): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3191): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 3191): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3191): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3191): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 3191): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
,W/ActivityManager(  764): Unbind failed: could not find connection for android.os.BinderProxy@9e04ae4
,D/ConnectivityService(  764): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  764): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2722): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2722): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1614): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1614): onCreate
D/SystemUpdateService( 1614): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1614): active receiver: enabled
,I/SystemUpdateService( 1614): showing system update notification,
,I/ValidateNoPeople(  764): skipping global notification
,V/SystemUpdateService( 1614): retry (wakeup: false) in 3599975 ms
,D/SystemUpdateService( 1614): onDestroy
,E/GpsLocationProvider(  764): No APN found to select.
,I/jxcore-log( 3116): Test app app.js loaded
I/jxcore-log( 3116): 
,I/chromium( 3116): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3116): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 3116): BLE advertisement is supported
I/jxcore-log( 3116): 
,D/Finsky  ( 2631): [255] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
D/Finsky  ( 2631): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,V/GLSActivity( 1571): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1571): Vacuum at: now=1454063378205 tag=VacuumService
,I/PhenotypeConfigurator( 1571): Scheduling Phenotype for one-off execution 233 seconds from now (1454063378617)
,D/GetConfigurationSnapshotOperation( 1571): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1571): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1571): Using platform SSLCertificateSocketFactory
,V/GLSActivity( 1571): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1571): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  764): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=3489 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
,I/GAv4    ( 3489): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3489):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3489):   adb logcat -s GAv4
,W/GAv4    ( 3489): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3489): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3489): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  764): Killing 2678:com.android.settings/1000 (adj 15): empty #17
,D/WifiService(  764): Client connection lost with reason: 4
,W/libprocessgroup(  764): failed to open /acct/uid_1000/pid_2678/cgroup.procs: No such file or directory
,I/ClearcutLoggerApiImpl( 1571): disconnect managed GoogleApiClient
,I/jxcore-log( 3116): --= Surplus to requirements =--
I/jxcore-log( 3116): 
I/jxcore-log( 3116): ****TEST TOOK:  ms ****
I/jxcore-log( 3116): 
I/jxcore-log( 3116): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3116): 
,D/AndroidRuntime( 3538): 
D/AndroidRuntime( 3538): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 3538): CheckJNI is OFF
,D/AndroidRuntime( 3538): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  764): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
I/ActivityManager(  764): Killing 3116:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
,I/WindowState(  764): WIN DEATH: Window{fafdc46 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  764): Client connection lost with reason: 4
,W/PackageSettings(  764): Skipping PackageSetting{2783b6b9 com.example.hello/10278} due to missing metadata
,I/ActivityManager(  764):   Force finishing activity ActivityRecord{6d55772 u0 com.test.thalitest/.MainActivity t216}
,W/ActivityManager(  764): Spurious death for ProcessRecord{3e268457 3116:com.test.thalitest/u0a270}, curProc for 3116: null
,I/ActivityManager(  764): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
,I/ActivityManager(  764):   Force finishing activity ActivityRecord{6d55772 u0 com.test.thalitest/.MainActivity t216 f}
W/ActivityManager(  764): Duplicate finish request for ActivityRecord{6d55772 u0 com.test.thalitest/.MainActivity t216 f}
,I/art     ( 1368): Explicit concurrent mark sweep GC freed 7531(526KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 19MB/25MB, paused 758us total 35.731ms
,I/art     ( 1279): Explicit concurrent mark sweep GC freed 3932(293KB) AllocSpace objects, 1(126KB) LOS objects, 23% free, 25MB/33MB, paused 15.400ms total 33.460ms
,I/InputReader(  764): Reconfiguring input devices.  changes=0x00000010
,I/Keyboard.Facilitator( 1095): resetDictionaries() : en_US
,W/GeofencerStateMachine( 1571): Ignoring removeGeofence because network location is disabled.
,I/art     ( 1614): Explicit concurrent mark sweep GC freed 3751(199KB) AllocSpace objects, 1(16KB) LOS objects, 24% free, 22MB/30MB, paused 483us total 65.883ms
,I/Adreno-EGL(  950): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
I/OpenGLRenderer(  950): Initialized EGL, version 1.4
,D/OpenGLRenderer(  950): Enabling debug mode 0
,D/VoicemailCleanupService( 2833): Cleaning up data for package: com.test.thalitest
,I/Keyboard.Facilitator.DecoderInitializer( 1095): run()
W/Launcher( 1279): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@318a0d0a new=com.google.android.velvet.VelvetApplication@318a0d0a
,I/UpdateIcingCorporaServi( 1368): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/art     (  764): Explicit concurrent mark sweep GC freed 49547(2MB) AllocSpace objects, 8(128KB) LOS objects, 33% free, 27MB/41MB, paused 1.412ms total 99.466ms
,I/art     (  764): WaitForGcToComplete blocked for 80.748ms for cause Explicit
,I/Decoder ( 1095): createOrResetDecoder
,I/ActivityManager(  764): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3579 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,D/BackupManagerService(  764): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/JobSchedulerService(  764): Receieved: android.intent.action.PACKAGE_REMOVED
,D/TaskPersister(  764): removeObsoleteFile: deleting file=216_task.xml
,I/art     (  764): Explicit concurrent mark sweep GC freed 6780(368KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 1.337ms total 100.111ms
I/art     (  764): WaitForGcToComplete blocked for 110.703ms for cause Explicit
,I/art     (  764): Explicit concurrent mark sweep GC freed 2286(135KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 27MB/41MB, paused 866us total 47.843ms
,I/ConfigService( 1571): onCreate
,W/InputMethodManagerService(  764): Focus gain on non-focused client com.android.internal.view.IInputMethodClient$Stub$Proxy@20347470 (uid=10034 pid=950)
,D/AndroidRuntime( 3538): Shutting down VM
,W/ContextImpl( 3579): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
,I/UpdateIcingCorporaServi( 1368): UpdateCorporaTask done [took 215 ms] updated apps [took 215 ms] 
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1095): run()
,D/ChimeraCfgMgr( 1614): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1614): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1614): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1614): Module APK com.google.android.play.games already loaded
,E/NetworkScheduler.SchedulerReceiver( 1571): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1571): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,D/PackageBroadcastService( 1614): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1614): Clearing selected account for com.test.thalitest
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1095): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1095): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1095): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1095): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1095): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1095): run() : Loaded File = UserHistory.en_US.dict
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1095): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1095): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1095): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1095): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1095): run()
I/StatsUtilsManager( 1095): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1095): shouldRecordStats() = Too Soon
,I/LocationSettingsChecker( 1614): Removing dialog suppression flag for package com.test.thalitest
,D/gH_CompatibleDatabase( 1614): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1614): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1614): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1614): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/gH_CompatibleDatabase( 1614): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
,D/gH_CompatibleDatabase( 1614): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1614): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/gH_CompatibleDatabase( 1614): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1614): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 1614): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
,D/gH_CompatibleDatabase( 1614): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1614): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1614): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/ActivityManager(  764): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3610 uid=10039 gids={50039, 9997} abi=armeabi-v7a
,I/Launcher( 1279): Deferring update until onResume
I/ActivityManager(  764): Killing 2567:com.google.android.gm/u0a70 (adj 15): empty #17
,W/ResourcesManager( 1279): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 1279): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/Launcher( 1279): Deferring update until onResume
,W/libprocessgroup(  764): failed to open /acct/uid_10070/pid_2567/cgroup.procs: No such file or directory
,W/BaseAppContext( 1614): Using Auth Proxy for data requests.
I/GMPM-SVC( 1614): App measurement is starting up, version: 8489
I/GMPM-SVC( 1614): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
,W/BaseAppContext( 1614): Using Auth Proxy for data requests.
,I/Icing   ( 1614): doRemovePackageData com.test.thalitest
,W/FileUtils( 1614): Failed to chmod(/data/data/com.google.android.gms/databases/google_app_measurement.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,W/FileUtils( 1614): Failed to chmod(/data/data/com.google.android.gms/files): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
E/Icing   ( 1614): Failed to open Apps corpus file.
,E/Icing   ( 1614): Failed to open Apps corpus file.
,E/SQLiteDatabase( 3610): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 3610): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3610): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3610): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 3610): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 3610): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3610): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3610): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3610): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 3610): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 3610): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 3610): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
E/SQLiteDatabase( 3610): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 3610): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 3610): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 3610): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/SQLiteDatabase( 3610): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/SQLiteDatabase( 3610): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:367)
E/SQLiteDatabase( 3610): 	at android.content.ContentResolver.call(ContentResolver.java:1372)
E/SQLiteDatabase( 3610): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/SQLiteDatabase( 3610): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2579)
E/SQLiteDatabase( 3610): 	at android.app.ActivityThread.access$1700(ActivityThread.java:144)
E/SQLiteDatabase( 3610): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1355)
E/SQLiteDatabase( 3610): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 3610): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 3610): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/SQLiteDatabase( 3610): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 3610): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 3610): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/SQLiteDatabase( 3610): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
,D/AndroidRuntime( 3610): Shutting down VM
E/SharedPreferencesImpl( 1614): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/proxy-apps-corpus.xml to backup file /data/data/com.google.android.gms/shared_prefs/proxy-apps-corpus.xml.bak
--------- beginning of crash
E/AndroidRuntime( 3610): FATAL EXCEPTION: main
E/AndroidRuntime( 3610): Process: com.android.documentsui, PID: 3610
E/AndroidRuntime( 3610): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 3610): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2586)
E/AndroidRuntime( 3610): 	at android.app.ActivityThread.access$1700(ActivityThread.java:144)
E/AndroidRuntime( 3610): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1355)
E/AndroidRuntime( 3610): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 3610): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 3610): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/AndroidRuntime( 3610): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 3610): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 3610): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/AndroidRuntime( 3610): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
E/AndroidRuntime( 3610): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 3610): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 3610): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 3610): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 3610): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 3610): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 3610): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 3610): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AndroidRuntime( 3610): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AndroidRuntime( 3610): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 3610): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
E/AndroidRuntime( 3610): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime( 3610): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 3610): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 3610): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/AndroidRuntime( 3610): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/AndroidRuntime( 3610): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:367)
E/AndroidRuntime( 3610): 	at android.content.ContentResolver.call(ContentResolver.java:1372)
E/AndroidRuntime( 3610): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/AndroidRuntime( 3610): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2579)
E/AndroidRuntime( 3610): 	... 9 more
I/ActivityManager(  764): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3639 uid=10007 gids={50007, 9997, 1028, 1015, 1023} abi=armeabi-v7a
I/ActivityManager(  764): Killing 1988:com.google.android.calendar/u0a31 (adj 15): empty #17
,W/libprocessgroup(  764): failed to open /acct/uid_10031/pid_1988/cgroup.procs: No such file or directory
I/Process ( 3610): Sending signal. PID: 3610 SIG: 9

```
