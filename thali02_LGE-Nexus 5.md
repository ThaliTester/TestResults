#### Test 57924002a578a80_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
I/GAv4    ( 3126): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3126):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3126):   adb logcat -s GAv4
W/GAv4    ( 3126): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3126): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3126): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 3126): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
E/SQLiteLog( 3126): (283) recovered 24 frames from WAL file /data/data/com.google.android.apps.docs/databases/DocList.db-wal
D/Finsky  ( 2672): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
--------- beginning of system
I/ActivityManager(  735): Killing 2369:com.lge.SprintHiddenMenu/1000 (adj 15): empty #17
W/ResourcesManager( 3126): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3126): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/libprocessgroup(  735): failed to open /acct/uid_1000/pid_2369/cgroup.procs: No such file or directory
V/JNIHelp ( 3126): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/System  ( 3126): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3126): Installed default security provider GmsCore_OpenSSL
V/GLSActivity( 1612): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Icing   ( 1635): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
I/Icing   ( 1635): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
I/Icing   ( 1635): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1635): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
,D/AndroidRuntime( 3184): 
D/AndroidRuntime( 3184): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3184): CheckJNI is OFF
D/AndroidRuntime( 3184): Calling main entry com.android.commands.am.Am
I/ActivityManager(  735): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  735): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3205 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3184): Shutting down VM
I/art     (  196): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 211us total 9.104ms
I/art     (  196): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 189us total 8.235ms
I/art     (  196): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 189us total 9.640ms
I/ActivityManager(  735): Killing 2464:com.google.android.youtube/u0a80 (adj 15): empty #17
V/ActivityManager(  735): Display changed displayId=0
W/libprocessgroup(  735): failed to open /acct/uid_10080/pid_2464/cgroup.procs: No such file or directory
I/WebViewFactory( 3205): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3205): Time to load native libraries: 1 ms (timestamps 7448-7449)
I/LibraryLoader( 3205): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3205): Binding Chromium to main looper Looper (main, tid 1) {d2d8a91}
I/LibraryLoader( 3205): Expected native library version number "",actual native library version number ""
I/chromium( 3205): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3205): Initializing chromium process, singleProcess=true
,W/art     ( 3205): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3205): ApplicationContext is null in ApplicationStatus
,W/chromium( 3205): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3205): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3205): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3205): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  735): Message: 20
D/BluetoothManagerService(  735): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1f0895db:true
,W/art     ( 3205): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3205): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3205): CordovaWebView is running on device made by: LGE
,W/art     ( 3205): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3205): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3205): Render dirty regions requested: true
,D/Atlas   ( 3205): Validating map...
,W/chromium( 3205): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3205): Initialized EGL, version 1.4
D/OpenGLRenderer( 3205): Enabling debug mode 0
,I/Keyboard.Facilitator( 1090): onFinishInput()
,W/IInputConnectionWrapper( 3205): showStatusIcon on inactive InputConnection
,I/ActivityManager(  735): Displayed com.test.thalitest/.MainActivity: +413ms (total +46s472ms)
,W/BindingManager( 3205): Cannot call determinedVisibility() - never saw a connection for the pid: 3205
,D/JsMessageQueue( 3205): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3205): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257332480
,I/chromium( 3205): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/ActivityManager(  735): Killing 2091:com.google.android.deskclock/u0a38 (adj 15): empty #17
,W/libprocessgroup(  735): failed to open /acct/uid_10038/pid_2091/cgroup.procs: No such file or directory
,W/jxcore-log( 3205): Initializing JXcore engine
W/jxcore-log( 3205): JXcore engine is ready
,W/Thread-297( 3254): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[8064]" dev="sockfs" ino=8064 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-297( 3254): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/Thread-297( 3254): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[8142]" dev="sockfs" ino=8142 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-297( 3254): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[18305]" dev="sockfs" ino=18305 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3205): Starting JXcore engine
,W/jxcore-log( 3205): Platform android
W/jxcore-log( 3205): 
W/jxcore-log( 3205): Process ARCH arm
W/jxcore-log( 3205): 
,I/jxcore-log( 3205): JXcore Cordova bridge is ready!
I/jxcore-log( 3205): 
,W/jxcore-log( 3205): JXcore engine is started
,I/jxcore-log( 3205): Toggling radios to true
I/jxcore-log( 3205): 
,D/BluetoothAdapter( 3205): enable(): BT is already enabled..!
,D/WifiService(  735): New client listening to asynchronous messages
,D/WifiService(  735): setWifiEnabled: true pid=3205, uid=10270
E/WifiService(  735): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3205): Radios toggled
I/jxcore-log( 3205): 
,I/jxcore-log( 3205): My device name is: LGE-Nexus 5
I/jxcore-log( 3205): 
,I/wpa_supplicant(  990): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  735): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  735): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/native  (  735): do suspend true
,D/CommandListener(  181): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1612): Read error: ssl=0x9dc6c000: I/O error during system call, Connection timed out
,V/NativeCrypto( 1612): SSL shutdown failed: ssl=0x9dc6c000: I/O error during system call, Broken pipe
,D/ConnectivityService(  735): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): ValidatedState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): DefaultState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,D/ConnectivityService(  735): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,D/ConnectivityService(  735): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,E/WifiConfigStore(  735): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiStateMachine(  735): Start Disconnecting Watchdog 1
I/wpa_supplicant(  990): wlan0: CTRL-EVENT-SCAN-STARTED 
,E/native  (  735): do suspend true
,D/CommandListener(  181): Clearing all IP addresses on wlan0
D/ConnectivityService(  735): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityManager.CallbackHandler(  901): CM callback handler got msg 524292
D/ConnectivityManager.CallbackHandler( 1635): CM callback handler got msg 524292
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): Disconnected - quitting
,D/Nat464Xlat(  735): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  735): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  735): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  735): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  735): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory( 1248): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/ConnectivityService(  735): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,D/WifiNetworkAgent(  735): NetworkAgent: NetworkAgent channel lost
,D/Finsky  ( 2672): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/GLSActivity( 1612): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1612): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1612): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 2672): [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,V/GLSActivity( 1612): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1612): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  735): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=3288 uid=10008 gids={50008, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/ResourcesManager( 3288): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3288): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/Finsky  ( 2672): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,I/MultiDex( 3288): VM with version 2.1.0 has multidex support
I/MultiDex( 3288): install
I/MultiDex( 3288): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 3288): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 3288): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 3288): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@364538eb: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3288): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1612): callingUid 10008, callindPid: 1612
,E/MDM     ( 1612): [226] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/ChimeraCfgMgr( 3288): Reading stored module config
,D/ChimeraCfgMgr( 3288): Loading module com.google.android.gms.car from APK com.google.android.gms
,D/LocationInitializer( 1635): Restart initialization of location
D/AuthorizationBluetoothService( 1612): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1612): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1612): No location to return for getLastLocation()
W/FusedLocationProvider( 1612): location=null
,I/wpa_supplicant(  990): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,D/NativeLibraryUtils( 3288): Install completed successfully. count=14 extracted=0
,D/CAR.SERVICE( 3288): Connecting to CarCallService...
,I/wpa_supplicant(  990): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/art     ( 3288): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 3288): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/wpa_supplicant(  990): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant(  990): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/CAR.SERVICE( 3288): com.google.android.projection.gearhead isn't installed.
,D/ConnectivityService(  735): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore(  735): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  735): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  735): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/CAR.TEL.Service( 3288): Creating a new CarCallService.
,D/CommandListener(  181): Setting iface cfg
,E/WifiStateMachine(  735): Start Dhcp Watchdog 2
D/CAR.TEL.PhoneAdapter( 3288): Creating a new PhoneAdapter instance
W/ActivityManager(  735): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter( 3288): setListener: com.google.android.gms.car.dn@2f81f0b6
,W/ActivityManager(  735): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter( 3288): Returning an existing PhoneAdapter instance.
,D/CAR.TEL.Service( 3288): Starting CarCallService with initial phone null
,D/CAR.SERVICE( 3288): Package validated; name: com.android.vending
,V/Finsky  ( 2672): [1] GearheadStateMonitor.access$100: mIsProjecting:false
,E/native  (  735): do suspend false
,E/WifiStateMachine(  735): scanCount==0 - aborting
,V/GLSActivity( 1612): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 2672): [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,D/Finsky  ( 2672): [1] DailyHygiene.access$600: Logging device features
,D/Finsky  ( 2672): [1] DailyHygiene.reschedule: Scheduling new run in 256 minutes (failures=4)
,I/art     (  735): Explicit concurrent mark sweep GC freed 34770(1688KB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 27MB/41MB, paused 1.286ms total 76.889ms
,D/DeviceConnectionService( 1612): client connected with version: 8296000
,D/Finsky  ( 2672): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/Finsky  ( 2672): [266] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 2672): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,V/GLSActivity( 1612): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/dhcpcd  ( 3335): version 5.5.6 starting
,E/dhcpcd  ( 3335): get_duid: Read-only file system
,I/dhcpcd  ( 3335): wlan0: rebinding lease of 192.168.1.114
,I/ActivityManager(  735): Killing 2642:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
,W/libprocessgroup(  735): failed to open /acct/uid_10069/pid_2642/cgroup.procs: No such file or directory
,I/dhcpcd  ( 3335): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3335): wlan0: leased 192.168.1.114 for 86400 seconds
,D/ConnectivityService(  735): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  735): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  735): MasterInitialState.processMessage what=3
,D/Tethering(  735): MasterInitialState.processMessage what=3
,V/MusicLeanback( 2792): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1635): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1635): onCreate
,D/SystemUpdateService( 1635): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1635): active receiver: enabled
,I/iu.Environment( 1635): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/SystemUpdateService( 1635): showing system update notification
,I/iu.UploadsManager( 1635): num queued entries: 0
I/iu.UploadsManager( 1635): num updated entries: 0
I/iu.SyncManager( 1635): NEXT; no task
,I/Babel   ( 1949): connection state changed from CONNECTED to DISCONNECTED
,E/native  (  735): do suspend true
,I/ActivityManager(  735): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3382 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/GpsLocationProvider(  735): No APN found to select.
,D/ConnectivityService(  735): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  735): Adding iface wlan0 to network 101
,E/WifiStateMachine(  735): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  735): Unexpected mtu value: 0, wlan0
,D/ConnectivityService(  735): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/ConnectivityService(  735): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  735): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  735): Setting Dns servers for network 101 to [/192.168.1.1]
,D/Nat464Xlat(  735): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  735): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  735): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  735): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  735):    accepting network in place of null
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/CSLegacyTypeTracker(  735): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  735): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  735): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::5255:27ff:fef0:fd0b/64,192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/ConnectivityService(  735): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  901): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1635): CM callback handler got msg 524290
,E/GpsLocationProvider(  735): No APN found to select.
,I/ValidateNoPeople(  735): skipping global notification
,V/SystemUpdateService( 1635): retry (wakeup: false) in 3599911 ms
,D/SystemUpdateService( 1635): onDestroy
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 03 Feb 2016 00:41:43 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454460103193], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454460103175]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): Validated
D/ConnectivityService(  735): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  735): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  735): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  735): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  735): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/TelephonyNetworkFactory( 1248): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler(  901): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1635): CM callback handler got msg 524290
,I/GAv4    ( 3382): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3382):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3382):   adb logcat -s GAv4
,W/GAv4    ( 3382): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3382): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3382): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 3382): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3382): Time to load native libraries: 1 ms (timestamps 3156-3157)
I/LibraryLoader( 3382): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3382): Binding Chromium to main looper Looper (main, tid 1) {130a32db}
I/LibraryLoader( 3382): Expected native library version number "",actual native library version number ""
I/chromium( 3382): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3382): Initializing chromium process, singleProcess=true
W/art     ( 3382): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3382): ApplicationContext is null in ApplicationStatus
,W/chromium( 3382): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3382): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3382): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3382): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,I/NSApplication( 3382): Starting up...
,W/AudioManagerAndroid( 3382): Requires BLUETOOTH permission
,I/ActivityManager(  735): Killing 2569:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,W/libprocessgroup(  735): failed to open /acct/uid_10045/pid_2569/cgroup.procs: No such file or directory
,V/MusicLeanback( 2792): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1635): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1635): onCreate
,D/SystemUpdateService( 1635): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/iu.Environment( 1635): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/SystemUpdateService( 1635): active receiver: enabled
,I/iu.UploadsManager( 1635): num queued entries: 0
I/iu.UploadsManager( 1635): num updated entries: 0
I/iu.SyncManager( 1635): NEXT; no task
I/SystemUpdateService( 1635): showing system update notification
,I/ValidateNoPeople(  735): skipping global notification
V/SystemUpdateService( 1635): retry (wakeup: false) in 3599965 ms
D/SystemUpdateService( 1635): onDestroy
,I/Babel   ( 1949): connection state changed from DISCONNECTED to CONNECTED
,D/ConnectivityService(  735): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/jxcore-log( 3205): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 3205): 
,I/jxcore-log( 3205): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 3205): 
,I/jxcore-log( 3205): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 3205): 
I/jxcore-log( 3205): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
I/jxcore-log( 3205): 
,I/jxcore-log( 3205): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 3205): 
,D/ConnectivityService(  735): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  735): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2792): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2792): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1635): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1635): onCreate
,D/SystemUpdateService( 1635): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1635): active receiver: enabled
,E/GpsLocationProvider(  735): No APN found to select.
,I/SystemUpdateService( 1635): showing system update notification
,I/ValidateNoPeople(  735): skipping global notification
,V/SystemUpdateService( 1635): retry (wakeup: false) in 3599969 ms
,D/SystemUpdateService( 1635): onDestroy
,D/CAR.SERVICE( 3288): mConnectedToCar = false, abort
,E/ActivityThread( 3288): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@eb743de that was originally bound here
E/ActivityThread( 3288): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@eb743de that was originally bound here
E/ActivityThread( 3288): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 3288): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 3288): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 3288): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 3288): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3288): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3288): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3288): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 3288): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 3288): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 3288): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 3288): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 3288): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 3288): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2731)
E/ActivityThread( 3288): 	at android.app.ActivityThread.access$1800(ActivityThread.java:144)
E/ActivityThread( 3288): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1361)
E/ActivityThread( 3288): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3288): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3288): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 3288): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3288): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3288): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 3288): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
,E/ActivityThread( 3288): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@2a38b051 that was originally bound here
E/ActivityThread( 3288): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@2a38b051 that was originally bound here
E/ActivityThread( 3288): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 3288): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 3288): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 3288): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 3288): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3288): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 3288): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 3288): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 3288): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 3288): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 3288): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 3288): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 3288): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2758)
E/ActivityThread( 3288): 	at android.app.ActivityThread.access$1900(ActivityThread.java:144)
E/ActivityThread( 3288): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
E/ActivityThread( 3288): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3288): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3288): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 3288): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3288): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3288): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 3288): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
,W/ActivityManager(  735): Unbind failed: could not find connection for android.os.BinderProxy@11711e70
,I/jxcore-log( 3205): Test app app.js loaded
I/jxcore-log( 3205): 
,I/chromium( 3205): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3205): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3205): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3205): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3205): 	Bluetooth MAC address: 34:FC:EF:11:AE:67, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3205): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3205): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3205): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3205): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3205): 	Scan mode: 1
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3205): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cd9f8d0 added. We now have 1 listener(s)
,I/jxcore-log( 3205): BLE advertisement is not supported: Bluetooth LE advertising is not supported,
I/jxcore-log( 3205): 
,D/Finsky  ( 2672): [255] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2672): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,V/GLSActivity( 1612): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1612): Vacuum at: now=1454460132218 tag=VacuumService
,I/Keyboard.Facilitator.LanguageModelFlusher( 1090): run()
I/Keyboard.Facilitator( 1090): flushDynamicLanguageModels()
,I/ClearcutLoggerApiImpl( 1612): disconnect managed GoogleApiClient
,I/ActivityManager(  735): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=3566 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
,I/GAv4    ( 3566): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3566):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3566):   adb logcat -s GAv4
,W/GAv4    ( 3566): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3566): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3566): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  735): Killing 2764:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,W/libprocessgroup(  735): failed to open /acct/uid_10003/pid_2764/cgroup.procs: No such file or directory
,V/GLSActivity( 1612): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1612): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1612): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  735): Killing 2743:com.android.settings/1000 (adj 15): empty #17
,D/WifiService(  735): Client connection lost with reason: 4
,W/libprocessgroup(  735): failed to open /acct/uid_1000/pid_2743/cgroup.procs: No such file or directory
,W/bt-smp  ( 2119): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 2119): Plain text(LSB ~ MSB) = 59 cd 72 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2119): Encrypted text(LSB ~ MSB) = 62 58 c6 70 a9 0a ec 4c 61 0b 1a 95 55 20 92 21 
,W/bt-btm  ( 2119): Stopping oneshot timer
,I/PhenotypeConfigurator( 1612): Scheduling Phenotype for one-off execution 2225 seconds from now (1454461004439)
,D/GetConfigurationSnapshotOperation( 1612): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1612): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1612): Using platform SSLCertificateSocketFactory
,V/GLSActivity( 1612): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1612): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/UsageStatsService(  735): User[0] Flushing usage stats to disk
,TIME-OUT KILL (timeout was 1200000ms)
```
