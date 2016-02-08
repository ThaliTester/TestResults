#### Test 58380500962e22b_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
D/qdhwcomposer(  171): hwc_blank: Done blanking display: 0
D/SurfaceControl(  756): Excessive delay in setPowerMode(): 292ms
D/ChimeraCfgMgr( 1651): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1651): Module APK com.google.android.play.games already loaded
I/GAv4    ( 3060): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3060):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3060):   adb logcat -s GAv4
W/GAv4    ( 3060): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3060): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 3060): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
W/GAv4    ( 3060): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
D/Finsky  ( 2620): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
--------- beginning of system
W/ResourcesManager( 3060): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3060): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  756): Killing 2412:com.google.android.youtube/u0a80 (adj 15): empty #17
V/JNIHelp ( 3060): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/System  ( 3060): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3060): Installed default security provider GmsCore_OpenSSL
W/libprocessgroup(  756): failed to open /acct/uid_10080/pid_2412/cgroup.procs: No such file or directory
V/GLSActivity( 1616): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Icing   ( 1651): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
I/Icing   ( 1651): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1651): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
I/Icing   ( 1651): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
I/ActivityManager(  756): Killing 2539:com.google.android.deskclock/u0a38 (adj 15): empty #17
W/libprocessgroup(  756): failed to open /acct/uid_10038/pid_2539/cgroup.procs: No such file or directory
,D/AndroidRuntime( 3129): 
D/AndroidRuntime( 3129): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3129): CheckJNI is OFF
D/AndroidRuntime( 3129): Calling main entry com.android.commands.am.Am
I/ActivityManager(  756): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  756): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3150 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3129): Shutting down VM
V/ActivityManager(  756): Display changed displayId=0
I/WebViewFactory( 3150): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3150): Time to load native libraries: 2 ms (timestamps 3802-3804)
I/LibraryLoader( 3150): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3150): Binding Chromium to main looper Looper (main, tid 1) {22b147e6}
I/LibraryLoader( 3150): Expected native library version number "",actual native library version number ""
I/chromium( 3150): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3150): Initializing chromium process, singleProcess=true
W/art     ( 3150): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3150): ApplicationContext is null in ApplicationStatus
W/chromium( 3150): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3150): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3150): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3150): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  756): Message: 20
D/BluetoothManagerService(  756): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@119d6373:true
,W/art     ( 3150): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3150): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3150): CordovaWebView is running on device made by: LGE
,W/art     ( 3150): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3150): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3150): Render dirty regions requested: true
,D/Atlas   ( 3150): Validating map...
,W/chromium( 3150): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3150): Initialized EGL, version 1.4
D/OpenGLRenderer( 3150): Enabling debug mode 0
,I/Keyboard.Facilitator( 1101): onFinishInput()
,I/ActivityManager(  756): Displayed com.test.thalitest/.MainActivity: +381ms (total +41s232ms)
,W/IInputConnectionWrapper( 3150): showStatusIcon on inactive InputConnection
,W/BindingManager( 3150): Cannot call determinedVisibility() - never saw a connection for the pid: 3150
,D/JsMessageQueue( 3150): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3150): JniHelper::setJavaVM(0xb4f5c280), pthread_self() = -1258381056
,I/chromium( 3150): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/ActivityManager(  756): Killing 2590:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
,W/libprocessgroup(  756): failed to open /acct/uid_10069/pid_2590/cgroup.procs: No such file or directory
,W/jxcore-log( 3150): Initializing JXcore engine
W/jxcore-log( 3150): JXcore engine is ready
,W/Thread-302( 3199): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[7974]" dev="sockfs" ino=7974 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-302( 3199): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
,W/Thread-302( 3199): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[8082]" dev="sockfs" ino=8082 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-302( 3199): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[18421]" dev="sockfs" ino=18421 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3150): Starting JXcore engine
,W/jxcore-log( 3150): Platform android
W/jxcore-log( 3150): 
W/jxcore-log( 3150): Process ARCH arm
W/jxcore-log( 3150): 
,I/jxcore-log( 3150): JXcore Cordova bridge is ready!
I/jxcore-log( 3150): 
W/jxcore-log( 3150): JXcore engine is started
,I/jxcore-log( 3150): Toggling radios to true
I/jxcore-log( 3150): 
,D/BluetoothAdapter( 3150): enable(): BT is already enabled..!
,D/WifiService(  756): New client listening to asynchronous messages
D/WifiService(  756): setWifiEnabled: true pid=3150, uid=10270
E/WifiService(  756): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3150): Radios toggled
I/jxcore-log( 3150): 
,I/jxcore-log( 3150): My device name is: LGE-Nexus 5
I/jxcore-log( 3150): 
,I/wpa_supplicant( 1046): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  756): WifiStateMachine: Leaving Connected state
,E/WifiConfigStore(  756): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/native  (  756): do suspend true
,D/CommandListener(  178): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1616): Read error: ssl=0xaf728e00: I/O error during system call, Connection timed out
,V/NativeCrypto( 1616): SSL shutdown failed: ssl=0xaf728e00: I/O error during system call, Broken pipe
,D/ConnectivityService(  756): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  756): ValidatedState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  756): DefaultState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  756): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  756): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  756): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  756): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,E/WifiConfigStore(  756): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/ConnectivityService(  756): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  756): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,E/WifiStateMachine(  756): Start Disconnecting Watchdog 1
,I/wpa_supplicant( 1046): wlan0: CTRL-EVENT-SCAN-STARTED 
,E/native  (  756): do suspend true
,D/CommandListener(  178): Clearing all IP addresses on wlan0
D/ConnectivityService(  756): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityManager.CallbackHandler(  917): CM callback handler got msg 524292
D/Nat464Xlat(  756): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  756): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityManager.CallbackHandler( 1651): CM callback handler got msg 524292
D/ConnectivityService(  756): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  756): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  756): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory( 1222): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  756): EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  756): DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  756): Disconnected - quitting
,D/WifiNetworkAgent(  756): NetworkAgent: NetworkAgent channel lost
,D/Finsky  ( 2620): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/GLSActivity( 1616): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1616): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1616): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 2620): [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,V/GLSActivity( 1616): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1616): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  756): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=3241 uid=10008 gids={50008, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/ResourcesManager( 3241): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3241): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 3241): VM with version 2.1.0 has multidex support
,I/MultiDex( 3241): install
I/MultiDex( 3241): VM has multidex support, MultiDex support library is disabled.
,W/Finsky  ( 2620): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,V/JNIHelp ( 3241): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 3241): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 3241): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@21b4f6b8: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3241): Installed default security provider GmsCore_OpenSSL
,D/ChimeraCfgMgr( 3241): Reading stored module config
,D/WearableService( 1616): callingUid 10008, callindPid: 1616
,D/LocationInitializer( 1651): Restart initialization of location
D/AuthorizationBluetoothService( 1616): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
E/MDM     ( 1616): [227] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,V/GLSActivity( 1616): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ChimeraCfgMgr( 3241): Loading module com.google.android.gms.car from APK com.google.android.gms
,W/GCoreFlp( 1616): No location to return for getLastLocation()
,W/FusedLocationProvider( 1616): location=null
,D/CAR.SERVICE( 3241): Connecting to CarCallService...
,I/art     ( 3241): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 3241): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
D/NativeLibraryUtils( 3241): Install completed successfully. count=14 extracted=0
,D/CAR.SERVICE( 3241): com.google.android.projection.gearhead isn't installed.
,I/art     (  756): Explicit concurrent mark sweep GC freed 31125(1496KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 787us total 57.760ms
,D/CAR.TEL.Service( 3241): Creating a new CarCallService.
D/CAR.TEL.PhoneAdapter( 3241): Creating a new PhoneAdapter instance
,W/ActivityManager(  756): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 3241): setListener: com.google.android.gms.car.dn@19d68ce7
,W/ActivityManager(  756): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter( 3241): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 3241): Starting CarCallService with initial phone null
,D/CAR.SERVICE( 3241): Package validated; name: com.android.vending
,V/Finsky  ( 2620): [1] GearheadStateMonitor.access$100: mIsProjecting:false
,I/wpa_supplicant( 1046): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,V/GLSActivity( 1616): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/wpa_supplicant( 1046): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 1046): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1046): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
W/Finsky  ( 2620): [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,D/ConnectivityService(  756): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore(  756): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  756): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  756): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  178): Setting iface cfg
,E/WifiStateMachine(  756): Start Dhcp Watchdog 2
D/Finsky  ( 2620): [1] DailyHygiene.access$600: Logging device features
,D/Finsky  ( 2620): [1] DailyHygiene.reschedule: Scheduling new run in 9 minutes (failures=1)
,D/DeviceConnectionService( 1616): client connected with version: 8296000
,D/Finsky  ( 2620): [266] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,V/GLSActivity( 1616): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2620): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 2620): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,E/native  (  756): do suspend false
,I/ActivityManager(  756): Killing 2515:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,E/WifiStateMachine(  756): scanCount==0 - aborting
,W/libprocessgroup(  756): failed to open /acct/uid_10045/pid_2515/cgroup.procs: No such file or directory
,I/dhcpcd  ( 3292): version 5.5.6 starting
E/dhcpcd  ( 3292): get_duid: Read-only file system
,I/art     ( 1616): Explicit concurrent mark sweep GC freed 34425(2MB) AllocSpace objects, 18(288KB) LOS objects, 39% free, 21MB/35MB, paused 1.164ms total 59.524ms
,I/dhcpcd  ( 3292): wlan0: rebinding lease of 192.168.1.114
,I/dhcpcd  ( 3292): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3292): wlan0: leased 192.168.1.114 for 86400 seconds
,E/native  (  756): do suspend true
,D/ConnectivityService(  756): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService(  756): Adding iface wlan0 to network 101
E/WifiStateMachine(  756): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  756): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  756): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  756): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  756): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  756): Setting Dns servers for network 101 to [/192.168.1.1]
,D/Nat464Xlat(  756): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  756): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  756): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  756): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  756):    accepting network in place of null
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  756): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  756): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  756): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  756): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/CSLegacyTypeTracker(  756): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  756): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  756): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  756): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler(  917): CM callback handler got msg 524290
,D/Nat464Xlat(  756): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  756): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler( 1651): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler(  917): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 1651): CM callback handler got msg 524295
D/ConnectivityService(  756): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  756): MasterInitialState.processMessage what=3
,D/ConnectivityService(  756): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  756): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2730): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2730): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 2730): type=WIFI subType= reason=null isConnected=true
,E/GpsLocationProvider(  756): No APN found to select.
,I/SystemUpdateService( 1651): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1651): onCreate
,E/GpsLocationProvider(  756): No APN found to select.
,D/SystemUpdateService( 1651): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1651): active receiver: enabled
,I/SystemUpdateService( 1651): showing system update notification
,I/ValidateNoPeople(  756): skipping global notification
,V/SystemUpdateService( 1651): retry (wakeup: false) in 3599982 ms
,I/ActivityManager(  756): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3352 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  756): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 08 Feb 2016 23:15:39 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454973339548], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454973339530]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  756): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  756): Validated
D/ConnectivityService(  756): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  756): rematching NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  756): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  756): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  756): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler(  917): CM callback handler got msg 524290
D/ConnectivityManager.CallbackHandler( 1651): CM callback handler got msg 524290
D/SystemUpdateService( 1651): onDestroy
D/TelephonyNetworkFactory( 1222): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/GAv4    ( 3352): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3352):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3352):   adb logcat -s GAv4
,W/GAv4    ( 3352): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3352): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.,
,W/GAv4    ( 3352): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 3352): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3352): Time to load native libraries: 3 ms (timestamps 9703-9706)
I/LibraryLoader( 3352): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3352): Binding Chromium to main looper Looper (main, tid 1) {2caf7de8}
,I/LibraryLoader( 3352): Expected native library version number "",actual native library version number ""
I/chromium( 3352): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3352): Initializing chromium process, singleProcess=true
W/art     ( 3352): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3352): ApplicationContext is null in ApplicationStatus
,W/chromium( 3352): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3352): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3352): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3352): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,I/NSApplication( 3352): Starting up...
,W/AudioManagerAndroid( 3352): Requires BLUETOOTH permission
,I/ActivityManager(  756): Killing 2710:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,D/ConnectivityService(  756): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,W/libprocessgroup(  756): failed to open /acct/uid_10003/pid_2710/cgroup.procs: No such file or directory
,V/MusicLeanback( 2730): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1651): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1651): onCreate
,D/SystemUpdateService( 1651): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1651): active receiver: enabled
,I/jxcore-log( 3150): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 3150): 
,I/SystemUpdateService( 1651): showing system update notification
,W/art     ( 2905): Suspending all threads took: 25.446ms
,I/ValidateNoPeople(  756): skipping global notification
,V/SystemUpdateService( 1651): retry (wakeup: false) in 3599943 ms
,D/SystemUpdateService( 1651): onDestroy
,I/jxcore-log( 3150): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 3150): 
,I/jxcore-log( 3150): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 3150): 
I/jxcore-log( 3150): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 3150): 
,I/jxcore-log( 3150): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 3150): 
,I/jxcore-log( 3150): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 3150): 
I/jxcore-log( 3150): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
I/jxcore-log( 3150): 
,I/jxcore-log( 3150): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 3150): 
I/jxcore-log( 3150): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 3150): 
,D/ConnectivityService(  756): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  756): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2730): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2730): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1651): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1651): onCreate
,D/SystemUpdateService( 1651): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1651): active receiver: enabled
,I/SystemUpdateService( 1651): showing system update notification
,E/GpsLocationProvider(  756): No APN found to select.
,D/AlarmManagerService(  756): Setting time of day to sec=1454973342
,W/AlarmManagerService(  756): Unable to set rtc to 1454973342: Invalid argument
,I/ValidateNoPeople(  756): skipping global notification
,V/SystemUpdateService( 1651): retry (wakeup: false) in 3600181 ms
,D/SystemUpdateService( 1651): onDestroy
,I/ActivityManager(  756): Start proc com.google.android.keep for broadcast com.google.android.keep/.notification.AlertReceiver: pid=3451 uid=10071 gids={50071, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/CAR.SERVICE( 3241): mConnectedToCar = false, abort
,E/ActivityThread( 3241): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@124daeef that was originally bound here
E/ActivityThread( 3241): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@124daeef that was originally bound here
E/ActivityThread( 3241): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 3241): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 3241): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 3241): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 3241): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3241): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3241): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3241): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 3241): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 3241): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 3241): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 3241): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 3241): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 3241): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2731)
E/ActivityThread( 3241): 	at android.app.ActivityThread.access$1800(ActivityThread.java:144)
E/ActivityThread( 3241): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1361)
E/ActivityThread( 3241): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3241): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3241): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 3241): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3241): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3241): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 3241): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
,E/ActivityThread( 3241): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@36644aa6 that was originally bound here
E/ActivityThread( 3241): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@36644aa6 that was originally bound here
E/ActivityThread( 3241): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 3241): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 3241): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 3241): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 3241): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3241): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 3241): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 3241): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 3241): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 3241): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 3241): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 3241): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 3241): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2758)
E/ActivityThread( 3241): 	at android.app.ActivityThread.access$1900(ActivityThread.java:144)
E/ActivityThread( 3241): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
E/ActivityThread( 3241): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3241): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3241): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 3241): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3241): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3241): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 3241): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
,W/ActivityManager(  756): Unbind failed: could not find connection for android.os.BinderProxy@10b76327
,I/ActivityManager(  756): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=3474 uid=10076 gids={50076, 9997} abi=armeabi-v7a
,I/ActivityManager(  756): Killing 2690:com.android.settings/1000 (adj 15): empty #17
,D/WifiService(  756): Client connection lost with reason: 4
,W/libprocessgroup(  756): failed to open /acct/uid_1000/pid_2690/cgroup.procs: No such file or directory
,D/TimeService( 3474): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1454973343021
D/        ( 3474): TimeServiceNative: User Time to be set is 1454973343021
D/QC-time-services( 3474): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 3474): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 3474): Lib:time_genoff_operation: pargs->ts_val = 1454973343021
D/QC-time-services(  197): Daemon: Connection accepted:time_genoff
,D/QC-time-services(  197): Daemon:Received base = 2, unit = 1, operation = 0,value = 1454973343021
D/QC-time-services(  197): Daemon:genoff_opr: Base = 2, val = 1454973343021, operation = 0
D/QC-time-services(  197): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS5/13/70 5:6:0
D/QC-time-services(  197): Daemon:Value read from RTC seconds = 14101560000
D/QC-time-services(  197): Daemon:new time 1454973343021 
D/QC-time-services(  197): Daemon: delta 1440871783021 genoff 1440871783021 
D/QC-time-services(  197): Daemon:genoff_persistent_update: Writing genoff = 1440871783021 to memory
D/QC-time-services(  197): Daemon:Opening File: /data/system/time/ats_2
D/QC-time-services(  197): Daemon:time_persistent_memory_opr:Genoff write operation 
D/QC-time-services( 3474): Lib:time_genoff_operation: Send to server  passed!!
,D/QC-time-services(  197): Updating the TOD offset
D/QC-time-services(  197): Daemon:genoff_persistent_update: Writing genoff = 1440871783021 to memory
D/QC-time-services(  197): Daemon:Opening File: /data/system/time/ats_1
D/QC-time-services(  197): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  197): Daemon:Update to modem bit set
,D/QC-time-services(  197): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  197): Daemon: Base = 2, Value being sent to MODEM = 1139008543021
,E/QC-time-services( 3474): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
I/ActivityManager(  756): Killing 2565:com.google.android.gm/u0a70 (adj 15): empty #17
,D/QC-time-services(  197): Daemon: Time-services: Waiting to acceptconnection
,D/QC-time-services(  197): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,W/libprocessgroup(  756): failed to open /acct/uid_10070/pid_2565/cgroup.procs: No such file or directory
,I/CheckinService( 1651): Checkin interval check for package: unspecified last checkin: 1454956998688 min interval config: 0 actual interval: 16344458
,I/ActivityManager(  756): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver: pid=3500 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
,I/GAv4    ( 3500): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3500):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3500):   adb logcat -s GAv4
,W/GAv4    ( 3500): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3500): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3500): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  756): Killing 2870:android.process.acore/u0a4 (adj 15): empty #17
,W/libprocessgroup(  756): failed to open /acct/uid_10004/pid_2870/cgroup.procs: No such file or directory
,I/jxcore-log( 3150): Test app app.js loaded
I/jxcore-log( 3150): 
,I/chromium( 3150): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3150): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3150): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3150): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3150): 	Bluetooth MAC address: 34:FC:EF:11:AE:67, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3150): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3150): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3150): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3150): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3150): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3150): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@398363 added. We now have 1 listener(s)
,I/jxcore-log( 3150): BLE advertisement is not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 3150): 
,I/jxcore-log( 3150): TAP version 13
I/jxcore-log( 3150): 
,I/jxcore-log( 3150): # setup
I/jxcore-log( 3150): 
,I/jxcore-log( 3150): # #generatePreambleAndBeacons empty keys to notify
I/jxcore-log( 3150): 
,I/jxcore-log( 3150): ok 1 should be equal
I/jxcore-log( 3150): 
I/jxcore-log( 3150): # teardown
I/jxcore-log( 3150): 
I/jxcore-log( 3150): # setup
I/jxcore-log( 3150): 
I/jxcore-log( 3150): # #generatePreambleAndBeacons multiple keys to notify
I/jxcore-log( 3150): 
,I/jxcore-log( 3150): ok 2 should be equal
I/jxcore-log( 3150): 
,I/jxcore-log( 3150): ok 3 should be equal
I/jxcore-log( 3150): 
,I/jxcore-log( 3150): ok 4 should be equal
I/jxcore-log( 3150): 
,I/jxcore-log( 3150): ok 5 should be equal
I/jxcore-log( 3150): 
,I/jxcore-log( 3150): # teardown
I/jxcore-log( 3150): 
,I/jxcore-log( 3150): # setup
I/jxcore-log( 3150): 
,I/jxcore-log( 3150): # #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble
I/jxcore-log( 3150): 
,I/jxcore-log( 3150): ok 6 should throw
I/jxcore-log( 3150): 
,I/jxcore-log( 3150): # teardown
I/jxcore-log( 3150): 
,I/jxcore-log( 3150): # setup
I/jxcore-log( 3150): 
,I/jxcore-log( 3150): # #parseBeacons invalid expiration in beaconStreamWithPreAmble
I/jxcore-log( 3150): 
,I/jxcore-log( 3150): ok 7 should throw
I/jxcore-log( 3150): 
,I/jxcore-log( 3150): # teardown
I/jxcore-log( 3150): 
,I/jxcore-log( 3150): # setup
I/jxcore-log( 3150): 
,I/jxcore-log( 3150): # #parseBeacons no beacons returns null
I/jxcore-log( 3150): 
,I/jxcore-log( 3150): ok 8 should be equal
I/jxcore-log( 3150): 
I/jxcore-log( 3150): # teardown
I/jxcore-log( 3150): 
I/jxcore-log( 3150): # setup
I/jxcore-log( 3150): 
I/jxcore-log( 3150): # #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble
I/jxcore-log( 3150): 
,I/jxcore-log( 3150): ok 9 should throw
I/jxcore-log( 3150): 
,I/jxcore-log( 3150): # teardown
I/jxcore-log( 3150): 
,I/jxcore-log( 3150): # setup
I/jxcore-log( 3150): 
,I/jxcore-log( 3150): # #parseBeacons addressBookCallback fails decrypt
I/jxcore-log( 3150): 
,I/jxcore-log( 3150): ok 10 should be equal
I/jxcore-log( 3150): 
,I/jxcore-log( 3150): # teardown
I/jxcore-log( 3150): 
,I/jxcore-log( 3150): # setup
I/jxcore-log( 3150): 
I/jxcore-log( 3150): # #parseBeacons addressBookCallback returns no matches
I/jxcore-log( 3150): 
,I/jxcore-log( 3150): ok 11 should be equal
I/jxcore-log( 3150): 
,I/jxcore-log( 3150): ok 12 should be equal
I/jxcore-log( 3150): 
I/jxcore-log( 3150): # teardown
I/jxcore-log( 3150): 
I/jxcore-log( 3150): # setup
I/jxcore-log( 3150): 
I/jxcore-log( 3150): # #parseBeacons addressBookCallback returns public key
I/jxcore-log( 3150): 
,I/jxcore-log( 3150): ok 13 should be equal
I/jxcore-log( 3150): 
,I/jxcore-log( 3150): ok 14 (unnamed assert)
I/jxcore-log( 3150): 
I/jxcore-log( 3150): # teardown
I/jxcore-log( 3150): 
I/jxcore-log( 3150): # setup
I/jxcore-log( 3150): 
I/jxcore-log( 3150): # #parseBeacons with beacons both for and not for the user
I/jxcore-log( 3150): 
,I/jxcore-log( 3150): ok 15 (unnamed assert)
I/jxcore-log( 3150): 
I/jxcore-log( 3150): # teardown
I/jxcore-log( 3150): 
,W/ProcessCpuTracker(  756): Skipping unknown process pid 3527
,I/art     (  756): Explicit concurrent mark sweep GC freed 36605(1724KB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 27MB/41MB, paused 1.119ms total 57.088ms
,D/Finsky  ( 2620): [255] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2620): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,V/GLSActivity( 1616): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1616): Vacuum at: now=1454973367972 tag=VacuumService
,I/PhenotypeConfigurator( 1616): Scheduling Phenotype for one-off execution 8495 seconds from now (1454973368354)
,D/GetConfigurationSnapshotOperation( 1616): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1616): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1616): Using platform SSLCertificateSocketFactory
,I/Keyboard.Facilitator.LanguageModelFlusher( 1101): run()
I/Keyboard.Facilitator( 1101): flushDynamicLanguageModels()
,I/ConfigService( 1616): onCreate
,I/ConfigService( 1616): onDestroy
,I/ClearcutLoggerApiImpl( 1616): disconnect managed GoogleApiClient
,I/EventLogService( 1651): Aggregate from 1454971609145 (log), 1454971609145 (data)
,I/jxcore-log( 3150): --= Surplus to requirements =--
I/jxcore-log( 3150): 
I/jxcore-log( 3150): ****TEST TOOK:  ms ****
I/jxcore-log( 3150): 
I/jxcore-log( 3150): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3150): 
,D/AndroidRuntime( 3630): 
D/AndroidRuntime( 3630): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 3630): CheckJNI is OFF
,D/AndroidRuntime( 3630): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  756): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
I/ActivityManager(  756): Killing 3150:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
,I/WindowState(  756): WIN DEATH: Window{23f6e760 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  756): Client connection lost with reason: 4
,W/PackageSettings(  756): Skipping PackageSetting{28b4201a com.example.hello/10278} due to missing metadata
,I/ActivityManager(  756):   Force finishing activity ActivityRecord{164d952c u0 com.test.thalitest/.MainActivity t216}
,W/ActivityManager(  756): Spurious death for ProcessRecord{38a485d2 3150:com.test.thalitest/u0a270}, curProc for 3150: null
,I/ActivityManager(  756): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
,I/art     ( 1306): Explicit concurrent mark sweep GC freed 10201(699KB) AllocSpace objects, 1(39KB) LOS objects, 24% free, 19MB/25MB, paused 314us total 20.883ms
,I/art     ( 1261): Explicit concurrent mark sweep GC freed 3952(294KB) AllocSpace objects, 1(126KB) LOS objects, 38% free, 25MB/41MB, paused 743us total 19.678ms
,I/Keyboard.Facilitator( 1101): resetDictionaries() : en_US
W/GeofencerStateMachine( 1616): Ignoring removeGeofence because network location is disabled.
,I/InputReader(  756): Reconfiguring input devices.  changes=0x00000010
,I/Keyboard.Facilitator.DecoderInitializer( 1101): run()
,I/Decoder ( 1101): createOrResetDecoder
,I/ActivityManager(  756): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=3659 uid=10004 gids={50004, 9997} abi=armeabi-v7a
,I/art     ( 1651): Explicit concurrent mark sweep GC freed 6118(362KB) AllocSpace objects, 3(48KB) LOS objects, 24% free, 22MB/30MB, paused 475us total 77.473ms
,I/ConfigService( 1616): onCreate
,D/NetworkChangeNotifierAutoDetect(  939): Network connectivity changed, type is: 2
,I/art     (  756): Explicit concurrent mark sweep GC freed 21751(1218KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 27MB/41MB, paused 930us total 86.636ms
,I/art     (  756): WaitForGcToComplete blocked for 27.825ms for cause Explicit
,I/LibraryLoader( 1484): Loading chrome directly from within /data/app/com.android.chrome-1/base.apk
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1101): run()
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1101): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1101): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1101): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1101): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1101): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1101): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1101): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1101): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1101): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1101): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1101): run()
I/StatsUtilsManager( 1101): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1101): shouldRecordStats() = Too Soon
,D/BackupManagerService(  756): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  756): Receieved: android.intent.action.PACKAGE_REMOVED
,D/TaskPersister(  756): removeObsoleteFile: deleting file=216_task.xml
,W/InputMethodManagerService(  756): Got RemoteException sending setActive(false) notification to pid 3150 uid 10270
,I/Keyboard.Facilitator( 1101): onFinishInput()
,I/art     (  756): Explicit concurrent mark sweep GC freed 5285(318KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 1.210ms total 131.162ms
,I/LibraryLoader( 1484): Time to load native libraries: 128 ms (timestamps 1206-1334)
,I/LibraryLoader( 1484): Expected native library version number "44.0.2403.133",actual native library version number "44.0.2403.133"
,I/chromium( 1484): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,W/art     ( 1484): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 1484): Attempt to remove local handle scope entry from IRT, ignoring
,D/VoicemailCleanupService( 3659): Cleaning up data for package: com.test.thalitest
,I/UpdateIcingCorporaServi( 1306): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,W/Launcher( 1261): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@b47e127 new=com.google.android.velvet.VelvetApplication@b47e127
,I/ActivityManager(  756): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3703 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,I/Launcher( 1261): Deferring update until onResume
,W/ResourcesManager( 1261): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ContactLocale( 3659): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  756): Killing 1428:com.google.android.partnersetup/u0a13 (adj 15): empty #17
,D/AndroidRuntime( 3630): Shutting down VM
,W/ResourcesManager( 1261): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ContextImpl( 3703): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
,I/Launcher( 1261): Deferring update until onResume
,W/libprocessgroup(  756): failed to open /acct/uid_10013/pid_1428/cgroup.procs: No such file or directory
,D/PackageBroadcastService( 1651): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,D/AccountUtils( 1651): Clearing selected account for com.test.thalitest
,D/ChimeraCfgMgr( 1651): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1651): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1651): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1651): Module APK com.google.android.play.games already loaded
,I/LocationSettingsChecker( 1651): Removing dialog suppression flag for package com.test.thalitest
,I/ActivityManager(  756): Killing 3060:com.google.android.apps.docs/u0a40 (adj 15): empty #17
E/NetworkScheduler.SchedulerReceiver( 1616): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1616): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,I/UpdateIcingCorporaServi( 1306): UpdateCorporaTask done [took 174 ms] updated apps [took 174 ms] 
,D/gH_CompatibleDatabase( 1651): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1651): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,D/gH_MetricsDatabase( 1651): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1651): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/gH_CompatibleDatabase( 1651): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1651): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/gH_CompatibleDatabase( 1651): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,W/BroadcastQueue(  756): Exception when sending broadcast to ComponentInfo{com.google.android.apps.docs/com.google.android.apps.docs.receivers.AppPackageAddRemoveReceiver}
W/BroadcastQueue(  756): android.os.DeadObjectException
W/BroadcastQueue(  756): 	at android.os.BinderProxy.transactNative(Native Method)
W/BroadcastQueue(  756): 	at android.os.BinderProxy.transact(Binder.java:496)
W/BroadcastQueue(  756): 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:857)
W/BroadcastQueue(  756): 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:245)
W/BroadcastQueue(  756): 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:898)
W/BroadcastQueue(  756): 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:16008)
W/BroadcastQueue(  756): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:470)
W/BroadcastQueue(  756): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2407)
W/BroadcastQueue(  756): 	at android.os.Binder.execTransact(Binder.java:446)
W/libprocessgroup(  756): failed to open /acct/uid_10040/pid_3060/cgroup.procs: No such file or directory
,D/gH_CompatibleDatabase( 1651): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1651): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 1651): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1651): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1651): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1651): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,I/ActivityManager(  756): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=3731 uid=10040 gids={50040, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,W/ActivityManager(  756): Spurious death for ProcessRecord{13658369 3731:com.google.android.apps.docs/u0a40}, curProc for 3060: null
,I/GMPM-SVC( 1651): App measurement is starting up, version: 8489
,I/GMPM-SVC( 1651): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
,W/BaseAppContext( 1651): Using Auth Proxy for data requests.
,W/BaseAppContext( 1651): Using Auth Proxy for data requests.
,I/Icing   ( 1651): doRemovePackageData com.test.thalitest

```
